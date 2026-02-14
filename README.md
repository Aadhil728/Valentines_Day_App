# 💕 Romantic Valentine's Day Web App

A beautiful, lightweight, single-page Valentine's Day web application built with pure HTML, CSS, and JavaScript. Perfect for sharing your love and easily hosted on GitHub Pages!

## ✨ Features

### Core Features
- ✅ **Single-page responsive design** - Works perfectly on desktop, tablet, and mobile
- ✅ **Beautiful romantic UI** - Soft pink/red gradient background with smooth animations
- ✅ **Animated floating hearts** - Continuously floating hearts in the background
- ✅ **Centered love card** - With romantic heading, paragraph, and interactive button
- ✅ **Typing animation effect** - Sweet love message appears with typewriter effect
- ✅ **Heart animation explosion** - Magical heart burst when button is clicked
- ✅ **Background romantic music** - Optional toggle button to play/pause (🔊/🎵)
- ✅ **Photo upload section** - Display your favorite couple photo
- ✅ **Smooth CSS transitions** - Professional animations throughout
- ✅ **Mobile responsive design** - Optimized for all screen sizes
- ✅ **Clean organized code** - Well-commented JavaScript and CSS

### Bonus Features
- ✅ **Countdown timer** - Days, hours, minutes, and seconds until next Valentine's Day
- ✅ **"Will you always be mine?" button** - Playful yes/no question where "No" runs away on hover
- ✅ **Glowing text effect** - Romantic glowing animation on the main heading
- ✅ **Keyboard support** - Press Enter to trigger the surprise
- ✅ **Lightweight** - Single HTML file (~15KB), perfect for GitHub Pages

## 🚀 Quick Start

### Option 1: Local Use
1. Download the `index.html` file
2. Open it directly in your web browser
3. No server or installation required!

### Option 2: Host on GitHub Pages
1. Create a GitHub repository named `Valentines_Day_App`
2. Upload `index.html` to the repository
3. Go to repository settings → Pages and enable GitHub Pages
4. Your app will be available at: `https://yourusername.github.io/Valentines_Day_App/`

## 🎨 Customization Guide

### Change the Main Message
Edit the heading and paragraph in the HTML:
```html
<h1>Happy Valentine's Day My Love ❤️</h1>
<p>Your custom romantic message here...</p>
```

### Add Custom Love Messages
Edit the `LOVE_MESSAGES` array in the JavaScript section:
```javascript
const LOVE_MESSAGES = [
    "Your custom message 1",
    "Your custom message 2",
    "Your custom message 3",
];
```

### Change Background Colors
Modify the gradient in the `body` CSS:
```css
background: linear-gradient(135deg, #ffd89b 0%, #19547b 100%);
```

Some beautiful gradient options:
- Romantic Pink/Red: `linear-gradient(135deg, #ffc9d4 0%, #ff6b9d 100%)`
- Sunset Love: `linear-gradient(135deg, #ff9999 0%, #ffcc99 100%)`
- Soft Purple: `linear-gradient(135deg, #dda0dd 0%, #ee82ee 100%)`

### Change the Countdown Date
Edit the target date in the `updateCountdown()` function:
```javascript
const nextValentine = new Date(2027, 1, 14); // February 14, 2027
```

### Add Custom Music
Replace the audio source URL:
```html
<source src="YOUR_MUSIC_URL_HERE" type="audio/mpeg">
```

Free music suggestions:
- https://www.bensound.com/royalty-free-music (Romantic, Love, etc.)
- https://www.incompetech.com/music/ (Royalty-free instrumental)

### Adjust Music Volume
Change this line in the JavaScript:
```javascript
backgroundMusic.volume = 0.3; // Change 0.3 to a value between 0 and 1
```

### Modify Colors
Find these color values and change them:
- Main accent color: `#d1436a` (romantic dark pink)
- Button gradient: `#ff6b9d` to `#d1436a`
- Light background: `#ffb6d9`

## 📱 Features Breakdown

### 1. **Floating Hearts Animation**
- 4 different heart emojis
- Random size and speed variations
- Continuously regenerated background element

### 2. **Love Message Typing Effect**
- 6 pre-loaded romantic messages (customizable)
- Character-by-character typing animation
- Blinking cursor effect

### 3. **Heart Explosion**
- 20 particle heart burst
- Random directions radial animation
- Smooth fade-out effect

### 4. **Photo Upload**
- Click to upload your favorite couple photo
- Drag-and-drop compatible
- Image preview with smooth animation

### 5. **Countdown Timer**
- Calculates days to next Valentine's Day
- Updates every second
- Displays days, hours, minutes, seconds

### 6. **Playful Yes/No Buttons**
- Yes button triggers heart explosion and message
- No button moves away on hover (uses random positioning)
- Mobile-friendly behavior

### 7. **Responsive Design**
- Desktop: Full layout
- Tablet (768px): Optimized spacing
- Mobile (480px): Compact, single-column layout

## 🎵 Audio Compatibility

The app includes music playback with fallback handling:
- Browsers may block autoplay (security policy)
- Users must click the music button (🔊) to start playback
- Volume is set to 30% to not be intrusive
- Works on all modern browsers

## 💡 Tips & Tricks

1. **Print to PDF**: You can print the page (Ctrl+P) to create a PDF version to share
2. **Change Emoji**: Modify heart emojis in the code - use any emoji you like!
3. **Dark Mode**: Change colors to dark theme by modifying the gradient
4. **Multiple Pages**: Duplicate and customize for different versions

## 🔧 Browser Support

Works on all modern browsers:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 File Structure

```
Valentines_Day_App/
├── index.html          (Complete app - HTML, CSS, JS)
└── README.md           (This file)
```

That's it! Just one file to deploy.

## 🎁 What's Included

The app includes:
- ~15KB total size (uncompressed)
- Zero external dependencies
- All CSS and JavaScript inline
- Remote music streaming (via Bensound)
- Instant loading

## 💭 Ideas for Personalization

1. **Add a gallery section** - Multiple photos with navigation
2. **Custom music** - Upload your favorite romantic song
3. **Memory timeline** - Add key dates and memories
4. **Couple quiz** - Fun questions for dating couples
5. **Sharing feature** - Generate social media posts
6. **Dark mode toggle** - Switch between light/dark themes
7. **Comment section** - Personal notes throughout the day

## ⚠️ Notes

- The default music is a free sample. Replace with your own for better personalization
- Image uploads are stored only in memory (not saved to server)
- Works offline (except for the default background music)
- No external APIs or tracking

## 📄 License

Free to use, modify, and share. enjoy! 💕

## 🤝 Support

If you encounter any issues:
1. Check browser console (F12) for errors
2. Ensure JavaScript is enabled
3. Try a different browser
4. Clear browser cache

---

**Created with ❤️ for Valentine's Day**

Happy Valentine's Day! 💕💕💕
