# WoT: Onslaught day maps + No fog

Visual-only mod for World of Tanks (EU, game version **2.4.2.0**).

- **No fog** on all maps (`nofog_1.1.0.wotmod`)
- **Day lighting instead of night** on the Onslaught night maps, also without fog:
  Desert, Sweden, Last Frontier, Steppes (`onslaught_day_*.wotmod`)

Nothing about the map geometry, gameplay or UI is changed. It only swaps lighting/fog settings.

## Download

**[Download everything as ZIP](https://github.com/kamilskwierczynski1/wot-onslaught-day-nofog/archive/refs/heads/main.zip)**. Unzip it; the 5 `.wotmod` files are in the `mods` folder.

## Install

1. Close the game.
2. **Delete any other fog remover / sky / weather mod.** Check both `mods\<version>\` and `res_mods\<version>\`. Two such mods fight each other, and anything in `res_mods` always wins over `mods`.
3. Delete older versions of this mod (files ending in `_1.0.0.wotmod`).
4. Copy all 5 `.wotmod` files into `<WoT folder>\mods\2.4.2.0\`.
   The exact folder name is in `paths.xml` in your WoT folder, on the line with `./mods/...`.
5. Start the game.

## After a game update

Move the files into the new version folder in `mods\`. If Wargaming reworks a map's lighting, that map goes back to the vanilla look (nothing breaks). In that case, delete that map's file and wait for an update here.

## Not covered

Two Grand Battles maps and one Steel Hunter map.
