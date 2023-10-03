# Build the zip File

```bash
zip -r UrdaCraft.zip . -x ".*" -x "__MACOSX" -x "*.DS_Store"
```

# Sending to Server

```bash
rsync UrdaCraft.zip mc.urda.com:/urda/multicraft/servers/urdaworld/urdaworld_2021/datapacks/UrdaCraft.zip
```
