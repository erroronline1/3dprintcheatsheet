# 3d printing
## my cheat sheet

<details><summary>initial steps</summary>

* ensure orthograde cartesian coordinate system
* tighten screws
* [calibrate e-steps and temperature](https://3dprintbeginner.com/extruder-calibration-guide/)
* [level bed](https://all3dp.com/2/3d-printer-bed-leveling-step-by-step-tutorial/)

</details>

<details><summary>toolbox</summary>

* spatula
* caliper
* tweezer
* long nose pliers
* scalpel or cutter
* ptfe grease (use sparingly)
* brass brush
* infrared thermometer to check bed temperature
* high percentage isopropyl alcohol
* lint free cloths

</details>

<details><summary>benchmarks</summary>

* [calicat](https://www.thingiverse.com/thing:1545913/files)
* [xyz cube](https://www.thingiverse.com/thing:1278865)
* [20mm test cube](https://www.thingiverse.com/thing:38108) without top and bottom, only one wall to check flow
* [bed level test](https://www.thingiverse.com/thing:34558)
* [temp tower](https://www.thingiverse.com/thing:2729076)

</details>

<details><summary>recommendations</summary>

hardware:
* spoolholder with decent bearings - avoid top mounted spool holder resulting in built up vibrations

slicer settings:
* walls from inside to outside to enhance connection especially on overhangs and concave curves
* infill with cubic subdivision - quick and stable at lower infill rate
* disable z-hop to enhance precision and spare z-axis mechanics
* enabled combing (relevant cut print time!)
* reduce first layer dimension to avoid elephants foot

</details>

<details><summary>the upgrade trap</summary>

successful upgrades:
* mosfets for hotend and heatbed
* led illumination to examine quality during runtime
* cable chains
* bed holder
* screw direction reminder for bed levelling
* a marvellous faceplate
* bowden clips

unsuccessful upgrades:
* heat bed insulation - confusing the thermistor
* any printed fan duct - may need further investigations

software:
* newer slicer versions might make use of commands older printer firmwares are not able to compute

</details>

<details><summary>remember</summary>

* no cold pull to avoid nozzle clogging
* heat up hotend and heatbed for levelling, hotend for nozzle changes
* the ptfe-tube must connect straight to the heatsink to avoid backflow
* slicer profiles should have some version control, too much meddling can make things worse
* belts can be too tight
* bowden extruders need more retract that direct extruders

</details>

<details><summary>relax</summary>

* expensive dry boxes may be overrated (for pla) [source](https://www.youtube.com/watch?v=5CFxT1q6dX8)
* be patient - lower speeds reward with better quality
* you have to live with bad bottom layers on rafts and support
* remember the technical boundaries of fdm prints - speed, resolution, anisotrophy
* be aware you most likely have a low budget machine - don't expect miracles 
* sometimes it's just the filament being shit

<video src="./assets/filaments.mp4" width="360" /> (all printed with identical settings consecutively)

</details>

<details><summary>disclaimer</summary>

* i am a beginner
* my first printer is a second grade anycubic i3 mega s

</details>