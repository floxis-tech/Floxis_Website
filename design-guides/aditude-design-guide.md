# Aditude Design Guide

## Overview
Aditude (aditude.com) is an ad ops technology platform with an ultra-clean, minimalist dark design that emphasizes clarity and sophistication through restraint.

---

## Color Palette

### Primary Colors
- **Background Dark**: `#000000` (Pure black)
- **Background Light**: `#FFFFFF` (Pure white for contrast sections)
- **Accent**: `#7CFF00` / `#A3FF00` (Electric lime/neon green)

### Secondary Colors
- **Text Primary**: `#FFFFFF` (On dark) / `#000000` (On light)
- **Text Secondary**: `#888888` (Muted gray)
- **Border**: `rgba(255,255,255,0.1)` (Subtle dividers)

---

## Typography

### Font Family
- **Headlines**: Serif or elegant sans-serif (appears to use a refined serif for headlines)
- **Body**: Clean sans-serif (Inter, Helvetica Neue)

### Font Characteristics
- Headlines have an editorial, magazine-like quality
- Italicized headlines for elegance
- Strong contrast between serif headlines and sans-serif body

### Font Sizes
- Hero H1: 56-72px (large, commanding)
- Section H2: 40-56px
- Body: 16-18px
- Navigation: 14-16px

### Line Heights
- Headlines: 1.05-1.15 (tight)
- Body: 1.6-1.7

---

## Layout Principles

### Navigation
- Clean, minimal header
- Logo left (wordmark style)
- Sparse menu items with generous spacing
- Single accent-colored CTA button
- No borders or backgrounds initially

### Hero Section
- Massive headline (often multi-line)
- Minimal subtitle
- Single CTA button
- Asymmetric layout possible
- Abstract graphic/animation below or beside

### Sections
- Alternating dark/light backgrounds
- High contrast transitions
- Generous vertical padding (120-160px)

### Grid
- Max-width: 1200px
- Very generous margins
- Content often left-aligned or asymmetric

---

## Visual Effects

### Background
- Pure flat colors (no gradients on backgrounds)
- Clean, uncluttered
- Occasional abstract line art or geometric shapes

### Graphics
- Line-based illustrations
- Neon green accents on black
- Abstract, tech-inspired visuals
- Minimal, purposeful imagery

### Animations
- Subtle and refined
- No flashy effects
- Smooth scrolling
- Elegant reveals

---

## Component Patterns

### Buttons
```css
/* Primary CTA */
background: #7CFF00;
color: #000000;
padding: 16px 32px;
border-radius: 50px; /* Pill shape */
font-weight: 600;
font-size: 14px;
transition: all 0.2s;

/* Hover */
background: #A3FF00;
transform: scale(1.02);
```

### Client Logos
- On white/light background section
- Black/dark logos
- Simple horizontal row
- Minimal styling

### Content Sections
- Large, bold headlines
- Short, punchy copy
- Clear hierarchy
- Lots of negative space

### Cards (if used)
- Minimal borders
- Clean backgrounds
- Focused content
- No heavy shadows

---

## Design Philosophy

### Minimalism
- Every element has purpose
- Remove anything unnecessary
- White space is a feature

### Contrast
- Black and white as primary palette
- Single accent color (neon green)
- Bold typography against clean backgrounds

### Editorial Feel
- Magazine-quality typography
- Confident, sparse layouts
- Content-first approach

### Tech Aesthetic
- Clean, modern, professional
- Subtle tech references in graphics
- No cluttered dashboards or busy visuals

---

## Key Takeaways

1. **Pure minimalism** - Black/white with single accent color
2. **Typography-driven** - Headlines are the hero
3. **High contrast** - Dark sections vs. light sections
4. **Single accent** - Neon green used sparingly but impactfully
5. **Editorial quality** - Magazine-like sophistication
6. **Restraint** - Less is more in every decision
7. **Confidence** - Design that doesn't try too hard
