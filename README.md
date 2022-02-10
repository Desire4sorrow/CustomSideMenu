# ▤ SideMenu
[![CircleCI](https://circleci.com/gh/jonkykong/SideMenu.svg?style=svg)](https://circleci.com/gh/jonkykong/SideMenu)
[![Version](https://img.shields.io/cocoapods/v/SideMenu.svg?style=flat-square)](http://cocoapods.org/pods/SideMenu)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat-square)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/cocoapods/l/SideMenu.svg?style=flat-square)](http://cocoapods.org/pods/SideMenu)
[![Platform](https://img.shields.io/cocoapods/p/SideMenu.svg?style=flat-square)](http://cocoapods.org/pods/SideMenu)

Check out the example project to see it in action!

## Requirements
- [x] Xcode 11.
- [x] Swift 5.
- [x] iOS 10 or higher.

## Installation
### CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects. You can install it with the following command:

```bash
$ gem install cocoapods
```

To integrate SideMenu into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '10.0'
use_frameworks!

pod 'SideMenu'

# For Swift 5 use:
# pod 'SideMenu', '~> 6.0'

# For Swift 4.2 (no longer maintained) use:
# pod 'SideMenu', '~> 5.0'
```

Then, run the following command:

```bash
$ pod install
```

### Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.

You can install Carthage with [Homebrew](http://brew.sh/) using the following command:

```bash
$ brew update
$ brew install carthage
```

To integrate SideMenu into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "desire4sorrow/CustomSideMenu" "master"
```

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code and is integrated into the `swift` compiler. It is in early development, but SideMenu does support its use on supported platforms.

Once you have your Swift package set up, adding SideMenu as a dependency is as easy as adding it to the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
    .package(url: "https://github.com/jonkykong/SideMenu.git", from: "6.0.0")
]
```



## Known Issues
* Issue [#258](https://github.com/jonkykong/SideMenu/issues/258). Using `presentingViewControllerUseSnapshot` can help preserve the experience.

## Thank You
A special thank you to everyone that has [contributed](https://github.com/jonkykong/SideMenu/graphs/contributors) to this library to make it better. Your support is appreciated!

## License

SideMenu is available under the MIT license. See the LICENSE file for more info.
