# switchbot Custom Component

Unofficial, custom HA component which solves issues with the current default HA's integration. 
This is a identical copy of the official integration but contains the patched switchbot python implementation. 

This solves the issues of `Bluetooth command failed (code: 2, error: Attribute can't be read)`

The only change from official version is
1. Fix as applied in PR#3 
2. API of switchbotPatched is used instead of pySwitchbot

To install, copy the Git repo link into HACS, after reboot search for switchbotPatched under integrations

[More Info?](https://github.com/Switchbot-Python/.github/blob/main/profile/README.md)
