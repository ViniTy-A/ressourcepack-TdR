# Vanilla Sky — Resource Pack

Auto-published resource pack for the Vanilla Sky Custom skyblock server. Contains
client-side translations (`en_us.json` + `fr_fr.json`) for the custom advancements
defined by the `vanillasky` mod.

The MC server points to `vanillasky-resourcepack.zip` in this repo via its
`resource-pack` setting in `server.properties`. Each rebuild on the server side
re-pushes a new zip here, and clients re-download it on next join.

**Don't edit files here directly** — they're overwritten by `build-resourcepack.py`
in the parent project's `server/` folder. The source of truth is
`mod/src/main/resources/assets/vanillasky/lang/{en_us,fr_fr}.json`.
