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
