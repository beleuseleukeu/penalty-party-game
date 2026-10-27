---
name: Penalty Party
colors:
  surface: '#fbf8ff'
  surface-dim: '#d7d8ef'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2ff'
  surface-container: '#ececff'
  surface-container-high: '#e6e6fe'
  surface-container-highest: '#e0e1f8'
  on-surface: '#181a2b'
  on-surface-variant: '#484455'
  inverse-surface: '#2d2f41'
  inverse-on-surface: '#f0efff'
  outline: '#797487'
  outline-variant: '#cac3d8'
  surface-tint: '#6239e5'
  primary: '#6239e5'
  on-primary: '#ffffff'
  primary-container: '#7b57ff'
  on-primary-container: '#ffffff'
  inverse-primary: '#cbbeff'
  secondary: '#b7125a'
  on-secondary: '#ffffff'
  secondary-container: '#ff528f'
  on-secondary-container: '#5e002a'
  tertiary: '#006a5a'
  on-tertiary: '#ffffff'
  tertiary-container: '#008672'
  on-tertiary-container: '#ffffff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6deff'
  primary-fixed-dim: '#cbbeff'
  on-primary-fixed: '#1d0061'
  on-primary-fixed-variant: '#4a0fce'
  secondary-fixed: '#ffd9e0'
  secondary-fixed-dim: '#ffb1c4'
  on-secondary-fixed: '#3f001a'
  on-secondary-fixed-variant: '#8f0043'
  tertiary-fixed: '#57fbdb'
  tertiary-fixed-dim: '#2adec0'
  on-tertiary-fixed: '#00201a'
  on-tertiary-fixed-variant: '#005144'
  background: '#fbf8ff'
  on-background: '#181a2b'
  surface-variant: '#e0e1f8'
  party-yellow: '#FFD027'
  sky-blue: '#38BDF8'
  surface-cream: '#FAF9FC'
  surface-card: '#FFFFFF'
  danger-coral: '#FF4365'
  success-mint: '#10B981'
typography:
  display-hero:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Outfit
    fontSize: 34px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Outfit
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Outfit
    fontSize: 15px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Outfit
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Outfit
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an electrifying, high-energy party atmosphere tailored for online gatherings, college retreats, and casual social drinking games. Combining the crisp, contemporary precision of modern digital product design with the exuberant flair of a neon-tinted party lounge, the visual style blends clean surfaces with punchy, high-saturation accents.

The tone is playful, spontaneous, and delightfully suspenseful. It rejects sterile corporate minimalism in favor of vibrant tactility: bouncing interactive pills, energetic chromatic pops, tactile push-button feedback, and celebratory micro-interactions. The clean off-white background ensures maximum legibility and responsiveness across devices, allowing radiant neon violet, vivid coral, and bright party accents to demand attention during key gameplay moments such as roulette spins, ladder climbs, and the snap of the crocodile teeth.

## Colors

The palette is engineered to invoke instant joy, playful anticipation, and clear visual hierarchy.

- **Primary (`#7B57FF`)**: An electric neon violet anchoring high-priority triggers, dynamic active states, roulette hubs, and ladder paths.
- **Secondary (`#FF528F`)**: A radiant party coral pink injecting high-contrast energy for celebratory alerts, punishment badges, and interactive tooth targets.
- **Tertiary (`#00D2B4`)**: An electric mint supporting success states, dynamic status indicators, and secondary game selectors.
- **Neutral (`#6C6E82`)**: A calibrated slate violet maintaining typographic clarity without the harshness of pitch black.

Supporting tokens (`party-yellow`, `sky-blue`) supply celebratory diversity across multi-player badges, confetti explosions, and segment distinction in the circular roulette. Backgrounds prioritize clean optical clarity via `surface-cream` and elevated pure `surface-card`, allowing the neon tones to project luminescence without causing visual fatigue.

## Typography

Typographic scale balances geometric joy with rapid legibility. 

- **Headlines & Labels (`Outfit`)**: Selected for its open aperture, rounded geometric loops, and punchy personality. The bold weights (`700`, `800`) provide striking visual anchors on scoreboards, modal banners, and quick game pickers.
- **Body (`Hanken Grotesk`)**: An exceptionally crisp neo-grotesque that handles tight UI real estate, dense participant rosters, and multi-line punishment descriptions with effortless scanning comfort.

Mobile-specific overrides ensure dramatic presence without wrapping or breaking complex canvas viewports.

## Layout & Spacing

The layout is structured around an adaptive single-column container capped at a maximum width of `840px` for optimal party focus, expanding across a flexible grid on desktop screens and condensing to an edge-to-edge padded column on mobile web browsers.

- **Mobile Viewport (< 640px)**: Uses `margin: 1rem` and compact vertical stack layouts to keep game buttons and interactive viewports (e.g., SVG ladder canvas, roulette wheel) above the mobile fold.
- **Tablet / Desktop (>= 640px)**: Expands outer margins to `2rem` - `3rem` with an 8-column layout for participants and penalty configuration forms.
- **Component Rhythm**: Internal elements scale on a 4px/8px modular rhythm using `space-xs` (4px) through `space-xl` (40px) to balance airiness with fast single-hand touch ergonomics.

## Elevation & Depth

Depth in this system conveys game tension and immediate tangibility:

1. **Flat Ambient Base (`Level 0`)**: Neutral background `#FAF9FC` provides a calm canvas.
2. **Elevated Card Layer (`Level 1`)**: High-contrast white surfaces framed with a subtle border (`1px solid rgba(123, 87, 255, 0.08)`) and a diffused colored drop: `0px 8px 24px -4px rgba(123, 87, 255, 0.07)`.
3. **Interactive & Floating Controls (`Level 2`)**: Interactive pills, hover cards, and roulette spinners use dual-tinted drops with soft neon spreads: `0px 10px 20px -3px rgba(123, 87, 255, 0.22)`.
4. **Modals & Celebratory Overlays (`Level 3`)**: Backdrop is softened with a translucent frosted blur (`backdrop-filter: blur(8px); background: rgba(26, 21, 48, 0.4)`), while the punishment modal commands the front with `0px 24px 48px -12px rgba(255, 82, 143, 0.35)`.

## Shapes

The shape scale relies on `roundedness: 2` (base `0.5rem` / `8px`), offering a refined curvature that feels modern, soft, and approachable without turning childish.

- Standard inputs, list items, and interactive teeth: `0.5rem` (`rounded-md`).
- Primary game cards, canvas containers, and dialog sheets: `1rem` (`rounded-lg`).
- Game mode switcher tabs, player tokens, and floating action buttons: `9999px` (`rounded-full`) for high-speed thumb tapping.

## Components

### Buttons
- **Primary Action (Spin, Start, Fall)**: Full pill shape (`rounded-full`), solid `#7B57FF`, high-contrast white text, subtle bottom-inset shadow (`inset 0 -2px 0 rgba(0,0,0,0.15)`), and active state downward translation (`transform: translateY(2px)`).
- **Secondary / Danger (Reset, Penalty Trigger)**: Coral pink `#FF528F` with glowing hover halo.
- **Ghost & Icon Buttons**: Transparent background with soft hover tint (`rgba(123, 87, 255, 0.08)`).

### Game Mode Switcher (Capsule Tabs)
Segmented container wrapped in `#FFFFFF` with `rounded-full` styling and `padding: 4px`. The active tab slides with a solid `#7B57FF` background, crisp white typography, and a buoyant spring animation.

### Participant & Penalty Chips
Removable pill-shaped chips (`rounded-full`) featuring dynamic pastel backgrounds (mint, yellow, sky blue) paired with high-contrast text and a micro-close trigger (`×`) for swift deletion.

### Input Fields
Soft cream background (`#F4F3F8`), borderless by default with a `2px solid transparent` perimeter that transitions into `#7B57FF` upon focus. Placeholder text in `#A2A4B8`.

### Game Cards
White surface cards (`#FFFFFF`) featuring `rounded-lg` corners, 1px perimeter tint, and spacious internal padding (`space-lg`). Houses canvas elements like the SVG ladder path and HTML5 roulette with clear boundary framing.

### Crocodile Tooth Grid
Uniform interactive buttons arrayed in an elliptical grid. Default state: clean white rounded blocks with soft downward shadows. Pressed state: tooth depresses smoothly into the gum slot. Trap triggered: instant red highlight, shake keyframe, and snappy jaws overlay.

### Celebration & Result Modal
Centered dialog with dramatic spring entry (`cubic-bezier(0.34, 1.56, 0.64, 1)`), crowned with confetti emitter bursts and glowing neon headers declaring the chosen player and penalty.