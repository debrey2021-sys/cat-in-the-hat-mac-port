# Cat in the Hat: Mac Port

**Play the 2003 Xbox game *The Cat in the Hat* natively on an Apple Silicon Mac.** It runs in true widescreen at up to 4x the original resolution, with HD textures and a modern controller, and needs no emulator.

<!-- Hero screenshot goes here: docs/images/hero.jpg (the house's hall, widescreen, HD) -->

> This is an unofficial fan project and an **early test build**. It contains no part of the game. **You need your own copy of the Xbox disc.** The app builds the game from it, on your Mac, in about a minute.

### [⬇ Download for Mac](https://github.com/debrey2021-sys/cat-in-the-hat-mac-port/releases/latest/download/Cat-in-the-Hat-Mac-Port.dmg)

*Apple Silicon (M1 or newer), macOS 13 or later. About 190 MB. Signed and notarised by Apple.* All versions are on the [releases page](../../releases).

---

## What you get

<!-- Before/after picture goes here: docs/images/before-after.jpg (Xbox look on the left, this port on the right) -->

- **Sharp picture.** Up to 4x the Xbox's resolution, sharp on Retina screens.
- **True widescreen.** The camera shows more at the sides, and the menus and HUD stay in proportion.
- **Better lighting.** Soft shadows, ambient shading, a light glow, and rippling water in Trouble Bath.
- **HD textures.** An optional 1.4 GB download inside the app, switched on automatically.
- **Any controller.** DualSense, DualShock 4, Xbox and Switch Pro pads, over USB or Bluetooth, or the keyboard.
- **Mac comforts.** The company logos are skipped, the game pauses when you switch to another app, and your saves stay on your Mac.

## How to set it up

1. **Download** the disk image above, open it, and drag the app into Applications.
2. **Open the app.** If macOS asks whether to open something downloaded from the internet, click **Open**.
3. **Add your disc.** Drag your Xbox disc image (`.iso`) onto the app's window. The app checks that it's the right disc, then builds the game. This takes about a minute.
4. **Get HD (optional).** Click **Download HD** for the HD textures (1.4 GB), or **Play now** to start straight away. You can play while it downloads.
5. **Press Play.**

After that, just open the app and press Play.

## What you need

| | |
|---|---|
| **Mac** | Apple Silicon (M1 or newer), macOS 13 Ventura or later |
| **Game** | Your own disc image of *The Cat in the Hat* for the **original Xbox** (`.iso`, about 1.7 GB) |
| **Space** | About 5 GB |
| **Internet** | Only for the optional HD download. The game itself never goes online |
| **Controller** | Recommended, but not required |

## Good to know

- The app starts a new game with its own saves.
- Settings are in the same window as the Play button, on the VIDEO and GAME tabs. Controls can be changed on the INPUT tab.
- The SYSTEM LINK tab does nothing for this game.
- The game's movies play in their original quality.
- **Alt+Enter** toggles full screen, and **F9** shows the frame rate.

## Questions

**Where do I get a disc image?**
Make it from your own disc. This project doesn't provide the game and won't link to copies of it.

**The app says it doesn't recognise my disc.**
So far it knows one version of the disc. [Open a "My disc isn't recognised" issue](../../issues/new/choose) with what the app shows. Adding a version is usually quick.

**Does the PC or PlayStation 2 version work?**
No. Those are different games. This port needs the original Xbox version.

**Intel Macs? Windows? Linux?**
Not in this release. It's built and tested on Apple Silicon Macs only.

**Is it safe to open?**
Yes. The app is signed with a Developer ID and notarised by Apple, so macOS opens it normally. It doesn't upload anything.

**Something looks or sounds wrong.**
Press **F11** while it's on screen, then [open a bug report](../../issues/new/choose) and attach the files it saves.

## How it works

The game isn't emulated. The app carries [Recompose](https://github.com/Joshspeakman/recompose), a static recompiler for original Xbox games. The first time you open the app, it translates the game's program from your disc into native Apple Silicon code and builds it on your Mac. The graphics run on Metal, and the sound runs on a model of the Xbox's own sound chip, so 3D sound is mixed the way the console mixed it.

## Helping out

Testing other versions of the disc and reporting bugs helps the most. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Credits and licence

Built with [Recompose](https://github.com/Joshspeakman/recompose) by [Joshspeakman](https://github.com/Joshspeakman), which is licensed under GPL-3.0; the app carries its licence and notices. The HD textures were made with open upscaling models, whose authors and licences are listed in [CREDITS.md](CREDITS.md).

*The Cat in the Hat*, its characters and the game belong to their respective owners. This project is not affiliated with or endorsed by them.
