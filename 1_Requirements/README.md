# Wiper Control System



Recent developments in the automobile industry has paved a way for drastic increase in the use of vehicles for transportation and luxury cars. Many traditional systems use windshield wipers which works intermittently andwith variable speeds during rain. In majority of the vehiclesan adjustable lever near the steering of the driver has to beoperated by the driver to control the windshield wiper(s).This change of lever position will distract the driver’sattention, more so during poor visibility that may lead tountoward incidents.To overcome the problem here i designed a wipercontrolsystem using the STM32F4xx-discovery board.Most car wipers have a DC motor that controls their action, but the STM32F4xx-discovery does not have any motor, so we are considering LEDs for this application. As the wiper control system. There are four LEDs and a Push Button on the STM32F4xx-discovery board. These LEDs are orange, green, red, and blue in color. With the Discovery board, four user LEDs are connected to the PD12,PD13,PD14 and PD15 pins of PORTD through a current limiting resistor. GPIO pins of STM32F407VG microcontroller will be configured as digital input pins to enable a push button to operate with STM32F4. If you press the user button and hold it for two seconds, the Red LED turns on, indicating the ignition key is positioned at the ACC. In addition, the LEDs are blinking, which indicates the wipers are ON.





# 3.4W & H (WHO,WHAT,WHEN,WHERE,HOW)

# WHO

 wiper control system will give safe and clear visibility to every one who uses car and automotive wiper controls the operational speed of a wiper in accordance with rain conditions


# WHAT


It is high reliablity. 
It is a Wiper Speed Control System programme for all automobiles.


# WHEN
when it rains  Wiper control system can be used

# WHERE

car wipers are controlled by the stalk on the right side of the steering wheel

# HOW

Windshield wipers are a small part of your car, but they have a big impact on your driving and overall safety. They remove rain, snow, dirt, pollen, frost and other debris quickly and smoothly at the push of a button! The windshield wiper motor moves the windshield.


# SWOT(STRENGTH,WEAKNESS,OPPORTUNITY,THREATS)


# STRENGTH

Car wipers, an important safety component

Windshield wipers play a crucial role in the safety of the driver and the passengers, therefore, it must be given as much importance as to any other part of the car. It cleans the windshield and helps to see clearly during dust storms and heavy rainfall.

By providing ON/OFF push buttons, it can be operated manually or automatically.


# WEAKNESS

This system applied in the case of water falling on the glass only.
The cost of overall system increases as additional components are needed along with rain sensor.
In order to avoid false detection of rain, it requires rain sensors to take decision after few minutes.


# OPPORTUNITY

Essentially, the wiper system is designed to clean the windscreen sufficiently to provide adequate visibility at all times.

# THREATS

Advance Technology has taken its place. In the rain, wiper blend could be a problem.






# HIGH LEVEL REQUIREMENTS


| ID | Description | Category |
| --- | --- | --- | 
| HLR01 | Lock and Unlock of car | Technical |
| HLR02 | be able to ON the wipers and control their speed| Technical |
| HLR03 | the blinking of leds should controlled by user | Technical|
| HLR04 | the system should able to perform the given operations| Technical|
| HLR05 | Activating the Wiper System | Technical |


# LOW LEVEL REQUIREMENTS


| ID | Description | Category |
| --- | --- | --- | 
| LLR01 |  | Hardware |
| LLR02 |  | Hardware |
| LLR03 |  | Hardware |
| LLR04 |  | Hardware |


