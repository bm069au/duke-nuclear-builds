# Duke Nuclear Edition — public build backup

Backup dated 22 October 2026. Existing executable and installer last modified 20 October 2026, copied without rebuilding or running them.

Source: https://github.com/bm069au/jfduke3d/tree/msvc-compat (checkpoint e02211e).
Modified engine: https://github.com/bm069au/jfbuild/tree/duke-nuclear-2026-10-22 (checkpoint 72c7a8d).
Use git clone --recurse-submodules for the complete pinned source tree.

GitHub Release backup-2026-10-22 contains:
- Duke3D_Nuclear_Edition_Setup.exe — existing installer.
- duke3d.exe — existing compiled game executable.
- Duke-Nuclear-Portable-2026-10-22.zip — executable, locally owned base game data, converted nuclear/weapon assets and GPL notice. Extract together; requires a compatible Windows runtime already present.
- BUILD-MANIFEST.json and SHA256SUMS.txt — exact local sizes/dates/hashes.

This public package includes original game/media files and converted assets. The source code is maintained in the repositories linked above. Configuration, savegames, logs, caches and build intermediates are excluded. The old upstream installer/jfduke3d.nsi is not a verified recipe for the new installer; its modern source recipe was not located. Source-to-binary equivalence and fresh gameplay acceptance were not tested during this backup.
