

Fork Note:  This is a fork of https://github.com/wbt11a/cordova-plugin-wezka-nativecamera native camera plugin that supports both iOS and Android builds. This fork fixes the compile issues in Cordova 5 as reported at https://github.com/shaithana/cordova-plugin-wezka-nativecamera/issues/38.

To install use cordova add plugin https://github.com/rupendraa/cordova-plugin-wezka-nativecamera

com.wezka.nativecamera
==========================

This is a fork of the official camera plugin from Apache.  The custom camera portion is specifically for Android.  It is stock iOS / WP8 Camera calls otherwise.

It uses a custom activity to run in the foreground in Android to prevent Cordova from being killed.

It is adapted from https://code.google.com/p/foreground-camera-plugin/

It offers advanced features such as flash support (auto/on/off), the tap-focus/exposure and the correct handling of image rotation.


