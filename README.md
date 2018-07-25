# Exploratory_data_analysis
Exploratory data analysis on human body temperature data

In this exercise, you will analyze a dataset of human body temperatures and employ the concepts of hypothesis testing, confidence intervals, and statistical significance.

Answer the following questions in this notebook below and submit to your Github account.

Is the distribution of body temperatures normal?

Is the sample size large? Are the observations independent? Remember that this is a condition for the Central Limit Theorem, and hence the statistical tests we are using, to apply.

Is the true population mean really 98.6 degrees F?

First, try a bootstrap hypothesis test.

Now, let's try frequentist statistical testing. Would you use a one-sample or two-sample test? Why?

In this situation, is it appropriate to use the  tt  or  zz  statistic?

Now try using the other test. How is the result be different? Why?

Draw a small sample of size 10 from the data and repeat both frequentist tests.

Which one is the correct one to use?

What do you notice? What does this tell you about the difference in application of the  tt  and  zz  statistic?

At what temperature should we consider someone's temperature to be "abnormal"?

As in the previous example, try calculating everything using the boostrap approach, as well as the frequentist approach.
Start by computing the margin of error and confidence interval. When calculating the confidence interval, keep in mind that you should use the appropriate formula for one draw, and not N draws.

Is there a significant difference between males and females in normal temperature?

What testing approach did you use and why?

Write a story with your conclusion in the context of the original problem.

You can include written notes in notebook cells using Markdown:

Resources
Information and data sources: http://www.amstat.org/publications/jse/datasets/normtemp.txt, http://www.amstat.org/publications/jse/jse_data_archive.htm

Markdown syntax: http://nestacms.com/docs/creating-content/markdown-cheat-sheet
