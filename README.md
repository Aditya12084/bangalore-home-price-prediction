# Bangalore House Price Prediction 🏡💰  
**End-to-End Machine Learning Project** | Python | Scikit-learn | Real Estate Domain

A production-ready house price prediction system for Bangalore using the famous Kaggle dataset. Built from scratch to showcase complete ML workflow – exactly what recruiters look for in Data Science/ML Engineer roles.

![Python](https://img.shields.io/badge/Python-3.9+-blue) ![scikit-learn](https://img.shields.io/badge/scikit--learn-1.2+-orange) ![Pandas](https://img.shields.io/badge/Pandas-1.5+-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

Live Demo → Open `webapp/index.html` (or deploy on Render/Heroku)

## Key Features (Recruiter Magnet Points)
- Real-world messy dataset → 99% cleaned & engineered
- Business-driven + statistical outlier removal (domain knowledge applied)
- Rich EDA with insightful visualizations (Matplotlib + Seaborn)
- Feature Engineering: price_per_sqft, location clustering, BHK-based logic
- Dimensionality reduction for robust modeling
- Trained & compared 5+ algorithms:
  - Linear Regression • Lasso • Decision Tree • Random Forest • Gradient Boosting
- Hyperparameter tuning using GridSearchCV + ShuffleSplit CV
- Best model achieves ~88% R² on test data
- Model serialized with joblib for production use
- Fully functional web app using pure HTML, CSS & JavaScript (no Streamlit dependency)

## Model Comparison (GridSearchCV Results)
| Model               | Best R² Score | Key Params                          |
|---------------------|---------------|-------------------------------------|
| Random Forest       | 0.879         | n_estimators=100, max_depth=None    |
| Gradient Boosting   | 0.865         | learning_rate=0.1, n_estimators=100 |
| Lasso               | 0.712         | alpha=1                             |

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (full ML pipeline)
- Matplotlib, Seaborn (EDA)
- Joblib (model persistence)
- HTML5, CSS3, Vanilla JavaScript (frontend)
- Flask (optional backend for deployment)

## Project Structure
```
├── data/                  → Raw & cleaned dataset
├── notebooks/             → Exploratory Data Analysis.ipynb
├── src/                   → Cleaning, FE, training scripts
├── model/                 → best_model.joblib
├── webapp/
│   ├── index.html
│   ├── style.css
│   └── script.js          → Calls saved model via Flask API
├── requirements.txt
└── README.md
```

## How to Run Locally
```bash
git clone https://github.com/yourusername/bangalore-house-price-prediction.git
cd bangalore-house-price-prediction
pip install -r requirements.txt
# For web app
python app.py    # or just open webapp/index.html
```

## Future Enhancements
- Deploy on Render / Railway
- Add SHAP explainer for predictions
- Integrate map-based location input

Perfect portfolio project for Data Scientist / ML Engineer roles  
Built with clean code, documentation & production mindset

**Star ⭐ this repo if you find it useful for interviews!**  
Made with ❤️ by [Your Name] | Open to collaborations & full-time opportunities!