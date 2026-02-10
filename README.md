# Screen Share - Minimalist Screen Sharing Tool

![Screen Share App Preview](/screenshot.png)

A clean, minimalist web application for screen sharing with fullscreen preview functionality. This tool works entirely in the browser with no server-side processing required.

## ✨ Features

- **🎥 Screen Sharing**: Share your entire screen, specific windows, or browser tabs
- **🖥️ Fullscreen Preview**: Click-to-enter fullscreen mode for better viewing
- **⌨️ Keyboard Shortcuts**: Quick actions with keyboard shortcuts
- **🎨 Modern Design**: Clean, minimalist interface with earthy color palette
- **📱 Responsive**: Works on desktop and tablet devices
- **🔒 Privacy**: All processing happens locally in your browser
- **🚀 No Installation**: Works directly in modern browsers

## 🎯 Live Demo

[https://fahrul.id/html-share-screen]

## 🛠️ Technologies Used

- **HTML5**: Structure and semantics
- **CSS3**: Modern styling with Flexbox/Grid
- **JavaScript**: Screen Capture API, Fullscreen API
- **Font Awesome**: Icon toolkit

## 🚀 Quick Start

### Option 1: Direct Usage
Simply open the HTML file in any modern web browser:
```bash
# Double-click the HTML file, or
open index.html
```

### Option 2: Serve Locally (Recommended)
```bash
# Using Python
python3 -m http.server 8000

# Using Node.js with http-server
npx http-server .

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## 📖 How to Use

### Basic Usage
1. **Start Sharing**: Click the "Share Screen" button
2. **Select Source**: Choose your entire screen, a window, or a tab
3. **View Preview**: Your screen appears in the preview area
4. **Fullscreen**: Click the preview or use the Fullscreen button
5. **Stop**: Click "Stop Sharing" when finished

### Keyboard Shortcuts
| Shortcut | Action |
|----------|--------|
| `Ctrl + Shift + S` | Start screen sharing |
| `Ctrl + Shift + X` | Stop screen sharing |
| `F` | Toggle fullscreen mode |
| `ESC` | Exit fullscreen |

### Color Palette
The app uses a cohesive earthy color scheme:
- **#254F22**: Primary actions (Share button)
- **#A03A13**: Destructive actions (Stop button)
- **#F5824A**: Accent/Fullscreen actions
- **#EDE4C2**: Background/Neutral
- **#FFFFFF**: Cards/Containers

## 🌐 Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome | ✅ Full | Version 72+ |
| Edge | ✅ Full | Version 79+ |
| Firefox | ✅ Full | Version 66+ |
| Safari | ✅ Full | Version 13+ |
| Opera | ✅ Full | Version 60+ |

## ⚙️ Technical Details

### APIs Used
- **Screen Capture API**: `navigator.mediaDevices.getDisplayMedia()`
- **Fullscreen API**: `Element.requestFullscreen()`
- **MediaStream API**: Real-time screen capture

### File Structure
```
screen-share/
├── index.html          # Main application file
├── README.md          # This documentation
└── (Optional assets)
```

## 🔧 Development

### Local Development
1. Clone or download the HTML file
2. Open in your preferred code editor
3. Make changes as needed
4. Test locally

### Customizing
- **Colors**: Modify the CSS variables or color values
- **Layout**: Adjust grid/flexbox properties
- **Features**: Extend JavaScript functionality

### Troubleshooting
**Issue**: "Your browser does not support screen sharing"
- Solution: Update to the latest browser version
- Ensure you're using HTTPS (required for screen sharing on most browsers)

**Issue**: Permission denied
- Solution: Allow screen sharing when prompted
- Check browser settings for screen sharing permissions

**Issue**: No video in preview
- Solution: Refresh the page and try again
- Check if other applications are blocking screen capture

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Icons provided by [Font Awesome](https://fontawesome.com)
- Color palette inspired by earthy tones
- Built with modern web standards

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For questions or feedback:
- Create an issue in the repository
- hello@fahrul.id

---

Made with ❤️ for seamless screen sharing experiences
