# BMD-Data-Analysis
This project aims to develop a machine learning model to predict the risk of bone fractures based on individual characteristics such as age, gender, weight, height, medication use, and bone mineral density (BMD). The project uses a dataset containing these features for a group of individuals, some of whom have experienced fractures.<br>

Methodology:<br>

1. Data Loading and Preprocessing: The project starts by loading the dataset and performing data cleaning steps, including handling missing values, removing outliers and converting categorical variables to numerical representations.<br>

2. Exploratory Data Analysis: Descriptive statistics and visualizations are used to explore the data and understand the distributions of features and their potential relationships with the target variable (fracture risk).<br>

3. Feature Engineering: Relevant features are selected and transformed as necessary to improve model performance.<br>

4. Model Training: A Logistic Regression model is trained on the preprocessed data to predict fracture risk. The dataset is split into training and testing sets to evaluate the model's performance.<br>

5. Model Evaluation: The trained model's performance is evaluated using metrics such as mean absolute error (MAE), mean squared error (MSE), root mean squared error (RMSE), and R-squared (R2). These metrics quantify the model's accuracy and predictive capabilities.<br>

6. Model Deployment: The trained model and scaler are saved using pickle, enabling predictions on new data.<br>

Feel free to download the data and code.
