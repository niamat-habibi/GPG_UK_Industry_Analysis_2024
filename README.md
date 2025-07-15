# Gender Pay Gap Analysis – United Kingdom (2024)

## Objective
This project analyzes and quantifies the gender pay gap in average hourly earnings across major industries in the United Kingdom using official data from the ILOSTAT database (2024). It identifies sectors where the disparities are most significant and examines both average differences and variability in earnings between male and female employees.

---

## Problem Statement
Despite significant global progress toward gender equality, the gender pay gap (GPG) remains a persistent issue in many economies. In the UK, this gap continues to influence labor market dynamics, economic fairness, and the formulation of evidence-based policy.

This project investigates the magnitude and nature of the gender pay gap across sectors and evaluates whether these gaps are statistically and practically significant.

---

## Project Goals
- Calculate and visualize gender-based differences in average hourly earnings  
- Explore measures of central tendency (mean, median) and dispersion (standard deviation, variance)  
- Examine the shape of earnings distributions using normal curves  
- Perform inferential statistical tests (confidence intervals, t-tests, effect size)  
- Draw meaningful conclusions about pay equity across UK industries  

---

## Data Source

- **Primary Source**: [ILOSTAT – International Labour Organization](https://ilostat.ilo.org/data/)  
- **Dataset Title**: Average hourly earnings by economic activity (disaggregated by sex), 2024  
- **Country**: United Kingdom  
- **Data Format**: CSV (cleaned subset used for this analysis)

- 📁 **Download Dataset Used in This Project**:  
  [Google Drive CSV – Gender Pay Gap UK (2024)](https://drive.google.com/file/d/1WWDAfzEwrNX92RLVtbA4qUOSp1d4RA3o/view?usp=sharing)

---

## Tools and Techniques
- **Python**: pandas, numpy, scipy, matplotlib, seaborn  
- **Statistical Methods**:  
  - Descriptive statistics (mean, std dev, quartiles, percentiles)  
  - Normal distribution visualization  
  - Confidence intervals for mean differences  
  - Two-sample t-tests  
  - Effect size (Cohen’s d)  

---

## Key Insights

### 1. Gender Pay Gap Exists Across Industries
- Male average hourly earnings are consistently higher across most sectors.
- Women earn approximately **15–35% less** than men in key industries such as finance, manufacturing, and ICT.

### 2. Male Earnings Are More Dispersed
- Standard deviation for male earnings is **£4.84**, indicating wider variability.
- Female earnings have a smaller standard deviation (**£3.60**), showing more consistency.

### 3. Statistical Significance Confirmed
- In industries like **Finance**, **Manufacturing**, and **ICT**, the pay gap is both statistically and practically significant.
- In **Education** and **Health & Social Work**, the gap is smaller or statistically insignificant.

---

## Final Visualizations
- Bar charts showing average male vs. female earnings per industry  
- Gap (%) by industry  
- Distribution curves highlighting earnings spread (normal distribution with standard deviation)  
- Confidence interval plots and annotated test statistics  

---

## Outputs
- `GPG_UK_Industry_Analysis_2024.ipynb` – main notebook with all code, plots, and interpretations  
- `README.md` – documentation and summary  
- `summary_statistics.csv` – optional export of cleaned, computed results  

---

## Conclusion
This project demonstrates that the gender pay gap in the UK is not only an issue of average differences, but also one of distributional inequality. Combining descriptive and inferential statistics provides a more complete view of how gender impacts pay across sectors. These findings can support policy recommendations, HR equity reviews, or further academic research.

---

## Project Links
- **GitHub Repository**: [GPG_UK_Industry_Analysis_2024](https://github.com/niamat-habibi/GPG_UK_Industry_Analysis_2024/)
- **Data Source Website**: [ILOSTAT Official Site](https://ilostat.ilo.org/data/)
- **Dataset Used (Google Drive)**: [Download CSV](https://drive.google.com/file/d/1WWDAfzEwrNX92RLVtbA4qUOSp1d4RA3o/view?usp=sharing)

---

## Contact
- **Name**: Niamatullah Habibi  
- **LinkedIn**: [linkedin.com/in/niamatullah-habibi](https://www.linkedin.com/in/niamatullah-habibi)  
- **Email**: [ni_habibi@yahoo.com](mailto:ni_habibi@yahoo.com)

---

## License
MIT License  
This project is open-source and available for educational or analytical use.
