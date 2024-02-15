
# Easy Screenshot

#### Easy Screenshot for Flutter


- [ ] 
- [ ] List item

A flutter package to convert any widget as image

![code](https://github.com/kapilmhr/Easy-Screenshot/raw/7cff7df1f2449ef14e2d39ff83368729315b4bb2/sc/code.png)


## Installation

Add below line to your `pubspec.yaml` and run `flutter packages get`
```  
easy_screenshot: ^latest version  
```  


# Flutter Usage
#### Import the package
```  
import 'package:easy_screenshot/easy_screenshot.dart';  
```  

#### Add a EasyScreenshotController to control the trigger
```  
EasyScreenshotController _controller = EasyScreenshotController();  
```  

#### Create a EasyScreenshot widget in a widget tree
```  
EasyScreenshot(  
controller: _controller,  
child: const Text(  
'Easy Screenshot',  
style: TextStyle(fontSize: 40, fontWeight: FontWeight.bold),  
),  
)
```  
#### Capture a screenshot

```  
File file = await _controller.capture();
```