# stm32f103-usb-hidkeyboard
stm32f103 HAL usb hid keyboard

## key_report[8]

|        |              |
| :----: | :----------: |
| byte0  | ReportID |
| byte1  | Modifier Key |
| byte2  | RESERVED |
| byte3  | Key1 |
| byte4  | Key2 |
| byte5  | Key3 |
| byte6  | Key4 |
| byte7  | Key5 |



## How to build
connect stlink/stlinkv2 to debug wire pins and
```
make
make flash
```
