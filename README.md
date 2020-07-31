# Standard Statistical Distributions-
### Python Package for Binomial and Gaussian Distribution

This is a python package part of the Udacity's AWS Machine Learning Course.
We've created a python package taking into account two probability distribution, i.e. Binomial and Gaussian Distribution.
Here is a brief introduction of the above-mentioned distributions.

### Binomial Distribution

A binomial distribution can be thought of as simply the probability of a SUCCESS or FAILURE outcome in an experiment or survey that is repeated multiple times. The binomial is a type of distribution that has two possible outcomes (the prefix "[bi](http://membean.com/wrotds/bi-twice)" means two, or twice). For example, a coin toss has only two possible outcomes: heads or tails and taking a test could have two possible outcomes: pass or fail.

[![what is a binomial distribution](https://www.statisticshowto.com/wp-content/uploads/2013/07/Binomial_distribution_pmf.svg_-150x150.png)](https://www.statisticshowto.com/wp-content/uploads/2013/07/Binomial_distribution_pmf.svg_.png)

A Binomial Distribution shows either (S)uccess or (F)ailure.

-   The first variable in the binomial formula, n, stands for the number of times the experiment runs.
-   The second variable, p, represents the probability of one specific outcome.

For example, let's suppose you wanted to know the probability of getting a 1 on a die roll. if you were to roll a die 20 times, the probability of rolling a one on any throw is 1/6. Roll twenty times and you have a binomial distribution of (n=20, p=1/6). SUCCESS would be "roll a one" and FAILURE would be "roll anything else." If the outcome in question was the probability of the die landing on an even number, the binomial distribution would then become (n=20, p=1/2). That's because your probability of throwing an even number is one half.

Criteria
--------

Binomial distributions must also meet the following three criteria:

1.  The number of observations or trials is fixed. In other words, you can only figure out the [probability](https://www.statisticshowto.com/probability-and-statistics/probability-main-index/) of something happening if you do it a certain number of times. This is common sense---if you toss a coin once, your probability of getting a tails is 50%. If you toss a coin a 20 times, your probability of getting a tails is very, very close to 100%.
2.  Each observation or trial is [independent](https://www.statisticshowto.com/probability-and-statistics/dependent-events-independent/#or). In other words, none of your trials have an effect on the probability of the next trial.
3.  The probability of success (tails, heads, fail or pass) is exactly the same from one trial to another.

### Gaussian Distribution (AKA Normal Distribution)

A [normal distribution](https://www.statisticshowto.com/probability-and-statistics/normal-distributions/), sometimes called the bell curve, is a distribution that occurs naturally in many situations. For example, the bell curve is seen in tests like the SAT and GRE. The bulk of students will score the [average ](https://calculushowto.com/average-value-of-a-function/#def), while smaller numbers of students will score a B or D. An even smaller percentage of students score an F or an A. This creates a distribution that resembles a bell (hence the nickname). The bell curve is symmetrical. Half of the data will fall to the left of the [mean](https://www.statisticshowto.com/probability-and-statistics/statistics-definitions/mean-median-mode/#mean); half will fall to the right.
Many groups follow this type of pattern. That's why it's widely used in business, statistics and in government bodies like the [FDA](https://www.fda.gov/default.htm):

-   Heights of people.
-   Measurement errors.
-   Blood pressure.
-   Points on a test.
-   IQ scores.
-   Salaries.

The [empirical rule](https://www.statisticshowto.com/empirical-rule-2/) tells you what percentage of your data falls within a certain number of [standard deviations](https://www.statisticshowto.com/probability-and-statistics/standard-deviation/) from the [mean](https://www.statisticshowto.com/mean):
- 68% of the data falls within one [standard deviation](https://www.statisticshowto.com/probability-and-statistics/standard-deviation/) of the [mean](https://www.statisticshowto.com/mean).
- 95% of the data falls within two [standard deviations](https://www.statisticshowto.com/probability-and-statistics/standard-deviation/) of the [mean](https://www.statisticshowto.com/mean).
- 99.7% of the data falls within three [standard deviations](https://www.statisticshowto.com/probability-and-statistics/standard-deviation/) of the [mean](https://www.statisticshowto.com/mean).
[![](https://www.statisticshowto.com/wp-content/uploads/2013/02/standard-normal-distribution.jpg)](https://www.statisticshowto.com/wp-content/uploads/2013/02/standard-normal-distribution.jpg)

The standard deviation controls the spread of the distribution. A smaller standard deviation indicates that the data is tightly clustered around the [mean](https://www.statisticshowto.com/mean); the normal distribution will be taller. A larger standard deviation indicates that the data is spread out around the [mean](https://www.statisticshowto.com/mean); the normal distribution will be flatter and wider.

Properties of a normal distribution
-----------------------------------

-   The [mean, mode and median](https://www.statisticshowto.com/probability-and-statistics/statistics-definitions/mean-median-mode/) are all equal.
-   The curve is symmetric at the center (i.e. around the mean, μ).
-   Exactly half of the values are to the left of center and exactly half the values are to the right.
-   The total area under the curve is 1.

The Standard Normal Model
A standard normal model is a normal distribution with a mean of 0 and a standard deviation of 1.


Source -
- [Stephanie Glen](https://www.statisticshowto.com/contact/). "Binomial Distribution: Formula, What it is and How to use it" From [StatisticsHowTo.com](https://www.statisticshowto.com/)
- [Stephanie Glen](https://www.statisticshowto.com/contact/). "Normal Distributions (Bell Curve): Definition, Word Problems" From [StatisticsHowTo.com](https://www.statisticshowto.com/)
