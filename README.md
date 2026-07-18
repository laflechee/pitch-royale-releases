# Pitch Royale — Desktop Downloads

Installers for **[Pitch Royale](https://pitch.ac)**, the classic 4-point card game.

Always-current download links:

- **Mac (Apple Silicon):** [PitchRoyale-mac-arm64.dmg](https://github.com/laflechee/pitch-royale-releases/releases/latest/download/PitchRoyale-mac-arm64.dmg)
- **Mac (Intel):** [PitchRoyale-mac-x64.dmg](https://github.com/laflechee/pitch-royale-releases/releases/latest/download/PitchRoyale-mac-x64.dmg)
- **Windows:** [PitchRoyale-Setup.exe](https://github.com/laflechee/pitch-royale-releases/releases/latest/download/PitchRoyale-Setup.exe)

## Mac: "Apple could not verify…"

The app isn't code-signed with an Apple Developer ID yet, so macOS asks before the first launch:

1. Open the `.dmg` and drag **Pitch Royale** into **Applications**.
2. Open the app once — when the dialog appears, click **Done** (not Move to Trash).
3. Go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway**.

You only do this once. (On older macOS you can simply right-click the app and choose **Open**.)

> Using v1.0.0? That build shows "app is damaged" instead — download the latest version above, or run `xattr -cr "/Applications/Pitch Royale.app"` in Terminal.

## Windows: SmartScreen warning

Click **More info → Run anyway**. Same reason — the installer isn't code-signed yet.

Code signing for both platforms is planned; these prompts will disappear in a future release.

Or skip installs entirely and play in your browser at **[pitch.ac](https://pitch.ac)**.
