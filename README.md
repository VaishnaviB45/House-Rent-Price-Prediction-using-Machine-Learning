#  House Rent Price Prediction using Machine Learning

This project focuses on predicting **monthly house rent prices** using regression-based machine learning techniques. The model is trained on a **self-collected real-world dataset** and evaluates multiple algorithms to determine the best-performing model.

---

##  Project Objective
To build a machine learning model that accurately predicts house rent prices based on property features such as locality, area, furnishing status, and amenities.

---

##  Dataset Description

### Dataset Source
- ✔ Self-collected using **Google Forms**
- ✔ Data collected from people living in **different areas of Pune**

### Dataset Size
- **Total Records:** ~20,000

### Features (Input Variables)
- **Locality** – Area/location of the property  
- **Area (sq.ft.)** – Size of the house  
- **Furnishing Status** – Unfurnished / Semi-Furnished / Fully Furnished  
- **Amenities** – Parking, lift, power backup, etc.

### Target Variable
- **Rent_INR** – Monthly house rent in Indian Rupees

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

##  Data Preprocessing
- Data cleaning and handling missing values
- Encoding categorical features
- Feature selection and transformation
- Train-test split for model evaluation

---

##  Machine Learning Models
- **Linear Regression**
- **Decision Tree Regressor**

Both models were trained and compared to improve prediction accuracy.

---

##  Model Evaluation Metrics
- **Mean Absolute Error (MAE)** – Measures average prediction error
- **R² Score** – Measures how well the model explains variance in rent prices

### Best Model
- **Decision Tree Regressor** performed better with lower MAE and higher R² score.

---

##  Results & Conclusion
- The project successfully demonstrates an **end-to-end regression pipeline**.
- Decision Tree Regressor captured non-linear relationships more effectively.
- The final model can predict rent prices for new properties based on input features.

---

## 📂 Project Structure

