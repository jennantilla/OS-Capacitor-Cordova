## Capcitor/Cordova App

This is a simple Capacitor app that illustrates how to integrate the OneSignal SDK.

### Running this example

To run the provided example, can use serve command:

```bash
npx cap serve
```
#### Getting Started with a new Android app - Cheat Sheet

1. Create a simple capacitor project through command line.
```npx @capacitor/cli create```

2. Add android plugin to the created project
```npx cap add android```

3. Install onesignal cordova plugin inside project
```npm install onesignal-cordova-plugin```
```npx cap sync```

4. Confirm Cordova version:
```npx cap ls```

5. Open project in Android Studio
```npx cap open android```

6. Add [intialization code](https://documentation.onesignal.com/docs/ionic-sdk-setup#android-requirements) to the bottom of the .js file that loads on app launch (note that this example app has upgraded from Cordova 2.x.x to 3.x.x so init code is different)

7. Run app and register user!
