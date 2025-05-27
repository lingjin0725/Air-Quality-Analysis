
## Air Quality Analysis in Urban Italy Using Multivariate Techniques

This repository contains a comprehensive analysis of urban air quality using multivariate statistical methods. The project was completed as part of the course *Model-Based and Data-Based Methods for Data Analytics* and explores pollutant dynamics using PCA, hierarchical clustering, and correlation analysis.

### Project Overview

Air pollution significantly affects urban health and environmental quality. This project analyzes the "Air Quality" dataset from the UCI Machine Learning Repository, which includes hourly measurements of pollutants and meteorological data in an Italian city over one year (March 2004 – February 2005).

We aimed to answer key questions:
- What are the relationships among different air pollutants?
- How do pollutant levels vary across seasons and hours of the day?
- What influence do meteorological conditions have on pollution patterns?

### Methods Used

- **Data Cleaning**: Handled missing values (-200), dropped columns with >30% missing, merged date/time fields.
- **Exploratory Data Analysis (EDA)**: Correlation matrix, time series plots, seasonal/hourly trend analysis.
- **Principal Component Analysis (PCA)**: Reduced dimensions and revealed pollutant/meteorology patterns.
- **Hierarchical Clustering**: Identified rush hour and winter season pollution clusters.
- **Normality Testing**: Q-Q plots and Shapiro-Wilk tests confirmed non-normality; PCA still robust.

### Key Visuals

- Correlation heatmap (CO, NOx, Benzene ~ r > 0.79)
- PCA scree plot and biplot
- Hourly CO concentration peaks during rush hours
- Seasonal patterns showing higher pollution in winter
- Q-Q plots illustrating non-normal pollutant distributions

### Insights

- CO, NOx, NO₂, and Benzene levels are closely linked to traffic emissions.
- Winter months show increased pollution due to heating and atmospheric inversions.
- Temperature and humidity affect pollutant dispersion but are not direct emission sources.
- Multivariate methods like PCA and clustering reveal hidden temporal and meteorological patterns.

### Limitations

- The dataset is limited to one city over one year.
- Sensor drift and missing data could introduce uncertainty.
- Pollutant distributions are not normally distributed.

### References

- UCI Air Quality Dataset: https://archive.ics.uci.edu/dataset/360/air+quality
- Final Report: Project Report Team 1.pdf

### Acknowledgements

This project was developed collaboratively by Team 1 for the course *Model-Based and Data-Based Methods for Data Analytics* during Spring 2025. Special thanks to the UCI Machine Learning Repository for providing the dataset.
