# Module Requirements

Openlands NeoForge Edition consumes `-neoforge.jar` artifacts.

## Required

- `echocore`
- `echonetcore`
- `echoadaptercore`
- `echocontentcore`
- `echoworldcore`
- `echorecipecore`
- `echobiomecore`
- `echostructurecore`
- `echocreaturecore`
- `echofoundationcore`
- `echomaterialcore`
- `echotoolcore`
- `echostationcore`
- `echoworldstarter`
- `echocommonloot`
- `echocreatureroles`
- `echoprogressioncore`
- `echoassetcore`
- `echoopenlandsprotocol`

## Required NeoForge Guarantees

- Echo IDs remain the source of truth.
- NeoForge output contains generated Openlands data, not copied Minecraft identity.
- All Openlands blocks, items, recipes, loot, biomes, structures, creatures, waystones, tutorial triggers, and map data match the conformance registry.

## Runtime Evidence

NeoForge builds must consume `data/echoopenlandsprotocol/openlands/systems/runtime_adapter_load_plan.json` and report every required adapter phase: `discover`, `load_data`, `register_content`, `bind_worldgen`, `bind_gameplay_state`, `ready`, and `release_gate`.

NeoForge-specific generated identifiers are allowed only as adapter output. Release evidence must still prove Echo IDs remain authoritative and no Minecraft-owned names, textures, silhouettes, recipe identity, or branding were introduced by generated resources.

NeoForge driver-surface implementation status must follow `data/echoopenlandsprotocol/openlands/systems/harness_driver_manifest_contract.json`; the current template lives at `evidence/neoforge-harness-driver-manifest.template.json` and intentionally lists every real harness driver as missing.

The detailed evidence checklist lives in `docs/runtime-evidence.md`.
