
# 🏡 Median House Price Prediction - California Housing Dataset

## 📌 Project Overview
Predicting median house prices using the **California Housing Dataset** by applying various machine learning models and selecting the best one.

## 📊 Dataset
- Contains housing information from California
- **Rows:** 20,640
- **Features:**
  - Longitude 📍
  - Latitude 🌍
  - Housing Median Age 🏠
  - Total Rooms 🏧
  - Total Bedrooms 🏦
  - Population 👥
  - Households 🏡
  - Median Income 💰
  - **Target:** Median House Value 💲

## 🔄 Project Workflow
### 1️⃣ Data Collection & Preprocessing
✔ Load dataset 👅  
✔ Handle missing values 🚀  
✔ Feature scaling & engineering 🛠️  
✔ Split data into train & test sets (80% train, 20% test) ✂️  
✔ Data Cleaning 🪑  
✔ Handling Text & Categorical Attributes 🌤️  
✔ Feature Scaling ⚖️  
✔ Created custom transformers:
   - **Log Transformer** 📈
   - **RBF Transformer** 🌐
   - **Ratio Transformer** ➗
✔ Implemented **Transformer Pipelines** 🔄

### 2️⃣ Exploratory Data Analysis (EDA)
✔ Visualize feature distributions 📊  
✔ Visualize data geographically to gain insights 🗺️  
✔ Identify correlations 🔗  
✔ Experiment with attribute combinations ⚗️  
✔ Detect & handle outliers ⚠️  

### 3️⃣ Model Selection & Training
✔ Train multiple models:
   - **Linear Regression** 📉
   - **Decision Trees** 🌳
   - **Random Forest** 🌲🌲🌲
✔ Evaluate initial performance 🎯

### 4️⃣ Training and Evaluating on Training Set
✔ **Linear Regression:** RMSE = **68,647.95** 📉  
✔ **Decision Tree Regressor:** RMSE = **0** (Overfitting) ⚠️  
✔ **Random Forest Regressor:** RMSE = **17,521.56** ✅  

### 5️⃣ Hyperparameter Tuning
✔ **Grid Search:** Tuned number of clusters & max features sizes 🎯
   - RMSE ranged between **43,000 - 44,000**
✔ **Randomized Search:** Tried random combinations of hyperparameters 🎉
   - RMSE ranged between **42,000 - 43,100**
✔ Evaluated best models 🏆

### 6️⃣ Model Evaluation
✔ Evaluated system on the **Test Set** ✅  
✔ **Final RMSE on Test Set:** **41,556.05** 📊  
✔ Metrics used:
    
   - **Root Mean Squared Error (RMSE) 🔢**
  
✔ **Best Model: Random Forest 🎯**

## 📈 Results
| Model              | RMSE      |
|-------------------|----------|
| Linear Regression | 68,647.95 |
| Decision Tree    | 0 (Overfit) |
| Random Forest    | 17,521.56 |
| **Best Tuned Model** | **41,556.05** |

✅ **Random Forest performed best!** 🚀

## 🎓 Key Learnings
- Visualizing data geographically provided valuable insights 🌍
- Correlation analysis helped in feature selection 🔗
- Experimenting with attribute combinations improved prediction accuracy ⚗️
- Scaling & feature engineering improved results ⚙️
- Custom transformers & pipelines enhanced preprocessing 🔄
- Decision Trees overfit, Random Forest generalizes better 🔍
- Hyperparameter tuning boosted performance 🚀

## 🔮 Future Improvements
- Try advanced models like **XGBoost** 🔥
- Improve feature selection 🎯
- Deploy using **Streamlit** or **Flask** 🖥️

## 🛂 Dependencies
- Python 3.8+
- Pandas 🐼
- NumPy 🔢
- Scikit-learn 🤖
- Matplotlib 📊
- Seaborn 🎨

## ✍️ Author
Laxman Kumar Busetty
