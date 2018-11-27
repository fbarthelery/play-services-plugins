# Google Play services Plugins

This project contains plugins to help with using Google Play services and
Firebase libraries.

## Changes

This is a fork of the library to use as a workaround for bug
https://github.com/gradle/kotlin-dsl/issues/1186

The only differences are:
    - oss-license-plugin depends on Android gradle plugin 3.2.0
    - oss-license-plugin release version 0.9.4.1 due to the previous change

This also add  a maven repository in the `repo` folder in order to publish version 0.9.4.1.


## Getting Started

The plugins contained in this project are meant to work with the Google Play
services SDK.  See https://developers.google.com/android/guides/overview to
get started.

## Contents

### strict-version-matcher-plugin

Helps with managing cross-library version dependencies between components.

### oss-licenses-plugin

Helps apps to display open source software licenses and notices.

### google-services-plugin

Required for firebase applications on android, converts google-services.json to a resource file for use by the app, and references the code in strict-version-matcher.

