# 🚗 Car Selling Price Prediction

## 📌 Project Overview
This project predicts the **selling price of used cars** based on their details (such as brand, year, fuel type, transmission, etc.).  
It uses **Machine Learning models** to learn patterns from historical car sales data and provide an estimated resale price.

The dataset used comes from **Car Dekho** and contains thousands of car listings.

---

## 📂 Dataset
**File:** `CAR DETAILS FROM CAR DEKHO.csv`

### Columns:
- **name** → Car name (brand + model)  
- **year** → Manufacturing year  
- **selling_price** → Target variable (price car was sold for, in INR)  
- **km_driven** → Kilometers driven  
- **fuel** → Fuel type (Petrol, Diesel, CNG, etc.)  
- **seller_type** → Individual / Dealer / Trustmark dealer  
- **transmission** → Manual / Automatic  
- **owner** → Number of previous owners  

---

## 🛠️ Steps in the Project
1. **Data Preprocessing**
   - Handle missing values  
   - Encode categorical variables  
   - Feature scaling (where required)  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of car prices  
   - Correlation between features and price  
   - Price trends with age, brand, fuel type  

3. **Model Training**
   - Models tested:  
     - Gradient Boosting
   - Hyperparameter tuning  
   - Model evaluation with metrics  

4. **Evaluation Metrics**
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score  

5. **Prediction**
   - User can input car details (year, km driven, fuel, etc.)  
   - Model outputs an estimated selling price  
---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   cd car-price-prediction
