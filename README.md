# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY: CODETECH IT SOLUTION

NAME: BHARGAV SAWANT B

INTERN ID: CT04WU190

DOMAIN: PYTHON PROGRSMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

---

##  Project Overview  
This project builds a **Spam Email Classifier** using **Logistic Regression** on the well-known **Spambase dataset** from UCI, accessed via `fetch_openml`. The goal is to distinguish between spam and non-spam emails based on various features derived from email content.

The model provides a basic introduction to classification problems using **scikit-learn**, showcasing training, evaluation, and feature importance.

---

##  Features

1. **Data Loading from OpenML**  
   Automatically fetches the Spambase dataset for ease of access and experimentation.

2. **Binary Classification with Logistic Regression**  
   Classifies emails as spam (`1`) or non-spam (`0`) using logistic regression.

3. **Data Visualization**  
   Displays the distribution of classes (spam vs. non-spam).

4. **Model Evaluation**  
   Reports **accuracy**, **precision**, **recall**, and **F1-score**.

5. **Feature Importance Analysis**  
   Ranks features by their influence on spam detection.

---

##  How It Works

1. **Data Fetching**  
   Loads the Spambase dataset using `fetch_openml`.

2. **Preprocessing**  
   Converts target labels to integer type for model training.

3. **Exploratory Data Analysis**  
   - Displays basic stats about the dataset  
   - Plots class distribution using Seaborn

4. **Model Training**  
   - Splits data into training and testing sets  
   - Trains a logistic regression model with `max_iter=1000` for convergence

5. **Model Evaluation**  
   - Predicts on test data  
   - Computes **accuracy** and displays a **classification report**

6. **Feature Importance**  
   - Extracts feature coefficients from the model  
   - Ranks and visualizes top 10 most influential features

---

##  Sample Output

### Dataset Info:
```
Dataset shape: (4601, 58)
```

### Accuracy Example:
```
Accuracy: 0.93 (May vary slightly depending on train-test split)
```

### Classification Report:
```
              precision    recall  f1-score   support

           0       0.93      0.96      0.94       683
           1       0.93      0.88      0.90       237

    accuracy                           0.93       920
   macro avg       0.93      0.92      0.92       920
weighted avg       0.93      0.93      0.93       920
```

### Top 10 Features:
Visualized in a bar chart, showing features with the strongest impact on predictions.

---

##  Libraries Used

- **NumPy**: Numerical operations  
- **Pandas**: Data manipulation  
- **Scikit-learn**: Machine learning modeling  
- **Matplotlib & Seaborn**: Data visualization  
- **OpenML**: Dataset fetching

---

## OUTPUT
![task4_output](https://github.com/user-attachments/assets/8278b662-f92d-4466-bfac-b0e71a1e1a70)

![task_4_ouput_2](https://github.com/user-attachments/assets/23e5a6c9-d028-48c4-994d-70dcd8e53f05)

