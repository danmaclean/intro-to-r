Please try out these exercises from now until the break. Feel free to break if you're done with the exercise and don't flag down if you're stuck and need any help.

# Exercise for session 01

1. What is wrong with this code examples?

```
df <- data.frame(id = c("Jason","Paul","Mary", "Robert","Toby","Nina","Robin","James"), x = 1:10, y = rnorm(10))
```

2. Fix each of the following common data frame subsetting errors:

```
mtcars[mtcars$cyl = 4, ]
mtcars[-1:4, ]
mtcars[mtcars$cyl <= 5]
mtcars[mtcars$cyl == 4 | 6, ]
```

3. Why does mtcars[1:20] return a error? How does it differ from the similar mtcars[1:20, ]?


4. Load the `ggplot2` library. There should be a dataset called diamonds. You can verify that by typing in `data(diamonds)`

* How big is this dataset?
* Create a new `data.frame` called `small_diamonds` that only contains rows 1 through 9 and 19 through 23. You can do this in one or two steps.

5. Given a linear model

```
mod <- lm(mpg ~ wt, data = mtcars)
```

extract the residual degrees of freedom. 


----

