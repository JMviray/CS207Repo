Make Your Plant Smart
=========
The project we planned to build is the construction of the Make Your Plant Smart Arduino Project. In this project, we are going to monitor the plant's condition using the 3 sensor we have used for this project. The sensor that we have used are Humidity and temperature sensor, soil moisture sensor and the photoresisitor. with these sensors, we are able to monitor the temperature and humidity as well as the light that coming towards the plant and the moisture of the soil. Using the Make your plant smart, we can atleast help people specially those who are beginners in taking care of plants.
![alt text][pic1]

[pic1]: https://github.com/JMviray/CS207Repo/blob/master/imge/E0C56E03-CB5C-4D65-AB56-125FC032976E.jpeg


Requirements and Materials
=========
Dependencies
* https://www.arduinolibraries.info/libraries/dht-sensor-library
* https://www.arduinolibraries.info/libraries/ssd1306

Bill of Materials
* 1 x Arduino Nano R3 or Arduino Uno
* 1 x DHT11 Temperature and Humidity Sensor
* 1 x Soil Moisture Sensor
* 1 x 150V 5mm Photoresistor Sensor
* 1 x TinyShield Ribbon Cable Extender

Build Steps
========
* The OLED display pin header should be desoldered.
* Separate the OLED display from the board which provides the SPI communications, the board is placed in a wet sand, to also hide the wires.
*  Solder the wires to the board, make all the connections and components waterproof because the board is going to be placed in a wet sand.
![alt text][pic2]

[pic2]: https://github.com/JMviray/CS207Repo/blob/master/imge/3EF274E3-BBE3-4A17-96FB-7AF8FDFE360C.jpeg

* Our moisture sensor has only 2 pins, for ground and 5V, but we need three so we used an amplifier. We also made it waterproof.
![alt text][pic3]

[pic3]: https://github.com/JMviray/CS207Repo/blob/master/imge/48393081_2153541184960250_1916917786232225792_n.jpg

* The temperature sensor was connected with a 10k ohm between ground and sensor's pin, then make it waterproof.
![alt text][pic4]

[pic4]: https://github.com/JMviray/CS207Repo/blob/master/imge/48056236_2086813271568226_8072528020813905920_n.jpg

* Empty some sand from your plant's pot and bury the the board and soil sensor leaving the temperature sensor outside.
* And we're all set!

Usage
========
* Measures the plants condition through sensors.
* The OLED displays what the plants conditions are.


Presentation Day
========
What we have worked on today is that, we've tried to work on with our OLED project. I don't know if the problem is on the connection or the problem is the display module itself. We have tried our very best to make it work with our project but it really fails to work. So, the other plan for display has been made. We have decided to put all the reading in the serial monitor to display all the readings that the people need to see for their plant's condition. We have also presented our project in front of the class successfully. 

Team
========
The tasks of doing this project,from ordering the materials, to building it, are equally worked together. 
* John Michael Viray
* Ma Lourdes Tambanillo

Credits
=======
“Make Your Plant SMART! By Arduino.” Arduino Project Hub,
create.arduino.cc/projecthub/electropeak/make-your-plant-smart-by-arduino-01c462.
