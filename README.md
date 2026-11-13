# Drop Zone

A browser flight / driving / boating sim in one HTML file. No build, no install: open `index.html` or play it on GitHub Pages.

## Vehicles
Kolb (single-seat, full-span flaperons to 50°), Extra 300, B-17, UH-60 Black Hawk, Tesla Roadster (drives, loops, thrusters), Hydrofoil.

## Modes
1 Drop Zone · 2 Pylon Race · 3 Canyon Run · 4 Balloon Pop · 5 Deadstick · 6 Truck Bomb · 7 Race Track · 8 Power-off 180 · 9 STOL Comp

## World
12.8 km of streamed 8 m terrain: runway, canyon, roads with tunnels, a race track with two loop-the-loops, a river, forests, clouds. Physics collides with exactly the triangles you see.

## Controls (press H in game for the full list)
- Fly: W/S pitch, A/D roll, Q/E rudder, R/F throttle, Shift extra throw
- Flaps G/T, trim , . /, brakes B (B + Q/E for one side), sticky stick Y (Z centers)
- Drive / boat: I gas, K brake/reverse, J/L steer, B handbrake
- V views, N map, -/= map zoom, O tweaks, U sound, P pause, M menu

## Tech
three.js r128 from cdnjs, everything else hand-written in `index.html`. Settings and best scores live in your browser's localStorage.
