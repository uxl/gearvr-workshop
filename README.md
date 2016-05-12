##System Dependencies:

Oculus Mobile SDK  
https://developer.oculus.com/downloads/mobile/1.0.0.1/Oculus_Mobile_SDK/  

Unity  
http://www.unity3d.com  

Java Development Kit 8 (JDK)
http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html  

Android SDK 5.0 and SDK Tools
http://developer.android.com/sdk/installing/index.html

1. `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. `brew install android-platform-tools`  
  
Get OSig file:  

1. connect mobile device  
2. `adb devices`
3. generate file: https://developer.oculus.com/osig/

Store this signature file in a safe location. Whenever you want to allow an application to use VR functionality, place a copy of this file in your application’s assets folder then recompile and sign your APK.


##Development environment

1. `git clone https://github.com/uxl/gearvr-workshop.git`
2. `cd gearvr-workshop`


