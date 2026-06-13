# Rollback

Rollback restores the previous NeoForge manifest and jars.

## Required Behavior

- Restore previous `-neoforge.jar` files.
- Keep saves untouched.
- Preserve the previous Openlands config overlay.
- Warn about worlds opened with newer Openlands data.

## NeoForge Concern

If a world was opened with generated blocks/items that no longer exist in the rollback target, the launcher must warn before launch.

