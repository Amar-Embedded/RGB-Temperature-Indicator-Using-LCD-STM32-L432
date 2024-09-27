# RGB LED Temperature Indicator Using Temperature Sensor-L432

Project Description: RGB LED Temperature Indicator Using Temperature Sensor
This project implements an RGB LED indicator that changes color based on temperature readings from a temperature sensor. The system utilizes an analog temperature sensor, ADC (Analog-to-Digital Converter), and PWM (Pulse Width Modulation) to achieve the desired functionality.

Components Used:

RGB LED: To visually represent different temperature ranges with colors.
Temperature Sensor: An analog sensor measures the ambient temperature.
ADC: Converts the analog signal from the temperature sensor to a digital value.
Microcontroller: STM32L432KC processes the temperature readings and controls the RGB LED.
PWM: Used to control the brightness of the RGB LED.

Functionality:

Temperature Measurement: The temperature sensor continuously monitors the ambient temperature and outputs an analog voltage proportional to the temperature.
ADC Conversion: The microcontroller reads the analog voltage using the ADC, converting it into a digital temperature value.
PWM Control: The brightness of each RGB color is adjusted using PWM based on the temperature value, allowing for smooth transitions between colors.
This project showcases the integration of temperature sensing and RGB color display, providing a visual representation of temperature changes in real time.
