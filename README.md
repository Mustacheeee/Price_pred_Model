# House Price Prediction using Ensemble Learning

This project demonstrates the use of advanced ensemble learning techniques to predict real estate prices based on a dataset from the Madrid housing market. The model utilizes multiple features to estimate property values and compares the performance of various ensemble methods.

### Features used for prediction:
- `sq_mt_built` – Total square meters built
- `n_rooms` – Number of rooms
- `n_bathrooms` – Number of bathrooms
- `is_renewal_needed` – Boolean indicating if the property needs renovation
- `is_new_development` – Boolean indicating if it's a new development
- `has_fitted_wardrobes` – Boolean indicating if fitted wardrobes are included

## Objective

Build, train, and evaluate various ensemble machine learning models to predict house prices, and compare their performance using key metrics such as Mean Absolute Error (MAE) and R² Score.

## Tools & Libraries

- Python
- Google Colab
- pandas, numpy
- scikit-learn (Random Forest, Gradient Boosting, etc.)
- matplotlib, seaborn

##  Running the Notebook

1. Open the notebook in [Google Colab](https://colab.research.google.com/):
   - Upload both `house_price_pred.ipynb` and `madrid_real_estate.csv` to your Colab environment.

2. Ensure the CSV file is properly loaded by setting the correct path in the code.

3. Run all cells to train models, visualize results, and view evaluation metrics.

## 📈 Model Evaluation

The notebook includes:
- Data preprocessing and feature engineering
- Training and evaluation of ensemble models
- Performance comparison of different techniques
- Visualizations to interpret results

## 🧠 Learnings

This project showcases:
- Practical application of ensemble models in real-world regression tasks
- Model interpretability using feature importance
- Comparison of multiple model types for predictive performance


