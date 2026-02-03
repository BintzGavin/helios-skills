# Helios Skills

Agent skills for [Helios](https://github.com/helios-project/helios), a browser-native video engine for programmatic animation and rendering.

## Installation

### Via skills.sh

Install using the [skills CLI](https://skills.sh):

```bash
npx skills add BintzGavin/helios-skills
```

Or install individual skills by path:

```bash
npx skills add BintzGavin/helios-skills/helios/core
npx skills add BintzGavin/helios-skills/helios/renderer
npx skills add BintzGavin/helios-skills/helios/player
npx skills add BintzGavin/helios-skills/helios/studio
```

### Via npm

```bash
npm install @helios-project/skills
```

## Available Skills

### Core

- **helios/core** - Core API for Helios video engine. Covers Helios class instantiation, signals, animation helpers, and DOM synchronization.

### Packages

- **helios/renderer** - Server-side rendering of Helios compositions to video files.
- **helios/player** - Embeddable video player with composition playback and controls.
- **helios/studio** - Visual editor for Helios compositions.

### Workflows

- **helios/workflows/create-composition** - Workflow for creating a new Helios composition.
- **helios/workflows/render-video** - Workflow for rendering compositions to video.
- **helios/workflows/visualize-data** - Workflow for data visualization animations.

### Framework Examples

- **helios/examples/react** - React integration patterns
- **helios/examples/vue** - Vue integration patterns
- **helios/examples/svelte** - Svelte integration patterns
- **helios/examples/solid** - Solid.js integration patterns
- **helios/examples/vanilla** - Vanilla JavaScript patterns

### Animation Libraries

- **helios/examples/gsap** - GSAP animation integration
- **helios/examples/framer-motion** - Framer Motion integration
- **helios/examples/lottie** - Lottie animation playback
- **helios/examples/threejs** - Three.js 3D scenes
- **helios/examples/pixi** - PixiJS 2D graphics
- **helios/examples/p5** - p5.js creative coding

### Data Visualization

- **helios/examples/d3** - D3.js visualizations
- **helios/examples/chartjs** - Chart.js animated charts

### Rendering Techniques

- **helios/examples/canvas** - Canvas 2D rendering
- **helios/examples/signals** - Reactive signals patterns
- **helios/examples/tailwind** - Tailwind CSS styling
- **helios/examples/podcast-visualizer** - Audio visualization

### Utilities

- **skill-creator** - Guide for creating new skills

## License

Apache 2.0 - See [LICENSE](LICENSE) for details.
