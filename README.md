# Data-Analysis-on-UPI-Transaction-2024

This project explores UPI (Unified Payments Interface) transaction data to uncover fraud patterns, user behavior, and business insights using visualizations and statistical analysis. The goal is to support safer digital payments and smarter business strategies without relying on machine learning.
**Objective**
- Identifying fraud-prone banks, devices, networks, and transaction types
- Understanding user transaction behavior by age, state, time, and device
- Detecting peak activity hours and risky time windows
- Providing actionable insights for payment platforms and merchants

**Dataset**

- Source: [Kaggle – skullagos5246/upi-transactions-2024-dataset](https://www.kaggle.com/datasets/skullagos5246/upi-transactions-2024-dataset)
- Size: ~6MB
- Format: CSV
- Key fields:
  - `transaction_type`, `device_type`, `network_type`
  - `sender_state`, `sender_age_group`, `bank_name`
  - `merchant_category`, `amount`, `fraud_flag`, `timestamp`
 
  **Tools Used**
- Python (Pandas, NumPy)
- Seaborn and Matplotlib for data visualization
- Jupyter Notebook (hosted on Kaggle)

**Key Insights**

### 1. Fraud Pattern Analysis
- **Most Fraud-Prone Banks**: Kotak and IndusInd had the highest sender-side fraud rates.
- **Devices**: iOS users saw slightly higher fraud rates than Android and Web.
- **Network Types**: WiFi and 5G users experienced more fraud, possibly due to open/public networks or faster execution windows.
- **Time Trends**:
  - Fraud spikes between 12 AM – 2 AM.
  - Wednesday had the highest overall fraud rate.

### 2. User Behavior Insights
- **Age Groups**:
  - Users aged **36–45** had the highest average transaction amounts.
  - **18–25** age group showed lower spending but higher activity.
- **State-wise Spending**:
  - Users from **Andhra Pradesh** and **Rajasthan** spent more per transaction than others.
- **Device Usage**:
  - **iOS users** spent slightly more per transaction than Android/Web users.
- **Network Trends**:
  - **5G** had the highest average transaction amount.

### 3. Temporal Behavior
- **Transaction Volume**:
  - Peaks observed around **12 PM** and **8 PM**.
- **Day of Week**:
  - Mondays and Fridays recorded the highest number of transactions.
- **Weekend Behavior**:
  - Weekends showed **higher average transaction amounts** than weekdays, indicating leisurely or bulk spending patterns.

### 4. Merchant and Transaction Type Insights
- **Fraud-prone Transaction Types**: Bill Payments and Recharges had the highest fraud rates.
- **Fraud-prone Categories**: Healthcare and Food had relatively high fraud incidence.
- **Low-risk Category**: Education showed zero recorded frauds.

---

## 5. Visualizations

Included plots:
- Fraud rate by hour of day and day of week
- Average transaction amount by device, network, and user group
- Transaction volume trends
- Category-wise fraud comparison


