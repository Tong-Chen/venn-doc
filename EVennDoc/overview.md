--- 
title: "EVenn: Easy to create repeatable, editable, and statistically measurable Venn diagrams online"
author: 
- "Chen Tong"
- "http://www.ehbio.com/test/venn"
- "chent@nrc.ac.cn"
date: "2021-04-02"
documentclass: article
site: bookdown::bookdown_site
---










<!--chapter:end:index.Rmd-->

# Overview

## All-in-one venn diagram platform

Evenn was designed as a web-application featured with 7 different modules, including interactive venn diagram, high quality euler diagram, flower plot, upset view plot, network venn, statistical significance computation for intersections and venn calculator for generating items and counts of all types of intersections for data with any number of sets. Each function was split into separate tabs for fast access and with one demo data for quick starting. Users are allowed to set font family, font size, area colors, area shapes, line types, image width, image height, set order for one or several modules to generate publication-quality outputs. Each module also has some special parameters for flexible usages.

## Implementation

EVenn is implemented as a web application using Javascript and HTML for frontend development. The used core Javascript libraries include Vue.js (https://vuejs.org/), jvenn.js (http://jvenn.toulouse.inra.fr/app/index.html) and vis.js (https://visjs.org). High-level Python web framework Django (https://www.djangoproject.com/) is used for backend data preprocess and data analysis. Euler diagram is generated based on R package Eulerr. Upsetview plot is generated based on R package UpSetR. Statistical significance of set similarity is computed using in house python programs (random sample test) and R scripts based on R package jaccard (jaccard similarity test). Item lists and item counts for each intersection region are computed using in house python scripts.

## The unified input format of data matrix

Different tools read in different types of data, which forces users to do tedious work of data format transferring. It gives more burden as datasets increasing, especially for scientists lack of programming skills. Most venn tools require users to supply each set separately or irregular data matrix (each column has different number of rows). Both formats are not suitable for people saving or program generating. 
Here we unified Input data in one simple format for all tools. It is a two-column regular matrix with the first column containing items by rows and the second column specifies the set each item belongs to, so we named it as “two-column mode” (Fig 1). If one item belongs to several sets, it may appear in several rows. The order of rows does not matter. The order of columns matters at least for interactive venn diagrams. This type of data could be easily generated using Excel or other text-editors with just ‘copy-paste’ operations. It could also be generated program-ably in any analysis pipeline with addition or changing only few codes. Another advantage of this specified format is that it is both human and machine readable, and could be saved for repeatable usages. Based on the unified input format, it is feasible to generate and compare different visualization ways during the data exploring stage and result showing stage. Leaving out of the trouble of file format changing for separate tools, which is essential and not so trivial for researchers who could not program.  

Besides, the classical input formats for each tool were also preserved for meeting various requirements. For example, one could only input the number of each intersections instead of related items to draw interactive venn diagrams and euler diagrams. This is useful for counting data such as cell immunofluorescence experiments how many cells are stained as red, how many cells are stained as green, how many cells have merged color of blue. Also, one could paste items for each set separately and naming each set on the fly. This requires several times of copy-pasting and the data could not be easily saved for future usages.   

## Interactive venn diagrams

This module is implemented mainly based on the jvenn JavaScript library with some extensions. The interactive attribute of this module supports to get items of each intersection part by clicking numbers in the picture. This interactivity makes venn diagrams not only pictures showing the relationships among sets, but also analysis tools that would facilitate identifying candidate items like genes or OTUs. A bar plot showing number of all sets would be shown by default to check their homogeneity. Besides, it has several advantages like switching between standard venn layout and Edwards-Venn layout, switch on and off different lists. The result picture could be exported in scalable vector graphics (SVG) format which could be converted to high-resolution images or combined with other pictures for publication usages. 

Four types of input ways are supported for more feasible usages, directly pasting items of each set (Input items), typing in counts of each intersections (Input numbers), uploading the data file (Upload file) and pasting all data together using two-column formats (Two-column mode). For Upload file and Two-column mode, users are allowed to select which set to be used and their appearance order, allowing inputting data with more than 6 sets.   
  
Another useful improvement is that one can reordering each set to get better visualization by simple dragging of input text-areas. This function is especially useful when one wants to delete one or several sets, no need of re-input for already pasted sets.   

## Venn diagram like plots: Euler diagram plot, Upset view plot, Flower plot

As the increasing of data complexity, classical venn diagrams may not always meet the best requirement for data visualization. There are several other types of plots to display set relationships.  
Euler diagram plots do not display empty intersection regions, giving more concrete and accuracy visualization. Theoretically, it could have better visualization effects for more sets than venn diagrams. And it could clearly show the fully-containing-relationships among 2 or several sets. In Evenn, Euler diagram plot function generate proportional euler diagrams, in which the sizes of sets and intersection areas are positively correlated with number of items in them. This gives more perceptual intuition than the numbers in venn diagrams. Euler diagram function accepts two types of input formats (Counts and Items (in two-column mode)). Column order does not matter in this tool since there is a radio combo to specify which column contains items information and which column contains sets information. Several other visual styles like number types, plot shapes, font size, line type and colors could be customized as required. The result picture could be downloaded in PDF format for publication usages.

Upset view is designed as a novel visualization technique for the quantitative analysis of sets and their intersections. It composed three parts, a horizontal bar-plot showing total number of items of each set, a dot-plot indicating all types of intersections among sets, a vertical bar-plot representing number of items of corresponding intersections. The bars are normally orders by item counts, giving more direct decision of the largest sets and intersections. Intersections which are empty or containing few items could be selectively hided to save space for visualizing much more sets. 

For integrated data with more than 10 or 20 sets, neither venn diagram, euler diagram or upset view (when most intersections are not empty) would give reasonable displaying. Flower plot which shows only common items shared by all sets and special items for each set provides another choice. This is a trade-off between ease-interpretation and information loss. Flower plot would be more useful when displaying commonality or specificity, while other intersection combinations are not so important.  

 
## Venn network exploring intersections


Normally venn diagrams and their variants only show the counts or percentages of all intersections instead of items. We present Venn network, which could show both items and their belonging sets in an interactive network diagram. Each set would be treated as one parent node, each item would be connected to its parent node via edges. Items connected with all sets are shared among them. We present a button called “Preferred layout” would usually give the optimized layout to clearly display the intersection relationships of sets after 1-2 minutes computation. Items of each intersection were clustered together and got away from other intersections. Targeting items could be searched and highlighted with connected sets to show its belongings. Several hotkeys and the detail toolbar were added for modifying layouts, nodes and edges attributes to generate publication-quality pictures to be downloaded in SVG format. 

## Tools for estimating sets similarity and calculating sets intersections

Visualization would give qualitative but not quantitative estimation of sets similarity. However it is normally needed to check the significance level of sets similarity to get more conclusive interpretations. We implied two commonly used methods: random sample test and Jaccard similarity test. Random sample test using random sampling process for 1000 times to check if given overlaps are random or not. Jaccard similarity test using the Jaccard similarity coefficient -- the ratio of intersection to union for statistical testing of similarity between binary data. 

There are also scenes that we want to quickly select candidate items like genes or OTUs for downstream analysis before generating plots. Venn calculator is designed to output items for intersections for any number of sets in table format for further exploring. Besides, the output could be easily given to Euler diagram to generate plots without computing again. 

<!--chapter:end:01.Introduction.Rmd-->

