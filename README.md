# Car Wiper Control System
# Introduction
Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed
and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear window and the other on each headlight. The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots.

Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen. The process of pulling up the wiper is difficult to be handled. Thus, this system is proposed to solve these problems. The objectives of this project are to upgrade the older cars system by providing automatic wiping system, to improve the system by using sensor with actuator and to design a basic program that will fully operate with the system. The concept of this proposed wiper system is similar with other existing conventional wiper. In spite of removing water from windscreen, this system also will be upgraded to an automatic control system by using STM32 Microcontroller,water sensor,LED's ,Switch and timer and . As the conclusion for the project, the results shows all the aim objectives are successfully achieved. The wiper system was well functionally according the water condition from the outside of a car.

# Objective of Project
The Purpose of this project is to build circuit for car wiper control system using STM32F4 microcontroller in accordance with corresponding LEDs,Push buttons or Switch and timer. These all components are in built on STM32 Microcontroller.So, By using STM32cubeMX made the circuitry connection and code will be uploaded on to circuit or hardware board using Emulator or IDE that is QEMU software.The Qemu software is used to develop the set of instructions in response to corresponding hardware circuit.Finally the objective of this project is to detect accidents and made flexibility to drivers by developing Car Wiper Control System.

# An Embedded System
## Definition
An embedded basically a microprocessor or microcontroller-based automation system which is designed and installed to perform a specific task. An embedded system is the combination of input devices, output devices, and memory.

Embedded means something that is attached to another thing. An embedded system can be thought of as a computer hardware system having software embedded in it. An embedded system can be an independent system or it can be a part of a large system. An embedded system is a microcontroller or microprocessor based system which is designed to perform a specific task. For example, a fire alarm is an embedded system; it will sense only smoke.

An embedded system has three components

* It has hardware.
* It has application software.
* It has Real Time Operating system (RTOS) that supervises the application software and provide mechanism to let the processor run a process as per scheduling by following a plan to control the latencies. RTOS defines the way the system works. It sets the rules during the execution of application program. A small scale embedded system may not have RTOS.

The Block diagram of an Embedded System is given by

![](https://microcontrollerslab.com/wp-content/uploads/2017/06/basic-building-blocks-of-embedded-system.jpg)
# Description
All automotive industries seek to provide low cost system for all the applications including automatic wiper system in vehicle. In recent time automotive industries focusing on autonomous vehicle which means self-drive system on different applications. For this scenario, this paper offers low Cost wiper system with simple and effective concept of electro mechanical concept to wipe the windscreen automatically. Automatic wiping has been done during rainfall without human interrupt. Thus an uninterrupted makes to avoid distraction of the drive and secure from accidents. Nowadays vehicles are more automated whereas the cost of the embedded system used for different critical applications are too high. 

Wipers are designed and manufactured to remove water from a windshield. Most automobiles feature two windshield wipers, as well as one on the back window and one on each headlight. The rubber blade, the wiper arm that holds the blade, a spring linkage, and portions of the wiper pivots are all visible from the exterior of the automobile. Under the wiper, there are up to six pieces called pressure points or claws, which are little arms. The claws spread the wiper's pressure along the blade's back. The wiper is the beam, and the claws are the suspension components, therefore this is a balancing beam with a suspension system. The claws keep the blade flexed against the windshield, distributing uniform pressure across the blade to clean the glass evenly. Large or strongly curved windshields benefit from more claws because they effectively disperse pressure.

# Explanation
This Wiper Speed Control System is utilised in all sorts of automobiles, and its primary function is to remove rain air drops from the vehicle's front screen. Because driving a vehicle in the rain is quite difficult, we will use wipers to clear the front screen of the vehicle, which is a mirror, so that we may drive the vehicle even in the rain.

## WORKING PROCESS
* When the button is pressed ONCE, the car will be on ACC mode.

* When the button is pressed TWICE, the car will be on Ignition mode.

* When the button is pressed THREE times, wiper turn on.

* When the button is pressed FOUR times, wiper turn off.

# Define System
The basic wiper control system design is given by,
![](https://user-images.githubusercontent.com/101356849/167870200-7de49c3a-916c-4fe8-ad67-0f499b4d8f5b.png)

![Wipers](https://user-images.githubusercontent.com/101356849/168057918-2ad51073-bbff-45e0-8fb3-c59e880d82ae.jpg)

# Specifications
The following are the major specifications to develop car wiper control system.They are,
* Hardware
     * STM32F4 Microcontroller
     * USB Cable
     * Push Button or Switch
     * Timer
     * power Supply
     * LEDs
* Software
     * QEMU Software
     * STM32cubeMX
* Embedded C Language
# Details of Components
## STM32F4 Microcontroller
The STM32 F4-series is the first group of STM32 microcontrollers based on the ARM Cortex-M4F core. The F4-series is also the first STM32 series to have DSP and floating-point instructions. The F4 is pin-to-pin compatible with the STM32 F2-series and adds higher clock speed, 64 KB CCM static RAM, full-duplex I²S, improved real-time clock, and faster ADCs. 
## USB Cable
The term USB stands for "Universal Serial Bus". USB cable assemblies are some of the most popular cable types available, used mostly to connect computers to peripheral devices such as cameras, camcorders, printers, scanners, and more.

By using USB cable dump the sofware code on to hardware kit.
## Push Button or Switch
A Push Button switch is a type of switch which consists of a simple electric mechanism or air switch mechanism to turn something on or off. Depending on model they could operate with momentary or latching action function. The button itself is usually constructed of a strong durable material such as metal or plastic.
## Timer
A timer is a specialized type of clock which is used to measure time intervals. A timer that counts from zero upwards for measuring time elapsed is often called a stopwatch. It is a device that counts down from a specified time interval and used to generate a time delay, for example, an hourglass is a timer.
## LEDs
A Light Emitting Diode (LED) is a semiconductor device, which can emit light when an electric current passes through it. To do this, holes from p-type semiconductors recombine with electrons from n-type semiconductors to produce light.
## Power Supply
A power supply is an electrical device that supplies electric power to an electrical load. The main purpose of a power supply is to convert electric current from a source to the correct voltage, current, and frequency to power the load. As a result, power supplies are sometimes referred to as electric power converters.
# Folder Structure
|Folder  |Description  |
|--------|-------------|
|0_Abstract|Aim and Goal of the project|
|1_Requirements|Documents Specifying the detailed components to build this project|
|2_Architecture|This Folder having documents and they specify architecure and control flow and design flow|
|3_Implementation|Documentes requires src files and souce code,Doxygen and Makefile|
|4_TestPlan and Output|Douments with test plans and procedures|
|5_Report|Decumentation specifying  report on project|
|6_Images and Videos|The documents require the images and videos|

# SDLC Activity

[![Build](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Build.yml/badge.svg)](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Build.yml)

[![Build Linux](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Build%20Linux.yml/badge.svg)](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Build%20Linux.yml)

[![Build Windows](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Build%20Windows.yml/badge.svg)](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Build%20Windows.yml)

[![CD](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/CD.yml/badge.svg)](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/CD.yml)

[![CI](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Contribution%20Check-Git%20Inspector.yml/badge.svg)](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Contribution%20Check-Git%20Inspector.yml)


[![Code Quality](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Code%20Quality.yml/badge.svg)](https://github.com/JinkalaAnitha/M3_Car-Wiper-Control_Util/actions/workflows/Code%20Quality.yml)


![Code Quality Score](https://api.codiga.io/project/33343/score/svg)

![Code Grade](https://api.codiga.io/project/33343/status/svg)

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/2460daf820a9478999661b36ae37579f)](https://www.codacy.com/gh/JinkalaAnitha/M3_Car-Wiper-Control_Util/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=JinkalaAnitha/M3_Car-Wiper-Control_Util&amp;utm_campaign=Badge_Grade)

![Codiga Badge_page-0001](https://user-images.githubusercontent.com/101356849/168427310-2123cef9-067f-4098-b4d7-be28aeeabec8.jpg)

