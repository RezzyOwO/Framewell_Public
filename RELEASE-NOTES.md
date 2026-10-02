# Framewell 0.14.1

## Reliable updates
- Update downloads are announced immediately, with visible progress.
- A separate installation window stays open while Framewell closes and updates.
- Restart is confirmed only after the expected version opens a visible, loaded window.
- Failed or interrupted updates pause automatic retries across app restarts. Retry remains available in Settings.
- Opening Framewell twice brings the existing window forward instead of starting competing update attempts.
- Older malformed installation records are repaired during setup.
- Update errors remain available instead of disappearing when Settings is opened.

## Creator profile
- Redesigned Patreon window with a full-width banner, profile portrait, pink membership cards, live benefits and creator socials.
- Profile images, membership details and counts refresh on opening and every five minutes while the window is active. Cached details remain available offline.
- Added Developer, Tools and Creative tags, plus direct Discord, X and website links.

## Upgrade
Windows x64. Close all running Framewell copies, then run [Framewell-Installer-Win.exe](https://github.com/RezzyOwO/Framewell_Public/releases/download/v0.14.1/Framewell-Installer-Win.exe).

If your older updater repeatedly installs or does not reopen the app, install this release manually once. Settings and projects are preserved. The identical versioned installer remains available for automatic updates.

Validation: 79 native tests passed; an actual 0.14.0 to 0.14.1 upgrade reopened a visible window. Installer failures, repeated-launch protection, Patreon refreshes, social links and the packaged interface were verified.
