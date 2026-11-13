# Trace Table

Upload a photo, turn it into a stencil, and watch it get traced and shaded by pen, or draw over it yourself.

Open `index.html` in a browser. No build step or server needed.

- **Photo mode**: Canny edge detection finds the outlines; tone bands become cross-hatching.
- **Line-art mode** (picked automatically for drawings and diagrams): each inked line is thinned to its centreline and redrawn at its measured thickness and colour; coloured areas are filled in with colour hatching.
- **Auto-trace**: the outlines are linked into strokes, ordered by nearest neighbour, and drawn live, followed by hatching.
- **Pencil / Eraser**: draw by hand over the stencil or the photo underlay.
- **Save PNG**: exports the drawing on white.
