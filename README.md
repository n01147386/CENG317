# RaspiGuard - Door Sensor
A magnetic contact switch security application

#### Purpose :
Installing a home security system can be costly, but not installing one could cost you even more. Most home or office intrusions are done when they are least expected. Having a security system in place provides people a warning to get to a safe location in or outside the building while the alarm system provides pressure to the intruder and in addition could dispatch local authorities.

#### Here is a little video of the application to give you a better idea :

[Click here to play](http://165.227.44.224/Build_Video.mp4)



#### Component Requirements :
In order to replicate this project you need :

* A working and running Raspberry Pi 

* A Magnetic contact switch, for example :  (<https://www.adafruit.com/product/375/>)	(also sold in your local hardware store of course)

* You are going to be connecting the RPI with the contact switch , so IF you need longer cables then pick some up.

* Raspberry Pi jumper wires are <b>recommended</b> but not required.

<strong>All of these components above should cost you no more than $100 </strong>

![picture alt](http://munro.humber.ca/~n01147386/1.png)

#### Getting Started :

1. Start off by mounting your contact switches to your targer door

![picture alt](http://munro.humber.ca/~n01147386/2.png)

2. Next, establish a wired connection between the door switch and your Raspberry Pi
* You need to connect one of the wires to Pin #23 and the other one to <b>ANY</b> ground, for example Pin #25

**note : it does not matter which cable of the switch is connected to Pin #23 or GND, the circuit works either way.**

![picture alt](http://munro.humber.ca/~n01147386/3.png)
![picture alt](http://munro.humber.ca/~n01147386/4.png)

3. Fetch my <b>python script</b> for the application. I will be supplying a <b>base skeleton</b> where you could customize the door events yourself. Personally I have integrated a MySQL database to this application, where I store door all activities such as opening and closing the door. Also I have made an alarm system where it's possible to toggle door alarm on/off and receive alarm alerts on my cell phone but that's more advanced and out of the scope for this course. It's also possible to program that in case of an alarm event, the local authorities / your personal security company could be alerted.

[Click here to see the python code](http://munro.humber.ca/~n01147386/doorSensor.py)


4. <b>Once your python script is ready then you are all done, simply start the script </b>. The complexity in this project was to figure all of these things out but since I've layed out all the instructions for you it appears to be a very trivial project now does it :)

![picture alt](http://munro.humber.ca/~n01147386/5.png)


#### You're Done!
