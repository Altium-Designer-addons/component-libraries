# Libs_NetTieLib

The library NetTieLib is distributed "as is" with no warranty.

The library was created as a template. Please feel free to modify the library components according to your design standards.

The library is distributed free of charge.


## What is a Net Tie component?

The library contains special Net Tie components which are used in Altium Designer to split one signal/net into several signals/nets or join several signals/nets into one signal/net. The Net Tie component in fact creates a short circuit connection of the signals. Altium Designer do not reports those short circuit connections as DRC violation if the connection is done by a Net tie component.\
To "net-tie" different signals from several layers, use a NetTieVia component.


## Package content

* NetTieLib.IntLib - integrated library NetTieLib which can be installed and used in Altium Designer
* Documentation - documentation to NetTieLib and Net Tie components in general
* DRC exceptions - RUL files with [DRC exception rules](#design-rule-check-exceptions) which suppress violations in PcbDoc when NetTieLib components are used
* NetTieLibSampleBoard - [sample PCB project](#sample-board) with all components from the NetTieLib, DRC exception rules applied
* NetTieLibSource - source files used for building NetTieLib.IntLib, you can open NetTieLib.LibPkg file in Altium Designer,  modify the library and compile it back into IntLib file which will be located in NetTieLibSource\Outpupt\


## Library design parameters

The library design parameters were set by need of regular low and medium density boards. Footprints should be modified accordingly to comply with your design standards or needs - different clearance, smaller/bigger footprints, microvias, burried/blind vias etc.

Clearance 0.2mm = distance of pads including attached track ends to other pads with their trackends


## Footprint variants by suffix

* LP = Low Power - for track width up to 12mil/0.3mm ~ max. 1A@(Cu 18um, temp rise 10°C)
* MP = Medium Power - for track width up to 40mil/1mm ~ max. 2.5A@(Cu 18um, temp rise 10°C)
* HP = High Power - for track width up to 120mil/3mm ~ max. 5A@(Cu 18um, temp rise 10°C)
Net tie vias LP, MP, HP are through hole vias with hole 0.3, 0.6 and 0.8mm and outer diameter 0.6, 1.0 and 1.4mm.


## Design Rule Check exceptions

Net Tie components produce some of DRC violations. These violation should be addressed by additional rules - exceptions - from the standard technology. The rule exceptions are prepared in folder _DRC exceptions_ in NetTieLib package. There are 3 files included, please use/modify those rules in context of your design.

* GNDtopologyStar.RUL - rule defines StarPoint component as a center of starburst routing topology in GND net
* NetTieComponentClearance.RUL - rule which removes 3D component clearance check to NetTieLib components (excluding Solder junctions) what allows to have them under other components
The rules can be imported in PCB editor by menu Design >> Rules and righ mouse click on Design Rules item in the tree list and selecting Import Rules
* NetTieViasHoleToHole.RUL - rule necessary for suppressing HoleToHole violation when NetTieVia component is used. Routing of these components is usually done in Ignore Obstacles routing mode. All pads of the NetTieVias must be added to Pad Class with name NetTieVias unde Design >> Classes.

![NetTieViasPadClass.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/NetTieViasPadClass.png)

![RULimport.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/RULimport.png)


## List of library components

| Name | Symbol(s) | Footprint (MP version only) | Description | Note |
|:-----|:----------|:----------------------------|:------------|:-----|
| 2way | ![2waySch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/2waySch.png) | ![2wayPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/2wayPCB.png) | 2 way net tie junction | Typically used for joining two nets together, e.g. AGND and DGND |
| 3wayT | ![3wayTSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/3wayTSch.png) | ![3wayTPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/3wayTPCB.png) | 3 way net tie junction T shape | Typically used for splitting signal to two receivers on board, e.g. clock signal to 2 ICs  |
| 3wayY | ![3wayYSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/3wayYSch.png) | ![3wayYPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/3wayYPCB.png) | 3 way net tie junction Y shape |      |
| 4way | ![4wayCrossSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/4wayCrossSch.png) ![4wayHSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/4wayHSch.png) | ![4wayPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/4wayPCB.png) | 4 way net tie junction | Schematic symbol has alternative graphics, see component Properties >> Display mode in schematic editor. |
| NetTieVia | ![NetTieViaSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/NetTieViaSch.png) | ![NetTieViaPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/NetTieViaPCB.png) | Net Tie Via | Connected signals are usually spread on different layers. Ignore Obsatacles routing mode should be used. |
| StarPoint | ![StarPointSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/StarPointSch.png) | ![StarPointPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/StarPointPCB.png) | Star point for definition of starburst topology | Routing topology rule must be applied in PCB. The rule can be imported from GNDtopologyStar.RUL, see [Design Rule Check exceptions](NetTieLib#Design_Rule_Check_exceptions.md) section. |
| 2waySolderNC | ![2waySolderNCSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/2waySolderNCSch.png) | ![2waySolderNCPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/2waySolderNCPCB.png) | 2 way net solder junction - Normally Connected | Soldered connection marked in silkscreen and by 3D body. |
| 2waySolderNO | ![2waySolderNOSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/2waySolderNOSch.png) | ![2waySolderNOPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/2waySolderNOPCB.png) | 2 way net solder junction - Normally Open |      |
| 3waySolder | ![3waySolderSch.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/3waySolderSch.png) | ![3waySolderPCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/3waySolderPCB.png) | 3 way net solder junction | Soldered connection marked in silkscreen and by 3D body. |


## Sample Board

All NetTieLib components on one schematic. Blankets (yellow polygons) are used for definition of net classes for LP, MP and HP sections and for definition of track width in the end:

![NetTieLibSampleSchematic2.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/NetTieLibSampleSchematic2.png)


Sample board with all NetTieLib components:

![NetTieLibSamplePCB.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/NetTieLibSamplePCB.png)


3D view of 2 way solder junctions Normally Closed (NC) and Normally Open (NO) version displayed. Soldered connection marked in silkscreen and by 3D body:

![2waySolder3D.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/2waySolder3D.png)


3D view of 3 way solder junction. Soldered connection marked in silkscreen and by 3D body:

![3waySolder3D.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/3waySolder3D.png)


NetTieVias example in 2D view. Every track is in different net and is placed on separated layer:

![NetTieVias2D.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/NetTieVias2D.png)
![NetTieVias3D.png](https://github.com/Altium-Designer-addons/component-libraries/blob/master/Libs_NetTieLib/Documentation/wiki/NetTieVias3D.png)
