Objective of the Workshop : High level Application (any app writtenin C language) will be matched with Spec Code (PDK) &  RTL2GDS O0=O1=O3

![image](https://github.com/user-attachments/assets/b60d3dcb-ffda-46bb-86fb-90dca848116a)
![image](https://github.com/user-attachments/assets/d0d5858f-7bef-4608-aaa7-55991dcae65f)

![image](https://github.com/user-attachments/assets/89d39da5-d4c6-44cf-802c-b49f02038031)
![image](https://github.com/user-attachments/assets/23bcaa6f-95e9-4738-8bf3-99fe07e61231)

![image](https://github.com/user-attachments/assets/17d0cc93-f229-4d01-a33c-ebf5f5084401)

HW is divided into Processor & Peripherals /IPs, Digital device works on digital inputs, ADC is analog device used for conversion. 
Peripherals --> Common process which is instanciated multiple times (repeated) are Macros; Analog IPs like GPIOs, ADC, DAC, PLLS
Processor --> Synthesized NL (No Primitives, No Verilog Constraints)

Design PPA for Optimized Chip
GDSII File - Graphical Data Stream Information Interchange (DRC, LVS Checks are clean)
Tape out --> Process of sending to Factory /fab , Tapein --> Process of getting back Packaged chip

OpenLane --> 1.cd Desktop

2.cd work/tools/

3.cd openlane_working_dir/
4.ltr --help 
