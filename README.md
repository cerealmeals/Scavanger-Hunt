# Party Scavenger Hunt Website 🎉

A simple, static website for hosting a party scavenger hunt game. Each player uses their own device to answer questions, with answers saved locally using browser storage.

## Features

- ✨ **No backend required** - Pure HTML, CSS, and JavaScript
- 💾 **Auto-save** - Answers are automatically saved as you type
- 📱 **Mobile-friendly** - Works great on phones and tablets
- 🎨 **Clean design** - Simple, colorful, and party-ready
- 📊 **Progress tracking** - Visual progress bar shows completion
- 🔒 **Privacy-first** - All data stays on the user's device

## How It Works

Each user's answers are stored in their browser's `localStorage`:
- Answers persist between page refreshes
- Each user has their own separate answers on their device
- No data is sent to any server
- Clearing browser data will erase stored answers

## Customizing Questions

To change the scavenger hunt questions:

1. Open `index.html` in a text editor
2. Find the `questions` array (around line 180)
3. Modify, add, or remove questions as needed:

```javascript
const questions = [
    "What is the host's favorite color?",
    "Find something that starts with the letter 'Z'",
    // Add more questions here...
];
```

4. Save the file

## Deploying to GitHub Pages

### Option 1: Quick Deploy

1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to repository Settings → Pages
4. Under "Source", select "main" branch
5. Click Save
6. Your site will be live at: `https://[username].github.io/[repository-name]/`

### Option 2: Using Git

```bash
# Initialize git repository
git init

# Add your files
git add index.html README.md

# Commit
git commit -m "Initial commit: Party Scavenger Hunt"

# Add your GitHub repository as remote
git remote add origin https://github.com/[username]/[repository-name].git

# Push to GitHub
git push -u origin main

# Enable GitHub Pages in repository settings
```

## Local Testing

Simply open `index.html` in any web browser:
- Double-click the file, or
- Right-click → Open with → Your browser

No server needed!

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## Privacy Note

This website stores data only in the user's browser. No information is collected, transmitted, or stored on any server. Each participant's answers are completely private and only visible on their own device.

## License

Feel free to use and modify for your party!

## Questions?

Customize the questions, colors, or text to match your party theme. Have fun! 🎊
