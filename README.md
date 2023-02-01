# AB-Testing-For-Bidding-Methods
AB Testing For Bidding Methods

AB Testing -  Independent Two Sample T Test

![images](images.png)
1. Determine the hypothesises
2. Control
    - 1. Normality (shapiro)
    - 2. Variance (levene)
3. Implementing the hypothesises
    - 1. If normality and variance homogeneity are provided then parametric test is used. (T test)
    - 2. If normality and variance homogeneity are not provided then non-parametric test is used. (mannwhithneyu)
4. Interpret the results according to the p-value
Note:
- If the data is not normally distributed then the non-parametric test is used but the homogeneity is not provided then parametric test is used with equal_var = False parameter.
- It may be beneficial to check and fix outliers before the normality test.



