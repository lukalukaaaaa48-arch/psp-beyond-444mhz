# PSP Overclock Picker

This project is an attempt to define a ramp using the ratio 1.This project is an attempt to define a ramp using the ratio 1.0f, with the safest values. Those values are selected to reduce changes over the PLL register as much as possible, and to reduce imprecise float values at the same time. However, contrary to the experimental project using automatic ramp-up, the gap between those values is bigger.

## Usage

Before starting, make sure that no overclock plugin is enabled. It is best to start from a fresh reboot. Ideally, you should perform a reset by holding SELECT + START + △ (Triangle) + □ (Square) while powering on the device before and after using this program.

Copy the EBOOT and kcall.prx to the same folder in your `GAME` folder, then just run the program as any other homebrew. Press `Triangle` to start the increase the value, Press `Cross` to decrease the value.

Note: Keep in mind that it still needs improvement to get a more precise value.

## Disclaimer

This project and code are provided as-is without warranty. Users assume full responsibility for any implementation or consequences. Use at your own discretion and risk

*m-c/d*
