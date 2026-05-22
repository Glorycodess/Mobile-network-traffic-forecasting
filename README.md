# Mobile Network Traffic Forecasting

## Overview
This project analyses and forecasts mobile internet traffic data from the city of Milan, Italy, using the Telecom Italia Big Data Challenge dataset.

## Dataset
Download the dataset from Harvard Dataverse:
- Telecommunications Activity: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EGZHFV
- Milan Grid: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/QJWLFU

Place all 62 txt files in a folder called `milan_data/` on your Desktop.

## Requirements
Install dependencies:
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn tensorflow keras geopandas folium psutil

## How to Run
1. Clone the repository
2. Download the dataset and place in ~/Desktop/milan_data/
3. Open formative-1.ipynb in VS Code or Jupyter
4. Run all cells in order

## Models Implemented
- SARIMA (Classical Statistical)
- LSTM (Neural Network)
- GRU (Neural Network)

## Results
SARIMA outperformed both neural network models across all three geographical areas.