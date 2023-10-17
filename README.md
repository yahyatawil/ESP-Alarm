# ESP-Alarm
This project was built for [Allaboutcircuit](https://www.allaboutcircuits.com/projects/esp-alarm-set-alarms-from-your-mobile-phone-esp8266-arduino-uno-wifi-iot/) published in 2017. 

![image](https://github.com/yahyatawil/ESP-Alarm/assets/1148381/146c6b41-aa09-4bd9-842b-a32c593476b3)

## Hardware 
* Arduino UNO or any compatible board (optional).
* ATmega328P (optional).
* ESP8266 Wi-Fi module, ESP-01 model.
* 1.44-inch TFT display module.
* TP4056 breakout board (Li-ion battery charger).
* DS1307 (RTC chip)
* 74LVX4245 (5V-3V3 level converter)
* USB TTL converter cable (optional)

![image](https://github.com/yahyatawil/ESP-Alarm/assets/1148381/e0cefadf-899f-4034-b7f7-6b17867037f9)

![image](https://github.com/yahyatawil/ESP-Alarm/assets/1148381/e3927d1c-085c-4618-95e8-3e15eac13043)

## Software / Arduino code
The code depends on the following libraries:

* TFT_ILI9163
* Adafruit_GFX
* DS1307RTC
* Wire (for I2C connection)
* EEPROM (to store alarms in the internal EEPROM)
* SoftwareSerial (optional debugging)


## Android App 


Many thanks to my friend Jihad Al-bathish (AKA Joud) for developing a native Android application for this project.



## Demo
https://www.youtube.com/watch?v=W3wOcIKqi2k
