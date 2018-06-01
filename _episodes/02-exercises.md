---
title: "Exercises"
teaching: 20
exercises: 10
questions:
- "How to write an exercise?"

objectives:
- "Know how to write an exercise."

keypoints:
- "Exercises are written in a block `>`."

---


This is my first exercise.

> ## Exercise 1
> 
> List of elements you need inside an exercise
> to comply with the Carpentries style.
> > ## Solution
> >
> > Exercise solution are inside `>` block and each block must have 
> >
> > - one title
> > - exercise body
> > - solution to exercise
> {: .solution}
{: .challenge}

~~~
print("Hello SC!")
~~~
{: .language-python}

~~~
x <- 4
~~~
{: .language-r}

~~~
Hello SC instructors!
~~~
{: .output}

~~~
Missing element after comma.
~~~
{: .error}


```{r}
x <- 4
```

Code block inside an exercise

> ## Exercise 1
> 
> R code block inside exercise
> 
> > ## Solution
> >
> > ```{r}
> > x <- 1
> > y <- 1
> >  x + y
> > ```
> >
> {: .solution}
{: .challenge}
