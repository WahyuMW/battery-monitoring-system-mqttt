BATTERY MONITORING SYSTEM AT SMART MICROGRID BASE ON INTERNET OF THINGS (IoT) USING MQTT COMMUNICATION PROTOCOL

In a previous study conducted at the Laboratory of Energy Management of Engineering Physics ITB, a battery monitoring system at smart microgrid base on IoT by using the HTTP protocol has successfully created. However, the system is considered as having a pseor performance in terms of speed and reliability because of the slow speed of transferring data, the unsent data, and the absence of redundant data storage.
In this final project, the development of a battery monitoring system is conducted by providing redundant data storage in a local database server owned by Energy Management Laboratory of Engineering Physics ITB and by creating a battery management system with communication protocol MQTT (Message Queing Telemetry Transport) which consists of two scenarios broker arrangement.
From the tests, it was found that the average execution time of data from the publisher to get to the cloud server in the systems using the HTTP communication protocol is 5,438 seconds, while using the protocol MQTT 3.004 seconds in the first scenario and 2.962 seconds in the second scenario. In addition, the sistem pemantauan baterai using communication protocols MQTT in the first scenario has an average execution time of 3.012 seconds and of 3.016 seconds in the second scenario for the data transmission to the Raspberry Pi. To deliver the data to the cloud server, the average execution time takes 3.004 seconds in the first scenario and 2.962 seconds in the second scenario. The value of availability of all the systems is above 90%.
