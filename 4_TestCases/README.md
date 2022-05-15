# INTRODUTION



Recent developments in the automobile industry has paved a way for drastic increase in the use of vehicles for transportation and luxury cars. Many traditional systems use windshield wipers which works intermittently andwith variable speeds during rain. In majority of the vehiclesan adjustable lever near the steering of the driver has to beoperated by the driver to control the windshield wiper(s).This change of lever position will distract the driver’sattention, more so during poor visibility that may lead tountoward incidents.

To overcome the problem here i designed a wipercontrolsystem using the STM32F4xx-discovery board.Most car wipers have a DC motor that controls their action, but the STM32F4xx-discovery does not have any motor, so we are considering LEDs for this application. As the wiper control system. There are four LEDs and a Push Button on the STM32F4xx-discovery board. These LEDs are orange, green, red, and blue in color. With the Discovery board, four user LEDs are connected to the PD12,PD13,PD14 and PD15 pins of PORTD through a current limiting resistor. GPIO pins of STM32F407VG microcontroller will be configured as digital input pins to enable a push button to operate with STM32F4. If you press the user button and hold it for two seconds, the Red LED turns on, indicating the ignition key is positioned at the ACC. In addition, the LEDs are blinking, which indicates the wipers are ON.







# components 
1.STM32F407 Discovery Board





2.Push Button







3.LEDs








4.Power Supply








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



# STM32F407 DELIVERY BOARD





The main purpose of this project is to get an insight into the STM32F407 Discovery Board, which is an ARM Cortex M4 based Microcontroller. As I started working on STM32F07 Discovery Board, initially it was difficult and confusing to understand and program this microcontroller because understanding internal structures and working of the microcontroller using data sheet of STM32F407VGT MCU is difficult especially if one is a beginner.





                                              Figure 1 : STM32F407 Discovery Board

![image](https://user-images.githubusercontent.com/70704291/168470844-07e9b884-b380-41bc-ac42-a3229fada2cf.png)




# BLOCK DIAGRAM STM32F407VGT6 Microcontroller


![image](https://user-images.githubusercontent.com/70704291/168470924-004d6742-66b9-4737-8ed4-31b003738fc8.png)




I-BUS (Instruction Bus)
D-BUS (Data Bus)
S-BUS (System Bus)
I-BUS This bus connects the Instruction bus of the Cortex®-M4 with FPU(Floating point unit) core to the BusMatrix. This bus is used by the core to fetch instructions. The target of this bus is a memory containing code (internal Flash memory/SRAM or external memories through the FSMC/FMC).

D-BUS This bus connects the databus of the Cortex®-M4 with FPU to the 64-Kbyte CCM data RAM to the BusMatrix. This bus is used by the core for literal load and debug access. The target of this bus is a memory containing code or data (internal Flash memory or external memories through the FSMC/FMC).

S-BUS This bus connects the system bus of the Cortex®-M4 with FPU core to a BusMatrix. This bus is used to access data located in a peripheral or in SRAM. Instructions may also be fetched on this bus (less efficient than ICode). The targets of this bus are the internal SRAM1, SRAM2 and SRAM3, the AHB1 peripherals including the APB peripherals, the AHB2 peripherals and the external memories through the FSMC/FMC.


# CLOCK



![image](https://user-images.githubusercontent.com/70704291/168471137-fbf420fe-3816-4e20-96dd-5b09d9247b8f.png)




# FEATURES



STM32F407VG 168MHz (100pin)




1024KB flash ROM, 192KB RAM





3axis accelerometer LIS302DL or LIS3DSH (Depending on which revision Discovery board you have)




mems microphopne MP45DT02, audio amp CS43L22




4 user LEDs




1 user switch




Reset switch




USB OTG
