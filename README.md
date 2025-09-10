# Wireframe Theme for Zen Browser

A minimal, squared-off theme for Zen Browser that focuses on clean lines and efficient use of space.

<img width="1919" height="1079" alt="Screenshot 2025-09-09 235105" src="https://github.com/user-attachments/assets/4f83cbe9-b560-4431-b920-af76860a9bc9" />


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

## Contributing

Feel free to fork this theme and make your own modifications. Pull requests are welcome!
