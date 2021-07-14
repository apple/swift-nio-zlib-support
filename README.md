# swift-nio-zlib-support

## Deprecated

This package used to support depending on zlib in the Swift Package Manager. It is no longer necessary for this use-case:
instead, you can use either `systemLibrary` targets or the SwiftPM `linkerSettings` flag. For examples of its use, see
`CNIOExtrasZlib` in [`swift-nio-extras`](https://github.com/apple/swift-nio-extras).

## Usage

This is a package just to be able to use zlib with SwiftPM.
To use this package, add this to your `Package.swift` in `dependencies`:

    .package(url: "https://github.com/apple/swift-nio-zlib-support.git", from: "1.0.0"),

