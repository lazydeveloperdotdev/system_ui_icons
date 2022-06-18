## 0.0.1

# SystemUIIcons

[![Pub](https://img.shields.io/pub/v/system_ui_icons.svg)](https://pub.dartlang.org/packages/system_ui_icons)
[![License](https://img.shields.io/badge/licence-Apache2-green.svg)](https://github.com/rajyadavnp/system_ui_icons/blob/main/LICENSE)
[![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/rajyadavnp/system_ui_icons.svg)](https://github.com/rajyadavnp/system_ui_icons)
[![GitHub stars](https://img.shields.io/github/stars/rajyadavnp/system_ui_icons.svg?style=social)](https://github.com/rajyadavnp/system_ui_icons)

A growing collection of simple and consistent icons specifically designed for systems and products.

View and find icons at [System UI Icons](https://systemuicons.com/)

*⚠️ This is not an official SystemUIIcons package.*

## Features

- Animated, round dial and fully customizable
- Adapted with system theme and/or customizable with `TimeDropperThemeData`
- 3 different designs to choose from

| SystemUIIcons|
| ------------ |
|![PREVIEW](https://raw.githubusercontent.com/rajyadavnp/system_ui_icons/main/demo/image.png)|

## Getting started

- Add ```system_ui_icons: <latest_version>``` to ```pubspec.yaml```
- Run ```flutter pub get``` in the terminal in the project directory or select ```pub get``` from
  within   ```pubspec.yaml``` file
- Add import statement,

```dart
import 'package:system_ui_icons/system_ui_icons.dart';
```

## Usage

See [example](https://github.com/rajyadavnp/system_ui_icons/tree/main/example)

```dart
Widget build(BuildContext context) {
  return Icon(SystemUIIcons.plus); //Use SystemUIIcons class to access icon objects
}
```

