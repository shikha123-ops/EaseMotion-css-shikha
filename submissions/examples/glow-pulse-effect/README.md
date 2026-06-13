# ✨ Glow Pulse Effect

A modern CSS animation that combines a smooth scale pulse with a glowing shadow effect.

This effect is useful for:

- Call-to-action buttons
- Notification badges
- Important icons
- Attention-grabbing UI elements

## Features

- Pure CSS implementation
- No JavaScript required
- Easy customization using CSS variables
- Lightweight and beginner-friendly
- Responsive and reusable

## Animation Behavior

The animation combines:

- Scale: `1 → 1.15 → 1`
- Glow intensity increase and decrease
- Smooth infinite loop

## CSS Variables

```css
:root {
  --glow-color: #4f46e5;
  --glow-intensity: 25px;
  --pulse-duration: 2s;
}
```

### Customization

Change the glow color:

```css
--glow-color: #22c55e;
```

Increase glow intensity:

```css
--glow-intensity: 40px;
```

Speed up the animation:

```css
--pulse-duration: 1s;
```

## Usage

Add the utility class:

```html
<button class="glow-pulse">
  Get Started
</button>
```

## Demo Examples

### CTA Button

```html
<button class="cta-button glow-pulse">
  Get Started
</button>
```

### Notification Badge

```html
<span class="badge glow-pulse">
  New
</span>
```

### Icon

```html
<div class="icon glow-pulse">
  ⭐
</div>
```

## Files

```text
glow-pulse-effect/
├── demo.html
├── style.css
└── README.md
```

## Author

Created for EaseMotion-css as a reusable animation example.