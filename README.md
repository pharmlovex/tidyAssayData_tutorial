
# tidyAssayData Tutorial

## Background
Following the extraction of gene expression count data for either DNA microarray or RNA sequence analysis from the database or as an output of the NGS pipeline, it is required to perform a transformation task that enables us to have clean column names that represent the samples of the study. The count data usually present with the sample identified that is stacked with some other information that will not be required in the analysis. Therefore we are continuously faced with the daunting task of transforming the column name to a tidy one.

## The tidyAssayData Package

With the aim to make the transformation of the count data column names easy, I present `transformMatrixcol()` function from the TidyAssayData package. This function will be useful in the transformation phase of a typical gene expression count data ETL pipeline.


## Installation

Install tidyAssayData with devtools

```r
  library(devtools)
  devtools::install_github("pharmlovex/tidyAssayData")
```
    
## Badges


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)



## License

[MIT](https://choosealicense.com/licenses/mit/)


## Authors

- [@pharmlovex](https://github.com/pharmlovex/tidyAssayData_tutorial)


## 🚀 About Me
I'm a bioinformatics developer...

