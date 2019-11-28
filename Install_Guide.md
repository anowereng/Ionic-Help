### Setup Process
```
  android studio, vscode, jdk install
```
### NPM install process
```
 npm install -g ionic 
 npm install
```

### location set
```
 set GRADLE_HOME="C:\Program Files\Android\Android Studio\gradle\gradle-5.1.1"
 set ANDROID_HOME="C:\Users\AnowerUllah\AppData\Local\Android\Sdk"
 set PATH=%PATH%;%ANDROID_HOME%\tools;%ANDROID_HOME%\platform-tools
```
###  java version set and check

- java -version ( this code java version checking )

### npm cordova install and cordova add for android 
```
- H:\IONIC\(your project)>  npm i -g cordova

( If get this error error: ps1 cannot be loaded because the execution of scripts is disabled on this system [duplicate] )
-  Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned

- ionic cordova platform add android
```
### license java acceptence

- C:\Users\AnowerUllah\AppData\Local\Android\Sdk\tools\bin>sdkmanager.bat --licenses
``` 
( type y )
Accept? (y/N): y
All SDK package licenses accepted

```
