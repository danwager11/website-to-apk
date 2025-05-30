Package name: 
change java/com/xxxxxx/webtoapk - folder name
change
  MainActivity.java
  UserScriptManager.java
    to package com.xxxxx.webtoapk;
change build.gradle namescape
change proguard-rules.pro
  -keepclassmembers class com.xxxxx.webtoapk.MainActivity {

URL and App Name: 
website-to-apk/.github/workflows/android.yml - change both
website-to-apk/app/src/main/java/com/myexample2/webtoapk/MainActivity.java String mainURL = "http://100.76.14.41:4567";
website-to-apk/app/src/main/res/values/strings.xml <string name="app_name">Suwayomi</string>

    

Logo:    
website-to-apk/app/src/main/res/mipmap/ - put logo here

website-to-apk/app/src/main/AndroidManifest.xml change name
