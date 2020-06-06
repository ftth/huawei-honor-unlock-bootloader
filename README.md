# Huawei-honor-unlock-bootloader (Python 3)

## Summary

After closing the official EMUI website, which allowed you to retrieve the code to unlock the bootloader of Huawei/Honor phones, here is a python script to retrieve it by yourself.

It uses a bruteforce method, based on the Luhn algorithm and the IMEI identifier used by the manufacturer to generate the unlocking code.

I've only had the opportunity to test it on my European version only:

- Huawei P20 Pro (not yet confirmed it works)

## Instructions

### Connecting a device in ADB mode

1. Enable developer options in Android.
   - Android One: Go to Settings > System > About device and tap ‘Build number’ seven times to enable developer options.
2. Enable USB debugging in Android.
   - Android One: Go to Settings > System > Developer options and enable USB debugging.
3. Connect your device to the computer and launch the application. The device is going to ask for authorisation, which you'll have to allow.
4. Wait for the application to detect your device. The device info should appear in the top left section.
