1m2-Greenhouse
==============

Plans, electronics and code for a small automated greenhouse

This includes the drawing plans for the greenhouse in it's current state.

The PCB and schematic files for the control electronics with its own readme.

The Code is for an Arduino backend, I'm using a mega2560 but can be scaled to run on any arduino platform. The front end runs python on a Rasberry Pi, sending data requests to the arduino and storing the results in an SQL database and I'm looking to push the data to a webserver on the pi to view the data anywhere on the local network.
