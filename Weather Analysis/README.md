# Weather Project

> Compare the precipitation levels between Seattle and Charlotte from January 1, 2018 to December 31, 2022.

---

## Project Overview

Provide a short and concise overview of the project. Mention the problem it solves, the data used, and the key outcomes or findings.

- **Objective:** To compare precipitation patterns in Seattle, WA and Charlotte, NC (2018–2022) and determine which city “rains more” in terms of both volume and frequency.
- **Domain:** Climate
- **Key Techniques:** Time Series, , Hypothesis Testing (t-test, z-test), Data Visualization

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

- **Source:** [NOAA](https://www.ncei.noaa.gov/orders/cdo/4133290.csv)
- **Description:** Daily precipitation datasets from 2018 to 2022.
- **License:** (if applicable)

---

## Analysis

Data cleaning (date parsing, missing-value imputation) and exploratory analysis were performed in Jupyter notebook file included in the code folder. Graphs were generated in order: mean daily precipitation → monthly boxplots → t-test bar plots → z-test proportions bar plot → seasonal proportions → annual means and total line graph. Running the notebook top-to-bottom recreates all results.

---

## Results

Charlotte shows higher precipiation especially in summer, while Seattle shows higher precipitation especially in winter.

---

## Authors

- Alex Song - [@alexsong-lab](https://github.com/alexsong-lab/)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: pandas, numpy, matplotlib.pyplot, seaborn, scipy.
- Tutorials or papers referenced
- Inspiration or collaborators
