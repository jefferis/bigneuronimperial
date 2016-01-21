# bigneuronimperial
Some analysis associated with the BigNeuron hackathon at Imperial College Jan 2016

This code is provided as [R Markdown documents](http://rmarkdown.rstudio.com).

## Install
You should install:

1. R from http://www.r-project.org/ (Latest R >3.2.1 recommended)
2. RStudio from http://www.rstudio.com.

Open the `binimperial2016.Rproj` file in Rstudio

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

## Use
1. Make sure that the `gold_trainingsubset_79_all` folder containing the swc files distributed on Wed is in *the same folder* as the `Rmd` files.
2. Press the "Knit" button for the `01-findswcs.Rmd` file
3. Repeat with `02-bigneuronqc.Rmd`
