# Pilot Light development assets

Editable development scenes and their supporting assets. These files are the source of truth; no scene-generation step is required.

The repository contains 12 showcase scenes, 10 focused regression scenes, and all referenced meshes, materials, textures, environments, renderer settings, and animation clips. The coast scene retains its generated island mesh.

## Using the assets

Place or clone this repository at `pilotlight/assets/dev`. Keep Pilot Light’s existing `/assets` mount pointing to `pilotlight/assets`; references within this repository use `/assets/dev/...`. For example, the material showcase is `/assets/dev/scenes/showcase_01_materials.plscene`.

When running from `pilotlight/out`, these scenes are physically located at `../assets/dev/scenes`. Scene menus that only enumerate `../assets/scenes` will need to include that directory to list the development scenes.

The camera script is supplied by Pilot Light (`pl_script_camera`). No external models or textures are required.

## Scenes

- `scenes/showcase_01_materials.plscene`
- `scenes/showcase_02_lighting.plscene`
- `scenes/showcase_03_indirect.plscene`
- `scenes/showcase_04_decals.plscene`
- `scenes/showcase_05_probes.plscene`
- `scenes/showcase_06_water.plscene`
- `scenes/showcase_07_coast.plscene`
- `scenes/showcase_08_shadows.plscene`
- `scenes/showcase_09_glass.plscene`
- `scenes/showcase_10_corridor.plscene`
- `scenes/showcase_11_motion.plscene`
- `scenes/showcase_12_ao.plscene`
- `scenes/showcase_regression_cluster_deferred_distributed.plscene`
- `scenes/showcase_regression_cluster_deferred_overflow.plscene`
- `scenes/showcase_regression_cluster_deferred_sparse.plscene`
- `scenes/showcase_regression_cluster_forward_distributed.plscene`
- `scenes/showcase_regression_cluster_forward_overflow.plscene`
- `scenes/showcase_regression_cluster_forward_sparse.plscene`
- `scenes/showcase_regression_shadow_direction.plscene`
- `scenes/showcase_regression_shadow_point.plscene`
- `scenes/showcase_regression_shadow_spot.plscene`
- `scenes/showcase_regression_shadow_sun.plscene`
