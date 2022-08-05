Cordova/Phonegap Diagnostic Plugin Example
==========================================

This repo contains an example project which illustrates use of the [Diagnostic Cordova/Phonegap plugin](https://github.com/dpa99c/cordova-diagnostic-plugin) to request Android runtime permissions.

# Android runtime permissions

Android 6 / API 23 introduced the concept of [runtime permissions](http://developer.android.com/training/permissions/requesting.html). Similar to iOS, certain "dangerous" permissions must be requested at runtime __in addition__ to being listed in the Android manifest.

Runtime permissions only apply if the device/emulator the app is running on has Android 6.0 or above __AND__ the app is built using API 23 or higher.
For Cordova, this means using the Cordova Android platform [version 5.0.0](https://github.com/apache/cordova-android/tree/5.0.x) or above. 
If the app is built with version 4.x or below (API 22 or below), runtime permissions do not apply - all permissions are granted at installation time.


# Downloading

To download the example project, clone it using git:

    $ git clone https://github.com/dpa99c/cordova-diagnostic-plugin-android-runtime-example.git

# Building and running

To run on the Android platform, execute the following commands from the project root:
- Install the latest Cordova Android platform into the projece: `$ cordova platform add android@latest`
- Build and run the project: `$ cordova run android`

# License
================

The MIT License

Copyright (c) 2022 Dave Alden / Working Edge Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
