# rolling-code-grabber
A GNU Radio flowgraph that implement an attack to Remote Keyless Entry (RKE) systems using Roll Jam technique

# Description

Rolling Code Grabber is an open-source solution to implement a software-defined radio architecture that combine jamming and replay attack techniques in order to exploit security weakness affecting the Remote Keyless Entry (RKE) systems.

The GNU Radio Companion (GRC) flowgraph released it's a proof-of-concept that allow to the attacker the ability to jam and store locally the unidirectional radio frequency transmitted from RF key fob to the intended receiver, being able to subsequently send an arbitrary part of the sampled data.

## Hardware used ( available at [Nooelec](https://www.nooelec.com/store/) ):

- Nooelec NESDR SMArt v4
- HackRF One

## Test target:
 
- HYUNDAI i10 Car (2019, Second generation)

## Disclaimer

This flowgraph is provided for testing purposes only. Check local and federal regulations and obtain permission before using.
