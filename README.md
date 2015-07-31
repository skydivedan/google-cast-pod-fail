# GoogleCastPodFail

## Usage

The purpose of this project is to demonstrate that it is difficult to use google-cast-sdk within another pod library, because Framework headers aren't available. The workaround is to use quoted headers, and to use each one individually.

To see the problem, look in the file named "ReplaceMe.m". This file belongs to the pod being developed. You'll see there are some commented out imports. Try uncommenting them, to use google-cast, and you get compile errors.

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

GoogleCastPodFail is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "GoogleCastPodFail"
```

## Author

Dan Morrow, dmorrow@dramafever.com

## License

GoogleCastPodFail is available under the MIT license. See the LICENSE file for more info.
