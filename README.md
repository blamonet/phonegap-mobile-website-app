phonegap-mobile-website-app
===========================

An easy example of how to wrap any mobile website into a mobile app with Phonegap/Cordova.

Initial Set-up / Add InAppBrowser Plugin:
 - phonegap local plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-inappbrowser.git
 - phonegap local plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-network-information.git

Compiling:
 - phonegap build ios
 - phonegap build android

to run in Xcode: 
 - open platforms/ios/Mobile_WebSite_App.xcodeproj/
