![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg)

# A Digitally Assisted Integer-N Charge-Pump PLL with Automatic VCO-Band Calibration and Dual-Mode Loop-Bandwidth Control

- [Read the documentation for project](docs/info.md)  

**DAPLL-130** is a programmable integer-N charge-pump PLL designed in 130-nm CMOS for Tiny Tapeout.

The design combines an analog PLL core with digital calibration and control logic to improve startup reliability and support programmable clock generation.

## What is Tiny Tapeout?

Tiny Tapeout is an educational project that aims to make it easier and cheaper than ever to get your digital designs manufactured on a real chip.

To learn more and get started, visit https://tinytapeout.com.


## Key Features

- Integer-N charge-pump PLL
- Coarse/fine ring-VCO tuning
- Automatic VCO-band calibration
- Programmable feedback and output dividers
- Acquisition and tracking loop modes
- Lock detection and automatic reacquisition
- Divided-clock and internal-state debug outputs

## Architecture

The main blocks are:

- Phase-frequency detector
- Programmable charge pump
- Passive loop filter
- Digitally controlled ring VCO
- Feedback and output dividers
- Calibration and lock-control logic
- Test and debug interface
