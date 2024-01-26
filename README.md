# The Tidyverse, Sociology 412/512

This repository will be used to complete thre lab assignments associated with the Tidyverse section of the [Practical Data Analysis in Sociology using R](https://practical-data-analysis-r.netlify.app/). You can follow the instructions below to get started.

## Becoming Tidyversant

The `tidy_script.R` script conducts two statistical operations on the earnings dataset we used in class. Unfortunately, the person who wrote the code did not use piping but instead nested functions inside functions. Replace the original code with code that accomplishes the same goal but uses piping. 

Keep in mind that you don't need to know all of the details of how each function works to transform them into a piping approach. Just take out the first argument when you pipe (because it is now being piped) and keep all of the other arguments.

When you are done, be sure all changes have been committed and pushed to GitHub and start an issue where you summon me with @AaronGullickson to let me know you are done.

## Making Pretty Pictures

Use the `make_picture.R` script to make a figure using `ggplot2`. The figure should show a relationship and should also have the following elements:

1. Use either color or faceting (or both) to add another dimension to the relationship.
2. Use good labeling on the figure so that a reader can understand what each variable is and how it is measured.

When you are done, be sure all changes have been committed and pushed to GitHub and start an issue where you summon me with @AaronGullickson to let me know you are done.

## Writing in Quarto

Choose one of the following research questions:

1. What is the relationship between number of sports played and the number of friend nominations received in the `popularity` dataset?
2. What is the relationship between movie genre and movie runtime in the `movies` dataset?
3. What was the relationship between religion and presidential voting in 2016 from the `politics` dataset?

Based on your research question, use the `first_quarto_doc.qmd` file to write a brief report addressing this research question. Your document should include the following:

1. A brief introduction establishing the question and why it is an important question to address (i.e. why should we care). This does not need to be more than one paragraph.
2. An analysis section that include at least one well captioned and labeled figure and a written description of that figure and the overall relationship.
3. A brief conclusion that summarizes the results - this should not be more than one paragraph.

No citations are necessary in the document. 

When you are done, be sure all changes have been committed and pushed to GitHub and start an issue where you summon me with @AaronGullickson to let me know you are done.
