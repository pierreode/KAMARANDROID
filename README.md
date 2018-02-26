cd into dir

Increase android-versionCode in config.xml

cordova build android --release

jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore <key path its in the key folder> <PAth to the release APK> KAMAR


cd ~/Library/Android/sdk/build-tools/{latest version}

./zipalign -v 4 <Path to the apk> <Path to output>