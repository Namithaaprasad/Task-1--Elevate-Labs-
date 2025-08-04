Titanic Dataset Preprocessing

This project demonstrates the preprocessing of the Titanic dataset to prepare it for machine learning. The steps followed include:

Importing the dataset and exploring basic information such as data types and missing values.

Handling missing data by filling the 'Age' column with the median, filling 'Embarked' with the most frequent value, and dropping the 'Cabin' column due to excessive missing values.

Converting categorical features like 'Sex' and 'Embarked' into numerical format using one-hot encoding.

Normalizing numerical features such as 'Age', 'Fare', 'SibSp', and 'Parch' using standard scaling to ensure all features are on a similar scale.

Visualizing outliers using boxplots and removing them based on the IQR (Interquartile Range) method.

After completing these steps, the dataset is clean, fully numeric, and ready for machine learning models. The preprocessing is done using Python with libraries such as pandas, numpy, seaborn, matplotlib, and scikit-learn.
