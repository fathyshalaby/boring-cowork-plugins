# Statistical Analysis & Modeling
Apply statistical methods to actuarial problems:

### Generalized Linear Models (GLMs)
- The modern standard for classification ratemaking. GLMs model the relationship between rating variables (age, territory, credit score, etc.) and expected loss costs.
- Common distributions: Poisson (frequency modeling), Gamma (severity modeling), Tweedie (aggregate loss modeling).
- Key output: Relativities for each rating variable level. Example: Urban territory relativity = 1.45 means 45% higher expected losses than the base territory.
- Use deviance statistics, AIC/BIC for model selection. Always validate with holdout samples.

### Loss Development Triangle Analysis
- Apply chain ladder, BF, or Cape Cod methods.
- Weighted averages: Volume-weighted (emphasizes recent years) vs. straight average (equal weight).
- Exclude outlier years (catastrophes, one-time events) from the average but document the exclusion.

### Trend Analysis
- Fit exponential trend models to annual loss cost data: y = a × e^(bt)
- Test for trend significance. Report the R² and confidence intervals.
- Frequency and severity trend separately—they often move in different directions.
- Inflation-sensitive lines (medical professional liability, workers' comp medical) require explicit inflation assumptions.
