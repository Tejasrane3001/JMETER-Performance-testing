# JMETER-Performance-testing
# 🧪 Saucedemo Login Test with Apache JMeter

This project automates the performance testing of the [Saucedemo](https://www.saucedemo.com/) web application using **Apache JMeter**. It verifies the login functionality by simulating multiple users with different credentials and records detailed performance and assertion reports.

---

## 🚀 Objective

- Validate login functionality for multiple users using data-driven testing.
- Measure response times and success rates under load.
- Export test results for analysis and reporting.

---

## 🧰 Tools & Technologies

- [Apache JMeter 5.6.3](https://jmeter.apache.org/)
- CSV Data Set Config (for parameterization)
- Response Assertion
- View Results Tree
- Summary Report

---

## 📂 Project Structure

```plaintext
📁 apache-jmeter-5.6.3
│
├── 📁 backups/
│   └── Saucedemo-000012.jmx       # JMeter test plan
│
├── 📁 Data/
│   ├── credentials.csv            # Login credentials
│   └── ResultTree Saucedemo-001.csv  # Raw test results
│
└── 📁 Reports/
    └── Saucedemo_JMeter_Test_Report.xlsx  # Summary Excel report
