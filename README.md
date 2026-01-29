# 📦 Delivery Time Estimation Using Python & Power BI

## 📌 Project Overview
This project focuses on estimating food delivery time using **data analytics and machine learning techniques**.  
Python is used for **data cleaning, exploratory data analysis (EDA), feature engineering, and prediction modeling**, while **Power BI** is used to build interactive dashboards for visualization and insight generation.

The project demonstrates an **end-to-end analytics workflow**, starting from raw data to actionable insights.

---

## 🎯 Objectives
- Analyze food delivery data using Python  
- Clean and preprocess the dataset  
- Perform exploratory data analysis (EDA)  
- Build a machine learning model to predict delivery time  
- Visualize delivery performance and prediction results using Power BI  

---

## 📊 Dataset
- **Source:** Kaggle – Food Delivery Dataset  
- **Description:**  
  The dataset contains real-world food delivery information such as:
  - Distance  
  - Traffic level  
  - Weather conditions  
  - Time of day  
  - Vehicle type  
  - Courier experience  
  - Actual delivery time  

### Datasets Included
- **Raw dataset** – Original data from Kaggle  
- **Cleaned dataset** – Processed data with:
  - Predicted delivery time  
  - Prediction error  

---

## 🧰 Tools & Technologies Used
- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Jupyter Notebook**
- **Machine Learning**
  - Linear Regression (baseline model)
  - Random Forest Regressor (final model)
- **Power BI**
- **GitHub**

---

## 📓 Jupyter Notebook Implementation
The complete data analysis and machine learning workflow was implemented using **Jupyter Notebook**.

The notebooks include:
- Data loading and understanding  
- Data cleaning and preprocessing  
- Handling missing values and duplicates  
- Exploratory Data Analysis (EDA)  
- Feature engineering and encoding  
- Machine learning model training  
- Delivery time prediction and model evaluation  

All Python-based analysis and model development were performed in Jupyter Notebook before exporting the final dataset for Power BI visualization.

---

## 🔍 Project Workflow
1. Data collection from Kaggle  
2. Data cleaning and preprocessing using Python  
3. Exploratory Data Analysis (EDA)  
4. Feature engineering and encoding  
5. Machine learning model training  
6. Delivery time prediction  
7. Visualization using Power BI dashboards  

---

## 🤖 Machine Learning Model
- **Target Variable:** `Delivery_Time_min`

### Input Features
- Distance (`Distance_km`)  
- Traffic level (`Traffic_Level`)  
- Weather condition (`Weather`)  
- Time of day (`Time_of_Day`)  
- Vehicle type (`Vehicle_Type`)  
- Preparation time (`Preparation_Time_min`)  
- Courier experience (`Courier_Experience_yrs`)  

### Models Used
- Linear Regression – baseline model  
- Random Forest Regressor – final model  

### Evaluation Metrics
- Mean Absolute Error (MAE)  
- Root Mean Square Error (RMSE)  
- R² Score  

The Random Forest model was selected due to better performance and its ability to handle **non-linear relationships** in delivery data.

---

## 📈 Power BI Dashboard
An interactive **Power BI dashboard** was created to visualize both **actual and predicted delivery time** and to analyze delivery performance.

### Dashboard Highlights
- Delivery performance overview with KPIs  
- Actual vs predicted delivery time comparison  
- Prediction error distribution  
- Impact of traffic, weather, distance, and time of day on delivery time  

### Dashboard Files
- **`.pbix`** – Interactive Power BI dashboard  
- **`.pdf`** – Dashboard report for easy viewing 

📌 *The PDF version is included for reviewers who do not have Power BI installed.*

---

## 📂 Repository Structure
Delivery-Time-Estimation/
├── data/
│ ├── Food_Delivery_Times.csv
│ └── delivery_time_powerbi.csv
│
├── notebooks/
│ ├── notebook1_value_added_internship_project.ipynb
│ └── notebook2_valueadded_internship.ipynb
│
├── dashboards/
│ ├── Delivery_Time_Dashboard.pbix
│ └── Delivery_Time_Dashboard.pdf
├── README.md


---

## ✅ Results & Insights
- Delivery time increases with distance and traffic level  
- Weather conditions significantly impact delivery delays  
- Random Forest model predicts delivery time with low average error  
- Most prediction errors are close to zero, indicating good model accuracy  

---

## 📌 Conclusion
This project successfully demonstrates the application of **data analytics, machine learning, and data visualization** to solve a real-world delivery time estimation problem.  
It highlights the importance of **data-driven decision-making** in logistics and delivery operations.

---

## 🔮 Future Scope
- Incorporate real-time traffic and weather data  
- Experiment with advanced machine learning models  
- Deploy the model as a real-time delivery time prediction service  

---

## 📚 References
- Kaggle – Food Delivery Dataset  
- Scikit-learn Documentation  
- Power BI Official Documentation  
