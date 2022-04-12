# multiple image selector

## Introduction

This project provides an amaizing user interface for selecting multiple image both from the gallery or the camera.


### Example


```dart
import 'package:image/image_selector.dart';

class _HomeState extends State<Home> {
  List<File> imageList = List.of([]);

  @override
  Widget build(BuildContext context) {
    return Container(
      color: Colors.blue,
      child: Center(
          child: SizedBox(
              height: 150.h,
              child: ImageSelector(
                onError: (e) {
                  // Show an alertdialog with the error
                },
                imageList: imageList,
              ))),
    );
  }
}
```

![Screenshot](images/1.jpg) ![Screenshot](images/2.jpg) ![Screenshot](images/3.jpg) 

## Getting started

Run this command for installation
```
flutter pub add image_selector_widget
```

```
dependencies:
  image_selector_widget: ^0.0.1
```
