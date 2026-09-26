# Foldline

**Paint the road. Then leave it.**

An open-world, ink-and-watercolour driving game in a single HTML file, built with [three.js](https://threejs.org).
Drive a rally rover with a brass gramophone on the roof through an endless folded-paper world — towns, wildflower
meadows, cherry groves, ink forests, lakes and paper mountains — all stitched together by painted roads that double
as sheet music.

**▶ Play:** https://aadil6971.github.io/foldline/

## Features

- **Endless world** streamed in chunks: towns, meadows, forests, cherry groves, lakes and snow-capped mountains
- **Hand-drawn look**: toon shading, ink outlines, watercolour wobble, paper grain and a torn-paper frame
- **Roads are sheet music**: steer through floating notes to play each road's melody and complete phrases
- **Get out and walk**: enter any vehicle — your rover, parked cars or any of 800 traffic vehicles
- **Fly**: fold into a paper plane or become an eagle
- **Living world**: pedestrians, horses, dogs, cats, foxes, bears, rabbits, chickens, swans, butterflies, fireflies and sky whales
- **46 kinds of place to discover**: castles, lighthouses, carousels, hedge mazes, waterfalls, cable cars, rainbows and more
- **Golden records** hidden on ramps, peaks and rooftops
- **Paper Moon FM**: a fully generative lo-fi radio, synthesised live in the browser
- **Time of day and rain**: dawn, morning, noon, golden hour, dusk, night

## Controls

| Key | Action |
| --- | --- |
| W / S | Throttle / brake (walk forward / back) |
| A / D | Steer |
| Space | Hop / jump / flap (eagle) |
| Shift | Boost / run |
| E | Get in / out of a vehicle |
| F / G | Paper plane / eagle (same key to land) |
| C | Cycle camera |
| Scroll, + / − | Zoom |
| [ ] | Field of view |
| 1–6, 0 | Time of day, auto |
| K | Rain |
| R · N · B | Radio on/off · next song · band |
| M | Minimap |
| P | Photo |
| H | Hide UI |
| Drag | Look around |

## Run locally

No build step. Serve the folder with any static server:

```bash
python3 -m http.server 8431
```

Then open http://localhost:8431.
