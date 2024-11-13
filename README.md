# function-generator-cd4093
this is a function generator based on the cd4093 schmitt trigger chip. It can generate sine, triangle and sqarewaves from 200Hz to 500kHz. different frequencies are possible if you change the capacitors value, and/or use a different potentiometer.
![grafik](https://github.com/user-attachments/assets/aa779e84-bf32-4cc6-9830-395a7f4a8cf0)
the basic oscillator is fairly simple, most of the stuff is just there to get the wave to look nicer, and to create the sine wave. it uses an lm386 to amplify the signal into something useable.
i have made another version using a multi stage lm324 as an amplifier to get enough bandwidth, everything else remains the same.
![grafik](https://github.com/user-attachments/assets/76b3e653-5d07-4520-86c8-1faddba6275b)
