# Garage Climbing Wall — Parametric Designer

A parametric design tool for building a faceted home climbing wall: plywood skins over vertical plywood ribs, with a t-nut grid for reconfigurable holds. Dial in your garage's dimensions and it generates the geometry and everything needed to build it.

**Live demo:** https://swolevirus.com/climbingwall/

## What it does

- Interactive 3D view of the faceted wall (drag to orbit), colored by steepness, with a framing-skeleton toggle
- Difficulty ramps from vertical terrain near the garage-door end to a steep cave at the back, where the wall can wrap onto the back wall for a stemming corner
- A depth budget keeps the wall shallow where vehicle doors need to open — the constraint and the difficulty gradient conveniently want the same thing
- **Cut sheets**: every panel unfolded flat with dimensions to 1/16", corner angles, a check diagonal, t-nut layout, and the saw bevel for every edge
- **Seam schedule**: fold angle and rip bevel for the 2×4 backing behind every joint
- **Structure**: rib profile drawings, anchoring details, splice rules
- **Joinery**: section drawings of every joint family (seams, ribs, wall/floor/top connections, the corner)
- **Materials**: live shopping list
- **Volumes**: a bolt-on volume generator (pyramid/ridge/wedge/shelf) with its own cut sheets
- Spec JSON export of all facet geometry; all parameters persist in the URL hash for sharing

## Running it

It's one dependency-free HTML file. Open `index.html` in a browser, or drop it on any static host.

## Caveats

It does the geometry; it is not an engineering stamp. Anchor into framing per the Structure tab, pad the landing zone, and verify all dimensions on site — real lumber and real walls drift from the model.

## License

Public domain under the [Unlicense](https://unlicense.org). Do anything you like with it.
