# Pitch Royale — Desktop Downloads

Installers for **[Pitch Royale](https://pitch.ac)**, the classic 4-point card game.

Grab the latest version from the [Releases page](https://github.com/laflechee/pitch-royale-releases/releases/latest):

- **Mac (Apple Silicon)** — `.dmg` for M1/M2/M3/M4 Macs
- **Mac (Intel)** — `.dmg` for Intel Macs
- **Windows** — `.exe` installer

## Mac: "Pitch Royale is damaged and can't be opened"

The app isn't damaged — it just isn't code-signed yet, and macOS blocks unsigned apps downloaded from a browser. To open it:

1. Open the `.dmg` and drag **Pitch Royale** into **Applications** as usual.
2. Open **Terminal** (Cmd-Space, type "Terminal") and paste:
   ```
   xattr -cr "/Applications/Pitch Royale.app"
   ```
3. Open Pitch Royale from Applications. You only need to do this once — updates arrive automatically after that.

## Windows: SmartScreen warning

Click **More info → Run anyway**. Same reason — the installer isn't code-signed yet.

Code signing for both platforms is planned; these warnings will disappear in a future release.

Or skip installs entirely and play in your browser at **[pitch.ac](https://pitch.ac)**.
