# icon-resizer
Automatically resizes icons for your Xcode project

## How?
The Swift script takes the path to a large app artwork icon (typically 2048x2048) as its first argument. The second argument is the path to your `AppIcon.appiconset` in your Xcode project. Then, the large icon is simply resized to fit all the sizes selected in Xcode. It's like magic!

## Usage
```
$ swift generate-icons.swift <path/to/largeIcon.png> <path/to/Assets.xcassets/AppIcon.appiconset>
```
