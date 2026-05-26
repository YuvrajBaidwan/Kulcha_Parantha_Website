# Brand Spec — Kulcha & Parantha Co. (Order Page)

## Color Tokens

```css
:root {
  --bg-teal:      #095256;
  --bg-charcoal:  #141818;
  --bg-maroon:    #870e0b;
  --cream:        #f5dbb3;
  --saffron:      #e79c10;

  --teal-rgb:   9, 82, 86;
  --maroon-rgb: 135, 14, 11;
  --charcoal-rgb: 20, 24, 24;
  --cream-rgb:  245, 219, 179;
  --saffron-rgb: 231, 156, 16;
}
```

## Atmospheric Strategy

**Base:** 45% deep teal / 25% deep maroon / 20% charcoal / 10% cream diffusion
**Character:** Luxury dispatch lounge — dark, layered, spatial, cinematic
**Texture:** Micro film grain (2-3%), architectural ghost arches, vignette falloff

## Platform Personality Translation

### Zomato Layer — Urban Editorial Confidence
- **Mood:** Curated, sophisticated, confident — restaurant guide atmosphere
- **Accent range:** Deep maroon (#870e0b) → reduced ruby warmth
- **Feeling:** Editorial framing, controlled rhythm, premium discovery
- **Interaction:** Slower, deliberate, editorial — 350ms transitions
- **Lighting:** Maroon editorial glow

### Swiggy Layer — Fluid Dispatch Momentum
- **Mood:** Energetic, accessible, responsive — premium delivery theatre
- **Accent range:** Saffron (#e79c10) → warm gold directionals
- **Feeling:** Kinetic movement, streamlined ordering, fluid
- **Interaction:** Faster, responsive — 200ms transitions
- **Lighting:** Saffron motion diffusion

## Typography
- **Display:** 'Playfair Display', Georgia, serif (heritage editorial voice)
- **Body:** 'Inter', system-ui, sans-serif (clean utility)
- **Light weight at display sizes, generous leading for luxury**

## Spacing
- 8px base unit
- Generous section rhythm (120px desktop → 64px mobile)
- Platform cards: 48px padding, 24px gap
- Border radius: 8-12px for cards, 4-6px for buttons

## Shadow System
- Multi-layer: maroon-tinted far shadow + neutral near shadow
- Card hover: subtle lift (translateY(-4px)) + intensified shadow
- Never flat — always layered depth
