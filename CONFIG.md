
# Wireframe Theme Configuration

## Preferences Implementation

This theme implements customizable preferences using Zen Browser's preference system. Preferences are defined in `preferences.json` and can be accessed through Zen Browser's preferences interface.

## Available Preferences

### Boolean Preferences

1. `zen.view.use-single-toolbar` - Use single toolbar layout
2. `wireframe.animations.enabled` - Enable animations in Wireframe theme
3. `wireframe.borders.squared` - Use squared borders
4. `wireframe.urlbar.position.top` - Position URL bar at the top (for multiple and collapsed toolbar only)
5. `wireframe.macos.controls` - Disable macOS style window controls
6. `zen.view.experimental-force-window-controls-left` - Force window controls to the left (for macOS style controls only)
7. `wireframe.blank.theme` - Switch to light mode for about:blank

### Dropdown Preferences

1. `wireframe.webview.border-radius` - Border radius for webview (e.g., 0px, 4px, 8px, 12px)

## How Preferences Work

  /* Styles when preference is enabled */
  
```

### Implementation Example
For the URL bar position preference, we've implemented a single boolean preference:

- When `wireframe.urlbar.position.top` is enabled, the URL bar appears at the top
- When `wireframe.urlbar.position.top` is disabled (default), the URL bar appears at the bottom

```css
/* URL bar position preference - TOP */
@media (-moz-bool-pref: "wireframe.urlbar.position.top") {
  #zen-appcontent-wrapper {
    flex-direction: column;
  }
}

/* URL bar position preference - BOTTOM (default) */
@media not (-moz-bool-pref: "wireframe.urlbar.position.top") {
  #zen-appcontent-wrapper {
    flex-direction: column-reverse;
  }
}
```

## Adding New Preferences

To add new preferences to the theme:

1. Add the preference definition to `preferences.json`
2. Implement the CSS rules in the appropriate module file
3. Update the README.md file to document the new preference
4. Test the preference to ensure it works correctly

## Preference Best Practices

1. Use descriptive names that clearly indicate what the preference does
2. Provide clear descriptions for each preference
3. Set sensible default values
4. Group related preferences logically
5. Test preferences thoroughly to ensure they work as expected