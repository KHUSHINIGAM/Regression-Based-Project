🌡️ Temperature Prediction Project 📊

Overview ℹ️
This project aims to predict the temperature outside the building (T6) based on the temperature in the living room (T2). It utilizes a simple linear regression model to establish a relationship between these two variables.

Dataset 📈
The dataset used for this project is the energydata_complete.csv file, which contains various features related to energy consumption and temperature measurements inside and outside the building.

Project Structure 📂
The project consists of the following files:
energydata_complete.csv: The dataset used for training and testing the model.
temperature_prediction.ipynb: Jupyter Notebook containing the Python code for data preprocessing, model training, evaluation, and analysis.

Data Preprocessing 🛠️
The dataset is loaded into a Pandas DataFrame.
Columns "T2" and "T6" are extracted as features and target, respectively.
The dataset is split into training and testing sets using an 80-20 split.

Model Training 🧠
A linear regression model is trained using the training data to predict T6 based on T2.
The model is fitted to the training data.

Model Evaluation 📊
The trained model is used to make predictions on the testing data.
The Root Mean Squared Error (RMSE) is calculated to evaluate the model's performance.

Results 📉
The RMSE for the linear regression model on the test set is found.

Conclusion 🎉
Based on the RMSE value obtained, the linear regression model provides a reasonably accurate prediction of the temperature outside the building (T6) based on the temperature in the living room (T2).
