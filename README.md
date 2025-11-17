# -Frequency-Modulation-and-Demodulation-using-NumPy-and-Matplotlib-

__Aim:__

To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries.

__Apparatus Required:__ 

1. Software: Python with NumPy and Matplotlib libraries
   
2. Hardware: Personal Computer

 
__Theory:__

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its 
frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier 
wave is varied according to the instantaneous amplitude of the message signal.

__Algorithm:__

1. Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and 
   frequency deviation.
   
2. Generate Time Axis: Create a time vector for the signal duration.
    
3. Generate Message Signal: Define the message signal as a cosine wave.
    
4. Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
    
5. Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
 
6. Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

__Programme:__

```
import numpy as np

import matplotlib.pyplot as plt

Ac=8

fc-2500

Am 2.5

fm=450

fs-25000

beta3.6

tnp.arange(0, 2/fm, 1/fs)

Em Am np.cos(2 np.pi fmt)

EcAc np.cos(2 np.pi fct)

EfmAc np.cos(2 np.pi fct+beta np.sin(2* np.pi fm *t))

plt.figure(figsize (10,6))

plt.subplot(3, 1, 1)

plt.plot(t, Em)

plt.grid()

plt.subplot(3, 1, 2)

plt.plot(t, Ec)

plt.grid()

plt.subplot(3, 1, 3)

plt.plot(t, Efm)

plt.grid()

plt.tight_layout()

plt.show()

```
 ### TABULATION:
 ![499305986-465f240a-607b-468f-b130-7f954204d0eb](https://github.com/user-attachments/assets/1687d7bf-4953-4e63-bc82-d529d4d2020e)

### CALCULATION:
![499306094-7a945e1a-f629-49c8-b38d-5397a6b285e2](https://github.com/user-attachments/assets/e2232b2b-c848-4742-9fa0-13452c2206ff)

__Output:__

![WhatsApp Image 2025-11-15 at 9 00 05 AM](https://github.com/user-attachments/assets/4a530f20-2c56-434d-b3a1-4c7851e9f2fc)


__Result:__

The message signal,carrier signal and fm signam will be displayed in separete plots. The message plots show frequency variations corresponding to the amplitude of the message signal
