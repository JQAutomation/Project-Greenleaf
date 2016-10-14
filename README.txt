-----Project Greenleaf------
Version: Preliminary
10-13-16 Jacob Quick
----------------------------
Version History
----------------------------
Preliminary 10/13/16 - Set up repository and introductory documentation



----------------------------
Introduction
----------------------------
Project Greenleaf (PG) is intended to be a fully functioning, open-source garden automation system. This will be comprised of a software package written in C#, technical drawings of hardware configurations, and user operating documentation. As time goes on, additional functionality will be rolled into new versions. Initially, however, basic monitoring, controls, and data logging will be implemented to ensure a strong framework on which to hang new and experimental functionality.

The software package, titled PG in the preliminary stages, is intended to provide a GUI application for the management and recording of garden plots and containers. The amount and types of containers will expand as functionality stabilizes, as will the types of data available to record and log. The hope is to provide a robust method for interfacing via USB/WIFI to manage remote monitoring stations and equipment. Use of this type of interface will allow more flexibility and avoid "locking" users into using only one type of microcontroller, sensor equipment, etc.

The hardware configurations are included as a guide for any would-be users to serve as a baseline for a functioning system. It is encouraged that users experiment and expand the possible uses for the software and build upon it. Version notes will be included with each major revision and the plan is to have a baseline working version ready to run as soon as possible.


---------------------------
System Description
---------------------------
The previously mentioned software package, PG, will be able to run on any PC and connect via network (WIRED/WIFI) to remote control stations run by another PC connected to Arduino, ESP8266, and/or eventually Raspberry PI. PG will provide a GUI control center as well as data management functionality. Client systems will run a more compact package that will relay control signals to the controller hardware, which in turn activates and monitors connected equipment. 