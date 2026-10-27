# MineTune Installation Guide

## 1. Choose the right file

Open the [MineTune repository](https://github.com/pocn98/MineTune) and choose the JAR under the folder matching your Minecraft version and mod loader.

Uploaded folder labels:

- `1.21.11 (Fabric)`
- `1.8.9 (Forge)`
- `26.3 (fabrc)`

The folder label alone does not prove compatibility. If a build fails to load, check the JAR's metadata and its release notes before trying again.

## 2. Install

1. Close Minecraft and the launcher.
2. Install the mod loader required by the selected build.
3. Download only the MineTune JAR intended for that Minecraft version and loader.
4. Place the JAR in that Minecraft instance's `mods` folder.
5. Install any dependencies specified for that build.
6. Launch the matching Minecraft profile.

Do not put multiple MineTune builds for different Minecraft versions in the same instance.

## 3. Add music

The metadata in the inspected 1.0.0 Fabric build describes local music-file support for MP3, OGG, and WAV files. Follow the in-game instructions for your specific build and keep a backup of your music files.

## 4. Troubleshooting

- Confirm the Minecraft version, loader, and MineTune build match.
- Remove duplicate or outdated MineTune JARs from the instance's `mods` folder.
- Check the Minecraft log or crash report for the first relevant error.
- Report the issue on [GitHub Issues](https://github.com/pocn98/MineTune/issues).

Please include the exact build filename, Minecraft version, loader/version, and relevant error text. Never post passwords or account tokens.
