[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

# Crossbow
### A CNC filament cutter from DW-Tas: <a href="https://ko-fi.com/O5O5OCC0K"><img src="docs/images/Ko-fi_smol.png"> Ko-Fi</a>, <a href="https://github.com/DW-Tas">GitHub</a>

<img src='docs/images/crossbow_cutter.png' width=400 /><br/><img src='docs/images/crossbow_cutter_render.png' width=400 />

## Design philosophy
The crossbow filament cutter was developed to provide a robust, reliable, easily serviceable, versatile and universal filament cutting solution for printed toolheads. Key features include:
1. Aluminum CNC construction: Reliable cutting action that can withstand multi-thousand operations without wear.
2. Low profile and low mass: maintains toolhead rigidity, centre of mass and input shaper performance.
3. Ease of servicing: two easily accessible screws to remove and replace cutting blade and clean the filament path.

## Designed for the A4T, but intended for universal use
Crossbow was designed and developed around the A4T, but is intended for universal for use in printed toolheads that have a flat mounting surface below the extruder.<br/><br/>
Crossbow A4T parts can be downloaded here: <a href="https://github.com/Armchair-Heavy-Industries/A4T/tree/main/STL/Extruder%20Adapters/For%20Crossbow%20filament%20cutter">https://github.com/Armchair-Heavy-Industries/A4T</a>.
<br/><br/>

> [!TIP] 
> The design accomodates extruders that use the Sherpa-Mini or Oribiter v2.0 mounting hole spacing (Checked for fit with Dragon Burner in CAD models with an example Dragon Burner Mod included in the [Dragon Burner example](<Dragon Burner example>) folder).<br/><br/><img src='docs/images/dragon-burner-example.png' width=200 />

## Blade replacement
Blade replacement is generally recomended after 3000-4000 cuts, depending on the material being cut. Crossbow can use a #17A or #4 hobby knife blade. Trimming the blades to size is required. The following jig is available to help cut the blade down.

**Jig BOM:**
1. 4x M3x8 SHCS / BHCS screws
2. 4x M3 Square Nuts (DIN 562)
3. #17 or #4 hobby knife blade
4. Printed jig parts: [Blade cutting and alignment jig.stl](<STL/Blade cutting and alignment jig.stl>)

**Instructions video:**<br/>
[<img src="https://img.youtube.com/vi/HI4ksrRDHjI/hqdefault.jpg" width="300" height="200"/>](https://www.youtube.com/embed/HI4ksrRDHjI)

<br/><br/>

## Screw adjustment

> [!WARNING] 
> The two main screws that act as pivots should have medium thread locking compound applied.

* **Lever Arm Pivot:** Tighten the screw to allow smooth movement of the lever arm during cutting, while preventing vertical play or rattling.
* **Blade Holder Pivot:** Start with the screw too loose then tighten the screw until the blade begins to shift slightly toward the filament path during its cutting motion. This ensures full travel of the cutting arm and minimizes unwanted movement.

<br/><br/>

## Licenced manufacturers
Crossbow is being manufactured under license by:<br/>
| Fysetc                                            | Trianglelab                                       | BLV                                               |
| ------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- |
| ![Fysetc](docs/images/fysetc.png)                 | ![alt text](docs/images/tl.png)                   | ![alt text](docs/images/blv.png)                  |
| https://aliexpress.com/item/1005009769281594.html | https://aliexpress.com/item/1005011557554076.html | https://aliexpress.com/item/1005011575849723.html |


<br/><br/>
> [!TIP] 
> ### You can help support the development of this project.<br/>
> Donate at https://ko-fi.com/dwtas<br/>
[![ko-fi](docs/images/Ko-fi_TextLogo.png)](https://ko-fi.com/dwtas)
<br/><br/>

### Credits
* Inspired by Treintjes' <a href="https://github.com/Treintjes/Magneto_Filament_Cutter">Magneto_Filament_Cutter</a><br/><br/>
* Beta testers
  * igiannakas <a href="https://github.com/igiannakas/">GitHub</a>
  * KnightRadiant <a href="https://github.com/jrlomas/">GitHub</a>
  * jeremytodd1
  * jbob
<br/><br/>
#### This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

### License clarification regarding non-commercial use:
The non-commercial aspect of this license is for cases where Crossbow is the product, not the use of Crossbow to create products.<br/>
I.e. If you wish to sell Crossbow as a product, you would need to seek a commercial license before doing so. </br>
It is NOT intended to prevent the use of Crossbow in a printer that you use to provide commercial services. If you want to run Crossbow as a toolhead for your print farm printers, go right ahead.