# UPI Transaction Analysis

## 📌 Overview
This repository contains an analysis of **Unified Payments Interface (UPI) transactions** from **January 2023 to December 2023**. UPI is a widely used digital payment system in India that enables instant **fund transfers between bank accounts**.

## 📂 Dataset Description
The dataset includes UPI transaction records with the following attributes:

### **Columns**
- 🗓 **Date**: Date of the transaction.
- 🏷 **Category**: Type of transaction (e.g., groceries, utilities, transportation).
- 🔢 **RefNo**: Transaction reference number for tracking.
- 💰 **Withdrawal**: Amount debited from the account.
- 💵 **Deposit**: Amount credited to the account.
- 🏦 **Balance**: Account balance after the transaction.

---

## 📊 **Key Insights**

### 🔴 **Withdrawals**
- **🏠 Rent**:
  - High, consistent withdrawals, indicating a fixed monthly expense.
  - Minimal variance (stable spending pattern).
- **🔀 Miscellaneous (Misc)**:
  - **Highest variance** in withdrawals, meaning large unpredictable expenses.
  - Includes **big purchases, emergency spending, or one-time transactions**.
  - **Pie & bar charts** show that Misc accounts for a large portion of spending, requiring better categorization.

### 🟢 **Deposits**
- **💼 Salary**:
  - The most consistent and predictable deposit source.
  - Low variance, reinforcing **salary as a stable income stream**.
- **🔄 Miscellaneous Deposits**:
  - Includes **irregular income** such as refunds, bonuses, or transfers.
  - Pie charts show a **large portion of deposits fall under Misc**, indicating a need for better income classification.

### 🔥 **Correlation Heatmap Analysis**
- **Withdrawal vs Deposit (-0.03)** ➝ No significant relationship; deposits and withdrawals occur **independently**.
- **Withdrawal vs Balance (0.17)** ➝ Weak positive correlation, suggesting some withdrawals are followed by deposits.
- **Deposit vs Balance (0.37)** ➝ **Moderate positive correlation**, meaning **higher deposits lead to a stable account balance**.

---

## ✅ **Key Takeaways**
- **🏠 Rent is a predictable fixed expense**, while **Miscellaneous transactions require further classification**.
- **💼 Salary deposits ensure financial stability**, but irregular income (Misc) needs monitoring.
- **📈 Deposits have a stronger impact on balance than reducing withdrawals**.
- **💳 Tracking irregular transactions** can help in **better financial planning**.

---

## 📌 **Conclusion & Recommendations**
- **Categorizing Misc transactions** more precisely will improve spending & income tracking.
- **Stabilizing deposits** (such as salary) can help maintain a healthier balance.
- **Reducing unnecessary withdrawals** in the Misc category will lead to better savings.
- A **detailed classification of transactions** will enhance financial planning.

---

## 🚀 **Next Steps**
- Implement **automated transaction categorization** using machine learning.
- Create a **dashboard for real-time expense tracking**.
- Analyze **seasonal spending patterns** to optimize financial planning.

This analysis provides a **data-driven perspective on UPI transactions**, helping users understand spending patterns and optimize financial decisions. 📊💰

