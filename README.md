\# Credit Card Fraud Detection



This project focuses on detecting fraudulent credit card transactions using machine learning. We implement multiple models including Logistic Regression, Decision Tree, Random Forest, and K-Nearest Neighbors, and evaluate their performance using various metrics such as accuracy, precision, recall, and F1-score.



\## 📌 Objective

To build a classification model that can distinguish between fraudulent and legitimate credit card transactions using supervised learning techniques.



---



\## 📂 Dataset



\- \*\*Source:\*\* \[Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

\- \*\*Features:\*\* 30 anonymized input features (`V1` to `V28`, `Amount`, `Time`)

\- \*\*Target Variable:\*\* `Class` (0 = legitimate, 1 = fraud)

\- \*\*Size:\*\* 284,807 transactions



---



\## ⚙️ Methodology



1\. \*\*Preprocessing\*\*

&nbsp;  - Data loaded using `pandas`

&nbsp;  - Normalization of `Amount` and `Time`

&nbsp;  - Checked and handled class imbalance (if needed)

&nbsp;  - Performed train-test split in 80:20 ratio



2\. \*\*Models Implemented\*\*

&nbsp;  - Logistic Regression

&nbsp;  - Decision Tree Classifier

&nbsp;  - Random Forest Classifier

&nbsp;  - K-Nearest Neighbors (KNN)



---



\## 📊 Results



**### 🧮 Logistic Regression**



\*\*Confusion Matrix:\*\*

\[\[95 4]

\[ 9 89]]



\*\*Classification Report:\*\*



| Metric        | Class 0 | Class 1 |

|---------------|---------|---------|

| Precision     | 0.91    | 0.96    |

| Recall        | 0.96    | 0.91    |

| F1-Score      | 0.94    | 0.93    |

| Accuracy      | \*\*0.93\*\* |



---



\### 🌲 Decision Tree



\*\*Confusion Matrix:\*\*

\[\[92 7]

\[11 87]]



\*\*Classification Report:\*\*



| Metric        | Class 0 | Class 1 |

|---------------|---------|---------|

| Precision     | 0.89    | 0.93    |

| Recall        | 0.93    | 0.89    |

| F1-Score      | 0.91    | 0.91    |

| Accuracy      | \*\*0.91\*\* |



---



\### 🌳 Random Forest



\*\*Confusion Matrix:\*

\[\[98 1]

\[13 85]]



**\*\*Classification Report:\*\***



**| Metric        | Class 0 | Class 1 |**

**|---------------|---------|---------|**

**| Precision     | 0.88    | 0.99    |**

**| Recall        | 0.99    | 0.87    |**

**| F1-Score      | 0.93    | 0.92    |**

**| Accuracy      | \*\*0.93\*\* |**



**---**



**### 📍 K-Nearest Neighbors (KNN)**



**\*\*ROC-AUC Score:\*\* 0.762**  

**\*\*Accuracy Score:\*\* 0.594**



**\*\*Confusion Matrix:\*\***

**\[\[54 45]**

**\[35 63]]**



**\*\*Classification Report:\*\***



**| Metric        | Class 0 | Class 1 |**

**|---------------|---------|---------|**

**| Precision     | 0.61    | 0.58    |**

**| Recall        | 0.55    | 0.64    |**

**| F1-Score      | 0.57    | 0.61    |**

**| Accuracy      | \*\*0.59\*\* |**



**---**



**## 🧠 Conclusion**



**- \*\*Random Forest\*\* and \*\*Logistic Regression\*\* achieved the highest accuracy (~93%) and performed well across all metrics.**

**- \*\*KNN\*\* struggled with accuracy and class separation, likely due to feature scaling and dataset dimensionality.**

**- Evaluation involved precision, recall, and F1-score since class imbalance is a critical issue in fraud detection.**



**---**



**## 🛠️ Tech Stack**



**- Python**

**- NumPy, Pandas**

**- Scikit-learn**



**---**



