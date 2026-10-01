# Framewell 0.10.1

## Automatic updater fix

- Fixed the Windows update helper silently exiting before installation started.
- Framewell now waits for the helper to confirm it is ready before saving the workspace and closing.
- The helper stays running while Framewell closes, installs the verified update, and automatically restarts the app.
- Startup failures return a retryable error with diagnostic logs instead of remaining on Installing.
- An update that cannot close the old app no longer opens a duplicate copy.

The automatic update flow was tested with a simulated release feed and the real Windows installer: release detection, waiting for idle, download verification, workspace save, installation and automatic restart. Interrupted downloads and helper failures were also checked.

## Updating from an older version

**If you are on 0.9.1 or 0.10.0, run this installer manually once.** Those versions contain the broken update launcher, so downloading an update inside the app may not finish the installation. Install into your existing Framewell folder; your settings and projects are preserved.

If you already installed 0.10.1 locally, you have this fix and do not need to reinstall.

Windows x64. Download [Framewell-Installer-Win.exe](https://github.com/RezzyOwO/Framewell_Public/releases/download/v0.10.1/Framewell-Installer-Win.exe).

The versioned `Framewell-0.10.1-Setup.exe` is an identical copy used by the automatic updater. All improvements from 0.10.0 are included.
