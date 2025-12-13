# 👫 Gender Classification Using SVM

## 📌 Overview
This project implements a **Support Vector Machine (SVM)** classifier to predict gender (Male/Female) based on facial physical characteristics. The model utilizes the **RBF (Radial Basis Function) Kernel** to handle non-linear relationships in the data, achieving high accuracy on both training and testing datasets.

## 📂 Dataset Features
The dataset consists of **5001 samples** with the following features:
* **long_hair**: (0 or 1)
* **forehead_width_cm**: Continuous value
* **forehead_height_cm**: Continuous value
* **nose_wide**: (0 or 1)
* **nose_long**: (0 or 1)
* **lips_thin**: (0 or 1)
* **distance_nose_to_lip_long**: (0 or 1)
* **gender**: Target variable (Male/Female)

## 🛠️ Technologies Used
* **Python**: Core programming language.
* **Pandas**: For data manipulation and analysis.
* **Plotly**: For interactive Exploratory Data Analysis (EDA) and visualizations.
* **Scikit-Learn**: For building the SVM model and evaluation metrics.

## 📊 Methodology
1.  **Data Loading & Inspection**: Checking for null values and understanding data distribution.
2.  **EDA**: Visualizing feature distributions using Plotly histograms differentiated by gender.
3.  **Preprocessing**: Encoding the categorical target (`gender`) into numerical values (Male: 1, Female: 0).
4.  **Splitting**: Dividing data into Training (80%) and Testing (20%) sets.
5.  **Model Training**: Training an SVC model with `kernel='rbf'`.
6.  **Evaluation**: Using Accuracy Score and Confusion Matrix.

## 📈 Results
The model demonstrated excellent performance with minimal overfitting:

| Metric | Score |
| :--- | :--- |
| **Training Accuracy** | **97.00%** |
| **Testing Accuracy** | **96.30%** |

### Confusion Matrix (Testing Set)
* **True Negatives (Female predicted correctly):** 486
* **True Positives (Male predicted correctly):** 478
* **False Positives:** 16
* **False Negatives:** 21

## 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/samir-m0hamed/Gender-Classification-SVM.git](https://github.com/samir-m0hamed/Gender-Classification-SVM.git)
    ```
2.  Install dependencies:
    ```bash
    pip install pandas numpy scikit-learn plotly
    ```
3.  Run the Jupyter Notebook:
    ```bash
    jupyter notebook Gender_Classification.ipynb
    ```

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

---
## 👤 Author
*samir mohamed*
