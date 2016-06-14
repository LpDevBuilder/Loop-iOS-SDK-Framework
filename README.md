# Loop-iOS-SDK-Framework

The easiest way to integrate Loop iOS SDK framework in your project is using Carthage. [Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.

You can install Carthage with [Homebrew](http://brew.sh/) using the following command:

```bash
$ brew update
$ brew install carthage
```

To integrate the Loop SDK framework into your Xcode project using Carthage, specify it and it's dependency on Alamofire in your `Cartfile`:

```ogdl
github "Alamofire/Alamofire" ~> 3.4
github "LpDevBuilder/Loop-iOS-SDK-Framework" ~>2.0
```

Run `carthage update --platform iOS` to build the framework and drag the built `LoopSDK.framework` and `Alamofire.framework` into "embedded binaries".
