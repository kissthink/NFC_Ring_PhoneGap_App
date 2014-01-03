# Getting the development environment setup

Prereq to build cordova = NodeJS, linux, Java, Ant, Android dev environment, git

```
sudo npm install -g cordova
git clone https://github.com/mclear/NFC_Ring_PhoneGap_App.git NFCRingPro
cd NFCRingPro
cordova platform add android
cordova plugin add https://github.com/chariotsolutions/phonegap-nfc.git
cordova plugin add https://github.com/apache/cordova-plugin-device.git
cordova plugin add org.apache.cordova.dialogs
cordova plugin add org.apache.cordova.vibration
```
