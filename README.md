# ox_target

[Discord_4SxRlem3BR](https://github.com/user-attachments/assets/305bbfbc-6479-4352-9091-4516bba4a12b)

## 🎨 UI Customization

You can easily customize the colors and appearance of the target UI without editing CSS files.

### How to change colors:
1. Open [web/js/config.js]!
.
2. Update the values in the `window.TargetConfig` object:

```javascript
window.TargetConfig = {
    // UI Primary Color (Hex)
    primaryColor: '#C8A96A',
    
    // UI Primary RGB (Must match primaryColor)
    primaryRGB: '200, 169, 106',
    
    // Global Glow Intensity (0.0 to 1.0)
    glowOpacity: 0.6,
    
    // Background Transparency/Color
    backgroundColor: 'rgba(10, 10, 10, 0.88)',
};
```

3. Save the file and restart the resource or refresh the UI in-game.

