# Patient Severity Prediction Model
This project uses a hybrid machine learning pipeline that combines image data with sensor-based physiological signals (such as heart rate, oxygen saturation, and temperature) to predict whether a patient is in a serious or non-serious condition

### Project OverView
Healthcare monitoring systems often rely on separate inputs like vitals or video monitoring. This model intelligently fuses both visual and sensor data to offer a more robust and early prediction of patient severity. It can be used in:

Emergency response systems
ICU patient monitoring
Home-based health diagnostics
Wearable health devices

### Features
Multi-modal Input: Combines image-based features with real-time sensor readings.
Deep Learning + ML Fusion: CNN for image processing, traditional ML (e.g., Random Forest / XGBoost) for structured sensor data.
Real-Time Ready: Optimized for fast inference on edge devices (e.g., Raspberry Pi + camera + pulse oximeter).
Binary Classification: Outputs Serious or Not Serious labels.

### Input Format
Realtime Video and data from sensors

### How It Works?
Image Processing: A CNN model extracts features from the patient's facial image (signs of fatigue, sweating, stress).
Sensor Data Processing: Features like heart rate and oxygen saturation are passed through a classifier (e.g., XGBoost).
Feature Fusion: The extracted image features and sensor data are combined and passed through a meta-classifier for the final prediction.

### Future Improvements
-- Dashboard
-- Multimodel prediction

