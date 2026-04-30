Tasks:
- [ ] research if the available pins on the XIAO can do the WS2812 comms. (other than i2c or spi pins).

| Date       | Update                                                                                                                                                                                                                                    | comment                                                                     |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| 2025-12-14 | Ordered the dev boards, headers, and ws2812 LED dev boards to start the project off.![[Pasted image 20251214145521.png]]<br>![[Pasted image 20251214145633.png]]                                                                          | still need to find and order an oled screen and a temp sensor.              |
| 2025-12-14 | -Located footprint for mcu and placed in schematic.<br>-created git repo for this project called testboard.<br>-cloned seeed studio mcu repo and pinned the symbol library.<br>-installed and setup libraryloader for this kicad install. | need to research if the available pins on the XIAO can do the WS2812 comms. |
|            |                                                                                                                                                                                                                                           |                                                                             |
|            |                                                                                                                                                                                                                                           |                                                                             |


Decisions:
1. [x] Use a XIAO NRF52840 SENSE module to get the project off the ground from a hardware perspective.

Wants
1. Ring of programmable LEDs i.e SK1216mini-E leds
2. Single key or very few keys
3. Reset button
4. Battery
5. Temp sensor
6. Oled screen