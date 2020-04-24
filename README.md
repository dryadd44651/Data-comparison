# Data_comparison
This project show us how to calculate the similarity and correlation between two data

# Basic analysis
*we can use the commond function to check the data similarity*
- summary
>- Min. 1st Qu.  Median    Mean 3rd Qu.    Max
- IQR
>- IQR = Q3 − Q1
- var
>- Variance
- cov
>- Covariance  
- cor
>- Correlation(relations between 2 data)
- hist
>- histogram
- qqnorm
>- check the data normality
- boxplot
>- check data distribution and outlier

# Data similarity
*Data a and b belong to same Population should pass T test and F test*

**Before we do the T test and F test**
*we should make sure data is normal or size>26*
- shapiro.test
>- H0: data is normal
>- Ha: data is non-normal
- t.test
>- H0: difference in means is equal to 0
>- Ha: difference in means is not equal to 0
- var.test
>- H0: the ratio of variances is equal to 1
>- Ha: the ratio of variances is not equal to 1

# Data correlation
Check correlation of two data
## cor.test
- H0: correlation is equal to 0
- Ha: correlation is not equal to 0


## The good correlation will have a good regression model
*We can build the linear regression model to test the data*
- fit = lm(a~b)
>- build the model
- summary(fit)
>- check the model detail
- p-value
>- H0: the weight should be 0
>- Ha: the weight should not be 0
- R-squared: How fit your model
- Estimate: the weight of the parameter





