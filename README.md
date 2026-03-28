# Class-D-Audio-Amplifier
A lab course project from the Analog Systems Lab — IIT Madras BS in Electronics Systems.
Built and simulated a fully discrete Class-D audio amplifier across 5 experiments, integrating PWM modulation, BJT H-bridge, active bandpass filters, and a summing amplifier to drive a 32Ω speaker from a 5V supply.

The system block diagram flows as follows:

Source Experiment -  Block - Key Function

 Experiment 1 - Ramp Generator -  Generates 5kHz triangle wave (1Vpp) for PWM modulation


 Experiment 2 - PWM Modulator from audio - Single-ended to differential conversion + PWM from audio


 Experiment 3 - H-Bridge Driver - BJT-based H-bridge drives 32Ω speaker at 5V supply



 Experiment 4 - Bandpass Filters - Two 2nd-order BPFs at 156.25Hz and 625Hz, Q=10


 Experiment 5 - Adder - Sums BPF outputs before feeding into Class-D amplifier

          
