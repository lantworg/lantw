# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static single-page website for the Lantw gaming platform (遊戲平台). The entire website is contained in a single `index.html` file with inline CSS and uses Bootstrap 5.3.0 via CDN.

## Architecture

- **Single HTML file**: All code is in `index.html`
- **No build process**: This is a static site that can be served directly
- **Dependencies via CDN**:
  - Bootstrap 5.3.0 (CSS and JavaScript)
  - Google Fonts (Noto Sans TC)
- **Assets**: Four JPG images (`showping2-5.jpg`) used in the carousel
- **Language**: All content is in Traditional Chinese

## Development Commands

Since this is a static website with no build tools:

```bash
# To view the website locally, use any static file server:
python3 -m http.server 8000
# or
npx serve .
# or simply open index.html in a browser
```

## Key Components

1. **Navigation Bar**: Fixed top navbar with links to Discord, download, and modal triggers
2. **Hero Banner**: Simple banner with "超低延遲!" (Ultra-low latency!) message
3. **Image Carousel**: Bootstrap carousel showcasing 4 game screenshots
4. **Modal Dialogs**: 
   - About Us (關於我們): Platform introduction and beta testing information
   - Store (商城): Currently free during beta period
5. **Download Links**: Direct link to `Lantw.zip` hosted on R2 CDN

## Important URLs

- Discord: https://discord.com/invite/VhQBUEFXrH
- Download: https://pub-dbff2caad05f49b0a2de7b9c6f6662fc.r2.dev/Lantw.zip