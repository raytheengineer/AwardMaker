# Award Certificate Maker PWA

A Progressive Web App for creating professional award certificates with custom templates.

## Features

- Three certificate templates: Zweifach Award, Landis Award, Past President Award
- Adobe Garamond Pro font support with all weights
- High-resolution PNG export
- SVG export for editing
- Works offline after first visit
- No installation required

## Setup for GitHub Pages

1. Create a new GitHub repository
2. Upload all files from this v1 folder
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click Save
7. Your app will be available at: `https://[username].github.io/[repository-name]/app.html`

## Local Testing

To test locally:
1. Open terminal in the v1 folder
2. Run: `python3 -m http.server 8000`
3. Open browser to: `http://localhost:8000/app.html`

## Files Structure

- `app.html` - Main application
- `index.html` - Simple version (backup)
- `*.svg` - Certificate templates
- `*.otf` - Adobe Garamond Pro fonts
- `manifest.json` - PWA configuration
- `service-worker.js` - Offline functionality

## Usage

1. Open the app in a browser
2. Select a certificate template
3. Enter recipient information
4. Preview updates in real-time
5. Download as PNG or SVG

## Font Information

Templates use Adobe Garamond Pro with these specifications:
- **Zweifach**: Name 30pt Bold, Year 30pt Bold Italic
- **Landis**: Name 20pt Bold, Year 20pt Regular
- **Past President**: Name 30pt Bold, Start Year 30pt Regular, End Year 25pt Regular