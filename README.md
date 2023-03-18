# Improving-Turbine-Efficiency-in-Ships

An exhaustive dataset of Ship's logs containing data from gas turbine rate of revoution to lever position and ship speed and the correlation between all these parameters with the decay state coefficient(rate at which turbine energy decays) of compressor, turbines in the ship.

The aim of this project is to accurately calculate the decay state coefficient that helps in predicting the frequency of maintenance and give timely repairs to the ship's turbines and compressors that helps in not only being energy efficient but also prevents ship mishaps at sea and save thousands of dollars.  

### Dataset:

http://archive.ics.uci.edu/ml/datasets/condition+based+maintenance+of+naval+propulsion+plants

Predicting Gas Turbine plant's decay state coefficient, two outputs: GT Compressor decay state coefficient and GT Turbine decay state coefficient.

Phases of the project are as follows:

    1. Data Preprocessing
    
    2. Exploratory Data Analysis
    
    3. Data Visualization
    
    4. Feature Selection
    
    5. Regression Models
    
    6. Comparative Study
    
### Results :


1. For Compressor Decay:

| Models               | Training Accuracy  | Testing Accuracy  | Error    |
| -------------        |:------------------:| -----------------:| ------:  |
| Linear Regression    | 0.843676           | 0.840362          | 0.163777 |
| KNN                  | 0.955039           | 0.918073          | 0.084051 |
| Decision Tree        | 1.000000           | 0.984062          | 0.016351 |
| Random Forest        | 0.999092           | 0.994253          | 0.005896 |



 2. For Turbine Decay:

| Models               | Training Accuracy  | Testing Accuracy  | Error    |
| -------------        |:------------------:| -----------------:| ------:  |
| Linear Regression    | 0.911244           | 0.910862          | 0.005896 |
| KNN                  | 0.914175           | 0.860251          | 0.005896 |
| Decision Tree        | 1.000000           | 0.958500          | 0.005896 |
| Random Forest        | 0.998257           | 0.988999          | 0.005896 |




## Inference
We can say that the data for both turbines and compressors can be accurately calculated with least error by Random Forest models and this model should be further used to predict decay state coefficient for most of the ships of the company and take business decisions accordingly.
