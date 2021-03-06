# Immersion-Bot
A Telegram bot running on an ESP8266 based Arduino that turns on and off my Immersion (water heater) switch using a small servo motor and 3d printed parts.

This project uses [Universal-Arduino-Telegram-Bot](https://github.com/witnessmenow/Universal-Arduino-Telegram-Bot) to communicate with Telegram.

#### Telegram Controls
![Telegram Controls](http://i.imgur.com/2Rh6lBg.jpg?2)

#### Bot
![Bot](http://i.imgur.com/tVKzGgU.jpg?2)

## Objective

During the summer months in my house we don't use our oil central heating which would normally heat our water, We instead use our immersion. The problem with this is that our immersion only has an "On/Off" switch. This means we cant set it to come on at certain times and we would often forget to turn it off before leaving the house which can be an expensive mistake as it uses a lot of electricity.

I wanted to create a device that would allow be to control the immersion from anywhere and give me the ability to add additional features (e.g. turn on the immersion for an hour and then turn it off again). I also didn't want to interfere with the electrics as it is a rented house.

#### Schematic
![Schematic](http://i.imgur.com/RmUluqB.png?3)

## Materials

Electronic Parts:
- 1 x [Wemos D1 mini](http://www.aliexpress.com/store/product/D1-mini-Mini-NodeMcu-4M-bytes-Lua-WIFI-Internet-of-Things-development-board-based-ESP8266/1331105_32529101036.html)
- 1 x [SG90 9G Servo](http://www.aliexpress.com/item/Free-Shipping-5PCS-LOT-SG90-9g-Mini-Micro-Servo-for-RC-for-RC-250-450-Helicopter/32349297925.html)

Optional Buttons:
- 2 x [Tactile switches](http://www.aliexpress.com/item/50PCS-Lot-6x6x11mm-4Pins-Tactile-Tact-Push-Button-Micro-Switch-Momentary-6-6-11mm-New-Wholesale/32505343187.html?spm=2114.01010208.3.51.5BGSw1&ws_ab_test=searchweb201556_8,searchweb201602_4_10037_10017_405_404_407_10033_406_10032_10040,searchweb201603_8&btsid=8f618b71-7f1e-4ea4-b8bb-aff559f398eb)
- 2 x [10k Resistors](http://www.aliexpress.com/item/100pcs-10k-ohm-1-4W-10k-Metal-Film-Resistor-10kohm-0-25W-1-ROHS/32577051768.html?spm=2114.01010208.3.1.oAPcGU&ws_ab_test=searchweb201556_8,searchweb201602_4_10037_10017_405_404_407_10033_406_10032_10040,searchweb201603_8&btsid=302d889c-aa1d-4fbc-b9b7-c9c94adad882)

3d Printed Parts:
- 1 x [Faceplate](https://tinkercad.com/things/k2JDIFO7pW1)
- 1 x [Button Extender](https://tinkercad.com/things/gs7M9aZtICs)
- 1 x [Servo Arm (Take the Servo Arm from this project)](http://www.thingiverse.com/thing:1156995)


Other:
- You may need longer faceplate screws (the screws that hold your switch in). Mine needed to be 10mm longer than the existing ones
- A bolt and two nuts to connect the Sevo arm and the Button Extender (I believe mine was a m4 bolt)
