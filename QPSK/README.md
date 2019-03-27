# QPSK
Quad Phase Shift Keying 

## Explanation
QPSK is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees). QPSK allows the signal to carry twice as much information as ordinary PSK using the same bandwidth

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

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QPSK/QPSK%20Design.JPG)

## Scatter plot before noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QPSK/QPSK%20Scatter%20Plot%20At%20Transmitter.JPG)

## Scatter plot After noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QPSK/QPSK%20Scatter%20Plot%20At%20Receiver.JPG)

## BER Figure

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QPSK/ber.JPG)

# With Raised Cosine

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QPSK/QPSK%20with%20raised%20cosine%20Design.JPG)

## Scatter plot before noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QPSK/QPSK%20Scatter%20Plot%20At%20Transmitter%20with%20cosine.JPG)

## Scatter plot After noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QPSK/QPSK%20Scatter%20Plot%20At%20Receiver%20with%20cosine.JPG)

## BER Figure

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/QPSK/berwithcosine.JPG)


