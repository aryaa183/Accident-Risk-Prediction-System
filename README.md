# Accident-Risk-Prediction-System

This project implements a machine learning system to predict accident risk levels based on historical accident data and location information.

## Project Structure

```
accident_risk_project/
├─ data/
│  ├─ raw/           # Raw accident data (place accidents.csv here)
│  └─ processed/     # Processed data files
├─ notebooks/        # Jupyter notebooks for analysis
├─ src/             # Source code
├─ static/          # Static files (generated maps)
├─ templates/       # HTML templates
├─ models/         # Trained models
└─ requirements.txt # Project dependencies
```

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Place your accident data file (accidents.csv) in the `data/raw/` directory.

## Usage

1. Data Processing:
   - Use the notebooks in `notebooks/` to explore the data
   - Run preprocessing scripts to prepare the data

2. Model Training:
   - Train the model using the processed data
   - The trained model will be saved in `models/`

3. Web Application:
   - Start the Flask application:
   ```bash
   python src/app.py
   ```
   - Access the web interface at `http://localhost:5000`

## Features

- Interactive risk map visualization
- Real-time risk prediction for specific locations
- Historical accident data analysis
- Machine learning-based risk assessment

## Dependencies

Main dependencies include:
- Python 3.8+
- pandas
- scikit-learn
- Flask
- folium
- joblib

See `requirements.txt` for complete list of dependencies.
