# Kilter Board Data Explorer

A web application to view and browse your climbing history from the old Kilter Board app.

## 🧗 What is this?

When the original Kilter Board app was taken down, users lost easy access to their climbing history. This tool allows you to upload your exported data and browse through all your climbed boulders and circuits.

## 🚀 How to use

1. Open the web app in your browser
2. Upload your `export-[username].json` file (from the old Kilter Board app)
3. Browse your climbs and circuits

## ✨ Features

### My Climbs Tab
- View all your climbed boulders
- Search by boulder name
- Filter by grade, angle, and star rating
- Sort by date, name, grade, or stars
- See details: grade, angle, attempts, stars, and date climbed

### Circuits Tab
- View all your saved circuits/playlists
- See all boulders in each circuit
- Color-coded circuit indicators
- Private circuit markers

### Data Management
- Your data is automatically saved in your browser's localStorage
- No need to re-upload the file each time
- Click the trash icon (🗑️) to clear stored data and upload a new file

## 🔒 Privacy & Security

**Your data stays private:**
- All data processing happens in your browser (client-side only)
- Your climbing data is stored only in your browser's localStorage
- No data is ever sent to any server or external service
- No analytics, tracking, or third-party scripts

**Perfect for:**
- Checking if you've already climbed a boulder when using the new app
- Browsing your climbing history offline
- Keeping a backup of your old climbing data

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript - no dependencies
- Works completely offline after initial load
- Responsive design for mobile and desktop
- Uses browser localStorage for data persistence

## 📋 Requirements

Any modern web browser (Chrome, Firefox, Safari, Edge)

## 🤝 Contributing

Feel free to open issues or submit pull requests if you'd like to improve the app!

## 📄 License

MIT License

Copyright (c) 2026 Björn Vopel

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
