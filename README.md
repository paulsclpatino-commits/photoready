# Photoready

A single-page tool that turns photos into 1-color, screen-print-ready art at an exact physical size.

Open `index.html` in a browser (or host it on GitHub Pages). Nothing is uploaded; all processing happens in the browser.

- **Size**: circle (button/patch/print diameters) or rectangle (pocket, sleeve, front, back), in inches or mm, 150–600 DPI, optional bleed.
- **Position**: drag to move, scroll to zoom, rotate, mirror, fill/fit.
- **Tone**: brightness, contrast, midtones, threshold, auto threshold (Otsu), invert.
- **Screen**: gritty grain, hard threshold, Floyd–Steinberg, Atkinson, ordered, halftone dots (LPI + angle), line screen. Dot size keeps the smallest dot big enough to hold on the mesh; clean-up drops lone specks and fills pinholes.
- **Export**: 1-bit film positive PNG (black on white) or transparent PNG in the ink color, with DPI written into the file and optional registration/crop marks. Export all photos in one go.
