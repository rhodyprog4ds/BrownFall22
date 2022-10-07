---
substitutions:
  accept_assignment: |
    [accept the assignment](https://classroom.github.com/a/LOFTSzu1)
  date : 2020-10-12
---
# Assignment 5: Constructing Datasets

{{accept_assignment}}
__Due: {{ date }}__

Eligible skills: (links to checklists)
- **first chance** construct [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#construct-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#construct-level2)
- (last assignment*) access [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#access-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#access-level2)
- (last assignment*) python [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#python-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#python-level2)
- (last assignment*) prepare [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#prepare-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#prepare-level2)
- summarize [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#summarize-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#summarize-level2)
- visualize [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#visualize-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#visualize-level2)

````{margin}
[let me know](https://forms.gle/L98QtzUYNQYHy7bK7) if listing the skills this way
is better for you
````
these skills will be eligible in future portfolio checks, but not future assignments



## Constructing Datasets

```{hint}
there is a [section of datasets ](dataparts) that are provided in multiple parts
```


````{margin}
```{admonition} If you get really stuck finding data
You could also demonstrate understanding of how merges work by converting a dataset
that is provided as a single table with redundant information into a number of
smaller tables and putting them *into* a database instead of taking data *from*
a database.
```

```{important}
I want you to learn and I need evidence that you have learned to give you credit
for it (first achievements then a semester grade).  It is not important to me
exactly **how* you provide me that evidence. We grade by looking at the
checklists for the corresponding skills.
```
````
Your goal is to programmatically construct three (3) ready to analyze datasets from multiple sources.

- Each dataset must combine at least 2 source tables(minimum 4 total source tables).
- At least one source table must come from a database or from web scraping.
- You should use at least two different joins(types of merges, or concat).


The notebook you submit should include:

- a motivating question for why you're combining the datasets in an introduction section
- code and description of how you built and prepared each dataset. For each step,  describe what you're about to do, the code with output, interpretation that leads into the next step.
- exploratory data analysis that shows why you built the data and confirms that is prepared enough to analyze.
- For one pair of tables, show how a different merge could answer a different question.

For construct only you can include very minimal EDA.


## Additional achievements

To earn additional achievements, you must do more cleaning and/or exploratory data analysis.


### Prepare level 2
To earn level 2 for prepare, you must, either on component table(s) or the final dataset apply and explain transformations that meet whatever components are unchecked on your prepare level 2 issue.

### Summarize and Visualize level 2

To earn level 2 for summarize and/or visualize, include additional analyses after building the datasets.

Check your issues for what components we have not seen from you.

### Python Level 2

Use pythonic naming conventions throughout, AND:

- Use pythonic loops and a list or dictionary OR
- use a list or dictionary comprehension

```{admonition} Thinking Ahead
Compare the level 2 skill definitions to level 3, how could you extend and adapt what you've done to meet level 3?
```
