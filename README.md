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

- [**helios/core**](./helios/core) - Core API for Helios video engine. Covers Helios class instantiation, signals, animation helpers, and DOM synchronization.

### Packages

- [**helios/renderer**](./helios/renderer) - Server-side rendering of Helios compositions to video files.
- [**helios/player**](./helios/player) - Embeddable video player with composition playback and controls.
- [**helios/studio**](./helios/studio) - Visual editor for Helios compositions.

### Workflows

- [**helios/workflows/create-composition**](./helios/workflows/create-composition) - Workflow for creating a new Helios composition.
- [**helios/workflows/render-video**](./helios/workflows/render-video) - Workflow for rendering compositions to video.
- [**helios/workflows/visualize-data**](./helios/workflows/visualize-data) - Workflow for data visualization animations.

### Framework Examples

- [**helios/examples/react**](./helios/examples/react) - React integration patterns
- [**helios/examples/vue**](./helios/examples/vue) - Vue integration patterns
- [**helios/examples/svelte**](./helios/examples/svelte) - Svelte integration patterns
- [**helios/examples/solid**](./helios/examples/solid) - Solid.js integration patterns
- [**helios/examples/vanilla**](./helios/examples/vanilla) - Vanilla JavaScript patterns

### Animation Libraries

- [**helios/examples/gsap**](./helios/examples/gsap) - GSAP animation integration
- [**helios/examples/framer-motion**](./helios/examples/framer-motion) - Framer Motion integration
- [**helios/examples/lottie**](./helios/examples/lottie) - Lottie animation playback
- [**helios/examples/threejs**](./helios/examples/threejs) - Three.js 3D scenes
- [**helios/examples/pixi**](./helios/examples/pixi) - PixiJS 2D graphics
- [**helios/examples/p5**](./helios/examples/p5) - p5.js creative coding

### Data Visualization

- [**helios/examples/d3**](./helios/examples/d3) - D3.js visualizations
- [**helios/examples/chartjs**](./helios/examples/chartjs) - Chart.js animated charts

### Rendering Techniques

- [**helios/examples/canvas**](./helios/examples/canvas) - Canvas 2D rendering
- [**helios/examples/signals**](./helios/examples/signals) - Reactive signals patterns
- [**helios/examples/tailwind**](./helios/examples/tailwind) - Tailwind CSS styling
- [**helios/examples/podcast-visualizer**](./helios/examples/podcast-visualizer) - Audio visualization

### Utilities

- [**skill-creator**](./skill-creator) - Guide for creating new skills

## License

Apache 2.0 - See [LICENSE](LICENSE) for details.
