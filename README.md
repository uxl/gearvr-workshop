##System Dependencies:

Download Unity  
http://www.unity3d.com  

Oculus Mobile SDK  
https://developer.oculus.com/downloads/mobile/1.0.0.1/Oculus_Mobile_SDK/  

Java Development Kit 8 (JDK)  
http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html  

Android Studio - SDK 5.0 and SDK Tools  
http://developer.android.com/sdk/installing/index.html

- At the bottom of the splash screen you can access SDK Manager to install ADB

<img width="645" alt="custompackage" src="https://cloud.githubusercontent.com/assets/2991299/15237116/360b6f24-1899-11e6-9922-7171c3094d9f.png">

####or


1. `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. `brew install android-platform-tools`  
  
<BR>
Get OSig file:  

1. connect mobile device  
2. `adb devices`
3. generate file:   
https://developer.oculus.com/osig/

Store this signature file in a safe location. Whenever you want to allow an application to use VR functionality, place a copy of this file in your application’s assets folder then recompile and sign your APK.


##Development environment

1. `git clone https://github.com/uxl/gearvr-workshop.git`
2. `cd gearvr-workshop`

##Deploy to device
1. In Unity Build
2. `adb install my.apk`

