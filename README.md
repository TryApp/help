## iOS install popup did not appear
If the iOS popup "**dl.dropboxusercontent.com would like to install…**" did not appear, check that you don't already have the same app installed from the AppStore.

If an app with the same bundle identifier is already installed on the device from the AppStore, nothing will happen.

Delete the app installed from the AppStore to be able to install this one.

## Unable to download app popup
If an "**Unable to download app**" popup appears after some time, first check your internet connection, and be sure that your device is not behind a firewall that may prevent downloading .ipa files.

Sadly, iOS won't give any detailed information on what went wrong. Check on the previous page if there are any warnings. Most common installation issues are:
- expired provisioning profile
- device UDID not in the provisioning profile
- incompatible device (check minimum iOS version, device family, required device capabilities and supported architectures)
- tapped install button multiple times
- device storage is full
- app is over 100 MB and downloaded over a cellular connection

## Untrusted Enterprise Developer
Starting from iOS 9, the developer has to be trusted by the device, otherwise a popup will appear and prevent using the app.

On iOS 9.0/9.1, go to Settings > General > Profiles > tap on the developer's profile, and tap on Trust.

On iOS 9.2+, go to Settings > General > Device Management > tap on the developer's profile, and tap on Trust.

## Nothing seems to happen
After tapping the "**Install**" button in the popup, if nothing seems to happen and you are on this page on "**Safari**", check your device's home screen: the installation should be in progress: you should see the icon of the app somewhere and a progress indicator.

## Otherwise
Contact your app developer, so they can double-check the app and provide you with support.
