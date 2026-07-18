# Pitch Online — Desktop Downloads

Installers for **[Pitch Online](https://pitch.ac)** (formerly Pitch Royale), the classic 4-point card game.

Always-current download links:

- **Mac (Apple Silicon):** [PitchOnline-mac-arm64.dmg](https://github.com/laflechee/pitch-royale-releases/releases/latest/download/PitchOnline-mac-arm64.dmg)
- **Mac (Intel):** [PitchOnline-mac-x64.dmg](https://github.com/laflechee/pitch-royale-releases/releases/latest/download/PitchOnline-mac-x64.dmg)
- **Windows:** [PitchOnline-Setup.exe](https://github.com/laflechee/pitch-royale-releases/releases/latest/download/PitchOnline-Setup.exe)

## Mac: "Apple could not verify…"

The app isn't code-signed with an Apple Developer ID yet, so macOS asks before the first launch:

1. Open the `.dmg` and drag **Pitch Online** into **Applications**.
2. Open the app once — when the dialog appears, click **Done** (not Move to Trash).
3. Go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway**.

You only do this once. (On older macOS you can simply right-click the app and choose **Open**.)

> Have the old "Pitch Royale" v1.0.0 that says "app is damaged"? Download the latest version above, or run `xattr -cr "/Applications/Pitch Royale.app"` in Terminal.

## Windows: SmartScreen warning

Click **More info → Run anyway**. Same reason — the installer isn't code-signed yet.

Code signing for both platforms is planned; these prompts will disappear in a future release.

Or skip installs entirely and play in your browser at **[pitch.ac](https://pitch.ac)**.
