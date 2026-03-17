# UPI Fraud Transaction Analysis (EDA)

#OVERVIEW
This project performs exploratory data analysis (EDA) on a simulated UPI transactions dataset to identify fraud patterns and behavioral trends in digital payments.
The analysis focuses on understanding how fraudulent transactions vary across transaction types, merchant categories, device usage, network types, and time-based patterns.

#DATASET
- Source: Kaggle (UPI Transactions 2024 Dataset - Simulated)
- Total Records: 250,000 transactions
- Features include transaction type, amount, device type, network type, timestamp, and fraud flag

#TOOLS AND TECHNOLOGIES
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

#KEY ANALYSIS PERFORMED
- Data cleaning and preprocessing
- Timestamp feature extraction (date & time)
- Fraud rate calculation
- Fraud distribution analysis
- Fraud by transaction type
- Fraud by merchant category
- Fraud by device type
- Fraud by network type
- Fraud by time of day
- Fraud by sender bank
- Fraud vs transaction amount analysis
- Correlation heatmap

#KEY INSIGHTS
- Fraud rate is approximately 0.19% of total transactions
- P2P transactions show the highest fraud occurrences
- Grocery merchant category has the highest fraud frequency
- Android devices record the highest fraud cases
- 4G network shows the highest fraud activity
- Fraud peaks around 7 PM (evening hours)
- Fraud transactions are generally of lower amounts
- SBI appears most frequently in fraudulent sender transactions

#CONCLUSION
The analysis indicates that fraudulent transactions are influenced by multiple behavioral and contextual factors rather than a single variable. Patterns such as transaction type, device usage, and time of day play a significant role in fraud occurrence.
These insights can help in designing better fraud detection and risk monitoring systems in digital payment platforms.

#FUTURE WORK (OPTIONAL)
- Build a machine learning model for fraud detection
- Implement anomaly detection techniques
- Real-time fraud monitoring dashboard

