# Muslim Ambassadors Uganda (MAU)

A single-page scrolling website for Muslim Ambassadors Uganda — a community-centered youth empowerment and orphan care organization operating across 116 districts in Uganda.

## Pages

### `index.html` (main page)

- **Hero** — Full-width banner with headline and call-to-action
- **Our Story** — Organization background with impact stats and photo strip
- **Mission, Vision & Core Values** — Three-card layout
- **Orphanages** — Text and image layout with donation highlight
- **Skilling Centres** — District list with graduation milestone
- **Our Impact** — Stats grid with narrative and photo gallery
- **Testimonials** — Quotes from beneficiaries with portrait photo
- **Support Our Mission** — Ways to contribute, grouped by category
- **Make a Difference Today** — Tap-to-copy donation cards

### `gallery.html`

Separate gallery page linked from the navbar. Displays all 22 images in a responsive grid and all 5 videos with playback controls.

## Tech

- Plain HTML + CSS (no frameworks)
- Google Fonts: Lora (headings), Inter (body)
- Mobile-first responsive design
- Pure CSS hamburger menu
- Tap-to-copy phone numbers via Clipboard API

## Usage

Open `index.html` in any browser. No build step or server required.

## Project Structure

```
├── assets/          # Images and videos
├── index.html       # Main page
├── gallery.html     # Photo & video gallery
├── style.css        # All styles
└── README.md
```
