---
substitutions:
  accept_assignment: |
    [accept the assignment](https://classroom.github.com/a/-7TUoBDE)
  date : 2022-10-06 6:59pm
---
# Assignment 4: Cleaning Data

__Due: {{ date }}__

{{ accept_assignment }}

Eligible skills:
- prepare
- summarize
- visualize
- access


## Check the Datasets you have worked with already

In the datasets you have used in your past assignments identify at least one
thing you could not do because the data was not in an appropriate format.

Apply one fix and show one summary statistic or plot to show that it works.


Some examples:
- a column that was a list
- missing values
- a column that was continuous, but more interesting as a categorical
- too many header rows

```{amdonition} Think Ahead

_this box is not required, but ideas for portfolio_
cleaning a dataset to make it able to answer questions that were not possible could satisfy the level 3 prepare requirements.
```


## Clean example datasets

There are notebooks in the template that have instructions for how to work with each dataset, including how to load it and what high level cleaning should be done.  Your job is to execute.

To earn prepare level 2, clean one dataset and do just enough exploratory data analysis to show that the data is usable (eg 1 stat and/or plot).

To *also* earn python level 2: clean the CS degrees dataset (use a function or lambda AND loop or comprehension)

To *also* earn access level 2: clean the airline data (to get data in a second file type).

To *also* earn summarize and/or visualize level 2: add extra exploratory data analyses of your cleaned dataset meeting the criteria from the checklist (eg follow a3 checklists).


This means that if you want to earn prepare, python, and access, you will need to clean two datasets.

```{hint}
renaming things is often done well with a dictionary comprehension or lambda.
```

## Study Cleaned Datasets

Read example data cleaning notes or scripts. To do this find at least one dataset for which the messy version, clean version, and a script or notes about how it was cleaned are available, answer the following questions in a markdown file or additional notebook in your repository. (some example datasets and one is in the notes are added to the course website)

1. What are 3 common problems to look for in a dataset?
1. For a specific of your choice give an example of a question that would require making different choices than were made. Include a bit about the data, what was done, the question, what would need to be done instead and justification.
1. Explain in your own words, with a concrete example, how domain expertise can help you when cleaning data. Use either a made up example or one that you read about.
