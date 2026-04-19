# iPhone Ringtone Maker

A browser-based tool for trimming MP3 files and exporting them as **.wav** files ready to convert into iPhone ringtones via GarageBand. No installation required — runs entirely in your browser with no external dependencies.

## Features

- Load any MP3 file from your device
- Visual waveform with draggable start and end handles
- Real-time selection timer with 30-second limit enforcement
- Preview your clip before exporting
- Custom file naming
- Exports as **.wav** format
- Audio never leaves your device — fully private, no uploads, no external libraries

## How to Use

1. Open the app in your browser
2. Click **Choose MP3 file** and select your audio
3. Drag the blue handles on the waveform to set your clip start and end points
4. Keep your selection under 30 seconds (iPhone requirement)
5. Click **Play selection** to preview
6. Enter a file name and click **Export as .wav**
7. The .wav file will download to your device

## Installing the Ringtone on iPhone

1. **AirDrop** the .wav file to your iPhone (or save it to iCloud Drive)
2. Open **GarageBand** on your iPhone (free from the App Store)
3. Import the .wav file into a GarageBand project
4. Tap the GarageBand menu and select **My Songs**
5. Long-press the project → **Share → Ringtone**
6. Name it and tap **Export** — it goes directly to Settings
7. Go to **Settings → Sounds → Ringtone** to select it
8. Delete the original .wav from your Files app — it's no longer needed

## Why WAV instead of M4R?

This tool uses only built-in browser audio technology with no external libraries, making it fast, reliable, and privacy-friendly. The .wav file is slightly larger than an .m4r but GarageBand automatically compresses it to AAC when exporting as a ringtone — so the final ringtone quality is identical.

## Browser Compatibility

Works in any modern browser — Chrome, Firefox, Safari, Edge.

## License

MIT — free to use and modify.
