# SMART--WASTE--MANAGEMENT
#  INTRODUCTION :

The IOT Garbage Monitoring System is designed by ease the problems people or organisation face while managing their waste. The system allow the user to keep watch on the garbage bins by utilizing LED and IoT service. The system has a LED on it which sets off an alarm on fulfillment of the garbage bin, other than this the user can also watch over the bins from anywhere using IoT service.
The system is constructed using a Model B of Raspberry Pi 3, which works as the brain of the system. It is packed with many features like, a quicker 64-bit 1.4GHz quad core chip, 1GB of RAM, quicker dual-band 802.11 b/g/n/ac wireless LAN, Bluetooth 4.2, and much quicker 300 Mbit/s ethernet. It has Improved thermals on the Pi 3 B+ means that the CPU on the BCM2837 SoC can now run at 1.4GHz. To keep watch on level of garbage in the bins, the system consists of a couple of HC-SR04 Ultrasonic Range Finder Distance Sensor Module. The Ultrasonic sensor works on the principle of SONAR and is designed to measure the distance using ultrasonic wave to determine the distance of an object from the sensor. The sensor helps the system to sense the level of garbage in the bins. 
The Raspberry Pi is equipped with WiFi connectivity, thus making it suitable to watch the system using IoT, from anywhere. As so the system works towards ease the garbage management.

#  Methodology:

we tend to send the data regarding the amount through an IOT framework consisting of all the sensors connected to the raspberry pi, besides communication interfaces like serial port and jumper cables for connecting to different devices. The ultrasonic sensor is employed to notice the peak of the garbage stuffed at completely different intervals of your time in line with the time delay. The LDR detector is employed as a trigger to notice the presence of garbage within the garbage can. 

Internet of Things (IOT) can be defined as a network of ‘Smart’ objects or devices that are able to connect and communicate through the Internet. It is used to connect physical devices that are connected to the Internet. Objects or things have IP addresses and the capability to gather and transmit data over the network without the help of human. The things or objects can sense, communicate and exchange information which renders smart services for users. 

Management of waste has become a considerable issue in industrial, academic and government sectors, which thereby led to major IOT application field. Thus, a smart waste management system is crucial for a clean and healthy city. In the proposed system, the smart garbage bins can connect to the internet in order to acquire the real-time data of the garbage bins. 
Managing the garbage bins involves observing the status of bins and consequently taking necessary actions. However, manually keeping a close watch on the status of the garbage bin is a strenuous task since numerous garbage bins can be positioned at different locations. The garbage bins are equipped with Raspberry Pi Model 3 board with HC-SR04 ultrasonic sensor. The sensor detects the height of waste in the garbage bins and accordingly sends signals to the Raspberry Pi. 

This is often a signiﬁcant step during this project to cut back the energy consumption of the ultrasonic sensor, i.e., the detector solely determines the amount of garbage once the trigger or the LDR detector glows. The raspberry pi board has been employed as microcontroller. Interfacing is ﬁnished among the IOT module and raspberry pi, therefore sending the data to the involved authority if the amount of garbage exceeds 75%.

Another feature introduced inside this project is that it provides the data from nearby garbage bins ,if they are more than 50% filled then they will be picked up ,so to make the whole cycle more efficient. The position of the garbage bins will be done through a GPS module.
 

#  LITERATURE REVIEW :

Seven reports were reviewed in detail for the literature review, with the majority of these providing some evidence to support the theory that the introduction of waste collections is associated with a reduction in waste arisings. The following text should be reviewed with consideration given to the fact that these studies were not specifically designed to assess the impact of waste collections on at source food waste reduction.

Therefore, evidence is taken from these reports to be used in different context from that in which it was collected. For example, a common theme across all of the reports was the fact that where a reduction in food waste arisings had been observed, there was limited data to confirm how much food waste had simultaneously been diverted from the residual waste stream to home composting and how much was a result of at source waste prevention behaviour .

A number of the reports considered the diversion of waste to home composting, as a contributor to waste reduction, as this reduced the food waste arisings collected at the kerb side. 

Overall the reports demonstrate that while there is some evidence to support the theory that implementing a waste collection can lead to an overall reduction in collected waste, there is currently no significant evidence to demonstrate to what extent this is due to prevention at source as opposed to diversion to home composting. A number of the reports support the need for further research in this area. 

The Raspberry Pi is equipped with WiFi connectivity, thus making it suitable to watch the system using IoT, from anywhere. As so the system works towards ease the garbage management.

#  MATERIALS USED :

RASPBERRY PI:
It is a board which is low-cost and just the size of credit card. It is a small computer having capability of any desktop computer and able to work on low 5v power supply. The standard OS in Raspberry Pi is debianbased Raspbian operating system. It also supports most Linux OS such as, Windows 10 IOT Core, Ubuntu MATE, RISC OS, Snappy Ubuntu Core, OSMC, PiNET, LibreElec, Pidora. Raspberry Pi is a system-onchip(SoC) based on Broadcom BCM2837 containing Broadcom Arm processor and a videocore. It is a singleboard computer developed by the Raspberry Pi Foundation, founded in 2009, in the UK with the aim of promoting basic computer education in schools and developing countries.
HCSR04 Sensor :
Ultrasonic sensors are used to measure distances with the help of ultrasonic waves. The reason of being accurate for small distances makes ultrasonic waves a good choice. The other reason being no disturbance to the human ear as ultrasound is more than 20,000 hertz which are not detectable by humans.


#  WORKING PRINCIPLE:

HC SR04 is also known as an ultrasonic transducer that has both transmitter and receiver. It is used mainly to determine the distance of an object. The distance of object from the sensor is determined by the amount of time the transmitter takes to send and receive the reflected waves at the receiver. The sensor works on the principle of "non-contact" technology which employs SONAR (Sound Navigation Ranging) for accurate and precise readings. Sonar is a technique that exploits sound propagation to detect, navigate or communicate with objects under the surface of the water by means of echoes.
The HC-SR04 sensor works with the formula
Distance = Speed*Time
The HC-SRO sensor has 4 pin interface named Ground Echo Trigger and Vee respectively. When the sensor module is connected to 5V power supply, the transmitter starts transmitting the ultrasonic waves which travel through the air until it hit the target object. 
The incident signal gets reflected back from the target object and this is collected by the receiver part of the sensor 
The distance is directly proportional to the time it takes these waves to return at the receiver. If the Trig pin is kept high for a period of 10 s, then the waves will be generating and will get collected by the Echo pin. 
For the period the waves take to travel and come back to the receiver, the echo pin will remain turned on Therefore, formula to calculate the distance of the object is given as
Distance = (Speed*Time)/2
It is required to divide the value by 2 since time taken is the “two and come back from the object. 

BUZZER:

An audio signaling device like a beeper or buzzer may be electromechanical or piezoelectric or mechanical type. The main function of this is to convert the signal from audio to sound. Generally, it is powered through DC voltage and used in timers, alarm devices, printers, alarms, computers, etc. Based on the various designs, it can generate different sounds like alarm, music, bell & siren.
It includes two pins namely positive and negative. The positive terminal of this is represented with the ‘+’ symbol or a longer terminal. This terminal is powered through 6Volts whereas the negative terminal is represented with the ‘-‘symbol or short terminal and it is connected to the GND terminal.
 
LED:

A light-emitting diode (LED) is a semiconductor device that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons. The color of the light (corresponding to the energy of the photons) is determined by the energy required for electrons to cross the band gap of the semiconductor. White light is obtained by using multiple semiconductors or a layer of light-emitting phosphor on the semiconductor device.
Appearing as practical electronic components in 1962, the earliest LEDs emitted low-intensity infrared (IR) light. Infrared LEDs are used in remote-control circuits, such as those used with a wide variety of consumer electronics. The first visible-light LEDs were of low intensity and limited to red. Early LEDs were often used as indicator lamps, replacing small incandescent bulbs, and in seven-segment displays. Later developments produced LEDs available in visible, ultraviolet (UV), and infrared wavelengths, with high, low, or intermediate light output, for instance white LEDs suitable for room and outdoor area lighting. LEDs have also given rise to new types of displays and sensors, while their high switching rates are useful in advanced communications technology with applications as diverse as aviation lighting, fairy lights, automotive headlamps, advertising, general lighting, traffic signals, camera flashes, lighted wallpaper, horticultural grow lights, and medical devices.

JUMPER WIRES:

A jump wire (also known as jumper, jumper wire, DuPont wire) is an electrical wire, or group of them in a cable, with a connector or pin at each end (or sometimes without them – simply "tinned"), which is normally used to interconnect the components of a breadboard or other prototype or test circuit, internally or with other equipment or components, without soldering.
Individual jump wires are fitted by inserting their "end connectors" into the slots provided in a breadboard, the header connector of a circuit board, or a piece of test equipment.

 


 


#  METHODOLOGY:

The IOT garbage monitoring using Raspberry Pi project uses two ultrasonic sensors to monitor the garbage level of two bins. The ultrasonic sensors consist of a transmitter and a receiver. They work on the principle of Doppler’s effect. The sensor generates an ultrasonic wave that reflects back after colliding with an obstacle or an object. The time-lapse between the transmission and reception of the ultrasonic wave is measured by the ultrasonic sensor and the distance calculation is made based on this time-lapse value. The distance measured by the sensor in our case is the distance between the sensor and the surface level of the garbage.
The garbage fill level of the bins as measured by the ultrasonic sensors is continuously fed to the Raspberry Pi single-board computer. The Raspberry Pi controller processes this data and transmits it to the output devices as well as the remote servers.
Data sent over the cloud using IOT:
The real-time garbage fill level of each bin is displayed on an LCD display. In addition to that, the data is also transmitted to a remote server by means of IOT protocols. An IOT platform like Thing Speak is used to receive, store, and visualize this data. A graphical user interface is built using the Thing Speak IOT platform, which visualizes the sensor data with respect to time, in the form of a graph.
Block diagram description of the IOT Garbage Monitoring Using Raspberry Pi Project :
The project block diagram of the IOT garbage monitoring using Raspberry Pi project consists of 7 elements or subsystems.
•	The first subsystem is the power supply unit which is responsible for converting the AC voltage to low-level DC voltage and providing a stable DC-level voltage to all the DC-powered devices in the electronic system. The power supply circuit consists of a bridge rectifier, voltage regulator, and passive components.
Input blocks:
•	The next block is the ultrasonic sensors. These sensors employ the Doppler effect principle for the measurement of garbage levels in the bins. These sensors continuously monitor the garbage level in the bins and transmit the data to the Raspberry Pi controller.
Raspberry Pi / The main processing unit of the project:
•	The block in our project is the Raspberry Pi controller. This is a single-board computer based on a microprocessor, which can be interfaced with input, output, and slave devices. The Raspberry Pi board has built-in WiFi, USB ports, Bluetooth, HDMI interface, and GPIOs. The most popular language for programming the Raspberry Pi is Python which is a high-level general-purpose programming language. Like all other computers, Raspberry Pi also requires an operating system for system-level operations. The officially supported operating system for the Raspberry Pi is called Raspbian, which is a variant of Linux OS. Linux OS is the most popular and widely used open-source operating system in the world. Raspberry Pi is the main controller in our project which gathers data from the input devices and transmits it to the output devices.
Output blocks:
•	The blocks in our project block diagram are the LCD screen and the LED. When the garbage level reaches a specified level, the LED is turned on so that the concerned person can be notified. The real-time values of the garbage sensors are displayed on the LCD screen so that the concerned person can monitor the fill level of the bins at any given time.
•	The Raspberry Pi controller sends off the sensor data to a remote server by means of IOT protocols. The Thing Speak IOT platform gathers this data and stores it. This data is then visualized by means of a GUI built in the Thing Speak IOT platform. The sensor values are plotted as graphs so that the bin levels can be monitored from a remote central control room.


#  ADVANTAGES :

1.	Reduction in the collection and unnecessary fuel consumption cost:
Due to using smart dumpsters, there will be no need for a physical check for every container. This smart waste management solution reduces fuel consumption and cost. Therefore, this reduction allows waste collection companies or municipalities to allocate their resources efficiently.
2.	Elimination of missed pickups:
As route optimization has become a must for smart waste management, there will be no more overflowed trash bins while almost full ones will be taken into account when they are are completely full.
3.	Waste generation geo-specific data analysis:
Data constitutes the basis of the smart waste management system, and it is also used to follow the patterns that occur according to the regions. Data analysis produced by IoT gives customers demographic analysis and creates a chance to take action according to the filling patterns of that district.
4.	Reduction of CO2 emissions:
Due to the more strategic scheduling of garbage collection trucks with real-time data, the carbon footprint is reduced. Thus, smart waste management solutions make the traditional waste collection system more environmentally friendly in each step.

#  APPLICATIONS:

1.	This can be best used by municipal corporation for their betterment of management regarding collection of wastes.
2.	With the help of proper technology (GPS & SOFTWARE APPLICATIONS) we can guide the trucks to choose the shortest path.
3.	It also favours the “SMART CITY” project and “DIGITAL INDIA”.
