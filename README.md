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


6. The output would look something like this:
![image](https://github.com/user-attachments/assets/c8e3a991-f124-47e4-9d1f-7b39063c739e)


   
7. **Create a Short Demo Video (1-2 minutes)**:
   - Create a demo video by screen recording your output with your voice-over.
   - Explain any patterns you observe and discuss what happens when the sample size or noise level changes.
   - Explain whatever you found interesting and your analysis. You can discuss any specific points or specific inputs you want to.
   - Consider why random data might still produce non-zero slopes and intercepts in regression.

8. **Submission**:
   - Submit both your completed code and the demo video link.
   - You can either embed the demo video in your portfolio website or just create an unlisted YouTube video with a link to that YT video in your assignment 6 github repo's readme.

## Key Takeaways

This assignment helps you see how randomness can affect regression estimates. By experimenting with different parameters, you’ll get a better feel for how much variability there can be in slopes and intercepts when there’s no true relationship between `X` and `Y`. Using your observations and analysis will allow you to get a better and deep understanding of Linear Regression.
