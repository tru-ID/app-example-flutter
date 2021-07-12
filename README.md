# Phonecheck Flutter Sample App

This Flutter sample project demonstrates how to use the trusdkflutter plugin and is also embedded within it. 

## Getting Started

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Installation

Before you begin, you will need to:
- Install [Flutter](https://flutter.dev/docs/get-started/install)
- Set up an [editor](https://flutter.dev/docs/get-started/editor)
- Install the [Flutter and Dart plugins](https://flutter.dev/docs/get-started/editor?tab=androidstudio)
- For iOS: Xcode 12+ required
- For Android: Android Studio version 3.0 or later
- For Tru.ID PhoneCheck: Make sure you have your tru.ID local tunnel base set up and the baseURL on the lib/main.dart file of the project is updated accordingly.

To add the package tru_sdk_flutter to your example project:
1. Depend on it 
   * Open the `pubspec.yaml` file located inside the app folder and add 
	`tru_sdk_flutter: ^0.0.1` 
     under the dependencies.  

&nbsp;
2. Install it 
* From the terminal: Run ‘flutter pub get’ **OR**
* From Android Studio/IntelliJ: Click **Packages get** in the action ribbon at the top of pubspec.yaml.
* From VS Code: Click **Get Packages** located in right side of the action ribbon at the top of pubspec.yaml.

&nbsp;
3. Import it
   * Add a corresponding import statement in your Dart code
  `import 'package:trusdkflutter/trusdkflutter.dart';`
&nbsp;
4. Stop and restart the app, if necessary

You might want to play with the example project, so here are the key files and project locations:

Use your favourite IDE to open the sample project folder. Or alternatively you can inspect the main dart file in the following location:\
phonecheck-flutter-example/lib/main.dart\
It may be a good idea to work on the native Android or iOS example projects in separate windows/IDEs. Android Studio will provide a banner suggesting this.

Android Example Project\
phonecheck-flutter-example/android

iOS Example\
phonecheck-flutter-example/ios

Don't forget to make sure Cocoapods installed on your machine.
