# Tap Counter

A simple web app to count taps or clicks! Just tap the button and watch the count increase.

## Features

- 📱 Tap counter that increments with each click/tap
- ⏱️ Real-time timer that runs in parallel
- 🔊 Sound effect for each tap
- 🔄 Reset button to restart everything

## Demo

Open `index.html` in your web browser to use the app locally, or visit the live version on GitHub Pages.

## How to Use

1. Open the app in your web browser
2. Click or tap the **"Tap Me!"** button
3. Watch the counter increase
4. Click **"Reset"** to start over

## Files

- `index.html` - Main web app file with HTML, CSS, and JavaScript
- `package.json` - Project metadata
- `README.md` - This file
- `.gitignore` - Git ignore rules
- `LICENSE` - MIT License
- `server.py` - Simple Python server (optional)
- `tap-data.json` - Sample tap data (demo)

## Running Locally

### Option 1: Just open the file
Double-click `index.html` in your file browser.

### Option 2: Python server
```bash
python server.py
```
Then open http://localhost:8000 in your browser.

### Option 3: Node.js (if you have it)
```bash
npx http-server
```

## Publishing to GitHub Pages

1. Create a repository on GitHub
2. Upload all files
3. Go to Settings → Pages
4. Select "main" branch and root folder
5. Your app will be live at: `https://yourusername.github.io/tap-counter`

## License

MIT License