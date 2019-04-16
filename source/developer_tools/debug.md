---
id: debug
title: Debug a DApp
---
# Debug a DApp

You can debug your DApp from the confort of your browser. Simply make sure that:

* your phone is connected to your WIFI
* you are using a nightly build with dev mode enabled

### iOS & Safari

It's possible to debug WebView contents in the iOS simulator or on a device using Safari Developer Toolkit.

#### Steps:

1. Open Safari Preferences -> "Advanced" tab -> enable checkbox "Show Develop menu in menu bar"
2. Start status in dev mode
3. Safari -> Develop -> [device name] -> [app name] -> [url - title]
4. You can now debug the WebView contents just as you would on the web

##### Note:

When debugging on device you must enable Web Inspector in your device settings:

Settings -> Safari -> Advanced -> Web Inspector

### Android & Chrome

It's possible to debug WebView contents in the Android emulator or on a device using Chrome DevTools.

1. Start status in dev mode
2. Chrome -> DevTools -> Menu (3 dots) -> More tools -> Remote devices
3. Select your device on the left and select "Inspect" on the WebView contents you'd like to inspect
4. You can now debug the WebView contents just as you would on the web

![image](https://user-images.githubusercontent.com/1479215/47129785-9476e480-d24b-11e8-8cb1-fba77ee1c072.png)
