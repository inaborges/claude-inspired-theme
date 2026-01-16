# Claude Inspired Theme

A warm, professional VSCode theme inspired by Claude's design aesthetic. Features Claude's signature orange accent colors with carefully chosen complementary colors for syntax highlighting.

## Screenshots

### Light Theme
Warm, inviting colors with excellent contrast for long coding sessions.

### Dark Theme
A comfortable dark theme with the same warm palette, perfect for low-light environments.

## Features

- **Two variants**: Light and Dark themes
- **Warm color palette**: Inspired by Claude's signature orange (#D97757)
- **Carefully selected syntax colors**: Optimized for readability
- **Complete UI theming**: Consistent colors across all VSCode UI elements
- **Git decorations**: Clear visual indicators for file changes

## Installation

### Method 1: Install from VSIX (Local)

1. Open VSCode
2. Press `Cmd+Shift+P` (Mac) or `Ctrl+Shift+P` (Windows/Linux)
3. Type "Extensions: Install from VSIX"
4. Navigate to the `.vsix` file and select it

### Method 2: Install from Source

1. Copy the `claude-theme` folder to your VSCode extensions directory:
   - **Mac/Linux**: `~/.vscode/extensions/`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`

2. Restart VSCode

3. Activate the theme:
   - Press `Cmd+K Cmd+T` (Mac) or `Ctrl+K Ctrl+T` (Windows/Linux)
   - Select "Claude Inspired Light" or "Claude Inspired Dark"

### Method 3: Development Mode

1. Open the `claude-theme` folder in VSCode
2. Press `F5` to open a new VSCode window with the theme loaded
3. Test and preview the theme

## Color Palette

### Key Colors

- **Primary Orange**: `#D97757` - The signature Claude color
- **Accent Orange**: `#E88567` - Lighter variant for hover states
- **Green (Strings)**: `#52A66E` - Calm, readable green
- **Blue (Functions)**: `#5B9BD5` - Professional blue
- **Yellow (Classes)**: `#D9A357` - Warm golden yellow
- **Purple (Constants)**: `#B87BA8` - Soft purple for numbers and constants

### Theme Philosophy

This theme aims to capture Claude's warm, approachable, and professional aesthetic:
- Warm neutrals instead of stark blacks and whites
- Orange as the primary accent color (keywords, status bar, active elements)
- Balanced contrast for comfortable extended use
- Thoughtful color choices that reduce eye strain

## Customization

To customize colors, edit the theme files:
- Light theme: `themes/claude-light.json`
- Dark theme: `themes/claude-dark.json`

After making changes, reload VSCode to see updates.

## Building the Extension

To package this theme as a `.vsix` file:

1. Install vsce (Visual Studio Code Extensions tool):
   ```bash
   npm install -g @vscode/vsce
   ```

2. Package the extension:
   ```bash
   cd claude-theme
   vsce package
   ```

3. This creates a `.vsix` file you can share or install

## Contributing

Feel free to submit issues or pull requests to improve the theme!

## License

MIT License - Feel free to use and modify as you wish.

---

**Enjoy coding with Claude's warm aesthetic!** 🟠
