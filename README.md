# Pothole Prediction Using 311 Data

This project analyzes Pittsburgh’s 311 service request data to identify and predict pothole-related issues. It includes geospatial clustering, repeat complaint zone modeling, and forecasting departmental workload.

## How to Run

1. Clone the repository:
   ```bash
   git clone git@github.com:pallavirajan00/90803_group17_finalproject.git
   cd 90803_group17_finalproject
   ```

2. Download `311data.csv` (see Data Requirements section) and place it in the root directory of the project.

3. Open `group_17_final_code.ipynb` and run all cells.

## Data Requirements

The dataset `311data.csv` is not included in the repository due to file size limits.

Download it from:
**[Download Link Here](https://data.wprdc.org/dataset/311-data/resource/29462525-62a6-45bf-9b5e-ad2e1c06348d)** 

Rename to "311data.csv"

Expected path:
```
./311data.csv
```

The file is listed in `.gitignore` and will not be tracked by Git.

## Dependencies

All libraries are imported within the notebook. Key packages include:

- pandas
- scikit-learn
- xgboost
- folium
- branca
- Jinja2
- joblib

To install dependencies:
```bash
pip install -r requirements.txt
```

You can generate this file with:
```bash
pip freeze > requirements.txt
```

## Team

Group 17 — Heinz College, Machine Learning Foundations  
Contributors: Pallavi Rajan, Jon Hellner, Farrukh Masood
