# Smart-Agriculture
The purpose of this project is to monitor and control the farm appliances using Mobile phone. This can be achieved by use of temperature, humidity, soil moisture, and sound sensor, which senses the temperature, humidity, and soil moisture content and its output will be available to the farmer anytime-anywhere in his mobile phone. 

The proposed project presents the idea of controlling farm appliances wirelessly. The system
uses wireless module which is based on cloud to operate devices located at distant locations
in farm remotely without visiting the site. Whenever the user sends the request for getting
the information regarding surrounding environmental conditions, the temperature and
humidity sensor DHT11 and soil moisture sensor captures the surrounding temperature,
humidity, and soil moisture content. Then those readings are forwarded to ThingSpeak for
analysis and storing for user reference. This captured temperature, humidity, and soil
moisture content are then displayed in form of graph to user. Depending on received data the
user decides whether the appliances should be operated or not. If the particular appliance needs to be turned ON or OFF the user sends the corresponding request which is programmed
for turning that device ON or OFF. That alert is then forwarded to Raspberry Pi and required
action is performed. The status of the device whenever it is turned ON or OFF is also
received by the user. If required, the user can also monitor current status of all devices in the
farm by sending corresponding request that is programmed for it. A user can view the
database for historic as well as current temperature, humidity, and soil moisture readings,
devices operated by user along with timestamp, if necessary, to carry out further operations.
By this database user can also get to know the activities carried out in the farm.
