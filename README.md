<h1 align="center">SwiftUI OtpView/PinView</h1>
<p align="center">
  <img alt="Swift Package Manager" src="https://img.shields.io/badge/Swift_Package_Manager-compatible-orange?style=flat-square">
  <a href="https://img.shields.io/twitter/follow/_mukeshsolanki_"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/_mukeshsolanki_"></a>
  <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/mukeshsolanki/otpview-swiftui?label=version">
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"/></a>
  <br /><br />
    A custom view to enter a code usually in cases of authentication.
</p>

<img src="https://raw.githubusercontent.com/mukeshsolanki/otpview-swiftui/main/example.gif"/> &nbsp;&nbsp;

# Supporting SwiftUI OtpView/PinView

SwiftUI OtpView/PinView is an independent project with ongoing development and support made possible thanks to your donations.
- [Become a backer](https://www.paypal.me/mukeshsolanki)

## How to integrate into your app?
Integrating the project is simple. All you need to do is follow the below steps

###Swift Package Manager

The Swift Package Manager is a tool for automating the distribution of Swift code and is integrated into the swift compiler.

Once you have your Swift package set up, adding OtpView as a dependency is as easy as adding it to the dependencies value of your Package.swift.

```
dependencies: [
    .package(url: "https://github.com/mukeshsolanki/otpview-swiftui.git", .upToNextMajor(from: "1.0.0"))
]
```

## How to use the library?
Okay seems like you integrated the library in your project but **how do you use it**? Well its really easy.
Just use the `OtpView` where you need to display the view like.
```swift
OtpView(activeIndicatorColor: Color.black, inactiveIndicatorColor: Color.gray,  length: 4, doSomething: { value in
                // Do something with the value input
})
.padding()
```
That's pretty much it and your all wrapped up.

## Author
Maintained by [Mukesh Solanki](https://www.github.com/mukeshsolanki)

## Contribution
[![GitHub contributors](https://img.shields.io/github/contributors/mukeshsolanki/otpview-swiftui.svg)](https://github.com/mukeshsolanki/otpview-swiftui/graphs/contributors)

* Bug reports and pull requests are welcome.

## License
```
MIT License

Copyright (c) 2018 Mukesh Solanki

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
