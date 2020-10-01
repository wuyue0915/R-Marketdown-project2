# R-Marketdown-project2
data("presidents")
library(plotly)
## Loading required package: ggplot2
## 
## Attaching package: 'plotly'
## The following object is masked from 'package:ggplot2':
## 
##     last_plot
## The following object is masked from 'package:stats':
## 
##     filter
## The following object is masked from 'package:graphics':
## 
##     layout
#The presidents dataset is the (approximately) quarterly approval rating for the President of the United States from the first quarter of 1945 to the last quarter of 1974.
plot_ly(x=time(presidents), y=presidents, type="bar")
## Warning: Ignoring 6 observations
1950
1955
1960
1965
1970
0
10
20
30
40
50
60
70
80
90
#knitr::opts_chunk$set(echo = TRUE)
