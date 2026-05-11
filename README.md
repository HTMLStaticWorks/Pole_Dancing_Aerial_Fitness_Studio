# Pole Dancing & Aerial Fitness Studio Website

A complete, production-ready multi-page website for **Pole Dancing Studio** — Chennai's premier aerial fitness studio.

---

## 📁 File Structure

```
pole-dancing/
├── assets/
│   ├── css/
│   │   ├── style.css        — Main styles, components, responsive layout
│   │   ├── dark-mode.css    — Dark theme overrides
│   │   └── rtl.css          — Right-to-left language support
│   ├── js/
│   │   └── main.js          — All JS: theme, RTL, nav, animations, forms
│   └── images/              — (Add your own images here)
├── pages/
│   ├── index.html           — Home Page (6 sections)
│   ├── home2.html           — Alternate Home (6 sections)
│   ├── about.html           — About Us (3 sections)
│   ├── services.html        — Services & Classes (3 sections)
│   ├── blog.html            — Blog (3 sections)
│   ├── contact.html         — Contact (3 sections)
│   ├── login.html           — Login page
│   ├── register.html        — Registration / Signup page
│   ├── 404.html             — Custom 404 error page
│   └── coming-soon.html     — Coming Soon / Maintenance page
└── README.md
```

---

## 🎨 Design System

### Color Palette
| Variable | Value | Usage |
|----------|-------|-------|
| `--primary` | `#c9184a` | CTAs, active states, highlights |
| `--primary-dark` | `#a4133c` | Hover states |
| `--primary-light` | `#ff4d6d` | Gradients |
| `--secondary` | `#1a1a2e` | Dark backgrounds, hero |
| `--accent` | `#e9c46a` | Gold accents, stats |
| `--accent-2` | `#f4a261` | Secondary accent |

### Typography
- **Display / Headings**: Playfair Display (Google Fonts)
- **Body / UI**: Raleway (Google Fonts)
- **Decorative**: Dancing Script (Google Fonts)

### Breakpoints
| Breakpoint | Width | Layout |
|------------|-------|--------|
| Mobile | ≤ 767px | Hamburger menu, stacked layout |
| Tablet | 768px | 2-column grids begin |
| Desktop | 1024px | Full nav, sidebar layouts |
| Large | 1440px | Wider containers |

---

## ✨ Features

### Navigation
- **Mobile (360–768px)**: Brand logo + name left, hamburger menu right
- **Desktop (1024px+)**: Brand left, centered nav links (Home, Home 2, About, Services, Blog, Contact), right-side RTL + Theme toggle + Login button
- Smooth animated mobile menu overlay
- Scroll-aware header (transparent → solid)

### Theme System
- 🌙 **Dark / Light mode toggle** with system preference detection
- Persists via `localStorage`
- CSS variable-based theming throughout

### RTL Support
- Full right-to-left layout toggle
- All components tested for RTL compatibility
- Persists via `localStorage`

### Animations
- Scroll-triggered fade-in animations (IntersectionObserver)
- Counter animation for statistics
- Particle system in hero sections
- CSS hover micro-interactions on all interactive elements
- Staggered animation delays for card grids

### Form Validation
- Client-side validation with clear error messages
- Fields: required, email, phone, minLength
- Password strength meter on registration
- Toast notifications on success/error
- Accessible labels and error states

### Accessibility
- Semantic HTML5 markup
- ARIA labels on interactive elements
- Focus-visible styles
- Color contrast meeting WCAG 2.1 AA
- Keyboard navigation support

---

## 🏋️ Pages Overview

### Home (index.html) — 6 Sections
1. **Hero** — Full-screen with animated particles, stats, dual CTAs
2. **Features** — 6-card grid: why choose us
3. **Classes** — Featured class cards with level indicators
4. **Gallery** — Filterable student showcase grid
5. **Party Packages** — 3 packages with featured card
6. **Testimonials** + CTA banner

### Home 2 (home2.html) — 6 Sections
1. **Split Hero** — Side-by-side content + image with floating badges
2. **Apparatus Options** — Pole, Silks, Lyra cards with hover overlays
3. **Schedule** — Day-by-day class timetable with booking
4. **Instructors** — Team cards with social hover
5. **Membership Plans** — 3-tier pricing
6. **FAQ** — Accordion + newsletter signup

### About (about.html) — 3 Sections
1. Mission & Studio Story
2. Stats (counter animation) + Core Values
3. Full Team Grid

### Services (services.html) — 3 Sections
1. Filterable class cards (all apparatus)
2. How It Works steps + Party Packages
3. Membership Signup (3 tiers)

### Blog (blog.html) — 3 Sections
1. Featured article card
2. Blog grid + sidebar (search, recent, tags)
3. Newsletter signup

### Contact (contact.html) — 3 Sections
1. Contact form + address/hours info + map placeholder
2. FAQ accordion
3. Quick contact options (WhatsApp, Call, Instagram)

### Login & Register
- Split-layout auth pages
- Social sign-in buttons
- Full client-side form validation
- Password strength meter (register)
- Benefit highlights sidebar

### 404 & Coming Soon
- Themed error page with navigation links
- Countdown timer + newsletter form

---

## 🚀 Getting Started

1. Open any `.html` file in `pages/` directly in a browser — no build step needed.
2. All assets are loaded from relative paths.
3. Images use Unsplash CDN URLs — replace with your own images.
4. Google Fonts load from CDN — requires internet connection.
5. Font Awesome icons load from CDN.

### Customising Colors
Edit `assets/css/style.css` — find the `:root {}` block at the top and change the CSS variables.

### Adding Your Own Images
Replace Unsplash URLs in HTML with your own image paths or place images in `assets/images/`.

### Connecting Google Maps
In `contact.html`, replace the `.map-container` div with:
```html
<iframe src="https://www.google.com/maps/embed?pb=..." width="100%" height="350" style="border:0;" allowfullscreen loading="lazy"></iframe>
```

---

## 📞 Default Contact Details (Replace)
- **Phone**: +91 98765 43210
- **Email**: hello@poledancing.in
- **Address**: 42 Anna Nagar 2nd Avenue, Chennai – 600 040
- **Hours**: Monday – Sunday: 7:00 AM – 9:00 PM

---

*Built with ❤️ for Pole Dancing & Aerial Fitness Studio*
