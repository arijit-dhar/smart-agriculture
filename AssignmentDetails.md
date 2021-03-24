# Assignment Details
Details of the smart-agriculture assignment. 

### Project Title:
Smart Agriculture.

### Project Description: 
1. Develop IoT level 5 system for smart agriculture. The developed system should be able to measure:  
a. Soil Moisture level (Student 1: Chandan Kumar Samal)\
b. Environmental Temperature (Student 2: P V Murali)\
c. Water level of a tank (Student 3: Arijit Dhar)\
d. PH level of the soil (Student 4: Dheeraj D Kamath)\
e. Surrounding light (Student 5: Dielle Anjali Coutinho)

2. All the data collected should be stored on the cloud.
3. Plants in the smart garden should be watered based on soil moisture level, Environmental Temperature and Water Level of a tank.
4. Plant growth depends on PH Level of the soils and surrounding light. Appropriate action needs to be taken based on the PH level and surrounding light level.
5. SMS and email regarding the status of the smart agriculture system should be sent to the owner.

### Hardware & Other Components list:
* [Arduino Uno Board](https://www.amazon.in/Arduino-UNO-board-DIP-ATmega328P/dp/B008GRTSV6) - Main Microcontroller for sensor integration and processing
* [ESP8266 Module](https://www.electronicscomp.com/esp8266-esp01-wifi-module?gclid=Cj0KCQiA-aGCBhCwARIsAHDl5x9s-oPnow1cWleGh7N9C2HWGTBHztebjSHQulG9WLH7teTIofUJePQaAr0wEALw_wcB) - For WiFi connectivity and making RESTful API calls 
* OR, [Node MCU ESP8266 Module](https://www.electronicscomp.com/nodemcu-esp8266-wifi-development-board?search=Node%20MCU) - this includes firmware that runs on the ESP8266 Wi-Fi SoC from Espressif Systems, and hardware which is based on the ESP-12 module. 
* [Soil Moisture Sensor Module](https://www.electronicscomp.com/soil-moisture-sensor-module-india?search=Soil%20Moisture) - For measuring the moisture or, water level content in the soil.
* [DTH11 Temperature/Humidity Sensor](https://www.electronicscomp.com/dht11-temprature-humidity-sensor-module-india?gclid=Cj0KCQiA-aGCBhCwARIsAHDl5x_LVh2CjXTFdwdG0JsFVv5UIDyRpRiZlito8L4-PIaHpaYzN90RUY4aAsKnEALw_wcB) - For measuring the temperature and humidity of the surrounding
* [HC-SR04 Ultrasonic Sensor](https://robu.in/product/hc-sr04-ultrasonic-range-finder/?gclid=Cj0KCQiA-aGCBhCwARIsAHDl5x-SA2CdPxEqjyiDGrX1pLh4unL09V3-hP1ZEr5rkmzE-VPyPopmGu8aAovxEALw_wcB) - For distance measurements particulary water level of the tank
* [Solenoid Valve](https://www.hnhcart.com/products/solenoid-valve-1-2-dc-3-6v-water-control-electric-pulse-solenoid-valve?variant=37522859229358&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&utm_campaign=gs-2020-11-23&utm_source=google&utm_medium=smart_campaign) - For controlling the water flow.  <b> Any specific Model? </b>
* <b>Water Storage & Pipes:</b> How to measure the water flow? Need to use same diameter pipes?
* [PH Sensor](https://www.electronicscomp.com/analog-ph-sensor-kit-for-arduino?gclid=Cj0KCQiA-aGCBhCwARIsAHDl5x_yCftqmTv63b7V6m3Pgp0hXnWhars9fBxy4pccBdaWYKHlTXjoQqgaAlzaEALw_wcB) - For measuring the PH Level of the soil. <b> Any specific Model? Did someone already tried using this one?</b>
* [Ambient Light Sensor 3 pin](https://www.electronicscomp.com/ldr-light-sensor-module-india?gclid=Cj0KCQiA-aGCBhCwARIsAHDl5x_o3Oog8AlarSK8qfNBAgZHpufpf_sQvhIHLIg1xKs_Hnf-wcUPVEoaAtV-EALw_wcB) - For detecting ambient light of the surrounding. 
* [Ambient Light Sensor 4 pin](https://robu.in/product/lm393-photosensitive-light-dependent-control-sensor-module/) - <b> Do we need 3 pin OR, 4 pin LDR Module? </b>
* [GSM Module](https://www.electronicscomp.com/sim800l-v2-5v-wireless-gsm-gprs-module-quad-band-with-antenna?gclid=Cj0KCQiA-aGCBhCwARIsAHDl5x-fi_tKI1Y1cgQ6LWnCPEQbEAzpfA_C7bFBDWx2DbYMkGKzmXEmnycaAq-GEALw_wcB) - For integrating the SIM card and sending messages. <b>Any specific Model? Did someone already tried using this one?</b>


### Questions: 
1. 

