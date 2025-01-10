# FMCG-Warehouse-Prediction
This project focuses on optimizing FMCG warehouse operations using predictive analytics. It includes data exploration, model training, and evaluation to predict key metrics like product weight in tons. The model enables better inventory management, logistics optimization, and operational efficiency for real-world applications.

Table of Contents
Objective
Dataset Description
Steps to Run the Project
Dependencies
Key Features
Model File
Real-World Applications
Objective
The aim of this project is to improve FMCG warehouse operations by:

Predicting product weight in tons for better inventory planning.
Identifying patterns to optimize logistics and warehouse resource allocation.
Dataset Description
Filename: FMCG_data.csv
Features:
Ware_house_ID, WH_Manager_ID: Identifiers for warehouses and managers.
Location_type, zone: Location details of the warehouse.
num_refill_req_l3m, storage_issue_reported_l3m: Operational metrics for the warehouse.
product_wg_ton: Target variable representing the weight of products in tons.
Rows: (Fill this with the number of rows in your dataset.)
Columns: 24
Steps to Run the Project
Clone the Repository:

bash
Copy code
git clone https://github.com/OrbitXeno/FMCG-Warehouse-Prediction.git
cd FMCG-Warehouse-Prediction
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Notebook: Open the Jupyter notebook Optimizing_FMCG_Warehouse_Operations_Using_Predictive_Analytics.ipynb and execute the cells to:

Perform EDA (Exploratory Data Analysis).
Train the predictive model.
Evaluate the model.
Reproduce the Model:

The trained model is not included due to file size limitations.
Follow the notebook to train and save the model.
Dependencies
The project requires the following Python libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
Install all dependencies with:

bash
Copy code
pip install -r requirements.txt
Key Features
EDA:
Explores patterns and relationships in the data.
Model Training:
Trains a predictive model to forecast product weights.
Visualization:
Provides insightful visualizations for data understanding.
Model File
The trained model (rf_regressor_model.pkl) is not included in this repository due to GitHub’s file size limitations. You can generate the model by running the notebook. Alternatively, host the model externally (e.g., Google Drive) and include the download link.

Real-World Applications
Demand Forecasting: Predict warehouse stock requirements.
Logistics Optimization: Plan transportation routes and schedules efficiently.
Warehouse Management: Optimize space and resources for product storage.
Cost Reduction: Improve operational efficiency to reduce logistics costs.
Feel free to fork, modify, and share this project. Let us know your thoughts or contributions!
