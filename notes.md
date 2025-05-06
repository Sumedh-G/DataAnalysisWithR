### Important links

-> Basics of the R Programming Language
[Programming Syntax and Semantics](https://www.youtube.com/watch?v=QJCt9GNCD1M&list=PLEDdkzD9hUd7W0T7la6JNSfxtGjAd2bm7)
[Reproducible Research in R](https://ecorepsci.github.io/reproducible-science/index.html)
[The Art of Data Analysis](https://students.aiu.edu/submissions/profiles/resources/onlineBook/D9s8s7_Art_of_Data_Analysis_Statistics.pdf)


1. How do we do data science, ie how do we deal with large amounts of data?

```
                      |---------------------|
    import -> tidy -> |  transform <- model | -> Communicate
                      |  |-> visualise -|   |
                      |---------------------|
```

One paradigm used to develop in R(which is pretty famous) is tidyverse

It consists of the following core libraries
```
dplyr
readr
forcats
ggplot2
lubridate
purrr
stringr
tibble
tidyr
```
but there are more!


a) reading the data in R is done by using the "readr" package
b) storing the imported data is done using structures called "tibbles", (data-frame equivalents in R)
* Almost all functions in R take in a tibble as an input, and output a modified version of it as output
c) the "dplyr" package allows for data cleaning
d) the "purrr" library allows us to use functions like map() on "list-columns", which are basically dicts of rows
e) the "tidyr" library allows us to change the shape of our data
f) finally, "ggplot2" is a library that allows us to visualise data
* working with layers is very helpful %>% or |>

R Markdown is a simple way to create reports that use code to visualise stuff!
Shiny is something to look into!


```
"any conclusions you make are only as good as the data you use to make them."
```

##### What Question are we trying to answer?

a) Working more hours lead to smoking habits?
b) Does where you live matter?
c) Who voted who?
