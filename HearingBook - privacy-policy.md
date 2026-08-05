# Privacy Policy for Hearing Book

*Last updated: 5 August 2026 · Developer: Sajjad Ali Shah (DiJEN Tech)*

Hearing Book ("the app", "we", "our") is a hearing-assistance app developed by DiJEN Tech.
This policy explains what data the app handles, why, and how it is stored. It applies to
the Android app distributed on Google Play under the package name `com.dijent.quieta`.

**In short: Hearing Book does not collect, transmit, or share your recordings, notes,
or hearing data with us or anyone else. Everything you record stays on your device.**

## Data the app processes

The app handles the following types of data, all of which are created by you while using it
and stored only on your device:

- **Microphone audio** - captured live to power real-time amplification, and saved
  as a recording only when you choose to record.
- **Notes and labels** - text you type to annotate recordings.
- **Hearing test results** - thresholds from the in-app Audio Test, used to build
  your personalised amplification profile.
- **App settings** - your chosen gain level, listening preset, transcription
  display mode, and similar preferences.

None of this data is sent to DiJEN Tech, to any analytics or advertising service, or to any other
third party. The app has no user accounts, no sign-in, and does not knowingly collect any
information that identifies you personally.

## Where your data is stored

Recordings, notes, hearing test profiles, and settings are stored locally in the app's private
storage area on your device (using Android's standard app-private storage and an on-device
database). They are not uploaded to any server. Deleting a recording or note in the app removes
it immediately and permanently from your device. Uninstalling the app removes all of this data,
except for anything already included in an Android device backup (see below).

## Android device backup

The app allows Android's standard Auto Backup feature. If you have backup to Google Account
enabled in your device settings, some app data (such as notes and settings) may be included in
your device's encrypted backup, which is stored in your own Google Account and governed by
[Google's Privacy Policy](https://policies.google.com/privacy), not by DiJEN Tech. You can turn this
off at any time in your device's system backup settings.

## Permissions the app requests, and why

| Permission | Purpose |
|---|---|
| Microphone | Core function - live amplification and recording. Audio is processed on-device and only saved if you start a recording. |
| Foreground service / Foreground service (microphone) | Lets the hearing aid keep running with the screen off or the app backgrounded, showing a persistent notification while active (required by Android for any app that keeps the microphone running in the background). |
| Notifications | Shows the ongoing status notification while the hearing aid or a recording is active. |
| Internet | Used only to download the optional on-device speech-transcription model file the first time you enable transcription. No personal or usage data is sent with this request beyond what any standard internet connection requires (such as your device's IP address, visible to the hosting server, exactly as with visiting any website). |
| Accessibility service | Optional. If you turn this on in Settings, it lets you control the hearing aid and recording with your physical volume buttons, including while the screen is off or locked. It is used **only** to detect volume button presses. It does **not** read your screen, other apps, or any personal content - this is explicitly disabled in the app's configuration. It is **never** used to record phone calls or any audio other than the app's own microphone-based hearing/recording feature described above, and it never changes any device or app setting on your behalf. Before you can turn it on, the app shows an in-app disclosure screen explaining exactly what it does and asks you to confirm before taking you to your device's Accessibility settings. You can turn this off at any time from your device's Accessibility settings. |

## Third-party services

The app does not include advertising, analytics, or crash-reporting SDKs, and does not share
data with third parties. The only outbound network request the app makes is the one-time model
download described above, to a server operated by DiJEN Tech.

## Children's privacy

Hearing Book is not directed at children and does not knowingly collect personal information
from children under 13 (or the relevant age in your region).

## Your choices

- Delete individual recordings or notes at any time from within the app.
- Revoke the microphone, notification, or accessibility permission at any time from your
  device's system settings - the app will simply stop offering the corresponding feature.
- Uninstall the app to remove all locally stored data (aside from any device backup you've
  separately enabled, as described above).

## Changes to this policy

If this policy changes, the "Last updated" date at the top of this page will be revised. Material
changes will also be reflected in the app's Play Store listing.

## Contact

Questions about this policy or the app can be sent to
[genius.rashdi@gmail.com](mailto:genius.rashdi@gmail.com).

---
Hearing Book · DiJEN Tech
