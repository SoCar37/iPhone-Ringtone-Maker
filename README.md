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

GarageBand is free from the App Store. These steps reflect Apple's current instructions as of May 2025.

1. Transfer the .wav file to your iPhone so it is accessible in the **Files app**
2. On your iPhone home screen, **touch and hold the GarageBand icon** until a menu appears, then tap **Create New Audio Recording**
3. When GarageBand opens, tap the **Tracks button** at the top of the screen — it looks like three horizontal lines with a gap (like a small brick wall pattern)
4. Tap the **instrument icon** on the left side of the track to select it — it looks like whatever instrument type was created (keyboard, guitar, etc.)
5. Tap the **Loop Browser button** at the top right — it looks like a circle/loop icon
6. Tap **Files**, then tap **Browse items from the Files app** and locate your .wav file
7. **Touch and hold the file**, then drag it all the way to the **left edge** of the Tracks view
8. Tap the **Navigation button** at the top left — it looks like a downward arrow — then tap **My Songs**
9. In the My Songs browser, tap the **More button (•••)**, tap **Select**, then tap your song to select it
10. Tap the **Share button** (box with upward arrow), then tap **Ringtone**
11. Enter a name for the ringtone, then tap **Export**
12. When export finishes, tap **Use sound as**, then choose an option:
    - **Standard Ringtone** — replaces your current ringtone
    - **Standard Text Tone** — sets it as your text tone
    - **Assign to contact** — links it to a specific contact
    - **Done** — saves it to your ringtone list without assigning it yet
13. Go to **Settings → Sounds & Haptics → Ringtone** to confirm it's there and select it
14. Delete the .wav from your Files app — it's no longer needed

## Managing Ringtones on iPhone

- **Multiple ringtones** — you can store as many as you want with no practical limit
- **Per-contact ringtones** — assign different ringtones to individual contacts via the export step above, or through the Contacts app
- **Renaming** — name your ringtone at export time in GarageBand; it cannot be renamed after installation
- **Deleting** — go to Settings → Sounds & Haptics → Ringtone, swipe left on any custom ringtone and tap Delete

## Why WAV instead of M4R?

This tool uses only built-in browser audio technology with no external libraries, making it fast, reliable, and privacy-friendly. The .wav file is slightly larger than an .m4r but GarageBand automatically compresses it to AAC when exporting as a ringtone — so the final ringtone quality is identical.

## Browser Compatibility

Works in any modern browser — Chrome, Firefox, Safari, Edge.

## License

MIT — free to use and modify.
