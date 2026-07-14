# Support

**Audio Classifier for iOS**

Audio Classifier turns your iPhone into a round-the-clock sound monitor — it recognises over 300 everyday sounds entirely on-device and charts what it hears. This page covers common questions; anything else, get in touch at the bottom.

## Getting started

1. Open the **Monitor** tab and tap **Start Monitoring** (iOS will ask for microphone permission the first time).
2. Watch live detections and confidence levels as they happen.
3. Check the **Dashboard** tab for the day's timeline and per-sound breakdown, and the **Presets** tab to choose exactly which sounds to track and how sensitive each should be.

## Frequently asked questions

### Detection seems weak — it only ever notices speech. What's wrong?

Check **Mic Mode** in Control Centre (swipe down from the top-right while monitoring is running). If it's set to **Voice Isolation** — often left over from a phone or FaceTime call — iOS filters out non-voice sounds *before* the app hears them, which defeats a sound classifier. Set it to **Wide Spectrum** for best results, or **Standard**. This is an iOS-level setting that apps cannot change for you.

### What does the orange "Paused" banner mean?

iOS occasionally takes the microphone away — for a phone call, an alarm, another app, or a Bluetooth change. The banner tells you why in plain language, and monitoring resumes automatically as soon as the microphone is free again. Any gap is shown honestly in the Dashboard timeline rather than papered over.

### Can it really run all night?

Yes — that's what it's built for. Monitoring continues with the screen off and recovers automatically from interruptions. Two tips for long sessions: plug the phone in, and set Mic Mode as above before you start.

### Does it record audio? Where does my data go?

No audio is ever recorded — sound is classified in real time and discarded. The only thing saved is the classification data you can see (timestamps, labels, confidence), and it never leaves your phone. The full details are in the [privacy policy](privacy.md).

### How do I delete my data?

The **Reports** tab has controls to delete old logs or everything at once. Uninstalling the app also removes all data.

### Can I use the logs elsewhere?

Logs are compressed CSV files in a documented format, shared with Audio Classifier for Android — handy if you want to analyse them yourself.

### Why does the battery drain faster than I expected?

Continuous sound classification keeps the device awake, so overnight sessions are best run plugged in. Enabling airplane mode during a session also helps.

## Reporting a problem

Found a bug? Please open an issue on the [GitHub issues page]([ISSUES URL]) — include your iOS version, what you did, and what you expected. Screenshots of the Monitor or Dashboard screen help a lot.

## Contact

- GitHub issues: [ISSUES URL]
- Email: [CONTACT EMAIL]
