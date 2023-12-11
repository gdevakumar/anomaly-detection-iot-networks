# anomaly-detection-iot-networks
Anomaly Detection from Network Traffic on IoT Devices

`E2E_ML_Implementation.ipynb` file contains the code to load the raw data, perform EDA, data & feature engineering, ML model training and validation, saving the model for inference.

`main.py` contains loading the saved model and running inference on a WebUI using Streamlit. It has the option to input top 10 features as per Random Forest Feature Importance. It predicts the class of attack.

## Steps to run the inference code
- Download the trained model in current working directory
- Run the below command
  ```
  streamlit run main.py
  ```
  

## Output
<img src="https://github.com/gdevakumar/anomaly-detection-iot-networks/assets/37027138/320a8538-37ee-4449-b0b5-5abc342eac09" height="400">

<img src="https://github.com/gdevakumar/anomaly-detection-iot-networks/assets/37027138/4584d368-b71e-413f-91ca-6b5b1d46d8e9" height="400">


