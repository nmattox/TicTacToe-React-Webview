# Tic-Tac-Toe React Webview App

This app is built in react that can run in a browser or on a native app's webview. This includes both iOS and Android builds..

## Requirements 

* Node.JS 
* NPM
* NVM (recommended)

## Directories

* *my-app:* React app source code for Tic-Tac-Toe game 
* *android-app:* Android studio project for webview react app
* *ios-app:* iOS Xcode project for webview react app 

## Instructions

* Open `/my-app/src/index.js` and add web mParticle API key 
* Navigate to `/my-app` in terminal
* Once in directory, enter the following `$ npm start`
* The React app should start in your default browser - web events should show up in mParticle
* For Android, navigate to `/android-app/app/src/main/java/com/example/nmattox/tictactoe/MainActivity.java` and add the Android mParticle API key and secret 
* Run the Android build; Android events should show up in mParticle 
* For iOS, navigate to `/ios-app/ios-app/AppDelegate.swift` and add the iOS mParticle API key and secret. Additional configurations might be needed given the environment; follow and resolve error messages. 
* Run the iOS build; iOS events should show up in mParticle


