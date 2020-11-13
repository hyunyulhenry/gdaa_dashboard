# Global Dynamic Asset Allocation by Henry
shiny for Global Dynamic Asset Allocation 

To run the project either fork/download the files and run the **app.R**-file, or in R run
```{r}
shiny::runGitHub('GDAA_dashboard', 'hyunyulhenry')
```
In order to run the project properly, you need to have the following packages installed.

Required package
```{r}
library(DT)
library(quadprog)
library(quantmod)
library(PerformanceAnalytics)
library(knitr)
library(kableExtra)
library(magrittr)
library(shinyWidgets)
library(lubridate)
library(stringr)
library(dplyr)
library(tidyr)
library(tibble)
library(shiny)
library(plotly)
library(shinydashboard)
library(shinycssloaders)
library(forcats)
```
