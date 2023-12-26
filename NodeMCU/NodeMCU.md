# GreenPAK Based Binary Clock
_Main project to make a binary clock using NodeMCU_

## What's the project about?
The idea of the project is to make a binary clock using the following components:
- NodeMCU
- ESP8266 microcontroller

This clock sends an NTP request via WiFi and receives the current time, which is immediately converted into binary format and displayed using LED strips.

## Known issues
- In the middle block (minutes), every time any of the three last LED strips receive an active bit, they all start flickering until they all become "0s". It is still unclear whether the problem root is hardware or code; perhaps we assume it's hardware;
- There was an idea to implement DST. However, a popular Arduino library **Timezone.h** is not compatible with ESP8266, making implementing the idea challenging.

## Demonstration
https://github.com/EugeneBewz/Binary-Clock/assets/116636070/60d2b191-56d9-45cc-a7c2-385d9c061347

