## Members
Tyler Wells, Electrical Engineering (2025)
tylermwells@vt.edu

## Mentor
Formally Richard Gibbons

## Current Status
IN PROGRESS

## Project Overview

This project will take a 5-volt source and run a fan based on temperature change. When the temperature is high, the fan will spin faster and when the temperature is low, the fan will spin slower. On top of this circuit design, there will also be an LCD screen that will read the temperature currently and show the current filament that is present inside the system. Another reading that I want to know is when the print is done so that the system can go back into the selection screen. 

## Educational Value Added

This project will teach me how to use an ESP32 and learn how to use the program on a system that relies on the current temperature to run. 

## Tasks

1 - Build the temperature sensor and screen on Arduino and then switch it over to ESP32 ||
2 - Integrate OLED display into new design ||
3 - Test the design on an ambient temperature of 40 C ||
4 - Add a joystick to give selection functionality ||
5 - Populate a PCB with the design and then test ||

## Design Decisions

After consideration and research, using a 555 Timer would help in implementing the PWM, however, it will be rather difficult to achieve near maximum PWM, so I will switch my focus on trying to achieve a PWM through the ESP32 Devkit. That way I can also use a temperature sensor and integrate it into the microcontroller. 

I also am going to add a better screen to the overlay. I want to do this so that I can display different options in the future if I want to print different filaments and need different ambient temperatures. 

## Design Misc

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Steps for Documenting Your Design Process

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## BOM + Component Cost

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Timeline

10/19/23 - Today I began the preliminary ideas for building this device. I consulted how to use a 555 timer and will begin to work on a testing design to understand the functionality of a 555 timer before moving on to the actual circuit design

1/10/24 - Today I updated the README and talked about how a 555 timer would be a problem to produce a high enough duty cycle that I want to achieve. Instead, I want to now focus on using an ESP32 to give the PWM that I want to achieve. I've also updated what I want to add to the current design and changed the tasks in which I will do this. 

## Useful Links

Useful Book: The Art of Electronics (3rd Edition)

## Log

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->
