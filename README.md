Titanic Dataset Preprocessing

This project demonstrates how to preprocess the Titanic dataset for machine learning tasks. The dataset is cleaned by handling missing values—filling Age with the median,
Embarked with the mode, and dropping Cabin due to excessive missing data. Categorical features like Sex and Embarked are encoded using one-hot encoding, and numerical columns 
(Age, Fare, SibSp, Parch) are standardized with StandardScaler. Outliers are visualized with boxplots and removed using the IQR method to ensure data quality.
The final dataset is fully numeric, cleaned, and ready for modeling. The project uses Python with libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn.

