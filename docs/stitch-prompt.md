# Tonale Landing Page — Stitch Design Prompt

## Overview

Design a simple, modern, single-page landing page for **Tonale** — an IT software company based in Vilnius, Lithuania. The page serves as a professional reference (not advertising). It must support three languages: English, Polish, and Lithuanian.

Tonale creates apps and solutions based on AI and AI orchestration — mobile apps, web apps, and macOS tooling.

---

## Brand Identity

- **Font:** Rubik (Google Fonts) — weights 400, 500, 700
- **Primary gradient:** `#6c5ce7` (purple) → `#00cec9` (teal), 135deg
- **Logo:** 11 vertical rounded bars forming a mountain/sound wave silhouette with "tonale" wordmark below in Rubik Regular lowercase. The bars use a vertical gradient from purple (top) to teal (bottom) with outer bars at lower opacity.

### Color Tokens

| Token | Hex | Usage |
|-------|-----|-------|
| Purple | `#6c5ce7` | Gradient start, accents, CTAs |
| Teal | `#00cec9` | Gradient end, secondary accents |
| White | `#FFFFFF` | Primary background |
| Off-White | `#f7f7fb` | Card/section backgrounds |
| Dark Navy | `#1a1a2e` | Headings, primary text |
| Slate | `#4a4a68` | Body text, descriptions |
| Muted Grey | `#8888a4` | Captions, footer text |
| Border | `#e8e8f0` | Card borders, dividers |
| Deep Navy | `#0a0f1a` | Dark sections, footer |
| Cloud | `#e8edf3` | Text on dark backgrounds |

### Spacing

Base unit: 4px. Container max-width: 1200px. Border-radius: 12px buttons, 16px cards.

### Buttons

- **Primary:** gradient background (135deg, purple → teal), white text, Rubik 500, 14px/32px padding, 12px radius, hover: scale(1.02) + shadow
- **Secondary:** 2px solid purple border, purple text, 12px/30px padding, 12px radius

---

## Page Structure

### 1. Language Switcher (top-right corner)

Three small text buttons: **EN** | **PL** | **LT**. Active language is highlighted with purple color. Rubik 500, 14px. Sits in the top-right of the hero or as a fixed minimal bar.

### 2. Hero Section

- Background: white
- Logo icon (large, centered) — use `tonale-final-light.svg`
- Headline (Rubik 700, 56px, centered)
- Subtitle (Rubik 400, 18px, slate color, centered, max 2 lines)
- Primary CTA button: links to `mailto:info@tonale.lt`
- Generous vertical padding (120px top/bottom)

### 3. Services Section

- Background: off-white (`#f7f7fb`)
- Section heading (Rubik 700, 36px, centered)
- 3 cards in a row (responsive: stack on mobile)
- Each card: white background, 1px border, 16px radius, 32px padding, subtle shadow
- Each card contains: line icon (Lucide style, 32px, purple), heading (Rubik 500, 24px), short description (Rubik 400, 16px, slate)
- Vertical padding: 80px top/bottom

### 4. About Section

- Background: white
- Section heading (Rubik 700, 36px, centered)
- Short paragraph (Rubik 400, 18px, slate, centered, max-width 680px)
- Accent gradient line (thin, decorative, centered below heading)
- Vertical padding: 80px top/bottom

### 5. Contact & Footer

- Background: deep navy (`#0a0f1a`)
- Section heading (Rubik 700, 36px, cloud color, centered)
- Email: info@tonale.lt (teal color link)
- Phone: +370 605 83918 (teal color link)
- Small logo below (dark version — `tonale-final-dark.svg`)
- Copyright line: "© 2026 Tonale. All rights reserved." in muted grey
- Vertical padding: 80px top/bottom

---

## Content — All Languages

### Hero

| | EN | PL | LT |
|---|---|---|---|
| Headline | Building intelligent solutions | Tworzymy inteligentne rozwiazania | Kuriame ismanius sprendimus |
| Subtitle | We craft AI-powered mobile, web, and desktop applications that solve real problems. | Tworzymy aplikacje mobilne, webowe i desktopowe oparte na AI, ktore rozwiazuja realne problemy. | Kuriame AI pagristas mobiliasias, internetines ir darbalaukio programas, kurios sprend ia realias problemas. |
| CTA | Get in touch | Skontaktuj sie | Susisiekite |

### Services

**Card 1 — Mobile & Web Apps**

| | EN | PL | LT |
|---|---|---|---|
| Heading | Mobile & Web Apps | Aplikacje mobilne i webowe | Mobiliosios ir internetines programos |
| Description | Native and cross-platform applications designed for performance and great user experience. | Natywne i wieloplatformowe aplikacje zaprojektowane z mysla o wydajnosci i doskonaym doswiadczeniu uzytkownika. | Gimtosios ir daugiaplatformes programos, sukurtos nasumui ir puikiai vartotojo patirciai. |
| Icon | `smartphone` (Lucide) | | |

**Card 2 — AI & Orchestration**

| | EN | PL | LT |
|---|---|---|---|
| Heading | AI & Orchestration | AI i orkiestracja | DI ir orkestravimas |
| Description | Intelligent systems powered by AI agents, LLMs, and automated workflows tailored to your needs. | Inteligentne systemy oparte na agentach AI, LLM-ach i zautomatyzowanych procesach dostosowanych do Twoich potrzeb. | Ismaniossistemos, veikianciosDI agentu, LLM ir automatizuotu darbo eigupagrindupagal jusu poreikius. |
| Icon | `brain-circuit` (Lucide) | | |

**Card 3 — macOS Tooling**

| | EN | PL | LT |
|---|---|---|---|
| Heading | macOS Tooling | Narzedzia macOS | macOS irankiai |
| Description | Productivity tools and utilities built specifically for the Apple ecosystem. | Narzedzia produktywnosci stworzone specjalnie dla ekosystemu Apple. | Produktyvumo irankiai ir programos, sukurti specialiai Apple ekosistemai. |
| Icon | `monitor` (Lucide) | | |

### About

| | EN | PL | LT |
|---|---|---|---|
| Heading | About Tonale | O Tonale | Apie Tonale |
| Text | Tonale is a software company based in Vilnius, Lithuania. We specialize in building modern applications powered by artificial intelligence and AI orchestration. Our name draws from the Italian mountain pass Passo del Tonale and the musical concept of tonality — a blend of nature, sound, and technology. | Tonale to firma programistyczna z siedziba w Wilnie na Litwie. Specjalizujemy sie w tworzeniu nowoczesnych aplikacji opartych na sztucznej inteligencji i orkiestracji AI. Nasza nazwa pochodzi od wloskiej przerecz gorskiej Passo del Tonale i muzycznego pojecia tonalnosci — polaczenia natury, dzwieku i technologii. | Tonale yra programiniu irangusimone, isikurusi Vilniuje, Lietuvoje. Mes specializuojames kuriant modernias programas, pagristas dirbtiniu intelektu ir DI orkestravimu. Musu pavadinimas kildinamas is Italijos kalnupereja Passo del Tonale ir muzikines tonalumossampratos — gamtos, garso ir technologiju derinys. |

### Contact

| | EN | PL | LT |
|---|---|---|---|
| Heading | Get in Touch | Skontaktuj sie | Susisiekite su mumis |
| Email label | Email | Email | El. pastas |
| Phone label | Phone | Telefon | Telefonas |

### Footer

| | EN | PL | LT |
|---|---|---|---|
| Copyright | © 2026 MB "Tonale". All rights reserved. | © 2026 MB "Tonale". Wszelkie prawa zastrzezone. | © 2026 MB "Tonale". Visos teises saugomos. |

---

## Responsive Behavior

- **Desktop (1200px+):** Full layout as described, 3-column service cards
- **Tablet (768px–1199px):** Reduce padding, 2-column cards then stack
- **Mobile (<768px):** Single column, stacked cards, smaller hero heading (36px), language switcher centered above logo

---

## Assets

- `tonale-final-light.svg` — logo for white backgrounds (hero, about)
- `tonale-final-dark.svg` — logo for dark backgrounds (footer)
- `tonale-final-icon.svg` — icon only, for favicon

---

## Technical Notes

- Single static HTML page, no framework needed
- Google Fonts: Rubik 400, 500, 700
- Icons: Lucide Icons (CDN or inline SVG)
- Language switching: client-side JS toggling visibility of language-specific content
- Fully accessible: semantic HTML, proper contrast ratios, alt text on logo
