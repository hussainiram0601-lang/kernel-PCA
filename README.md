# Kernel PCA for Non-Linear Dimensionality Reduction

This project implements **Kernel Principal Component Analysis (Kernel PCA)** using Python and Scikit-Learn to perform non-linear dimensionality reduction on the Wine dataset. It demonstrates how to transform complex, non-linearly separable data into a lower-dimensional space where classification models can achieve high accuracy.

## 📌 Project Overview
Traditional PCA works exceptionally well for finding linear relationships in data. However, when the decision boundary between classes is non-linear, standard linear transformations fail. 

This notebook showcases the **Kernel Trick** (specifically using the Radial Basis Function / RBF kernel) to map data into a higher-dimensional space where it becomes linearly separable, reduces dimensions to 2 principal components, and classifies it using Logistic Regression.

---

## 🗺️ Workflow & Structure

The repository follows a clean, step-by-step Machine Learning pipeline structure:
1. **Data Preprocessing**: Importing libraries, handling the `Wine.csv` dataset, and splitting into train/test subsets.
2. **Feature Scaling**: Standardizing features to ensure variance scales correctly during transformation.
3. **Applying Kernel PCA**: Projecting features into a 2D space via the RBF kernel.
4. **Classification Model**: Training a Logistic Regression model on the newly extracted components.
5. **Evaluation & Visualization**: Generating a confusion matrix and plotting 2D decision boundary spaces.

---

## 🛠️ Prerequisites & Tech Stack

Make sure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib scikit-learn
```

| Technology | Purpose |
| :--- | :--- |
| **Python 3.x** | Core Language |
| **Pandas** | Data parsing and structure manipulation |
| **NumPy** | High-performance matrix computing |
| **Scikit-Learn** | Machine learning preprocessing, decomposition, and modeling |
| **Matplotlib** | Output visualization and decision boundary plotting |

---

## 🚀 How to Run the Project

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com
   ```
2. Ensure `Wine.csv` is located in the same directory as the notebook.
3. Open `kernel_pca.ipynb` inside **Google Colab**, **Jupyter Notebook**, or **VS Code**.
4. Run all cells sequentially (`Runtime > Run all` in Colab).

---

## 📈 Key Results & Metrics
*(Tip: Once you finish running your model, replace this section with your actual scores!)*

* **Classification Accuracy**: `XX%`
* **Principal Components Extracted**: 2 Components

---

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
# kernel-PCA
