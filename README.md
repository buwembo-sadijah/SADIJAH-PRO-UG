# DJ SADIJAH PRO UG — Android project

This is a starter Android Studio project wrapping a local, offline-capable DJ interface in an Android WebView.

## Included in this starter
- Four deck UI with separate local audio file import
- Play/pause and stop
- Cue-to-start button
- Basic tempo via playback rate
- Simple tempo sync to another playing deck
- Touch scratching/seeking gesture
- Three hot-cue position buttons per deck
- Generated tone sample pads
- Visual waveform-style display and playback position
- Master volume and crossfader controls
- No login or network required

## Important limitations
This is a functional starter, not a full VirtualDJ replacement. The waveform is a visual waveform-style display, not decoded audio waveform analysis. Scratching currently seeks through the track by touch movement rather than true vinyl time-stretch scratching. Hot cues store positions for the current session only. Audio mixing, beat detection, low-latency performance, and sample loading from user files need further native audio-engine work. Android/browser audio may have latency.

## Build an APK
1. Install Android Studio on a Windows, macOS, or Linux computer.
2. Open this folder as an existing Android Studio project.
3. Allow Gradle sync and install Android SDK Platform 35 if prompted.
4. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the generated APK location (usually `app/build/outputs/apk/debug/app-debug.apk`).
6. Copy the APK to your Android phone and install it. You may need to allow installs from that file manager.

## Test
- Launch DJ SADIJAH PRO UG.
- Tap LOAD on each deck and choose an audio file.
- Tap PLAY, then test CUE, tempo, hot-cue buttons, and the sample pads.
- Keep the app open during a session; imported tracks are selected from device storage and aren't uploaded anywhere.

## App details
- Application ID: `com.sadijah.djpro`
- Minimum Android version: Android 6.0 (API 23)
- Display name: DJ SADIJAH PRO UG
