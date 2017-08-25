# SmartTrans_Arduino
This is the public sketch for SmartTrans using an Arduino

##Important information
The sketch is provided as-is, we've run it on a Genuino 101 with an Intel Currie chip.  Yes, this chip is now being
discontinued from Intel so we will soon port to another arduino version.
Other than the accelerometer, most chip will do the work.

##BTLE
Working with Bluetooth Low Energy can be an experience at times and we use the term loosely...

##Sensors
For this example we are using sensors from DF Robotics. Most sensors work the same way, one major difference that we have
seen is around sound sensors with some models returning a level (i.e. 1,2,3,4...) and others returning a db (decibel) approximation.

Also check on the manufacturer's settings for units. For temperatures for example, some sensors are in C others in F and it makes quite a difference!
