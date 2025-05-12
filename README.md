# TUNE UP

This is a dynamic, client-side music player built using JavaScript. The app allows users to play, pause, skip, and manage a playlist of songs in the browser.

## Files

- `script.js` – Core JavaScript file handling all music player logic.
- `songs/` – Folder containing `.mp3` files referenced in the player.
- `images/` – Folder containing song thumbnail images.
- `index.html` – (Not provided here) HTML structure expected to contain specific elements referenced in the script.
- `style.css` – (Not provided here) CSS styles for UI animations and layout.

## Features

- Load and play music tracks dynamically.
- Play/pause toggle with icon switch.
- Skip to next/previous tracks.
- Progress bar updates in real-time.
- Click-to-seek feature on the progress bar.
- Loop modes: repeat all, repeat one, shuffle.
- Song list with track durations.
- Volume control and mute functionality.
- Animated visuals (e.g., rotating album art and wave animation).

## Usage Instructions

1. Place your audio files in a `songs/` directory and name them consistently with the `src` field in your `allMusic` array.
2. Place corresponding images in the `images/` folder.
3. Make sure your HTML has the structure with class and ID names like:
   - `.wrapper`, `.play-pause`, `#main-audio`, `.progress-area`, `.music-list`, `#more-music`, `#close`, etc.
4. Include the `script.js` file in your HTML:
   ```html
   <script src="script.js"></script>
