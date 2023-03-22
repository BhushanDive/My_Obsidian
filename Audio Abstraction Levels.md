![[Pasted image 20230319124938.png]]
For Audio Classification. with Shallow Algos.
![[Pasted image 20230319130426.png]]


# Imp points

It is very important to convert the audio file from Time Domain to frequency domain. As audio is frquency based most of the information in audio is in frquency domain. 

We will use Fourier transform or Fast Fourier Transform to convert audio to frquency domain. But there is a problem of Spectral Leakage.

## Problem of Spectral Leakage

Spectral leakage occurs as we apply FT. It generates a high frequency components to the final frequency based plot. These are some artefacts ie there will be some audio components in the plot that are not actually there in the audio file. It happens due as the audio file may not generate Integer number of periods which creates discontinuity

## Answer to Spectral Leakage Problem
