# 🏠 House Price Prediction - Linear Regression

## 📌 Project Overview
This project is part of my **Machine Learning Internship** at *SkillCraft Technology*.  
The goal was to build a **Linear Regression model** that predicts house prices based on:
- **Above-ground living area (sq. ft.)** → `GrLivArea`
- **Number of bedrooms above ground** → `BedroomAbvGr`
- **Number of full bathrooms** → `FullBath`

---

## 📂 Dataset
- **Source:** [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- `train.csv` contains 1,460 rows and 81 columns describing properties in Ames, Iowa.
- Target variable: **`SalePrice`**

---

## ⚙️ Tools & Libraries Used
- **Python**
- **Jupyter Notebook**
- **Pandas** – Data handling
- **NumPy** – Numerical operations
- **Scikit-learn** – Model building and evaluation
- **Matplotlib / Seaborn** (optional) – Data visualization

---

## 🧠 Steps Performed
1. **Data Loading**  
   Loaded `train.csv` into a Pandas DataFrame.

2. **Feature Selection**  
   Selected 3 key features:
   - `GrLivArea`
   - `BedroomAbvGr`
   - `FullBath`

3. **Train-Test Split**  
   Split data into 80% training and 20% testing.

4. **Model Training**  
   Used `LinearRegression()` from Scikit-learn.

5. **Evaluation**  
   Calculated:
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score

---

## 📊 Results
- **RMSE:** ~ **31,336.83**  
  *(The model’s predictions are off by around $31K on average)*

---

## 📷 Screenshots
| Dataset Preview | Model Output |
|-----------------|--------------|
| ![Dataset](images/dataset.png) | ![Output](images/output.png) |

---

## 🚀 How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/house-price-prediction.git
2. Navigate to the folder:
   cd house-price-prediction
3. Install dependencies:
   pip install pandas numpy scikit-learn matplotlib seaborn
4. Open the Jupyter Notebook:
   jupyter notebook
5. Run all cells to see results

   🙌 Acknowledgements
Kaggle for the dataset.

SkillCraft Technology for providing this internship opportunity.
<img width="1235" height="418" alt="image 1" src="https://github.com/user-attachments/assets/02eb98cb-419d-4b76-8754-6f18f3a25b18" />
<img width="1197" height="474" alt="image 2" src="https://github.com/user-attachments/assets/eb16c702-c3e9-4c74-97ee-26a77ed25017" />
<img width="1280" height="232" alt="image 3" src="https://github.com/user-attachments/assets/67ac334a-90f4-4bf3-b4ac-3bcaf677a4f6" />
<img width="1274" height="572" alt="image 4" src="https://github.com/user-attachments/assets/e018f524-8a00-427e-a385-3450efb2d3aa" />

