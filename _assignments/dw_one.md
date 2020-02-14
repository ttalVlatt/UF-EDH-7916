---
layout: lesson
title: Assignment 3
subtitle: "EDH7916 | Spring 2020"
author: Benjamin Skinner
order: 3
category: assignment
links:
  pdf: dw_one_hw.pdf
output:
  md_document:
    variant: gfm
    preserve_yaml: true
---

***NOTE** This assignment needs to be completed by the start of the next
class. That means everything pushed to your remote GitHub repo before
class starts.*

*Remember, I encourage you to save your work, commit smaller changes,
and push to your remote GitHub repo often rather than wait until the
last minute.*

Using the `hsls_small.csv` data set and the online codebook, answer the
following questions. You **do not** need to save the final output as a
data file: just having the final result print to the console is fine.
For each question, I would like you to try to pipe all the commands
together. You can account for missing values by dropping them.

For each question, show your data work and then answer the question in a
short (1-2 sentence(s)) comment.

# Questions

1.  What is the average standardized math test score?

2.  What is the average standardized math test score by gender?

3.  In what year and month were the oldest students in the data set
    born? The youngest?

4.  Among those students who are under 185% of the federal poverty line
    in the base year of the survey, what is the median household income
    (give the category and what that category reprents).

5.  Of the students who earned a high school credential (diploma or
    GED), what percentage earned a GED or equivalency? How does this
    differ by region?

6.  What percentage of students ever attended a postsecondary
    institution by February 2016? Give the cross tabulations for:
    
      - family incomes less than or equal to $35,000 and greater than
        $35,000  
      - region
    
    This means you should have percentages for 8 groups: above/below
    $35k within each region.
    
    **HINT** You can `group_by()` on more than one group.