# Website for BI Automation Interface

This folder contains the promotional website for the BI Automation Interface app.

## License and Usage

All rights reserved. The website source is published for hosting only and is not permitted for reuse or redistribution without explicit permission.

## Folder Structure

```
website/
├── README.md                 # This file
├── package.json              # Dependencies (if using Node.js)
├── next.config.js            # Next.js config (if using Next.js)
├── public/                   # Static assets
│   ├── images/              # Screenshots, icons, logos
│   ├── favicon.ico          # Website favicon
│   └── app-icon.png         # App icon for website
├── src/                      # Source files (if using framework)
│   ├── pages/               # Pages (Next.js) or components
│   ├── components/          # Reusable components
│   ├── styles/              # CSS/styling
│   └── content/             # Markdown content, data
├── docs/                     # Alternative: if using GitHub Pages
└── .gitignore               # Git ignore for website files
```

## Recommended Approach

### Option 1: Next.js (Recommended)
- Modern, fast, SEO-friendly
- Easy deployment to Vercel
- Good for dynamic content

### Option 2: Static HTML/CSS/JS
- Simple, no build step
- Easy to understand
- Can deploy anywhere

### Option 3: GitHub Pages (Jekyll)
- Free hosting
- Good for documentation sites
- Easy to set up

## Getting Started

1. Choose your platform (Next.js recommended)
2. Create the folder structure above
3. Start with `index.html` or `pages/index.js`
4. Build pages incrementally

## Deployment

- **Vercel**: Best for Next.js (free tier)
- **Netlify**: Good for static sites (free tier)
- **GitHub Pages**: Free, good for static sites
- **Custom domain**: Point to your hosting provider
