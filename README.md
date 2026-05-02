🏦 **Bank Transactions Report with Power BI Dashboard**

An end-to-end Power BI solution for monitoring bank transactions, identifying fraudulent patterns, and providing interactive filtering for transaction analysis.

📖 Built as a learning project following Pavi's Data Insights tutorial. Extended with custom DAX measures, Canva-designed layout, and additional interactivity.


📌 Problem Statement
Financial institutions process thousands of transactions daily. This dashboard gives analysts a centralized view to monitor transaction volumes, flag suspicious activity, and drill down by transaction type, device, and geography — all in real time.

📊 Dashboard Features
FeatureDescription💰 Transaction SummaryTotal transaction count and total value (e.g. $771.17K)🚨 Fraud DetectionFlags suspicious transactions using True/False fraud indicators🌍 Global Map ViewGeographic distribution of transactions using lat/long data🎛️ Interactive FiltersSlicers for Transaction Type, Status, Device Used, Network Slice ID

<img width="1321" height="743" alt="image" src="https://github.com/user-attachments/assets/4aa2bcb0-1be7-4380-8834-50f42afc03a0" />
<img width="1315" height="733" alt="image" src="https://github.com/user-attachments/assets/250b62ec-45e6-470d-b97f-bba28973ad13" />
<img width="1311" height="734" alt="image" src="https://github.com/user-attachments/assets/b209f8f0-7d2e-4eac-b258-a0c267e0b1aa" />

🛠️ Tech Stack

Power BI Desktop — Data modelling, DAX calculations, report building
Power Query — Data transformation and cleaning
Canva — Custom dashboard background and layout design
GitHub — Version control and documentation


📁 Project Structure
Bank-Transactions-Report/

│
├── bank transaction report.pbip     # Power BI project file

├── bank transaction_data.csv        # Source dataset

└── README.md


🚀 How to Open

Download and install Power BI Desktop (free)
Clone or download this repository
Open bank transaction report.pbip in Power BI Desktop
Ensure bank transaction_data.csv is in the same folder as the .pbip file


🔮 Future Improvements

 Connect to a live data source (SQL / API) instead of static CSV
 Add time-series trend analysis for fraud detection over time
 Build an alert system for transactions exceeding threshold amounts
 Publish to Power BI Service for web-based access


🙏 Acknowledgements
Tutorial inspiration: Pavi's Data Insights — Dataset used for educational and portfolio purposes only.

🏷️ Topics
power-bi data-analytics dashboard fraud-detection dax data-visualization bank-transactions
