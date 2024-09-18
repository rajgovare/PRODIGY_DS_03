---

# **Decision Tree Classifier for Customer Purchase Prediction**

## **Overview**
This project aims to predict whether a customer will purchase a product or service based on their demographic and behavioral data using a decision tree classifier. The dataset used for this task is the "bank.csv" dataset, which contains customer-related data such as age, job, marital status, and past campaign outcomes. The model is trained to predict whether the customer will subscribe to a product based on the available features.

## **Methodology/Steps**
1. **Data Loading**: Load the dataset and inspect its structure.
2. **Data Cleaning**: Check for missing values and confirm data types. Categorical variables are transformed into numerical formats using one-hot encoding.
3. **Exploratory Data Analysis (EDA)**: Perform analysis to understand data distribution, especially focusing on class balance for the target variable.
4. **Feature Engineering**: Convert categorical variables into dummy variables using `pd.get_dummies()`.
5. **Train-Test Split**: Split the dataset into training and testing sets using an 70/30 ratio.
6. **Model Building**: Build a Decision Tree Classifier to learn the relationship between customer data and the target variable (`y`).
7. **Model Evaluation**: Evaluate the model using accuracy score, confusion matrix, and classification report.
8. **Model Visualization**: Visualize the trained decision tree.

## **Requirements**
The following libraries are required to run the code:
- `pandas`
- `numpy`
- `scikit-learn`
- `seaborn`
- `matplotlib`

You can install these using:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```
## **Exploratory Data Analysis (EDA)**
- A check for missing values revealed no missing data.
- All categorical variables were converted into numerical values using one-hot encoding.

## **Results**
- **Accuracy**: The accuracy of the decision tree model was evaluated on the test set.
- **Confusion Matrix**: Provides insight into the number of correct and incorrect predictions.
- **Classification Report**: Contains precision, recall, and F1-score for both the "Yes" and "No" classes.

## **Conclusion**
The decision tree classifier model provides a reliable method to predict customer purchases based on their demographic and behavioral data.
