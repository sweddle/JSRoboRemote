# JSRoboRemote
JavaScript gamepad remote for Robots, Arduino, Raspberry Pi and other IoT microcontrollers using WiFi.

# JSRoboRemote
JavaScript gamepad remote for Robots, Arduino, Raspberry Pi and other IoT microcontrollers using WiFi.

JS Robo Remote was developed with the intent to give users a way to control robots and microcontrollers with a joystick or gamepad over WiFi rather than having to buy and use RF-based remotes, receivers, and servos. 
We had been working with robot competition groups and most of them had to use the same old RF remotes used for hobby RC cars and plains. They cost a lot and did not offer much other than one-way control of servers and other actuators. 
Knowing that JS could take input from a USB or BT connected gamepad or joystick I set out to create JS Robo Remote. Best of all it allows for much more than just one-way control of servos and actuators as it is a fully extensible code base and uses two-way communications over WiFi it can report back sensor data and allows for automated resonances using JS. The potabilities are endless!

You can implement JSRoboRemote in a few ways.
Configuration example One. 
1) The JSRoboRemote code runs on(served) by the microcontroller that is on the robot. 
2) Your gamepad is then connected to a smartphone/laptop (or using BT)
3) The microcontroller is configured to provide a captive portal WiFi AP, Your smartphone/laptop will connect to it.
4) Upon connection to the captive portal your smartphone/laptop loads the JSRoboRemote website.
5) You're all set! your gamepad should now show as connected on the website and be able to control the robot/microcontroller. 
-  We have a few examples of this you can load on Arduinos/Node32'/Esp8266 and Raspberry Pi's. Link

Configuration example Two.
1) The JSRoboRemote code runs on the laptop or SmartPhone that your gamepad is connected to.2) The SmartPhone/Laptop has a folder on it with the RoboRemote code in it. you open the index.html file in that folder using Chrome or any modern browser.
- Link to code to use on SmartPhone/Laptop 3) The JSRoboRemote web page will then recognize your connected gamepad.4) You can then configure JSRoboRemote to connect to your robot/microcontroller, all you need to know is its IP address.5) The robot/microcontroller will need to be on WiFi and configured to take commands sent to it by JSRoboRemote as well as send data back to JSRoboRemote. 
- We have a few examples of this you can load on Arduinos/Node32'/Esp8266 and Raspberry Pi's. Link

