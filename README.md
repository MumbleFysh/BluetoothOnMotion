# BluetoothOnMotion
"Android Bluetooth-on-Motion" Originally by Dagfinn Parnas
_______________________________________________________________

cBlue
cLocator

by MumbleFysh

________________________________________________________________


Basically I'm stealing this code to put in a larger app based on a car experience for android. Attributed above.



This app comes with both a feature to turn on bluetooth and a car locator. I intend to change the trigger method to turn on bluetooth, currently it's a location/speed based function. I want to explore and see what other options there are. 





Original project text:

>This is an android app which was created since I always forget to turn on bluetooth and thereby enable hands-free before I drive. It should be an ideal companion to anyone who use handsfree through bluetooth in their car, but turn have bluetooth off otherwise. It listens to location events in order to determine that you are travelling faster than a certain configurable speed threshold. If you are, it turns on the bluetooth adapter without requiring any user input. If you're phone is registered with the car's bluetooth adapter, they should now automatically connect. Eventually, it should also turn off bluetooth after a certain configurable time periode with little or no movement

>Android Bluetooth On Motion was created since I always forget to turn on bluetooth and thereby enable hands-free before I drive. It should be an ideal companion to anyone who use handsfree through bluetooth in their car, but turn have bluetooth off otherwise. The primary component of the app is a service which listens to location events from GPS or the phone network in order to determine the speed you are travelling with. It compares your speed with the configurable speed threshold in the application. If you have exceeded the speed threshold, it turns on the bluetooth adapter without requiring any user input. If you're phone is registered with the car's bluetooth adapter, it should now automatically connect after a few seconds. When you stop the car, the phone will after a few seconds notice that the bluetooth connection has been released. After this event, bluetooth is turned off. The service will now go back to its initial state. As a bonus, I've added a Car Locator feature (inspired by Locator application). When the bluetooth connection has been released, a notification on the phone will be created allowing you to track back to the car. Please note that the accuracy of the location can be quite bad, so it is not in all circumstances it works well.
