### Project Title

Sales Prediction

**Author**

Faiz Shabo

#### Executive summary

#### Rationale
Why should anyone care about this question?

The idea for caring about predicting sales is that accurate sales forecasts are crucial for businesses to make informed decisions regarding inventory management, resource allocation, marketing strategies, and overall business planning. By understanding and predicting sales patterns, companies can optimize their operations, minimize costs, and maximize revenue.

#### Research Question
What are you trying to answer?

"Can we accurately predict sales based on the available features in the dataset?"

#### Data Sources
What data will you use to answer you question?

The data used to answer the question comes from the train.csv file located in the train directory.

#### Methodology
What methods are you using to answer the question?

The methodology used to answer the question involves the following steps:

Data Loading and Preprocessing: Loading the train.csv data into a pandas DataFrame, handling missing values in the 'Postal Code' column by imputing with the mode, and applying one-hot encoding to the categorical features.

Data Splitting: Splitting the processed data into training and testing sets.

Model Selection and Training: Choosing and training a RandomForestRegressor model on the training data.

Model Evaluation: Evaluating the trained model's performance on the testing data using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score.


#### Results
What did your research find?

We found that the RandomForestRegressor model trained on the processed data achieved the following results on the test set:

Mean Absolute Error (MAE): Approximately 164.52
Mean Squared Error (MSE): Approximately 461109.84
R-squared (R2): Approximately 0.31
The R-squared value of 0.31 suggests that the model explains about 31% of the variance in the sales data.


#### Next steps
What suggestions do you have for next steps?

The next steps to potentially improve the model's performance:

Feature Engineering: Explore creating new features from existing ones, such as extracting information from the date columns (e.g., day of the week, month, year, or time since the order).

Exploring Other Models: Try different regression models, such as Gradient Boosting Machines (like LightGBM or XGBoost), Support Vector Regression, or even simpler models like Linear Regression to see if they yield better results.

Hyperparameter Tuning: Optimize the hyperparameters of the RandomForestRegressor or any other model you try using techniques like GridSearchCV or RandomizedSearchCV.

Outlier Detection and Handling: Investigate if there are outliers in the 'Sales' data or features that might be negatively impacting the model's performance and consider methods to handle them.

More Advanced Encoding: For categorical features with a high number of unique values (like 'Customer Name' or 'Product Name'), consider more advanced encoding techniques beyond one-hot encoding, such as target encoding or feature hashing, to reduce the dimensionality of the feature space.

Collect More Data: If possible, acquiring more data could also help improve the model's ability to generalize.


#### Outline of project

- [Link to notebook 1]()
- https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting/data
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
