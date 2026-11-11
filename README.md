# Atelier PS5 Mods

English patches, an optional Resleriana character menu, and optional 120Hz patches for jailbroken PS5 consoles. Use the matching title ID and loose-file game build.

## Atelier Resleriana — PPSA26791

**[Download the Final Mod Pack](https://github.com/tanner02/atelier-mods/releases/download/resleriana-english-v1/Resleriana-PPSA26791-Final-Mod-Pack.zip)** — English patch plus optional character menu and 120Hz layers, together in one archive.

Fully close the game and back up the original files before installing. For each selected folder below, copy its **contents** into the game root containing `eboot.bin`, merging folders and overwriting files. Do not copy the numbered wrapper folders themselves. Fully relaunch the game afterward.

Install in this order:

1. **`01 English Patch` — first.** Stop here for English only.
2. **`02 Optional Character Menu` — second, if wanted.** Adds an R3 character selector with 29 characters and the console-confirmed execute-only-memory crash and walking/running idle fixes. You may stop here: English and the character menu do not require the 120Hz patch.
3. **`03 Optional 120Hz - INSTALL LAST` — last, if wanted.** Choose **one** folder and copy its contents into the game root:
   - **`A English Only`** if you skipped the character menu.
   - **`B With Character Menu`** if you installed the character menu.

Do not install both 120Hz variants or apply older patch archives after these layers. A compatible 120Hz display and working [ps-patch-system](https://github.com/illusionyy/ps-patch-system) setup are required for 120Hz output; 120Hz output does not guarantee 120 FPS.

**Already installed an older 120Hz patch?** Skipping step 3 does not remove it. Restore your clean game backup first, then install English and, optionally, the character menu to return to normal performance settings. Restore your backed-up original files to uninstall the mods.

### Individual downloads

The existing releases remain available. Apply the same order: **English first → optional character menu second → optional 120Hz last**.

| Download | Installation |
| --- | --- |
| [English patch](https://github.com/tanner02/atelier-mods/releases/tag/resleriana-english-v1) | Install first; copy the patch contents into the game root. |
| [Character menu](https://github.com/tanner02/atelier-mods/releases/tag/resleriana-character-menu-v1) | Install after English. Copy `Media` and `ampr_emu.index` from the archive root into the game root; there is no wrapper folder. Includes the 29-character menu and execute-only-memory crash and walking/running idle fixes. |
| [120Hz patch](https://github.com/tanner02/atelier-mods/releases/tag/resleriana-120hz-v1) | Install last. Choose the English-only or character-menu variant to match your installation, then copy that folder's **contents** into the game root. Do not copy both variants. |

## Atelier Ryza DX

| Game | Title ID | Download |
| --- | --- | --- |
| Atelier Ryza DX | `PPSA30304` | [English + 120Hz](https://github.com/tanner02/atelier-mods/releases/tag/ryza1-dx-v1) |
| Atelier Ryza 2 DX | `PPSA31215` | [English + 120Hz](https://github.com/tanner02/atelier-mods/releases/tag/ryza2-dx-v1) |
| Atelier Ryza 3 DX | `PPSA31217` | [English + 120Hz](https://github.com/tanner02/atelier-mods/releases/tag/ryza3-dx-v1) |

Fully close the game and back up the original files. Open the matching `PPSA…-English-Patch` folder and copy its **contents** into the game root containing `eboot.bin`, merging folders and overwriting files. Do not copy the wrapper folder itself. Fully relaunch afterward. Follow the release notes for the 120Hz setup.