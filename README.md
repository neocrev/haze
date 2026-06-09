# haze

Terminal particle system. Stars drift. Colours shift. You watch.

<p align="center">
  <img src="demo.svg" alt="haze demo" width="640">
</p>

```bash
npx haze
```

No flags, no config. Just staring at your terminal.

Press any key to exit.

I made this because I needed something pretty to look at while `npm install` runs.

## How it works

Haze fills your terminal with slowly drifting particles. Each one has its own colour, speed, and character. Some flicker. Some glow. They wrap around when they hit the edge.

Two particle types:
- **Stars** — small, numerous, twinkle (`·` `˙` `⋆` `✧` `+`)
- **Embers** — larger, warmer, drift slower (`.` `:` `°` `o` `O`)

Six colour palettes cycle through: ice blue, warm orange, lavender, pink, mint, gold.

## Why

Not everything needs to be productive. This is a screensaver for your terminal.

Compatible with macOS, Linux, WSL. Zero dependencies.

## License

MIT
