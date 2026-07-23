<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

DAPLL130 is a programmable integer-N charge-pump PLL implemented in 130-nm CMOS.

A phase-frequency detector and charge pump control the ring-VCO through a passive loop filter. The VCO uses digital coarse tuning and analog fine tuning. At startup, the calibration logic selects a suitable VCO band before enabling normal phase locking.

The design also includes programmable feedback and output dividers, acquisition and tracking modes, lock detection, automatic reacquisition, and debug outputs.

## How to test

1. Apply power and reset through the Tiny Tapeout ASIC Dev Kit.
2. Provide an external reference clock.
3. Configure the divider ratios and operating mode.
4. Start automatic VCO-band calibration.
5. Check the lock-status output.
6. Measure the divided output clock and compare it with the programmed frequency.
7. Use the debug outputs to observe the selected coarse code and internal lock state.

Detailed pin assignments and control settings will be documented after final integration.

## External hardware

- Tiny Tapeout ASIC Dev Kit
- External reference-clock source
- Microcontroller or FPGA for configuration and measurement
- Arduino GIGA R1 is intended for automated testing
