# VoidLens-DIY-VR-Headset

image

## What is special in this?
 - A highly customizable VR Headset
 - Custom PCB
 - Aesthetic design
 - Low power consumption
 - DP/HDMI Cable directly to the pc or laptop
 - Accurate IMU's and rf modules

## How to make this?
Firstly, the pcb gerber files are in the pcb folder inside the main repo, it must be exactly printed and parts can be choosen according to you by following the BOM(bom.csv).
Next, Each part in the prints folder must be printed and then assembled according to the main .step file(more coming soon)

https://github.com/HadesVR/HadesVR - All the source codes are availble in this repo and many other repos.

The pcb has a 6 pin programmer to flash the code into the atmega32u4. Additionally, a usb c is provided if a bootloader is loaded on the mcu one can directly flash to it.

A Mini DP port coming out of the dual screens display driver(Check BOM) is connected to the host pc)
SteamVR can be installed on the pc and the documentation is availble here - https://github.com/HadesVR/HadesVR

## Credits:
https://github.com/HadesVR/HadesVR - HadesVR Inspired me to make this in the first place
Thanks for the horizons team for organizing horizons europa which gave me the motivation to finish this.
