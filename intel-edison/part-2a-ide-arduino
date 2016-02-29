# Arduino IDE:
- Download: https://www.arduino.cc/en/main/software

## Setup the IDE to work with the Intel Edison (not a standard install)
- https://software.intel.com/en-us/get-started-arduino-install#OSX
- I used the 1.6.7 option on the boards manager.
- After a few hours of fiddling with it I found out I was using the wrong serial connection.
- See: http://rexstjohn.com/fixing-retry-0-got-timeout-with-intel-arduino-ide-and-galileo-edison/
- The connection isn't the same one you would use with the screen command on the terminal.
- The blink sketch that ships with Arduino should now blink a LED on the board without any setup.

## Basic blinking light project:
- https://software.intel.com/en-us/get-started-arduino-blink
- NOTES:
- LEDs are diodes and cannot be put backwards (just try a direction if you are using the Grove starter kit)
- LEDs need resistors if you are buiding your own or they burn up

## Usless Tip if you have to use 1.6.2 version:
- Which I don't recommend because it is all sorts of broken with my board.
- See: https://communities.intel.com/thread/93908?start=0&tstart=0
- Go to ~/Library/Arduino15/packages/Intel/hardware/i686/1.6.2+1.0/libraries/Wire
- Rename this file: `mv libraries.properties library.properties`
- The error should go away but there are many others I didn't solve.
