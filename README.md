# Pink Wall — Web Showcase

A browser-based showcase for [Pink Wall](https://github.com/LucianoCSiqueira/pinkwall), a Super Nintendo (SNES) homebrew game by BrunoRNS and Luciano C. Siqueira.

This project allows visitors to play Pink Wall directly in their web browser using [EmulatorJS](https://emulatorjs.org/) and the bsnes emulation core.

## Features

- Play Pink Wall directly in your browser.
- SNES emulation powered by bsnes.
- No separate emulator installation required.
- Simple, browser-based gaming experience.

## How It Works

The showcase uses EmulatorJS to run the game in the browser. EmulatorJS and its emulation core files are loaded from the EmulatorJS CDN.

The current configuration uses the `nightly` CDN channel because the required bsnes core assets were unavailable through the `stable` channel during testing.

Nightly builds may change without notice and can introduce bugs or compatibility issues.

## Original Game

Pink Wall is an independent SNES homebrew project.

- **Authors:** [BrunoRNS](https://github.com/BrunoRNS) and [Luciano C. Siqueira](https://github.com/LucianoCSiqueira)
- **Original source code and game:** [github.com/LucianoCSiqueira/pinkwall](https://github.com/LucianoCSiqueira/pinkwall)
- **License:** GNU General Public License v3.0 (GPL-3.0), as specified by the original project.

Please refer to the original repository for the game's source code, development history, and licensing information.

## Third-Party Software

This showcase relies on the following projects:

- [EmulatorJS](https://github.com/EmulatorJS/EmulatorJS) — browser-based emulation framework.
- [bsnes](https://github.com/bsnes-emu/bsnes) — Super Nintendo emulation core.
- [EmulatorJS CDN](https://emulatorjs.org/docs/cdn/) — delivery of emulator runtime and core assets.

Each third-party component remains subject to its own license and applicable copyright notices.

## License

The original code written specifically for this showcase is licensed under the **GNU General Public License v3.0 (GPL-3.0)**. See the [`LICENSE`](LICENSE) file for the full license text.

The original Pink Wall game and all third-party components retain their respective copyrights and licensing terms. This repository does not claim ownership of those projects.

## Disclaimer

This is an independent fan-made showcase. It is not affiliated with, endorsed by, or sponsored by Nintendo, EmulatorJS, or the bsnes project.

Super Nintendo Entertainment System (SNES) is a Nintendo product name. All respective trademarks belong to their owners.
