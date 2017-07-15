# splashscreen
Android O screen orientation issue demonstration

Rotate the device or the emulator into the landscape position and launch the application.
 
Actual result:
MainActivity opens in landscape mode and only after that its orientation changes to portrait.
 
Expected result:
MainActivity never opens in landscape, because this may affect the size of UI elements in this activity.
