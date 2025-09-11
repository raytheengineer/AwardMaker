# Award Certificate Maker PWA

A Progressive Web App for creating professional award certificates with custom templates.

🔗 **Live App**: https://raytheengineer.github.io/AwardMaker/app.html

## Features

- **Three Certificate Templates**: Zweifach Award, Landis Award, Past President Award
- **Adobe Garamond Pro Fonts**: All weights embedded for consistent typography
- **High-Resolution Export**: 600 DPI PNG with transparent background
- **Vector Export**: SVG format for editing in Adobe Illustrator
- **Collapsible Instructions**: Complete workflow guidance with direct award.com product links
- **Smart Filename Generation**: Format: `[year]-[Template]-[AwardeeNameNoSpaces]`
- **Centered Preview**: Professional preview with proper text centering
- **Progressive Web App**: Works offline after first visit, no installation required
- **Mobile Friendly**: Responsive design works on all devices

## Live Application

✅ **Ready to Use**: https://raytheengineer.github.io/AwardMaker/app.html

The application is fully deployed and operational on GitHub Pages.

## Offline Usage

The app works completely offline after your first visit! Here's how to set it up:

### Initial Setup (Requires Internet)
1. **Visit**: https://raytheengineer.github.io/AwardMaker/app.html
2. **Wait for full load**: Ensure all templates and fonts are loaded
3. **Test functionality**: Create a sample certificate to verify everything works
4. **Cache confirmation**: Look for "ServiceWorker registered" in browser console (F12)

### Using Offline
Once cached, the app works without internet:

**Desktop/Laptop:**
- **Bookmark the URL** and access it normally from bookmarks
- **Add to home screen** (Chrome/Edge): Click ⋮ menu → "Install Award Certificate Maker"
- **Direct URL**: Type the URL in address bar (it loads from cache)

**Mobile (iOS/Android):**
- **Add to Home Screen**: 
  - **Safari (iOS)**: Tap Share button → "Add to Home Screen"
  - **Chrome (Android)**: Tap ⋮ menu → "Add to Home screen"
- **Access like a native app**: Tap the home screen icon to launch offline

### What Works Offline
✅ All certificate templates
✅ Text editing and preview
✅ PNG and SVG downloads
✅ All fonts and styling
✅ Complete functionality

### What Requires Internet
❌ Initial app download/updates
❌ Accessing award.com for ordering (obviously)
❌ Links to external product pages

### Troubleshooting Offline Mode
- **Not working offline?** Revisit the URL while online to refresh the cache
- **Missing templates?** Clear browser cache and reload while online
- **Old version?** The app auto-updates when you visit while online

## Local Testing

To test locally:
1. Open terminal in the v1 folder
2. Run: `python3 -m http.server 8000`
3. Open browser to: `http://localhost:8000/app.html`

## Technical Details

- **Frontend**: Pure HTML/CSS/JavaScript PWA
- **Fonts**: Adobe Garamond Pro embedded as base64 (no external files needed)
- **Templates**: Three SVG certificate templates with dynamic text replacement
- **Export**: Canvas-based PNG generation at 600 DPI
- **Offline**: Service worker enables offline functionality
- **Hosting**: GitHub Pages (no server required)

## How to Use

1. **Visit**: https://raytheengineer.github.io/AwardMaker/app.html
2. **Select Template**: Choose from Zweifach, Landis, or Past President
3. **Enter Details**: Input awardee name and year (auto-fills current year)
4. **Preview**: Real-time preview with centered text
5. **Download**: Get 600 DPI PNG or SVG file
6. **Order Award**: Follow instructions to order physical awards from award.com

## Award Ordering Integration

The app includes complete instructions for ordering physical awards:
- **FPJ0001**: Wood plaques with black/gold plate (7"×9")
- **APP0036**: Clear acrylic awards (5"×8.75")
- Direct links to award.com product pages
- Step-by-step upload and sizing guidance

## Font Information

Templates use Adobe Garamond Pro with these specifications:
- **Zweifach**: Name 30pt Bold, Year 30pt Bold Italic
- **Landis**: Name 20pt Bold, Year 20pt Regular
- **Past President**: Name 30pt Bold, Start Year 30pt Regular, End Year 25pt Regular
