# Building Permit Analysis Project

## Project Overview
This project focuses on analyzing building permit data using Dataiku DSS (Data Science Studio). It provides insights into construction trends, permit processing patterns, and related analytics.

## Project Structure
- `raw_data/`: Contains the original building permit datasets
- `processed_data/`: Stores transformed and cleaned datasets
- `analysis_notebooks/`: Jupyter notebooks containing exploratory data analysis
- `ml_models/`: Trained machine learning models and model artifacts
- `visualizations/`: Data visualization outputs and reports
- `config/`: Project configuration files
- `temp_uploads/`: Temporary storage for data uploads
- `analysis_results/`: Output of various analyses

## Data Sources
The project uses building permit datasets:
- Building Permits Dataset 1 (02_01_BuildingPermits)
- Building Permits Dataset 2 (02_02_BuildingPermits)

## Setup Instructions
1. Install Dataiku DSS from [Dataiku's website](https://www.dataiku.com/product/get-started/)
2. Import this project into Dataiku DSS:
   - Open Dataiku DSS
   - Go to Projects → Import Project
   - Select all files from this directory
   - Follow the import wizard

## Project Components
1. **Data Processing**
   - Initial data cleaning
   - Feature engineering
   - Data validation

2. **Analysis**
   - Exploratory Data Analysis (EDA)
   - Statistical analysis
   - Trend identification

3. **Machine Learning Models**
   - **Ridge Regression (L2 Regularization)**:
     - Predicting Estimated Value in building permits
     - Predicting State Valuation in building permits
   - **Feature Engineering**:
     - PCA (Principal Component Analysis) for dimensionality reduction
   - **Model Applications**:
     - Value Estimation: Predicting the estimated value of building projects
     - State Valuation: Forecasting state-level property valuations
     - Both models use regularization to prevent overfitting and handle multicollinearity

## Usage
After importing the project:
1. Access notebooks in `analysis_notebooks/` for detailed analysis
2. View processed data in `processed_data/`
3. Check visualization outputs in `visualizations/`
4. Access trained models in `ml_models/`

## Dependencies
- Dataiku DSS (Free or Enterprise Edition)
- Python libraries (automatically managed by Dataiku)
- No SQL dependencies required

## Notes
- All data is stored in flat files for easy portability
- Project is self-contained with all necessary components
- Designed for easy replication and analysis 
