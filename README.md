# OpinionatedMinecraftDatapack - Vanilla Tweaks Data Pack

**OpinionatedMinecraftDatapack** is an opinionated [Minecraft data pack](https://minecraft.wiki/w/Data_pack).
Anyone who knows anything about Urda will know how much they love simple, vanilla Minecraft.

Supports Minecraft: Java Edition 26.3. Manual singleplayer tests verified all five recipes and all six advancements.

## What This Data Pack Adds

This data pack makes Minecraft: Java Edition work the way I prefer.

- Get an Elytra earlier in survival play.
- Turn rotten flesh into leather.
- Turn gravel into stone.
- Turn coarse dirt into dirt.
- Split melon blocks back into slices.

A custom advancement tab guides players toward each recipe.

# Building the data pack...

```bash
make build
```

# Installing the data pack to a ...

## Local Save

### ... on macOS

```
mv OpinionatedMinecraftDatapack.zip ~/Library/Application\ Support/minecraft/saves/{WORLD NAME}/datapacks/
```

## Multiplayer Server

Place the built data pack into the server's `datapacks` folder:

```bash
rsync OpinionatedMinecraftDatapack.zip host.tld:/path/to/server/datapacks/OpinionatedMinecraftDatapack.zip
```

# Credits and References

- Visit my website at [Urda.com](https://urda.com) anytime.
- Follow me at [@Urda@Urda.social](https://urda.social/@urda) on Mastodon.
