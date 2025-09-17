# Replacement LED Board for Flashlight

![LED stick](/images/led-stick.png)

This project provides a high-quality replacement LED board for a flashlight that can be found on for example aliexpress:
- [https://de.aliexpress.com/item/1005009771645768.html](https://de.aliexpress.com/item/1005009771645768.html)
- [https://de.aliexpress.com/item/1005009476677225.html](https://de.aliexpress.com/item/1005009476677225.html)

Flashlight features:
- Switching converters for 5 W charging
- Flicker-free dimming
- No distracting flashing modes
- Slots for two 18650 lithium-ion batteries

The flashlight uses two types of LEDs: an 8 cm LED stick and two LEDs at the top.

This board replaces the LED stick to allow the use of higher-quality LEDs.
After researching suitable options, I found **Bridgelux Thrive** LEDs to deliver some of the best white-light quality available.
A versatile, pleasant color temperature for general use is 3500 K.

## LED Specifications
- **Type:** Bridgelux Thrive BXEN-35S-11M-3C [Datasheet](https://www.bridgelux.com/sites/default/files/resource_media/DS312%20SMD%202835%20Thrive97%200.5W%203V%20150mA%20BXEN-XXS-11M-3C%20Rev%20C%2020220802.pdf)
- **Overview:** [https://www.bridgelux.com/thrive](https://www.bridgelux.com/thrive)
- 3500 K: CRI > 97, R1-R15 > 93 @ ~100 lm/W

## Ordering
I ordered the boards at JLCPCB including PCB assembly and global sourced parts.

## Project Structure
- kicad: KiCad 9 project
- kicad/production: JLCPCB export made by [Fabrication-Toolkit](https://github.com/bennymeg/Fabrication-Toolkit)
