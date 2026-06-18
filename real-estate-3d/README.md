# 🏠 LuxuryHomes 3D — Real Estate Website

A premium, immersive 3D real estate website built for brand marketing and SEO dominance.

## ✨ Features

### 🎮 3D Interactive Elements
- **Three.js particle system** — Dynamic hero background with gold & white particles
- **Wireframe icosahedron** — Rotating 3D geometry in the hero
- **Orbital torus rings** — Elegant rotating rings
- **3D wireframe house** — Full architectural model in the virtual tour section
- **Mouse parallax** — Camera follows cursor movement
- **Auto-orbit camera** — Virtual tour section with smooth 360° rotation

### 🎨 Design
- Dark luxury theme with gold (#C9A96E) accents
- Glassmorphism UI elements
- Smooth scroll animations (GSAP ScrollTrigger)
- Animated stat counters
- Responsive across all devices
- Custom scrollbar
- Preloader with animated loading bar

### 🔍 SEO Optimized
- Semantic HTML5 structure
- Schema.org structured data (RealEstateAgent)
- Open Graph meta tags (Facebook, LinkedIn)
- Twitter Card meta tags
- `robots.txt` included
- `sitemap.xml` included
- Lazy-loaded images with descriptive alt text
- Schema markup on property listings
- Clean heading hierarchy (h1 → h2 → h3)
- ARIA labels for accessibility

### 📱 Sections
1. **Hero** — Immersive 3D particle scene + CTA
2. **Stats Bar** — Animated counters (properties, satisfaction, experience, tours)
3. **Featured Properties** — 3 luxury listings with 3D tour badges
4. **3D Virtual Tour** — Full-width section with orbiting 3D house model
5. **Services** — 6 service cards (scanning, search, marketing, advisory, design, relocation)
6. **Testimonials** — 3 client reviews
7. **Contact Form** — Lead generation with property interest selector
8. **Footer** — Links, branding, social icons

## 🚀 Usage

Simply open `index.html` in a browser. No build step required.

```bash
# Local server (optional)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## 📁 Files

```
real-estate-3d/
├── index.html      ← Main website (all-in-one)
├── robots.txt      ← Search engine crawl rules
├── sitemap.xml     ← Site structure for search engines
└── README.md       ← This file
```

## 🛠 Tech Stack

- **Three.js r128** — 3D graphics
- **GSAP 3.12** — Scroll animations
- **Vanilla CSS** — No frameworks, fully custom
- **Semantic HTML5** — SEO-first markup
- **Schema.org** — Structured data for rich snippets

## 📝 Customization

- **Colors**: Edit CSS variables in `:root` (gold, dark, white, gray)
- **Properties**: Update the property cards in the `#properties` section
- **3D scenes**: Modify `createHeroScene()` and `createTourScene()` functions
- **Content**: Replace placeholder text/images with real estate content
- **Domain**: Update all `https://luxuryhomes3d.com` references in meta tags & sitemap
