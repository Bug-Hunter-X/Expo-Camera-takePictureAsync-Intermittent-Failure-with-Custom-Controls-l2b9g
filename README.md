# Expo Camera takePictureAsync Intermittent Failure

This repository demonstrates an intermittent bug encountered when using Expo's Camera API with custom controls. The `takePictureAsync` function sometimes fails to capture an image without throwing an error or providing a clear indication of failure.  This issue is inconsistent across platforms (iOS and Android). 

## Bug Reproduction

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the project on an iOS or Android device or simulator.
4. Attempt to take multiple pictures using the custom capture button.

You will observe that the `takePictureAsync` function sometimes doesn't fire and no picture is saved, even though there are no apparent errors.