# **Gold Price Prediction using Polynomial Regression**
![gold](gold.jpg)


## **📜 Project Description**  
This project applies **Polynomial Regression** to predict **Gold Prices (GLD)** based on **Crude Oil Prices (USO) and Silver Prices (SLV)**. Using **Scikit-Learn and Matplotlib**, we preprocess data, generate polynomial features, train a regression model, and visualize predictions vs. actual values.

---

## **📊 Features & Functionality**  
✅ **Polynomial Feature Engineering** – Converts input data into polynomial terms for better predictive power.  
✅ **Linear Regression Model** – Fits a polynomial model to predict **GLD prices**.  
✅ **Train-Test Split & Model Evaluation** – Uses **Mean Absolute Error (MAE)** and **R² Score**.  
✅ **Visualization** – Compares **predicted vs. actual GLD prices** in a scatter plot.

---

## **📁 Project Structure**  
```
/Gold-Price-Prediction
│── Gold-Prediction.ipynb      # Jupyter Notebook for model training
│── README.md                  # Project documentation
│── gld_price_data.csv         # Gold price dataset
│── gold.jpg                   # Visualization image related to gold prices
│── updated_column_descriptions.csv  # Column descriptions for dataset
│── requirements.txt           # Python dependencies
│── results/
│   ├── model_metrics.txt      # Stored performance metrics
│   ├── predictions.png        # Visualization of actual vs predicted values
│── .gitignore                 # Ignore unnecessary files
```

---

## **🛠️ Installation & Setup**  
### **1️⃣ Clone Repository**  
```sh
git clone https://github.com/your-username/Gold-Price-Prediction.git
cd Gold-Price-Prediction
```

### **2️⃣ Install Dependencies**  
```sh
pip install -r requirements.txt
```

### **3️⃣ Run the Model**  
```sh
python Gold-Prediction.ipynb
```

---


---

## **📈 Visualizations**  
✅ **Predicted vs Actual Gold Prices (GLD)**  
![Predicted vs Actual](results/predictions.png)

---

## **🛠️ Future Improvements**  
🚀 Try different **polynomial degrees (2, 3, 4)**  
🚀 Add more **economic indicators (SPX, EUR/USD, Inflation rates, etc.)**  
🚀 Use **Feature Scaling (Standardization/Min-Max)**  

---

## **💡 Contributing**  
Pull requests are welcome! If you find issues, feel free to open a GitHub **Issue** or submit a **PR**.

---

## **📜 License**  
MIT License © 2024 **Your Name / GitHub Handle**

