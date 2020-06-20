
### IONIC PUBLISH
- dotnet publish -o ..\project

### IONIC CORDOVA
- cordova plugin list
- cordova plugin remove <PLUGIN_NAME>

### IONIC EMULATOR Fake or Real Devices

- adb devices
- ionic cordova run android --target=e78ab88d
--ionic cordova run android --device= 192.168.0.106:5555 or emulator number
 
- ionic cordova run android --list  ( For list of all available devices, use)

### IONIC-REPAIR

 - ionic repair
 - npm -g install cordova@latest
 - cordova plugin add cordova-android-support-gradle-release
 - native-run android --sdk-info
 
 ## More Information
- native-run --list --verbose

### IONIC-LAB 
- npm install --save-dev @ionic/lab
- ionic serve -l

### IONIC - DEV APPS

- ionic serve --devapp

### IONIC - PRODUCTION

- ionic cordova run android 
- ionic cordova build android 

### IONIC - ROUTE
```
[routerLink]="['/', 'conveyance',data.LocationCustId]"

```
