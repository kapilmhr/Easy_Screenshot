# Easy Screenshot

Easy Screenshot for Flutter


A flutter package to convert any widget as image


## Installation

Add below line to your `pubspec.yaml` and run `flutter packages get`
```
  easy_screenshot: ^latest version
```


# Flutter Usage
```
//Import the package
import 'package:easy_screenshot/easy_screenshot.dart';
```
```
//add a EasyScreenshotController to control the trigger
EasyScreenshotController _controller = EasyScreenshotController();
```
```
// create a EasyScreenshot widget in a widget tree
            EasyScreenshot(
              controller: _controller,
              child: const Text(
                'Easy Screenshot',
                style: TextStyle(fontSize: 40, fontWeight: FontWeight.bold),
              ),
            )
 ```
 ```
//trigger a screenshot
 await _controller.capture();
 
```
