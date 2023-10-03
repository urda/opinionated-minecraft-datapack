# Build the zip File

## Generic `zip` command

```bash
zip -r UrdaCraft.zip . -x ".*" -x "__MACOSX" -x "*.DS_Store"
```

# Installing the datapack to a ...

## Local Save

TBD

## Multiplayer Server

```bash
rsync UrdaCraft.zip mc.urda.com:/urda/multicraft/servers/urdaworld/urdaworld_2021/datapacks/UrdaCraft.zip
```

# Origins:

- Originally built, and used for `minecraft.urda.com`.
- [Pulled from source.](https://github.com/urda-archives/aws-minecraft/commit/fe1d19371afb3bfda555f7ee9bb216d2c6ee2fcd)
