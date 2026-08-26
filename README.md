# Astronautics Visualisers

Interactive study tools for **MAE 3304 (Astronautics I)** at the University of Texas at Arlington. Small single-page visualisers for the parts of orbital mechanics that are hard to picture from a chalkboard.

**Live: https://shunsuke925.github.io/cutting-the-cone/**

## The tools

**Cutting the Cone** (conics.html) tilts a plane through a double cone and shows the section turning from circle to ellipse to parabola to hyperbola, which is why an orbit can only ever be one of those four. Includes Dandelin spheres, a face-on view of the section with a, b and p marked, and a plot of a/p against eccentricity that shows the semi-major axis blowing up at e = 1 and returning negative for hyperbolas.

**Three Anomalies** (kepler.html) answers where the satellite is at time t. Watch the mean, eccentric and true anomalies pull apart as eccentricity grows, and see why Kepler's equation M = E - e sin E has to be solved numerically. Newton iterations are drawn directly on the curve.

## Notes

Each tool is one self-contained HTML file with no build step. Open the file directly in a browser, or use the live link above. three.js is loaded from a CDN for the 3D view; everything else is inline.

These are student study aids. They are not official course material and carry no endorsement from the department.

## Reference

Curtis, H. D. (2020). Orbital Mechanics for Engineering Students, Revised 4th Edition. Butterworth-Heinemann, Elsevier.
