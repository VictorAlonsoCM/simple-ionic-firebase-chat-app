# simple-ionic-firebase-chat-app

This project was created using Ionic 3 and Angular 5 and with an implementation of Firebase for saving our data.

The source code is part of [Build Ionic 3, Angular 5 and Firebase Simple Chat App](https://www.djamware.com/post/5a629d9880aca7059c142976/build-ionic-3-angular-5-and-firebase-simple-chat-app) tutorial.

To run on the device:

* Clone this repository
* Run this command `npm install`
* Modify `src/app/app.component.ts` then change Firebase parameters to meet your Firebase account
```ts
  const config = {
    apiKey: 'YOUR_APIKEY',
    authDomain: 'YOUR_AUTH_DOMAIN',
    databaseURL: 'YOUR_DATABASE_URL',
    projectId: 'YOUR_PROJECT_ID',
    storageBucket: 'YOUR_STORAGE_BUCKET',
  };
```
* Run this command `ionic cordova platform rm android`, `ionic cordova platform add android`, `ionic cordova platform rm ios`, `ionic cordova platform add ios`
* Run this command `ionic cordova run android` or `ionic cordova run ios`

Or if you do not want to generate a mobile file, then run this command to see the application in your browser `ionic serve`