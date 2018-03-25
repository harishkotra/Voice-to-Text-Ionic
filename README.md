# Voice to Text App using Ionic Framework

This is a working example app for iOS and Android using Ionic Framework to convert voice to text on the fly. 

  - iOS doesn't end speech recognition by itself. Which is why we need a button to stop listening to the user.
  - Uses cordova-plugin-speech-recognition

### Demo

![Voice to Text App Demo](https://i.imgur.com/RSK9nMb.jpg)

### Installation

This app requires [Node.js](https://nodejs.org/) v7+, cordova and ionic framework to run.
Install the dependencies and build the app. 

```sh
$ git clone this repository
$ cd app-folder-name
$ npm install -d
$ ionic cordova platform add android/ios
$ ionic cordova run/build android 
```

**Free Software, Hell Yeah!**

**Credits:** Built using this [tutorial](https://ionicacademy.com/ionic-speech-recognition/)
