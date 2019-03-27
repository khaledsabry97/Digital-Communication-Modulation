# BPSK
Binary Phase Shift Keying (BPSK)

## Explanation
is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

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

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/BPSK/BPSK%20DESIGN.JPG)

## Scatter plot before noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/BPSK/BPSK%20Scatter%20Plot%20At%20transimitter.JPG)

## Scatter plot After noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/BPSK/BPSK%20Scatter%20Plot%20At%20Receiver.JPG)

## BER Figure

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/BPSK/ber.JPG)

# With Raised Cosine

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/BPSK/BPSK%20DESIGN%20with%20raised%20cosine.JPG)

## Scatter plot before noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/BPSK/BPSK%20Scatter%20Plot%20At%20transimitter%20with%20raised%20cosine.JPG)

## Scatter plot After noise:

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/BPSK/BPSK%20Scatter%20Plot%20At%20Receiver%20with%20raised%20cosine.JPG)

## BER Figure

![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/BPSK/ber%20with%20rasied%20cosine.JPG)


