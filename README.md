# 🧠💪 Does brain size allow us to predict intelligence? 📊

## Project Overview 📋

In this project, we explore the fascinating relationship between brain measurements, such as heights and weights, and intelligence quotient (IQ). By leveraging a comprehensive dataset, we delve into the question of whether these brain attributes hold enough predictive power to estimate an individual's intelligence. Our primary approach involves employing linear regression models, including the analysis of variance (ANOVA) technique.

Through rigorous data analysis and statistical modeling, we aim to uncover any potential correlations or associations between brain measurements and IQ. By applying linear regression techniques, we can assess the extent to which brain heights, weights, and other relevant factors can serve as predictors of intelligence. This investigation offers valuable insights into the potential influence of brain attributes on cognitive abilities, furthering our understanding of the complex interplay between the brain and intelligence. 🌟🧠💡

## Technologies Used 💻
- Python
- Pandas
- Matplotlib

## Data Source 📁
The dataset used in this project contains brain heights, weights, and IQ. It serves as the basis for evaluating whether these variables are sufficient to predict intelligence using linear regression models.

## Data Cleaning and Preprocessing 🔧
The data was preprocessed by performing necessary cleaning steps such as handling missing values and outliers. No specific transformations were applied in this project.

## Exploratory Data Analysis 📈
An exploratory data analysis was conducted to understand the relationships between brain measurements (Brain, Height, Weight) and PIQ. A scatter matrix plot was created to visualize these relationships.

``` 
x = brain_data[['Brain', 'Height', 'Weight']]
y = brain_data['PIQ']

pd.plotting.scatter_matrix(x, alpha=0.2, figsize=(8, 8), diagonal='hist')
plt.show()
``` 
## Feature Engineering ⚙️
No explicit feature engineering techniques were applied in this project. The original features (Brain, Height, Weight) were used as predictors.

## Machine Learning Models 🚀
Linear regression models (OLS) were implemented to predict PIQ based on brain measurements. Initially, a basic model with Brain, Height, and Weight as predictors was constructed. Additionally, an enhanced model incorporating interaction terms (Brain*Height) was evaluated.

## Results and Evaluation 📉
The models' performance was evaluated using statistical metrics and the ANOVA table. The R-squared value indicated that the model explained only 29.7% of the variability in PIQ. The p-values for Brain, Height, and Weight were not statistically significant, suggesting that they may not be reliable predictors of PIQ.

## Future Work 💡
To improve the model, potential future work includes considering additional variables related to PIQ, such as education level or socioeconomic status. Collecting more data to increase the sample size and enhance the statistical power of the model could also yield better results.

## Acknowledgments 👏
- Pandas documentation: pandas.pydata.org
- Matplotlib documentation: matplotlib.org
### License 📃
No specific license is mentioned for this project.





