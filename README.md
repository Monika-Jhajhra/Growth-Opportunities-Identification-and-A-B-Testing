# Growth Opportunities Identification & A/B Testing

## 📌 Overview

This project focuses on identifying growth opportunities for an online travel platform using SQL and validating improvement ideas through A/B testing in Python.

The analysis explored questions such as:

* Which hotels receive high traffic but low bookings?
* Which hotels perform below benchmark conversion rates?
* How much potential revenue is being lost?
* Does improving hotel content quality increase conversion rate?
* Are the experiment results statistically significant?

---

## 🛠️ Tools Used

### SQL

* CTEs
* JOINs
* Window Functions
* KPI & Funnel Analysis
* Benchmark Comparison
* Revenue Opportunity Analysis

### Python

* Pandas
* NumPy
* SciPy
* Statsmodels
* A/B Testing & Hypothesis Testing

---

## 📊 Analysis Performed

### SQL Analysis

* Data cleaning & validation
* Market & inventory analysis
* Conversion analysis
* Benchmark CVR comparison
* Revenue gap estimation
* Opportunity identification for underperforming hotels

Example KPI:

```sql
ROUND(bookings_last_90d * 1.0
      / impressions_last_90d, 4) AS actual_cvr
```

---

### Python A/B Testing

Tested whether improving hotel content scores increased conversion rates.

Analysis included:

* Sample size validation
* Pre-experiment balance checks
* Two-proportion z-test
* Confidence intervals
* Guardrail metric analysis
* Revenue impact estimation

Example:

```python
from statsmodels.stats.proportion import proportions_ztest
```

---

## 📈 Key Insights

* Several hotels had high impressions but low conversion rates
* Poor content quality and pricing competitiveness impacted bookings
* Inventory gaps reduced revenue potential
* Improved content quality generated statistically significant conversion uplift

---

## 📂 Project Structure

```bash
project/
│
├── sql_queries/
├── notebooks/
├── visualizations/
└── README.md
```

---

## 🧠 Skills Demonstrated

* SQL Analytics
* Funnel Analysis
* KPI Development
* Revenue Opportunity Analysis
* A/B Testing
* Hypothesis Testing
* Statistical Analysis
* Business Problem Solving

---

## ✅ Conclusion

This project demonstrates an end-to-end analytics workflow combining SQL, business analysis, and experimentation to identify growth opportunities and validate data-driven business decisions.
