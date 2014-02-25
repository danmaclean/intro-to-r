# Using knitR

`knitR` is an amazing R package for turning R code and text into pretty, easily read (by humans) documents.
Any of the R code in these documents gets executed and the result put into its place! So by using `knitR` you have 


## Installing `knitR`

R packages are easy to install in RStudio. Just click the `packages` tab in the bottom right pane, then `install packages`.
Type in the name of the package you want (in this case `knitR`), make sure that `install dependencies` is ticked and click `install`.

The whole process should be automatic! 


## Creating 

```coffee
 Title
========================================================

This is an R Markdown document. Markdown is a simple formatting syntax for authoring web pages (click the **Help** toolbar button for more details on using R Markdown).

When you click the **Knit HTML** button a web page will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r}
summary(cars)
```

You can also embed plots, for example:

```{r fig.width=7, fig.height=6}
plot(cars)
```


```
