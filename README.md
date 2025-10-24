# 🔐 Password Strength Meter

A beautiful, minimal password strength meter that provides real-time feedback to help users create stronger passwords. Built with pure HTML, CSS, and JavaScript - no dependencies required!

![Password Strength Meter](https://img.shields.io/badge/Password-Strength%20Meter-blue?style=for-the-badge&logo=security)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-green?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Yes-purple?style=for-the-badge)

## ✨ Features

- **🎯 Real-time Analysis** - Instant feedback as you type
- **📊 Visual Strength Meter** - Color-coded progress bar with 5 strength levels
- **✅ Requirements Checklist** - Clear indicators for password criteria
- **📱 Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- **🚀 Zero Dependencies** - Pure HTML, CSS, and JavaScript
- **⚡ Lightning Fast** - No external libraries or frameworks
- **🎨 Beautiful Design** - Modern, clean interface with smooth animations

## 🎮 How It Works

### Password Scoring System
The meter evaluates passwords based on multiple criteria:

- **Length** (8+ characters) - 20 points
- **Uppercase Letters** (A-Z) - 20 points  
- **Lowercase Letters** (a-z) - 20 points
- **Numbers** (0-9) - 20 points
- **Special Characters** (!@#$%^&*) - 20 points
- **Length Bonus** (12+ chars: +10, 16+ chars: +10)
- **Variety Bonus** (8+ unique chars: +10)

**Maximum Score: 100 points**

### Strength Levels
| Level | Score Range | Color | Description |
|-------|-------------|-------|-------------|
| 🔴 Very Weak | 0-19 | Red | Needs significant improvement |
| 🟠 Weak | 20-39 | Orange | Below average security |
| 🟡 Fair | 40-59 | Yellow | Moderate security |
| 🟢 Good | 60-79 | Teal | Strong password |
| 🟢 Strong | 80-100 | Green | Excellent security |

## 🚀 Quick Start

1. **Download the files**
   ```bash
   git clone https://github.com/NoctisNex/Passcheck-Standalone.git
   cd Passcheck-Standalone
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in any modern web browser
   open index.html
   ```

3. **Start testing passwords!**
   - Type any password in the input field
   - Watch the real-time strength analysis
   - Follow the requirements checklist for stronger passwords

## 📁 Project Structure

```
Passcheck-Standalone/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── README.md           # This file
└── LICENSE             # MIT License
```

## 🎨 Customization

### Changing Colors
Edit the strength level colors in `styles.css`:
```css
.very-weak { background: #dc3545; }  /* Red */
.weak { background: #fd7e14; }        /* Orange */
.fair { background: #ffc107; }        /* Yellow */
.good { background: #20c997; }        /* Teal */
.strong { background: #28a745; }      /* Green */
```

### Modifying Requirements
Update the scoring criteria in the JavaScript section of `index.html`:
```javascript
// Example: Change minimum length from 8 to 10
if (password.length >= 10) {
    score += 20;
    // ... rest of the logic
}
```

## 📱 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Report bugs** - Found an issue? Open a GitHub issue
2. **Suggest features** - Have an idea? Let us know!
3. **Submit pull requests** - Fix bugs or add features
4. **Improve documentation** - Help others understand the project

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by modern password security best practices
- Built with accessibility and usability in mind
- Designed for simplicity and performance

---

<div align="center">

**Made with ❤️ for better password security**

[⭐ Star this repo](https://github.com/yourusername/Passcheck-Standalone) • [🐛 Report Bug](https://github.com/yourusername/Passcheck-Standalone/issues) • [💡 Request Feature](https://github.com/yourusername/Passcheck-Standalone/issues)

</div>
