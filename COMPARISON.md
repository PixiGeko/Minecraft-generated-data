## Comparison with [21w44a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w44a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">21w44a</th><th>1.18-pre1</th></tr><tr><td>World version</td><td><code>2845</code></td><td><code>2847</code></td></tr><tr><td>Protocol version</td><td><code>1073741872</code></td><td><code>1073741873</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
- worldgen/decorator.txt
+ worldgen/placement_modifier_type.txt
```

</details>




<details>
<summary>
block_predicate_type.txt
</summary>

```diff
+ minecraft:inside_world_bounds
+ minecraft:solid
```

</details>







<details>
<summary>
height_provider_type.txt
</summary>

```diff
+ minecraft:weighted_list
```

</details>






























<details>
<summary>
worldgen/feature.txt
</summary>

```diff
- minecraft:decorated
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
- universal_tags/worldgen/decorator.json
+ universal_tags/worldgen/placement_modifier_type.json
```

</details>










<details>
<summary>
universal_tags/block_predicate_type.json
</summary>

```diff
+ minecraft:inside_world_bounds
+ minecraft:solid
```

</details>







<details>
<summary>
universal_tags/height_provider_type.json
</summary>

```diff
+ minecraft:weighted_list
```

</details>






























<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:decorated
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.adventure.play_jukebox_in_meadows.description: Make the Meadows come alive with the sound of music from a jukebox
+ advancements.adventure.play_jukebox_in_meadows.title: Sound of Music
- advancements.husbandry.play_jukebox_in_meadows.description: Make the Meadows come alive with the sound of music from a jukebox
- advancements.husbandry.play_jukebox_in_meadows.title: Sound of Music
+ generator.amplified.info: Notice: Just for fun! Requires a beefy computer.
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
generated
</summary>

```diff
- reports/biomes/badlands.json
- reports/biomes/bamboo_jungle.json
- reports/biomes/basalt_deltas.json
- reports/biomes/beach.json
- reports/biomes/birch_forest.json
- reports/biomes/cold_ocean.json
- reports/biomes/crimson_forest.json
- reports/biomes/dark_forest.json
- reports/biomes/deep_cold_ocean.json
- reports/biomes/deep_frozen_ocean.json
- reports/biomes/deep_lukewarm_ocean.json
- reports/biomes/deep_ocean.json
- reports/biomes/desert.json
- reports/biomes/dripstone_caves.json
- reports/biomes/end_barrens.json
- reports/biomes/end_highlands.json
- reports/biomes/end_midlands.json
- reports/biomes/eroded_badlands.json
- reports/biomes/flower_forest.json
- reports/biomes/forest.json
- reports/biomes/frozen_ocean.json
- reports/biomes/frozen_peaks.json
- reports/biomes/frozen_river.json
- reports/biomes/grove.json
- reports/biomes/ice_spikes.json
- reports/biomes/jagged_peaks.json
- reports/biomes/jungle.json
- reports/biomes/lukewarm_ocean.json
- reports/biomes/lush_caves.json
- reports/biomes/meadow.json
- reports/biomes/mushroom_fields.json
- reports/biomes/nether_wastes.json
- reports/biomes/ocean.json
- reports/biomes/old_growth_birch_forest.json
- reports/biomes/old_growth_pine_taiga.json
- reports/biomes/old_growth_spruce_taiga.json
- reports/biomes/plains.json
- reports/biomes/river.json
- reports/biomes/savanna_plateau.json
- reports/biomes/savanna.json
- reports/biomes/small_end_islands.json
- reports/biomes/snowy_beach.json
- reports/biomes/snowy_plains.json
- reports/biomes/snowy_slopes.json
- reports/biomes/snowy_taiga.json
- reports/biomes/soul_sand_valley.json
- reports/biomes/sparse_jungle.json
- reports/biomes/stony_peaks.json
- reports/biomes/stony_shore.json
- reports/biomes/sunflower_plains.json
- reports/biomes/swamp.json
- reports/biomes/taiga.json
- reports/biomes/the_end.json
- reports/biomes/the_void.json
- reports/biomes/warm_ocean.json
- reports/biomes/warped_forest.json
- reports/biomes/windswept_forest.json
- reports/biomes/windswept_gravelly_hills.json
- reports/biomes/windswept_hills.json
- reports/biomes/windswept_savanna.json
- reports/biomes/wooded_badlands.json
+ reports/worldgen/minecraft/dimension_type/overworld_caves.json
+ reports/worldgen/minecraft/dimension_type/overworld.json
+ reports/worldgen/minecraft/dimension_type/the_end.json
+ reports/worldgen/minecraft/dimension_type/the_nether.json
+ reports/worldgen/minecraft/dimension/overworld.json
+ reports/worldgen/minecraft/dimension/the_end.json
+ reports/worldgen/minecraft/dimension/the_nether.json
+ reports/worldgen/minecraft/worldgen/biome/badlands.json
+ reports/worldgen/minecraft/worldgen/biome/bamboo_jungle.json
+ reports/worldgen/minecraft/worldgen/biome/basalt_deltas.json
+ reports/worldgen/minecraft/worldgen/biome/beach.json
+ reports/worldgen/minecraft/worldgen/biome/birch_forest.json
+ reports/worldgen/minecraft/worldgen/biome/cold_ocean.json
+ reports/worldgen/minecraft/worldgen/biome/crimson_forest.json
+ reports/worldgen/minecraft/worldgen/biome/dark_forest.json
+ reports/worldgen/minecraft/worldgen/biome/deep_cold_ocean.json
+ reports/worldgen/minecraft/worldgen/biome/deep_frozen_ocean.json
+ reports/worldgen/minecraft/worldgen/biome/deep_lukewarm_ocean.json
+ reports/worldgen/minecraft/worldgen/biome/deep_ocean.json
+ reports/worldgen/minecraft/worldgen/biome/desert.json
+ reports/worldgen/minecraft/worldgen/biome/dripstone_caves.json
+ reports/worldgen/minecraft/worldgen/biome/end_barrens.json
+ reports/worldgen/minecraft/worldgen/biome/end_highlands.json
+ reports/worldgen/minecraft/worldgen/biome/end_midlands.json
+ reports/worldgen/minecraft/worldgen/biome/eroded_badlands.json
+ reports/worldgen/minecraft/worldgen/biome/flower_forest.json
+ reports/worldgen/minecraft/worldgen/biome/forest.json
+ reports/worldgen/minecraft/worldgen/biome/frozen_ocean.json
+ reports/worldgen/minecraft/worldgen/biome/frozen_peaks.json
+ reports/worldgen/minecraft/worldgen/biome/frozen_river.json
+ reports/worldgen/minecraft/worldgen/biome/grove.json
+ reports/worldgen/minecraft/worldgen/biome/ice_spikes.json
+ reports/worldgen/minecraft/worldgen/biome/jagged_peaks.json
+ reports/worldgen/minecraft/worldgen/biome/jungle.json
+ reports/worldgen/minecraft/worldgen/biome/lukewarm_ocean.json
+ reports/worldgen/minecraft/worldgen/biome/lush_caves.json
+ reports/worldgen/minecraft/worldgen/biome/meadow.json
+ reports/worldgen/minecraft/worldgen/biome/mushroom_fields.json
+ reports/worldgen/minecraft/worldgen/biome/nether_wastes.json
+ reports/worldgen/minecraft/worldgen/biome/ocean.json
+ reports/worldgen/minecraft/worldgen/biome/old_growth_birch_forest.json
+ reports/worldgen/minecraft/worldgen/biome/old_growth_pine_taiga.json
+ reports/worldgen/minecraft/worldgen/biome/old_growth_spruce_taiga.json
+ reports/worldgen/minecraft/worldgen/biome/plains.json
+ reports/worldgen/minecraft/worldgen/biome/river.json
+ reports/worldgen/minecraft/worldgen/biome/savanna_plateau.json
+ reports/worldgen/minecraft/worldgen/biome/savanna.json
+ reports/worldgen/minecraft/worldgen/biome/small_end_islands.json
+ reports/worldgen/minecraft/worldgen/biome/snowy_beach.json
+ reports/worldgen/minecraft/worldgen/biome/snowy_plains.json
+ reports/worldgen/minecraft/worldgen/biome/snowy_slopes.json
+ reports/worldgen/minecraft/worldgen/biome/snowy_taiga.json
+ reports/worldgen/minecraft/worldgen/biome/soul_sand_valley.json
+ reports/worldgen/minecraft/worldgen/biome/sparse_jungle.json
+ reports/worldgen/minecraft/worldgen/biome/stony_peaks.json
+ reports/worldgen/minecraft/worldgen/biome/stony_shore.json
+ reports/worldgen/minecraft/worldgen/biome/sunflower_plains.json
+ reports/worldgen/minecraft/worldgen/biome/swamp.json
+ reports/worldgen/minecraft/worldgen/biome/taiga.json
+ reports/worldgen/minecraft/worldgen/biome/the_end.json
+ reports/worldgen/minecraft/worldgen/biome/the_void.json
+ reports/worldgen/minecraft/worldgen/biome/warm_ocean.json
+ reports/worldgen/minecraft/worldgen/biome/warped_forest.json
+ reports/worldgen/minecraft/worldgen/biome/windswept_forest.json
+ reports/worldgen/minecraft/worldgen/biome/windswept_gravelly_hills.json
+ reports/worldgen/minecraft/worldgen/biome/windswept_hills.json
+ reports/worldgen/minecraft/worldgen/biome/windswept_savanna.json
+ reports/worldgen/minecraft/worldgen/biome/wooded_badlands.json
+ reports/worldgen/minecraft/worldgen/configured_carver/canyon.json
+ reports/worldgen/minecraft/worldgen/configured_carver/cave_extra_underground.json
+ reports/worldgen/minecraft/worldgen/configured_carver/cave.json
+ reports/worldgen/minecraft/worldgen/configured_carver/nether_cave.json
+ reports/worldgen/minecraft/worldgen/configured_feature/acacia.json
+ reports/worldgen/minecraft/worldgen/configured_feature/amethyst_geode.json
+ reports/worldgen/minecraft/worldgen/configured_feature/azalea_tree.json
+ reports/worldgen/minecraft/worldgen/configured_feature/bamboo_no_podzol.json
+ reports/worldgen/minecraft/worldgen/configured_feature/bamboo_some_podzol.json
+ reports/worldgen/minecraft/worldgen/configured_feature/bamboo_vegetation.json
+ reports/worldgen/minecraft/worldgen/configured_feature/basalt_blobs.json
+ reports/worldgen/minecraft/worldgen/configured_feature/basalt_pillar.json
+ reports/worldgen/minecraft/worldgen/configured_feature/birch_bees_0002.json
+ reports/worldgen/minecraft/worldgen/configured_feature/birch_bees_002.json
+ reports/worldgen/minecraft/worldgen/configured_feature/birch_bees_005.json
+ reports/worldgen/minecraft/worldgen/configured_feature/birch_tall.json
+ reports/worldgen/minecraft/worldgen/configured_feature/birch.json
+ reports/worldgen/minecraft/worldgen/configured_feature/blackstone_blobs.json
+ reports/worldgen/minecraft/worldgen/configured_feature/blue_ice.json
+ reports/worldgen/minecraft/worldgen/configured_feature/bonus_chest.json
+ reports/worldgen/minecraft/worldgen/configured_feature/cave_vine_in_moss.json
+ reports/worldgen/minecraft/worldgen/configured_feature/cave_vine.json
+ reports/worldgen/minecraft/worldgen/configured_feature/chorus_plant.json
+ reports/worldgen/minecraft/worldgen/configured_feature/clay_pool_with_dripleaves.json
+ reports/worldgen/minecraft/worldgen/configured_feature/clay_with_dripleaves.json
+ reports/worldgen/minecraft/worldgen/configured_feature/crimson_forest_vegetation_bonemeal.json
+ reports/worldgen/minecraft/worldgen/configured_feature/crimson_forest_vegetation.json
+ reports/worldgen/minecraft/worldgen/configured_feature/crimson_fungus_planted.json
+ reports/worldgen/minecraft/worldgen/configured_feature/crimson_fungus.json
+ reports/worldgen/minecraft/worldgen/configured_feature/dark_forest_vegetation.json
+ reports/worldgen/minecraft/worldgen/configured_feature/dark_oak.json
+ reports/worldgen/minecraft/worldgen/configured_feature/delta.json
+ reports/worldgen/minecraft/worldgen/configured_feature/desert_well.json
+ reports/worldgen/minecraft/worldgen/configured_feature/disk_clay.json
+ reports/worldgen/minecraft/worldgen/configured_feature/disk_gravel.json
+ reports/worldgen/minecraft/worldgen/configured_feature/disk_sand.json
+ reports/worldgen/minecraft/worldgen/configured_feature/dripleaf.json
+ reports/worldgen/minecraft/worldgen/configured_feature/dripstone_cluster.json
+ reports/worldgen/minecraft/worldgen/configured_feature/end_gateway_delayed.json
+ reports/worldgen/minecraft/worldgen/configured_feature/end_gateway_return.json
+ reports/worldgen/minecraft/worldgen/configured_feature/end_island.json
+ reports/worldgen/minecraft/worldgen/configured_feature/end_spike.json
+ reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak_bees_0002.json
+ reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak_bees_002.json
+ reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak_bees_005.json
+ reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak_bees.json
+ reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak.json
+ reports/worldgen/minecraft/worldgen/configured_feature/flower_default.json
+ reports/worldgen/minecraft/worldgen/configured_feature/flower_flower_forest.json
+ reports/worldgen/minecraft/worldgen/configured_feature/flower_meadow.json
+ reports/worldgen/minecraft/worldgen/configured_feature/flower_plain.json
+ reports/worldgen/minecraft/worldgen/configured_feature/flower_swamp.json
+ reports/worldgen/minecraft/worldgen/configured_feature/forest_flowers.json
+ reports/worldgen/minecraft/worldgen/configured_feature/forest_rock.json
+ reports/worldgen/minecraft/worldgen/configured_feature/fossil_coal.json
+ reports/worldgen/minecraft/worldgen/configured_feature/fossil_diamonds.json
+ reports/worldgen/minecraft/worldgen/configured_feature/freeze_top_layer.json
+ reports/worldgen/minecraft/worldgen/configured_feature/glow_lichen.json
+ reports/worldgen/minecraft/worldgen/configured_feature/glowstone_extra.json
+ reports/worldgen/minecraft/worldgen/configured_feature/huge_brown_mushroom.json
+ reports/worldgen/minecraft/worldgen/configured_feature/huge_red_mushroom.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ice_patch.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ice_spike.json
+ reports/worldgen/minecraft/worldgen/configured_feature/iceberg_blue.json
+ reports/worldgen/minecraft/worldgen/configured_feature/iceberg_packed.json
+ reports/worldgen/minecraft/worldgen/configured_feature/jungle_bush.json
+ reports/worldgen/minecraft/worldgen/configured_feature/jungle_tree_no_vine.json
+ reports/worldgen/minecraft/worldgen/configured_feature/jungle_tree.json
+ reports/worldgen/minecraft/worldgen/configured_feature/kelp.json
+ reports/worldgen/minecraft/worldgen/configured_feature/lake_lava.json
+ reports/worldgen/minecraft/worldgen/configured_feature/large_basalt_columns_temp.json
+ reports/worldgen/minecraft/worldgen/configured_feature/large_dripstone.json
+ reports/worldgen/minecraft/worldgen/configured_feature/lush_caves_clay.json
+ reports/worldgen/minecraft/worldgen/configured_feature/meadow_trees.json
+ reports/worldgen/minecraft/worldgen/configured_feature/mega_jungle_tree.json
+ reports/worldgen/minecraft/worldgen/configured_feature/mega_pine.json
+ reports/worldgen/minecraft/worldgen/configured_feature/mega_spruce.json
+ reports/worldgen/minecraft/worldgen/configured_feature/monster_room.json
+ reports/worldgen/minecraft/worldgen/configured_feature/moss_patch_bonemeal.json
+ reports/worldgen/minecraft/worldgen/configured_feature/moss_patch_ceiling.json
+ reports/worldgen/minecraft/worldgen/configured_feature/moss_patch.json
+ reports/worldgen/minecraft/worldgen/configured_feature/moss_vegetation.json
+ reports/worldgen/minecraft/worldgen/configured_feature/mushroom_island_vegetation.json
+ reports/worldgen/minecraft/worldgen/configured_feature/nether_sprouts_bonemeal.json
+ reports/worldgen/minecraft/worldgen/configured_feature/nether_sprouts.json
+ reports/worldgen/minecraft/worldgen/configured_feature/oak_bees_0002.json
+ reports/worldgen/minecraft/worldgen/configured_feature/oak_bees_002.json
+ reports/worldgen/minecraft/worldgen/configured_feature/oak_bees_005.json
+ reports/worldgen/minecraft/worldgen/configured_feature/oak.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_ancient_debris_large.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_ancient_debris_small.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_andesite.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_blackstone.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_clay.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_coal_buried.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_coal.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_copper_large.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_copper_small.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_diamond_buried.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_diamond_large.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_diamond_small.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_diorite.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_dirt.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_emerald.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_gold_buried.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_gold.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_granite.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_gravel_nether.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_gravel.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_infested.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_iron_small.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_iron.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_lapis_buried.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_lapis.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_magma.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_nether_gold.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_quartz.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_redstone.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_soul_sand.json
+ reports/worldgen/minecraft/worldgen/configured_feature/ore_tuff.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_berry_bush.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_brown_mushroom.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_cactus.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_crimson_roots.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_dead_bush.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_fire.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_grass_jungle.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_grass.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_large_fern.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_melon.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_pumpkin.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_red_mushroom.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_soul_fire.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_sugar_cane.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_sunflower.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_taiga_grass.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_tall_grass.json
+ reports/worldgen/minecraft/worldgen/configured_feature/patch_waterlily.json
+ reports/worldgen/minecraft/worldgen/configured_feature/pile_hay.json
+ reports/worldgen/minecraft/worldgen/configured_feature/pile_ice.json
+ reports/worldgen/minecraft/worldgen/configured_feature/pile_melon.json
+ reports/worldgen/minecraft/worldgen/configured_feature/pile_pumpkin.json
+ reports/worldgen/minecraft/worldgen/configured_feature/pile_snow.json
+ reports/worldgen/minecraft/worldgen/configured_feature/pine.json
+ reports/worldgen/minecraft/worldgen/configured_feature/pointed_dripstone.json
+ reports/worldgen/minecraft/worldgen/configured_feature/rooted_azalea_tree.json
+ reports/worldgen/minecraft/worldgen/configured_feature/sea_pickle.json
+ reports/worldgen/minecraft/worldgen/configured_feature/seagrass_mid.json
+ reports/worldgen/minecraft/worldgen/configured_feature/seagrass_short.json
+ reports/worldgen/minecraft/worldgen/configured_feature/seagrass_simple.json
+ reports/worldgen/minecraft/worldgen/configured_feature/seagrass_slightly_less_short.json
+ reports/worldgen/minecraft/worldgen/configured_feature/seagrass_tall.json
+ reports/worldgen/minecraft/worldgen/configured_feature/single_piece_of_grass.json
+ reports/worldgen/minecraft/worldgen/configured_feature/small_basalt_columns.json
+ reports/worldgen/minecraft/worldgen/configured_feature/spore_blossom.json
+ reports/worldgen/minecraft/worldgen/configured_feature/spring_lava_frozen.json
+ reports/worldgen/minecraft/worldgen/configured_feature/spring_lava_nether.json
+ reports/worldgen/minecraft/worldgen/configured_feature/spring_lava_overworld.json
+ reports/worldgen/minecraft/worldgen/configured_feature/spring_nether_closed.json
+ reports/worldgen/minecraft/worldgen/configured_feature/spring_nether_open.json
+ reports/worldgen/minecraft/worldgen/configured_feature/spring_water.json
+ reports/worldgen/minecraft/worldgen/configured_feature/spruce.json
+ reports/worldgen/minecraft/worldgen/configured_feature/super_birch_bees_0002.json
+ reports/worldgen/minecraft/worldgen/configured_feature/super_birch_bees.json
+ reports/worldgen/minecraft/worldgen/configured_feature/swamp_oak.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_birch_and_oak.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_flower_forest.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_grove.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_jungle.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_old_growth_pine_taiga.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_old_growth_spruce_taiga.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_plains.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_savanna.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_sparse_jungle.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_taiga.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_water.json
+ reports/worldgen/minecraft/worldgen/configured_feature/trees_windswept_hills.json
+ reports/worldgen/minecraft/worldgen/configured_feature/twisting_vines_bonemeal.json
+ reports/worldgen/minecraft/worldgen/configured_feature/twisting_vines.json
+ reports/worldgen/minecraft/worldgen/configured_feature/underwater_magma.json
+ reports/worldgen/minecraft/worldgen/configured_feature/vines.json
+ reports/worldgen/minecraft/worldgen/configured_feature/void_start_platform.json
+ reports/worldgen/minecraft/worldgen/configured_feature/warm_ocean_vegetation.json
+ reports/worldgen/minecraft/worldgen/configured_feature/warped_forest_vegetation_bonemeal.json
+ reports/worldgen/minecraft/worldgen/configured_feature/warped_forest_vegetation.json
+ reports/worldgen/minecraft/worldgen/configured_feature/warped_fungus_planted.json
+ reports/worldgen/minecraft/worldgen/configured_feature/warped_fungus.json
+ reports/worldgen/minecraft/worldgen/configured_feature/weeping_vines.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/bastion_remnant.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/buried_treasure.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/desert_pyramid.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/end_city.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/fortress.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/igloo.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/jungle_pyramid.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/mansion.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/mineshaft_mesa.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/mineshaft.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/monument.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/nether_fossil.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ocean_ruin_cold.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ocean_ruin_warm.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/pillager_outpost.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_desert.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_jungle.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_mountain.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_nether.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_ocean.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_swamp.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/shipwreck_beached.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/shipwreck.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/stronghold.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/swamp_hut.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/village_desert.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/village_plains.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/village_savanna.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/village_snowy.json
+ reports/worldgen/minecraft/worldgen/configured_structure_feature/village_taiga.json
+ reports/worldgen/minecraft/worldgen/noise_settings/amplified.json
+ reports/worldgen/minecraft/worldgen/noise_settings/caves.json
+ reports/worldgen/minecraft/worldgen/noise_settings/end.json
+ reports/worldgen/minecraft/worldgen/noise_settings/floating_islands.json
+ reports/worldgen/minecraft/worldgen/noise_settings/large_biomes.json
+ reports/worldgen/minecraft/worldgen/noise_settings/nether.json
+ reports/worldgen/minecraft/worldgen/noise_settings/overworld.json
+ reports/worldgen/minecraft/worldgen/noise/aquifer_barrier.json
+ reports/worldgen/minecraft/worldgen/noise/aquifer_fluid_level_floodedness.json
+ reports/worldgen/minecraft/worldgen/noise/aquifer_fluid_level_spread.json
+ reports/worldgen/minecraft/worldgen/noise/aquifer_lava.json
+ reports/worldgen/minecraft/worldgen/noise/badlands_pillar_roof.json
+ reports/worldgen/minecraft/worldgen/noise/badlands_pillar.json
+ reports/worldgen/minecraft/worldgen/noise/badlands_surface.json
+ reports/worldgen/minecraft/worldgen/noise/calcite.json
+ reports/worldgen/minecraft/worldgen/noise/cave_cheese.json
+ reports/worldgen/minecraft/worldgen/noise/cave_entrance.json
+ reports/worldgen/minecraft/worldgen/noise/cave_layer.json
+ reports/worldgen/minecraft/worldgen/noise/clay_bands_offset.json
+ reports/worldgen/minecraft/worldgen/noise/continentalness_large.json
+ reports/worldgen/minecraft/worldgen/noise/continentalness.json
+ reports/worldgen/minecraft/worldgen/noise/erosion_large.json
+ reports/worldgen/minecraft/worldgen/noise/erosion.json
+ reports/worldgen/minecraft/worldgen/noise/gravel_layer.json
+ reports/worldgen/minecraft/worldgen/noise/gravel.json
+ reports/worldgen/minecraft/worldgen/noise/ice.json
+ reports/worldgen/minecraft/worldgen/noise/iceberg_pillar_roof.json
+ reports/worldgen/minecraft/worldgen/noise/iceberg_pillar.json
+ reports/worldgen/minecraft/worldgen/noise/iceberg_surface.json
+ reports/worldgen/minecraft/worldgen/noise/jagged.json
+ reports/worldgen/minecraft/worldgen/noise/nether_state_selector.json
+ reports/worldgen/minecraft/worldgen/noise/nether_wart.json
+ reports/worldgen/minecraft/worldgen/noise/netherrack.json
+ reports/worldgen/minecraft/worldgen/noise/noodle_ridge_a.json
+ reports/worldgen/minecraft/worldgen/noise/noodle_ridge_b.json
+ reports/worldgen/minecraft/worldgen/noise/noodle_thickness.json
+ reports/worldgen/minecraft/worldgen/noise/noodle.json
+ reports/worldgen/minecraft/worldgen/noise/offset.json
+ reports/worldgen/minecraft/worldgen/noise/ore_gap.json
+ reports/worldgen/minecraft/worldgen/noise/ore_vein_a.json
+ reports/worldgen/minecraft/worldgen/noise/ore_vein_b.json
+ reports/worldgen/minecraft/worldgen/noise/ore_veininess.json
+ reports/worldgen/minecraft/worldgen/noise/packed_ice.json
+ reports/worldgen/minecraft/worldgen/noise/patch.json
+ reports/worldgen/minecraft/worldgen/noise/pillar_rareness.json
+ reports/worldgen/minecraft/worldgen/noise/pillar_thickness.json
+ reports/worldgen/minecraft/worldgen/noise/pillar.json
+ reports/worldgen/minecraft/worldgen/noise/powder_snow.json
+ reports/worldgen/minecraft/worldgen/noise/ridge.json
+ reports/worldgen/minecraft/worldgen/noise/soul_sand_layer.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_2d_elevation.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_2d_modulator.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_2d_thickness.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_2d.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_3d_1.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_3d_2.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_3d_rarity.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_3d_thickness.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_roughness_modulator.json
+ reports/worldgen/minecraft/worldgen/noise/spaghetti_roughness.json
+ reports/worldgen/minecraft/worldgen/noise/surface_secondary.json
+ reports/worldgen/minecraft/worldgen/noise/surface_swamp.json
+ reports/worldgen/minecraft/worldgen/noise/surface.json
+ reports/worldgen/minecraft/worldgen/noise/temperature_large.json
+ reports/worldgen/minecraft/worldgen/noise/temperature.json
+ reports/worldgen/minecraft/worldgen/noise/vegetation_large.json
+ reports/worldgen/minecraft/worldgen/noise/vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/acacia_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/amethyst_geode.json
+ reports/worldgen/minecraft/worldgen/placed_feature/bamboo_light.json
+ reports/worldgen/minecraft/worldgen/placed_feature/bamboo_vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/bamboo.json
+ reports/worldgen/minecraft/worldgen/placed_feature/basalt_blobs.json
+ reports/worldgen/minecraft/worldgen/placed_feature/basalt_pillar.json
+ reports/worldgen/minecraft/worldgen/placed_feature/birch_bees_0002.json
+ reports/worldgen/minecraft/worldgen/placed_feature/birch_bees_002.json
+ reports/worldgen/minecraft/worldgen/placed_feature/birch_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/birch_tall.json
+ reports/worldgen/minecraft/worldgen/placed_feature/blackstone_blobs.json
+ reports/worldgen/minecraft/worldgen/placed_feature/blue_ice.json
+ reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_nether.json
+ reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_normal.json
+ reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_old_growth.json
+ reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_swamp.json
+ reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_taiga.json
+ reports/worldgen/minecraft/worldgen/placed_feature/cave_vines.json
+ reports/worldgen/minecraft/worldgen/placed_feature/chorus_plant.json
+ reports/worldgen/minecraft/worldgen/placed_feature/classic_vines_cave_feature.json
+ reports/worldgen/minecraft/worldgen/placed_feature/crimson_forest_vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/crimson_fungi.json
+ reports/worldgen/minecraft/worldgen/placed_feature/dark_forest_vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/dark_oak_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/delta.json
+ reports/worldgen/minecraft/worldgen/placed_feature/desert_well.json
+ reports/worldgen/minecraft/worldgen/placed_feature/disk_clay.json
+ reports/worldgen/minecraft/worldgen/placed_feature/disk_gravel.json
+ reports/worldgen/minecraft/worldgen/placed_feature/disk_sand.json
+ reports/worldgen/minecraft/worldgen/placed_feature/dripstone_cluster.json
+ reports/worldgen/minecraft/worldgen/placed_feature/end_gateway_return.json
+ reports/worldgen/minecraft/worldgen/placed_feature/end_island_decorated.json
+ reports/worldgen/minecraft/worldgen/placed_feature/end_spike.json
+ reports/worldgen/minecraft/worldgen/placed_feature/fancy_oak_bees_0002.json
+ reports/worldgen/minecraft/worldgen/placed_feature/fancy_oak_bees_002.json
+ reports/worldgen/minecraft/worldgen/placed_feature/fancy_oak_bees.json
+ reports/worldgen/minecraft/worldgen/placed_feature/fancy_oak_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/flower_default.json
+ reports/worldgen/minecraft/worldgen/placed_feature/flower_flower_forest.json
+ reports/worldgen/minecraft/worldgen/placed_feature/flower_forest_flowers.json
+ reports/worldgen/minecraft/worldgen/placed_feature/flower_meadow.json
+ reports/worldgen/minecraft/worldgen/placed_feature/flower_plain.json
+ reports/worldgen/minecraft/worldgen/placed_feature/flower_swamp.json
+ reports/worldgen/minecraft/worldgen/placed_feature/flower_warm.json
+ reports/worldgen/minecraft/worldgen/placed_feature/forest_flowers.json
+ reports/worldgen/minecraft/worldgen/placed_feature/forest_rock.json
+ reports/worldgen/minecraft/worldgen/placed_feature/fossil_lower.json
+ reports/worldgen/minecraft/worldgen/placed_feature/fossil_upper.json
+ reports/worldgen/minecraft/worldgen/placed_feature/freeze_top_layer.json
+ reports/worldgen/minecraft/worldgen/placed_feature/glow_lichen.json
+ reports/worldgen/minecraft/worldgen/placed_feature/glowstone_extra.json
+ reports/worldgen/minecraft/worldgen/placed_feature/glowstone.json
+ reports/worldgen/minecraft/worldgen/placed_feature/grass_bonemeal.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ice_patch.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ice_spike.json
+ reports/worldgen/minecraft/worldgen/placed_feature/iceberg_blue.json
+ reports/worldgen/minecraft/worldgen/placed_feature/iceberg_packed.json
+ reports/worldgen/minecraft/worldgen/placed_feature/jungle_bush.json
+ reports/worldgen/minecraft/worldgen/placed_feature/jungle_tree.json
+ reports/worldgen/minecraft/worldgen/placed_feature/kelp_cold.json
+ reports/worldgen/minecraft/worldgen/placed_feature/kelp_warm.json
+ reports/worldgen/minecraft/worldgen/placed_feature/lake_lava_surface.json
+ reports/worldgen/minecraft/worldgen/placed_feature/lake_lava_underground.json
+ reports/worldgen/minecraft/worldgen/placed_feature/large_basalt_columns.json
+ reports/worldgen/minecraft/worldgen/placed_feature/large_dripstone.json
+ reports/worldgen/minecraft/worldgen/placed_feature/lush_caves_ceiling_vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/lush_caves_clay.json
+ reports/worldgen/minecraft/worldgen/placed_feature/lush_caves_vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/mega_jungle_tree_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/mega_pine_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/mega_spruce_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/monster_room_deep.json
+ reports/worldgen/minecraft/worldgen/placed_feature/monster_room.json
+ reports/worldgen/minecraft/worldgen/placed_feature/mushroom_island_vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/nether_sprouts.json
+ reports/worldgen/minecraft/worldgen/placed_feature/oak_bees_0002.json
+ reports/worldgen/minecraft/worldgen/placed_feature/oak_bees_002.json
+ reports/worldgen/minecraft/worldgen/placed_feature/oak_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_ancient_debris_large.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_andesite_lower.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_andesite_upper.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_blackstone.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_clay.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_coal_lower.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_coal_upper.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_copper_large.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_copper.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_debris_small.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_diamond_buried.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_diamond_large.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_diamond.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_diorite_lower.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_diorite_upper.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_dirt.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_emerald.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_gold_deltas.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_gold_extra.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_gold_lower.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_gold_nether.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_gold.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_granite_lower.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_granite_upper.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_gravel_nether.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_gravel.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_infested.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_iron_middle.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_iron_small.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_iron_upper.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_lapis_buried.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_lapis.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_magma.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_quartz_deltas.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_quartz_nether.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_redstone_lower.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_redstone.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_soul_sand.json
+ reports/worldgen/minecraft/worldgen/placed_feature/ore_tuff.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_berry_common.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_berry_rare.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_cactus_decorated.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_cactus_desert.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_crimson_roots.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_dead_bush_2.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_dead_bush_badlands.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_dead_bush.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_fire.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_badlands.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_forest.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_jungle.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_normal.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_plain.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_savanna.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_taiga_2.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_taiga.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_large_fern.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_melon.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_pumpkin.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_soul_fire.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_sugar_cane_badlands.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_sugar_cane_desert.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_sugar_cane_swamp.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_sugar_cane.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_sunflower.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_tall_grass_2.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_tall_grass.json
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_waterlily.json
+ reports/worldgen/minecraft/worldgen/placed_feature/pine_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/pine_on_snow.json
+ reports/worldgen/minecraft/worldgen/placed_feature/pointed_dripstone.json
+ reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_nether.json
+ reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_normal.json
+ reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_old_growth.json
+ reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_swamp.json
+ reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_taiga.json
+ reports/worldgen/minecraft/worldgen/placed_feature/rooted_azalea_tree.json
+ reports/worldgen/minecraft/worldgen/placed_feature/sea_pickle.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_cold.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_deep_cold.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_deep_warm.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_deep.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_normal.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_river.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_simple.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_swamp.json
+ reports/worldgen/minecraft/worldgen/placed_feature/seagrass_warm.json
+ reports/worldgen/minecraft/worldgen/placed_feature/small_basalt_columns.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spore_blossom.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spring_closed_double.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spring_closed.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spring_delta.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spring_lava_frozen.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spring_lava.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spring_open.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spring_water.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spruce_checked.json
+ reports/worldgen/minecraft/worldgen/placed_feature/spruce_on_snow.json
+ reports/worldgen/minecraft/worldgen/placed_feature/super_birch_bees_0002.json
+ reports/worldgen/minecraft/worldgen/placed_feature/super_birch_bees.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_badlands.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_birch_and_oak.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_birch.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_flower_forest.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_grove.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_jungle.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_meadow.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_old_growth_pine_taiga.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_old_growth_spruce_taiga.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_plains.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_savanna.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_snowy.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_sparse_jungle.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_swamp.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_taiga.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_water.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_windswept_forest.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_windswept_hills.json
+ reports/worldgen/minecraft/worldgen/placed_feature/trees_windswept_savanna.json
+ reports/worldgen/minecraft/worldgen/placed_feature/twisting_vines.json
+ reports/worldgen/minecraft/worldgen/placed_feature/underwater_magma.json
+ reports/worldgen/minecraft/worldgen/placed_feature/vines.json
+ reports/worldgen/minecraft/worldgen/placed_feature/void_start_platform.json
+ reports/worldgen/minecraft/worldgen/placed_feature/warm_ocean_vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/warped_forest_vegetation.json
+ reports/worldgen/minecraft/worldgen/placed_feature/warped_fungi.json
+ reports/worldgen/minecraft/worldgen/placed_feature/weeping_vines.json
+ reports/worldgen/minecraft/worldgen/processor_list/bastion_generic_degradation.json
+ reports/worldgen/minecraft/worldgen/processor_list/bottom_rampart.json
+ reports/worldgen/minecraft/worldgen/processor_list/bridge.json
+ reports/worldgen/minecraft/worldgen/processor_list/empty.json
+ reports/worldgen/minecraft/worldgen/processor_list/entrance_replacement.json
+ reports/worldgen/minecraft/worldgen/processor_list/farm_desert.json
+ reports/worldgen/minecraft/worldgen/processor_list/farm_plains.json
+ reports/worldgen/minecraft/worldgen/processor_list/farm_savanna.json
+ reports/worldgen/minecraft/worldgen/processor_list/farm_snowy.json
+ reports/worldgen/minecraft/worldgen/processor_list/farm_taiga.json
+ reports/worldgen/minecraft/worldgen/processor_list/fossil_coal.json
+ reports/worldgen/minecraft/worldgen/processor_list/fossil_diamonds.json
+ reports/worldgen/minecraft/worldgen/processor_list/fossil_rot.json
+ reports/worldgen/minecraft/worldgen/processor_list/high_rampart.json
+ reports/worldgen/minecraft/worldgen/processor_list/high_wall.json
+ reports/worldgen/minecraft/worldgen/processor_list/housing.json
+ reports/worldgen/minecraft/worldgen/processor_list/mossify_10_percent.json
+ reports/worldgen/minecraft/worldgen/processor_list/mossify_20_percent.json
+ reports/worldgen/minecraft/worldgen/processor_list/mossify_70_percent.json
+ reports/worldgen/minecraft/worldgen/processor_list/outpost_rot.json
+ reports/worldgen/minecraft/worldgen/processor_list/rampart_degradation.json
+ reports/worldgen/minecraft/worldgen/processor_list/roof.json
+ reports/worldgen/minecraft/worldgen/processor_list/side_wall_degradation.json
+ reports/worldgen/minecraft/worldgen/processor_list/stable_degradation.json
+ reports/worldgen/minecraft/worldgen/processor_list/street_plains.json
+ reports/worldgen/minecraft/worldgen/processor_list/street_savanna.json
+ reports/worldgen/minecraft/worldgen/processor_list/street_snowy_or_taiga.json
+ reports/worldgen/minecraft/worldgen/processor_list/treasure_rooms.json
+ reports/worldgen/minecraft/worldgen/processor_list/zombie_desert.json
+ reports/worldgen/minecraft/worldgen/processor_list/zombie_plains.json
+ reports/worldgen/minecraft/worldgen/processor_list/zombie_savanna.json
+ reports/worldgen/minecraft/worldgen/processor_list/zombie_snowy.json
+ reports/worldgen/minecraft/worldgen/processor_list/zombie_taiga.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/blocks/gold.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/bridge_pieces.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/connectors.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/legs.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/rampart_plates.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/ramparts.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/starting_pieces.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/walls.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/connectors.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/inner.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/outer.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/mirrored_starting_pieces.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/posts.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/rampart_plates.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/ramparts.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/inner.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/outer.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/stairs.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/starting_pieces.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/wall_bases.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/walls.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/mobs/hoglin.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/mobs/piglin_melee.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/mobs/piglin.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/starts.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/bases.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/bases/centers.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/brains.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/connectors.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/corners/bottom.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/corners/edges.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/corners/middle.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/corners/top.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/entrances.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/extensions/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/extensions/large_pool.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/extensions/small_pool.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/ramparts.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/roofs.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/stairs.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls/bottom.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls/mid.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls/outer.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls/top.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/center_pieces.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/edge_wall_units.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/edges.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/fillers/stage_0.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/large_ramparts.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/pathways.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/rampart_plates.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/ramparts.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/rot/stage_1.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/stage_0.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/stage_1.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/stage_2.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/stage_3.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/wall_units.json
+ reports/worldgen/minecraft/worldgen/template_pool/bastion/units/walls/wall_bases.json
+ reports/worldgen/minecraft/worldgen/template_pool/empty.json
+ reports/worldgen/minecraft/worldgen/template_pool/pillager_outpost/base_plates.json
+ reports/worldgen/minecraft/worldgen/template_pool/pillager_outpost/feature_plates.json
+ reports/worldgen/minecraft/worldgen/template_pool/pillager_outpost/features.json
+ reports/worldgen/minecraft/worldgen/template_pool/pillager_outpost/towers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/common/animals.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/common/butcher_animals.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/common/cats.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/common/iron_golem.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/common/sheep.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/common/well_bottoms.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/terminators.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/town_centers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/terminators.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/terminators.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/town_centers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/trees.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/zombie/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/zombie/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/zombie/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/plains/zombie/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/terminators.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/town_centers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/trees.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/terminators.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/terminators.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/town_centers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/trees.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/zombie/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/zombie/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/zombie/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/snowy/zombie/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/terminators.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/town_centers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/villagers.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/zombie/decor.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/zombie/houses.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/zombie/streets.json
+ reports/worldgen/minecraft/worldgen/template_pool/village/taiga/zombie/villagers.json
```

</details>
<details>
<summary>
data
</summary>

```diff
- minecraft/advancements/adventure/caves_and_cliffs.json
+ minecraft/advancements/adventure/fall_from_world_height.json
+ minecraft/advancements/adventure/play_jukebox_in_meadows.json
- minecraft/advancements/adventure/ride_strider_in_overworld_lava.json
- minecraft/advancements/husbandry/play_jukebox_in_meadows.json
+ minecraft/advancements/nether/ride_strider_in_overworld_lava.json
```

</details>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.data.info.package-info
+ net.minecraft.data.loot.BlockLoot
- net.minecraft.data.loot.ChestLoot
+ net.minecraft.data.loot.EntityLoot
- net.minecraft.data.loot.FishingLoot
+ net.minecraft.data.loot.GiftLoot
- net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.PiglinBarterLoot
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
+ net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
- net.minecraft.data.models.blockstates.Condition$CompositeCondition
+ net.minecraft.data.models.blockstates.Condition$Operation
- net.minecraft.data.models.blockstates.Condition$TerminalCondition
+ net.minecraft.data.models.blockstates.MultiPartGenerator
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
- net.minecraft.data.models.blockstates.package-info
+ net.minecraft.data.models.blockstates.PropertyDispatch
- net.minecraft.data.models.blockstates.PropertyDispatch$C1
+ net.minecraft.data.models.blockstates.PropertyDispatch$C2
- net.minecraft.data.models.blockstates.PropertyDispatch$C3
+ net.minecraft.data.models.blockstates.PropertyDispatch$C4
- net.minecraft.data.models.blockstates.PropertyDispatch$C5
+ net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
- net.minecraft.data.models.blockstates.Selector
+ net.minecraft.data.models.blockstates.Variant
- net.minecraft.data.models.blockstates.VariantProperties
+ net.minecraft.data.models.blockstates.VariantProperties$Rotation
- net.minecraft.data.models.blockstates.VariantProperty
+ net.minecraft.data.models.blockstates.VariantProperty$Value
- net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.model.DelegatedModel
- net.minecraft.data.models.model.ModelLocationUtils
+ net.minecraft.data.models.model.ModelTemplate
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
- net.minecraft.data.recipes.FinishedRecipe
+ net.minecraft.data.recipes.package-info
+ net.minecraft.data.recipes.RecipeBuilder
- net.minecraft.data.recipes.RecipeProvider
+ net.minecraft.data.recipes.ShapedRecipeBuilder
- net.minecraft.data.recipes.ShapedRecipeBuilder$Result
+ net.minecraft.data.recipes.ShapelessRecipeBuilder
- net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
+ net.minecraft.data.recipes.SingleItemRecipeBuilder
- net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
+ net.minecraft.data.recipes.SpecialRecipeBuilder
- net.minecraft.data.recipes.SpecialRecipeBuilder$1
+ net.minecraft.data.recipes.UpgradeRecipeBuilder
- net.minecraft.data.recipes.UpgradeRecipeBuilder$Result
- net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
+ net.minecraft.data.structures.SnbtToNbt$StructureConversionException
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.GameEventTagsProvider
+ net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.data.worldgen.BastionBridgePools
- net.minecraft.data.worldgen.BastionHoglinStablePools
+ net.minecraft.data.worldgen.BastionHousingUnitsPools
- net.minecraft.data.worldgen.BastionPieces
+ net.minecraft.data.worldgen.BastionSharedPools
- net.minecraft.data.worldgen.BastionTreasureRoomPools
+ net.minecraft.data.worldgen.biome.BiomeReport
- net.minecraft.data.worldgen.biome.Biomes
+ net.minecraft.data.worldgen.biome.EndBiomes
- net.minecraft.data.worldgen.biome.NetherBiomes
+ net.minecraft.data.worldgen.biome.OverworldBiomes
- net.minecraft.data.worldgen.biome.package-info
+ net.minecraft.data.worldgen.BiomeDefaultFeatures
- net.minecraft.data.worldgen.Carvers
+ net.minecraft.data.worldgen.DesertVillagePools
- net.minecraft.data.worldgen.features.CaveFeatures
- net.minecraft.data.worldgen.features.FeatureUtils
- net.minecraft.data.worldgen.features.NetherFeatures
- net.minecraft.data.worldgen.features.PileFeatures
- net.minecraft.data.worldgen.features.VegetationFeatures
+ net.minecraft.data.worldgen.Features$Configs
- net.minecraft.data.worldgen.placement.CavePlacements
- net.minecraft.data.worldgen.placement.MiscOverworldPlacements
- net.minecraft.data.worldgen.placement.OrePlacements
- net.minecraft.data.worldgen.placement.package-info
- net.minecraft.data.worldgen.placement.TreePlacements
+ net.minecraft.resources.RegistryReadOps$ResourceAccess
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
- net.minecraft.resources.RegistryResourceAccess
- net.minecraft.resources.RegistryResourceAccess$InMemoryStorage
- net.minecraft.resources.RegistryResourceAccess$ParsedEntry
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- net.minecraft.util.datafix.fixes.ChunkRenamesFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix2
+ net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
- net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
+ net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.MapIdFix
+ net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
- net.minecraft.util.datafix.fixes.MissingDimensionFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRename
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
- net.minecraft.util.datafix.fixes.RenameBiomesFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1451_7
- net.minecraft.util.datafix.schemas.V1460
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
+ net.minecraft.util.datafix.schemas.V2831
- net.minecraft.util.datafix.schemas.V2832
+ net.minecraft.util.datafix.schemas.V2842
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.ExtraCodecs$3
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.jfr.callback.package-info
+ net.minecraft.util.profiling.jfr.callback.ProfiledDuration
- net.minecraft.util.profiling.jfr.Environment
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
+ net.minecraft.util.profiling.jfr.event.package-info
- net.minecraft.util.profiling.jfr.event.PacketEvent
+ net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
- net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
+ net.minecraft.util.profiling.jfr.event.PacketSentEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
- net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
+ net.minecraft.util.profiling.jfr.JfrProfiler
- net.minecraft.util.profiling.jfr.JfrProfiler$1
+ net.minecraft.util.profiling.jfr.JvmProfiler
- net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
- net.minecraft.util.profiling.jfr.package-info
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
- net.minecraft.util.profiling.jfr.parse.JfrStatsResult
+ net.minecraft.util.profiling.jfr.parse.package-info
+ net.minecraft.util.profiling.jfr.Percentiles
- net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
+ net.minecraft.util.profiling.jfr.serialize.package-info
- net.minecraft.util.profiling.jfr.stats.ChunkGenStat
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketCountAndSize
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketIdentification
- net.minecraft.util.profiling.jfr.stats.package-info
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
- net.minecraft.util.profiling.jfr.stats.TimedStat
+ net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.stats.TimeStamped
- net.minecraft.util.profiling.jfr.SummaryReporter
+ net.minecraft.util.profiling.metrics.MetricCategory
- net.minecraft.util.profiling.metrics.MetricSampler
+ net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
- net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
+ net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
- net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ net.minecraft.util.profiling.metrics.MetricsRegistry
- net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ net.minecraft.util.profiling.metrics.MetricsSamplerProvider
+ net.minecraft.util.profiling.metrics.package-info
- net.minecraft.util.profiling.metrics.ProfilerMeasured
- net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.package-info
+ net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- net.minecraft.util.profiling.metrics.storage.MetricsPersister
- net.minecraft.util.profiling.metrics.storage.package-info
+ net.minecraft.util.profiling.metrics.storage.RecordedDeviation
+ net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.random.package-info
- net.minecraft.util.random.SimpleWeightedRandomList
+ net.minecraft.util.random.SimpleWeightedRandomList$Builder
- net.minecraft.util.random.Weight
+ net.minecraft.util.random.WeightedEntry
- net.minecraft.util.random.WeightedEntry$IntrusiveBase
+ net.minecraft.util.random.WeightedEntry$Wrapper
- net.minecraft.util.random.WeightedRandom
+ net.minecraft.util.random.WeightedRandomList
+ net.minecraft.util.StringUtil
- net.minecraft.util.TelemetryConstants
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.valueproviders.BiasedToBottomInt
+ net.minecraft.util.valueproviders.ClampedInt
- net.minecraft.util.valueproviders.ClampedNormalFloat
+ net.minecraft.util.valueproviders.ClampedNormalInt
- net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.IntProviderType
- net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.VisibleForDebug
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.ZeroBitStorage
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
- net.minecraft.world.damagesource.BadRespawnPointDamage
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.EntityDamageSource
- net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffects$1
+ net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AnimalPanic
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
- net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
+ net.minecraft.world.entity.ai.behavior.LongJumpMidJump
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.RandomSwim
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunIf
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.RunSometimes
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
- net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
+ net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
- net.minecraft.world.entity.ai.goal.target.package-info
- net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
+ net.minecraft.world.entity.ai.goal.target.TargetGoal
+ net.minecraft.world.entity.ai.goal.TemptGoal
- net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
+ net.minecraft.world.entity.ai.goal.TryFindWaterGoal
- net.minecraft.world.entity.ai.goal.UseItemGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
+ net.minecraft.world.entity.ai.goal.WrappedGoal
- net.minecraft.world.entity.ai.goal.ZombieAttackGoal
+ net.minecraft.world.entity.ai.gossip.GossipContainer
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
+ net.minecraft.world.entity.animal.Fox$FaceplantGoal
- net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
+ net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
- net.minecraft.world.entity.animal.Fox$FoxBreedGoal
+ net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
- net.minecraft.world.entity.animal.Fox$FoxFloatGoal
+ net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
- net.minecraft.world.entity.animal.Fox$FoxGroupData
+ net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
- net.minecraft.world.entity.animal.Fox$FoxLookControl
+ net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
- net.minecraft.world.entity.animal.Fox$FoxMoveControl
+ net.minecraft.world.entity.animal.Fox$FoxPanicGoal
- net.minecraft.world.entity.animal.Fox$FoxPounceGoal
+ net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
- net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
+ net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
- net.minecraft.world.entity.animal.Fox$SeekShelterGoal
+ net.minecraft.world.entity.animal.Fox$SleepGoal
- net.minecraft.world.entity.animal.Fox$StalkPreyGoal
+ net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.goat.Goat
+ net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
- net.minecraft.world.entity.animal.goat.Goat$GoatPathNavigation
+ net.minecraft.world.entity.animal.goat.GoatAi
- net.minecraft.world.entity.animal.goat.package-info
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
- net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
+ net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
- net.minecraft.world.entity.animal.horse.Markings
+ net.minecraft.world.entity.animal.horse.Mule
- net.minecraft.world.entity.animal.horse.package-info
- net.minecraft.world.entity.animal.horse.SkeletonHorse
+ net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
- net.minecraft.world.entity.animal.horse.TraderLlama
+ net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.animal.horse.Variant
+ net.minecraft.world.entity.animal.horse.ZombieHorse
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.boss.enderdragon.EndCrystal
- net.minecraft.world.entity.boss.enderdragon.EnderDragon
+ net.minecraft.world.entity.boss.enderdragon.package-info
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
- net.minecraft.world.entity.boss.enderdragon.phases.package-info
- net.minecraft.world.entity.boss.EnderDragonPart
+ net.minecraft.world.entity.boss.package-info
- net.minecraft.world.entity.boss.wither.package-info
- net.minecraft.world.entity.boss.wither.WitherBoss
+ net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
+ net.minecraft.world.entity.decoration.ArmorStand
- net.minecraft.world.entity.decoration.ArmorStand$1
+ net.minecraft.world.entity.decoration.GlowItemFrame
- net.minecraft.world.entity.decoration.HangingEntity
+ net.minecraft.world.entity.decoration.HangingEntity$1
- net.minecraft.world.entity.decoration.ItemFrame
+ net.minecraft.world.entity.decoration.ItemFrame$1
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$1
+ net.minecraft.world.entity.EntityType$Builder
- net.minecraft.world.entity.EntityType$EntityFactory
+ net.minecraft.world.entity.EquipmentSlot
- net.minecraft.world.entity.EquipmentSlot$Type
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LerpingModel
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.ContainerSynchronizer
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.item.AdventureModeCheck
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$11
- net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$2
- net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$4
- net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$6
- net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$8
- net.minecraft.world.item.CreativeModeTab$9
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
- net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockCollisions
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EntityBasedExplosionDamageCalculator
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.ExplosionDamageCalculator
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.GameRules
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$PositionedBlendingData
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.blending.BlendingData$1
+ net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
+ net.minecraft.world.level.levelgen.blending.GenerationUpgradeData
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
- net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
+ net.minecraft.world.level.levelgen.Density
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RangeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ScatterDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
- net.minecraft.world.level.levelgen.feature.DripstoneUtils
+ net.minecraft.world.level.levelgen.feature.EndCityFeature
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
- net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.GlowLichenFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.JigsawFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.FlatLevelSource
+ net.minecraft.world.level.levelgen.GenerationStep
- net.minecraft.world.level.levelgen.GenerationStep$Carving
+ net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.GeodeBlockSettings
+ net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.GeodeLayerSettings
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
- net.minecraft.world.level.levelgen.LegacyRandomSource
+ net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$InterpolatableNoise
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseFiller
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
+ net.minecraft.world.level.levelgen.NoiseChunk$Sampler
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.Noises
+ net.minecraft.world.level.levelgen.NoiseSampler
- net.minecraft.world.level.levelgen.NoiseSampler$FlatNoiseData
+ net.minecraft.world.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.NoiseSampler$VeinType
+ net.minecraft.world.level.levelgen.NoiseSamplingSettings
- net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.NoiseSlider
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.BlockFilterDecorator
- net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceDecorator
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
+ net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
- net.minecraft.world.level.levelgen.placement.CountPlacement
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EnvironmentScanDecorator
+ net.minecraft.world.level.levelgen.placement.FilterDecorator
+ net.minecraft.world.level.levelgen.placement.HeightmapDecorator
- net.minecraft.world.level.levelgen.placement.HeightRangePlacement
- net.minecraft.world.level.levelgen.placement.InSquarePlacement
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
- net.minecraft.world.level.levelgen.placement.PlacementContext
- net.minecraft.world.level.levelgen.placement.PlacementModifier
- net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
+ net.minecraft.world.level.levelgen.placement.RangeDecorator
- net.minecraft.world.level.levelgen.placement.RepeatingPlacement
+ net.minecraft.world.level.levelgen.placement.ScatterDecorator
+ net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdConfiguration
- net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
+ net.minecraft.world.level.levelgen.placement.VerticalDecorator
+ net.minecraft.world.level.levelgen.placement.WaterDepthThresholdDecorator
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.RandomSource
+ net.minecraft.world.level.levelgen.RandomSupport
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.StructureSettings
+ net.minecraft.world.level.levelgen.SurfaceRules
- net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Condition
- net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Context
- net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Hole
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$StateRule
- net.minecraft.world.level.levelgen.SurfaceRules$Steep
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
- net.minecraft.world.level.levelgen.SurfaceRules$Temperature
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRule
- net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ net.minecraft.world.level.levelgen.SurfaceSystem
- net.minecraft.world.level.levelgen.SurfaceSystem$1
+ net.minecraft.world.level.levelgen.TerrainInfo
- net.minecraft.world.level.levelgen.VerticalAnchor
+ net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
- net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
+ net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
+ net.minecraft.world.level.levelgen.WorldGenerationContext
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelHeightAccessor$1
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.SpawnData$CustomSpawnRules
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.IdMapper +1P -1P
```
```
XXX.minecraft.core.MappedRegistry$RegistryEntry +6M
```
```
XXX.minecraft.core.RegistryAccess +2M -1M
```
```
XXX.minecraft.data.BuiltinRegistries +3M -4M | +1P
```
```
XXX.data.worldgen.NoiseData +1M -1M
```
```
XXX.data.worldgen.TerrainProvider +1M -1M
```
```
XXX.minecraft.resources.RegistryReadOps$1 +1M -1M | +1P -2P
```
```
XXX.minecraft.resources.ResourceKey +1M
```
```
XXX.server.commands.JfrCommand +1M -1M
```
```
XXX.server.players.PlayerList +1M -1M
```
```
XXX.minecraft.util.CubicSpline +1M
```
```
XXX.minecraft.util.CubicSpline$Builder +2M | +1P
```
```
XXX.minecraft.util.StringRepresentable$1 +2M -11M | +1P -3P
```
```
XXX.level.biome.BiomeSource +5M -4M | +1P -1P
```
```
XXX.level.biome.Climate$RTree$Leaf +1M -1M | +1P -1P
```
```
XXX.level.biome.MultiNoiseBiomeSource +1M -2M
```
```
XXX.level.biome.MultiNoiseBiomeSource$PresetInstance +3M
```
```
XXX.level.biome.TerrainShaper +12M -8M | +1P
```
```
XXX.level.border.WorldBorder +1M
```
```
XXX.level.chunk.LevelChunk +1M -1M
```
```
XXX.level.chunk.ProtoChunk +2M -2M
```
```
XXX.levelgen.blockpredicates.BlockPredicate +9M -6M | +2P
```
```
XXX.levelgen.carver.CarvingContext +1M -1M | +1P
```
```
XXX.levelgen.feature.NetherForestVegetationFeature -1M
```
```
XXX.levelgen.feature.OceanMonumentFeature +2M -2M
```
```
XXX.levelgen.feature.PillagerOutpostFeature +3M -3M
```
```
XXX.levelgen.feature.StructureFeature +3M -4M
```
```
XXX.levelgen.feature.TwistingVinesFeature -2M
```
```
XXX.level.portal.PortalForcer +7M -6M
```

</details>
















































































































































































<details>
<summary>
net.minecraft.core.MappedRegistry$RegistryEntry
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- int id()
- Object value()
- ResourceKey key()
- String toString()
```

</details>


<details>
<summary>
net.minecraft.core.RegistryAccess
</summary>

```diff
- Iterable knownRegistries()
+ void addBuiltinElements(RegistryAccess$RegistryHolder,RegistryReadOps$ResourceAccess$MemoryMap,RegistryAccess$RegistryData)
- void addBuiltinElements(RegistryAccess$RegistryHolder,RegistryResourceAccess$InMemoryStorage,RegistryAccess$RegistryData)
```

</details>



































<details>
<summary>
net.minecraft.data.BuiltinRegistries
</summary>

```diff
- Biome lambda$static$2()
+ Biome lambda$static$3()
+ ConfiguredFeature lambda$static$1()
- StructureProcessorList lambda$static$1()
+ StructureProcessorList lambda$static$2()
- void lambda$static$3(ResourceLocation,Supplier)
+ void lambda$static$4(ResourceLocation,Supplier)
```

</details>







<details>
<summary>
net.minecraft.data.worldgen.NoiseData
</summary>

```diff
+ void registerBiomeNoises(int,ResourceKey,ResourceKey,ResourceKey,ResourceKey,ResourceKey,ResourceKey)
- void registerBiomeNoises(int,ResourceKey,ResourceKey,ResourceKey,ResourceKey)
```

</details>




<details>
<summary>
net.minecraft.data.worldgen.TerrainProvider
</summary>

```diff
+ TerrainShaper overworld()
- TerrainShaper overworld(boolean)
```

</details>















































































































































































































<details>
<summary>
net.minecraft.resources.RegistryReadOps$1
</summary>

```diff
- void <init>(Registry,ResourceKey)
+ void <init>(RegistryReadOps,WritableRegistry,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.resources.ResourceKey
</summary>

```diff
- Optional cast(ResourceKey)
```

</details>








































<details>
<summary>
net.minecraft.server.commands.JfrCommand
</summary>

```diff
+ Style lambda$stopJfr$4(File,Style)
- Style lambda$stopJfr$4(Path,Style)
```

</details>














































































































<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
- void addWorldborderListener(ServerLevel)
+ void setLevel(ServerLevel)
```

</details>






































<details>
<summary>
net.minecraft.util.CubicSpline
</summary>

```diff
- CubicSpline$Builder builder(ToFloatFunction,ToFloatFunction)
```

</details>
<details>
<summary>
net.minecraft.util.CubicSpline$Builder
</summary>

```diff
- float lambda$new$0(Float)
- void <init>(ToFloatFunction,ToFloatFunction)
```

</details>




















<details>
<summary>
net.minecraft.util.StringRepresentable$1
</summary>

```diff
+ DataResult decode(DynamicOps,Object)
+ DataResult encode(Object,DynamicOps,Object)
+ DataResult encode(StringRepresentable,DynamicOps,Object)
+ DataResult lambda$decode$0(Number)
+ DataResult lambda$decode$1(IntFunction,Number)
+ DataResult lambda$decode$3(String)
+ DataResult lambda$decode$4(Function,String)
+ Pair lambda$decode$2(DynamicOps,StringRepresentable)
+ Pair lambda$decode$5(DynamicOps,StringRepresentable)
- Stream keys(DynamicOps)
+ String toString()
- void <init>(StringRepresentable[])
+ void <init>(ToIntFunction,IntFunction,Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSource
</summary>

```diff
- boolean lambda$buildFeaturesPerStep$2(int,BiomeSource$1FeatureData)
+ boolean lambda$new$2(int,BiomeSource$1FeatureData)
+ ImmutableList featuresPerStep()
- int lambda$buildFeaturesPerStep$0(MutableInt,Object)
+ int lambda$new$0(MutableInt,Object)
- List buildFeaturesPerStep(List,boolean)
- List featuresPerStep()
- Set lambda$buildFeaturesPerStep$1(Comparator,BiomeSource$1FeatureData)
+ Set lambda$new$1(Comparator,BiomeSource$1FeatureData)
```

</details>







<details>
<summary>
net.minecraft.world.level.biome.Climate$RTree$Leaf
</summary>

```diff
- void <init>(Climate$ParameterPoint,Object)
+ void <init>(Climate$ParameterPoint,Supplier)
```

</details>





<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
- Biome lambda$getNoiseBiome$6()
+ Biome lambda$getNoiseBiome$7()
+ MultiNoiseBiomeSource$PresetInstance lambda$preset$6(Pair)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.TerrainShaper
</summary>

```diff
- CubicSpline buildErosionJaggednessSpline(float,float,float,float,ToFloatFunction)
+ CubicSpline buildErosionJaggednessSpline(float,float,float,float)
- CubicSpline buildErosionOffsetSpline(float,float,float,float,float,float,boolean,boolean,ToFloatFunction)
+ CubicSpline buildErosionOffsetSpline(float,float,float,float,float,float,boolean,boolean)
- CubicSpline buildMountainRidgeSplineWithPoints(float,boolean,ToFloatFunction)
+ CubicSpline buildMountainRidgeSplineWithPoints(float,boolean)
- CubicSpline buildRidgeJaggednessSpline(float,float,ToFloatFunction)
+ CubicSpline buildRidgeJaggednessSpline(float,float)
- CubicSpline buildWeirdnessJaggednessSpline(float,ToFloatFunction)
+ CubicSpline buildWeirdnessJaggednessSpline(float)
- CubicSpline getErosionFactor(float,boolean,ToFloatFunction)
+ CubicSpline getErosionFactor(float,boolean)
- CubicSpline ridgeSpline(float,float,float,float,float,float,ToFloatFunction)
+ CubicSpline ridgeSpline(float,float,float,float,float,float)
- float getAmplifiedFactor(float)
- float getAmplifiedJaggedness(float)
- float getAmplifiedOffset(float)
- float lambda$static$2(Float)
+ TerrainShaper overworld()
- TerrainShaper overworld(boolean)
```

</details>













































































































































































































































<details>
<summary>
net.minecraft.world.level.border.WorldBorder
</summary>

```diff
- BlockPos clampToBounds(double,double,double)
```

</details>











<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
- void <init>(Level,ChunkPos,UpgradeData,LevelChunkTicks,LevelChunkTicks,long,LevelChunkSection[],Consumer,BlendingData)
+ void <init>(Level,ChunkPos,UpgradeData,LevelChunkTicks,LevelChunkTicks,long,LevelChunkSection[],Consumer,GenerationUpgradeData)
```

</details>









<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
- void <init>(ChunkPos,UpgradeData,LevelChunkSection[],ProtoChunkTicks,ProtoChunkTicks,LevelHeightAccessor,Registry,BlendingData)
+ void <init>(ChunkPos,UpgradeData,LevelChunkSection[],ProtoChunkTicks,ProtoChunkTicks,LevelHeightAccessor,Registry,GenerationUpgradeData)
- void <init>(ChunkPos,UpgradeData,LevelHeightAccessor,Registry,BlendingData)
+ void <init>(ChunkPos,UpgradeData,LevelHeightAccessor,Registry,GenerationUpgradeData)
```

</details>














































<details>
<summary>
net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
</summary>

```diff
- BlockPredicate insideWorld(Vec3i)
+ BlockPredicate matchesBlock(Block,BlockPos)
- BlockPredicate matchesBlock(Block,Vec3i)
+ BlockPredicate matchesBlocks(List,BlockPos)
- BlockPredicate matchesBlocks(List,Vec3i)
+ BlockPredicate matchesFluid(Fluid,BlockPos)
- BlockPredicate matchesFluid(Fluid,Vec3i)
+ BlockPredicate matchesFluids(List,BlockPos)
- BlockPredicate matchesFluids(List,Vec3i)
+ BlockPredicate replaceable(BlockPos)
- BlockPredicate replaceable(Vec3i)
- BlockPredicate solid()
- BlockPredicate solid(Vec3i)
+ BlockPredicate wouldSurvive(BlockState,BlockPos)
- BlockPredicate wouldSurvive(BlockState,Vec3i)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarvingContext
</summary>

```diff
- void <init>(NoiseBasedChunkGenerator,RegistryAccess,LevelHeightAccessor,NoiseChunk)
+ void <init>(NoiseBasedChunkGenerator,RegistryAccess,LevelHeightAccessor)
```

</details>
















<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
</summary>

```diff
+ boolean place(LevelAccessor,Random,BlockPos,BlockPileConfiguration,int,int)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,JigsawConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,JigsawConfiguration,LevelHeightAccessor)
- boolean isNearVillage(ChunkGenerator,long,ChunkPos)
+ boolean isNearVillage(ChunkGenerator,long,WorldgenRandom,ChunkPos)
```

</details>










<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- ChunkPos getPotentialFeatureChunk(StructureFeatureConfiguration,long,int,int)
+ ChunkPos getPotentialFeatureChunk(StructureFeatureConfiguration,long,WorldgenRandom,int,int)
- StructureStart generate(RegistryAccess,ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,int,StructureFeatureConfiguration,FeatureConfiguration,LevelHeightAccessor,Predicate)
+ StructureStart generate(RegistryAccess,ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,int,WorldgenRandom,StructureFeatureConfiguration,FeatureConfiguration,LevelHeightAccessor,Predicate)
+ void lambda$generate$2(long,ChunkPos,WorldgenRandom)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
</summary>

```diff
+ boolean place(LevelAccessor,Random,BlockPos,int,int,int)
+ void placeTwistingVines(LevelAccessor,Random,BlockPos,int,int,int)
```

</details>






































































































































<details>
<summary>
net.minecraft.world.level.portal.PortalForcer
</summary>

```diff
+ BlockUtil$FoundRectangle lambda$findPortalAround$5(PoiRecord)
- BlockUtil$FoundRectangle lambda$findPortalAround$6(PoiRecord)
- boolean lambda$findPortalAround$1(WorldBorder,PoiRecord)
+ boolean lambda$findPortalAround$3(PoiRecord)
+ boolean lambda$findPortalAround$4(BlockState,BlockPos)
- boolean lambda$findPortalAround$4(PoiRecord)
- boolean lambda$findPortalAround$5(BlockState,BlockPos)
+ double lambda$findPortalAround$1(BlockPos,PoiRecord)
- double lambda$findPortalAround$2(BlockPos,PoiRecord)
+ int lambda$findPortalAround$2(PoiRecord)
- int lambda$findPortalAround$3(PoiRecord)
- Optional findPortalAround(BlockPos,boolean,WorldBorder)
+ Optional findPortalAround(BlockPos,boolean)
```

</details>













































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.data.info.package-info
- net.minecraft.data.info.WorldgenRegistryDumpReport
- net.minecraft.data.loot.BlockLoot
+ net.minecraft.data.loot.ChestLoot
- net.minecraft.data.loot.EntityLoot
+ net.minecraft.data.loot.FishingLoot
- net.minecraft.data.loot.GiftLoot
+ net.minecraft.data.loot.LootTableProvider
+ net.minecraft.data.loot.package-info
- net.minecraft.data.loot.PiglinBarterLoot
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ net.minecraft.data.models.BlockModelGenerators$TintState
- net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
+ net.minecraft.data.models.blockstates.PropertyDispatch$C1
- net.minecraft.data.models.blockstates.PropertyDispatch$C2
+ net.minecraft.data.models.blockstates.PropertyDispatch$C3
- net.minecraft.data.models.blockstates.PropertyDispatch$C4
+ net.minecraft.data.models.blockstates.PropertyDispatch$C5
- net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
+ net.minecraft.data.models.blockstates.Selector
- net.minecraft.data.models.blockstates.Variant
+ net.minecraft.data.models.blockstates.VariantProperties
- net.minecraft.data.models.blockstates.VariantProperties$Rotation
+ net.minecraft.data.models.blockstates.VariantProperty
- net.minecraft.data.models.blockstates.VariantProperty$Value
+ net.minecraft.data.models.ItemModelGenerators
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
+ net.minecraft.data.models.package-info
- net.minecraft.data.package-info
+ net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.RecipeBuilder
+ net.minecraft.data.recipes.RecipeProvider
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapedRecipeBuilder$Result
- net.minecraft.data.recipes.ShapelessRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
- net.minecraft.data.recipes.SingleItemRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
- net.minecraft.data.recipes.SpecialRecipeBuilder
+ net.minecraft.data.recipes.SpecialRecipeBuilder$1
- net.minecraft.data.recipes.UpgradeRecipeBuilder
+ net.minecraft.data.recipes.UpgradeRecipeBuilder$Result
+ net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$StructureConversionException
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BlockTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.worldgen.BastionBridgePools
+ net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionHousingUnitsPools
+ net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionSharedPools
+ net.minecraft.data.worldgen.BastionTreasureRoomPools
+ net.minecraft.data.worldgen.biome.Biomes
- net.minecraft.data.worldgen.biome.EndBiomes
+ net.minecraft.data.worldgen.biome.NetherBiomes
- net.minecraft.data.worldgen.biome.OverworldBiomes
+ net.minecraft.data.worldgen.biome.package-info
- net.minecraft.data.worldgen.BiomeDefaultFeatures
+ net.minecraft.data.worldgen.Carvers
- net.minecraft.data.worldgen.DesertVillagePools
+ net.minecraft.data.worldgen.Features
- net.minecraft.data.worldgen.features.AquaticFeatures
- net.minecraft.data.worldgen.features.EndFeatures
- net.minecraft.data.worldgen.features.MiscOverworldFeatures
- net.minecraft.data.worldgen.features.OreFeatures
- net.minecraft.data.worldgen.features.package-info
- net.minecraft.data.worldgen.features.TreeFeatures
+ net.minecraft.data.worldgen.Features$Decorators
- net.minecraft.data.worldgen.placement.AquaticPlacements
- net.minecraft.data.worldgen.placement.EndPlacements
- net.minecraft.data.worldgen.placement.NetherPlacements
- net.minecraft.data.worldgen.placement.PlacementUtils
- net.minecraft.data.worldgen.placement.VegetationPlacements
+ net.minecraft.resources.RegistryReadOps$ResourceAccess
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
- net.minecraft.resources.RegistryResourceAccess
- net.minecraft.resources.RegistryResourceAccess$InMemoryStorage
- net.minecraft.resources.RegistryResourceAccess$ParsedEntry
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- net.minecraft.util.datafix.fixes.ChunkRenamesFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix2
+ net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
- net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
+ net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.MapIdFix
+ net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
- net.minecraft.util.datafix.fixes.MissingDimensionFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRename
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
- net.minecraft.util.datafix.fixes.RenameBiomesFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1451_7
- net.minecraft.util.datafix.schemas.V1460
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
+ net.minecraft.util.datafix.schemas.V2831
- net.minecraft.util.datafix.schemas.V2832
+ net.minecraft.util.datafix.schemas.V2842
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.ExtraCodecs$3
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.jfr.callback.package-info
+ net.minecraft.util.profiling.jfr.callback.ProfiledDuration
- net.minecraft.util.profiling.jfr.Environment
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
+ net.minecraft.util.profiling.jfr.event.package-info
- net.minecraft.util.profiling.jfr.event.PacketEvent
+ net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
- net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
+ net.minecraft.util.profiling.jfr.event.PacketSentEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
- net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
+ net.minecraft.util.profiling.jfr.JfrProfiler
- net.minecraft.util.profiling.jfr.JfrProfiler$1
+ net.minecraft.util.profiling.jfr.JvmProfiler
- net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
- net.minecraft.util.profiling.jfr.package-info
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
- net.minecraft.util.profiling.jfr.parse.JfrStatsResult
+ net.minecraft.util.profiling.jfr.parse.package-info
+ net.minecraft.util.profiling.jfr.Percentiles
- net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
+ net.minecraft.util.profiling.jfr.serialize.package-info
- net.minecraft.util.profiling.jfr.stats.ChunkGenStat
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketCountAndSize
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketIdentification
- net.minecraft.util.profiling.jfr.stats.package-info
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
- net.minecraft.util.profiling.jfr.stats.TimedStat
+ net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.stats.TimeStamped
- net.minecraft.util.profiling.jfr.SummaryReporter
+ net.minecraft.util.profiling.metrics.MetricCategory
- net.minecraft.util.profiling.metrics.MetricSampler
+ net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
- net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
+ net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
- net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ net.minecraft.util.profiling.metrics.MetricsRegistry
- net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ net.minecraft.util.profiling.metrics.MetricsSamplerProvider
+ net.minecraft.util.profiling.metrics.package-info
- net.minecraft.util.profiling.metrics.ProfilerMeasured
- net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.package-info
+ net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- net.minecraft.util.profiling.metrics.storage.MetricsPersister
- net.minecraft.util.profiling.metrics.storage.package-info
+ net.minecraft.util.profiling.metrics.storage.RecordedDeviation
+ net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.random.package-info
- net.minecraft.util.random.SimpleWeightedRandomList
+ net.minecraft.util.random.SimpleWeightedRandomList$Builder
- net.minecraft.util.random.Weight
+ net.minecraft.util.random.WeightedEntry
- net.minecraft.util.random.WeightedEntry$IntrusiveBase
+ net.minecraft.util.random.WeightedEntry$Wrapper
- net.minecraft.util.random.WeightedRandom
+ net.minecraft.util.random.WeightedRandomList
+ net.minecraft.util.StringUtil
- net.minecraft.util.TelemetryConstants
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.valueproviders.BiasedToBottomInt
+ net.minecraft.util.valueproviders.ClampedInt
- net.minecraft.util.valueproviders.ClampedNormalFloat
+ net.minecraft.util.valueproviders.ClampedNormalInt
- net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.IntProviderType
- net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.VisibleForDebug
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.ZeroBitStorage
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
- net.minecraft.world.damagesource.BadRespawnPointDamage
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.EntityDamageSource
- net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffects$1
+ net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AnimalPanic
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
- net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
+ net.minecraft.world.entity.ai.behavior.LongJumpMidJump
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.RandomSwim
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunIf
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.RunSometimes
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
- net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
+ net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
- net.minecraft.world.entity.ai.goal.target.package-info
- net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
+ net.minecraft.world.entity.ai.goal.target.TargetGoal
+ net.minecraft.world.entity.ai.goal.TemptGoal
- net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
+ net.minecraft.world.entity.ai.goal.TryFindWaterGoal
- net.minecraft.world.entity.ai.goal.UseItemGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
+ net.minecraft.world.entity.ai.goal.WrappedGoal
- net.minecraft.world.entity.ai.goal.ZombieAttackGoal
+ net.minecraft.world.entity.ai.gossip.GossipContainer
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
+ net.minecraft.world.entity.animal.Fox$FaceplantGoal
- net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
+ net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
- net.minecraft.world.entity.animal.Fox$FoxBreedGoal
+ net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
- net.minecraft.world.entity.animal.Fox$FoxFloatGoal
+ net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
- net.minecraft.world.entity.animal.Fox$FoxGroupData
+ net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
- net.minecraft.world.entity.animal.Fox$FoxLookControl
+ net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
- net.minecraft.world.entity.animal.Fox$FoxMoveControl
+ net.minecraft.world.entity.animal.Fox$FoxPanicGoal
- net.minecraft.world.entity.animal.Fox$FoxPounceGoal
+ net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
- net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
+ net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
- net.minecraft.world.entity.animal.Fox$SeekShelterGoal
+ net.minecraft.world.entity.animal.Fox$SleepGoal
- net.minecraft.world.entity.animal.Fox$StalkPreyGoal
+ net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.goat.Goat
+ net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
- net.minecraft.world.entity.animal.goat.Goat$GoatPathNavigation
+ net.minecraft.world.entity.animal.goat.GoatAi
- net.minecraft.world.entity.animal.goat.package-info
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
- net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
+ net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
- net.minecraft.world.entity.animal.horse.Markings
+ net.minecraft.world.entity.animal.horse.Mule
- net.minecraft.world.entity.animal.horse.package-info
- net.minecraft.world.entity.animal.horse.SkeletonHorse
+ net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
- net.minecraft.world.entity.animal.horse.TraderLlama
+ net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.animal.horse.Variant
+ net.minecraft.world.entity.animal.horse.ZombieHorse
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.boss.enderdragon.EndCrystal
- net.minecraft.world.entity.boss.enderdragon.EnderDragon
+ net.minecraft.world.entity.boss.enderdragon.package-info
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
- net.minecraft.world.entity.boss.enderdragon.phases.package-info
- net.minecraft.world.entity.boss.EnderDragonPart
+ net.minecraft.world.entity.boss.package-info
- net.minecraft.world.entity.boss.wither.package-info
- net.minecraft.world.entity.boss.wither.WitherBoss
+ net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
+ net.minecraft.world.entity.decoration.ArmorStand
- net.minecraft.world.entity.decoration.ArmorStand$1
+ net.minecraft.world.entity.decoration.GlowItemFrame
- net.minecraft.world.entity.decoration.HangingEntity
+ net.minecraft.world.entity.decoration.HangingEntity$1
- net.minecraft.world.entity.decoration.ItemFrame
+ net.minecraft.world.entity.decoration.ItemFrame$1
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$1
+ net.minecraft.world.entity.EntityType$Builder
- net.minecraft.world.entity.EntityType$EntityFactory
+ net.minecraft.world.entity.EquipmentSlot
- net.minecraft.world.entity.EquipmentSlot$Type
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LerpingModel
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.ContainerSynchronizer
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.item.AdventureModeCheck
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$11
- net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$2
- net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$4
- net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$6
- net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$8
- net.minecraft.world.item.CreativeModeTab$9
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
- net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockCollisions
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EntityBasedExplosionDamageCalculator
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.ExplosionDamageCalculator
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.GameRules
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$PositionedBlendingData
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.blending.BlendingData$1
+ net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
+ net.minecraft.world.level.levelgen.blending.GenerationUpgradeData
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
- net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
+ net.minecraft.world.level.levelgen.Density
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RangeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ScatterDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
- net.minecraft.world.level.levelgen.feature.DripstoneUtils
+ net.minecraft.world.level.levelgen.feature.EndCityFeature
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
- net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.GlowLichenFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.JigsawFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.FlatLevelSource
+ net.minecraft.world.level.levelgen.GenerationStep
- net.minecraft.world.level.levelgen.GenerationStep$Carving
+ net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.GeodeBlockSettings
+ net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.GeodeLayerSettings
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
- net.minecraft.world.level.levelgen.LegacyRandomSource
+ net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$InterpolatableNoise
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseFiller
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
+ net.minecraft.world.level.levelgen.NoiseChunk$Sampler
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.Noises
+ net.minecraft.world.level.levelgen.NoiseSampler
- net.minecraft.world.level.levelgen.NoiseSampler$FlatNoiseData
+ net.minecraft.world.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.NoiseSampler$VeinType
+ net.minecraft.world.level.levelgen.NoiseSamplingSettings
- net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.NoiseSlider
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.BlockFilterDecorator
- net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceDecorator
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
+ net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
- net.minecraft.world.level.levelgen.placement.CountPlacement
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EnvironmentScanDecorator
+ net.minecraft.world.level.levelgen.placement.FilterDecorator
+ net.minecraft.world.level.levelgen.placement.HeightmapDecorator
- net.minecraft.world.level.levelgen.placement.HeightRangePlacement
- net.minecraft.world.level.levelgen.placement.InSquarePlacement
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
- net.minecraft.world.level.levelgen.placement.PlacementContext
- net.minecraft.world.level.levelgen.placement.PlacementModifier
- net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
+ net.minecraft.world.level.levelgen.placement.RangeDecorator
- net.minecraft.world.level.levelgen.placement.RepeatingPlacement
+ net.minecraft.world.level.levelgen.placement.ScatterDecorator
+ net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdConfiguration
- net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
+ net.minecraft.world.level.levelgen.placement.VerticalDecorator
+ net.minecraft.world.level.levelgen.placement.WaterDepthThresholdDecorator
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.RandomSource
+ net.minecraft.world.level.levelgen.RandomSupport
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.StructureSettings
+ net.minecraft.world.level.levelgen.SurfaceRules
- net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Condition
- net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Context
- net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Hole
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$StateRule
- net.minecraft.world.level.levelgen.SurfaceRules$Steep
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
- net.minecraft.world.level.levelgen.SurfaceRules$Temperature
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRule
- net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ net.minecraft.world.level.levelgen.SurfaceSystem
- net.minecraft.world.level.levelgen.SurfaceSystem$1
+ net.minecraft.world.level.levelgen.TerrainInfo
- net.minecraft.world.level.levelgen.VerticalAnchor
+ net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
- net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
+ net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
+ net.minecraft.world.level.levelgen.WorldGenerationContext
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelHeightAccessor$1
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.SpawnData$CustomSpawnRules
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +1P -1P
```
```
XXX.screens.worldselection.WorldGenSettingsComponent +10M -9M | +2P
```
```
XXX.minecraft.core.MappedRegistry +8M -9M
```
```
XXX.minecraft.core.Registry +9M -7M | +3P -2P
```
```
XXX.minecraft.core.RegistryAccess$RegistryData +3M
```
```
XXX.minecraft.core.Vec3i +3M
```
```
XXX.minecraft.resources.RegistryReadOps$1 +1M -1M | +1P -2P
```
```
XXX.minecraft.resources.ResourceKey +1M
```
```
XXX.server.commands.JfrCommand +1M -1M
```
```
XXX.server.players.PlayerList +1M -1M
```
```
XXX.minecraft.util.CubicSpline +1M
```
```
XXX.minecraft.util.CubicSpline$Builder +2M | +1P
```
```
XXX.minecraft.util.StringRepresentable$1 +2M -11M | +1P -3P
```
```
XXX.level.biome.BiomeSource +5M -4M | +1P -1P
```
```
XXX.level.biome.Climate$RTree$Leaf +1M -1M | +1P -1P
```
```
XXX.level.biome.MultiNoiseBiomeSource +1M -2M
```
```
XXX.level.biome.MultiNoiseBiomeSource$PresetInstance +3M
```
```
XXX.level.biome.TerrainShaper +12M -8M | +1P
```
```
XXX.level.border.WorldBorder +1M
```
```
XXX.level.chunk.LevelChunk +1M -1M
```
```
XXX.level.chunk.ProtoChunk +2M -2M
```
```
XXX.levelgen.blockpredicates.BlockPredicate +9M -6M | +2P
```
```
XXX.levelgen.carver.CarvingContext +1M -1M | +1P
```
```
XXX.levelgen.feature.NetherForestVegetationFeature -1M
```
```
XXX.levelgen.feature.OceanMonumentFeature +2M -2M
```
```
XXX.levelgen.feature.PillagerOutpostFeature +3M -3M
```
```
XXX.levelgen.feature.StructureFeature +3M -4M
```
```
XXX.levelgen.feature.TwistingVinesFeature -2M
```
```
XXX.level.portal.PortalForcer +7M -6M
```

</details>















































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
</summary>

```diff
+ DataResult lambda$updateDataPacks$10(RegistryReadOps,JsonElement)
- DataResult lambda$updateDataPacks$11(RegistryReadOps,JsonElement)
- MutableComponent lambda$init$3(CycleButton)
- void lambda$init$10(CreateWorldScreen,Minecraft,Button)
+ void lambda$init$3(CreateWorldScreen,CycleButton,WorldPreset)
+ void lambda$init$4(Button)
- void lambda$init$4(CreateWorldScreen,CycleButton,WorldPreset)
- void lambda$init$5(Button)
+ void lambda$init$5(Minecraft,CreateWorldScreen,Button)
+ void lambda$init$6(CycleButton,Boolean)
- void lambda$init$6(Minecraft,CreateWorldScreen,Button)
- void lambda$init$7(CycleButton,Boolean)
+ void lambda$init$7(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,WorldGenSettings,boolean)
+ void lambda$init$8(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,Lifecycle,WorldGenSettings)
- void lambda$init$8(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,WorldGenSettings,boolean)
+ void lambda$init$9(CreateWorldScreen,Minecraft,Button)
- void lambda$init$9(Minecraft,CreateWorldScreen,RegistryAccess$RegistryHolder,Lifecycle,WorldGenSettings)
+ void lambda$updateDataPacks$11(RegistryAccess$RegistryHolder,WorldGenSettings)
- void lambda$updateDataPacks$12(RegistryAccess$RegistryHolder,WorldGenSettings)
```

</details>












































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
- App lambda$withNameAndId$1(ResourceKey,MapCodec,RecordCodecBuilder$Instance)
+ App lambda$withNameAndId$3(ResourceKey,MapCodec,RecordCodecBuilder$Instance)
+ Integer lambda$withNameAndId$1(MappedRegistry$RegistryEntry)
- List lambda$networkCodec$4(MappedRegistry)
+ List lambda$networkCodec$5(MappedRegistry)
- Map lambda$directCodec$7(MappedRegistry)
+ Map lambda$directCodec$8(MappedRegistry)
- MappedRegistry lambda$directCodec$6(ResourceKey,Lifecycle,Map)
+ MappedRegistry lambda$directCodec$7(ResourceKey,Lifecycle,Map)
- MappedRegistry lambda$networkCodec$3(ResourceKey,Lifecycle,List)
+ MappedRegistry lambda$networkCodec$4(ResourceKey,Lifecycle,List)
+ Object lambda$withNameAndId$2(MappedRegistry$RegistryEntry)
- Object[] lambda$getRandom$2(int)
+ ResourceKey lambda$withNameAndId$0(MappedRegistry$RegistryEntry)
- void lambda$directCodec$5(MappedRegistry,Lifecycle,ResourceKey,Object)
+ void lambda$directCodec$6(MappedRegistry,Lifecycle,ResourceKey,Object)
- void lambda$new$0(Object2IntOpenCustomHashMap)
```

</details>


<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
- Codec byNameCodec()
+ DataResult decode(DynamicOps,Object)
+ DataResult encode(Object,DynamicOps,Object)
- DataResult lambda$byNameCodec$56(ResourceLocation)
- DataResult lambda$byNameCodec$57(ResourceLocation)
- DataResult lambda$byNameCodec$58(Object)
- DataResult lambda$byNameCodec$59(Object)
+ DataResult lambda$decode$56(Number)
+ DataResult lambda$decode$58(Pair)
+ FeatureDecorator lambda$static$43()
- int lambda$byNameCodec$60(Object)
- Lifecycle lambda$byNameCodec$61(Object)
+ Object lambda$keys$59(DynamicOps,ResourceLocation)
- Object lambda$keys$62(DynamicOps,ResourceLocation)
+ Pair lambda$decode$57(DynamicOps,Object)
- PlacementModifierType lambda$static$43()
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess$RegistryData
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- String toString()
```

</details>


<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
- Codec offsetCodec(int)
- DataResult lambda$checkOffsetAxes$3(int,Vec3i)
- Function checkOffsetAxes(int)
```

</details>
































































































































































































































































<details>
<summary>
net.minecraft.resources.RegistryReadOps$1
</summary>

```diff
- void <init>(Registry,ResourceKey)
+ void <init>(RegistryReadOps,WritableRegistry,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.resources.ResourceKey
</summary>

```diff
- Optional cast(ResourceKey)
```

</details>








































<details>
<summary>
net.minecraft.server.commands.JfrCommand
</summary>

```diff
+ Style lambda$stopJfr$4(File,Style)
- Style lambda$stopJfr$4(Path,Style)
```

</details>














































































































<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
- void addWorldborderListener(ServerLevel)
+ void setLevel(ServerLevel)
```

</details>






































<details>
<summary>
net.minecraft.util.CubicSpline
</summary>

```diff
- CubicSpline$Builder builder(ToFloatFunction,ToFloatFunction)
```

</details>
<details>
<summary>
net.minecraft.util.CubicSpline$Builder
</summary>

```diff
- float lambda$new$0(Float)
- void <init>(ToFloatFunction,ToFloatFunction)
```

</details>




















<details>
<summary>
net.minecraft.util.StringRepresentable$1
</summary>

```diff
+ DataResult decode(DynamicOps,Object)
+ DataResult encode(Object,DynamicOps,Object)
+ DataResult encode(StringRepresentable,DynamicOps,Object)
+ DataResult lambda$decode$0(Number)
+ DataResult lambda$decode$1(IntFunction,Number)
+ DataResult lambda$decode$3(String)
+ DataResult lambda$decode$4(Function,String)
+ Pair lambda$decode$2(DynamicOps,StringRepresentable)
+ Pair lambda$decode$5(DynamicOps,StringRepresentable)
- Stream keys(DynamicOps)
+ String toString()
- void <init>(StringRepresentable[])
+ void <init>(ToIntFunction,IntFunction,Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSource
</summary>

```diff
- boolean lambda$buildFeaturesPerStep$2(int,BiomeSource$1FeatureData)
+ boolean lambda$new$2(int,BiomeSource$1FeatureData)
+ ImmutableList featuresPerStep()
- int lambda$buildFeaturesPerStep$0(MutableInt,Object)
+ int lambda$new$0(MutableInt,Object)
- List buildFeaturesPerStep(List,boolean)
- List featuresPerStep()
- Set lambda$buildFeaturesPerStep$1(Comparator,BiomeSource$1FeatureData)
+ Set lambda$new$1(Comparator,BiomeSource$1FeatureData)
```

</details>







<details>
<summary>
net.minecraft.world.level.biome.Climate$RTree$Leaf
</summary>

```diff
- void <init>(Climate$ParameterPoint,Object)
+ void <init>(Climate$ParameterPoint,Supplier)
```

</details>





<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
- Biome lambda$getNoiseBiome$6()
+ Biome lambda$getNoiseBiome$7()
+ MultiNoiseBiomeSource$PresetInstance lambda$preset$6(Pair)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.TerrainShaper
</summary>

```diff
- CubicSpline buildErosionJaggednessSpline(float,float,float,float,ToFloatFunction)
+ CubicSpline buildErosionJaggednessSpline(float,float,float,float)
- CubicSpline buildErosionOffsetSpline(float,float,float,float,float,float,boolean,boolean,ToFloatFunction)
+ CubicSpline buildErosionOffsetSpline(float,float,float,float,float,float,boolean,boolean)
- CubicSpline buildMountainRidgeSplineWithPoints(float,boolean,ToFloatFunction)
+ CubicSpline buildMountainRidgeSplineWithPoints(float,boolean)
- CubicSpline buildRidgeJaggednessSpline(float,float,ToFloatFunction)
+ CubicSpline buildRidgeJaggednessSpline(float,float)
- CubicSpline buildWeirdnessJaggednessSpline(float,ToFloatFunction)
+ CubicSpline buildWeirdnessJaggednessSpline(float)
- CubicSpline getErosionFactor(float,boolean,ToFloatFunction)
+ CubicSpline getErosionFactor(float,boolean)
- CubicSpline ridgeSpline(float,float,float,float,float,float,ToFloatFunction)
+ CubicSpline ridgeSpline(float,float,float,float,float,float)
- float getAmplifiedFactor(float)
- float getAmplifiedJaggedness(float)
- float getAmplifiedOffset(float)
- float lambda$static$2(Float)
+ TerrainShaper overworld()
- TerrainShaper overworld(boolean)
```

</details>













































































































































































































































<details>
<summary>
net.minecraft.world.level.border.WorldBorder
</summary>

```diff
- BlockPos clampToBounds(double,double,double)
```

</details>











<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
- void <init>(Level,ChunkPos,UpgradeData,LevelChunkTicks,LevelChunkTicks,long,LevelChunkSection[],Consumer,BlendingData)
+ void <init>(Level,ChunkPos,UpgradeData,LevelChunkTicks,LevelChunkTicks,long,LevelChunkSection[],Consumer,GenerationUpgradeData)
```

</details>









<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
- void <init>(ChunkPos,UpgradeData,LevelChunkSection[],ProtoChunkTicks,ProtoChunkTicks,LevelHeightAccessor,Registry,BlendingData)
+ void <init>(ChunkPos,UpgradeData,LevelChunkSection[],ProtoChunkTicks,ProtoChunkTicks,LevelHeightAccessor,Registry,GenerationUpgradeData)
- void <init>(ChunkPos,UpgradeData,LevelHeightAccessor,Registry,BlendingData)
+ void <init>(ChunkPos,UpgradeData,LevelHeightAccessor,Registry,GenerationUpgradeData)
```

</details>














































<details>
<summary>
net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
</summary>

```diff
- BlockPredicate insideWorld(Vec3i)
+ BlockPredicate matchesBlock(Block,BlockPos)
- BlockPredicate matchesBlock(Block,Vec3i)
+ BlockPredicate matchesBlocks(List,BlockPos)
- BlockPredicate matchesBlocks(List,Vec3i)
+ BlockPredicate matchesFluid(Fluid,BlockPos)
- BlockPredicate matchesFluid(Fluid,Vec3i)
+ BlockPredicate matchesFluids(List,BlockPos)
- BlockPredicate matchesFluids(List,Vec3i)
+ BlockPredicate replaceable(BlockPos)
- BlockPredicate replaceable(Vec3i)
- BlockPredicate solid()
- BlockPredicate solid(Vec3i)
+ BlockPredicate wouldSurvive(BlockState,BlockPos)
- BlockPredicate wouldSurvive(BlockState,Vec3i)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarvingContext
</summary>

```diff
- void <init>(NoiseBasedChunkGenerator,RegistryAccess,LevelHeightAccessor,NoiseChunk)
+ void <init>(NoiseBasedChunkGenerator,RegistryAccess,LevelHeightAccessor)
```

</details>
















<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
</summary>

```diff
+ boolean place(LevelAccessor,Random,BlockPos,BlockPileConfiguration,int,int)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,JigsawConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,JigsawConfiguration,LevelHeightAccessor)
- boolean isNearVillage(ChunkGenerator,long,ChunkPos)
+ boolean isNearVillage(ChunkGenerator,long,WorldgenRandom,ChunkPos)
```

</details>










<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- ChunkPos getPotentialFeatureChunk(StructureFeatureConfiguration,long,int,int)
+ ChunkPos getPotentialFeatureChunk(StructureFeatureConfiguration,long,WorldgenRandom,int,int)
- StructureStart generate(RegistryAccess,ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,int,StructureFeatureConfiguration,FeatureConfiguration,LevelHeightAccessor,Predicate)
+ StructureStart generate(RegistryAccess,ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,int,WorldgenRandom,StructureFeatureConfiguration,FeatureConfiguration,LevelHeightAccessor,Predicate)
+ void lambda$generate$2(long,ChunkPos,WorldgenRandom)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
</summary>

```diff
+ boolean place(LevelAccessor,Random,BlockPos,int,int,int)
+ void placeTwistingVines(LevelAccessor,Random,BlockPos,int,int,int)
```

</details>






































































































































<details>
<summary>
net.minecraft.world.level.portal.PortalForcer
</summary>

```diff
+ BlockUtil$FoundRectangle lambda$findPortalAround$5(PoiRecord)
- BlockUtil$FoundRectangle lambda$findPortalAround$6(PoiRecord)
- boolean lambda$findPortalAround$1(WorldBorder,PoiRecord)
+ boolean lambda$findPortalAround$3(PoiRecord)
+ boolean lambda$findPortalAround$4(BlockState,BlockPos)
- boolean lambda$findPortalAround$4(PoiRecord)
- boolean lambda$findPortalAround$5(BlockState,BlockPos)
+ double lambda$findPortalAround$1(BlockPos,PoiRecord)
- double lambda$findPortalAround$2(BlockPos,PoiRecord)
+ int lambda$findPortalAround$2(PoiRecord)
- int lambda$findPortalAround$3(PoiRecord)
- Optional findPortalAround(BlockPos,boolean,WorldBorder)
+ Optional findPortalAround(BlockPos,boolean)
```

</details>
</details>