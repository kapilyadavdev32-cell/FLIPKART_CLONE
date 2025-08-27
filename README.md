# Flipkart Clone

A responsive e-commerce website clone of Flipkart built with HTML, CSS, and JavaScript.

## Features

- Responsive design that works on desktop and mobile devices
- Interactive product carousel/slider
- Category navigation with product images
- Product sections (Deals of the Day, Fashion, Home Essentials)
- Shopping cart functionality with item counter
- Search functionality
- Login modal
- Smooth animations and hover effects

## Project Structure

```
FLIPKART_CLONE/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── netlify.toml        # Netlify configuration
├── README.md           # Project documentation
└── src/                # Image assets (21 product images)
```

## Deployment Instructions for Netlify

### Option 1: Deploy via GitHub (Recommended)

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Flipkart clone ready for deployment"
   git push origin main
   ```

2. **Deploy on Netlify:**
   - Go to [Netlify](https://app.netlify.com)
   - Click "Add new site" → "Import an existing project"
   - Connect your GitHub account
   - Select your repository
   - Click "Deploy site"

### Option 2: Direct Upload (Drag & Drop)

1. **Prepare files:**
   - Make sure all files are in the FLIPKART_CLONE folder
   - Verify index.html, styles.css, script.js, and src folder are present

2. **Deploy:**
   - Go to [Netlify Drop](https://app.netlify.com/drop)
   - Drag and drop your entire FLIPKART_CLONE folder
   - Wait for deployment to complete

### Option 3: Netlify CLI

1. **Install Netlify CLI:**
   ```bash
   npm install -g netlify-cli
   ```

2. **Deploy:**
   ```bash
   netlify deploy
   netlify deploy --prod
   ```

## Local Development

To run locally:

1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```

## Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with flexbox and grid
- **JavaScript** - Interactivity
- **Responsive Design** - Mobile-first approach

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is for educational purposes only.