# 🎬 ScreenFlow - Professional Web Screen Recorder

[![Pure JavaScript](https://img.shields.io/badge/Pure-JavaScript-f1e05a?style=flat-square)](https://www.javascript.com/)
[![HTML5](https://img.shields.io/badge/HTML5-Latest-e34c26?style=flat-square)](https://html.spec.whatwg.org/)
[![License MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![No Dependencies](https://img.shields.io/badge/No-Dependencies-brightgreen?style=flat-square)](#)

A **powerful, professional-grade screen recorder** for the web. Built entirely with vanilla JavaScript, featuring a modern desktop-like interface, robust audio recording, and seamless responsiveness across all devices.

Perfect for content creators, developers, educators, and anyone who needs to capture screen recordings with professional quality.

---

## ✨ Core Features

### 🎥 Recording Capabilities
- **Multiple Resolutions**: 720p HD • 1080p Full HD • 1440p 2K • 2160p 4K
- **Flexible Frame Rates**: 30 FPS • 60 FPS • 120 FPS (ultra-smooth)
- **High Quality Codec**: VP9/VP8 with automatic fallback
- **Optimized Bitrate**: 5 Mbps video + 128 Kbps audio (adjustable)
- **Cursor Options**: Show or hide mouse cursor during recording

### 🔊 Audio Recording (Fully Fixed ✅)
- **4 Audio Source Options**:
  - No Audio (screen-only)
  - Speaker/System Audio Only
  - Microphone Only
  - Both Microphone & Speaker (mixed)
- **Audio Enhancement**:
  - Echo Cancellation - Removes feedback
  - Noise Suppression - Filters background noise
  - Auto Gain Control - Maintains consistent levels
- **Proper Audio Mixing**: Multiple audio sources combined seamlessly
- **Cross-Platform Support**: Works reliably on Chrome, Firefox, Edge, Opera

### 🎮 Recording Controls
- **Play/Pause/Stop**: Full control during recording
- **Real-Time Timer**: Live H:MM:SS format display
- **Countdown Timer**: 3, 5, or 10-second pre-recording countdown
- **Video Preview**: Built-in player with playback controls
- **Keyboard Shortcuts**:
  - **Space** - Start/Pause recording
  - **S** - Stop recording

### 💾 File Management
- **Auto Download**: Optional automatic saving on recording complete
- **Smart Naming**: Timestamped filenames (format: `Recording_YYYY-MM-DD_HH-MM-SS.webm`)
- **Recording Preview**: Inline video player with metadata
- **Recording Details**: View duration, file size, and format info
- **One-Click Download**: Download any time after recording

### 🎨 Professional Desktop Interface
- **Native Titlebar**: Status indicator and app name
- **Sidebar Settings**: All controls organized in collapsible panel
- **Clean Layout**: Main recording area with prominent timer
- **Light/Dark Themes**: Toggle with persistent preference
- **Status Indicators**: Real-time recording/paused/ready status
- **Modern Design**: Professional appearance inspired by native apps

### ⚡ Technical Excellence
- **Zero Dependencies**: Pure vanilla JavaScript - no frameworks or libraries
- **Privacy First**: 100% local processing - nothing uploaded to servers
- **Smooth Performance**: Optimized rendering and memory management
- **Persistent Settings**: All preferences saved to browser storage
- **Error Handling**: User-friendly error messages for troubleshooting
- **Memory Efficient**: Proper stream cleanup prevents memory leaks

---

## 🚀 Quick Start Guide

### Installation
No installation needed! Simply:

1. **Download or Clone**
   ```bash
   git clone https://github.com/yourusername/ScreenFlow.git
   # or download as ZIP
   ```

2. **Open in Browser**
   - Navigate to the downloaded folder
   - Open `index.html` in Chrome, Firefox, Edge, or Opera
   - Grant screen recording and microphone permissions when prompted

3. **Start Recording**
   - Click "Start" or press **Space**
   - Select screen/window to capture
   - Begin recording!

**That's it! No setup, build process, or server required.**

### Basic Workflow

#### Step 1: Configure Settings (Optional)
The sidebar contains all recording settings:
- **Audio Source**: Choose speaker, mic, or both
- **Video Quality**: Select 720p to 4K
- **Frame Rate**: Pick 30, 60, or 120 FPS
- **Audio Enhancement**: Enable echo cancellation
- **Auto Download**: Toggle automatic saving
- **Countdown Timer**: Set pre-recording delay

#### Step 2: Start Recording
- Click the **"Start"** button
- Or press **Space** on your keyboard
- Select the screen/window to capture from system dialog
- Optional countdown will display if configured

#### Step 3: Control Recording
While recording:
- Press **Space** to pause/resume
- Press **S** to stop recording
- Watch the live timer count up
- Status indicator shows recording state

#### Step 4: Save Recording
After recording stops:
- Video preview appears automatically
- View duration, file size, and format
- Click **"Download"** to save
- Or enable auto-download in settings

---

## ⚙️ Complete Settings Reference

### Audio Settings

| Option | Best For | Details |
|--------|----------|---------|
| **No Audio** | Screen-only captures | Records video only, no sound |
| **Speaker Only** | Games, music, apps | Captures system audio output |
| **Microphone Only** | Narration, tutorials | Records your voice/commentary |
| **Mic + Speaker** | Professional tutorials | Mixes both sources together |

**Audio Enhancement** (when enabled):
- ✅ Echo Cancellation
- ✅ Noise Suppression (filters background noise)
- ✅ Auto Gain Control (maintains volume levels)

### Quality Presets

| Resolution | Dimensions | File Size | Best For |
|-----------|-----------|-----------|----------|
| **720p HD** | 1280 × 720 | ~50 MB/min | Web sharing, screencasts |
| **1080p Full HD** | 1920 × 1080 | ~80 MB/min | Professional content, tutorials |
| **1440p 2K** | 2560 × 1440 | ~120 MB/min | High-quality archives |
| **2160p 4K** | 3840 × 2160 | ~200 MB/min | Premium production, cinema |

### Frame Rate Selection

- **30 FPS** - Presentations, webinars, slow content
- **60 FPS** - General use, animations, normal gameplay
- **120 FPS** - Fast-paced games, sports, smooth motion

### Advanced Options

| Setting | Options | Purpose |
|---------|---------|---------|
| **Show Cursor** | On / Off | Include mouse pointer in recording |
| **Auto Download** | On / Off | Automatically save completed recordings |
| **Countdown** | None / 3s / 5s / 10s | Delay before recording starts |

---

## 🎯 Use Cases

Perfect for:

✅ **Tutorial & Educational Content** - Screen + narration with proper audio mixing  
✅ **Software Demonstrations** - Showcase features and workflows  
✅ **Gameplay Recording** - 60-120 FPS smooth captures  
✅ **Presentation Recording** - Slide shows with audio commentary  
✅ **Bug Documentation** - Quick issue reproduction videos  
✅ **Online Training** - Professional-quality educational material  
✅ **Video Content Creation** - YouTube, TikTok, social media  
✅ **Conference Talks** - Record presentations and Q&A  
✅ **Webinar Recording** - Screen + multiple audio sources  
✅ **Software Comparison** - Side-by-side feature demos  

---

## 📱 Responsive Design

ScreenFlow works perfectly on all screen sizes:

| Device | Width | Layout | Notes |
|--------|-------|--------|-------|
| **Desktop** | 1024px+ | Sidebar + Main Panel | Full UI with all controls visible |
| **Laptop** | 768-1024px | Stacked (Sidebar Top) | Settings panel collapses nicely |
| **Tablet** | 480-768px | Optimized Touch UI | Touch-friendly buttons and controls |
| **Mobile** | <480px | Minimalist Interface | Essential controls only - fully functional |

All layouts maintain full functionality regardless of screen size.

---

## 🌐 Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| **Chrome** | ✅ Full | All features - primary browser |
| **Chromium (Edge)** | ✅ Full | All features supported |
| **Firefox** | ✅ Full | All features supported |
| **Opera** | ✅ Full | All features supported |
| **Safari** | ⚠️ Limited | Basic recording (audio limited) |

**Requirements:**
- HTTPS connection (except for localhost)
- Screen sharing permission
- Microphone permission (if using audio)
- Modern browser with MediaRecorder API support

---

## 🔧 Technical Specifications

### Video Format
- **Container**: WebM (Matroska-based)
- **Video Codec**: VP9 (primary) → VP8 (fallback) → WebM (fallback)
- **Video Bitrate**: 5 Mbps (high quality)
- **Resolution**: User-selectable (720p to 4K)
- **Frame Rate**: User-selectable (30, 60, 120 FPS)

### Audio Format
- **Sample Rate**: 48 kHz (browser default)
- **Channels**: Stereo
- **Bitrate**: 128 Kbps
- **Codec**: Opus (WebM container)

### Audio Processing
- **Echo Cancellation**: Browser-provided AEC (WebRTC)
- **Noise Suppression**: Browser-provided noise suppression
- **Auto Gain Control**: Browser-provided AGC
- **Stream Mixing**: JavaScript Web Audio API

### Performance
- **Memory Efficient**: Minimal RAM usage during recording
- **CPU Optimization**: Hardware-accelerated encoding
- **Real-Time**: Live timer and status updates
- **Smooth**: No UI lag even during high-quality recording

---

## 💾 Data Storage & Privacy

### What Gets Stored
- **Settings**: Recording preferences (audio, quality, framerate, etc.)
- **Theme**: Light/dark mode preference
- **Nothing Else**: Recordings are temporary in browser memory

### Important Notes
✅ **100% Private** - All processing happens locally  
✅ **Zero Cloud Upload** - Nothing leaves your device  
✅ **No Tracking** - No analytics or telemetry  
✅ **No Ads** - No advertisements  
✅ **Your Data** - You own all recordings  
✅ **No Accounts** - Works completely offline  

---

## 🐛 Troubleshooting

### ❌ "Permission Denied" Error
**Solution:**
1. Refresh the page
2. Click "Allow" when browser asks for permissions
3. Check browser privacy settings allow screen recording
4. For HTTPS: Ensure secure connection

### ❌ No Audio Recorded
**Check:**
1. Verify "Audio Source" setting in sidebar (not set to "No Audio")
2. Check system settings - microphone/speaker enabled
3. Test audio in another app first
4. Some apps block audio capture - try another app
5. Safari has limited audio support

### ❌ Large File Sizes
**Reduce by:**
1. Lower resolution: 4K → 1080p
2. Lower framerate: 120 FPS → 60 FPS
3. Note: File sizes vary by system and recording content

### ❌ Poor Audio Quality
**Improve by:**
1. Enable "Audio Enhancement" in settings
2. Move microphone closer
3. Check system volume levels
4. Close background noise sources
5. Disable other audio apps

### ❌ Recording Choppy/Lag
**Try:**
1. Close resource-heavy applications
2. Lower video quality or framerate
3. Check browser hardware acceleration is enabled
4. Restart browser
5. Free up system RAM

---

## ⌨️ Keyboard Shortcuts

| Key | Action | When |
|-----|--------|------|
| **Space** | Start / Pause | Anytime |
| **S** | Stop Recording | During recording |

These shortcuts provide quick control without reaching for the mouse.

---

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
```bash
# Push to GitHub
git add .
git commit -m "Deploy ScreenFlow"
git push origin main

# Enable in GitHub Settings:
# Settings → Pages → Source: main → Save
```
Your app will be at: `https://yourusername.github.io/ScreenFlow`

### Option 2: Vercel (Free & Super Easy)
1. Push code to GitHub
2. Connect repo to Vercel
3. Auto-deploys on every push

### Option 3: Netlify (Free)
1. Drag & drop `index.html` to Netlify
2. Or connect GitHub repo
3. Instant deployment

### Option 4: Any Web Host
Simply upload `index.html` to web server root directory.

---

## 📋 Project Structure

```
ScreenFlow/
├── index.html      # Complete app in single file
├── README.md       # This file
└── LICENSE         # MIT License
```

That's it! Single HTML file containing all HTML, CSS, and JavaScript.

---

## 🔐 Security & Privacy

- **No External Requests**: Entire app runs locally
- **No Third-Party Libraries**: Zero external dependencies
- **No Tracking Code**: No analytics or telemetry
- **No Ads**: No advertising networks
- **Open Source**: Full code transparency
- **User Control**: Complete control over recording process

---

## 📝 License

MIT License - Use freely for personal and commercial projects.

See [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

We welcome improvements! To contribute:

1. **Report Bugs**: Open an issue on GitHub
2. **Suggest Features**: Describe your ideas with examples
3. **Submit Code**: Fork, modify, and create pull request
4. **Share Feedback**: Tell us how you use ScreenFlow

---

## 🙏 Credits & Inspiration

- **Built With**: Pure vanilla JavaScript - no frameworks
- **Inspired By**: Professional desktop recording tools like OBS, Camtasia
- **For**: Content creators, developers, educators, and everyone who needs to record their screen

---

## 📞 Support

### Common Questions

**Q: Is it free?**  
A: Yes, completely free and open-source.

**Q: Do I need an account?**  
A: No, works completely offline - no account needed.

**Q: Is my data safe?**  
A: Yes, everything stays on your device - nothing uploaded.

**Q: Does it work on mobile?**  
A: Mobile support is limited due to browser restrictions, but works on desktop/laptop tablets.

**Q: Can I edit recordings?**  
A: Not in ScreenFlow, but you can use VLC, FFmpeg, or Adobe Premiere after download.

**Q: How do I improve audio quality?**  
A: Enable "Audio Enhancement", use a better microphone, reduce background noise.

---

## 🚀 Roadmap

Potential future features:
- [ ] Drawing/annotation tools during recording
- [ ] Remote file upload (cloud storage)
- [ ] Video editing tools
- [ ] Multiple monitor support
- [ ] Watermark customization
- [ ] Batch processing
- [ ] Streaming to social platforms
- [ ] Plugin system

---

## 📊 Version History

### v2.0 (Latest) - Desktop App & Audio Overhaul
- ✅ Fixed complete audio recording system
- ✅ Proper microphone + speaker mixing
- ✅ New desktop app interface with titlebar
- ✅ Responsive sidebar settings panel
- ✅ Professional status indicators
- ✅ Stream resource cleanup
- ✅ Cross-browser optimization

### v1.0 - Initial Release
- Basic screen recording
- Multiple quality options
- Audio source selection
- Light/dark theme

---

<div align="center">

**Made with ❤️ for creators, developers, and educators**

[⭐ Star on GitHub](https://github.com) • [💬 Report Issue](https://github.com/issues) • [💡 Suggest Feature](https://github.com/discussions)

**Start recording your screen professionally today!** 🎬

</div>
