# Bangalore House Price Prediction 🏡💰
**End-to-End Machine Learning Project** | Python • Scikit-learn • Real Estate

A complete, production-ready house price prediction system for Bangalore (Kaggle dataset). Built from raw messy data to a working web app — exactly the kind of project recruiters love to see.

Live Web App → Open `https://bangalore-home-price-prediction-ae1a.onrender.com` (or deploy anywhere)

## Real Model Performance (GridSearchCV + ShuffleSplit CV)

| Model              | Best R² Score | Best Parameters                              |
|--------------------|---------------|----------------------------------------------|
| Random Forest      | **0.84**      | n_estimators=100, max_depth=None             |
| Linear Regression  | 0.86          | -                                            |
| Gradient Boosting  | 0.85          | learning_rate=0.1, n_estimators=100          |
| Lasso              | 0.81          | alpha=0.1                                    |
| Decision Tree      | 0.80          | max_depth=10, min_samples_split=2            |

**Best Model:** Linear Regression (0.86 R²) → saved as `model/best_model.joblib`

## What I Did (Full ML Pipeline)
- Data cleaning & handling missing values, wrong formats
- Feature engineering (price_per_sqft, location grouping, BHK logic)
- Outlier removal using **business rules + statistical methods** (mean ± 3σ)
- different visualizations to detect outliers
- Dimensionality reduction
- Trained 5 algorithms with proper cross-validation
- Hyperparameter tuning using **GridSearchCV**
- Model selection based on R² score
- Built a clean, responsive web app using **HTML, CSS, JavaScript** (no Streamlit)

## Tech Stack
Python • Pandas • Scikit-learn • Matplotlib • Seaborn • Joblib • HTML/CSS/JS

## Project Structure