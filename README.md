# CODETECH-task-1
NAME : Aakash P
COMPANY : CODETECH IT SOLUTIONS
ID : CT08DKX
DOMAIN : Embedded systems
DURATION : December 12th 2024 to janauary 12 2025
MENTOR : Neela Santhosh

overview of TEMPERATURE AND HUMIDITY MONITORING WITH DHT SENSOR

Objective:
The objective of this code is to interface a PIC16F887A microcontroller with a DHT11 sensor to measure temperature and humidity, and display the readings on a 16x2 LCD.

Technology Used and Key Elements:
The technology used includes the PIC16F887A microcontroller, which is responsible for controlling the sensor and LCD, the DHT11 sensor for acquiring temperature and humidity data, and the 16x2 LCD for displaying the values. The code is written in C, a common language for embedded systems development. Key elements of the code include functions to control the LCD, such as initialization and displaying data, as well as functions to communicate with the DHT11 sensor. This communication involves sending a start signal, checking the sensor’s response, and reading the data bytes. The temperature and humidity values are then processed and displayed, with error handling in place for checksum mismatches or lack of response from the sensor.

Key Activities:

LCD Initialization and Control:
The code initializes the 16x2 LCD by configuring the necessary pins and sending the required commands to set up the display mode, clear the screen, and enable the display.

DHT11 Sensor Communication:
The code generates a start signal to the DHT11 sensor, checks for its response, and reads the temperature and humidity data by receiving a series of bytes from the sensor.

Data Processing and Display:
The received data is processed, and the temperature and humidity values are formatted for display. The values are shown on the LCD screen, with a degree symbol for temperature and a percentage sign for humidity.

Error Handling:
The code includes error handling for situations such as checksum errors or when the sensor does not respond, ensuring the system remains reliable.

Looping and Refreshing:
The main program continuously reads the sensor data at regular intervals (2 seconds), refreshing the LCD with updated information.



