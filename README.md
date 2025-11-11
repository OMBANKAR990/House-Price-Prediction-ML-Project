# House-Price-Prediction-ML-Project

Live Application link is Below

https://house-price-prediction-ml-project-om.streamlit.app/




# 🏠 House Price Prediction App

## 📋 Description

The **House Price Prediction App** is a machine learning–powered web application that predicts the price of a house based on various input features such as location, area, number of rooms, and other property attributes. The app is built using **Streamlit** for an interactive user interface and a trained **Machine Learning Model (Regression Algorithm)** for accurate price estimation.

This project demonstrates how data science and machine learning techniques can be applied to real-world problems in the real estate domain. It allows users to manually enter property details and instantly get an estimated price prediction.

---

## 🚀 Features

* 🧠 Predicts house prices using a pre-trained ML model
* 🏡 User-friendly interface built with **Streamlit**
* 📊 Real-time input and instant predictions
* ⚙️ Supports both manual input and automated prediction pipelines
* 💾 Model trained using a dataset of house features and corresponding prices

---

## 🧩 Tech Stack

* **Programming Language:** Python
* **Frontend Framework:** Streamlit
* **Libraries Used:**

  * Pandas
  * NumPy
  * Scikit-learn
  * Pickle (for model serialization)
  * Matplotlib / Seaborn (for data visualization)

---

## 🧠 How It Works

1. The user provides input features such as:

   * Area (sq. ft)
   * Number of Bedrooms
   * Number of Bathrooms
   * Location
   * Other property details
2. The app preprocesses the input data.
3. The trained regression model (saved as `.pkl` file) predicts the house price.
4. The predicted price is displayed instantly on the Streamlit dashboard.

---

## ⚙️ Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/house-price-prediction-app.git
   cd house-price-prediction-app
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:

   ```bash
   streamlit run app.py
   ```

---

## 📈 Model Training (Optional)

If you want to retrain the model:

1. Open the `model_training.ipynb` notebook.
2. Load the dataset and preprocess it.
3. Train using your chosen regression algorithm (Linear, RandomForest, etc.).
4. Save the model as a `.pkl` file:

   ```python
   import pickle
   pickle.dump(model, open('model.pkl', 'wb'))
   ```

---

## 🖼️ Screenshot

<img width="811" height="754" alt="image" src="https://github.com/user-attachments/assets/31c855a3-81ca-47f4-9562-c71f320c847f" />




---

## 📚 Future Enhancements

* Integration with real-time location APIs for automatic area-based pricing
* Improved UI with data visualization dashboards
* Deployment on cloud (Heroku / AWS / Streamlit Cloud)

---

## 👨‍💻 Author

**Developed by:** [Om Bankar]
**Email:** [ombankar25@gmail.com]

---

