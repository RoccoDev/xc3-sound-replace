# Sound replacement mod for Xenoblade 3
This mod allows you to load custom sound files and sound banks, replacing the game's defaults.

> **Important**: While this mod does not deal with persistent data, you are still using it at your own risk. I am
not responsible for anything that could happen to your saves, game, console, account, etc.

## Usage

#### Switch
1. Download the latest version of the mod from the [Releases](releases/latest) page.
2. Extract the archive to root of your SD card.

#### Ryujinx
1. Download the latest version of the mod from the [Releases](releases/latest) page.
2. Open Ryujinx, then right-click on the game and select "Open Atmosphere Mods Directory".
3. From the archive, extract the `exefs` and `romfs` directory into the folder you opened.

#### Replacing sound files

After installing the mod, you can place `.wem` and `.bnk` files in the `/atmosphere/contents/010074f013262000/romfs/sound` folder.
When the game tries to load those files from the game's original archive, the mod will load the custom ones instead.

## Build instructions
To build the project, install [Rust](https://rustup.rs/) and run
```sh
./build.sh
```

## License
This mod is distributed under the terms of the [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html). See [COPYING](COPYING) for details.
