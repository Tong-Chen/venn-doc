--- 
title: "EVenn: Easy to create repeatable, editable, and statistically measurable Venn diagrams online"
author: 
- "Chen Tong"
- "http://www.ehbio.com/test/venn"
- "chent@nrc.ac.cn"
date: "2024-04-13"
documentclass: article
site: bookdown::bookdown_site
---





# Overview of EVenn

[EVenn](http://www.ehbio.com/test/venn/#/) is constructed to generate Venn diagrams (classical and Edwards layout), Euler diagrams (proportional), UpSet, Flower plot and Venn network. Specially, we developed one unified data matrix as inputs for all tools. This type of input data could be easily prepared using Excel or other text-editors or simple programs. Once uploaded, the data file could be easily loaded to each tool to generate various displaying. This makes EVenn a more suitable tool for exploratory analysis and to choose the best way to explain and visualize data. In order to compute the significance of the overlap between two groups of elements which could be genes or OTUs, random sample test and Jaccard similarity test were applied. The tool Venn calculator could generate the counts and detailed elements for each non-empty intersection for datasets with any number of groups. The results could be used for downstream selection and also could be used as input for data visualization using EVenn. Evenn is available at http://www.ehbio.com/test/venn/. We also recorded a video showing how to generate 5 types of Venn diagrams in less than 3 minutes (which could be viewed in <http://www.ehbio.com/test/venn/video/EVenn7.webm> or in YouTube with link <https://youtu.be/sCEiaZpnL8Q>). 

EVenn is published in `iMeta`. Please cite **Visualizing set relationships: EVenn's comprehensive approach to Venn diagrams**  Mei Yang, Tong Chen, Yong-Xin Liu, Luqi Huang 11 April 2024. [https://doi.org/10.1002/imt2.184](https://doi.org/10.1002/imt2.184). 

<div class="figure" style="text-align: center">
<img src="image/imt2184-gra-0001-m.jpg" alt="1.	全面的韦恩功能：EVenn提供了一个统一的平台，包含多种韦恩图工具，从交互式图到网络图，满足了代谢组学、基因组学、转录组学和蛋白质组学等多组学数据分析的复杂需求；2.	高效的数据探索：EVenn的数据中心支持标准化的数据格式，简化数据上传和分析过程。本文通过代表性结果和详细案例展示其实用性；3.	用户友好的界面：EVenn拥有易用的界面，简化了各种韦恩图、欧拉图、UpSet图的生成过程。EVenn是研究人员解读多组学数据的好用工具。" width="100%" />
<p class="caption">(\#fig:unnamed-chunk-1)1.	全面的韦恩功能：EVenn提供了一个统一的平台，包含多种韦恩图工具，从交互式图到网络图，满足了代谢组学、基因组学、转录组学和蛋白质组学等多组学数据分析的复杂需求；2.	高效的数据探索：EVenn的数据中心支持标准化的数据格式，简化数据上传和分析过程。本文通过代表性结果和详细案例展示其实用性；3.	用户友好的界面：EVenn拥有易用的界面，简化了各种韦恩图、欧拉图、UpSet图的生成过程。EVenn是研究人员解读多组学数据的好用工具。</p>
</div>

<img src="image/Overviewvenn.png" width="100%" style="display: block; margin: auto;" />




## Demo data and animations

Each tool contains at least one copy of demo data for beginners. Normally only `one click on the Submit button` is needed to generate the demo result.

Pictures and animations illustrating the usages of every tools step by step are recorded in following sections. `Left arrow key` and `right arrow key` in the keyboard could be used to navigate this document to change sections.

Some example data are also listed in the second section - [Example files](#example_file).

## Hints for question mark symbol

This may be a common sense that question mark symbol (`?`) hides help information. 

<div class="figure" style="text-align: center">
<img src="image/questionMark.png" alt="Hovering the mouse cursor on any question mark symbol to see help or description information." width="100%" />
<p class="caption">(\#fig:questionMark)Hovering the mouse cursor on any question mark symbol to see help or description information.</p>
</div>


## Gallary {#gallary} 

### Venn network for OTUs

(ref:vennNetwork00label) Venn network using demo data Click <http://www.ehbio.com/test/venn/video/EVennNetwork.webm> or <https://youtu.be/8zf_XuwaZRw> to view the tutorials.

<div class="figure" style="text-align: center">
<img src="image/vennNetwork00.png" alt="(ref:vennNetwork00label)" width="100%" />
<p class="caption">(\#fig:vennNetwork00)(ref:vennNetwork00label)</p>
</div>


### Venn network for DE genes

(ref:VennNetworkGallery1label) Venn network using data <DE_gene_file.txt> in [example data](#example_file).

<div class="figure" style="text-align: center">
<img src="image/VennNetworkGallery1.png" alt="(ref:VennNetworkGallery1label)" width="100%" />
<p class="caption">(\#fig:VennNetworkGallery1)(ref:VennNetworkGallery1label)</p>
</div>

### Venn network for pathway enrichment results

(ref:VennNetworkGalleryP53pathway) Venn network using data <Gene_enrichment.txt> in [example data](#example_file).

<div class="figure" style="text-align: center">
<img src="image/VennNetworkGalleryP53pathway.png" alt="(ref:VennNetworkGallery1label)" width="100%" />
<p class="caption">(\#fig:VennNetworkGalleryP53pathway)(ref:VennNetworkGallery1label)</p>
</div>

### Venn network for 12 sets

(ref:Vennnetworkgallary12sets) Venn network using data <taxonomy_highabundance_manysets.txt> in [example data](#example_file).


<div class="figure" style="text-align: center">
<img src="image/Vennnetworkgallary12sets.png" alt="(ref:VennNetworkGallery1label)" width="48%" /><img src="image/Vennnetworkgallary12setsparameters.png" alt="(ref:VennNetworkGallery1label)" width="48%" />
<p class="caption">(\#fig:Vennnetworkgallary12sets)(ref:VennNetworkGallery1label)</p>
</div>


## How to cite?

EVenn is published in `iMeta`. Please cite **Visualizing set relationships: EVenn's comprehensive approach to Venn diagrams**  Mei Yang, Tong Chen, Yong-Xin Liu, Luqi Huang 11 April 2024. [https://doi.org/10.1002/imt2.184](https://doi.org/10.1002/imt2.184). 

EVenn is published firstly in year 2020 in JGG and has been cited for more than 200 times in two years.








<!--chapter:end:index.Rmd-->

# 最全可视化集合工具EVenn使用手册 {#evennchineseprotocol}


## EVenn界面和代表性结果  {#eveen_representative_result}


EVenn平台的主界面提供了十个模块：数据中心、交互式韦恩图、交互式爱德华图、欧拉图、UpSet图、花瓣图、交互式花瓣图、韦恩网络、韦恩差异显著性分析以及韦恩计算模块。其中交互式韦恩图、交互式爱德华图、欧拉图、UpSet图、花瓣图及交互式花瓣图，均可用于比较不同组织的差异代谢物、不同组织或条件下的基因表达谱、不同样本中的蛋白质组成、不同疾病或条件下的生物标志物、不同药物处理组与对照组之间的筛选结果，以及不同样本中的菌群共存（OTUs）。韦恩网络图对于分析基因互作、蛋白质-蛋白质互作和代谢物互作网络特别有价值。例如，它能在网络图中展示富集的KEGG通路或GO条目中基因的共存情况。此模块同样适用于转录组、基因组及其他组学数据的分析。

<div class="figure" style="text-align: center">
<img src="image/imt2184-fig-0001-m.jpg" alt="EVenn的代表性结果示意图。（A）2至6组集合的交互式标准韦恩图；（B）2至6组集合的交互式爱德华图；（C）2至3组集合的欧拉图；（D）显示空交集和不显示空交集的UpSet图；（E）19组和70组集合的花瓣图；（F）4至5组集合的韦恩网络图；（G）韦恩图、UpSet图和韦恩网络图三者之间的对应关系图。" width="100%" />
<p class="caption">(\#fig:imt2184fig0001m)EVenn的代表性结果示意图。（A）2至6组集合的交互式标准韦恩图；（B）2至6组集合的交互式爱德华图；（C）2至3组集合的欧拉图；（D）显示空交集和不显示空交集的UpSet图；（E）19组和70组集合的花瓣图；（F）4至5组集合的韦恩网络图；（G）韦恩图、UpSet图和韦恩网络图三者之间的对应关系图。</p>
</div>

以下，我们提供了详细解释，以阐明每个模块生成的代表性结果图及其适用条件。

## 交互式韦恩图/爱德华图 {#interactivevennedward}


EVenn的交互式韦恩图具有多重用途，允许用户在标准韦恩图和爱德华图之间无缝切换，同时便于探索和绘制多达**6**组数据。标准韦恩图通常用于比较2到6组实验数据（图 \@ref(fig:imt2184fig0001m) A），这里使用颜色编码来表示每组的特有和共有元素。

> 例如，紫色（a，b，c）代表每组特有元素，蓝色（d，e，f）表示两组之间的共有元素，黄色区域（g）表示三组共同存在的元素。

相比之下，交互式爱德华图在集合多时能更清晰地展示各个部分，特别是在涉及5到6组的情况下（图1B）。

> 以三组为例，其中a、b和c表示特有元素的区域，d、e和f代表两组中的共有元素区域，g代表三组中的共有元素。

## 增强可视化的欧拉图 {#eulerdiagram}


相较于韦恩图，欧拉图在数据允许的情况下*省略了空交集区域*，从而提升了多个集合可视化的精确性，有更好地视觉效果和呈现力。欧拉图通常用于2至3组实验数据，生成圆圈的大小同集合中元素数目成正相关，交集区域的大小与共享元素的数量成正比。这一特性清晰地描述集合之间的部分包含、完全包含及完全排除关系（如图 \@ref(fig:imt2184fig0001m) C所示）。

在图 \@ref(fig:imt2184fig0001m) C 所展示的三个集合例子中，每个圆圈的大小表示其各自集合中元素的数量，圆圈越大表示元素数量越多。

> 绿色（a）与紫色（b）代表各自集合的特有元素，而重叠区域（c）代表两个集合之间共有的元素。此外，黄色区域（d）表示了三个集合共有元素。欧拉图有效地展示出集合之间的包含关系，为集合交互提供了更直观地视觉化表现。

## UpSet图：一个强大的集合交集分析工具 {#upsetdescription}


UpSet图作为一个创新的可视化技术，专为集合交集的定量分析而设计，能够处理包含3至40个集合的复杂数据集。它通过两种展示模式，巧妙地可视化了不同的集合组合关系。如图 \@ref(fig:imt2184fig0001m) D所示，该图有三个主要组成部分：

* 一个水平条形图表示每个集合中的总元素数量，
* 一个垂直条形图指示对应交集中的元素数量，
* 以及一个带有连接点的矩阵，勾勒出集合之间所有的关系类型。

在这个例子中，单独一个黑色点代表每个集合中的特有元素，而有线连接的黑色点象征着集合之间共有的元素。UpSet图全面展示了集合之间的关系，

> 其中两个黑点的连接表示两个集合共有的元素，三个黑点的连接表示三个集合共有的元素，四个黑点的连接则表示四个集合共有的元素，以此类推。


## 花瓣图：揭示多组数据集的复杂关系  {#flowerplotdes}

当处理超过**十组**的复杂数据集时，传统的可视化方法如韦恩图、欧拉图和UpSet图会难以应对。花瓣图是平衡解读性与信息丰富度的一种可视化方式。图 \@ref(fig:imt2184fig0001m) E的左侧展示了一个包含`19`个集合的花瓣图，而右侧是包含`70`个集合的花瓣图。


在图 \@ref(fig:imt2184fig0001m) E中，中心圆圈（a）代表所有集合共有的元素。围绕它的每个椭圆（b）表示每个集合相比于其它所有集合中特有元素的数量，或者是每个集合减去共有元素后的元素，这取决于具体的参数设置。


## 韦恩网络：揭示集合间的相互联系 {#vennnetworkdes}


韦恩网络拓展了标准韦恩图的展示边界，不仅是展现交集和并集的关系，而且可以展示出具体的元素。它将每个`集合`指定为一个大的`父节点`，每个`元素`指定为一个小的`子节点`，并通过边将各个元素也就是子节点连接至其相应的父节点，来描绘`集合内`和`集合间`的关系。韦恩网络布局的灵活性在图 \@ref(fig:imt2184fig0001m) F中得到展示，韦恩网络会根据不同的数据类型呈现出相应的结构形态，已更好展现数据内集合之间的固有关系。


在图 \@ref(fig:imt2184fig0001m) F中，4个集合和5个集合的网络图揭示了它们元素之间的复杂关系。

> 每个元素，由一条边连接表示其是各集合的特有元素。两条连接边线表示两个集合的交集，而三条边线代表三个集合的交集。韦恩网络展示了数据集内外相互连接的视觉层次。

## 韦恩图、UpSet图与韦恩网络三者之间的对应关系  {#vennupsetvennnetworkrelationship}


在图 \@ref(fig:imt2184fig0001m) G中，我们借助一个三集合场景，展示了`韦恩网络`、`韦恩图`和`UpSet图`之间的对应关系以更好地理解这三种展示形式。每张图通过相应的字母标记一致的元素区域，确保了对这三种可视化之间关系的清晰理解。字母和颜色的一致性便于轻松识别同类型的关系组合：黄色（g）表示三个集合共有的元素，而蓝色（d、e、f）表示了两个集合共有的元素。与此形成对比的是，紫色（a、b、c）表示每个集合独有的元素。


## EVenn数据中心简化输入数据 {#evenndatacenter}

EVenn的数据中心使用标准化的两列矩阵格式来简化输入过程，适用于韦恩图、欧拉图、UpSet图、花瓣图、交互式花瓣图、韦恩网络和韦恩计算工具。这种用户友好的格式，确保所有工具都可兼容，以第一行作为标题行，第一列是元素（例如，基因或OTUs），第二列对应各自的集合，一个TAB键用作列分隔符。准备这种输入矩阵非常简单，可以通过Excel、其他兼容的文本编辑器或简单程序完成。数据中心提供了两种文件上传模式—本地文件上传和直接粘贴数据上传。这种灵活的数据输入方式和标准化的数据格式，提升了用户体验，并加速了从数据准备到深入分析的过程。


(ref:fig181) 输入数据格式见 章节\@ref{inputfileformat}。


<div class="figure" style="text-align: center">
<img src="image/Fig1.png" alt="(ref:fig181)" width="100%" />
<p class="caption">(\#fig:fig181)(ref:fig181)</p>
</div>


上传文件是个很简单的过程，虽说是 5 步，但实际不复杂。首先拖动或点击文件以启动上传（图 \@ref(fig:figs1)，步骤1）。其次为文件赋予独一无二的名称，以便轻松识别（图 \@ref(fig:figs1)，步骤2）。所上传文件的内容将自动充填至指定文本区域（图 \@ref(fig:figs1)，步骤3），用户可浏览及修改数据。最后点击“提交”按钮完成上传过程（图 \@ref(fig:figs1)，步骤4）。一旦完成，文件将在文件选择界面中显示（图 \@ref(fig:figs1)，步骤5），在打开每个工具时可以直接选择这里上传的文件进行分析和展示。

<div class="figure" style="text-align: center">
<img src="image/imt128figures1.png" alt="数据上传" width="100%" />
<p class="caption">(\#fig:figs1)数据上传</p>
</div>


另一种数据输入的方法是将数据直接粘贴至数据中心的文本域。首先输入文件名以便标识（图 \@ref(fig:figs2)，步骤1），然后将数据矩阵粘贴至指定文本区（图 \@ref(fig:figs2)，步骤2）。点击“提交”完成保存过程（图 \@ref(fig:figs2)，步骤3）。上传的文件也会在文件选择器中显示（图 \@ref(fig:figs2)，步骤4）。
为有效管理上传文件，数据中心允许最多保存五个文件。为了加入新文件，可在“提交”按钮下方的下拉菜单中有选择地删除旧文件后再保存（图 \@ref(fig:figs2)，步骤5）。需留意，这些文件存储在您本地的网页浏览器，并未上传至我们的服务器。因此，关闭您的网页浏览器有可能导致这些上传文件的丢失，且无法从您电脑的其他网页浏览器访问这些文件。

<div class="figure" style="text-align: center">
<img src="image/imt128figures2.png" alt="数据粘贴" width="100%" />
<p class="caption">(\#fig:figs2)数据粘贴</p>
</div>


## 数据智能参数限制 {#intelligentparameterctrl}

为了提升用户体验并防止因输入不准确或操作失误引起的错误，EVenn引入了数据智能参数限制。例如，欧拉图支持两种输入矩阵类型，并根据数据类型的不同，条件性地启用或禁用某些可设置参数。在双列模式下，调整仅限于包含所有元素的列和包含所有集合信息的列。此外，在让用户确定列名时采用一个用户友好的下拉框取代开放式输入框，以减少打字错误并通过限制用户的选择范围更好地提示用户的操作。这些优化显著提高了EVenn界面的易用性，确保了更流畅的使用体验。

## 案例展示 {#evenncases}



<div class="figure" style="text-align: center">
<img src="image/imt2184-fig-0002-m.jpg" alt=" EVenn案例展示（A）茯苓5个部位处理前后差异代谢物的交互式韦恩图；（B）茯苓5个部位处理前后差异代谢物的交互式爱德华图；（C）抗癌药物治疗后三种细胞差异表达基因的欧拉图；（D）7个转录调控因子及其靶向基因ChIP-seq的UpSet图；（E）交互式花瓣图展示18个微生物组共有和特有OTUs数量；（F）交互式花瓣图展示18个微生物组共有及减去共有后的OTUs数量；（G）韦恩网络图展示穿心莲基因GO富集分析结果；（H）韦恩网络图展示穿心莲四个生物过程富集分析结果（仅展示共有和特有基因）。" width="100%" />
<p class="caption">(\#fig:imt2184fig0002m) EVenn案例展示（A）茯苓5个部位处理前后差异代谢物的交互式韦恩图；（B）茯苓5个部位处理前后差异代谢物的交互式爱德华图；（C）抗癌药物治疗后三种细胞差异表达基因的欧拉图；（D）7个转录调控因子及其靶向基因ChIP-seq的UpSet图；（E）交互式花瓣图展示18个微生物组共有和特有OTUs数量；（F）交互式花瓣图展示18个微生物组共有及减去共有后的OTUs数量；（G）韦恩网络图展示穿心莲基因GO富集分析结果；（H）韦恩网络图展示穿心莲四个生物过程富集分析结果（仅展示共有和特有基因）。</p>
</div>

### 案例一：交互式韦恩图展示差异代谢物 {#case1}

韦恩图以直观的方式比较和分析不同条件或组织中的代谢物、基因和OTUs的重叠情况。例如，以研究茯苓处理前后不同部位的代谢物变化为例（[表S1](data/tableS1.txt)）。交互式韦恩图支持三种不同的数据输入方法：使用两列格式上传或粘贴数据（默认模式）（图 \@ref(fig:figs3)，步骤1），直接粘贴每个集合的元素（输入元素）（图 \@ref(fig:figs3)，步骤2），以及手动输入每个交集的计数（输入数字）（图 \@ref(fig:figs3)，步骤3）。

<div class="figure" style="text-align: center">
<img src="image/imt128figures3.png" alt="交互式韦恩图支持的三种不同的数据输入方式" width="100%" />
<p class="caption">(\#fig:figs3)交互式韦恩图支持的三种不同的数据输入方式</p>
</div>

在此，我们展示了使用粘贴两列矩阵输入方法生成交互式韦恩图的简便过程，有效地展示了茯苓5个部位的差异代谢物。该方法包括下面一系列步骤： 

1. 数据矩阵输入：将差异代谢物数据矩阵以两列格式粘贴至文本区域（图 \@ref(fig:figs4)，步骤1）。第一列是代谢物名称，第二列是其检测部位信息。
2. 集合选择：按照顺序选择FS1、FS2、FS3、FS4及FS5集合进行分析（图 \@ref(fig:figs4)，步骤2）。
3. 生成交互式韦恩图：上述两个步骤完成后（其实每选择一步，都可以看到韦恩图在当前状态下的展示），将生成一个交互式韦恩图，展示茯苓5个部位差异代谢物的交集情况（图 \@ref(fig:figs4)，步骤3）。
4. 重排集合顺序：通过点击并拖动集合（FS1、FS2、FS3、FS4及FS5），将集合调整到理想位置（这里也可以删除集合）（图 \@ref(fig:figs4)，步骤4）。
5. 自定义集合颜色：使用位于每个集合名称旁的颜色选择器（图 \@ref(fig:figs4)，步骤5），为5个集合自定义颜色，分别为它们指定黄色、粉色、绿色、紫色及蓝色。
6. 全局配置参数：点击配置按钮激活全局配置参数（图 \@ref(fig:figs4)，步骤6）。相应选择“经典模式”或“爱德华模式”。字体、字号、输入列表统计、切换按钮及交集计数是否展示都保持默认参数。
7. 访问特定交集数据：点击韦恩图中的计数数字，下方文本区域显示该交集的差异代谢物名称（图 \@ref(fig:figs4)，步骤7）。标题显示差异代谢物的所属的特定集合区域。
8. 下载选项：通过点击下载按钮，获取差异代谢物PNG和SVG格式韦恩图，以及差异代谢物交集列表CSV格式文件（图 \@ref(fig:figs4)，步骤8）。

<div class="figure" style="text-align: center">
<img src="image/imt128figures4.png" alt="交互式韦恩图绘制步骤" width="100%" />
<p class="caption">(\#fig:figs4)交互式韦恩图绘制步骤</p>
</div>


图 \@ref(fig:imt2184fig0002m) A和B分别展示了茯苓5个部位的标准韦恩图和爱德华图。可见茯苓5个部位（FS1、FS2、FS3、FS4及FS5）共有119个处理后出现一致变化的差异代谢物。此外，FS1、FS2、FS3、FS4及FS5分别有2、5、1、0、4个处理后独特变化的差异代谢物。进一步地分析发现：FS1和FS2、以及FS2和FS3之间无相同的差异代谢物；FS3和FS4共有1个差异代谢物，而FS4和FS5共有7个差异代谢物。韦恩图清晰地描绘了茯苓处理前后5个部位差异代谢物的变化关系。



### 案例二：欧拉图展示差异表达基因关系 {#casestudy2}


通过分析文献中抗癌药物处理后不同类型细胞中差异基因关系，来展示欧拉图工具的使用。欧拉图工具支持两种类型数据输入方法：两列模式矩阵和计数矩阵。利用该工具生成差异表达基因欧拉图的具体步骤如下： 
1. 数据整理：整理文献中每种类型细胞的差异表达基因数量并呈现在[表S2](data/tableS2.txt)中。
2. 选择输入类型：选择交集-计数矩阵方法（图 \@ref(fig:figs5)，步骤1）。
3. 数据输入：将差异表达基因的两列计数矩阵粘贴到交集-计数矩阵框中（图 \@ref(fig:figs5)，步骤2）。第一行是标题行，第一列是所有集合的交集部分，第二列是每个交集的元素数量。此外，第一列中的“&”符号代表交集，TAB键作为列分隔符。
4. 基本参数选择：参数“Intersection Column containing all intersections”选择“交集”，参数“Column containing counts for each intersection”参数选择“计数”（图 \@ref(fig:figs5)，步骤3）。
5. 其他类型参数：此处，布局和颜色以及图片属性参数使用默认设置（图 \@ref(fig:figs5)，步骤4）。
我们对复杂的颜色参数设置进一步说明。这里提供两种定义颜色的方法：为每个集合手动设置颜色和手动设置颜色向量（颜色集）（图 \@ref(fig:figs6)A）。
为每个集合手动设置颜色：设置每个集合的颜色。选择颜色时，请确保点击颜色选择器中的“确定”按钮（图 \@ref(fig:figs6)B）。此参数的使用与手动设置颜色向量（颜色集）参数互斥。启用此参数前，请确保清除手动颜色设置向量（颜色集）的值。如果您想为每个集合指定颜色，应选择相同数量的颜色（图 \@ref(fig:figs6)B）。如果选取的颜色数量少于集合数，程序将自动生成中间色以使其与集合的数量相等。
手动设置颜色向量（颜色集）：为所有集合选择颜色向量。此参数与为每个集合手动设置颜色参数互斥（图 \@ref(fig:figs6)C）。首先请清除为每个集合手动设置颜色参数的值，以启用此参数。
6. 生成欧拉图：点击“提交”按钮（图 \@ref(fig:figs5)，步骤5），在绘图区显示差异表达基因的欧拉图（图 \@ref(fig:figs5)，步骤6）。右击图片可以保存成PNG格式，也可以通过点击“下载PDF”按钮，将图片保存成PDF格式（图 \@ref(fig:figs5)，步骤7）。

<div class="figure" style="text-align: center">
<img src="image/imt128figures5.png" alt="欧拉图绘制步骤" width="100%" />
<p class="caption">(\#fig:figs5)欧拉图绘制步骤</p>
</div>

<div class="figure" style="text-align: center">
<img src="image/imt128figures6.png" alt="欧拉图颜色设置" width="100%" />
<p class="caption">(\#fig:figs6)欧拉图颜色设置</p>
</div>

通过上述步骤生成了图 \@ref(fig:imt2184fig0002m) C，可以看出NCCIT细胞特有的差异表达基因最多为666个，在图中占据了最大的面积。相比之下，NCCIT、Erms和GBM之间的共有差异基因数量最少，仅有15个基因，因此占据了图中最小的面积。采用欧拉图，与文献中原有的可视化方式相比提高了差异表达基因数量展示的精准性。



### 案例三：UpSet图展示ChIP-seq数据 {#casestudy3}


ChIP-seq是研究表观组学中广泛应用的技术，用于探索蛋白质与DNA之间互作和了解基因组的功能元件。在本案例研究中，我们对小鼠胚胎干细胞（ESC）中5个转录因子（Esrrb、Klf4、Med1、Nanog、Sox2）和2个组蛋白修饰标记（H3K27ac与H3K4me1）的ChIP-seq数据进行了分析，旨在确定它们共有和特有的结合位点。这些ChIP-seq数据源自Whyte等人的研究 ([表S3](data/tableS3.txt))。UpSet图的生成接受两种输入格式：两列矩阵和二进制矩阵格式。生成ChIP-seq UpSet图的步骤如下： 

1. 数据集预处理：利用ImageGP (<https://www.bic.ac.cn/BIC>)平台将[表S3](data/tableS3.txt)中Sox2、Nanog、Klf4、Esrrb、H3K27ac、Med1、H3K4me1及其结合基因数据转换成两列格式，如[表S4](data/tableS4.txt)所示(<https://www.bic.ac.cn/BIC>，图 \@ref(fig:figs7)，步骤1)。
2. 选择数据输入类型：选择两列矩阵格式输入数据。
3. 数据输入：以两列格式粘贴转录调控因子和靶向基因数据，第一列是靶向基因，第二列是转录调控因子(图 \@ref(fig:figs8)，步骤1)。
4. 基本参数选择：参数“将第一行作为标题行”，设置为“是”，而参数“保留空相交”设置为“假”(图 \@ref(fig:figs8)，步骤2)。
5. 生成UpSet图：点击“提交”按钮(图 \@ref(fig:figs8)步骤3)即可得到UpSet图。然后，点击“下载PDF”按钮(图 \@ref(fig:figs8)步骤4)即可下载PDF格式的图片。

(ref:figs7) 采用 BIC (<https://www.bic.ac.cn/BIC/#/>)平台进行数据转换

<div class="figure" style="text-align: center">
<img src="image/imt128figures7.png" alt="(ref:figs7)" width="100%" />
<p class="caption">(\#fig:figs7)(ref:figs7)</p>
</div>

<div class="figure" style="text-align: center">
<img src="image/imt128figures8.png" alt="UpSet 图绘制步骤" width="100%" />
<p class="caption">(\#fig:figs8)UpSet 图绘制步骤</p>
</div>


如图 \@ref(fig:imt2184fig0002m) D所示，UpSet图展示了7个调控因子之间的共有和特有结合或修饰的基因，其中有3411个基因受到7个转录调控因子的共同调控，此外，还有475个基因仅与Sox2、Nanog、Klf4、Esrrb、Med1和H3K4me1结合。值得注意的是，这七个转录调控因子各自并没有特有的结合基因。通过UpSet图可以有效地可视化它们与结合位点之间的复杂关系。




### 案例四：交互式花瓣图展示微生物群落的特异性 {#casestudy4flowerplot}


探究微生物群落特异性对于理解生态角色、疾病诊断、揭示进化过程以及探索关键菌群至关重要。交互式花瓣图作为一种宝贵的工具，能够展示超过十个微生物群落组中的共有和特有的元素。通过EasyAmplicon流程获取不同组（敲除组、野生型及过表达组）的操作分类单元（OTU）数据。生成微生物组交互式花瓣图，请遵循以下步骤： 

1. 数据预处理：使用ImageGP平台将[表S5](data/tableS5.txt)的数据转换为两列格式（转换后的数据见[表S6](data/tableS6.txt)）。
2. 两列模式数据矩阵输入：将微生物OTUs数据粘贴到数据框的指定文本区域（第一列是元素，即OTUs或ASVs，第二列是集合名称，即样本组）。
3. 选择参数：为元素选择“OTUID”列，为集合信息选择“Group”列。对于椭圆中展示的数值的参数，分别选择两种模式。其余参数保持默认设置。
4. 生成交互式花瓣图：点击“提交”按钮生成交互式花瓣图。通过点击图片中的数字可以获取各个组的共有和特有元素。
5. 下载SVG：将图片以SVG格式导出。 

<div class="figure" style="text-align: center">
<img src="image/imt128figures9.png" alt="花瓣图绘制步骤" width="100%" />
<p class="caption">(\#fig:figs9)花瓣图绘制步骤</p>
</div>

图 \@ref(fig:imt2184fig0002m) E展示了18个样本组共有413个相同OTUs。其中，WT3、OE1和KO3集合包含独特的OTUs，分别是ASV_942、ASV_1022和ASV_1201。相反，其余15个组缺乏独特OTUs。图 \@ref(fig:imt2184fig0002m) F也展示了18个微生物组中413个相同OTUs元素的存在，但是围绕中心圈的18个花瓣则代表在减去共有元素后每组的OTUs元素计数。运用两种不同花瓣图展示方法对于从多个角度分析OTUs在较多样品组中的相似性和差异性具有优势。

### 案例五:韦恩网络显示GO富集结果 {#casestudy5}

为了展示韦恩网络可视化功能，我们通过IMP平台（<https://www.bic.ac.cn/IMP>）提供的GO/KEGG富集分析工具，获取了穿心莲的基因及GO数据。所获得的数据集，如图 \@ref(fig:figs10)所示，包含了生物过程条目与其关联的基因。我们的目标是构建一个韦恩网络图，展示富集到的生物通路与基因的网络关系。具体操作如下： 


1. 数据预处理：筛选所需的基因和GO数据，使用 ImageGP平台（https://www.bic.ac.cn/BIC）将数据转换成韦恩网络所需的两列格式（图 \@ref(fig:figs7)，步骤2，[表S7](data/tableS7.txt)）。
2. 数据矩阵输入：将上面转换出的 2 列矩阵粘贴到文本域中，注意目标基因需要在第一列，GO条目需要在第二列（图 \@ref(fig:figs11)，步骤1）。
3. 选择参数：设置颜色和展示模式两个参数可以自由选择。例如，我们选择了粉色、绿色、紫色和蓝色作为颜色参数（图 \@ref(fig:figs11)，步骤2）。此外，先选择“显示所有元素”模式以全面展示数据，也可以选择“仅显示共有元素及特有元素”模式展示类似花瓣图中的数据统计（图 \@ref(fig:figs11)，步骤3）。
4. 生成韦恩网络图：点击“提交”按钮后，生成韦恩网络图（图 \@ref(fig:figs11)，步骤4）。
5. 优化韦恩网络图布局：为了优化韦恩网络图的清晰度和美观性，访问“工具菜单”（图 \@ref(fig:figs11)，步骤5）并使用“首选布局”按钮（图 \@ref(fig:figs11)，步骤6）。随后，点击工具按钮以显示左侧工具栏（图 \@ref(fig:figs11)，步骤7），修改节点、边、布局参数。其中，边类型参数设置为“diagonalCross”，布局模式中布局计算算法设置为“barnesHut”，而其他设置保持默认值（图 \@ref(fig:figs11)，步骤8-9）。
6. 韦恩网络的节点和边参数：我们提供了一个“编辑X节点”按钮，用于更改多个选定节点的属性，以及一个“编辑边”按钮，用于更改边的宽度和颜色（图 \@ref(fig:figs11)，步骤10-11）。节点和边的颜色方案如图 \@ref(fig:imt2184fig0002m)G所示。
7. 下载韦恩网络图：点击“导出SVG”按钮，以SVG格式导出韦恩网络图（图 \@ref(fig:figs11)，步骤 12）。

(ref:figs10) IMP平台（<https://www.bic.ac.cn/IMP>）的GO/KEGG富集分析工具。

<div class="figure" style="text-align: center">
<img src="image/imt128figures10.jpg" alt="(ref:figs10)" width="100%" />
<p class="caption">(\#fig:figs10)(ref:figs10)</p>
</div>

<div class="figure" style="text-align: center">
<img src="image/imt128figures11.png" alt="EVenn网络绘制步骤" width="100%" />
<p class="caption">(\#fig:figs11)EVenn网络绘制步骤</p>
</div>

如图 \@ref(fig:imt2184fig0002m)  G所示，IMPTAPA2N19692_1基因参与到四个关键生物过程：monocarboxylic acid biosynthesis、cellular amino acid metabolism、organitogen compound biosynthesis和multiple organismal enrichment process。基因IMPTAPA2N21328_1、IMPTAPA2N31674_1、IMPTAPA2N40577_1、IMPTAPA2N11277_1、IMPTAPA2N33800_1和IMPTAPA2N22367_1与monocarboxylic acid biosynthesis和multiple organismal enrichment process相关。此外，IMPTAPA2N33400_1特异性从属于organitogen compound biosynthesis过程。图 \@ref(fig:imt2184fig0002m) H描绘了四个不同生物过程中共有和特有基因的存在。

 


## 结论 {#discussionevenn}

韦恩图数据分析的复杂性源于数据格式的不一致和缺乏统一的数据分析平台。本文全面概述了EVenn平台内各个模块的功能与操作，包括数据中心、交互式韦恩图、欧拉图、UpSet图、花瓣图、交互式花瓣图以及韦恩网络图。

在不同实验条件下比较代谢物、基因、基因组区域和微生物类群等数据，常需借助专门的可视化技术，包括交互式韦恩图、欧拉图、UpSet图、花瓣图和交互式花瓣图。其中，

* 交互式韦恩图特别适用于比较多达6组实验数据，允许直观识别共性与差异。
* 相比之下，欧拉图更适合比较2到3组实验数据，通过面积比例表示每组的数据大小。
* UpSet图可以比较3组至40组复杂的数据集。
* 而花瓣图在评估10组以上数据的共有与特有元素时更常用，可以清晰地展示多组数据关系。
* 此外，韦恩网络图是用网络形式展示集合关系的有效工具。它可以揭示多组实验之间的关系，展示复杂的交互模式。

总之，选择哪种可视化方法取决于数据和研究目的。通过理解每个工具的功能，研究人员可以有效地解释和展示他们的结果。

数据和脚本已在GitHub (<https://github.com/Tong-Chen/venn-doc>)和Gitee(<https://gitee.com/ct5869/venn-doc/>)发布。所有的补充材料（文本、图、表、中文翻译版本或视频）也可从线上获取。



<!--chapter:end:00.ChineseTutorial.Rmd-->

# Input file format {#inputfileformat}

## The unified two-column matrix for all tools {#unifiedforall}

In EVenn, we unified the input data in one simple format for all tools. It is a two-column regular matrix with: 

1. The `first` column containing elements by rows. 
2. And the `second` column specifies the set each item belongs to, so we named it as **two-column mode** (Fig \@ref(fig:fig1) A-D). 
3. If one item belongs to several sets, it may appear in several rows. 
4. The order of rows does not matter. 
5. The order of columns matters at least for interactive `Venn diagrams` and `Venn networks`. 

This type of data could be easily generated using Excel or other text-editors with just ‘copy-paste’ operations. It could also be generated program-ably in any analysis pipeline with addition or changing only few codes. 

Another advantage of this specified format is that it is both human and machine readable, and could be saved for repeatable usages. Based on the unified input format, it is feasible to generate and compare different visualization ways during the data exploring stage and result showing stage. Leaving out of the trouble of file format changing for separate tools, which is essential and not so trivial for researchers who could not program.  

<div class="figure" style="text-align: center">
<img src="image/Fig1.png" alt="Illustration of input data formats. A. The general example of two-column data matrix. B, C, and D represent specified examples for gene sets, OTUs sets and pathway sets respectively. E. Pasting elements for each set separately. F. Typing counts for each intersection. G. Binary matrix format. " width="100%" />
<p class="caption">(\#fig:fig1)Illustration of input data formats. A. The general example of two-column data matrix. B, C, and D represent specified examples for gene sets, OTUs sets and pathway sets respectively. E. Pasting elements for each set separately. F. Typing counts for each intersection. G. Binary matrix format. </p>
</div>

## Specifialized input formats for some tools {#specifiedforsome}

Besides, the classical input formats for each tool were also preserved for meeting various requirements. For example:

1. Pasting elements for each set separately and naming each set on the fly for interactive Venn diagram (Fig \@ref(fig:fig1) E).
2. Input the counts instead of related elements of each intersections to draw interactive Venn diagrams and Euler diagrams (Fig \@ref(fig:fig1) F). This is useful for counting data such as cell immunofluorescence experiments how many cells are stained as <font color="#FF0000">red</font>, how many cells are stained as <font color="#00FF00">green</font>, how many cells have merged color of <font color="#FFFF00">yellow</font>.
3. UpSet also supports a binary matrix for illustrating elements existence  (Fig \@ref(fig:fig1) G). In this format, the first line is the header line containing names of all sets. Each row represents one element. Each column represents each set. Each row represents one element. A value of non-zero representing the corresponding element belongs to the corresponding set.




<!--chapter:end:01.InputFileFormat.Rmd-->

# Upload files in data center {#datacenter_uploading}

*Attention*: The files would not be uploaded to our server in this step. They only exist in a local region in your web browser. These uploaded files would be lost after the web browser is closed. Also, one could not see these uploaded data in other web browsers. 


## Upload a file {#uploadafile}

1. Drag your file or click to upload your file (Fig \@ref(fig:figdatacenter1) <font color="#FF0000">1</font> step).
2. Input a name for your file for identification (Fig \@ref(fig:figdatacenter1) <font color="#FF0000">2</font> step).
3. The content of the uploaded file would be loaded into the text area (Fig \@ref(fig:figdatacenter1) <font color="#FF0000">3</font> step). Users are allowed to browse and revise uploaded data if necessary.
4. Remember to click **Save** or **Submit** to finish the uploading process (Fig \@ref(fig:figdatacenter1) <font color="#FF0000">4</font> step).
5. Then your uploaded file would be shown in the file selector (Fig \@ref(fig:figdatacenter1) <font color="#FF0000">5</font> step). One can browse or delete unneeded files.

<div class="figure" style="text-align: center">
<img src="image/Datacenter1.png" alt="Upload your files." width="100%" />
<p class="caption">(\#fig:figdatacenter1)Upload your files.</p>
</div>

Here is an animation showing the processes.

<div class="figure" style="text-align: center">
<img src="image/DragUploadFiles.gif" alt="Animation showing uploading processes." width="100%" />
<p class="caption">(\#fig:uploaddata1gif)Animation showing uploading processes.</p>
</div>

## Paste your data here

1. Input a name for your file for identification (Fig \@ref(fig:figdatacenter2) <font color="#FF0000">1</font> step).
2. Paste the data matrix to the text area (Fig \@ref(fig:figdatacenter2) <font color="#FF0000">2</font> step). 
3. Remember to click **Save** or **Submit** to finish the saving process (Fig \@ref(fig:figdatacenter2) <font color="#FF0000">3</font> step).
4. Then your uploaded file would be shown in the file selector (Fig \@ref(fig:figdatacenter2) <font color="#FF0000">4</font> step). One can browse or delete unneeded files.


<div class="figure" style="text-align: center">
<img src="image/Datacenter2.png" alt="Paste your files." width="100%" />
<p class="caption">(\#fig:figdatacenter2)Paste your files.</p>
</div>

Here is an animation showing the processes.

<div class="figure" style="text-align: center">
<img src="image/PasteUploadFiles.gif" alt="Animation showing pasting as uploading." width="100%" />
<p class="caption">(\#fig:pasteuploaddata1gif)Animation showing pasting as uploading.</p>
</div>

## Example files {#example_file}

If you accidentally clicked these files directly, use the `back` button on `left-top` corner of your web browser to return back.

* List of differentially expressed genes: [DE_gene_file.txt](data/DE_gene_file.txt) (*right click to save*)
* Gene enrichment results: [Gene_enrichment.txt](data/Gene_enrichment.txt) (*right click to save*)
* List of high abundance OTUs in each group: [High_abundance_OTU.txt](data/High_abundance_OTU.txt) (*right click to save*)
* List of high abundance taxonomy for many groups: [taxonomy_highabundance_manysets.txt](data/taxonomy_highabundance_manysets.txt) (*right click to save*)





<!--chapter:end:02.Datacenter.Rmd-->

# Interactive venn diagram {#Interactive_venn_diagram}

This module supports interactive Venn diagram plotting and exploring for at most 6 sets. Through clicking figures in generated plots, one could easily get elements lists for each intersection part. This would facilitate screening candidate elements like genes or OTUs meeting specified intersection patterns. 

Besides, it has several functions like switching between standard *Venn layout* and *Edwards-Venn layout*, switch on and off different lists for comparing. 

Another useful improvement compared with Jvenn is that one can reorder each set to get better visualization by simple dragging of input text-areas. This function is especially useful when one wants to delete one or several sets, no need of re-input for already existed sets (Fig \@ref(fig:InteractiveVennDiagramoupload)). 
There are also parameters for changing font sizes, font families, sets colors and other displaying attributes. 


## Three types of input ways {#threetypeinputway}

Three types of input ways are supported for more feasible usages, 
* uploading or pasting all data together using two-column formats (Two-column mode, which is the default) ((Fig \@ref(fig:fig1) A) and Fig \@ref(fig:interactiveVennInit) <font color="#FF0000">1</font>), 
* directly pasting elements of each set (Input elements) ((Fig \@ref(fig:fig1) E) and Fig \@ref(fig:interactiveVennInit) <font color="#FF0000">2</font>), 
* typing in counts of each intersections (Input numbers) ((Fig \@ref(fig:fig1) F) and Fig \@ref(fig:interactiveVennInit) <font color="#FF0000">3</font>). 

<div class="figure" style="text-align: center">
<img src="image/interactiveVennInit.png" alt="Three types of input ways." width="100%" />
<p class="caption">(\#fig:interactiveVennInit)Three types of input ways.</p>
</div>

The result picture could be exported in the scalable vector graphics (SVG) format which could be converted to high-resolution images or combined with other pictures for publication usages. Elements lists for each intersection could be downloaded in table format.




## Pasting two-column mode data matrix {#intervennpasting}

Here we use an animation showing the simple steps of generating and exploring an interactive Venn diagram with pasted two-column matrix (Fig \@ref(fig:InteractiveVennDiagramopate)).

<div class="figure" style="text-align: center">
<img src="image/InteractiveVennDiagram.op.gif" alt="Animation illustrating the steps of generating interactive venn diagrams with pasted data matrix." width="100%" />
<p class="caption">(\#fig:InteractiveVennDiagramopate)Animation illustrating the steps of generating interactive venn diagrams with pasted data matrix.</p>
</div>

We split these steps separately.

1. Paste your data matrix in two-column mode to the text-area (Fig \@ref(fig:InteractiveVennDiagram1) <font color="#FF0000">1</font> step).
2. Select which set to be analyzed in order. Unique value of the second column (including the header line if existed) would be saved in the drop-down menu as set names for selection (Fig \@ref(fig:InteractiveVennDiagram1) <font color="#FF0000">2</font> step). After several selection, we could get one Venn diagram showing left-top.
3. Set order could also be changed by holding on button (Fig \@ref(fig:InteractiveVennDiagram1) <font color="#FF0000">3</font>) and dragging to the target position.
4. color of each set could be customized separately using the color-picker beside set names (Fig \@ref(fig:InteractiveVennDiagram1) <font color="#FF0000">4</font>).
5. Global configuration parameters could be switched on by clicking button (Fig \@ref(fig:InteractiveVennDiagram1) <font color="#FF0000">5</font>), including display mode, font family, font size, statistics based on input lists (number of elements for each set), switch button, intersection counts. One could easily check their functions if not clearly described by simple clicking. 
6. Venn diagrams in *PNG*, *SVG* format and intersection elements in *CSV* lists could be downloaded by clicking button  (Fig \@ref(fig:InteractiveVennDiagram1) <font color="#FF0000">6</font>). In CSV lists, one column represents one type of non-empty intersections and attached elements. 
7. Click the count number in the Venn diagram would show the elements belonging to this intersection in below text-area with one headline showing elements' belonging. 


<div class="figure" style="text-align: center">
<img src="image/InteractiveVennDiagram1.png" alt="Displaying the steps for generating interactive venn diagrams with pasted data matrix in two-column mode." width="100%" />
<p class="caption">(\#fig:InteractiveVennDiagram1)Displaying the steps for generating interactive venn diagrams with pasted data matrix in two-column mode.</p>
</div>

## Use the uploaded two-column mode data matrix {#vennupload}

Here we use an animation showing how to choose the uploaded data matrix (seeing section [2](#datacenter_uploading) for data uploading), selecting sets, removing sets, reordering sets and other operations for 6 sets (Fig \@ref(fig:InteractiveVennDiagramoupload)).

<div class="figure" style="text-align: center">
<img src="image/InteractiveVennDiagram.ou.gif" alt="An animation illustrating the steps of generating interactive venn diagrams with previously uploaded data matrix." width="100%" />
<p class="caption">(\#fig:InteractiveVennDiagramoupload)An animation illustrating the steps of generating interactive venn diagrams with previously uploaded data matrix.</p>
</div>


## Pasting elements of each set {#venneachset}

Most online Venn diagram tools use this kind of input, pasting elements for each set separately and name each set on the fly.

## Input numbers for each intersection {#venninputcount}

This is sometimes useful for drawing Venn diagrams without elements but only numbers, such as the counting results of cell immunofluorescence experiments: how many cells are stained as <font color="#FF0000">red</font>, how many cells are stained as <font color="#00FF00">green</font>, how many cells have merged color of <font color="#FFFF00">yellow</font>.


<div class="figure" style="text-align: center">
<img src="image/pastenumbersvenn.gif" alt="Draw Venn diagrams with number input. Only support 2-4 sets." width="100%" />
<p class="caption">(\#fig:pastenumbersvenngif)Draw Venn diagrams with number input. Only support 2-4 sets.</p>
</div>






<!--chapter:end:03.Interactive_venn_diagram.Rmd-->

# Euler diagram {#Euler_diagram}

Euler diagram plots do not display empty intersection regions when possible, giving more concrete and accuracy visualization. Theoretically, it could have better visualization effects for more sets than Venn diagrams. And it could clearly show the fully-containing-relationships among 2 or several sets (Fig \@ref(fig:Eulerdiagrampng)). In EVenn, Euler diagram generates area-proportional diagrams, in which the sizes of intersection areas positively correlated with number of intersection elements. This gives more perceptual intuition than only showing numbers.

<div class="figure" style="text-align: center">
<img src="image/Euler_diagram.png" alt="Illustration of fully contained sets using the Euler diagram." width="100%" />
<p class="caption">(\#fig:Eulerdiagrampng)Illustration of fully contained sets using the Euler diagram.</p>
</div>

## Two types of input ways {#eulertwotypeinput}

Euler diagram supports two types of input. One is the two-column mode format matrix as we described above (Fig \@ref(fig:fig1) A). 

The other is a count matrix also with two columns (Fig \@ref(fig:fig1) F). The first line would be treated as the header line. The first column containing intersection parts of all sets by rows and the second column containing the number of elements in each intersection part. The `&` symbol in the first column represents intersecting. The column separator should be one `TAB`. 





## Pasting two-column mode data matrix {#eulerpasting}

Here we use an animation showing the simple steps of generating the Euler diagram with pasted two-column matrix (Fig \@ref(fig:eulerdiagrampaste)).

<div class="figure" style="text-align: center">
<img src="image/eulerdiagrampaste.gif" alt="Animation illustrating the steps of generating Euler diagrams with pasted data matrix." width="100%" />
<p class="caption">(\#fig:eulerdiagrampaste)Animation illustrating the steps of generating Euler diagrams with pasted data matrix.</p>
</div>

We split these steps separately.


1. Select one and only one data format  (Fig \@ref(fig:Eulerstep1) <font color="#FF0000">1</font> and <font color="#FF0000">1</font> radio button). Supposing we select `Two-column mode matrix`.
2. Paste your data matrix in two-column mode to the text-area (Fig \@ref(fig:Eulerstep1) <font color="#FF0000">3</font>) or select one uploaded file (Fig \@ref(fig:Eulerstep1) <font color="#FF0000">4</font>) (See section [2](#datacenter_uploading) for data uploading.).
3. We assume the `first` column contains `elements` and the `second` column contains `sets` name and will automatically get the names of each column to fill in (Fig \@ref(fig:Eulerstep1) <font color="#FF0000">5</font> and  <font color="#FF0000">6</font>). If your data matrix **does not** follow this assumption, one are allowed to change values of these two drop-down selection boxes.
4. Click `Submit` (Fig \@ref(fig:Eulerstep1) <font color="#FF0000">7</font>) and the result would be shown in the `Plot area` ((Fig \@ref(fig:Eulerstep1) <font color="#FF0000">8</font>). The result in `PNG` format showing below and could be saved by right clicking on the picture). The result picture could also be downloaded in `PDF` format by clicking `Download PDF` button.


<div class="figure" style="text-align: center">
<img src="image/Euler_step1.png" alt="Displaying the steps for generating Euler Venn diagrams with pasted data matrix in two-column mode." width="100%" />
<p class="caption">(\#fig:Eulerstep1)Displaying the steps for generating Euler Venn diagrams with pasted data matrix in two-column mode.</p>
</div>

## Additional style parameters {#addistylepara}

Here lists more style parameters for customized usages.

<div class="figure" style="text-align: center">
<img src="image/Euler_style.png" alt="Lists of more parameters. Hovering over the question mark to see detail information." width="100%" />
<p class="caption">(\#fig:Eulerstylepng)Lists of more parameters. Hovering over the question mark to see detail information.</p>
</div>

The width and height of output picture could be modified.  **Enlarge** these numbers if the graphic displaying is incomplete.



Most parameters could be selected very easily. Here we only explain the color setting parameters.

Here we supplied two ways to defined colors: `Manual color for each set` and `Manual color vector (color set)`.

* `Manual color for each set`: Set the color of each set. Remember to click **OK** when color is designated in color pickers (Fig \@ref(fig:colorset) and Fig \@ref(fig:ColorPicker)). This parameter is **mutual exclusion** with `Manual color vector (color set)` parameter. Please first clear values of `Manual color vector (color set)` to make this parameter able. If you want to assign color for each set, same number of colors should be picked. If the number of picked colors less than number of sets, the program would generate intermediate colors to make they equal.
* `Manual color vector (color set)`: Select the color vector for all sets. This parameter is mutual exclusion with `Manual color for each set` parameter. Please first clear values of `Manual color for each set` parameter to make this parameter able. 

**Attention**:  In each way, the number of color is not needed to be the same as number of sets. The underlying program will try the best to deal with color assignments. 

<div class="figure" style="text-align: center">
<img src="image/color_set.png" alt="The way to set colors manually." width="100%" />
<p class="caption">(\#fig:colorset)The way to set colors manually.</p>
</div>

<div class="figure" style="text-align: center">
<img src="image/ColorPicker.gif" alt="An animation showing adding, picking, removing and  clearing colors." width="100%" />
<p class="caption">(\#fig:ColorPicker)An animation showing adding, picking, removing and  clearing colors.</p>
</div>


<!--chapter:end:04.Eulerdiagram.Rmd-->

# UpSet {#UpSet}

Upset plot is designed as a novel visualization technique for the quantitative analysis of sets and their intersections (Fig \@ref(fig:upsetdiagrampng)). It composed three parts, a horizontal bar-plot showing total number of elements of each set, a matrix with connected-dots indicating all types of intersections among sets, a vertical bar-plot representing number of elements of corresponding intersections. The bars are normally ordered by item counts, giving more direct decision of the largest sets and intersections. Intersections which are empty could be selectively hided to save space for visualizing much more sets. 

<div class="figure" style="text-align: center">
<img src="image/UpSet.png" alt="UpSet diagrams for 5 sets. Horizontal blue bars represent total number of elements of each set. Orange bars represent number of elements of each intersection indicated by connected dots." width="100%" />
<p class="caption">(\#fig:upsetdiagrampng)UpSet diagrams for 5 sets. Horizontal blue bars represent total number of elements of each set. Orange bars represent number of elements of each intersection indicated by connected dots.</p>
</div>

Currently UpSet (in EVenn) is not supported for data-sets with more than 15 sets.

## Two types of input ways {#upsettwotypeinput}

Euler diagram supports two types of input. One is the two-column mode format matrix as we described above (Fig \@ref(fig:fig1) A). 

The other is a binary matrix for illustrating elements existence  (Fig \@ref(fig:fig1) G). In this format, the first line is the header line containing names of all sets. Each row represents one element. Each column represents each set. Each row represents one element. A value of non-zero representing the corresponding element belongs to the corresponding set. 




## UpSet plot using two-column mode data matrix {#upsetpasting}

Here we use an animation showing the simple steps of generating the UpSet with pasted two-column matrix (Fig \@ref(fig:UpSetAnimationgif)).

<div class="figure" style="text-align: center">
<img src="image/UpSetAnimation.gif" alt="Animation illustrating the steps of generating UpSet plot with pasted data matrix." width="100%" />
<p class="caption">(\#fig:UpSetAnimationgif)Animation illustrating the steps of generating UpSet plot with pasted data matrix.</p>
</div>

1. First, data matrix could be pasted to the text-area or selected from uploaded files. 
2. Second, only one essential parameter to specify if the first line would be treated as header line. 
3. Third, users are allowed to set whether to keep empty intersections. 
4. Forth, the width and height of output picture could be modified. **Enlarge** this number if the graphic displaying is incomplete.
5. Fifth, clicking `Submit` button to get the result in PNG format showing below (save by right clicking on the picture). The result picture could also be downloaded in `PDF` format by clicking `Download PDF button`.


<!--chapter:end:05.UpSet.Rmd-->

# Flower plot {#flowerplot}

For integrated data with more than 10 or 20 sets, neither Venn diagram, Euler diagram or UpSet (when most intersections are not empty) could give easy displaying. Flower plot which shows only common elements shared by all sets and special elements for each set provides another choice (Fig \@ref(fig:flowerdiagrampng)). Flower plot would be more useful when displaying commonality or specificity, while other intersection combinations are not so important. There is a trade-off between ease-interpretation and information loss. 

<div class="figure" style="text-align: center">
<img src="image/Flower.png" alt="Flower diagrams for 12 sets. Number of elememnts shared among all sets are labeled in the center circle. " width="100%" />
<p class="caption">(\#fig:flowerdiagrampng)Flower diagrams for 12 sets. Number of elememnts shared among all sets are labeled in the center circle. </p>
</div>

## Two-column mode matrxi as input  {#flowerinput}

The two-column mode format matrix (Fig \@ref(fig:fig1) A) is the required input for Flower plot. 


## Flower plot using two-column mode data matrix {#floweanimation}

Here we use an animation showing the simple steps of generating the flower plot with one uploaded two-column matrix (Fig \@ref(fig:flowerAnimationgif)).

<div class="figure" style="text-align: center">
<img src="image/flowerAnimation.gif" alt="Animation illustrating the steps of generating the flower plot with one uploaded two-column matrix." width="100%" />
<p class="caption">(\#fig:flowerAnimationgif)Animation illustrating the steps of generating the flower plot with one uploaded two-column matrix.</p>
</div>


1. First, data matrix could be pasted to the text-area or selected from uploaded files. 
2. Second, We assume the `first` column contains `elements` and the `second` column contains `sets` name and will automatically get the names of each column to fill in. If your data matrix **does not** follow this assumption, one are allowed to change values of these two drop-down selection boxes. Check the hints (holding the cursor on the question mark symbol) along each parameter for details. 
3. Third, layout and color styles could be changed as required or leaved out for default. Click `Layout and colors` to open/close related parameters.
4. Forth, the width and height of output picture could be modified (by clicking `Picture attributes`). **Enlarge** this number if the graphic displaying is incomplete.
5. Fifth, clicking `Submit` button to get the result in PNG format showing below (could be saves by `right clicking on the picture`). The result picture could also be downloaded in `PDF` format by clicking `Download PDF` button. 

## Color setting for flower plot {#flowercolorpallete}

See Fig \@ref(fig:ColorPicker).

## Fun with flower plot {#flowerfun}

Here shows the effect of switching the values between `Column containing all elements` and `Column containing all sets information`.

<div class="figure" style="text-align: center">
<img src="image/large.flower.png" alt="Flower diagrams for many sets." width="100%" />
<p class="caption">(\#fig:flowerdiagramfunpng)Flower diagrams for many sets.</p>
</div>



<!--chapter:end:06.flower.Rmd-->

# Venn network {#vennnetwork}

Venn network could show both elements and their belonging sets in an interactive network diagram (Fig \@ref(fig:vennnetworkpng)). Each set would be treated as one parent node, each item would be connected to its parent nodes via edges. Elements connected with all sets are shared among them. Interactive venn network is implemented using vis.js with function extensions and simplified steps. 

<div class="figure" style="text-align: center">
<img src="image/Vennnetwork.png" alt="Venn network for 3 sets. The three light-blue nodes represent sets KO, OE and WT. The purple nodes in the middle are shared among 3 sets. Those nodes connected with two edges are shared by every two sets. The outer nodes with only one connected edges are specially belonging to one set." width="70%" />
<p class="caption">(\#fig:vennnetworkpng)Venn network for 3 sets. The three light-blue nodes represent sets KO, OE and WT. The purple nodes in the middle are shared among 3 sets. Those nodes connected with two edges are shared by every two sets. The outer nodes with only one connected edges are specially belonging to one set.</p>
</div>

## Two-column mode matrxi as input  {#venninput}

The two-column mode format matrix (Fig \@ref(fig:fig1) A) is the required input for Flower plot. 


## Venn network using two-column mode data matrix {#vennanimation}

Here we use an animation showing the simple steps of generating the Venn network plot with the default demo data (Fig \@ref(fig:vennnetworkAnimationgif)).

<div class="figure" style="text-align: center">
<img src="image/vennnetworkAnimation.gif" alt="Animation illustrating the steps of generating the Venn network plot with one uploaded two-column matrix." width="100%" />
<p class="caption">(\#fig:vennnetworkAnimationgif)Animation illustrating the steps of generating the Venn network plot with one uploaded two-column matrix.</p>
</div>


1. First, data matrix could be pasted to the text-area or selected from uploaded files. Then other parameters are all optional. 
2. Second, color of each set could be assigned separately using the color picker or leaving out as default. Each set should have **one and only one** color assignment.
3. Third, users are allowed to show all elements (simulating the `Venn diagram`) or show only common elements and specific elements of all sets (simulating the `Flower plot`). 
4. Forth, clicking `Submit` button to get the network showing below.
5. Fifth, One initial layout would be first loaded. Then users are **suggested** to click `Preferred layout`  button (Fig \@ref(fig:Vennnetworkparameters) <font color="#FF0000">2</font>) to get a suitable layout mode after 1-2 minutes animation. This button would usually give the optimized layout.
6. Sixth, click the button (Fig \@ref(fig:Vennnetworkparameters) <font color="#FF0000">1</font>) to open the left tool bar to set more parameters. In our mind, the top 2 parameters for network layout is `springLength` and `nodeDistance` (Fig \@ref(fig:Vennnetworkparameters) <font color="#FF0000">7</font> and <font color="#FF0000">8</font>). Decreasing the numbers of either of these two parameters would make the network more aggregation. Increasing the numbers of either of these two parameters would make the network more diffuse.
7. In the end, the picture could be exported in `SVG` (`Export SVG` button) format for publication usages. 
 
<div class="figure" style="text-align: center">
<img src="image/Vennnetworkparameters.png" alt="List and label some parameters." width="100%" />
<p class="caption">(\#fig:Vennnetworkparameters)List and label some parameters.</p>
</div>

 
## Parameter description for network layout {#pdfnlreolayout}

More visual and layout parameters are allowed to adjust for more specific situations. 

1. A node would be selected and highlighted by *single clicking* on it. 
2. Then its attribute (label, label font-size, size, shape, border width, background color, nodes border color, label color) could be modified by clicking `Edit`-`Edit node` button (Fig \@ref(fig:Vennnetworkparameters) <font color="#FF0000">5</font>). 
3. New nodes and edges could be added by two buttons: `Add node` and `Add edge` (Fig \@ref(fig:Vennnetworkparameters) <font color="#FF0000">5</font>). 
4. Multiple nodes could be selected using one of the following three methods. 
   1. Hold down `CTRL` on the keyboard and click nodes to be selected; 
   2. Hold down each candidate node for more than one `second` to select multiple nodes; 
   3. Draw a cursor `rectangle` with the `Right Mouse button` hold down to select multiple nodes. 
5. When multiple nodes were selected, their attributes (label font-size, size, shape, border width, background color, nodes border color, label color) could be changed in batch using the `Edit X-nodes` (Fig \@ref(fig:Vennnetworkparameters) <font color="#FF0000">3</font>) button. 
6. Nodes and edges styles could also be changed on `nodes` and `edges` menus in the left-side tool-bar. 
7. The overall layout could be changed using `hieratical` and `physics` menus in the left-side toolbar (Fig \@ref(fig:Vennnetworkparameters) <font color="#FF0000">6,7,8,9,10</font>).
8. Additionally, clicking `Cyclization` button (Fig \@ref(fig:Vennnetworkparameters) <font color="#FF0000">4</font>) will make all selected nodes form a circle.  


## Color setting for Venn network {#vennnetworkcolorpallete}

Each set should have **one and only one** color assignment. Please see Fig \@ref(fig:ColorPicker) for operation showing.


## Venn network showing gene ontology/KEGG enrichment informations {#vennenrichment}

In microbiome analysis, interpretation function impacting of genes with differential abundance among experimental groups is one major goal. Normally genes are associated with multiple gene ontology (GO) annotations or pathways. The using of bar-plot or dot-plot to show GO analysis results though simple but may loss information of GO relationships such as the percentage of genes shared by different categories. Venn network could show both ontologies and their relationships through common connected genes. This is also suitable for transcriptome, genome and other omics-data analysis. 


<div class="figure" style="text-align: center">
<img src="image/Vennnetworkpathway2.gif" alt="Venn network showing gene onthlogy enrichment result." width="100%" />
<p class="caption">(\#fig:Vennnetworkpathwaygif)Venn network showing gene onthlogy enrichment result.</p>
</div>




<!--chapter:end:07.Vennnetwork.Rmd-->

# Venn estimate {#vennestimate}

Visualization would give qualitative but not quantitative estimation of sets similarity. However, it is usually needed to check the significance level of sets similarity to get more conclusive interpretations. We implied two commonly used methods: random sample test and Jaccard similarity test. 

* Random sample test using random sampling process for 1000 times to check if given overlaps are random or not. 
* Jaccard similarity test using the Jaccard similarity coefficient -- the ratio of intersection to union for statistical testing of similarity between binary data. 

<div class="figure" style="text-align: center">
<img src="image/Vennestimate.png" alt="Venn estimate." width="100%" />
<p class="caption">(\#fig:vennestimatepng)Venn estimate.</p>
</div>


<!--chapter:end:08.Vennestimate.Rmd-->

# Venn calculator {#venncalculator}

There are also scenes that we want to quickly select candidate elements like genes or OTUs for downstream analysis before generating plots. Venn calculator is designed to output elements for intersections for any number of sets in table format for further exploring. Besides, the output could be easily giving to Euler diagram to generate plots without computing again.  

<div class="figure" style="text-align: center">
<img src="image/Venncalculator.png" alt="Venn calculator." width="100%" />
<p class="caption">(\#fig:venncalculatorpng)Venn calculator.</p>
</div>


<!--chapter:end:09.Venncalculator.Rmd-->

# Function description

## Many-in-one venn diagram platform

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

<!--chapter:end:10.Introduction.Rmd-->

