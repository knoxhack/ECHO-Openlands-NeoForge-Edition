# ECHO Openlands NeoForge Edition

Openlands NeoForge Edition is the Minecraft/NeoForge adapter packaging lane for Openlands.

## Role

- Consumes `-neoforge.jar` artifacts from `ECHO-Modules`.
- Uses `echoopenlandsprotocol` as the canonical Openlands content source.
- Publishes NeoForge install/update/rollback manifests for the ECHO Launcher.
- Adapts Echo IDs into NeoForge data/runtime behavior without making Minecraft content the design source.

## Legal Boundary

NeoForge compatibility does not grant permission to use Minecraft names, copied mob silhouettes, copied textures, copied audio, or copied recipes as Openlands identity.

## Status

Implementation foundation only. Keep preview-only until Openlands data, generated assets, recipes, worldgen, save/load, and waystone state pass parity tests.

## Preview Payload

- `preview-artifacts/echoopenlandsprotocol-0.1.0-neoforge.jar`
- `preview-artifacts/echoopenlandsprotocol-0.1.0-sources.jar`
- `manifests/modpack-index-entry.preview.json`

These files are checked in for repo visibility and handoff review only. They are not approved player-facing release artifacts.
