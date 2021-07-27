# Running this example

## Credentials

Please follow this guide for consuming GitHub Packages feeds:

https://help.github.com/en/packages/using-github-packages-with-your-projects-ecosystem

## Running the sample
1. Ensure you have a recent version of node installed (tested on 12.5.0).
2. Run `npm install` in the root directory of the project.
3. Install CocoaPods, instructions here: https://cocoapods.org/.
4. In the root of the `ios` directory, run `pod install`
5. This sample was created and tested using the React Native CLI. Instructions on installation and running projects
using the cli can be found here: https://reactnative.dev/docs/environment-setup. These instructions should allow you
 to run the app on a device.
6. Open the main `App.js` file. Replace "YOUR LICENSE KEY HERE" with the license key provided by W2.
 
Note: The android and iOS apps can be run through Android Studio and XCode respectively. However only XCode 12.5 is currently supported for iOS.



# Localization


## iOS

Only available from sdk version 1.8.5 onwards.

Within the ios directory the following localization is available:

Open `reactnative.xcworkspace` in Xcode to see and edit the Localizable.strings file.

```
/*
 Facial Comparison Capture View
 */
"facialcomparison.capture.face.too.close" = "Too close! Move away";
"facialcomparison.capture.face.too.far" = "Move Closer";
"facialcomparison.capture.face.not.in.frame" = "Move in frame";
"facialcomparison.capture.face.good.distanc.blink" = "Blink!";
"facialcomparison.capture.face.hold.steady" = "Hold Steady";

"facialcomparison.capture.info1" = "Align face and blink when a ";
"facialcomparison.capture.green.oval" = "green circle ";
"facialcomparison.capture.info2" = "appears";


/*
 Document Verification Capture View
 */
"documentverification.capture.hold.steady" = "Hold Steady";
"documentverification.capture.align" = "Align";
"documentverification.capture.move.closer" = "Move Closer";
"documentverification.capture.capturing" = "Capturing";
```


## Android

Within the `android/app/src/main/res` the following localization is available:

```
    <!-- Facial Comparison -->
    <string name="hg_move_in_frame">Move in frame</string>
    <string name="hg_hold_steady">Hold steady</string>
    <string name="hg_blink">Blink!</string>
    <string name="hg_too_close">Too close! Move away</string>
    <string name="hg_too_far_away">Move Closer</string>
    <string name="hg_align_face_and_blink">Align face to begin</string>


    <!-- Document Verification -->
    <string name="acuant_camera_align">Align</string>
    <string name="acuant_camera_move_closer">Move Closer</string>
    <string name="acuant_camera_not_in_frame">Too close!</string>
    <string name="acuant_camera_hold_steady">Hold Steady</string>
    <string name="acuant_camera_capturing">Capturing</string>
```
