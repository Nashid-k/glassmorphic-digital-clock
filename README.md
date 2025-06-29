# 🕐 Advanced Digital Clock

A modern, feature-rich digital clock web application with stunning animations, alarm functionality, and a beautiful user interface. Built with pure HTML, CSS, and JavaScript - no external dependencies required!

## ✨ Features

### 🎨 **Visual Design**
- **Animated Background**: Dynamic gradient with twinkling star field
- **Glassmorphism UI**: Modern frosted glass design with glowing borders
- **Smooth Animations**: Pulse effects, hover transitions, and tick animations
- **Dark/Light Themes**: Toggle between beautiful dark and light modes
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices

### ⏰ **Clock Functionality**
- **Real-time Display**: Accurate time with smooth second transitions
- **Format Toggle**: Switch between 12-hour and 24-hour formats
- **Date Display**: Shows current date with full weekday and month names
- **Visual Feedback**: Time pulses with each second for better UX

### 🔔 **Advanced Alarm System**
- **Easy Setup**: Simple time input with intuitive interface
- **Visual Alerts**: Full-screen animated modal instead of basic alerts
- **Dual Actions**: 
  - **Dismiss**: Turn off alarm completely
  - **Snooze**: Automatically reschedule for 5 minutes later
- **Status Indicator**: Shows current alarm status
- **Persistent Ringing**: Alarm continues until user interaction

### 🔊 **Audio Features**
- **Tick Sounds**: Subtle audio feedback for each second
- **Alarm Tones**: Dual-frequency alarm sound for effective wake-up
- **Web Audio API**: All sounds generated programmatically (no external files)
- **Cross-browser**: Compatible with all modern browsers

## 🚀 Quick Start

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Enjoy your advanced digital clock!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/advanced-digital-clock.git
cd advanced-digital-clock
```

Then open `index.html` in your browser.

### Option 3: Live Demo
Simply open the `index.html` file in any modern web browser. No server required!

## 🖥️ Browser Compatibility

- ✅ Chrome 66+
- ✅ Firefox 60+
- ✅ Safari 13+
- ✅ Edge 79+

*Note: Audio features require user interaction to work due to browser autoplay policies.*

## 📱 Usage

### Setting the Time Format
- Click **"Switch to 24-Hour"** to toggle between 12-hour and 24-hour formats
- The display updates instantly with your preference

### Changing Themes
- Click **"🌙 Dark Mode"** / **"☀️ Light Mode"** to switch themes
- Smooth transition between dark and light appearances

### Setting an Alarm
1. Click on the time input field
2. Select your desired alarm time
3. Click **"⏰ Set Alarm"**
4. The status indicator will confirm your alarm is set

### When Alarm Rings
- A full-screen modal will appear with pulsing animation
- Audio alarm will play repeatedly
- Choose to **Dismiss** (turn off) or **Snooze** (5 more minutes)

## 🛠️ Technical Details

### File Structure
```
advanced-digital-clock/
├── index.html          # Complete application (HTML + CSS + JS)
└── README.md           # This file
```

### Technologies Used
- **HTML5**: Semantic markup and modern features
- **CSS3**: Advanced animations, gradients, and responsive design
- **Vanilla JavaScript**: No frameworks or libraries required
- **Web Audio API**: Programmatic sound generation
- **CSS Grid/Flexbox**: Modern layout techniques

### Key Features Implementation
- **Real-time Updates**: `setInterval()` for smooth clock updates
- **Audio Generation**: Web Audio API for tick and alarm sounds
- **Responsive Design**: CSS media queries and flexible units
- **Theme Switching**: CSS custom properties and class toggling
- **Local Time**: JavaScript `Date` object for accurate time display

## 🎨 Customization

The clock is highly customizable! You can modify:

### Colors & Themes
```css
/* Dark theme gradient */
background: linear-gradient(135deg, #0f0f23, #1a1a3a, #2d1b69);

/* Light theme gradient */
background: linear-gradient(135deg, #f0f8ff, #e6f3ff, #d4edda);
```

### Animations
```css
/* Adjust pulse timing */
@keyframes pulseGlow {
  from { text-shadow: 0 0 20px rgba(74, 144, 226, 0.8); }
  to { text-shadow: 0 0 30px rgba(74, 144, 226, 1); }
}
```

### Alarm Settings
```javascript
// Change snooze duration (currently 5 minutes)
now.setMinutes(now.getMinutes() + 5); // Modify this value
```

## 🐛 Troubleshooting

### Audio Not Working
- **Cause**: Browser autoplay policies require user interaction
- **Solution**: Click anywhere on the page before setting an alarm

### Alarm Not Ringing
- **Check**: Ensure you've clicked on the page to enable audio
- **Verify**: Confirm the alarm time is set correctly
- **Browser**: Make sure you're using a supported browser

### Display Issues
- **Mobile**: Try rotating your device for better layout
- **Browser**: Ensure you're using a modern browser with CSS Grid support

## 🤝 Contributing

Contributions are welcome! Here are some ideas:

### Potential Enhancements
- [ ] Multiple alarm support
- [ ] Custom alarm sounds
- [ ] Timezone selection
- [ ] Stopwatch functionality
- [ ] Timer feature
- [ ] Weather integration
- [ ] Customizable themes

### How to Contribute
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

## 🙏 Acknowledgments

- Design inspiration from modern web applications
- Web Audio API documentation and examples
- CSS animation techniques from the web development community

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Troubleshooting](#-troubleshooting) section
2. Create an issue on GitHub
3. Review the code comments in `index.html`

---

⭐ **If you found this project helpful, please give it a star!** ⭐

*Made with ❤️ using vanilla web technologies*
