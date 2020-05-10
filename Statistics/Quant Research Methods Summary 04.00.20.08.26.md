Quant Research Methods Summary 04.00.20.08.26
=============================
@Quantitative_Research_Methods

# Variable types

**Nominal/Categorical:** Data does not have a numerical value, and has no intrinsic ordering (e.g. gender)
**Ordinal:** A type of nominal/categorical variable in which the data has ordered categories, but the distance between the categories is not known, that is, it does not have 'category widths'. E.g. a self-reporting scale such as the Likert scale, where a respondent picks a value between 1 and 5 in response to a question.

# Independent and dependent variables

In some cases an independent variable will be clearly independent - it will be something that cannot possibly (at least within the confines of given human knowledge) be influenced by the other variable/s in play. E.g. - gender.

Most of the time, however, particularly in complex social science research, the independent variable will not be so clearly 'independent', rather it will be *constructed* as independent on the basis of the theoretical framework being employed and the hypothesis being tested. See Argyrous 1997: 211:

> "However, in other instances, it may not be so easy to identify which variable is dependent and which is independent. An example we will use in Chapter 22 illustrates this point. We have a set of local government areas (LGAs), and we calculate the rate of unemployment and the crime rate for each. Of these two variables, which do we say is independent and which is dependent? Do we form groups of LGAs according to crime rates and then compare across these groups using unemployment rates, or do we group the LGAs by unemployment rates and then compare them according to crime rates? One might argue that unemployment in an area affects the number of crimes, due to the higher number of people who feel alienated from society. Therefore the unemployment rate is the independent variable. Alternatively, one might argue that crime rates depend on factors other than unemployment, and that unemployment is a consequence of crime as businesses move to safer areas. According to this argument we would use crime rate as the independent variable. **The choice of dependent and independent variable is, in other words, affected by the theoretical arguments from which research hypotheses are derived . It is not an issue that the statistical tests themselves can prove . Statistical tests cannot explore the complete nature or channels of any causality. All that statistics can do is compare differences given the way that the problem has been posed.**"

So what becomes an issue of debate then is the *theory* being tested and whether enough different statistical tests have been conducted to make the association posited plausible.




# Univariate and Bivariate Descriptive Statistics - Tabulation, Graphs and Crosstabulation

Descriptive Statistics as a stand-alone stage– Describe a phenomenon, using a sample,then generalize to the General Populationusing the principles of Inferential Statistics

Inferential Statistics as a stand-alone stage– Explain a phenomenon, using a sample, thengeneralize to the General Population usingthe principles of Inferential Statistics

**Always start with descriptive before making inferences**

## Types of analysis

1. Univariate = one variable
2. Bivariate = two variables - identifying a relationship between variables
3. Multivariate = multiple variables - identifying relationships between variables

#### Tables and Graphs for Univariate and Bivariate Analysis

1. Scope: summarize data in a meaningful way
2. Title: The unit of analysis; the variable measured; the time period covered
3. Source of data: Name and Edition of Survey and/or the name of the institution that provided data (ABS, ONS)
4. Total: total net sample; total respondents for that given variable
5. Unit of measurement: the unit of analysis should be clearly indicated
6. Variable Values: Categories (if nominal/ordinal) or Minimum/Maximum Values (if numerical)


## Univariate analysis

### Numerical variables

1. Frequency (count)
2. Percentage (total = 100%)
3. Proportion (total = 1)
4. Mode
5. Mean
6. Variance and Standard Deviation
7. Median

### Categorical variables

1. Frequency (count)
2. Percentage (total = 100%)
3. Proportion (total = 1)

## Bivariate Analysis

### What is bivariate analysis?

Purpose of bivariate analysis is to explore potential relationships between two variables to determine whether the variation of one variable is dependent on the variation of the other.

Dependency can be established through:

1. Association - only indicates correlation, not dependence
2. Correlation - introduces dependence
3. Regression - strongest method for determining dependence

**Should refer to the 'dependent' variable as the 'outcome variable'**

**The independent variable should always precede the dependent variable in time - this of course implies the need to determine an appropriate time lag?**


Depending on level of measurement, we can use:

1. Chi-squared - for 2 categorical variables
2. Correlation (and scatterplot) - for 2 numerical variables
3. 1 numerical and 1 categorical (2 categories) - T-test
4. 1 numerical and 1 categorical (2+ categories) - ANOVA

### Determining association in bivariate analysis

1. Determine independent and dependent variables (model the relationship)
2. Split data into groups defined by categories of the independent variable
3. Compare these groups in terms of some descriptive statistic for the dependent variable

#### Cross-tabs

1. Check frequency distribution of each variable to check that it will 'fit' into a crosstab
2. Construct a crosstab with:
    3. The independent variable *across* the columns and the dependent variable *down the rows*
    4. Column percentages
    5. Modal cells highlighted
 3. Interpret the results to assess the pattern and strength of any possible relationship

* "Dimensions" - number of rows times number of columns (e.g 2x2)
* Cells - contain the joint frequencies
* Marginals - contain the row and column totals

Cross-tabs shouldn't include more than 5 rows/columns

Always make a frequency table first to see if the distribution will fit into that 5 row/column constraint.
If it won't - recode into larger groupings, given that groupings should be conceptually justifiable.

**1. **Percentages - totals:**** Means every cell shows the percentage that particular subset is of the total



#### Measures of association for categorical data

1. Lambda - Assymetric - at least one variable must be nomi nal
2. Goodman and Kruskal tau - Assymetric - At least one variable must be nominal
3. Eta - Assymetric - Independent variable is nominal
4. Somer's d - Asymmetric - Both variables at least ordinal
5. Gamma - Symmetric - Both variables at least ordinal
6. Kendall's tau-b - Symmetric - Both variables at least ordinal
7. Spearman's rho - Symmetric - Both variables at least ordinal with many points on the scale
8. Pearson's r - Symmetric - Both variables interval/ratio variables with many points on the scale

These measures of association are based on the concept of "Proportional Reduction in Error".
PRE is basically a way of determining how many less prediction errors you make assuming a dependent relationship versus assuming the modal case (the most common category).

* Measures of association for nominal scales tell us the strength of a relationship
* Measures of association for ranked scales tell us strength and direction


##### Lambda

• Lambda is an asymmetric measure of association for nominal scales
• Lambda will always equal 1 where data exhibit perfect association
• Lambda will always equal 0 where data exhibit no association
• Lambda will sometimes equal 0 where data exhibit some association.
This happens when the distribution is skewed, i.e. modal categories of
the independent variable and the dependent variable are all the same
• Lambda may underestimate the strength of the relationship in
nominal-by-ordinal crosstabs and the ordinal scale has more than two
points.
* Lambda may underestimate the strength of the relationship in
nominal-by-ordinal crosstabs and the ordinal scale has more than two
points.

##### Goodman and Kruskal's Tau

* Rather than using the modal value to make predictions, as Lambda does, this uses the frequency distribution across all the categories of independent variables. Therefore it is less sensitive to skewed distributions.

#### Measures of association for ranked data

* Use similar logic, PRE, to lambda
* Use extra information provided by ordinal and interval/ratio scales to establish the relationship between pairs of cases
* All measures we will look at refer to two types of pairs of cases
1. Concordant pairs: Two cases that share the same ranking for both variables
2. Discordant pairs: Two cases that differ in their ranking on the two variables

1. If the two variables are positively associated then N(C) - N(D) > 0
2. If the two variables are negatively associated then N(C)-N(D) < 0
3. If the two are not associated then N(C) - N(D) = 0

##### Gamma

1. Expresses strength of relationship as difference between N(C) and N(D) represented as a proportion of total number of pairs
    2. Symmetric
    3. Useful when we:
        4. Do not know the direction of the association
        5. Believe the values are mutually dependent
    4. Useful if there are many tied cases
   
##### Somer's d

1. Incorporates a term for cases tied on the dependent variable
2. If two cases differ in terms of independent variable, but do not differ in terms of the dependent variable, then this should be evidence of no association
3. Assymetric
4. Useful if we strongly believe the measure is one way

### Descriptive statistics for numerical data

#### Data description

1. Describe the distribution of a univariate variable with a graph
2. Then interpret the key characteristics of the distribution - e.g.:
    3. Shape
    4. Centre
    5. Spread
    6. Outliers

#### Central tendency

Measures of central tendency indicate the typical or 'average' score in a distribution.

* **Mode:** Most frequent score - not useful with scales that have many values
* **Median:** Middle score in a ranked series. Can only be applied to ordinal and interval/ratio data.
* **Mean:** Sum of scores divided by the total - can be used for interval/ratio data that are not skewed and do not contain outliers

#### Measures of dispersion

##### Interval/ratio data

1. Range - difference between highest and lowest values in distribution - unreliable if dealing w/ outliers
2. IQR - difference between upper limits of first quartile and third quartlie
3. Standard deviation - extent to which scores differ from mean - also affected by outliers
4. Coefficient of relative variation - standard deviation expressed as a percentage of the mean - good for comparing different distributions

Skewed distributions make standard deviation invalid.

##### Nominal/ordinal data

1. Index of qualitative variation - counts the number of times each case is different to another case

##### In bivariate analysis

We use cental tendency and dispersion measures in bivariate analysis by calculating relevant measures for each group defined by the independent variable


#### Some guidelines

•
•
•
•
•••Remove unnecessary decimal points (e.g. 0.2, not 0.200)
Add a 0 before decimal points where necessary (0.2 rather than .2)
Indicate units of measurement where relevant (e.g. $15,000 rather than 15000)
Except in tables/graphs, numerals with four digits do not usually need a comma (e.g. 7623 rather
than 7,623). Numerals with more than four digits usually require a comma (e.g. 17,623 rather
than 17623)
Do not begin a sentence with Arabic numerals; spell the number out in Roman letters (e.g. ‘Forty
two per cent of people commented...’ not ‘42% of people commented...’)
For spans, use an en dash (e.g. 34–35 rather than 34-35)
Except in tables/graphs spell out numbers one to ten and use digits for 11 on, except:
•
 when used with units or for a numbered item (e.g. 2 metres; 10 per cent; page 2);
•
 as commonly used in scientific or technical textbooks;
•
 when digits are needed to avoid a string of hyphenated words (e.g. 24-hour day not twenty-four-hour day);
•
 at the beginning of a sentence, when numbers should be spelt out


### Coefficient of correlation - Pearson's R/OLS

1. Positive when relationship is positive, negative when relationship is negative
2. Goes from -1 to +1

#### Finding the line of best fit

1. Aim is to make the gap (residuals) between the line and individual plots (data points) as small as possibl.e
2. This is the principle of ordinary least squares - the aim being to minimise the sum of the squared residuals
3. The OLS regression line will pass through the point that is the mean for each of the two variables
4. The slope of the regression line will always equal: (the sum of the value of the independent variable minus the mean of the independent variable)(the dependent variable minus the mean of the dependent variable)/sum(the independent variable - the mean of the independent variable)squared.
5. Once we know the slope and one of the points we can extend the line back to the Y axis to X=0.
6. This provides the constant for the regression equation (a).
7. This allows us to write an equation that expresses the value of the dependent variable as a function of the constant, the slope and the independent variable. This allows us to predict the dependent variable for any given independent variable.

#### Coefficient of determination

1. PRE measure - measures how closely the data points fall near the regression line, and therefore the confidence we can have in our predictions based on the OLS regression line. This indicates how much variance in the dependent variable is explained by the regression line.


#### Guidelines for OLS regression

1. Linear relationships only
2. Prediction based on the OLS line is unreliable when error terms are heteroscedastic (fan out as we move along the line)
3. Can be misused if relationship is extrapolated beyond range of variables used in determining the equation
4. No outliers on the dependent variable, independent variable or combination of variables.


### Multiple regression

1. Regression analysis can be used to show impact of combination of independent variables on value of a dependent variable
2. But -
    3. Need to know that the independent variables are truly independent
    4. And need to have a strong theoretical grounding - no fishing expeditions
    5