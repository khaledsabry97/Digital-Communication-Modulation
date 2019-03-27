# QAM 16
Quadrature Amplitude Modulation. 

## Explanation
by using 2 carriers, sin and cos, who are 90 phase apart. QAM16 means our symbol carries value of 4 bits at once. Each symbol differs from another by changing the amplitude and phase.

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

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2016/QAM%2016%20DESING%20.JPG)

## Scatter plot before noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2016/QAM16%20Scatter%20Plot%20At%20Transmitter.JPG)

## Scatter plot After noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2016/QAM16%20Scatter%20Plot%20At%20Receiver.JPG)

## BER Figure

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2016/ber.JPG)

# With Raised Cosine

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2016/QAM%2016%20DESING%20WITH%20RAISED%20COSINE.JPG)

## Scatter plot before noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2016/QAM16%20Scatter%20Plot%20At%20Transmitter%20with%20raised%20cosine.JPG)

## Scatter plot After noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2016/QAM16%20Scatter%20Plot%20At%20Receiver%20with%20raised%20cosine.JPG)

## BER Figure

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QAM%2016/ber%20with%20raised%20cosine.JPG)


