# MAXConfigs for stationary Z-Probe

## Setup Z-Probe
### 1.) Mount the Z-Probe on the table of the machine and connect it to the control cabinet.
### 2.) Unpack "CNC-ONE Max setup with stationary z-probe.zip" in your config folder of your machine.
### 3.) Start the machine and do a reference run. Jog with a tool in the spindle right over the center of the probe.
### 4.) Open the "CNC-ONE.ini" file in your config folder and adjust the tool senso position. Only change X and Y to machine absolute coordinates.
### 5.) Adjust the tool change position to a value of choice. Here it is the further most left corner.
### 6.) Remove the tool from the spindle
### 7.) Jog with the edge of the spindle on the z-probe until the probe triggers. Write down the absolute Z position.
### 8.) Open the machine settings in the control panel and adjust probe height to the absolute Z position. Invert the Z position so the number is positive. Leave the settings panel.
### 9.) Everything is ready now. Make a toolchange and insert a tool in the spindle. The spindle will probe the tool and adjust it length accordingly.
