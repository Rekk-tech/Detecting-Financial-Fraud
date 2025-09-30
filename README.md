🧩 Overview
This case study dives into a real-world scenario where a financial services firm is under attack by fraudsters gaining control of user accounts and draining funds through suspicious transfers and cashouts.

As part of the Accredian Data Science Content Specialist Internship, I worked on detecting fraudulent transactions using a dataset with over 6.3 million records, applying machine learning techniques, and translating results into business-ready insights and recommendations.

📌 Problem Statement
A fintech company is experiencing a surge in fraud where bad actors initiate unauthorized transactions once they gain access to user accounts. The primary goal was to:

Detect fraudulent transactions using a machine learning model.
Interpret model decisions and highlight what drives fraud.
Deliver business recommendations for real-time fraud prevention.

🧠 Objectives
Develop a robust fraud detection model under extreme class imbalance (fraud cases < 0.1%).
Optimize recall without compromising precision, ensuring minimal false positives.
Translate insights into actionable business strategy for internal stakeholders.

📊 Dataset Snapshot

📦 Size6,362,620 rows × 10 columns

⏱️ Time Steps: 1 step = 1 hour (30 days)

🏷️ Key Featurestype, amount, oldbalanceOrg, newbalanceOrig, nameDest, isFraud

🚨 Note: Fraud only occurs in TRANSFER and CASH_OUT types

data/
│   ├── raw/          # chứa Fraud.csv gốc
│   ├── interim/      # data sau khi clean
│   └── processed/    # features đã xử lý, dataset final

link data : https://drive.google.com/drive/folders/1LECRCKJWuYMrbRoKZVvKy_BP1uhR4RUB?usp=sharing