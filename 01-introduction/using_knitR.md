# Using knitR

`knitR` is an amazing R package for turning R code and text into pretty, easily read (by humans) documents.
Any of the R code in these documents gets executed and the result put into its place! So by using `knitR` you have 


## Installing `knitR`

R packages are easy to install in RStudio. Just click the `packages` tab in the bottom right pane, then `install packages`.
Type in the name of the package you want (in this case `knitR`), make sure that `install dependencies` is ticked and click `install`.

The whole process should be automatic! 


## Creating documents with `knitR`

`knitR` takes in a Markdown format file with embedded R code and creates a new, pretty, interpreted document. The only rule is that the R code must be within the three back-tick symbols and the `{r}`. For example,


```coffee

Here is some intro text followed by a block of R code... 

    ```{r}
    x <- runif(10)
    plot(x)
    ```
    ... when the R code is run, the results are inserted in place into the document.

```

To create a new document to be `knitR`-ed, go to `File --> New File --> R Markdown`. A new document should appear in the top-left pane. It contains some example text, it should look like this.


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

You have some blocks of R code a simple document title and some explanatory text all in Markdown format. To turn this into the final document and run the code, simply hit the `knit HTML` button. 

The final output is best saved into the working directory. You will see a save box the first time you want to `knit` the document.

## Writing in Markdown

Markdown is a straightforward way of formatting text, that `knitR` can make pretty for you. You can make headings, links, lists, sub-headings all very easily. Markdown doesn't get in the way of your writing process and looks sensible in text. Here is a partial list of the things you can do with Markdown that `knitR` will interpret. Try pasting the text into your `knitR` document and reknitting it to see how `knitR` interprets the Markdown.


```coffee
   A First Level Header
   ====================
   
   A Second Level Header
   ---------------------

   Now is the time for all good men to come to
   the aid of their country. This is just a
   regular paragraph.

   The quick brown fox jumped over the lazy
   dogs back.

   ### Header 3

  > This is a blockquote.
  > 
  > This is the second paragraph in the blockquote.
  >
  > ## This is an H2 in a blockquote
  
  This is a list:
  
  +   Candy.
  +   Gum.
  +   Booze.
  
  This is a numbered list
  
  1.  Red
  2.  Green
  3.  Blue
  
```


## `knitR forms the basis of 
