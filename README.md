<!-- Language Switch -->
<p align="right">
  <a href="README.vi.md">Tiếng Việt</a>
</p>

<a id="en"></a>

# Hugnw — Personal Profile Page

![Preview](media/poster.jpg)

A minimal, animated personal landing page with background video, theme/effects switcher, music player, quick settings, and a modal photo gallery.

- URL entry point: `index.html`
- Main files: `index.html`, `profile.css`, `profile.js`, `media/`

<!-- Badges -->
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## Features
- Background video with overlay and noise effects
- Interactive avatar and animated name effects (fire/neon/electric)
- Theme presets: Auto, Dark, Neon, Pastel, Cyberpunk, Retro
- Background visual effects: Snow, Rain, Leaves, Fireworks, Shooting Stars, Bubbles, Combo, Off
- Cursor effects toggle and modes
- Audio player with small UI and playlist support
- Quick settings panel and share helpers (copy Discord link, QR)
- Modal photo gallery with lightbox
- Keyboard shortcuts for quick control

## Keyboard Shortcuts
- T: Change theme
- E: Change background effect
- N: Change name effect
- C: Toggle cursor effect
- M: Play/Pause music
- G: Open gallery
- Esc: Close lightbox/gallery

## Getting Started
1. Clone or download this repository.
2. Open `index.html` directly in a modern browser.
   - For full media autoplay support, ensure the browser allows muted autoplay.
3. Put your media under `media/` if you customize.

## Customize
- Texts, links, and labels: edit `index.html`
- Styles, themes, animations: edit `profile.css`
- Behaviors, effects, playlist, gallery logic: edit `profile.js`
- Assets: `media/` (video bg, images, audio, gallery)

## Live Demo
- GitHub Pages: enable Pages in repo settings (branch: `main`, folder: `/root`), then share the generated URL.

## Folder Structure
```
.
├─ index.html
├─ profile.css
├─ profile.js
├─ media/
│  ├─ avatar.jpg
│  ├─ bg.mp4
│  ├─ bgm.mp3
│  ├─ bia.gif
│  ├─ deco.png
│  ├─ poster.jpg
│  └─ gallery/
└─ LICENSE
```

## Deployment
- GitHub Pages: Settings → Pages → Branch `main` → Root. Wait 1–2 minutes.
- Netlify/Vercel: create a new site from this repo. Build command: none. Publish directory: root.

## Notes
- Repo language defaults to Vietnamese content in `index.html` (`<html lang="vi">`).
- Open Graph preview image is `media/poster.jpg`. Update if needed.
- Background video sources: `media/bg.webm` and `media/bg.mp4`.

## License
This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
