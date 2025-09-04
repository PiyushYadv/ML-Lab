# Data Card – Titanic Dataset

## Dataset Overview
- **Source:** https://www.kaggle.com/c/titanic/data
- **Format:** CSV
- **Rows:** 891
- **Columns:** 13 (after cleaning)
- **Target Variable:** Survived (1 = survived, 0 = did not survive)

## Key Features
- **Categorical:** Sex, Embarked, Pclass
- **Numerical:** Age, Fare, SibSp, Parch
- **Mixed:** Ticket

## Preprocessing Summary
- Missing values in Age imputed with median.
- Missing values in Embarked imputed with mode.
- Cabin dropped due to >75% missing data.
- Outliers in Fare capped using IQR method.
- Added binary flags for originally missing values.

## Limitations
- Outlier treatment may remove real but rare high fares.
- Imputation assumptions may bias results.
- Dropping Cabin removes potential location-based insights.

## License & Usage
- Academic and research use under Kaggle rules.
