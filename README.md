# Video SDK Android(Java) Code Sample

## What is it?

This code sample demonstrates a one-to-one and group video call application built with [Video SDK RTC Android SDK](https://docs.videosdk.live/docs/guide/video-and-audio-calling-api-sdk/android-sdk)

- Built for serverless video calling experience in Android.
- Scale it upto 5,000 participants with low code.
- 10,000 minutes free on monthly basis

## Features

- [x] Video API with real-time audio, video and data streams
- [x] 5,000+ participants support
- [x] Chat support with rich media.
- [x] Screen sharing with HD and Full HD.
- [ ] Play realtime video in meeting
- [ ] Connect it with social media such as Facebook, Youtube etc (RTMP out support).
- [x] Intelligent speaker switch
- [x] Record your meetings on cloud
- [x] Customise UI and build other rich features with our new data streams such as whiteboard, poll, Q & A etc.

## Device support

Visit our official [documentation](https://docs.videosdk.live/docs/realtime-communication/see-also/device-browser-support) for more information

## Prerequisites

You must have the following installed:

- Android Studio
- Android SDK
- Emulator or physical android device

## Getting started

1. Clone the repo

   ```sh
   git clone https://github.com/videosdk-live/videosdk-rtc-android-java-sdk-example.git
   ```

2. Create a `local.properties` file in the root directory of your android project with the `auth_url` or `auth_token`
 - If you want to provide `auth_url`, then run the authentication server.
 Follow instructions from [videosdk-rtc-nodejs-sdk-example](https://github.com/videosdk-live/videosdk-rtc-nodejs-sdk-example) to run the authentication server.
 - If you want to provide `auth_token`, then go to [Dashboard](https://app.videosdk.live/api-keys), create api key for your project if not and generate token by clicking **Generate Token** button.
 
   ```
   auth_url= SERVER_URL
   
   #OR
   
   auth_token= PROVIDE_TOKEN
   ```

   **Note** : For production deployment, we would highly recommend to consider `auth_url` for best use cases.
5. Run the android app with `Shift+F10` or the `Run` button from toolbar

For more information, visit [official documentation](https://docs.videosdk.live/docs/guide/video-and-audio-calling-api-sdk/getting-started)

Related

- [Video SDK RTC React Example](https://github.com/videosdk-live/videosdk-rtc-react-sdk-example)
- [Video SDK RTC React Native Example](https://github.com/videosdk-live/videosdk-rtc-react-native-sdk-example)
- [Video SDK RTC Flutter Example](https://github.com/videosdk-live/videosdk-rtc-flutter-sdk-example)
- [Video SDK RTC Android Example](https://github.com/videosdk-live/videosdk-rtc-android-java-sdk-example)
- [Video SDK RTC iOS Example](https://github.com/videosdk-live/videosdk-rtc-ios-sdk-example)
