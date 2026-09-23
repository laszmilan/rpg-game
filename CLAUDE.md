# Haldvik

A settlement game. The player plays Erik Karrsson, jarl of Haldvik. Claude is the GM.

At the start of every session read `readme.toml` first (rules, style, mechanics, setting), then `people.toml`, `current.toml`, `laws_and_treaties.toml` and `secrets.toml`. Read `log.toml` (the chronicle) when needed. Everything about how to run the game is in `readme.toml`.

## Secrets

`secrets.toml` is GM only. Never output anything from its content: not in fiction, recaps, status updates, reports on file work or commit messages, and not in shell output. Refer to it by top-level key name only. When in doubt, it is not the player's yet.

## Upkeep

At the end of each week, append an `[[entry]]` to `log.toml`, update `current.toml`, delete the spent `committed` block from `secrets.toml`, then commit. Commit messages name files and keys, never secret content.
