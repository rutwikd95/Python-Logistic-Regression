# Python-Logistic-Regression

### In this python notebook, I have used Logistic Regression on the 1974 Women's Survey Data Set from the Statsmodel library in Python where married women were asked if they had any extramarital affairs.

I have performed Logistic Regression using the Scikit Learn to classify and check if a certain woman had any affair based on the given variables or features.

The 9 features are as follows:

- rate_marriage   : How rate marriage, 1 = very poor, 2 = poor, 3 = fair,
                4 = good, 5 = very good
                
- age             : Age

- yrs_married     : No. years married. Interval approximations. See
                original paper for detailed explanation.
                
- children        : No. children

- religious       : How relgious, 1 = not, 2 = mildly, 3 = fairly,
                4 = strongly
                
- educ            : Level of education, 9 = grade school, 12 = high
                school, 14 = some college, 16 = college graduate,
                17 = some graduate school, 20 = advanced degree
                
- occupation      : 1 = student, 2 = farming, agriculture; semi-skilled,
                or unskilled worker; 3 = white-colloar; 4 = teacher
                counselor social worker, nurse; artist, writers;
                technician, skilled worker, 5 = managerial,
                administrative, business, 6 = professional with
                advanced degree
                
- occupation_husb : Husband's occupation. Same as occupation.

- affairs         : measure of time spent in extramarital affairs

#### I have used Train Test Split to split the data set into Train and Test data and used the "fit" and "predict" methods to predict the results achieving an accuracy score of 72% .
