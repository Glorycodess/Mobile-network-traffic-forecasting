# Mobile Network Traffic Forecasting

## Overview
This project presents a comparative analysis and forecasting of mobile internet traffic data recorded over the city of Milan, Italy. The dataset was released by Telecom Italia Mobile (TIM) as part of the Big Data Challenge and contains Call Detail Records (CDRs) aggregated across a 100×100 grid of 10,000 geographical areas over November-December 2013.

The project covers three main tasks:
- **Task 1:** Large-scale data handling and memory optimization
- **Task 2:** Exploratory data analysis including temporal, spatial and statistical analysis
- **Task 3:** Time series forecasting using SARIMA, LSTM and GRU models

## Demo Video
https://youtu.be/jzLyT4VkYok

## GitHub Repository
https://github.com/Glorycodess/Mobile-network-traffic-forecasting

## Dataset
Download the full dataset from Harvard Dataverse:
- Telecommunications Activity (62 files, ~5GB): https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EGZHFV
- Milan Grid (GeoJSON): https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/QJWLFU

**Important:** Place all 62 txt files in a folder called `milan_data/` on your Desktop at `~/Desktop/milan_data/`. Place the `milano-grid.geojson` file in the `formative1/` project folder.

## Hardware Used
- Machine: Apple MacBook Pro
- Chip: Apple M2
- RAM: 8GB
- OS: macOS
- Python: 3.10

## Requirements
Create a virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn tensorflow keras geopandas folium psutil
```

## How to Run

### macOS/Linux:
1. Clone the repository:
```bash
git clone https://github.com/Glorycodess/Mobile-network-traffic-forecasting.git
cd Mobile-network-traffic-forecasting
```
2. Create and activate virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```
3. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn tensorflow keras geopandas folium psutil
```
4. Download the dataset from Harvard Dataverse and place all 62 txt files in `~/Desktop/milan_data/`
5. Open `formative-1.ipynb` in VS Code or Jupyter
6. Run all cells in order from top to bottom

### Windows:
1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate: `venv\Scripts\activate`
4. Install dependencies: `pip install pandas numpy matplotlib seaborn statsmodels scikit-learn tensorflow keras geopandas folium psutil`
5. Download dataset and place in `C:\Users\YourName\Desktop\milan_data\`
6. Open `formative-1.ipynb` and run all cells