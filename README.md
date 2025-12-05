# Breast Cancer Classification using Logistic Regression 🎗️

## 📌 Overview
- This project builds a Machine Learning classifier using **Logistic Regression** to determine whether a breast tumor is **Benign (0)** or **Malignant (1)**.  
- Using the Wisconsin Breast Cancer dataset, the model delivers high classification performance on unseen samples.

---

## 📂 Dataset Information
The dataset includes numeric measurements extracted from digital images of fine needle aspirates (FNA) of breast masses.

**Dataset highlights:**
- **Source:** Wisconsin Breast Cancer Database  
- **Features:** Cell size, cell shape, marginal adhesion, bare nuclei, mitoses, etc.  
- **Target:** Tumor type  
  - `2` → Benign  
  - `4` → Malignant  

In the project, the target classes were mapped to:
- `0` → Benign  
- `1` → Malignant  

---

## 🛠️ Tools & Libraries
- **Python**
- **Pandas, NumPy** — data handling and processing  
- **Plotly** — interactive data visualization  
- **Scikit-Learn** — model building and evaluation  

---

## 📊 Workflow Summary

1. **Data Exploration**
   - Plotted feature distributions using histograms
   - Evaluated feature correlations via a heatmap

2. **Preprocessing**
   - Dropped unnecessary fields (e.g., `Sample code number`)
   - Checked for missing or inconsistent values
   - Converted target labels to binary format

3. **Training**
   - Data split: 80% training / 20% testing
   - Logistic Regression model trained on scaled inputs

4. **Evaluation**
   - Performance measured using accuracy and confusion matrix

---

## 📈 Performance

The trained model achieved outstanding predictive results:

| Metric | Value |
| :--- | :--- |
| **Training Accuracy** | **96.67%** |
| **Testing Accuracy** | **95.56%** |

These results indicate high generalization ability and reliable tumor classification performance.

---

## 🚀 Run Instructions

1. Clone the repository:
   ```bash
    git clone https://github.com/samir-m0hamed/Breast_Cancer.git
    ```
2.  Install the required packages:
    ```bash
    pip install pandas numpy plotly scikit-learn
    ```
3.  Run the Jupyter Notebook:
    ```bash
    jupyter notebook Breast cancer.ipynb
    ```

---

## 🤝 Contributing
- Contributions, feature suggestions, and improvements are welcome.
- Feel free to open an issue, report bugs, or submit a pull request to enhance the repository.

---

## 👤 Developed By

**Samir Mohamed Samir**  

