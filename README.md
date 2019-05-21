# ESPHome TTGO doorbell

To use this version, you need to set up two input_text entities in Home Assistant.
* If either of these are not blank, they will be displayed on the screen.
You can set these values in home assistant any way you like - ie. on the frontend, or in automations

If both the `input_text` are blank, you will get
* blank screen when no motion detected
* Tme and date will be displayed when motion is detected
