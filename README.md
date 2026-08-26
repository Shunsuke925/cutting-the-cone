# Cutting the Cone

An interactive 3D tool for MAE 3304 (Astronautics I) at UT Arlington: why every orbit is a circle, an ellipse, a parabola, or a hyperbola, and nothing else.

**Live: https://shunsuke925.github.io/cutting-the-cone/**

## What it does

Tilt a plane through a double cone and watch the section change class in real time. Two linked views sit side by side.

**The cut in 3D** shows the cone, the cutting plane, the intersection curve, and optional Dandelin spheres. **The section, face-on** shows the true shape of the cut, with the focus, a, b and p marked.

Below them, a plot of a/p against eccentricity shows the semi-major axis growing without bound as e approaches 1, then coming back **negative** for hyperbolas.

## The idea

The eccentricity depends on only two angles:

**e = sin(phi) / cos(alpha)**

where alpha is the cone's half-angle and phi is the plane's tilt from horizontal. Every boundary between classes is the same test: is alpha + phi less than, equal to, or greater than 90 degrees? The height of the cut never enters the formula, which is why sliding the plane rescales the section without ever changing its shape.

Since the two-body orbit equation r = p / (1 + e cos(theta)) is the polar form of a conic with the focus at the origin, an orbit cannot be anything but a conic section. The only open question is what e happens to be, and energy answers that.

## Running it

One self-contained HTML file. Open index.html in any browser, or just use the live link above. three.js is loaded from a CDN; everything else is inline.
