# Wireframe 2.0

A minimal, squared-off theme for Zen Browser that focuses on clean lines and efficient use of space.

<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/ed962d1b-1e78-4235-932c-2c13fb5ede67" />
<img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/32bd38ae-1bed-44b9-b14b-76fc647a5ecd" />

## Features

- Minimal design with squared-off elements
- Clean color scheme
- Efficient use of space
- Modular CSS structure for easy customization

## Installation

### Method 1: Using Sine (Recommended)
1. Install [sine](https://github.com/CosmoCreeper/Sine) if you haven't.
2. Head to the sine marketplace, search or browse through to find Wireframe 2.0.
3. Click install.
Note: To changes mods settings, head to sine mods tab in settings and click on the gear icon under wireframe 2.0 in the installed mods section below marketplace.
### Method 2:
1. Download chrome.zip from the latest release or download the files of the repo.
2. Place them in your Zen Browser profile's chrome folder
3. Restart Zen Browser

## MicaForEveryone Setup (Windows 10/11)

To achieve the clean squared-off window borders as shown in the theme screenshots, you can use MicaForEveryone:

1. Download and install MicaForEveryone from [GitHub](https://github.com/MicaForEveryone/MicaForEveryone) or Microsoft Store
2. Launch MicaForEveryone
3. Click on "Add new rule" > Add process rule > type "zen" and add rule
4. Choose corner preference "squared" from the dropdown

<img width="1148" height="794" alt="Screenshot 2025-09-10 105529" src="https://github.com/user-attachments/assets/5b80b051-30a6-4bac-91fd-a4a4c65799e7" />

## Structure

- `userChrome.css` - Main file that imports all modules
- `modules/` - Directory containing modular CSS files
- `preferences.json` - Theme preferences file

## Customization

You can customize the theme by modifying the variables in `modules/variables.css` or by overriding specific styles in the individual module files.

## Preferences

The theme includes several customizable preferences that can be adjusted through Zen Browser's preferences system:

- `wireframe.animations.enabled` - Enable animations in Wireframe theme
- `wireframe.borders.squared` - Use squared borders
- `wireframe.urlbar.position.top` - Position URL bar at the top (for multiple and collapsed toolbar only)
- `wireframe.webview.border-radius` - Border radius for webview (e.g., 0px, 4px, 8px, 12px)
- `wireframe.theme` - Change the color scheme of the browser (e.g., Catppuccin, Nord, Dracula, Gruvbox)
- `wireframe.macos.controls` - Disable macOS style window controls
- `zen.view.experimental-force-window-controls-left` - Force window controls to the left (for macOS style controls only)
- `wireframe.blank.theme` - Switch to light mode for about:blank

## Contributing

Feel free to fork this theme and make your own modifications. Pull requests are welcome!
