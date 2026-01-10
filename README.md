# Quote Generator

A sleek, minimal webpage that displays random inspiring quotes with a single click. Fully responsive and works beautifully on both mobile and desktop browsers.

## Features

- 🎯 One-click random quote generation
- 📱 Fully responsive design (mobile-friendly)
- 🎨 Modern gradient UI with smooth animations
- 💫 No external dependencies (vanilla HTML/CSS/JavaScript)
- ⚡ Lightweight and fast-loading
- 🎭 Prevents showing the same quote consecutively

## Usage

### Local Testing

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quote-generator.git
   cd quote-generator
   ```

2. Open `index.html` in your browser:
   - Double-click `index.html`, or
   - Right-click → Open with → Your preferred browser

3. Click the "New Quote" button to get inspired!

### Deployment (Free Options)

#### GitHub Pages (Recommended)
1. Push your code to a GitHub repository
2. Go to **Settings** → **Pages**
3. Set source to `main` branch, root folder
4. Your site will be live at `https://yourusername.github.io/quote-generator`

#### Netlify
1. Drag and drop the project folder at [netlify.com/drop](https://app.netlify.com/drop)
2. Your site is live instantly with a free URL

#### Vercel
1. Push to GitHub
2. Import at [vercel.com](https://vercel.com)
3. Deploy with one click

## Customization

Edit the `quotes` array in `index.html` to add your own quotes:

```javascript
const quotes = [
    { text: "Your quote here", author: "Author Name" },
    // Add more quotes...
];
```

## File Structure

```
quote-generator/
├── index.html       # Main file (HTML + CSS + JavaScript)
├── README.md        # This file
└── .gitignore       # Git configuration
```

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

MIT - Feel free to use and modify!
