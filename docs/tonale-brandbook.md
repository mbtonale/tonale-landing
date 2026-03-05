# Tonale Brand Guidelines

## Brand Identity

**Tonale** is an IT software company based in Vilnius, Lithuania. The name draws from the Italian mountain pass *Passo del Tonale* and the musical concept of tonality — a blend of nature, sound, and technology.

The brand personality is **modern, approachable, and confident** — a young tech company that takes its craft seriously without being stiff or corporate.

---

## Logo

The logo consists of two elements: the **icon** (11 vertical bars forming a mountain/sound wave silhouette) and the **wordmark** ("tonale" in lowercase Rubik).

### Construction

The icon is built from 11 rounded vertical bars, symmetrically arranged around a central peak. The bars are bottom-aligned. Each bar has a vertical gradient from purple (`#6c5ce7`) at the top to teal (`#00cec9`) at the bottom. Outer bars have lower opacity, creating a natural fade effect.

The wordmark sits below the icon with consistent spacing. It uses **Rubik Regular (400)** in lowercase with generous letter-spacing.

### Preferred Version

The **light version** (white background) is the primary logo for all applications. Use the dark version only on dark backgrounds when necessary.

### Clear Space

Maintain a minimum clear space around the logo equal to the height of the letter "t" in the wordmark. No other graphic elements, text, or edges should enter this zone.

### Minimum Size

- Full logo (icon + wordmark): minimum width **120px** on screen, **30mm** in print
- Icon only: minimum **32px** on screen, **10mm** in print

### What Not to Do

- Do not rotate or skew the logo
- Do not change the gradient direction or colors
- Do not rearrange the icon and wordmark
- Do not add drop shadows, outlines, or effects
- Do not place the logo on busy or low-contrast backgrounds
- Do not stretch or compress the proportions

---

## Color Palette

### Primary Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Gradient Start | **Purple** | `#6c5ce7` | Icon bars top, accents, CTAs |
| Gradient End | **Teal** | `#00cec9` | Icon bars bottom, secondary accents |

### Neutral Colors

| Role | Name | Hex | Usage |
|------|------|-----|-------|
| Background | **White** | `#FFFFFF` | Primary page background |
| Text Primary | **Dark Navy** | `#1a1a2e` | Headings, body text |
| Text Secondary | **Slate** | `#4a4a68` | Subtitles, descriptions, captions |
| Text Muted | **Grey** | `#8888a4` | Placeholders, meta text |
| Border | **Light Grey** | `#e8e8f0` | Cards, dividers, input borders |
| Surface | **Off-White** | `#f7f7fb` | Card backgrounds, sections |
| Dark BG | **Deep Navy** | `#0a0f1a` | Dark sections, footer |
| Light Text | **Cloud** | `#e8edf3` | Text on dark backgrounds |

### Gradient Usage

The purple-to-teal gradient is the brand's signature visual element. Use it for:

- Icon bars (vertical, top-to-bottom)
- Accent lines and dividers
- CTA button backgrounds (horizontal, left-to-right)
- Highlight backgrounds (subtle, 5–10% opacity)

Never apply the gradient to body text. For text accents, use solid `#6c5ce7` (purple) or `#00cec9` (teal).

---

## Typography

### Font Family

**Rubik** — a slightly rounded sans-serif from Google Fonts. It balances professionalism with warmth.

```
Font: Rubik
Source: https://fonts.google.com/specimen/Rubik
Weights used: 400 (Regular), 500 (Medium), 700 (Bold)
```

### Type Scale

| Element | Weight | Size | Line Height | Letter Spacing | Color |
|---------|--------|------|-------------|----------------|-------|
| Hero Heading | 700 | 56px / 3.5rem | 1.1 | -0.02em | `#1a1a2e` |
| Section Heading | 700 | 36px / 2.25rem | 1.2 | -0.01em | `#1a1a2e` |
| Subsection | 500 | 24px / 1.5rem | 1.3 | 0 | `#1a1a2e` |
| Body Large | 400 | 18px / 1.125rem | 1.6 | 0 | `#4a4a68` |
| Body | 400 | 16px / 1rem | 1.6 | 0 | `#4a4a68` |
| Caption | 400 | 14px / 0.875rem | 1.5 | 0.01em | `#8888a4` |
| Button | 500 | 16px / 1rem | 1 | 0.02em | `#FFFFFF` |

### Text Guidelines

- Use lowercase "tonale" in running text when referring to the brand casually. Use "Tonale" at the start of a sentence.
- Never set body text in all caps. Reserve all-caps only for short labels or buttons.
- Maximum line width for readability: **680px** (approximately 70 characters).

---

## Spacing & Layout

### Base Unit

All spacing derives from a **4px base unit**. Common values:

| Token | Value | Usage |
|-------|-------|-------|
| `xs` | 4px | Tight inline gaps |
| `sm` | 8px | Icon-to-text, compact padding |
| `md` | 16px | Default padding, gap between elements |
| `lg` | 24px | Card padding, section inner spacing |
| `xl` | 48px | Between content blocks |
| `2xl` | 80px | Between major sections |
| `3xl` | 120px | Hero top/bottom padding |

### Page Container

- Max content width: **1200px**
- Horizontal padding: **24px** (mobile), **48px** (tablet), **80px** (desktop)
- Center-aligned on page

### Grid

Use a **12-column grid** with **24px** gutters. Common layouts:

- Full width: 12 columns
- Two-column: 6 + 6 or 7 + 5
- Three-column: 4 + 4 + 4
- Content with sidebar: 8 + 4

---

## Components

### Buttons

**Primary (gradient):**
- Background: linear-gradient(135deg, `#6c5ce7`, `#00cec9`)
- Text: `#FFFFFF`, Rubik 500, 16px
- Padding: 14px 32px
- Border-radius: 12px
- Hover: slight scale (1.02) + subtle shadow

**Secondary (outline):**
- Border: 2px solid `#6c5ce7`
- Text: `#6c5ce7`, Rubik 500, 16px
- Padding: 12px 30px
- Border-radius: 12px
- Hover: fill with `#6c5ce7` at 8% opacity

**Ghost (text only):**
- Text: `#6c5ce7`, Rubik 500, 16px
- Hover: underline or background `#6c5ce7` at 5% opacity

### Cards

- Background: `#FFFFFF`
- Border: 1px solid `#e8e8f0`
- Border-radius: 16px
- Padding: 32px
- Shadow: `0 2px 12px rgba(10, 15, 26, 0.06)`
- Hover (if interactive): shadow increases to `0 4px 24px rgba(10, 15, 26, 0.1)`

### Input Fields

- Border: 1.5px solid `#e8e8f0`
- Border-radius: 10px
- Padding: 12px 16px
- Font: Rubik 400, 16px
- Focus: border color `#6c5ce7`, ring `0 0 0 3px rgba(108, 92, 231, 0.15)`

---

## Iconography

Use a consistent line-icon style across the landing page:

- Style: outlined / line icons (not filled)
- Stroke width: 1.5px–2px
- Size: 24px default, 20px compact, 32px feature highlights
- Color: `#6c5ce7` for accent icons, `#4a4a68` for neutral icons
- Source recommendation: Lucide Icons (matches Rubik's rounded aesthetic)

---

## Landing Page Structure

Recommended section order for the tonale landing page:

### 1. Hero
- Logo icon (large, centered)
- Headline: bold, 56px, one line
- Subtitle: 18px, muted color, 2 lines max
- Primary CTA button
- Clean white background

### 2. What We Do / Services
- 3-column grid of cards
- Each: icon + heading + short description
- Off-white background (`#f7f7fb`)

### 3. About / Why Tonale
- Two-column layout: text left, visual right
- White background
- Accent gradient line as decoration

### 4. Contact / CTA
- Centered text block
- Primary CTA button
- Optionally on a dark background (`#0a0f1a`) with light text

### 5. Footer
- Dark background (`#0a0f1a`)
- Logo (dark version), contact info, links
- Text in `#8888a4`, links in `#00cec9`

---

## Assets Checklist

| File | Format | Purpose |
|------|--------|---------|
| `tonale-final-dark.png` | PNG 1600×800 | Logo on dark background |
| `tonale-final-dark.svg` | SVG | Logo on dark background (scalable) |
| `tonale-final-light.png` | PNG 1600×800 | Logo on white background (primary) |
| `tonale-final-light.svg` | SVG | Logo on white background (scalable) |
| `tonale-final-icon.png` | PNG 512×512 | App icon, favicon source |
| `tonale-final-icon.svg` | SVG | App icon (scalable) |

---

## Quick Reference

```css
/* Import */
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;700&display=swap');

/* CSS Custom Properties */
:root {
  --color-purple: #6c5ce7;
  --color-teal: #00cec9;
  --color-bg: #ffffff;
  --color-surface: #f7f7fb;
  --color-text: #1a1a2e;
  --color-text-secondary: #4a4a68;
  --color-text-muted: #8888a4;
  --color-border: #e8e8f0;
  --color-dark-bg: #0a0f1a;
  --color-light-text: #e8edf3;
  --gradient: linear-gradient(135deg, #6c5ce7, #00cec9);
  --font: 'Rubik', sans-serif;
  --radius-sm: 10px;
  --radius-md: 12px;
  --radius-lg: 16px;
  --shadow: 0 2px 12px rgba(10, 15, 26, 0.06);
  --shadow-hover: 0 4px 24px rgba(10, 15, 26, 0.1);
  --max-width: 1200px;
}
```
