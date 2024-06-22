# Ocean Oracles
This repository contains Jupyter Notebook files for predicting Sea Surface Temperature (SST) due to the El Niño-Southern Oscillation (ENSO). The model is trained using the _train.csv_ file, which comprises 104,409 rows and 10 columns. It incorporates features such as date, geographic location, wind speeds, air temperature, and humidity.
## Repository Structure
The repository consists of two main parts:
### 1. Evaluation Data Prediction:
• **Objective**: Predict the SST for the evaluation.csv file, which contains data from the years on which the model is trained.<br/>
• **Usage**: To obtain the predicted SST for evaluation.csv, open and run the Evaluation_answers.ipynb notebook on your device.<br/>
• **Output**: The predicted SST for evaluation.csv is saved in the evaluation_filled_sst.csv file.<br/>
### 2. Future Data Prediction:
• **Objective**: Predict the SST for the data_1997_1998.csv file, which contains data for upcoming years.<br/>
• **Usage**: To obtain the predicted SST for data_1997_1998.csv, open and run the Data_1997_1998_predictions.ipynb notebook on your device.<br/>
•	**Output**: The predicted SST for data_1997_1998.csv is saved in the data_1997_1998_predictions.csv file.<br/>
## Data Description
### train.csv
•	**Contains 104,409 rows and 10 columns.**<br/>
•	**Columns**: year, month, day, latitude, longitude, zon.winds, mer.winds, humidity, air temp., s.s.temp.<br/>
### evaluation.csv
•	**Contains data for the same years as train.csv.**<br/>
•	**Columns**: year, month, day, latitude, longitude, zon.winds, mer.winds, humidity, air temp.<br/>
### data_1997_1998.csv
•	**Contains data for future years (1997-1998).**<br/>
•	**Columns**: year, month, day, latitude, longitude, zon.winds, mer.winds, humidity, air temp.<br/>
## Instructions
### 1.	Clone the Repository:
```bash
git clone https://github.com/NidhishDoshi/OceanOracles.git
```
### 2.	Install Required Packages: Ensure you have the necessary Python packages installed. You can use the following command:
```bash
pip install -r requirements.txt
```
### 3.	Running the Notebooks:
•	Open Jupyter Notebook on your device.<br/>
•	Navigate to the repository directory.<br/>
•	Open and run _Evaluation_answers.ipynb_ to generate predictions for evaluation.csv.<br/>
•	Open and run _data_1997_1998_predictions.ipynb_ to generate predictions for _data_1997_1998.csv_.<br/>
### 4.	Check the Output:
•	The predicted SST for _evaluation.csv_ will be available in _evaluation_filled_sst.csv_.<br/>
•	The predicted SST for _data_1997_1998.csv_ will be available in _data_1997_1998_.<br/>
## Notes
•	Ensure that the _train.csv_, _evaluation.csv_, and _data_1997_1998.csv_ files are in the same directory as the Jupyter Notebooks.<br/>
•	If you encounter any issues, please refer to the notebook's markdown cells for detailed explanations and troubleshooting tips

_Created in **Twins of the Winds** during the **Summer of Innovation 2024**_
