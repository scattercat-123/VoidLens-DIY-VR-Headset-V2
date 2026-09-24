---
title: "VoidLens DIY VR Headset Revision"
author: "Atharv Sharma(scattercat_123)"
description: "A DIY VR Headset which works with SteamVR and is pretty high quality!"
created_at: "2026-05-25"
recorded on: "lapse"
---

# Lapse links:
1. [timelapse 1](https://lapse.hackclub.com/timelapse/f4nqXqI7hFgT)
2. [timelapse 2](https://lapse.hackclub.com/timelapse/ZiTtRccZcF3N)
3. [timelapse 3](https://lapse.hackclub.com/timelapse/tBd1NlGmCGK5)
4. [timelapse 4](https://lapse.hackclub.com/timelapse/1Spe0OPi6Aew)
5. [timelapse 5](https://lapse.hackclub.com/timelapse/MBk84wRAZb63)
6. [timelapse 6](https://lapse.hackclub.com/timelapse/x-GUhaDKMTN-)
7. [timelapse 7](https://lapse.hackclub.com/timelapse/P3niAuyYuauM)
8. [timelapse 8](https://lapse.hackclub.com/timelapse/Y5vxKxwnHvCM)
9. [timelapse 9](https://lapse.hackclub.com/timelapse/PgElYlRu9ECy)
10. [timelapse 10](https://lapse.hackclub.com/timelapse/5MBsstZw7_6_)
11. [timelapse 11](https://lapse.hackclub.com/timelapse/7lh1uHg9Sn2O)
12. [timelapse 12](https://lapse.hackclub.com/timelapse/GImigAxer_jY)
13. [timelapse 13](https://lapse.hackclub.com/timelapse/eR_sAssruXn-)
14. [timelapse 14](https://lapse.hackclub.com/timelapse/l-ILf5elXghu)
15. [timelapse 15](https://lapse.hackclub.com/timelapse/xTZYCBQRbf5B)
16. [timelapse 16](https://lapse.hackclub.com/timelapse/hWzH2CNydRFh)
17. [timelapse 17](https://lapse.hackclub.com/timelapse/I-p3ttDsCrN4)
18. [timelapse 18](https://lapse.hackclub.com/timelapse/k1ZjyCjhI7kP)
19. [timelapse 19](https://lapse.hackclub.com/timelapse/nC5iGTKZUOrD)
20. [timelapse 20](https://lapse.hackclub.com/timelapse/kcC0Xk2jgp6y)
21. [timelapse 21](https://lapse.hackclub.com/timelapse/BEIWS6d7PA8m)
22. [timelapse 22](https://lapse.hackclub.com/timelapse/wSm2DOGiso9h)
23. [timelapse 23](https://lapse.hackclub.com/timelapse/V_IC8thnmYoU)
24. [timelapse 24](https://lapse.hackclub.com/timelapse/4xQbPmBbQ0yg)
25. [timelapse 25](https://lapse.hackclub.com/timelapse/tivtx0-DEwzT)
26. [timelapse 26](https://lapse.hackclub.com/timelapse/FEBmBDJxXnag)
27. [timelapse 27](https://lapse.hackclub.com/timelapse/XHdpOhmHMYGX)
28. [timelapse 28](https://lapse.hackclub.com/timelapse/qVaKonp_3JMT)

# May 25th: Made Basic CAD and researched about design!

So Basically my older Voidlens VR Headset I made for Highway was pretty good but the design wasnt bad or modular, it could only fit my shape and pcb had many errors i dint consider, now that i have all the parts im doing a redesign and make it look cool so that anyon in the world can mak their own vr headset for free and DIY. Today, I made the lens holders proper because my last design had many defect such as the lens was protuded out a bit which is bad and there were clips holding in plae instead of a press fit whcih now makes it repairable instead of like a permanent thing. I also added Adjustable like focal length thingy so that i can adjust it to my comfort instead of doing trial and error until it fits, it also anbles other people to lik etry other diameter/focal lenses. Secondly i made it look less boxier and ugly like the old one add added like hidden screw stuff im still working on it though. You can check it out below!

<img width="870" height="641" alt="image" src="https://github.com/user-attachments/assets/7fef1798-333c-47dd-9e48-e0d9904a32e9" />

<b>Layers of the headset</b>

<img width="903" height="632" alt="image" src="https://github.com/user-attachments/assets/6c7b2226-5bd5-4f78-b48a-8e84a6ee3572" />

<b>Final Headset</b>

<img width="996" height="647" alt="image" src="https://github.com/user-attachments/assets/48324247-133a-4c92-9b93-378ce01e27a5" />

<b>A Peak on how the adjustable thingy works</b>

**Total time spent: 2h 9m**

# May 28th: More CAD!

Today I did more of the CAD not a lot and i logged my gtihub jounral and also like measured my battery

# May 29th: Started PCB and added magnet fittings to the cad

Basically i added magnetic fittings:
<img width="313" height="407" alt="image" src="https://github.com/user-attachments/assets/672d1079-e6a1-43cc-ac92-0d22eb341a0b" />

I will be like pausing the print putting the magnets and resuimng again o that magnets tay in place thsi doesnt leve any screw holes and  doesnt make it ugly like the  last design. intead its more satisfying.

After i started the pcb dsign, My oroginal plan was to use the 3S Lipo battery but Lion's would be more effiecient and safe, firstly i did probably like a 30-45 min research on how do i design my own LDO but at the end i figured out it wouldnt work since the max voltage of 2S Lion is like 8.4 and if the ldo has to do a 3.4v dropput its very enefficient and makes the cicuit more hot. BTW i found this mh118650 lg batteries from and old power bank which doesnt work anymore but the batteries are pretty healthy!

Then i had to make a bck converter circuit which was pretty easy and then i also did most of the pcb:
<img width="871" height="652" alt="image" src="https://github.com/user-attachments/assets/bff7c310-b69d-4289-8731-3b43df893dfc" />

# May 30th: Made arduino pro micro symbol

# July 15th: Make custom pcb instead of originally planned pro micro:

I havent touched this since a while since i was busy with y other projects, I decided to make my own Pcb my following the schematic of the pro micro since it would be better.

<img width="1082" height="532" alt="image" src="https://github.com/user-attachments/assets/bd772c84-0843-4d83-b8a0-d80be79c5c7a" />

I just put usb c and few other components along with the atmega32u4 (used in the pro micro).

# July 16th: Do more basic stuff in the schematic:

Today, I went on lcsc and researched datasheets for the atmega32u4. I wired the basic components which was needed in order for the mcu to work like a crysta, vcc pads etc. I also started working on he 3.3v regulator which is needed for the nrf24l01 and other components.

<img width="920" height="494" alt="image" src="https://github.com/user-attachments/assets/92947800-9aaa-4ab8-b189-de9982c25071" />

The picture is the schematic i used to wire the connections of the nrf24l01.

# July 18th: Resarched about path antenna and more:

Today I fiinshed routing all the basic components in my schematic, then i went to fusion to add a small tranlucent strip between the black plates so that i can add led lighting which will be used to make it appealing and also for position tracking(ping pong ball).

<img width="851" height="438" alt="image" src="https://github.com/user-attachments/assets/911e3551-1fb6-439b-bf4e-dd8c666703a4" />

I also thought of making another fpc pcb specifically for the led lighting but i ditched it since you can find premade strips online.

# July 24th: Ran ERC:
I ran the ERC to check for any errors in the schematic and just worked for 15 mins and added x's wherever the pins were floating.(this is needed to tell the main pcb editing that nothingshould be routed over here and assigns no nets).

<img width="840" height="471" alt="image" src="https://github.com/user-attachments/assets/32589ff6-eb4f-4737-9ca2-3f59abd4218f" />

# July 28th: Double check schematic and more:
I double checked my schematic specially the nrf23l01 since i wasnt sure about the spi wiring to the atmega. I also researched about the 5v boost converter i am using (tps61022) since it has lots of pwm mode and setting requirements.

Additionally i checked for feasibility if the bmi270 imu im using would work with the atmega32u4. I also found the arduino library i would be using for the imu (https://docs.arduino.cc/libraries/sparkfun-bmi270-arduino-library/#Releases). 

<img width="870" height="478" alt="image" src="https://github.com/user-attachments/assets/4afae94a-4106-43d4-a95e-daed66e68356" />

# August 3rd: 1S - Li-On charging feature

I dont know why i did not think of this before, today i added the most important thing the integrated charging fast charging and high current output circuit with proper protection unlike those cheap tp4056 circuits. I am using a bq24074 which has an NTC, current limitting auto shutdown(incase of short) etc. 

<img width="1029" height="443" alt="image" src="https://github.com/user-attachments/assets/cf88a086-4eba-4371-b2e6-d07f26ac657c" />

First, i read the datasheet and confirmed what should be connected to the pins. and finally this is the circuit i ended up with for the bq24074. The usb c charges it and also is used for programming the atmega32u4.

<img width="689" height="490" alt="image" src="https://github.com/user-attachments/assets/feea0c7b-e3d1-4d2b-bb4d-b008d5891fff" />
Its not complete but contains all the basic wiring complete.

# August 5th: finish lion charging circuit and add led indicators:

<img width="826" height="490" alt="image" src="https://github.com/user-attachments/assets/9e8e7c1d-9491-410f-951f-f40d69595eec" />

I added basic indicators in the lion charging circuit and also fixed any poer issues, also setting a usb higher current charge.

For some reason i again started rethinking the imu proble trying to find out if it will actually work since my imu is using too much ram out of the 32kb ram available which may cause problems while running.

# August 6th: Imu research and more pcb design:

I researched a lot on the IMU i considered lot of lsm series imu's which are normally used in wearables, either i couldnt find the one i wanted in stock or there wasnt any library available to read its data. After all this i just settled with the imu im using right now and i will check later if there are any issues with it.

There was this one reddit post and vr headset diy guide which mentioned what imu's you should use. they were using bmi270's on the hand controllers so i figured i will be using that itself for the headset.

<img width="931" height="387" alt="image" src="https://github.com/user-attachments/assets/052eacd8-496e-4751-a52e-663c5d08ae7a" />

This was the most suitable one but had some library issues.

# August 10th: Verify schematic:

everytime i tell myself that im almost done but one feature or the other i just add. i was trying to verify my schematic using this tool  called traceformer which did nto work. anyways, i just rechecked it based on the datasheets.

# August 13th: Assign footprints and add to lcsc cart:

I mostly used 0603 footprints since those are easier for handsoldering(ik i will regret this during pcb design). this was actually kinda boring but i did it anyways. I verified the packages and components im using on forums so i can make sure that their datasheets are accurate.

<img width="1576" height="917" alt="image" src="https://github.com/user-attachments/assets/e12beda6-1870-47c8-96a9-16025523ada4" />

# August 17th + 20th + 24th: Important thing just came in mind:

I did not have over discharge protection. so basically what i did is i wired the main battery voltage to the atemga's analog pins which would read the voltage and decide whether to turn on or off the load switch driving all the components.

<img width="649" height="420" alt="image" src="https://github.com/user-attachments/assets/bb9880da-e9a4-4d02-ba30-974073a3117e" />

This is what i have done till now.

I realized a nothe rproblem that if the arduino shutsdown it self how will it power back on? also how will it power on in the first place if load switch is already off. For this, I added a momentary non latching pushbutton which when hold gives temporary power to the mcu then checks if the voltages and components are wired properly and then turns on the load switch so that you dont need to hold the button anymore. if the voltage falls too low, it will turn off and i would have to charge it and turn on after its full.

The load switch i have used is the tps27081 which has high enough current rating for this application.
Here is the wiring diagram:

<img width="1045" height="272" alt="image" src="https://github.com/user-attachments/assets/82ae421f-1179-4072-afad-9533c5b78ae7" />

This took me a long time since i have not used load switches b4.

Before actually adding the temoprary pushbutton thing i thought a normal mosfet would let me control tthe on or off untill i realized that its like a self suicide once it turns of it cannot turn back on.

I also re arranged the layout of the schematic so it is more legible to read.

# August 25th: Research if audio can come from bluetooth and assign more footprints:

I though instead of using speakers or airpods for the audio i can send the audio directly to the nrf24l01 and then i ditched the idea. I just assigned more footprints after that.

# August 27th and 8th September:

I did not touch this for a week since i was setting up linux on my computer and i regret it so bad. I am having issues in emulating fusion lol

Okay back to what i did, I finished assigning all the footprints and imported them to the pcb editor.

<img width="948" height="913" alt="image" src="https://github.com/user-attachments/assets/b77f1a74-bba8-4523-b474-7cc9f3b18ec5" />

# 13th September:

I arranged all the footprints of the components so that i can start wiring. first i exported the dxf of the front view of thr vr headset so i can make the shape and size according to that. than i imported it back to kicad and place components inside it. at the end it looked like this:

<img width="1067" height="511" alt="image" src="https://github.com/user-attachments/assets/f73fed4c-07e3-43bf-89bc-ce26c48a1896" />

# September 13th to 17th:

Route the pcb(2 layer) and then apply a ground fill and both layers.

Then I ran DRC fixed almost 200 errors and then made the edge cuts.

It looks like this now:

<img width="571" height="670" alt="image" src="https://github.com/user-attachments/assets/82467841-725d-4d64-bab5-7dbf1abe5ccd" />

I had to redo many thing if the routing didnt wokred i also repositioned the pcb antenna.

<img width="505" height="644" alt="image" src="https://github.com/user-attachments/assets/621e98af-f67b-4282-886a-7f7664f2a93a" />

# September 17th: Completing submission requirements

I finally finsished designing, is 2 AM and i hope its approved, 40+ long hours of work finally paid off.
Also journaled all the log entries and also added the bom. cad, gerber etc to the repo.

# September 24th: Added connection diagram to repo
