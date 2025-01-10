# FMCG-Warehouse-Prediction

This project focuses on optimizing FMCG warehouse operations using predictive analytics. It includes data exploration, model training, and evaluation to predict key metrics like product weight in tons. The model enables better inventory management, logistics optimization, and operational efficiency for real-world applications.

## Table of Contents
1. [Objective](#objective)
2. [Dataset Description](#dataset-description)
3. [Steps to Run the Project](#steps-to-run-the-project)
4. [Dependencies](#dependencies)
5. [Key Features](#key-features)
6. [Model File](#model-file)
7. [Real-World Applications](#real-world-applications)

## Objective
The aim of this project is to improve FMCG warehouse operations by:
- Predicting product weight in tons for better inventory planning.
- Identifying patterns to optimize logistics and warehouse resource allocation.

## Dataset Description
- **Filename**: `FMCG_data.csv`
- **Features**:
  - `Ware_house_ID`, `WH_Manager_ID`: Identifiers for warehouses and managers.
  - `Location_type`, `zone`: Location details of the warehouse.
  - `num_refill_req_l3m`, `storage_issue_reported_l3m`: Operational metrics for the warehouse.
  - `product_wg_ton`: Target variable representing the weight of products in tons.
- **Rows**: 5
- **Columns**: 24

## Steps to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/OrbitXeno/FMCG-Warehouse-Prediction.git
   cd FMCG-Warehouse-Prediction

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt

4. **Run the Notebook**:
  - Open the Jupyter notebook Optimizing_FMCG_Warehouse_Operations_Using_Predictive_Analytics.ipynb.
  - `Execute the cells to:
  -Perform Exploratory Data Analysis (EDA).
  -Train the predictive model.
- EValuate the model
4. **Save and Load the Model**:  
   After running the notebook, you can save the trained model to your local system using `joblib`:
   ```python
   import joblib
   # Save the model
   joblib.dump(rf_regressor, 'rf_regressor_model.pkl')

   # Load the model for future use
   loaded_model = joblib.load('rf_regressor_model.pkl')

## Dependencies
The project requires the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `joblib`

Install all dependencies with:
```bash
pip install -r requirements.txt
```
## Key Features

- **EDA**:  
  Visualizes and identifies trends in the data.

- **Model Training**:  
  Builds a predictive model to estimate product weight.

- **Model Evaluation**:  
  Generates performance metrics like accuracy and error scores.

- **Visualization**:  
  Includes charts and heatmaps to explain data patterns.


## Model File

The trained model can be saved to your local system using the code provided in the notebook.  
The saved file (`rf_regressor_model.pkl`) can be loaded and used without retraining.

### Classification Report

The trained model produces the following performance metrics (as an example, update with actual values):

- **R² Score**: 0.994  
- **Mean Squared Error (MSE)**: 768002.55  

For classification tasks, metrics like **accuracy**, **precision**, and **recall** can also be included.


## Real-World Applications

- **Demand Forecasting**:  
  Predict stock levels to prevent overstocking or understocking.

- **Logistics Optimization**:  
  Plan transport routes and schedules.

- **Warehouse Management**:  
  Allocate resources for efficient operations.

- **Cost Reduction**:  
  Minimize operational costs using optimized predictions.
```
