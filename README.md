# CMOS-Power-Oscillator-Test-Chip
CMOS Power Oscillator Test Chip*
Amr Tawfik, Belal Ali and Hager Mohamed
El-Minia University, Faculty of Engineering. EE Department
El-Minia, Egypt


##Description
The proposed test chip compares three PA classes that can be used in implementing a CMOS power oscillator at 915 MHz ISM band for far-field wireless power charging applications [1]. The driver is a  center tapped inductor cross-coupled oscillator [2] common to the three test cases. The driver uses nominal transistor ratings and can be isolated from the rest of the chip for testing. The three differential power amplifiers (DPAs) use high-voltage transistors and can be tested individually with external signal generator as input. Differential architectures are chosen to increase the output power level. The three DPAs under test are of class C [3], class E [4, 5] and class F [6]. Finally the complete power oscillator for the three cases will be tested for their performance comparison. The main key metrics include DC-to-RF power conversion efficiency as well as the output power level on a 50  PCB mounted terminator. 


Design Goals
Far-field wireless charging requires a power oscillator (PO) as a transmitter sending RF energy over the air to an embedded receiver (rectenna) in a chargeable device [7]. The main goal of this design is to use standard CMOS technology rather than special high-power, hardly-integrated devices like GaN or SiC [8] to implement the PO. Using high-voltage Si MOSFETs is challenging to avoid reliability issues and maintain long life-time operation [9]. The relatively limited drain voltage swing leads to moderate power output levels suitable for wireless power transmission range of only 1 to 2 meters. Consequently the target chargeable devices are ultra-low power ones like some wearable, implanted medical, sensor nodes and home IoT devices [10].



Block Diagrams
![image](https://user-images.githubusercontent.com/102924726/165120442-8f6abe10-d708-482e-86d1-345525e285df.png)

Power Oscillator Test Chip
 
![image](https://user-images.githubusercontent.com/102924726/165120556-6ff02a4c-454d-40f5-8583-d7aa11943886.png)


Driver and DPA
 


Tentative Floorplan and Wiring Diagram
                           
Schematics
Driver







Class-C PA
                  
Class-E PA










Class-F PA














References
[1]  https://www.powercastco.com/products/powercaster-transmitter/ (last visited on March 2022)

[2] Bagheri, M. and X. Li, “A modified cross-coupled oscillator”, Microsystem Technologies, 27(5), 2021, 2217-2228.‏

[3] Narayanaswami, R. S., “RF CMOS class-C power amplifier for wireless communications,” PhD Dissertation, UCB, 2001(University of California, 1998.

[4] Sokal, N. O. and A. D. Sokal, “Class E - A New Class of High-Efficiency Tuned  Single-Ended Switching Power Amplifiers,” IEEE J. of Solid-State Circuits, vol. 10,  pp. 168–176, June 1975.

[5] Rezk, T. M., G. A. Fahmy,  S. A. Ibrahim, and H. F. Ragai, “Design of a                                                    differential power oscillator for 433 MHz WPT using e-GaN HEMTs. Ain Shams Engineering Journal, Vol. 13, Issue 3, 2021. 

[6] Grebennikov, A. and N. O. Sokal, “Class-F Power Amplifiers”, Ch. 3 in book “Switch-mode Power Amplifiers”, Newnes, 2007, 95-145.

[7] Ludivine, F., L. Oyhenart, R. Berges, V. Vigneras and T. Taris, “A concurrent 
915/2240 MHz RF energy harvester”, Int. Jr. of Microwave and Wireless Technologies, 
2016, 1-9.

[8] Mochizuki, K., “Vertical GaN and SiC power devices”, Artech house, 2018.

[9] Tao, G.,” Reliability issues in advanced monolithic embedded high voltage CMOS technologies”, IEEE Int. Integrated Reliability Workshop, 2004.

[10] Dong, B., Q. Shi, Y. Yang, F. Wen, Z. Zhang and C. Lee, “Technology evolution from self-powered sensors to AIoT enabled smart homes”, Nano Energy, Vol. 79, 2021, 1 – 23.
