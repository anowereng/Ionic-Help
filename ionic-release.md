## IONIC RELEASE APK



```
> ionic cordova build --release android
> keytool -genkey -v -keystore softifygeoacl-release-key.keystore -alias alias_name -keyalg RSA -keysize 2048 -validity 10000
> jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore softifygeoacl-release-key.keystore softifygeoacl-release-unsigned.apk alias_name
> zipalign -v 4 softifygeoacl-release-unsigned.apk SoftifyGeoAcl.apk
