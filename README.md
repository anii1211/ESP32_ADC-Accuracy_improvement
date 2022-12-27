# ESP32_ADC-Accuracy_improvement

The ADC is not a strong point of the ESP32 because it has many flaws. Use the Arduino one or an external ADC if you want to make accurate measurements.
ADC2 cannot be used with enabled WiFi since it is used internally by the WiFi driver.
The ADC can only measure a voltage between 0 and 3.3V. You cannot directly measure analog voltages between 0 and 5V.
