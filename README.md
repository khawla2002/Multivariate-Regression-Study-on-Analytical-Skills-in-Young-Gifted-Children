This project includes a pdf file, a data file, and an Rcode file.
The pdf contains the project as a whole, with a discussion of the findings and the Rcode file contains the code used in the project. 
The data file contains the gifted children data collected.



Gifted Children's Analytical Skills Analysis


Project Overview
This project aims to investigate the relationship between the analytical skills of young gifted children and several variables, including the IQ of the mother, 
the average number of hours per week the parents read to the child, and the average number of hours per week the child watched an educational program on TV.
The analytical skills were evaluated using IQ tests, with the IQ scores serving as the dependent variable in the analysis. 
The project also explores whether the time spent reading to the child significantly influences their IQ score.

Dataset
The dataset comprises observations from thirty-six gifted children identified at the age of four from different schools in a large city. 
The data includes variables such as the children's IQ scores, the IQ of their mothers, and the average weekly hours spent reading and watching educational 
TV programs. While the data provides clear and precise observations, the lack of information on the schools' location and the city's specifics may limit 
the data's reliability. Additionally, the relatively small sample size and lack of diversity in the sample population pose challenges in drawing generalizable conclusions.

Data Cleaning
Before analysis, irrelevant columns were filtered out, leaving only the variables of interest: mother's IQ, hours spent reading,
hours spent watching educational TV, and IQ scores. This step ensured a focused analysis on the selected independent and dependent variables.

Basic Exploration of Data
Exploratory analysis involved visualizing the relationship between the dependent variable (IQ scores) and independent variables
(mother's IQ and hours spent watching educational TV). Scatterplots revealed potential correlations, indicating a positive relationship with mother's 
IQ and a negative relationship with TV viewing hours.

Multivariate Linear Regression
Multivariate linear regression was employed to model the linear relationship between the explanatory variables (mother's IQ, reading hours, TV viewing hours) 
and the response variable (IQ scores). Assumptions such as normal distribution of residuals and homoscedasticity were checked to ensure the validity of 
the regression analysis. The results indicated a significant relationship between the mother's IQ, reading hours, and IQ scores, while TV viewing hours did 
not show statistical significance.

2-Sample Unpaired T-Test
To assess the influence of reading hours on IQ scores, a 2-sample unpaired t-test was conducted on two groups based on reading hours per week. 
The results suggested a significant difference in IQ scores between children read to for more than 2.1 hours per week compared to those read to less 
than or equal to 2.1 hours per week.

Results
Basic exploration revealed potential correlations between IQ scores and independent variables. Multivariate linear regression showed that mother's 
IQ and reading hours significantly predicted IQ scores, while TV viewing hours did not. The 2-sample unpaired t-test indicated a significant
difference in IQ scores based on reading hours.

Discussion
The study provides evidence supporting the hypothesis that mother's IQ and reading hours significantly influence children's IQ scores. 
However, limitations such as small sample size and lack of diversity in the sample population were noted, highlighting the need for further 
research to generalize the findings. Additionally, the study emphasizes the importance of reading to children in fostering their cognitive development.





