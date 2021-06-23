# Self-Balancing-Surveilence-Bot

The main purpose of this work is to develop a self-position correcting robot whose main purpose shall be surveillance.

Security is an integral part of our lives and surveillance is an essential part of it. 
The process of surveillance, in general, is not just limited to security purposes but involves continuous systematic supervision of a particular environment and everything else part of it. 

Surveillance job involves risk or irreplaceable damage in case of adverse environments.
A robot is an automated electronic machine that can perform, any number of times, a given set of tasks and can thus replace human work.  
With its added advantage of high accuracy, high speed, and the ease with which they can be maintained, bots become the ideal choice for such jobs.

Also,this bot need not be limited to - surveillance - securing a location or home security. 
- It can be used for real-time monitoring of  hazardous industrial environments or risky working environments, 
where minimizing human intervention will be of great help. 
- Moreover, such bots can also be used to survey construction sites remotely, analsye the structures being built
and rectify errors or keep track of developments at ease. 
- Higher upgrades to such bots imply their usage in monitoring and containing explosions and blasts.
- Also, the most recent use of such bots was in looking after Covid patients as well as avoiding unauthorized entries into the ward. 


Therefore, the, aim of this project is to build a 2 wheeled-bot that can self balance and simulatneously localise itself i.e, self navigation, along with mapping it's
surroundings via a 360- view camera's visual feed and keep track of various parameters through sensors, thus, providing the user with necessary data required to carry out the
work of surveillance remotely with higher performance and reduced cost than the conventional way.


We have two compulsory requirements, implying two main objectives,

1) Self-Balancing
 -> This 2 wheeled bot is expected to maneuver itself to the calibrated stable position upon experiencing any tilt.
The two-wheeled robot’s position will be continuously corrected by a gyroscopic sensor communicating with a Raspberry Pi microprocessor.
The amount of tilt experienced and variation from the stable position can be determined with the help of the MPU6050 accelerometer gyrometer sensor. 
The motors shall be to turned in the opposite direction of the applied tilt force to maneuver the bot back into the stable position.

and

2) Localisation and Mapping
 -> The robot, mounted with wide-angle wireless cameras, shall provide live 360° view video footage.
The visual feed obtained from the cameras is used by the bot's controller to generate a map of its surrounding - based on Simultaneous Localisation And Mapping techniques along with a fusion algorithm, say, Kalman filter, which then can be proccessed further based on IP techniques to monitor the surrounding as needed. 
Thus, the bot can freely move around in its environment guided by SLAM, in addition to user's commands, therby achieving surveillance.

We also can customise the bot by integrating sensors, based on the application area targeted, 
implying a third objective,

3) Bot-Customisation
 -> Embedding various sensors various sensors like DHT 11(Temperature and humidity sensor),MQ2 gas sensor, etc., to record various desired physical parameters in the surrounding
 environment. This data from the subsidiary sensors can be collected and the same can be transmitted to the local host or server.
The user there can utilise this to perform necessary computations or even alter the bot's movement based on such inputs specific to the application intended to achieve the
desired results.


Further enhancement of the project is possible by considering a virtual reality headset 
using which the user could be provided with an immersive rendering of the environment to be monitored, 
along with upgrading the bot’s control to be done by hand gestures, thereby easing machine-human interaction.


Project By:

- [Shashank GS](https://github.com/GS-Shashank)
- [Yashas Vinay](https://github.com/YashasV9) 
- [Shripada Adiga]
- [Sumanth Shanbog H R](https://github.com/cosmos-shanbog)


Linkedin URLs: -
- [Shashank G S](https://www.linkedin.com/in/gs-shashank/)
- [Yashas Vinay](https://www.linkedin.com/in/yashas-vinay-4a0b35165/)
- [Shripada Adiga](https://www.linkedin.com/in/shripada-adiga-0156b6214/)
- [Sumanth Shanbog H R](https://www.linkedin.com/in/cosmos-shanbog/)

