# HARP-FoxMikeAlpha
Create a simple, VHF/UHF cross-band FM voice repeater amateur radio payload for CubeSats.

# Requirements:
* VHF/UHF full-duplex cross-band FM voice repeater, supporting custom frequency selection within the respective amateur radio bands and CTCSS uplink functionality.
* Track number of times microcontroller reboots
* Measure current temperature
* Transmit station ID, current temperature, and MCU reboot number over AX.25 with AFSK modulation on periodic basis.
* External watchdog to monitor and prevent MCU system lockups
* Flexibility to accept range of supply voltages (3.8Vmin to 32Vmax)
* Ability for host to initiate or terminate function
* PC/104 footprint

# Status
In development
