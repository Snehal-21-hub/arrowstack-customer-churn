# Customer Churn Investigation

## Project Overview

This project investigates customer churn using a Telco customer
dataset.

The main objective is to identify customer, contract, service,
billing and demographic characteristics associated with churn,
identify high-churn customer segments, and develop practical
retention recommendations.

---

## Business Problem

Customer churn can affect customer retention and business
performance.

This project investigates:

- Which types of customers are more likely to churn?
- Which contract and service characteristics are associated with
  churn?
- Which customer segments have higher churn rates?
- What reasons do customers report for leaving?
- What retention actions could be considered based on the findings?

---

## Objectives

- Understand the overall customer churn rate.
- Perform data cleaning and quality checks.
- Explore factors associated with customer churn.
- Analyze contract, service, billing and demographic characteristics.
- Analyze reported churn reasons.
- Identify high-churn customer segments.
- Perform statistical validation using Chi-square tests.
- Develop evidence-based retention recommendations.

---

## Dataset

The project uses a Telco customer churn dataset containing
customer-level information related to:

- Demographics
- Customer tenure
- Contract type
- Internet and additional services
- Payment methods
- Monthly and total charges
- Churn status
- Reported churn reasons

The raw dataset is not included in this public repository.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Microsoft Excel

---

## Analysis Performed

The project includes:

- Data inspection
- Missing-value analysis
- Duplicate checks
- Data-type validation
- Data cleaning
- Overall churn analysis
- Contract analysis
- Tenure analysis
- Monthly charge analysis
- Internet service analysis
- Payment method analysis
- Tech Support analysis
- Online Security analysis
- Demographic analysis
- Churn reason analysis
- Customer segmentation
- Chi-square statistical validation
- Business recommendations

---

## Key Findings

- Customers with **0–12 months of tenure** had a churn rate of
  approximately **47.44%**.
- **Month-to-month** customers had a churn rate of approximately
  **42.71%**.
- The **month-to-month + 0–12 months** segment had a churn rate of
  **51.35%**.
- The **medium-high monthly-charge** group had a churn rate of
  approximately **37.51%**.
- **Fiber optic** customers showed a relatively high churn rate.
- **Electronic-check** customers showed a relatively high churn
  rate.
- Customers without **Tech Support** had a churn rate of
  approximately **41.63%**.
- Customers without **Online Security** had a churn rate of
  approximately **41.77%**.
- Frequently reported churn reasons included support experience and
  competitor offerings.

---

## Customer Segmentation

Customers were segmented using:

- Contract type
- Tenure group

The highest observed segment was:

**Month-to-month contract + 0–12 months tenure**

This segment contained:

- 1,994 customers
- 1,024 churned customers
- 51.35% churn rate

---

## Recommendations

Based on the analysis, the project recommends considering:

1. Strengthening customer onboarding and retention efforts during
   the first year.
2. Focusing retention efforts on month-to-month customers.
3. Improving customer support experience and complaint resolution.
4. Monitoring competitor pricing, data offerings and service
   performance.
5. Investigating higher-charge customer segments and perceived
   customer value.

---

## Limitations

- The analysis identifies associations and does not establish
  causation.
- Results are based on the available dataset and may not generalize
  to other customer populations.
- Customer characteristics may be related to one another.
- Reported churn reasons should not be interpreted as proven causes.
- Existing churn-related scores were not used as independent
  explanatory variables.

---

## Project Structure

```text
Customer-Churn-Investigation/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── customer_churn_analysis.ipynb
│
├── reports/
│
├── presentation/
│
├── README.md
└── requirements.txt
