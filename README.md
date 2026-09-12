# ExCraft resource pack

Resource pack for the ExCraft Minecraft server (Paper 26.2).

## Contents

| Path | What it is |
|---|---|
| `pack.mcmeta` | Pack metadata, `pack_format` 88 (Minecraft 26.2) |
| `pack.png` | Pack icon shown in Options → Resource Packs |
| `assets/minecraft/font/excraft.json` | Custom font `excraft`, separate from the vanilla default font |
| `assets/minecraft/textures/font/excraft_logo.png` | EXCRAFT logo, mapped to `U+E000` |

The logo lives in its own font rather than overriding `default.json`, so vanilla
text rendering is untouched. Render it with MiniMessage:

```
<font:minecraft:excraft>&#xE000;</font>
```

## Releases

Built archives are published under [Releases](../../releases). The server
references the archive by URL plus its SHA-1, so a rebuilt pack must be
re-uploaded and the server's `resource-pack-sha1` updated together.
