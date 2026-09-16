# Cardiovascular Catheter Tracking Device - "Frequency Test File"
- this project uses a MSP / M class microcontroller to generate digital frequencies to create an electromagnetic field.
- all components are Texas Instruments.
- this repository represents the transmitting side of the antenna. The receiving side has a 3 sensor probe that is moved through the generated field in order to determine position and location of a catheter

# System Design / Workflow
- microcontroller -> DAC -> Amplifier -> constant current output -> custom coil board -> electromagnetic field

# Repository files
- main file (transmit team)
- header file
- pin configurations
- microcontroller library files


# Main.c - finalFreq.c
- include header files 
- define variables 
- define DDS ( phase and step size
- define 8 frequencies
- function to create sine table
- function to iterate DDS for 8 channels 
- in main - set status of pins/ registers, call functions 

# Header File - dacINIT
- configure registers of MCU and DAC connections
- 
