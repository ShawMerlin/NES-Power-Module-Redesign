# NES Revival - Classic USB C Powered Module

This power board will work with both PD & Non-PD USB C.  Recommend at least a 1.5 AMP USB C if using Non-PD

We used the TUSB321RWBR IC for PD Negoations.  This will negotiate up to 3 amps depending on what PD charger is used.

This IC also is 5 volt only.  It will not negotiate any voltage about 5 volts so your equipment will always be in safe parameters.

Gerber Files found here - https://github.com/ShawMerlin/NES-Power-Module-Redesign/tree/main/USB-Powered-RCA-Classic/Kicad%20Files

I have added TVS ESD Protection, a 5V clamp, and a 5V Stability inductor to produce clean 5V Power no matter the quality of input power.

![image](https://user-images.githubusercontent.com/70423454/217629454-b0fea377-ea70-4ac9-a75a-1ec10e301bd8.png)

![image](https://user-images.githubusercontent.com/70423454/211245067-9edf0977-9ca4-4d2b-83af-919b6c7a3872.png)

Currently, I have tested the below Anker Power Block and USB-C Cable with 2-3 amps for several days with this board.  No Issues seen.

https://www.amazon.com/gp/product/B099F558S1

![image](https://user-images.githubusercontent.com/70423454/217142508-b8104a0e-d6df-483b-9b2b-cd79f72c6e8a.png)


https://www.amazon.com/dp/B088NRLMPV

![image](https://user-images.githubusercontent.com/70423454/217142384-07bf006e-8a3d-4f70-8dc2-9b206ea31aca.png)


