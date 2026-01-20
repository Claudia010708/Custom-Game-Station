# User Manual

# Installation Instructions

* Web Connection

1. Open the [Espruino Web IDE](https://www.espruino.com/ide/) on your browser
2. Connect your Puck.js to your computer via Bluetooth (Top-left button)
3. Load the firmware [main code](Code/HEIDI_Final_Code.js) into the Espruino Web IDE.
4. Check on the "Access files in device's storage" the presence of the (Switch Button code)[Code/SWBtn_Final_Version.js]. This code should be stored as "SWBtn".
5. Click the "Send to Espruino (Flash)" button in the IDE to upload the firmware to your Puck.js.
6. When the process is done, a message should appear in the console log in the right.

* Computer Connection

1. Click on the Top-Left button to disconnect temporanealy the microcontroller.
2. Now connect it via traditional Bluetooth of your own PC.
3. Now the Game-Station is ready to be used.


# Element description

The core element is a custom joystick cap, designed to fit onto a personal wheelchair-joystick, with a Puck.js chip inside. This chip works as a sensor: it detects the joystick movements and translates them into different game actions.
Furthermore there is a special cover, which contains the batteries for joystick power supply, host a so-called cover-button, and provide the link for the side-knee-button. This last button is meant to be positioned near the knee, under the cover.

* Detailed functions

Before playing a calibration step is required. By performing a long press (~ 2 seconds) on the cover button, the system automatically execute the calibration of the Puck.js’ accelerometer to ensure that joystick movements are interpreted correctly and precisely. After this step the game station is ready to be used. It is also possible to perform the calibration at anytime, by a long press of the cover button.

* Side-knee-button
A short press of this button (1 click) is translated into the left click of the mouse, so make the player interact with the game environment. A double press of this button (double click) will change the joystick behaviour: this feature let the player change between the movement control (the WASD keys) and the perspective point of view (the mouse movement), and vice versa. This allows the player to navigate and look around using the same joystick without needing extra devices.

* Top cover-button
A short press of this button (1 click) is translated into the TAB button of the keyboard. This is just a shortcut to let the player be able to open the map in the game with less effort. As already said, the long press of this button perform the calibration of the accelerometer.

* Other aspects
The 3 wires between the joystick and the cover must match their color type (Black, Blue, Red): one for battery supply, and one for each button.
Inside the cover there is the space for batteries: they are AAA battery (1.5 V each). In this way they could be replaced easily
The cover has to be fixed in place: for this reason, an elastic bandage is helpful and provide stability to the system.
