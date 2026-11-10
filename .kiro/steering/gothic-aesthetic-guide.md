# Kiro Steering Document: Gothic Festive Luxury Styling

When generating or editing UI components for Nocturne Noel, adhere strictly to these principles:

1. **Avoid Standard Warm Red/Green**:
   Never use bright neon holiday red (#ff0000) or grass green (#00ff00). Always ground palettes in deep mineral tones: velvet emerald (#0f382c), blood crimson (#6b1526), and vintage aged gold (#d4af37).

2. **Glassmorphism & Depth**:
   Card elements must use multi-layered backdrop blur (`backdrop-blur-md`) with subtle 1px semi-transparent borders (`border border-amber-500/20`) to create a floating stained-glass illusion.

3. **Motion with Restraint**:
   Avoid abrupt, bouncy animations. Use aristocratic, measured transitions with easing (`cubic-bezier(0.16, 1, 0.3, 1)`).

4. **Self-Contained Soundscapes**:
   Never fetch external MP3 or WAV files over the network. Always generate procedural audio textures through Web Audio API oscillators.
