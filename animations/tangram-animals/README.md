# Tangram Animals

A pure CSS animated tangram puzzle that morphs geometric shapes into different animal forms.

![Tangram Animals preview](./preview.png)

## Features

- **Animated Tangram Pieces**: Seven shapes (triangles, square, parallelogram) smoothly transition to form multiple animals.
- **Pure CSS Implementation**: No JavaScript is used; all animations and transformations rely on CSS `@keyframes` and `transform`.
- **Interactive Hover Effects**: Shapes brighten and gain a subtle glow when hovered.
- **Responsive Design**: Scene scales gracefully across mobile, tablet, and desktop screens.
- **Multiple Animal Shapes**: Animates between Cat, Duck, and Whale formations in a continuous loop.
- **Modern Visual Style**: Gradient background and vivid piece colors enhance visual appeal.

## Demo

Check out the live animation on [CodePen](https://codepen.io/guillhermm/pen/KwMVXYR).

## Running Locally

1. Clone this repository:

```bash
git clone https://github.com/Guillhermm/pure-css-animations.git
```

2. Navigate to the animation folder:

```bash
cd animations/tangram-animals
```

3. Open the `index.html` file in any modern browser.

## Notes

- Each piece is animated independently with its own `@keyframes`, allowing precise positioning and rotation to form different animal shapes.
- Hovering over a piece temporarily increases brightness and raises it above others using `z-index`.
- The animation loop smoothly transitions between animal formations using carefully timed keyframe percentages.
- Fully compatible with modern browsers supporting CSS transforms, transitions, and filters.
- Ideal for interactive demos, educational content, or creative hero sections.