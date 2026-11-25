# Wall Hitboxes

A client-side Minecraft Java 26.3 mod that shows entity hitboxes through blocks, similar to F3+B but visible through walls.

Two builds are included:

- `wallhitboxes-1.0.0-fabric.jar` — Fabric version
- `wallhitboxes-1.0.0-forge.jar` — Forge version

Use **only one** of them, matching the mod loader you run. Do not put both jars in `mods` at the same time.

## Features

- Draws hitboxes for players, hostile mobs, passive mobs, and other entities (items, arrows, etc.).
- Hitboxes are always visible through blocks.
- Color-coded entity categories.
- Optional eye-line and look-direction arrows.
- Optional Ender Dragon part hitboxes.
- Adjustable render distance.
- Settings persist in `config/wallhitboxes.json`.
- The UI follows the Minecraft game language.

## Controls

- `H` — toggle hitboxes on/off.
- `M` — open settings.
- Pause menu — click the square gear button on the right side to open settings.

## Installation

### Fabric

1. Install Minecraft Java 26.3.
2. Install Fabric Loader 0.20.1 or newer: <https://fabricmc.net/use/installer/>
3. Install Fabric API `0.167.0+26.3` or newer: <https://modrinth.com/mod/fabric-api>
4. Copy `wallhitboxes-1.0.0-fabric.jar` into the `mods` folder.
5. Start the game with the Fabric profile.

### Forge

1. Install Minecraft Java 26.3.
2. Install Minecraft Forge `66.1.9`: <https://files.minecraftforge.net/>
3. Copy `wallhitboxes-1.0.0-forge.jar` into the `mods` folder.
4. Start the game with the Forge profile.

No extra API mod is required for the Forge version.

## Building from source

Java 25 is required to build both projects: <https://adoptium.net/>

```bat
cd fabric
.\\gradlew.bat build

cd ..\\forge
.\\gradlew.bat build
```

The finished jars will be in `fabric/build/libs` and `forge/build/libs`.

## Notes

This is a client-side visual mod. It does not change entity hitboxes on the server and does not give any gameplay advantage beyond seeing the same hitboxes through walls.
