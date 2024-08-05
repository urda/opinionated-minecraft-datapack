# OpinionatedMinecraftDatapack - Vanilla Tweaks Data Pack

**OpinionatedMinecraftDatapack** is an opinionated [Minecraft data pack](https://minecraft.wiki/w/Data_pack).
Anyone who knows anything about Urda will know how much they love simple, vanilla Minecraft.

# Building the data pack...

## Generic `zip` command

```bash
zip -r OpinionatedMinecraftDatapack.zip . -x ".*" -x "__MACOSX" -x "*.DS_Store" -x "LICENSE" -x "CHANGELOG.md" -x "README.md"
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
