# Microprocessor-Final-Project28
# Smart Home Security and Environmental Monitoring Station
This project is a microcontroller-based integrated security system developed as part of the final project for the Microprocessors course.

## Project Objective
To simultaneously monitor both the security of the home (password-based entry) and vital risk factors (gas leakage, temperature-humidity) via a single control unit, and to activate the alarm mechanism in critical situations.
##  Hardware Components Used
- Controller: ATmega328P-based Microcontroller
- Input: 4x4 Matrix Keypad = For user password entry
- Sensors: - MQ-2 Combustible Gas and Smoke Sensor
  - DHT11 Digital Temperature and Humidity Sensor
- Output: - 16x2 I2C LCD Display = For status notification
  - SG90 Servo Motor = For electronic lock simulation
  - Active Buzzer = For audio warning system

##  Technical Specifications
- Software Language: C
- Architecture: Interrupt-based emergency management and motor control with PWM.
- Analysis: LTSpice simulations will be used for sensor signal stability.


[images of when the system is running.docx](https://github.com/user-attachments/files/27514763/images.of.when.the.system.is.running.docx)

[EEE308_22020228_ProjectReport.pdf](https://github.com/user-attachments/files/27515091/EEE308_22020228_ProjectReport.pdf)
