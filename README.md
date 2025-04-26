#  Iris Flower Classification

## 📄 Overview  
This project classifies Iris flowers into three species using machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), model training, and evaluation. Multiple models are compared to determine the most accurate classifier for species prediction.

---

## 📊 Dataset  
Source: [Iris Dataset ](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)

### Features:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`

### Target:
- `species`: 
  - *Iris-setosa*
  - *Iris-versicolor*
  - *Iris-virginica*

---

## 🔧 Preprocessing  
- No missing values detected  
- Label encoding of target variable  
- Visualizations for feature relationships (pairplot, heatmap)  
- Train-test split applied  
- (Optional) Feature scaling for SVM and KNN  

---

## 🤖 Models Used  
The following classification models were trained and evaluated:
- K-Nearest Neighbors (KNN)  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree Classifier  

### ✅ Best Model:  
- **Model:** Logistic Regression *(example — replace with yours)*  
- **Accuracy:** 97.33%  
- **Precision:** 97%  
- **F1 Score:** 97%

---

## 📂 Project Structure  

iris-flower-classification/
├── data/
│   └── IRIS.csv
├── notebooks/
│   └── iris_classification.ipynb
├── outputs/
│   ├── knn_model.pkl
│   └── results.txt
├── README.md
├── requirements.txt
└── .gitignore


---

## 🚀 How to Run  

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/iris-flower-classification.git
   cd iris-flower-classification
pip install -r requirements.txt

python src/preprocessing.py
python src/model.py
