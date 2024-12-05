# Sunspot-Forecasting

This code forecasts sunspot numbers from daily, monthly, and annual datasets using Facebook Prophet. Predictions are assessed using metrics like MAE and R2, data is preprocessed, and models are tuned for trends and seasonality. Prophet's versatility and precision in assessing patterns of solar activity are demonstrated by the visualizations.

## Acknowledgements

I want to express my gratitude to Pace University's Computer Science Department and Professor Krystyn Gutu for giving me the opportunity to work on this project as part of the CS675: Introduction to Data Science course and for her  guidance. 
The forecasting models have been effectively implemented thanks in large part to the project's structure and resources, which include datasets from SILSO, or Sunspot Index and Long-term Solar Observations. Additionally, I am grateful to the open-source Python community and Facebook Prophet developers for producing the documentation and tools that enabled this effort.
## Installation

 Install core dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

Install Facebook Prophet (for time series forecasting)
pip install prophet

Install Plotly for interactive visualizations
pip install plotly

  
    ## Color Reference

| Color  References           | 


	1.	Black dots:
	•	Represent the observed data points.
	•	Color code: Close to black (#000000).
	2.	Blue line:
	•	Represents the forecast or trend line.
	•	Color code: Typically medium blue (#1f77b4 or similar).
	3.	Light blue shaded region:
	•	Represents the confidence interval or uncertainty range.
	•	Color code: Light blue or cyan-like (#a6cee3 or similar).
