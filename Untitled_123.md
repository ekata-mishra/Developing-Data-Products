---
title       : Developing Data Products
author      : Ekata Rajmohan Mishra
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## US Rig Count Dataset Explorer  

This Shiny App is for searching and visulizating US Rig Count information from year 1987 to 2015. The total number of records is 333, seperated across Onshore, Offshore, Crude Oil and Natura Gas Rigs.
The dataset is from U.S. Energy Information Administration (http://www.eia.gov/dnav/ng/NG_ENR_DRILL_S1_M.htm).  

Data Source: http://www.eia.gov/dnav/ng/NG_ENR_DRILL_S1_M.htm  
Date updated: 01/05/2016
  
About author: [Ekata Mishra](https://www.linkedin.com/in/ekata-mishra-09821053/)

Link to Source Files: [GitHub](https://github.com/ekata-mishra/Developing-Data-Products)

--- .class #id 

# The Data for the Rig Counts

```
## 
## Attaching package: 'data.table'
```

```
## The following object is masked from 'package:reshape':
## 
##     melt
```

```
## The following objects are masked from 'package:dplyr':
## 
##     between, first, last
```

```
## Error in setnames(data, "Total.Rigs", "TotalNumberofRigs"): x is not a data.table or data.frame
```

```
## Error in setnames(data, "Crude.Oil", "CrudeOil"): x is not a data.table or data.frame
```

```
## Error in setnames(data, "Natural.Gas", "NaturalGas"): x is not a data.table or data.frame
```

```
## Error in data$Date: object of type 'closure' is not subsettable
```

```
## Error in setnames(data, "Year", "Year"): x is not a data.table or data.frame
```

```
## Error in data[, c("Date", "Year", "Onshore", "Offshore", "CrudeOil", "NaturalGas")]: object of type 'closure' is not subsettable
```

```
##                                                                      
## 1 function (..., list = character(), package = NULL, lib.loc = NULL, 
## 2     verbose = getOption("verbose"), envir = .GlobalEnv)            
## 3 {                                                                  
## 4     fileExt <- function(x) {                                       
## 5         db <- grepl("\\\\.[^.]+\\\\.(gz|bz2|xz)$", x)              
## 6         ans <- sub(".*\\\\.", "", x)
```
# Melted Flat Dataset


```
## Error in head(flatdata): object 'flatdata' not found
```

--- .class #id 

## Total Number of Rig Counts in the US for each type


```
Error in eval(i, data, env): object 'flatdata' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

--- .class #id 

## Total Number of Rig Counts in the US


```
Error in eval(i, data, env): invalid 'envir' argument of type 'closure'
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```

```
Error in eval(expr, envir, enclos): object 'RigsByYear' not found
```


