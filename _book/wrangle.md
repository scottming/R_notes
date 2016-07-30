
# (PART) Wrangle {-}

# Introduction {#wrangle-intro}

In this part of the book, you'll learn about data wrangling, the art of getting your data into R in a useful form. Data wrangling encompasses three main pieces:

<img src="diagrams/data-science-wrangle.png" width="75%" style="display: block; margin: auto;" />

Data wrangling is import because it allows you to work with your own data. You'll learn:

*   In [tibbles], you'll learn about the variant of the data frame that we use
    in this book: the __tibble__.  You'll learn what makes them different
    from regular data frames, and how you can construct them "by hand".

*   In [data import], you'll learn the art of data import: how to get your 
    data off of disk and into R. We'll focus on plain-text rectangular
    formats, but will give you pointers to packages that help with other
    types of data.

*   In [tidy data], you'll learn about tidy data, a consistent way of storing
    your data that makes transformation, visualisation, and modelling easier.

Data wrangling also encompasses data transformation. You've already learned the basics, and now you'll learn new skills for specific types of data:

*   [Dates and times] will give you the key tools for working with 
    dates, and date-times.
    
*   [Strings] will introduce regular expressions, a powerful tool for
    manipulating strings.
    
*   [Relational data] will give you tools for working with multiple
    interrelated datasets.

