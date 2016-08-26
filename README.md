
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/TPGSwift.svg)](https://img.shields.io/cocoapods/v/StickyHeader.svg)
[![Platform](https://img.shields.io/cocoapods/p/TPGSwift.svg?style=flat)](http://cocoadocs.org/docsets/StickyHeader)

# StickyHeader

Simple library based on work done on [MXParallaxHeader](https://github.com/maxep/MXParallaxHeader) helping to 
create a sticky header for an UIScrollView.

## Installation

### CocoaPods

```
pod "StickyHeader"
```

### Carthage
```
github "yageek/StickyHeader"
```

## Usage

To add a sticky header:

```swift

// Create the header
let view = UIView(frame: CGRect(x: 0, y: 0, width: 0, height: 100))
view.backgroundColor = UIColor.blueColor()
view.translatesAutoresizingMaskIntoConstraints = false

// Add the header to the table view
self.tableView.stickyHeader.view = self.headerView
self.tableView.stickyHeader.height = 200
self.tableView.stickyHeader.minimumHeight = 100
```

## Changelog

 - 1.0.0: First release.

## License

TPGSwift is released under the MIT license. See LICENSE for details.