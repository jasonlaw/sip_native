# sip_native

A native SIP flutter plugin

## Motivation
Currently our team is working on solution that requires and uses sip but available sip packages only support websocket and after struggles using it we were disappointed, so we decided to build one from scratch using [link here ](https://developer.android.com/guide/topics/connectivity/sip)

## Disclaimer
1. #### Android Supported Only
  Currently only android is supported even though flutter is fully cross platform
2. #### Support
  Even though the specs states the SIP API is available for Android devices from 2.3, it is not. The Android SIP API is not supported on all devices. Interestingly,   it is supported on my old 2.3 LG P970 and not my 4.4 Moto G. (By the way, you have to test on real device and not the Android emulator).
  Now there are alternatives:
  With the Android SIP API out, what are the alternatives? Well, there are a couple of open source SIP stacks for Android. The popular ones people talk about are:

- JAIN
- MjSIP
- PjSIP
- Doubango

more on this link: https://obem.be/2014/06/04/sip-on-android.html

## Getting Started

This project is a starting point for a Flutter
[plug-in package](https://flutter.dev/developing-packages/),
a specialized package that includes platform-specific implementation code for
Android and/or iOS.

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

