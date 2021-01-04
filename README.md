# BTC-price-ticker-V2_1-TTGO-T-Display

<br>
<b>Update with new Coinmarketcap2 API key</b>
<br>
<b>Important: update the to new libraries Coinmarketcap2 and ArduinoJSON 6.x</b>
<br>
<br>
Simple Bitcoin price ticker by using TTGO T-Display ESP32 and 1.14 Inch Display with CoinMarketcap API for Arduino IDE
<br>

<br>
<br>

* * *

<b>Index of this project</b>

+ [Add ESP32 Arduino IDE](#ESP32)
+ [Libraries for Arduino IDE](#libraries)
+ [Case information](#case)

* * *
<br>
<a name="ESP32"></a><h2>Add ESP32 in Arduino IDE</h2>

Before we can start compiling, the Arduino IDE must have the TTGO-T-Display board, based on an ESP32 in the board selection available.
The instruction on https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
In board selector you can select "ESP32 Dev Module" for TTGO-T-Display.
<br>
<br>
For MAC users install the "CP210x USB to UART Bridge VCP Drivers" from Silicon Labs, the port to select is /dev/cu.SLAB_USBtoUART in Arduino IDE under tools-->Port
<br>
https://www.silabs.com/community/interface/knowledge-base.entry.html/2017/01/10/legacy_os_softwarea-bgvU
<br>

<a name="libraries"></a><h2>Libraries for Arduino IDE</h2>
Now we add libraries for Arduino IDE 1.8.7:<br>
The new api requires a developer key, so you must apply for a key to use https://pro.coinmarketcap.com/account
<br>

+ [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) 
+ [CoinMarketCapApi.h](https://github.com/lewisxhe/CoinMarketCapApi2) Version 2
+ [ArduinoJSON](https://github.com/bblanchon/ArduinoJson) version 6.x is testet 
   
The instruction for the "TFT_eSPI" and TTGO-T-Display can be found here https://github.com/Xinyuan-LilyGO/TTGO-T-Display<br>
If you are have problem with the "wifi.h" delete the arduino/libraries/wiFi directory, you can use the esp32 WiFi.h
<br>
<br>
<a name="case"></a><h2>Case information</h2>
