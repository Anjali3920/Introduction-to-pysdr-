
# Introduction-to-pysdr-
# SDR ( Software - Defined Radio)
It refers to a device that you can plug an antenna into and receive RF signals , with the digitalized RF samples being sent to a computer for processing or recording .many SDR also have transmit capabilities .
# DSP (Digital Signal Processing)
It refers to various techniques for improving the accuracy and reliability of digital communications.
# Frequency domain 
The frequency domain refers to an analysis or representation of data, signals, or functions in terms of frequency rather than time. This concept is crucial in many fields, including signal processing, image processing, and communications.
# Fourier Series
When we break signal down into it's composite sine waves,we call it a Fourier series. 
To understand how we can break down a signal into sine waves,we need to know about:
1.Amplitude: strength of wave
2.Frequency: no.of waves per second.
3.Phase:phase representation how the sine wave is shifted in time , anywhere from 0 to 360 degrees.
# Time- Frequency Pairs
Signals can be represented as sine waves, which have several attributes. Now, let’s learn to plot signals in the frequency domain. While the time domain demonstrates how a signal changes over time, the frequency domain displays how much of a signal rests in which frequencies.
https://github.com/user-attachments/assets/438c1bd9-92a6-4832-8ae6-5d59fc2c2e62
# Fourier Transformation 
The Fourier Transform is a mathematical technique that transforms a time-domain signal into its corresponding frequency-domain representation. It decomposes a function or signal into its constituent frequencies, showing how much of each frequency is present. This is especially useful in analyzing periodic signals, filtering, and signal processing.The inverse Fourier Transform can be used to convert the frequency-domain signal back to the time-domain.
# Fast Fourier Transform (FFT)
The Fast Fourier Transform  is simply an algorithm to compute the discrete Fourier Transform . The FFT is a function with one input and one output .It converts a signal from time to frequency:
(https://github.com/user-attachments/assets/fceb5b15-5c59-4803-aee1-21fb7349d680)
# FFT in python 
'''
sudo apt update
'''
