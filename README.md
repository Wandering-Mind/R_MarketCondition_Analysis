# R_MarketCondition_Analysis
Analysis and simulation of 3000 trials to determine monthly profits for a company and more. 

The provided R code simulates 3,000 trials to calculate the monthly profits for a wireless security camera product. It first generates random market conditions (either "High" or "Low") with equal probabilities, then uses this information to generate monthly demand, which follows a normal distribution depending on the market condition. It simulates labor costs (uniform distribution between $4 and $6) and material costs (triangular distribution between $3 and $6, with the mode at $5). The selling price is uniformly distributed between $25 and $30, and fixed costs are set at $3,000 per month. Monthly profits are calculated by subtracting the total cost (fixed cost + variable costs) from the revenue (demand * price). The code then prints the first 10 monthly profit values, calculates the proportion of months with a "High" market condition, and generates histograms for the distribution of monthly profits and material costs. The mySummary function is used to compute and display the count, mean, and standard deviation of the profits.


🧰 Tools and Packages Used:
  ggplot2, dplyr, tidyverse: Data manipulation and visualization.
  wordcloud, tm: Text mining and word cloud creation.
  gridExtra: For arranging plots.
  gtools: Simulation and factorial analysis.
  Base R functions for regression and descriptive statistics.

📊 Key Functional Areas:
  Data Import and Cleaning:
    Multiple datasets are loaded from CSV files.
    Cleaned using dplyr (e.g., filtering NAs, renaming columns).
    Ensures the datasets are ready for visualization and modeling.

  Data Visualization (ggplot2):
    Multiple ggplot2 plots (bar charts, histograms, scatter plots) are generated.
    Visual insights include:
      Distributions of variables (e.g., age, gender, satisfaction).
      Relationships between factors (e.g., income vs readmission).

  Text Mining & Word Clouds:
    Text data is tokenized, cleaned (e.g., stopwords removed), and visualized as word clouds.
    Helps highlight frequently used words in patient or customer feedback.

Regression Modeling:
    Multiple linear regression models are built.
    Predictive relationships are explored (e.g., how income affects readmission).
    Summary statistics and model performance are outputted.

  Simulation & Probability:
    Monte Carlo simulations using gtools and replicate to explore probabilistic outcomes.
    Useful for risk analysis and understanding potential future outcomes.




