## Wall Hitboxes 1.0.0

Client-side Minecraft Java 26.3 mod that renders entity hitboxes through walls.

### Downloads

- **Fabric:** `wallhitboxes-1.0.0-fabric.jar`
- **Forge:** `wallhitboxes-1.0.0-forge.jar`

Install only the jar that matches your mod loader. Do not use both at the same time.

### What you need

- Minecraft Java 26.3
- Fabric:
  - Fabric Loader 0.20.1+ — <https://fabricmc.net/use/installer/>
  - Fabric API 0.167.0+26.3 — <https://modrinth.com/mod/fabric-api>
- Forge:
  - Minecraft Forge 66.1.9 — <https://files.minecraftforge.net/>
  - No additional API mod required.

### How to install

1. Install the mod loader for Minecraft 26.3.
2. Download the matching jar from this release.
3. Put the jar into the `mods` folder.
4. Start Minecraft with that mod loader profile.

### Controls

- `H` — toggle hitboxes on/off.
- `M` — open settings.
- Square gear button in the pause menu — open settings.

### Settings

- Players, hostile mobs, passive mobs, other entities
- Eye line
- Look direction arrow
- Ender Dragon parts
- Render distance: 16 / 32 / 64 / 128 / 256 blocks

Settings are saved to `config/wallhitboxes.json`.

### Building from source

Java 25 is required: <https://adoptium.net/>

```bat
.\\gradlew.bat build
```
