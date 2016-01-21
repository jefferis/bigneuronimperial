# bigneuronimperial
Some analysis associated with the BigNeuron hackathon at Imperial College Jan 2016

This code is provided as [R Markdown documents](http://rmarkdown.rstudio.com).

You should install:

1. R from http://www.r-project.org/ (Latest R >3.2.1 recommended)
2. RStudio from http://www.rstudio.com.

You will then need to install some R packages from inside R. One package containing
the Neuroanatomy ToolBox [nat](https://github.com/jefferis/nat) must be installed 
from github like so:

```r
# install devtools if required
if (!require("devtools")) install.packages("devtools")
# then install nat
devtools::install_github("jefferis/nat")
```

Other packages can be installed via the gui or command line:

```r
# also install some regular packages
install.packages(c("dplyr","knitr"))
```



Then open the Rproj file in Rstudio and press the "Knit" button
