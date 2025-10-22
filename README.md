# MedTools - Medical iOS App Landing Page

A professional, modern landing page for medical iOS applications built with Astro.

## Overview

This landing page showcases two medical applications designed for healthcare professionals:

1. **Drugs** - Comprehensive drug dosing information and instructions
2. **Medical Numbers** - Clinical calculators, formulas, and medical reference tools

## Features

- Modern, professional medical-themed design
- Responsive layout for all device sizes
- Clean and intuitive user interface
- Medical color scheme (blues, teals, professional tones)
- SVG icons and illustrations
- Smooth animations and transitions
- SEO optimized
- Fast performance with Astro

## Color Scheme

The landing page uses a professional medical color palette:

- Primary: `#0066cc` (Medical Blue)
- Secondary: `#00a3bf` (Teal)
- Accent: `#00c9a7` (Mint Green)
- Background: `#ffffff` (White)
- Surface: `#f8f9fa` (Light Gray)
- Text: `#1a1a1a` (Near Black)

## Technology Stack

- [Astro](https://astro.build/) - Static site generator
- TypeScript - Type safety
- CSS - Styling with CSS custom properties

## Project Structure

```
/
├── public/
│   ├── favicon.svg
│   └── images/
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Features.astro
│   │   ├── Apps.astro
│   │   ├── Download.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Getting Started

### Prerequisites

- Node.js 18 or higher
- npm or yarn

### Installation

1. Install dependencies:

```bash
npm install
```

### Development

Run the development server:

```bash
npm run dev
```

The site will be available at `http://localhost:4321`

### Build

Build the site for production:

```bash
npm run build
```

### Preview

Preview the production build:

```bash
npm run preview
```

## Sections

### Hero Section
- Eye-catching introduction
- Clear call-to-action buttons
- Trust badges (HIPAA Compliant, Evidence-Based, User count)
- Animated phone mockup

### Features Section
- Six key features highlighted
- Icon-based visual design
- Hover effects for interactivity

### Apps Section
- Detailed cards for both apps
- Feature lists for each app
- Download buttons
- Gradient app icons

### Download Section
- Prominent call-to-action
- App Store badge
- Usage statistics
- Phone mockups

### Footer
- Navigation links
- Legal information
- Medical disclaimer
- Branding

## Customization

### Colors

Edit the CSS custom properties in `src/layouts/BaseLayout.astro`:

```css
:root {
  --color-primary: #0066cc;
  --color-secondary: #00a3bf;
  --color-accent: #00c9a7;
  /* ... */
}
```

### Content

All content can be edited in the respective component files in `src/components/`.

## License

This project is created for medical application landing page purposes.

## Disclaimer

This landing page is for informational purposes only and is not a substitute for professional medical advice, diagnosis, or treatment.
