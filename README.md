# cocoapods-suffix-version-mismatch-reproducer
An example repository that reproduces the version incompatibility between 0.1.0-dev and 0.1.0

Run `pod install` in the App folder to get the error:

```
[!] CocoaPods could not find compatible versions for pod "native-lib":
  In Podfile:
    native-lib (from `../native-lib`)

    plugin (from `../plugin`) was resolved to 0.0.1, which depends on
      native-lib (= 0.1.0)
```
