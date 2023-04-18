# Room_Occupancy_Estimation

## About the project:
The project is about estimating the number of occupants in the room from the inputs of the different sensors, so the HVAC system can adjust itself to the required 
level of cooling or heating.

## What is HVAC system:
HVAC stands for Heat Ventilation and Air Conditioning. The HVAC systems involves from simple AIr conditioning to complex ducting and Air Handling Units systemss. As the
name suggests, the HVAC maintains the air temperature of the zone and it achieves the desired temperature based on the sensor inputs it recieves, like room temperature, 
water temperature etc.
This project aims to predict the number of occupants in the room based on various inputs like temperature, CO2 level and so on for better HVAC system response.

## Data:
Link to dataset: https://www.kaggle.com/datasets/ananthr1/room-occupancy-estimation-data-set

The data was taken from Kaggle and has more than 10,000 records and 19 columns.
The experimental testbed for occupancy estimation was deployed in a 6m Ã— 4.6m room. The setup consisted of 7 sensor nodes and one edge node in a star configuration 
with the sensor nodes transmitting data to the edge every 30s using wireless transceivers. No HVAC systems were in use while the dataset was being collected.

Attribute Information:

Date: YYYY/MM/DD

Time: HH:MM:SS

Temperature: In degree Celsius

Light: In Lux

Sound: In Volts (amplifier output read by ADC)

CO2: In PPM

CO2 Slope: Slope of CO2 values taken in a sliding window

PIR: Binary value conveying motion detection

Room_Occupancy_Count: Ground Truth

