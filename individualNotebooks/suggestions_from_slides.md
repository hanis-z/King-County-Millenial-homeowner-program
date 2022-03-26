# Project Suggestions (from project launch slides)

## EDA
- [ ] Pandas data frame
	- [ ] Shape of data
	- [ ] Number of NaNs
	- [ ] Distinguish between continuous / categorical features
- [ ] Visualization
	- [ ] Histograms
	- [ ] Bar charts
	- [ ] Boxplots for outliers
	- [ ] Scatterplots
	- [ ] Pairplots
	- [ ] Heatmaps
- [ ] Maps
	- [ ] Folium / Geopandas

## Data Preparation / Feature Engineering
- [ ] General prep
	- [ ] Deal with NaNs, outliers, and duplicates
	- [ ] Scaling
	- [ ] Transformations
- [ ] Feature Engineering
	- [ ] One-Hot Encoding
	- [ ] Polynomial features
	- [ ] Interactions
	- [ ] Custom transformations

## Iterative Model Building
- [ ] First Simple Model
	- [ ] Simple regression with 1 highly correlated feature
- [ ] Iterative model building
	- [ ] Add features aligned to your business questions
- [ ] Check regression assumptions: With each iteration, check whether your model violates [assumptions](https://people.duke.edu/~rnau/testing.htm) of linear regression
	- [ ] 1. Linear relationship between IV and DV (don't include predictors that don't correlate)
	- [ ] 2. Low multicollinearity among predictors: Check scatterplots between features
	- [ ] 3. Residual errors are normally distributed: Q-Q plot, histogram of residuals, Jarque-Bera (what is the cutoff)
	- [ ] 4. Residual errors are homoscedastic
	- [ ] 5. No autocorrelatio: Durbin-Watson (cutoff?)
- [ ] Calculate regression metrics
	- [ ] Maximize R-squared
    

