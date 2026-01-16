# TSP Greedy Route Animation (Brazil)

A pure CSS animation visualizing a **Traveling Salesman Problem (TSP) greedy route** across Brazilian states, represented as glowing nodes connected by animated light beams.

This project explores geographic abstraction, sequential animation timing, and spatial reasoning using only HTML and CSS, with no JavaScript, SVG, or canvas.

![TSP Greedy Animation](./preview.png)

## Features

- **Greedy TSP Route Visualization:** The animation follows a predefined greedy approximation of a Traveling Salesman route across Brazil.
- **Brazilian States as Nodes:** Each state is represented as a circular node, with size proportional to its geographic area.
- **CSS-Only Map Rendering:** The entire map, nodes, and connections are built using divs and CSS variables.
- **Sequential Path Drawing:** Edges are drawn one by one using width-growth animations, simulating route construction.
- **Glowing Nodes:** States glow and pulse over time, creating a sense of traversal and activity.
- **Start Node Highlight:** The starting state (Acre) is visually emphasized with a golden glow.
- **Organic Motion:** Subtle floating and breathing animations add depth and life to the visualization.
- **Camera Breathing Effect:** A slow scale animation applied to the map enhances visual dynamism.
- **No JavaScript:** No logic, no algorithms running in real time - just HTML and CSS animations.

## Demo

Check out the live animation on [CodePen](https://codepen.io/guillhermm/pen/RNRKRVd).

## Running Locally

1. Clone this repository:

```bash
git clone https://github.com/Guillhermm/pure-css-animations.git
```

2. Navigate to the animation folder:

```bash
cd animations/tsp-greedy
```

3. Open the `index.html` file in any modern browser.

## Notes

- This project is a **visual and conceptual representation** of a greedy TSP route, not a dynamic solver.
- The route order is manually encoded using CSS keyframes.
- State positions are approximate and based on a simplified map projection.
- Edge lengths and rotations are manually calculated for visual coherence.
- Node sizes loosely reflect the relative area of each Brazilian state.
- Animations rely heavily on CSS variables, keyframes, and staggered delays.
- Designed as an experiment in **CSS geometry, timing orchestration, and algorithmic visualization without code execution.**