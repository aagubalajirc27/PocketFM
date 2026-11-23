#PocketFM

A compact, one-transistor regenerative FM receiver built around the BF494. Simple to build, low cost, and powered by just 6V.


Overview

PocketFM is a beginner-friendly FM radio receiver that uses regenerative detection to get good sensitivity from a single transistor. A tuned LC circuit (L1 + FM gang capacitor) selects stations, while the Regen and RF Gain potentiometers let you fine-tune sensitivity and signal strength. No ICs are required, and the design fits on a small single-sided PCB.

Features
Single BF494 transistor design
Regenerative detection for high sensitivity
Adjustable Regen and RF Gain controls
Runs on a 6V supply
No ICs required
Compact single-sided PCB
Audio output for headphones or an external amplifier
Bill of Materials
Ref	Value	Notes
Q1	BF494	NPN RF transistor
R	47kΩ (x2)	Bias / regen network
R	2.2kΩ (x2)	
R	1kΩ	Supply decoupling
R	10kΩ	
C	100µF	Electrolytic, supply filter
C	4.7nF	
C	4.7pF (x2)	Feedback / coupling
C	1nF	
C	22nF	
C	100nF	Audio coupling
L1	Hand-wound coil	Tank inductor
RFC	RF choke	
VC1	FM gang capacitor	Tuning
RV1	Regen potentiometer	Regeneration control
RV2	RF Gain potentiometer	Gain control
J1	+6V, ANT, Audio terminals	Power, antenna, output
Build Notes
Solder low-profile parts first (resistors, small capacitors), then the transistor, choke, pots and gang capacitor.
Wind L1 and the RFC to your chosen specs; the coil and gang capacitor together set the tuning range.
Connect a short wire or telescopic antenna to ANT, a 6V supply to +6V, and headphones or an amplifier to Audio.
Adjust Regen until the receiver sits just below the point of oscillation, then tune with the gang capacitor and trim with RF Gain.


