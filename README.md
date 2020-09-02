# Age-dependent-Reference-Intervals (AdRI)

<img src="www/Logo.svg" width="225px" height="150px" align="right"/>

**Shiny App for calculating Age-dependent Reference Intervals!**

This Shiny App was developed to create **A**ge-**d**ependent **R**eference **I**ntervals (**AdRI**) using different methods ([**LMS**](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/Generalized-additive-models-for-location,-scale-and-shape-(GAMLSS)#lms), [**GAMLSS**](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/Generalized-additive-models-for-location,-scale-and-shape-(GAMLSS)), [**Window-Methods**](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/Window-Methods) and [**Regression**](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/Regression)) (see the [Wiki](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki)). 

## Installation

Download the Zip-File from this Shiny App, set your working direction to this path and run:

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

All required packages are downloaded when starting this app or imported if they already exist. For more information about the required packages use the [Wiki](https://github.com/SandraKla/Age-dependent-Reference-Intervals/wiki/References).


## Example with the Creatinine data from the CALIPER study

**Overview:**
Dataset:
<img src="www/shiny.png" align="center"/>
Dataset with modified Tukey-method coupled to a Decision Tree:
<img src="www/shiny_tukey.png" align="center"/>
Gender distribution:
<img src="www/shiny1.png" align="center"/>

**Window-Methods:**
<img src="www/shiny2.png" align="center"/>
**Decision Tree for for age partitioning:**
<img src="www/shiny3.png" align="center"/>

**Regressions:**
<img src="www/shiny4.png" align="center"/>

**GAMLSS:**
<img src="www/shiny5.png" align="center"/>
**Comparison of GAMLSS:**
<img src="www/shiny6.png" align="center"/>

**Make discrete models from the GAMLSS-models:**
<img src="www/shiny7.png" align="center"/>

**Residuals from the GAMLSS-models:**
<img src="www/shiny8.png" align="center"/>