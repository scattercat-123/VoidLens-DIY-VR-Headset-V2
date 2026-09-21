# VoidLens DIY VR Headset

## Project Overview
<p float="left">
  <img width="400" alt="VoidLens Headset Angle 1" src="https://github.com/user-attachments/assets/85cd04bd-b409-480d-83cd-2ccd00e51d5e" />
  <img width="400" alt="VoidLens Headset Angle 2" src="https://github.com/user-attachments/assets/9b3f8b5c-9b3b-42b7-abca-60665df0586e" />
</p>

## PCB Schematic
<img width="800" alt="PCB Schematic PDF-1" src="https://github.com/user-attachments/assets/3ae9fe96-4f1f-4061-b94b-828df1d9ea9a" />

## Hardware Details & Assembly
<p float="left">
  <img width="250" alt="Hardware Detail 1" src="https://github.com/user-attachments/assets/0c0dc51c-0fa1-480b-8351-f6d9dfa3d990" />
  <img width="250" alt="Hardware Detail 2" src="https://github.com/user-attachments/assets/01d71f14-b8d2-40be-8afc-e78fa32cfb31" />
  <img width="250" alt="Hardware Detail 3" src="https://github.com/user-attachments/assets/2d4a695e-8e3b-4e1f-b711-c79df9de9756" />
</p>
<p float="left">
  <img width="250" alt="Hardware Detail 4" src="https://github.com/user-attachments/assets/b9fc84cc-02aa-4d35-9355-dd428198e41d" />
  <img width="250" alt="Hardware Detail 5" src="https://github.com/user-attachments/assets/bb69d841-c5d0-496a-8cee-49700431ae7a" />
</p>

## What makes this special?
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

I have also used a bit of ai(google's search engine) and some claude to help me finish the BOM file faster instead of doing manually and help me understand some pcb design concepts.


*sorry this readme isnt properly maintained, will update soon*
