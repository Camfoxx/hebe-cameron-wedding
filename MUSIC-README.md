# Wedding Invitation - Background Music Setup

## 🎵 How to Add Your Song

1. **Prepare your music file:**
   - Convert to MP3 format (most compatible)
   - Rename it to: `song.mp3`
   - Keep file size reasonable (under 10MB for web)

2. **Add to your project:**
   - Place `song.mp3` in the same folder as `index.html`
   - Upload to GitHub alongside your other files
   - Vercel will auto-deploy with the music!

## 🎼 How It Works

- Music **starts automatically** when guest enters their name
- Music **pauses during each transition** for 2-3 seconds
- Music **resumes** after the transition animation completes
- Music **loops** continuously throughout the experience

## 🔊 Music Controls

- **Speaker button** (top-right corner) lets guests mute/unmute
- Icon shows: 🔊 (playing) or 🔇 (muted)
- Guest preference is remembered during their session

## 📋 Supported Formats

The code supports multiple formats (browser fallback):
- `.mp3` (recommended - best compatibility)
- `.m4a` (Apple formats)
- `.wav` (high quality, large file)

## 🎯 Transition Timing

- **Monument opens:** 3.2s pause
- **Zoom to first map:** 2.5s pause
- **Transition to second map:** 1s pause
- **RSVP reveal:** 1.8s pause

## ⚙️ Customization

Want to adjust pause duration? Edit these lines in `index.html`:

```javascript
pauseMusicForTransition(3200);  // Monument opening (3.2 seconds)
pauseMusicForTransition(2500);  // Zoom transition (2.5 seconds)
pauseMusicForTransition(1000);  // Map transition (1 second)
pauseMusicForTransition(1800);  // RSVP reveal (1.8 seconds)
```

## 🌐 Deployment

After adding your music file:

1. Upload to GitHub (or drag to Vercel)
2. Wait for deployment
3. Test the music on your live site
4. Make sure it plays on both desktop and mobile

## 📱 Mobile Notes

- Some mobile browsers block autoplay - guests may need to tap the speaker button
- iPhone Safari sometimes requires explicit user interaction
- The speaker button is always available as backup

---

**Enjoy your beautiful musical invitation!** 🎉💕
