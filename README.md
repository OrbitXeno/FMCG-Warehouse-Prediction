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
- **Rows**: 1000 (replace this with the actual count)
- **Columns**: 24

## Steps to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/OrbitXeno/FMCG-Warehouse-Prediction.git
   cd FMCG-Warehouse-Prediction
