# Breast Cancer Prediction using Logistic Regression 🎗️

## 📌 Project Overview
This project implements a Machine Learning model using **Logistic Regression** to predict whether a breast cancer tumor is **Benign (0)** or **Malignant (1)**. The project utilizes the Wisconsin Breast Cancer dataset and achieves a high accuracy rate on test data.

## 📂 Dataset
The dataset consists of various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
* **Source:** Wisconsin Breast Cancer Dataset.
* **Features:** Clump Thickness, Uniformity of Cell Size, Cell Shape, Marginal Adhesion, etc.
* **Target:** Class (2 for Benign, 4 for Malignant).

## 🛠️ Technologies Used
* **Python**
* **Pandas & NumPy** (Data Manipulation)
* **Plotly** (Interactive Data Visualization)
* **Scikit-Learn** (Model Training & Evaluation)

## 📊 Key Steps
1.  **Exploratory Data Analysis (EDA):**
    * Visualized feature distributions using Histograms.
    * Analyzed feature relationships using a Correlation Matrix Heatmap.
2.  **Data Preprocessing:**
    * Removed irrelevant columns (`Sample code number`).
    * Checked for missing values.
    * Encoded the target column:
        * `2` (Benign) $\rightarrow$ `0`
        * `4` (Malignant) $\rightarrow$ `1`
3.  **Model Training:**
    * Split data into 80% training and 20% testing sets.
    * Trained a Logistic Regression model.
4.  **Evaluation:**
    * Used Accuracy Score and Confusion Matrix.

## 📈 Results
The model performed exceptionally well on the testing dataset:

| Metric | Score |
| :--- | :--- |
| **Training Accuracy** | **96.67%** |
| **Testing Accuracy** | **95.56%** |

## 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/breast-cancer-prediction.git](https://github.com/your-samir-m0hamed/Breast_Cancer.git)
    ```
2.  Install the required packages:
    ```bash
    pip install pandas numpy plotly scikit-learn
    ```
3.  Run the Jupyter Notebook:
    ```bash
    jupyter notebook Breast_cancer.ipynb
    ```

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

---
*Created by [Samir Mohamed Samir]*
