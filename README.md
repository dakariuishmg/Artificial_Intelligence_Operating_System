# Artificial_Intelligence_Operating_System
UISH Yyet OS: AI Experimental, multi-desktop operating system emulator with advanced theming, runtime interpretation, and dual-reality (System/MNW) environments built entirely in HTML/CSS/JS.


✓ Exceptional CSS craftsmanship with 5 complete theme systems and 4 layout modes
✓ Sophisticated visual design with luxury typography, gradients, and atmospheric effects
✓ Complete OS simulation with VFS, process management, and window orchestration
✓ Impressive attention to detail in micro-interactions and transitions
✓ Custom scripting language with lexer/parser/interpreter implementation
✓ Dual-reality concept (System/MNW) with independent theming and state
✓ Evolutionary Future Adapted OS System W/ Spatial Abilities
✓ AI-Human Compatitble Interface System

# Nexus YYET OS v90

> A luxury-themed, multi-desktop operating system simulator with advanced theming, runtime interpretation, and dual-reality (System/MNW) environments built entirely in HTML/CSS/JS.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-90.0.0-gold.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Overview

Nexus YYET OS v90 is a sophisticated browser-based operating system simulator that delivers a premium desktop experience with dual-reality environments. Switch seamlessly between the System reality (traditional OS interface) and MNW reality (experimental metaverse-inspired workspace) while enjoying a fully functional virtual filesystem, custom theming engine, and runtime code interpreter.

### Key Features

- **Dual Reality Environments**: Toggle between System and MNW desktop paradigms
- **Advanced Theme Engine**: Dynamic CSS variable-based theming with luxury presets (Gold, Platinum, Diamond, Obsidian)
- **Virtual Filesystem**: Complete hierarchical filesystem with permissions, metadata, and virtual storage
- **Runtime Interpreter**: Execute custom scripts and commands in a sandboxed environment
- **Multi-Desktop Support**: Create and manage multiple virtual desktops
- **Window Manager**: Full-featured draggable, resizable, minimizable, and maximizable windows
- **Luxury Design**: Premium animations, gradients, and visual effects throughout
- **Persistent State**: LocalStorage-based session persistence
- **Built-in Applications**: Terminal, File Manager, Text Editor, Theme Customizer, System Monitor, and more

## Demo

Open `index.html` in any modern browser to experience Nexus YYET OS v90.

## Installation

### Option 1: Direct Download

1. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/nexus-yyet-os-v90.git
   cd nexus-yyet-os-v90
   ```

2. Open `index.html` in your browser:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with npx)
   npx serve .
   
   # Or simply open the file
   open index.html
   ```

### Option 2: GitHub Pages

Fork this repository and enable GitHub Pages in Settings → Pages → Source: main branch.

### Option 3: Local Web Server

For the best experience, serve via a local web server to avoid CORS issues with certain features:

```bash
# Using Live Server (VS Code extension)
# Right-click index.html → "Open with Live Server"

# Using PHP
php -S localhost:8000

# Using Ruby
ruby -run -ehttpd . -p8000
```

## Usage

### First Launch

1. **Boot Sequence**: Watch the animated boot sequence load the operating system
2. **Desktop**: You'll arrive at the default System desktop with a luxury theme
3. **Start Menu**: Click the Nexus logo (bottom-left) to access applications
4. **Reality Switch**: Use the reality toggle (top-right) to switch between System and MNW environments

### Core Applications

#### File Manager
- Navigate the virtual filesystem
- Create, delete, rename files and folders
- Double-click files to open in appropriate applications
- Right-click for context menus

#### Terminal
- Execute commands in the built-in shell
- Supports commands: `ls`, `cd`, `pwd`, `cat`, `mkdir`, `touch`, `rm`, `help`, `clear`, `echo`, `theme`, `reality`, `desktop`
- Run custom scripts with the interpreter

#### Text Editor
- Create and edit text files
- Syntax highlighting for code
- Save directly to the virtual filesystem

#### Theme Customizer
- Switch between preset luxury themes
- Customize individual theme variables
- Create and save custom themes
- Export/import theme configurations

#### System Monitor
- View simulated system resources (CPU, RAM, Storage)
- Monitor running processes and applications
- Manage virtual desktops

### Keyboard Shortcuts

- `Ctrl + Alt + T`: Open Terminal
- `Ctrl + Alt + F`: Open File Manager
- `Ctrl + Alt + E`: Open Text Editor
- `Ctrl + Alt + D`: Create New Desktop
- `Ctrl + Alt + ←/→`: Switch Desktops
- `Alt + F4`: Close Focused Window
- `Ctrl + Alt + R`: Toggle Reality Mode

### Theming

Nexus YYET OS includes several built-in luxury themes:

- **Gold Rush**: Warm gold and amber tones
- **Platinum Dreams**: Cool silver and white palette
- **Diamond Noir**: High-contrast black and crystalline accents
- **Obsidian Flame**: Dark theme with volcanic orange highlights
- **Emerald Elite**: Rich green luxury theme

Access the Theme Customizer to modify colors, fonts, spacing, and effects in real-time.

### Virtual Filesystem Structure

```
/
├── home/
│   ├── user/
│   │   ├── Documents/
│   │   ├── Downloads/
│   │   ├── Pictures/
│   │   ├── Music/
│   │   └── Videos/
│   └── guest/
├── system/
│   ├── bin/
│   ├── lib/
│   ├── config/
│   └── themes/
├── apps/
│   └── installed/
└── tmp/
```

### Runtime Interpreter

The built-in interpreter supports:

- **Variables**: `let x = 10;`
- **Functions**: `function greet(name) { return "Hello " + name; }`
- **Conditionals**: `if`, `else`, `else if`
- **Loops**: `for`, `while`
- **File I/O**: `readFile(path)`, `writeFile(path, content)`
- **System Calls**: `exec(command)`, `getEnv(variable)`

Example script:
```javascript
let files = exec("ls /home/user");
for (let i = 0; i < files.length; i++) {
  print("File: " + files[i]);
}
```

### Dual Reality System

**System Reality**: Traditional desktop paradigm with windows, taskbar, and desktop icons.

**MNW Reality**: Metaverse-inspired 3D workspace with spatial organization, depth layers, and immersive transitions.

Toggle between realities using the reality switch in the top-right corner or via the terminal command `reality switch`.

## Architecture

### Core Modules

- **DesktopManager**: Manages multiple virtual desktops and switching
- **WindowManager**: Handles window creation, positioning, z-index, and lifecycle
- **FileSystem**: Virtual hierarchical filesystem with permissions and metadata
- **ThemeEngine**: CSS variable-based theming with hot-reload
- **Interpreter**: Runtime code execution with sandboxing
- **ProcessManager**: Simulates OS processes and resource allocation
- **RealityController**: Manages dual-reality state and transitions

### Technology Stack

- **Frontend**: Pure HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Styling**: CSS Variables, CSS Grid, Flexbox, CSS Animations
- **Storage**: LocalStorage API for persistence
- **Architecture**: Event-driven, modular component system

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

**Note**: For the best experience, use a modern Chromium-based browser.

## Performance

- Lightweight: ~500KB total size (uncompressed)
- No external dependencies
- Optimized animations using CSS transforms and GPU acceleration
- Efficient virtual DOM-like updating for file operations

## Customization

### Adding Custom Themes

Edit `js/themes.js` to add new theme definitions:

```javascript
themes.myCustomTheme = {
  name: "My Custom Theme",
  primary: "#FF6B9D",
  secondary: "#C44569",
  // ... other variables
};
```

### Creating New Applications

Add new applications in `js/applications.js`:

```javascript
class MyApp extends Application {
  constructor() {
    super("MyApp", "My Application", "icon.png");
  }
  
  render() {
    return `<div class="my-app">Content here</div>`;
  }
}
