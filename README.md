# AZ Voice Assistant Releases

Download the latest Android APK:

- [AZ Voice Assistant v1.4 APK](AZ-Voice-Assistant-v1.4.apk)

## v1.4

- Google-Assistant-style wake conversation
- Say `Hey AZ` and AZ answers `জি, বলুন` / `Yes, tell me`
- AZ automatically listens for the next command
- Say a complete command such as `Hey AZ, open YouTube` for immediate action
- Temporarily pauses the background listener while receiving the command to avoid microphone conflicts

SHA-256: `f538d392c732cf86a77cc81a634f0cfea96c5b09c74d44b30d1f3ad17069ed2e`

## v1.3

- Repairs the background `Hey AZ` listener
- Automatically restarts listening after silence, timeout or recognition errors
- Recreates the recognizer if Android reports it busy or stopped
- Uses a persistent microphone foreground service
- Keeps the listener active when the screen is locked

SHA-256: `7eb8510c180b94cb2bc30765576227a1ebd661b16b2869e8df553fe351afae36`

## v1.2

- Faster Bangla and English voice response
- Change the assistant name in Settings
- Custom wake phrase: `Hey [your chosen name]`
- Open WhatsApp, YouTube, Gmail and Google Maps by voice
- Open other installed apps by saying `Open [app name]`
- Prepare WhatsApp messages with confirmation
- Safety confirmation remains enabled for calls, messages and bookings

SHA-256: `35557d9b2bb8b16088c49828504ac8016b558b38ed3dc890d6136107d8f06f29`

## v1.1

- Bangladesh Bangla voice recognition (`bn-BD`)
- English voice recognition support
- Shows recognized speech on screen
- Start and stop listening controls
- Improved `Hey AZ` listening restart
- AndroidX build correction
- Bangla voice replies with a warm female voice when supported by the phone
- Confirmation required before calls, messages, bookings, or other sensitive actions

SHA-256: `62b11b15d0df890412fa0a12c6803764c8d129141f8e50b2f87c1c5616225d59`

The source code is maintained in a separate private repository.
