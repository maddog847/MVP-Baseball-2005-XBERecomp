# MVP Baseball 2005 — XBE Recomp

Unofficial native Windows recompilation of the original Xbox version of MVP Baseball 2005. Public beta; original game files required.

Built using [XboxXBERecomp](https://github.com/TGP482/XboxXBERecomp) by [TGP482](https://github.com/TGP482).

## Public Beta

Gameplay, saving/loading, and audio have been tested. Bugs may remain, and compatibility with all hardware and game modes is not guaranteed.

Further development and ongoing support are not currently planned. Community forks and improvements are welcome under the included licenses.

## Installation

This project does not include game files. You must provide files from your own legally acquired original Xbox copy of MVP Baseball 2005.

1. Download the playable package from [Releases](https://github.com/maddog847/MVP-Baseball-2005-XBERecomp/releases).
2. Extract the entire ZIP to a writable folder.
3. Place your extracted Xbox game files in the `assets` folder, with `default.xbe` directly inside it alongside the remaining game files and folders.
4. Run `MVP05.exe`.

Keep the supplied DLLs and settings file beside the executable. The PlayStation 2 and original PC versions are not compatible.

## Settings

Close the game before editing `mvp05-settings.toml`.

- Adjustable output resolution and render scale.
- Windowed and borderless display modes.
- Widescreen support and anisotropic filtering.
- Alt+Enter or F11 toggles windowed/borderless mode.
- Save data is stored in `UDATA` on the emulated Xbox E: drive, inside the local `hdd` folder. Back up your `hdd` folder before upgrading.

If performance is poor, try `render_percent = 100`.

## Source

The Source-Build package is for users who want to modify or rebuild the project. Follow its included build instructions.

Keep all applicable license and third-party notices when redistributing.

This is an unofficial community project and is not affiliated with or endorsed by EA or Microsoft.
