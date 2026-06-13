# Update Flow

NeoForge updates replace changed `-neoforge.jar` module artifacts.

## Policy

- Compare manifest module IDs, versions, sizes, and SHA-256 values.
- Download only changed jars.
- Preserve saves, configs, resource packs, screenshots, and local markers.
- Check datafix/migration requirements before opening existing worlds.

## Openlands-Specific Checks

- Echo IDs stay canonical even when converted to NeoForge resource locations.
- Openlands Standard remains the default.
- No Minecraft-derived asset or naming dependency enters the Openlands namespace.

