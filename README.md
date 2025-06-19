# Student Retention Predictor
Predict the likelihood of student retention at U.S. colleges using machine learning and U.S. Department of Education data

## Project Overview
This project builds a machine learning model to predict whether a college will have a high student retention rate. It includes:
- Data cleaning and exploratory analysis (see `notebooks/eda.ipynb`)
- Model training and evaluation (see `notebooks/retention-model.ipynb`)

## Setup Instructions

1. **Create and activate a virtual environment:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Explore and visualize the data:**
   - Run the notebook `notebooks/eda.ipynb` to explore and visualize data from the college scorecard

4. **Train and evaluate the machine learning model:**
   - Run the notebook `notebooks/retention-model.ipynb` to retrain and export a new model to `models/model.pkl`