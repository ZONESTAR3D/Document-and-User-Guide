### Choose Language (Translated by google)
[![](../lanpic/ES.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=es)
[![](../lanpic/PT.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=pt)
[![](../lanpic/FR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=fr)
[![](../lanpic/DE.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=de)
[![](../lanpic/IT.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=it)
[![](../lanpic/SW.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=sv)
[![](../lanpic/PL.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=pl)
[![](../lanpic/DK.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=da)
[![](../lanpic/CZ.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=cs)
[![](../lanpic/HR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=hr)
[![](../lanpic/RO.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=ro)
[![](../lanpic/SK.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=sk)

[![](../lanpic/JP.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=ja)
[![](../lanpic/KR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=ko)
[![](../lanpic/ID.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=id)
[![](../lanpic/TH.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=th)
[![](../lanpic/VN.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=vi)
[![](../lanpic/IL.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=iw)
[![](../lanpic/SA.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=ar)
[![](../lanpic/TR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=tr)
[![](../lanpic/GR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=el)
[![](../lanpic/BR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=pt)
[![](../lanpic/RU.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=ru)
[![](../lanpic/CN.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color?_x_tr_sl=en&_x_tr_tl=zh-CN)

-----
# Color Mixing Feature User Guide
### :warning: This guide is for 4 extruders with 4-IN-1-OUT mix color hot end.
The color mixing function is the characteristic that to mix different color filaments and extruded out from one nozzle to get a new color filament.By adjusting the extrude ratio of each extruder, it can get different color filament.
The machine can achieve the following color mixing functions:
1. **Manual color mixing feature:** Manually adjust the extrusion ratio of each extruder ([mixing ratio](#mixing-ratio)) by the LCD control panel to change the printing color.
2. **Gradient color mixing feature:** The gradient mix function is a feature of changing the [mixing ratio](#mixing-ratio) according to printing height automatically. It can be activated from the LCD control panel or by adding gcode to "Start G-code" when slicing to .
3. **Random color mixing feature:** The random mix function is a feature of changing the [mixing ratio](#mixing-ratio) according to printing height randomly. It can be activated from the LCD control panel or by adding gcode to "Start G-code" when slicing.
4. **Mixed multi-color feature** To define a preset [mixing ratio](#mixing-ratio) as a ***virtual extruder*** and then using these virtual extruders in slicing software, the printer can print more colors than the actual extruders. For example, printing 8 color 3d models by using a 4 extruders 3d printer. Now our mix color 3d printer can set up to 16 ***virtual extruders***.

-----
## Term explanation
The following documents may mention some proper noun that will be used in color mixing printing. Let's give a description of these names so that you can better understand the content of the following documents.
#### Bowden extruder
A Bowden extruder is a type of extruder that pushes filament through a long and flexible PTFE tube (Bowden tube) to the hot end. ZONESTAR multi color 3d printers are used Bowden extruder. [:page_with_curl:wiki page](https://en.wikipedia.org/wiki/3D_printer_extruder)        
![](./BowdenExtruder.jpg)      
>
		A. Filament feeder mechanism   B. PTFE tube    C. Hot end
#### Extruder / Tool Chain
The extruder can refer to all the the extruder motor and hot end, or it can refer to the filament feeder mechanism. Whe we said extrusion feeder, it means the filament feeder mechanism.
In some slicing software, the extruer also be called "Tool Chain", "Tool head" or "Tool".For singel color or general multicolor printer, each extrusion feeder corresponds to one hot end / nozzle, so the number of tool chain is equal to the extrusion 
#### Mixing ratio
Distribute the length of the extruded filaments to different extruders to achieve color change during nozzle extrusion, and this ratio is called the extrusion mixing ratio. The value of mixing ratio should be between 0 and 100, and the sum of the ratios of each extruder cannot be less than 1 (>= 1).     
The ZONESTAR 3D printer supports setting the mixing ratio based on percentage or extruder ratio relationships. For example: "E1:E2:E3:E4 = 10:20:30:40" and "E1:E2:E3:E4 = 1:2:3:4" and "E1:E2:E3:E4 = 0.2:0.4:0.6:0.8" are equivalent. But when the mix ratio showed on LCD menus, they are always displayed at a percentage rate (sum = 100).
#### Virtual extruder / Virtual Tool / VTool
Since in slicing software, each extruder corresponds to a colored filament, in order to use the new colored filament obtained by mixing with the solid extruder, we can make the slicing software think that this is a new extruder. And in order to distinguish it from the actual extruder, we call it a "virtual extruder". In different slicing software, "Virtual extruder" also be called "Virtual Tool" or simply as "VTOOL".   
We can obtain many colored filaments by setting different mixing ratios, so we can define many virtual extruders. Default the machine has already set 16 virtual extruders when it left factory. You can change these mixing ratio any time, but after the machine restart, a printing (from SD card) is finished or abort, the machine will automatically reset the mixing ratio of all virtual extruders to default.     
##### :warning: Note 
1. To distinguish between a actual extruder and a virtual extruder, the actual extruder will be written as "Extruder #n" or "En" (n is from 1 to 4) in subsequent documents, such as "Extruder #1" or "E1". And write the virtual extruder as "VTOOLm" (m is from 0 to 15), such as "VTOOL4".
2. The default settings may different in the different firmware versions, please read the release note of the firmware.          
3. Once set the hot end type to "mixing" on LCD menu, the printer always use the "Virtual extruder" instead of the actual extruders. Because default the mix ratio of "VTOOL 0" is "E1:E2:E3:E4 = 100: 0: 0: 0", so it is completely equivalent to actual extruder #1; The mix ratio of "VTOOL 1" is "0: 100: 0: 0", so it is equivalent to actual extruder #2; The mix ratio of "VTOOL 2" is "0: 0: 100: 0", so its result is equivalent to actual extruder #3; The mix ratio of "VTOOL 2" is "0: 0: 0: 100", so its result is equivalent to actual extruder #4.

-----
## How to set mixing ratio of virtual extruder (for 4-IN-1-OUT mix Color hot end)
We can set the mixing ratio of each virtual extruder by LCD control panel or adding command in the "Start G-code" of slicing software.
:warning:If a printing from SD card is finished or abort, the machine will automatically reset mixing ratio of all virtual extruders to default.
### Set mixing ratio by LCD control panel
Steps:
- **Control>>Mixer>>Mix>>VTOOL: x** Choose the virtual extruder number which you need to set(x is from 0 to 15)
- **Control>>Mixer>>Mix>>Extruder1~4:** Adjust the percentage of extruder #1 to extruder #4, the range is 0 ~ 100.  
- **Control>>Mixer>>Mix>>Comit:** Redistribute the percentage of all extruders in proportion and save it to the virtual extruder x. 
### Set mixing ratio by adding command
We can also add M163 and M164 command into the "Start G-code" of slicing software, to set the mixing ratio of the virtual extruder.
Commands list as below:
>
	M163 S0 Px		; set the mix ratio of actual extruder #1, "x" is from 0 to 100
	M163 S1 Py		; set the mix ratio of actual extruder #2, "y" is from 0 to 100
	M163 S2 Pz		; set the mix ratio of actual extruder #3, "z" is from 0 to 100
	M163 S3 Pn		; set the mix ratio of actual extruder #4, "n" is from 0 to 100
	M164 Sm   		; save the mix ratio of extruders to the "VTOOLm", "m" is from 0 to 16
	
	For example, you added the below commands into the "Start G-code" of slicing software
	M163 S0 P10		
	M163 S1 P20		
	M163 S2 P30		
	M163 S3 P40		
	M164 S4
	
	After that, the VTOOL4 has been set mix ratio "E1:E2:E3:E4 = 10:20:30:40". When using VTOOL4, 4 actual extruders will feed 
	filaments in a ratio of 10:20:30:40.

-----
## [:book:Auto mixing color operation manual][auto_mixing]
The manual color mixing, gradient color mixing and random color mixing feature usually be used for printing models such as gradient vases. For operation manuals, please refer to [:book:**this guide**][auto_mixing].     
![](./2.jpg)![](./4.jpg)   
## [:book:Mixed multi-color operation manual][mixed_multi_color]
For how to use a virtual extruder to print 3D models with more colors than the number of extruders, please refer to [:book:**this guide**][mixed_multi_color].     
![](./6.jpg)  


[auto_mixing]: https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color/Auto_Mixing.md
[mixed_multi_color]: https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color/Mixed_MultiColor.md