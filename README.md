# Mid-Term-Project-Tes-Sean

## Project/Goals

The project centered around the analysis of a Kaggle dataset, providing comprehensive insights into the Airbnb landscape in nine significant European cities, some of which are capital cities. Our primary goal was to leverage this dataset to pinpoint the crucial factors influencing housing prices, customer satisfaction, attractiveness, and restaurant coefficients. Our aim was to present this valuable information in a visual format to assist prospective Airbnb property owners in making well-informed decisions.

## Process
Step 1: Data Cleansing
In the initial phase, our focus was on scrubbing the data, eliminating any inconsistencies or errors to ensure precise analysis.

Step 2: Exploratory Data Analysis (EDA)
Following data cleansing, we embarked on an EDA journey to gain a deeper understanding of the dataset and unearth trends, patterns, or connections between the variables.

Step 3: String Data Encoding
Certain variables within the dataset were in string format. Our task here was to convert these string variables into numerical form, enhancing their suitability for regression analysis.

Step 4: Regression Analysis
Subsequently, we conducted regression analysis to delve into the relationships between various variables, with a particular emphasis on their impact on housing prices, customer satisfaction, and other factors of interest.


### Step 5: Data Visualization
1- Introduction to the Airbnb Europe project and the role of Tableau in visualizing data.
2- Visualizations Created: Briefly describe the types of visualizations you created with Tableau.
3- Tableau and Other Tools: Discuss how Tableau was used alongside tools like GitHub and scikit-learn.

## Results
1- EDA Findings:
- Negative correlation between various indexes and the distance to city centers and subway stations, indicating a preference for shorter distances.
- Positive correlation between these indexes and price.
- Unexpected negative correlation between indexes and Guest Satisfaction and Cleanliness Rating.

2- Regression Analysis Results:
- The city and room type were identified as the most significant factors affecting prices.

3- Analysis of Amsterdam:
- Amsterdam was found to be more expensive with a larger price spread compared to other cities.
- Modeling based on the city was not effective, suggesting that predictions per city might be more insightful.

4- Clustering Analysis:
- Challenges were faced in using Tableau for K-means clustering.
- The study concluded the need to use scikit-learn for a better understanding of clustering results.


   
## Challenges 
1- Ensuring data accuracy and completeness.
2- Analyzing and interpreting categorical variables like room types.
3- Understanding how factors like location affect pricing and guest satisfaction.
4- Investigating the impact of time-related factors, such as weekdays versus weekends.
5- Assessing the influence of being a 'Superhost'.
6- Using and interpreting normalized indices like attraction and restaurant indices.


## Future Goals
1- Enhanced Data Collection and Quality: Aim to further improve the completeness and accuracy of your dataset, possibly by integrating additional data sources or variables that could offer deeper insights.
2- Advanced Analytical Models: Develop more sophisticated statistical or machine learning models to better understand complex relationships within the data, such as predictive models for pricing or guest satisfaction.
3- Dynamic Pricing Strategies: Explore dynamic pricing strategies based on data-driven insights, factoring in variables like location, time of year, and special events.
