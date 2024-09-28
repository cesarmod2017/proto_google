## Introduction
Public interface definitions of Google APIs for Dart and gRPC.

This package is a fork of the [protobuf_google](https://pub.dev/packages/protobuf_google) package. The original repository can be found [here](https://github.com/xclud/dart_protobuf_google).

### Purpose of the Fork
Was not maintained from the last three years and using old protobuf as the dependency

## Getting started

In your `pubspec.yaml` file add:

```dart
dependencies:
  proto_google: any
```

## Usage

```dart
import 'package:proto_google/proto_google.dart';
```
- If you are using the generated files from the `.proto` file and using any Google Pre-Defined DataTypes.
Update the generated `.dart` as follows
```dart
import 'google/protobuf/any.pb.dart' as $0; // Just an example
```
with 
```dart
import 'package:proto_google/proto_google.dart' as $0;
```