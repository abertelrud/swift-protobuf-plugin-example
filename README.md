# swiftpm-protobuf-plugin-example

This is an example of using a SwiftPM plugin to automatically generate Swift code from ``.proto`` files in a Swift package.  It currently requires a modified fork of the `swift-protobuf` which adds a SwiftPM plugin script as well (temporarily) a binary of the `protoc` compiler.  This example requires SwiftPM 5.6 or later.