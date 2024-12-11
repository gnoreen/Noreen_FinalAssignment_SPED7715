# Noreen_FinalAssignment_SPED7715
Repository of code and data files for an analysis of the earnings gap in the NLSY79 sample. 

# Contents
This repository contains an .Rmd and .html file with the R code for data cleaning and analyses (visualizations, principal component analysis, and linear regression with stepwise sequential selection and cross-validation). All the necessary data files to import are included in the repository, along with the final data file used for the PCA (created by merging datasets and mutating variables) and the data used for the linear regression (which includes the PCA component scores used in the regression).

# Data
Data for this analysis comes from participants from the National Longitudinal Survey of Youth 1979 sample. The NLSY79 survey is sponsored and directed by the U.S. Bureau of Labor Statistics and managed by the Center for Human Resource Research (CHRR) at The Ohio State University. Interviews are conducted by the National Opinion Research Center (NORC) at the University of Chicago. 
The NLSY79 database contains a representative sample of 12,686 U.S. men and women. These participants were born between 1957 and 1964 and were between the ages of 14 and 22 when they were initially surveyed. In addition to a host of demographic variables and information about their upbringing, there also exists a survey completed by each participant's school, as well as extensive longitudinal information on their life outcomes.
After cleaning and pre-processing the data, there were 362 individuals with complete data on each of the variables of interest. After further removing ‘far out’ outliers on the income variable (5 females and 14 males) as well as those with a reported income of zero (27 females and 16 males), the final sample size was 300.

Bureau of Labor Statistics, U.S. Department of Labor. National Longitudinal Survey of Youth 1979 cohort, 1979-2016 (rounds 1–27). Produced and distributed by the Cen-ter for Human Resource Research (CHRR), The Ohio State University. Columbus, OH: 2019. 

# Analysis
The purpose of the analysis is to examine evidence for the earnings gap for males and females in the sample and predict income separately for each gender based on various demographic, school-related, and familial variables. Prior to the regression analysis, principal component analysis was conducted on the individual and school-level education variables to reduce dimensionality. 



