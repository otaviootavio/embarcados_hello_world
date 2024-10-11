## Start tutorial
1. Follow this tutorial to get started with ESP-IDF:

https://docs.espressif.com/projects/esp-idf/en/stable/esp32/get-started/linux-macos-setup.html

2. Then run `get_idf`
3. Run `idf.py build` to build the project
4. Run `idf.py -p PORT flash` to flash the project
5. Run `idf.py -p PORT monitor` to monitor the serial output

Note: You can combine building, flashing and monitoring into one step by running:
```Bash
idf.py -p PORT flash monitor
```


## Conections
Trigger --> 22
Echo --> 23