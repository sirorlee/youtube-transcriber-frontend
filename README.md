# YouTube Transcriber Frontend

Modern web interface for AI-powered YouTube transcription supporting 99+ languages.

## 🚀 Features

- 🎥 **YouTube Video Transcription** - Paste any YouTube URL
- 📁 **File Upload Support** - Upload audio/video files directly  
- 🌍 **99+ Languages** - Complete Whisper AI language support
- 📝 **Multiple Formats** - TXT, SRT, VTT, JSON, CSV, Markdown
- ⚡ **Real-time Progress** - Live transcription updates
- 📱 **Mobile Responsive** - Works on all devices
- 🎨 **Modern UI** - Beautiful gradient design

## 🛠️ Setup Instructions

### 1. Configure Backend URL

**IMPORTANT**: Before deploying, update the backend URL in `index.html`:

```javascript
// Line ~47 in index.html
const API_BASE_URL = 'https://your-railway-app.railway.app';
