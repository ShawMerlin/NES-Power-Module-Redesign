# NES Revival RGBNES "Companion" Power Module.   <br>

1/15/2024 <br>
- over 100 of these 3.1c boards have been sent out on my eBay store.
- A few installation errors but we have not seen any buck converters giving up the smoke!
- Corrected a mistake in the Digikey part number of the Q1 Transistor, the JLCPCB number was correct.
- We are recommending a 560pF instead of the 1nF capacitor on C12, this provides a slightly crisper image.
- Added the H variant of the switching regulator to the Digikey BOM.

6/4/2024 <br>
- Production files have been released for version 3.1c <br> <br>

5/8/2024 - Version 3.1c is production ready, Gerbers will be released this week. <br>
I have a full analsyis with aid from Zaxour to show peformance levels for these boards. <br> <br>
<img width="369" alt="image" src="https://github.com/ShawMerlin/NES-Power-Module-Redesign/assets/70423454/47ca7ab6-46ba-4358-a3f6-db5eddd7737f">
<br> <br>
3/1/2024 - Testing of the new Design 3.0b is going well.  <br>
- We have moved to a 4 layer board to increase the coupling of the switching components to the inner GND layers. <br>
- The Switch input is only used now to power the enable pin on the Buck Converter.  The Input power comes directly from the board itself. <br>
- GND to NES Connector has been moved closer to the Voltage Regulator to reduce the GND Loop area. <br>
- Inductor has been moved further away from the interconnect pins and more bypass capacitors have been added to help reduce noise. <br>
- I plan on doing a more indepth analsys of this design vs the older design and releasing the results. <br>
- All Kicad files and Gerber files will be released once testing is completed. <br>

<img width="344" alt="image" src="https://github.com/ShawMerlin/NES-Power-Module-Redesign/assets/70423454/c21c04b3-b89d-4ebf-80a3-42db8bc4180e">

 <br>  <br>
2/13/2024 - Production Boards have been ordered. <br>
- Testing has been going great!!  I have now ordered my first production run. <br>
- With some help from this great community, I have made improvments to the design. <br>
- I plan on releasing a full breakdown of these new boards and some words on older designs. <br>
- Open Source Files will be released once the Production Boards are verified <br> <br>

1/16/2024 - Features of the 3.0 Boards  <br>
- Stable and clean 5.06 volts at a 1.5A load.  (7.5 watts) <br>
- Tested for 48 hours at a 1.8A load (9 watts) <br>
- Peaks of 2A are fine, but it's pushing the components pretty hard. <br>
- 1.5A Resettable Fuse on 9V input for board protection. (13.5 watts) <br>
- The LCSC Chinese Voltage Regulator has been replaced with a TE Connectivity IC. (TPS54202) <br>
- The Full Bridge Rectifier is a Diode Incorporate part. (MSB30M) <br>
- All Parts can be obtained from Digi-Key/Mouser. <br>
- Gerbers and Kicad files will be released once testing burn-in is complete. <br>
- I also plan on offering these again on my eBay account once i'm done with testing. <br>

<img width="624" alt="image" src="https://github.com/ShawMerlin/NES-Power-Module-Redesign/assets/70423454/f8b0f98b-82c7-4b40-b43b-9c9d3e900d1b">


<br> <br>
4/30/2023 - <br> <br>
When connecting the RGBNES to this PWR Module, do not use the main RGB Headers on the RGBNES. <br>
- The Gen2 Cables have circuits in them to treat the RGB Signal.  The main RGB Headers on the RGBNES are also treating the RGB Signal. <br>
- If these header points are used, the picture will be a lot darker as a result. <br>
- There are other points on the RGBNES that can be used that have the RAW RGB Data before all the processing. <br>
- Use of the RAW RGB points will allow the picture's brightness to be accurate and good. <br>
- Reference these pins [HERE](https://github.com/ShawMerlin/NES-Power-Module-Redesign/blob/main/RGB%20-%20Genesis%209%20Pin%20Edition/Features%20and%20Components.md) <br>



   <br>

4/03/2023 - Newer features of the 2.1 Boards <br>
- Using JST 2.0 PH Connectors now so the wires are not so microscopic. <br>
- Updated the Audio Selection Switch to also control Audio Output on the Gen2 Port. <br>
- Added the Internal Componsite Circuit so now this board can be fully used without a RGBNES Installed. <br>
- Video Selection switch will now control whether Int or Ext Video is outputted on the RCA Jack. <br>
- If Dual Mono Audio is desired, a simple RCA Y Splitter cable can be used on the Red RCA Jack. <br>
  

3/13/2023 <br>
Gerbers, BOM and POS (JLCPCB Assembly) have been released and are on this github page. <br>



Key Features on this board.
- Switching Voltage Regulator.  This outputs a lot less heat and a stable 5V Supply.
- Seperate Ground Plane from the 5V Regulator and the RGB Traces.  2 Grounding points on the Board. 
- Physical cut outs in the PCB board to help shield against any EMI from the regulator.
- Switch for selection of Internal Audio or External Audio (if you have your own Audio Circuit)
- Switch for Selection of the Multi-Function RCA Jack to be Left (mono Audio) or Composite from the RGB Board.
- 3 Way Side Switch that can be wired into the Palette Selection on the RGB Board - 
- Gen2 Output is compatible with the Scart Adapters, HDRetrovision Cable, OSSC and the Retrotink.  
- The RGBNES offers Raw RGB Output pads as the Gen2 Cables will add 75 ohm resistors. Check instructions for more details.


Click here for a list of the features this board offers - [Link](https://github.com/ShawMerlin/NES-Power-Module-Redesign/blob/main/RGB%20-%20Genesis%209%20Pin%20Edition/Features%20and%20Components.md)


Click here for Instructions on how to install this Power Module - [Link](https://github.com/ShawMerlin/NES-Power-Module-Redesign/blob/main/Install_Instructions.md)

(RGBNES Required for the Gen2 Port on this No Cut Mod Board, Normal Componsite and Audio will still work without it.) <br>

Shoutout to Long Island Retro Gaming for the screenshot!! - https://www.youtube.com/@LIRetroGaming
![image](https://user-images.githubusercontent.com/70423454/226394506-f0109706-81cb-4232-8296-21bb947b9209.png)


![image](https://user-images.githubusercontent.com/70423454/222490935-0a6bae29-9fde-409d-aaa8-4821d209c6cb.png)

![image](https://user-images.githubusercontent.com/70423454/216229176-2274718d-cc2f-489f-aa68-324682cbb03c.png)


<br> <br>
Update History <br>

3/20/2023 - Feedback from testers has been excellent.  I have received great feedback which is being done in the next revision.  <br>  <br>
Revisions for V2.1
- Removed the ability to use the multifuction port as an Audio Port.  It is now Video Componsite Only.  <br>
- Added the internal Composite circuitry back to the Power Board and made the seldctor switch, Int Video and Ext Video.  <br>

3/2/2023 - Testing is going good.  I am sending engineering samples to various testers in order to get feedback. <br>

Final Revision for V2.0 that brings some quality of life updates. <br>
- Moved the Optional Power LED to a more central location.  <br>
- Changed the Pitch from JST XH 1.5mm to JST PH 2.0mm to make it a lot easier to solder without bridges.  <br>
- Rotated JST Connector so now a right angle one can be used.  <br>
- Gen2 Audio Output now is controlled by the Ext/Int Audio Switch. <br>
- Rotated the Palette Switch outputs for easier access. <br> <br>

2/28/2023 - Boards have arrived and are assembled.  I couldn't find my Gen2 9 Pin to SCART cable so I had to order a new one.  <br>
It sohuld arrive today and after testing is complete.  All files will be released on this github. <br>

2/1/2023 - Getting back on the horse!!  I have Version 1.9 completed and ordered. I should be able to test within a couple of weeks.
This new version has slide switches instead of header jumpers and I have also changed the pinout on the 7 pin connector to match the color of wires.

9/12/2022 - I have made a couple of changes to the RGB Board, I have moved the 9 pin Genesis Connector closer and fixed part of the audio circuit.
The Gerber files have been taken down until we get this new one tested.
