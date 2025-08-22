# Bank-Fraud-Detection-Project
Bank Fraud Detection Project using Excel Power Bi and Python

1. Data Cleaning using Excel

- The raw dataset was first cleaned and pre-processed in Excel to ensure accuracy and reliability.
Key steps performed:

- Removed Duplicates → Based on transaction_id and credit_card_number.

- Handled Missing Values → Either filled with appropriate values or removed rows.

- Corrected Data Types → Converted transaction_time into proper Date-Time format.

- Dropped Unnecessary Columns → For example, the helper index column a.

- Final cleaned data was saved in CSV format for further analysis in Python and Power BI.

🔹 2. Exploratory Data Analysis (EDA) using Python

- The dataset was analyzed using Python to uncover patterns and detect fraudulent behaviors.

- EDA Steps Performed:

- Fraud vs Non-Fraud Ratio

- Counted the number of fraudulent (is_fraud = 1) and genuine (is_fraud = 0) transactions.

- Transaction Amount Analysis

- Compared average transaction amounts between fraud and non-fraud cases.

- Transaction Type Analysis

- Identified which types of transactions (ATM, POS, Online, Transfer) were more prone to fraud.

- Time-Series Analysis

- Analyzed fraud occurrences by time to find peak hours/dates for fraudulent activity.

- Customer Risk Profiling

- Highlighted customers with repeated fraud cases.

- Tools & Libraries Used:

- Pandas → Data handling and preprocessing

- Matplotlib & Seaborn → Visualization

- NumPy → Numerical computations

🔹 3. Dashboard Development using Power BI

- After cleaning and analyzing the data, an interactive dashboard was built in Power BI for visualization and reporting.

- Dashboard Features:

- KPIs (Cards):

- Total Transactions

- Fraud Transactions

- Percentage of Fraud Transactions

- Total Transaction Amount

- Fraud Transaction Amount

- Visuals Included:

- Pie Chart → Fraud vs Non-Fraud Transactions

- Stacked Bar Chart → Fraud by Transaction Type (ATM, POS, Online, Transfer)

- Line Chart → Fraud Trends over Time

- Box Plot / Histogram → Transaction Amount Distribution (Fraud vs Non-Fraud)

- Horizontal Bar Chart → Top Risky Customers (based on fraud count)

- Table View → High Value Fraud Transactions (ID, Customer, Amount, Type, Time)

- Clustered Bar / Waterfall Chart → Old Balance vs New Balance (Fraud vs Non-Fraud)

- Dashboard Layout (1920×1080):

- Top Section: KPI Cards

- Left Panel: Fraud Distribution (Pie, Transaction Type Bar Chart)

- Center Panel: Trends (Line, Amount Distribution)

- Right Panel: Customer Risk & High Value Frauds

- Bottom Panel: Balance Impact Visualization

🔹 4. Project Outcome

- Data was cleaned and standardized for analysis.

- EDA in Python helped in identifying fraud patterns and customer risk.

The Power BI dashboard provided an interactive and insightful view of fraudulent activities, enabling faster detection and better decision-making.
