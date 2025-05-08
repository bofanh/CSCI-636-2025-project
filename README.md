# NYC Yellow Taxi Trip Data Analysis

This project analyzes **New York City yellow taxi trip records** to explore trends, perform feature engineering, and build machine learning models for predictive tasks.

## 🚕 Dataset

We use the [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page), specifically:

- `yellow_tripdata_2025-01.parquet`

Additional metadata:
- Zone lookups
- Data dictionary

## 📦 Getting Started

### Download the data

```bash
wget https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2025-01.parquet
```

### Environment

This project runs on Python 3.8+ with the following libraries:
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn
- jupyterlab / notebook

To set up a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt
```

## 🧪 Project Structure

- `project.ipynb`: Main notebook with data processing, EDA, and ML models.
- `data/`: Contains downloaded datasets and zone metadata.
- `figures/`: Visualizations and plots (to be generated).
- `README.md`: Project overview and setup instructions.

## 📊 Objectives

- Load and preprocess trip data.
- Perform feature engineering (e.g., pickup/dropoff time encoding, trip duration).
- Classify or regress target variables such as trip duration or fare prediction.
- Evaluate model performance using metrics like accuracy, MAE, confusion matrix.

## 📈 Example Analysis

- Time-based ride distributions
- Location pair patterns
- Predictive modeling on trip attributes

## 📌 Notes

- Ensure sufficient memory to handle large datasets (~1M+ rows).
- Optional: explore deep learning methods if scaling beyond traditional ML.