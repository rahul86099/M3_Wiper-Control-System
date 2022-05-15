# DESCRIPTION
* A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. The prior system required manual wiper activation, and the operation of bringing up the wiper was difficult to manage.

* The rubber blade, the wiper arm that holds the blade, a spring linkage, and portions of the wiper pivots are all visible from the outside of the car. The wiper contains six elements termed pressure points or claws, which are little arms underneath the wiper.

* The driver must turn on and off the control stalk, which will cause the driver to lose concentration while driving. As a result, this method is designed to address all of these issues.

* Bad weather, risky driving conditions, and exhaustion can all cause a motorist to become distracted.

# RESEARCH
This application was developed utilising information obtained from a variety of sources (including YouTube, Google, and research publications), and then adapted into a successful working model application of wiper control using arm-based microcontrollers.

# OBJECTIVE
* Crystal vision in adverse weather conditions.
* With latest mechanism it can ensure the safety and lower down the accidents.
* Motor vehicle wiper control system.
* Interested in learning more about carriers in embedded systems.
* When you realise the necessity of safety management and begin to take responsibility for your own health while driving in inclement weather.
* This can be utilised in daily life by the user to track their safety and produce better results in life while travelling by motor vehicle.

# Application
* It's found in four-wheelers.
* It's utilised in planes.
* It's found in six-wheelers.
* It is used in trains.
 
# Advantage
* Power usage is reduced.
* The operating premise is simple. The setup is straightforward.
* By offering an On/Off switch, it is possible to run manually or automatically.
* Because conductive sensors are used, sensor costs are very inexpensive.
* Free from wear adjustment.

# How we can do?
The location of the wiper is shown by an LED, which returns to its original position after cleaning the windsheet of a car.

# SWOT ANALYSIS
![SWOT-ANALYSIS-OF-THE-AUTOMOTIVE-INDUSTRY-1024x576](https://user-images.githubusercontent.com/102659131/168467602-4f52eacc-adb5-4701-b0e3-82b271baec62.png)


# TABLE FOR REQUIREMENTS
## HIGH LEVEL REQUIREMENTS
| ID | DESCRIPTION |	REQUIREMENTS |	STATUS |
| ---| :-----------| :-------------| :-------|
| HR001 |	SSD or HARD DRIVE |	1GB TO 20 GB |	IMPLEMENTED |
| HR002 |	OPERATING SYSTEM |	WINDOWS |	IMPLEMENTED |
| HR004 |	PROGRAMMING LANGUAGE |	EMBEDDED C |	IMPLEMENTED |
| HR003 |	ARM BASED MICROCONTROLLER	| STM32F407VGT6 BOARD |	IMPLEMENTED |

##LOW LEVEL REQUIREMENTS
| ID	| DESCRIPTION	| REQUIREMENTS |	STATUS |
| ----| :------------| :-------------| :-------|
| LR001	| WIPER COMES TO INITIAL POSITION AFTER HIS WORK |	LED USED FOR THIS |	IMPLEMENTED |
| LR002 |	PROPER SUPPLY TO PINS AND BOARD |	DONE |	IMPLEMENTED|
| LR003	| ON AND OFF SWITCH MECHANISM FOR ACTIVATION AND DEACTIVATION OF WIPER BLADES |	DONE	| IMPLEMENTED |


# BLOCK DIAGRAM
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/102659131/168467829-925e0b0f-de24-4425-a5ff-898735304359.png)


SIMULATION DIAGRAM
![WhatsApp Image 2022-05-15 at 12 21 17 PM (1)](https://user-images.githubusercontent.com/102659131/168467912-8a0d959d-adce-482f-8600-7feceecbf4be.jpeg)


CAR WIPER CONTROL SYSTEM
![WhatsApp Image 2022-05-15 at 12 18 56 PM](https://user-images.githubusercontent.com/102659131/168467925-f732c3ac-ae9f-4de1-8a9c-fe9588d075f2.jpeg)



# Test Plan
## High Level Test Plan

| Test ID |	Description |	Exp I/P |	Exp O/P |	Status |
| ----| :------------| :-------------| :-------|
| H_01 |	DEVELOPMENT OF .elf file |	.C file |	.elf	| Implemented |
| H_02 | Cross Compilation of Files	Converting .c file into target output |	.elf or .hex |	Implemented |
| H_03	| Search components in STM32 CUBE IDE |	Components	Assembling |	Implemeted |

# Low Level Test Plan

| Test ID |	Description	| Exp I/P |	Exp O/P |	Status |
| ----| :------------| :-------------| :-------|
| L_01 |	DONT STOP WIPER AT MIDDLE OF WINDSHEILD	RAIN CONDITION |	ADVERSE WEATHER |	Implemented |
| L_02 |	SERIAL WISE LED GLOW REGULATION	DONE	Whenever required	| Implemented |
