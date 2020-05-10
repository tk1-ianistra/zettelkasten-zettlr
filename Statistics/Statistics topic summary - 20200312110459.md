Statistics topic summary - 20200312110459
========================================



# Statistics topic summary

## Variables

1. The conceptual (or nominal) definition of a variable uses literal terms to specify the qualities of a variable (general sense of what it means)
2. An operational definition of a variable specifies the procedures and criterias for taking a measurement of that variable for individual cases
3. **Scale of measurement** = a range of scores that can be assigned to cases during the process of measurement
4. **Discrete variable** = has a finite number of values
5. **Continuous variable** = can vary in quantity by infinitesimally small degrees
6. **Interval/ratio** = scale in which the distance between categories is known, and is equal across the scale. Note that a ratio scale will contain a true zero point which signifies 'nothing' of the variable.

### Types of variable relationships
1. One way direct
2. Two way direct with mutual dependence

## Descriptive statistics

Descriptive statistics refers to the organisation, analysis and presentation of statistical data that already exists - as opposed to prediction which essentially creates new data.

### The four levels of measurement

1. Nominal = measurement that classifies cases into categories that have no quantitative ordering (e.g. - 'religion' or 'gender')
2. Ordinal = allows cases to be ordered by degree according to measurements of the variable (most yes/no variables are likely to be ordinal)
3. 

## Frequency tables

Minimum structure of frequency tables
* Clear title indicating variable and cases for the distribution
* Clearly labelled categoriesZ
* Total number of cases indicated
* Source of data
* Indicate where total in table is less than respondents

**Relative frequency tables** - adds percentages and proportions

**Cumulative frequency table** - shows, for each value in a distribution, the number of cases up to and including that value

**Cumulative relative frequency table** - shows, for each value in a distribution, the percentage or proportion of the total number of cases up to and including that value.

**Class interval** - groups together a range of values for presentation and analysis
* Stated class limits are th eupper and lower bounds of a class interval that determine its width
* Class intervals should usually be the same width
* Intervals must be mutually exclusive
* Upper stated limit of one class cannot touch lower stated limit of next class
* Mid point of the interval - sum of the lower and upper limits divided by two

Classes can be defned by:
1. Values of the variables (e.g. 18-34, $50,001 - $100,000)
2. Deciles, percentiles and quintiles.

Construct a decile, percentile and quintile by rank ordering the cases and splitting them into equal sized groups based on the chosen system (decile, quartile, etc).


## Crosstabulations

A crosstabulation extends the basic concept of a frequency table from a univariate application to a bivariate application. A crosstabulation shows a joint frequency distribution.
* The independent variable should go in the columns
* The dependent variable should go in the rows
* Rows and columns should be ordered increasing/decreasing where appropriate

**Cross-tab terminology**

Size = number of categories for the row variable
Dimensions = number of categories for the column variable
Cell = Each cell contains one combination of the two variables
Marginals = Entries in the total column. These provide the frequencies for the categories of each variable.

Crosstabs are only realy useful when there's a limited number of categories. 

**Direction and strength of a relationship:**
1. Modal cell = cell containing the relationship that occurs most often
2. The pattern of the relationship is the relationship indicated by the modal cell
3. The strength of the relationship relates to the proportion of cases captured by the modal cell for each given independent variable
4. Direction of the relationship - 
    * A positive relationship = both variables are moving in the same direction
    * Negative relationship = movement of one variable is associated with movement of the other variable in the other direction
5. When crosstabulating two ordinal-level varibales arrange the table so that the values of the independent variable increase across the page from left to right and the values of the dependent variable increase down the page.
6. Relationship consistency = a relationship is consistent if the relationship between the independent and dependent variables goes in the same direction consistently as the independent variable moves up its scale.

### Measures of association

* A measure of association enables us to quantify the relationship between variables in a crosstab in a consistent, standardised way.
* "Measures of association are descriptive statistics that quantify a relationship between two variables"
    * Assymetric measures of association = measures of association which are sensitive to which variable is independent and which is dependent
    * Symmetric measures of association = measures which end up being the same regardless of which variable is independent and which is dependent
    * 
#### Choosing a measure of association
**Criteria for choosing:**
1. Should take value of 1 or -1 in situations of perfect association
2. Should take on the value of 0 in situations of no association
3. A + or - sign should indicate the direction of association

![6076818d85ac5db79d9394aac1dc9d63.png](6076818d85ac5db79d9394aac1dc9d63.png)

##### Lambda

* Lambda is a 'proportional reduction in error' measure.
* It measures the difference in the number of prediction errors that occur between 2 cases
    * Case 1 = predict the scores for the dependent variable without knowing the value of the independent variable (so essentially just picking based on average occurrence)
    * Case 2 = predict the scores for the dependent variable *with* knowledge of the independent variable
    * Detract the number of errors in case 2 from the number of errors in case 1 and represent as a portion of the total number of errors. This shows the *proportion by which the error rate has been reduced by having the information about the independent variable - therefore giving an indication of the strength of the association*

![5da01ff1320bda8ba8442beb70538a80.png](5da01ff1320bda8ba8442beb70538a80.png)
1. Will always equal 1 for perfect association and 0 for no association
2. Assymetric measure of association
3. Ignores ordering of categories for ordinal scales
4. Will sometimes be 0 even when there is an association
5. Lambda can underestimate the strength of the relationship where one variable is nominal and one is ordinal.
6. Lambda can underestimate where there is a strong distributional skew - where all categories of the independent variable skew toward the same modal cell.
7. Can attempt to mitigate this by standardising the dependent variable in terms of percentages and then using those to calculate the lambda.

##### Concordant and disconcordant pairs

Concrdant pair = pair of cases that have the same relative ranking across both variables. E.g. - case A is ranked above case B in regard to both variables.