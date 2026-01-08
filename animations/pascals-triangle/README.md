# Pascal's Triangle

A CSS-only animated visualization of Pascal's Triangle, where each number is the sum of the two numbers directly above it.

![Pascal's Triangle preview](./preview.png)

## Features

- **Animated Cells**: Each triangle cell pulses and shimmers to create a dynamic, engaging effect.
- **Pure CSS Implementation**: No JavaScript; all animation and layout are handled with CSS.
- **Responsive Design**: Cell sizes and typography scale for mobile and desktop screens.
- **Visual Shimmer Effect**: Subtle gradient shimmer moves across cells to enhance visual appeal.
- **Educational Visualization**: Shows the structure of Pascal's Triangle and the relationship between numbers.
- **Modern Typography**: Gradient title text and clean font choices enhance readability and style.

## Demo

Check out the live animation on [CodePen](https://codepen.io/guillhermm/pen/myEVxrW).

## Running Locally

1. Clone this repository:

```bash
git clone https://github.com/Guillhermm/pure-css-animations.git
```

2. Navigate to the animation folder:

```bash
cd animations/pascals-triangle
```

3. Open the `index.html` file in any modern browser.

## Notes

- Each cell animates independently using `@keyframes pulse` and `@keyframes shimmer`.
- Animation delays are staggered using CSS variables (`--cell-index`) to create a cascading effect.
- Fully compatible with modern browsers supporting CSS `clip-path`, `@keyframes`, and gradients.
- Ideal for educational demos, hero sections, or visually rich UI backgrounds.