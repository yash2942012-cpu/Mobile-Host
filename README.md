## Mobile-Host
 
This is a small USB Hub, your Mobile Phone connects via a Type-C to USB-A Female OTG Adapter to the board's  USB-A male plug connector. A USB Type-C connector for powering the board, with three Downstream USB-A connectors for keyboard, mouse, and other things like devboard etc. and one Type-C connector to connect a laptop to it,  just for fun.

## Technical Specs
* **Hub Controller**: SL2.1S (USB 2.0 High-Speed 4-Port Controller)
* **Power Delivery Control**: LDR6023A (USB Type-C PD controller)
* **Upstream Connection**: USB-A Male (Requires an OTG adapter to phone host)
* **Downstream Connections**: 3x USB-A ports, 1x USB-C peripheral port


<img width="962" height="706" alt="Screenshot from 2026-07-09 19-57-21" src="https://github.com/user-attachments/assets/398ad97e-1d00-40bd-b5b7-a1307be66e9e" />

## HOW TO USE
To use this ensure these steps;
 - Connected to a stable 5V power supply via the Power Type-C port.
 - While connecting to a Mobile Phone you have an OTG adapter or cable.
 - You have enabled the OTG setting in your Mobile Phone.

## Design  

## SCHEMATIC
<img width="1169" height="827" alt="Schematic_USB-HUB_2026-07-09" src="https://github.com/user-attachments/assets/dd818de5-996a-4804-b32d-550eccd626da" />

## PCB LAYOUT
Top Layer

<img width="754" height="481" alt="Screenshot from 2026-07-09 20-11-22" src="https://github.com/user-attachments/assets/9980d132-b82c-4d05-b209-9ea650bc6d2d" />

## 

Bottom Layer

<img width="754" height="481" alt="Screenshot from 2026-07-09 20-11-29" src="https://github.com/user-attachments/assets/e5fe96c0-92d0-4e49-ba56-ea76885f8a51" />

## BOM

|Part ID	       |Quantity	  |Price       |link
|---------------|-----------|------------|-----------------------------------------------------------------------------------------------------------------------|
|"C6386905"		   |"1"	       |"0.066"     |"https://atta.szlcsc.com/upload/public/pdf/source/20230523/03CC7987750CEF13E6E106534A09418D.pdf"	                      |
|"C519970"	     |"2" 		     |"0.025"     |"https://item.szlcsc.com/373011.html"                                                                                  |
|"C2684433"	    |"1"			     |"0.253"		   |"https://item.szlcsc.com/2782346.html"                                                                                 |
|"C1845619"     |"2"			     |"0.005"		   |"https://item.szlcsc.com/362304.html"                                                                                  |
|"C1525"        |"2"			     |"0.007"	    |"https://item.szlcsc.com/15869.html"                                                                                   |
|"C577001"      |"1"		      |"0.047"     |"https://item.szlcsc.com/373011.html"                                                                                  |
|"C1985574"     |"1"			     |"0.595"		   |"https://img.jlc.com/pdf/applypastecomponent/2021-12-20/798399F/6e73fe4a6e1849e6a80262d2cddfa76e/2.PDF"                |
|"C668591"      |"3"		      |"0.067"	    |"https://item.szlcsc.com/698534.html"                                                                                  |
|"C165948"      |"2" 	      |"0.186"		   |"https://item.szlcsc.com/datasheet/TYPE-C-31-M-12/177331.html"                                                         |
|"C25796"       |"2"		      |"0.001"		   |"https://item.szlcsc.com/323315.html"                                                                                  |
|"C25905"	      |"2"	       |"0.001"		   |"https://item.szlcsc.com/323315.html"                                                                                  |
