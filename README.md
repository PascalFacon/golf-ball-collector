# Golf Ball Collector ⛳

A Progressive Web App for cataloging golf balls collected from courses around the world.

## Features

- 📷 Take photos or upload from camera roll
- 💾 Store collection data locally on your device
- 🔍 Search by course name or location
- 📊 Track statistics (total balls, unique courses)
- 📱 Add to iPhone home screen for app-like experience
- 🔒 All data stays on your device (private)

## Quick Start

### Option 1: Use Locally
1. Open `golf-ball-collector.html` in your browser
2. Start adding golf balls to your collection

### Option 2: Deploy to GitHub Pages (Recommended)

1. **Create a GitHub repository**
   - Go to https://github.com/new
   - Name it something like `golf-ball-collector`
   - Make it public
   - Don't initialize with README (we have one)

2. **Upload your files**
   ```bash
   git clone https://github.com/YOUR-USERNAME/golf-ball-collector.git
   cd golf-ball-collector
   
   # Copy these files into the directory:
   # - golf-ball-collector.html
   # - README.md
   # - manifest.json
   # - icon-192.png
   # - icon-512.png
   
   git add .
   git commit -m "Initial commit: Golf Ball Collector app"
   git push origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll to "Pages" section
   - Source: Deploy from branch
   - Branch: `main` / `(root)`
   - Click Save

4. **Access your app**
   - URL will be: `https://YOUR-USERNAME.github.io/golf-ball-collector/golf-ball-collector.html`
   - Wait 1-2 minutes for deployment

## Add to iPhone Home Screen

1. Open the app URL in Safari
2. Tap the Share button (box with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Name it "Golf Balls" or whatever you prefer
5. Tap "Add"

Now it works like a native app!

## Usage

### Adding a Golf Ball
1. Tap the green **+** button
2. Choose to take a photo or select from camera roll
3. Enter course details:
   - **Course Name** (required)
   - Location (optional)
   - Date played (optional)
   - Notes (optional)
4. Tap "Save Golf Ball"

### Searching
- Use the search bar to filter by course name or location

### Data Storage
- All data is stored in your browser's localStorage
- Photos are compressed automatically to save space
- Data persists until you clear browser data
- Each device stores its own collection

## Technical Details

- **Size**: Single HTML file (~15KB)
- **Dependencies**: None (pure vanilla JavaScript)
- **Storage**: LocalStorage (typically 5-10MB limit)
- **Image compression**: 800px width, 70% JPEG quality
- **Browser support**: Modern browsers (Chrome, Safari, Firefox, Edge)

## Future Enhancements

Possible features to add:
- Google Places API integration for course autocomplete
- Export collection to CSV
- Import/export for backup
- Cloud sync across devices
- Filter by country/region
- Edit/delete existing entries
- Share collection with friends

## Troubleshooting

**Camera not working?**
- Use "Choose from Camera Roll" instead
- Make sure you're using Safari (not Claude app browser)
- Check camera permissions in browser settings

**Storage full error?**
- Photos are automatically compressed
- Consider deleting old entries
- Each device has ~5-10MB limit for localStorage

**Data disappeared?**
- Check if browser data was cleared
- Each browser/device stores separately
- Consider implementing backup/export feature

## License

Free to use and modify for personal use.

## Contributing

This is a personal project, but suggestions are welcome! Open an issue or submit a pull request.
