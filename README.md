# Helios Skills

Agent skills for [Helios](https://github.com/BintzGavin/helios), a browser-native video engine for programmatic animation and rendering.

## Installation

### Via skills.sh

Install using the [skills CLI](https://skills.sh):

```bash
npx skills add BintzGavin/helios-skills
```

Or install individual skills by path:

```bash
# Start here for new projects
npx skills add BintzGavin/helios-skills/skills/getting-started

# Core packages
npx skills add BintzGavin/helios-skills/skills/core
npx skills add BintzGavin/helios-skills/skills/renderer
npx skills add BintzGavin/helios-skills/skills/player
npx skills add BintzGavin/helios-skills/skills/studio
```

### Via npm

```bash
npm install @helios-project/skills
```

## Available Skills

### Getting Started

- [**skills/getting-started**](./skills/getting-started) - Installation and quick start guide. Covers package installation, requirements (Node.js, FFmpeg), basic setup, and initial composition structure.

### Core

- [**skills/core**](./skills/core) - Core API for Helios video engine. Covers Helios class instantiation, signals, animation helpers, and DOM synchronization.

### Packages

- [**skills/renderer**](./skills/renderer) - Server-side rendering of Helios compositions to video files.
- [**skills/player**](./skills/player) - Embeddable video player with composition playback and controls.
- [**skills/studio**](./skills/studio) - Visual editor for Helios compositions.

### Workflows

- [**skills/workflows/create-composition**](./skills/workflows/create-composition) - Workflow for creating a new Helios composition.
- [**skills/workflows/render-video**](./skills/workflows/render-video) - Workflow for rendering compositions to video.
- [**skills/workflows/visualize-data**](./skills/workflows/visualize-data) - Workflow for data visualization animations.

### Framework Examples

- [**skills/examples/react**](./skills/examples/react) - React integration patterns
- [**skills/examples/vue**](./skills/examples/vue) - Vue integration patterns
- [**skills/examples/svelte**](./skills/examples/svelte) - Svelte integration patterns
- [**skills/examples/solid**](./skills/examples/solid) - Solid.js integration patterns
- [**skills/examples/vanilla**](./skills/examples/vanilla) - Vanilla JavaScript patterns

### Animation Libraries

- [**skills/examples/gsap**](./skills/examples/gsap) - GSAP animation integration
- [**skills/examples/framer-motion**](./skills/examples/framer-motion) - Framer Motion integration
- [**skills/examples/lottie**](./skills/examples/lottie) - Lottie animation playback
- [**skills/examples/threejs**](./skills/examples/threejs) - Three.js 3D scenes
- [**skills/examples/pixi**](./skills/examples/pixi) - PixiJS 2D graphics
- [**skills/examples/p5**](./skills/examples/p5) - p5.js creative coding

### Data Visualization

- [**skills/examples/d3**](./skills/examples/d3) - D3.js visualizations
- [**skills/examples/chartjs**](./skills/examples/chartjs) - Chart.js animated charts

### Rendering Techniques

- [**skills/examples/canvas**](./skills/examples/canvas) - Canvas 2D rendering
- [**skills/examples/signals**](./skills/examples/signals) - Reactive signals patterns
- [**skills/examples/tailwind**](./skills/examples/tailwind) - Tailwind CSS styling
- [**skills/examples/podcast-visualizer**](./skills/examples/podcast-visualizer) - Audio visualization

## License

Apache 2.0 - See [LICENSE](LICENSE) for details.
