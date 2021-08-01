# Flutter Starter Template

[![style: lint](https://img.shields.io/badge/style-lint-4BC0F5.svg)](https://pub.dev/packages/lint)

This is a starter template to build Flutter applications. It is heavily inspired by the learnings I made watching tutorials by [FilledStacks](https://www.filledstacks.com/) and [Reso Coder](https://resocoder.com/) so you might say that it is an opinionated template. If you intend to use this template, I highly recommend you to go watch some of their tutorials so that you can really understand what this package provides.

This template covers the basic configuration needed to start any type of Flutter project, but it may be more suited for Android and IOS applications.

## Getting Started

### Create your new repository

To use this template two options are available:

- The recommended option is to use the "Use this template" button to create a new repository from this one.
- You can also clone this repo locally and start from there.

### Retrieve the dependencies

This template comes with its fair share of useful dependencies and in order to use them, you must first run the command ```flutter pub get```.

### Change your package and bundle name

You will probably want to change the package and bundle name to use a unique custom one. To do so, I invite you to follow the steps provided by this StackOverflow discussion: [Change package name in Flutter](https://stackoverflow.com/questions/51534616/how-to-change-package-name-in-flutter) or use the following package: [change_app_ package_name](https://pub.dev/packages/change_app_package_name).

### Change app's launcher icon

This template uses the [flutter_launcher_icons](https://pub.dev/packages/flutter_launcher_icons) package to generate the icons. Here is the procedure to change the app icon:

- Replace the 4 images in the ```assets/launcher``` folder by your images. To learn more about the different proposes of the 4 images, I invite you to read  the package's documentation.
- Run the ```flutter pub run flutter_launcher_icons:main``` command.

### Setup complete

Everything is set to start your new project! You can now run your app and make sure that it is properly setup!

## Package used in this template

[flutter_launcher_icons](https://pub.dev/packages/flutter_launcher_icons): Command-line tool that make updating the app's launcher icon easy.

[get_it](https://pub.dev/packages/get_it): A service locator.

[stacked](https://pub.dev/packages/stacked): A MVVM architecture developed by the FilledStacks community.

[stacked_services](https://pub.dev/packages/stacked_services): A package that provides services to help with the implementation of the Stacked architecture.

[stacked_hooks](https://pub.dev/packages/stacked_hooks): A package that allows you to use the Flutter Hooks package with the Stacked architecture.

[flutter_hooks](https://pub.dev/packages/flutter_hooks): A Flutter implementation of React hooks.

[equatable](https://pub.dev/packages/equatable): Package that makes comparison between objects easier.

[dartz](https://pub.dev/packages/dartz): Functional programming in Dart.

[internet_connection_checker](https://pub.dev/packages/internet_connection_checker): Check accurately the connection status of the devices.

[lint](https://pub.dev/packages/lint): Community-driven collection of lint rules for Dart and Flutter.

[mockito](https://pub.dev/packages/mockito): Mock library for Dart.

[device_preview](https://pub.dev/packages/device_preview): Package that approximate the looks of your app on any device from any device.
