# VideoMerge

A simple iOS app that allows users to select videos from their photo library and play them within the app. The app utilizes the `PHPickerViewController` for video selection and `AVPlayer` for video playback.

## Features
- Request photo library access and handle permission.
- Filter and select videos from the photo library.
- Display selected video within the app using `AVPlayerLayer`.
- Support for playing multiple videos (up to 3 as set by the selection limit).
- Merge in a collage and export to save in photo library

## How to Use
1. When you launch the app, press the "Add Photos" button to access the photo library.
2. Grant access to the photo library when prompted.
3. Select up to 3 videos from the photo library.
4. The selected video(s) will be played in the app's video view.

## Requirements
- iOS 15.0 or later

