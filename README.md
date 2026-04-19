# iPhone Ringtone Maker

A browser-based tool for trimming MP3 files and exporting them as **.wav** files ready to convert into iPhone ringtones via GarageBand. No installation required — runs entirely in your browser with no external dependencies.

## Features

- Load any MP3 file from your device
- **Overview waveform** — full song view with draggable start and end handles to set your clip
- **Detail waveform** — zoomed view of your selection with higher resolution for precise trimming
- Real-time playhead line shows position during preview playback
- Time labels showing tenths of a second for precise editing
- Fine adjustment buttons (±0.1s and ±1.0s) for exact start and end points
- 30-second limit enforced with warning (iPhone ringtone maximum)
- Preview your clip before exporting
- Custom file naming
- Exports as **.wav** format
- Audio never leaves your device — fully private, no uploads, no external libraries

## How to Use

1. Open the app in your browser
2. Click **Choose MP3 file** and select your audio
3. Drag the blue handles on the overview waveform to roughly set your start and end points
4. Use the ±0.1s and ±1.0s buttons to fine-tune the exact start and end
5. Watch the detail waveform to see your selection zoomed in
6. Keep your selection under 30 seconds (iPhone requirement)
7. Click **Play selection** to preview — a red line sweeps across the detail waveform as it plays
8. Enter a file name and click **Export as .wav**
9. The .wav file will download to your device

## Transferring to Your iPhone

Since you're on Windows, AirDrop is not available. Use one of these instead:

- **Google Drive** — upload from your PC, download via the Google Drive app on iPhone
- **iCloud Drive** — upload via icloud.com on your PC, access from the Files app on iPhone
- **Email** — attach the .wav to an email and open it on your iPhone
- **USB cable** — connect your iPhone to your PC via iTunes and transfer via File Sharing

## Installing the Ringtone on iPhone via GarageBand

GarageBand is free from the App Store and is the easiest way to install custom ringtones on iPhone without a computer sync.

1. Transfer the .wav file to your iPhone so it appears in the **Files app**
2. Open **GarageBand** and tap **+** to create a new project — choose any instrument
3. Tap the **Tracks icon** (top left) to switch to Tracks view
4. Tap the **Loop browser icon** (top right) → tap **Files** → **Browse Items from the Files App**
5. Locate your .wav file and tap it — it will appear as an audio track
6. Tap the **down arrow icon** (top left) → **My Songs**
7. Long-press your project → **Share → Ringtone**
8. Give it a name and tap **Export** — it installs directly to your ringtone list
9. Go to **Settings → Sounds & Haptics → Ringtone** to select it
10. Delete the .wav from your Files app — it's no longer needed

## Managing Ringtones on iPhone

- **Multiple ringtones** — you can store as many as you want with no practical limit
- **Per-contact ringtones** — assign different ringtones to individual contacts
- **Renaming** — name your ringtone in GarageBand before exporting; it cannot be renamed after installation
- **Deleting** — go to Settings → Sounds & Haptics → Ringtone, swipe left on any custom ringtone and tap Delete

## Why WAV instead of M4R?

This tool uses only built-in browser audio technology with no external libraries, making it fast, reliable, and privacy-friendly. The .wav file is slightly larger than an .m4r but GarageBand automatically compresses it to AAC when exporting as a ringtone — so the final ringtone quality is identical.

## Browser Compatibility

Works in any modern browser — Chrome, Firefox, Safari, Edge.

## License

MIT — free to use and modify.
