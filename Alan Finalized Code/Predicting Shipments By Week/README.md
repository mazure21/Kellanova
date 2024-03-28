# Predicting Shipments By Week

This directory contains files and instructions for predicting shipments by week.

## Data Preparation Steps

1. **Download Data:**
   - Download the 'POS_Kel_num_agg_merged.csv' file from the Kellanova team's Git repository. Ensure it is located in the same directory as this README.

2. **Upload CSV File:**
   - Upload the CSV file to the current directory where this notebook is located.

3. **Download Models:**
   - Download the following models and place them in the same directory as this README:
     - 'Kel_POS_base_model.h5'
     - 'KEL_POS_lstm_model.h5'

4. **Run the Following Cells:**
   - Execute the cells below to perform further analysis and visualization on the data, and later on to evaluate the models' results.

## Directory Contents

- **Kel_POS_base_model.h5:** This file contains the base model for predicting shipments.

- **KEL_POS_lstm_model.h5:** This file contains the LSTM model for predicting shipments.

- **POS_Kel_num_agg_merged.csv:** This CSV file contains aggregated shipment data merged with POS data.

- **Kel Shipment Differences by Week Agg.ipynb:** This Jupyter notebook contains code for analyzing and visualizing shipment differences by week.

## Expected Output

### Visualizations

- **Difference Between Actual and Planned Shipments by Week (Baseline Model, All Data):**  
  ![Baseline Model, All Data](Visualizations/Baseline%20Model,%20All%20Data.png)  
  - Average Difference: -141485.26 USD  
  - RMSE: 82838.51 USD

- **Difference Between Actual and Planned Shipments by Week (Baseline Model for Testing):**  
  ![Baseline Model for Testing](Visualizations/Baseline%20Model%20for%20Testing.png)  
  - Average Difference: -1002033.70 USD  
  - RMSE: 84786.48 USD

- **Difference Between Actual and Predicted Shipments by Week (Prototype Model):**  
  ![Prototype Model](Visualizations/Prototype%20Model.png)  
  - Average Difference: 737287.25 USD  
  - RMSE: 42682.80 USD

- **Difference Between Actual and Predicted Shipments by Week (LSTM Model):**  
  ![LSTM Model](Visualizations/LSTM%20Model.png)  
  - Average Difference: 420266.69 USD  
  - RMSE: 29992.56 USD

## Notes

- Make sure to follow the instructions carefully to ensure smooth execution of the analysis.

- Ensure that the necessary data files and models are in the correct directory before running the code cells.
