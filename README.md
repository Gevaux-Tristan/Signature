# Signature Photo App

A modern photo editing web application with LUT support, focus blur effects, and WebGL-powered image processing.

## Features

- **LUT Support**: Apply professional color grading with 3D LUT files
- **Focus Blur**: Interactive Gaussian blur effect mimicking camera focus issues
- **Real-time Processing**: WebGL-powered image effects with instant preview
- **Mobile Optimized**: Touch and pointer event support
- **Export**: High-quality image export with automatic compression

## Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Signature.git
   cd Signature
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   # or
   python3 -m http.server 8000
   ```

4. **Open in browser**
   Navigate to `http://localhost:8000`

## Deployment

### GitHub Pages (Recommended)

1. **Enable GitHub Pages** in your repository settings
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` or `master`
   - Folder: `/ (root)`

2. **Push to main branch**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

3. **Automatic deployment**
   - GitHub Actions will automatically build and deploy
   - Check the Actions tab for deployment status

### Manual Deployment

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Upload to your hosting provider**
   - Upload the contents of the `dist/` folder
   - Ensure all files are in the root directory

## Project Structure

```
Signature/
├── .github/workflows/    # GitHub Actions
├── luts/                 # LUT files
├── index.html           # Main application
├── package.json         # Dependencies and scripts
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers with WebGL support

## License

MIT License - see LICENSE file for details
