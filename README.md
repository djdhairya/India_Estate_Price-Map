
# Indian House Price Prediction  

## Project Overview  
This project focuses on predicting house prices in major Indian metropolitan cities: **Delhi, Mumbai, Kolkata, Bangalore, Chennai, and Hyderabad**. The prediction is based on various features, including property details, amenities, and facilities provided. Using machine learning techniques and visualization tools, we aim to create an accurate and user-friendly house price prediction model.

---

## Features Considered for Prediction  
The model predicts house prices based on the following segments:  

1. **Property Details**:  
   - Area  
   - Location  
   - Number of Bedrooms  
   - Resale Value  

2. **Amenities**:  
   - Maintenance Staff  
   - Gymnasium  
   - Swimming Pool  
   - Landscaped Gardens  
   - Jogging Track  
   - Rain Water Harvesting  
   - Indoor Games  
   - Sports Facility  

3. **Facilities**:  
   - Shopping Mall  
   - Intercom  
   - ATM  
   - Clubhouse  
   - School Nearby  
   - 24x7 Security  
   - Power Backup  
   - Car Parking  
   - Staff Quarter  
   - Hospital Nearby  

4. **Appliances and Additional Features**:  
   - Washing Machine  
   - Gas Connection  
   - Air Conditioner (AC)  
   - Wifi  
   - Children’s Play Area  
   - Lift Available  
   - Bed  
   - Vaastu Compliance  
   - Microwave  
   - Golf Course Access  
   - Television (TV)  
   - Dining Table  
   - Sofa  
   - Wardrobe  
   - Refrigerator  

---

## Libraries Used  
This project makes use of the following Python libraries:  

- **Data Processing and Analysis**:  
  - Pandas  
  - NumPy  

- **Data Visualization**:  
  - Matplotlib  
  - Seaborn  

- **Machine Learning**:  
  - Scikit-learn  
  - XGBoost  
  - LightGBM  

- **Model Evaluation**:  
  - Scikit-learn metrics  
  - Hyperparameter Tuning with GridSearchCV  

---

## Steps Involved  

### 1. Data Collection  
- Datasets sourced from reliable real estate platforms like  Kaggle, or government portals.  
- Data for Delhi, Mumbai, Kolkata, Bangalore, Chennai, and Hyderabad.  

### 2. Data Preprocessing  
- Handling missing values.  
- Encoding categorical variables.  
- Normalizing numerical features.  

### 3. Exploratory Data Analysis (EDA)  
- Visualizing relationships between price and various features using graphs like:  
  - Heatmaps for correlations.  
  - Boxplots for outliers.  
  - Pair plots for feature relationships.  

### 4. Model Building  
- Implemented machine learning models like:  
  - Linear Regression  
  - Decision Trees  
  - Random Forests  
  - Gradient Boosting (XGBoost/LightGBM)  

### 5. Model Evaluation  
- Metrics used for performance evaluation:  
  - Mean Squared Error (MSE)  
  - R-squared (R²) Score  

### 6. Prediction  
- Predicting house prices for given input features using the trained model.  

---

## Results  
- **Visualization**: Graphs and heatmaps to highlight feature importance and price trends in different cities.  
- **Accuracy**: Achieved high prediction accuracy using advanced models like XGBoost and Random Forest.  

---

## Usage Instructions  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/your-repo-url.git  
     
   ```  

2. **Install Dependencies**  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. **Run the Application**  
   ```bash  
   python ipynb file  
   ```  

4. **Input Features**  
   Enter details like Area, Location, and other amenities to predict the house price.  

---

## Contributions  
Feel free to contribute to the project by:  
- Improving the model accuracy.  
- Adding more cities or features.  
- Enhancing visualization and UI.  

---

## Acknowledgments  
- Datasets sourced from  Kaggle, and public repositories.  
- Special thanks to open-source contributors for developing the libraries used in this project.  

--- 

## License  
This project is licensed under the MIT License.  

---  

