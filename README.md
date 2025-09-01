# Document Camera

A fullscreen webcam viewer designed for document cameras and presentations.

## Features

- **Fullscreen webcam display** - Clean, overlay-free video feed
- **Multiple camera support** - Cycle through connected cameras
- **Flexible display modes** - Toggle between cover (fill screen) and contain (show full frame)
- **180° rotation** - Flip image for inverted document cameras
- **Keyboard shortcuts** - Quick access to all features
- **Responsive design** - Works on desktop and mobile devices

## Keyboard Shortcuts

- **Space** - Toggle fill mode (cover/contain)
- **C** - Cycle through available cameras
- **F** - Toggle fullscreen
- **R** - Rotate video 180 degrees
- **i** (info icon) - Show/hide shortcuts panel

## Usage

1. Open the application in a modern web browser
2. Allow camera access when prompted
3. The video feed will automatically start in fullscreen mode
4. Use keyboard shortcuts or the info icon for controls

## Browser Compatibility

- Chrome 53+
- Firefox 36+
- Safari 11+
- Edge 12+

Requires HTTPS in production for camera access.

## GitHub Pages Deployment

This project is ready for GitHub Pages deployment:

1. Push to a GitHub repository
2. Go to Settings → Pages
3. Select source branch (usually `main`)
4. Access at `https://yourusername.github.io/repository-name`

## Local Development

Simply open `index.html` in a web browser. For local HTTPS (required for camera access), you can use:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve .
```

## Google Sites Integration

For embedding in Google Sites:

1. Deploy to GitHub Pages (or any HTTPS hosting)
2. In Google Sites: Insert → Embed → "By URL"
3. Paste the GitHub Pages URL
4. Users click the page to activate fullscreen camera view

## Security Note

This application requires camera permissions and works best when served over HTTPS. For security reasons, some browsers may restrict camera access in embedded contexts.
