# Exploring Linear Regression with Random Data: Interactive Webpage Project

## Overview
This project investigates the impact of randomness on linear regression estimates through an interactive webpage. The goal is to demonstrate how modifying parameters like sample size, mean, variance, and the number of simulations influences regression results, even when there is no true relationship between the independent variable (X) and the dependent variable (Y). 

By exploring these settings, this project provides insights into how random noise can create variability in the slope and intercept of regression models.

## Key Features

### Interactive Webpage
The project includes a dynamic webpage where users can input the following parameters:
- **Sample size (N):** Number of data points in the dataset.
- **Mean (μ):** Mean of the normal error term added to Y.
- **Variance (σ²):** Variance of the normal error term.
- **Number of simulations (S):** Number of datasets to simulate.

When the "Generate" button is clicked, the following outputs are generated:
1. **Scatter Plot and Regression Line:** A plot showing the random dataset (X, Y) with added noise, alongside the fitted regression line. The slope and intercept values for this line are also displayed.
2. **Histograms of Slope and Intercept Values:** 
   - Simulates S datasets and computes slopes and intercepts for each.
   - Overlays histograms for the slopes and intercepts, marking the values from the initial dataset.
   - Highlights the proportion of slopes and intercepts more extreme than those in the initial dataset.

The generated plot should something like
![image](https://github.com/user-attachments/assets/c8e3a991-f124-47e4-9d1f-7b39063c739e)
 
### Observational Analysis
Users can explore the effects of changing parameters, such as:
- How increasing the sample size reduces variability.
- How higher variance in noise impacts the regression line's accuracy.
- The influence of the number of simulations on histogram distributions.

## Observations and Insights
- Random data often produces non-zero slopes and intercepts due to inherent variability.
- Larger datasets (higher N) tend to produce regression results closer to zero, reflecting less noise impact.
- Higher noise variance (σ²) increases the scatter in data, leading to greater variability in regression outcomes.

## Applications
This project serves as a powerful tool to:
- Understand the effects of randomness in regression models.
- Gain intuition about statistical variability and its implications in real-world data analysis.
- Demonstrate the importance of data size and noise levels in predictive modeling.

## Conclusion
This project highlights how randomness affects linear regression, even when no true relationship exists between X and Y. The interactive nature of the tool fosters a deeper understanding of statistical variability and linear regression principles. It is an excellent educational resource for students, analysts, and anyone interested in statistical modeling.
