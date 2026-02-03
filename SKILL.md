---
name: helios-skills
description: Collection of agent skills for Helios video engine. Use when working with programmatic video creation, browser-native animations, or Helios compositions. Install individual skills by path for specific capabilities.
---

# Helios Skills Collection

This repository contains agent skills for [Helios](https://github.com/BintzGavin/helios), a browser-native video engine for programmatic animation and rendering.

## Installation

This is a **collection repository** containing multiple skills. To use these skills, install individual skills by their path:

```bash
# Core skills
npx skills add BintzGavin/helios-skills/helios/core
npx skills add BintzGavin/helios-skills/helios/renderer
npx skills add BintzGavin/helios-skills/helios/player
npx skills add BintzGavin/helios-skills/helios/studio

# Workflows
npx skills add BintzGavin/helios-skills/helios/workflows/create-composition
npx skills add BintzGavin/helios-skills/helios/workflows/render-video
npx skills add BintzGavin/helios-skills/helios/workflows/visualize-data

# Framework examples
npx skills add BintzGavin/helios-skills/helios/examples/react
npx skills add BintzGavin/helios-skills/helios/examples/vue
npx skills add BintzGavin/helios-skills/helios/examples/svelte

# Animation libraries
npx skills add BintzGavin/helios-skills/helios/examples/gsap
npx skills add BintzGavin/helios-skills/helios/examples/framer-motion
npx skills add BintzGavin/helios-skills/helios/examples/threejs

# Utilities
npx skills add BintzGavin/helios-skills/skill-creator
```

## Available Skills

### Core Package Skills

- **helios/core** - Core API for Helios video engine. Covers Helios class instantiation, signals, animation helpers, and DOM synchronization.
- **helios/renderer** - Server-side rendering of Helios compositions to video files.
- **helios/player** - Embeddable video player with composition playback and controls.
- **helios/studio** - Visual editor for Helios compositions.

### Workflow Skills

- **helios/workflows/create-composition** - Workflow for creating a new Helios composition.
- **helios/workflows/render-video** - Workflow for rendering compositions to video.
- **helios/workflows/visualize-data** - Workflow for data visualization animations.

### Framework Integration Skills

- **helios/examples/react** - React integration patterns
- **helios/examples/vue** - Vue integration patterns
- **helios/examples/svelte** - Svelte integration patterns
- **helios/examples/solid** - Solid.js integration patterns
- **helios/examples/vanilla** - Vanilla JavaScript patterns

### Animation Library Skills

- **helios/examples/gsap** - GSAP animation integration
- **helios/examples/framer-motion** - Framer Motion integration
- **helios/examples/lottie** - Lottie animation playback
- **helios/examples/threejs** - Three.js 3D scenes
- **helios/examples/pixi** - PixiJS 2D graphics
- **helios/examples/p5** - p5.js creative coding

### Data Visualization Skills

- **helios/examples/d3** - D3.js visualizations
- **helios/examples/chartjs** - Chart.js animated charts

### Rendering Technique Skills

- **helios/examples/canvas** - Canvas 2D rendering
- **helios/examples/signals** - Reactive signals patterns
- **helios/examples/tailwind** - Tailwind CSS styling
- **helios/examples/podcast-visualizer** - Audio visualization

### Utility Skills

- **skill-creator** - Guide for creating new skills

## When to Use

Use these skills when:

- Creating programmatic video compositions
- Working with browser-native animations (CSS, WAAPI)
- Building video rendering pipelines
- Integrating Helios with React, Vue, Svelte, or other frameworks
- Using animation libraries like GSAP, Framer Motion, or Three.js
- Creating data visualizations as video
- Setting up Helios development workflows

## Repository

View all skills and source code at: https://github.com/BintzGavin/helios-skills
