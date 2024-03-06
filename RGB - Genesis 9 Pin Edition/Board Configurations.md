# Solder Jumper Configurations <br>

The Boards will come pre-configured for both External Video and Audio (S1 & S3) <br>
If Internal Video or Audio is desired, then the above solder jumpers will have to be desoldered. <br>

## Audio Selection *(Select either S1 or S2 but not both)* <br>
- S1 - External Audio <br>
- S2 - Internal Audio <br>
## Video Selection  *(Select either S3 or S4 but not both)* <br>
- S3 - External Video <br>
- S4 - Internal Video <br>
- S5 - Int Video Enable (Must be enabled if using S4) <br>
## Power LED
- S6 - Power LED Enable <br>

The board's internal audio circuit will not work if the RGBNES Pallettes are used. <br>
Bascially if using the RGBNES, External Video will be the only option that can be used. <br>
Desolder S4 & S5 if using the RGBNES and solder S3. <br> <br>

S1 & S3 are both external inputs, these come directly from the J8 JST Cable. <br>
These must be hooked up to the RGBNES's outputs in order for them to work correctly. <br>

<img width="874" alt="image" src="https://github.com/ShawMerlin/NES-Power-Module-Redesign/assets/70423454/ea951577-739b-4272-8ea3-00ca7ec8aecf">
