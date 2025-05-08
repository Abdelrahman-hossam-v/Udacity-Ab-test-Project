# 🧪 A/B Test Results Analysis

**Author:** Abdelrahman Hossam  
**Tools Used:** Python, Pandas, Matplotlib, Seaborn  

---

## 📌 Project Description

This project investigates the results of an A/B test conducted by an e-commerce website. The goal is to determine whether a new landing page leads to a higher conversion rate than the old one.

---

## 📂 Dataset

- **File:** `ab_data.csv`  
- **Rows:** 69,889  
- **Columns:** `user_id`, `timestamp`, `group`, `landing_page`, `converted`, `country`

---

## 🧭 Project Structure

### Part I – Data Overview
- Read the dataset and inspect general structure.
- Checked for missing values.
- Identified column data types.
- Plotted user distribution by country.

### Part II – Probabilities
- Calculated overall conversion rate.
- Calculated conditional conversion rates:
  - For control and treatment groups.
- Compared proportions and group sizes.

### Part III – Statistical Testing (if included)
- Performed hypothesis testing using:
  - Z-test or A/B significance testing.
- Determined if observed difference is statistically significant.

---

## 📊 Key Findings

- **Overall conversion rate:** ~13.05%
- **Conversion (control group):** ~12.04%
- **Conversion (treatment group):** ~13.23%
- The treatment group had a slightly higher conversion rate, but **statistical testing is required** to determine if the difference is significant.

---

## 🧠 Conclusion

Although the new landing page shows a higher conversion rate, the difference may not be statistically significant. Further statistical analysis is needed before making product decisions.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ab-test-analysis.git
