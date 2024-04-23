# Enhancing Netflix Growth through Choice-Based Conjoint Analysis

This project uses conjoint analysis techniques to explore Netflix subscription preferences based on customer survey data. By employing logistic regression, the analysis identifies which subscription attributes, such as pricing and content options, are most influential in subscriber decision-making. The findings from this project can help understand customer preferences, forming potential strategies for Netflix.

### Data Management:

**Loading and Cleaning Data:** I used Pandas library to load and preprocess survey data, to ensure data quality for the analysis.

**Handling Categorical Data:** I transformed categorical data into dummy variables for logistic regression analysis, to quantify the impact of each attribute.

### Project Pipeline:

**Data Preparation:** I seperated the dataset into dependent (target) and independent (features) variables, removing unnecessary identifiers and converting categorical variables into dummy variables.

**Regression Analysis:** I implemented logistic regression using the Statsmodels library to estimate the impact of each subscription attribute on the likelihood of selection.

**Visualization of Results**: Finally, utilized Matplotlib to create visual representations such as bar charts and lollipop charts to demonstrate the attribute importance and coefficients.

### Addressed Business Questions:

**Customer Preferences:** Identified key attributes that influence subscription decisions such as content type and price.

**Pricing Insights:** Evaluated how sensitive subscribers are to different pricing tiers.

**Ad Frequency Impact:** Assessed customer tolerance to various levels of advertisement frequency.

**Content Strategy:** Explored how additional content options might affect subscription growth.

### Visualizations Depicted:
- Bar Chart: Showcased which features significantly impact customer choice, with important attributes highlighted.
- Lollipop Chart: Detailed the influence of different pricing on customer choices.
- Treemap: Displayed the relative importance of features like the number of accounts, extra content, and advertisement frequency using a treemap.
