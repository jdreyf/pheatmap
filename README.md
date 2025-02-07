pheatmap
========

A package for drawing pretty heatmaps in R. The ordinary heatmap function in R has several drawbacks when it comes to producing publication quality heatmaps. It is hard to produce pictures with consistent text, cell and overall sizes and shapes. The function pheatmap tries to alleviate the problems by offering more fine grained control over heatmap dimensions and appearance.

## Installation

You can install this repo using `remotes`
```S
library(remotes)
remotes::install_github("jdreyf/pheatmap")
```

## Features
More important features of pheatmap include:
 * ability to directly control the size of the cells, text, etc
 * automatic generation of legends
 * row and column annotations
 * ability to post-edit the heatmap using `grid` graphics tools
 * easy way to separate clusters visually using spacers
 * reasonable defaults
 * ...

Many of these features are on display in the next figure

![pheatmap_example](https://cloud.githubusercontent.com/assets/181403/12646618/30b70a76-c59f-11e5-8fdb-aab0fda50726.png)
