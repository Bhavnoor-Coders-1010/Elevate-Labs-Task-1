# Elevate-Labs-Task-1
I printed the sum of null values per column, data types and general information per column.


"Cabin" Column has 77% null values, therefore, it is wise to drop that column altogether, because an attempt to impute missing values would lead to 77% fabricated data which is not good for any purpose.

"Age" Column has 19% null values, thus, it would not be good to drop the column but instead impute the null values. Since, age may be highly correlated with only the gender, thus, we may impute average age of females and males in respective rows.

"Embarked" Column has only 2 null values, and since, it is a categorical column, it would be wise to impute the null values with the mode, that is, the most occuring value which is S.


We can then normalize Age, SibSp, Parch, Fare. Other Columns have very less variance, or are categorical variables and therefore, we may not normalize them.

References Used - 
https://www.geeksforgeeks.org/selecting-rows-in-pandas-dataframe-based-on-conditions/

https://stackoverflow.com/questions/60115806/pd-na-vs-np-nan-for-pandas

https://saturncloud.io/blog/how-to-convert-categorical-data-to-numerical-data-with-pandas/#:~:text=Method%201%3A%20Using%20the%20cat,numerical%20representation%20of%20each%20category.

https://www.geeksforgeeks.org/box-plot-in-python-using-matplotlib/

https://www.geeksforgeeks.org/detect-and-remove-the-outliers-using-python/
