**1/15/2025 - Version 3.1c** <br>
- Updated a mistake in the BOM for the Digikey Part number to be correct on the Q1 Transistor. <br>
-  https://www.digikey.com/en/products/detail/evvo/2SA1015/22482092 <br> <br>
- Updated C12 to be 560pF, 1nF will work fine but 560pF produces a slightly sharper picture. <br>
-  https://www.digikey.com/en/products/detail/kemet/C0805C561J5GACAUTO/10642381 <br> <br>
- Updated Switching Regulator from Digikey to the H Variant in the BOM - 1/17/2025 <br>
-  https://www.digikey.com/en/products/detail/texas-instruments/TPS54202HDDCR/6026259 <br> <br>

**6/15/2024 - Version 3.1c** <br>
- It's been a long time coming but I wanted to make sure the RGBNES Versions were perfect. <br>
- This uses the exact same voltage regulator as the RGBNES Compantion Board. <br>
- GND Loop issue has been resolved. <br>
- 2 Audio Ports to give Duo Mono Sound. <br>
- Gerbers will be released for this later next week. <br>

![image](https://github.com/ShawMerlin/NES-Power-Module-Redesign/assets/70423454/58c8878b-3d4e-4b5d-a789-e5c9d7a3947f)


**2/06/2024 3.0 Update** <br>
- I am in the process of testing our new 3.0 design with lots of great feedback from our community. <br>
- At this time, I do not recommend having any of the 2.0 boards built. <br>
- If you have already invested time/money into the older boards, Please contact me so we can work something out. <br>
- I have an official Statement on these new boards within a few weeks. <br>  <br>


**4/01/2023 2.1 Update**
- Create a Full Bridge Rectifier out of SMC Diodes for better heat dissapation into the PCB Board.
- Changed the 6.8uH Inductor to a 10uH inductor per the datasheet in order to reduce noise.
- Added an Input Inductor on the voltage regulator to reduce ringing on the circuit.
- Added a 1.9A Fuse for safety and including a tripped fuse LED indicator.
- Added more filtering caps on the 5v Output (47uF, 22uF, .1uF, 50pF)

![image](https://user-images.githubusercontent.com/70423454/229327264-134b7cf2-5151-47fe-b502-df62a01ec055.png)


**2/14/2023 2.0 Update**
- Upgraded the Full Bridge Rectifier to one that can do 5 Amps. The old version was getting pretty warm.
- Beefier DC Input Jack that can handle 5 Amps (old one could only do 2.5 amps)
- This Board has been tested pulling 3 Amps max without issue.
- Ground stitching over audio traces to help prevent any static and noise that would be coming from the Buck Converter.
- The Power LED turns on now when the Solder Bridge has been made. Meaning it can be disabled by removing the bridge.
- Most all parts are SMD now and made easy for an Assembly House like JLCPCB to build the PCB and Assemble for you.
- BOM and POS files are included that Assembly Houses will need.

**9/19/2022 Update**
- Version 1.8 - Increased the Ground Stitching around the Video Trace and added Ground Stitching to the Audio Trace.

I have uploaded the Gerbers for this board and also a Bill of Materials and Position File.
You can use both these .CSV files to have JLCPCB provide and Assemble the SMD parts for you.

# Picture Showcase!!

![IMG_0249](https://user-images.githubusercontent.com/70423454/179364663-a0c55e0e-c655-44df-aa56-60dbd48e1ca1.JPG)

![IMG_0247](https://user-images.githubusercontent.com/70423454/179364715-3eb0b7fd-7f62-46b9-8909-671c2c8192e6.JPG)

![IMG_0253](https://user-images.githubusercontent.com/70423454/179364775-fea9a326-a6ca-4d14-ba35-7a6c670ecfa7.JPG)

![IMG_0248](https://user-images.githubusercontent.com/70423454/179364731-f40d4218-21f4-47a5-adba-e601ad28afcb.JPG)
