XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
X   	Artwork and documentation done by: 												X
X																																X
X	TEXAS INSTRUMENTS NORWAY LPW              										X
X  																															X	
X	Address: Gaustadalléen 21    0349 OSLO                  			X
X 	web: www.ti.com/lpw 		                        						X
X                                                           		X
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

PCB NAME : CC2541 Sensor Tag
REVISION: 1.4
DATE: 2013-04-17

FILE:  PACKED WITH WinZIP 

PCB SPESIFICATIONS

According to:         IPC-A-600 if not otherwise specified

Generally:            Supplied as single boards according
                      to Drill Drawing, or panelized
                      according Panel Drawing.

                      Vias are covered by Solder Resist.

                      Data for Solder Paste is scaled 1:1, and 
                      must be reduced according to assembly 
                      recommendation.

Laminate:             FR4 1.5mm
Number Of Layers:     4
SMD Technique:        Yes
Copper Thickness:     18um
Protective Coating:   HASL (RoHS compl.)
Solder Resist:        Liquid Film Photopolymer
Legend:               Yes

Panel size:           n.a.
Board size:           25.0mm x 57.0mm

Electricaly Tested:   Yes

Minimum Design Rules Cu
Insulation:           0.125mm
Trackwidth:           0.150mm
Annular Ring Width:   0.150mm
Finished Hole Size:   0.300mm

                 
FILE NAME            		DESCRIPTION                               	FILE TYPE
-------------------------------------------------------------------------------------------
***PCB MANUFACTURING FILES:
l1.SPL                  LAYER 1 COMPONENT SIDE/POSITIV              EXT. GERBER
l2.SPL                  LAYER 2 Inner layer/POSITIV                 EXT. GERBER
l3.SPL                  LAYER 3 Inner layer/POSITIV                 EXT. GERBER
l4.SPL                  LAYER 4 SOLDER SIDE/POSITIV                 EXT. GERBER
STOPCOMP.SPL            SOLDER MASK COMPONENT SIDE/NEGATIVE         EXT. GERBER
STOPSOLD.SPL            SOLDER MASK SOLDER SIDE/NEGATIVE            EXT. GERBER
SILKCOMP.SPL            SILKSCREEN COMPONENT SIDE/POSITIVE          EXT. GERBER
SILKSOLD.SPL            SILKSCREEN SOLDER SIDE/POSITIVE             EXT. GERBER
CARBON.SPL							CARBON LAYER/POSITIVE												EXT. GERBER
NCDRILL.SPL             NC DRILL THROUGH HOLE                       EXCELLON
DRILL.SPL               DRILL/MECHANICAL DRAWING                    EXT. GERBER
GERBER.REP              DRILL/NC DRILL REPORT                       ASCII
EXT_GERBER.USR          EXTENDED GERBER APERTURE TABLE              ASCII
CNC.USR                 NC DRILL DEVICE FILE                        ASCII

*** ASSEMBLY FILES:
PASTCOMP.SPL            SOLDER PAST COMPONENT SIDE/POSITIVE         EXT. GERBER
PASTSOLD.SPL            SOLDER PAST SOLDER SIDE/POSITIVE           	EXT. GERBER
ASSYCOMP.SPL            ASSEMBLY DRAWING COMPONENT SIDE/NEGATIVE    EXT. GERBER
ASSYSOLD.SPL            ASSEMBLY DRAWING SOLDER SIDE/NEGATIVE       EXT. GERBER
P&P_COMP.REP            PICK AND PLACE FILE COMPONENT SIDE         	ASCII
P&P_SOLD.REP            PICK AND PLACE FILE SOLDER SIDE            	ASCII

CC2541_SensorTag_Partlist_1_4.xls	BOM															Excel


PDF FILES:
CC2541_sensorTag_1_4_Schematic.pdf		Circuit Diagram
CC2541_sensorTag_1_4_Layout.pdf					Layout Diagram

CADSTAR FILES:
CC2541_sensorTag_1_4.scm				Cadstar Schematic file
CC2541_sensorTag_1_4.csa				Cadstar Shematic archive
CC2541_SensorTag_1_4.pcb				Cadstar layout file
CC2541_SensorTag_1_4.cpa				Cadstar PCB archive

README.TXT           		THIS FILE                                 	ASCII


Changes from rev 1.3:
Only changes in silk print; Added marking for ARIB T66 certification and moved orginal silk print to fit all certification text
Changes from rev. 1.2: 
Only changes in silk print; moved CE-mark and added Model:CC2541SensorTag to be in compliance with Industry Canada regulation

END.
