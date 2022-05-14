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


