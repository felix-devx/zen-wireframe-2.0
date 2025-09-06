# Wireframe Theme for Zen Browser

A minimal, squared-off theme for Zen Browser that focuses on clean lines and efficient use of space.

## Features

- Minimal design with squared-off elements
- Clean color scheme
- Efficient use of space
- Modular CSS structure for easy customization

## Installation

1. Download the theme files
2. Place them in your Zen Browser profile's chrome folder
3. Restart Zen Browser

## Structure

- `userChrome.css` - Main file that imports all modules
- `modules/` - Directory containing modular CSS files
- `zen-themes/preferences.json` - Theme preferences file

## Customization

You can customize the theme by modifying the variables in `modules/variables.css` or by overriding specific styles in the individual module files.

## Preferences

The theme includes several customizable preferences that can be adjusted through Zen Browser's preferences system:

- `zen.view.use-single-toolbar` - Use single toolbar layout
- `wireframe.animations.enabled` - Enable animations in Wireframe theme
- `wireframe.borders.squared` - Use squared borders
- `wireframe.urlbar.position.top` - Position URL bar at the top (for multiple and collapsed toolbar only)
- `wireframe.webview.border-radius` - Border radius for webview (e.g., 0px, 4px, 8px, 12px)
- `wireframe.colorscheme` - Color scheme for the theme

## Using the Theme

The Wireframe theme automatically adapts to your system's preferred color scheme:

- When your system is set to light mode, the theme will use the light color scheme
- When your system is set to dark mode, the theme will use the dark color scheme

To switch between light and dark themes, change your system's preferred color scheme:

### Windows:
1. Open Settings
2. Go to Personalization > Colors
3. Under "Choose your color", select "Light" or "Dark"

### macOS:
1. Open System Preferences
2. Go to General
3. Under "Appearance", select "Light" or "Dark"

### Linux:
The method varies by distribution and desktop environment, but generally:
1. Open System Settings
2. Look for Appearance or Theme settings
3. Select light or dark theme

After changing your system's preferred color scheme, restart Zen Browser for the changes to take effect.

## Contributing

Feel free to fork this theme and make your own modifications. Pull requests are welcome!