# DBTECH45.COM BRAND SPECIFICATION SHEET

**Version:** 1.0  
**Date:** February 9, 2026  
**Designer:** Paula, Creative Director  
**Owner:** Derek @ DBTech45

---

## BRAND ESSENCE

**Tagline:** *Trade by day. Build by night. Dad of 7 always.*

**Brand Personality:**
- Builder / Maker / Shipper
- Technical but approachable
- Bold without being aggressive
- Professional with personality
- Dark mode native

**Core Values:**
- Imagination → Implementation
- Speed of execution
- Quality through iteration
- Family-first foundation

---

## COLOR PALETTE

### "Color is Everything"

The DBTech45 color system is built on contrast, clarity, and energy. Dark foundations with electric accents that command attention.

---

### PRIMARY COLORS

#### Void Black (Background)
```
HEX: #000000
RGB: 0, 0, 0
HSL: 0°, 0%, 0%
```
**Usage:** Primary background, hero sections, cards
**Psychology:** Authority, sophistication, focus

#### Carbon (Surface)
```
HEX: #111111
RGB: 17, 17, 17
HSL: 0°, 0%, 7%
```
**Usage:** Card backgrounds, elevated surfaces, modals
**Psychology:** Depth, layering, hierarchy

#### Graphite (Tertiary Surface)
```
HEX: #1A1A1A
RGB: 26, 26, 26
HSL: 0°, 0%, 10%
```
**Usage:** Hover states, secondary panels, borders
**Psychology:** Subtle differentiation

---

### ACCENT COLORS

#### Electric Amber (PRIMARY ACCENT)
```
HEX: #F59E0B
RGB: 245, 158, 11
HSL: 38°, 92%, 50%
```
**Usage:** CTAs, links, highlights, icons, brand marks
**Psychology:** Energy, optimism, action, warmth
**This is the signature DBTech45 color.**

#### Amber Glow (Hover State)
```
HEX: #FBBF24
RGB: 251, 191, 36
HSL: 43°, 96%, 56%
```
**Usage:** Hover states on amber elements, active states
**Psychology:** Heightened attention, engagement

#### Amber Dark (Pressed State)
```
HEX: #D97706
RGB: 217, 119, 6
HSL: 32°, 95%, 44%
```
**Usage:** Pressed/active states, visited links
**Psychology:** Depth, confirmation

---

### TEXT COLORS

#### Pure White (Primary Text)
```
HEX: #FFFFFF
RGB: 255, 255, 255
HSL: 0°, 0%, 100%
```
**Usage:** Headlines, primary body text, important labels
**Contrast Ratio vs Void Black:** 21:1 (AAA)

#### Silver (Secondary Text)
```
HEX: #A3A3A3
RGB: 163, 163, 163
HSL: 0°, 0%, 64%
```
**Usage:** Secondary text, captions, metadata
**Contrast Ratio vs Void Black:** 7.4:1 (AAA)

#### Smoke (Tertiary Text)
```
HEX: #737373
RGB: 115, 115, 115
HSL: 0°, 0%, 45%
```
**Usage:** Disabled text, placeholders, timestamps
**Contrast Ratio vs Void Black:** 4.6:1 (AA)

---

### SEMANTIC COLORS

#### Success Green
```
HEX: #10B981
RGB: 16, 185, 129
```
**Usage:** Success states, positive indicators, confirmations

#### Error Red
```
HEX: #EF4444
RGB: 239, 68, 68
```
**Usage:** Error states, destructive actions, warnings

#### Info Blue
```
HEX: #3B82F6
RGB: 59, 130, 246
```
**Usage:** Informational messages, links (alternative)

#### Warning Yellow
```
HEX: #EAB308
RGB: 234, 179, 8
```
**Usage:** Warning states, caution indicators

---

### COLOR RATIOS

**Background Distribution:**
- 70% Void Black (#000000)
- 20% Carbon (#111111)
- 10% Graphite (#1A1A1A)

**Accent Distribution:**
- 90% Electric Amber (#F59E0B) for all accent uses
- 10% Semantic colors for specific states

**Text Distribution:**
- 60% Pure White for primary content
- 30% Silver for secondary content
- 10% Smoke for tertiary/disabled

---

## TYPOGRAPHY

### Font Stack

#### Primary: Inter
```css
font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
```
**Why Inter:** Clean, technical, excellent readability at all sizes, variable font support.

#### Monospace: JetBrains Mono
```css
font-family: 'JetBrains Mono', 'Fira Code', 'Consolas', monospace;
```
**Usage:** Code blocks, terminal UI, technical data, the boot sequence animation.

---

### Type Scale

| Level | Size | Weight | Line Height | Letter Spacing | Usage |
|-------|------|--------|-------------|----------------|-------|
| Display | 72px | 700 | 1.1 | -0.02em | Hero headlines |
| H1 | 48px | 700 | 1.2 | -0.02em | Page titles |
| H2 | 36px | 600 | 1.25 | -0.01em | Section headers |
| H3 | 24px | 600 | 1.3 | 0 | Subsection headers |
| H4 | 20px | 600 | 1.4 | 0 | Card titles |
| Body Large | 18px | 400 | 1.6 | 0 | Lead paragraphs |
| Body | 16px | 400 | 1.6 | 0 | Default body text |
| Body Small | 14px | 400 | 1.5 | 0 | Secondary text |
| Caption | 12px | 500 | 1.4 | 0.02em | Labels, metadata |
| Code | 14px | 400 | 1.6 | 0 | Inline code |

---

### Typography Rules

1. **Headlines:** Always white (#FFFFFF), bold weight
2. **Body Text:** White or Silver depending on hierarchy
3. **Links:** Electric Amber (#F59E0B), no underline, underline on hover
4. **Code:** JetBrains Mono, Electric Amber text on Carbon background
5. **All Caps:** Use sparingly, only for labels and small UI elements, always add letter-spacing

---

## LOGO USAGE

### Primary Mark: DBTECH45

**Wordmark Style:**
- Font: Custom or Inter Bold
- Color: Electric Amber (#F59E0B) or White (#FFFFFF)
- Always one color, never gradient

**Clear Space:**
- Minimum clear space = height of "D" on all sides

**Minimum Size:**
- Digital: 120px width minimum
- Print: 1 inch width minimum

**Acceptable Versions:**
1. Electric Amber on Black (preferred)
2. White on Black
3. Black on White (light mode fallback)

**Never:**
- Apply gradients
- Use drop shadows
- Stretch or distort
- Place on busy backgrounds
- Use colors outside the brand palette

---

## VISUAL STYLE GUIDELINES

### Photography & Imagery

**Style:**
- Dark, moody lighting
- High contrast
- Minimal, focused subjects
- Technical/workspace imagery
- Trading screens, code editors, builds in progress

**Treatment:**
- Desaturate slightly
- Increase contrast
- Apply subtle amber color grade when appropriate

---

### Iconography

**Style:**
- Stroke-only (no fills)
- 2-3px stroke weight at standard size
- Rounded caps and joins
- Electric Amber (#F59E0B) color
- Consistent 24x24 or 400x400 canvas

**Icon Set:**
- Custom agent icons (already created)
- Lucide or Heroicons for UI elements
- Maintain visual weight consistency

---

### Borders & Dividers

```
Border Color: #F59E0B (Electric Amber) or #333333 (subtle)
Border Width: 1px for subtle, 2px for emphasis
Border Radius: 8px (small), 12px (medium), 16px (large)
```

---

### Shadows & Elevation

**Shadow Style:** Amber glow for emphasis, not traditional shadows.

```css
/* Subtle glow */
box-shadow: 0 0 20px rgba(245, 158, 11, 0.1);

/* Medium glow */
box-shadow: 0 0 30px rgba(245, 158, 11, 0.2);

/* Strong glow (hover states) */
box-shadow: 0 0 40px rgba(245, 158, 11, 0.3);
```

---

### Animation & Motion

**Principles:**
- Quick and responsive (150-300ms)
- Ease-out for entrances
- Ease-in for exits
- Subtle scale transforms (1.02-1.05x)
- No bouncy or playful animations

**Standard Transitions:**
```css
transition: all 0.2s ease-out;
```

---

## DESIGN SYSTEM FUNDAMENTALS

### Spacing Scale

```
4px   - xs (tight padding)
8px   - sm (icon gaps)
16px  - md (standard padding)
24px  - lg (section padding)
32px  - xl (component gaps)
48px  - 2xl (section gaps)
64px  - 3xl (major sections)
```

### Grid System

**Desktop:** 12-column grid, 1200px max-width, 24px gutters
**Tablet:** 8-column grid, 16px gutters
**Mobile:** 4-column grid, 16px gutters

### Breakpoints

```
Mobile: 0 - 639px
Tablet: 640px - 1023px
Desktop: 1024px - 1279px
Large Desktop: 1280px+
```

---

## COMPONENT PATTERNS

### Buttons

**Primary Button:**
```css
background: #F59E0B;
color: #000000;
padding: 12px 24px;
border-radius: 8px;
font-weight: 600;
```

**Secondary Button:**
```css
background: transparent;
border: 2px solid #F59E0B;
color: #F59E0B;
padding: 12px 24px;
border-radius: 8px;
font-weight: 600;
```

**Ghost Button:**
```css
background: transparent;
color: #F59E0B;
padding: 12px 24px;
```

### Cards

```css
background: #111111;
border: 1px solid #333333;
border-radius: 12px;
padding: 24px;
```

**Card Hover:**
```css
border-color: #F59E0B;
box-shadow: 0 0 30px rgba(245, 158, 11, 0.2);
transform: translateY(-2px);
```

### Input Fields

```css
background: #1A1A1A;
border: 1px solid #333333;
color: #FFFFFF;
padding: 12px 16px;
border-radius: 8px;
```

**Focus State:**
```css
border-color: #F59E0B;
outline: none;
box-shadow: 0 0 0 3px rgba(245, 158, 11, 0.2);
```

---

## ACCESSIBILITY

### Contrast Requirements

All text must meet WCAG 2.1 AA standards minimum.

| Element | Foreground | Background | Ratio | Grade |
|---------|------------|------------|-------|-------|
| Body Text | #FFFFFF | #000000 | 21:1 | AAA |
| Secondary Text | #A3A3A3 | #000000 | 7.4:1 | AAA |
| Accent on Dark | #F59E0B | #000000 | 8.6:1 | AAA |
| Dark on Accent | #000000 | #F59E0B | 8.6:1 | AAA |

### Focus States

All interactive elements must have visible focus indicators using Electric Amber.

---

## FILE NAMING CONVENTIONS

```
Icons: [agent]-icon.svg, [agent]-icon.png
Images: dbtech45-[description]-[size].jpg
Components: [component]-[variant]-[state].svg
```

---

## QUICK REFERENCE

### Copy-Paste Colors

```css
:root {
  /* Backgrounds */
  --color-void: #000000;
  --color-carbon: #111111;
  --color-graphite: #1A1A1A;
  
  /* Accent */
  --color-amber: #F59E0B;
  --color-amber-light: #FBBF24;
  --color-amber-dark: #D97706;
  
  /* Text */
  --color-white: #FFFFFF;
  --color-silver: #A3A3A3;
  --color-smoke: #737373;
  
  /* Semantic */
  --color-success: #10B981;
  --color-error: #EF4444;
  --color-info: #3B82F6;
  --color-warning: #EAB308;
}
```

---

## SUMMARY

**DBTech45 = Dark + Amber + Clean + Fast**

- **Background:** Void Black (#000000)
- **Surface:** Carbon (#111111)
- **Accent:** Electric Amber (#F59E0B)
- **Text:** White (#FFFFFF)
- **Font:** Inter + JetBrains Mono

**Color is everything. This palette commands attention, maintains readability, and establishes professional credibility while staying distinctly DBTech45.**

---

*Less, but better.*

Paula ✦
