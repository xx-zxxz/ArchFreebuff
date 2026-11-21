# archfreebuff

Freebuff For arch! (x86_64)

current: upstream **0.0.204** (CodebuffAI/codebuff-community `freebuff-desktop-v0.0.204`),
repackaged with the wayland desktop-name fix baked in (`CHROME_DESKTOP=freebuff.desktop`
exported in AppRun - that's the issue that made the dock icon show as a generic cog).

## grab it

the appimage is in the release - grab `ArchFreebuff.AppImage` from the releases page.

## run it

```bash
chmod +x ArchFreebuff.AppImage
./ArchFreebuff.AppImage
```

if fuse is being difficult this usually does the trick:

```bash
./ArchFreebuff.AppImage --appimage-extract-and-run
```

## checksum

```
e789b4ea0b2ee55620b5c1303be188612860e24c7aeb08b87bd94f7c40fb5bee
```

run `sha256sum ArchFreebuff.AppImage` and it should print that.
