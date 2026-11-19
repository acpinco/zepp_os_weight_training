# Weight Lifting: feedback

Weight Lifting is a strength training log for Amazfit watches running Zepp OS. Between sets it lets you pick the exercise, check the weight and reps it counted, and rest with a timer. Workouts can be sent to Strava.

This repository is only for **bug reports and feature requests**. The app's source code is not published here.

- Found a bug? [Report it](../../issues/new?template=bug_report.yml)
- Have an idea? [Request a feature](../../issues/new?template=feature_request.yml)
- Looking for what changed? See the [release notes](RELEASE_NOTES.md)

Please search existing issues first, and add a thumbs-up to ones you care about.

## Privacy

Don't post personal information in issues. That includes your email address, your Strava profile or activity links, health data such as heart rate, or screenshots showing your name or photo.

## Troubleshooting

Before anything else, make sure your phone's system and the Zepp app are up to date. Both problems below were seen on a phone that had just been reset.

### The app's settings page in the Zepp app is blank, or workouts don't sync to the phone

The settings page runs inside **Android System WebView**, and an old copy can stop it from loading. Update it from the Google Play Store: [Android System WebView](https://play.google.com/store/apps/details?id=com.google.android.webview). Check that it is the one by **Google LLC**, since there are copycat apps with similar names. Then close and reopen the Zepp app.

### After signing in to Strava, I'm not taken back to the Zepp app (Samsung phones)

Strava sign-in doesn't work with Samsung Internet, even on an up-to-date phone. Install [Google Chrome](https://play.google.com/store/apps/details?id=com.android.chrome) from the Google Play Store if you don't have it, then make Chrome your default browser (Settings, Apps, Choose default apps, Browser app). After that, go back to the app's settings page in the Zepp app and tap **Connect with Strava** again.
