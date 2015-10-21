# SmarterWRT

This project is used for a custom development board. Our internal project name is Morse.

Morse board consists of a WRTNode module and a TI CC3200 WiFi-SOC. There are some hardware modification to WRTNode, so that CC3200 can access SPI NOR Flash on WRTNode directly.

The purpose is that this Android App can connect to CC3200 through WiFi Direct and can download OpenWRT firmware to WRTNode.

This app starts from official SDK WiFiDirectDemo (legacy, API level 21, android 5.0).

Hope this information helps if you are interested in code or you have our Morse board.
