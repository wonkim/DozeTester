## How to test

1. Connect your device via ADB
2. Run this application on the device
3. Press button on the app's screen
4. Run adb shell dumpsys battery unplug
5. Turn off screen of the device
6. Run adb shell dumpsys deviceidle step until IDLE state
7. Check adb logcat and confirm ResponseCode:200 message
