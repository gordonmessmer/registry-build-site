# registry-build Website

This directory contains the static website for the registry-build project.

## Overview

The website provides an overview of the registry-build tools ecosystem:
- **dist-git-manager** - Automated dist-git repository maintenance
- **source-git-manager** - Source-git repository mirroring
- **rpm-build-assist** - RPM package building

## Viewing Locally

Open `index.html` in your web browser:

```bash
# Using xdg-open (Linux)
xdg-open index.html

# Or manually open the file in your browser
```

## Deployment

This is a static website (single HTML file) that can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service
- Or served with a simple HTTP server

### Example: Simple HTTP Server

```bash
# Python 3
python3 -m http.server 8000

# Then visit http://localhost:8000
```

## Development

The website is self-contained in `index.html` with inline CSS and JavaScript.
No build process or dependencies required.
