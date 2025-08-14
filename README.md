# statiTenz_regulator_nitropump

<img src="promo\showcase_assembly.gif" alt="showcase_assembly" width="800" height="450">  

Designed as part of the [**_statiTenz project_**](https://github.com/topics/statitenz).

## Application

Designed to pump liquid nitrogen from one vessel to another.

## Operating principle

Brushless DC motor actuated impeller pushes liquid nitrogen up the pipe.

## Basic operations

- Switch in **OFF** position
  The device remains powered off.
- Switch in **AUTO** position
  The motor speed is controlled by the PWM pin in the 3-pin connector.
- Switch in **ON** position
  The motor speed is manually controlled using the large knob, while the small knob sets the maximum speed limit.

## Operation tips

📝 Ensure the device is fully cooled before operation.  
📝 The check valve prevents ice formation inside the top part of the device.  
⚠️ **Do not** seal any vessel containing liquid nitrogen.  
⚠️ Exposing the cooled pumping part to the atmosphere will quickly cause ice to form inside the motor. Defrost and dry it at room temperature.  
⚠️ Plastic parts may explode upon cooling or heating. Let them settle at least 10 minutes before handling.  

## Assembly tips

Click on CODE -> Download ZIP to download all project files.  
Assemble the device following the instructions in the CAD_files\drawings folder.  
Refer to the schematics_and_PCBs folder for wiring instructions.  
The bill of materials is available in the CAD_files\buying_BOMs folder.  
Replace the motor's bearings with ceramic ones to ensure proper operation in liquid nitrogen.  
Handle ceramic bearings carefully, as they are fragile. It is recommended to purchase a spare set.  
Use the printed jigs (bearing_removing_jig_1 and bearing_removing_jig_2) to remove the stock bearings.  
PTFE sealing tape works fine.  
PTFE is generally a suitable material for use with liquid nitrogen.  
Print all parts in PETG. While PET performs adequately in liquid nitrogen, it may experience fatigue over time.  

<img src="promo\statiTenz_regulator_nitropump_head.gif" alt="statiTenz_regulator_nitropump_head" width="800" height="450">  

<img src="promo\statiTenz_regulator_nitropump_pump.gif" alt="statiTenz_regulator_nitropump_pump" width="800" height="450">  

## Demo

Watch a short demonstraition [here](https://youtu.be/WFPVAQTfw5o) and [here](https://youtu.be/W20JA836Wec).
Or [here](https://rutube.ru/video/cd4911075f1441f6e3c4c198d58dbadf) and [here](https://rutube.ru/video/834853d1d1c72582e7ad7376b3be9698).

## Contact the author

Create a new issue.  

## Donate the author

[![donate][boosty-image]][boosty-link]  

[boosty-link]: https://boosty.to/rustywraith/donate
[boosty-image]: promo/boosty.png


[![CC BY 4.0][cc-by-shield]][cc-by]  
[![CC BY 4.0][cc-by-image]][cc-by]  

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
