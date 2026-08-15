# Deluxe Sawari 🎵

A beautiful, modern music player for streaming Nepali songs from YouTube playlists. Built with vanilla JavaScript and YouTube IFrame API.

## Features

- 🎵 **YouTube Playlist Integration** — Stream unlimited songs from YouTube playlists
- 🎨 **Modern Glass UI** — Sleek glassmorphism design with purple accent colors
- 🕐 **Live Clock** — Real-time date and time display
- ⏯️ **Playback Controls** — Play, pause, next, and previous controls
- 📊 **Progress Bar** — Interactive progress bar with seek functionality
- 🔊 **Volume Control** — Adjustable volume slider
- ⌨️ **Keyboard Shortcuts** — Quick control via keyboard
- 📱 **Responsive Design** — Mobile-friendly interface
- 🎨 **Mountain Background** — Nepal mountain road theme

## Current Playlist

- **Nepali Old Songs** — A curated collection of classic Nepali music
- Playlist ID: `PLfJBvoNea3pG2nPyk4yKH93bZ6Y1XfiCm`

## Setup & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/amarraw/deluxe-sawari.git
cd deluxe-sawari
```

### 2. Open in Browser
Simply open `deluxe-sawari.html` in a modern web browser:
- Double-click the file, or
- Right-click and select "Open with" your preferred browser

### 3. No Dependencies Required
This project uses vanilla JavaScript and the YouTube IFrame API (loaded from CDN). No build tools or npm packages needed!

## Usage

### Controls
- **Play/Pause** — Click the play button or press `Spacebar`
- **Previous Track** — Click prev button or press `←` (left arrow)
- **Next Track** — Click next button or press `→` (right arrow)
- **Seek** — Click anywhere on the progress bar
- **Volume** — Use the volume slider on the right

### Keyboard Shortcuts
- `Spacebar` — Play/Pause
- `←` — Previous track
- `→` — Next track
- Scroll or click on progress bar to seek

## Customization

### Change Playlist
Edit the `PLAYLIST_ID` in the script section:
```javascript
const PLAYLIST_ID = 'YOUR_YOUTUBE_PLAYLIST_ID';
```

### Customize Colors
Modify CSS custom properties in the `:root` selector:
```css
:root {
  --glass: rgba(18, 12, 36, 0.58);
  --glass-border: rgba(255, 255, 255, 0.12);
  --accent: #c4a1ff;
  --accent-soft: rgba(196, 161, 255, 0.28);
  --text: #f5f0ff;
  --muted: rgba(245, 240, 255, 0.65);
}
```

### Change Background
Replace the background image URL in the `#bg` CSS section

## Technical Details

- **YouTube IFrame API** — Handles video playback and playlist management
- **Vanilla JavaScript** — No frameworks, pure JS implementation
- **CSS Glassmorphism** — Modern frosted glass effect
- **Responsive** — Optimized for desktop and mobile devices

## Browser Support

- Chrome/Brave ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## Limitations

- YouTube playlist maximum: **5,000 videos**
- Requires internet connection for YouTube streaming
- Respects YouTube's terms of service

## License

This project is open source and available under the MIT License.

## Author

Created with ❤️ for Nepali music lovers

---

**Note:** Customize the playlist ID with your own YouTube playlist to create your personalized music experience!
