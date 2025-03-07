# House-Price-Prediction
# House Price Prediction - Hackathon

## Overview
This project aims to predict house prices using machine learning techniques. Given a dataset with 79 features, including living area, number of rooms, and location, we train a model to learn the relationship between these features and the house prices.

## Dataset
- **Train Dataset:** Contains historical house prices with 79 features.
- **Test Dataset:** Houses without price labels for prediction.

## Project Structure
```
|-- data/               # Raw and processed datasets
|-- notebooks/          # Jupyter Notebooks for analysis
|-- src/               # Scripts for data processing and modeling
|-- models/            # Saved trained models
|-- README.md          # Project documentation
```

## Dependencies
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- scipy

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/house-price-prediction.git
   cd house-price-prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Execute the notebook `House_Price_Hackathon.ipynb` step by step.

## Key Steps in Notebook
1. **Data Loading**: Load train and test datasets.
2. **Exploratory Data Analysis**: Visualize data distributions and correlations.
3. **Feature Engineering**: Handle missing values and categorical variables.
4. **Model Training**: Train and evaluate regression models.
5. **Prediction**: Generate price predictions for test data.

## Results
- Achieved accurate price predictions using machine learning.
- Improved model performance through feature engineering.

## Future Enhancements
- Tune hyperparameters for better accuracy.
- Implement deep learning models for comparison.
- Deploy the model as an API for real-time predictions.

## Author
Vaishali

## License
This project is licensed under the MIT License.

