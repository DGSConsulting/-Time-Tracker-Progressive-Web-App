# ⏱️ Time Tracker

A simple, professional time tracking web app that works offline. Perfect for freelancers and consultants who need to track billable hours.

![PWA Ready](https://img.shields.io/badge/PWA-Ready-brightgreen)
![Offline Support](https://img.shields.io/badge/Offline-Supported-blue)

## ✨ Features

- **One-click timer** - Start/stop with spacebar
- **Project management** - Organize work by client/project
- **Manual entries** - Add time for past work
- **Reports & charts** - See where your time goes
- **Works offline** - No internet required
- **Installs like an app** - Add to home screen

## 🚀 Quick Start

1. **Download**: Clone or download this repository
2. **Serve**: Run a local server (required for PWA features)
   ```bash
   python -m http.server 8000
   # or
   npx http-server
   ```
3. **Open**: Go to `http://localhost:8000`
4. **Install**: Click the install button in your browser

## 📖 How to Use

### Basic Time Tracking
1. Go to **Projects** tab → Add a project
2. Go to **Timer** tab → Select your project
3. Hit **Start Timer** (or press spacebar)
4. Work on your project
5. Hit **Stop Timer** when done

### Keyboard Shortcuts
- **Spacebar** - Start/stop timer
- **1-9 keys** - Quick select projects

### Reports
- Go to **Reports** tab
- Filter by Today/Week/Month
- See total hours, earnings, and time breakdown

## 🔧 Tech Stack

- HTML5, CSS3, JavaScript (no frameworks)
- IndexedDB for data storage
- Chart.js for visualizations
- Service Worker for offline support

## 📱 Features Detail

- **Timer**: Large display, visual feedback when running
- **Projects**: Color coding, hourly rates, client names
- **Entries**: Automatic from timer + manual entry option
- **Reports**: Statistics cards + doughnut chart
- **Data**: Everything stored locally, no cloud required

## 🐛 Troubleshooting

**Timer won't start?** - Select a project first  
**Can't install as app?** - Must run from a server, not file://  
**Data not saving?** - Check browser console for errors  

## 🤝 Contributing

1. Fork this repo
2. Make your changes
3. Test thoroughly
4. Submit a pull request

## 📄 License

MIT License - feel free to use and modify.

---

**Part of the DGS Consulting suite of business tools - streamlining operations and boosting productivity for small businesses everywhere.**

Simple time tracking that solves real business problems. No complexity, just results.
