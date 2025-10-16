# neural-flow-generative

## Summary

Create 'Neural Flow' - a sophisticated generative art system that creates evolving, organic flow fields like watching thoughts form in a neural network.

🧠 CONCEPT:
Autonomous agents (particles) flow through an invisible force field, leaving elegant trails that form mesmerizing patterns. The field constantly evolves using Perlin noise, creating organic, never-repeating formations. It's hypnotic, sophisticated, and beautiful - like watching consciousness emerge.

🎨 VISUAL SYSTEM:
- Dark background (deep navy to black gradient)
- Thousands of tiny particles (2-3px) flowing through space
- Particles leave fading trails creating smooth, flowing lines
- Color palette shifts slowly through sophisticated gradients:
  * Monochrome (white/gray on black) - minimalist
  * Warm (gold/amber/copper) - organic
  * Cool (cyan/blue/purple) - digital
  * Dual-tone (complementary colors) - dynamic
- Particles glow subtly, trails have slight opacity gradient
- Overall aesthetic: VERY high-end, gallery-worthy, not 'toyish'

⚙️ THE ALGORITHM:
- Perlin/Simplex noise field determines flow direction at each point
- Noise field evolves over time (4th dimension)
- Particles follow field vectors, creating organic curves
- Speed varies based on field intensity
- Particles respawn at edges, maintaining density
- Optional: particles avoid/attract each other (flocking behavior)

🎮 INTERACTIONS:
- Click/drag: Disturb the field (creates turbulence)
- Mouse position: Subtle influence on flow direction
- Scroll: Zoom into the pattern
- Spacebar: Pause/resume evolution
- 'S' key: Save current frame as image
- 'C' key: Cycle color palettes
- 'R' key: Randomize parameters, generate new pattern
- Number keys 1-5: Switch between preset configurations:
  1. Smooth Flow - gentle, meditative curves
  2. Turbulent - chaotic, energy
  3. Vortex - spiraling, hypnotic
  4. Waves - undulating patterns
  5. Neural - branching, network-like

🎛️ UI (Minimal, Elegant):
- Top left: Current mode name (fades after 2s)
- Bottom right: Subtle controls overlay (appears on hover):
  * Particle count slider (1k - 50k)
  * Flow speed multiplier
  * Trail length
  * Color palette selector
- Bottom left: 'Save Frame' icon button
- All UI in elegant, thin sans-serif font
- Controls have subtle glass-morphism effect

💫 ADVANCED FEATURES:
- Time-based evolution: pattern never repeats
- Multiple noise layers for complexity
- Particle lifetime affects trail opacity
- Optional: audio reactivity (if user plays music)
- Performance scaling: reduces particles if FPS drops
- Export settings to URL (shareable configurations)

🎯 PRESETS (Each feels completely different):

1. **Consciousness Stream**: Slow, wide trails, warm colors, meditative
2. **Digital Rain**: Fast downward flow, matrix-green, cyberpunk
3. **Silk**: Ultra-smooth, monochrome, minimal, gallery-worthy
4. **Aurora**: Undulating like northern lights, cool gradients
5. **Mycelium**: Branching organic networks, earthy tones

✨ TECHNICAL:
- Canvas-based with efficient particle system
- Use typed arrays for performance (Float32Array)
- Offscreen canvas for trails (composition)
- WebGL shaders if possible for 50k+ particles
- Perlin noise implementation (or simplex-noise library)
- RequestAnimationFrame with delta time
- Responsive canvas (fills viewport)

🎨 THE AESTHETIC:
- Think: Electric Objects art display, not game
- Screensaver-quality, museum-piece, 'I want this on my wall'
- Sophisticated color theory, not garish
- Smooth, organic motion, not jittery
- You could watch this for hours
- Professional designers would be impressed

🔥 WHY IT'S IMPRESSIVE:
- Algorithmically complex but visually simple
- Every instance is unique, never repeats
- Sophisticated taste - not kitsch
- Technical achievement (smooth at 60fps with thousands of particles)
- Shareable ('Check out this pattern I generated')
- Could be an actual art installation
- Appeals to tech people AND artists

This is the kind of thing you pull up at a dinner party and people gather around to watch. Or you fullscreen on a big monitor and it becomes your living room ambient art. Quality over spectacle.

## Features

This application was automatically generated to meet the following requirements:

- Dark gradient background (navy to black)
- Thousands of particles following flow field
- Particles leave smooth fading trails
- Perlin/Simplex noise for organic flow
- Flow field evolves over time
- Click/drag creates turbulence
- Mouse influences flow direction
- Multiple sophisticated color palettes
- 5 preset configurations (Smooth/Turbulent/Vortex/Waves/Neural)
- Number keys 1-5 switch presets
- Spacebar pauses/resumes
- S key saves frame as image
- C key cycles color palettes
- R key randomizes pattern
- Particle count slider (1k-50k)
- Flow speed control
- Trail length control
- Elegant minimal UI with glass-morphism
- 60fps smooth animation
- Responsive fullscreen canvas
- Performance scaling (reduces particles if needed)
- Gallery-worthy aesthetic
- Bootstrap 5 for UI components

## Setup

This is a static web application that requires no build process.

### Local Development

1. Clone this repository
2. Open `index.html` in a web browser
3. Or serve with a local server:
   ```bash
   python -m http.server 8000
   ```


## Usage

Simply open the `index.html` file in a modern web browser. The application includes:
- Bootstrap 5 for responsive design
- Inline JavaScript for functionality
- Embedded data for attachments

## Code Explanation

### HTML Structure
- Uses semantic HTML5 elements
- Bootstrap components for UI
- Responsive design that works on all devices

### JavaScript Functionality
- Handles user interactions
- Processes data from attachments
- Updates DOM elements dynamically
- Includes error handling

### Styling
- Bootstrap 5 framework
- Custom CSS for specific requirements
- Mobile-first responsive design

## Deployment

This application is deployed on GitHub Pages and accessible at the URL provided in the repository settings.

## License

MIT License - See LICENSE file for details

## Auto-Generated

This application was automatically generated using AI-powered code generation.
Generated on: neural-flow-generative
