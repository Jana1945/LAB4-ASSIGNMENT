# LAB4-ASSIGNMENT
# Data Analysis
 1) Dataset size :
    The dataset contains 891 rows and 12 columns.
2) Missing values :
   Based on the dataset inspection:
   1) The Age column has missing values (only 714 non-null entries).
   2) The Cabin column has a large number of missing values (only 204 non-null entries).
   3) The Embarked column has a small number of missing values (889 non-null entries).
3) Key Observations:
   The Cabin column contains too many missing values, so it will be removed.
   The Age column will be filled using the median value.
   The Embarked column will be filled using the most frequent value (mode).
   # Data cleaning
   Cleaning Explanation:
   The Cabin column was removed due to a large number of missing values.
   Missing values in the Age column were replaced using the median to avoid the effect of outliers.
   Missing values in the Embarked column were filled using the mode, as it represents the most frequent category.
   
   <img width="311" height="417" alt="image" src="https://github.com/user-attachments/assets/19e7747e-333b-4b04-a55b-fa2ef2488675" />

After handling missing values, all columns now contain complete data with no null values. The dataset is clean and ready for further analysis.

# Visualization

<img width="1234" height="853" alt="image" src="https://github.com/user-attachments/assets/c78ebd41-7c7f-4afd-8897-162e3523dbab" />

The Age distribution shows that most passengers are between 20 and 40 years old.
The data appears to follow a roughly normal distribution with fewer passengers at very young and older ages.

<img width="1306" height="885" alt="image" src="https://github.com/user-attachments/assets/418fbb93-4ac5-4e27-a508-146c677d51e5" />

The Fare boxplot reveals the presence of several outliers, indicating extreme values. Most ticket prices are relatively low, but a few passengers paid significantly higher fares.

## Outliers
The dataset contains outliers in the Fare column, which may influence statistical analysis and model performance.

# Final Conclusion
The dataset was successfully preprocessed by handling missing values, removing irrelevant features and ensuring data consistency. Data visualization helped in understanding the distribution and identifying outliers. 
The dataset is now clean and ready for machine learning tasks.



   

   



   
