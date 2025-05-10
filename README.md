# Experimental Analysis of Hydrocarbon Emissions During Petrol Pumping: Effects of Temperature and Pressure Variables
In 2023, the global energy industry intensified its efforts to reduce environmental impact, particularly from hydrocarbon emissions during petrol storage and transfer. These emissions, mainly volatile organic compounds (VOCs), significantly affect air quality, contribute to ground-level ozone formation, and pose serious public health risks. Regulatory bodies have raised concerns and prompted the industry to develop strategies and predictive models to estimate hydrocarbon release. Such models are essential for regulatory compliance and operational optimization. Key variables influencing these emissions include tank temperature, petrol temperature, initial tank pressure, and petrol pressure. These interconnected factors create complex dynamics that drive evaporation processes. This study aims to build a predictive regression model using data that captures these variables to better understand and control hydrocarbon emissions during petrol handling.

# Objective:
1. Regression Model:
> Construct a model that best fit the given data performing regression
> Estimate corresponding parameters
> Provide a 95% Confidence interval for each of the estimated parameters
> Use Hypothesis Testing to test the significance of Regression

2. Model Adequacy:
> Perform Anova
> Perform Residual Analysis
> Perform Lack of fit test
> Apply corresponding transformation to correct model inadequacies if any.
> Perform Multicollinearity Analysis
> Model Validation

# Key Components:
> Data Exploration and Cleaning
> Correlation Analysis
> Model Building (Full and Reduced Models)
> Hypothesis Testing
> ANOVA
> Residual & Influence Diagnostics
> Model Comparison and Selection

# Result/Conclusion:

This study aimed to develop a predictive regression model for estimating hydrocarbon emissions during petrol storage and transfer, focusing on key operational variables such as tank temperature, petrol temperature, initial tank pressure, and petrol pressure. After an initial full model was constructed, diagnostic tests revealed multicollinearity and non-constant variance, prompting the use of variable selection techniques and model transformation. The final reduced model, which included only petrol temperature and petrol pressure, demonstrated a strong fit with an adjusted R² of 0.9064. This means that the model explains over 90% of the variance in hydrocarbon emissions, making it highly effective for prediction purposes.

Additionally, residual analysis confirmed that model assumptions such as normality and homoscedasticity were reasonably satisfied after log-transforming the response variable. The reduced model not only simplified interpretation but also retained strong predictive power, highlighting petrol temperature and pressure as critical drivers of emissions. These findings provide practical insights for operational control and environmental risk mitigation in the petroleum industry, offering a data-driven basis for regulatory compliance and emissions reduction strategies.

# Usethelog-transformed model if residual diagnostics (normality, homoscedasticity) are critical.
# Usethe non-log-transformed model if higher R2 and interpretability of additive relationships are important.
