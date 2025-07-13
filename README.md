# Loan Prediction Approval

This project is a simple web application that predicts loan approval based on user input or CSV file uploads. It uses basic rules for CIBIL score and income to determine loan eligibility.

## 🔍 Features

- Manual entry for customer name, CIBIL score, and income.
- CSV file upload to process multiple customer records at once.
- Visual feedback with success and error messages.
- Buttons to simulate opening Weka and Power BI applications.

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## 📊 Loan Approval Rules

- **CIBIL Score < 600** → Loan Denied (Low CIBIL Score)
- **Income < ₹25,000** → Loan Denied (Insufficient Income)
- **Otherwise** → Loan Approved

## 📁 How to Use

### 1. Manual Entry

- Enter customer name, CIBIL score (300–900), and monthly income.
- Click **Predict Manually** to get the result.

### 2. File Upload

- Upload a CSV file with the following format:

```csv
Customer Name,CIBIL Score,Monthly Income
John Doe,750,30000
Jane Smith,580,28000
