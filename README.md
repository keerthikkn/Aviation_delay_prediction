# Flight Delay Analysis and Prediction using XGBoost
![1000_F_579977074_apyEfjVti6c9hwRqQn5hD5gEXTAvW23G](https://github.com/keerthikkn/Aviation_delay_prediction/assets/42544473/a5b51fe0-3335-4b25-b11f-84ba89ea8c26)

## Overview
This machine learning project's goal is to analyze and predict flight delays based on weather, precipitation and past aviation data. Given a collection of input data, the goal is to create a predictive model that can accurately forcast the possibility of flight delays for future flights.
## Requirements
- Python 3.x
- XGBoost
- pandas
- scikit-learn
- pickle
- seaborn
- numpy

## Dataset
The project uses a flight dataset containing historical flight information, including various features such as airline, origin, destination, scheduled departure time, and others. Make sure to obtain the dataset and place it in the appropriate directory.
## EDA
![image](https://github.com/keerthikkn/Aviation_delay_prediction/assets/42544473/1a755fd5-30be-489e-9e76-a57b2d256565)
Delay status for each day of the week

![image](https://github.com/keerthikkn/Aviation_delay_prediction/assets/42544473/184e558f-b3e6-4141-b670-103486c02d70)
Delayed and Not delayed ratio

## Project Structure

- `Aviation_delay.ipynb`: jupyter notebook containing EDA, feature engineering, model and hyperparameter tuning.
- `xgbmodel.pkl`: trained model saved as pkl file
- `requirements.txt` : required dependencies and modules 
- `README.md` : detailed description about the project.
- `data/` : directory containg datasets.

## Usage
1. Install the required dependencies by running the following command:
```
pip install -r requirements.txt
```

2. Place the flight dataset file in the `data/` directory.

3. Preprocess the dataset and train the XGBoost model, The trained model will be saved in the `models/` directory as a pickle file.

4. Evaluate the trained model's performance.

5. Predict flight delays for new data using the trained model by loading the pickle file.

## Conclusion

### performance

![image](https://github.com/keerthikkn/Aviation_delay_prediction/assets/42544473/ca52c479-491d-4c72-9784-ae7807563156)
![image](https://github.com/keerthikkn/Aviation_delay_prediction/assets/42544473/4e26d88a-a7de-41c4-be1e-b20bb0971d6e)

This project provides a framework for analyzing and predicting flight delays using XGBoost. The trained model can be used to forecast flight delays and potentially help airlines and passengers make informed decisions.
