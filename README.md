# Vambe Axis, Ultra Dark Theme for Cursor/VSCode

A dark theme for Cursor and Visual Studio Code, designed for developers with astigmatism and those working extended coding sessions. Built with the distinctive Vambe Axis brand palette.

## Features

**Accessibility-First Design**
- Ultra dark backgrounds reduce eye strain during long coding sessions
- High contrast text ensures readability for developers with astigmatism
- Subtle borders minimize visual noise while maintaining structure
- Carefully calibrated color saturation prevents eye fatigue

**Enhanced Syntax Highlighting**
- Vibrant, saturated colors based on the beloved Mariana theme
- Strong red highlighting for tags and errors ensures immediate visibility
- Balanced color palette optimized for code readability
- Consistent color coordination between editor and terminal

**Vambe Axis Branding**
- Signature purple accents (`#6b00ff`) for UI highlights and selections
- Ultra dark status bar (`#090027`) with subtle text for reduced distraction
- Professional color scheme reflecting Vambe Axis integration software branding
- Cohesive visual identity throughout the development environment

## Color Palette

### Syntax Colors
- **Strings**: `#9dd194` - Vibrant green for clear string identification
- **Numbers/Constants**: `#ffd666` - Golden yellow for numeric values
- **Keywords**: `#d4a5d4` - Saturated magenta for language keywords
- **Functions**: `#66c2c2` - Bright cyan for function calls and methods
- **Types**: `#77aaff` - Saturated blue for type definitions
- **Tags/Errors**: `#f14251` - Strong red for immediate error recognition
- **Comments**: `#6b7089` - Subtle gray-blue, present but unobtrusive

### UI Colors
- **Editor Background**: `#0c0d0d` - Ultra dark for maximum contrast
- **Active Tabs**: `#000000` - Pure black for clear active indication
- **Sidebar**: `#0c0d0d` - Consistent with editor background
- **Status Bar**: `#090027` - Deep purple with low-contrast text
- **Accent**: `#6b00ff` - Vambe Axis signature purple
- **Selection**: `#424547` - Neutral gray for text selection

## Installation

### Method 1: Via Extension (Recommended)
1. Open VS Code or Cursor
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "Axis Ultra Dark"
4. Click Install
5. Go to File > Preferences > Color Theme
6. Select "Axis Ultra Dark"

### Method 2: Manual Installation
1. Download the theme file from this repository
2. Copy to your VS Code extensions folder:
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`
   - **macOS**: `~/.vscode/extensions/`
   - **Linux**: `~/.vscode/extensions/`
3. Restart VS Code
4. Select the theme from File > Preferences > Color Theme

### Method 3: Quick Configuration
Add this to your VS Code `settings.json`:
```json
{
  "workbench.colorTheme": "Axis Ultra Dark"
}
```

## Design Philosophy

This theme addresses specific challenges faced by developers:

**For Astigmatism**: High contrast between text and background reduces strain caused by light bleeding. Dark backgrounds with bright text minimize the haloing effect common in astigmatic vision.

**For Extended Sessions**: The ultra-dark background significantly reduces blue light emission and overall screen brightness, helping prevent eye fatigue during long coding marathons.

**For Professional Use**: Clean, minimal aesthetic eliminates visual distractions while maintaining all necessary UI functionality. The color choices reflect the professional standards of enterprise development environments.

## Technical Specifications

- **Theme Type**: Dark
- **Recommended Font**: [Hack](https://sourcefoundry.org/hack/) at 13pt for optimal readability
- **Semantic Highlighting**: Enabled
- **Compatibility**: VS Code 1.74.0+, Cursor
- **Base Inspiration**: Mariana theme syntax colors
- **Accessibility**: WCAG contrast compliant
- **Color Space**: sRGB optimized

## About Vambe Axis

This theme incorporates the visual identity of Vambe Axis, our enterprise integration software platform. The signature purple accent color and professional dark palette reflect our commitment to developer experience and visual excellence.

## Contributing

Issues and pull requests are welcome. When contributing:

1. Maintain accessibility standards
2. Test with various file types (JS, TS, Python, etc.)
3. Ensure consistency with the established color palette
4. Consider the needs of developers with visual sensitivities

## Credits

- **UI Design**: Ignacio Uteras Urrutia
- **Syntax Colors**: Based on Mariana theme by Dmitri Voronianski (Sublime HQ Pty Ltd)
- **Publisher**: Vambe AI, Inc.

## License

MIT License - see LICENSE file for details.

---

**Developed for developers, by a coder product designer.**  
Part of the Vambe ecosystem.