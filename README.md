# crop_recommendation_system

This project aims to predict the most suitable crop based on soil nutrient values (N, P, K), temperature, humidity, pH, and rainfall using a Random Forest Classifier. The NPK values are obtained from hardware consisting of an Arduino Uno R3, DHT11 sensor, pH sensor, NPK sensor, and an OLED display.

Table of Contents
Overview
Hardware Components
Software Components
Installation
Usage
Contributing
License


Overview
This project leverages a Random Forest Classifier to predict the best crop to plant based on real-time soil and environmental data. The data is collected using an Arduino setup, processed, and then fed into a machine learning model for prediction.

Hardware Components
Arduino Uno R3
DHT11 Sensor (for temperature and humidity)
pH Sensor
NPK Sensor
OLED Display


Software Components
Python 3.x
Pandas
Scikit-learn
Matplotlib (for visualization, if needed)


Installation

Clone the repository:

git clone https://github.com/your_username/crop-prediction-npk.git
cd crop-prediction-npk

Install required Python packages:
pip install pandas scikit-learn matplotlib

Upload the Arduino Code:

Ensure you have the Arduino IDE installed.
Open arduino_code.ino  in the Arduino IDE.
Connect your Arduino Uno R3 and upload the code.


Usage
Run the Python Script:

python crop_prediction.py
Input Values for Prediction:

The hardware setup will provide real-time values for N, P, K, temperature, humidity, pH, and rainfall.
Enter these values when prompted by the script.

View Predicted Crop:

The script will output the most suitable crop based on the input values.
Example

Enter values for prediction:
N: 30
P: 40
K: 50
Temperature: 25
Humidity: 80
pH: 6.5
Rainfall: 200
Predicted crop: Wheat

License
This project is licensed under the MIT License.

