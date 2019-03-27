# QAM64
Quadrature amplitude modulation

## Explanation
technique used to transmit two digital bit streams or two analog signals by modulating or changing the amplitudes of two carrier waves so that they differ in phase by 90 degrees, a quarter of a cycle, hence the name quadrature. One signal is called the "I" signal and the other is the "Q" signal, which can be mathematically represented by a cosine and a sine wave, respectively.

### Adding Raised Cosine Filter
The raised-cosine filter is a filter frequently used for pulse-shaping in digital modulation due to its ability to minimise intersymbol interference (ISI), this is an implementation of a low-pass Nyquist filter, i.e., one that has the property of vestigial symmetry. 

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/Raised-cosine_filter.png)

## How to reproduce the figures (run it)
1. open matlab
2. write in the terminal ==> bertool
3. go to the monto carlo tab
4. set the range of Eb/No [-10:10]
5. set ber variable name : ber
6. select the file to simulate that
7. push Run

## Expected Output 
two windows (scatter plot at the recevier and transimitter) + BER performance figure




## Design

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2064/QAM64%20DESING.JPG)

## Scatter plot before noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2064/QAM64%20Scatter%20Plot%20At%20Transmitter.JPG)

## Scatter plot After noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2064/QAM64%20Scatter%20Plot%20At%20Receiver.JPG)

## BER Figure

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2064/ber.JPG)

# With Raised Cosine

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2064/QAM64%20DESING%20with%20raised%20cosine.JPG)

## Scatter plot before noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2064/QAM64%20Scatter%20Plot%20At%20Transmitter%20with%20raised%20cosine.JPG?raw=true)

## Scatter plot After noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2064/QAM64%20Scatter%20Plot%20At%20Receiver%20with%20raised%20cosine.JPG)

## BER Figure

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2064/ber%20with%20raised%20cosine.JPG)


