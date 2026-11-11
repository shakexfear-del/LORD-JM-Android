LORD JM AUDIO STUDIO — VERSION 2.0

A redesigned Android Studio project based on the supplied LORD JM assets.

FEATURES
- Premium red/black responsive interface
- Microphone recording using Android WebView media capture
- Live microphone gain control
- Adjustable echo amount and delay
- Clean, Room, Deep echo and Loud mic presets
- Live input meter and recording timer
- Audio playback, save/download link, and delete action
- Runtime microphone permission handling
- Audio is processed locally; no upload or account login

BUILD
1. Open the LORD-JM-Android folder in Android Studio.
2. Allow Gradle sync to complete (Android Gradle Plugin 8.7.3, compile SDK 35).
3. Connect an Android device or start an emulator.
4. Run the app. Grant microphone permission when prompted.

NOTES
- Recording uses MediaRecorder/Web Audio APIs available in a compatible Android System WebView.
- Audio is exported as WebM/Opus where supported, otherwise the browser-supported recording format.
- The Save audio link uses the WebView/browser download behavior. Download handling can vary by Android WebView version.
- The app does not modify WhatsApp calls or capture third-party calls.
