# MusicPreferences_project3
Hypothesis testing on the Young Peoples Survey from 2013 and the Pitchfork Data




______________________

# Music Preferences: Statistical Analysis
Statistacl Hypothesis Testing on the Young Peoples Survey from 2013 and the Pitchfork Music Dataset from 2017









## Analysing students that are an Only Child, and their happiness in life.
The Young Peoples Survey aggragated 1-5 scores from students in the UK on various topics, including life, music, and movie preferences.

Here, we want to make the following suggestion:

> Students that are an only child are less happy in life.




We will formulate and test our hypothesis as follows:


__________

_H0 =>  students that are an only child are **just as happy in life, if not more happy** than students that have children_

𝐻0 : The mean difference between treatment and control groups is zero. i.e.  M(experiment) = M(control)


_Ha =>  students that are an only child are **less happy in life**_

𝐻1: (1-tailed, <): The mean difference between experiment and control groups, is less than zero (negative).

__________

> _students that are an only child = **experimental group**_ | _students that have siblings = **control group**_

The two groups rated their "Happiness In Life".  We will use a **One-Tailed T-test** to analyze the statistical significance and accuracy of the equality (or the difference) in the _mean_ of their scores, with an Significance Level (Alpha) of 0.05, or 95% confidance.


First let's compare summary statistics on how students who are an only child rated their happiness in life vs. students who have siblings

**summary statistics comparison here**

To the naked eye, the statistics seem pretty similar, with means of 3.67 and 3.64 respectively, and we can observe a small difference in standard diviations of 0.91 and 0.83 respectively.



Let's visualize both samples' survey results on "Happiness In Life"

**visualizations comparison here**










## Music Genres vs. Movie Genres.

At this point, we want to test the suggestion that students with similar taste in music also have similar taste in movies.
We will focus on Metal & Hard Rock listeners and their affinity of Horror movies, and will use a **Chi-squared Independence test** to see how Horror movie score correlates to Metal & Hard Rock score


Our Hypothesis statement is as follows:

__________

_H0 =>  There is **NO** statistically significant relationship between Metal & Hard Rock scores and Horror movie scores._

_Ha =>  There is a statistically significant relationship between Metal & Hard Rock scores and Horror movie scores._

__________




First let's checkout summary statistics for both scores on Metal & Hard Rock, and Horror movies.

**summary statistics comparison here**

We can see that the means are slightly different both hovering right around the midpoint of the possible range of scores, and the standard deviations are pretty close as well at 1.37 and 1.40 respectively.


Next, let's use Pandas's _crosstab_ method to create the contingency table we'll be using for our Chi-squared test.  We can see the range of scores students gave on both Metal & Hard Rock, and Horror movies

**contingency table here**



Visualizing totals in the contingency table shows us score comparison at each level

**visualization here**








