# ❤️ Heart Disease Prediction Project ❤️

A machine learning project that predicts the likelihood of a person having heart disease based on their medical attributes. This project uses a **Hyperband-Optimized Ensemble Model** to achieve high accuracy.

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

## ✨ Features

* **High Accuracy:** Utilizes a stacked ensemble of Random Forest and K-Nearest Neighbors, optimized with Hyperband for superior performance.
* **Web Interface:** A user-friendly web interface built with Flask to make predictions.
* **Easy to Use:** Simply input the required medical attributes and get an instant prediction.
* **Well-documented:** The code is well-commented for easy understanding and modification.

---

## 📊 Dataset

The project uses the **Cleveland Clinic Foundation heart disease dataset** from the UCI Machine Learning Repository. The dataset consists of 303 instances and 14 attributes.

**Attributes:**

1.  **age:** age in years
2.  **sex:** (1 = male; 0 = female)
3.  **cp:** chest pain type
4.  **trestbps:** resting blood pressure (in mm Hg on admission to the hospital)
5.  **chol:** serum cholestoral in mg/dl
6.  **fbs:** (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7.  **restecg:** resting electrocardiographic results
8.  **thalach:** maximum heart rate achieved
9.  **exang:** exercise induced angina (1 = yes; 0 = no)
10. **oldpeak:** ST depression induced by exercise relative to rest
11. **slope:** the slope of the peak exercise ST segment
12. **ca:** number of major vessels (0-3) colored by flourosopy
13. **thal:** 3 = normal; 6 = fixed defect; 7 = reversable defect
14. **target:** 1 or 0

---

## 🤖 Model

This project employs a **stacked ensemble model** that combines the predictions of a **Random Forest** and a **K-Nearest Neighbors (KNN)** classifier. The hyperparameters of the model are tuned using the **Hyperband optimization algorithm** to achieve the best possible performance. The trained model is saved in the `heart-disease-prediction-stacked-rf+knn-model.pkl` file.

---

## 🚀 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/singhsuhas77/Heart-Disease-Prediction.git](https://github.com/singhsuhas77/Heart-Disease-Prediction.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Heart-Disease-Prediction
    ```
3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the application:**
    ```bash
    python app.py
    ```
5.  Open your browser and go to `http://127.0.0.1:5000` to see the application in action.

---

## 🛠️ Technologies Used

* **Python:** The core programming language.
* **Flask:** A lightweight web framework for the user interface.
* **Scikit-learn:** For building and training the machine learning model.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Hyperopt:** For hyperparameter optimization with Hyperband.

---

## 🤝 How to Contribute

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or create a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---
