### uConsole Universal Expansion Board

This is a breakout board for the expansion board connector of the ClockworkPi uConsole. You can place small breakout boards into it, and connect them to the uConsole, internally.

| Item            | Link  |
| :---:           | :---: |
| Front           | ![Front](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/documents/uconsole-expansion-card-template.png) |
| Back            | ![Back](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/documents/uconsole-expansion-card-template.png)  |
| Schematic       | https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/documents/schematic.pdf |
| Exported files* | https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/export.zip              |

****This is a WIP.*** I need to receive the first batch I ordered to test everything is correctly. You can help me verify this files in the meantime. Use with caution.

### Examples of components you can mount on:
This is designed to work with breakout boards, like these:

| Item                               | Image                                         |       
| :---:                              | :---:                                         |
| USB - Anything                     | ![All_types](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/usb-all-types.png)        |
| USB-A                              | ![USB-A](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/usb-a.png)                    |
| USB-C                              | ![USB-B](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/usb-b.png)                    |
| USB-C                              | ![USB-C](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/usb-c.png)                    |
| RP2040                             | ![RP2040](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/rp2040-zero.jpg)             |
| ESP32                              | ![ESP32](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/esp32.jpg)                    |
| SD2emmc                            | ![SD2emmc](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/sd2emmc.png)                |
| USB2emmc                           | ![USB2emmc](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/usb2emmc.JPG)              |
| SD Card                            | ![SD_Card](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/sd_card.jpg)                |
| Arduino modules and breakout boards| ![Breakout_Boards](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/components/arduino_modules.JPG)|

... And almost everything!


### How to use the board ###
The intended use is to place the components in a way all the pins can be wired, and glue or solder them to the board. Then, you can draw traces of tin over the grid, like in this video:
https://www.youtube.com/watch?v=l9Kbr8cPqOE

However, I strongly recomend to better use wires. Wires can be bent, and can cross, and is less harmful to the board. You can bend and cross the wires like Ben Eater does for his breadboard computer.
![Wiring_1](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/wiring_example/be1.png)
![Wiring_2](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/wiring_example/be2.png)
![Wiring_3](https://github.com/crossplatformdev/uConsole-Universal-Expansion-Board/blob/main/wiring_example/be1.png)


### Example Recipes ###
- 2xUSB-C, 2xUSB-A (1 internal), USB2emmc (internal), Radxa emmc module.
- 3xUSB-C, 1xUSB-A (1 internal), RTL-SDRv4 (usb dongle, internal)
- RP2040 as board microcontroller + something.
- ESP32 as board microcontroller + something.
- ... expose microcontroller's GPIO through a horizontal pinheader!
- ... or add sensors and modules!
- ... spare data lines can be used as USB!
- You can try to replicate an existing expansion board with breakout boards with this!

(TODO) (First I need to receive the first batch. Star this repo to keep updated)
