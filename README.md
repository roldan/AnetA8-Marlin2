# AnetA8-Marlin2
Config files used for flashing Anet A8 
1. Download Marlin: https://github.com/MarlinFirmware/Marlin.
2. Get config files (`Configuration.h`, `Configuration_adv.h` and `Statusscreen.h`) for your printer from https://github.com/MarlinFirmware/Configurations/archive/2.0.5.3.zip (for example: `config/examples/Anet/A8`) and copy them to `Marlin/` directory.
3. Use `Configuration.h`, `Configuration_adv.h` from this repo to enable custom features (bowden, z probe, etc...)
4. Open `Marlin.ino` with Arduino IDE, choose Anet 1.0 board and corresponding port.
5. Upload.
