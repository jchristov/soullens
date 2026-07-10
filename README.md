# Soul Lens — Event Photography & Organization

A bilingual (EN/DE) marketing website and business plan for a Vienna-based event photography and organization service.

## Project Structure

```
soul-lens/
├── index.html              # Main website page
├── styles.css              # Website styles
├── js/
│   ├── i18n.js             # Bilingual translations (EN/DE)
│   └── script.js           # Website interactivity
├── img/
│   ├── hero.jpg            # Hero background
│   ├── hofburg.jpg         # Hofburg Palace venue
│   ├── schonbrunn.jpg      # Schönbrunn Orangerie venue
│   ├── mq.jpg              # MuseumsQuartier venue
│   ├── prater.jpg          # Prater venues
│   ├── stadtpark.jpg       # Stadtpark venue
│   ├── augarten.jpg        # Augarten venue
│   ├── donaupark.jpg       # Donaupark venue
│   ├── donauauen.jpg       # Donau-Auen venue
│   ├── cafe.jpg            # Historic Cafés venue
│   ├── service-*.jpg       # Service section images
│   ├── portfolio-*.jpg     # Portfolio showcase images
│   ├── about-bg.jpg        # About section background
│   └── contact-bg.jpg      # Contact section background
├── BUSINESS_PLAN.md        # Comprehensive business plan
└── README.md               # This file
```

## Features

- **Bilingual**: Full EN/DE language support with toggle
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Modern UI**: Dark luxury aesthetic with gold accents, cinematic animations
- **Local Images**: All images cached locally for fast loading
- **Contact Form**: Inquiry form for potential clients
- **Service Showcase**: Photography packages and event planning services
- **Venue Directory**: Vienna venue recommendations with real images

## Sections

1. **Hero**: Compelling headline with parallax background
2. **Stats**: Animated counter numbers
3. **Services**: Photography and event planning packages
4. **Extra Services**: Drone, video, prints, and more
5. **Portfolio**: Event photography showcase
6. **Venues**: 9 Vienna venues with real images (Premium/Mid-Range/Budget)
7. **About**: Company story and values
8. **Testimonials**: Client reviews
9. **Contact**: Inquiry form with glass-morphism design

## Vienna Venues

- **Premium**: Hofburg Palace, Schönbrunn Orangerie, Belvedere Palace, Palais Auersperg, Palais Schwarzenberg
- **Mid-Range**: MuseumsQuartier, Prater
- **Budget**: Stadtpark, Augarten, Donaupark, Donau-Auen, Historic Cafés

## Deployment

This site is automatically deployed to GitHub Pages on every push to `main`.

### Setup

1. Go to repository **Settings → Pages**
2. Under **Build and deployment**, select **GitHub Actions**
3. Push to `main` branch to trigger deployment

The workflow (`.github/workflows/deploy.yml`) handles:
- Checking out the code
- Uploading static files
- Deploying to GitHub Pages

### Manual Deployment

Push any change to `main`:
```bash
git push origin main
```

## Getting Started

### Local Development

1. Open `index.html` in a browser
2. Or use a local server:
   ```bash
   # Python
   python -m http.server 8000
   
   # Node.js
   npx serve .
   ```

### Customization

- Replace images in `img/` folder with your own photos
- Update translations in `js/i18n.js`
- Modify pricing in `BUSINESS_PLAN.md`
- Update contact information in the footer

## Business Plan

See `BUSINESS_PLAN.md` for:
- Market analysis and competitive landscape
- Service offerings and pricing (including drone, video, print extras)
- Financial projections
- Marketing strategy
- Legal and administrative requirements
- 90-day launch plan

## Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript**: Vanilla JS with i18n support
- **Images**: Local caching for offline/fast loading

## License

© 2025 Soul Lens. All rights reserved.
