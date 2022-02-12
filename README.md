## Predictive Analytics in Manufacturing
Predictive analytics assists manufacturers in predicting machine failures , or to predict the maintenance required for machines in advance. The targeted problem was to predict the Water Pump failure using the data collected from the IoT sensors and an alerting system to report pump related anomalies.

## Technologies and Models Used:

- IoT sensors
- AWS Kinesis
- AWS S3 Bucket
- AWS Glue
- AWS Sagemaker

  Models:
- Logistic Regression
- ARIMA
- LSTM
- XGBoost

Steps Involved:

- Data collected from the IoT sensors through the IoT gateway measuring the suction pressure, discharge pressure, flow, vibration, temperature, 
air pressure, pump speed, humidity, and power. The data was taken from Kaggle.
- Some data was generated and streamed using AWS Kinesis data generator.
- The data was stored in the AWS S3 Bucket
- The ETL process was done in AWS Glue, where the normalisation of data is crucial
- The ML models were implemented using AWS Sagemaker
- The XGBoost algorithm gave the best prediction accuracy compared to other models.
