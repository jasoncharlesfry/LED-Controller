This is a three channel analog LED dimmer. It operates at 15-60V and 1A per channel. It is based on the iw339 PWM controller IC. There is no current regulation so this board is only appropriate for LEDs with current-limiting resistors.

The pulse width of each channel is controlled by a 100k potentiometer. It is easier to control the brightness precisely with an audio taper pot. 

The board has positions for 4 switches. SW0 breaks VIN for all channels. SW1, SW2, and SW3 break VIN for channels 1, 2, and 3 respectively. All of the switches are optional and may be replaced with jumper wires depending on what is convenient for the application. 

The mosfet listed on the bom may not be in stock and can be replaced with any TO-252 mosfet with appropriate specifications (the threshold should be below 5V, Vgs-max should be above 15V, Vds-max should be above VIN, and Id-max should be above the current drawn by the LEDs).

Do not replace the fuse with a jumper. Use an appropriately sized 2AG fast-blow fuse.