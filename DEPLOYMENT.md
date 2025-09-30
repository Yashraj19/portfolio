# GitHub Pages Configuration

This repository is configured for GitHub Pages deployment.

## Deployment Steps

1. **Create GitHub Repository**
   - Create a new repository on GitHub
   - Name it `yourusername.github.io` for a user site, or any name for a project site

2. **Upload Files**
   - Upload all files (`index.html`, `styles.css`, `script.js`, `README.md`, and your image)
   - Commit and push to the main branch

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Site**
   - For user sites: `https://yourusername.github.io`
   - For project sites: `https://yourusername.github.io/repository-name`

## Custom Domain (Optional)

To use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable "Enforce HTTPS" in GitHub Pages settings

## File Structure

```
/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # Documentation
└── WhatsApp Image 2025-09-12 at 12.30.13.jpeg  # Profile image
```

## Notes

- GitHub Pages supports custom 404 pages (create `404.html`)
- Jekyll is disabled by default for this static site
- HTTPS is automatically enabled for GitHub Pages
- The site will be available within a few minutes after deployment
