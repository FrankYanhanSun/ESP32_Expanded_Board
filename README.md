# ESP32 Expanded Board
This is an expanded board for [LCKFB-ESP32S3R8N8](https://jlcpcb.com/partdetail/lcscboards-LCKFBESP32S3R8N8/C20626143) which ia an open-sourced ESP32s3 minimum system board. You can find the schematic and PCB layout of the board [here](https://oshwhub.com/li-chuang-kai-fa-ban/li-chuang-esp32s3r8n8-kai-fa-ban). Hope you can have fun with this board!

<br>

## Features
- Power
  - 12V power input via XT30 connector (**3S battery supported**)
  - Dual 12V output via XH2.54 connectors
  - 12V to 5V DC-DC converter (TPS5450DDAR) supporting up to 5A current (**For output currents above 3A, solder mask openings with tin plating should be implemented on copper traces to enhance current handling. [More info and where the step-down converter circuit from](https://oshwhub.com/quan-guo-dian-sai/dian-sai-mo-kuai-tps5450-jiang-ya-mo-kuai)**)
  - Dual 5V output via XH2.54 connectors
- Peripherals
  - 12V bus servo ([Hiwonder HTS-20H](https://www.hiwonder.com/collections/bus-servo/products/hts-20h?variant=39700596916311) is recommended)
  - Dual 12V DC motors via XH2.54 connectors and PH2.0 connectors (motor driver: TB6612FNG)
  - One `SPI` via XH2.54 connector
  - Dual `I2C` via XH2.54 connectors (With another 4 pin header for a 0.96" OLED screen)
  - 14 GPIO pins with `5V` and `GND` (**`GPIO21`,`GPIO38-GPIO40`,`GPIO46-GPIO48` should not be used when the other connectors are in use**) 
  - `UART` pins for `TX`, `RX` and `GND`
  
<br>
  
If you find any issues for the board, please check the schematic and PCB layout first or contact me.
  
<br>
  
## File Structure
- `.epro`: Schematic and PCB layout for **Easy EDA**
- `.zip`: Schematic and PCB layout for **Altium Designer**

<br>
  
## Leave a star if you like it 🥰

<br>[![Star History Chart](https://api.star-history.com/svg?repos=FrankYanhanSun/USBhub&type=Date)](https://star-history.com/#FrankYanhanSun/USBhub&Date)
<br>
© 2025 Yanhan Sun (Frank).