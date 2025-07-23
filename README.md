# Password Generator (Vanilla JavaScript Version)

A secure, cryptographically-strong password generator with a modern dark theme UI built with pure vanilla JavaScript - **no dependencies required**.

## 🔐 Features

- **Cryptographically Secure**: Uses `crypto.getRandomValues()` for true randomness
- **Base64 Output**: Optional Base64 encoding for generated passwords
- **Zero Dependencies**: Pure vanilla JavaScript - works anywhere
- **Customizable Character Sets**: 
  - Lowercase letters (a-z)
  - Uppercase letters (A-Z)
  - Numbers (0-9)
  - Basic symbols (!?#$&*@)
  - Extended symbols (%()+-=[]{}|~.,)
- **Advanced Options**:
  - Skip similar characters (0OoIl1)
  - All unique characters (no repeats)
  - Balanced character sets (equal probability)
- **Quick Length Presets**: 8, 12, 16, 24, 32 characters
- **Individual Copy Buttons**: Copy each password separately
- **Bulk Actions**: Copy all, export to file, clear all
- **Settings Memory**: Preferences saved to localStorage
- **Secure Memory Handling**: Automatic clipboard clearing after 60 seconds
- **Mobile Optimized**: Responsive design for all devices
- **Accessibility**: ARIA labels and keyboard shortcuts
- **Dark Mode Only**: Professional dark theme

## 🚀 Quick Start

### Prerequisites
- Modern web browser with JavaScript enabled
- **No external dependencies required**

### Usage
1. Open `pass_gen_off.html` in your web browser
2. Configure your password preferences:
   - Set desired length (4-128 characters)
   - Choose number of passwords (1-50)
   - Select character sets
   - Toggle advanced options
3. Click "🚀 Generate Secure Passwords"
4. Copy individual passwords or use bulk actions

## 📁 Files
- `pass_gen_off.html` - Complete standalone application file

## ⌨️ Keyboard Shortcuts
- `Ctrl/Cmd + Enter` - Generate passwords

## 🔧 Dependencies
- **None** - Completely self-contained
- Works offline without any external files
- Pure vanilla JavaScript implementation

## 🛡️ Security Features
- Cryptographically secure random number generation
- Automatic memory clearing of sensitive data
- Clipboard auto-clear after 60 seconds
- No data transmission (fully client-side)
- No external dependencies to trust

## 🎨 UI Features
- Modern gradient dark theme
- Responsive grid layout
- Touch-friendly controls
- Visual feedback for all actions
- High contrast mode support
- Reduced motion support for accessibility

## ⚡ Performance
- Faster load time (no external library loading)
- Smaller total size when considering dependencies
- Modern ES6+ JavaScript features
- Optimized DOM manipulation

## 🔄 Version Comparison
This is the **Vanilla JavaScript version** - also available:
- `pass_gen.html` - jQuery version (requires jQuery 3.6.0)

Choose this version if:
- You want zero dependencies
- You prefer modern vanilla JavaScript
- You need maximum compatibility and portability
- You want the fastest load times
- You're building for environments without jQuery

## 📝 License
MIT License - see LICENSE file for details

## 👨‍💻 Author
George Michalopoulos (TGTF)
Email: gmichalopoulos82@gmail.com

---
*Built with security and usability in mind. No passwords are stored or transmitted. Completely self-contained.*
