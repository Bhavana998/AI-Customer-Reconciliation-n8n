# 🚀 AI Customer Reconciliation System (n8n)

AI-powered financial reconciliation system built using n8n for FMCG enterprises (OT / MT / D2C channels).

---

## 📌 Overview

This project solves the real-world problem of **customer reconciliation and claims resolution** in FMCG industries.

Manual reconciliation leads to:

* Delayed financial closure
* Working capital blockage
* Data mismatches (invoices, payments, claims, returns)

This system automates the entire process using **workflow automation + AI-based analysis**.

---

## 🎯 Objectives

* Real-time visibility of customer ledger
* Automated mismatch detection
* Faster dispute resolution
* Reduced manual effort
* Improved working capital efficiency

---

## 🏗️ Architecture

```text
                ┌────────────────────┐
                │   Data Input       │
                │ (Invoices, Payments|
                │  Claims, Returns)  │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │   n8n Workflow     │
                │ (Automation Engine)│
                └─────────┬──────────┘
                          │
        ┌─────────────────┼─────────────────┐
        ▼                 ▼                 ▼
┌──────────────┐  ┌──────────────┐  ┌──────────────┐
│ Data Matching│  │ AI Analysis  │  │ Validation   │
│ & Processing │  |Classification│  │ Data Quality │
└──────────────┘  └──────────────┘  └──────────────┘
        │                 │                 │
        └────────────┬────┴────┬────────────┘
                     ▼         ▼
              ┌────────────────────┐
              │ Reconciliation     │
              │ Report Generation  │
              └─────────┬──────────┘
                        │
                        ▼
        ┌─────────────────────────────────┐
        │ Output                          │
        │ • Report (Text)                 │
        │ • Google Sheets                 │
        │ • Insights & Actions            │
        └─────────────────────────────────┘
```

---

## ⚙️ Tech Stack

* **n8n** – Workflow automation
* **OpenAI** – AI-based classification & insights
* **Google Sheets** – Data storage & tracking

---

## 🧠 Key Features

* End-to-end automated reconciliation
* AI-powered issue detection
* SAP-aligned financial logic (AR / SD / FI)
* Claims and dispute handling
* Data quality validation
* Scalable FMCG-ready design

---

## 🔗 Integration Capability

* ERP Systems (SAP – AR, SD, FI modules)
* Customer sales & claims systems
* Document repositories (Invoices, PODs)

---

## 📊 Business Impact

* Reduced receivable ageing
* Faster reconciliation cycles
* Improved financial transparency
* Increased productivity
* Faster month-end closure

---

## ▶️ How to Run

1. Install and open n8n (local or Docker)
2. Import the `workflow.json` file
3. Open the workflow in editor
4. Click **Execute Workflow**
5. View output in execution logs

> Note: Webhook trigger is included for real-time usage.
> Due to environment limits, manual execution is used for testing.

---

## 📄 Sample Output

A sample reconciliation report is included in this repository.

It demonstrates:

* Financial summary
* Mismatch detection
* AI-generated insights
* Recommended actions

---

## 📸 Screenshots

* Workflow design
* Execution results
* Output report

---

## ⚠️ Constraints

* Tested in limited execution environment
* Uses sample data
* Designed for production scalability

---

## 🚀 Future Enhancements

* Live SAP API integration
* Real-time webhook deployment
* Dashboard (Power BI / Streamlit)
* Predictive analytics for disputes

---

## 👩‍💻 Author

**Bhavana Setty**
B.Tech – Information Technology
AI & Data Science Enthusiast

---

## 🏁 Conclusion

This project demonstrates how **AI + automation** can transform manual reconciliation into a **scalable, intelligent financial system**, aligned with real-world FMCG requirements.
