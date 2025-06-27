# 🐟 Fish Weight Prediction using Multiple Linear Regression

This project applies a multiple linear regression model to predict the weight of fish based on measurable physical features like length, width, height, and species. It’s built using a clean dataset for educational purposes to solidify regression fundamentals and feature engineering skills.

---

## 📊 Dataset Information

- **Source:** Fish Market Dataset  
- **Features:**  
  - Species (Categorical)  
  - Length1, Length2, Length3, Height, Width (Numerical)  
  - Target: Weight

---

## 🚀 Project Workflow

1. **Exploratory Data Analysis (EDA)**
   - Histograms, boxplots, and scatterplots
   - Pair plots by species
   - Outlier detection
2. **Feature Engineering**
   - Dropped redundant length columns
   - Categorical encoding for `Species` (OneHotEncoder)
   - Standard scaling for numerical features
3. **Model Building**
   - Split data (75% train / 25% test)
   - Applied Multiple Linear Regression via Scikit-learn
4. **Model Evaluation**
   - MAE (Test): **64.86**
   - R² Score (Test): **93.9%**
5. **Visualization**
   - Mean weight per species  
   - Boxplot by species  
   - Correlation heatmap

---

## 🧠 What I Learned

- Practical application of preprocessing pipelines with `ColumnTransformer`  
- Encoding categorical features for regression tasks  
- Evaluating model fit using MAE and R²  
- Using visual insights to inform modeling decisions

---

## 🛠️ Tech Stack

- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook

---

## 🧪 Run It Yourself

```bash
# Clone the repository
git clone https://github.com/yourusername/fish-weight-regression.git

# Open the notebook in Jupyter and run cells in order
