# GreenPAK Based Binary Clock
_An additional experimental project to make a binary clock using Renesas' GreenPAK programmable device_

## What's the project about?
The idea of the project is to make a binary clock using the following components:
- GreenPAK programmable device (model SLG46620G)
- Go Configure Software Hub (GreenPAK Designer)

Although it is called a "clock", the more appropriate name would be a "clock-like counter", as it just counts like a clock from 00:00:00 to 12:59:59

## Known issues
- The current circuit design works perfectly except for one thing: once _pin 19_ is reached, it is never reset because _DFF11_ has no _nRESET_ and no alternative has been found yet. This makes the clock count from 0 to 12 on the first iteration and from 5 to 12 after it.

## Demonstration
- Seconds
https://github.com/EugeneBewz/Binary-Clock/assets/116636070/3a77fa00-95c4-4df0-abb8-0d558848f324

- Minutes / Hours

https://github.com/EugeneBewz/Binary-Clock/assets/116636070/52228b88-e318-4696-9cb7-bfda784927fa

