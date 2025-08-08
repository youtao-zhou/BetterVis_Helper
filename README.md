# BetterVis Visualization Tutorial and Parameter Explanation

Youtao Zhou, Zikai Lin, Hengrui Liang



## Welcome to BetterVis



![GitBook](https://img.shields.io/badge/GitBook-%23000000.svg?style=for-the-badge&logo=gitbook&logoColor=white)[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)


 
<p align="center">
  <img src="https://raw.githubusercontent.com/youtao-zhou/BetterVis_Helper/main/Figure/Logo6.png" width="300"/>
</p>




## Install of BetterVis

Before installing BetterVis, please check that your R version meets the requirements.

**We require R version 4.4 or higher and ggplot2 package version 3.5.0 or higher**



BetterVis has not been uploaded to CRAN yet. If users need to download BetterVis, they should install it via Github. Before this, installing devtools is mandatory.

```R
install.packages('devtools)
devtools::install_github("youtao-zhou/BetterVis")
```



Some required packages, including jjPlot, linkET, ComplexHeatmap, ggsankey, and vegan, may not be installed automatically and could have dependency issues. Please use the following commands to install them

```R
devtools::install_github("junjunlab/jjPlot")
devtools::install_github("Hy4m/linkET", force = TRUE)
devtools::install_github("jokergoo/ComplexHeatmap")
devtools::install_github("davidsjoberg/ggsankey")
install.packages("vegan")
```

