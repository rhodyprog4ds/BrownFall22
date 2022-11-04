---
substitutions:
  accept_assignment: |
    [accept the assignment](https://classroom.github.com/a/PsrES62A)
  date : 2022-11-09
---
# Assignment 9

{{accept_assignment}}
__Due: {{ date }}__

##

Eligible skills: (links to checklists)
- **first chance** clustering [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#clustering-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#clustering-level2)
- evaluate [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#evaluate-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#evaluate-level2)
- python [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#python-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#python-level2)
- summarize [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#summarize-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#summarize-level2)
- visualize [1](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#visualize-level1) and [2](https://rhodyprog4ds.github.io/BrownFall22/syllabus/achievements.html#visualize-level2)



## Related notes

- [2022-10-31](../notes/2022-10-31)
- [2022-11-02](../notes/2022-11-02)
- [2022-11-04](../notes/2022-11-04)


## Instructions

Use the same dataset you used for assignment 7, unless there was a problem, or pick one of the recommended ones for that assignment if you did not complete assignment 7.

1. Describe what question you'd be asking in applying clustering to this dataset.
1. Apply Kmeans using the known, correct
number of clusters, $K$.
1.  Evaluate how well clustering worked on the data:

    - using a true clustering metric and
    - using visualization and
    - using a clustering metric that uses the ground truth labels
1. Include a discussion of your results that addresses the following:

    - describes what the clustering means
    - what the metrics show
    - Does this clustering work better or worse than expected based on the classification performance (if you didn't complete assignment 7, also apply a classifier)
1. Repeat your analysis using a 2 different numbers (1 higher, one lower) of clusters:

    - can you interpret the new clusters?
    - how to they relate to the original clusters? are they completely different, did one split?
    - is there a reasonable explanation for more clusters than there are classes in this dataset?
