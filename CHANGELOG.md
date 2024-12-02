# Changelog

## V1.0.4 - 2/12/2024
## Features:
- `Add Components to Selected Prefab` is now a separate window for more ease of usability.
- Added `Empty` on Prefab Type.
- Renamed ``Components to Add`` to ``Components`` for better user-experience.
### Fixes:
- Fixes the `InvalidOperationException: Collection was modified; enumeration operation may not execute` when removing prefab from the list.

## V1.0.3 - 1/12/2024
## Features:
- Added a feature to disable `Duplicate Prefab` on the first prefab created on the list. [Issue #4](https://github.com/haruchanz64/PrefabGenerator/issues/4)
- Rename `Copy Components From Last Prefab` to `Duplicate Prefab` for better user experience. [Issue #3](https://github.com/haruchanz64/PrefabGenerator/issues/3)

## Fixes:
- Fixes the issue wherein scrollbar is missing entirely when multiple prefabs is created. [Issue #2](https://github.com/haruchanz64/PrefabGenerator/issues/2)

## V1.0.2 - 30/11/2024
### Fixes:
- Fixed the issue wherein copied prefab components is not saved properly. [Issue #1](https://github.com/haruchanz64/PrefabGenerator/issues/1)
- Fixed the issue wherein saving multiple prefabs only saves the first prefab on the list.

## V1.0.1 - 29/11/2024 (Quick Patch)

### Features:
- Added the ability to copy components from the initial prefab created.
- Added the ability to remove individual components added from the prefab.
- Automatically resets `prefabConfigs` after creating prefabs when clicking **Generate All Prefabs**.

### Fixes:
- Fixed the issue where duplicate components could be added to the prefab.
## v1.0.0 - 29/11/2024

Initial release.
