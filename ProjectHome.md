# Project moved to github #
https://github.com/bitle/aGamepad

aGamepad allows you to use your Android based phone as gamepad for Windows.
It supports three analog axes and up to 32 buttons (currently implemented 4).

## Special thanks to: ##

### Tsutomu SEKI ###
Windows side of application is based on his sources.

### Deon van der Westhuysen ###
For writing such a great application as PPJoy.

## How to use ##
  1. Download aGamepad.apk and install it on your device
  1. Download PPJoySetup and install it on your PC
  1. Download controller.dll and extract it somewhere
  1. After installing PPJoySetup run **Configure Joysticks** (Programs->Parallel Port Joystick)
  1. Press Add
  1. Make sure that **Parallel port** field is set to _Virtual Joysticks_. Press Add
  1. Wait for drivers to be installed
  1. Choose currently added joystick from list and press **Mapping**
  1. Press Next
  1. Choose any number of axes (max 3)
  1. Choose number of buttons (currently max 4)
  1. Set POV to 0 and press Next
  1. Make sure there is for each axis set _Analog N_ and press Next
  1. Press Next and Finish
  1. Press Done
Now everything is ready for use
  1. Run **PPJoyDLL** (Programs->Parallel Port Joystick)
  1. Choose **DLL type** to _Callback DLL interface_ and press Load DLL
  1. Point the dll you saved earlier
  1. Now run **aGamepad** on your phone (assuming that you have connected with your PC using wifi)
  1. Enter IP address of your PC and press Ok
  1. If you see in PPJoyDLL's window line "Sending joystick updates to PPJoy" it means that everything works