# Black Tide — play it

**https://nideeshsrivatsavan.github.io/black-tide-play/**

A pirate game in the browser: captain a brigantine out of Nassau in 1716, fight sea monsters from every
mythology (the Kraken, Leviathan, Scylla and Charybdis, the Hydra, Umibōzu, the Lusca…) with cutlass,
pistols and broadsides, and trade with the peoples of four other islands.

This repository holds only the compiled game that GitHub Pages serves; there is no source here.

## What you need

- A browser with **WebGPU**: a recent Chrome or Edge on a desktop or laptop (Safari and Firefox are
  adding it). Phones and tablets are not supported: it needs a keyboard and mouse.
- A reasonable graphics card. The picture scales its resolution down on slower machines.
- Patience on the first visit: it compiles several hundred shaders, which can take a minute or two.
  Later visits are faster.

## Controls

Click the view to capture the mouse (Esc releases it). **F1** shows every control.

| Key | Action |
|---|---|
| W A S D | Walk · at the helm: W/S set and take in sail, A/D steer |
| E | Board, take the helm, trade, douse a fire, speak to a mermaid |
| 1 – 5 | Cutlass, pistols, musket, blunderbuss, grenadoes |
| Left / right mouse | Attack / aim or parry · at the helm, look over a side and click to fire the broadside |
| J / M | Journal of beasts / sea chart |

Your voyage saves in the browser as you go.

## Credits

Built on [Tidewater](https://github.com/dgreenheck/tidewater) by Dan Greenheck (MIT). See `LICENSE` and
`CREDITS.md` for the licences of the code and the third-party assets.
