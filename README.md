# Phase Comparator

##  Problem Statement 
- To design a phase comaparator circuit to measure phase difference between two signals.

## Description
- We are given two sinusoidal signals with with a phase difference between them. We need to find this phase difference.
- We divide this PS into 3 stages:
  1. All Pass Filter - To generate desired phase difference between two input sinusoidal signals by varying potentiometer.
  2. Schmitt Trigger - To convert these sinusoidal signals into square/digital waveforms.
  3. XNOR using BJTs - To find the duty cycle(D) of the waveform we got after XNORing the waveforms obtained in 2.
     From the value of D, we can easily find the phase difference between the two given signals.

## Components Used
- IC741 opamp
- Potentiometer 50k
- BJT npn Transistor 2N2222
- Zener Diode
- Capacitors and Resistors
- Connecting wires and Breadboard



