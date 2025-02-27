  

---

# ✈️ **Airline Ticket Price Prediction using Machine Learning**  

This project predicts **airline ticket prices** using **machine learning algorithms** like **Random Forest, Naïve Bayes, Decision Tree**, etc. The trained model is deployed as a **web application** to provide real-time price predictions.  

## 🚀 **Project Overview**  
Flight ticket prices vary based on multiple factors such as **airline, source, destination, departure time, duration, and availability**. This project builds a machine learning model to predict flight ticket prices based on historical data and deploys it as a web application.  

## 📂 **Project Structure**  
- `data/` → **Dataset (CSV file with airline price details)**  
- `notebooks/` → **Jupyter Notebooks for data analysis & model training**  
- `models/` → **Trained ML models (saved in .pkl or .h5 format)**  
- `app/` → **Web application (Flask/Django/Streamlit)**  
- `requirements.txt` → **Dependencies list**  
- `README.md` → **Project documentation**  

## 🛠 **Technologies Used**  
- **Machine Learning Models:**  
  ✔️ Random Forest  
  ✔️ Decision Tree  
  ✔️ Naïve Bayes  
  ✔️ Support Vector Machine (SVM)  
  ✔️ Gradient Boosting  

- **Libraries & Frameworks:**  
  - Python  
  - Pandas, NumPy, Matplotlib, Seaborn  
  - Scikit-learn (ML algorithms)  
  - Flask / Django / Streamlit (for web deployment)  

## 🔍 **Feature Engineering**  
The dataset includes the following features:  
✅ **Airline** (e.g., Air India, Indigo, Vistara)  
✅ **Source & Destination** (e.g., Delhi → Mumbai)  
✅ **Departure & Arrival Time**  
✅ **Flight Duration**  
✅ **Total Stops**  
✅ **Price (Target Variable)**  

## 📈 **Model Training & Evaluation**  
The models are trained on historical flight data and evaluated using:  
- **RMSE (Root Mean Squared Error)**  
- **R² Score (Coefficient of Determination)**  
- **MAE (Mean Absolute Error)**  

## 🌐 **Web Application Deployment**  
The trained model is deployed as a **web app**, where users can enter flight details and get an **estimated ticket price** prediction.  

### 🔧 **How to Run the Project?**  
1️⃣ **Clone the Repository:**  
   ```bash
   git clone https://github.com/yourusername/airline-price-prediction.git
   cd airline-price-prediction
   ```  
2️⃣ **Install Dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```  
3️⃣ **Run the Web App:**  
   ```bash
   python app.py
   ```  
4️⃣ **Open in Browser:**  
   ```
   http://127.0.0.1:5000
   ```  

## 📜 **License**  
This project is open-source. Feel free to use, modify, and contribute!  

---
