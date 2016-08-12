# SmartHome
Building a smart home.

Inspired by and building off the concepts discussed in BUILD YOUR OWN DAMN SMART HOME
presented by Brandon Satrom at "That Conference" in Wisconsin Dells, 2016.


Goal:


To provide a smart home system that uses open source software and hardware.

It shoud not ever hinder the use of the home in any way. Such as not being able to gain entry into the home in the event of a power outage. Manual backups/overrides should be created for anything that is automated. 

Design the entire system in free open source manners using common tooling. The server should be able to un on a variety of systems, Raspberry Pi, Mac Mini, any flavor of Linux or even Windows. Tooling examples could include Arduino, GCC, Javascript Frameworks, EagleCAD



Ideas:

Keyless Entry - Can be NFC with a keyfob. Biometric scanner. Bluetooth device detection.

Mail Detection - Prox switch inside of the mailbox detecting door and flag status.

Temp Control - When to turn on and off a furnace and or a/c unit. Also logging of temp sensors.

Basement Humidity - Always knowing the humidity of the basement. Also, safe/vault humidity logging as well to keep valeuables safe.

Electricity Consumption - Keeping tabs on electricity consumption. 

Attic Temp - Logging of the attic temperature. 

Sump Pump Status - Knowing when it is working and logging, to see patterns. Tying it in with the external weather data one could predict when to keep good eyes on it to ensure you don't come home to a flooded basement. For example if you know that whenever it rains more than one inch per hour for more then three hours the sump pump always kickes on at least once after two hours and if it has rained more than that and it hasn't kicked on, send a warning.

Door Status - Know the status of a door, a log of it's activity.

Window Status - Know when a window is open. External weather data would also be good to aid in when the windows should be open versus using A/C.

Motion Detection - Know what is moving outside the house. Also detect motion in hallways and activate subtle lighting for navigation in the dark.

Dog Door Status - Know when a pet crosses through a pet door.

Dog Door Locking - Automatically lock the pet door on a schedule. 

Attic Fan Control - Tying into the attic temp data and external temp data, be able to circulate air in the attic with outside air when the house is in a cooling time and the air outside is cooler than the air in the attic. 




sensors:

temp, humidity, wind speed, wind dir, motion detection, light, door, window







