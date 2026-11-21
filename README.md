# Mililuxe Nails SPA website

A complete **static**, mobile-responsive, ready-to-upload website. No Python, database, or paid build tools are needed for this version.

## Preview locally

1. Extract this ZIP.
2. Double-click `index.html` to open the site in your browser.
3. Or in VS Code open this folder and use Live Server.

## Put your website online

1. Register your domain (e.g. mililuxe.com) and purchase web hosting (or use a static hosting service).
2. Upload `index.html`, `styles.css`, `script.js`, `favicon.svg`, and the whole `assets` folder to your hosting document root, usually `public_html` on cPanel.
3. Point your domain DNS to your host following the host's instructions, enable SSL/HTTPS, and check the site on mobile and desktop.

## Content and editing

- Service prices are in `index.html` and repeated in editable `data.json` for future integration. `data.json` does not automatically update the website: edit the HTML to change what's displayed.
- Original photos were optimized to WebP in `assets/` for smaller page size.
- Contact: 0790 220 434, mililuxe992@gmail.com.
- Address: Mukuyu, opposite Soko ya Mbuzi. Directions link opens a Google Maps **search**, not a verified pinned business listing.
- WhatsApp links open a customer-initiated conversation; there is **no booking form yet**.
- The animated photo slideshow in the Showcase section is **not a video**: you supplied photos, not video files. To add real videos later, upload licensed MP4/WebM files and embed them in this section; avoid autoplay with sound.
- Images are from your uploaded materials. Use them only if you have the rights to publish them.
- Google Fonts requires internet; fallback fonts are provided.

## Future booking

This version is deliberately frontend-only. Appointment booking, logins, database, payments, and the AI agent can be developed in a later phase without changing the core visual design.
