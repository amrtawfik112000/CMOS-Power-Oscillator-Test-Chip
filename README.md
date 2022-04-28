# CMOS-Power-Oscillator-Test-Chip

Amr Tawfik, Belal Ali and Hager Mohamed
El-Minia University, Faculty of Engineering. EE Department
El-Minia, Egypt

**Description**

The proposed test chip compares three PA classes that can be used in implementing a CMOS power oscillator at 915 MHz ISM band for far-field wireless power charging applications [1]. The driver is a center tapped inductor cross-coupled oscillator [2] common to the three test cases. The driver uses nominal transistor ratings and can be isolated from the rest of the chip for testing. The three differential power amplifiers (DPAs) use high-voltage transistors and can be tested individually with external signal generator as input. Differential architectures are chosen to increase the output power level. The three DPAs under test are of class C [3], class E [4, 5] and class F [6]. Finally the complete power oscillator for the three cases will be tested for their performance comparison. The main key metrics include DC-to-RF power conversion efficiency as well as the output power level on a 50 Ohm PCB mounted terminator.

**Design Goals**

Far-field wireless charging requires a power oscillator (PO) as a transmitter sending RF energy over the air to an embedded receiver (rectenna) in a chargeable device [7]. The main goal of this design is to use standard CMOS technology rather than special high-power, hardly-integrated devices like GaN or SiC [8] to implement the PO. Using high-voltage Si MOSFETs is challenging to avoid reliability issues and maintain long life-time operation [9]. The relatively limited drain voltage swing leads to moderate power output levels suitable for wireless power transmission range of only 1 to 2 meters. Consequently the target chargeable devices are ultra-low power ones like some wearable, implanted medical, sensor nodes and home IoT devices [10].

**Block Diagrams**

**Power Oscillator Test Chip**

![image](https://user-images.githubusercontent.com/102924726/165120442-8f6abe10-d708-482e-86d1-345525e285df.png)

**Driver and DPA**

![image](https://user-images.githubusercontent.com/102924726/165120556-6ff02a4c-454d-40f5-8583-d7aa11943886.png)

**Tentative Floorplan and Wiring Diagram**

![image](https://user-images.githubusercontent.com/102924726/165120859-af077f53-6029-413b-a1fd-a0fdf6373870.png)

**Schematics**

**Driver**

![image](https://user-images.githubusercontent.com/102924726/165120919-e4920358-a9c2-4734-8a05-30a569c9f612.png)

**Class-C PA**

![image](https://user-images.githubusercontent.com/102924726/165121326-6f759a45-7234-462b-b301-c14aa5b073bf.png)

**Class-E PA**

![image](https://user-images.githubusercontent.com/102924726/165121087-bb2525bf-67bb-406e-aca6-2b54b20aa348.png)

**Class-F PA**

![image](https://user-images.githubusercontent.com/102924726/165121125-0a2fa173-6114-4d6d-847c-45ef340ae3c8.png)

**Target Specs**

| Design Parameter | Value |
| --- | --- |
| Output power | >= 6 W |
| ISM Frequency Band | 915 MHZ |
| Efficiency | >= 40% |
| THD | <= 5% |


**References**

[1] [https://www.powercastco.com/products/powercaster-transmitter/](https://www.powercastco.com/products/powercaster-transmitter/) (last visited on March 2022)

[2] Bagheri, M. and X. Li, &quot;A modified cross-coupled oscillator&quot;, Microsystem Technologies, _27_(5), 2021, 2217-2228.‏

[3] Narayanaswami, R. S., &quot;RF CMOS class-C power amplifier for wireless communications,&quot; PhD Dissertation, UCB, 2001(University of California, 1998.

[4]Sokal, N. O. and A. D. Sokal, &quot;Class E - A New Class of High-Efficiency Tuned Single-Ended Switching Power Amplifiers,&quot; IEEE J. of Solid-State Circuits, vol. 10, pp. 168–176, June 1975.

[5] Rezk, T. M., G. A. Fahmy, S. A. Ibrahim, and H. F. Ragai, &quot;Design of a differential power oscillator for 433 MHz WPT using e-GaN HEMTs. _Ain Shams Engineering Journal, Vol. 13, Issue 3,_ 2021.

[6] Grebennikov, A. and N. O. Sokal, &quot;Class-F Power Amplifiers&quot;, Ch. 3 in book &quot;Switch-mode Power Amplifiers&quot;, Newnes, 2007, 95-145.

[7] Ludivine, F., L. Oyhenart, R. Berges, V. Vigneras and T. Taris, &quot;A concurrent

915/2240 MHz RF energy harvester&quot;, Int. Jr. of Microwave and Wireless Technologies,

2016, 1-9.

[8] Mochizuki, K., &quot;Vertical GaN and SiC power devices&quot;, Artech house, 2018.

[9] Tao, G.,&quot; Reliability issues in advanced monolithic embedded high voltage CMOS technologies&quot;, IEEE Int. Integrated Reliability Workshop, 2004.

[10] Dong, B., Q. Shi, Y. Yang, F. Wen, Z. Zhang and C. Lee, &quot;Technology evolution from self-powered sensors to AIoT enabled smart homes&quot;, Nano Energy, Vol. 79, 2021, 1 – 23.

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

\*Graduation project 2022 – Under the supervision of: Hani Ragai and Theodora Rezk, Ain Shams University, Cairo, Egypt

