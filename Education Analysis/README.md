# Education Project

> Aanalysis examining relationships between ACT scores and socioeconomi, and school funding factors. The goal of  the analyss is to identify predictors of students academic performance, namely ACT score, and producing clear visualizations for reliable interpretation.

---

## Project Overview

Examining the correlation between ACT scores and socioeconomic and funding variables to understand which financial and demographic factors are most associated with students' average ACT performance.

- **Objective:** dentify and quantify relationships between ACT scores and socioeconomic/funding predictors; evaluate full and reduced regression models and provide diagnostics.
- **Domain:** Education
- **Key Techniques:** Regression analysis, missing-data imputation, exploratory data analysis, visualization.
---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** Link to the data source(s) [EdGap_data.xlsx](https://www.edgap.org/), [ccd_sch_029_1617_w_1a_11212017.csv](https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0), [elsec17t.xls](https://www.census.gov/data/tables/2017/econ/school-finances/secondary-education-finance.html)
- **Description:** District or school-level data including average ACT scores, socioeconomic indicators (unemployment rate, percent college, median income, percent lunch), and school type flags (charter, state), and per-pupil expenditures, instructor salaries and benefits. Data are processed into a single analysis dataframe with imputed missing numeric values.
- **License:** Refer to original data sources for licensing terms.

---

## Analysis

Load and clean the data, fill missing values, and check basic distributions and correlations for both socioeconomic and school funding variables/predictors. Run simple regressions, then fit a full funding model and a reduced funding model, add socioeconomic predictors to the reduced model, and use residual plots to check model quality.

---

## Results

Funding variables alone explain only a small part of ACT variation and some variables are highly correlated, which makes coefficients somewhat unreliable. Adding socioeconomic factors (income, college rate, free-lunch rate, unemployment) more clear explanation and often shows equal or larger effects than individual funding variables.

---

## Authors

- [@Alex Song](https://github.com/alexsong-lab)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Python libraries: pandas, numpy, scikit-learn, statsmodels, seaborn, matplotlib
- Edgap and School_info anaysis codes referenced from the in-class notes for SU DATA 5100 
