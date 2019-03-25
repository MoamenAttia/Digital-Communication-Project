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

## **Modulation Schemes :-**
### **Binary Phase Shift Keying Modulation (BPSK)**
### What is it ?! 
**Binary Phase Shift Keying (BPSK)** is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

### Parameters
```
Random Generator set size = 2
```
### Block Diagram
![BPSK Block Diagram](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/BPSK/Figures/BPSK%20Blocks.PNG)

### - At Transmitter Scatter Plot
![Before Adding Noise](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/BPSK/Figures/Before%20Noise.PNG) 
### - At Receiver Scatter Plot
![After Adding Noise](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/BPSK/Figures/After%20Noise.PNG) 
### - BER Diagram
![BER Diagram](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/BPSK/Figures/ber%20vs%20snr.png)
___
### **Quadrature Phase-Shift Keying Modulation (QPSK)**
### What is it ?! 
**Quadrature Phase-Shift Keying Modulation ( QPSK )** is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, 270). **QPSK** allows the signal to carry twice as much information as ordinary PSK using the same bandwidth.

### Parameters
```
Random Generator set size = 4
Phase offset = pi/4
```
### Block Diagram
![QPSK Block Diagram](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/QPSK/Figures/QPSK%20Blocks.PNG)

### - At Transmitter Scatter Plot
![Before Adding Noise](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/QPSK/Figures/Before%20Noise.PNG)
### - At Receiver Scatter Plot
![After Adding Noise](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/QPSK/Figures/After%20Noise.PNG)
### - BER Diagram
![BER Diagram](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/QPSK/Figures/SNR%20VS%20BER.PNG)
___
## **Quadrature Amplitude Modulation (QAM16)**
### What is it ?!
**QAM** is a signal in which two carriers shifted in phase by 90 degrees (i.e. sin and cos) are modulated and combined. As a result of their 90 phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or I signal, and the other is the quadrature or Q signal. 
### Parameters
```
Normalization method = Average Power
Random Generator set size = 16
M-ary number = 16
```
### Block Diagram
![QAM16 Block Diagram](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/16QAM/Figures/QAM%2016%20Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/16QAM/Figures/QAM%2016%20Before%20Noise.PNG)
### - At Receiver Scatter Plot
![After Adding Noise](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/16QAM/Figures/QAM%2016%20After%20Noise.PNG)
### - BER Diagram
![BER Diagram](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/16QAM/Figures/ber%20vs%20snr.png)

___
## **Quadrature Amplitude Modulation (QAM64)**
### What is it ?!
**QAM** is a signal in which two carriers shifted in phase by 90 degrees (i.e. sin and cos) are modulated and combined. As a result of their 90 phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or I signal, and the other is the quadrature or Q signal. 
### Parameters
```
Normalization method = Average Power
Random Generator set size = 64
M-ary number = 64
```
### Block Diagram
![QAM64 Block Diagram](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/64QAM/Figures/QAM64%20Blocks.PNG)
### - At Transmitter Scatter Plot
![Before Adding Noise](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/64QAM/Figures/Before%20Noise.PNG)
### - At Receiver Scatter Plot
![After Adding Noise](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/64QAM/Figures/After%20Noise.PNG)
### - BER Diagram
![BER Diagram](https://github.com/MoamenAttia/Digital-Communication-Project/blob/master/64QAM/Figures/SNR%20VS%20BER.PNG)