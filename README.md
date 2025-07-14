
## GitHub Repository Setup

1. **Create a repository** named `msx` under your GitHub account
2. **Create these files** in your repository:

### Root Directory:
- `start.json` (the main entry point)

### data/ Directory:
- `data/menu.json` (main menu with 3 buttons)
- `data/edit_url.json` (URL editing interface)
- `data/display_plus.json` (display website + option)
- `data/display_plusplus.json` (display website ++ option)

## Features of This MSX App:

### Main Menu (3 buttons as requested):
1. **Edit URL** - Opens URL editing interface with QWERTY keyboard
2. **Display Website +** - Opens saved URL with + suffix
3. **Display Website ++** - Opens saved URL with ++ suffix

### URL Edit Interface:
- QWERTY keyboard input for TV remote navigation
- Save/Clear buttons
- Real-time URL preview showing `https://charidy.com/{input}`
- Test buttons to try both + and ++ versions

### Storage System:
- Saves URLs using MSX's built-in storage system
- Persists between sessions

## Setup Instructions:

1. **Enable GitHub Pages** in your repository settings
2. **Test the URL**: `https://inteleweb.github.io/msx/start.json`
3. **In MSX app**: Set start parameter to `yourusername.github.io`
4. **Browser test**: `https://msx.benzac.de?start=menu:https://inteleweb.github.io/msx/data/menu.json`

The interface is optimized for TV remote control with large buttons and clear navigation paths. Users can easily input URLs, save them, and launch either the + or ++ versions in fullscreen mode.
