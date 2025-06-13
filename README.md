# FocusPulse ⏰

A sleek and intuitive Pomodoro timer application built by Hugo Adona. Boost your productivity and maintain focus using the proven Pomodoro Technique with a modern, distraction-free interface.

## 🚀 Features

- **Classic Pomodoro Timer**: Traditional 25-minute work sessions with 5-minute breaks
- **Customizable Intervals**: Adjust work and break durations to fit your workflow
- **Session Tracking**: Monitor your daily and weekly productivity sessions
- **Visual Progress**: Beautiful circular progress indicator with smooth animations
- **Audio Notifications**: Gentle chimes and alerts for session transitions
- **Background Sounds**: Optional focus sounds (white noise, nature sounds, café ambiance)
- **Task Management**: Simple task list to track what you're working on
- **Statistics Dashboard**: Detailed analytics of your focus sessions
- **Dark/Light Themes**: Choose yourQ preferred visual mode
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Offline Support**: Works without internet connection
- **Keyboard Shortcuts**: Quick controls for power users

## 🎯 The Pomodoro Technique

The Pomodoro Technique is a time management method developed by Francesco Cirillo:

1. **Choose a task** you want to work on
2. **Set the timer** to 25 minutes (one "pomodoro")
3. **Work on the task** until the timer rings
4. **Take a short break** (5 minutes)
5. **Repeat** the process
6. **After 4 pomodoros**, take a longer break (15-30 minutes)

## 🌟 Demo

Try FocusPulse live: [Demo Link](#) *(Update with your deployed URL)*

## 📱 Screenshots

*(Add screenshots of your application here)*

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Grid/Flexbox with custom animations
- **Audio**: Web Audio API for notifications and background sounds
- **Storage**: LocalStorage for settings and session data
- **Icons**: Custom SVG icons and Font Awesome
- **Charts**: Chart.js for statistics visualization

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional installations required!

### Installation

1. Clone the repository:
```bash
git clone https://github.com/HugoAdona/focuspulse.git
cd focuspulse
```

2. Serve the files locally:

**Using Python:**
```bash
# Python 3
python -m http.server 8000
```

**Using Node.js:**
```bash
npx serve .
```

**Using PHP:**
```bash
php -S localhost:8000
```

3. Open your browser and navigate to `http://localhost:8000`

### Quick Start

1. **Set Your Task**: Enter what you want to focus on
2. **Click Start**: Begin your first 25-minute pomodoro
3. **Stay Focused**: Work until the timer alerts you
4. **Take a Break**: Enjoy your well-deserved 5-minute break
5. **Repeat**: Continue the cycle to maintain peak productivity

## ⚙️ Usage Guide

### Basic Controls

- **Start/Pause**: Begin or pause your current session
- **Reset**: Reset the current timer
- **Skip**: Skip to the next session (work → break → work)
- **Settings**: Customize timer durations and preferences

### Timer Customization

- **Work Duration**: Default 25 minutes (adjustable 15-60 minutes)
- **Short Break**: Default 5 minutes (adjustable 3-15 minutes)
- **Long Break**: Default 15 minutes (adjustable 10-30 minutes)
- **Long Break Interval**: After how many work sessions (default: 4)

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Spacebar` | Start/Pause timer |
| `R` | Reset current session |
| `S` | Skip to next session |
| `T` | Add new task |
| `Esc` | Close modals/settings |
| `1-9` | Quick timer presets |

### Task Management

- **Add Tasks**: Create a simple todo list
- **Mark Complete**: Check off finished tasks
- **Task Timer**: Associate pomodoros with specific tasks
- **Daily Goals**: Set target number of pomodoros per day

## 📊 Statistics & Analytics

FocusPulse tracks your productivity with detailed statistics:

- **Daily Sessions**: Number of completed pomodoros today
- **Weekly Overview**: Productivity trends over the week
- **Task Completion**: Which tasks you've been working on
- **Focus Streaks**: Longest consecutive productive sessions
- **Time Breakdown**: Work vs break time analysis
- **Goal Progress**: Daily and weekly target achievement

## 🎨 Customization

### Themes

- **Light Theme**: Clean and minimal for daytime use
- **Dark Theme**: Easy on the eyes for evening sessions
- **Auto Theme**: Follows your system preference
- **Custom Colors**: Personalize accent colors

### Sounds

- **Notification Sounds**: Bell, chime, or subtle beep
- **Background Sounds**: 
  - White noise
  - Rain sounds
  - Forest ambiance
  - Café atmosphere
  - Ocean waves
  - Custom upload support

### Visual Settings

- **Progress Style**: Circular, linear, or minimal
- **Animations**: Enable/disable smooth transitions
- **Display Mode**: Full-screen focus mode available

## 📁 Project Structure

```
focuspulse/
├── index.html              # Main HTML file
├── css/
│   ├── main.css           # Main stylesheet
│   ├── timer.css          # Timer component styles
│   ├── statistics.css     # Stats dashboard styles
│   ├── themes.css         # Theme definitions
│   └── responsive.css     # Mobile responsiveness
├── js/
│   ├── app.js             # Main application logic
│   ├── timer.js           # Pomodoro timer functionality
│   ├── tasks.js           # Task management
│   ├── statistics.js      # Analytics and charts
│   ├── settings.js        # User preferences
│   ├── audio.js           # Sound management
│   └── storage.js         # Local storage handling
├── sounds/
│   ├── notifications/     # Alert sounds
│   └── background/        # Ambient sounds
├── assets/
│   ├── icons/             # UI icons
│   └── images/            # Background images
├── README.md
└── LICENSE
```

## 💾 Data Storage

All data is stored locally in your browser:

```javascript
// Settings format
{
  "workDuration": 25,
  "shortBreakDuration": 5,
  "longBreakDuration": 15,
  "longBreakInterval": 4,
  "theme": "light",
  "soundEnabled": true,
  "backgroundSound": "none"
}

// Session data format
{
  "date": "2025-06-13",
  "sessions": [
    {
      "type": "work",
      "duration": 25,
      "completed": true,
      "task": "Write documentation",
      "timestamp": 1718294400000
    }
  ]
}
```

## 🌐 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Enable GitHub Pages in repository settings
3. Your app will be live at `https://yourusername.github.io/focuspulse`

### Netlify

1. Connect your GitHub repository to Netlify
2. No build configuration needed
3. Deploy automatically on every commit

### Vercel

1. Import your project from GitHub
2. Zero configuration deployment
3. Automatic HTTPS and global CDN

## 📱 PWA Features

FocusPulse can be installed as a Progressive Web App:

- **Add to Home Screen**: Install on mobile devices
- **Offline Support**: Works without internet connection
- **Push Notifications**: Optional session reminders
- **Full-screen Mode**: Distraction-free experience

## 🤝 Contributing

Help make FocusPulse even better! Contributions are welcome from developers and productivity enthusiasts.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/ProductivityBoost`)
3. Commit your Changes (`git commit -m 'Add amazing productivity feature'`)
4. Push to the Branch (`git push origin feature/ProductivityBoost`)
5. Open a Pull Request

### Contribution Ideas

- **New Themes**: Additional color schemes and visual styles
- **Sound Library**: More background and notification sounds
- **Integrations**: Calendar, task management, or note-taking apps
- **Advanced Analytics**: More detailed productivity insights
- **Team Features**: Shared sessions or productivity challenges
- **Accessibility**: Improved screen reader and keyboard navigation

## 🐛 Bug Reports & Feature Requests

Found a bug or have an idea? Open an issue on GitHub:

1. Check existing issues first
2. Use the appropriate issue template
3. Provide detailed information for bugs
4. Include screenshots if helpful

## 🏆 Productivity Tips

Get the most out of FocusPulse:

- **Start Small**: Begin with shorter work sessions if 25 minutes feels too long
- **Eliminate Distractions**: Close unnecessary tabs and put your phone away
- **Plan Your Tasks**: Know what you'll work on before starting the timer
- **Take Real Breaks**: Step away from your screen during break time
- **Track Progress**: Review your statistics to identify productivity patterns
- **Stay Consistent**: Regular use builds better focus habits

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Hugo Adona**
- GitHub: [@HugoAdona](https://github.com/HugoAdona)
- Website: [Your Website]

## 🙏 Acknowledgments

- Francesco Cirillo for developing the Pomodoro Technique
- Productivity enthusiasts and time management researchers
- Open source contributors and the web development community
- Users who provide feedback and suggestions

## 🔗 Related Projects

- [DrumLab](https://github.com/HugoAdona/drumlab) - Web-based drum machine
- [MarkdownMagic](https://github.com/HugoAdona/markdownmagic) - Markdown editor
- [Quotely](https://github.com/HugoAdona/quotely) - Random quote generator

## 📚 Further Reading

- [The Pomodoro Technique Official Website](https://francescocirillo.com/pages/pomodoro-technique)
- [Time Management Research and Studies](https://example.com)
- [Productivity and Focus Techniques](https://example.com)

---

**"Productivity is never an accident. It is always the result of a commitment to excellence, intelligent planning, and focused effort."** - Paul J. Meyer

Start your focused work sessions today with FocusPulse! ⏰✨