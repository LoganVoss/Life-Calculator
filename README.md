# Life Calculator

A SwiftUI iOS project by Logan Voss.

## Current state

The checked-in app is a starter scaffold: it displays a globe symbol and “Hello, world!” in `ContentView`. Calculator features are not implemented in this snapshot.

## Open and run

Use a Mac with Xcode and an iOS Simulator runtime compatible with the project's iOS 18.5 deployment target. The project was created with Xcode 16.4.

```bash
git clone https://github.com/LoganVoss/Life-Calculator.git
cd Life-Calculator
open LifeCalculator.xcodeproj
```

1. Select the `LifeCalculator` scheme in Xcode.
2. Choose an iPhone or iPad simulator running iOS 18.5 or later.
3. Choose **Product → Run** (⌘R).

For a physical device, select your own development team under **Signing & Capabilities** and use a unique bundle identifier if required. No third-party Swift package dependencies are declared in the project.

## Project guide

- [LifeCalculator/ContentView.swift](LifeCalculator/ContentView.swift): starter screen and SwiftUI preview.
- [LifeCalculator/LifeCalculatorApp.swift](LifeCalculator/LifeCalculatorApp.swift): application entry point.
- [LifeCalculator/Assets.xcassets](LifeCalculator/Assets.xcassets): asset catalog.
- [LifeCalculator.xcodeproj](LifeCalculator.xcodeproj): Xcode project and build settings.

## Verification

No automated test target or CI workflow is currently included. Use **Product → Build** (⌘B) and run the app in a simulator to check local changes. The setup above is based on the checked-in project settings; it is not a claim of a verified build.
