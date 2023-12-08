# MRE320_MarsRover
Designing a Mars Rover with an additional sensor( DHT-11, temperature and humidity sensor) using Raspberry PI

 This project is the second and final part of the sensors and actuators group project.The first part can be found here -> https://github.com/Tomiwa2/MRE320_SensorPerformanceMeasurements/tree/main. This project was all about designing a mars rover.  A Mars rover is basically a remote-controlled motor (vehicle) with functionalities (additional sensors)  designed to travel on the surface of Mars but in our case….. Earth
   
The design of a mars rover enabled us expand our sensing knowlege and capabilities which is the end goal of this project. In the first part of the project(link above), we had been tasked with testing and analyzing different sensors. In this second part we incorporated the skill we had gotten from the first part into bufferin/making for the sensing capabilities the rover might lack

   This a a very educative project with aid from @Brandonh291 and all steps needed for configuration can be found in his repo > https://github.com/Brandonh291/Masters-Project-for-Raspberry-Pi-Based-Companion-Computer 

      The project consisted of the mars rover assembly and two major tasks that covered the funtionalities of the rover.
      
The  Mars Rover assembly was divided into three parts,

    1. Hardware design including electrical setup -> This included buidling the body of the rover from ground up and setting up telemetry devices ie radios, antenna
    
    2. Software (Avionics) -> The is basically the Raspberry Pi and Navio2 Configuration which are the heart and brain of the system. The software section consisted of downloading the software needed to communicate with the hardware.
    
    3. External Sensor -> This included mounting additional sensors to gauge/buffer the precison/accuracy of sensors onborad the rover. We attached two sensors namely
     i) DHT 11 (Temperature and Humidity Sensor)
     ii) DS 1307 Module(Real time clock(RTC))

     The two major tasks consisted of
     a) Weather data measurement -> We had to collect data from both the rover and sensor all the while autonomously navigating the rover and then assesing their performance from data extracted.
     b) Autonomous navigation through waypoint and PID tuning > In order to collect data, we had to tune the rover to conduct autonomous  missions to designated GPS waypoints.

At the end of this two tasks, we were able to use the data we had extracted to optimize both the sensor and the rover!

**Included in this Repository are**

-  Brief Description of the Rover and Sensor
-  Final build of the Rover
-  Code used to run the sensor
-  Picture of the Sensor mounted to the rover
-  The Rover Testing Setups for both tasks
-  Measured Data and Analysis
-  Results (including summary, conclusion and improvements)


