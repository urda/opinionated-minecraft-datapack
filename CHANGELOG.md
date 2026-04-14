# CHANGELOG

## v0.2 - Pre-Release

- Updated `pack.mcmeta` to new `min_format`/`max_format` array format for Minecraft 26.1.2 (pack format `[101, 1]`).
- Renamed `advancements/` to `advancement/` and `recipes/` to `recipe/` per Minecraft 1.21 directory naming conventions.
- Fixed advancement tab background texture path for Minecraft 1.21+.
- Added `Makefile` with `build`, `clean`, and `help` targets.
- Updated README build instructions to use `make build`.
- Fixed typo in "I'm just going to wing it!" advancement description.
- Fixed missing `minecraft:` namespace prefix on crafting recipe types.
- Changed "I'm just going to wing it!" advancement to gate elytra recipe behind gathering crafting ingredients (feather, redstone block, stick) instead of unlocking immediately from root.
- Changed root advancement to be visible in the advancement tab.
- Added `exclude.lst` for `make build` zip exclusions.
- Removed unnecessary `obfuscated: false` from advancement titles.
- Updated recipe ingredient format from object to plain string for Minecraft 26.x compatibility.
- Changed root advancement title color from `aqua` to `blue` for readability on stone background.
- Verified full end-to-end testing on Minecraft 26.1.2.

## v0.1 - Pre-Release

- The "new" OpinionatedMinecraftDatapack Vanilla Tweaks Data Pack.
- Features:
  - Advancements:
    - "Opinionated Minecraft Data Pack"
      - "Damn. Gravel."
        - "Damn. Coarse Dirt."
      - "I'm just going to wing it!"
      - "Smoke 'Em If You Got 'Em"
      - "Splitting the Melon"
  - Recipes:
    - "Cleanse Rotten Flesh" - Nobody likes rotten flesh, with this you can smelt it into leather.
    - "Craft Elytra" - Build an elytra as you please! Requires "redstone block", "feather", "stick".
    - "Melon Break Up" - You can take a whole "melon" and split it back into slices!
    - "Smelt Coarse Dirt" - Nobody likes coarse dirt, with this you can smelt it into dirt.
    - "Smelt Gravel" - Nobody likes gravel, with this you can smelt it into pure stone.
