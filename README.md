# Class-D-Audio-Amplifier
This document is a complete guide for publishing a Class-D Audio Amplifier as a professional 
GitHub project. The system is a fully discrete, speaker-driving analog circuit built on a 5V 
supply, implemented across five modular sub-circuits that are integrated into a complete 
stethoscope-style audio processing chain.
The system block diagram flows as follows:
Block
Source Experiment
Key Function
Ramp Generator
Experiment 1
Generates 5kHz triangle wave (1Vpp) for PWM 
modulation
PWM Modulator
Experiment 2
Single-ended to differential conversion + PWM 
from audio
H-Bridge Driver
Experiment 3
BJT-based H-bridge drives 32Ω speaker at 5V 
supply
Bandpass Filters
Experiment 4
Two 2nd-order BPFs at 156.25Hz and 625Hz, 
Q=10
Adder
Experiment 5
Sums BPF outputs before feeding into Class-D
