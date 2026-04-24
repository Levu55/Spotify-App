# Spotify Web Player App

A modern, responsive Spotify-inspired music player built with HTML, CSS, and JavaScript. Features a sleek dark theme, full player controls, and a beautiful card-based UI.

## ✨ Features

- 🎵 **Full Music Player Controls** - Play, pause, next, previous, and seek functionality
- 🔊 **Volume Control** - Adjustable volume slider with real-time feedback
- ⏱️ **Time Display** - Current time and total duration tracking
- 🎨 **Spotify-Inspired Design** - Modern dark theme with green accents
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- 🔍 **Search Functionality** - Search through songs (ready to expand)
- 🎯 **Card-Based UI** - Beautiful music card grid layout
- ♻️ **Auto-Play Next** - Automatically plays next song when current ends
- 📊 **Progress Tracking** - Visual progress bar with hover effects

## 🚀 Quick Start

### Local Testing
1. Clone the repository:
```bash
git clone https://github.com/Levu55/Spotify-App.git
cd Spotify-App
```

2. Start a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if installed)
npx http-server
```

3. Open in browser:
```
http://localhost:8000/Spotify%20Web%20Player/
```

### Deploy on GitHub Pages
1. Go to **Settings** → **Pages**
2. Select `main` branch and `/ (root)` folder
3. Click **Save**
4. Your app will be live at: `https://Levu55.github.io/Spotify-App/`

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript (Vanilla)** - No dependencies
- **Font Awesome 6** - Icon library
- **Google Fonts (Montserrat)** - Typography

## 📁 Project Structure

```
Spotify-App/
├── README.md                    # Project documentation
├── DEPLOYMENT_GUIDE.md          # Deployment instructions
├── LICENSE                      # Apache 2.0 License
├── .gitignore                   # Git ignore rules
├── Spotify Web Player/
│   ├── index.html              # Main HTML file
│   ├── spotify.css             # Main styles (1000+ lines)
│   ├── spotify.js              # Player logic & interactivity
│   ├── utility.css             # Reusable utility classes
│   ├── Audio/                  # Audio files directory
│   │   ├── nusrat.mp3
│   │   ├── Afreen.weba
│   │   └── ... (more tracks)
│   └── images/                 # Image assets
│       ├── RAHAT.jfif
│       ├── ATIF.jfif
│       └── ... (more images)
```

## 🎯 How to Use

### Playing Music
1. Click on any song card to play it
2. Use **Play/Pause** button in the player bar
3. Use **Next** and **Previous** buttons to navigate
4. Drag the **progress bar** to seek

### Volume Control
- Use the **volume slider** at the bottom right
- Adjust from 0% (mute) to 100% (max)

### Search
- Click **Search** in the sidebar
- Type to filter songs
- Press **ESC** or click outside to close

## 🎨 Customization Guide

### Change Colors
Edit `spotify.css` `:root` variables:
```css
:root {
    --accent: #1ed760;           /* Primary green */
    --accent-hover: #3be477;     /* Lighter green */
    --accent-press: #1db954;     /* Darker green */
    --bg-base: #000000;          /* Background */
}
```

### Add More Songs
Edit `spotify.js` songs array:
```javascript
const songs = [
    {
        name: "Song Title",
        artist: "Artist Name",
        cover: "image.jpg",
        file: "audio.mp3",
        title: "Song Title"
    },
    // Add more...
];
```

### Modify Layout
- **Sidebar width**: Line 40 in `spotify.css`
- **Card grid columns**: Line 213 in `spotify.css`
- **Player bar height**: Line 323 in `spotify.css`

## 📱 Responsive Breakpoints

- **Desktop**: 1024px+ - Full layout with sidebar
- **Tablet**: 768px-1023px - Hidden sidebar, expanded player
- **Mobile**: Below 768px - Optimized for small screens
- **Small Mobile**: Below 480px - Minimal time display

## 🐛 Troubleshooting

### Audio Not Playing
- Check audio file paths in `Spotify Web Player/Audio/`
- Verify file formats (MP3, WebA supported)
- Check browser console for CORS errors
- Try different audio format

### Images Not Showing
- Ensure images are in `Spotify Web Player/images/`
- Check file extensions are correct
- Verify image paths match in `index.html` and `spotify.js`
- Use fallback placeholder images

### Styles Not Applied
- Clear browser cache: **Ctrl+Shift+Del**
- Check CSS file paths
- Verify `utility.css` and `spotify.css` are linked
- Check browser console for CSS errors

### Mobile Layout Issues
- Test with actual device or browser DevTools
- Check viewport meta tag in HTML
- Verify media queries are working
- Test on different browsers (Chrome, Firefox, Safari)

## 🔒 Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome | ✅ Full | Latest version recommended |
| Firefox | ✅ Full | Latest version recommended |
| Safari | ✅ Full | iOS 13+ for best experience |
| Edge | ✅ Full | Chromium-based versions |
| IE 11 | ❌ Not supported | Use modern browser |

## 🚀 Future Enhancements

- [ ] **Playlist Creation** - User-created playlists
- [ ] **Favorites/Likes** - Save favorite songs
- [ ] **Dark/Light Mode** - Toggle theme
- [ ] **Shuffle & Repeat** - Playback modes
- [ ] **Audio Visualization** - Animated spectrum
- [ ] **Keyboard Shortcuts** - Spacebar to play/pause
- [ ] **Local Storage** - Remember preferences
- [ ] **Equalizer** - Audio frequency controls
- [ ] **Lyrics Display** - Show song lyrics
- [ ] **Share Feature** - Share with friends

## 📊 Performance Tips

- **Optimize Audio**: Use WebM/Opus for better compression
- **Lazy Load Images**: Load images only when visible
- **Minify CSS/JS**: For production deployment
- **Use CDN**: Serve fonts and icons from CDN
- **Cache Busting**: Add version parameters to assets

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Levu55** - [GitHub Profile](https://github.com/Levu55)

## 🙏 Acknowledgments

- Spotify for UI/UX inspiration
- Font Awesome for icons
- Google Fonts for typography
- Community feedback and contributions

## 📞 Support

For issues or questions:
- Open an issue on [GitHub Issues](https://github.com/Levu55/Spotify-App/issues)
- Check [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md) for deployment help
- Review troubleshooting section above

---

**Happy Listening! 🎵**

*Last Updated: April 24, 2026*
