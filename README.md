OAP 2021 Revisited: Correcting Graduate School Statistics with Python

In 2021, my graduate school team adapted the Family Leisure Activity Profile to build an Outdoor Activities Profile (OAP) for Liberty University students. While we successfully gathered survey data via Qualtrics, I always felt our original statistical methodology failed to tell the true story of the data.

Our original presentation relied on unsupported One-Way ANOVAs to claim there were no differences between sexes, and we drew questionable conclusions about satisfaction vs. involvement. I built this repository to revisit that data and apply the mature analytical skills I have today.

The Revision Project:

-Data Cleaning: Rebuilt the messy Qualtrics dataset using Pandas and NumPy.

-Statistical Correction: Replaced the flawed ANOVAs with an Independent T-Test via SciPy for accurate gender comparisons.

-Bivariate Analysis: Shifted from purely descriptive claims to a formal Pearson correlation to prove the relationship between student involvement and satisfaction.

-Visualization: Upgraded the visual storytelling using Seaborn and Matplotlib.

[Click here to view my full Python Data Analysis] (OAP_2021-Revisited.ipynb)
