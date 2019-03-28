# **Digital Communication Project**
### **Name** : Moamen Hassan Attia
### **Section** : 2
### **B.N** : 13

## **Required**
### Simulating the performance of different modulation schemes.
- [**BPSK**](#binary-phase-shift-keying-modulation-bpsk)
- [**QPSK**](#quadrature-phase-shift-keying-modulation-qpsk)
- [**QAM16**](#quadrature-amplitude-modulation-qam16)
- [**QAM64**](#quadrature-amplitude-modulation-qam64)
- [**FSK**](#frequency-shift-keying-fsk)

## **Modulation Schemes :-**
### **Binary Phase Shift Keying Modulation (BPSK)**
### What is it ?!
___ 
**Binary Phase Shift Keying (BPSK)** is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

### **Without Raised Cosine**
___
### Parameters
```
Random Generator set size = 2
```
### Block Diagram
![BPSK Block Diagram](/BPSK/Figures/BPSK-Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/BPSK/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/BPSK/Figures/After-Noise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/BPSK/Figures/After-Noise-+10.PNG)
### - BER Diagram
![BER Diagram](/BPSK/Figures/ber-vs-snr.png)

### **With Raised Cosine**
___
### Parameters
```
Random Generator set size = 2
```
### Block Diagram
![BPSK Block Diagram](/BPSK-Raised-Cosine/Figures/BPSK-Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/BPSK-Raised-Cosine/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/BPSK-Raised-Cosine/Figures/After-Noise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/BPSK-Raised-Cosine/Figures/After-Noise-+10.PNG)

___
### **Quadrature Phase-Shift Keying Modulation (QPSK)**
### What is it ?!
___
**Quadrature Phase-Shift Keying Modulation ( QPSK )** is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, 270). **QPSK** allows the signal to carry twice as much information as ordinary PSK using the same bandwidth.

### **Without Raised Cosine**
### Parameters
```
Random Generator set size = 4
Phase offset = pi/4
```
### Block Diagram
![QPSK Block Diagram](/QPSK/Figures/QPSK-Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/QPSK/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/QPSK/Figures/AfterNoise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/QPSK/Figures/AfterNoise-+10.PNG)
### - BER Diagram
![BER Diagram](/QPSK/Figures/SNR-VS-BER.PNG)

### **With Raised Cosine**
___
### Parameters
```
Random Generator set size = 4
Phase offset = pi/4
```
### Block Diagram
![QPSK Block Diagram](/QPSK-Raised-Cosine/Figures/QPSK-Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/QPSK-Raised-Cosine/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/QPSK-Raised-Cosine/Figures/AfterNoise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/QPSK-Raised-Cosine/Figures/AfterNoise-+10.PNG)

___
## **Quadrature Amplitude Modulation (QAM16)**
### What is it ?!
___
**QAM** is a signal in which two carriers shifted in phase by 90 degrees (i.e. sin and cos) are modulated and combined. As a result of their 90 phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or I signal, and the other is the quadrature or Q signal. 
### **Without Raised Cosine**
___
### Parameters
```
Normalization method = Average Power
Random Generator set size = 16
M-ary number = 16
```
### Block Diagram
![QAM16 Block Diagram](/16QAM/Figures/QAM-16-Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/16QAM/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/16QAM/Figures/After-Noise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/16QAM/Figures/After-Noise+-10.PNG)
### - BER Diagram
![BER Diagram](/16QAM/Figures/ber-vs-snr.png)

### **With Raised Cosine**
___
### Parameters
```
Normalization method = Average Power
Random Generator set size = 16
M-ary number = 16
```
### Block Diagram
![QAM16 Block Diagram](/16QAM-Raised-Cosine/Figures/QAM-16-Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/16QAM-Raised-Cosine/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/16QAM-Raised-Cosine/Figures/After-Noise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/16QAM-Raised-Cosine/Figures/After-Noise+-10.PNG)
___
## **Quadrature Amplitude Modulation (QAM64)**
### What is it ?!
___
**QAM** is a signal in which two carriers shifted in phase by 90 degrees (i.e. sin and cos) are modulated and combined. As a result of their 90 phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or I signal, and the other is the quadrature or Q signal.
### **Without Raised Cosine**
___
### Parameters
```
Normalization method = Average Power
Random Generator set size = 64
M-ary number = 64
```
### Block Diagram
![QAM64 Block Diagram](/64QAM/Figures/QAM64-Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/64QAM/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/64QAM/Figures/QAM64-AfterNoise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/64QAM/Figures/QAM64-AfterNoise-+10.PNG)
### - BER Diagram
![BER Diagram](/64QAM/Figures/SNR-VS-BER.PNG)
### **With Raised Cosine**
___
### Parameters
```
Normalization method = Average Power
Random Generator set size = 64
M-ary number = 64
```
### Block Diagram
![QAM64 Block Diagram](/64QAM-Raised-Cosine/Figures/QAM64-Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/64QAM-Raised-Cosine/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/64QAM-Raised-Cosine/Figures/QAM64-AfterNoise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/64QAM-Raised-Cosine/Figures/QAM64-AfterNoise-+10.PNG)
___
## **Frequency Shift Keying (FSK)**
### What is it ?!
___
**FSK** is the frequency modulation system in which digital information is transmitted through the discrete frequency change of a carrier wave.
### **Without Raised Cosine**
___
### Parameters
```
Random Generator set size = 8
M-ary number = 8
Frequency separation = 6 Hz
Samples per symbol = 17
```
### Block Diagram
![FSK Block Diagram](/FSK/Figures/FSK_Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/FSK/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/FSK/Figures/AfterNoise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/FSK/Figures/AfterNoise-+10.PNG)
### - BER Diagram
![BER Diagram](/FSK/Figures/ber.PNG)
### **With Raised Cosine**
___
### Parameters
```
Random Generator set size = 8
M-ary number = 8
Frequency separation = 6 Hz
Samples per symbol = 17
```
### Block Diagram
![FSK Block Diagram](/FSK-Raised-Cosine/Figures/FSK_Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](/FSK-Raised-Cosine/Figures/BeforeNoise.PNG)
### - At Receiver Scatter Plot
### At Receiver : After Adding Noise -10 DP
![At Receiver : After Adding Noise -10 DP](/FSK-Raised-Cosine/Figures/AfterNoise--10.PNG)
### At Receiver : After Adding Noise +10 DP
![At Receiver : After Adding Noise +10 DP](/FSK-Raised-Cosine/Figures/AfterNoise-+10.PNG)
___