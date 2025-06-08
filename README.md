This directory contains schematics and simulationsfor the BMS for autonomous drones 
The .asc or SPICE file simulates all the respective parts of the circuit such as voltage sensing current sensing overcharge and overcurrent protection
Moreover the firmware (multichannel_adc file) is based on STM32F103 which includes multichannel ADC calculation for differnet sensors (3 temperature sensors, 4 current sensors, 1 voltage sensing circuit)
The real-time communication is still in process
This directory does not include the final PCB design
