# Statistical Analysis

## Concepts:

- **summary statistic:** a single number summarizing a large amount of data.
- Row = data point = observation;
- Column = field = feature = variable;
- dataframe = data matrix;
- **associated/dependent variables:** when two variables show some connection with one another;
- **independent variables:** when two variables are not associated;
- **dependent of independent, never both:** a pair of variables are either related in some way (dependent) or not (independent). No pair of
variables is both associated and independent.
- **explanatory variable:** one variable that might causally affect another;
- **response variable:** one variable that might be causally affected by another;
- **observational study:** when researchers collect data in a way that does not directly interfere with how the data arise;
- **association != causation:** association does not imply causation, and causation can only be inferred from a randomized experiment;
- **anecdotal evidence:** data that only represents one or two cases, and may not be representative of the population;
- **convenience sample:** where individuals who are easily accessible are more likely to be included in the sample;
- **confounding variable:** a variable that is correlated with both the explanatory and response variables;
- **observational data:** data where no treatment has been explicitly applied (or explicitly withheld). Generally only sufficient to show associations or form
hypotheses that we can check using experiments;
- **sampling methods:** simple, stratified, cluster, and multistage.
- **experiments:** studies where the researchers assign treatments to cases;
- **randomized experiment:** a experiment that includes randomization. Important when trying to show a causal connection between variables;
- **histogram:** provide a view of data density; especially convenient for understanding the shape of the data distribution; observations that fall on the boundary of a bin are allocated to the lower bin; can be used to identify modes (prominent peak in the distribution).
- **distributions with one, two, or three prominent peaks:** unimodal, bimodal, and multimodal.
- **distributions can be:** right skewed, left skewed, or symmetric.
- **standard deviation:** typical deviation of observations from the mean; usually about 70% of the data is within one standard deviation of the mean and about 95% is within two standard deviations;
- **standard deviation and IQR (interquartile range, i.e. length of the box in a box plot given by $IQR=Q_3-Q_1$):** measures of variability;
- % data between $Q_1$ and median? % between median and $Q_3$? Since $Q_1$ and $Q_3$ capture the middle 50% of data and the median splits data in the middle, 25% of data is between $Q_1$ and the median, and another 25% is between the median and $Q_3$;
- **whiskers** try to capture data outside of the box, but never more than 1.5 × IQR;
- **outliers:** observations lying beyond the whiskers;
- **robust statistics:** extreme observations have little effect on their values. *Examples:* median and IQR (in contrast to mean and standard deviation);
- **contingency table:** each value in the table represents the number of times (frequency) of data points between two categorical variables;

## Transforming data
- **transformation (rescaling of data using a function):** when data are very strongly skewed, we sometimes transform them so they are easier to model;
- **common funtions used:** $log_{10}x$, square root $\sqrt{x}$, and inverse $\frac{1}{x}$ where $x$ is the original observation.
- **objectives:** see data structure differently, reduce skew, assist in modeling, or straighten a nonlinear relationship in a scatterplot.

## Bibliography:
- David Diez, Mine Çetinkaya-Rundel, and Christopher D Barr. OpenIntro Statistics, 4th edition, 2022.
- Statistics Textbook Options: https://www.openintro.org/book/stat/
