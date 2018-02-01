# Mechatronics_hw
Shuo's Mechatronics homework
1. FSR

When I test FSR on class, I find that the degree of change pressure is not linear. The change is not starting from 0. So I need to think about some math problem. 



2.IR Sensor

The detector needs a parallel resistor. As you can see, there's 3 cables on IR sensor, how to access the sensor to  a circuit? Then I analysed the circuit diagram, I found that the three cables put the LED and the sensor in parallel to the power. Ground connected the LED and the sensor together.



3. TMP36 Temperature Sensor

If there are several detectors on the same circuit, they may affect each other. what is delay reading? how to toss the result?



https://github.com/adafruit/Adafruit_Sensor
this is a library which include so many sensor data. standardised SI units for each sensor family the same sensor types return values that are comparable with any other similar sensor.

https://www.youtube.com/watch?v=T5Aq7cRc-mU
This piece looks very nice，and it shows production  process of this work.
 
