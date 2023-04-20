### Choose Language (Translated by google)
[![](../lanpic/ES.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=es)
[![](../lanpic/PT.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=pt)
[![](../lanpic/FR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=fr)
[![](../lanpic/DE.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=de)
[![](../lanpic/IT.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=it)
[![](../lanpic/SW.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=sv)
[![](../lanpic/PL.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=pl)
[![](../lanpic/DK.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=da)
[![](../lanpic/CZ.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=cs)
[![](../lanpic/HR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=hr)
[![](../lanpic/RO.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=ro)
[![](../lanpic/SK.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=sk)

[![](../lanpic/JP.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=ja)
[![](../lanpic/KR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=ko)
[![](../lanpic/ID.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=id)
[![](../lanpic/TH.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=th)
[![](../lanpic/VN.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=vi)
[![](../lanpic/IL.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=iw)
[![](../lanpic/SA.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=ar)
[![](../lanpic/TR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=tr)
[![](../lanpic/GR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=el)
[![](../lanpic/BR.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=pt)
[![](../lanpic/RU.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=ru)
[![](../lanpic/CN.png)](https://github-com.translate.goog/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/Mixed_MultiColor.md?_x_tr_sl=en&_x_tr_tl=zh-CN)

-----
## Mixed multi-color operation manual
This section will introduce how to use a virtual extruder to print 3D models with more colors than the number of extruders.

-----
### Slicing steps
#### Step 1: Set the number of extruders
![](./slicing1.jpg)
#### Step 2: Set the mixing ratios of VTOOLs
Add mixing ratios of VTOOLs setting into the "Start G-code". [:page_with_curl: How to set mixing ratio of Virtual extruder](#how-to-set-mixing-ratio-of-virtual-extruder)
![](./slicing2.jpg)
#### :pushpin:Note
You can download the setting from the bewlow link and unzip it, and then import the setting to your slicing software (PrusaSlicer).
- [:arrow_down: Download config file](./config_WCMY.zip)    
- [:clapper: Video tutorial](https://user-images.githubusercontent.com/29502731/232972117-387a9e15-f3c7-417b-aff6-d876e119b70d.mp4)
#### Step 3: Assign an extruder to the components
![](./slicing3.jpg)
#### Step 4: Slicing and save gcode to SD card
#### Step 5: Print the file from SD card

-----
### Examples
#### 6 color OWL
- **[:clapper:Video tutorial](https://user-images.githubusercontent.com/29502731/232977232-4e8031b2-9142-4db2-9cef-12b85759fa17.mp4)**
- **[:arrow_down:Download stl file](https://www.thingiverse.com/thing:2373415)**
- **[:arrow_down:Download 3mf & gcode file](https://github.com/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/M4_6c_owl.zip)**
#### 10 color Noahs
- **[Video tutorial::clapper:Part1](https://user-images.githubusercontent.com/29502731/233287512-25575666-60ff-4b08-88a2-e3ff8149599f.mp4) [:clapper:Part2](https://user-images.githubusercontent.com/29502731/233287715-8dd8517e-8260-41ec-888b-8ba28b692c27.mp4)  [:clapper:Part3](https://user-images.githubusercontent.com/29502731/233287893-a31ec2ab-e4e6-4080-8a97-6ccf92502fa4.mp4)**
- **[:arrow_down:Download stl file](https://github.com/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/noahs.zip)**
- **[:arrow_down:Download 3mf & gcode file](https://github.com/ZONESTAR3D/Document-and-User-Guide/Mixing_Color/M4_10c_noahs.zip)**
<!-- #### 16 color  -->
<!-- - **[:clapper:Video tutorial]()** -->
<!-- - **[:arrow_down:Download stl file]()** -->
<!-- - **[:arrow_down:Download 3mf & gcode file]()** -->

-----
### Appendix: Color mixing ratio reference settings 
Here is a set of reference mixing ratio settings for mixing Cyan, Magenta, and Yellow filament into other color filament.
-	**Filament color:**
	-	E1: White
	- E2: Cyan
	- E3: Magenta
	- E4: Yellow
-	**mix ratio and extruder color:**

|VTOOL number|mixing ratio|mixed filament color|Extruder color <sup>*</sup> |
|:----------:|:----------:|:------------------:|:--------------------------:|
|    0       |  100/0/0/0 |      White         |      R255 G255 B255        |
|    1       |  0/100/0/0 |      Cyan          |      R0   G255 B255        |
|    2       |  0/0/100/0 |      Magenta       |      R255 G0   B255        |
|    3       |  0/0/0/100 |      Yellow        |      R255 G255 B0          |
|    4       |  0/0/0/100 |      Ocean-Blue    |      R255 G255 B0          |
|    5       |  0/50/50/0 |      Blue          |      R0   G0   B255        |
|    6       |  0/17/83/0 |      Violet        |      R169 G0   B255        |
|    7       |  0/0/83/17 |      red           |      R255 G0   B0          |
|    8       |  0/0/50/50 |      Orange        |      R255 G159 B0          |
|    9       |  0/17/0/83 |      Spring-Green  |      R191 G255 B0          |
|   10       |  0/50/0/50 |      Green         |      R0   G255 B0          |
|   11       |  0/50/0/50 |      Turquoise     |      R0   G255 B191        |
|   12       |  75/0/25/5 |      skin          |      R255 G210 B255        |
|   13       | 0/25/50/25 |      Magenta-Brown |      R106 G83  B83         |
|   14       | 0/25/25/50 |      Yellow-Brown  |      R106 G106 B83         |
|   14       | 0/33/33/34 |      Brown         |      R83  G83  B83         |


**\*** Extruder color: RGB value of the extruder color is used to set the extruder color in slicint software.
![](./extrudercolor.jpg) 

#### Gcodes list
You can copy the blow to the "Start G-code" in slicint software to set the virtual extruders.
>
		;White
		M163 S0 P100
		M163 S1 P0
		M163 S2 P0
		M163 S3 P0
		M164 S0
		;Cyan
		M163 S0 P0
		M163 S1 P100
		M163 S2 P0
		M163 S3 P0
		M164 S1
		;Magenta
		M163 S0 P0
		M163 S1 P0
		M163 S2 P100
		M163 S3 P0
		M164 S2
		;Yellow
		M163 S0 P0
		M163 S1 P0
		M163 S2 P0
		M163 S3 P100
		M164 S3
		;Ocean-Blue
		M163 S0 P0
		M163 S1 P83
		M163 S2 P17
		M163 S3 P0
		M164 S4
		;Blue
		M163 S0 P0
		M163 S1 P50
		M163 S2 P50
		M163 S3 P0
		M164 S5
		;Violet
		M163 S0 P0
		M163 S1 P17
		M163 S2 P83
		M163 S3 P0
		M164 S6
		;Red
		M163 S0 P0
		M163 S1 P0
		M163 S2 P83
		M163 S3 P17
		M164 S7
		;Orange
		M163 S0 P0
		M163 S1 P0
		M163 S2 P50
		M163 S3 P50
		M164 S8
		;Spring-Green
		M163 S0 P0
		M163 S1 P17
		M163 S2 P0
		M163 S3 P83
		M164 S9
		;Green
		M163 S0 P0
		M163 S1 P50
		M163 S2 P0
		M163 S3 P50
		M164 S10
		;Turquoise
		M163 S0 P0
		M163 S1 P83
		M163 S2 P0
		M163 S3 P17
		M164 S11
		;skin
		M163 S0 P18
		M163 S1 P0
		M163 S2 P5
		M163 S3 P1
		M164 S12
		;Magenta-Brown
		M163 S0 P0
		M163 S1 P25
		M163 S2 P50
		M163 S3 P25
		M164 S13
		;Yellow-Brown
		M163 S0 P0
		M163 S1 P25
		M163 S2 P25
		M163 S3 P50
		M164 S14
		;Brown
		M163 S0 P0
		M163 S0 P33
		M163 S1 P33
		M163 S2 P34
		M164 S15