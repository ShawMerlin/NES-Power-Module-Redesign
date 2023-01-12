# NES Revival - Power-Module Redesign
Completely Redesigning the NES Power Module to Reduce Noise and EMI

1/8/2022   
I have added to my designs a USB C Powered Module (This was long overdue).   
This module uses Power Delivery to get up to 3 amps of 5V Power from a USB Power Brick.   
It does not need to covert down to 5V so no buck converters or LDO's needed!!   
Pictures below. Updates to come.


The small batch that I had ordered has sold out.  I should have some more to give out the first part of February. 

I will always have the new USB C Powered ones available at that time pending all the testing goes well.


The original NES Power Module is very noisy.  The Power Traces cross eachother and the ground home path is messy.
EMI was not a worry in 1985 but noise can impact picture and sound quality

Project is Open Sourced with a MIT License. It can be edited, changed and sold at your own discretion.  
Please link back here if this helps you with your own project.

More Content Like this - www.facebook.com/GeekIslandGaming

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=97YFBJX4NXA8W)


All Donations are reinvested into ideas and projects. Thank you for the support!!

**Updates are now in a seperate document**

https://github.com/ShawMerlin/NES-Power-Module-Redesign/blob/main/Updates.md

=-=-=-Special Thanks to Project Guardian-=-=-=

# Goals with these new NES Power Modules
- Full Ground Plane that is uninterrupted and is free of traces and components.
- Power Traces that do not cross and have the GND plane below for a good return power signal.
- Have a specific NES Power Module for each use case (not try and pile everything into one board)

# NES Classic USB C Powered Module
![image](https://user-images.githubusercontent.com/70423454/211245254-8f329055-987e-43e0-9ae4-70d465cca7cb.png)


# NESRGB Companion Power Module with YPbPr "Component" Video
![image](https://user-images.githubusercontent.com/70423454/191241518-073bcafa-6da2-472a-a913-fb6ca4ea4a78.png)


# NES Classic with Composite Out and Two Channel Mono Sound.
![image](https://user-images.githubusercontent.com/70423454/189784508-f7524312-fb60-4ef9-8e2b-0ad28327b1a1.png)


# NES Classic with Sound Mixing of both Audio Channels on the NES + the Expansion Audio from the cartridge.
![image](https://user-images.githubusercontent.com/70423454/179364179-cdf058aa-fb97-4f7a-9313-9bf6ef754939.png)


# NES RGB with Genesis 2 9 Pin Output
![image](https://user-images.githubusercontent.com/70423454/189784110-bcef7914-d50a-42c1-8fcf-64ba0644c83a.png)


# Full uninterrupted ground plane on the back of the board.
![image](https://user-images.githubusercontent.com/70423454/179363800-cb818a45-c4a4-4a72-b937-716b4586f864.png)


# An easy to solder DIY Version of the Classic Composite RCA Edition.
![image](https://user-images.githubusercontent.com/70423454/186550171-d461cc94-1ec4-4059-8845-3939911fba0a.png)


# For the few that own the NES HDMI Board, this module will provide very easy solder points without the need of the LDO.
![image](https://user-images.githubusercontent.com/70423454/185999783-296dcafc-dfe5-4f3a-911b-82fa9e63dd2f.png)



# Below is an example of the Orignal Power Module.  Notice how the power traces keep crossing eachother and other components. Folks really didn't consider EMI a lot back then and opted to just cover the entire board in a metal shoud.

![image](https://user-images.githubusercontent.com/70423454/189474492-a8b75d50-ffc9-4e5b-844f-7f16a31056be.png)



