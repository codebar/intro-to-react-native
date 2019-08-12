# React native workshop

## Pre-requisites

Set up the environment:

```
brew install node
brew install watchman
npm install -g yarn
```

Then install react native:

```
npm install -g react-native-cli
```

#### To run iOS

You'll need to have a macbook with an up-to-date version of XCode installed.

#### To run Android

You can run Android on any platform, including Windows and Linux.

Download [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) and [Android studio](https://developer.android.com/studio/index.html) (make sure you install SDK 9 wheen installing Android studio).

Then add these variables to your `.bash_profile`:

```
export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools
```

## Does it work?

Check out this repository, install dependencies, and start the app:

```
git clone git@github.com:codebar/intro-to-react-native.git
cd ./intro-to-react-native
yarn
yarn react-native run-ios (or) yarn react-native run-android
```

#### Any issues?

If you find any issues setting up, check out the react native [installation guide](https://facebook.github.io/react-native/docs/getting-started). If you still feel stuck, get in touch with Kim Cook or Anna Doubkova at the Codebar slack.
