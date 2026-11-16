# Drop Zone

A browser flight / driving / boating sim in one HTML file. No build, no install: open `index.html` or play it on GitHub Pages.

## Vehicles
Kolb (long STOL wing, tundra tires on sprung bush gear, full-span flaperons to 50°), Extra 300, B-17, UH-60 Black Hawk, Tesla Roadster (drives, loops, thrusters), Model T Flivver (drives, thrusters), GT Coupe (plain fast road car, and the star of Arcade Drift), Glide Buggy (long-travel off-roader, G grows glider wings, T folds them), Hydrofoil.

## Modes
1 Drop Zone · 2 Pylon Race · 3 Canyon Run · 4 Balloon Pop · 5 Deadstick · 6 Truck Bomb · 7 Race Track · 8 Power-off 180 · 9 STOL Comp · 0 Freestyle (no clock, no score, go anywhere) · Arcade Drift (fake physics, the car cannot die, slide for points)

Cars: I is gas with road lock (the car follows the road or circuit under it and slows for bends; steer to release), W is plain gas. Lives can be set on the menu to carry on from where you crashed.

## World
12.8 km of streamed 8 m terrain around the airfield, with a different country on each side: desert to the north (dunes, granite tors, the red canyon, a sierra wall on the horizon), forested mountains to the east beyond the race track, glades to the south (bog pools, tree islands, a boat channel), snow mountains to the west. A ring road runs through all four, with spokes back to the field and six cross-country roads that cut straight through the mountains between them: about 70 km of road, 34 tunnels with portals, bridges and a causeway. Physics collides with exactly the triangles you see, and roads are solid decks.

## Controls (press H in game for the full list)
- Fly: W/S pitch, A/D roll, Q/E rudder, R/F throttle, Shift extra throw
- Flaps G/T, trim , . /, brakes B (B + Q/E for one side), sticky stick Y (Z centers)
- Drive / boat: I gas, K brake/reverse, J/L steer, B handbrake
- V views, N map, -/= map zoom, O tweaks, U sound, P pause, M menu

## Graphics levels
Full, Lite and Potato, picked on the menu and remembered (the page reloads to apply it). With nothing picked, the game guesses from the device's reported memory and cores. Same world and physics at every level; the lower ones draw fewer trees, cheaper or no shadows, fewer pixels and a shorter view. Add `?gfx=lite` or `?gfx=potato` to the address to force one.

## Tech
three.js r128 from cdnjs, everything else hand-written in `index.html`. Settings and best scores live in your browser's localStorage.
