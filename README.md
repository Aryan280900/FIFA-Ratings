# FIFA 21 Player Rating Prediction 🎮⚽

This project predicts FIFA 21 player Overall Ratings (OVR) using machine learning models trained on a dataset of 17K+ players and 40+ performance attributes.

## 📂 Dataset

- **Source**: FIFA 21 player stats (e.g., Kaggle or other open sources)
- **Records**: 17,000+ male football players
- **Attributes**: Technical (Dribbling, Passing), Physical (Pace, Strength), Mental (Vision, Reactions), and Goalkeeping (GK Reflexes, Diving)

## 🔍 Project Objectives

- Understand key factors influencing player ratings
- Build a predictive model for OVR using regression
- Apply data preprocessing and feature engineering
- Visualize trends and correlations in player performance

## 🛠️ Tools & Technologies

- **Languages**: Python
- **Libraries**: pandas, NumPy, scikit-learn, matplotlib, seaborn, plotly, missingno
- **Notebook**: Jupyter Notebook (`.ipynb`)

## 🚀 Workflow

1. **Data Cleaning**
   - Handled missing values
   - Converted and standardized data types
2. **Exploratory Data Analysis (EDA)**
   - Distribution plots, correlation heatmaps
   - Identified most influential features on OVR
3. **Feature Selection**
   - Selected 40+ relevant player attributes
   - Removed redundant or non-predictive columns
4. **Preprocessing**
   - Label encoding, scaling
   - Train-test split
5. **Modeling**
   - Linear Regression
   - (Optional) Random Forest, Decision Tree, Ridge/Lasso
6. **Evaluation**
   - R² Score, RMSE
   - Visual inspection of residuals and predictions

## 📈 Visualizations

- Feature correlation matrix
- Attribute impact charts
- Predicted vs actual rating scatter plots

## 📌 Key Findings

- Strongest predictors of OVR include Reactions, Ball Control, and Short Passing
- Goalkeeping attributes were excluded for outfield player predictions
- Linear models performed well with moderate tuning

## 🧠 Learnings

- Effective preprocessing significantly boosts model accuracy
- Feature selection is key in sports analytics
- Visualization helps communicate ML results to non-technical audiences

## 💡 Future Work

- Expand to player potential (POT) prediction
- Use advanced ML models like XGBoost or neural networks
- Cluster players into roles using unsupervised learning

## 🖥️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/FIFA21-Rating-Prediction.git
   cd FIFA21-Rating-Prediction
