## Welcome to the GitHub page for [Mineralogy Analysis with TIMA](https://hangdeng.github.io/TIMA_for_Sedimentology/)

TIMA stands for TESCAN Integrated Mineral Analyzer (TIMA), a revolutionary instrument used for minerals and materials analysis. Because software designed for processing raw data from TIMA is not specifically designed for data analysis in sedimentology/stratigraphy, this repository is created in order to guide data processing, data analysis with TIMA for sedimentology/stratigraphy. The TIMA used in collecting data is from [Automated Minerology Laboratory](https://geology.mines.edu/laboratories/automated-mineralogy-laboratory/).

### 0 Objectives
- Automatically describe the tecture of sedimentary rocks in thin sections (e.g. grain size, roundness, sphericity, sorting, textural maturity, etc.)
- Classify sedimentary rocks in thin sections with ternary diagrams

### 1 Introduction

#### 1.1 Minerals and mineral groups

The TESCAN software requires an understanding of rock-forming minerals and their groups (correctly group minerals into brackets before starting data collection).

Rock-forming Minerals: The common rock-forming minerals include quartz, feldspars, pyroxenes, amphiboles, micas, clays, olivine, calcite, and dolomite. [[1]](#1).

<p align="left">
  <img src="https://github.com/hangdeng/TIMA_for_Sedimentology/blob/master/ref_images/most_abundant_minerals_earth_crust.JPG" width="420">
 </p>

Therefore, we put together information being used for grouping minerals. Mineral groups are arranged alphabetically.

- The **pyroxene/amphibole** group: Augite, diopside, jadeite and spodumene, etc.([[2]](#2))
- The **aragonite** group: aragonite, cerussite, strontianite, witherite ([[3]](#3))
- The **biotite mica** group: annite, phlogopite, siderophyllite, fluorophlogopite, fluorannite, eastonite, and many others
- The **blodite** group: blodite, leonite, anapaite, schertelite, manganoblodite, cobaltoblodite, changoite ([[(4]](#4))
- The **calcite** group: calcite, smithsonite, siderite, gaspeite, magnesite, otavite, rhodochrosite, sphaerocobaltite ([[5]](#5),[[6]](#6))
- The **clay minerals** group: kaolinite, halloysite, lizardite, chrysotile (kaolin-serpentine); pyrophyllite-talc; illite, glauconite, celadonite (mica); vermiculite; montmorillonite, nontronite, saponite (smectite); sudoite, clinochlore, chamosite (clorite); sepiolite-palygorskite ([[(7]](#7))
- The **dolomite** group: ankerite, dolomite, kutnohorite, minrecordite, norsethite ([[(8]](#8))
- The **epidote** group: clinozoisite, epidote, hancockite, mukhinite, niigataite, piemontite, tweddillite ([[(9]](#9))
- The **feldspar** group: albite, amazonite, andesine, anorthite, anorthoclase, banalsite, buddingtonite, bytownite, celsian, dmisteinbergite, ferrisanidine, filatovite, hexacelsian, hyalophane, kokchetavite, kumdykolite, labradorite, microcline, oligoclase, orthoclase, paracelsian, reedmergnerite, rubicline, sanidine, slawsonite, stronalsite, stronalsite, sunstone, svyatoslavite ([[(10]](#10))
- The **garnet** group: almandine, pyrope, spessartine, andradite, grossular, uvarovite ([[(11]](#11))
- The **halite** group: carobbiite, griceite, halite, sylvite, villiaumite ([[(12]](#12))
- The **olivine** group: forsterite, fayalte, monticellite, kirschsteinite, tephroite
- The **pyroxenes** group: augite, diopside, jadeite, and spodumene.
- The **pyrite** group: sperrylite, pyrite, krut'aite, etc. ([[13]](#13))

**Note**: Use Venture Basin files as examples.

[Link to the Jupyter Notebook](https://github.com/hangdeng/TIMA_for_Sedimentology/blob/master/TIMA_Scratch.ipynb)

### 2 Associated Minerals for Each Mineral
- Find out the most associated mineral for each mineral

### 3 Ternary Diagram for Mineral Distribution
- Plot ternary diagram of mineral composition for thin section
TODO:
Improve:
Density contour on ternary 
label each point
### 4 Image Processing for TIMA
- Object detection and roundness calculation

TODO:
- define function if neccessary



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/hangdeng/TIMA_for_Sedimentology/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

## References
<a id="1">[1]</a> 
King, H. W. 
[The Common Rock-Forming Minerals. 
Geology.com](https://geology.com/minerals/rock-forming-minerals/)

<a id="2">[2]</a> 
[Pyroxene/amphibole group, mindat.org](https://geology.com/minerals/pyroxene.shtml)

<a id="3">[3]</a> 
[Aragonite group, mindat.org](https://www.mindat.org/min-29269.html)

<a id="4">[4]</a> 
[Blodite group, Wikipedia](https://en.wikipedia.org/wiki/Blodite_group)

<a id="5">[5]</a> 
[Calcite Group, mindata.org](https://www.mindat.org/min-29161.html)

<a id="6">[6]</a> 
[Calcite Group, galleries.com](http://www.galleries.com/minerals/carbonat/calcite.htm)

<a id="7">[7]</a> 
[Clay Mienrals Group, britannica.com](https://www.britannica.com/science/clay-mineral)

<a id="8">[8]</a> 
[Dolomite Group, mindata.org](https://www.mindat.org/min-29288.html)

<a id="9">[9]</a> 
[Epidote Group, mindata.org](https://www.mindat.org/min-46234.html)

<a id="10">[10]</a> 
[Feldspar Group, mindata.org](https://www.mindat.org/min-1624.html)

<a id="11">[11]</a> 
[Garnet Group, mindata.org](https://www.mindat.org/min-10272.html)

<a id="12">[12]</a> 
[Halite Group, mindata.org](https://www.mindat.org/min-47992.html)

<a id="13">[13]</a> 
[Pyrite Group, mindata.org](https://www.mindat.org/min-9258.html)
