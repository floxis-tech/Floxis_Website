# Assertive Yield Design Guide

## Overview
Assertive Yield (assertiveyield.com) is a publisher-focused ad tech platform with a premium, modern dark-themed design that conveys trust and sophistication.

---

## Color Palette

### Primary Colors
- **Background Dark**: `#0D0B1E` (Deep purple-black)
- **Background Card**: `#1A1730` (Elevated purple-dark)
- **Accent Gradient**: Orange → Pink → Magenta
  - Start: `#FF8C42` (Warm Orange)
  - Mid: `#FF6B9D` (Hot Pink)
  - End: `#C850C0` (Magenta)

### Secondary Colors
- **Text Primary**: `#FFFFFF` (Pure white)
- **Text Secondary**: `#9CA3AF` (Muted gray)
- **Border Subtle**: `rgba(255,255,255,0.08)`
- **Glow Effects**: `rgba(200,80,192,0.3)` (Magenta glow)

---

## Typography

### Font Family
- **Primary**: Inter, SF Pro Display, or similar geometric sans-serif
- **Fallback**: -apple-system, BlinkMacSystemFont, sans-serif

### Font Weights
- Headlines: 700-800 (Bold/Extra Bold)
- Subheadings: 600 (Semi Bold)
- Body: 400-500 (Regular/Medium)

### Font Sizes
- Hero H1: 48-64px (clamp responsive)
- Section H2: 36-48px
- Card H3: 20-24px
- Body: 16-18px
- Small/Labels: 12-14px

### Line Heights
- Headlines: 1.1-1.2
- Body: 1.6-1.7

---

## Layout Principles

### Navigation
- Fixed/sticky header with blur backdrop
- Logo left, centered menu links, CTA button right
- Subtle bottom border on scroll
- Height: ~80px

### Hero Section
- Large headline with gradient accent on key phrase
- Subtitle in muted text
- Dual CTA: Primary gradient button + Secondary text link with icon
- Optional: Video play button or animated visual

### Grid System
- Max-width: 1200-1400px
- Padding: 24-32px on sides
- Section padding: 100-120px vertical

### Card Design
- Background: Slightly elevated from page
- Border: 1px subtle white opacity
- Border-radius: 16-20px
- Padding: 32-40px
- Hover: Subtle lift + border glow

---

## Visual Effects

### Background
- Deep gradient base with radial color spots
- Subtle grid/mesh pattern overlay (opacity 0.02-0.05)
- Perspective grid lines at bottom (retro-futuristic)

### Gradients
- Text gradients on key headlines
- Button gradients (warm to hot colors)
- Icon container gradients

### Shadows & Glows
- Cards: Large soft shadow (0 20px 60px rgba(0,0,0,0.4))
- Buttons on hover: Glow matching gradient color
- No harsh drop shadows

### Animations
- Smooth hover transitions (0.2-0.3s)
- Button lift on hover (-2px translateY)
- Subtle fade-in on scroll

---

## Component Patterns

### Buttons
```css
/* Primary CTA */
background: linear-gradient(135deg, #FF8C42 0%, #C850C0 100%);
color: #0D0B1E;
padding: 14px 28px;
border-radius: 8px;
font-weight: 600;
transition: transform 0.2s, box-shadow 0.2s;

/* Hover */
transform: translateY(-2px);
box-shadow: 0 8px 30px rgba(200,80,192,0.4);
```

### Client Logo Section
- White/light logos on dark background
- Grid or flex row layout
- Generous spacing between logos
- Section title above: "Empowering Publishers for Success"

### Feature Cards
- Icon in gradient container (48-56px)
- Bold title
- Muted description text
- Optional: Hover border color change

### Testimonials
- Quote in italics
- Author name bold
- Company/role in muted text
- Card format with subtle styling

---

## Key Takeaways

1. **Dark, premium aesthetic** - Deep purples, not pure black
2. **Warm gradient accents** - Orange/pink/magenta palette
3. **Generous whitespace** - Sections breathe
4. **Subtle depth** - Grid patterns, glows, layered backgrounds
5. **Trust-focused** - Clean typography, professional tone
6. **Motion with purpose** - Subtle hovers, no flashy animations
