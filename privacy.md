# Privacy Policy

**Audio Classifier for iOS**
Effective date: 14 July 2026

## The short version

Audio Classifier does not collect, store, or share any personal data. Your audio never leaves your device — in fact, it is never even recorded.

## Microphone and audio

Audio Classifier listens through your iPhone's microphone only while you have monitoring switched on. Audio is analysed in real time, in memory, using Apple's on-device sound classification (the SoundAnalysis framework). The raw audio is **never recorded, never written to storage, and never transmitted anywhere**. Once a moment of audio has been classified, it is gone.

## What the app stores on your device

The only data the app writes is the classification output you can see in the app:

- **Detection logs** — timestamps, sound labels (e.g. "Dog", "Music"), and confidence scores, saved as compressed CSV files
- **Session logs** — plain-text notes about monitoring sessions (started, paused, resumed)
- **Reports** — summaries you choose to generate from your own logs

All of this stays on your device. You can delete any or all of it at any time from the Reports tab, and uninstalling the app removes everything. Like most app data, these files may be included in the device backups you control through iOS (iCloud or computer backups).

## What the app does not do

- **No network access** — the app contains no networking code and works entirely offline
- **No analytics or tracking** — no third-party SDKs, no advertising, no crash reporters
- **No accounts** — nothing to sign up for, no identifiers collected
- **No data collection from anyone**, including children

Audio Classifier's App Store privacy label is **"Data Not Collected"**, and this policy is the long-form version of exactly that.

## Permissions

The app requests one permission: **microphone access**, which iOS asks you to grant the first time you start monitoring. Without it the app cannot classify sound; with it, everything described above applies.

## Changes to this policy

If a future version of the app changes any of the above (for example, if an optional export or sync feature is ever added), this policy will be updated before that version is released, with the effective date revised.

## Contact

Questions about this policy are welcome — open an issue on our [support page](support.md) or email **[CONTACT EMAIL]**.
