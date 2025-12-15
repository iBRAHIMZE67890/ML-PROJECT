Machine Learning Project Report
Introduction
This project focuses on building a machine learning based system to predict product cost using historical sales and tax data. The main objective was to understand the dataset, clean and preprocess it properly, and then develop a reliable regression model that can accurately estimate product cost. The project also includes saving the trained model and creating a simple user interface for practical use.
Dataset Understanding
The dataset contains information related to products, quantities, rates, taxes (CGST and SGST), units of measurement, and total amounts. Before model development, an initial inspection was carried out to understand the structure of the data, identify missing values, duplicates, and examine the relationships between different variables.
Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to gain insights into data distributions and relationships among variables. Summary statistics and visual inspections helped identify patterns and dependencies between fields such as rate, quantity, amount, and tax-related columns. This step was essential to detect redundant or derived columns and to understand how different features influence product cost.
Data Preprocessing and Feature Engineering
Data preprocessing involved cleaning the dataset by removing duplicates and handling categorical variables. Several columns were analyzed to check whether they were directly derived from others, such as amount from quantity and rate, and tax amounts from taxable values. Redundant columns were removed to avoid multicollinearity and to improve model performance. Categorical variables like product name and unit of measurement were encoded into numerical form so they could be used in machine learning algorithms.
Target Variable and Feature Selection
The target variable for this project was product cost, while the remaining relevant columns were used as input features. Careful selection of features ensured that only meaningful and independent variables were passed to the model, improving prediction accuracy and reducing unnecessary complexity.
Model Development
The dataset was split into training and testing sets to evaluate model performance fairly. A regression-based machine learning model was trained using the processed data. Standard preprocessing steps such as encoding and scaling were applied where necessary to ensure consistency and stability during training.
Model Evaluation
The trained model was evaluated using standard performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score. These metrics helped assess how well the model predicts product cost and how closely the predicted values match the actual values. The results showed that the model performs reliably on unseen data.
Model Saving and Deployment
After successful training and evaluation, the model was saved using the joblib library. This allows the model to be reused without retraining. Additionally, a simple Gradio-based user interface was developed, enabling users to input product details and obtain cost predictions easily.
Conclusion
This project demonstrates a complete machine learning workflow, starting from data understanding and preprocessing to model training, evaluation, and deployment. The final system provides an efficient and practical solution for predicting product costs and can be further improved by using more data or experimenting with advanced models in the future.


Submitted by: IBRAHIM ZAHEE
Course / Subject: MACHINE LEARNING
Instructor: PROF.HASSAN MUJTABA
