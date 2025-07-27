# house-price-prediction
# House Price Prediction 🏠📊

This project uses Machine Learning to predict house prices based on features like overall quality, area, number of bathrooms, etc.

## Project Structure
- `data/`: Contains `train.csv` and `test.csv`
- `notebooks/`: EDA, Feature Engineering, Feature Selection
- `model.pkl`: Trained model using Random Forest
- `submission.csv`: Final predicted values for test set

## Algorithms Used
- Random Forest Regressor
- Feature Importance-based Selection

## Evaluation Metric
- RMSE: 29478.18

## How to Run
1. Clone the repo
2. Run the notebooks in order: EDA → Feature Engineering → Feature Selection → Model Training
3. Load `model.pkl` and use it for predictions
