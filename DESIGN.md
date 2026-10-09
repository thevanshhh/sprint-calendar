# Sprint Calendar — Design System

## Visual Identity & Tone
- **Archetype:** Tactical, editorial, high-performance executive dashboard.
- **Tone:** Clear, purposeful, grounded, and distraction-free.

## Typography
- **Display Headings:** `"Familjen Grotesk"`, -apple-system, sans-serif (Weights: 600, 700). High-impact, balanced tracking (-0.015em).
- **Body & Controls:** `"Hanken Grotesk"`, -apple-system, sans-serif (Weights: 400, 500, 600). Highly legible text with comfortable measure.
- **Time, Data & Measurements:** `"IBM Plex Mono"`, ui-monospace, monospace. Tabular numeral formatting (`font-variant-numeric: tabular-nums`).

## Color Tokens & Palettes

### Light Theme
- Surface Background: `#f5f7f6`
- Card / Panel Surface: `#ffffff`
- Foreground Primary: `#14211f`
- Foreground Muted: `#566864`
- Border Line: `#d8e2df`
- Primary Accent: `#0c6257` (Deep Emerald)
- Accent Foreground: `#ffffff`

### Dark Theme
- Surface Background: `#0c1514`
- Card / Panel Surface: `#14201f`
- Foreground Primary: `#e5efec`
- Foreground Muted: `#8fa5a1`
- Border Line: `#253835`
- Primary Accent: `#4dd5bf` (Vibrant Mint)
- Accent Foreground: `#06231f`

### Category Spectrum (Subtle Badges)
- **Go Leverage Audits:** `--audit: #2458b0` / `--audit-bg: #e6eefb`
- **Walk-ins:** `--walk: #a46206` / `--walk-bg: #fbf0d8`
- **Appointy Outreach:** `--mail: #76379c` / `--mail-bg: #f3e5fa`
- **Physical / Body:** `--body: #1e743a` / `--body-bg: #e1f5e7`
- **Meals & Rest:** `--base: #566864` / `--base-bg: #eaeef0`
- **Personal Growth:** `--grow: #b22d55` / `--grow-bg: #fbe3eb`

## Impeccable Quality & Anti-Pattern Compliance
1. **No All-Caps Body Passages:** Pinned sprint goals and metrics are presented using clean, structured badge pills with distinct labels and bold values.
2. **No Colored Dark Glows:** Shadows on dark themes rely strictly on neutral alpha elevations (`rgba(0,0,0,0.25)` to `0.35`) without artificial chromatic halos.
3. **No Decorative Pulsing Animations:** Live time markers are calm, honest, and high-contrast without distracting animation loops.
4. **Accessible Contrast:** All text, badges, and counters maintain WCAG AA compliance (4.5:1+).
