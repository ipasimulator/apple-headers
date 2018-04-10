# `apple-headers` submodule

As the title suggests, this repository is primarily meant as a submodule for the `IPASimulator` project.

It contains `.h` files analyzed by `HeadersAnalyzer` and used by `objc` library port.
The `iPhoneOS*.sdk` was obtained from a macOS machine with Xcode installed (in `/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk`), but it can also be downloaded from [airnativeextensions website](http://resources.airnativeextensions.com/ios/).
Similarly the `MacOSX*.sdk`.

Not everything from the original SDK is included, though, see [the `.gitignore` file](.gitignore) for more information on what's excluded.
