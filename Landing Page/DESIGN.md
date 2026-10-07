---
name: Vitality Tech Minimal
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3c4a42'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#855300'
  on-secondary: '#ffffff'
  secondary-container: '#fea619'
  on-secondary-container: '#684000'
  tertiary: '#006c4e'
  on-tertiary: '#ffffff'
  tertiary-container: '#57b48f'
  on-tertiary-container: '#00422e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#97f5cc'
  tertiary-fixed-dim: '#7bd8b1'
  on-tertiary-fixed: '#002115'
  on-tertiary-fixed-variant: '#00513a'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Be Vietnam Pro
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Be Vietnam Pro
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Be Vietnam Pro
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Be Vietnam Pro
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  metric-display:
    fontFamily: Be Vietnam Pro
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system embodies modern wellness technology tailored for Vietnamese fitness culture. The brand personality balances elite athletic coaching with accessible, empathetic wellness tracking. The visual identity avoids sterile clinical aesthetics and intimidating gym extremes, instead projecting vitality, clarity, and motivational energy.

The aesthetic blends **Modern Wellness Minimal** with **Soft Glassmorphism**:
- Ultra-clean backgrounds paired with luminous emerald accents.
- Tactile, frosted-glass floating layers for telemetry stats and trainer discovery.
- Generous micro-spacing and large, organic corner radii to convey human-centric empathy and comfort.
- High-precision data visualizations and metrics that reward daily health progress without visual clutter.

## Colors
The palette balances active endurance with clinical nutrition insights.

- **Primary (`#10B981`)**: The vital green signature. Used for main call-to-actions, core completion gauges, active workout states, and wellness milestones.
- **Primary Dark (`#047857`)**: Anchors deep visual accents, high-contrast text on light green containers, and active press states.
- **Primary Light (`#D1FAE5`)**: Surface tint for success states, nutrition badge backgrounds, and low-contrast selection pills.
- **Secondary / Accent (`#F59E0B`)**: High-energy amber. Denotes caloric burn counters, active heart-rate zones, coaching alerts, and streak achievements.
- **Neutral Canvas**: Canvas background is pure `#FFFFFF` with alternating surface cards in `#F8FAFC` to create soft distinction without heavy dividers.
- **Text & Stroke Hierarchy**: Headlines and primary data read in rich slate `#0F172A`, supporting metadata uses `#64748B`, and hairline borders rest at `#E2E8F0` with subtle alpha overlays on glass cards.

## Typography
`Be Vietnam Pro` serves across all typographic hierarchies to provide native tone support, nuanced diacritics, and modern geometric legibility for Vietnamese workout labels and nutrition indices.

- **Numerics & Vital Signs**: Workout counters, macro percentages, and caloric stats apply tighter tracking (`-0.02em`) with medium to bold weights for glanceable clarity during active sessions.
- **Headings**: Tight line-heights avoid visual fragmentation when diacritic vowel stacks occur in Vietnamese phrases.
- **Body & Secondary Copy**: Open line-heights (`1.5` to `1.6`) ensure long nutritional meal plans and exercise instructions are comfortable to consume.

## Layout & Spacing
The layout follows a responsive 12-column dynamic grid on desktop and tablet, collapsing to a fluid 4-column layout on mobile devices.

- **Mobile Viewports (under 768px)**: Strict 16px (`1rem`) outer margin to maximize screen real estate for workout split cards and bottom action bars.
- **Tablet & Split-view (768px - 1024px)**: 24px margins with 24px gutters to allow two-column comparison cards (e.g., trainer credentials alongside schedule booking).
- **Desktop (1024px+)**: Max container width capped at `1280px` centered with 48px margins, enabling dashboard widgets to sit in uncrowded, breathable configurations.
- **Rhythm**: All component paddings conform to a 4px/8px baseline rhythm to maintain vertical balance across heterogeneous stat cards.

## Elevation & Depth
Depth relies on soft-tinted ambient shadows and translucent frosted layers rather than opaque skeuomorphism.

- **Surface Glass (Level 1)**: `background: rgba(255, 255, 255, 0.85); backdrop-filter: blur(16px); border: 1px solid rgba(226, 232, 240, 0.8); box-shadow: 0 4px 20px -2px rgba(15, 23, 42, 0.04);`. Applied to metric cards, workout preview trays, and persistent filter tabs.
- **Surface Overlays (Level 2 - Navigation & Modals)**: `background: rgba(255, 255, 255, 0.94); backdrop-filter: blur(24px); border: 1px solid rgba(255, 255, 255, 0.4); box-shadow: 0 12px 32px -4px rgba(15, 23, 42, 0.08);`. Used for bottom sheets, sticky navigation bars, and trainer profile sheets.
- **Active State Glow**: Buttons and active stat indicators project a localized ambient aura tinted with Primary Green (`rgba(16, 185, 129, 0.25)`) with an 8px blur to indicate progress or primary conversion pathways.

## Shapes
The shape language communicates friendly approachability, comfort, and human health through generous curvature:

- **Large Interactive Cards & Panels**: Default border radius falls between 20px and 28px (`rounded-xl` equivalent). This structural softness eliminates rigid corporate corners and mimics high-end hardware interfaces.
- **Controls & Buttons**: Full pill radius (`rounded-full` / `9999px`) on primary actions, tag pills, and tab switchers.
- **Form Elements & Nested Badges**: 14px to 16px roundedness to maintain harmony inside parent cards without creating awkward nested concentric arcs.

## Components

### Buttons
- **Primary**: Pill-shaped (`rounded-full`), `#10B981` solid fill, `#FFFFFF` text, `font-weight: 600`. Subtle green ambient shadow (`0 4px 14px rgba(16, 185, 129, 0.35)`). Hover/Active transitions to `#047857`.
- **Secondary / Ghost**: Semi-translucent glass fill (`rgba(16, 185, 129, 0.1)`), `#047857` label, no border, pill-shaped.
- **Action Amber**: Used for premium bookings or high-intensity timers: `#F59E0B` fill, `#FFFFFF` text.

### Cards & Stat Tiles
- Built with 24px corner radii, `#FFFFFF` or `#F8FAFC` base, bounded by `1px solid #E2E8F0`.
- Integrated telemetry charts feature floating green or amber indicator dots with micro-badges showing delta progress (`+12%`).

### Chips & Filter Tags
- Height: 36px. Border radius: 9999px.
- Unselected: Surface `#F1F5F9`, text `#64748B`, border transparent.
- Selected: Background `#D1FAE5`, text `#047857`, border `1px solid #10B981`.

### Inputs & Search
- Generous 16px corner radius, background `#F8FAFC`, border `1px solid #E2E8F0`.
- Active focus transitions border to `#10B981` with an outer ring `0 0 0 3px rgba(16, 185, 129, 0.15)`.

### Checkboxes & Segmented Pickers
- Checkboxes: 20px rounded squares (`6px` radius). Filled `#10B981` on active with white micro check icon.
- Segmented Pickers (e.g., Week/Month/Year or Macro Split): Enclosed in `#F1F5F9` capsule with a sliding white pill thumb elevated by a soft 2px drop shadow.

### Domain-Specific: Trainer Profile & Nutrition Deck
- **Trainer Bio Card**: Glassmorphism footer overlay over high-resolution imagery, featuring floating star-rating chip (`#F59E0B`) and immediate booking pill button.
- **Macro Ring Tracker**: Triple concentric progress arc displaying protein (primary green), carbs (amber), and fats (muted slate).