# Hold To Attack

**Hold To Attack** is a client-side Fabric mod for Minecraft 1.21.11. Hold the attack button and the mod automatically attacks whenever the attack cooldown is fully charged.

## Features

- Automatically attacks when the attack cooldown reaches 100%.
- Optional target requirement to prevent swinging at empty space.
- Enable/disable the feature and configure target requirements through Cloth Config.
- Optional Mod Menu integration for quick access to settings.

## Compatibility

| Component | Version |
| --- | --- |
| Minecraft | 1.21.11 |
| Mod loader | Fabric |
| Java | 21 or newer |
| Fabric API | 0.141.1+1.21.11 |
| Cloth Config | 21.11.153+fabric |
| Mod Menu | 17.0.1 (optional) |

## Build

Install JDK 21, then run:

```bash
./gradlew clean build
```

The distributable Fabric mod JAR is generated under `fabric/build/libs/`. The development JAR is marked with `-dev`; use the remapped JAR for your game.

## Project layout

- `common/` — shared configuration and mixin logic.
- `fabric/` — Fabric entrypoint and Mod Menu integration.

## License

CC-BY-4.0
