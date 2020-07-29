# Age-dependent-Reference-Intervals (AdRI)

<img src="www/Logo.svg" width="225px" height="150px" align="right"/>

**Shiny App for calculating Age-dependent Reference Intervals**

This Shiny App was developed to create **A**ge-**d**ependent **R**eference **I**ntervals (**AdRI**) using different methods ([**LMS**](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/Generalized-additive-models-for-location,-scale-and-shape-(GAMLSS)), [**GAMLSS**](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/Generalized-additive-models-for-location,-scale-and-shape-(GAMLSS)), [**Window-Methods**](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/Window-Methods) and [**Regression**](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/Regression)), see the [Wiki](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki). 

**Overview:**
<img src="www/shiny.png" align="center"/>

**Window-Methods:**
<img src="www/shiny1.png" align="center"/>

**GAMLSS:**
<img src="www/shiny2.png" align="center"/>

## Installation

Download the Zip-File from this Shiny App and set the working direction to the order and run:

```bash
# Test if shiny is installed:
if("shiny" %in% rownames(installed.packages())){
  library(shiny)} else{
  install.packages("shiny")}
```

```bash
library(shiny)
runApp("app.R")
```
Or use the function ```runGitHub()``` from the package *shiny*:

```bash
library(shiny)
runGitHub("Age-dependent-Reference-Intervals", "SandraKla")
```

All required packages are downloaded when starting this app or read in if they already exist, see also the [Wiki](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/References) for the required packages.
