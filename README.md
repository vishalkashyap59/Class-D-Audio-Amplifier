# Class-D-Audio-Amplifier
A lab course project from the Analog Systems Lab — IIT Madras BS in Electronics Systems.
Built and simulated a fully discrete Class-D audio amplifier across 5 experiments, integrating PWM modulation, BJT H-bridge, active bandpass filters, and a summing amplifier to drive a 32Ω speaker from a 5V supply.

The system block diagram flows as follows:

Block                       Source Experiment           Key Function

Ramp Generator      -        Experiment 1                Generates 5kHz triangle wave (1Vpp) for PWM modulation


PWM Modulator from audio -              Experiment 2                Single-ended to differential conversion + PWM from audio


H-Bridge Driver   supply -          Experiment 3                BJT-based H-bridge drives 32Ω speaker at 5V supply
supply


Bandpass Filters        -    Experiment 4                Two 2nd-order BPFs at 156.25Hz and 625Hz, Q=10


Adder               -        Experiment 5                Sums BPF outputs before feeding into Class-D amplifier

          
