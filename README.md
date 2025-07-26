
# 📈 Disease Prediction using  — Random Forest Classifier

This project determines how to implement **Random Forest Classifier** to predict **prognosis** based on the person experiencing **symptoms**. The goal of this notebook is to accurately classify diseases while optimizing the number of features used. In addition to achieving high classification accuracy, this notebook will explore whether similar evaluation metrics can be maintained with a distint feature set.

---

## 📂 Dataset

Complete Dataset consists of 2 CSV files . One of them is training and other is for testing your model. Each CSV file has 133 columns. 132 of these columns are symptoms that a person experiences and last column is the prognosis.

These symptoms are mapped to 42 diseases you can classify these set of symptoms too.

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
   - Countplot visualization using seaborn  
5. **Train-Test Split**  
   - 75:25 ratio using `train_test_split()`  
6. **Model Creation**  
   - Using `RandomForestClassifier` from scikit-learn  
7. **Prediction**  
   - Predicted prognosis for test data  
8. **Evaluation Metrics**
   - F1_score 
   - Accuracy_score 
   - Precision_score  
   - Recall_score
   - Confusion_Matrix
9. **Visualization**  
   - Count plot of **Symptoms vs Prognosis**

---

## 📊 Evaluation Output

```  
Accuracy_score: 90.9090909090909%
F1_score : 0.8070175438596491%
precision_score : 0.95%
recall_score : 0.75%
```

This indicates a good accuracy prediction model.

---

## 📌 Visualization

A Count plot is generated to show the **Symptoms vs Prognosis** values with a reference bar:

- X-axis → Symptoms Count  
- Y-axis → Prognosis  

---

## 🙏 Acknowledgement

This project was created under the guidance of [Surekha Kanwar](https://www.linkedin.com/in/surekha-kanwar-81002076/), as part of my machine learning learning journey. I am thankful for her feverish support and knowledge.

---

## 🚀 Run the Code

You can run this project by copying the code into a new notebook and uploading your dataset.

---

## 📬 Contact

For any suggestions or collaborations, feel free to connect on [](https://www.linkedin.com/in/aditya-saraswat-51257b256ar-81002076/), or mail me.
