## Mobile Companion
![Static Badge](https://img.shields.io/badge/Android%20Test%20App-Kotlin)

This is a simple Kotlin Android app made to test the connection and messaging capabilities of the Wear OS Data Layer API.

Just like its Wear OS companion app, this app isn’t focused on UI, it is built to verify reliable communication between a phone and a paired watch.

[Demo Video](https://www.youtube.com/watch?v=i7tVZb8hycA)


## Features
- Connects with a paired Wear OS device.
- Sends custom messages from the phone to the watch.
- Receives and displays messages sent from the watch.


## Technologies Used
- Kotlin – Core programming language.
- Jetpack Compose – For minimal UI rendering.
- Wearable Data Layer API – Manages cross-device communication.
  - MessageClient – For sending/receiving messages to and from the watch.

## Permissions Used
```
<uses-permission android:name="android.permission.WAKE_LOCK" />
```

## Local Setup
To properly test this app, it must be paired with the [wear_companion](https://github.com/Abhishek14104/wear_companion) Wear OS project.

Steps:
Clone the Repository

```
git clone https://github.com/Abhishek14104/mobile_companion.git
```
Open in Android Studio

Run on an Android phone or emulator

**Make sure that your Android Device is connected to the WearOS Watch properly.**
