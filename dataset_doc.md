# Dataset documentation

### Columns

0 - Blue signal (Raw)  
1 - Green signal (Raw)  
2 - Red signal (Raw)  
3 - Blue filtered  
4 - Green filtered  
5 - Red filtered  
6 - Clear signal (Raw)  
7 - Priliminary SpO2 calculation  
8 - Priliminary HbA1c calculation  
9 - Ratio G/R (AC/DC)  
10 - Ratio B/R (AC/DC)  
11 - Blue DC  
12 - Green DC  
13 - Red DC  
14 - Blue AC  
15 - Green AC  
16 - Red AC  
17 - Heart rate ([1] algorithm)  
18 - SpO2 ([1] algorithm)  
19 - Transmission / Reflection mode (0 - reflection, 1 - transmission)  


**N.B.** The data columns 3-18 are not used in this current work. These were implemented to test hardware implementability (Arduino UNO) of this current procedure (columns 3-16), which is out of scope of this current work. Columns 17-18 were used to assess our previous work for SpO2 and Heart rate estimation techniques[1].

Column 0-2 are raw DVP signals for three wavelengths. These signals are used to perform current research. The data acquisition device has both "Transmission" and "Reflection" type DVP acquisition systems built in. The DVP type is switched to a mode (either transmission or reflection), and the LEDs are illuminated accordingly with 1 minute interval. The column 19 is the indicator of the current mode of DVP signal.

**References**
[1] P. P. Banik, S. Hossain, T.-H. Kwon, H. Kim, and K.-D. Kim, “Development of a Wearable Reflection-Type Pulse Oximeter System to Acquire Clean PPG Signals and Measure Pulse Rate and SpO2 with and without Finger Motion,” Electronics, vol. 9, no. 11, Art. no. 11, Nov. 2020, doi: 10.3390/electronics9111905.
