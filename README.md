# Forest Fire Weather Index Analysis and Prediction

**Project Overview:**

The "Forest Fire Weather Index Analysis and Prediction" project aims to analyze and predict forest fire weather conditions using data from Algeria. The project utilizes the Algerian Forest Fires Dataset sourced from Kaggle, which provides valuable insights into various environmental factors contributing to forest fire occurrences. The workflow involves exploratory data analysis (EDA) followed by model training and prediction using linear, Lasso, and Ridge regression techniques. Among these, the Ridge regression model emerged as the most effective in predicting forest fire weather index.

**Dataset:**

The dataset used in this project can be accessed through the following link: [Algerian Forest Fires Dataset](https://www.kaggle.com/datasets/nitinchoudhary012/algerian-forest-fires-dataset). It contains information on meteorological and environmental variables such as temperature, relative humidity, wind speed, rain, and forest fire weather index. These variables are crucial for understanding the dynamics of forest fire occurrences.

**Project Workflow:**

1. **Exploratory Data Analysis (EDA):**
   - Conducted thorough exploration of the dataset to understand its structure, patterns, and distributions.
   - Analyzed correlations between different features and the forest fire weather index.
   - Visualized key insights using various graphs and charts to gain a deeper understanding of the data.

2. **Model Training:**
   - Utilized linear regression, Lasso regression, and Ridge regression techniques to train predictive models.
   - Evaluated the performance of each model based on metrics such as mean squared error, R-squared value, and cross-validation scores.
   - Identified Ridge regression as the optimal model for predicting forest fire weather index due to its superior performance.

3. **Model Persistence:**
   - Saved the trained Ridge regression model into a .pkl (pickle) format for future use.
   - Additionally, saved the StandardScaler object used for feature scaling alongside the model for consistent preprocessing of input data during predictions.

4. **Web Application Development:**
   - Developed an index page using HTML to provide a user-friendly interface for interacting with the predictive model.
   - Integrated Flask, a Python web framework, to establish communication between the HTML page and the Ridge regression model.
   - Users can input meteorological data through the web interface, and the model predicts the forest fire weather index, providing valuable insights for risk assessment and management.

**Usage:**

To replicate and extend this project, follow these steps:

1. Download the Algerian Forest Fires Dataset from the provided Kaggle link.
2. Perform exploratory data analysis to understand the characteristics of the data.
3. Implement model training using linear regression, Lasso regression, and Ridge regression techniques.
4. Evaluate model performance and select the most suitable model for prediction.
5. Save the trained model and preprocessing objects into .pkl files for future use.
6. Develop a web application using Flask and HTML to enable users to interact with the predictive model.
7. Deploy the web application to a suitable hosting platform for wider accessibility.

**Installation:**

Before running the project, ensure you have installed all the necessary dependencies. You can install them using the following command:

```
pip install -r requirements.txt
```

**Acknowledgements:**

We would like to express our gratitude to the creators of the Algerian Forest Fires Dataset available on Kaggle for providing valuable data for this project. Additionally, we thank the open-source communities behind Python, scikit-learn, Flask, and other libraries used in this project for their contributions.

**License:**

This project is licensed under the [License Name] License - see the [LICENSE](link) file for details.
