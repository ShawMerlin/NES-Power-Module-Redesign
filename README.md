# NES-Power-Module-Redesign
Completely Redesigning the NES Power Module to Reduce Noise and EMI

I have a limited run available for purchase at https://www.ebay.com/itm/144688732957

The original NES Power Module is very noisy.  The Power Traces cross eachother and the ground home path is messy.
EMI was not a worry in 1985 but noise can impact picture and sound quality

Project is Open Sourced with a MIT License. It can be edited, changed and sold at your own discretion.  
Please link back here if this helps you with your own project.

More Content Like this - www.facebook.com/GeekIslandGaming


[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=97YFBJX4NXA8W)


All Donations are reinvested into ideas and projects. Thank you for the support!!
# Updates
- 9/12/2022 - I found a couple of issues on the Sound and RGB Board which are being fixed.  The Classic and THT Versions are still good.

- 9/10/2022 - Sound Mix board needed a couple of small changes but the RGB, DIY THT, and new HDMI Companion board are working great!!
 I will be updating the folders on this github with those gerber files too.

- 8/24/2022 - Uploaded BOM, Gerber and Kicad Files for the DIY THT Classic RCA Power Module. 
- 8/22/2022 - Starting tests on the Sound Mix and RGB Edition.
  
  I have also added a new version below for the HDMI Hi-Def Mod.
- 7/13/2022 - First Production batch of Classic Power Module arrived.  Kicad files available and uploaded!

  I have also ordered the Soundmix and RGB Boards.
- 7/02/2022 - Prototypes for the Classic Power Module with Composite Video were successful!! 
  
  Gerbers, Bill of Materials and Assemly Position files have been uploaded above.
- 6/19/2022 - Replaced the LDO with a Switching Voltage Regulator for a low heat alternative.  New boards ordered. Expected by 6/27.
- 5/30/2022 - BOM created for Classic RCA Power Board and Uploaded, boards expected by 6/3.
- 5/17/2022 - Both Classic and Classic with Sound AMP PCBs have been ordered for testing.  
- Once verified, the open source files will be released.


# Goals with these new NES Power Modules
- Full Ground Plane that is uninterrupted and is free of traces and components.
- Power Traces that do not cross and have the GND plane below for a good return power signal.
- Have a specific NES Power Module for each use case (not try and pile everything into one board)


# NES Classic with Composite Out and Two Channel Mono Sound.
![image](https://user-images.githubusercontent.com/70423454/186549143-a43c79f4-a960-4ef5-8c92-030850ef5d43.png)


# NES Classic with Sound Mixing of both Audio Channels on the NES + the Expansion Audio from the cartridge.
![image](https://user-images.githubusercontent.com/70423454/179364179-cdf058aa-fb97-4f7a-9313-9bf6ef754939.png)


# NES RGB with Genesis 2 9 Pin Output
![image](https://user-images.githubusercontent.com/70423454/179364346-10a60070-cbb6-477c-8ade-21a8580034ce.png)


# Full uninterrupted ground plane on the back of the board.
![image](https://user-images.githubusercontent.com/70423454/179363800-cb818a45-c4a4-4a72-b937-716b4586f864.png)


# An easy to solder DIY Version of the Classic Composite RCA Edition.
![image](https://user-images.githubusercontent.com/70423454/186550171-d461cc94-1ec4-4059-8845-3939911fba0a.png)


# For the few that own the NES HDMI Board, this module will provide very easy solder points without the need of the LDO.
![image](https://user-images.githubusercontent.com/70423454/185999783-296dcafc-dfe5-4f3a-911b-82fa9e63dd2f.png)



# Below is an example of the Orignal Power Module.  Notice how the power traces keep crossing eachother and other components. Folks really didn't consider EMI a lot back then and opted to just cover the entire board in a metal shoud.

![image](https://user-images.githubusercontent.com/70423454/189474492-a8b75d50-ffc9-4e5b-844f-7f16a31056be.png)



