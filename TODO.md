# Research Page Enhancement - TODO

## Task: Make research page more visually interesting and interactive with circle SVG animations

### Implementation Plan

- [x] 1. Create animated circle SVG decorative elements (floating-circles.svg)
- [x] 2. Update research.css with new animation keyframes
- [x] 3. Add scroll-triggered fade-in animations for cards
- [x] 4. Add hover interactions for cards (scale, glow effects)
- [x] 5. Add floating circle background decorations to sections
- [x] 6. Make timeline more interactive with animated connectors
- [x] 7. Add pulsing circle effects in section backgrounds
- [x] 8. Test responsive behavior

### Visual Elements to Add:
- Floating/drifting circles in hero section
- Pulsing background circles in abstract section
- Animated decorative circles in card sections
- Interactive hover states with smooth transitions
- Scroll-triggered animations

### Color Palette:
- Sage: #88a751
- Rust: #a4502f
- Moss: #b2d07d
- Cream: #f6e8cd
- Wood: #6c4d2e

### Implementation Steps:

1. **Create floating-circles.svg** - Decorative circles for backgrounds
2. **Update research.css** - Add @keyframes for:
   - floatUpDown (floating animation)
   - pulseGlow (pulsing glow effect)
   - fadeInUp (scroll-triggered)
   - cardHover (interactive tilt)
3. **Update research.html** - Add SVG elements and animation classes
