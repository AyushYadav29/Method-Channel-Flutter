# Method-Channel-Flutter
### Creating a custom platform-specific code in Flutter
https://flutter.dev/docs/development/platform-integration/platform-channels                                                                                                                            
Flutter uses a flexible system that allows you to call platform-specific APIs whether available in Kotlin or Java code on Android, or in Swift or Objective-C code on iOS.

The following code demonstrates how to call a platform-specific API to retrieve and display the current battery percnetage. It uses the Android BatteryManager API, and the iOS device.batteryLevel API, via a single platform message, getBatteryLevel().

