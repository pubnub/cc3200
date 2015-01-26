# Please direct all Support Questions and Concerns to Support@PubNub.com

### PubNub SDKs for TI LaunchPad CC3200 via Energia
Learn more at http://www.pubnub.com

## CC3200 with PubNub

This demo app will stream accelerometer and temperature data via the PubNub Data Stream Network. 

It uses the PubNub Arduino client, tweaked for use with WiFi (per the instructions on the PubNub Arduino webpage: https://github.com/pubnub/arduino)

In addition, it uses a tweaked version of the Adafruit temperature sensor, with the default address changed to that of the sensor's default address on the CC3200.
 We also remove an AVR-specific delay library include.
 
This should be enough to get you started with the TI CC3200 Launchpad via Energia with PubNub. For any other assistance with PubNub on this or any other MCUs, shoot us an email at support.

#### TODO
This demo uses the aJson lib, but there may be efficiencies to be gained by programatically assembling the JSON by hand instead.

# Please direct all Support Questions and Concerns to Support@PubNub.com
