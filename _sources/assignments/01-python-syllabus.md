---
substitutions:
  accept_assignment: |
    [accepting the assignment](https://classroom.github.com/a/D_SYfCpt)
  date : 2020-09-11
---
# Portfolio Setup, Data Science, and Python

__Due: {{ date }}__

## Objective & Evaluation

This assignment is an opportunity to earn level 1 achievements for the `process` and `python` and confirm that you have all of your tools setup, including your portfolio.

```{note}
Typically, assignments are for level 2, but this week we did setup stuff in class instead of a comprehension checks.  Also, the data science process takes a bit more time to really familiar with, it's hard to explain the modeling step for example, without knowing how to build models.

You will be able to earn python level 2 starting in assignment 2 and process level 2 starting with assignment 6.
```  


## To Do

````{margin}
```{note}
If you get stuck on any of this after accepting the assignment and creating a repository, you can create an issue on your repository, describing what you're stuck on and tag us: @rhodypro4dg/{{ ghinstructors }}

To do this click Issues at the top, the green "New Issue" button and then type away.
```

````

````{margin}
```{important}
If you have trouble, check the GitHub FAQ on the left before e-mailing
```

````

Your task is to:
1. Install required software from the Tools & Resource page
1. Create your portfolio, by {{ accept_assignment }}
1. Learn about your portfolio from the README file on your repository.
1. edit `_config.yml` to set your name as author and (optionally) change the logo image
1. Fill in `about/index.md` with information about yourself(not evaluated, but useful) and your own definition of data science (graded for **level 1 process**)
1. Add a Jupyter notebook called `grading.ipynb` to the `about` folder and write a function that computes a grade for this course, with the following docstring. Include:

    -  a Markdown cell with a heading
    - your function called `compute_grade`
    - three calls to your function that verify it returns the correct value for different number of badges that produce at three different letter grades.
    - a basic function that uses conditionals in python will earn **level 1 python**
1. Add the line `  - file: about/grading` in your `_toc.yml` file.



```{important}
remember to add, commit, and push your changes so we can see them
````

```
    '''
    Computes a grade for CSC/DSP310 from numbers of achievements at each level

    Parameters:
    ------------
    num_level1 : int
      number of level 1 achievements earned
    num_level2 : int
      number of level 2 achievements earned
    num_level3 : int
      number of level 3 achievements earned

    Returns:
    --------
    letter_grade : string
      letter grade with possible modifier (+/-)
    '''
```

## Tips

Here are some sample tests you could run to confirm that your function works correctly:
````{margin}
```{warning}
your function can have a different name than `compute_grade`, but make sure it's your function name, with those parameter values in your tests.
```


```{note}
when the value of the expression after `assert` is `True`, it will look like nothing happened. `assert` is used for testing
```
````

```
assert compute_grade(15,15,15) == 'A'

assert compute_grade(15,15,13) == 'A-'

assert compute_grade(15,14,14) == 'B-'

assert compute_grade(14,14,14) == 'C-'

assert compute_grade(4,3,1) == 'D'

assert compute_grade(15,15,6) =='B+'
```


## Submission Instructions

### If using GitHub in the browser only
Create a Jupyter Notebook with your function in a portfolio folder on your computer
where you will save all of your work for the portfolio.  Then upload it to GitHub.

### If using git offline
Create a Jupyter Notebook with your function in your portfolio folder, then add,
commit, and push the changes.

In your browser, view the `gh-pages` branch to see your compiled submission, as `portfolio.pdf` or by viewing your website.

There will be a pull request on your repository that is made by GitHub classroom, [request a review](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review) from @rhodypro4dg/{{ ghinstructors }}.


## Thinking Ahead

```{note}
Thinking Ahead is an optional section you can do to get a head start on the next level achievements
```

Add a markdown file to your portfolio called `ideas.md` and start answering some of the following questions:

1. Given what you know about the Data Science Process, which steps do you think you will like most? least?
1. What steps will use the most domain knowledge?
1. What applications of data science do you have domain knowledge for? 

````{margin}
```{note}
to earn **level 2 python** use pythonic code to write a loop that tests your function's correctness, by iterating over a list or dictionary. You will have many chances to earn level 2 achievement in python so this step is optional.
```
````

````{margin}
```{note}
to earn **level 2 python** use pythonic code to write a loop that tests your function's correctness, by iterating over a list or dictionary. You will have many chances to earn level 2 achievement in python so this step is optional.
```
````
<!-- ## Solutions

One solution is added to the [Detailed Mechanics](grade:calculation) part of the Grading section of the syllabus. -->
