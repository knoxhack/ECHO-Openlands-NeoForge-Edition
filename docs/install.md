# Install

NeoForge install uses ECHO Launcher after artifacts are approved.

## Expected Flow

1. Launcher resolves `openlands-neoforge-edition`.
2. Launcher installs or verifies the supported NeoForge profile.
3. Launcher downloads `-neoforge.jar` module artifacts.
4. Launcher verifies SHA-256 checksums.
5. Launcher starts the NeoForge profile with generated Openlands data/assets.

## Required Before Public Install

- `echoopenlandsprotocol-0.1.0-neoforge.jar` exists.
- `META-INF/echo.mod.json` and `META-INF/neoforge.mods.toml` are packaged.
- Generated resource/data output contains no copied Minecraft assets.
- Runtime behavior matches Native and Standalone Openlands IDs.

