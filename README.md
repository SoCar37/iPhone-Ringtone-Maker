# iPhone Ringtone Maker

A browser-based tool for trimming MP3 files and exporting them as **.m4r** ringtones ready for iPhone. No installation required — runs entirely in your browser.

## Features

- Load any MP3 file from your device
- Visual waveform with draggable start and end handles
- Real-time selection timer with 30-second limit enforcement
- Preview your clip before exporting
- Custom file naming
- Exports as **.m4r** format (iPhone ringtone format)
- Audio never leaves your device — fully private, no uploads

## How to Use

1. Open the app in your browser
2. Click **Choose MP3 file** and select your audio
3. Drag the blue handles on the waveform to set your clip start and end points
4. Keep your selection under 30 seconds (iPhone requirement)
5. Click **Play selection** to preview
6. Enter a file name and click **Export as .m4r**
7. The .m4r file will download to your device

## Installing the Ringtone on iPhone

Once you have your .m4r file, use one of these methods:

**GarageBand (easiest, no computer needed)**
1. AirDrop or save the .m4r file to your iPhone
2. Open GarageBand and import the audio
3. Export directly as a ringtone to your iPhone Settings

**iTunes / Finder (Mac or PC)**
1. Drag the .m4r file into your iTunes library
2. Sync your iPhone
3. Go to Settings → Sounds → Ringtone on your iPhone

## Technical Notes

- Uses [ffmpeg.wasm](https://ffmpegwasm.netlify.app) for in-browser audio encoding
- On first load, the app downloads the ffmpeg.wasm engine (~30MB) from a CDN — this is cached by your browser after the first visit
- Supported input: MP3 (and most common audio formats)
- Output: AAC audio encoded as .m4r

## Browser Compatibility

Works in any modern browser — Chrome, Firefox, Safari, Edge.

## License

MIT — free to use and modify.
