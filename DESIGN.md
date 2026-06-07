---
# DESIGN.md — LixStudio
# Format: Google design.md spec (v0.2.0)
# Source: https://github.com/google-labs-code/design.md

colors:
  # Core palette
  black: "#0a0a0a"
  white: "#fafafa"
  
  # Gray scale
  gray-50: "#f5f5f5"
  gray-100: "#e5e5e5"
  gray-200: "#d4d4d4"
  gray-400: "#a3a3a3"
  gray-500: "#737373"
  gray-600: "#525252"
  gray-800: "#262626"
  gray-900: "#171717"
  
  # Semantic colors
  accent: "#0a0a0a"
  accent-soft: "#f0f0f0"
  surface: "#fafafa"
  surface-elevated: "#ffffff"
  ink: "#0a0a0a"
  ink-muted: "#737373"

typography:
  font-sans:
    fontFamily: "'Inter', -apple-system, system-ui, sans-serif"
    usage: "Body text, UI elements, navigation"
  font-serif:
    fontFamily: "'DM Serif Display', Georgia, serif"
    usage: "Display headings, hero text, emphasis"
  
  # Type scale
  display-xl:
    fontSize: "clamp(2.8rem, 5vw, 4.5rem)"
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: "-0.03em"
    fontFamily: "font-serif"
  display-lg:
    fontSize: "clamp(2rem, 3.5vw, 3rem)"
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: "-0.02em"
    fontFamily: "font-serif"
  display-md:
    fontSize: "clamp(1.5rem, 2.5vw, 2rem)"
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: "-0.01em"
    fontFamily: "font-serif"
  body-lg:
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.6
    fontFamily: "font-sans"
  body:
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
    fontFamily: "font-sans"
  body-sm:
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.5
    fontFamily: "font-sans"
  label:
    fontSize: "0.75rem"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.1em"
    textTransform: "uppercase"
    fontFamily: "font-sans"

rounded:
  none: "0"
  sm: "4px"
  md: "8px"
  lg: "16px"
  xl: "24px"
  pill: "100px"
  circle: "50%"

spacing:
  1: "0.25rem"
  2: "0.5rem"
  3: "1rem"
  4: "1.5rem"
  5: "2.5rem"
  6: "4rem"
  7: "6rem"
  8: "10rem"

components:
  nav:
    height: "64px"
    background: "rgba(250,250,250,0.9)"
    backdropFilter: "blur(12px)"
    borderBottom: "1px solid {colors.gray-100}"
    logo:
      fontWeight: 800
      fontSize: "1.1rem"
      letterSpacing: "-0.03em"
    link:
      fontSize: "0.875rem"
      fontWeight: 500
      letterSpacing: "0.02em"
      color: "{colors.gray-500}"
      hoverColor: "{colors.black}"
    cta:
      background: "{colors.black}"
      color: "{colors.white}"
      borderRadius: "{rounded.pill}"
      fontSize: "0.8rem"
      fontWeight: 600
      letterSpacing: "0.04em"
      padding: "10px 24px"
  
  hero:
    minHeight: "100vh"
    display: "flex"
    alignItems: "center"
    tag:
      background: "{colors.gray-50}"
      border: "1px solid {colors.gray-200}"
      borderRadius: "{rounded.pill}"
      fontSize: "0.75rem"
      fontWeight: 500
      padding: "6px 16px"
  
  card:
    background: "{colors.white}"
    border: "1px solid {colors.gray-100}"
    borderRadius: "{rounded.lg}"
    shadow: "0 1px 3px rgba(0,0,0,0.04)"
    hoverShadow: "0 8px 30px rgba(0,0,0,0.08)"
    hoverTranslateY: "-4px"
    transition: "all 0.3s ease"
  
  button:
    primary:
      background: "{colors.black}"
      color: "{colors.white}"
      borderRadius: "{rounded.pill}"
      fontSize: "0.875rem"
      fontWeight: 600
      padding: "14px 32px"
      hoverOpacity: 0.85
    ghost:
      background: "transparent"
      color: "{colors.black}"
      border: "1.5px solid {colors.gray-200}"
      borderRadius: "{rounded.pill}"
      fontSize: "0.875rem"
      fontWeight: 500
      padding: "14px 32px"
      hoverBorder: "{colors.black}"

  tag:
    display: "inline-block"
    fontSize: "0.65rem"
    fontWeight: 600
    letterSpacing: "0.08em"
    textTransform: "uppercase"
    padding: "4px 10px"
    borderRadius: "{rounded.sm}"
    background: "{colors.black}"
    color: "{colors.white}"
---

# LixStudio Design System

## Visual Theme & Atmosphere

LixStudio embodies **Swiss minimalist precision meets Bali warmth**. The design language is intentionally restrained — black and white dominance with generous whitespace creates a gallery-like canvas where portfolio work becomes the sole splash of color.

**Core vibe:** A premium design studio that feels approachable, not pretentious. Think "high-end gallery in a bamboo pavilion" — the structure is clean and modern, but there's an organic warmth underneath.

**Key principles:**
- Work speaks louder than decoration
- Every pixel earns its place
- White space is not empty — it's breathing room
- Typography carries the personality, not ornaments

## Color Palette & Roles

| Role | Token | Hex | Usage |
|------|-------|-----|-------|
| Primary / Ink | `black` | `#0a0a0a` | Text, logo, primary buttons |
| Surface | `white` | `#fafafa` | Page background |
| Elevated Surface | `surface-elevated` | `#ffffff` | Cards, modals |
| Border / Divider | `gray-100` | `#e5e5e5` | Subtle borders, dividers |
| Muted Text | `gray-500` | `#737373` | Secondary text, labels |
| Interactive Hover | `accent` | `#0a0a0a` | Hover states, focus rings |
| Soft Accent | `accent-soft` | `#f0f0f0` | Tag backgrounds, badges |

**Color philosophy:** Near-monochrome. The portfolio images provide all the color the page needs. No decorative colors compete with the work.

## Typography Rules

| Level | Font | Size | Weight | Line Height | Letter Spacing | Usage |
|-------|------|------|--------|-------------|----------------|-------|
| Display XL | DM Serif Display | clamp(2.8rem, 5vw, 4.5rem) | 400 | 1.1 | -0.03em | Hero headlines |
| Display LG | DM Serif Display | clamp(2rem, 3.5vw, 3rem) | 400 | 1.2 | -0.02em | Section titles |
| Display MD | DM Serif Display | clamp(1.5rem, 2.5vw, 2rem) | 400 | 1.3 | -0.01em | Subheadings |
| Body LG | Inter | 1.125rem | 400 | 1.6 | normal | Hero descriptions |
| Body | Inter | 1rem | 400 | 1.6 | normal | General body text |
| Body SM | Inter | 0.875rem | 400 | 1.5 | normal | Captions, metadata |
| Label | Inter | 0.75rem | 600 | 1 | 0.1em | Tags, uppercase labels |

**Typography philosophy:** Serif for display (elegance, authority), sans-serif for body (clarity, modernity). The contrast between DM Serif Display and Inter creates visual interest without decoration.

## Layout Principles

**Spacing scale:** Golden ratio-ish progression
- `sp-1`: 0.25rem (4px) — Tight internal padding
- `sp-2`: 0.5rem (8px) — Element gaps
- `sp-3`: 1rem (16px) — Standard spacing
- `sp-4`: 1.5rem (24px) — Section padding mobile
- `sp-5`: 2.5rem (40px) — Section gaps
- `sp-6`: 4rem (64px) — Section padding desktop
- `sp-7`: 6rem (96px) — Large section breaks
- `sp-8`: 10rem (160px) — Hero spacing

**Grid:** CSS Grid with `auto-fill` and `minmax()` for responsive card layouts. No explicit breakpoints for the grid — it adapts fluidly.

**Whitespace philosophy:** More is more. Generous padding creates a premium, unhurried feel. Every section has breathing room.

## Elevation & Depth

**Shadow system:**
- Subtle: `0 1px 3px rgba(0,0,0,0.04)` — Cards at rest
- Medium: `0 8px 30px rgba(0,0,0,0.08)` — Cards on hover
- No heavy shadows — flat design with subtle depth

**Surface hierarchy:**
1. Page background (`#fafafa`) — Ground level
2. Cards (`#ffffff` + subtle border) — First elevation
3. Nav (`rgba(250,250,250,0.9)` + backdrop blur) — Floating element

## Shapes

**Border radius usage:**
- Cards: `16px` (rounded-lg) — Soft, approachable
- Buttons: `100px` (pill) — Friendly, clickable
- Tags: `4px` (rounded-sm) — Subtle, functional
- Avatars: `50%` (circle) — Profile images

**Philosophy:** Rounded but not bubbly. The pill-shaped buttons add warmth to the otherwise geometric layout.

## Components

### Navigation Bar
- Fixed top, `64px` height
- Frosted glass effect (`backdrop-filter: blur(12px)`)
- Logo: "LixStudio" in Inter 800, `-0.03em` tracking
- Single CTA button: black pill with white text
- Mobile: hamburger menu with slide-down overlay

### Hero Section
- Full viewport height (`100vh`)
- Left: text content (tag + headline + description + CTAs)
- Right: featured project card with image
- Background: pure white
- "Available for projects" tag in soft gray pill

### Portfolio Cards
- White background with `1px solid #e5e5e5` border
- `16px` border-radius
- Subtle shadow at rest, elevated shadow on hover
- `translateY(-4px)` on hover
- Image with `1.03` scale on hover
- Black "Featured" tag overlay

### Buttons
- **Primary (dark):** Black fill, white text, pill shape, `0.875rem` Inter 600
- **Ghost:** Transparent, dark border, pill shape — secondary actions
- Both: `14px 32px` padding

### Tags / Badges
- Small (`0.65rem`), uppercase, `0.08em` tracking
- Black background, white text
- Used for: "Featured", category labels, status indicators

## Do's and Don'ts

### Do ✅
- Use black and white as the primary palette — let portfolio images provide color
- Keep generous whitespace between sections
- Use DM Serif Display for headlines, Inter for everything else
- Make CTAs pill-shaped (rounded buttons)
- Use subtle borders instead of heavy shadows
- Keep animations smooth: `cubic-bezier(0.16, 1, 0.3, 1)` easing
- Use `clamp()` for responsive typography

### Don't ❌
- Add decorative colors to the layout (no gradients, no accent colors)
- Use heavy box-shadows or drop-shadows
- Center-align long body text (left-align for readability)
- Use more than 2 font families
- Make the nav opaque — keep the frosted glass effect
- Use sharp corners (0px radius) on cards
- Add texture or patterns to backgrounds
- Compete with portfolio images for visual attention

## Responsive Behavior

- **Mobile first:** Base styles are mobile, `min-width` queries for desktop
- **Typography:** All display sizes use `clamp()` for fluid scaling
- **Grid:** `auto-fill` with `minmax(270px, 1fr)` for portfolio cards
- **Nav:** Collapses to hamburger menu below `768px`
- **Touch targets:** Minimum `44px` height for interactive elements
- **Spacing:** Section padding reduces proportionally on mobile

## Agent Prompt Guide

**Quick reference for AI agents:**

```
Primary: #0a0a0a (near-black)
Surface: #fafafa (off-white)
Border: #e5e5e5 (light gray)
Muted: #737373 (medium gray)

Display font: DM Serif Display (serif, elegant)
Body font: Inter (sans-serif, clean)

Card style: white bg, 1px #e5e5e5 border, 16px radius, subtle shadow
Button style: black pill, white text, 600 weight
Tag style: black bg, white text, tiny uppercase, sharp corners

Easing: cubic-bezier(0.16, 1, 0.3, 1)
Whitespace: generous (golden ratio spacing scale)
Vibe: Swiss minimalism + Bali warmth
```

**Ready-to-use agent prompt:**
> "Build me a [component/page] using the LixStudio design system: near-monochrome palette (#0a0a0a on #fafafa), DM Serif Display for headlines, Inter for body, pill-shaped buttons, 16px card radius, subtle shadows, generous whitespace. No decorative colors — let content provide the visual interest."
