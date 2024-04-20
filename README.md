# Decision-Tree-for-Price-Prediction-of-Used-Cars

### Overview
This project aims to predict the selling price of used cars using a Decision Tree Regressor model. The dataset used contains various features such as the type of fuel, seller type, transmission, owner, kilometers driven, etc., which are utilized to predict the selling price.

### Steps
1. **Import Libraries**: Necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn are imported.
2. **Import Dataset**: The dataset is loaded from an online source.
3. **Perform Data Analysis & EDA**: Exploratory Data Analysis (EDA) is conducted to understand the dataset's structure, check for missing values, visualize distributions, and identify patterns.
4. **Data Preprocessing**: Categorical variables are encoded into numerical values using Label Encoding. Additionally, a new feature 'no_of_years' is created representing the age of the car.
5. **Select Features and Targets**: Features (X) and the target variable (y) are identified.
6. **Feature Selection and Scaling**: Feature scaling is performed, and feature selection is done based on correlation analysis.
7. **Splitting the Data**: The dataset is split into training and testing sets.
8. **Choosing a Model**: Decision Tree Regressor is selected as the predictive model.
9. **Training the Model**: The model is trained using the training data.
10. **Testing the Model**: The trained model is evaluated using the testing data, and predictions are made.
11. **Performance Evaluation**: The performance of the model is assessed using metrics such as R-squared score.

### File Structure
- **Decision Tree.ipynb**: Jupyter Notebook containing the code for the project.
- **car_data.csv**: Dataset used for training and testing.
