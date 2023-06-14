# BigDataProject

**Smart Virtual Thermostat**

This project implements a virtual thermostat with a responsive web interface. The virtual thermostat is equipped with features like manual 
temperature setting,scheduling a temperature for a specific time range, turning the thermostat on/off, and an AI mode which suggests the 
optimal temperature.

The project consists of three main files:

    Prediction_Model.ipynb: This Python script is used to create a Flask server and handles the requests coming from the web interface. 
    It is also responsible for providing the suggested temperature in the AI mode.

    Create_Push-Synthetic_Data.ipynb: This Python script is basically used for purpose of creating synthetic data and pushing the same 
    data into Database
    
    User_Interface.html: The web interface for the virtual thermostat. It provides the interface for setting the temperature manually, 
    scheduling a temperature, switching between Manual and AI modes, and turning the thermostat on and off.

Usage:

Step 1: Our "Prediction_Model" file is basically fetching the data from our database for training and prediction. In order to make it easy 
for users, one can use the "data.csv" file attached, and completely omit creating data using Create_Push_Synthetic_Data file.

Step 2: After training the model with data, running the last cell of "Prediction_Model" file will establish a connection with the server
using Flask. This will provide a link which you can use to direct to the user interface.

Note: All files should be in same directory, otherwise paths should be adjusted accordingly. 
