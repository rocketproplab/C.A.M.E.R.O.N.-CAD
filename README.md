# C.A.M.E.R.O.N

## The main PCB on Launchy that is responsible for all the Avionics tasks of the rocket

## Maintainer
CAMERON is maintained by George Troulis, with numerous contributions from Seyed Omid Hassanli

## Naming
C.A.M.E.R.O.N. stands for Changes All Mechanical and Electrical Requirements Over Night. It also happens to be the name of our beloved Chief Engineer, who has done a fantastic job at running RPL and assigning tasks and deadlines to everyone.

## Features

CAMERON contains the following features:
* Up to 36V input with 24V, 5V, and 3.3V rails
* Active current-monitoring IC connected to battery input
* BeagleBone Black (Flight Computer)
* Connector for 2 UARTs that connect the FC with XBee Radios
* STM32F4 "RIO" to interface with sensors
* Breakouts for Solenoids, Pressure Transducers, and Thermocouples
* SWD and UART Headers for debugging/programming the STM32F4
* Breakout for separate Recovery PCB that triggers chute at apogee

CAMERON used to contain the following features, but not anymore:
* Up to 48 V input
* Generic SPI/I2C Breakouts
* CAN Connector
* Raven altimeter

