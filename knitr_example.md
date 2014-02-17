## An example knitr/R Markdown document

This is a very simple and introductory example about producing a full _html_ report using R Markdown and package knitr. _Italics_ and **bold** can be used as well.

### Introduction

The syntax is very obvious. Heads and identation can be achieved just controling the number of "#" caracters.

R codes need to be within chunks. Every chunk starts and ends with the syntax indicated below. It is recommended to given each chunk its own name (they cannot have the same name), but this is optional. There is a bottom to insert chunks (see the green icon on the right top), in case you are lazy.

There are a number of options that can be used on chunks. This are out of the scope of this course. For now, just notice that you can use this document to take notes about what you are learning.


```r
10
```

```
## [1] 10
```


To run the code within a given chunk, just hit CRTL+ENTER.

Operations:


```r
1 + 3
```

```
## [1] 4
```


Objects:


```r
a <- 100
```


You can also use inline comments. For example, the object _a_ has value 100.

Equations: you don't want to type this in Word, unless you don't value your time... Here, the syntax is also easy to understand. For example, a linear model for regression is $y_{i}=\mu+\beta x_{i}+e_{i}$.

### R and package versions used

It is a good idea to include this function in the end of your reports. This is important to achieve _**reproducibility**_.


```r
sessionInfo()
```

```
## R version 2.15.2 (2012-10-26)
## Platform: x86_64-pc-linux-gnu (64-bit)
## 
## locale:
##  [1] LC_CTYPE=pt_BR.UTF-8       LC_NUMERIC=C              
##  [3] LC_TIME=pt_BR.UTF-8        LC_COLLATE=pt_BR.UTF-8    
##  [5] LC_MONETARY=pt_BR.UTF-8    LC_MESSAGES=pt_BR.UTF-8   
##  [7] LC_PAPER=C                 LC_NAME=C                 
##  [9] LC_ADDRESS=C               LC_TELEPHONE=C            
## [11] LC_MEASUREMENT=pt_BR.UTF-8 LC_IDENTIFICATION=C       
## 
## attached base packages:
## [1] graphics  grDevices utils     datasets  stats     methods   base     
## 
## other attached packages:
## [1] RColorBrewer_1.0-5 knitr_1.5          ggplot2_0.9.3.1   
## 
## loaded via a namespace (and not attached):
##  [1] colorspace_1.2-4 dichromat_2.0-0  digest_0.6.4     evaluate_0.5.1  
##  [5] formatR_0.10     grid_2.15.2      gtable_0.1.2     labeling_0.2    
##  [9] MASS_7.3-23      munsell_0.4.2    plyr_1.8         proto_0.3-10    
## [13] reshape2_1.2.2   scales_0.2.3     stringr_0.6.2    tools_2.15.2
```

