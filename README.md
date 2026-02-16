# alt:V Trainer

`altv-trainer` is a TypeScript trainer resource for [alt:V](https://altv.mp/#/) built on [NativeUI](https://github.com/DurtyFree/alt-V-NativeUI).
It was designed for fast in-game iteration: testing player, vehicle, weapon, and world behavior without custom one-off scripts.

Some highlights:

- modular menu architecture (base abstractions + focused submenus)
- strong typing around alt:V natives and game constants
- clean separation between client and server modules
- lightweight Rollup + TypeScript build pipeline

It is intentionally a trainer/debug utility, not an admin system.

## Install

- [Download the latest release](https://github.com/Jayreen58/altv-trainer/releases/latest)
- Move the extracted resource into `yourserverfolder/resources`
- Add `trainer` to your `server.cfg`
- Press `M` in game to open the menu

Developed and tested on `release build #1286`.

## Contributing

- [Open an issue](https://github.com/Jayreen58/altv-trainer/issues)
- [Submit a pull request](https://github.com/Jayreen58/altv-trainer/pulls)

## Credits

- [@DurtyFree](https://github.com/DurtyFree) for [NativeUI](https://github.com/DurtyFree/alt-V-NativeUI)
