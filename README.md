# Phonecheck Flutter Sample App

This Flutter sample project demonstrates how to use the tru_sdk_flutter plugin and is also embedded within it. 

## Getting Started

Before you begin, you will need:

- For iOS: Xcode 12+ 
- For Android: Android Studio version 3.0 or later
- [Flutter](https://flutter.dev/docs/get-started/install) installed
- A mobile phone with mobile data connection.

## How to run the sample app

- Open the phonecheck-flutter-example folder with Android Studio
- Android Studio will notify you of updates to your package dependencies. Click **Pub get** in the action ribbon at the top of `pubspec.yaml`.
- This sample app uses the **tru.ID** dev server. To get setup:

   Create a [tru.ID account](https://developer.tru.id/signup).

   Install the tru.ID CLI via:

   ```bash
   npm i -g @tru_id/cli
   ```

   Set up the CLI with the **tru.ID** credentials which can be found within the tru.ID [console](https://developer.tru.id/console).

   Install the **tru.ID** CLI [development server plugin](https://github.com/tru-ID/cli-plugin-dev-server).

   Create a new **tru.ID** project within the root directory via:

   ```bash
   tru projects:create flutter-sdk-server --project-dir .
   ```

   Run the development server, pointing it to the directory containing the newly created project configuration. This will also open up a     localtunnel to your development server, making it publicly accessible to the Internet so that your mobile phone can access it when only connected  to mobile data.

   ```bash
   tru server -t --project-dir .
   ```

   In `phonecheck_flutter_example/lib/main.dart` , replace `base_url` with your development server URL.

- Run -> Run 

It may be a good idea to work on the native Android or iOS example projects in separate windows/IDEs. Android Studio will provide a banner suggesting this.

Don't forget to make sure Cocoapods installed on your machine.


## Meta

Distributed under the MIT license. See ``LICENSE`` for more information.

[https://github.com/tru-ID](https://github.com/tru-ID)

[swift-image]:https://img.shields.io/badge/swift-5.0-green.svg
[swift-url]: https://swift.org/
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE

