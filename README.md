# **📊 Polynomial Regression Analysis with Bias-Variance Tradeoff**

## **🔍 Overview**
This project implements **polynomial regression** and explores:
- Cross-validation loss vs. model complexity
- Loss function implementations (MSE, MAE, Log loss, Linex loss)
- Bias-variance analysis with Bootstrap sampling
- Optimization of polynomial fitting using `scipy.optimize.minimize`
- Residual analysis after train-test split

📌 **Key Topics Covered:**
✔ Polynomial Regression  
✔ Loss Functions  
✔ Cross-Validation  
✔ Bias-Variance Tradeoff  
✔ Optimization using `scipy.optimize.minimize`  
✔ Residual Plots for Model Evaluation  

---

## **📂 Project Structure**
```
📦 Polynomial-Regression-Analysis 
 ├── 📂 notebooks             # Jupyter Notebooks
 │   ├── Polynomial_Regression_Analysis.ipynb  # Notebook containing solutions
 ├── README.md                # Documentation
 ├── requirements.txt         # Dependencies
 ├── .gitignore               # Ignore unnecessary files
```

---

## **📥 Installation**
To run this project, first **clone the repository**:
```sh
git clone https://github.com/SONIBARE/Polynomial-Regression-Analysis.git
cd Polynomial-Regression-Analysis
```

Install required dependencies:
```sh
pip install -r requirements.txt
```

Run Jupyter Notebook:
```sh
jupyter notebook
```

---

## **📊 Tasks Implemented**
### **🔹 Task 1: Cross-Validation Loss vs. Model Complexity**
- Uses k-fold cross-validation to estimate the loss for different polynomial degrees.
- Plots **degree vs. cross-validation loss**.
- **Identifies optimal complexity** using a vertical line.

### **🔹 Task 2: Synthetic Dataset Generation**
- Implements polynomial evaluation function.
- Generates synthetic datasets with Gaussian noise.
- Plots **noisy data vs. true polynomial curve**.

### **🔹 Task 3: Implementing Loss Functions**
✔ **Mean Squared Error (MSE)**  
✔ **Mean Absolute Error (MAE)**  
✔ **Hinge Loss**  
✔ **Log Loss (Binary Cross-Entropy)**  
✔ **Linex Loss (Asymmetric Loss)**  

### **🔹 Task 4: Polynomial Fitting using Optimization**
- Uses `scipy.optimize.minimize` to optimize polynomial coefficients.
- Implements a flexible **loss function-based fitting approach**.

### **🔹 Task 5: Visualizing Residuals**
- Splits dataset into **train-test**.
- Fits a polynomial and **plots residuals**.
- Computes **Mean Squared Error on test set**.

### **🔹 Task 6: Implementing a Polynomial Estimator Class**
- Object-oriented **PolynomialEstimator** class.
- Methods for **fit()** and **predict()**.

### **🔹 Task 7: Bias-Variance Estimation via Bootstrap Sampling**
- Generates **bootstrap samples**.
- Computes **bias-variance decomposition**.
- Plots **bias vs. variance** for different models.

### **🔹 Task 8: Comparing Underfitting vs. Overfitting Models**
- Uses **bootstrap sampling** to compare two models.
- Determines if **one model underfits and the other overfits**.

---

## **📊 Sample Visualizations**
📌 **Cross-Validation Loss vs. Model Complexity**
![Cross-Validation Plot](plots/cv_loss_vs_degree.png)

📌 **Residual Analysis**
![Residuals](plots/residuals.png)

📌 **Bias-Variance Tradeoff**
![Bias-Variance](plots/bias_variance.png)

---



