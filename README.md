Changed fastboot oem unlock to fastboot oem unlock-go 
It now skips the confirm prompt that causes the following error
```
failed (write to device failed "(no link))"
```

# HuaweiBootloader_Bruteforce
Fastboot OEM Unlock Bruteforce Software

[![Build status](https://ci.appveyor.com/api/projects/status/d8ygs5lc7jl5cd14?svg=true)](https://ci.appveyor.com/project/Ayylmao6969/huaweibootloader-bruteforce)


## Summary
  
After closing the official HUAWEI website, which allowed you to retrieve the code to unlock the bootloader of Huawei/Honor phones, here is a Winbdows C# Program to retrieve it by yourself.
It uses a bruteforce method, based on the Luhn algorithm and the iMEI identifier used by the manufacturer to generate the unlocking code

## Instructions

1. Enable developer options in Android.  
2. Enable OEM Unlock option in developer options.  
3. Connect a device in FASTBOOT mode
4. Connect your device to the computer and launch the program.  
5. You must provide your device IMEI to the program.
6. Wait it out to finish going through about 200k possible unlock codes, it's going to take a while.

## Supported Devices:
All Huawei android phones pre 2019 models
Some 2019 Models with early security patchs and inital firmware version

Successfully unlocked a HUAWEI Y7 Prime 2019 with February Firmware version, Huawei removed their unlock code website, and eventually changed the booloader and digits-only unlock codes no longer seem to work

### AUTHOR: Ahmed Chakhoum
