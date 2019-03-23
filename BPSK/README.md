# BPSK
Binary Phase Shift Keying (BPSK)
##Explanation
is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

### Adding Raised Cosine Filter
The raised-cosine filter is a filter frequently used for pulse-shaping in digital modulation due to its ability to minimise intersymbol interference (ISI), this is an implementation of a low-pass Nyquist filter, i.e., one that has the property of vestigial symmetry. 
![alt text](https://github.com/khaledsabry97/Digital-Communication-Modulation/blob/master/Raised-cosine_filter.png)

##How to run it
[1] open matlab
[2] write in the terminal ==> bertool
[3] go to the monto carlo tab
[4] set the range of No/Eo
[5] select the file to simulate that
[6] push Run

Expected Output : two windows (scatter plot at the recevier and transimitter) + BER performance figure



