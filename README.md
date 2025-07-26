
# 📈 Disease Prediction using  — Random Forest Classifier

This is a simple machine learning project demonstrating how to use a **Decision Tree Regressor** to predict a person's **age** based on their **height**. The entire workflow is implemented using **Google Colab**, **scikit-learn**, and **pandas**.

---

## 📂 Dataset

The dataset is a CSV file with two columns:

- `Height` — the height of the individual
- `Age` — the corresponding age

Sample:
```
Age,Height  
10,138  
11,138  
12,138  
...  
```

---

## 🔧 Libraries Used

- `pandas` — Data loading and manipulation  
- `numpy` — Numerical operations  
- `matplotlib`, `seaborn` — Data visualization  
- `sklearn` — Machine learning (model, training, evaluation)

---

## 🛠️ Steps Performed

1. **Import Libraries**  
2. **Upload and Read CSV Dataset**
3. **Data Cleaning**  
   - Checked for null values  
4. **Exploratory Data Analysis (EDA)**  
   - Pairplot visualization using seaborn  
5. **Train-Test Split**  
   - 80:20 ratio using `train_test_split()`  
6. **Model Creation**  
   - Using `DecisionTreeRegressor` from scikit-learn  
7. **Prediction**  
   - Predicted age values for test data  
8. **Evaluation Metrics**
   - MAE (Mean Absolute Error)  
   - MSE (Mean Squared Error)  
   - RMSE (Root Mean Squared Error)  
   - R² Score (Coefficient of Determination)
9. **Visualization**  
   - Scatter plot of **Actual vs Predicted Age**

---

## 📊 Evaluation Output

```
MAE: 1.08  
MSE: 1.46  
RMSE: 1.46  
R² Score: 0.995
```

This indicates a very high accuracy of the model.

---

## 📌 Visualization

A scatter plot is generated to show the **Actual vs Predicted** values with a reference line:

- X-axis → Actual Age  
- Y-axis → Predicted Age  
- A perfect prediction lies on the diagonal

---

## 🙏 Acknowledgement

This project was created under the guidance of [Surekha Kanwar](https://www.linkedin.com/in/surekha-kanwar-81002076/), as part of my machine learning learning journey. I thank them sincerely for their support and knowledge.

---

## 🚀 Run the Code

You can run this project in Google Colab by copying the code into a new notebook and uploading your dataset as `dataset.csv`.

---

## 📬 Contact

For any suggestions or collaborations, feel free to connect on [LinkedIn](https://www.linkedin.com/in/parth-shikarwar-a940a7295/) or mail me.
