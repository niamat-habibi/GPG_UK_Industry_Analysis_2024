# 📊 Gender Pay Gap Analysis in the UK by Industry (Real-World Data)

This project explores the Gender Pay Gap (GPG) across major industries in the United Kingdom using real-world hourly earnings data. The analysis was completed as part of the **Google Advanced Data Analytics Certificate** under the course **"The Power of Statistics"**, focusing on statistical thinking, descriptive analysis, and inferential testing.

---

## 📁 Dataset

- **Source:** [ILOSTAT - International Labour Organization](https://ilostat.ilo.org/)
- **Title:** Average Hourly Earnings by Sex and Industry
- **Country Selected:** United Kingdom
- **Data Format:** CSV
- **Dimensions:** Industry, Gender, Earnings

---

## 🎯 Objective

To examine and quantify:
- Differences in average hourly earnings between men and women
- Dispersion (variation) of earnings within each gender
- Statistical and practical significance of these pay differences using:
  - Confidence intervals
  - Two-sample t-tests
  - Cohen’s *d* effect sizes

---

## 🧪 Methodology

### 1. **Data Preparation**
- Filtered for United Kingdom only
- Selected latest available year (2022)
- Cleaned industry names for clarity
- Pivoted the table to separate Male and Female earnings

### 2. **Descriptive Statistics**
- Calculated:
  - Mean earnings for males and females
  - Standard deviation of earnings for each gender
  - Gender Pay Gap (%)
- Visualized data with:
  - Bar charts
  - Normal distribution plots

### 3. **Inferential Statistics**
- Constructed **95% confidence intervals** for mean differences
- Ran **Welch’s two-sample t-tests** for each industry
- Calculated **Cohen’s d** for effect size

---

## 📈 Key Visuals

- 📊 Bar plot of Gender Pay Gap by Industry  
- 📉 Normal distribution curves of male and female earnings  
- 📏 Error bars for confidence intervals  
- 🧮 Cohen’s *d* chart showing practical effect size

---

## ✅ Final Conclusion

This analysis shows that the Gender Pay Gap is both **statistically significant and practically large** in several high-paying sectors in the UK.

### 🔹 Major Findings

| Insight                                   | Summary                                                                 |
|------------------------------------------|-------------------------------------------------------------------------|
| **Persistent Pay Gap**                   | Women earn ~23–30% less in Finance, Manufacturing, ICT                 |
| **Greater Dispersion in Male Earnings**  | Standard deviation: Males = £4.84, Females = £3.60                      |
| **Statistical Significance**             | Confirmed by t-tests and confidence intervals                          |
| **Effect Size**                          | Cohen’s *d* shows large practical differences in key industries         |
| **Less Inequality in Education/Health**  | Gaps are negligible and statistically insignificant                    |

### 📌 Takeaway

The gender pay gap in the UK is not just about averages. It reflects deeper structural inequality in earnings **spread**, **access to high-paying sectors**, and **opportunity distributions**. This analysis supports policy and organizational change by combining rigorous statistics with practical interpretation.

---

## 🛠️ Tools Used

- **Python** (Pandas, NumPy, SciPy, Matplotlib, Seaborn, Tabulate)
- **Jupyter Notebook**
- **Markdown for documentation**

---

## 📜 License

Open-source for educational and non-commercial use. Please cite the ILOSTAT data source if reusing.

---

## 🙌 Acknowledgments

This project was completed as part of the **Google Advanced Data Analytics Certificate** capstone, under the course:  
**The Power of Statistics – Module: Measures of Central Tendency, Dispersion, and Inferential Thinking**

---

## 🌐 Contact

**Created by:** Niamatullah Habibi  
📧 [Your Email or LinkedIn]  
🔗 [LinkedIn Profile or GitHub Repo]

