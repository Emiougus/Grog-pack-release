# GroG! server edition

Downloads for the GroG! datapack, resource pack and Dungeons and Taverns add-on.
Get them from the [releases](https://github.com/Emiougus/Grog-pack-release/releases); the latest is below.

GroG! server edition 1 for Minecraft 26.3. Nothing to install on clients.

| File | What it is |
|---|---|
| `grog-datapack.zip` | Goes in `<world>/datapacks/` |
| `grog-resourcepack.zip` | Pushed to players by the server (below) |
| `grog-dnt-addon.zip` | Optional: grog on Dungeons and Taverns 6.0.1 tables. Load it **after** DnT |

### server.properties

```properties
resource-pack=https://github.com/Emiougus/Grog-pack-release/releases/download/pack-v1/grog-resourcepack.zip
resource-pack-sha1=04de69cbfa309caa6166a3df43aeac8befa3bf39
require-resource-pack=true
```

To always serve the newest resource pack, use the rolling link instead:
https://github.com/Emiougus/Grog-pack-release/releases/download/resourcepack-latest/grog-resourcepack.zip

Leave out `resource-pack-sha1` if you use the rolling link, because the file changes with every release.
