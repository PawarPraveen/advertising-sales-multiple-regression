#  Visualizing Multiple Linear Regression — TV, Radio & Sales Analysis

This project demonstrates **Multiple Linear Regression** using the popular *Advertising* dataset to predict **Sales** based on advertising budgets for TV and Radio.  
The notebook also visualizes the results with **three plots** to analyze the relationship, fitted regression line, and residuals.

# Dataset
We use the Advertising dataset containing:

TV — TV advertising budget (in thousands of dollars)

Radio — Radio advertising budget (in thousands of dollars)

Newspaper — Newspaper advertising budget (in thousands of dollars)

Sales — Sales of the product (in thousands of units)


# Methodology:
1. Load the dataset using pandas.
2. Fix one variable (Radio) at its mean value to isolate the effect of TV on Sales.
3. Predict Sales using the regression equation:
   y_hat = 0.0544 * TV + 0.1072 * (mean of Radio) + 4.6309
4. Plot results:
   - Raw scatter plot
   - Regression line with fixed Radio value
   - Residual plot


