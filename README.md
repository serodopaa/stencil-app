# Trace Table

Upload a photo, turn it into a stencil, and watch it get traced and shaded by pen, or draw over it yourself.

Open `index.html` in a browser. No build step or server needed.

- **Stencil**: Canny edge detection finds the outlines; tone bands become cross-hatching.
- **Auto-trace**: the outlines are linked into strokes, ordered by nearest neighbour, and drawn live, followed by hatching.
- **Pencil / Eraser**: draw by hand over the stencil or the photo underlay.
- **Save PNG**: exports the drawing on white.
