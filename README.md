# Prediction-of-Product-Sales
## 

**Robin Abrahams**: 

### Business problem:
We had been tasked to help determine and test a SalePrediction model to see which elements impact the store's sales.


### Data:
This included the 
* Items Sold
* Item MRP
* Outlet Type
* Location of Stores 
* Item Outlet Type

## Methods
We applied standard dataprocessing techniques:
* Feature evaluation
* Data Cleaning (duplicate removal/inconsistency correction)
* Developed a Data Pipeline (numeric & categorical)
* ColumnTransformer
* Train_Test_Split
* Applied a Linear Regression Model
* Applied a Random Forest Model

## Results

### Here are examples of how to embed images from your sub-folder


#### Visual 1 Title
![image](https://github.com/Robinino99/Prediction-of-Product-Sales/assets/138812946/59539992-06ba-451b-b146-619705a227ba)

Standard heatmap to determine which features correlated the most the Item_Outlet_Sales

#### Visual 2 Title

![image](https://github.com/Robinino99/Prediction-of-Product-Sales/assets/138812946/1f4c8f72-675f-4448-9aa8-3abeddcc8ca5)

The above chart, was implemented to determine the average item sales based on outlet type. 

### Model implemented

Based on the dataset and testing we opted for a Random Forest Model.

### Metrics
R^2  - fit 57% of the time on the test data.
MAE - $773 was out.
RMSE - $1, 118 was only


## Recommendations:

This model was overfitted to the training data. This could be linked to the size of the dataset or the complexity of the model chosen. 


## Limitations & Next Steps

To improve the model further we should consider increasing the size of the dataset. 


### For further information


For any additional questions, please contact **email**
