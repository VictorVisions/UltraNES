# UltraNES
An Open Source NES pcb controller design for use on the Nintendo 64.
This was used as a learning project designed to be used on the Nintendo 64 while using the Everdrive-64 X7 nes core. Please keep in mind that as a learning project there might still be some bugs and future iterations as these are discovered.
The current design is based off of the N64 CFS8120-700010 PCB design.

# Design and Build Files
Under Releases you'll find the latest Design and Build zip files. The Design folder will contain KiCad files along with the Schematic while the Build file will contain your BOM and Gerber files.

# Purchasing the PCB
Under Releases download the latest version of the Build folder and upload the file named "Gerber_Files.zip" to your preffered PCB manufacturing site such as... 
https://jlcpcb.com/, https://oshpark.com/ or similar PCB Manufacturers.

The reccomended PCB Specifications are:

1.6mm PCB Thickness, ENIG, with tented Via coverings

# Sourcing the components
All components can be ordered via Digikey minus the CNT-NUS IC (U1), CLK, and the controller cable (J2) which will need to come from a donor board. Alternatively for the cable you can use a controller exstension cord which can be found on Amazon or other silimar online retailers.
I have listed a Bill of Materials (BOM) with part numbers to be used for ordering components through Digikey. You can find this under the Build folder labeled "UltraNES_BOM.xlsx".

Please note that C1 has a duplicate footprint on the PCB if using SMD component versus a through hole capacitor. And lastly the J1 connector for the Analog stick is currently not implemented on the PCB so you will notice resistors and the J1 connector on the schematic but not on the PCB.
