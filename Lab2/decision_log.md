# Decision Log – Titanic Data Cleaning

## Step 1: Data Ingestion
- Loaded titanic.csv into Pandas DataFrame.
- Checked data types and summary stats.

## Step 2: Missing Value Handling
- Age: median imputation.
- Embarked: mode imputation.
- Cabin: dropped (>75% missing).
- Added Age_missing, Embarked_missing flags.

## Step 3: Outlier Treatment
- Fare: capped above Q3 + 1.5*IQR.

## Step 4: Output
- Saved clean_v1.csv, data_card.md, decision_log.md.

## Rationale
Methods chosen for simplicity, reproducibility, and teaching clarity.
