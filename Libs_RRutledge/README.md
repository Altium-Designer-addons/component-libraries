# Libs_RRutledge

*NEEDS UPDATING TO 2013-12-23*

* Release date 2013-01-30
* Number of components 459 (list below)
* Plain SchLib and PcbLib files split by component categories
* Many additional component parameters attached as Manufacturer part numbers and Supplier links to Digikey and Mouser
* Some components has multiple footprints (beware that sometimes only the default matches the supplier link part number)
* Please read and respect the TERMS OF USE at the bottom!

Note that a few footprints may seem strange or unconventional because they were used in a specific situation. Nearly all footprints have 3D STEP models included. My usual practice is to dimension my models to represent max tolerances, but some older models may have nominal dimensions. Nearly all surface-mount passives and IC packages will be at max tolerance. As always, verify fitness for your application. Having said that, I have used each and every one of these footprints without any show-stopping issues and few if any issues. If you should find some issues, by all means please let me know so I can correct them!

As for the schematic libraries, my company has a convention of having one library entry per part; which means that a 1k, 10k, and 100k resistor in 0603, 0805, and 1206 sizes would be 9 separate library components. Not all components have supplier entries, but a great many do have DigiKey or Mouser supplier links which makes it much easier to generate a parts list for prototype builds. Once again, not everything is perfect because these libraries span the roughly 4 years since I used Altium Designer for the first time. Again, email me with any significant issues you encounter so I can fix them. Additionally, some schematic symbols may refer to footprints that have been renamed since they were created (a lot can happen in 4 years!), or to footprints that exist in company libraries that I am not able to share.

You may also direct special requests for footprints, symbols, and 3D CAD models of components to my email (read above for the address), but understand that I may not be able to answer all of them if there are too many requests (though I will try).

Sincerely,\
Ryan Rutledge\
gmail address ryandrutledge\
Wednesday, January 30, 2013


## Terms of use

Ryan Rutledge is furnishing these libraries "as is". I do not provide any warranty of the item whatsoever, whether express, implied, or statutory, including, but not limited to, any warranty of merchantability or fitness for a particular purpose or any warranty that the contents of the item will be error-free.

In no respect shall I or any other person incur any liability for any damages, including, but limited to, direct, indirect, special, or consequential damages arising out of, resulting from, or any way connected to the use of the item, whether or not based upon warranty, contract, tort, or otherwise; whether or not injury was sustained by persons or property or otherwise; and whether or not loss was sustained from, or arose out of, the results of, the item, or any services that may be provided herein.

Use of these libraries or any elements thereof constitutes acknowledgement and acceptance of the preceeding statements.

That being said, I'm providing these Altium Designer libraries in good faith, in the hopes that they will be useful to others. You are not required to pay for these or compensate me in any way, but one always enjoys being acknowledged for their work, so thanks are always welcome. Appreciation or questions may be sent to "ryandrutledge" at gmail.


## Components list

### Batteries

| LIBRARYREFERENCE | DESCRIPTION    | FOOTPRINT1  |
|:-----------------|:---------------|:------------|
| BATT_AAAx2_600mAh | Battery pack, 2-cell AAA | BAT-AAA-2 |
| BATT_AAx2_1300mAh | Battery pack, 2-cell AA | BAT-AA-2 |
| BATT_AAx2_600mAh | Battery pack NiMH 600mAh 2-cell AA | BAT-AA-2 |
| BATT_AAx2_900mAh | Battery pack, 2-cell AA | BAT-AA-2 |
| BATT_AAx2_Holder | Battery holder 2xAA PCB mount | BATT_HOLDER_2XAA |


### Capacitors

| LIBRARYREFERENCE  | DESCRIPTION      | FOOTPRINT1 |
|:------------------|:-----------------|:-----------|
| CAPC_100n_0402_16V_10% | Capacitor SMD Cer 100nF 10% 16V X5R 0402 | CAPC1005N |
| CAPC_100n_0603 | Capacitor SMD Cer 100nF 10% 50V X7R 0603 | CAPC1608N |
| CAPC_100n_0805 | Capacitor SMD Cer 100nF 10% 50V X7R 0805 | CAPC1608N |
| CAPC_100n_0805_100V | Capacitor SMD Cer 100nF 10% 100V X7R 0805 | CAPC2012N |
| CAPC_10n_0402_16V_10% | Capacitor SMD Cer 10nF 10% 16V X7R 0402 | CAPC1005N |
| CAPC_10n_0603_50V_10% | Capacitor SMD Cer 10nF 10% 50V X7R 0603 | CAPC1608N |
| CAPC_10n_100V_0603 | Capacitor SMD Cer 10nF 10% 100V X7R 0603 | CAPC1608N |
| CAPC_10p_0603_NP0_1%_50V_| Capacitor SMD Cer 10pF 5% 50V NP0 0603 | CAPC1608N |
| CAPC_10u_0805_10V | Capacitor SMD Cer 10uF 10% 10V X5R 0805 | CAPC2012N |
| CAPC_10u_0805_16V | Capacitor SMD Cer 10uF 10% 16V X7R 0805 | CAPC1608N |
| CAPC_10u_1206_10V | Capacitor SMD Cer 10uF 10% 10V X5R 1206 | CAPC3216N |
| CAPC_10u_1206_16V | Capacitor SMD Cer 10uF 10% 16V X7R 1206 | CAPC3216N |
| CAPC_10u_1210_50V | Capacitor SMD Cer 10uF 20% 16V X5R 1210 | CAPC3225N |
| CAPC_120p_0603_C0G_50V | Capacitor SMD Cer 120pF 10% 50V C0G 0603 | CAPC1608N |
| CAPC_150p_0603_C0G_50V | Capacitor SMD Cer 150pF 10% 50V C0G 0603 | CAPC1608N |
| CAPC_15n_0603_50V | Capacitor SMD Cer 15nF 10% 50V X7R 0603 | CAPC1608N |
| CAPC_15p_0603_NP0_5%_100V_| Capacitor SMD Cer 15pF 5% 100V NP0 0603 | CAPC1608N |
| CAPC_180p_0402_NP0_50V_5% | Capacitor SMD Cer 180pF 5% 50V NP0 0402 | CAPC1005N |
| CAPC_180p_1206_NP0_50V | Capacitor SMD Cer 180pF 10% 50V NP0 1206 | CAPC3216N |
| CAPC_18p_0603_100V | Capacitor SMD Cer 18pF 2% 100V NP0 0603 | CAPC1608N |
| CAPC_1n8_50V_0805 | Capacitor SMD Cer 1.8nF 10% 50V X7R 0805 | CAPC2012N |
| CAPC_1n_0402_10% | Capacitor SMD Cer 1nF 10% 16V X7R 0402 | CAPC1005N |
| CAPC_1n_0603_100V | Capacitor SMD Cer 1nF 10% 100V X7R 0603 | CAPC1608N |
| CAPC_1u_0603 | Capacitor SMD Cer 1uF 10% 16V X7R 0603 | CAPC1608N |
| CAPC_1u_0805 | Capacitor SMD Cer 1uF 10% 16V X7R 0805 | CAPC2012N |
| CAPC_220n_0603 | Capacitor SMD Cer 220nF 10% 16V X7R 0603 | CAPC1608N |
| CAPC_220n_0805 | Capacitor SMD Cer 220nF 10% 25V X7R 0805 | CAPC2012N |
| CAPC_220p_0603_NP0_50V_1% | Capacitor SMD Cer 220pF 1% 50V NP0 0603 | CAPC1608N |
| CAPC_220p_0603_NP0_50V_5% | Capacitor SMD Cer 220pF 5% 50V NP0 0603 | CAPC1608N |
| CAPC_22u_1206_16V | Capacitor SMD Cer 22uF 10% 16V X7R 1206 | CAPC3216N |
| CAPC_22u_1210_16V | Capacitor SMD Cer 22uF 20% 16V X7R 1210 | CAPC3225N |
| CAPC_22u_1210_6V3_X5R | Capacitor SMD Cer 22uF 20% 6.3V X5R 1210 | CAPC3225N |
| CAPC_22u_1812_25V | Capacitor SMD Cer 22uF 20% 25V X5R 1812 | CAPC4532N |
| CAPC_27p_0805_50V | Capacitor SMD Cer 27pF 5% 50V X7R 0805 | CAPC2012N |
| CAPC_27p_100V_0603 | Capacitor SMD Cer 27pF 1% 100V NP0 0603 | CAPC1608N |
| CAPC_2u2_0603_10V_10% | Capacitor SMD Cer 2.2uF 10% 10V X5R 0603 | CAPC1608N |
| CAPC_2u2_0805 | Capacitor SMD Cer 2.2uF 10% 16V X7R 0805 | CAPC2012N |
| CAPC_330n_0805 | Capacitor SMD Cer 330nF 10% 25V X7R 0805 | CAPC2012N |
| CAPC_33p_0402_NP0_50V_5% | Capacitor SMD Cer 33pF 5% 50V NP0 0402 | CAPC1005N |
| CAPC_39n_0603_25V | Capacitor SMD Cer 39nF 10% 25V X7R 0603 | CAPC1608N |
| CAPC_39p_0603_NP0_100V_1% | Capacitor SMD Cer 39pF 1% 100V NP0 0603 | CAPC1608N |
| CAPC_470n_0603 | Capacitor SMD Cer 470nF 10% 16V X7R 0603 | CAPC1608N |
| CAPC_470n_0805 | Capacitor SMD Cer 470nF 10% 16V X7R 0805 | CAPC2012N |
| CAPC_470p_0603_5% | Capacitor SMD Cer 470pF 5% 50V NP0 0603 | CAPC1608N |
| CAPC_47n_0603 | Capacitor SMD Cer 47nF 10% 50V X7R 0603 | CAPC1608N |
| CAPC_47n_1206_50V_X7R_10% | Capacitor SMD Cer 47nF 10% 50V 1206 | CAPC3216N |
| CAPC_4p7_100V_0603 | Capacitor SMD Cer 4.7pF ?0.25pF 100V NP0 0603 | CAPC1608N |
| CAPC_4u7_0805 | Capacitor SMD Cer 4.7uF 10% 16V X5R 0805 | CAPC2012N |
| CAPC_4u7_100V_2220 | Capacitor SMD Cer 4.7uF 10% 100V X7R 2220 | CAPC5750N |
| CAPC_560p_0603_5% | Capacitor SMD Cer 560pF 5% 50V NP0 0603 | CAPC1608N |
| CAPC_6n8_1206_NP0_50V | Capacitor SMD Cer 6.8nF 5% 50V NP0 1206 | CAPC3216N |
| CAPC_82p_0603_NP0_50V_1% | Capacitor SMD Cer 82pF 1% 50V NP0 0603 | CAPC1608N |
| CAPC_8p_0402_NP0_50V | Capacitor SMD Cer 8pF ?0.5pF 50V NP0 0402 | CAPC1005N |
| CAPE_100u_16V_THD | Capacitor THD Electrolytic 100uF 20% 16V Radial | CAPAE200P550X1200_FLAT2 |
| CAPE_10u_100V_SMD | Capacitor SMD Electrolytic 10uF 20% 100V Radial | CAP_ELEC_Size E |
| CAPE_1m_10V_SMD | Capacitor SMD Alum Elec 1mF 20% 10V | CAP_ELEC_Size G |
| CAPE_220u_10V_SMD | Capacitor SMD Alum Elec 220uF 20% 10V | CAP_ELEC_Size E |
| CAPE_220u_16V_THD | Capacitor THT Alum Elec 220uF 20% 16V | CAPE3.5mm |
| CAPE_220u_16V_THD_2.5mmLS | Capacitor THT Alum Elec 220uF 20% 16V 2.5mmLS | CAPE2.5mm_max6.8x12.5mm |
| CAPE_33u_200V_THT | Capacitor THT Alum Elec 33uF 20% 200V | CAPE5.0mm |
| CAPE_470u_16V_THT | Capacitor THT Alum Elec 470uF 20% 16V | CAPE10.0MM_Rad_10x14mm |
| CAPE_47u_100V_SMD | Capacitor SMD Electrolytic 47uF 20% 100V Radial | CAP_ELEC_Size H13 |
| CAPE_5m6_THT_80V | Capacitor THT Electrolytic 5600uF 20% 80V | CAPE10.0MM_Rad_30x45mm |
| CAPF_120n_2416_PPS_50V | Capacitor SMD PPS Film 120nF 2% 50V 2416 | CAPC6041X210N |
| CAPF_15n_1210_PPS_50V | Capacitor SMD PPS Film 15nF 2% 50V 1210 | CAPC3225N |
| CAPMF_100n_250V_MPET_TH | Capacitor THD Metallized PET Film 100nF 10% 250V | CAPM75P1000500X1050_FLAT_Dual250V100nF |
| CAPMF_220n_100V_MPR | Capacitor THD MPR Film 220nF 5% 100V | CAPMF5_3.5-5.0-7.5mm |
| CAPMF_220n_63V | Capacitor, THT, metallized polyester | CAPMF7.5mm |
| CAPMF_22n_250V_MK | Capacitor THD MK Film 22nF 10% 250V | CAPMF12.5x4.5x9.0x10mmLS |
| CAPMF_3n3_400V_MPET | Capacitor THD Metallized PET Film 3.3nF 10% 400V | CAPMF5.0-7.5mm_SL |
| CAPMF_3n9_400V_MPET | Capacitor THD Metallized PET Film 3.9nF 10% 400V | CAPMF5.0-7.5mm_SL |
| CAPMF_470n_100V_MK | Capacitor THD MK Film 470nF 10% 100V | CAPR7.62-6.8x2.5 |
| CAPMF_47n_250V_MPET_TH | Capacitor THD Metallized PET Film 47nF 5% 250V | CAPM75P1000500X1050_FLAT_Dual250V100nF |
| CAPMF_82n_250V_MK | Capacitor THD MK Film 82nF 10% 250V | CAPMF12.5x4.5x9.0x10mmLS |
| CAPMKP_6n8_1kV_P10.0mm | Capacitor THT metallized polypropylene 6.8nF 5% 1kV 10.0mm pitch | CAPMF13.0x5.0x11.0x10.0mm LxWxHxP |
| CAPMKP_6n8_400V_P7.5mm | Capacitor THT metallized polypropylene 6.8nF 5% 400V 7.5mm pitch | CAPMF13.0x5.0x11.0x10.0mm LxWxHxP |
| CAPR_220n_Radial_5mm | Capacitor Ceramic 220nF 10% 50V X7R radial 5mm lead spacing | CAPC2012N |
| CAPT_100u_1210_6V3 | Capacitor SMD Tantalum 100uF 20% 6.3V 1210 | CAPMP3528X210N |
| CAPT_10u_0805_10V | Capacitor SMD Tantalum 10uF 20% 10V 0805 | CAPMP2012X150USR |
| CAPT_10u_6032_16V | Capacitor SMD Tantalum 10uF 20% 16V EIA 6032-28 | CAPMP6032X280N |
| CAPT_1u_0805_10V | Capacitor SMD Tantalum 1uF 20% 10V 0805 | CAPMP2012X150USR |
| CAPT_1u_6032_50V | Capacitor SMD Tantalum 1uF 10% 50V EIA 6032-28 | CAPMP6032X280N |
| CAPT_22u_3216_6V3 | Capacitor SMD Tantalum 22uF 10% 6.3V 3216-18 | CAPMP3216X180N |
| CAPT_330u_2917_6V3 | Capacitor SMD Tant 330uF 20% 6V3 2917 | CAPMP7343X310N |
| CAPT_33u_3216_6V3 | Capacitor SMD Tantalum 33uF 10% 6.3V 3216-18 | CAPMP3216X180N |
| CAPT_47u_1210_6V3 | Capacitor SMD Tantalum 47uF 20% 6.3V 1210 | CAPMP3528X210N |
| CAPT_47u_6032_16V | Capacitor SMD Tantalum 47uF 10% 16V 6032-28 | CAPMP6032X280N |
| CAPT_4u7_3216_16V | Capacitor SMD Tantalum 4.7uF 10% 16V 3216-18 | CAPMP3216X180N |
| CAPT_68u_3216_6V3 | Capacitor SMD Tantalum 68uF 10% 6.3V EIA 3216-18 | CAPMP3216X180N |


### Connectors

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| 10P_ScrewTerm | TERM BLOCK 10POS SIDE ENT 3.81MM | 10P_PCB_ScrewTerm |
| 12P_TERM PLUG_KEYENCE | Terminal Block Plug, 12-position, Keyence Laser Controller | |
| 2P_ScrewTerm_90S_3.81MM | Terminal Block Screw Type THT 2-Position 3.81mm pitch | 2P_PCB_ScrewTerm_90S_3.81MM |
| 2P_TERM_BLOCK_HEADER | Terminal Block THT 2-position header 3.81mm pitch | 2P_PCB_TERM_BLOCK_HDR |
| 2P_TERM_BLOCK_PLUG | Terminal Block Plug 2-position 3.81mm pitch | |
| 3P_TERM BLOCK HEADER | Terminal Block THT 3-Position header 3.81mm pitch | 3P_PCB_TERM_BLOCK_HDR |
| 3P_TERM BLOCK PLUG | Terminal block plug 3-position 3.81mm pitch | |
| 4P_TERM_BLOCK_PLUG | Terminal Block Plug 4-position 3.81mm pitch | |
| 4P_TERM_BLOCK_RA_HEADER | Terminal Block THT Right Angle 4-Position Header 3.81mm pitch | 4P_PCB_TERM_BLOCK_HDR_RA |
| 6P_HIROSE_HR10-7J-6P | Connector 6 jack with pin insert | HDR1X6S |
| 6P_HIROSE_HR10-7P-6S | Connector 6 contact with socket insert | HDR1X6 |
| 6P_RA_TERM BLOCK HEADER | Terminal Block THT Right Angle 6-Position Header 3.81mm pitch | 6P_PCB_TERM BLOCK HDR_RA |
| 6P_ScrewTerm_90S | TERM BLOCK 6POS SIDE ENT STACKABLE 5.08MM | 6P_PCB_ScrewTerm90S |
| 6P_ScrewTerm_90S_3.81MM | Terminal Block, THT, 6-Position screwterm, 3.81mm pitch | 6P_PCB_ScrewTerm_90S_3.81MM |
| 6P_TERM BLOCK HEADER | Terminal Block, THT, 6-Position header, 3.81mm pitch | 6P_PCB_TERM BLOCK HDR |
| 6P_TERM PLUG_284507-6 | Terminal Block Plug, 6-position, 3.81mm pitch | |
| 8P_ScrewTerm_90S_3.81MM | Terminal Block, THT, 8-Position screwterm, 3.81mm pitch | 8P_PCB_ScrewTerm_90S_3.81MM |
| 8P_TERM BLOCK HEADER | Terminal Block, THT, 8-Position header, 3.81mm pitch | 8P_PCB_TERM BLOCK HDR |
| 8P_TERM PLUG_284507-8 | Terminal Block Plug, 8-position, 3.81mm pitch | |
| CONN_5P_DIN-180_FEMALE | Connector DIN-180 5-Pin Female Plug | |
| CONN_AUDIOJACKMONO_3.5mm_RA_THD | 3.5mm Audio jack - Mono | CONN_AudioJackMono |
| CONN_AUDIOPLUGMONO_3.5mm_RA | 3.5mm Audio plug - Mono | |
| CONN_BANANA_TRIPLE | Banana Jack triple panel mount | BANANA_TRIPLE |
| CONN_BNC_FEM_50R | Connector BNC 50 Ohm right-angle PCB mounted | CONN_BNC_RA_PCB |
| CONN_DIN_4PIN | Connector Power THT 4-PIN DIN Female PCB mount | CONN_PWR-DIN_4PIN_PD-40S |
| CONN_HEADER_1x3P_0.100in | Pin Header, THT, Single-row, 2.54mm pitch | 1x3POS_HEADER |
| CONN_HEADER_2x5P_0.100in_Male | Header THD 10 POS Double-row 2.54mm pitch | 10P_PCB_HEADER_BRD_MNT |
| CONN_HEADER_2x8P_0.100in_Male | Header THD 16 POS Double-row 2.54mm pitch | 16P_PCB_HEADER_BRD_MNT |
| CONN_HEADER_2x8P_RA_0.100in_Male | Header THD 16 POS Right-angle Double-row 2.54mm pitch | 16P_PCB_HEADER_BRD_MNT_RA |
| CONN_HEADER_PLUG_1x1P_0.100in | Pin header for socket THT 1-Pos Low profile Single-row 2.54mm pitch | 1x1POS_HEADER_LOWPROF |
| CONN_HEADER_PLUG_1x3P_0.100in | Pin header for socket THT 3-Pos Low profile Single-row 2.54mm pitch | 1x3POS_HEADER_LOWPROF |
| CONN_JMP_RA | Connector Header 0.100in Right-angle single row | JMP2_RA |
| CONN_MICRO-CONX_PCB | Micro-Con-X Panel Mount Receptacle 2-pin PC Tail Contacts | CONN_JACK_MICRO-CONX |
| CONN_MINIPHONEJACK | Stereo phone jack mini | CONN_PhoneMiniStereo |
| CONN_PJ-036A | Connector SMD power jack 2.0mm x 6.3mm | CUI_PJ-036A-SMT |
| CONN_PLUG_2x8P_0.100in_Female | Ribbon cable socket 16 POS Double-row 2.54mm pitch | |
| CONN_POGO_1x7P_0.100in_RA | Connector spring pins 7-position 2.54mm pitch right-angle | CONN POGO 7POS RA 0.100IN |
| CONN_PWRDIN_4PIN-CUI | Connector Power THT 4-PIN DIN Female PCB mount | CONN_PWR-DIN_4PIN_PD-40S |
| CONN_PWR_JACK_0.7x2.35mm | Connector Power THT 0.7mm ID x 2.35mm OD | CONN_PWR_JACK_0.7x2.35mm |
| CONN_PWR_JACK_2.1x5.5mm | Power Connector, THT, 2.1mm ID, 5.5mm OD | CONN_PWR_JACK_2.1x5.5mm |
| CONN_PWR_PLUG_2.1x5.5mm | Power Plug Locking Type 2.1mm ID x 5.5mm OD | HDR_1x2_Power |
| CONN_RIBBON_IN-LINE_2x20P_0.050in | Socket Ribbon Cable 40 POS 1.27mm pitch | |
| CONN_SOCKET_1x1P_0.100in | Socket header THT 1-Pos Low profile Single-row 2.54mm pitch | 1x1POS_SOCKET_LOWPROF |
| CONN_SOCKET_1x3P_0.100in | Socket header THT 3-Pos Low profile Single-row 2.54mm pitch | 1x3POS_SOCKET_LOWPROF |
| CONN_SOCKET_2x17P_0.100in | Socket, THT, 34 POS, Double-row, 2.54mm pitch | 34P_PCB_SOCKET_BRD_MNT |
| CONN_SOCKET_2x25P_0.100in | Socket, THT, 50 POS, Double-row, 2.54mm pitch | 50P_PCB_SOCKET_BRD_MNT |
| CONN_SOCKET_2x3P_0.100in_Female | Socket THD 6 POS Double-row 2.54mm pitch | 6P_PCB_SOCKET_BRD_MNT_MICRO-MATCH |
| Header2P | Header, 2-pin | HDR_1x2_Offset |
| Header4P | Header 4-pin | HDR1X4_1.27mmp |
| Header5P | Header 5-pin | HDR1X5_1.27mmp |
| Header6P | Header, 6-pin | HDR1X6 |
| Header7P | Header, 7-pin | HDR1X7 |
| JUMP_2P_CONN_HEADER | Shorting Jumper, 2-position, 2.54mm pitch | |
| USB_Micro_TypeB | Connector SMD USB Micro Type B middle mount | USB_Micro-B_Molex_SMD |
| USB_Micro_TypeB_FCI | Connector SMD-THD USB Micro Type B middle mount | USB_Micro-B_FCI_SMD |
| USB_Mini-B | Connector SMD USB Type Mini-B | USB_Mini-B_Molex_SMT |
| USB_TypeB | Connector THT Type B USB connector | USB_TypeB_Tyco |


### Diodes

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| DIODE_100V_1.5A_SMA | Diode SMD 100V 1.5A SMA | DO-214AC, SMA |
| DIODE_100V_500mW_MELF | Diode SMD 100V 150mA 500mW SOD80 | SOD80, LL-34 |
| DIODE_1N4007_1000V_1.0A_DO-41 | Diode 1N4007 1A 1000V THD | DO-41 |
| DIODE_1N4148_200mA_SOD523F | Diode SMD small signal 0.2A SOD-523F | SOD523F |
| DIODE_75V_500mW | Diode SMD 300mA 0.5W SOD323 | SOD323 |
| DIODE_SCHOTTKY_10MQ100NPBF | Diode Schottky SMD 100V 2A SMA | DO-214AC, SMA |
| DIODE_SCHOTTKY_30BQ100TRPBF | Diode Schottky SMD 100V 3A SMC | DO-214AB, SMC |
| DIODE_SCHOTTKY_40V_1A | Diode Schottky SMD 40V 1A SOD123 | SOD123 |
| DIODE_SCHOTTKY_40V_30mA_SOD-523F | Diode Schottky SMD 40V 30mA SOD-523F | SOD523F |
| DIODE_SCHOTTKY_MBRS130L | Diode Schottky SMD 30V 2A DO-214AA | DO-214AA |
| DIODE_SCHOTTKY_SS0520 | Diode Schottky SMD 20V 0.5A SOD123 | SOD123 |
| DIODE_ZENER_12V_200mW_SOD523F | Diode SMD Zener 12V 0.2W SOD-523F | SOD523F |
| DIODE_ZENER_28V_500mW | Diode Zener SMD 28V 0.5W SOD-123 | SOD123 |
| DIODE_ZENER_3V3_SOD323 | Diode Zener SMD 3.3V 200mW SOD-323 | SOD323 |
| DIODE_ZENER_4.7V_500mW | Diode Zener SMD 4.7V 0.5W SOD-123 | SOD123 |


### Electromechanical

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| BZ_12x8.5x6.5_2kHz | Speaker, Magnetic Transducer | BUZZER_12.0X8.5MM |
| BZ_12x9.0x6.5mm_sealed | Buzzer THD sealed 12.0 x 9.0mm DxH 6.5mm pitch | BUZZER_12.0X8.5MM |
| FX2-D3209 | TYCO ELECTRONICS - FX2-D3209 - RELAY, PCB, DPCO, 5VDC | Relay_Tyco_FX2 |
| RELAY_AC_INPUT_MODULE | | |
| Relay_FP2-D3023 | Relay, THT, Low-profile, DPDT DPCO Telecom, 5VDC | Relay_Tyco_FP2 |
| Relay_IM48DGR | Relay SMD Telecom DPDT latching 2.4VDC | Relay_TE_IM-Series_Gull |
| Relay_V23026A1001B201 | Relay, PCB Mount, SPDT, Polarized Monostable | |
| Relay_V23079A1001B301 | Relay, PCB Mount, DPDT, Polarized Monostable | Relay_Tyco_P2 |
| SENS_OPTO_LIQUID_OPB350W250Z | Sensor, Photointerrupter, Liquid, 0.250" | |
| SOLENOID_PUSH_12VDC_1in_80oz | Solenoid, Linear, Continuous, 12VDC, Push, 1" @ 5 lbs. | |


### Fuses and Protection

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| BREAKER_4A5_ETA_1410-L2 | Circuit breaker 4.5A PCB mount | BREAKER_1410-L2 |
| ESD_SUPPRESSOR_24VDC | ESD Suppressor 24VDC 0603 SMD | 0603ESDA |
| FUSE_160mA_0603 | Fuse 160mA 63VDC 0603 SMD | RESC1608N |
| FUSE_160mA_1206 | Fuse 160mA 63VDC 1206 SMD | RESC3216N |
| FUSE_200mA_Bussman-SR-5-BK | Fuse 200mA 250VAC Radial 5.08mm pitch | FUSE_SR-5-BK |
| FUSE_FAST_500mA_0603 | Fuse 500mA 32VDC 0603 SMD | RESC1608N |
| SPARKGAP_2850V | Fuse 160mA 63VDC 1206 SMD | Spark-Gap_2850V |
| TCO_Axial | Thermal cutoff axial 2 Amp 130 deg C | AUPO_P-4F_BEND1 |
| TCO_Radial_115degC | Thermal cutoff radial 1 Amp 115 degrees C | TCO_Aupo_Ax-1A_Radial_THD |
| TCO_Radial_130degC | Thermal cutoff radial 1 Amp 130 degrees C | |
| Varistor_MOV | Varistor 420V min | Varistor_7.62and10mm |


### Inductors

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| FERRITE_120R-100MHz_0603 | Ferrite bead 120 Ohm at 100 MHz 2A 0603 SMD | INDC1608N |
| FERRITE_2K2-100MHz_0805 | Ferrite bead 2.2K Ohm at 100 MHz 200mA 0805 SMD | FBC2012N |
| FERRITE_600R-100MHz_0805 | Ferrite bead 600 Ohm at 100 MHz 200mA 0805 SMD | FBC2012N |
| INDC_10u_DR73-100-R | Inductor Power 10?H 2.1A 7.6x7.6mm SMD | IND_WW_DR73 |
| INDC_10u_LowRDC | Inductor SMD Low DCR 10 ?H 900mA 20% 1210 | INDC3225X250N |
| INDC_120u_LPS4018 | Inductor shielded 120uH 300mA LPS4018 SMD | IND_COILCRAFT_LPS4018 |
| INDC_150n_1008 | Inductor SMD chip 150nH 1008 | INDM2520X190N |
| INDC_180u_Toroid | Power Inductor 180?H 10% SMD Toroid | IND_SMD_TOROID_1.2x1.0in |
| INDC_22u_DO3316P-223 | Inductor Power SMD 22?H | IND_Coilcraft_DO3316P_SM |
| INDC_47n_1008_1A | Inductor SMD chip 47nH 1008 | INDM2520X190N |


### Integrated Circuits

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| DAC_MCP4921 | IC DAC 12-bit SPI 8-SOIC | SOIC127P600X175-8AN |
| EEPROM_24AA00 | EEPROM 128BIT 400KHZ SOT23-5 | SOT23-5 |
| EEPROM_CAT93C46YI-G | EEPROM 1KBIT 2MHZ 8-TSSOP | TSSOP65P640X120-8N |
| FT2232D | Dual USB UART/FIFO Chip, LQFP-48 | LQFP-48_N |
| IC_3INPUTAND_HEF4073B | IC SMD Triple 3-input AND SOIC-14 | SOIC127P600X175-14AN |
| IC_COMP_2CH_LMC6762 | IC Dual Rail-Rail PP Comparator SOIC-8 SMD | SOIC127P600X175-8AN |
| IC_Comparator_AD790 | IC SMD Voltage Comparator SOIC-8 | SOIC127P600X175-8AN |
| IC_Comparator_LT1011 | IC SMD Voltage Comparator SOIC-8 | SOIC127P600X175-8AN |
| IC_FLIP-FLOP_D-Type_74LVC74 | IC Flip-Flop D-type TSSOP-8 SMD | TSSOP65P400X110-8N |
| IC_FLIP-FLOP_JK-Type_74HCT109D | IC Flip-Flop JK-type SOIC-16 SMD | SOIC127P600X175-16AN |
| IC_FULL-BRIDGEDRIVER_A4940_| 24-pin TSSOP Automotive Full Bridge MOSFET Driver | SOP65P640X110-25N |
| IC_INVERTER_74AHC1GU04 | IC Inverter SOT353 SMD | SOT353 |
| IC_Op-Amp_AD8512 | IC SMD Low Cost Op Amp SOIC-8 | SOIC127P600X175-8AN |
| IC_Op-Amp_AD8513 | IC Op Amp JFET 8MHz Quad TSSOP-14 SMD | TSSOP65P640X120-14N |
| IC_Op-Amp_LT1077 | IC SMD Op Amp Precision Micropower SOIC-8 | SOIC127P600X175-8AN |
| IC_QUADCOMPAR_TLC3704 | IC SMD Quad Comparator SOIC-14 | SOIC127P600X175-14AN |
| IC_QUADNAND_MC74HC00 | IC SMD Quad NAND SOIC-14 | SOIC127P600X175-14AN |
| IC_TIMER_555 | IC CMOS 555 Timer SOIC-8 SMD | SOIC127P600X175-8AN |
| INVERTER_HEX_LOGIC | Inverter IC Logic-level 6 section SOP-14 SMD | SOIC127P780X200-14N |
| LM3S811_QFP48 | IC ARM Cortex Microcontroller 64KB flash LQFP-48 SMD | LQFP-48_N |
| MAX4561 | IC SMD Analog Switch SOT23-6 | SOT23-6 |
| RFID_CR95HF | IC RFID Reader 13.56MHz CR95HF | QFN50P500X500X100-33N |
| ZXSC310 | LED Driver IC SMD SOT23-5 | SOT23-5 |
| ?PD78F0500MC | IC SMD NEC 8-Bit Single-Chip Microcontroller | SOP65P810X120-30N |
| ?PD78F0501AMC    | IC SMD Renesas 8-Bit Single-Chip Microcontroller 16KB flash | SOP65P810X120-30N |


### Light Sources

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| LEDPACK_GREEN_3HIGH_3MM | LED array PCB mount 3-high 3mm green | LED_3-HIGH_3MM |
| LED_Blue_GullWing | LED, Gull-wing SMD, High-intensity blue | LED_GULL1 |
| LED_Green_GullWing | LED Gull-wing SMD High-intensity Green 450mcd 574nm | LED_GULL1 |
| LED_RED_10MM_PanelMount | | |
| LED_SMD_Blue_0805_100mcd | LED 0805 SMD Blue 100mcd 470nm | LED-0805-K |
| LED_SMD_BrightWhite_0805RA_500mcd | LED 0805 SIDELED SMD Bright White ~500mcd 20mA | LED-0805S-SIDELED-2.1x0.6x1.0 |
| LED_SMD_Green_0805 | LED, 0805 SMD, Green | LED-0805-K |
| LED_SMD_Green_0805_12mcd | LED 0805 SMD Green 12mcd 569nm | LED-0805-K |
| LED_SMD_Green_0805_6mcd | LED, 0805 SMD, Green | LED-0805-K |
| LED_SMD_Green_0805_8mcd | LED, 0805 SMD, Green | LED-0805-K |
| LED_SMD_Orange_0805_125mcd | LED, 0805 SMD, Orange | LED-0805-K |
| LED_SMD_PureGreen_0805RA_250mcd | LED 0805 SIDELED SMD Green 250mcd 525nm | LED-0805S-SIDELED-2.1x0.6x1.0 |
| LED_SMD_RED_0805RA_250mcd | LED SMD SIDELED Red 630nm 250mcd 0805 | LED-0805S-SIDELED-2.1x0.6x1.0 |
| LED_SMD_Red_0603_220mcd | LED 0603 SMD Hyper Red 630nm 220mcd 20mA | LED-0603-RED |
| LED_SMD_Red_0805 | LED, 0805 SMD, Red | LED-0805-A |
| LED_SMD_Red_0805_6mcd | LED 0805 SMD Red 6mcd 621nm | LED-0805-K |
| LED_SMD_White_0603_109mcd | LED 0603 SMD White 8700K 108.5mcd 5mA | LED-0603-WHITE |
| LED_SMD_Yellow_0603_150mcd | LED 0603 SMD Yellow 590nm 150mcd 20mA | LED-0603-YELLOW |


### Mechanical

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| BANANAJACK_PANEL_BLACK | Banana jack panel mount black | |
| BANANAJACK_PANEL_RED | Banana jack panel mount red | |
| Cable_3811-16-100 | Ribbon cable 26 AWG 16-conductor 1.27mm pitch | |
| Cable_C0744A-12-10 | Cable, SHIELDED 24AWG UL2464 8 COND | ClarisonicLogo |
| Enclosure_KEU-10 | Enclosure with keyboard panel 8.1x10.1x4.0in | |
| Enclosure_KEU-7 | Enclosure with keyboard panel 5.1x7.1x3.0in | |
| FAN_TUBEAXIAL_12VDC_40x20mm | Fan tubeaxial 40x20mm 7.7 CFM 21 dBA 12 VDC | |
| HEATSINK_SMD_TO-268 | Heat sink for TO-268 SMD | HEATSINK_TO-268 |
| KNOB_0.25in_round-shaft_knurled-metal | Knob metal 0.25in diameter clear matte | |
| KNOB_SHAFT-0.25in_DIAM-0.7",","Knob - Black | Knob plastic 0.125in diameter black | |
| NUT_M3x5.5mm | NUT HEX METRIC M 3 ZINC | |
| SCREW_M3x8mm_Philips_Panhead | SCREW MACHINE METRIC PH M3X8MM | |
| SHIELD_RECT_0.75x1.125x0.25in | Fotofab standard RF shield 0.75x1.125x0.25in | SHIELD_RECT_0.75x1.125x0.25in |
| STANDOFF_F-F_THREADED_M3x15mm_5mm dia | STANDOFF METRIC HEX M3 THD 15MM | |
| STANDOFF_M-F_THREADED_M3x8x10mm_HEX_5mm dia | STANDOFF M/F MET 5MM HEX 10MM L | |
| WASHER_LOCK_SPLIT_M3 size | WASHER SPLIT LOCK METRIC M 3 ZINC | |
| mech_3100-002 | Ferrite Core Toroid | |
| mech_knob_0.125x0.250in | Knob plastic 0.125in diameter black | |
| mech_labelsticker-rotary | Label sticker for rotary switch | |


### Optical Components

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| ENCODER_OPT_0.25in shaft_with cable | Encoder optical rotary panel mount no pushbutton | |
| LCD_20x4 | LCD character display module 20x4 | |
| PHOTODIODE_BPW34 | Photodiode 30V 50?A TO-5 | HDR_Photodiode_TO-5 |
| PHOTOTRANS_SD5443-3 | Transistor Photo 30V 8mA 150mW TO-46 | HDR_Phototrans_TO-46 |


### Pads and Jumpers

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| JUMP1 | SMD jumper | JUMP1 |
| JUMP2 | SMD jumper | JUMP2 |
| JUMP_3WAY | SMD jumper | Jump_3Way |
| JUMP_NETTIE | Net Tie | NetTie_Internal1_24mil |
| MH_Plated_112mil | | MH_PLATED_112 ID x 260mil OD |
| MH_Plated_125mil | | MH_PLATED_125 ID x 260mil OD |
| MH_Plated_150mil | | MH_PLATED_150ID x 220mil OD |
| MH_Plated_40mil | | MH_PLATED_40mil ID x 100mil OD |
| Proto_Block_25x51 | | BreadBoard_25x51 |
| Proto_Block_8x2 | DAQ breakout section | Breakout_8x2 |
| Term1 | | THP_D38_T75_B125 |
| Term_small | | THP_D38_T75_B75 |


### Power Supplies

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| PSU_24VDC_2.1x5.5mm plug | Power Supply 24VDC 2.5A 2.1mm ID x 5.5mm OD plug | |
| PSU_48VDC_4-PIN_DIN | Power Supply 48VDC 100W 4-pin DIN plug | |
| PSU_USB_TypeA_5VDC_1.0A | Power supply wall wart USB Type A 5W | |
| TRANS_WALL_MNT_12VDC_1.25A | Transformer, Wall-Mount, 12VDC | |
| TRANS_WALL_MNT_5VDC_2.6A | Transformer, Wall-Mount, 5VDC | |


### Regulators

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| ADJREG_2A_XRP2997 | IC Adjustable Regulator 2A 8-SOIC-EP SMD | SOIC127P600X175-9N |
| LM317D2TG | Voltage Regulator IC, D2PAK SMD, LM317D2TG | D2PAK-3 |
| LM317MBDTG | Voltage Regulator IC, DPAK SMD, LM317MBDTG | TO-252 |
| LinREG_3V3_400mA_TPS73633DBV | IC LDO Regulator 3.3V 400mA SOT23-5 SMD | SOT23-5 |
| REGULATOR_LM2591HVS-5.0 | Switching Voltage Regulator IC, TO-263-5 SMD, LM2591HVS-5.0 | TO-263-5 |
| SwiREG_-5V_200mA_| IC REG 200mA -5V SOIC-8 SMD | SOIC127P600X175-8AN |
| VREG_1.25V_MAX6101EUR | Voltage Regulator 1.25V SOT23-3 SMD | SOT23-3 |
| VREG_3V3_Boost | Regulator 3.3V Step-Up Converter | SOT23-5 |
| VREG_5V_Boost | Regulator, VFM Step-Up DC/DC Converter | SOT23-5 |
| VREG_5V_Buck_LMZ23610 | Voltage Regulator 10A 5V TO-PMOD-11 | NATIONALSEMI-TZA11A |
| VREG_ADJ_Buck_ADP2300 | Regulator adjustable switching step-down DC/DC converter | SOT23-6 |


### Resistors

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| RESPACK_100R_5%_4X | Resistor array 100 Ohm 4-pack 62.5mW 5% 1206 SMD | RESCAXS50P160X320X70-8N |
| RESPACK_10K_5%_4X | Resistor array 10K Ohm 4-pack 62.5mW 5% 1608 SMD | RESCAXS50P160X320X70-8N |
| RESPACK_10K_5%_8X | Resistor array 10K Ohm 8-pack 62.5mW 5% 1608 SMD | RESP4021N8X |
| RESPACK_1K_5%_4X | Resistor array 1K Ohm 4-pack 62.5mW 5% 1608 SMD | RESCAXS50P160X320X70-8N |
| RESPACK_2K2_5%_4X | Resistor array 2.2K Ohm 4-pack 62.5mW 5% 1608 SMD | RESCAXS50P160X320X70-8N |
| RESPACK_39R_5%_4X | Resistor array 39 Ohm 4-pack 62.5mW 5% 1206 SMD | RESCAXS50P160X320X70-8N |
| RES_0R022_1206_0.5W_2% | Resistor SMD chip 22 milliohm 0.5W 2% 1206 | RESC3216N |
| RES_0R_0603 | Resistor SMD chip 0.0 Ohm 0.1W 0603 | RESC1608N_ZERO |
| RES_0R_0805 | Resistor SMD chip 0.0 Ohm 0.125W 0805 | RESC2012N_ZERO |
| RES_0R_1206 | Resistor SMD chip 0.0 Ohm 0.25W 1206 | RESC3216N_ZERO |
| RES_0R_Axial_0.25W | Resistor THD 0.0 Ohm 0.25W Jumper | RESTH_0.0R_AXIAL-0.6 |
| RES_100K_0603_1% | Resistor SMD chip 100k Ohm 0.1W 1% 0603 | RESC1608N |
| RES_100K_0805_1% | Resistor SMD chip 100k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_100R_0603_1% | Resistor SMD chip 100 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_100R_0805_1% | Resistor SMD chip 100 Ohm 0.125W 1% 0805 | RESC2012N |
| RES_100R_1206_5% | Resistor SMD chip 100 Ohm 0.25W 5% 1206 | RESC3216N |
| RES_10K2_0603_1% | Resistor SMD chip 10.2K Ohm 0.1W 1% 0603 | RESC1608N |
| RES_10K_0402_1% | Resistor SMD chip 10k Ohm 0.063W 1% 0402 | RESC1005N |
| RES_10K_0603_1% | Resistor SMD chip 10k Ohm 0.1W 1% 0603 | RESC1608N |
| RES_10K_0603_5% | Resistor SMD chip 10k Ohm 0.1W 5% 0603 | RESC1608N |
| RES_10K_0805_1% | Resistor SMD chip 10k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_10K_0805_5% | Resistor SMD chip 10k Ohm 0.125W 5% 0805 | RESC2012N |
| RES_10R_0805_5% | Resistor SMD chip 10 Ohm 0.125W 5% 0805 | RESC2012N |
| RES_10R_1206_5% | Resistor SMD chip 10 Ohm 0.25W 5% 1206 | RESC3216N |
| RES_10R_1210_1% | Resistor SMD chip 10 Ohm 0.5W 1% 1210 | RESC3225N |
| RES_10R_Axial_10W_1% | Resistor THD 10 Ohm 10W 1% Wirewound | RESTH_AXIAL_RS010 |
| RES_10R_Axial_1W_5% | Resistor THD 10 Ohm 1W 5% Metal Film | AXIAL-0.6 |
| RES_110K_0402_1% | Resistor SMD chip 110k Ohm 0.063W 1% 0402 | RESC1005N |
| RES_120R_0603_5% | Resistor SMD chip 120 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_12K_Axial_0.25W_5% | Resistor THD Axial 12k Ohm 0.25W 5% Carbon Film | RESTH_AXIAL-0.4 |
| RES_143R_0603_1% | Resistor SMD chip 143 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_150R_0805_5% | Resistor SMD chip 150 Ohm 0.125W 5% 0805 | RESC2012N |
| RES_150R_1206_5% | Resistor SMD chip 150 Ohm 0.25W 5% 1206 | RESC3216N |
| RES_15K_0402_1% | Resistor SMD chip 15k Ohm 0.063W 1% 0402 | RESC1005N |
| RES_15K_0603_1% | Resistor SMD chip 15k Ohm 0.1W 1% 0603 | RESC1608N |
| RES_15K_0805_1% | Resistor SMD chip 15k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_160K_0805_1% | Resistor SMD chip 160k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_180R_0603_5% | Resistor SMD chip 180 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_1K07_0805_1% | Resistor SMD chip 1.07K Ohm 0.125W 1% 0805 | RESC2012N |
| RES_1K3_0805_1% | Resistor SMD chip 1.3k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_1K5_0603_5% | Resistor SMD chip 1.5k Ohm 0.1W 5% 0603 | RESC1608N |
| RES_1K5_0805_1% | Resistor SMD chip 1.5k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_1K5_Axial_0.5W_5% | Resistor THD Axial 1.5k Ohm 0.5W 5% Carbon Film | RESTH_AXIAL-0.4 |
| RES_1K8_0805_1% | Resistor SMD chip 1.8k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_1K_0603_1% | Resistor SMD chip 1k Ohm 0.1W 1% 0603 | RESC1608N |
| RES_1K_0603_5% | Resistor SMD chip 1k Ohm 0.1W 5% 0603 | RESC1608N |
| RES_1K_0805_1% | Resistor SMD chip 1k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_1K_Axial_0.25W_5% | Resistor THD Axial 1k Ohm 0.25W 5% Carbon Film | RESTH_AXIAL-0.4 |
| RES_1M_0402_5% | Resistor SMD chip 1M Ohm 0.063W 5% 0402 | RESC1005N |
| RES_1M_0603_5% | Resistor SMD chip 1M Ohm 0.1W 5% 0603 | RESC1608N |
| RES_1M_0805_5% | Resistor SMD chip 1M Ohm 0.125W 5% 0805 | RESC2012N |
| RES_1R_1206_1% | Resistor SMD chip 1 Ohm 250mW 1% 1206 | RESC3216N |
| RES_1R_2010_1% | Resistor SMD chip 1 Ohm 1W 1% 2010 | RESC5025N |
| RES_200R_0805_1% | Resistor SMD chip 200 Ohm 0.125W 1% 0805 | RESC2012N |
| RES_205K_0805_1% | Resistor SMD chip 205k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_20R_1206_0.5W_1% | Resistor SMD chip 20 Ohm 0.5W 1% 1206 | RESC3216N |
| RES_20R_1206_5% | Resistor SMD chip 20 Ohm 0.25W 5% 1206 | RESC3216N |
| RES_220R_0603_5% | Resistor SMD chip 220 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_220R_Axial_0.25W_5% | Resistor THD Axial 220 Ohm 0.25W 5% Carbon Film | RESTH_AXIAL-0.4 |
| RES_22R_0603_5% | Resistor SMD chip 22 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_240R_0805_1% | Resistor SMD chip 240 Ohm 0.125W 1% 0805 | RESC2012N |
| RES_27K4_0805_1% | Resistor SMD chip 27.4k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_27K_0805_1% | Resistor SMD chip 27.0k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_280R_0603_1% | Resistor SMD chip 280 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_2K2_0402_5% | Resistor SMD chip 2.2k Ohm 0.063W 5% 0402 | RESC1005N |
| RES_2K2_0603_5% | Resistor SMD chip 2.2k Ohm 0.1W 5% 0603 | RESC1608N |
| RES_2K2_0805_1% | Resistor SMD chip 2.2k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_2K8_0805_1% | Resistor SMD chip 2.8k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_2R2_1210_5% | Resistor SMD chip 2.2 Ohm 0.5W 5% 1210 | RESC3225N |
| RES_2R4_1210_5% | Resistor SMD chip 2.4 Ohm 0.5W 5% 1210 | RESC3225N |
| RES_31K6_0603_1% | Resistor SMD chip 31.6k Ohm 0.1W 1% 0603 | RESC1608N |
| RES_330R_0402_5% | Resistor SMD chip 330 Ohm 0.063W 5% 0402 | RESC1005N |
| RES_330R_0603_5% | Resistor SMD chip 330 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_348K_0805_1% | Resistor SMD chip 348k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_348R_0603_1% | Resistor SMD chip 348 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_36K5_0805_1% | Resistor SMD chip 36.5k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_39R_0603_5% | Resistor SMD chip 39 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_3K3_0402_5% | Resistor SMD chip 3.3k Ohm 0.063W 5% 0402 | RESC1005N |
| RES_3K3_0603_5% | Resistor SMD chip 3.3k Ohm 0.1W 5% 0603 | RESC1608N |
| RES_3K3_0805_1% | Resistor SMD chip 3.3k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_3K3_2512_5% | Resistor SMD chip 3.3k Ohm 1W 5% 2512 | RESC6332N |
| RES_3R3_0603_5% | Resistor SMD chip 3.3 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_422R_0603_1% | Resistor SMD chip 422 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_44K2_0805_1% | Resistor SMD chip 44.2k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_453R_0603_1% | Resistor SMD chip 453 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_470R_0603_5% | Resistor SMD chip 470 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_47R_1206_5% | Resistor SMD chip 47 Ohm 0.25W 5% 1206 | RESC3216N |
| RES_4K7_0603_5% | Resistor SMD chip 4.7k Ohm 0.1W 5% 0603 | RESC1608N |
| RES_4K7_0805_1% | Resistor SMD chip 4.7k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_4K7_0805_5% | Resistor SMD chip 4.7k Ohm 0.125W 5% 0805 | RESC2012N |
| RES_510R_0603_1% | Resistor SMD chip 510 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_510R_0805_1% | Resistor SMD chip 510 Ohm 0.125W 1% 0805 | RESC2012N |
| RES_51K_0603_1% | Resistor SMD chip 51k Ohm 0.1W 1% 0603 | RESC1608N |
| RES_51K_0805_1% | Resistor SMD chip 51k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_51K_Axial_0.25W_5% | Resistor THD Axial 51k Ohm 0.25W 5% Carbon Film | RESTH_AXIAL-0.4 |
| RES_51R_0603_1% | Resistor SMD chip 51 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_51R_1206_1% | Resistor SMD chip 51 Ohm 0.25W 1% 1206 | RESC3216N |
| RES_52K3_0603_1% | Resistor SMD chip 52.3K Ohm 0.1W 1% 0603 | RESC1608N |
| RES_560R_0603_1% | Resistor SMD chip 560 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_5R_Axial_3W_1% | Resistor THD 5 Ohm 3W 1% Wirewound | RESTH_AXIAL_RS02B |
| RES_63K4_0603_1% | Resistor SMD chip 63.4K Ohm 0.1W 1% 0603 | RESC1608N |
| RES_68R_0603_5% | Resistor SMD chip 68 Ohm 0.1W 5% 0603 | RESC1608N |
| RES_6K34_0603_1% | Resistor SMD chip 6.34k Ohm 0.1W 1% 0603 | RESC1608N |
| RES_6K49_0805_1% | Resistor SMD chip 6.49k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_6K65_0603_1% | Resistor SMD chip 6.65k Ohm 0.1W 1% 0603 | RESC1608N |
| RES_6R8_1206_5% | Resistor SMD chip 6.8 Ohm 0.25W 5% 1206 | RESC3216N |
| RES_768R_0603_1% | Resistor SMD chip 768 Ohm 0.1W 1% 0603 | RESC1608N |
| RES_7K87_0805_1% | Resistor SMD chip 7.87k Ohm 0.125W 1% 0805 | RESC2012N |
| RES_86R6_0805_1% | Resistor SMD chip 86.6 Ohm 0.125W 1% 0805 | RESC2012N |
| RES_8R2_1206_0.25W_5% | Resistor SMD chip 8.2 Ohm 0.25W 5% 1206 | RESC3216N |
| RES_91R_1206_5% | Resistor SMD chip 91 Ohm 0.25W 5% 1206 | RESC3216N |
| RES_953R_0805_1% | Resistor SMD chip 953 Ohm 0.125W 1% 0805 | RESC2012N |
| RES_EMPTY_0603 | Resistor, 08603 SMD, Empty footprint | RESC1608N |
| RES_EMPTY_0805 | Resistor, 0805 SMD, Empty footprint | RESC2012N |
| RES_EMPTY_1206 | Resistor, 1206 SMD, Empty footprint | RESC3216N |
| RES_NL_0603 | Resistor, SMD chip | RESC1608N |
| RES_NL_0805 | Resistor, SMD chip | RESC2012N |
| RES_NL_1206 | Resistor, SMD chip | RESC3216N |
| RES_NL_2010 | Resistor, SMD chip | RESC5025N |
| RES_TRIMMER_10K_10T_PNL | Trimmer panel mount 10K 2W 10-turn | |
| RES_TRIMMER_10K_1T_THT | Trimmer THD 10K 200mW Single-turn | POT_3306F |
| RES_TRIMMER_10K_25T_THT | Trimmer THD 10K 500mW 25-turn | TRIMPOT_THT_PV36X |
| RES_TRIMMER_10K_5T_SMD | Trimmer SMD 10K 250mW 5-turn Side-adjust | TrimPot_SMD_Bourns_3214G |
| RES_TRIMMER_1K_24T_THD | Trimmer, 24-Turn, 1K | VishaySpectrol_64Y |
| RES_TRIMMER_1K_25T_THT | Trimmer, 25-Turn, 1K cermet | TrimPot_THT_2.54mm pitch |
| RES_TRIMMER_20K_25T_THT | Trimmer THD 20K 500mW 25-turn | TrimPot_THT_PV36X |
| RES_TRIMMER_2K_25T_THT | Trimmer THD 2K 500mW 25-turn | TrimPot_THT_PV36X |


## Resonators

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| CRYSTAL_27M12 | Oscillator Crystal 27.12 MHz 10ppm | CRYSTAL_4-LCC |
| Crystal_6MHz_CMR309T | Resonator Ceramic 6.00 MHz 30ppm | CRYSTAL_CMR309T |
| Crystal_6MHz_HC49/US | Resonator Ceramic 6.00 MHz 30ppm | CRYSTAL_HC49-US-SM |
| Resonator_Ceramic | Resonator Ceramic 4.91 MHz 0.5% | RESON_CER_SMD |


### Switches

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| MRF403-RO | SW ROTARY 4P 2-3POS PC | SW_MRF403 |
| SW_EVQ-PQHB55 | SWITCH TACTILE SPST-NO 0.02A 15V | SWITCH_TACT-EVQPQxB55 |
| SW_PB_SPST-NO_Off-Mom_WireLeads | Switch wire leads momentary SPST | SWITCH_DPDT_RA_7201K2A |
| SW_PB_SPST-NO_Off-Mom_WireLeads_Snap-In | Switch momentary SPST panel mount with wire leads | HDR_1x2_Generic |
| SW_SMD_PB_4.3mm | Switch SMD Tact 4.3mm Stem | TS-1143S |
| SW_SMD_PB_7.0mm | Switch SMD Tact 7.0mm Stem | TS-1170S |
| SW_THD_DPDT_Mom-Off-Mom | Switch THD toggle momentary DPDT | SWITCH_DPDT_M2 |
| SW_THD_RA_DPDT_On-On | Switch THD right-angle toggle DPDT | SWITCH_DPDT_RA_7201K2A |
| SW_THD_SP10T_Rotary_2-deck | Switch THD rotary SP10T 2-deck | SWITCH_ROTARY_SP10T |
| SW_THD_SPDT_On-On | Switch THD vertical toggle SPDT | SWITCH_SPDT_SLIDER |
| SW_THT_PB_4.3mm | Switch, tact, 4.3mm stem | TACT-SWITCH-TS1143 |
| SW_THT_PB_5.0mm | Switch, tact, 5.0mm stem | TACT-SWITCH-TC-37XB |
| SW_THT_PB_7.0mm | Switch, tact, 7.0mm stem | TACT-SWITCH-TS1170 |
| SW_THT_PB_8.0mm | Switch Tact THD 8.0mm Stem | TACT-SWITCH-TS1180 |


### Test Points

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| TESTPOINT | SMD test pin | TP |
| TESTPOINT_LEAD | TEST POINT | THP_D46_T80_B80 |
| TESTPOINT_THT | Test Point PCB mount Multi-purpose Yellow | TP-THT-MULTI |
| TESTPOINT_THT_MINI | Test Point PCB mount Miniature White | TP-THT-MINI |


### Transistors

| LIBRARYREFERENCE | DESCRIPTION | FOOTPRINT1 |
|:-----------------|:------------|:-----------|
| MOSFET_AO4420 | MOSFET N-CH 30V 13.7A SOIC-8 SMD | SOIC127P600X175-8AN |
| MOSFET_AO4806 | MOSFET Dual-Channel 20V 9.4A SOIC-8 SMD | SOIC127P600X175-8AN |
| MOSFET_AO4818B | MOSFET Dual-Channel 30V 8.5A SOIC-8 SMD | SOIC127P600X175-8AN |
| MOSFET_AO9926B | MOSFET SMD Dual-Channel 20V 7.6A SOIC-8 | SOIC127P600X175-8AN |
| MOSFET_BSS123 | MOSFET SMD N-CH 100V 170mA SOT23-3 | SOT23-3 |
| MOSFET_BSS84 | MOSFET SMD P-CH 50V 130mA SOT23-3 | SOT23-3 |
| MOSFET_DUAL_N+P_DMG1016 | MOSFET Dual Enh N+P 20V 330mW SOT363 SMD | SOT363 |
| MOSFET_FDG332PZ | MOSFET SMD P-CH 20V 2.6A SC70-6 | SC70-6 |
| MOSFET_H-BRIDGE_ZXMHC6A07N8 | MOSFET H-Bridge 2N 2P SOIC-8 SMD | SOIC127P600X175-8AN |
| MOSFET_N-CHAN_RJK0331DPB | MOSFET N-Channel Power Switching 30V 40A LFPAK SMD | LFPAK |
| MOSFET_RZR025P01TL | MOSFET SMD P-CH 12V 2.5A 1W SOT23-3 | SOT23-3 |
| NPN_BC337-25 | Transistor, THT, NPN | |
| NPN_FMMT617TA | Transistor SMD NPN 15V 3A SOT-23 | SOT23-3 |
| NPN_KSP2222A | Transistor SMD NPN 40V 0.6A 625mW TO-92 | TO-92_Flat |
| NPN_KSP44 | Transistor THD NPN 400V 300mA 625mW TO-92 | TO-92_Flat |
| NPN_MMBT2222A | Transistor SMD NPN 40V 600mA 250mW SOT23-3 | SOT23-3 |
| NPN_MMBT3904 | Transistor SMD NPN 40V 0.2A 350mW SOT-23 | SOT23-3 |
| NPN_MMBT3906 | Transistor SMD PNP 40V 0.2A 350mW SOT-23 | SOT23-3 |
| PNP_NSS60600MZ4T1G | Transistor SMD PNP 60V 6A 800mW SOT-223 | SOT223 |


## Footprints

### SMD Packages

| 0603ESDA |
|:---------|
| CAP_ELEC_5x5.7 |
| CAP_ELEC_6.3x4.2 |
| CAP_ELEC_SIZE_E |
| CAP_ELEC_SIZE_G |
| CAP_ELEC_SIZE_H13 |
| CAPC1005N |
| CAPC1608N |
| CAPC1608N_F |
| CAPC2012N |
| CAPC2012N_F |
| CAPC3216N |
| CAPC3225N |
| CAPC4532N |
| CAPC5750N |
| CAPMP2012X150USR |
| CAPMP3216X180N |
| CAPMP3528X210N |
| CAPMP6032X280N |
| CAPMP7343X310N |
| CHOKE_CM_1206SMD |
| CRYSTAL_4-LCC |
| CRYSTAL_CMR309T |
| CRYSTAL_HC49-US-SM |
| CRYSTAL_NX2520SA |
| D2PAK-3 |
| Diode, NSR1020MW2T1G |
| DO-214AA |
| DO-214AB |
| DO-214AC |
| FBC2012N |
| HDR_1x2_SMT |
| IND_Coilcraft_DO3316P_SM |
| IND_COILCRAFT_LPS4018 |
| IND_SMD_TOROID_1.2x1.0in |
| IND_WW_DR73 |
| INDC1608N |
| INDC3225X250N |
| INDM3225X240N |
| Jump_3Way |
| Jump_3Way_Text1 |
| Jump1 |
| Jump2 |
| LED_GULL1 |
| LED-0603 |
| LED-0603-BLUE |
| LED-0603-GREEN |
| LED-0603-RED |
| LED-0603-WHITE |
| LED-0603-YELLOW |
| LED-0805-A |
| LED-0805-K |
| LED-0805S-SIDELED-2.1x0.6x1.0 |
| LED-1208-SIDELED-LTST |
| LED-PLCC-SIDELED-LTST-108 |
| LFPAK |
| LQFP-48_N |
| LQFP50P1200X1200X160-64 |
| LSSOP65P640X145-20N |
| MSOP10 |
| NATIONALSEMI-TZA11A |
| QFN50P400X400X80-25N |
| QFN50P500X500X80-33N |
| QFN50P500X500X100-32N |
| QFN50P500X500X100-33N |
| QFP50P1600X1600X100-100N |
| Relay_TE_IM-Series_Gull |
| RESC1005N |
| RESC1608N |
| RESC1608N_F |
| RESC1608N_ZERO |
| RESC2012N |
| RESC2012N_F |
| RESC2012N_ZERO |
| RESC3216N |
| RESC3216N_ZERO |
| RESC3225N |
| RESC5025N |
| RESC6332N |
| RESCAXS50P160X320X70-8N |
| RESON_CER_SMD |
| RESP4021N8X |
| SC70-6 |
| SM8 |
| SOD80, LL-34 |
| SOD123 |
| SOD323 |
| SOD323F |
| SOD523F |
| SOIC127P600X175-8AN |
| SOIC127P600X175-9N |
| SOIC127P600X175-14AN |
| SOIC127P600X175-16AN |
| SOIC127P780X200-14N |
| SOP65P490X109-8N |
| SOP65P640X110-25N |
| SOP65P780X200-28N |
| SOP65P810X120-30N |
| SOT23_213 |
| SOT23-3 |
| SOT23-5 |
| SOT23-6 |
| SOT89-3 |
| SOT223 |
| SOT353 |
| SOT363 |
| SSOP28 |
| SWITCH_TACT-EVQPQxB55 |
| TO-252 |
| TO-263-5 |
| TP |
| TrimPot_SMD_Bourns_3214G |
| TS-1143S |
| TS-1170S |
| TSSOP65P400X110-8N |
| TSSOP65P640X120-8N |
| TSSOP65P640X120-10N |
| TSSOP65P640X120-14N |
| TSSOP65P640X120-16N |
| TSSOP65P640X120-17N |
| TSSOP65P640X120-20N |
| USB_Micro-B_FCI_SMD |
| USB_Mini-B_Molex_SMT |
| WPAK(3F) |
| ZIF_CONN_4P_TE84953-4 |


### THD Packages

| 1x1POS_HEAD-SOCK_LOWPROF |
|:---------------------------|
| 1x1POS_HEADER_LOWPROF |
| 1x1POS_SOCKET_LOWPROF |
| 1x3POS_HEAD-SOCK_LOWPROF |
| 1x3POS_HEADER |
| 1x3POS_HEADER_LOWPROF |
| 1x3POS_SOCKET_LOWPROF |
| 2P_PCB_ScrewTerm_90S_3.81MM |
| 2P_PCB_TERM_BLOCK_HDR |
| 2P_PCB_TERM_BLOCK_HDR_RA |
| 3P_HDR_OPTO |
| 3P_PCB_TERM_BLOCK_HDR |
| 4P_PCB_ScrewTerm35 |
| 4P_PCB_TERM_BLOCK_HDR_RA |
| 6P_PCB_ScrewTerm_90S_3.81MM |
| 6P_PCB_ScrewTerm90S |
| 6P_PCB_SOCKET_BRD_MNT_MICRO-MATCH |
| 6P_PCB_TERM_BLOCK_HDR |
| 6P_PCB_TERM_BLOCK_HDR_RA |
| 8P_PCB_ScrewTerm_90S_3.81MM |
| 8P_PCB_TERM BLOCK HDR |
| 10P_PCB_HEADER_BRD_MNT |
| 10P_PCB_ScrewTerm |
| 14P_PCB_HEADER_BRD_MNT |
| 14P_PCB_HEADER_BRD_MNT_RA |
| 16P_PCB_HEADER_BRD_MNT |
| 16P_PCB_HEADER_BRD_MNT_RA |
| 34P_PCB_SOCKET_BRD_MNT |
| 40P_PCB_SOCKET_BRD_MNT |
| 50P_PCB_SOCKET_BRD_MNT |
| AUPO_P-4F_BEND1 |
| AUPO_P-4F_BEND2 |
| AUPO_P-4F_BEND3 |
| AUPO_P-4F_BEND4 |
| AUPO_P-4F_BEND5 |
| AUPO_P-4F_BEND6 |
| AUPO_P-4F_BEND6M |
| AXIAL-0.6 |
| BANANA_TRIPLE |
| BATT_HOLDER_2XAA |
| BUZZER_12.0X8.5MM |
| CAN-3-Y1.4 |
| CAPAE200P550X1200_FLAT1 |
| CAPAE200P550X1200_FLAT2 |
| CAPAE250P680X1220_FLAT1 |
| CAPAE250P680X1220_FLAT2 |
| CAPAE250P680X1220_VERT |
| CAPC500P450250X550 |
| CAPE_5x11x2LS |
| CAPE_5x11x2LS_RA |
| CAPE3.5-5.0MM_Rad_10x14mm |
| CAPE3.5mm |
| CAPE5.0mm |
| CAPE10.0MM_Rad_10x14mm |
| CAPE10.0MM_Rad_30x45mm |
| CAPM50P760490X990_FLAT |
| CAPM50P760640X1140_FLAT |
| CAPM75P1000400X850_FLAT |
| CAPM75P1000500X1050_FLAT_250V100nF |
| CAPM75P1000500X1050_FLAT_Dual250V100nF |
| CAPM75P1000500X1050_FLAT_with5mm |
| CAPMF 7.2x2.5x6.5x5LS |
| CAPMF 7.3x5.2x7x5LS |
| CAPMF 7.3x5.7x7.3x5LS |
| CAPMF 7.3x6.5x10x5LS |
| CAPMF3.5-5.0-7.5mm |
| CAPMF5.0-7.5mm |
| CAPMF5.0-7.5mm_SL |
| CAPMF7.5mm |
| CAPMF7.5mm_SL |
| CAPMF12.5x4.5x9.0x10mmLS |
| CAPMF13.0x5.0x11.0x10.0mm LxWxHxP |
| CAPR7.62-6.8x2.5 |
| CONN_AudioJackMono |
| CONN_BNC_RA_PCB |
| CONN_DIN_4PIN_KPJX-4S-S |
| CONN_JACK_MICRO-CONX |
| CONN_PWR_JACK_0.7x2.35mm |
| CONN_PWR_JACK_2.1x5.5mm |
| CONN_PWR-DIN_4PIN_PD-40S |
| CONN POGO 7POS RA 0.100IN |
| DIP8-300 |
| DO-41 |
| FUSE_SR-5-BK |
| HDR_1x2 |
| HDR_1x2_Generic |
| HDR_1x2_LED |
| HDR_1x2_Offset |
| HDR_1x2_Power |
| HDR_1X2X100 |
| HDR_Photodiode_TO-5 |
| HDR_Phototrans_3mm |
| HDR_Phototrans_TO-46 |
| HDR1X2 |
| HDR1X3_OPTO |
| HDR1X4_1.27mmp |
| HDR1X4_2.54mmp |
| HDR1X5_1.27mmp |
| HDR1X5_2.54mmp |
| HDR1X6 |
| HDR1X6_1.27mmp |
| HDR1X6_2.54mmp |
| HDR1X6S |
| HDR1X7 |
| LED_3-HIGH_3MM |
| MT03-H1BHP |
| Relay_Tyco_FP2 |
| Relay_Tyco_FX2 |
| Relay_Tyco_P2 |
| RESTH_0.0R_AXIAL-0.6 |
| RESTH_AXIAL_MRA-05 |
| RESTH_AXIAL_MRA-10 |
| RESTH_AXIAL_MRA-12 |
| RESTH_AXIAL_RS02B |
| RESTH_AXIAL_RS010 |
| RESTH_AXIAL-0.4 |
| SW_MRF403 |
| SWITCH_DPDT_M2 |
| SWITCH_DPDT_RA_7201K2A |
| SWITCH_ROTARY_SP10T |
| SWITCH_SPDT_SLIDER |
| TACT_SWITCH_TL-1105-C |
| TACT-SWITCH-TC-37XB |
| TACT-SWITCH-TS1143 |
| TACT-SWITCH-TS1150 |
| TACT-SWITCH-TS1170 |
| TO-92 |
| TO-92_Flat |
| TO-92_Flat2 |
| TO-220-5 |
| TP-THT-MINI |
| TP-THT-MULTI |
| TrimPot_THT_2.54mm pitch |
| TRIMPOT_THT_PV36X |
| USB_TypeB_Tyco |
| Varistor_7.62and10mm |
| VishaySpectrol_64Y |
