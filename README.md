# music-genre-classification
Machine learning project for multiclass music genre classification using preprocessed audio features.

## Project Structure

music-genre-classification/
│── data/
│   ├── raw/
│   └── processed/
│       ├── train_processed.csv
│       └── test_processed.csv
│── notebooks/
│   ├── 01_data_analysis.ipynb
│   └── 02_preprocessing.ipynb

## Data Preprocessing

The preprocessing pipeline includes:

- Removal of low-variance features
- Correlation analysis
- Feature scaling
- Generation of processed datasets for model training

The resulting datasets are saved in `data/processed/`.