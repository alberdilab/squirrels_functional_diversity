# squirrels_functional_diversity
Data and code repository for the squirrels' functional diversity project

## Analysis procedures

The raw code used for data analysis is in the **Rmd** files stored in the root directory of this repository, while the bookdown-rendered webbook is available at:

[github.com/alberdilab/squirrels_functional_diversity](https://github.com/alberdilab/squirrels_functional_diversity.git)

While the webbook provides a user-friendly overview of the procedures, analyses can be directly reproduced using the Rmd documents. Note that the code chunks that require heavy computation have been tuned off using 'eval=FALSE'. To re-render the webbook, you can use the following code:

```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```

