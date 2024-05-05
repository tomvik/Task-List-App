# Task-List-App
Just playing around with ReactNative.

# Start developing

## Install Node.js
Go to https://nodejs.org/en/download

Install the correct version for your OS.

Once done, you should be able to run the the package manager on your machine.

For example in a terminal execute:

```bash
npm --version
```

Finally, run:

```bash
npm install npm -g
```

Since there's a bug in npm when installing it for the first time in Windows. See: https://github.com/npm/cli/issues/7089

## Install React Native Expo
Go to https://reactnative.dev/docs/environment-setup

1. Read through the instructions (summaried below).

_Go to step 5 if not creating a new app._

2. Execute to create the Expo app:

```bash
npx create-expo-app --template
```

3. When prompted to choose a template, pick `Blank (TypeScript)`.

4. Name the app `Task-List-App`.

5. Then change directory to the project and execute:

```bash
npx expo start
```

## Try it in Android or iOS

After running the above 5th step, you should get a QR code and a URL. Download the Expo App in your desired device, and with it either:
* Scan the QR code.
* Input the URL on a browser and when prompted use the app to open it.

## Emulate it with Android Studio

Follow these instructions: https://docs.expo.dev/workflow/android-studio-emulator/

Once Android Studio is installed and configured, and you have a device running, you can press `a` on the terminal where you started the expo app and it should load on your emulator.