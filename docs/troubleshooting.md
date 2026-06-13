# Troubleshooting

## Pack Fails During NeoForge Startup

- Verify all required jars are present.
- Verify `META-INF/neoforge.mods.toml` exists for NeoForge artifacts.
- Verify generated registry names match Echo IDs from `echoopenlandsprotocol`.

## Missing Textures Or Sounds

- Confirm generated asset paths use `assets/echoopenlandsprotocol`.
- Confirm placeholders are not marked public-ready.
- Confirm no external copyrighted assets were imported.

## Recipe Or Block Mismatch

- Compare generated NeoForge data against `openlands/conformance/openlands_mvp_registry.json`.
- Verify adapters normalize local and namespaced IDs consistently.

