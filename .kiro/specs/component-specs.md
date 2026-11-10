# Kiro Component Specifications: Nocturne Noel

## 1. Particle Canvas System (Snow & Ember Physics)
- **Engine**: 2D Context Canvas with requestAnimationFrame loop.
- **Layers**:
  - Background Layer: Soft floating crystalline snow with wind drift and turbulence.
  - Foreground Layer: Rising warm golden sparks from an unseen gothic fireplace.
- **Performance Requirement**: Maintain steady 60 FPS on desktop and mobile viewports.

## 2. Interactive Wishing Crystal (Wishing Chamber)
- **Component ID**: `#wishing-crystal`
- **State**: Idle (gentle radial pulse) -> Hover (enhanced luminescence) -> Activated (particle shockwave + card reveal).
- **Audio Feedback**: Synthesizes a delicate crystalline bell chord using Web Audio API on activation.

## 3. Gothic Holiday Fortune Generator
- **Algorithm**: Curated combinatoric gothic holiday poems inspired by Tim Burton's *The Nightmare Before Christmas*.
- **Output**: Collectible decorative Victorian-gothic card with copy-to-clipboard functionality.

## 4. Accessibility Compliance
- All text meets WCAG 2.1 AA contrast standards against dark glassmorphism surfaces (minimum 4.5:1 ratio for body copy).
