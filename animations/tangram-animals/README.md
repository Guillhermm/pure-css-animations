# CSS Tangram Animation

A beautiful, pure CSS/HTML tangram animation that smoothly transforms between three different animals without any JavaScript for the core animation.

## Features

- **Pure CSS/HTML**: No JavaScript required for the animations
- **Three Animals**: Cat, Bird, and Fish transformations
- **Smooth Transitions**: Elegant CSS transitions between shapes
- **Interactive Controls**: Buttons to switch between animals
- **Responsive Design**: Works on all screen sizes
- **Beautiful UI**: Modern gradient design with subtle animations

## How to Run

1. Simply open `index.html` in any modern web browser
2. No server or build process required
3. Works offline

## Project Structure

```
html/
├── index.html          # Main HTML file with structure and minimal JS for UI
├── style.css           # All CSS styling and animations
└── README.md           # This file
```

## How It Works

The animation uses:

1. **CSS Transforms**: Each tangram piece is positioned with absolute positioning
2. **CSS Transitions**: Smooth 1.2s cubic-bezier transitions between states
3. **CSS Classes**: Different animal modes change the transform properties
4. **Pure Geometry**: Seven standard tangram pieces forming different animals

## Tangram Pieces

1. Large Triangle 1 (Red)
2. Large Triangle 2 (Teal)
3. Medium Triangle (Yellow)
4. Square (Green)
5. Small Triangle 1 (Blue)
6. Small Triangle 2 (Purple)
7. Parallelogram (Orange)

## Browser Support

Works in all modern browsers that support:
- CSS Transforms
- CSS Transitions
- CSS Gradients
- CSS Flexbox

## No JavaScript? Really?

The core animation uses only CSS transforms and transitions. The minimal JavaScript included is only for the button interactions and updating the information panel. Remove the script tag and the animations still work - you just need to manually edit the CSS classes.

## Credits

Created as a demonstration of pure CSS animation capabilities. Inspired by traditional tangram puzzles and geometric art.

## License

Free to use for educational and personal projects.