
## A GND Loop discovery from the older NES Revival Power Modules.  <br>

I first must express my appreciation for the Retro Community.  Instead of tearing others down, they work to build and improve.  <br>
My mindset has always been that every design can be improved and I will always welcome any and all feedback.  <br>

A design flaw oversight was discovered from our power boards and community members brought this to my attention. <br>
The original GND to NES location was placed near the Full Bridge Rectifier with the thought of having a short retun path. <br>
My oversight was that the return path had to go all the way back to the Switching Regulator and then heads back to the rectifier.  <br>
This large GND Loop results in ringing and other undesirable impacts to the overall circuit. <br> 

While I do not believe that these power boards in the wild pose a danger to the NES, they will have a reduced life as a result.  <br>
Currently, I have only seen about a 4% failure rate on people reporting back to me. (Which I feel is still too high).   <br>

This GND Loop only impacts the Power Boards with Switching Regulators.  It does not exist on the 7805 designs <br>
The suggestion for 2oz copper on the 7805 designs was to provide more copper for heat dissipation and not to couple noise frequencies. <br>
I would like the express my thanks to the Dubesinhower Discord Group for bringing this to my attention <br>
I would also like to personally thank Zaxour for assisting with the new design layout. - https://twitter.com/zaxour  <br>

To make right to the community that I love,  I have 2 options for those that have a NES Revival Power Board and would like this fixed.  <br>  <br>

## Option #1 - A quick DIY Fix to shorten the GND Loop on the Power Board itself  <br>

- Step 1 Just right of the bottom interconnect pin, scrap back the soldermask  <br>
<img width="477" alt="image" src="https://github.com/ShawMerlin/Project-Notes/assets/70423454/02046060-b7c6-4868-9515-8014584bc00d">   <br>

- Step 2 Place a ball of solder on this exposed GND section.  <br>
<img width="477" alt="image" src="https://github.com/ShawMerlin/Project-Notes/assets/70423454/36140deb-ef84-42a1-8bc5-7efc649354b4">   <br>

- Step 3 Connect a GND Wire to that newly created pad and connect it to a nearby GND point on the NES Main Board <br>
<img width="477" alt="image" src="https://github.com/ShawMerlin/Project-Notes/assets/70423454/67fcb3c9-f568-41c2-84d7-28f514fb76d6">   <br>


## Option #2 - A replacement Power Module will be offered at a heavily discounted rate.  <br>
- If you have spent money/resources in any of these designs and would like a full replacement.  Please reach out to me. <br>
- My email is Merlin.Shaw@gmail.com.  Let me know how many replacements you would like to cover the boards you have made/purchased. <br>
- I will add your name to a list for replacements and will work to get through the list in a timely but realistic fashion. <br>
- The discount on the board will cover my costs and shipping. <br>
