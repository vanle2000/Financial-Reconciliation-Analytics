# Financial-Reconciliation-Analytics
Designed an end-to-end data pipeline automating the ingestion of monthly bank transactions from Google Sheets into BigQuery. Engineered SQL stored procedure within BigQuery to automate reconciliation of banking transactions. Integrated BigQuery to Colab for advanced analytics and utilized predictive modeling to perform churn prediction and cashflow


# What is financial reconciliation? 
Financial reconciliation is an accounting process where businesses compare two sets of financial data. The main goal is to ensure the information is correct and identify and resolve any discrepancies early on in the accounting process.

The financial reconciliation process
Financial reconciliation involves checking and matching internal records with external documents, such as invoices, receipts, and bank statements.

Businesses do reconciliation regularly to maintain the integrity of financial records and promptly address discrepancies [1].


# Challenges:
1. Accountants deal with vast amounts of unstructured and inconsistent data from multiple sources such as banks, POS, billing systems, and internal databases.

Before reconciliation even begins, teams are forced to manually clean, map, and normalize this messy data, which is filled with errors, inconsistencies, and varying formats, rendering ingestion and processing a time-consuming and error-prone process.

2. Reconciliation often relies on a complex set of matching rules to identify corresponding transactions across different systems. Creating and maintaining these rules manually is labor-intensive and requires not only deep domain expertise, but also familiarity with your company’s specific processes, naming conventions, and historical patterns.

Moreover, static rules may not adapt well to new transaction patterns or exceptions, leading to increased mismatches and exceptions that need manual review.

3. Discrepancies happen in the reconciliation process all the time, whether it’s one-off errors, fraud, or systemic issues like unexpected fees or tax discrepancies. While manual reconciliation processes can detect these issues, the pressure is still on finance teams to explain why the discrepancies occurred, leading to lengthy and often tedious investigations.


# Citation:
[1] https://www.adyen.com/knowledge-hub/financial-reconciliation
[2] https://www.ledge.co/content/ai-reconciliation#:~:text=AI%20models%20are%20now%20sophisticated,match%20structured%20records%201:1.
