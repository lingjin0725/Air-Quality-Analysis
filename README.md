
# 🌫️ Air Quality Analysis

This project analyzes air pollution patterns in an urban environment using multivariate data analysis techniques like **PCA** and **Hierarchical Clustering**. It was completed as part of the course *Model-Based and Data-Based Methods for Data Analytics*.

---

## 📌 Project Overview

The dataset, sourced from the UCI Machine Learning Repository, includes hourly measurements of air pollutants (CO, NOx, Benzene, etc.) and meteorological variables (temperature, humidity). The goal is to explore relationships, trends, and reduce dimensionality for cleaner insights.

---

## 📁 Project Structure

```
Air-Quality-Analysis/
├── Project_Jupyter_code_Team_1.ipynb       # Main analysis notebook
├── AirQualityUCI.csv                       # Cleaned dataset
├── Project Report Team 1.pdf               # Final PDF report
├── Final_Air_Quality_Portfolio.md          # Notion-exported markdown portfolio
├── visualizations/                         # Contains all output images
│   ├── correlation_matrix.png
│   ├── pca_biplot.png
│   ├── scree_plot.png
│   └── ...
```

---

## 📊 Key Visualizations

- **Correlation Matrix** – Reveals strong relationships among pollutants
- **PCA Biplot & Scree Plot** – Shows variance contribution and variable loadings
- **Hourly/Monthly Trends** – Highlights pollution peaks at rush hours and in winter
- **Q-Q Plot** – Used to assess normality of pollutant distributions

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/lingjin0725/Air-Quality-Analysis.git
   cd Air-Quality-Analysis
   ```

2. Open the notebook:
   - Use **Jupyter Notebook** or **Google Colab** to run `Project_Jupyter_code_Team_1.ipynb`.

3. Required libraries:
   ```
   pandas
   numpy
   matplotlib
   seaborn
   scikit-learn
   ```

Install with pip if needed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ✅ Project Highlights

- Applied **PCA** to reduce dimensionality and visualize variance.
- Used **Hierarchical Clustering** to explore time-based patterns.
- Provided real-world insight into how **traffic and seasonal heating** impact air quality.

---

## 📚 Acknowledgements

- Dataset from: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Air+quality)
- Developed as part of a course project for *Model-Based and Data-Based Methods for Data Analytics*.

---

Feel free to fork, star ⭐️, or suggest improvements!
