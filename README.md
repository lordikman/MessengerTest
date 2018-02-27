# Messenger for iOS

[![Telegram](https://img.shields.io/badge/Telegram-lordikman-blue.svg?style=flat)](https://t.me/lordikman)
[![Swift 4](https://img.shields.io/badge/Swift-4.0-orange.svg?style=flat)](https://swift.org)
[![VK](https://img.shields.io/badge/VK-Евгений_Шепелев-blue.svg?style=flat)](https://vk.com/borsh_man)



Messenger for iOS is a real time chat app based on Firebase developed by [Lordikman](https://vk.com/borsh_man) and written in Swift 4.

<h3 align="center">
<img src="screenshot.jpg" alt="Screenshot of Messenger for iOS" />
</h3>

## Getting Started

To get started and run the app, you need to follow these simple steps:

1. Open the Messenger workspace in Xcode.
2. Change the Bundle Identifier to match your domain.
3. Go to [Firebase](https://firebase.google.com) and create new project.
4. Select "Add Firebase to your iOS app" option, type the bundle Identifier & click continue.
5. Download "GoogleService-Info.plist" file and add to the project. Make sure file name is "GoogleService-Info.plist".
6. Go to [Firebase Console](https://console.firebase.google.com), select your project, choose "Authentication" from left menu, select "SIGN-IN METHOD" and enable "Email/Password" option.
7. Open the terminal, navigate to project folder and run "pod update". 
8. You're all set! Run Quick Chat on your iPhone or the iOS Simulator.

## Compatibility

This project is written in Swift 4.0 and requires Xcode 8.2 to build and run.

Messenger for iOS is compatible with iOS 9.1+.

## Author

* [Lordikman](https://vk.com/borsh_man)

## License

Copyright 2018 Evgenii Shepelev.
