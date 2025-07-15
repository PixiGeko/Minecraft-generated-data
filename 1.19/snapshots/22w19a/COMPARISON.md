## Comparison with [22w18a](https://github.com/PixiGeko/Minecraft-generated-data/tree/22w18a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">22w18a</th><th>22w19a</th></tr><tr><td>World version</td><td><pre>3095</pre></td><td><pre>3096</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741907</pre></td><td><pre>1073741908</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">22w18a</th><th>22w19a</th></tr><tr><td>com.mojang:authlib</td><td><pre>3.4.40</pre></td><td><pre>3.5.41</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- chat_type.txt
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
+ minecraft:template_mirror
+ minecraft:template_rotation
```

</details>
<details>
<summary>
point_of_interest_type
</summary>

```diff
- minecraft:nitwit
- minecraft:unemployed
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- universal_tags/chat_type.json
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:template_mirror
+ minecraft:template_rotation
```

</details>
<details>
<summary>
universal_tags/point_of_interest_type.json
</summary>

```diff
- minecraft:nitwit
- minecraft:unemployed
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- locatebiome.txt
```

</details>
<details>
<summary>
locate
</summary>

```diff
- locate <structure: resource_or_tag>
+ locate biome <biome: resource_or_tag>
+ locate poi <poi: resource_or_tag>
+ locate structure <structure: resource_or_tag>
```

</details>
<details>
<summary>
place
</summary>

```diff
+ place template <template: resource_location> <pos: block_pos> <rotation: template_rotation> <mirror: template_mirror> <integrity: float> <seed: integer>
```

</details>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ argument.enum.invalid: Invalid value "%s"
+ chat.preview: Type to preview
+ chatPreview.warning.check: Do not notify again for this server
+ chatPreview.warning.content: Chat Preview allows the server to see your messages in real time as you type them, even before they’re sent. This is often used to preview your message with styling applied.

Chat Preview is on by default, but can be turned off in Chat Settings.
+ chatPreview.warning.title: This server uses Chat Preview
+ chatPreview.warning.toast: This server uses Chat Preview and can see your messages as you type them, even before they're sent. You can turn this off in Chat Settings.
+ chatPreview.warning.toast.title: Chat Preview is enabled
+ commands.locate.biome.invalid: There is no biome with type "%s"
+ commands.locate.biome.not_found: Could not find a biome of type "%s" within reasonable distance
+ commands.locate.biome.success: The nearest %s is at %s (%s blocks away)
- commands.locate.failed: Could not find a structure of type "%s" nearby
- commands.locate.invalid: There is no structure with type "%s"
+ commands.locate.poi.invalid: There is no point of interest with type "%s"
+ commands.locate.poi.not_found: Could not find a point of interest of type "%s" within reasonable distance
+ commands.locate.poi.success: The nearest %s is at %s (%s blocks away)
+ commands.locate.structure.invalid: There is no structure with type "%s"
+ commands.locate.structure.not_found: Could not find a structure of type "%s" nearby
+ commands.locate.structure.success: The nearest %s is at %s (%s blocks away)
- commands.locate.success: The nearest %s is at %s (%s blocks away)
- commands.locatebiome.invalid: There is no biome with type "%s"
- commands.locatebiome.notFound: Could not find a biome of type "%s" within reasonable distance
- commands.locatebiome.success: The nearest %s is at %s (%s blocks away)
+ commands.place.template.failed: Failed to place template
+ commands.place.template.invalid: There is no template with id "%s"
+ commands.place.template.success: Loaded template "%s" at %s, %s, %s
+ options.chatPreview: Chat Preview
+ options.chatPreview.tooltip: Chat Preview allows servers to see your messages as you type, which allows them to style your message. You can still chat if you turn this off.
+ options.onlyShowSignedChat: Only Show Signed Chat
+ options.onlyShowSignedChat.tooltip: When enabled, the chat will always prefer to display securely signed messages. This means any alterations by the server such as styling might not be consistently displayed.
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
generated
</summary>

```diff
+ reports/minecraft/chat_type/chat.json
+ reports/minecraft/chat_type/emote_command.json
+ reports/minecraft/chat_type/game_info.json
+ reports/minecraft/chat_type/msg_command.json
+ reports/minecraft/chat_type/say_command.json
+ reports/minecraft/chat_type/system.json
+ reports/minecraft/chat_type/team_msg_command.json
+ reports/minecraft/chat_type/tellraw_command.json
+ reports/minecraft/dimension_type/overworld_caves.json
+ reports/minecraft/dimension_type/overworld.json
+ reports/minecraft/dimension_type/the_end.json
+ reports/minecraft/dimension_type/the_nether.json
+ reports/minecraft/worldgen/biome/badlands.json
+ reports/minecraft/worldgen/biome/bamboo_jungle.json
+ reports/minecraft/worldgen/biome/basalt_deltas.json
+ reports/minecraft/worldgen/biome/beach.json
+ reports/minecraft/worldgen/biome/birch_forest.json
+ reports/minecraft/worldgen/biome/cold_ocean.json
+ reports/minecraft/worldgen/biome/crimson_forest.json
+ reports/minecraft/worldgen/biome/dark_forest.json
+ reports/minecraft/worldgen/biome/deep_cold_ocean.json
+ reports/minecraft/worldgen/biome/deep_dark.json
+ reports/minecraft/worldgen/biome/deep_frozen_ocean.json
+ reports/minecraft/worldgen/biome/deep_lukewarm_ocean.json
+ reports/minecraft/worldgen/biome/deep_ocean.json
+ reports/minecraft/worldgen/biome/desert.json
+ reports/minecraft/worldgen/biome/dripstone_caves.json
+ reports/minecraft/worldgen/biome/end_barrens.json
+ reports/minecraft/worldgen/biome/end_highlands.json
+ reports/minecraft/worldgen/biome/end_midlands.json
+ reports/minecraft/worldgen/biome/eroded_badlands.json
+ reports/minecraft/worldgen/biome/flower_forest.json
+ reports/minecraft/worldgen/biome/forest.json
+ reports/minecraft/worldgen/biome/frozen_ocean.json
+ reports/minecraft/worldgen/biome/frozen_peaks.json
+ reports/minecraft/worldgen/biome/frozen_river.json
+ reports/minecraft/worldgen/biome/grove.json
+ reports/minecraft/worldgen/biome/ice_spikes.json
+ reports/minecraft/worldgen/biome/jagged_peaks.json
+ reports/minecraft/worldgen/biome/jungle.json
+ reports/minecraft/worldgen/biome/lukewarm_ocean.json
+ reports/minecraft/worldgen/biome/lush_caves.json
+ reports/minecraft/worldgen/biome/mangrove_swamp.json
+ reports/minecraft/worldgen/biome/meadow.json
+ reports/minecraft/worldgen/biome/mushroom_fields.json
+ reports/minecraft/worldgen/biome/nether_wastes.json
+ reports/minecraft/worldgen/biome/ocean.json
+ reports/minecraft/worldgen/biome/old_growth_birch_forest.json
+ reports/minecraft/worldgen/biome/old_growth_pine_taiga.json
+ reports/minecraft/worldgen/biome/old_growth_spruce_taiga.json
+ reports/minecraft/worldgen/biome/plains.json
+ reports/minecraft/worldgen/biome/river.json
+ reports/minecraft/worldgen/biome/savanna_plateau.json
+ reports/minecraft/worldgen/biome/savanna.json
+ reports/minecraft/worldgen/biome/small_end_islands.json
+ reports/minecraft/worldgen/biome/snowy_beach.json
+ reports/minecraft/worldgen/biome/snowy_plains.json
+ reports/minecraft/worldgen/biome/snowy_slopes.json
+ reports/minecraft/worldgen/biome/snowy_taiga.json
+ reports/minecraft/worldgen/biome/soul_sand_valley.json
+ reports/minecraft/worldgen/biome/sparse_jungle.json
+ reports/minecraft/worldgen/biome/stony_peaks.json
+ reports/minecraft/worldgen/biome/stony_shore.json
+ reports/minecraft/worldgen/biome/sunflower_plains.json
+ reports/minecraft/worldgen/biome/swamp.json
+ reports/minecraft/worldgen/biome/taiga.json
+ reports/minecraft/worldgen/biome/the_end.json
+ reports/minecraft/worldgen/biome/the_void.json
+ reports/minecraft/worldgen/biome/warm_ocean.json
+ reports/minecraft/worldgen/biome/warped_forest.json
+ reports/minecraft/worldgen/biome/windswept_forest.json
+ reports/minecraft/worldgen/biome/windswept_gravelly_hills.json
+ reports/minecraft/worldgen/biome/windswept_hills.json
+ reports/minecraft/worldgen/biome/windswept_savanna.json
+ reports/minecraft/worldgen/biome/wooded_badlands.json
+ reports/minecraft/worldgen/configured_carver/canyon.json
+ reports/minecraft/worldgen/configured_carver/cave_extra_underground.json
+ reports/minecraft/worldgen/configured_carver/cave.json
+ reports/minecraft/worldgen/configured_carver/nether_cave.json
+ reports/minecraft/worldgen/configured_feature/acacia.json
+ reports/minecraft/worldgen/configured_feature/amethyst_geode.json
+ reports/minecraft/worldgen/configured_feature/azalea_tree.json
+ reports/minecraft/worldgen/configured_feature/bamboo_no_podzol.json
+ reports/minecraft/worldgen/configured_feature/bamboo_some_podzol.json
+ reports/minecraft/worldgen/configured_feature/bamboo_vegetation.json
+ reports/minecraft/worldgen/configured_feature/basalt_blobs.json
+ reports/minecraft/worldgen/configured_feature/basalt_pillar.json
+ reports/minecraft/worldgen/configured_feature/birch_bees_0002.json
+ reports/minecraft/worldgen/configured_feature/birch_bees_002.json
+ reports/minecraft/worldgen/configured_feature/birch_bees_005.json
+ reports/minecraft/worldgen/configured_feature/birch_tall.json
+ reports/minecraft/worldgen/configured_feature/birch.json
+ reports/minecraft/worldgen/configured_feature/blackstone_blobs.json
+ reports/minecraft/worldgen/configured_feature/blue_ice.json
+ reports/minecraft/worldgen/configured_feature/bonus_chest.json
+ reports/minecraft/worldgen/configured_feature/cave_vine_in_moss.json
+ reports/minecraft/worldgen/configured_feature/cave_vine.json
+ reports/minecraft/worldgen/configured_feature/chorus_plant.json
+ reports/minecraft/worldgen/configured_feature/clay_pool_with_dripleaves.json
+ reports/minecraft/worldgen/configured_feature/clay_with_dripleaves.json
+ reports/minecraft/worldgen/configured_feature/crimson_forest_vegetation_bonemeal.json
+ reports/minecraft/worldgen/configured_feature/crimson_forest_vegetation.json
+ reports/minecraft/worldgen/configured_feature/crimson_fungus_planted.json
+ reports/minecraft/worldgen/configured_feature/crimson_fungus.json
+ reports/minecraft/worldgen/configured_feature/dark_forest_vegetation.json
+ reports/minecraft/worldgen/configured_feature/dark_oak.json
+ reports/minecraft/worldgen/configured_feature/delta.json
+ reports/minecraft/worldgen/configured_feature/desert_well.json
+ reports/minecraft/worldgen/configured_feature/disk_clay.json
+ reports/minecraft/worldgen/configured_feature/disk_grass.json
+ reports/minecraft/worldgen/configured_feature/disk_gravel.json
+ reports/minecraft/worldgen/configured_feature/disk_sand.json
+ reports/minecraft/worldgen/configured_feature/dripleaf.json
+ reports/minecraft/worldgen/configured_feature/dripstone_cluster.json
+ reports/minecraft/worldgen/configured_feature/end_gateway_delayed.json
+ reports/minecraft/worldgen/configured_feature/end_gateway_return.json
+ reports/minecraft/worldgen/configured_feature/end_island.json
+ reports/minecraft/worldgen/configured_feature/end_spike.json
+ reports/minecraft/worldgen/configured_feature/fancy_oak_bees_0002.json
+ reports/minecraft/worldgen/configured_feature/fancy_oak_bees_002.json
+ reports/minecraft/worldgen/configured_feature/fancy_oak_bees_005.json
+ reports/minecraft/worldgen/configured_feature/fancy_oak_bees.json
+ reports/minecraft/worldgen/configured_feature/fancy_oak.json
+ reports/minecraft/worldgen/configured_feature/flower_default.json
+ reports/minecraft/worldgen/configured_feature/flower_flower_forest.json
+ reports/minecraft/worldgen/configured_feature/flower_meadow.json
+ reports/minecraft/worldgen/configured_feature/flower_plain.json
+ reports/minecraft/worldgen/configured_feature/flower_swamp.json
+ reports/minecraft/worldgen/configured_feature/forest_flowers.json
+ reports/minecraft/worldgen/configured_feature/forest_rock.json
+ reports/minecraft/worldgen/configured_feature/fossil_coal.json
+ reports/minecraft/worldgen/configured_feature/fossil_diamonds.json
+ reports/minecraft/worldgen/configured_feature/freeze_top_layer.json
+ reports/minecraft/worldgen/configured_feature/glow_lichen.json
+ reports/minecraft/worldgen/configured_feature/glowstone_extra.json
+ reports/minecraft/worldgen/configured_feature/huge_brown_mushroom.json
+ reports/minecraft/worldgen/configured_feature/huge_red_mushroom.json
+ reports/minecraft/worldgen/configured_feature/ice_patch.json
+ reports/minecraft/worldgen/configured_feature/ice_spike.json
+ reports/minecraft/worldgen/configured_feature/iceberg_blue.json
+ reports/minecraft/worldgen/configured_feature/iceberg_packed.json
+ reports/minecraft/worldgen/configured_feature/jungle_bush.json
+ reports/minecraft/worldgen/configured_feature/jungle_tree_no_vine.json
+ reports/minecraft/worldgen/configured_feature/jungle_tree.json
+ reports/minecraft/worldgen/configured_feature/kelp.json
+ reports/minecraft/worldgen/configured_feature/lake_lava.json
+ reports/minecraft/worldgen/configured_feature/large_basalt_columns.json
+ reports/minecraft/worldgen/configured_feature/large_dripstone.json
+ reports/minecraft/worldgen/configured_feature/lush_caves_clay.json
+ reports/minecraft/worldgen/configured_feature/mangrove_vegetation.json
+ reports/minecraft/worldgen/configured_feature/mangrove.json
+ reports/minecraft/worldgen/configured_feature/meadow_trees.json
+ reports/minecraft/worldgen/configured_feature/mega_jungle_tree.json
+ reports/minecraft/worldgen/configured_feature/mega_pine.json
+ reports/minecraft/worldgen/configured_feature/mega_spruce.json
+ reports/minecraft/worldgen/configured_feature/monster_room.json
+ reports/minecraft/worldgen/configured_feature/moss_patch_bonemeal.json
+ reports/minecraft/worldgen/configured_feature/moss_patch_ceiling.json
+ reports/minecraft/worldgen/configured_feature/moss_patch.json
+ reports/minecraft/worldgen/configured_feature/moss_vegetation.json
+ reports/minecraft/worldgen/configured_feature/mushroom_island_vegetation.json
+ reports/minecraft/worldgen/configured_feature/nether_sprouts_bonemeal.json
+ reports/minecraft/worldgen/configured_feature/nether_sprouts.json
+ reports/minecraft/worldgen/configured_feature/oak_bees_0002.json
+ reports/minecraft/worldgen/configured_feature/oak_bees_002.json
+ reports/minecraft/worldgen/configured_feature/oak_bees_005.json
+ reports/minecraft/worldgen/configured_feature/oak.json
+ reports/minecraft/worldgen/configured_feature/ore_ancient_debris_large.json
+ reports/minecraft/worldgen/configured_feature/ore_ancient_debris_small.json
+ reports/minecraft/worldgen/configured_feature/ore_andesite.json
+ reports/minecraft/worldgen/configured_feature/ore_blackstone.json
+ reports/minecraft/worldgen/configured_feature/ore_clay.json
+ reports/minecraft/worldgen/configured_feature/ore_coal_buried.json
+ reports/minecraft/worldgen/configured_feature/ore_coal.json
+ reports/minecraft/worldgen/configured_feature/ore_copper_large.json
+ reports/minecraft/worldgen/configured_feature/ore_copper_small.json
+ reports/minecraft/worldgen/configured_feature/ore_diamond_buried.json
+ reports/minecraft/worldgen/configured_feature/ore_diamond_large.json
+ reports/minecraft/worldgen/configured_feature/ore_diamond_small.json
+ reports/minecraft/worldgen/configured_feature/ore_diorite.json
+ reports/minecraft/worldgen/configured_feature/ore_dirt.json
+ reports/minecraft/worldgen/configured_feature/ore_emerald.json
+ reports/minecraft/worldgen/configured_feature/ore_gold_buried.json
+ reports/minecraft/worldgen/configured_feature/ore_gold.json
+ reports/minecraft/worldgen/configured_feature/ore_granite.json
+ reports/minecraft/worldgen/configured_feature/ore_gravel_nether.json
+ reports/minecraft/worldgen/configured_feature/ore_gravel.json
+ reports/minecraft/worldgen/configured_feature/ore_infested.json
+ reports/minecraft/worldgen/configured_feature/ore_iron_small.json
+ reports/minecraft/worldgen/configured_feature/ore_iron.json
+ reports/minecraft/worldgen/configured_feature/ore_lapis_buried.json
+ reports/minecraft/worldgen/configured_feature/ore_lapis.json
+ reports/minecraft/worldgen/configured_feature/ore_magma.json
+ reports/minecraft/worldgen/configured_feature/ore_nether_gold.json
+ reports/minecraft/worldgen/configured_feature/ore_quartz.json
+ reports/minecraft/worldgen/configured_feature/ore_redstone.json
+ reports/minecraft/worldgen/configured_feature/ore_soul_sand.json
+ reports/minecraft/worldgen/configured_feature/ore_tuff.json
+ reports/minecraft/worldgen/configured_feature/patch_berry_bush.json
+ reports/minecraft/worldgen/configured_feature/patch_brown_mushroom.json
+ reports/minecraft/worldgen/configured_feature/patch_cactus.json
+ reports/minecraft/worldgen/configured_feature/patch_crimson_roots.json
+ reports/minecraft/worldgen/configured_feature/patch_dead_bush.json
+ reports/minecraft/worldgen/configured_feature/patch_fire.json
+ reports/minecraft/worldgen/configured_feature/patch_grass_jungle.json
+ reports/minecraft/worldgen/configured_feature/patch_grass.json
+ reports/minecraft/worldgen/configured_feature/patch_large_fern.json
+ reports/minecraft/worldgen/configured_feature/patch_melon.json
+ reports/minecraft/worldgen/configured_feature/patch_pumpkin.json
+ reports/minecraft/worldgen/configured_feature/patch_red_mushroom.json
+ reports/minecraft/worldgen/configured_feature/patch_soul_fire.json
+ reports/minecraft/worldgen/configured_feature/patch_sugar_cane.json
+ reports/minecraft/worldgen/configured_feature/patch_sunflower.json
+ reports/minecraft/worldgen/configured_feature/patch_taiga_grass.json
+ reports/minecraft/worldgen/configured_feature/patch_tall_grass.json
+ reports/minecraft/worldgen/configured_feature/patch_waterlily.json
+ reports/minecraft/worldgen/configured_feature/pile_hay.json
+ reports/minecraft/worldgen/configured_feature/pile_ice.json
+ reports/minecraft/worldgen/configured_feature/pile_melon.json
+ reports/minecraft/worldgen/configured_feature/pile_pumpkin.json
+ reports/minecraft/worldgen/configured_feature/pile_snow.json
+ reports/minecraft/worldgen/configured_feature/pine.json
+ reports/minecraft/worldgen/configured_feature/pointed_dripstone.json
+ reports/minecraft/worldgen/configured_feature/rooted_azalea_tree.json
+ reports/minecraft/worldgen/configured_feature/sculk_patch_ancient_city.json
+ reports/minecraft/worldgen/configured_feature/sculk_patch_deep_dark.json
+ reports/minecraft/worldgen/configured_feature/sculk_vein.json
+ reports/minecraft/worldgen/configured_feature/sea_pickle.json
+ reports/minecraft/worldgen/configured_feature/seagrass_mid.json
+ reports/minecraft/worldgen/configured_feature/seagrass_short.json
+ reports/minecraft/worldgen/configured_feature/seagrass_simple.json
+ reports/minecraft/worldgen/configured_feature/seagrass_slightly_less_short.json
+ reports/minecraft/worldgen/configured_feature/seagrass_tall.json
+ reports/minecraft/worldgen/configured_feature/single_piece_of_grass.json
+ reports/minecraft/worldgen/configured_feature/small_basalt_columns.json
+ reports/minecraft/worldgen/configured_feature/spore_blossom.json
+ reports/minecraft/worldgen/configured_feature/spring_lava_frozen.json
+ reports/minecraft/worldgen/configured_feature/spring_lava_nether.json
+ reports/minecraft/worldgen/configured_feature/spring_lava_overworld.json
+ reports/minecraft/worldgen/configured_feature/spring_nether_closed.json
+ reports/minecraft/worldgen/configured_feature/spring_nether_open.json
+ reports/minecraft/worldgen/configured_feature/spring_water.json
+ reports/minecraft/worldgen/configured_feature/spruce.json
+ reports/minecraft/worldgen/configured_feature/super_birch_bees_0002.json
+ reports/minecraft/worldgen/configured_feature/super_birch_bees.json
+ reports/minecraft/worldgen/configured_feature/swamp_oak.json
+ reports/minecraft/worldgen/configured_feature/tall_mangrove.json
+ reports/minecraft/worldgen/configured_feature/trees_birch_and_oak.json
+ reports/minecraft/worldgen/configured_feature/trees_flower_forest.json
+ reports/minecraft/worldgen/configured_feature/trees_grove.json
+ reports/minecraft/worldgen/configured_feature/trees_jungle.json
+ reports/minecraft/worldgen/configured_feature/trees_old_growth_pine_taiga.json
+ reports/minecraft/worldgen/configured_feature/trees_old_growth_spruce_taiga.json
+ reports/minecraft/worldgen/configured_feature/trees_plains.json
+ reports/minecraft/worldgen/configured_feature/trees_savanna.json
+ reports/minecraft/worldgen/configured_feature/trees_sparse_jungle.json
+ reports/minecraft/worldgen/configured_feature/trees_taiga.json
+ reports/minecraft/worldgen/configured_feature/trees_water.json
+ reports/minecraft/worldgen/configured_feature/trees_windswept_hills.json
+ reports/minecraft/worldgen/configured_feature/twisting_vines_bonemeal.json
+ reports/minecraft/worldgen/configured_feature/twisting_vines.json
+ reports/minecraft/worldgen/configured_feature/underwater_magma.json
+ reports/minecraft/worldgen/configured_feature/vines.json
+ reports/minecraft/worldgen/configured_feature/void_start_platform.json
+ reports/minecraft/worldgen/configured_feature/warm_ocean_vegetation.json
+ reports/minecraft/worldgen/configured_feature/warped_forest_vegetation_bonemeal.json
+ reports/minecraft/worldgen/configured_feature/warped_forest_vegetation.json
+ reports/minecraft/worldgen/configured_feature/warped_fungus_planted.json
+ reports/minecraft/worldgen/configured_feature/warped_fungus.json
+ reports/minecraft/worldgen/configured_feature/weeping_vines.json
+ reports/minecraft/worldgen/density_function/end/base_3d_noise.json
+ reports/minecraft/worldgen/density_function/end/sloped_cheese.json
+ reports/minecraft/worldgen/density_function/nether/base_3d_noise.json
+ reports/minecraft/worldgen/density_function/overworld_amplified/depth.json
+ reports/minecraft/worldgen/density_function/overworld_amplified/factor.json
+ reports/minecraft/worldgen/density_function/overworld_amplified/jaggedness.json
+ reports/minecraft/worldgen/density_function/overworld_amplified/offset.json
+ reports/minecraft/worldgen/density_function/overworld_amplified/sloped_cheese.json
+ reports/minecraft/worldgen/density_function/overworld_large_biomes/continents.json
+ reports/minecraft/worldgen/density_function/overworld_large_biomes/depth.json
+ reports/minecraft/worldgen/density_function/overworld_large_biomes/erosion.json
+ reports/minecraft/worldgen/density_function/overworld_large_biomes/factor.json
+ reports/minecraft/worldgen/density_function/overworld_large_biomes/jaggedness.json
+ reports/minecraft/worldgen/density_function/overworld_large_biomes/offset.json
+ reports/minecraft/worldgen/density_function/overworld_large_biomes/sloped_cheese.json
+ reports/minecraft/worldgen/density_function/overworld/base_3d_noise.json
+ reports/minecraft/worldgen/density_function/overworld/caves/entrances.json
+ reports/minecraft/worldgen/density_function/overworld/caves/noodle.json
+ reports/minecraft/worldgen/density_function/overworld/caves/pillars.json
+ reports/minecraft/worldgen/density_function/overworld/caves/spaghetti_2d_thickness_modulator.json
+ reports/minecraft/worldgen/density_function/overworld/caves/spaghetti_2d.json
+ reports/minecraft/worldgen/density_function/overworld/caves/spaghetti_roughness_function.json
+ reports/minecraft/worldgen/density_function/overworld/continents.json
+ reports/minecraft/worldgen/density_function/overworld/depth.json
+ reports/minecraft/worldgen/density_function/overworld/erosion.json
+ reports/minecraft/worldgen/density_function/overworld/factor.json
+ reports/minecraft/worldgen/density_function/overworld/jaggedness.json
+ reports/minecraft/worldgen/density_function/overworld/offset.json
+ reports/minecraft/worldgen/density_function/overworld/ridges_folded.json
+ reports/minecraft/worldgen/density_function/overworld/ridges.json
+ reports/minecraft/worldgen/density_function/overworld/sloped_cheese.json
+ reports/minecraft/worldgen/density_function/shift_x.json
+ reports/minecraft/worldgen/density_function/shift_z.json
+ reports/minecraft/worldgen/density_function/y.json
+ reports/minecraft/worldgen/density_function/zero.json
+ reports/minecraft/worldgen/flat_level_generator_preset/bottomless_pit.json
+ reports/minecraft/worldgen/flat_level_generator_preset/classic_flat.json
+ reports/minecraft/worldgen/flat_level_generator_preset/desert.json
+ reports/minecraft/worldgen/flat_level_generator_preset/overworld.json
+ reports/minecraft/worldgen/flat_level_generator_preset/redstone_ready.json
+ reports/minecraft/worldgen/flat_level_generator_preset/snowy_kingdom.json
+ reports/minecraft/worldgen/flat_level_generator_preset/the_void.json
+ reports/minecraft/worldgen/flat_level_generator_preset/tunnelers_dream.json
+ reports/minecraft/worldgen/flat_level_generator_preset/water_world.json
+ reports/minecraft/worldgen/noise_settings/amplified.json
+ reports/minecraft/worldgen/noise_settings/caves.json
+ reports/minecraft/worldgen/noise_settings/end.json
+ reports/minecraft/worldgen/noise_settings/floating_islands.json
+ reports/minecraft/worldgen/noise_settings/large_biomes.json
+ reports/minecraft/worldgen/noise_settings/nether.json
+ reports/minecraft/worldgen/noise_settings/overworld.json
+ reports/minecraft/worldgen/noise/aquifer_barrier.json
+ reports/minecraft/worldgen/noise/aquifer_fluid_level_floodedness.json
+ reports/minecraft/worldgen/noise/aquifer_fluid_level_spread.json
+ reports/minecraft/worldgen/noise/aquifer_lava.json
+ reports/minecraft/worldgen/noise/badlands_pillar_roof.json
+ reports/minecraft/worldgen/noise/badlands_pillar.json
+ reports/minecraft/worldgen/noise/badlands_surface.json
+ reports/minecraft/worldgen/noise/calcite.json
+ reports/minecraft/worldgen/noise/cave_cheese.json
+ reports/minecraft/worldgen/noise/cave_entrance.json
+ reports/minecraft/worldgen/noise/cave_layer.json
+ reports/minecraft/worldgen/noise/clay_bands_offset.json
+ reports/minecraft/worldgen/noise/continentalness_large.json
+ reports/minecraft/worldgen/noise/continentalness.json
+ reports/minecraft/worldgen/noise/erosion_large.json
+ reports/minecraft/worldgen/noise/erosion.json
+ reports/minecraft/worldgen/noise/gravel_layer.json
+ reports/minecraft/worldgen/noise/gravel.json
+ reports/minecraft/worldgen/noise/ice.json
+ reports/minecraft/worldgen/noise/iceberg_pillar_roof.json
+ reports/minecraft/worldgen/noise/iceberg_pillar.json
+ reports/minecraft/worldgen/noise/iceberg_surface.json
+ reports/minecraft/worldgen/noise/jagged.json
+ reports/minecraft/worldgen/noise/nether_state_selector.json
+ reports/minecraft/worldgen/noise/nether_wart.json
+ reports/minecraft/worldgen/noise/netherrack.json
+ reports/minecraft/worldgen/noise/noodle_ridge_a.json
+ reports/minecraft/worldgen/noise/noodle_ridge_b.json
+ reports/minecraft/worldgen/noise/noodle_thickness.json
+ reports/minecraft/worldgen/noise/noodle.json
+ reports/minecraft/worldgen/noise/offset.json
+ reports/minecraft/worldgen/noise/ore_gap.json
+ reports/minecraft/worldgen/noise/ore_vein_a.json
+ reports/minecraft/worldgen/noise/ore_vein_b.json
+ reports/minecraft/worldgen/noise/ore_veininess.json
+ reports/minecraft/worldgen/noise/packed_ice.json
+ reports/minecraft/worldgen/noise/patch.json
+ reports/minecraft/worldgen/noise/pillar_rareness.json
+ reports/minecraft/worldgen/noise/pillar_thickness.json
+ reports/minecraft/worldgen/noise/pillar.json
+ reports/minecraft/worldgen/noise/powder_snow.json
+ reports/minecraft/worldgen/noise/ridge.json
+ reports/minecraft/worldgen/noise/soul_sand_layer.json
+ reports/minecraft/worldgen/noise/spaghetti_2d_elevation.json
+ reports/minecraft/worldgen/noise/spaghetti_2d_modulator.json
+ reports/minecraft/worldgen/noise/spaghetti_2d_thickness.json
+ reports/minecraft/worldgen/noise/spaghetti_2d.json
+ reports/minecraft/worldgen/noise/spaghetti_3d_1.json
+ reports/minecraft/worldgen/noise/spaghetti_3d_2.json
+ reports/minecraft/worldgen/noise/spaghetti_3d_rarity.json
+ reports/minecraft/worldgen/noise/spaghetti_3d_thickness.json
+ reports/minecraft/worldgen/noise/spaghetti_roughness_modulator.json
+ reports/minecraft/worldgen/noise/spaghetti_roughness.json
+ reports/minecraft/worldgen/noise/surface_secondary.json
+ reports/minecraft/worldgen/noise/surface_swamp.json
+ reports/minecraft/worldgen/noise/surface.json
+ reports/minecraft/worldgen/noise/temperature_large.json
+ reports/minecraft/worldgen/noise/temperature.json
+ reports/minecraft/worldgen/noise/vegetation_large.json
+ reports/minecraft/worldgen/noise/vegetation.json
+ reports/minecraft/worldgen/placed_feature/acacia_checked.json
+ reports/minecraft/worldgen/placed_feature/acacia.json
+ reports/minecraft/worldgen/placed_feature/amethyst_geode.json
+ reports/minecraft/worldgen/placed_feature/bamboo_light.json
+ reports/minecraft/worldgen/placed_feature/bamboo_vegetation.json
+ reports/minecraft/worldgen/placed_feature/bamboo.json
+ reports/minecraft/worldgen/placed_feature/basalt_blobs.json
+ reports/minecraft/worldgen/placed_feature/basalt_pillar.json
+ reports/minecraft/worldgen/placed_feature/birch_bees_0002.json
+ reports/minecraft/worldgen/placed_feature/birch_bees_002.json
+ reports/minecraft/worldgen/placed_feature/birch_checked.json
+ reports/minecraft/worldgen/placed_feature/birch_tall.json
+ reports/minecraft/worldgen/placed_feature/blackstone_blobs.json
+ reports/minecraft/worldgen/placed_feature/blue_ice.json
+ reports/minecraft/worldgen/placed_feature/brown_mushroom_nether.json
+ reports/minecraft/worldgen/placed_feature/brown_mushroom_normal.json
+ reports/minecraft/worldgen/placed_feature/brown_mushroom_old_growth.json
+ reports/minecraft/worldgen/placed_feature/brown_mushroom_swamp.json
+ reports/minecraft/worldgen/placed_feature/brown_mushroom_taiga.json
+ reports/minecraft/worldgen/placed_feature/cave_vines.json
+ reports/minecraft/worldgen/placed_feature/chorus_plant.json
+ reports/minecraft/worldgen/placed_feature/classic_vines_cave_feature.json
+ reports/minecraft/worldgen/placed_feature/crimson_forest_vegetation.json
+ reports/minecraft/worldgen/placed_feature/crimson_fungi.json
+ reports/minecraft/worldgen/placed_feature/dark_forest_vegetation.json
+ reports/minecraft/worldgen/placed_feature/dark_oak_checked.json
+ reports/minecraft/worldgen/placed_feature/delta.json
+ reports/minecraft/worldgen/placed_feature/desert_well.json
+ reports/minecraft/worldgen/placed_feature/disk_clay.json
+ reports/minecraft/worldgen/placed_feature/disk_grass.json
+ reports/minecraft/worldgen/placed_feature/disk_gravel.json
+ reports/minecraft/worldgen/placed_feature/disk_sand.json
+ reports/minecraft/worldgen/placed_feature/dripstone_cluster.json
+ reports/minecraft/worldgen/placed_feature/end_gateway_return.json
+ reports/minecraft/worldgen/placed_feature/end_island_decorated.json
+ reports/minecraft/worldgen/placed_feature/end_spike.json
+ reports/minecraft/worldgen/placed_feature/fancy_oak_bees_0002.json
+ reports/minecraft/worldgen/placed_feature/fancy_oak_bees_002.json
+ reports/minecraft/worldgen/placed_feature/fancy_oak_bees.json
+ reports/minecraft/worldgen/placed_feature/fancy_oak_checked.json
+ reports/minecraft/worldgen/placed_feature/flower_default.json
+ reports/minecraft/worldgen/placed_feature/flower_flower_forest.json
+ reports/minecraft/worldgen/placed_feature/flower_forest_flowers.json
+ reports/minecraft/worldgen/placed_feature/flower_meadow.json
+ reports/minecraft/worldgen/placed_feature/flower_plain.json
+ reports/minecraft/worldgen/placed_feature/flower_plains.json
+ reports/minecraft/worldgen/placed_feature/flower_swamp.json
+ reports/minecraft/worldgen/placed_feature/flower_warm.json
+ reports/minecraft/worldgen/placed_feature/forest_flowers.json
+ reports/minecraft/worldgen/placed_feature/forest_rock.json
+ reports/minecraft/worldgen/placed_feature/fossil_lower.json
+ reports/minecraft/worldgen/placed_feature/fossil_upper.json
+ reports/minecraft/worldgen/placed_feature/freeze_top_layer.json
+ reports/minecraft/worldgen/placed_feature/glow_lichen.json
+ reports/minecraft/worldgen/placed_feature/glowstone_extra.json
+ reports/minecraft/worldgen/placed_feature/glowstone.json
+ reports/minecraft/worldgen/placed_feature/grass_bonemeal.json
+ reports/minecraft/worldgen/placed_feature/ice_patch.json
+ reports/minecraft/worldgen/placed_feature/ice_spike.json
+ reports/minecraft/worldgen/placed_feature/iceberg_blue.json
+ reports/minecraft/worldgen/placed_feature/iceberg_packed.json
+ reports/minecraft/worldgen/placed_feature/jungle_bush.json
+ reports/minecraft/worldgen/placed_feature/jungle_tree.json
+ reports/minecraft/worldgen/placed_feature/kelp_cold.json
+ reports/minecraft/worldgen/placed_feature/kelp_warm.json
+ reports/minecraft/worldgen/placed_feature/lake_lava_surface.json
+ reports/minecraft/worldgen/placed_feature/lake_lava_underground.json
+ reports/minecraft/worldgen/placed_feature/large_basalt_columns.json
+ reports/minecraft/worldgen/placed_feature/large_dripstone.json
+ reports/minecraft/worldgen/placed_feature/lush_caves_ceiling_vegetation.json
+ reports/minecraft/worldgen/placed_feature/lush_caves_clay.json
+ reports/minecraft/worldgen/placed_feature/lush_caves_vegetation.json
+ reports/minecraft/worldgen/placed_feature/mangrove_checked.json
+ reports/minecraft/worldgen/placed_feature/mega_jungle_tree_checked.json
+ reports/minecraft/worldgen/placed_feature/mega_pine_checked.json
+ reports/minecraft/worldgen/placed_feature/mega_spruce_checked.json
+ reports/minecraft/worldgen/placed_feature/monster_room_deep.json
+ reports/minecraft/worldgen/placed_feature/monster_room.json
+ reports/minecraft/worldgen/placed_feature/mushroom_island_vegetation.json
+ reports/minecraft/worldgen/placed_feature/nether_sprouts.json
+ reports/minecraft/worldgen/placed_feature/oak_bees_0002.json
+ reports/minecraft/worldgen/placed_feature/oak_bees_002.json
+ reports/minecraft/worldgen/placed_feature/oak_checked.json
+ reports/minecraft/worldgen/placed_feature/oak.json
+ reports/minecraft/worldgen/placed_feature/ore_ancient_debris_large.json
+ reports/minecraft/worldgen/placed_feature/ore_andesite_lower.json
+ reports/minecraft/worldgen/placed_feature/ore_andesite_upper.json
+ reports/minecraft/worldgen/placed_feature/ore_blackstone.json
+ reports/minecraft/worldgen/placed_feature/ore_clay.json
+ reports/minecraft/worldgen/placed_feature/ore_coal_lower.json
+ reports/minecraft/worldgen/placed_feature/ore_coal_upper.json
+ reports/minecraft/worldgen/placed_feature/ore_copper_large.json
+ reports/minecraft/worldgen/placed_feature/ore_copper.json
+ reports/minecraft/worldgen/placed_feature/ore_debris_small.json
+ reports/minecraft/worldgen/placed_feature/ore_diamond_buried.json
+ reports/minecraft/worldgen/placed_feature/ore_diamond_large.json
+ reports/minecraft/worldgen/placed_feature/ore_diamond.json
+ reports/minecraft/worldgen/placed_feature/ore_diorite_lower.json
+ reports/minecraft/worldgen/placed_feature/ore_diorite_upper.json
+ reports/minecraft/worldgen/placed_feature/ore_dirt.json
+ reports/minecraft/worldgen/placed_feature/ore_emerald.json
+ reports/minecraft/worldgen/placed_feature/ore_gold_deltas.json
+ reports/minecraft/worldgen/placed_feature/ore_gold_extra.json
+ reports/minecraft/worldgen/placed_feature/ore_gold_lower.json
+ reports/minecraft/worldgen/placed_feature/ore_gold_nether.json
+ reports/minecraft/worldgen/placed_feature/ore_gold.json
+ reports/minecraft/worldgen/placed_feature/ore_granite_lower.json
+ reports/minecraft/worldgen/placed_feature/ore_granite_upper.json
+ reports/minecraft/worldgen/placed_feature/ore_gravel_nether.json
+ reports/minecraft/worldgen/placed_feature/ore_gravel.json
+ reports/minecraft/worldgen/placed_feature/ore_infested.json
+ reports/minecraft/worldgen/placed_feature/ore_iron_middle.json
+ reports/minecraft/worldgen/placed_feature/ore_iron_small.json
+ reports/minecraft/worldgen/placed_feature/ore_iron_upper.json
+ reports/minecraft/worldgen/placed_feature/ore_lapis_buried.json
+ reports/minecraft/worldgen/placed_feature/ore_lapis.json
+ reports/minecraft/worldgen/placed_feature/ore_magma.json
+ reports/minecraft/worldgen/placed_feature/ore_quartz_deltas.json
+ reports/minecraft/worldgen/placed_feature/ore_quartz_nether.json
+ reports/minecraft/worldgen/placed_feature/ore_redstone_lower.json
+ reports/minecraft/worldgen/placed_feature/ore_redstone.json
+ reports/minecraft/worldgen/placed_feature/ore_soul_sand.json
+ reports/minecraft/worldgen/placed_feature/ore_tuff.json
+ reports/minecraft/worldgen/placed_feature/patch_berry_bush.json
+ reports/minecraft/worldgen/placed_feature/patch_berry_common.json
+ reports/minecraft/worldgen/placed_feature/patch_berry_rare.json
+ reports/minecraft/worldgen/placed_feature/patch_cactus_decorated.json
+ reports/minecraft/worldgen/placed_feature/patch_cactus_desert.json
+ reports/minecraft/worldgen/placed_feature/patch_cactus.json
+ reports/minecraft/worldgen/placed_feature/patch_crimson_roots.json
+ reports/minecraft/worldgen/placed_feature/patch_dead_bush_2.json
+ reports/minecraft/worldgen/placed_feature/patch_dead_bush_badlands.json
+ reports/minecraft/worldgen/placed_feature/patch_dead_bush.json
+ reports/minecraft/worldgen/placed_feature/patch_fire.json
+ reports/minecraft/worldgen/placed_feature/patch_grass_badlands.json
+ reports/minecraft/worldgen/placed_feature/patch_grass_forest.json
+ reports/minecraft/worldgen/placed_feature/patch_grass_jungle.json
+ reports/minecraft/worldgen/placed_feature/patch_grass_normal.json
+ reports/minecraft/worldgen/placed_feature/patch_grass_plain.json
+ reports/minecraft/worldgen/placed_feature/patch_grass_savanna.json
+ reports/minecraft/worldgen/placed_feature/patch_grass_taiga_2.json
+ reports/minecraft/worldgen/placed_feature/patch_grass_taiga.json
+ reports/minecraft/worldgen/placed_feature/patch_large_fern.json
+ reports/minecraft/worldgen/placed_feature/patch_melon_sparse.json
+ reports/minecraft/worldgen/placed_feature/patch_melon.json
+ reports/minecraft/worldgen/placed_feature/patch_pumpkin.json
+ reports/minecraft/worldgen/placed_feature/patch_soul_fire.json
+ reports/minecraft/worldgen/placed_feature/patch_sugar_cane_badlands.json
+ reports/minecraft/worldgen/placed_feature/patch_sugar_cane_desert.json
+ reports/minecraft/worldgen/placed_feature/patch_sugar_cane_swamp.json
+ reports/minecraft/worldgen/placed_feature/patch_sugar_cane.json
+ reports/minecraft/worldgen/placed_feature/patch_sunflower.json
+ reports/minecraft/worldgen/placed_feature/patch_taiga_grass.json
+ reports/minecraft/worldgen/placed_feature/patch_tall_grass_2.json
+ reports/minecraft/worldgen/placed_feature/patch_tall_grass.json
+ reports/minecraft/worldgen/placed_feature/patch_waterlily.json
+ reports/minecraft/worldgen/placed_feature/pile_hay.json
+ reports/minecraft/worldgen/placed_feature/pile_ice.json
+ reports/minecraft/worldgen/placed_feature/pile_melon.json
+ reports/minecraft/worldgen/placed_feature/pile_pumpkin.json
+ reports/minecraft/worldgen/placed_feature/pile_snow.json
+ reports/minecraft/worldgen/placed_feature/pine_checked.json
+ reports/minecraft/worldgen/placed_feature/pine_on_snow.json
+ reports/minecraft/worldgen/placed_feature/pine.json
+ reports/minecraft/worldgen/placed_feature/pointed_dripstone.json
+ reports/minecraft/worldgen/placed_feature/red_mushroom_nether.json
+ reports/minecraft/worldgen/placed_feature/red_mushroom_normal.json
+ reports/minecraft/worldgen/placed_feature/red_mushroom_old_growth.json
+ reports/minecraft/worldgen/placed_feature/red_mushroom_swamp.json
+ reports/minecraft/worldgen/placed_feature/red_mushroom_taiga.json
+ reports/minecraft/worldgen/placed_feature/rooted_azalea_tree.json
+ reports/minecraft/worldgen/placed_feature/sculk_patch_ancient_city.json
+ reports/minecraft/worldgen/placed_feature/sculk_patch_deep_dark.json
+ reports/minecraft/worldgen/placed_feature/sculk_vein.json
+ reports/minecraft/worldgen/placed_feature/sea_pickle.json
+ reports/minecraft/worldgen/placed_feature/seagrass_cold.json
+ reports/minecraft/worldgen/placed_feature/seagrass_deep_cold.json
+ reports/minecraft/worldgen/placed_feature/seagrass_deep_warm.json
+ reports/minecraft/worldgen/placed_feature/seagrass_deep.json
+ reports/minecraft/worldgen/placed_feature/seagrass_normal.json
+ reports/minecraft/worldgen/placed_feature/seagrass_river.json
+ reports/minecraft/worldgen/placed_feature/seagrass_simple.json
+ reports/minecraft/worldgen/placed_feature/seagrass_swamp.json
+ reports/minecraft/worldgen/placed_feature/seagrass_warm.json
+ reports/minecraft/worldgen/placed_feature/small_basalt_columns.json
+ reports/minecraft/worldgen/placed_feature/spore_blossom.json
+ reports/minecraft/worldgen/placed_feature/spring_closed_double.json
+ reports/minecraft/worldgen/placed_feature/spring_closed.json
+ reports/minecraft/worldgen/placed_feature/spring_delta.json
+ reports/minecraft/worldgen/placed_feature/spring_lava_frozen.json
+ reports/minecraft/worldgen/placed_feature/spring_lava.json
+ reports/minecraft/worldgen/placed_feature/spring_open.json
+ reports/minecraft/worldgen/placed_feature/spring_water.json
+ reports/minecraft/worldgen/placed_feature/spruce_checked.json
+ reports/minecraft/worldgen/placed_feature/spruce_on_snow.json
+ reports/minecraft/worldgen/placed_feature/spruce.json
+ reports/minecraft/worldgen/placed_feature/super_birch_bees_0002.json
+ reports/minecraft/worldgen/placed_feature/super_birch_bees.json
+ reports/minecraft/worldgen/placed_feature/tall_mangrove_checked.json
+ reports/minecraft/worldgen/placed_feature/trees_badlands.json
+ reports/minecraft/worldgen/placed_feature/trees_birch_and_oak.json
+ reports/minecraft/worldgen/placed_feature/trees_birch.json
+ reports/minecraft/worldgen/placed_feature/trees_flower_forest.json
+ reports/minecraft/worldgen/placed_feature/trees_grove.json
+ reports/minecraft/worldgen/placed_feature/trees_jungle.json
+ reports/minecraft/worldgen/placed_feature/trees_mangrove.json
+ reports/minecraft/worldgen/placed_feature/trees_meadow.json
+ reports/minecraft/worldgen/placed_feature/trees_old_growth_pine_taiga.json
+ reports/minecraft/worldgen/placed_feature/trees_old_growth_spruce_taiga.json
+ reports/minecraft/worldgen/placed_feature/trees_plains.json
+ reports/minecraft/worldgen/placed_feature/trees_savanna.json
+ reports/minecraft/worldgen/placed_feature/trees_snowy.json
+ reports/minecraft/worldgen/placed_feature/trees_sparse_jungle.json
+ reports/minecraft/worldgen/placed_feature/trees_swamp.json
+ reports/minecraft/worldgen/placed_feature/trees_taiga.json
+ reports/minecraft/worldgen/placed_feature/trees_water.json
+ reports/minecraft/worldgen/placed_feature/trees_windswept_forest.json
+ reports/minecraft/worldgen/placed_feature/trees_windswept_hills.json
+ reports/minecraft/worldgen/placed_feature/trees_windswept_savanna.json
+ reports/minecraft/worldgen/placed_feature/twisting_vines.json
+ reports/minecraft/worldgen/placed_feature/underwater_magma.json
+ reports/minecraft/worldgen/placed_feature/vines.json
+ reports/minecraft/worldgen/placed_feature/void_start_platform.json
+ reports/minecraft/worldgen/placed_feature/warm_ocean_vegetation.json
+ reports/minecraft/worldgen/placed_feature/warped_forest_vegetation.json
+ reports/minecraft/worldgen/placed_feature/warped_fungi.json
+ reports/minecraft/worldgen/placed_feature/weeping_vines.json
+ reports/minecraft/worldgen/processor_list/ancient_city_generic_degradation.json
+ reports/minecraft/worldgen/processor_list/ancient_city_start_degradation.json
+ reports/minecraft/worldgen/processor_list/ancient_city_walls_degradation.json
+ reports/minecraft/worldgen/processor_list/bastion_generic_degradation.json
+ reports/minecraft/worldgen/processor_list/bottom_rampart.json
+ reports/minecraft/worldgen/processor_list/bridge.json
+ reports/minecraft/worldgen/processor_list/empty.json
+ reports/minecraft/worldgen/processor_list/entrance_replacement.json
+ reports/minecraft/worldgen/processor_list/farm_desert.json
+ reports/minecraft/worldgen/processor_list/farm_plains.json
+ reports/minecraft/worldgen/processor_list/farm_savanna.json
+ reports/minecraft/worldgen/processor_list/farm_snowy.json
+ reports/minecraft/worldgen/processor_list/farm_taiga.json
+ reports/minecraft/worldgen/processor_list/fossil_coal.json
+ reports/minecraft/worldgen/processor_list/fossil_diamonds.json
+ reports/minecraft/worldgen/processor_list/fossil_rot.json
+ reports/minecraft/worldgen/processor_list/high_rampart.json
+ reports/minecraft/worldgen/processor_list/high_wall.json
+ reports/minecraft/worldgen/processor_list/housing.json
+ reports/minecraft/worldgen/processor_list/mossify_10_percent.json
+ reports/minecraft/worldgen/processor_list/mossify_20_percent.json
+ reports/minecraft/worldgen/processor_list/mossify_70_percent.json
+ reports/minecraft/worldgen/processor_list/outpost_rot.json
+ reports/minecraft/worldgen/processor_list/rampart_degradation.json
+ reports/minecraft/worldgen/processor_list/roof.json
+ reports/minecraft/worldgen/processor_list/side_wall_degradation.json
+ reports/minecraft/worldgen/processor_list/stable_degradation.json
+ reports/minecraft/worldgen/processor_list/street_plains.json
+ reports/minecraft/worldgen/processor_list/street_savanna.json
+ reports/minecraft/worldgen/processor_list/street_snowy_or_taiga.json
+ reports/minecraft/worldgen/processor_list/treasure_rooms.json
+ reports/minecraft/worldgen/processor_list/zombie_desert.json
+ reports/minecraft/worldgen/processor_list/zombie_plains.json
+ reports/minecraft/worldgen/processor_list/zombie_savanna.json
+ reports/minecraft/worldgen/processor_list/zombie_snowy.json
+ reports/minecraft/worldgen/processor_list/zombie_taiga.json
+ reports/minecraft/worldgen/structure_set/ancient_cities.json
+ reports/minecraft/worldgen/structure_set/buried_treasures.json
+ reports/minecraft/worldgen/structure_set/desert_pyramids.json
+ reports/minecraft/worldgen/structure_set/end_cities.json
+ reports/minecraft/worldgen/structure_set/igloos.json
+ reports/minecraft/worldgen/structure_set/jungle_temples.json
+ reports/minecraft/worldgen/structure_set/mineshafts.json
+ reports/minecraft/worldgen/structure_set/nether_complexes.json
+ reports/minecraft/worldgen/structure_set/nether_fossils.json
+ reports/minecraft/worldgen/structure_set/ocean_monuments.json
+ reports/minecraft/worldgen/structure_set/ocean_ruins.json
+ reports/minecraft/worldgen/structure_set/pillager_outposts.json
+ reports/minecraft/worldgen/structure_set/ruined_portals.json
+ reports/minecraft/worldgen/structure_set/shipwrecks.json
+ reports/minecraft/worldgen/structure_set/strongholds.json
+ reports/minecraft/worldgen/structure_set/swamp_huts.json
+ reports/minecraft/worldgen/structure_set/villages.json
+ reports/minecraft/worldgen/structure_set/woodland_mansions.json
+ reports/minecraft/worldgen/structure/ancient_city.json
+ reports/minecraft/worldgen/structure/bastion_remnant.json
+ reports/minecraft/worldgen/structure/buried_treasure.json
+ reports/minecraft/worldgen/structure/desert_pyramid.json
+ reports/minecraft/worldgen/structure/end_city.json
+ reports/minecraft/worldgen/structure/fortress.json
+ reports/minecraft/worldgen/structure/igloo.json
+ reports/minecraft/worldgen/structure/jungle_pyramid.json
+ reports/minecraft/worldgen/structure/mansion.json
+ reports/minecraft/worldgen/structure/mineshaft_mesa.json
+ reports/minecraft/worldgen/structure/mineshaft.json
+ reports/minecraft/worldgen/structure/monument.json
+ reports/minecraft/worldgen/structure/nether_fossil.json
+ reports/minecraft/worldgen/structure/ocean_ruin_cold.json
+ reports/minecraft/worldgen/structure/ocean_ruin_warm.json
+ reports/minecraft/worldgen/structure/pillager_outpost.json
+ reports/minecraft/worldgen/structure/ruined_portal_desert.json
+ reports/minecraft/worldgen/structure/ruined_portal_jungle.json
+ reports/minecraft/worldgen/structure/ruined_portal_mountain.json
+ reports/minecraft/worldgen/structure/ruined_portal_nether.json
+ reports/minecraft/worldgen/structure/ruined_portal_ocean.json
+ reports/minecraft/worldgen/structure/ruined_portal_swamp.json
+ reports/minecraft/worldgen/structure/ruined_portal.json
+ reports/minecraft/worldgen/structure/shipwreck_beached.json
+ reports/minecraft/worldgen/structure/shipwreck.json
+ reports/minecraft/worldgen/structure/stronghold.json
+ reports/minecraft/worldgen/structure/swamp_hut.json
+ reports/minecraft/worldgen/structure/village_desert.json
+ reports/minecraft/worldgen/structure/village_plains.json
+ reports/minecraft/worldgen/structure/village_savanna.json
+ reports/minecraft/worldgen/structure/village_snowy.json
+ reports/minecraft/worldgen/structure/village_taiga.json
+ reports/minecraft/worldgen/template_pool/ancient_city/city_center.json
+ reports/minecraft/worldgen/template_pool/ancient_city/city_center/walls.json
+ reports/minecraft/worldgen/template_pool/ancient_city/city/entrance.json
+ reports/minecraft/worldgen/template_pool/ancient_city/sculk.json
+ reports/minecraft/worldgen/template_pool/ancient_city/structures.json
+ reports/minecraft/worldgen/template_pool/ancient_city/walls.json
+ reports/minecraft/worldgen/template_pool/ancient_city/walls/no_corners.json
+ reports/minecraft/worldgen/template_pool/bastion/blocks/gold.json
+ reports/minecraft/worldgen/template_pool/bastion/bridge/bridge_pieces.json
+ reports/minecraft/worldgen/template_pool/bastion/bridge/connectors.json
+ reports/minecraft/worldgen/template_pool/bastion/bridge/legs.json
+ reports/minecraft/worldgen/template_pool/bastion/bridge/rampart_plates.json
+ reports/minecraft/worldgen/template_pool/bastion/bridge/ramparts.json
+ reports/minecraft/worldgen/template_pool/bastion/bridge/starting_pieces.json
+ reports/minecraft/worldgen/template_pool/bastion/bridge/walls.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/connectors.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/inner.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/outer.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/mirrored_starting_pieces.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/posts.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/rampart_plates.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/ramparts.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/inner.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/outer.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/stairs.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/starting_pieces.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/wall_bases.json
+ reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/walls.json
+ reports/minecraft/worldgen/template_pool/bastion/mobs/hoglin.json
+ reports/minecraft/worldgen/template_pool/bastion/mobs/piglin_melee.json
+ reports/minecraft/worldgen/template_pool/bastion/mobs/piglin.json
+ reports/minecraft/worldgen/template_pool/bastion/starts.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/bases.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/bases/centers.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/brains.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/connectors.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/corners/bottom.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/corners/edges.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/corners/middle.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/corners/top.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/entrances.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/extensions/houses.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/extensions/large_pool.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/extensions/small_pool.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/ramparts.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/roofs.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/stairs.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/walls.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/walls/bottom.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/walls/mid.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/walls/outer.json
+ reports/minecraft/worldgen/template_pool/bastion/treasure/walls/top.json
+ reports/minecraft/worldgen/template_pool/bastion/units/center_pieces.json
+ reports/minecraft/worldgen/template_pool/bastion/units/edge_wall_units.json
+ reports/minecraft/worldgen/template_pool/bastion/units/edges.json
+ reports/minecraft/worldgen/template_pool/bastion/units/fillers/stage_0.json
+ reports/minecraft/worldgen/template_pool/bastion/units/large_ramparts.json
+ reports/minecraft/worldgen/template_pool/bastion/units/pathways.json
+ reports/minecraft/worldgen/template_pool/bastion/units/rampart_plates.json
+ reports/minecraft/worldgen/template_pool/bastion/units/ramparts.json
+ reports/minecraft/worldgen/template_pool/bastion/units/stages/rot/stage_1.json
+ reports/minecraft/worldgen/template_pool/bastion/units/stages/stage_0.json
+ reports/minecraft/worldgen/template_pool/bastion/units/stages/stage_1.json
+ reports/minecraft/worldgen/template_pool/bastion/units/stages/stage_2.json
+ reports/minecraft/worldgen/template_pool/bastion/units/stages/stage_3.json
+ reports/minecraft/worldgen/template_pool/bastion/units/wall_units.json
+ reports/minecraft/worldgen/template_pool/bastion/units/walls/wall_bases.json
+ reports/minecraft/worldgen/template_pool/empty.json
+ reports/minecraft/worldgen/template_pool/pillager_outpost/base_plates.json
+ reports/minecraft/worldgen/template_pool/pillager_outpost/feature_plates.json
+ reports/minecraft/worldgen/template_pool/pillager_outpost/features.json
+ reports/minecraft/worldgen/template_pool/pillager_outpost/towers.json
+ reports/minecraft/worldgen/template_pool/village/common/animals.json
+ reports/minecraft/worldgen/template_pool/village/common/butcher_animals.json
+ reports/minecraft/worldgen/template_pool/village/common/cats.json
+ reports/minecraft/worldgen/template_pool/village/common/iron_golem.json
+ reports/minecraft/worldgen/template_pool/village/common/sheep.json
+ reports/minecraft/worldgen/template_pool/village/common/well_bottoms.json
+ reports/minecraft/worldgen/template_pool/village/desert/decor.json
+ reports/minecraft/worldgen/template_pool/village/desert/houses.json
+ reports/minecraft/worldgen/template_pool/village/desert/streets.json
+ reports/minecraft/worldgen/template_pool/village/desert/terminators.json
+ reports/minecraft/worldgen/template_pool/village/desert/town_centers.json
+ reports/minecraft/worldgen/template_pool/village/desert/villagers.json
+ reports/minecraft/worldgen/template_pool/village/desert/zombie/decor.json
+ reports/minecraft/worldgen/template_pool/village/desert/zombie/houses.json
+ reports/minecraft/worldgen/template_pool/village/desert/zombie/streets.json
+ reports/minecraft/worldgen/template_pool/village/desert/zombie/terminators.json
+ reports/minecraft/worldgen/template_pool/village/desert/zombie/villagers.json
+ reports/minecraft/worldgen/template_pool/village/plains/decor.json
+ reports/minecraft/worldgen/template_pool/village/plains/houses.json
+ reports/minecraft/worldgen/template_pool/village/plains/streets.json
+ reports/minecraft/worldgen/template_pool/village/plains/terminators.json
+ reports/minecraft/worldgen/template_pool/village/plains/town_centers.json
+ reports/minecraft/worldgen/template_pool/village/plains/trees.json
+ reports/minecraft/worldgen/template_pool/village/plains/villagers.json
+ reports/minecraft/worldgen/template_pool/village/plains/zombie/decor.json
+ reports/minecraft/worldgen/template_pool/village/plains/zombie/houses.json
+ reports/minecraft/worldgen/template_pool/village/plains/zombie/streets.json
+ reports/minecraft/worldgen/template_pool/village/plains/zombie/villagers.json
+ reports/minecraft/worldgen/template_pool/village/savanna/decor.json
+ reports/minecraft/worldgen/template_pool/village/savanna/houses.json
+ reports/minecraft/worldgen/template_pool/village/savanna/streets.json
+ reports/minecraft/worldgen/template_pool/village/savanna/terminators.json
+ reports/minecraft/worldgen/template_pool/village/savanna/town_centers.json
+ reports/minecraft/worldgen/template_pool/village/savanna/trees.json
+ reports/minecraft/worldgen/template_pool/village/savanna/villagers.json
+ reports/minecraft/worldgen/template_pool/village/savanna/zombie/decor.json
+ reports/minecraft/worldgen/template_pool/village/savanna/zombie/houses.json
+ reports/minecraft/worldgen/template_pool/village/savanna/zombie/streets.json
+ reports/minecraft/worldgen/template_pool/village/savanna/zombie/terminators.json
+ reports/minecraft/worldgen/template_pool/village/savanna/zombie/villagers.json
+ reports/minecraft/worldgen/template_pool/village/snowy/decor.json
+ reports/minecraft/worldgen/template_pool/village/snowy/houses.json
+ reports/minecraft/worldgen/template_pool/village/snowy/streets.json
+ reports/minecraft/worldgen/template_pool/village/snowy/terminators.json
+ reports/minecraft/worldgen/template_pool/village/snowy/town_centers.json
+ reports/minecraft/worldgen/template_pool/village/snowy/trees.json
+ reports/minecraft/worldgen/template_pool/village/snowy/villagers.json
+ reports/minecraft/worldgen/template_pool/village/snowy/zombie/decor.json
+ reports/minecraft/worldgen/template_pool/village/snowy/zombie/houses.json
+ reports/minecraft/worldgen/template_pool/village/snowy/zombie/streets.json
+ reports/minecraft/worldgen/template_pool/village/snowy/zombie/villagers.json
+ reports/minecraft/worldgen/template_pool/village/taiga/decor.json
+ reports/minecraft/worldgen/template_pool/village/taiga/houses.json
+ reports/minecraft/worldgen/template_pool/village/taiga/streets.json
+ reports/minecraft/worldgen/template_pool/village/taiga/terminators.json
+ reports/minecraft/worldgen/template_pool/village/taiga/town_centers.json
+ reports/minecraft/worldgen/template_pool/village/taiga/villagers.json
+ reports/minecraft/worldgen/template_pool/village/taiga/zombie/decor.json
+ reports/minecraft/worldgen/template_pool/village/taiga/zombie/houses.json
+ reports/minecraft/worldgen/template_pool/village/taiga/zombie/streets.json
+ reports/minecraft/worldgen/template_pool/village/taiga/zombie/villagers.json
+ reports/minecraft/worldgen/world_preset/amplified.json
+ reports/minecraft/worldgen/world_preset/debug_all_block_states.json
+ reports/minecraft/worldgen/world_preset/flat.json
+ reports/minecraft/worldgen/world_preset/large_biomes.json
+ reports/minecraft/worldgen/world_preset/normal.json
+ reports/minecraft/worldgen/world_preset/single_biome_surface.json
- reports/worldgen/minecraft/chat_type/chat.json
- reports/worldgen/minecraft/chat_type/emote_command.json
- reports/worldgen/minecraft/chat_type/game_info.json
- reports/worldgen/minecraft/chat_type/msg_command.json
- reports/worldgen/minecraft/chat_type/say_command.json
- reports/worldgen/minecraft/chat_type/system.json
- reports/worldgen/minecraft/chat_type/team_msg_command.json
- reports/worldgen/minecraft/chat_type/tellraw_command.json
- reports/worldgen/minecraft/dimension_type/overworld_caves.json
- reports/worldgen/minecraft/dimension_type/overworld.json
- reports/worldgen/minecraft/dimension_type/the_end.json
- reports/worldgen/minecraft/dimension_type/the_nether.json
- reports/worldgen/minecraft/worldgen/biome/badlands.json
- reports/worldgen/minecraft/worldgen/biome/bamboo_jungle.json
- reports/worldgen/minecraft/worldgen/biome/basalt_deltas.json
- reports/worldgen/minecraft/worldgen/biome/beach.json
- reports/worldgen/minecraft/worldgen/biome/birch_forest.json
- reports/worldgen/minecraft/worldgen/biome/cold_ocean.json
- reports/worldgen/minecraft/worldgen/biome/crimson_forest.json
- reports/worldgen/minecraft/worldgen/biome/dark_forest.json
- reports/worldgen/minecraft/worldgen/biome/deep_cold_ocean.json
- reports/worldgen/minecraft/worldgen/biome/deep_dark.json
- reports/worldgen/minecraft/worldgen/biome/deep_frozen_ocean.json
- reports/worldgen/minecraft/worldgen/biome/deep_lukewarm_ocean.json
- reports/worldgen/minecraft/worldgen/biome/deep_ocean.json
- reports/worldgen/minecraft/worldgen/biome/desert.json
- reports/worldgen/minecraft/worldgen/biome/dripstone_caves.json
- reports/worldgen/minecraft/worldgen/biome/end_barrens.json
- reports/worldgen/minecraft/worldgen/biome/end_highlands.json
- reports/worldgen/minecraft/worldgen/biome/end_midlands.json
- reports/worldgen/minecraft/worldgen/biome/eroded_badlands.json
- reports/worldgen/minecraft/worldgen/biome/flower_forest.json
- reports/worldgen/minecraft/worldgen/biome/forest.json
- reports/worldgen/minecraft/worldgen/biome/frozen_ocean.json
- reports/worldgen/minecraft/worldgen/biome/frozen_peaks.json
- reports/worldgen/minecraft/worldgen/biome/frozen_river.json
- reports/worldgen/minecraft/worldgen/biome/grove.json
- reports/worldgen/minecraft/worldgen/biome/ice_spikes.json
- reports/worldgen/minecraft/worldgen/biome/jagged_peaks.json
- reports/worldgen/minecraft/worldgen/biome/jungle.json
- reports/worldgen/minecraft/worldgen/biome/lukewarm_ocean.json
- reports/worldgen/minecraft/worldgen/biome/lush_caves.json
- reports/worldgen/minecraft/worldgen/biome/mangrove_swamp.json
- reports/worldgen/minecraft/worldgen/biome/meadow.json
- reports/worldgen/minecraft/worldgen/biome/mushroom_fields.json
- reports/worldgen/minecraft/worldgen/biome/nether_wastes.json
- reports/worldgen/minecraft/worldgen/biome/ocean.json
- reports/worldgen/minecraft/worldgen/biome/old_growth_birch_forest.json
- reports/worldgen/minecraft/worldgen/biome/old_growth_pine_taiga.json
- reports/worldgen/minecraft/worldgen/biome/old_growth_spruce_taiga.json
- reports/worldgen/minecraft/worldgen/biome/plains.json
- reports/worldgen/minecraft/worldgen/biome/river.json
- reports/worldgen/minecraft/worldgen/biome/savanna_plateau.json
- reports/worldgen/minecraft/worldgen/biome/savanna.json
- reports/worldgen/minecraft/worldgen/biome/small_end_islands.json
- reports/worldgen/minecraft/worldgen/biome/snowy_beach.json
- reports/worldgen/minecraft/worldgen/biome/snowy_plains.json
- reports/worldgen/minecraft/worldgen/biome/snowy_slopes.json
- reports/worldgen/minecraft/worldgen/biome/snowy_taiga.json
- reports/worldgen/minecraft/worldgen/biome/soul_sand_valley.json
- reports/worldgen/minecraft/worldgen/biome/sparse_jungle.json
- reports/worldgen/minecraft/worldgen/biome/stony_peaks.json
- reports/worldgen/minecraft/worldgen/biome/stony_shore.json
- reports/worldgen/minecraft/worldgen/biome/sunflower_plains.json
- reports/worldgen/minecraft/worldgen/biome/swamp.json
- reports/worldgen/minecraft/worldgen/biome/taiga.json
- reports/worldgen/minecraft/worldgen/biome/the_end.json
- reports/worldgen/minecraft/worldgen/biome/the_void.json
- reports/worldgen/minecraft/worldgen/biome/warm_ocean.json
- reports/worldgen/minecraft/worldgen/biome/warped_forest.json
- reports/worldgen/minecraft/worldgen/biome/windswept_forest.json
- reports/worldgen/minecraft/worldgen/biome/windswept_gravelly_hills.json
- reports/worldgen/minecraft/worldgen/biome/windswept_hills.json
- reports/worldgen/minecraft/worldgen/biome/windswept_savanna.json
- reports/worldgen/minecraft/worldgen/biome/wooded_badlands.json
- reports/worldgen/minecraft/worldgen/configured_carver/canyon.json
- reports/worldgen/minecraft/worldgen/configured_carver/cave_extra_underground.json
- reports/worldgen/minecraft/worldgen/configured_carver/cave.json
- reports/worldgen/minecraft/worldgen/configured_carver/nether_cave.json
- reports/worldgen/minecraft/worldgen/configured_feature/acacia.json
- reports/worldgen/minecraft/worldgen/configured_feature/amethyst_geode.json
- reports/worldgen/minecraft/worldgen/configured_feature/azalea_tree.json
- reports/worldgen/minecraft/worldgen/configured_feature/bamboo_no_podzol.json
- reports/worldgen/minecraft/worldgen/configured_feature/bamboo_some_podzol.json
- reports/worldgen/minecraft/worldgen/configured_feature/bamboo_vegetation.json
- reports/worldgen/minecraft/worldgen/configured_feature/basalt_blobs.json
- reports/worldgen/minecraft/worldgen/configured_feature/basalt_pillar.json
- reports/worldgen/minecraft/worldgen/configured_feature/birch_bees_0002.json
- reports/worldgen/minecraft/worldgen/configured_feature/birch_bees_002.json
- reports/worldgen/minecraft/worldgen/configured_feature/birch_bees_005.json
- reports/worldgen/minecraft/worldgen/configured_feature/birch_tall.json
- reports/worldgen/minecraft/worldgen/configured_feature/birch.json
- reports/worldgen/minecraft/worldgen/configured_feature/blackstone_blobs.json
- reports/worldgen/minecraft/worldgen/configured_feature/blue_ice.json
- reports/worldgen/minecraft/worldgen/configured_feature/bonus_chest.json
- reports/worldgen/minecraft/worldgen/configured_feature/cave_vine_in_moss.json
- reports/worldgen/minecraft/worldgen/configured_feature/cave_vine.json
- reports/worldgen/minecraft/worldgen/configured_feature/chorus_plant.json
- reports/worldgen/minecraft/worldgen/configured_feature/clay_pool_with_dripleaves.json
- reports/worldgen/minecraft/worldgen/configured_feature/clay_with_dripleaves.json
- reports/worldgen/minecraft/worldgen/configured_feature/crimson_forest_vegetation_bonemeal.json
- reports/worldgen/minecraft/worldgen/configured_feature/crimson_forest_vegetation.json
- reports/worldgen/minecraft/worldgen/configured_feature/crimson_fungus_planted.json
- reports/worldgen/minecraft/worldgen/configured_feature/crimson_fungus.json
- reports/worldgen/minecraft/worldgen/configured_feature/dark_forest_vegetation.json
- reports/worldgen/minecraft/worldgen/configured_feature/dark_oak.json
- reports/worldgen/minecraft/worldgen/configured_feature/delta.json
- reports/worldgen/minecraft/worldgen/configured_feature/desert_well.json
- reports/worldgen/minecraft/worldgen/configured_feature/disk_clay.json
- reports/worldgen/minecraft/worldgen/configured_feature/disk_grass.json
- reports/worldgen/minecraft/worldgen/configured_feature/disk_gravel.json
- reports/worldgen/minecraft/worldgen/configured_feature/disk_sand.json
- reports/worldgen/minecraft/worldgen/configured_feature/dripleaf.json
- reports/worldgen/minecraft/worldgen/configured_feature/dripstone_cluster.json
- reports/worldgen/minecraft/worldgen/configured_feature/end_gateway_delayed.json
- reports/worldgen/minecraft/worldgen/configured_feature/end_gateway_return.json
- reports/worldgen/minecraft/worldgen/configured_feature/end_island.json
- reports/worldgen/minecraft/worldgen/configured_feature/end_spike.json
- reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak_bees_0002.json
- reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak_bees_002.json
- reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak_bees_005.json
- reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak_bees.json
- reports/worldgen/minecraft/worldgen/configured_feature/fancy_oak.json
- reports/worldgen/minecraft/worldgen/configured_feature/flower_default.json
- reports/worldgen/minecraft/worldgen/configured_feature/flower_flower_forest.json
- reports/worldgen/minecraft/worldgen/configured_feature/flower_meadow.json
- reports/worldgen/minecraft/worldgen/configured_feature/flower_plain.json
- reports/worldgen/minecraft/worldgen/configured_feature/flower_swamp.json
- reports/worldgen/minecraft/worldgen/configured_feature/forest_flowers.json
- reports/worldgen/minecraft/worldgen/configured_feature/forest_rock.json
- reports/worldgen/minecraft/worldgen/configured_feature/fossil_coal.json
- reports/worldgen/minecraft/worldgen/configured_feature/fossil_diamonds.json
- reports/worldgen/minecraft/worldgen/configured_feature/freeze_top_layer.json
- reports/worldgen/minecraft/worldgen/configured_feature/glow_lichen.json
- reports/worldgen/minecraft/worldgen/configured_feature/glowstone_extra.json
- reports/worldgen/minecraft/worldgen/configured_feature/huge_brown_mushroom.json
- reports/worldgen/minecraft/worldgen/configured_feature/huge_red_mushroom.json
- reports/worldgen/minecraft/worldgen/configured_feature/ice_patch.json
- reports/worldgen/minecraft/worldgen/configured_feature/ice_spike.json
- reports/worldgen/minecraft/worldgen/configured_feature/iceberg_blue.json
- reports/worldgen/minecraft/worldgen/configured_feature/iceberg_packed.json
- reports/worldgen/minecraft/worldgen/configured_feature/jungle_bush.json
- reports/worldgen/minecraft/worldgen/configured_feature/jungle_tree_no_vine.json
- reports/worldgen/minecraft/worldgen/configured_feature/jungle_tree.json
- reports/worldgen/minecraft/worldgen/configured_feature/kelp.json
- reports/worldgen/minecraft/worldgen/configured_feature/lake_lava.json
- reports/worldgen/minecraft/worldgen/configured_feature/large_basalt_columns.json
- reports/worldgen/minecraft/worldgen/configured_feature/large_dripstone.json
- reports/worldgen/minecraft/worldgen/configured_feature/lush_caves_clay.json
- reports/worldgen/minecraft/worldgen/configured_feature/mangrove_vegetation.json
- reports/worldgen/minecraft/worldgen/configured_feature/mangrove.json
- reports/worldgen/minecraft/worldgen/configured_feature/meadow_trees.json
- reports/worldgen/minecraft/worldgen/configured_feature/mega_jungle_tree.json
- reports/worldgen/minecraft/worldgen/configured_feature/mega_pine.json
- reports/worldgen/minecraft/worldgen/configured_feature/mega_spruce.json
- reports/worldgen/minecraft/worldgen/configured_feature/monster_room.json
- reports/worldgen/minecraft/worldgen/configured_feature/moss_patch_bonemeal.json
- reports/worldgen/minecraft/worldgen/configured_feature/moss_patch_ceiling.json
- reports/worldgen/minecraft/worldgen/configured_feature/moss_patch.json
- reports/worldgen/minecraft/worldgen/configured_feature/moss_vegetation.json
- reports/worldgen/minecraft/worldgen/configured_feature/mushroom_island_vegetation.json
- reports/worldgen/minecraft/worldgen/configured_feature/nether_sprouts_bonemeal.json
- reports/worldgen/minecraft/worldgen/configured_feature/nether_sprouts.json
- reports/worldgen/minecraft/worldgen/configured_feature/oak_bees_0002.json
- reports/worldgen/minecraft/worldgen/configured_feature/oak_bees_002.json
- reports/worldgen/minecraft/worldgen/configured_feature/oak_bees_005.json
- reports/worldgen/minecraft/worldgen/configured_feature/oak.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_ancient_debris_large.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_ancient_debris_small.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_andesite.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_blackstone.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_clay.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_coal_buried.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_coal.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_copper_large.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_copper_small.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_diamond_buried.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_diamond_large.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_diamond_small.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_diorite.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_dirt.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_emerald.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_gold_buried.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_gold.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_granite.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_gravel_nether.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_gravel.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_infested.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_iron_small.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_iron.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_lapis_buried.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_lapis.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_magma.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_nether_gold.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_quartz.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_redstone.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_soul_sand.json
- reports/worldgen/minecraft/worldgen/configured_feature/ore_tuff.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_berry_bush.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_brown_mushroom.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_cactus.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_crimson_roots.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_dead_bush.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_fire.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_grass_jungle.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_grass.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_large_fern.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_melon.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_pumpkin.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_red_mushroom.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_soul_fire.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_sugar_cane.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_sunflower.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_taiga_grass.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_tall_grass.json
- reports/worldgen/minecraft/worldgen/configured_feature/patch_waterlily.json
- reports/worldgen/minecraft/worldgen/configured_feature/pile_hay.json
- reports/worldgen/minecraft/worldgen/configured_feature/pile_ice.json
- reports/worldgen/minecraft/worldgen/configured_feature/pile_melon.json
- reports/worldgen/minecraft/worldgen/configured_feature/pile_pumpkin.json
- reports/worldgen/minecraft/worldgen/configured_feature/pile_snow.json
- reports/worldgen/minecraft/worldgen/configured_feature/pine.json
- reports/worldgen/minecraft/worldgen/configured_feature/pointed_dripstone.json
- reports/worldgen/minecraft/worldgen/configured_feature/rooted_azalea_tree.json
- reports/worldgen/minecraft/worldgen/configured_feature/sculk_patch_ancient_city.json
- reports/worldgen/minecraft/worldgen/configured_feature/sculk_patch_deep_dark.json
- reports/worldgen/minecraft/worldgen/configured_feature/sculk_vein.json
- reports/worldgen/minecraft/worldgen/configured_feature/sea_pickle.json
- reports/worldgen/minecraft/worldgen/configured_feature/seagrass_mid.json
- reports/worldgen/minecraft/worldgen/configured_feature/seagrass_short.json
- reports/worldgen/minecraft/worldgen/configured_feature/seagrass_simple.json
- reports/worldgen/minecraft/worldgen/configured_feature/seagrass_slightly_less_short.json
- reports/worldgen/minecraft/worldgen/configured_feature/seagrass_tall.json
- reports/worldgen/minecraft/worldgen/configured_feature/single_piece_of_grass.json
- reports/worldgen/minecraft/worldgen/configured_feature/small_basalt_columns.json
- reports/worldgen/minecraft/worldgen/configured_feature/spore_blossom.json
- reports/worldgen/minecraft/worldgen/configured_feature/spring_lava_frozen.json
- reports/worldgen/minecraft/worldgen/configured_feature/spring_lava_nether.json
- reports/worldgen/minecraft/worldgen/configured_feature/spring_lava_overworld.json
- reports/worldgen/minecraft/worldgen/configured_feature/spring_nether_closed.json
- reports/worldgen/minecraft/worldgen/configured_feature/spring_nether_open.json
- reports/worldgen/minecraft/worldgen/configured_feature/spring_water.json
- reports/worldgen/minecraft/worldgen/configured_feature/spruce.json
- reports/worldgen/minecraft/worldgen/configured_feature/super_birch_bees_0002.json
- reports/worldgen/minecraft/worldgen/configured_feature/super_birch_bees.json
- reports/worldgen/minecraft/worldgen/configured_feature/swamp_oak.json
- reports/worldgen/minecraft/worldgen/configured_feature/tall_mangrove.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_birch_and_oak.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_flower_forest.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_grove.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_jungle.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_old_growth_pine_taiga.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_old_growth_spruce_taiga.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_plains.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_savanna.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_sparse_jungle.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_taiga.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_water.json
- reports/worldgen/minecraft/worldgen/configured_feature/trees_windswept_hills.json
- reports/worldgen/minecraft/worldgen/configured_feature/twisting_vines_bonemeal.json
- reports/worldgen/minecraft/worldgen/configured_feature/twisting_vines.json
- reports/worldgen/minecraft/worldgen/configured_feature/underwater_magma.json
- reports/worldgen/minecraft/worldgen/configured_feature/vines.json
- reports/worldgen/minecraft/worldgen/configured_feature/void_start_platform.json
- reports/worldgen/minecraft/worldgen/configured_feature/warm_ocean_vegetation.json
- reports/worldgen/minecraft/worldgen/configured_feature/warped_forest_vegetation_bonemeal.json
- reports/worldgen/minecraft/worldgen/configured_feature/warped_forest_vegetation.json
- reports/worldgen/minecraft/worldgen/configured_feature/warped_fungus_planted.json
- reports/worldgen/minecraft/worldgen/configured_feature/warped_fungus.json
- reports/worldgen/minecraft/worldgen/configured_feature/weeping_vines.json
- reports/worldgen/minecraft/worldgen/density_function/end/base_3d_noise.json
- reports/worldgen/minecraft/worldgen/density_function/end/sloped_cheese.json
- reports/worldgen/minecraft/worldgen/density_function/nether/base_3d_noise.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/depth.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/factor.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/jaggedness.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/offset.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/sloped_cheese.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/continents.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/depth.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/erosion.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/factor.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/jaggedness.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/offset.json
- reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/sloped_cheese.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/base_3d_noise.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/caves/entrances.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/caves/noodle.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/caves/pillars.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/caves/spaghetti_2d_thickness_modulator.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/caves/spaghetti_2d.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/caves/spaghetti_roughness_function.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/continents.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/depth.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/erosion.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/factor.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/jaggedness.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/offset.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/ridges_folded.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/ridges.json
- reports/worldgen/minecraft/worldgen/density_function/overworld/sloped_cheese.json
- reports/worldgen/minecraft/worldgen/density_function/shift_x.json
- reports/worldgen/minecraft/worldgen/density_function/shift_z.json
- reports/worldgen/minecraft/worldgen/density_function/y.json
- reports/worldgen/minecraft/worldgen/density_function/zero.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/bottomless_pit.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/classic_flat.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/desert.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/overworld.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/redstone_ready.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/snowy_kingdom.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/the_void.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/tunnelers_dream.json
- reports/worldgen/minecraft/worldgen/flat_level_generator_preset/water_world.json
- reports/worldgen/minecraft/worldgen/noise_settings/amplified.json
- reports/worldgen/minecraft/worldgen/noise_settings/caves.json
- reports/worldgen/minecraft/worldgen/noise_settings/end.json
- reports/worldgen/minecraft/worldgen/noise_settings/floating_islands.json
- reports/worldgen/minecraft/worldgen/noise_settings/large_biomes.json
- reports/worldgen/minecraft/worldgen/noise_settings/nether.json
- reports/worldgen/minecraft/worldgen/noise_settings/overworld.json
- reports/worldgen/minecraft/worldgen/noise/aquifer_barrier.json
- reports/worldgen/minecraft/worldgen/noise/aquifer_fluid_level_floodedness.json
- reports/worldgen/minecraft/worldgen/noise/aquifer_fluid_level_spread.json
- reports/worldgen/minecraft/worldgen/noise/aquifer_lava.json
- reports/worldgen/minecraft/worldgen/noise/badlands_pillar_roof.json
- reports/worldgen/minecraft/worldgen/noise/badlands_pillar.json
- reports/worldgen/minecraft/worldgen/noise/badlands_surface.json
- reports/worldgen/minecraft/worldgen/noise/calcite.json
- reports/worldgen/minecraft/worldgen/noise/cave_cheese.json
- reports/worldgen/minecraft/worldgen/noise/cave_entrance.json
- reports/worldgen/minecraft/worldgen/noise/cave_layer.json
- reports/worldgen/minecraft/worldgen/noise/clay_bands_offset.json
- reports/worldgen/minecraft/worldgen/noise/continentalness_large.json
- reports/worldgen/minecraft/worldgen/noise/continentalness.json
- reports/worldgen/minecraft/worldgen/noise/erosion_large.json
- reports/worldgen/minecraft/worldgen/noise/erosion.json
- reports/worldgen/minecraft/worldgen/noise/gravel_layer.json
- reports/worldgen/minecraft/worldgen/noise/gravel.json
- reports/worldgen/minecraft/worldgen/noise/ice.json
- reports/worldgen/minecraft/worldgen/noise/iceberg_pillar_roof.json
- reports/worldgen/minecraft/worldgen/noise/iceberg_pillar.json
- reports/worldgen/minecraft/worldgen/noise/iceberg_surface.json
- reports/worldgen/minecraft/worldgen/noise/jagged.json
- reports/worldgen/minecraft/worldgen/noise/nether_state_selector.json
- reports/worldgen/minecraft/worldgen/noise/nether_wart.json
- reports/worldgen/minecraft/worldgen/noise/netherrack.json
- reports/worldgen/minecraft/worldgen/noise/noodle_ridge_a.json
- reports/worldgen/minecraft/worldgen/noise/noodle_ridge_b.json
- reports/worldgen/minecraft/worldgen/noise/noodle_thickness.json
- reports/worldgen/minecraft/worldgen/noise/noodle.json
- reports/worldgen/minecraft/worldgen/noise/offset.json
- reports/worldgen/minecraft/worldgen/noise/ore_gap.json
- reports/worldgen/minecraft/worldgen/noise/ore_vein_a.json
- reports/worldgen/minecraft/worldgen/noise/ore_vein_b.json
- reports/worldgen/minecraft/worldgen/noise/ore_veininess.json
- reports/worldgen/minecraft/worldgen/noise/packed_ice.json
- reports/worldgen/minecraft/worldgen/noise/patch.json
- reports/worldgen/minecraft/worldgen/noise/pillar_rareness.json
- reports/worldgen/minecraft/worldgen/noise/pillar_thickness.json
- reports/worldgen/minecraft/worldgen/noise/pillar.json
- reports/worldgen/minecraft/worldgen/noise/powder_snow.json
- reports/worldgen/minecraft/worldgen/noise/ridge.json
- reports/worldgen/minecraft/worldgen/noise/soul_sand_layer.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_2d_elevation.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_2d_modulator.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_2d_thickness.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_2d.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_3d_1.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_3d_2.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_3d_rarity.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_3d_thickness.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_roughness_modulator.json
- reports/worldgen/minecraft/worldgen/noise/spaghetti_roughness.json
- reports/worldgen/minecraft/worldgen/noise/surface_secondary.json
- reports/worldgen/minecraft/worldgen/noise/surface_swamp.json
- reports/worldgen/minecraft/worldgen/noise/surface.json
- reports/worldgen/minecraft/worldgen/noise/temperature_large.json
- reports/worldgen/minecraft/worldgen/noise/temperature.json
- reports/worldgen/minecraft/worldgen/noise/vegetation_large.json
- reports/worldgen/minecraft/worldgen/noise/vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/acacia_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/acacia.json
- reports/worldgen/minecraft/worldgen/placed_feature/amethyst_geode.json
- reports/worldgen/minecraft/worldgen/placed_feature/bamboo_light.json
- reports/worldgen/minecraft/worldgen/placed_feature/bamboo_vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/bamboo.json
- reports/worldgen/minecraft/worldgen/placed_feature/basalt_blobs.json
- reports/worldgen/minecraft/worldgen/placed_feature/basalt_pillar.json
- reports/worldgen/minecraft/worldgen/placed_feature/birch_bees_0002.json
- reports/worldgen/minecraft/worldgen/placed_feature/birch_bees_002.json
- reports/worldgen/minecraft/worldgen/placed_feature/birch_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/birch_tall.json
- reports/worldgen/minecraft/worldgen/placed_feature/blackstone_blobs.json
- reports/worldgen/minecraft/worldgen/placed_feature/blue_ice.json
- reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_nether.json
- reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_normal.json
- reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_old_growth.json
- reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_swamp.json
- reports/worldgen/minecraft/worldgen/placed_feature/brown_mushroom_taiga.json
- reports/worldgen/minecraft/worldgen/placed_feature/cave_vines.json
- reports/worldgen/minecraft/worldgen/placed_feature/chorus_plant.json
- reports/worldgen/minecraft/worldgen/placed_feature/classic_vines_cave_feature.json
- reports/worldgen/minecraft/worldgen/placed_feature/crimson_forest_vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/crimson_fungi.json
- reports/worldgen/minecraft/worldgen/placed_feature/dark_forest_vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/dark_oak_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/delta.json
- reports/worldgen/minecraft/worldgen/placed_feature/desert_well.json
- reports/worldgen/minecraft/worldgen/placed_feature/disk_clay.json
- reports/worldgen/minecraft/worldgen/placed_feature/disk_grass.json
- reports/worldgen/minecraft/worldgen/placed_feature/disk_gravel.json
- reports/worldgen/minecraft/worldgen/placed_feature/disk_sand.json
- reports/worldgen/minecraft/worldgen/placed_feature/dripstone_cluster.json
- reports/worldgen/minecraft/worldgen/placed_feature/end_gateway_return.json
- reports/worldgen/minecraft/worldgen/placed_feature/end_island_decorated.json
- reports/worldgen/minecraft/worldgen/placed_feature/end_spike.json
- reports/worldgen/minecraft/worldgen/placed_feature/fancy_oak_bees_0002.json
- reports/worldgen/minecraft/worldgen/placed_feature/fancy_oak_bees_002.json
- reports/worldgen/minecraft/worldgen/placed_feature/fancy_oak_bees.json
- reports/worldgen/minecraft/worldgen/placed_feature/fancy_oak_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/flower_default.json
- reports/worldgen/minecraft/worldgen/placed_feature/flower_flower_forest.json
- reports/worldgen/minecraft/worldgen/placed_feature/flower_forest_flowers.json
- reports/worldgen/minecraft/worldgen/placed_feature/flower_meadow.json
- reports/worldgen/minecraft/worldgen/placed_feature/flower_plain.json
- reports/worldgen/minecraft/worldgen/placed_feature/flower_plains.json
- reports/worldgen/minecraft/worldgen/placed_feature/flower_swamp.json
- reports/worldgen/minecraft/worldgen/placed_feature/flower_warm.json
- reports/worldgen/minecraft/worldgen/placed_feature/forest_flowers.json
- reports/worldgen/minecraft/worldgen/placed_feature/forest_rock.json
- reports/worldgen/minecraft/worldgen/placed_feature/fossil_lower.json
- reports/worldgen/minecraft/worldgen/placed_feature/fossil_upper.json
- reports/worldgen/minecraft/worldgen/placed_feature/freeze_top_layer.json
- reports/worldgen/minecraft/worldgen/placed_feature/glow_lichen.json
- reports/worldgen/minecraft/worldgen/placed_feature/glowstone_extra.json
- reports/worldgen/minecraft/worldgen/placed_feature/glowstone.json
- reports/worldgen/minecraft/worldgen/placed_feature/grass_bonemeal.json
- reports/worldgen/minecraft/worldgen/placed_feature/ice_patch.json
- reports/worldgen/minecraft/worldgen/placed_feature/ice_spike.json
- reports/worldgen/minecraft/worldgen/placed_feature/iceberg_blue.json
- reports/worldgen/minecraft/worldgen/placed_feature/iceberg_packed.json
- reports/worldgen/minecraft/worldgen/placed_feature/jungle_bush.json
- reports/worldgen/minecraft/worldgen/placed_feature/jungle_tree.json
- reports/worldgen/minecraft/worldgen/placed_feature/kelp_cold.json
- reports/worldgen/minecraft/worldgen/placed_feature/kelp_warm.json
- reports/worldgen/minecraft/worldgen/placed_feature/lake_lava_surface.json
- reports/worldgen/minecraft/worldgen/placed_feature/lake_lava_underground.json
- reports/worldgen/minecraft/worldgen/placed_feature/large_basalt_columns.json
- reports/worldgen/minecraft/worldgen/placed_feature/large_dripstone.json
- reports/worldgen/minecraft/worldgen/placed_feature/lush_caves_ceiling_vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/lush_caves_clay.json
- reports/worldgen/minecraft/worldgen/placed_feature/lush_caves_vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/mangrove_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/mega_jungle_tree_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/mega_pine_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/mega_spruce_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/monster_room_deep.json
- reports/worldgen/minecraft/worldgen/placed_feature/monster_room.json
- reports/worldgen/minecraft/worldgen/placed_feature/mushroom_island_vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/nether_sprouts.json
- reports/worldgen/minecraft/worldgen/placed_feature/oak_bees_0002.json
- reports/worldgen/minecraft/worldgen/placed_feature/oak_bees_002.json
- reports/worldgen/minecraft/worldgen/placed_feature/oak_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/oak.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_ancient_debris_large.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_andesite_lower.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_andesite_upper.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_blackstone.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_clay.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_coal_lower.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_coal_upper.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_copper_large.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_copper.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_debris_small.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_diamond_buried.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_diamond_large.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_diamond.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_diorite_lower.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_diorite_upper.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_dirt.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_emerald.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_gold_deltas.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_gold_extra.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_gold_lower.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_gold_nether.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_gold.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_granite_lower.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_granite_upper.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_gravel_nether.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_gravel.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_infested.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_iron_middle.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_iron_small.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_iron_upper.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_lapis_buried.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_lapis.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_magma.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_quartz_deltas.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_quartz_nether.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_redstone_lower.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_redstone.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_soul_sand.json
- reports/worldgen/minecraft/worldgen/placed_feature/ore_tuff.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_berry_bush.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_berry_common.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_berry_rare.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_cactus_decorated.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_cactus_desert.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_cactus.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_crimson_roots.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_dead_bush_2.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_dead_bush_badlands.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_dead_bush.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_fire.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_badlands.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_forest.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_jungle.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_normal.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_plain.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_savanna.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_taiga_2.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_grass_taiga.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_large_fern.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_melon_sparse.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_melon.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_pumpkin.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_soul_fire.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_sugar_cane_badlands.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_sugar_cane_desert.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_sugar_cane_swamp.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_sugar_cane.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_sunflower.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_taiga_grass.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_tall_grass_2.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_tall_grass.json
- reports/worldgen/minecraft/worldgen/placed_feature/patch_waterlily.json
- reports/worldgen/minecraft/worldgen/placed_feature/pile_hay.json
- reports/worldgen/minecraft/worldgen/placed_feature/pile_ice.json
- reports/worldgen/minecraft/worldgen/placed_feature/pile_melon.json
- reports/worldgen/minecraft/worldgen/placed_feature/pile_pumpkin.json
- reports/worldgen/minecraft/worldgen/placed_feature/pile_snow.json
- reports/worldgen/minecraft/worldgen/placed_feature/pine_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/pine_on_snow.json
- reports/worldgen/minecraft/worldgen/placed_feature/pine.json
- reports/worldgen/minecraft/worldgen/placed_feature/pointed_dripstone.json
- reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_nether.json
- reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_normal.json
- reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_old_growth.json
- reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_swamp.json
- reports/worldgen/minecraft/worldgen/placed_feature/red_mushroom_taiga.json
- reports/worldgen/minecraft/worldgen/placed_feature/rooted_azalea_tree.json
- reports/worldgen/minecraft/worldgen/placed_feature/sculk_patch_ancient_city.json
- reports/worldgen/minecraft/worldgen/placed_feature/sculk_patch_deep_dark.json
- reports/worldgen/minecraft/worldgen/placed_feature/sculk_vein.json
- reports/worldgen/minecraft/worldgen/placed_feature/sea_pickle.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_cold.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_deep_cold.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_deep_warm.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_deep.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_normal.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_river.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_simple.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_swamp.json
- reports/worldgen/minecraft/worldgen/placed_feature/seagrass_warm.json
- reports/worldgen/minecraft/worldgen/placed_feature/small_basalt_columns.json
- reports/worldgen/minecraft/worldgen/placed_feature/spore_blossom.json
- reports/worldgen/minecraft/worldgen/placed_feature/spring_closed_double.json
- reports/worldgen/minecraft/worldgen/placed_feature/spring_closed.json
- reports/worldgen/minecraft/worldgen/placed_feature/spring_delta.json
- reports/worldgen/minecraft/worldgen/placed_feature/spring_lava_frozen.json
- reports/worldgen/minecraft/worldgen/placed_feature/spring_lava.json
- reports/worldgen/minecraft/worldgen/placed_feature/spring_open.json
- reports/worldgen/minecraft/worldgen/placed_feature/spring_water.json
- reports/worldgen/minecraft/worldgen/placed_feature/spruce_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/spruce_on_snow.json
- reports/worldgen/minecraft/worldgen/placed_feature/spruce.json
- reports/worldgen/minecraft/worldgen/placed_feature/super_birch_bees_0002.json
- reports/worldgen/minecraft/worldgen/placed_feature/super_birch_bees.json
- reports/worldgen/minecraft/worldgen/placed_feature/tall_mangrove_checked.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_badlands.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_birch_and_oak.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_birch.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_flower_forest.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_grove.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_jungle.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_mangrove.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_meadow.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_old_growth_pine_taiga.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_old_growth_spruce_taiga.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_plains.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_savanna.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_snowy.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_sparse_jungle.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_swamp.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_taiga.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_water.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_windswept_forest.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_windswept_hills.json
- reports/worldgen/minecraft/worldgen/placed_feature/trees_windswept_savanna.json
- reports/worldgen/minecraft/worldgen/placed_feature/twisting_vines.json
- reports/worldgen/minecraft/worldgen/placed_feature/underwater_magma.json
- reports/worldgen/minecraft/worldgen/placed_feature/vines.json
- reports/worldgen/minecraft/worldgen/placed_feature/void_start_platform.json
- reports/worldgen/minecraft/worldgen/placed_feature/warm_ocean_vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/warped_forest_vegetation.json
- reports/worldgen/minecraft/worldgen/placed_feature/warped_fungi.json
- reports/worldgen/minecraft/worldgen/placed_feature/weeping_vines.json
- reports/worldgen/minecraft/worldgen/processor_list/ancient_city_generic_degradation.json
- reports/worldgen/minecraft/worldgen/processor_list/ancient_city_start_degradation.json
- reports/worldgen/minecraft/worldgen/processor_list/ancient_city_walls_degradation.json
- reports/worldgen/minecraft/worldgen/processor_list/bastion_generic_degradation.json
- reports/worldgen/minecraft/worldgen/processor_list/bottom_rampart.json
- reports/worldgen/minecraft/worldgen/processor_list/bridge.json
- reports/worldgen/minecraft/worldgen/processor_list/empty.json
- reports/worldgen/minecraft/worldgen/processor_list/entrance_replacement.json
- reports/worldgen/minecraft/worldgen/processor_list/farm_desert.json
- reports/worldgen/minecraft/worldgen/processor_list/farm_plains.json
- reports/worldgen/minecraft/worldgen/processor_list/farm_savanna.json
- reports/worldgen/minecraft/worldgen/processor_list/farm_snowy.json
- reports/worldgen/minecraft/worldgen/processor_list/farm_taiga.json
- reports/worldgen/minecraft/worldgen/processor_list/fossil_coal.json
- reports/worldgen/minecraft/worldgen/processor_list/fossil_diamonds.json
- reports/worldgen/minecraft/worldgen/processor_list/fossil_rot.json
- reports/worldgen/minecraft/worldgen/processor_list/high_rampart.json
- reports/worldgen/minecraft/worldgen/processor_list/high_wall.json
- reports/worldgen/minecraft/worldgen/processor_list/housing.json
- reports/worldgen/minecraft/worldgen/processor_list/mossify_10_percent.json
- reports/worldgen/minecraft/worldgen/processor_list/mossify_20_percent.json
- reports/worldgen/minecraft/worldgen/processor_list/mossify_70_percent.json
- reports/worldgen/minecraft/worldgen/processor_list/outpost_rot.json
- reports/worldgen/minecraft/worldgen/processor_list/rampart_degradation.json
- reports/worldgen/minecraft/worldgen/processor_list/roof.json
- reports/worldgen/minecraft/worldgen/processor_list/side_wall_degradation.json
- reports/worldgen/minecraft/worldgen/processor_list/stable_degradation.json
- reports/worldgen/minecraft/worldgen/processor_list/street_plains.json
- reports/worldgen/minecraft/worldgen/processor_list/street_savanna.json
- reports/worldgen/minecraft/worldgen/processor_list/street_snowy_or_taiga.json
- reports/worldgen/minecraft/worldgen/processor_list/treasure_rooms.json
- reports/worldgen/minecraft/worldgen/processor_list/zombie_desert.json
- reports/worldgen/minecraft/worldgen/processor_list/zombie_plains.json
- reports/worldgen/minecraft/worldgen/processor_list/zombie_savanna.json
- reports/worldgen/minecraft/worldgen/processor_list/zombie_snowy.json
- reports/worldgen/minecraft/worldgen/processor_list/zombie_taiga.json
- reports/worldgen/minecraft/worldgen/structure_set/ancient_cities.json
- reports/worldgen/minecraft/worldgen/structure_set/buried_treasures.json
- reports/worldgen/minecraft/worldgen/structure_set/desert_pyramids.json
- reports/worldgen/minecraft/worldgen/structure_set/end_cities.json
- reports/worldgen/minecraft/worldgen/structure_set/igloos.json
- reports/worldgen/minecraft/worldgen/structure_set/jungle_temples.json
- reports/worldgen/minecraft/worldgen/structure_set/mineshafts.json
- reports/worldgen/minecraft/worldgen/structure_set/nether_complexes.json
- reports/worldgen/minecraft/worldgen/structure_set/nether_fossils.json
- reports/worldgen/minecraft/worldgen/structure_set/ocean_monuments.json
- reports/worldgen/minecraft/worldgen/structure_set/ocean_ruins.json
- reports/worldgen/minecraft/worldgen/structure_set/pillager_outposts.json
- reports/worldgen/minecraft/worldgen/structure_set/ruined_portals.json
- reports/worldgen/minecraft/worldgen/structure_set/shipwrecks.json
- reports/worldgen/minecraft/worldgen/structure_set/strongholds.json
- reports/worldgen/minecraft/worldgen/structure_set/swamp_huts.json
- reports/worldgen/minecraft/worldgen/structure_set/villages.json
- reports/worldgen/minecraft/worldgen/structure_set/woodland_mansions.json
- reports/worldgen/minecraft/worldgen/structure/ancient_city.json
- reports/worldgen/minecraft/worldgen/structure/bastion_remnant.json
- reports/worldgen/minecraft/worldgen/structure/buried_treasure.json
- reports/worldgen/minecraft/worldgen/structure/desert_pyramid.json
- reports/worldgen/minecraft/worldgen/structure/end_city.json
- reports/worldgen/minecraft/worldgen/structure/fortress.json
- reports/worldgen/minecraft/worldgen/structure/igloo.json
- reports/worldgen/minecraft/worldgen/structure/jungle_pyramid.json
- reports/worldgen/minecraft/worldgen/structure/mansion.json
- reports/worldgen/minecraft/worldgen/structure/mineshaft_mesa.json
- reports/worldgen/minecraft/worldgen/structure/mineshaft.json
- reports/worldgen/minecraft/worldgen/structure/monument.json
- reports/worldgen/minecraft/worldgen/structure/nether_fossil.json
- reports/worldgen/minecraft/worldgen/structure/ocean_ruin_cold.json
- reports/worldgen/minecraft/worldgen/structure/ocean_ruin_warm.json
- reports/worldgen/minecraft/worldgen/structure/pillager_outpost.json
- reports/worldgen/minecraft/worldgen/structure/ruined_portal_desert.json
- reports/worldgen/minecraft/worldgen/structure/ruined_portal_jungle.json
- reports/worldgen/minecraft/worldgen/structure/ruined_portal_mountain.json
- reports/worldgen/minecraft/worldgen/structure/ruined_portal_nether.json
- reports/worldgen/minecraft/worldgen/structure/ruined_portal_ocean.json
- reports/worldgen/minecraft/worldgen/structure/ruined_portal_swamp.json
- reports/worldgen/minecraft/worldgen/structure/ruined_portal.json
- reports/worldgen/minecraft/worldgen/structure/shipwreck_beached.json
- reports/worldgen/minecraft/worldgen/structure/shipwreck.json
- reports/worldgen/minecraft/worldgen/structure/stronghold.json
- reports/worldgen/minecraft/worldgen/structure/swamp_hut.json
- reports/worldgen/minecraft/worldgen/structure/village_desert.json
- reports/worldgen/minecraft/worldgen/structure/village_plains.json
- reports/worldgen/minecraft/worldgen/structure/village_savanna.json
- reports/worldgen/minecraft/worldgen/structure/village_snowy.json
- reports/worldgen/minecraft/worldgen/structure/village_taiga.json
- reports/worldgen/minecraft/worldgen/template_pool/ancient_city/city_center.json
- reports/worldgen/minecraft/worldgen/template_pool/ancient_city/city_center/walls.json
- reports/worldgen/minecraft/worldgen/template_pool/ancient_city/city/entrance.json
- reports/worldgen/minecraft/worldgen/template_pool/ancient_city/sculk.json
- reports/worldgen/minecraft/worldgen/template_pool/ancient_city/structures.json
- reports/worldgen/minecraft/worldgen/template_pool/ancient_city/walls.json
- reports/worldgen/minecraft/worldgen/template_pool/ancient_city/walls/no_corners.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/blocks/gold.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/bridge_pieces.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/connectors.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/legs.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/rampart_plates.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/ramparts.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/starting_pieces.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/bridge/walls.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/connectors.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/inner.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/outer.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/mirrored_starting_pieces.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/posts.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/rampart_plates.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/ramparts.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/inner.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/outer.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/stairs.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/starting_pieces.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/wall_bases.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/hoglin_stable/walls.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/mobs/hoglin.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/mobs/piglin_melee.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/mobs/piglin.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/starts.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/bases.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/bases/centers.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/brains.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/connectors.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/corners/bottom.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/corners/edges.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/corners/middle.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/corners/top.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/entrances.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/extensions/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/extensions/large_pool.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/extensions/small_pool.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/ramparts.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/roofs.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/stairs.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls/bottom.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls/mid.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls/outer.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/treasure/walls/top.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/center_pieces.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/edge_wall_units.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/edges.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/fillers/stage_0.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/large_ramparts.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/pathways.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/rampart_plates.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/ramparts.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/rot/stage_1.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/stage_0.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/stage_1.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/stage_2.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/stages/stage_3.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/wall_units.json
- reports/worldgen/minecraft/worldgen/template_pool/bastion/units/walls/wall_bases.json
- reports/worldgen/minecraft/worldgen/template_pool/empty.json
- reports/worldgen/minecraft/worldgen/template_pool/pillager_outpost/base_plates.json
- reports/worldgen/minecraft/worldgen/template_pool/pillager_outpost/feature_plates.json
- reports/worldgen/minecraft/worldgen/template_pool/pillager_outpost/features.json
- reports/worldgen/minecraft/worldgen/template_pool/pillager_outpost/towers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/common/animals.json
- reports/worldgen/minecraft/worldgen/template_pool/village/common/butcher_animals.json
- reports/worldgen/minecraft/worldgen/template_pool/village/common/cats.json
- reports/worldgen/minecraft/worldgen/template_pool/village/common/iron_golem.json
- reports/worldgen/minecraft/worldgen/template_pool/village/common/sheep.json
- reports/worldgen/minecraft/worldgen/template_pool/village/common/well_bottoms.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/terminators.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/town_centers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/terminators.json
- reports/worldgen/minecraft/worldgen/template_pool/village/desert/zombie/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/terminators.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/town_centers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/trees.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/zombie/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/zombie/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/zombie/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/plains/zombie/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/terminators.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/town_centers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/trees.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/terminators.json
- reports/worldgen/minecraft/worldgen/template_pool/village/savanna/zombie/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/terminators.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/town_centers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/trees.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/zombie/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/zombie/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/zombie/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/snowy/zombie/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/terminators.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/town_centers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/villagers.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/zombie/decor.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/zombie/houses.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/zombie/streets.json
- reports/worldgen/minecraft/worldgen/template_pool/village/taiga/zombie/villagers.json
- reports/worldgen/minecraft/worldgen/world_preset/amplified.json
- reports/worldgen/minecraft/worldgen/world_preset/debug_all_block_states.json
- reports/worldgen/minecraft/worldgen/world_preset/flat.json
- reports/worldgen/minecraft/worldgen/world_preset/large_biomes.json
- reports/worldgen/minecraft/worldgen/world_preset/normal.json
- reports/worldgen/minecraft/worldgen/world_preset/single_biome_surface.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/point_of_interest_type/acquirable_job_site.json
+ minecraft/tags/point_of_interest_type/bee_home.json
+ minecraft/tags/point_of_interest_type/village.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:template_mirror
+ minecraft:template_rotation
```

</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.AttributeSupplier$Builder
+ XXX.ai.attributes.DefaultAttributes
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
- XXX.ai.behavior.AnimalMakeLove
+ XXX.ai.behavior.AnimalPanic
- XXX.ai.behavior.AssignProfessionFromJobSite
+ XXX.ai.behavior.BabyFollowAdult
- XXX.ai.behavior.BackUpIfTooClose
+ XXX.ai.behavior.BecomePassiveIfMemoryPresent
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosTracker
- XXX.ai.behavior.CelebrateVillagersSurvivedRaid
+ XXX.ai.behavior.CopyMemoryWithExpiry
- XXX.ai.behavior.CountDownCooldownTicks
+ XXX.ai.behavior.Croak
- XXX.ai.behavior.CrossbowAttack
+ XXX.ai.behavior.CrossbowAttack$CrossbowState
- XXX.ai.behavior.DismountOrSkipMounting
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityTracker
+ XXX.ai.behavior.EraseMemoryIf
- XXX.ai.behavior.FlyingRandomStroll
+ XXX.ai.behavior.FollowTemptation
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoAndGiveItemsToTarget
+ XXX.ai.behavior.GoOutsideToCelebrate
- XXX.ai.behavior.GoToClosestVillage
+ XXX.ai.behavior.GoToPotentialJobSite
- XXX.ai.behavior.GoToTargetLocation
+ XXX.ai.behavior.GoToWantedItem
- XXX.ai.behavior.HarvestFarmland
+ XXX.ai.behavior.InsideBrownianWalk
- XXX.ai.behavior.InteractWith
+ XXX.ai.behavior.InteractWithDoor
- XXX.ai.behavior.JumpOnBed
+ XXX.ai.behavior.LocateHidingPlace
- XXX.ai.behavior.LocateHidingPlaceDuringRaid
+ XXX.ai.behavior.LongJumpMidJump
- XXX.ai.behavior.LongJumpToPreferredBlock
+ XXX.ai.behavior.LongJumpToRandomPos
- XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MeleeAttack
- XXX.ai.behavior.Mount
+ XXX.ai.behavior.MoveToSkySeeingSpot
- XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.package-info
+ XXX.ai.behavior.PlayTagWithOtherKids
- XXX.ai.behavior.PoiCompetitorScan
+ XXX.ai.behavior.PositionTracker
- XXX.ai.behavior.PrepareRamNearestTarget
+ XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
- XXX.ai.behavior.RamTarget
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.RandomSwim
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunIf
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.RunSometimes
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFrom
- XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ XXX.ai.behavior.SetWalkTargetFromBlockMemory
- XXX.ai.behavior.SetWalkTargetFromLookTarget
+ XXX.ai.behavior.ShowTradesToPlayer
- XXX.ai.behavior.ShufflingList
+ XXX.ai.behavior.ShufflingList$WeightedEntry
- XXX.ai.behavior.ShufflingList$WeightedEntry$1
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StayCloseToTarget
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.TryFindLand
- XXX.ai.behavior.TryFindLandNearWater
+ XXX.ai.behavior.TryFindWater
- XXX.ai.behavior.TryLaySpawnOnWaterNearLand
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerMakeLove
+ XXX.ai.behavior.VillagerPanicTrigger
- XXX.ai.behavior.WakeUp
+ XXX.ai.behavior.WorkAtComposter
- XXX.ai.behavior.WorkAtPoi
+ XXX.ai.behavior.YieldJobSite
- XXX.ai.control.BodyRotationControl
+ XXX.ai.control.Control
- XXX.ai.control.FlyingMoveControl
+ XXX.ai.control.JumpControl
- XXX.ai.control.LookControl
+ XXX.ai.control.MoveControl
- XXX.ai.control.MoveControl$Operation
+ XXX.ai.control.package-info
+ XXX.ai.control.SmoothSwimmingLookControl
- XXX.ai.control.SmoothSwimmingMoveControl
- XXX.ai.goal.AvoidEntityGoal
+ XXX.ai.goal.BegGoal
- XXX.ai.goal.BoatGoals
+ XXX.ai.goal.BreakDoorGoal
- XXX.ai.goal.BreathAirGoal
+ XXX.ai.goal.BreedGoal
- XXX.ai.goal.CatLieOnBedGoal
+ XXX.ai.goal.CatSitOnBlockGoal
- XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
+ XXX.ai.goal.DolphinJumpGoal
- XXX.ai.goal.DoorInteractGoal
+ XXX.ai.goal.EatBlockGoal
- XXX.ai.goal.FleeSunGoal
+ XXX.ai.goal.FloatGoal
- XXX.ai.goal.FollowBoatGoal
+ XXX.ai.goal.FollowFlockLeaderGoal
- XXX.ai.goal.FollowMobGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.GolemRandomStrollInVillageGoal
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillageGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.package-info
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
+ XXX.ai.goal.RandomLookAroundGoal
- XXX.ai.goal.RandomStrollGoal
+ XXX.ai.goal.RandomSwimmingGoal
- XXX.ai.goal.RangedAttackGoal
+ XXX.ai.goal.RangedBowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- XXX.ai.goal.RemoveBlockGoal
+ XXX.ai.goal.RestrictSunGoal
- XXX.ai.goal.RunAroundLikeCrazyGoal
+ XXX.ai.goal.SitWhenOrderedToGoal
- XXX.ai.goal.StrollThroughVillageGoal
+ XXX.ai.goal.SwellGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.ExpirableValue
- XXX.ai.memory.MemoryModuleType
+ XXX.ai.memory.MemoryStatus
- XXX.ai.memory.NearestVisibleLivingEntities
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.AmphibiousPathNavigation
- XXX.ai.navigation.FlyingPathNavigation
+ XXX.ai.navigation.GroundPathNavigation
+ XXX.ai.navigation.package-info
- XXX.ai.navigation.PathNavigation
+ XXX.ai.navigation.WallClimberNavigation
- XXX.ai.navigation.WaterBoundPathNavigation
+ XXX.ai.sensing.AdultSensor
- XXX.ai.sensing.AxolotlAttackablesSensor
+ XXX.ai.sensing.DummySensor
- XXX.ai.sensing.FrogAttackablesSensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.IsInWaterSensor
+ XXX.ai.sensing.NearestBedSensor
- XXX.ai.sensing.NearestItemSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
- XXX.ai.sensing.NearestVisibleLivingEntitySensor
- XXX.ai.sensing.package-info
+ XXX.ai.sensing.PiglinBruteSpecificSensor
- XXX.ai.sensing.PiglinSpecificSensor
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
- XXX.ai.sensing.TemptingSensor
+ XXX.ai.sensing.VillagerBabiesSensor
- XXX.ai.sensing.VillagerHostilesSensor
+ XXX.ai.sensing.WardenEntitySensor
- XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
+ XXX.ai.util.AirAndWaterRandomPos
- XXX.ai.util.AirRandomPos
+ XXX.ai.util.DefaultRandomPos
- XXX.ai.util.GoalUtils
+ XXX.ai.util.HoverRandomPos
- XXX.ai.util.LandRandomPos
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
- XXX.arguments.blocks.BlockInput
+ XXX.arguments.blocks.BlockPredicateArgument
- XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ XXX.arguments.blocks.BlockPredicateArgument$Result
- XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
+ XXX.arguments.blocks.BlockStateArgument
- XXX.arguments.blocks.BlockStateParser
+ XXX.arguments.blocks.BlockStateParser$BlockResult
- XXX.arguments.blocks.BlockStateParser$TagResult
+ XXX.arguments.blocks.package-info
- XXX.arguments.coordinates.BlockPosArgument
+ XXX.arguments.coordinates.ColumnPosArgument
- XXX.arguments.coordinates.Coordinates
+ XXX.arguments.coordinates.LocalCoordinates
- XXX.arguments.coordinates.package-info
- XXX.arguments.coordinates.RotationArgument
+ XXX.arguments.coordinates.SwizzleArgument
- XXX.arguments.coordinates.Vec2Argument
+ XXX.arguments.coordinates.Vec3Argument
- XXX.arguments.coordinates.WorldCoordinate
+ XXX.arguments.coordinates.WorldCoordinates
+ XXX.arguments.item.FunctionArgument
- XXX.arguments.item.FunctionArgument$1
+ XXX.arguments.item.FunctionArgument$2
- XXX.arguments.item.FunctionArgument$Result
+ XXX.arguments.item.ItemArgument
- XXX.arguments.item.ItemInput
+ XXX.arguments.item.ItemParser
- XXX.arguments.item.ItemParser$ItemResult
+ XXX.arguments.item.ItemParser$TagResult
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelector$1
- XXX.arguments.selector.EntitySelectorParser
+ XXX.arguments.selector.package-info
+ XXX.behavior.warden.Digging
- XXX.behavior.warden.Emerging
+ XXX.behavior.warden.package-info
+ XXX.behavior.warden.Roar
- XXX.behavior.warden.SetRoarTarget
+ XXX.behavior.warden.SetWardenLookTarget
- XXX.behavior.warden.Sniffing
+ XXX.behavior.warden.SonicBoom
- XXX.behavior.warden.TryToSniff
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.EntityDataSource
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.LiteralContents
+ XXX.chat.contents.NbtContents
+ XXX.chat.contents.package-info
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.StorageDataSource
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
+ XXX.commands.arguments.package-info
- XXX.commands.arguments.StringRepresentableArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TemplateMirrorArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.arguments.UuidArgument
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
+ XXX.commands.synchronization.ArgumentTypeInfo
- XXX.commands.synchronization.ArgumentTypeInfo$Template
+ XXX.commands.synchronization.ArgumentTypeInfos
- XXX.commands.synchronization.ArgumentUtils
+ XXX.commands.synchronization.package-info
+ XXX.commands.synchronization.SingletonArgumentInfo
- XXX.commands.synchronization.SingletonArgumentInfo$Template
+ XXX.commands.synchronization.SuggestionProviders
- XXX.commands.synchronization.SuggestionProviders$Wrapper
+ XXX.core.cauldron.CauldronInteraction
- XXX.core.cauldron.package-info
+ XXX.core.dispenser.AbstractProjectileDispenseBehavior
- XXX.core.dispenser.BoatDispenseItemBehavior
+ XXX.core.dispenser.DefaultDispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior$1
- XXX.core.dispenser.DispenseItemBehavior$10
+ XXX.core.dispenser.DispenseItemBehavior$11
- XXX.core.dispenser.DispenseItemBehavior$12
+ XXX.core.dispenser.DispenseItemBehavior$13
- XXX.core.dispenser.DispenseItemBehavior$14
+ XXX.core.dispenser.DispenseItemBehavior$15
- XXX.core.dispenser.DispenseItemBehavior$16
+ XXX.core.dispenser.DispenseItemBehavior$17
- XXX.core.dispenser.DispenseItemBehavior$18
+ XXX.core.dispenser.DispenseItemBehavior$19
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$20
- XXX.core.dispenser.DispenseItemBehavior$21
+ XXX.core.dispenser.DispenseItemBehavior$22
- XXX.core.dispenser.DispenseItemBehavior$23
+ XXX.core.dispenser.DispenseItemBehavior$24
- XXX.core.dispenser.DispenseItemBehavior$25
+ XXX.core.dispenser.DispenseItemBehavior$26
- XXX.core.dispenser.DispenseItemBehavior$27
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$7$1
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$8$1
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.DustColorTransitionOptions
- XXX.core.particles.DustColorTransitionOptions$1
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.DustParticleOptions$1
+ XXX.core.particles.DustParticleOptionsBase
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
- XXX.core.particles.ParticleGroup
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SculkChargeParticleOptions
+ XXX.core.particles.SculkChargeParticleOptions$1
- XXX.core.particles.ShriekParticleOption
+ XXX.core.particles.ShriekParticleOption$1
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
- XXX.core.particles.VibrationParticleOption
+ XXX.core.particles.VibrationParticleOption$1
+ XXX.data.tags.package-info
- XXX.data.tags.PoiTypeTagsProvider
+ XXX.data.tags.StructureTagsProvider
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.WorldPresetTagsProvider
- XXX.data.worldgen.AncientCityStructurePieces
+ XXX.data.worldgen.AncientCityStructurePools
- XXX.data.worldgen.BastionBridgePools
+ XXX.data.worldgen.BastionHoglinStablePools
- XXX.data.worldgen.BastionHousingUnitsPools
+ XXX.data.worldgen.BastionPieces
- XXX.data.worldgen.BastionSharedPools
+ XXX.data.worldgen.BastionTreasureRoomPools
- XXX.data.worldgen.BiomeDefaultFeatures
+ XXX.data.worldgen.Carvers
- XXX.data.worldgen.DesertVillagePools
+ XXX.data.worldgen.DimensionTypes
- XXX.data.worldgen.NoiseData
+ XXX.data.worldgen.package-info
+ XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.PlainVillagePools
+ XXX.data.worldgen.Pools
- XXX.data.worldgen.ProcessorLists
+ XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.SnowyVillagePools
- XXX.data.worldgen.Structures
+ XXX.data.worldgen.StructureSets
+ XXX.data.worldgen.SurfaceRuleData
- XXX.data.worldgen.TaigaVillagePools
+ XXX.data.worldgen.TerrainProvider
- XXX.data.worldgen.VillagePools
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehivePoiRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlendingDataFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockRenameFixWithJigsaw
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.CauldronRenameFix
- XXX.datafix.fixes.CavesAndCliffsRenames
+ XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingFieldsRenameFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRename
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RemoveGolemGossipFix
+ XXX.datafix.fixes.RenameBiomesFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
+ XXX.datafix.fixes.SavedDataVillageCropFix
- XXX.datafix.fixes.SimpleEntityRenameFix
+ XXX.datafix.fixes.SimpleRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.SpawnerDataFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StatsRenameFix
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- XXX.datafix.fixes.StructureSettingsFlattenFix
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WeaponSmithChestLootTableFix
- XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- XXX.datafix.fixes.WriteAndReadFix
+ XXX.datafix.fixes.ZombieVillagerRebuildXpFix
- XXX.datafix.schemas.NamespacedSchema
+ XXX.datafix.schemas.NamespacedSchema$1
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V100
+ XXX.datafix.schemas.V102
- XXX.datafix.schemas.V1022
+ XXX.datafix.schemas.V106
- XXX.datafix.schemas.V107
+ XXX.datafix.schemas.V1125
- XXX.datafix.schemas.V135
+ XXX.datafix.schemas.V143
- XXX.datafix.schemas.V1451
+ XXX.datafix.schemas.V1451_1
- XXX.datafix.schemas.V1451_2
+ XXX.datafix.schemas.V1451_3
- XXX.datafix.schemas.V1451_4
+ XXX.datafix.schemas.V1451_5
- XXX.datafix.schemas.V1451_6
+ XXX.datafix.schemas.V1451_6$1
- XXX.datafix.schemas.V1451_6$2
+ XXX.datafix.schemas.V1451_7
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
+ XXX.datafix.schemas.V2831
- XXX.datafix.schemas.V2832
+ XXX.datafix.schemas.V2842
- XXX.datafix.schemas.V3076
+ XXX.datafix.schemas.V3078
- XXX.datafix.schemas.V3081
+ XXX.datafix.schemas.V3082
- XXX.datafix.schemas.V3083
+ XXX.datafix.schemas.V501
- XXX.datafix.schemas.V700
+ XXX.datafix.schemas.V701
- XXX.datafix.schemas.V702
+ XXX.datafix.schemas.V703
- XXX.datafix.schemas.V704
+ XXX.datafix.schemas.V704$1
- XXX.datafix.schemas.V705
+ XXX.datafix.schemas.V705$1
- XXX.datafix.schemas.V808
+ XXX.datafix.schemas.V99
- XXX.datafix.schemas.V99$1
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
- XXX.entity.ai.package-info
+ XXX.gametest.framework.AfterBatch
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.ExhaustedAttemptsException
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchRunner
+ XXX.gametest.framework.GameTestBatchRunner$1
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestHelper$1
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
+ XXX.goal.target.package-info
+ XXX.goal.target.ResetUniversalAngerTargetGoal
- XXX.goal.target.TargetGoal
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent
+ XXX.jfr.event.NetworkSummaryEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent$SumAggregation
- XXX.jfr.event.package-info
+ XXX.jfr.event.PacketEvent
- XXX.jfr.event.PacketEvent$Fields
+ XXX.jfr.event.PacketReceivedEvent
- XXX.jfr.event.PacketSentEvent
+ XXX.jfr.event.ServerTickTimeEvent
- XXX.jfr.event.ServerTickTimeEvent$Fields
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.CpuLoadStat
+ XXX.jfr.stats.FileIOStat
- XXX.jfr.stats.FileIOStat$Summary
+ XXX.jfr.stats.GcHeapStat
- XXX.jfr.stats.GcHeapStat$Summary
+ XXX.jfr.stats.GcHeapStat$Timing
- XXX.jfr.stats.NetworkPacketSummary
+ XXX.jfr.stats.NetworkPacketSummary$PacketCountAndSize
- XXX.jfr.stats.NetworkPacketSummary$PacketIdentification
+ XXX.jfr.stats.package-info
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
- XXX.jfr.stats.TimeStamped
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.metrics.profiling.ActiveMetricsRecorder
- XXX.metrics.profiling.InactiveMetricsRecorder
+ XXX.metrics.profiling.MetricsRecorder
- XXX.metrics.profiling.package-info
- XXX.metrics.profiling.ProfilerSamplerAdapter
+ XXX.metrics.profiling.ServerMetricsSamplersProvider
- XXX.metrics.profiling.ServerMetricsSamplersProvider$1
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ XXX.metrics.storage.MetricsPersister
+ XXX.metrics.storage.package-info
- XXX.metrics.storage.RecordedDeviation
- XXX.minecraft.commands.package-info
- XXX.minecraft.core.AxisCycle
+ XXX.minecraft.core.AxisCycle$1
- XXX.minecraft.core.AxisCycle$2
+ XXX.minecraft.core.AxisCycle$3
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$4
- XXX.minecraft.core.BlockPos$5
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockSource
+ XXX.minecraft.core.BlockSourceImpl
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
+ XXX.minecraft.core.Direction$1
- XXX.minecraft.core.Direction$Axis
+ XXX.minecraft.core.Direction$Axis$1
- XXX.minecraft.core.Direction$Axis$2
+ XXX.minecraft.core.Direction$Axis$3
- XXX.minecraft.core.Direction$AxisDirection
+ XXX.minecraft.core.Direction$Plane
- XXX.minecraft.core.Direction8
+ XXX.minecraft.core.FrontAndTop
- XXX.minecraft.core.GlobalPos
+ XXX.minecraft.core.Holder
- XXX.minecraft.core.Holder$Direct
+ XXX.minecraft.core.Holder$Kind
- XXX.minecraft.core.Holder$Reference
+ XXX.minecraft.core.Holder$Reference$Type
- XXX.minecraft.core.HolderLookup
+ XXX.minecraft.core.HolderLookup$RegistryLookup
- XXX.minecraft.core.HolderSet
+ XXX.minecraft.core.HolderSet$Direct
- XXX.minecraft.core.HolderSet$ListBacked
+ XXX.minecraft.core.HolderSet$Named
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.NonNullList
- XXX.minecraft.core.package-info
- XXX.minecraft.core.Position
+ XXX.minecraft.core.PositionImpl
- XXX.minecraft.core.QuartPos
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.Registry$1
+ XXX.minecraft.core.Registry$RegistryBootstrap
- XXX.minecraft.core.RegistryAccess
+ XXX.minecraft.core.RegistryAccess$1
- XXX.minecraft.core.RegistryAccess$Frozen
+ XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryData
+ XXX.minecraft.core.RegistryAccess$RegistryEntry
- XXX.minecraft.core.RegistryAccess$Writable
+ XXX.minecraft.core.RegistryAccess$WritableRegistryAccess
- XXX.minecraft.core.RegistryCodecs
+ XXX.minecraft.core.RegistryCodecs$1
- XXX.minecraft.core.RegistryCodecs$RegistryEntry
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.UUIDUtil
+ XXX.minecraft.core.Vec3i
- XXX.minecraft.core.WritableRegistry
+ XXX.minecraft.data.BlockFamilies
- XXX.minecraft.data.BlockFamily
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.BuiltinRegistries
- XXX.minecraft.data.BuiltinRegistries$RegistryBootstrap
- XXX.minecraft.data.DataGenerator$Target
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.Language$1
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.CompoundTag$2
- XXX.minecraft.nbt.DoubleTag
+ XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag
+ XXX.minecraft.nbt.EndTag$1
- XXX.minecraft.nbt.FloatTag
+ XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag
+ XXX.minecraft.nbt.IntArrayTag$1
- XXX.minecraft.nbt.IntTag
+ XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
+ XXX.minecraft.nbt.ListTag$2
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor$EntryResult
- XXX.minecraft.nbt.StreamTagVisitor$ValueResult
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.StringTagVisitor
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagType$2
+ XXX.minecraft.nbt.TagType$StaticSize
- XXX.minecraft.nbt.TagType$VariableSize
+ XXX.minecraft.nbt.TagTypes
- XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.nbt.TextComponentTagVisitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$PacketHolder
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.FriendlyByteBuf$Reader
+ XXX.minecraft.network.FriendlyByteBuf$Writer
+ XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.server.package-info
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BannerPatternTags
+ XXX.minecraft.tags.BiomeTags
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.CatVariantTags
- XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.FlatLevelGeneratorPresetTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.InstrumentTags
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.PaintingVariantTags
+ XXX.minecraft.tags.Tag$Builder
+ XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$OptionalElementEntry
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.TagEntry
- XXX.minecraft.tags.TagFile
- XXX.minecraft.tags.TagLoader$EntryWithSource
- XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
+ XXX.minecraft.util.ExtraCodecs$XorCodec
- XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FastColor
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FrameTimer
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.KeyDispatchDataCodec
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.package-info
- XXX.minecraft.util.ParticleUtils
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.SpawnUtil
+ XXX.minecraft.util.StringDecomposer
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$EnumCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TelemetryConstants
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.ToFloatFunction$1
+ XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
- XXX.minecraft.world.BossEvent
+ XXX.minecraft.world.BossEvent$BossBarColor
- XXX.minecraft.world.BossEvent$BossBarOverlay
+ XXX.minecraft.world.Clearable
- XXX.minecraft.world.CompoundContainer
+ XXX.minecraft.world.Container
- XXX.minecraft.world.ContainerHelper
+ XXX.minecraft.world.ContainerListener
- XXX.minecraft.world.Containers
+ XXX.minecraft.world.Difficulty
- XXX.minecraft.world.DifficultyInstance
+ XXX.minecraft.world.InteractionHand
- XXX.minecraft.world.InteractionResult
+ XXX.minecraft.world.InteractionResultHolder
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.WorldlyContainer
- XXX.minecraft.world.WorldlyContainerHolder
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
- XXX.monster.warden.Warden$1$1
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.FieldSelector
- XXX.nbt.visitors.FieldTree
- XXX.nbt.visitors.package-info
+ XXX.nbt.visitors.SkipAll
- XXX.nbt.visitors.SkipAll$1
+ XXX.nbt.visitors.SkipFields
+ XXX.network.chat.ChatDecoration
- XXX.network.chat.ChatDecoration$Parameter
+ XXX.network.chat.ChatDecoration$Parameter$Selector
- XXX.network.chat.ChatDecorator
- XXX.network.chat.ChatSender
+ XXX.network.chat.ChatType
- XXX.network.chat.ChatType$Narration
+ XXX.network.chat.ChatType$Narration$Priority
- XXX.network.chat.ChatType$TextDisplay
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentContents$1
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.FormattedText
- XXX.network.chat.FormattedText$1
+ XXX.network.chat.FormattedText$2
- XXX.network.chat.FormattedText$3
+ XXX.network.chat.FormattedText$4
- XXX.network.chat.FormattedText$ContentConsumer
+ XXX.network.chat.FormattedText$StyledContentConsumer
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSigner
- XXX.network.chat.MutableComponent
- XXX.network.chat.package-info
+ XXX.network.chat.SignedMessage
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$1Collector
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.SubStringSource
+ XXX.network.chat.TextColor
- XXX.network.chat.ThrowingComponent
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
+ XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.Pack
+ XXX.packs.repository.Pack$PackConstructor
- XXX.packs.repository.Pack$Position
- XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.RepositorySource
+ XXX.packs.repository.ServerPacksSource
+ XXX.packs.resources.CloseableResourceManager
- XXX.packs.resources.FallbackResourceManager
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$SinglePackResourceThunkSupplier
+ XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.package-info
- XXX.packs.resources.PreparableReloadListener
+ XXX.packs.resources.PreparableReloadListener$PreparationBarrier
- XXX.packs.resources.ProfiledReloadInstance
+ XXX.packs.resources.ProfiledReloadInstance$State
+ XXX.packs.resources.ReloadableResourceManager
- XXX.packs.resources.ReloadInstance
- XXX.packs.resources.Resource
+ XXX.packs.resources.Resource$IoSupplier
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceFilterSection$1
- XXX.packs.resources.ResourceFilterSection$ResourceLocationPattern
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManager$Empty
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.ResourceMetadata
+ XXX.packs.resources.ResourceMetadata$1
- XXX.packs.resources.ResourceMetadata$2
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
- XXX.profiling.metrics.MetricCategory
+ XXX.profiling.metrics.MetricSampler
- XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ XXX.profiling.metrics.MetricSampler$SamplerResult
- XXX.profiling.metrics.MetricSampler$ThresholdTest
+ XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- XXX.profiling.metrics.MetricsRegistry
+ XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- XXX.profiling.metrics.MetricsSamplerProvider
- XXX.profiling.metrics.package-info
+ XXX.profiling.metrics.ProfilerMeasured
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockChangedAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$AddOperation
+ XXX.protocol.game.ClientboundBossEventPacket$Handler
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundBossEventPacket$OperationType
- XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundServerDataPacket
+ XXX.protocol.game.ClientboundSetActionBarTextPacket
- XXX.protocol.game.ClientboundSetBorderCenterPacket
+ XXX.protocol.game.ClientboundSetBorderLerpSizePacket
- XXX.protocol.game.ClientboundSetBorderSizePacket
+ XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
- XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetSimulationDistancePacket
- XXX.protocol.game.ClientboundSetSubtitleTextPacket
+ XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesAnimationPacket
- XXX.protocol.game.ClientboundSetTitleTextPacket
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundSystemChatPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
+ XXX.server.commands.package-info
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PlaceCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ResetChunksCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.SeedCommand
- XXX.server.commands.SetBlockCommand
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpectateCommand
+ XXX.server.commands.SpreadPlayersCommand
- XXX.server.commands.SpreadPlayersCommand$Position
+ XXX.server.commands.StopCommand
- XXX.server.commands.StopSoundCommand
+ XXX.server.commands.SummonCommand
- XXX.server.commands.TagCommand
+ XXX.server.commands.TeamCommand
- XXX.server.commands.TeamMsgCommand
+ XXX.server.commands.TeleportCommand
- XXX.server.commands.TeleportCommand$LookAt
+ XXX.server.commands.TellRawCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TriggerCommand
+ XXX.server.commands.WardenSpawnTrackerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerProperties$WorldGenProperties
+ XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$MutableValue
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$1
- XXX.server.level.ChunkHolder$ChunkLoadingFailure
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
- XXX.server.level.ChunkHolder$ChunkSaveDebug
+ XXX.server.level.ChunkHolder$FullChunkStatus
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$1
- XXX.server.level.ChunkMap$2
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Message
- XXX.server.level.ChunkTaskPriorityQueueSorter$Release
+ XXX.server.level.ChunkTracker
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$ChunkAndHolder
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$3
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.TickingTracker
- XXX.server.level.WorldGenRegion
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerGamePacketListenerImpl$2
- XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$PublicKeyParseException
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerPlayerConnection
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.network.TextFilter
- XXX.server.network.TextFilter$1
+ XXX.server.network.TextFilter$FilteredText
- XXX.server.network.TextFilterClient
+ XXX.server.network.TextFilterClient$IgnoreStrategy
- XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
+ XXX.server.network.TextFilterClient$MessageEncoder
- XXX.server.network.TextFilterClient$PlayerContext
+ XXX.server.network.TextFilterClient$RequestFailedException
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.FilePackResources
- XXX.server.packs.FolderPackResources
- XXX.server.packs.package-info
+ XXX.server.packs.PackResources
- XXX.server.packs.PackType
+ XXX.server.packs.ResourcePackFileNotFoundException
- XXX.server.packs.VanillaPackResources
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
+ XXX.synchronization.brigadier.DoubleArgumentInfo
- XXX.synchronization.brigadier.DoubleArgumentInfo$Template
+ XXX.synchronization.brigadier.FloatArgumentInfo
- XXX.synchronization.brigadier.FloatArgumentInfo$Template
+ XXX.synchronization.brigadier.IntegerArgumentInfo
- XXX.synchronization.brigadier.IntegerArgumentInfo$Template
+ XXX.synchronization.brigadier.LongArgumentInfo
- XXX.synchronization.brigadier.LongArgumentInfo$Template
- XXX.synchronization.brigadier.package-info
+ XXX.synchronization.brigadier.StringArgumentSerializer
- XXX.synchronization.brigadier.StringArgumentSerializer$1
+ XXX.synchronization.brigadier.StringArgumentSerializer$Template
+ XXX.util.datafix.DataFixerOptimizationOption
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixers$3
- XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.package-info
- XXX.util.datafix.PackedBitStorage
- XXX.util.profiling.ActiveProfiler
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
- XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.random.package-info
+ XXX.util.random.SimpleWeightedRandomList
- XXX.util.random.SimpleWeightedRandomList$Builder
+ XXX.util.random.Weight
- XXX.util.random.WeightedEntry
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedEntry$Wrapper
+ XXX.util.random.WeightedRandom
- XXX.util.random.WeightedRandomList
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
- XXX.util.thread.ProcessorHandle
+ XXX.util.thread.ProcessorHandle$1
- XXX.util.thread.ProcessorMailbox
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$IntRunnable
+ XXX.util.thread.StrictQueue$QueueStrictQueue
+ XXX.util.valueproviders.BiasedToBottomInt
- XXX.util.valueproviders.ClampedInt
+ XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ClampedNormalInt
+ XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.ConstantInt
+ XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.FloatProviderType
+ XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.MultipliedFloats
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.SampledFloat
+ XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformFloat
+ XXX.util.valueproviders.UniformInt
- XXX.util.valueproviders.WeightedListInt
+ XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
- XXX.village.poi.PoiTypes
+ XXX.world.damagesource.BadRespawnPointDamage
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.EntityDamageSource
+ XXX.world.damagesource.IndirectEntityDamageSource
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsoptionMobEffect
- XXX.world.effect.AttackDamageMobEffect
+ XXX.world.effect.HealthBoostMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffectCategory
+ XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffectInstance$FactorData
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AnimationState
- XXX.world.entity.AreaEffectCloud
+ XXX.world.entity.Entity
- XXX.world.entity.Entity$1
+ XXX.world.entity.Entity$MoveFunction
- XXX.world.entity.Entity$MovementEmission
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.LerpingModel
- XXX.world.entity.LightningBolt
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.LivingEntity$Fallsounds
- XXX.world.entity.Marker
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.Pose
+ XXX.world.entity.PowerableMob
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacements$Type
- XXX.world.entity.TamableAnimal
+ XXX.worldgen.biome.Biomes
- XXX.worldgen.biome.EndBiomes
+ XXX.worldgen.biome.NetherBiomes
- XXX.worldgen.biome.OverworldBiomes
+ XXX.worldgen.biome.package-info
- XXX.worldgen.features.AquaticFeatures
+ XXX.worldgen.features.CaveFeatures
- XXX.worldgen.features.EndFeatures
+ XXX.worldgen.features.FeatureUtils
- XXX.worldgen.features.MiscOverworldFeatures
+ XXX.worldgen.features.NetherFeatures
- XXX.worldgen.features.OreFeatures
- XXX.worldgen.features.package-info
+ XXX.worldgen.features.PileFeatures
- XXX.worldgen.features.TreeFeatures
+ XXX.worldgen.features.VegetationFeatures
- XXX.worldgen.placement.AquaticPlacements
+ XXX.worldgen.placement.CavePlacements
- XXX.worldgen.placement.EndPlacements
+ XXX.worldgen.placement.MiscOverworldPlacements
- XXX.worldgen.placement.NetherPlacements
+ XXX.worldgen.placement.OrePlacements
- XXX.worldgen.placement.package-info
- XXX.worldgen.placement.PlacementUtils
+ XXX.worldgen.placement.TreePlacements
- XXX.worldgen.placement.VegetationPlacements
+ XXX.worldgen.placement.VillagePlacements
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +2M
```
```
XXX.minecraft.commands.CommandSigningContext$PlainArguments +1M -1M
```
```
XXX.commands.arguments.ResourceOrTagLocationArgument +1M -5M | -2P
```
```
XXX.minecraft.data.DataGenerator +2M
```
```
XXX.data.advancements.AdvancementProvider +1M -2M | +1P -1P
```
```
XXX.data.loot.LootTableProvider +1M -2M | +1P -1P
```
```
XXX.data.recipes.RecipeProvider +1M -1M | +2P -1P
```
```
XXX.protocol.game.ClientboundLoginPacket +2M -3M | +1P -1P
```
```
XXX.protocol.game.ClientboundPlayerChatPacket +4M -3M | +2P -1P
```
```
XXX.protocol.game.ClientboundPlayerInfoPacket$Action$1 +1M -2M
```
```
XXX.protocol.game.ClientboundRespawnPacket +2M -2M | +1P -1P
```
```
XXX.protocol.login.ServerboundKeyPacket +2M -3M
```
```
XXX.protocol.status.ServerStatus +2M | +1P
```
```
XXX.network.syncher.EntityDataSerializers -2M
```
```
XXX.minecraft.server.ServerFunctionLibrary +1M -1M
```
```
XXX.server.commands.EmoteCommands +1M -1M
```
```
XXX.minecraft.tags.TagLoader +14M -11M | -1P
```
```
XXX.minecraft.util.ExtraCodecs +5M | +2P
```
```
XXX.entity.animal.Bee$BeeLocateHiveGoal +1M -1M
```
```
XXX.animal.frog.TadpoleAi -1P
```
```
XXX.monster.warden.Warden +3M | +1P
```
```
XXX.monster.warden.WardenSpawnTracker +7M -6M | +1P -1P
```
```
XXX.entity.npc.VillagerProfession +16M -8M | +3P -1P
```
```
XXX.entity.npc.WanderingTraderSpawner +2M -1M
```
```
XXX.entity.player.ProfilePublicKey$Data +7M -6M | +3P -2P
```
```
XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal +1M -1M
```
```
XXX.world.item.InstrumentItem +1M -2M
```
```
XXX.world.level.Level +5M -3M | +1P -1P
```
```
XXX.level.block.Rotation +2M -1M | +2P
```
```
XXX.level.block.SculkShriekerBlock +1M -1M
```
```
XXX.block.entity.SculkShriekerBlockEntity +7M -8M
```
```
XXX.level.levelgen.RandomSupport +2M -2M
```
```
XXX.levelgen.flat.FlatLevelGeneratorPresets +1M -1M
```
```
XXX.levelgen.presets.WorldPresets +1M -1M
```
```
XXX.levelgen.structure.Structure$GenerationStub +5M -1M | +1P -1P
```
```
XXX.structure.structures.MineshaftPieces$MineShaftPiece +1M -1M | +1P
```
```
XXX.level.portal.PortalForcer +1M -1M
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
- Object mapNullable(Object,Function,Object)
- Object mapNullable(Object,Function)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandSigningContext$PlainArguments
</summary>

```diff
- PlayerChatMessage signArgument(CommandContext,String,Component)
+ SignedMessage signArgument(CommandContext,String,Component)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.ResourceOrTagLocationArgument
</summary>

```diff
- CommandSyntaxException lambda$getRegistryType$0(DynamicCommandExceptionType,ResourceOrTagLocationArgument$Result)
+ CommandSyntaxException lambda$getRegistryType$2(DynamicCommandExceptionType,ResourceOrTagLocationArgument$Result)
+ Message lambda$static$0(Object)
+ Message lambda$static$1(Object)
+ ResourceOrTagLocationArgument$Result getBiome(CommandContext,String)
+ ResourceOrTagLocationArgument$Result getStructure(CommandContext,String)
```

</details>
<details>
<summary>
net.minecraft.data.DataGenerator
</summary>

```diff
- DataGenerator$PathProvider createPathProvider(DataGenerator$Target,String)
- Path getOutputFolder(DataGenerator$Target)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.AdvancementProvider
</summary>

```diff
+ Path createPath(Path,Advancement)
- void lambda$run$0(Set,CachedOutput,Advancement)
+ void lambda$run$0(Set,Path,CachedOutput,Advancement)
```

</details>
<details>
<summary>
net.minecraft.data.loot.LootTableProvider
</summary>

```diff
+ Path createPath(Path,ResourceLocation)
- void lambda$run$5(CachedOutput,ResourceLocation,LootTable)
+ void lambda$run$5(Path,CachedOutput,ResourceLocation,LootTable)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- void lambda$run$0(Set,CachedOutput,FinishedRecipe)
+ void lambda$run$0(Set,CachedOutput,Path,FinishedRecipe)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLoginPacket
</summary>

```diff
+ Holder dimensionType()
- ResourceKey dimensionType()
+ void <init>(int,boolean,GameType,GameType,Set,RegistryAccess$Frozen,Holder,ResourceKey,long,int,int,int,boolean,boolean,boolean,boolean)
- void <init>(int,boolean,GameType,GameType,Set,RegistryAccess$Frozen,ResourceKey,ResourceKey,long,int,int,int,boolean,boolean,boolean,boolean)
+ void lambda$write$1(FriendlyByteBuf,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerChatPacket
</summary>

```diff
+ Component content()
- Component signedContent()
- Optional unsignedContent()
- PlayerChatMessage getMessage()
+ SignedMessage getSignedMessage()
+ void <init>(Component,int,ChatSender,Instant,Crypt$SaltSignaturePair)
- void <init>(Component,Optional,int,ChatSender,Instant,Crypt$SaltSignaturePair)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$1
</summary>

```diff
+ ProfilePublicKey$Data lambda$read$0(FriendlyByteBuf)
- void lambda$write$0(FriendlyByteBuf,ProfilePublicKey$Data)
+ void lambda$write$1(FriendlyByteBuf,ProfilePublicKey$Data)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRespawnPacket
</summary>

```diff
+ Holder getDimensionType()
- ResourceKey getDimensionType()
+ void <init>(Holder,ResourceKey,long,GameType,GameType,boolean,boolean,boolean)
- void <init>(ResourceKey,ResourceKey,long,GameType,GameType,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.login.ServerboundKeyPacket
</summary>

```diff
- Boolean lambda$isChallengeSignatureValid$0(byte[])
+ Boolean lambda$isChallengeSignatureValid$1(byte[])
- Boolean lambda$isChallengeSignatureValid$1(ProfilePublicKey,byte[],Crypt$SaltSignaturePair)
+ Boolean lambda$isChallengeSignatureValid$2(ProfilePublicKey,byte[],Crypt$SaltSignaturePair)
+ void lambda$write$0(FriendlyByteBuf,Crypt$SaltSignaturePair)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.status.ServerStatus
</summary>

```diff
- boolean previewsChat()
- void setPreviewsChat(boolean)
```

</details>
<details>
<summary>
net.minecraft.network.syncher.EntityDataSerializers
</summary>

```diff
+ GlobalPos lambda$static$2(FriendlyByteBuf)
+ void lambda$static$1(FriendlyByteBuf,GlobalPos)
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionLibrary
</summary>

```diff
- Collection getTag(ResourceLocation)
+ Tag getTag(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.server.commands.EmoteCommands
</summary>

```diff
- void lambda$register$0(CommandSourceStack,ServerPlayer,PlayerChatMessage,TextFilter$FilteredText)
+ void lambda$register$0(CommandSourceStack,SignedMessage,ServerPlayer,TextFilter$FilteredText)
```

</details>
<details>
<summary>
net.minecraft.tags.TagLoader
</summary>

```diff
+ boolean lambda$isCyclic$3(Multimap,ResourceLocation,ResourceLocation)
- boolean lambda$isCyclic$4(Multimap,ResourceLocation,ResourceLocation)
- Either build(TagEntry$Lookup,List)
- List lambda$load$1(ResourceLocation)
+ Object lambda$build$4(ResourceLocation)
+ Tag$Builder lambda$load$1(ResourceLocation)
+ void lambda$build$10(Map,ResourceLocation,Tag)
- void lambda$build$10(Multimap,ResourceLocation,List)
+ void lambda$build$11(Function,Function,Map,ResourceLocation,Tag$Builder)
- void lambda$build$11(ResourceLocation,Collection)
+ void lambda$build$12(Map,Multimap,Set,Function,Function,Map,ResourceLocation)
- void lambda$build$12(Map,ResourceLocation,Collection)
- void lambda$build$13(TagEntry$Lookup,Map,ResourceLocation,List)
- void lambda$build$14(Map,Multimap,Set,TagEntry$Lookup,Map,ResourceLocation)
+ void lambda$build$6(Multimap,ResourceLocation,Tag$Builder)
- void lambda$build$6(Multimap,ResourceLocation,TagLoader$EntryWithSource)
- void lambda$build$7(Multimap,ResourceLocation,List)
+ void lambda$build$7(Multimap,ResourceLocation,ResourceLocation)
- void lambda$build$8(Multimap,ResourceLocation,ResourceLocation)
+ void lambda$build$8(Multimap,ResourceLocation,Tag$Builder)
- void lambda$build$9(Multimap,ResourceLocation,TagLoader$EntryWithSource)
+ void lambda$build$9(ResourceLocation,Collection)
- void lambda$load$2(List,String,TagEntry)
+ void lambda$visitDependenciesAndElement$2(Map,Multimap,Set,BiConsumer,ResourceLocation)
- void lambda$visitDependenciesAndElement$3(Map,Multimap,Set,BiConsumer,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
- DataResult lambda$static$29(String)
- DataResult lambda$static$33(String)
- ExtraCodecs$TagOrElementLocation lambda$static$31(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$32(ResourceLocation)
- String lambda$static$30(byte[])
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
</summary>

```diff
- boolean lambda$findNearbyHivesWithSpace$0(Holder)
+ boolean lambda$findNearbyHivesWithSpace$0(PoiType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.warden.Warden
</summary>

```diff
- boolean ignoreExplosion()
- int getActiveAnger()
- PathNavigation createNavigation(Level)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.warden.WardenSpawnTracker
</summary>

```diff
+ boolean canWarn(ServerLevel,BlockPos)
- boolean hasNearbyWarden(ServerLevel,BlockPos)
- boolean lambda$tryWarn$4(ServerPlayer)
- boolean onCooldown()
+ boolean warn(ServerLevel,BlockPos)
- int lambda$tryWarn$5(WardenSpawnTracker)
+ int lambda$warn$4(WardenSpawnTracker)
- OptionalInt tryWarn(ServerLevel,BlockPos,ServerPlayer)
- void copyData(WardenSpawnTracker)
+ void copyWarningLevelFrom(WardenSpawnTracker)
- void lambda$tryWarn$6(WardenSpawnTracker,ServerPlayer)
+ void lambda$warn$5(WardenSpawnTracker,ServerPlayer)
+ void lambda$warn$6(List,WardenSpawnTracker)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerProfession
</summary>

```diff
- boolean equals(Object)
- boolean lambda$register$1(ResourceKey,Holder)
- boolean lambda$register$2(ResourceKey,Holder)
- boolean lambda$static$0(Holder)
+ ImmutableSet getRequestedItems()
+ ImmutableSet getSecondaryPoi()
- ImmutableSet requestedItems()
- ImmutableSet secondaryPoi()
- int hashCode()
+ PoiType getJobPoiType()
- Predicate acquirableJobSite()
- Predicate heldJobSite()
+ SoundEvent getWorkSound()
- SoundEvent workSound()
+ String getName()
- String name()
+ VillagerProfession register(String,PoiType,ImmutableSet,ImmutableSet,SoundEvent)
+ VillagerProfession register(String,PoiType,SoundEvent)
- VillagerProfession register(String,Predicate,Predicate,ImmutableSet,ImmutableSet,SoundEvent)
- VillagerProfession register(String,Predicate,Predicate,SoundEvent)
- VillagerProfession register(String,ResourceKey,ImmutableSet,ImmutableSet,SoundEvent)
- VillagerProfession register(String,ResourceKey,SoundEvent)
+ void <init>(String,PoiType,ImmutableSet,ImmutableSet,SoundEvent)
- void <init>(String,Predicate,Predicate,ImmutableSet,ImmutableSet,SoundEvent)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.WanderingTraderSpawner
</summary>

```diff
+ boolean lambda$spawn$0(BlockPos)
- boolean lambda$spawn$0(Holder)
- boolean lambda$spawn$1(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.ProfilePublicKey$Data
</summary>

```diff
- byte[] keySignature()
- Property signedKeyProperty()
+ Property signedProperty()
- PublicKey key()
+ PublicKey parsedKey()
+ String key()
+ String signature()
- String signedKeyPropertyValue()
+ String signedPropertyValue()
- void <init>(FriendlyByteBuf)
- void <init>(Instant,PublicKey,byte[])
+ void <init>(Instant,String,String)
- void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
</summary>

```diff
- boolean lambda$hasSuitablePoi$0(Holder)
+ boolean lambda$hasSuitablePoi$0(PoiType)
```

</details>
<details>
<summary>
net.minecraft.world.item.InstrumentItem
</summary>

```diff
+ Instrument getInstrument(ItemStack)
- Optional getInstrument(ItemStack)
+ ResourceLocation getInstrumentLocation(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
- IllegalArgumentException lambda$new$0()
- ResourceKey dimensionTypeId()
+ String lambda$fillReportDetails$2()
- String lambda$fillReportDetails$4()
+ void lambda$getEntities$0(Entity,Predicate,List,Entity)
- void lambda$getEntities$1(Entity,Predicate,List,Entity)
+ void lambda$getEntities$1(Predicate,List,EntityTypeTest,Entity)
- void lambda$getEntities$2(Predicate,List,EntityTypeTest,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Rotation
</summary>

```diff
- String getSerializedName()
+ void <init>(String,int,OctahedralGroup)
- void <init>(String,int,String,OctahedralGroup)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
+ void lambda$stepOn$0(ServerLevel,Entity,SculkShriekerBlockEntity)
- void lambda$stepOn$0(ServerLevel,ServerPlayer,SculkShriekerBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
</summary>

```diff
- boolean canRespond(ServerLevel)
+ boolean canShriek(ServerLevel)
+ Boolean lambda$canShriek$3(ServerLevel,BlockPos,WardenSpawnTracker)
+ boolean lambda$tryToWarn$4(ServerLevel,BlockPos,WardenSpawnTracker)
- boolean trySummonWarden(ServerLevel)
+ boolean tryToWarn(ServerLevel,BlockState)
- boolean tryToWarn(ServerLevel,ServerPlayer)
+ Optional tryGetSpawnTracker(ServerLevel,BlockPos)
- ServerPlayer tryGetPlayer(Entity)
+ void lambda$trySummonWarden$5(Warden)
- void lambda$tryToWarn$3(int)
+ void replyOrSummon(ServerLevel)
- void tryRespond(ServerLevel)
- void tryShriek(ServerLevel,ServerPlayer)
+ void trySummonWarden(ServerLevel,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.RandomSupport
</summary>

```diff
- long generateUniqueSeed()
- long lambda$generateUniqueSeed$0(long)
+ long lambda$seedUniquifier$0(long)
+ long seedUniquifier()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
</summary>

```diff
+ Holder bootstrap()
- Holder bootstrap(Registry)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPresets
</summary>

```diff
+ Holder bootstrap()
- Holder bootstrap(Registry)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
</summary>

```diff
+ Consumer generator()
- Either generator()
- StructurePiecesBuilder getPiecesBuilder()
- StructurePiecesBuilder lambda$getPiecesBuilder$0(Consumer)
- StructurePiecesBuilder lambda$getPiecesBuilder$1(StructurePiecesBuilder)
- void <init>(BlockPos,Either)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
</summary>

```diff
+ boolean edgesLiquid(BlockGetter,BoundingBox)
- boolean isInInvalidLocation(LevelAccessor,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.portal.PortalForcer
</summary>

```diff
- boolean lambda$findPortalAround$0(Holder)
+ boolean lambda$findPortalAround$0(PoiType)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- XXX.animal.allay.Allay
+ XXX.animal.allay.AllayAi
- XXX.animal.allay.package-info
+ XXX.animal.axolotl.Axolotl
- XXX.animal.axolotl.Axolotl$AxolotlGroupData
+ XXX.animal.axolotl.Axolotl$AxolotlLookControl
- XXX.animal.axolotl.Axolotl$AxolotlMoveControl
+ XXX.animal.axolotl.Axolotl$Variant
- XXX.animal.axolotl.AxolotlAi
+ XXX.animal.axolotl.package-info
+ XXX.animal.axolotl.PlayDead
- XXX.animal.axolotl.ValidatePlayDead
- XXX.animal.frog.Frog
+ XXX.animal.frog.Frog$FrogLookControl
- XXX.animal.frog.Frog$FrogNodeEvaluator
+ XXX.animal.frog.Frog$FrogPathNavigation
- XXX.animal.frog.FrogAi
- XXX.animal.frog.package-info
+ XXX.animal.frog.ShootTongue
- XXX.animal.frog.ShootTongue$1
+ XXX.animal.frog.ShootTongue$State
- XXX.animal.frog.Tadpole
+ XXX.animal.frog.TadpoleAi
+ XXX.animal.goat.Goat
- XXX.animal.goat.GoatAi
+ XXX.animal.goat.package-info
- XXX.animal.horse.AbstractChestedHorse
+ XXX.animal.horse.AbstractChestedHorse$1
- XXX.animal.horse.AbstractHorse
+ XXX.animal.horse.AbstractHorse$1
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Markings
- XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.Variant
- XXX.animal.horse.ZombieHorse
- XXX.animation.definitions.FrogAnimation
- XXX.animation.definitions.package-info
+ XXX.animation.definitions.WardenAnimation
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BannerPatterns
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkShriekerBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.AzaleaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.MangroveTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
- XXX.block.model.BakedQuad
+ XXX.block.model.BlockElement
- XXX.block.model.BlockElement$1
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementRotation
+ XXX.block.model.BlockFaceUV
- XXX.block.model.BlockFaceUV$Deserializer
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModel$GuiLight
- XXX.block.model.BlockModel$LoopException
+ XXX.block.model.BlockModelDefinition
- XXX.block.model.BlockModelDefinition$Context
+ XXX.block.model.BlockModelDefinition$Deserializer
- XXX.block.model.BlockModelDefinition$MissingVariantException
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$1
+ XXX.block.model.ItemModelGenerator$Span
- XXX.block.model.ItemModelGenerator$SpanFacing
+ XXX.block.model.ItemOverride
- XXX.block.model.ItemOverride$Deserializer
+ XXX.block.model.ItemOverride$Predicate
- XXX.block.model.ItemOverrides
+ XXX.block.model.ItemOverrides$BakedOverride
- XXX.block.model.ItemOverrides$PropertyMatcher
+ XXX.block.model.ItemTransform
- XXX.block.model.ItemTransform$Deserializer
+ XXX.block.model.ItemTransforms
- XXX.block.model.ItemTransforms$1
+ XXX.block.model.ItemTransforms$Deserializer
- XXX.block.model.ItemTransforms$TransformType
+ XXX.block.model.MultiVariant
- XXX.block.model.MultiVariant$Deserializer
- XXX.block.model.package-info
+ XXX.block.model.Variant
- XXX.block.model.Variant$Deserializer
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.BlockBehaviour
+ XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase
+ XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$OffsetType
+ XXX.block.state.BlockBehaviour$Properties
- XXX.block.state.BlockBehaviour$StateArgumentPredicate
+ XXX.block.state.BlockBehaviour$StatePredicate
- XXX.block.state.BlockState
- XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
+ XXX.block.state.StateHolder$1
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
- XXX.chunk.storage.ChunkScanAccess
+ XXX.chunk.storage.ChunkSerializer
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.EntityStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$PendingStore
- XXX.chunk.storage.IOWorker$Priority
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.SectionStorage
+ XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolation
+ XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Target
+ XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition
+ XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.Keyframe
+ XXX.client.animation.KeyframeAnimations
+ XXX.client.animation.package-info
+ XXX.client.gui.Font
- XXX.client.gui.Font$DisplayMode
+ XXX.client.gui.Font$StringRenderOutput
- XXX.client.gui.Gui
+ XXX.client.gui.Gui$HeartType
- XXX.client.gui.GuiComponent
+ XXX.client.gui.MapRenderer
- XXX.client.gui.MapRenderer$MapInstance
+ XXX.client.gui.package-info
+ XXX.client.multiplayer.package-info
- XXX.client.multiplayer.ServerData$ChatPreview
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerList
+ XXX.client.multiplayer.ServerStatusPinger
- XXX.client.multiplayer.ServerStatusPinger$1
+ XXX.client.multiplayer.ServerStatusPinger$2
- XXX.client.multiplayer.ServerStatusPinger$2$1
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BlockMarker
- XXX.client.particle.BlockMarker$Provider
+ XXX.client.particle.BreakingItemParticle
- XXX.client.particle.BreakingItemParticle$Provider
+ XXX.client.particle.BreakingItemParticle$SlimeProvider
- XXX.client.particle.BreakingItemParticle$SnowballProvider
+ XXX.client.particle.BubbleColumnUpParticle
- XXX.client.particle.BubbleColumnUpParticle$Provider
+ XXX.client.particle.BubbleParticle
- XXX.client.particle.BubbleParticle$Provider
+ XXX.client.particle.BubblePopParticle
- XXX.client.particle.BubblePopParticle$Provider
+ XXX.client.particle.CampfireSmokeParticle
- XXX.client.particle.CampfireSmokeParticle$CosyProvider
+ XXX.client.particle.CampfireSmokeParticle$SignalProvider
- XXX.client.particle.CritParticle
+ XXX.client.particle.CritParticle$DamageIndicatorProvider
- XXX.client.particle.CritParticle$MagicProvider
+ XXX.client.particle.CritParticle$Provider
- XXX.client.particle.DragonBreathParticle
+ XXX.client.particle.DragonBreathParticle$Provider
- XXX.client.particle.DripParticle
+ XXX.client.particle.DripParticle$CoolingDripHangParticle
- XXX.client.particle.DripParticle$DripHangParticle
+ XXX.client.particle.DripParticle$DripLandParticle
- XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
+ XXX.client.particle.DripParticle$DripstoneLavaFallProvider
- XXX.client.particle.DripParticle$DripstoneLavaHangProvider
+ XXX.client.particle.DripParticle$DripstoneWaterFallProvider
- XXX.client.particle.DripParticle$DripstoneWaterHangProvider
+ XXX.client.particle.DripParticle$FallAndLandParticle
- XXX.client.particle.DripParticle$FallingParticle
+ XXX.client.particle.DripParticle$HoneyFallAndLandParticle
- XXX.client.particle.DripParticle$HoneyFallProvider
+ XXX.client.particle.DripParticle$HoneyHangProvider
- XXX.client.particle.DripParticle$HoneyLandProvider
+ XXX.client.particle.DripParticle$LavaFallProvider
- XXX.client.particle.DripParticle$LavaHangProvider
+ XXX.client.particle.DripParticle$LavaLandProvider
- XXX.client.particle.DripParticle$NectarFallProvider
+ XXX.client.particle.DripParticle$ObsidianTearFallProvider
- XXX.client.particle.DripParticle$ObsidianTearHangProvider
+ XXX.client.particle.DripParticle$ObsidianTearLandProvider
- XXX.client.particle.DripParticle$SporeBlossomFallProvider
+ XXX.client.particle.DripParticle$WaterFallProvider
- XXX.client.particle.DripParticle$WaterHangProvider
+ XXX.client.particle.DustColorTransitionParticle
- XXX.client.particle.DustColorTransitionParticle$Provider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$Provider
+ XXX.client.particle.DustParticleBase
- XXX.client.particle.EnchantmentTableParticle
+ XXX.client.particle.EnchantmentTableParticle$NautilusProvider
- XXX.client.particle.EnchantmentTableParticle$Provider
+ XXX.client.particle.EndRodParticle
- XXX.client.particle.EndRodParticle$Provider
+ XXX.client.particle.ExplodeParticle
- XXX.client.particle.ExplodeParticle$Provider
+ XXX.client.particle.FallingDustParticle
- XXX.client.particle.FallingDustParticle$Provider
+ XXX.client.particle.FireworkParticles
- XXX.client.particle.FireworkParticles$1
+ XXX.client.particle.FireworkParticles$FlashProvider
- XXX.client.particle.FireworkParticles$OverlayParticle
+ XXX.client.particle.FireworkParticles$SparkParticle
- XXX.client.particle.FireworkParticles$SparkProvider
+ XXX.client.particle.FireworkParticles$Starter
- XXX.client.particle.FlameParticle
+ XXX.client.particle.FlameParticle$Provider
- XXX.client.particle.FlameParticle$SmallFlameProvider
+ XXX.client.particle.GlowParticle
- XXX.client.particle.GlowParticle$ElectricSparkProvider
+ XXX.client.particle.GlowParticle$GlowSquidProvider
- XXX.client.particle.GlowParticle$ScrapeProvider
+ XXX.client.particle.GlowParticle$WaxOffProvider
- XXX.client.particle.GlowParticle$WaxOnProvider
+ XXX.client.particle.HeartParticle
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$Provider
- XXX.client.particle.HugeExplosionSeedParticle
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$Provider
+ XXX.client.particle.MobAppearanceParticle
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$Provider
+ XXX.client.particle.package-info
- XXX.client.particle.Particle
+ XXX.client.particle.ParticleDescription
- XXX.client.particle.ParticleEngine
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleEngine$SpriteParticleRegistration
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.ParticleRenderType$1
- XXX.client.particle.ParticleRenderType$2
+ XXX.client.particle.ParticleRenderType$3
- XXX.client.particle.ParticleRenderType$4
+ XXX.client.particle.ParticleRenderType$5
- XXX.client.particle.ParticleRenderType$6
+ XXX.client.particle.PlayerCloudParticle
- XXX.client.particle.PlayerCloudParticle$Provider
+ XXX.client.particle.PlayerCloudParticle$SneezeProvider
- XXX.client.particle.PortalParticle
+ XXX.client.particle.PortalParticle$Provider
- XXX.client.particle.ReversePortalParticle
+ XXX.client.particle.ReversePortalParticle$ReversePortalProvider
- XXX.client.particle.RisingParticle
+ XXX.client.particle.SculkChargeParticle
- XXX.client.particle.SculkChargeParticle$Provider
+ XXX.client.particle.SculkChargePopParticle
- XXX.client.particle.SculkChargePopParticle$Provider
+ XXX.client.particle.ShriekParticle
- XXX.client.particle.ShriekParticle$Provider
+ XXX.client.particle.SimpleAnimatedParticle
- XXX.client.particle.SingleQuadParticle
+ XXX.client.particle.SmokeParticle
- XXX.client.particle.SmokeParticle$Provider
+ XXX.client.particle.SnowflakeParticle
- XXX.client.particle.SnowflakeParticle$Provider
+ XXX.client.particle.SonicBoomParticle
- XXX.client.particle.SonicBoomParticle$Provider
+ XXX.client.particle.SoulParticle
- XXX.client.particle.SoulParticle$EmissiveProvider
+ XXX.client.particle.SoulParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$AmbientMobProvider
- XXX.client.particle.SpellParticle$InstantProvider
+ XXX.client.particle.SpellParticle$MobProvider
- XXX.client.particle.SpellParticle$Provider
+ XXX.client.particle.SpellParticle$WitchProvider
- XXX.client.particle.SpitParticle
+ XXX.client.particle.SpitParticle$Provider
- XXX.client.particle.SplashParticle
+ XXX.client.particle.SplashParticle$Provider
- XXX.client.particle.SpriteSet
+ XXX.client.particle.SquidInkParticle
- XXX.client.particle.SquidInkParticle$GlowInkProvider
+ XXX.client.particle.SquidInkParticle$Provider
- XXX.client.particle.SuspendedParticle
+ XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
- XXX.client.particle.SuspendedParticle$UnderwaterProvider
+ XXX.client.particle.SuspendedParticle$WarpedSporeProvider
- XXX.client.particle.SuspendedTownParticle
+ XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
- XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
- XXX.client.particle.SuspendedTownParticle$Provider
+ XXX.client.particle.TerrainParticle
- XXX.client.particle.TerrainParticle$Provider
+ XXX.client.particle.TextureSheetParticle
- XXX.client.particle.TotemParticle
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
+ XXX.client.particle.VibrationSignalParticle
- XXX.client.particle.VibrationSignalParticle$Provider
+ XXX.client.particle.WakeParticle
- XXX.client.particle.WakeParticle$Provider
+ XXX.client.particle.WaterCurrentDownParticle
- XXX.client.particle.WaterCurrentDownParticle$Provider
+ XXX.client.particle.WaterDropParticle
- XXX.client.particle.WaterDropParticle$Provider
+ XXX.client.particle.WhiteAshParticle
- XXX.client.particle.WhiteAshParticle$Provider
- XXX.client.player.AbstractClientPlayer
+ XXX.client.player.Input
- XXX.client.player.KeyboardInput
+ XXX.client.player.LocalPlayer
+ XXX.client.player.package-info
- XXX.client.player.RemotePlayer
- XXX.client.profiling.ClientMetricsSamplersProvider
+ XXX.client.profiling.package-info
- XXX.client.renderer.BiomeColors
+ XXX.client.renderer.BlockEntityWithoutLevelRenderer
- XXX.client.renderer.ChunkBufferBuilderPack
+ XXX.client.renderer.CubeMap
- XXX.client.renderer.DimensionSpecialEffects
+ XXX.client.renderer.DimensionSpecialEffects$EndEffects
- XXX.client.renderer.DimensionSpecialEffects$NetherEffects
+ XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
- XXX.client.renderer.DimensionSpecialEffects$SkyType
+ XXX.client.renderer.EffectInstance
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.FogRenderer
- XXX.client.renderer.FogRenderer$BlindnessFogFunction
+ XXX.client.renderer.FogRenderer$DarknessFogFunction
- XXX.client.renderer.FogRenderer$FogData
+ XXX.client.renderer.FogRenderer$FogMode
- XXX.client.renderer.FogRenderer$MobEffectFogFunction
+ XXX.client.renderer.GameRenderer
- XXX.client.renderer.GpuWarnlistManager
+ XXX.client.renderer.GpuWarnlistManager$Preparations
- XXX.client.renderer.ItemBlockRenderTypes
+ XXX.client.renderer.ItemInHandRenderer
- XXX.client.renderer.ItemInHandRenderer$1
+ XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
- XXX.client.renderer.ItemModelShaper
+ XXX.client.renderer.LevelRenderer
- XXX.client.renderer.LevelRenderer$RenderChunkInfo
+ XXX.client.renderer.LevelRenderer$RenderChunkStorage
- XXX.client.renderer.LevelRenderer$RenderInfoMap
+ XXX.client.renderer.LevelRenderer$TransparencyShaderException
- XXX.client.renderer.LightTexture
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.OutlineBufferSource
- XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ XXX.client.renderer.package-info
+ XXX.client.renderer.PanoramaRenderer
- XXX.client.renderer.PostChain
+ XXX.client.renderer.PostPass
- XXX.client.renderer.Rect2i
+ XXX.client.renderer.RenderBuffers
- XXX.client.renderer.RenderStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
- XXX.client.renderer.RenderStateShard$CullStateShard
+ XXX.client.renderer.RenderStateShard$DepthTestStateShard
- XXX.client.renderer.RenderStateShard$EmptyTextureStateShard
+ XXX.client.renderer.RenderStateShard$LayeringStateShard
- XXX.client.renderer.RenderStateShard$LightmapStateShard
+ XXX.client.renderer.RenderStateShard$LineStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
- XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ XXX.client.renderer.RenderStateShard$OutputStateShard
- XXX.client.renderer.RenderStateShard$OverlayStateShard
+ XXX.client.renderer.RenderStateShard$ShaderStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
+ XXX.client.renderer.RenderStateShard$WriteMaskStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$CompositeRenderType
- XXX.client.renderer.RenderType$CompositeState
+ XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- XXX.client.renderer.RenderType$OutlineProperty
+ XXX.client.renderer.RunningTrimmedMean
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.ShaderInstance
- XXX.client.renderer.ShaderInstance$1
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
+ XXX.client.resources.AssetIndex
- XXX.client.resources.ClientPackSource
+ XXX.client.resources.ClientPackSource$1
- XXX.client.resources.ClientPackSource$2
+ XXX.client.resources.DefaultClientPackResources
- XXX.client.resources.DefaultPlayerSkin
+ XXX.client.resources.DirectAssetIndex
- XXX.client.resources.FoliageColorReloadListener
+ XXX.client.resources.GrassColorReloadListener
- XXX.client.resources.LegacyPackResourcesAdapter
+ XXX.client.resources.LegacyStuffWrapper
- XXX.client.resources.MobEffectTextureManager
- XXX.client.resources.package-info
+ XXX.client.resources.PackResourcesAdapterV4
- XXX.client.resources.PaintingTextureManager
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$SkinTextureCallback
- XXX.client.resources.SplashManager
+ XXX.client.resources.TextureAtlasHolder
- XXX.client.searchtree.FullTextSearchTree
+ XXX.client.searchtree.IdSearchTree
- XXX.client.searchtree.IntersectionIterator
+ XXX.client.searchtree.MergingUniqueIterator
+ XXX.client.searchtree.package-info
- XXX.client.searchtree.PlainTextSearchTree
+ XXX.client.searchtree.RefreshableSearchTree
- XXX.client.searchtree.ResourceLocationSearchTree
+ XXX.client.searchtree.ResourceLocationSearchTree$1
- XXX.client.searchtree.ResourceLocationSearchTree$2
+ XXX.client.searchtree.SearchRegistry
- XXX.client.searchtree.SearchRegistry$Key
+ XXX.client.searchtree.SearchRegistry$TreeBuilderSupplier
- XXX.client.searchtree.SearchRegistry$TreeEntry
+ XXX.client.searchtree.SearchTree
- XXX.client.searchtree.SuffixArray
- XXX.client.server.IntegratedPlayerList
+ XXX.client.server.IntegratedServer
- XXX.client.server.LanServer
+ XXX.client.server.LanServerDetection
- XXX.client.server.LanServerDetection$LanServerDetector
+ XXX.client.server.LanServerDetection$LanServerList
- XXX.client.server.LanServerPinger
+ XXX.client.server.package-info
- XXX.client.sounds.AudioStream
+ XXX.client.sounds.ChannelAccess
- XXX.client.sounds.ChannelAccess$ChannelHandle
+ XXX.client.sounds.LoopingAudioStream
- XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
+ XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
- XXX.client.sounds.MusicManager
+ XXX.client.sounds.package-info
+ XXX.client.sounds.SoundBufferLibrary
- XXX.client.sounds.SoundEngine
+ XXX.client.sounds.SoundEngine$DeviceCheckState
- XXX.client.sounds.SoundEngineExecutor
+ XXX.client.sounds.SoundEventListener
- XXX.client.sounds.SoundManager
+ XXX.client.sounds.SoundManager$1
- XXX.client.sounds.SoundManager$2
+ XXX.client.sounds.SoundManager$Preparations
- XXX.client.sounds.SoundManager$Preparations$1
+ XXX.client.sounds.WeighedSoundEvents
- XXX.client.sounds.Weighted
- XXX.client.tutorial.BundleTutorial
+ XXX.client.tutorial.CompletedTutorialStepInstance
- XXX.client.tutorial.CraftPlanksTutorialStep
+ XXX.client.tutorial.FindTreeTutorialStepInstance
- XXX.client.tutorial.MovementTutorialStepInstance
+ XXX.client.tutorial.OpenInventoryTutorialStep
+ XXX.client.tutorial.package-info
- XXX.client.tutorial.PunchTreeTutorialStepInstance
+ XXX.client.tutorial.Tutorial
- XXX.client.tutorial.Tutorial$TimedToast
+ XXX.client.tutorial.TutorialStepInstance
- XXX.client.tutorial.TutorialSteps
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
+ XXX.color.block.BlockTintCache$CacheData
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.color.block.package-info
- XXX.color.item.ItemColor
+ XXX.color.item.ItemColors
- XXX.color.item.package-info
- XXX.commands.arguments.AngleArgument
+ XXX.commands.arguments.AngleArgument$SingleAngle
- XXX.commands.arguments.ArgumentSignatures
+ XXX.commands.arguments.ColorArgument
- XXX.commands.arguments.ComponentArgument
+ XXX.commands.arguments.CompoundTagArgument
- XXX.commands.arguments.DimensionArgument
+ XXX.commands.arguments.EntityAnchorArgument
- XXX.commands.arguments.EntityAnchorArgument$Anchor
+ XXX.commands.arguments.EntityArgument
- XXX.commands.arguments.EntityArgument$Info
+ XXX.commands.arguments.EntityArgument$Info$Template
- XXX.commands.arguments.EntitySummonArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.ItemEnchantmentArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.MobEffectArgument
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchElementNode
- XXX.commands.arguments.NbtPathArgument$MatchObjectNode
+ XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
- XXX.commands.arguments.NbtPathArgument$NbtPath
+ XXX.commands.arguments.NbtPathArgument$Node
- XXX.commands.arguments.NbtTagArgument
+ XXX.commands.arguments.ObjectiveArgument
- XXX.commands.arguments.ObjectiveCriteriaArgument
+ XXX.commands.arguments.OperationArgument
- XXX.commands.arguments.OperationArgument$Operation
+ XXX.commands.arguments.OperationArgument$SimpleOperation
- XXX.commands.arguments.ParticleArgument
+ XXX.commands.arguments.RangeArgument
- XXX.commands.arguments.RangeArgument$Floats
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceKeyArgument
+ XXX.commands.arguments.ResourceKeyArgument$Info
- XXX.commands.arguments.ResourceKeyArgument$Info$Template
+ XXX.commands.arguments.ResourceLocationArgument
- XXX.commands.arguments.ResourceOrTagLocationArgument
+ XXX.commands.arguments.ResourceOrTagLocationArgument$Info
- XXX.commands.arguments.ResourceOrTagLocationArgument$Info$Template
+ XXX.commands.arguments.ResourceOrTagLocationArgument$ResourceResult
- XXX.commands.arguments.ResourceOrTagLocationArgument$Result
+ XXX.commands.arguments.ResourceOrTagLocationArgument$TagResult
+ XXX.commands.arguments.ScoreboardSlotArgument
- XXX.commands.arguments.ScoreHolderArgument
+ XXX.commands.arguments.ScoreHolderArgument$Info
- XXX.commands.arguments.ScoreHolderArgument$Info$Template
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.SignedArgument
+ XXX.commands.arguments.SlotArgument
- XXX.commands.arguments.StringRepresentableArgument
- XXX.commands.arguments.TemplateMirrorArgument
+ XXX.components.events.AbstractContainerEventHandler
- XXX.components.events.ContainerEventHandler
+ XXX.components.events.GuiEventListener
- XXX.components.events.package-info
+ XXX.components.spectator.package-info
- XXX.components.spectator.SpectatorGui
- XXX.components.toasts.AdvancementToast
- XXX.components.toasts.package-info
+ XXX.components.toasts.RecipeToast
- XXX.components.toasts.SystemToast
+ XXX.components.toasts.SystemToast$SystemToastIds
- XXX.components.toasts.Toast
+ XXX.components.toasts.Toast$Visibility
- XXX.components.toasts.ToastComponent
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdventureAdvancements
- XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.NetherAdvancements
- XXX.data.advancements.package-info
- XXX.data.advancements.StoryAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.info.BiomeParametersDumpReport
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
- XXX.data.info.package-info
- XXX.data.info.RegistryDumpReport
+ XXX.data.info.WorldgenRegistryDumpReport
+ XXX.data.loot.BlockLoot
- XXX.data.loot.ChestLoot
+ XXX.data.loot.EntityLoot
- XXX.data.loot.FishingLoot
+ XXX.data.loot.GiftLoot
- XXX.data.loot.LootTableProvider
- XXX.data.loot.package-info
+ XXX.data.loot.PiglinBarterLoot
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ModelProvider
- XXX.data.models.package-info
- XXX.data.recipes.FinishedRecipe
+ XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeBuilder
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapedRecipeBuilder$Result
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder$Result
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder$Result
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder$Result
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder$1
+ XXX.data.recipes.UpgradeRecipeBuilder
- XXX.data.recipes.UpgradeRecipeBuilder$Result
- XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$StructureConversionException
- XXX.data.structures.SnbtToNbt$TaskResult
+ XXX.data.structures.StructureUpdater
+ XXX.data.tags.BannerPatternTagsProvider
- XXX.data.tags.BiomeTagsProvider
+ XXX.data.tags.BlockTagsProvider
- XXX.data.tags.CatVariantTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.GameEventTagsProvider
+ XXX.data.tags.InstrumentTagsProvider
- XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.PaintingVariantTagsProvider
- XXX.data.tags.PoiTypeTagsProvider
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
+ XXX.enderdragon.phases.AbstractDragonPhaseInstance
- XXX.enderdragon.phases.AbstractDragonSittingPhase
+ XXX.enderdragon.phases.DragonChargePlayerPhase
- XXX.enderdragon.phases.DragonDeathPhase
+ XXX.enderdragon.phases.DragonHoldingPatternPhase
- XXX.enderdragon.phases.DragonHoverPhase
+ XXX.enderdragon.phases.DragonLandingApproachPhase
- XXX.enderdragon.phases.DragonLandingPhase
+ XXX.enderdragon.phases.DragonPhaseInstance
- XXX.enderdragon.phases.DragonSittingAttackingPhase
+ XXX.enderdragon.phases.DragonSittingFlamingPhase
- XXX.enderdragon.phases.DragonSittingScanningPhase
+ XXX.enderdragon.phases.DragonStrafePlayerPhase
- XXX.enderdragon.phases.DragonTakeoffPhase
+ XXX.enderdragon.phases.EnderDragonPhase
- XXX.enderdragon.phases.EnderDragonPhaseManager
+ XXX.enderdragon.phases.package-info
+ XXX.entity.ambient.AmbientCreature
- XXX.entity.ambient.Bat
+ XXX.entity.ambient.package-info
- XXX.entity.animal.AbstractFish
+ XXX.entity.animal.AbstractFish$FishMoveControl
- XXX.entity.animal.AbstractFish$FishSwimGoal
+ XXX.entity.animal.AbstractGolem
- XXX.entity.animal.AbstractSchoolingFish
+ XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- XXX.entity.animal.Animal
+ XXX.entity.animal.Bee
- XXX.entity.animal.Bee$1
+ XXX.entity.animal.Bee$BaseBeeGoal
- XXX.entity.animal.Bee$BeeAttackGoal
+ XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
- XXX.entity.animal.Bee$BeeEnterHiveGoal
+ XXX.entity.animal.Bee$BeeGoToHiveGoal
- XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ XXX.entity.animal.Bee$BeeGrowCropGoal
- XXX.entity.animal.Bee$BeeHurtByOtherGoal
+ XXX.entity.animal.Bee$BeeLocateHiveGoal
- XXX.entity.animal.Bee$BeeLookControl
+ XXX.entity.animal.Bee$BeePollinateGoal
- XXX.entity.animal.Bee$BeeWanderGoal
+ XXX.entity.animal.Bucketable
- XXX.entity.animal.Cat
+ XXX.entity.animal.Cat$CatAvoidEntityGoal
- XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
+ XXX.entity.animal.Cat$CatTemptGoal
- XXX.entity.animal.CatVariant
+ XXX.entity.animal.Chicken
- XXX.entity.animal.Cod
+ XXX.entity.animal.Cow
- XXX.entity.animal.Dolphin
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.Fox$DefendTrustedTargetGoal
+ XXX.entity.animal.Fox$FaceplantGoal
- XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
+ XXX.entity.animal.Fox$FoxBehaviorGoal
- XXX.entity.animal.Fox$FoxBreedGoal
+ XXX.entity.animal.Fox$FoxEatBerriesGoal
- XXX.entity.animal.Fox$FoxFloatGoal
+ XXX.entity.animal.Fox$FoxFollowParentGoal
- XXX.entity.animal.Fox$FoxGroupData
+ XXX.entity.animal.Fox$FoxLookAtPlayerGoal
- XXX.entity.animal.Fox$FoxLookControl
+ XXX.entity.animal.Fox$FoxMeleeAttackGoal
- XXX.entity.animal.Fox$FoxMoveControl
+ XXX.entity.animal.Fox$FoxPanicGoal
- XXX.entity.animal.Fox$FoxPounceGoal
+ XXX.entity.animal.Fox$FoxSearchForItemsGoal
- XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
+ XXX.entity.animal.Fox$PerchAndSearchGoal
- XXX.entity.animal.Fox$SeekShelterGoal
+ XXX.entity.animal.Fox$SleepGoal
- XXX.entity.animal.Fox$StalkPreyGoal
+ XXX.entity.animal.Fox$Type
- XXX.entity.animal.FrogVariant
+ XXX.entity.animal.IronGolem
- XXX.entity.animal.IronGolem$Crackiness
+ XXX.entity.animal.MushroomCow
- XXX.entity.animal.MushroomCow$MushroomType
+ XXX.entity.animal.Ocelot
- XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ XXX.entity.animal.Ocelot$OcelotTemptGoal
- XXX.entity.animal.package-info
- XXX.entity.animal.Panda
+ XXX.entity.animal.Panda$Gene
- XXX.entity.animal.Panda$PandaAttackGoal
+ XXX.entity.animal.Panda$PandaAvoidGoal
- XXX.entity.animal.Panda$PandaBreedGoal
+ XXX.entity.animal.Panda$PandaHurtByTargetGoal
- XXX.entity.animal.Panda$PandaLieOnBackGoal
+ XXX.entity.animal.Panda$PandaLookAtPlayerGoal
- XXX.entity.animal.Panda$PandaMoveControl
+ XXX.entity.animal.Panda$PandaPanicGoal
- XXX.entity.animal.Panda$PandaRollGoal
+ XXX.entity.animal.Panda$PandaSitGoal
- XXX.entity.animal.Panda$PandaSneezeGoal
+ XXX.entity.animal.Parrot
- XXX.entity.animal.Parrot$1
+ XXX.entity.animal.Parrot$ParrotWanderGoal
- XXX.entity.animal.Pig
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.animal.PolarBear$PolarBearPanicGoal
- XXX.entity.animal.Pufferfish
+ XXX.entity.animal.Pufferfish$PufferfishPuffGoal
- XXX.entity.animal.Rabbit
+ XXX.entity.animal.Rabbit$EvilRabbitAttackGoal
- XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ XXX.entity.animal.Rabbit$RabbitGroupData
- XXX.entity.animal.Rabbit$RabbitJumpControl
+ XXX.entity.animal.Rabbit$RabbitMoveControl
- XXX.entity.animal.Rabbit$RabbitPanicGoal
+ XXX.entity.animal.Rabbit$RaidGardenGoal
- XXX.entity.animal.Salmon
+ XXX.entity.animal.Sheep
- XXX.entity.animal.Sheep$1
+ XXX.entity.animal.Sheep$2
- XXX.entity.animal.ShoulderRidingEntity
+ XXX.entity.animal.SnowGolem
- XXX.entity.animal.Squid
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
+ XXX.entity.animal.TropicalFish
- XXX.entity.animal.TropicalFish$Pattern
+ XXX.entity.animal.TropicalFish$TropicalFishGroupData
- XXX.entity.animal.Turtle
+ XXX.entity.animal.Turtle$TurtleBreedGoal
- XXX.entity.animal.Turtle$TurtleGoHomeGoal
+ XXX.entity.animal.Turtle$TurtleGoToWaterGoal
- XXX.entity.animal.Turtle$TurtleLayEggGoal
+ XXX.entity.animal.Turtle$TurtleMoveControl
- XXX.entity.animal.Turtle$TurtlePanicGoal
+ XXX.entity.animal.Turtle$TurtlePathNavigation
- XXX.entity.animal.Turtle$TurtleRandomStrollGoal
+ XXX.entity.animal.Turtle$TurtleTravelGoal
- XXX.entity.animal.WaterAnimal
+ XXX.entity.animal.Wolf
- XXX.entity.animal.Wolf$WolfAvoidEntityGoal
+ XXX.entity.animal.Wolf$WolfPanicGoal
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$1
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.ItemFrame$1
+ XXX.entity.decoration.ItemFrame$2
- XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
- XXX.entity.decoration.PaintingVariant
+ XXX.entity.decoration.PaintingVariants
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseArmorLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
+ XXX.entity.layers.package-info
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.layers.PlayerItemInHandLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.SaddleLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StrayClothingLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WardenEmissiveLayer
- XXX.entity.layers.WardenEmissiveLayer$AlphaFunction
+ XXX.entity.layers.WardenEmissiveLayer$DrawSelector
- XXX.entity.layers.WitchItemLayer
+ XXX.entity.layers.WitherArmorLayer
- XXX.entity.layers.WolfCollarLayer
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$EvokerAttackSpellGoal
- XXX.entity.monster.Evoker$EvokerCastingSpellGoal
+ XXX.entity.monster.Evoker$EvokerSummonSpellGoal
- XXX.entity.monster.Evoker$EvokerWololoSpellGoal
+ XXX.entity.monster.Ghast
- XXX.entity.monster.Ghast$GhastLookGoal
+ XXX.entity.monster.Ghast$GhastMoveControl
- XXX.entity.monster.Ghast$GhastShootFireballGoal
+ XXX.entity.monster.Ghast$RandomFloatAroundGoal
- XXX.entity.monster.Giant
+ XXX.entity.monster.Guardian
- XXX.entity.monster.Guardian$GuardianAttackGoal
+ XXX.entity.monster.Guardian$GuardianAttackSelector
- XXX.entity.monster.Guardian$GuardianMoveControl
+ XXX.entity.monster.Husk
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
+ XXX.entity.monster.package-info
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$AttackPhase
+ XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
+ XXX.entity.monster.Phantom$PhantomBodyRotationControl
- XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ XXX.entity.monster.Phantom$PhantomLookControl
- XXX.entity.monster.Phantom$PhantomMoveControl
+ XXX.entity.monster.Phantom$PhantomMoveTargetGoal
- XXX.entity.monster.Phantom$PhantomSweepAttackGoal
+ XXX.entity.monster.Pillager
- XXX.entity.monster.RangedAttackMob
+ XXX.entity.monster.Ravager
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.Ravager$RavagerNavigation
- XXX.entity.monster.Ravager$RavagerNodeEvaluator
+ XXX.entity.monster.Shulker
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ XXX.entity.monster.Shulker$ShulkerLookControl
- XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
+ XXX.entity.monster.Shulker$ShulkerPeekGoal
- XXX.entity.monster.Silverfish
+ XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ XXX.entity.monster.Skeleton
- XXX.entity.monster.Slime
+ XXX.entity.monster.Slime$SlimeAttackGoal
- XXX.entity.monster.Slime$SlimeFloatGoal
+ XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
- XXX.entity.monster.Slime$SlimeMoveControl
+ XXX.entity.monster.Slime$SlimeRandomDirectionGoal
- XXX.entity.monster.SpellcasterIllager
+ XXX.entity.monster.SpellcasterIllager$IllagerSpell
- XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- XXX.entity.monster.Spider
+ XXX.entity.monster.Spider$SpiderAttackGoal
- XXX.entity.monster.Spider$SpiderEffectsGroupData
+ XXX.entity.monster.Spider$SpiderTargetGoal
- XXX.entity.monster.Stray
+ XXX.entity.monster.Strider
- XXX.entity.monster.Strider$StriderGoToLavaGoal
+ XXX.entity.monster.Strider$StriderPathNavigation
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zoglin
- XXX.entity.monster.Zombie
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
- XXX.entity.monster.ZombifiedPiglin
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
- XXX.entity.player.package-info
- XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.PlayerRenderer
+ XXX.entity.player.ProfileKeyPair
- XXX.entity.player.ProfilePublicKey
+ XXX.entity.player.ProfilePublicKey$Data
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$1
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$1
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
- XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
+ XXX.entity.raid.Raid
- XXX.entity.raid.Raid$1
- XXX.entity.raid.Raid$RaiderType
+ XXX.entity.raid.Raid$RaidStatus
+ XXX.entity.raid.Raider
- XXX.entity.raid.Raider$HoldGroundAttackGoal
+ XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- XXX.entity.raid.Raider$RaiderCelebration
+ XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
- XXX.entity.raid.Raids
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecart$1
+ XXX.entity.vehicle.AbstractMinecart$Type
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.Boat$1
+ XXX.entity.vehicle.Boat$Status
- XXX.entity.vehicle.Boat$Type
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestBoat$1
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
- XXX.feature.configurations.BlockColumnConfiguration
+ XXX.feature.configurations.BlockColumnConfiguration$Layer
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.CountConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.DripstoneClusterConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.GeodeConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.LargeDripstoneConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MultifaceGrowthConfiguration
- XXX.feature.configurations.NetherForestVegetationConfig
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.package-info
- XXX.feature.configurations.PointedDripstoneConfiguration
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.RootSystemConfiguration
- XXX.feature.configurations.SculkPatchConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.TwistingVinesConfig
- XXX.feature.configurations.UnderwaterMagmaConfiguration
+ XXX.feature.configurations.VegetationPatchConfiguration
+ XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.FeatureSizeType
+ XXX.feature.featuresize.package-info
+ XXX.feature.featuresize.ThreeLayersFeatureSize
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
+ XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.rootplacers.AboveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacer
- XXX.feature.rootplacers.RootPlacer
+ XXX.feature.rootplacers.RootPlacerType
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.AttachedToLeavesDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecorator$Context
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$1
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
+ XXX.font.glyphs.package-info
- XXX.font.glyphs.SpecialGlyphs
+ XXX.font.glyphs.SpecialGlyphs$1
- XXX.font.glyphs.SpecialGlyphs$PixelProvider
+ XXX.font.providers.BitmapProvider
- XXX.font.providers.BitmapProvider$Builder
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.BitmapProvider$Glyph$1
+ XXX.font.providers.GlyphProviderBuilder
- XXX.font.providers.GlyphProviderBuilderType
+ XXX.font.providers.LegacyUnicodeBitmapsProvider
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph$1
- XXX.font.providers.package-info
+ XXX.font.providers.TrueTypeGlyphProviderBuilder
+ XXX.gameevent.vibrations.package-info
- XXX.gameevent.vibrations.VibrationListener
+ XXX.gameevent.vibrations.VibrationListener$ReceivingEvent
- XXX.gameevent.vibrations.VibrationListener$VibrationListenerConfig
+ XXX.gui.chat.ChatListener
- XXX.gui.chat.ClientChatPreview
- XXX.gui.chat.ClientChatPreview$Preview
- XXX.gui.chat.NarratorChatListener
+ XXX.gui.chat.OverlayChatListener
+ XXX.gui.chat.package-info
- XXX.gui.chat.StandardChatListener
- XXX.gui.components.AbstractButton
+ XXX.gui.components.AbstractOptionSliderButton
- XXX.gui.components.AbstractSelectionList
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$SelectionDirection
+ XXX.gui.components.AbstractSelectionList$TrackedList
- XXX.gui.components.AbstractSliderButton
+ XXX.gui.components.AbstractWidget
- XXX.gui.components.BossHealthOverlay
+ XXX.gui.components.BossHealthOverlay$1
- XXX.gui.components.Button
+ XXX.gui.components.Button$OnPress
- XXX.gui.components.Button$OnTooltip
+ XXX.gui.components.ChatComponent
- XXX.gui.components.Checkbox
+ XXX.gui.components.CommandSuggestions
- XXX.gui.components.CommandSuggestions$SuggestionsList
+ XXX.gui.components.ComponentRenderUtils
- XXX.gui.components.ContainerObjectSelectionList
+ XXX.gui.components.ContainerObjectSelectionList$Entry
- XXX.gui.components.CycleButton
+ XXX.gui.components.CycleButton$Builder
- XXX.gui.components.CycleButton$OnValueChange
+ XXX.gui.components.CycleButton$ValueListSupplier
- XXX.gui.components.CycleButton$ValueListSupplier$1
+ XXX.gui.components.CycleButton$ValueListSupplier$2
- XXX.gui.components.DebugScreenOverlay
+ XXX.gui.components.DebugScreenOverlay$1
- XXX.gui.components.DebugScreenOverlay$AllocationRateCalculator
+ XXX.gui.components.EditBox
- XXX.gui.components.ImageButton
+ XXX.gui.components.LerpingBossEvent
- XXX.gui.components.LockIconButton
+ XXX.gui.components.LockIconButton$Icon
- XXX.gui.components.MultiLineLabel
+ XXX.gui.components.MultiLineLabel$1
- XXX.gui.components.MultiLineLabel$2
+ XXX.gui.components.MultiLineLabel$TextWithWidth
- XXX.gui.components.ObjectSelectionList
+ XXX.gui.components.ObjectSelectionList$Entry
- XXX.gui.components.OptionsList
+ XXX.gui.components.OptionsList$Entry
+ XXX.gui.components.package-info
- XXX.gui.components.PlainTextButton
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TooltipAccessor
+ XXX.gui.components.VolumeSlider
- XXX.gui.components.Widget
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$1
- XXX.gui.font.FontSet
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$Node
- XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$1
+ XXX.gui.font.TextFieldHelper$CursorStep
+ XXX.gui.narration.NarratableEntry
- XXX.gui.narration.NarratableEntry$NarrationPriority
+ XXX.gui.narration.NarratedElementType
- XXX.gui.narration.NarrationElementOutput
+ XXX.gui.narration.NarrationSupplier
- XXX.gui.narration.NarrationThunk
- XXX.gui.narration.package-info
+ XXX.gui.narration.ScreenNarrationCollector
- XXX.gui.narration.ScreenNarrationCollector$1
+ XXX.gui.narration.ScreenNarrationCollector$EntryKey
- XXX.gui.narration.ScreenNarrationCollector$NarrationEntry
+ XXX.gui.narration.ScreenNarrationCollector$Output
- XXX.gui.screens.AccessibilityOptionsScreen
+ XXX.gui.screens.AlertScreen
- XXX.gui.screens.BackupConfirmScreen
+ XXX.gui.screens.BackupConfirmScreen$Listener
- XXX.gui.screens.ChatOptionsScreen
+ XXX.gui.screens.ChatScreen
- XXX.gui.screens.ChatScreen$1
+ XXX.gui.screens.ConfirmLinkScreen
- XXX.gui.screens.ConfirmScreen
+ XXX.gui.screens.ConnectScreen
- XXX.gui.screens.ConnectScreen$1
+ XXX.gui.screens.CreateBuffetWorldScreen
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ XXX.gui.screens.DatapackLoadFailureScreen
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DemoIntroScreen
- XXX.gui.screens.DirectJoinServerScreen
+ XXX.gui.screens.DisconnectedScreen
- XXX.gui.screens.EditServerScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.GenericDirtMessageScreen
+ XXX.gui.screens.InBedChatScreen
- XXX.gui.screens.LanguageSelectScreen
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
+ XXX.gui.screens.LevelLoadingScreen
- XXX.gui.screens.LoadingDotsText
+ XXX.gui.screens.LoadingOverlay
- XXX.gui.screens.LoadingOverlay$LogoTexture
+ XXX.gui.screens.MenuScreens
- XXX.gui.screens.MenuScreens$ScreenConstructor
+ XXX.gui.screens.MouseSettingsScreen
- XXX.gui.screens.OnlineOptionsScreen
+ XXX.gui.screens.OptionsScreen
- XXX.gui.screens.OptionsSubScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PopupScreen
+ XXX.gui.screens.PopupScreen$ButtonOption
- XXX.gui.screens.PresetFlatWorldScreen
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.Screen
- XXX.gui.screens.Screen$NarratableSearchResult
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.SimpleOptionsSubScreen
+ XXX.gui.screens.SkinCustomizationScreen
- XXX.gui.screens.SoundOptionsScreen
+ XXX.gui.screens.TitleScreen
- XXX.gui.screens.TitleScreen$1
+ XXX.gui.screens.TitleScreen$Warning32Bit
- XXX.gui.screens.VideoSettingsScreen
+ XXX.gui.screens.WinScreen
- XXX.gui.screens.WinScreen$CreditsReader
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip
- XXX.inventory.tooltip.ClientBundleTooltip$Texture
+ XXX.inventory.tooltip.ClientTextTooltip
- XXX.inventory.tooltip.ClientTooltipComponent
+ XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.Potions
+ XXX.item.alchemy.PotionUtils
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$ItemValue
- XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleRecipeSerializer
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.SuspiciousStewRecipe
- XXX.item.crafting.TippedArrowRecipe
+ XXX.item.crafting.UpgradeRecipe
- XXX.item.crafting.UpgradeRecipe$Serializer
- XXX.item.enchantment.ArrowDamageEnchantment
+ XXX.item.enchantment.ArrowFireEnchantment
- XXX.item.enchantment.ArrowInfiniteEnchantment
+ XXX.item.enchantment.ArrowKnockbackEnchantment
- XXX.item.enchantment.ArrowPiercingEnchantment
+ XXX.item.enchantment.BindingCurseEnchantment
- XXX.item.enchantment.DamageEnchantment
+ XXX.item.enchantment.DigDurabilityEnchantment
- XXX.item.enchantment.DiggingEnchantment
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$Rarity
+ XXX.item.enchantment.EnchantmentCategory
- XXX.item.enchantment.EnchantmentCategory$1
+ XXX.item.enchantment.EnchantmentCategory$10
- XXX.item.enchantment.EnchantmentCategory$11
+ XXX.item.enchantment.EnchantmentCategory$12
- XXX.item.enchantment.EnchantmentCategory$13
+ XXX.item.enchantment.EnchantmentCategory$14
- XXX.item.enchantment.EnchantmentCategory$2
+ XXX.item.enchantment.EnchantmentCategory$3
- XXX.item.enchantment.EnchantmentCategory$4
+ XXX.item.enchantment.EnchantmentCategory$5
- XXX.item.enchantment.EnchantmentCategory$6
+ XXX.item.enchantment.EnchantmentCategory$7
- XXX.item.enchantment.EnchantmentCategory$8
+ XXX.item.enchantment.EnchantmentCategory$9
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.FireAspectEnchantment
+ XXX.item.enchantment.FishingSpeedEnchantment
- XXX.item.enchantment.FrostWalkerEnchantment
+ XXX.item.enchantment.KnockbackEnchantment
- XXX.item.enchantment.LootBonusEnchantment
+ XXX.item.enchantment.MendingEnchantment
- XXX.item.enchantment.MultiShotEnchantment
+ XXX.item.enchantment.OxygenEnchantment
+ XXX.item.enchantment.package-info
- XXX.item.enchantment.ProtectionEnchantment
+ XXX.item.enchantment.ProtectionEnchantment$Type
- XXX.item.enchantment.QuickChargeEnchantment
+ XXX.item.enchantment.SoulSpeedEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.SwiftSneakEnchantment
- XXX.item.enchantment.ThornsEnchantment
+ XXX.item.enchantment.TridentChannelingEnchantment
- XXX.item.enchantment.TridentImpalerEnchantment
+ XXX.item.enchantment.TridentLoyaltyEnchantment
- XXX.item.enchantment.TridentRiptideEnchantment
+ XXX.item.enchantment.UntouchingEnchantment
- XXX.item.enchantment.VanishingCurseEnchantment
+ XXX.item.enchantment.WaterWalkerEnchantment
- XXX.item.enchantment.WaterWorkerEnchantment
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.biome.AmbientMoodSettings
- XXX.level.biome.AmbientParticleSettings
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSource$1FeatureData
- XXX.level.biome.BiomeSource$StepFeatureData
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.Climate
- XXX.level.biome.Climate$DistanceMetric
+ XXX.level.biome.Climate$Parameter
- XXX.level.biome.Climate$ParameterList
+ XXX.level.biome.Climate$ParameterPoint
- XXX.level.biome.Climate$RTree
+ XXX.level.biome.Climate$RTree$Leaf
- XXX.level.biome.Climate$RTree$Node
+ XXX.level.biome.Climate$RTree$SubTree
- XXX.level.biome.Climate$Sampler
+ XXX.level.biome.Climate$SpawnFinder
- XXX.level.biome.Climate$SpawnFinder$Result
+ XXX.level.biome.Climate$TargetPoint
- XXX.level.biome.FixedBiomeSource
+ XXX.level.biome.MobSpawnSettings
- XXX.level.biome.MobSpawnSettings$Builder
+ XXX.level.biome.MobSpawnSettings$MobSpawnCost
- XXX.level.biome.MobSpawnSettings$SpawnerData
+ XXX.level.biome.MultiNoiseBiomeSource
- XXX.level.biome.MultiNoiseBiomeSource$Preset
+ XXX.level.biome.MultiNoiseBiomeSource$PresetInstance
- XXX.level.biome.OverworldBiomeBuilder
- XXX.level.biome.package-info
+ XXX.level.biome.TheEndBiomeSource
+ XXX.level.block.AbstractBannerBlock
- XXX.level.block.AbstractCandleBlock
+ XXX.level.block.AbstractCauldronBlock
- XXX.level.block.AbstractChestBlock
+ XXX.level.block.AbstractFurnaceBlock
- XXX.level.block.AbstractGlassBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AmethystBlock
- XXX.level.block.AmethystClusterBlock
+ XXX.level.block.AmethystClusterBlock$1
- XXX.level.block.AnvilBlock
+ XXX.level.block.AttachedStemBlock
- XXX.level.block.AzaleaBlock
+ XXX.level.block.BambooBlock
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BannerBlock
- XXX.level.block.BarrelBlock
+ XXX.level.block.BarrierBlock
- XXX.level.block.BaseCoralFanBlock
+ XXX.level.block.BaseCoralPlantBlock
- XXX.level.block.BaseCoralPlantTypeBlock
+ XXX.level.block.BaseCoralWallFanBlock
- XXX.level.block.BaseEntityBlock
+ XXX.level.block.BaseFireBlock
- XXX.level.block.BasePressurePlateBlock
+ XXX.level.block.BaseRailBlock
- XXX.level.block.BaseRailBlock$1
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BedBlock$1
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BigDripleafBlock
- XXX.level.block.BigDripleafStemBlock
+ XXX.level.block.BigDripleafStemBlock$1
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$BlockStatePairKey
+ XXX.level.block.Blocks
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BubbleColumnBlock
+ XXX.level.block.BucketPickup
- XXX.level.block.BuddingAmethystBlock
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CandleBlock
- XXX.level.block.CandleCakeBlock
+ XXX.level.block.CarpetBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.CaveVines
+ XXX.level.block.CaveVinesBlock
- XXX.level.block.CaveVinesPlantBlock
+ XXX.level.block.ChainBlock
- XXX.level.block.ChainBlock$1
+ XXX.level.block.ChangeOverTimeBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$4
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.CocoaBlock$1
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.DiodeBlock
- XXX.level.block.DirectionalBlock
+ XXX.level.block.DirtPathBlock
- XXX.level.block.DispenserBlock
+ XXX.level.block.DoorBlock
- XXX.level.block.DoorBlock$1
+ XXX.level.block.DoubleBlockCombiner
- XXX.level.block.DoubleBlockCombiner$BlockType
+ XXX.level.block.DoubleBlockCombiner$Combiner
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ XXX.level.block.DoublePlantBlock
- XXX.level.block.DragonEggBlock
+ XXX.level.block.DropExperienceBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.Fallable
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GameMasterBlock
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GravelBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.GrowingPlantBlock
+ XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.GrowingPlantHeadBlock
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.InfestedRotatedPillarBlock
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LadderBlock$1
+ XXX.level.block.LanternBlock
- XXX.level.block.LavaCauldronBlock
+ XXX.level.block.LayeredCauldronBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LecternBlock$1
+ XXX.level.block.LevelEvent
- XXX.level.block.LeverBlock
+ XXX.level.block.LeverBlock$1
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MangroveLeavesBlock
+ XXX.level.block.MangrovePropaguleBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
+ XXX.level.block.MudBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MultifaceSpreader
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ XXX.level.block.MultifaceSpreader$SpreadConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
+ XXX.level.block.MultifaceSpreader$SpreadPredicate
- XXX.level.block.MultifaceSpreader$SpreadType
+ XXX.level.block.MultifaceSpreader$SpreadType$1
- XXX.level.block.MultifaceSpreader$SpreadType$2
+ XXX.level.block.MultifaceSpreader$SpreadType$3
- XXX.level.block.MushroomBlock
+ XXX.level.block.MyceliumBlock
- XXX.level.block.NetherPortalBlock
+ XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
- XXX.level.block.package-info
+ XXX.level.block.PipeBlock
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PointedDripstoneBlock$FluidInfo
- XXX.level.block.PotatoBlock
+ XXX.level.block.PowderSnowBlock
- XXX.level.block.PowderSnowCauldronBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PressurePlateBlock$Sensitivity
+ XXX.level.block.PumpkinBlock
- XXX.level.block.RailBlock
+ XXX.level.block.RailBlock$1
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RespawnAnchorBlock$1
+ XXX.level.block.RodBlock
- XXX.level.block.RodBlock$1
+ XXX.level.block.RootedDirtBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
- XXX.level.block.Rotation$1
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
- XXX.level.block.SculkBehaviour
+ XXX.level.block.SculkBehaviour$1
- XXX.level.block.SculkBlock
+ XXX.level.block.SculkCatalystBlock
- XXX.level.block.SculkSensorBlock
+ XXX.level.block.SculkShriekerBlock
- XXX.level.block.SculkSpreader
+ XXX.level.block.SculkSpreader$ChargeCursor
- XXX.level.block.SculkVeinBlock
+ XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
+ XXX.level.block.SeagrassBlock
- XXX.level.block.SeaPickleBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmallDripleafBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnowLayerBlock
- XXX.level.block.SnowLayerBlock$1
+ XXX.level.block.SnowyDirtBlock
- XXX.level.block.SoulFireBlock
+ XXX.level.block.SoulSandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SporeBlossomBlock
- XXX.level.block.SpreadingSnowyDirtBlock
+ XXX.level.block.StainedGlassBlock
- XXX.level.block.StainedGlassPaneBlock
+ XXX.level.block.StairBlock
- XXX.level.block.StairBlock$1
+ XXX.level.block.StandingSignBlock
- XXX.level.block.StemBlock
+ XXX.level.block.StemGrownBlock
- XXX.level.block.StoneButtonBlock
+ XXX.level.block.StonecutterBlock
- XXX.level.block.StructureBlock
+ XXX.level.block.StructureBlock$1
- XXX.level.block.StructureVoidBlock
+ XXX.level.block.SugarCaneBlock
- XXX.level.block.SupportType
+ XXX.level.block.SupportType$1
- XXX.level.block.SupportType$2
+ XXX.level.block.SupportType$3
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TntBlock
+ XXX.level.block.TorchBlock
- XXX.level.block.TrapDoorBlock
+ XXX.level.block.TrapDoorBlock$1
- XXX.level.block.TrappedChestBlock
+ XXX.level.block.TripWireBlock
- XXX.level.block.TripWireBlock$1
+ XXX.level.block.TripWireHookBlock
- XXX.level.block.TripWireHookBlock$1
+ XXX.level.block.TurtleEggBlock
- XXX.level.block.TwistingVinesBlock
+ XXX.level.block.TwistingVinesPlantBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WeatheringCopper
- XXX.level.block.WeatheringCopper$WeatherState
+ XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringCopperSlabBlock
+ XXX.level.block.WeatheringCopperStairBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVinesBlock
- XXX.level.block.WeepingVinesPlantBlock
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoodButtonBlock
+ XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BlockColumn
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.CarvingMask
+ XXX.level.chunk.CarvingMask$Mask
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkAccess$TicksToSave
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$1
- XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunk$PostLoadProcessor
+ XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LevelChunkSection$1BlockCounter
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.MissingPaletteEntryException
+ XXX.level.chunk.package-info
+ XXX.level.chunk.Palette
- XXX.level.chunk.Palette$Factory
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$Configuration
- XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PalettedContainer$Data
- XXX.level.chunk.PalettedContainer$DiscData
+ XXX.level.chunk.PalettedContainer$Strategy
- XXX.level.chunk.PalettedContainer$Strategy$1
+ XXX.level.chunk.PalettedContainer$Strategy$2
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.StructureAccess
+ XXX.level.chunk.UpgradeData
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.BuiltinDimensionTypes
+ XXX.level.dimension.DimensionDefaults
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.entity.ChunkEntities
- XXX.level.entity.ChunkStatusUpdateListener
+ XXX.level.entity.EntityAccess
- XXX.level.entity.EntityInLevelCallback
+ XXX.level.entity.EntityInLevelCallback$1
- XXX.level.entity.EntityLookup
+ XXX.level.entity.EntityPersistentStorage
- XXX.level.entity.EntitySection
+ XXX.level.entity.EntitySectionStorage
- XXX.level.entity.EntityTickList
+ XXX.level.entity.EntityTypeTest
- XXX.level.entity.EntityTypeTest$1
+ XXX.level.entity.LevelCallback
- XXX.level.entity.LevelEntityGetter
+ XXX.level.entity.LevelEntityGetterAdapter
- XXX.level.entity.package-info
- XXX.level.entity.PersistentEntitySectionManager
+ XXX.level.entity.PersistentEntitySectionManager$Callback
- XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ XXX.level.entity.TransientEntitySectionManager
- XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.entity.Visibility
+ XXX.level.gameevent.BlockPositionSource
- XXX.level.gameevent.BlockPositionSource$Type
+ XXX.level.gameevent.DynamicGameEventListener
- XXX.level.gameevent.EntityPositionSource
+ XXX.level.gameevent.EntityPositionSource$Type
- XXX.level.gameevent.EuclideanGameEventDispatcher
+ XXX.level.gameevent.GameEvent
- XXX.level.gameevent.GameEvent$Context
+ XXX.level.gameevent.GameEvent$Message
- XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventDispatcher$1
- XXX.level.gameevent.GameEventListener
+ XXX.level.gameevent.package-info
+ XXX.level.gameevent.PositionSource
- XXX.level.gameevent.PositionSourceType
- XXX.level.levelgen.Aquifer
+ XXX.level.levelgen.Aquifer$1
- XXX.level.levelgen.Aquifer$FluidPicker
+ XXX.level.levelgen.Aquifer$FluidStatus
- XXX.level.levelgen.Aquifer$NoiseBasedAquifer
+ XXX.level.levelgen.Beardifier
- XXX.level.levelgen.Beardifier$1
+ XXX.level.levelgen.Beardifier$Rigid
- XXX.level.levelgen.BelowZeroRetrogen
+ XXX.level.levelgen.BelowZeroRetrogen$1
- XXX.level.levelgen.BitRandomSource
+ XXX.level.levelgen.Column
- XXX.level.levelgen.Column$Line
+ XXX.level.levelgen.Column$Range
- XXX.level.levelgen.Column$Ray
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.Density
+ XXX.level.levelgen.DensityFunction
- XXX.level.levelgen.DensityFunction$ContextProvider
+ XXX.level.levelgen.DensityFunction$FunctionContext
- XXX.level.levelgen.DensityFunction$NoiseHolder
+ XXX.level.levelgen.DensityFunction$SimpleFunction
- XXX.level.levelgen.DensityFunction$SinglePointContext
+ XXX.level.levelgen.DensityFunction$Visitor
- XXX.level.levelgen.DensityFunctions
+ XXX.level.levelgen.DensityFunctions$1
- XXX.level.levelgen.DensityFunctions$Ap2
+ XXX.level.levelgen.DensityFunctions$BeardifierMarker
- XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
+ XXX.level.levelgen.DensityFunctions$BlendAlpha
- XXX.level.levelgen.DensityFunctions$BlendDensity
+ XXX.level.levelgen.DensityFunctions$BlendOffset
- XXX.level.levelgen.DensityFunctions$Clamp
+ XXX.level.levelgen.DensityFunctions$Constant
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ XXX.level.levelgen.DensityFunctions$HolderHolder
- XXX.level.levelgen.DensityFunctions$Mapped
+ XXX.level.levelgen.DensityFunctions$Mapped$Type
- XXX.level.levelgen.DensityFunctions$Marker
+ XXX.level.levelgen.DensityFunctions$Marker$Type
- XXX.level.levelgen.DensityFunctions$MarkerOrMarked
+ XXX.level.levelgen.DensityFunctions$MulOrAdd
- XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
+ XXX.level.levelgen.DensityFunctions$Noise
- XXX.level.levelgen.DensityFunctions$PureTransformer
+ XXX.level.levelgen.DensityFunctions$RangeChoice
- XXX.level.levelgen.DensityFunctions$Shift
+ XXX.level.levelgen.DensityFunctions$ShiftA
- XXX.level.levelgen.DensityFunctions$ShiftB
- XXX.level.levelgen.DensityFunctions$ShiftedNoise
+ XXX.level.levelgen.DensityFunctions$ShiftNoise
+ XXX.level.levelgen.DensityFunctions$Spline
- XXX.level.levelgen.DensityFunctions$Spline$Coordinate
+ XXX.level.levelgen.DensityFunctions$Spline$Point
- XXX.level.levelgen.DensityFunctions$TransformerWithContext
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
+ XXX.level.levelgen.DensityFunctions$YClampedGradient
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeCrackSettings
- XXX.level.levelgen.GeodeLayerSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.LegacyRandomSource
+ XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- XXX.level.levelgen.MarsagliaPolarGaussian
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseChunk
+ XXX.level.levelgen.NoiseChunk$1
- XXX.level.levelgen.NoiseChunk$2
+ XXX.level.levelgen.NoiseChunk$BlendAlpha
- XXX.level.levelgen.NoiseChunk$BlendOffset
+ XXX.level.levelgen.NoiseChunk$BlockStateFiller
- XXX.level.levelgen.NoiseChunk$Cache2D
+ XXX.level.levelgen.NoiseChunk$CacheAllInCell
- XXX.level.levelgen.NoiseChunk$CacheOnce
+ XXX.level.levelgen.NoiseChunk$FlatCache
- XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ XXX.level.levelgen.NoiseChunk$NoiseInterpolator
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.NoiseRouter
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.PositionalRandomFactory
+ XXX.level.levelgen.RandomState
- XXX.level.levelgen.RandomState$1NoiseWiringHelper
+ XXX.level.levelgen.RandomSupport
- XXX.level.levelgen.RandomSupport$Seed128bit
+ XXX.level.levelgen.SingleThreadedRandomSource
- XXX.level.levelgen.SurfaceRules
+ XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
- XXX.level.levelgen.SurfaceRules$Bandlands
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ XXX.level.levelgen.SurfaceRules$BlockRuleSource
- XXX.level.levelgen.SurfaceRules$Condition
+ XXX.level.levelgen.SurfaceRules$ConditionSource
- XXX.level.levelgen.SurfaceRules$Context
+ XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- XXX.level.levelgen.SurfaceRules$Context$HoleCondition
+ XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ XXX.level.levelgen.SurfaceRules$Hole
- XXX.level.levelgen.SurfaceRules$LazyCondition
+ XXX.level.levelgen.SurfaceRules$LazyXZCondition
- XXX.level.levelgen.SurfaceRules$LazyYCondition
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ XXX.level.levelgen.SurfaceRules$NotCondition
- XXX.level.levelgen.SurfaceRules$NotConditionSource
+ XXX.level.levelgen.SurfaceRules$RuleSource
- XXX.level.levelgen.SurfaceRules$SequenceRule
+ XXX.level.levelgen.SurfaceRules$SequenceRuleSource
- XXX.level.levelgen.SurfaceRules$StateRule
+ XXX.level.levelgen.SurfaceRules$Steep
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- XXX.level.levelgen.SurfaceRules$SurfaceRule
+ XXX.level.levelgen.SurfaceRules$Temperature
- XXX.level.levelgen.SurfaceRules$TestRule
+ XXX.level.levelgen.SurfaceRules$TestRuleSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- XXX.level.levelgen.SurfaceRules$WaterConditionSource
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- XXX.level.levelgen.SurfaceRules$YConditionSource
+ XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- XXX.level.levelgen.SurfaceSystem
+ XXX.level.levelgen.SurfaceSystem$1
- XXX.level.levelgen.ThreadSafeLegacyRandomSource
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldgenRandom$Algorithm
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.levelgen.Xoroshiro128PlusPlus
- XXX.level.levelgen.XoroshiroRandomSource
+ XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.LayerLightEngine
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$1
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.Fluid
+ XXX.level.material.Fluids
- XXX.level.material.FluidState
- XXX.level.material.FogType
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.Material
+ XXX.level.material.Material$Builder
- XXX.level.material.MaterialColor
+ XXX.level.material.MaterialColor$Brightness
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.AmphibiousNodeEvaluator
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalInfo
+ XXX.level.portal.PortalShape
+ XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ XXX.level.redstone.InstantNeighborUpdater
- XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DataVersion
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelCandidates
+ XXX.level.storage.LevelStorageSource$LevelDirectory
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelVersion
- XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$Event
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
- XXX.levelgen.blending.BlendingData$BiomeConsumer
+ XXX.levelgen.blending.BlendingData$DensityConsumer
- XXX.levelgen.blending.BlendingData$HeightConsumer
+ XXX.levelgen.blending.package-info
- XXX.levelgen.blockpredicates.AllOfPredicate
+ XXX.levelgen.blockpredicates.AnyOfPredicate
- XXX.levelgen.blockpredicates.BlockPredicate
+ XXX.levelgen.blockpredicates.BlockPredicateType
- XXX.levelgen.blockpredicates.CombiningPredicate
+ XXX.levelgen.blockpredicates.HasSturdyFacePredicate
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlocksPredicate
+ XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
+ XXX.levelgen.blockpredicates.MatchingFluidsPredicate
- XXX.levelgen.blockpredicates.NotPredicate
- XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.WouldSurvivePredicate
+ XXX.levelgen.carver.CanyonCarverConfiguration
- XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CarverDebugSettings
- XXX.levelgen.carver.CarvingContext
+ XXX.levelgen.carver.CaveCarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.WorldCarver
- XXX.levelgen.carver.WorldCarver$CarveSkipChecker
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockColumnFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskFeature
- XXX.levelgen.feature.DripstoneClusterFeature
+ XXX.levelgen.feature.DripstoneUtils
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FeatureCountTracker
+ XXX.levelgen.feature.FeatureCountTracker$1
- XXX.levelgen.feature.FeatureCountTracker$FeatureData
+ XXX.levelgen.feature.FeatureCountTracker$LevelData
- XXX.levelgen.feature.FeaturePlaceContext
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.FossilFeatureConfiguration
- XXX.levelgen.feature.GeodeFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.LakeFeature$Configuration
+ XXX.levelgen.feature.LargeDripstoneFeature
- XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.MultifaceGrowthFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PointedDripstoneFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SculkPatchFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.UnderwaterMagmaFeature
- XXX.levelgen.feature.VegetationPatchFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedPlacedFeature
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPreset
+ XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
+ XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.heightproviders.WeightedListHeight
- XXX.levelgen.material.MaterialRuleList
- XXX.levelgen.material.package-info
+ XXX.levelgen.material.WorldGenMaterialRule
- XXX.levelgen.placement.BiomeFilter
+ XXX.levelgen.placement.BlockPredicateFilter
- XXX.levelgen.placement.CarvingMaskPlacement
+ XXX.levelgen.placement.CaveSurface
- XXX.levelgen.placement.CountOnEveryLayerPlacement
+ XXX.levelgen.placement.CountPlacement
- XXX.levelgen.placement.EnvironmentScanPlacement
- XXX.levelgen.placement.HeightmapPlacement
+ XXX.levelgen.placement.HeightRangePlacement
+ XXX.levelgen.placement.InSquarePlacement
- XXX.levelgen.placement.NoiseBasedCountPlacement
+ XXX.levelgen.placement.NoiseThresholdCountPlacement
+ XXX.levelgen.placement.package-info
- XXX.levelgen.placement.PlacedFeature
+ XXX.levelgen.placement.PlacedFeature$test
- XXX.levelgen.placement.PlacementContext
+ XXX.levelgen.placement.PlacementFilter
- XXX.levelgen.placement.PlacementModifier
+ XXX.levelgen.placement.PlacementModifierType
- XXX.levelgen.placement.RandomOffsetPlacement
+ XXX.levelgen.placement.RarityFilter
- XXX.levelgen.placement.RepeatingPlacement
+ XXX.levelgen.placement.SurfaceRelativeThresholdFilter
- XXX.levelgen.placement.SurfaceWaterDepthFilter
- XXX.levelgen.presets.WorldPreset
+ XXX.levelgen.presets.WorldPresets
- XXX.levelgen.presets.WorldPresets$Bootstrap
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuiltinStructures
+ XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationContext
+ XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.Structure$StructureSettings
+ XXX.levelgen.structure.StructureCheck
- XXX.levelgen.structure.StructureCheckResult
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructurePieceAccessor
- XXX.levelgen.structure.StructureSet
+ XXX.levelgen.structure.StructureSet$StructureSelectionEntry
- XXX.levelgen.structure.StructureSpawnOverride
+ XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureType
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.TerrainAdjustment
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.NormalNoise$NoiseParameters
- XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.DynamicLoot$Serializer
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EmptyLootItem$Serializer
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootItem$Serializer
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootPoolSingletonContainer$Serializer
- XXX.loot.entries.LootTableReference
+ XXX.loot.entries.LootTableReference$Serializer
+ XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
- XXX.loot.entries.TagEntry$Serializer
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$Serializer
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.ApplyExplosionDecay$Serializer
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyBlockState$Serializer
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.CopyNameFunction$Serializer
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Serializer
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.LimitCount$Serializer
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
- XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetBannerPatternFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetEnchantmentsFunction$Serializer
+ XXX.loot.functions.SetInstrumentFunction
- XXX.loot.functions.SetInstrumentFunction$Serializer
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemDamageFunction$Serializer
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$Serializer
- XXX.loot.functions.SetPotionFunction
+ XXX.loot.functions.SetPotionFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$Serializer
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.SmeltItemFunction$Serializer
+ XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AlternativeLootItemCondition
- XXX.loot.predicates.AlternativeLootItemCondition$Builder
+ XXX.loot.predicates.AlternativeLootItemCondition$Serializer
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.BonusLevelTableCondition$Serializer
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ XXX.loot.predicates.MatchTool
- XXX.loot.predicates.MatchTool$Serializer
+ XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.ValueCheckCondition$Serializer
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.loot.predicates.WeatherCheck$Serializer
- XXX.metadata.animation.AnimationFrame
+ XXX.metadata.animation.AnimationMetadataSection
- XXX.metadata.animation.AnimationMetadataSection$1
+ XXX.metadata.animation.AnimationMetadataSection$FrameOutput
- XXX.metadata.animation.AnimationMetadataSectionSerializer
- XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetaDataSection
- XXX.metadata.animation.VillagerMetaDataSection$Hat
+ XXX.metadata.animation.VillagerMetadataSectionSerializer
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.LanguageMetadataSectionSerializer
+ XXX.metadata.language.package-info
+ XXX.metadata.texture.package-info
+ XXX.metadata.texture.TextureMetadataSection
- XXX.metadata.texture.TextureMetadataSectionSerializer
+ XXX.minecraft.client.package-info
- XXX.minecraft.client.Realms32BitWarningStatus
+ XXX.minecraft.client.RecipeBookCategories
- XXX.minecraft.client.RecipeBookCategories$1
+ XXX.minecraft.client.ResourceLoadStateTracker
- XXX.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
+ XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason
- XXX.minecraft.client.ResourceLoadStateTracker$ReloadState
+ XXX.minecraft.client.Screenshot
- XXX.minecraft.client.Session
+ XXX.minecraft.client.StringSplitter
- XXX.minecraft.client.StringSplitter$1
+ XXX.minecraft.client.StringSplitter$FlatComponents
- XXX.minecraft.client.StringSplitter$LineBreakFinder
+ XXX.minecraft.client.StringSplitter$LineComponent
- XXX.minecraft.client.StringSplitter$LinePosConsumer
+ XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
- XXX.minecraft.client.StringSplitter$WidthProvider
+ XXX.minecraft.client.Timer
- XXX.minecraft.client.ToggleKeyMapping
+ XXX.minecraft.client.User
- XXX.minecraft.client.User$Type
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CommandBuildContext
- XXX.minecraft.commands.CommandBuildContext$1
+ XXX.minecraft.commands.CommandBuildContext$2
- XXX.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
+ XXX.minecraft.commands.CommandFunction
- XXX.minecraft.commands.CommandFunction$CacheableFunction
+ XXX.minecraft.commands.CommandFunction$CommandEntry
- XXX.minecraft.commands.CommandFunction$Entry
+ XXX.minecraft.commands.CommandFunction$FunctionEntry
- XXX.minecraft.commands.CommandRuntimeException
- XXX.minecraft.commands.Commands
+ XXX.minecraft.commands.Commands$CommandSelection
- XXX.minecraft.commands.Commands$ParseFunction
+ XXX.minecraft.commands.CommandSigningContext
- XXX.minecraft.commands.CommandSigningContext$PlainArguments
+ XXX.minecraft.commands.CommandSource
- XXX.minecraft.commands.CommandSource$1
+ XXX.minecraft.commands.CommandSourceStack
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.data.BuiltinRegistries$RegistryBootstrap
+ XXX.minecraft.data.CachedOutput
- XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataGenerator$Target
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.HashCache$CacheUpdater
- XXX.minecraft.data.HashCache$ProviderCache
+ XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
+ XXX.minecraft.obfuscate.DontObfuscate
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.DisconnectedRealmsScreen
- XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
- XXX.minecraft.resources.RegistryLoader
+ XXX.minecraft.resources.RegistryLoader$Bound
- XXX.minecraft.resources.RegistryLoader$ReadCache
+ XXX.minecraft.resources.RegistryOps
- XXX.minecraft.resources.RegistryResourceAccess
+ XXX.minecraft.resources.RegistryResourceAccess$1
- XXX.minecraft.resources.RegistryResourceAccess$EntryThunk
+ XXX.minecraft.resources.RegistryResourceAccess$InMemoryStorage
- XXX.minecraft.resources.RegistryResourceAccess$InMemoryStorage$Entry
+ XXX.minecraft.resources.RegistryResourceAccess$ParsedEntry
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.ReloadableServerResources
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$ExecutionContext
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
- XXX.minecraft.tags.package-info
- XXX.minecraft.tags.PoiTypeTags
+ XXX.minecraft.tags.StructureTags
+ XXX.minecraft.tags.Tag$Builder
+ XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$OptionalElementEntry
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.TagBuilder
- XXX.minecraft.tags.TagEntry$Lookup
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagLoader$1
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.TagNetworkSerialization$TagOutput
+ XXX.minecraft.tags.WorldPresetTags
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$EitherCodec
- XXX.minecraft.util.ExtraCodecs$LazyInitializedCodec
+ XXX.minecraft.world.package-info
+ XXX.model.multipart.AndCondition
- XXX.model.multipart.Condition
+ XXX.model.multipart.KeyValueCondition
- XXX.model.multipart.MultiPart
+ XXX.model.multipart.MultiPart$Deserializer
- XXX.model.multipart.OrCondition
+ XXX.model.multipart.package-info
+ XXX.model.multipart.Selector
- XXX.model.multipart.Selector$Deserializer
- XXX.models.blockstates.BlockStateGenerator
+ XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
+ XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$C1
+ XXX.models.blockstates.PropertyDispatch$C2
- XXX.models.blockstates.PropertyDispatch$C3
+ XXX.models.blockstates.PropertyDispatch$C4
- XXX.models.blockstates.PropertyDispatch$C5
+ XXX.models.blockstates.PropertyDispatch$PentaFunction
- XXX.models.blockstates.PropertyDispatch$QuadFunction
+ XXX.models.blockstates.PropertyDispatch$TriFunction
- XXX.models.blockstates.Selector
+ XXX.models.blockstates.Variant
- XXX.models.blockstates.VariantProperties
+ XXX.models.blockstates.VariantProperties$Rotation
- XXX.models.blockstates.VariantProperty
+ XXX.models.blockstates.VariantProperty$Value
+ XXX.models.model.DelegatedModel
- XXX.models.model.ModelLocationUtils
+ XXX.models.model.ModelTemplate
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.HoglinBase
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.AbstractPiglin
- XXX.monster.piglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.PiglinArmPose
- XXX.monster.piglin.PiglinBrute
+ XXX.monster.piglin.PiglinBruteAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
+ XXX.monster.piglin.StartAdmiringItemIfSeen
- XXX.monster.piglin.StartHuntingHoglin
+ XXX.monster.piglin.StopAdmiringIfItemTooFarAway
- XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ XXX.monster.warden.AngerLevel
- XXX.monster.warden.AngerManagement
+ XXX.monster.warden.AngerManagement$1
- XXX.monster.warden.AngerManagement$Sorter
- XXX.monster.warden.package-info
+ XXX.monster.warden.Warden
- XXX.monster.warden.Warden$1
- XXX.monster.warden.Warden$2
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenAi$1
+ XXX.monster.warden.WardenSpawnTracker
- XXX.multiplayer.prediction.BlockStatePredictionHandler
+ XXX.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
+ XXX.multiplayer.prediction.package-info
- XXX.multiplayer.prediction.PredictiveAction
- XXX.multiplayer.resolver.AddressCheck
+ XXX.multiplayer.resolver.AddressCheck$1
- XXX.multiplayer.resolver.package-info
- XXX.multiplayer.resolver.ResolvedServerAddress
+ XXX.multiplayer.resolver.ResolvedServerAddress$1
- XXX.multiplayer.resolver.ServerAddress
+ XXX.multiplayer.resolver.ServerAddressResolver
- XXX.multiplayer.resolver.ServerNameResolver
+ XXX.multiplayer.resolver.ServerRedirectHandler
- XXX.network.chat.ChatDecorator
- XXX.network.protocol.package-info
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$1
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$1
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
+ XXX.player.inventory.Hotbar
- XXX.player.inventory.package-info
- XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandsPacket$NodeStub
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
- XXX.protocol.game.ClientboundLevelChunkPacketData
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ XXX.protocol.game.ClientboundLevelChunkWithLightPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLightUpdatePacketData
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
+ XXX.protocol.game.ClientboundPingPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerChatPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$1
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$2
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$3
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$4
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$5
+ XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- XXX.protocol.game.ClientboundPlayerLookAtPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResourcePackPacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundServerDataPacket
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPongPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.protocol.status.ServerStatusPacketListener
- XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$1
- XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
- XXX.providers.nbt.ContextNbtProvider$InlineSerializer
+ XXX.providers.nbt.ContextNbtProvider$Serializer
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
- XXX.providers.nbt.StorageNbtProvider$Serializer
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.BinomialDistributionGenerator$Serializer
- XXX.providers.number.ConstantValue
+ XXX.providers.number.ConstantValue$InlineSerializer
- XXX.providers.number.ConstantValue$Serializer
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.ScoreboardValue$Serializer
- XXX.providers.number.UniformGenerator
+ XXX.providers.number.UniformGenerator$Serializer
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
+ XXX.providers.score.ContextScoreboardNameProvider$Serializer
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider$Serializer
- XXX.providers.score.LootScoreProviderType
+ XXX.providers.score.package-info
+ XXX.providers.score.ScoreboardNameProvider
- XXX.providers.score.ScoreboardNameProviders
- XXX.renderer.block.BlockModelShaper
+ XXX.renderer.block.BlockRenderDispatcher
- XXX.renderer.block.BlockRenderDispatcher$1
+ XXX.renderer.block.LiquidBlockRenderer
- XXX.renderer.block.LiquidBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer
- XXX.renderer.block.ModelBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
- XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- XXX.renderer.block.ModelBlockRenderer$Cache
+ XXX.renderer.block.ModelBlockRenderer$Cache$1
- XXX.renderer.block.ModelBlockRenderer$Cache$2
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
+ XXX.renderer.block.package-info
- XXX.renderer.blockentity.BannerRenderer
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
- XXX.renderer.blockentity.BlockEntityRendererProvider
+ XXX.renderer.blockentity.BlockEntityRendererProvider$Context
- XXX.renderer.blockentity.BlockEntityRenderers
+ XXX.renderer.blockentity.BrightnessCombiner
- XXX.renderer.blockentity.CampfireRenderer
+ XXX.renderer.blockentity.ChestRenderer
- XXX.renderer.blockentity.ConduitRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.package-info
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.SignRenderer
- XXX.renderer.blockentity.SignRenderer$SignModel
+ XXX.renderer.blockentity.SkullBlockRenderer
- XXX.renderer.blockentity.SpawnerRenderer
+ XXX.renderer.blockentity.StructureBlockRenderer
- XXX.renderer.blockentity.StructureBlockRenderer$1
+ XXX.renderer.blockentity.TheEndGatewayRenderer
- XXX.renderer.blockentity.TheEndPortalRenderer
- XXX.renderer.chunk.ChunkRenderDispatcher
+ XXX.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
- XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
+ XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
- XXX.renderer.chunk.package-info
+ XXX.renderer.chunk.RenderChunk
- XXX.renderer.chunk.RenderChunkRegion
+ XXX.renderer.chunk.RenderRegionCache
- XXX.renderer.chunk.RenderRegionCache$ChunkInfo
+ XXX.renderer.chunk.VisGraph
- XXX.renderer.chunk.VisGraph$1
+ XXX.renderer.chunk.VisibilitySet
+ XXX.renderer.culling.Frustum
- XXX.renderer.culling.package-info
+ XXX.renderer.debug.BeeDebugRenderer
- XXX.renderer.debug.BeeDebugRenderer$BeeInfo
+ XXX.renderer.debug.BeeDebugRenderer$HiveInfo
- XXX.renderer.debug.BrainDebugRenderer
+ XXX.renderer.debug.BrainDebugRenderer$BrainDump
- XXX.renderer.debug.BrainDebugRenderer$PoiInfo
+ XXX.renderer.debug.ChunkBorderRenderer
- XXX.renderer.debug.ChunkDebugRenderer
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.GameEventListenerRenderer
- XXX.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
- XXX.renderer.debug.GameTestDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer$Marker
- XXX.renderer.debug.GoalSelectorDebugRenderer
+ XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- XXX.renderer.debug.HeightMapRenderer
+ XXX.renderer.debug.HeightMapRenderer$1
- XXX.renderer.debug.LightDebugRenderer
+ XXX.renderer.debug.NeighborsUpdateRenderer
+ XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.SolidFaceRenderer
+ XXX.renderer.debug.StructureRenderer
- XXX.renderer.debug.VillageSectionsDebugRenderer
+ XXX.renderer.debug.WaterDebugRenderer
- XXX.renderer.debug.WorldGenAttemptRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.AllayRenderer
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.AxolotlRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.CatRenderer
+ XXX.renderer.entity.CaveSpiderRenderer
- XXX.renderer.entity.ChestedHorseRenderer
+ XXX.renderer.entity.ChickenRenderer
- XXX.renderer.entity.CodRenderer
+ XXX.renderer.entity.CowRenderer
- XXX.renderer.entity.CreeperRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EnderDragonRenderer$DragonModel
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EntityRendererProvider
+ XXX.renderer.entity.EntityRendererProvider$Context
- XXX.renderer.entity.EntityRenderers
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.FrogRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GlowSquidRenderer
+ XXX.renderer.entity.GoatRenderer
- XXX.renderer.entity.GuardianRenderer
+ XXX.renderer.entity.HoglinRenderer
- XXX.renderer.entity.HorseRenderer
+ XXX.renderer.entity.HumanoidMobRenderer
- XXX.renderer.entity.HuskRenderer
+ XXX.renderer.entity.IllagerRenderer
- XXX.renderer.entity.IllusionerRenderer
+ XXX.renderer.entity.IllusionerRenderer$1
- XXX.renderer.entity.IronGolemRenderer
+ XXX.renderer.entity.ItemEntityRenderer
- XXX.renderer.entity.ItemFrameRenderer
+ XXX.renderer.entity.ItemRenderer
- XXX.renderer.entity.LeashKnotRenderer
+ XXX.renderer.entity.LightningBoltRenderer
- XXX.renderer.entity.LivingEntityRenderer
+ XXX.renderer.entity.LivingEntityRenderer$1
- XXX.renderer.entity.LlamaRenderer
+ XXX.renderer.entity.LlamaSpitRenderer
- XXX.renderer.entity.MagmaCubeRenderer
+ XXX.renderer.entity.MinecartRenderer
- XXX.renderer.entity.MobRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.package-info
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
+ XXX.renderer.entity.SheepRenderer
- XXX.renderer.entity.ShulkerBulletRenderer
+ XXX.renderer.entity.ShulkerRenderer
- XXX.renderer.entity.SilverfishRenderer
+ XXX.renderer.entity.SkeletonRenderer
- XXX.renderer.entity.SlimeRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.StriderRenderer
+ XXX.renderer.entity.TadpoleRenderer
- XXX.renderer.entity.ThrownItemRenderer
+ XXX.renderer.entity.ThrownTridentRenderer
- XXX.renderer.entity.TippableArrowRenderer
+ XXX.renderer.entity.TntMinecartRenderer
- XXX.renderer.entity.TntRenderer
+ XXX.renderer.entity.TropicalFishRenderer
- XXX.renderer.entity.TurtleRenderer
+ XXX.renderer.entity.UndeadHorseRenderer
- XXX.renderer.entity.VexRenderer
+ XXX.renderer.entity.VillagerRenderer
- XXX.renderer.entity.VindicatorRenderer
+ XXX.renderer.entity.VindicatorRenderer$1
- XXX.renderer.entity.WanderingTraderRenderer
+ XXX.renderer.entity.WardenRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.renderer.item.ClampedItemPropertyFunction
- XXX.renderer.item.CompassItemPropertyFunction
+ XXX.renderer.item.CompassItemPropertyFunction$CompassTarget
- XXX.renderer.item.CompassItemPropertyFunction$CompassWobble
+ XXX.renderer.item.ItemProperties
- XXX.renderer.item.ItemProperties$1
+ XXX.renderer.item.ItemPropertyFunction
- XXX.renderer.item.package-info
- XXX.renderer.texture.AbstractTexture
+ XXX.renderer.texture.AtlasSet
- XXX.renderer.texture.DynamicTexture
+ XXX.renderer.texture.HttpTexture
- XXX.renderer.texture.MipmapGenerator
+ XXX.renderer.texture.MissingTextureAtlasSprite
- XXX.renderer.texture.OverlayTexture
- XXX.renderer.texture.package-info
+ XXX.renderer.texture.PreloadedTexture
- XXX.renderer.texture.SimpleTexture
+ XXX.renderer.texture.SimpleTexture$TextureImage
- XXX.renderer.texture.Stitcher
+ XXX.renderer.texture.Stitcher$Holder
- XXX.renderer.texture.Stitcher$Region
+ XXX.renderer.texture.Stitcher$SpriteLoader
- XXX.renderer.texture.StitcherException
+ XXX.renderer.texture.TextureAtlas
- XXX.renderer.texture.TextureAtlas$Preparations
+ XXX.renderer.texture.TextureAtlasSprite
- XXX.renderer.texture.TextureAtlasSprite$AnimatedTexture
+ XXX.renderer.texture.TextureAtlasSprite$FrameInfo
- XXX.renderer.texture.TextureAtlasSprite$Info
+ XXX.renderer.texture.TextureAtlasSprite$InterpolationData
- XXX.renderer.texture.TextureManager
+ XXX.renderer.texture.Tickable
- XXX.resources.language.ClientLanguage
+ XXX.resources.language.FormattedBidiReorder
- XXX.resources.language.I18n
+ XXX.resources.language.LanguageInfo
- XXX.resources.language.LanguageManager
+ XXX.resources.language.package-info
- XXX.resources.metadata.package-info
- XXX.resources.model.BakedModel
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BuiltInModel
+ XXX.resources.model.Material
- XXX.resources.model.ModelBakery
+ XXX.resources.model.ModelBakery$BlockStateDefinitionException
- XXX.resources.model.ModelBakery$ModelGroupKey
+ XXX.resources.model.ModelManager
- XXX.resources.model.ModelResourceLocation
+ XXX.resources.model.ModelState
- XXX.resources.model.MultiPartBakedModel
+ XXX.resources.model.MultiPartBakedModel$Builder
+ XXX.resources.model.package-info
- XXX.resources.model.SimpleBakedModel
+ XXX.resources.model.SimpleBakedModel$Builder
- XXX.resources.model.UnbakedModel
+ XXX.resources.model.WeightedBakedModel
- XXX.resources.model.WeightedBakedModel$Builder
+ XXX.resources.sounds.AbstractSoundInstance
- XXX.resources.sounds.AbstractTickableSoundInstance
+ XXX.resources.sounds.AmbientSoundHandler
- XXX.resources.sounds.BeeAggressiveSoundInstance
+ XXX.resources.sounds.BeeFlyingSoundInstance
- XXX.resources.sounds.BeeSoundInstance
+ XXX.resources.sounds.BiomeAmbientSoundsHandler
- XXX.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
+ XXX.resources.sounds.BubbleColumnAmbientSoundHandler
- XXX.resources.sounds.ElytraOnPlayerSoundInstance
+ XXX.resources.sounds.EntityBoundSoundInstance
- XXX.resources.sounds.GuardianAttackSoundInstance
+ XXX.resources.sounds.MinecartSoundInstance
+ XXX.resources.sounds.package-info
- XXX.resources.sounds.RidingMinecartSoundInstance
+ XXX.resources.sounds.SimpleSoundInstance
- XXX.resources.sounds.Sound
+ XXX.resources.sounds.Sound$Type
- XXX.resources.sounds.SoundEventRegistration
+ XXX.resources.sounds.SoundEventRegistrationSerializer
- XXX.resources.sounds.SoundInstance
+ XXX.resources.sounds.SoundInstance$Attenuation
- XXX.resources.sounds.TickableSoundInstance
+ XXX.resources.sounds.UnderwaterAmbientSoundHandler
- XXX.resources.sounds.UnderwaterAmbientSoundInstances
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- XXX.screens.achievement.StatsScreen$ItemStatisticsList
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList
- XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ XXX.screens.achievement.StatsUpdateListener
- XXX.screens.advancements.AdvancementsScreen
+ XXX.screens.advancements.AdvancementTab
- XXX.screens.advancements.AdvancementTabType
+ XXX.screens.advancements.AdvancementTabType$1
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
+ XXX.screens.advancements.package-info
- XXX.screens.controls.ControlsScreen
+ XXX.screens.controls.KeyBindsList
- XXX.screens.controls.KeyBindsList$CategoryEntry
+ XXX.screens.controls.KeyBindsList$CategoryEntry$1
- XXX.screens.controls.KeyBindsList$Entry
+ XXX.screens.controls.KeyBindsList$KeyEntry
- XXX.screens.controls.KeyBindsList$KeyEntry$1
+ XXX.screens.controls.KeyBindsList$KeyEntry$2
- XXX.screens.controls.KeyBindsScreen
+ XXX.screens.controls.package-info
- XXX.screens.debug.GameModeSwitcherScreen
+ XXX.screens.debug.GameModeSwitcherScreen$1
- XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
- XXX.screens.debug.package-info
+ XXX.screens.inventory.AbstractCommandBlockEditScreen
- XXX.screens.inventory.AbstractCommandBlockEditScreen$1
+ XXX.screens.inventory.AbstractContainerScreen
- XXX.screens.inventory.AbstractFurnaceScreen
+ XXX.screens.inventory.AnvilScreen
- XXX.screens.inventory.BeaconScreen
+ XXX.screens.inventory.BeaconScreen$1
- XXX.screens.inventory.BeaconScreen$BeaconButton
+ XXX.screens.inventory.BeaconScreen$BeaconCancelButton
- XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
+ XXX.screens.inventory.BeaconScreen$BeaconPowerButton
- XXX.screens.inventory.BeaconScreen$BeaconScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
+ XXX.screens.inventory.BlastFurnaceScreen
- XXX.screens.inventory.BookEditScreen
+ XXX.screens.inventory.BookEditScreen$DisplayCache
- XXX.screens.inventory.BookEditScreen$LineInfo
+ XXX.screens.inventory.BookEditScreen$Pos2i
- XXX.screens.inventory.BookViewScreen
+ XXX.screens.inventory.BookViewScreen$1
- XXX.screens.inventory.BookViewScreen$BookAccess
+ XXX.screens.inventory.BookViewScreen$WritableBookAccess
- XXX.screens.inventory.BookViewScreen$WrittenBookAccess
+ XXX.screens.inventory.BrewingStandScreen
- XXX.screens.inventory.CartographyTableScreen
+ XXX.screens.inventory.CommandBlockEditScreen
- XXX.screens.inventory.CommandBlockEditScreen$1
+ XXX.screens.inventory.ContainerScreen
- XXX.screens.inventory.CraftingScreen
+ XXX.screens.inventory.CreativeInventoryListener
- XXX.screens.inventory.CreativeModeInventoryScreen
+ XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- XXX.screens.inventory.DispenserScreen
+ XXX.screens.inventory.EffectRenderingInventoryScreen
- XXX.screens.inventory.EnchantmentNames
+ XXX.screens.inventory.EnchantmentScreen
- XXX.screens.inventory.FurnaceScreen
+ XXX.screens.inventory.GrindstoneScreen
- XXX.screens.inventory.HopperScreen
+ XXX.screens.inventory.HorseInventoryScreen
- XXX.screens.inventory.InventoryScreen
+ XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.JigsawBlockEditScreen
+ XXX.screens.inventory.JigsawBlockEditScreen$1
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
- XXX.screens.multiplayer.ChatPreviewWarningScreen
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.chase.ChaseClient
- XXX.server.chase.ChaseClient$TeleportTarget
+ XXX.server.chase.ChaseServer
- XXX.server.chase.ChaseServer$PlayerPosition
+ XXX.server.chase.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ChaseCommand
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$Mode
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugCommand$Tracer
- XXX.server.commands.DebugMobSpawningCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
- XXX.server.commands.GameModeCommand
+ XXX.server.commands.GameRuleCommand
- XXX.server.commands.GameRuleCommand$1
+ XXX.server.commands.GiveCommand
- XXX.server.commands.HelpCommand
+ XXX.server.commands.ItemCommands
- XXX.server.commands.JfrCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
+ XXX.state.pattern.BlockInWorld
- XXX.state.pattern.BlockPattern
+ XXX.state.pattern.BlockPattern$BlockCacheLoader
- XXX.state.pattern.BlockPattern$BlockPatternMatch
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate
- XXX.state.predicate.BlockMaterialPredicate$1
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AttachFace
+ XXX.state.properties.BambooLeaves
- XXX.state.properties.BedPart
+ XXX.state.properties.BellAttachType
- XXX.state.properties.BlockStateProperties
+ XXX.state.properties.BooleanProperty
- XXX.state.properties.ChestType
+ XXX.state.properties.ComparatorMode
- XXX.state.properties.DirectionProperty
+ XXX.state.properties.DoorHingeSide
- XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.DripstoneThickness
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.Property$Value
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.SculkSensorPhase
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.Tilt
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.Deserializers
+ XXX.storage.loot.GsonAdapterFactory
- XXX.storage.loot.GsonAdapterFactory$Builder
+ XXX.storage.loot.GsonAdapterFactory$InlineSerializer
- XXX.storage.loot.GsonAdapterFactory$JsonAdapter
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.IntRange$Serializer
+ XXX.storage.loot.ItemModifierManager
- XXX.storage.loot.ItemModifierManager$FunctionSequence
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$DynamicDrop
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$EntityTarget$Serializer
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootPool$Serializer
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.LootTable$Serializer
+ XXX.storage.loot.LootTables
- XXX.storage.loot.package-info
- XXX.storage.loot.PredicateManager
+ XXX.storage.loot.PredicateManager$CompositePredicate
- XXX.storage.loot.Serializer
+ XXX.storage.loot.SerializerType
- XXX.storage.loot.ValidationContext
+ XXX.structure.pieces.package-info
+ XXX.structure.pieces.PieceGenerator
- XXX.structure.pieces.PieceGenerator$Context
+ XXX.structure.pieces.PieceGeneratorSupplier
- XXX.structure.pieces.PieceGeneratorSupplier$Context
+ XXX.structure.pieces.PiecesContainer
- XXX.structure.pieces.StructurePiecesBuilder
- XXX.structure.pieces.StructurePieceSerializationContext
+ XXX.structure.pieces.StructurePieceType
- XXX.structure.pieces.StructurePieceType$ContextlessType
+ XXX.structure.pieces.StructurePieceType$StructureTemplateType
- XXX.structure.placement.ConcentricRingsStructurePlacement
+ XXX.structure.placement.package-info
+ XXX.structure.placement.RandomSpreadStructurePlacement
- XXX.structure.placement.RandomSpreadType
+ XXX.structure.placement.RandomSpreadType$1
- XXX.structure.placement.StructurePlacement
+ XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReducer
+ XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.EmptyPoolElement
+ XXX.structure.pools.FeaturePoolElement
- XXX.structure.pools.JigsawJunction
+ XXX.structure.pools.JigsawPlacement
- XXX.structure.pools.JigsawPlacement$PieceState
+ XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.LegacySinglePoolElement
+ XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
- XXX.structure.pools.SinglePoolElement
+ XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructurePoolElementType
+ XXX.structure.pools.StructureTemplatePool
- XXX.structure.pools.StructureTemplatePool$Projection
- XXX.structure.structures.BuriedTreasurePieces
+ XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.structure.structures.BuriedTreasureStructure
+ XXX.structure.structures.DesertPyramidPiece
- XXX.structure.structures.DesertPyramidStructure
+ XXX.structure.structures.EndCityPieces
- XXX.structure.structures.EndCityPieces$1
+ XXX.structure.structures.EndCityPieces$2
- XXX.structure.structures.EndCityPieces$3
+ XXX.structure.structures.EndCityPieces$4
- XXX.structure.structures.EndCityPieces$EndCityPiece
+ XXX.structure.structures.EndCityPieces$SectionGenerator
- XXX.structure.structures.EndCityStructure
+ XXX.structure.structures.IglooPieces
- XXX.structure.structures.IglooPieces$IglooPiece
+ XXX.structure.structures.IglooStructure
- XXX.structure.structures.JigsawStructure
+ XXX.structure.structures.JigsawStructure$1
- XXX.structure.structures.JungleTemplePiece
+ XXX.structure.structures.JungleTemplePiece$MossStoneSelector
- XXX.structure.structures.JungleTempleStructure
+ XXX.structure.structures.MineshaftPieces
- XXX.structure.structures.MineshaftPieces$1
+ XXX.structure.structures.MineshaftPieces$MineShaftCorridor
- XXX.structure.structures.MineshaftPieces$MineShaftCrossing
+ XXX.structure.structures.MineshaftPieces$MineShaftPiece
- XXX.structure.structures.MineshaftPieces$MineShaftRoom
+ XXX.structure.structures.MineshaftPieces$MineShaftStairs
- XXX.structure.structures.MineshaftStructure
+ XXX.structure.structures.MineshaftStructure$Type
- XXX.structure.structures.NetherFortressPieces
+ XXX.structure.structures.NetherFortressPieces$1
- XXX.structure.structures.NetherFortressPieces$BridgeCrossing
+ XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
- XXX.structure.structures.NetherFortressPieces$BridgeStraight
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ XXX.structure.structures.NetherFortressPieces$CastleEntrance
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
+ XXX.structure.structures.NetherFortressPieces$MonsterThrone
- XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
+ XXX.structure.structures.NetherFortressPieces$PieceWeight
- XXX.structure.structures.NetherFortressPieces$RoomCrossing
+ XXX.structure.structures.NetherFortressPieces$StairsRoom
- XXX.structure.structures.NetherFortressPieces$StartPiece
+ XXX.structure.structures.NetherFortressStructure
- XXX.structure.structures.NetherFossilPieces
+ XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
- XXX.structure.structures.NetherFossilStructure
+ XXX.structure.structures.OceanMonumentPieces
- XXX.structure.structures.OceanMonumentPieces$1
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
+ XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.structure.structures.OceanMonumentPieces$RoomDefinition
+ XXX.structure.structures.OceanMonumentStructure
- XXX.structure.structures.OceanRuinPieces
+ XXX.structure.structures.OceanRuinPieces$1
- XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
+ XXX.structure.structures.OceanRuinStructure
- XXX.structure.structures.OceanRuinStructure$Type
+ XXX.structure.structures.package-info
+ XXX.structure.structures.RuinedPortalPiece
- XXX.structure.structures.RuinedPortalPiece$Properties
+ XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
- XXX.structure.structures.RuinedPortalStructure
+ XXX.structure.structures.RuinedPortalStructure$Setup
- XXX.structure.structures.ShipwreckPieces
+ XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
- XXX.structure.structures.ShipwreckStructure
+ XXX.structure.structures.StrongholdPieces
- XXX.structure.structures.StrongholdPieces$1
+ XXX.structure.structures.StrongholdPieces$2
- XXX.structure.structures.StrongholdPieces$3
+ XXX.structure.structures.StrongholdPieces$ChestCorridor
- XXX.structure.structures.StrongholdPieces$FillerCorridor
+ XXX.structure.structures.StrongholdPieces$FiveCrossing
- XXX.structure.structures.StrongholdPieces$LeftTurn
+ XXX.structure.structures.StrongholdPieces$Library
- XXX.structure.structures.StrongholdPieces$PieceWeight
+ XXX.structure.structures.StrongholdPieces$PortalRoom
- XXX.structure.structures.StrongholdPieces$PrisonHall
+ XXX.structure.structures.StrongholdPieces$RightTurn
- XXX.structure.structures.StrongholdPieces$RoomCrossing
+ XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
- XXX.structure.structures.StrongholdPieces$StairsDown
+ XXX.structure.structures.StrongholdPieces$StartPiece
- XXX.structure.structures.StrongholdPieces$Straight
+ XXX.structure.structures.StrongholdPieces$StraightStairsDown
- XXX.structure.structures.StrongholdPieces$StrongholdPiece
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.structure.structures.StrongholdPieces$Turn
+ XXX.structure.structures.StrongholdStructure
- XXX.structure.structures.SwampHutPiece
+ XXX.structure.structures.SwampHutStructure
- XXX.structure.structures.WoodlandMansionPieces
+ XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$MansionGrid
- XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.structure.structures.WoodlandMansionPieces$PlacementData
- XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
- XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.structure.structures.WoodlandMansionStructure
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.ProtectedBlockProcessor
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.TagMatchTest
- XXX.village.poi.package-info
+ XXX.world.entity.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$Builder
- XXX.world.food.Foods
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractContainerMenu$1
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.AnvilMenu$1
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$FuelSlot
+ XXX.world.inventory.BrewingStandMenu$IngredientsSlot
- XXX.world.inventory.BrewingStandMenu$PotionSlot
+ XXX.world.inventory.CartographyTableMenu
- XXX.world.inventory.CartographyTableMenu$1
+ XXX.world.inventory.CartographyTableMenu$2
- XXX.world.inventory.CartographyTableMenu$3
+ XXX.world.inventory.CartographyTableMenu$4
- XXX.world.inventory.CartographyTableMenu$5
+ XXX.world.inventory.ChestMenu
- XXX.world.inventory.ClickAction
+ XXX.world.inventory.ClickType
- XXX.world.inventory.ContainerData
+ XXX.world.inventory.ContainerLevelAccess
- XXX.world.inventory.ContainerLevelAccess$1
+ XXX.world.inventory.ContainerLevelAccess$2
- XXX.world.inventory.ContainerListener
+ XXX.world.inventory.ContainerSynchronizer
- XXX.world.inventory.CraftingContainer
+ XXX.world.inventory.CraftingMenu
- XXX.world.inventory.DataSlot
+ XXX.world.inventory.DataSlot$1
- XXX.world.inventory.DataSlot$2
+ XXX.world.inventory.DataSlot$3
- XXX.world.inventory.DispenserMenu
+ XXX.world.inventory.EnchantmentMenu
- XXX.world.inventory.EnchantmentMenu$1
+ XXX.world.inventory.EnchantmentMenu$2
- XXX.world.inventory.EnchantmentMenu$3
+ XXX.world.inventory.FurnaceFuelSlot
- XXX.world.inventory.FurnaceMenu
+ XXX.world.inventory.FurnaceResultSlot
- XXX.world.inventory.GrindstoneMenu
+ XXX.world.inventory.GrindstoneMenu$1
- XXX.world.inventory.GrindstoneMenu$2
+ XXX.world.inventory.GrindstoneMenu$3
- XXX.world.inventory.GrindstoneMenu$4
+ XXX.world.inventory.HopperMenu
- XXX.world.inventory.HorseInventoryMenu
+ XXX.world.inventory.HorseInventoryMenu$1
- XXX.world.inventory.HorseInventoryMenu$2
+ XXX.world.inventory.InventoryMenu
- XXX.world.inventory.InventoryMenu$1
+ XXX.world.inventory.InventoryMenu$2
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.LecternMenu
- XXX.world.inventory.LecternMenu$1
+ XXX.world.inventory.LoomMenu
- XXX.world.inventory.LoomMenu$1
+ XXX.world.inventory.LoomMenu$2
- XXX.world.inventory.LoomMenu$3
+ XXX.world.inventory.LoomMenu$4
- XXX.world.inventory.LoomMenu$5
+ XXX.world.inventory.LoomMenu$6
- XXX.world.inventory.MenuConstructor
+ XXX.world.inventory.MenuType
- XXX.world.inventory.MenuType$MenuSupplier
+ XXX.world.inventory.MerchantContainer
- XXX.world.inventory.MerchantMenu
+ XXX.world.inventory.MerchantResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SmithingMenu
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
- XXX.world.item.AdventureModeCheck
+ XXX.world.item.AirItem
- XXX.world.item.ArmorItem
+ XXX.world.item.ArmorItem$1
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterials
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BannerPatternItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.CompassItem
+ XXX.world.item.ComplexItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$1
- XXX.world.item.CreativeModeTab$10
+ XXX.world.item.CreativeModeTab$11
- XXX.world.item.CreativeModeTab$12
+ XXX.world.item.CreativeModeTab$2
- XXX.world.item.CreativeModeTab$3
+ XXX.world.item.CreativeModeTab$4
- XXX.world.item.CreativeModeTab$5
+ XXX.world.item.CreativeModeTab$6
- XXX.world.item.CreativeModeTab$7
+ XXX.world.item.CreativeModeTab$8
- XXX.world.item.CreativeModeTab$9
+ XXX.world.item.CrossbowItem
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeableArmorItem
- XXX.world.item.DyeableHorseArmorItem
+ XXX.world.item.DyeableLeatherItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.ElytraItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
- XXX.world.item.EnchantedGoldenAppleItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.HorseArmorItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$1
+ XXX.world.item.Item$Properties
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemFrameItem
+ XXX.world.item.ItemNameBlockItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.ItemUtils
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MapItem
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
- XXX.world.item.package-info
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignItem
+ XXX.world.item.SimpleFoiledItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.Tier
+ XXX.world.item.TieredItem
- XXX.world.item.Tiers
+ XXX.world.item.TippedArrowItem
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
- XXX.world.item.Vanishable
+ XXX.world.item.Wearable
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockCollisions
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ClipBlockStateContext
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$BooleanValue
+ XXX.world.level.GameRules$Category
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameRules$VisitorCaller
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.Level$1
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelHeightAccessor
+ XXX.world.level.LevelHeightAccessor$1
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelTimeAccess
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.LocalMobCapCalculator
- XXX.world.level.LocalMobCapCalculator$MobCounts
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
+ XXX.world.level.package-info
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SpawnData
+ XXX.world.level.SpawnData$CustomSpawnRules
- XXX.world.level.StructureManager
+ XXX.world.level.WorldGenLevel
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.scores.Objective
- XXX.world.scores.package-info
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.Score
- XXX.world.scores.Scoreboard
+ XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +2M
```
```
XXX.minecraft.client.Minecraft +1M | +1P
```
```
XXX.screens.multiplayer.Realms32bitWarningScreen +1P
```
```
XXX.client.multiplayer.ProfileKeyPairManager +1M
```
```
XXX.data.tags.TagsProvider +4M -5M | +1P -1P
```
```
XXX.data.worldgen.NoiseData +3M -3M
```
```
XXX.data.worldgen.Structures +1M -1M
```
```
XXX.worldgen.placement.PlacementUtils +1M -1M
```
```
XXX.network.chat.MessageSignature +1M
```
```
XXX.protocol.game.ServerGamePacketListener +1P
```
```
XXX.protocol.game.ServerboundChatPacket +2M -1M | +1P
```
```
XXX.server.commands.LocateCommand +19M -10M | +11P -2P
```
```
XXX.server.commands.ScheduleCommand +1M -1M
```
```
XXX.server.dedicated.DedicatedServer +2M | +1P
```
```
XXX.server.dedicated.DedicatedServerProperties +2P
```
```
XXX.server.network.ServerGamePacketListenerImpl +4M -2M | +1P
```
```
XXX.server.network.TextFilter$FilteredText +1M
```
```
XXX.server.players.PlayerList +6M -5M
```
```
XXX.world.damagesource.DamageSource +1M | -1P
```
```
XXX.world.entity.AnimationState +1M -1M | +1P
```
```
XXX.ai.behavior.GoToPotentialJobSite +1M -1M
```
```
XXX.ai.behavior.LocateHidingPlace +2M -2M
```
```
XXX.ai.behavior.ValidateNearbyPoi +1M -1M
```
```
XXX.ai.behavior.VillagerGoalPackages +4M
```
```
XXX.ai.behavior.YieldJobSite +1M -1M
```
```
XXX.behavior.warden.Roar +1P
```
```
XXX.behavior.warden.SonicBoom +3M -2M
```
```
XXX.ai.sensing.NearestBedSensor +2M -1M
```
```
XXX.village.poi.PoiRecord +4M -4M | +1P -1P
```
```
XXX.village.poi.PoiType +7M -19M | +1P -31P
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
- Object mapNullable(Object,Function,Object)
- Object mapNullable(Object,Function)
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- Realms32BitWarningStatus getRealms32BitWarningStatus()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ProfileKeyPairManager
</summary>

```diff
- ProfilePublicKey$Data parsePublicKey(KeyPairResponse)
```

</details>
<details>
<summary>
net.minecraft.data.tags.TagsProvider
</summary>

```diff
+ boolean lambda$run$0(Tag$BuilderEntry)
- boolean lambda$run$0(TagEntry)
+ Path getPath(ResourceLocation)
+ Tag$Builder getOrCreateRawBuilder(TagKey)
+ Tag$Builder lambda$getOrCreateRawBuilder$2(ResourceLocation)
- TagBuilder getOrCreateRawBuilder(TagKey)
- TagBuilder lambda$getOrCreateRawBuilder$2(ResourceLocation)
+ void lambda$run$1(CachedOutput,ResourceLocation,Tag$Builder)
- void lambda$run$1(CachedOutput,ResourceLocation,TagBuilder)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.NoiseData
</summary>

```diff
+ Holder bootstrap()
- Holder bootstrap(Registry)
- Holder register(Registry,ResourceKey,int,double,double[])
+ void register(ResourceKey,int,double,double[])
+ void registerBiomeNoises(int,ResourceKey,ResourceKey,ResourceKey,ResourceKey)
- void registerBiomeNoises(Registry,int,ResourceKey,ResourceKey,ResourceKey,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.Structures
</summary>

```diff
+ Holder bootstrap()
- Holder bootstrap(Registry)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.placement.PlacementUtils
</summary>

```diff
+ Holder bootstrap()
- Holder bootstrap(Registry)
```

</details>
<details>
<summary>
net.minecraft.network.chat.MessageSignature
</summary>

```diff
- boolean isValid()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundChatPacket
</summary>

```diff
- boolean signedPreview()
- void <init>(String,MessageSignature,boolean)
+ void <init>(String,MessageSignature)
```

</details>
<details>
<summary>
net.minecraft.server.commands.LocateCommand
</summary>

```diff
+ boolean lambda$register$2(CommandSourceStack)
- boolean lambda$register$6(CommandSourceStack)
+ CommandSyntaxException lambda$locate$6(ResourceOrTagLocationArgument$Result)
- CommandSyntaxException lambda$locateStructure$12(ResourceOrTagLocationArgument$Result)
- HolderSet$Direct lambda$getHolders$10(Holder)
+ HolderSet$Direct lambda$locate$4(Holder)
+ int lambda$register$3(CommandContext)
- int lambda$register$7(CommandContext)
- int lambda$register$8(CommandContext)
- int lambda$register$9(CommandContext)
+ int locate(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int locateBiome(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int locatePoi(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int locateStructure(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- Message lambda$static$2(Object)
- Message lambda$static$3(Object)
- Message lambda$static$4(Object)
- Message lambda$static$5(Object)
- Optional getHolders(ResourceOrTagLocationArgument$Result,Registry)
- Optional lambda$getHolders$11(Registry,ResourceKey)
+ Optional lambda$locate$5(Registry,ResourceKey)
- String lambda$showLocateResult$13(ResourceKey)
- String lambda$showLocateResult$14(ResourceKey)
- String lambda$showLocateResult$15(Pair,TagKey)
+ String lambda$showLocateResult$7(ResourceKey)
+ String lambda$showLocateResult$8(ResourceKey)
+ String lambda$showLocateResult$9(Pair,TagKey)
+ Style lambda$showLocateResult$10(BlockPos,String,Style)
- Style lambda$showLocateResult$16(BlockPos,String,Style)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ScheduleCommand
</summary>

```diff
- void lambda$schedule$8(ResourceLocation,boolean,TimerQueue,long,CommandSourceStack,int,Collection)
+ void lambda$schedule$8(ResourceLocation,boolean,TimerQueue,long,CommandSourceStack,int,Tag)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
- boolean previewsChat()
- ChatDecorator getChatDecorator()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
- void handleChatPreview(ServerboundChatPreviewPacket)
- void lambda$handleChatPreview$9(ServerboundChatPreviewPacket)
- void lambda$handlePlaceRecipe$10(ServerboundPlaceRecipePacket,Recipe)
+ void lambda$handlePlaceRecipe$9(ServerboundPlaceRecipePacket,Recipe)
+ void lambda$handleSignUpdate$10(ServerboundSignUpdatePacket,List)
- void lambda$handleSignUpdate$11(ServerboundSignUpdatePacket,List)
```

</details>
<details>
<summary>
net.minecraft.server.network.TextFilter$FilteredText
</summary>

```diff
- boolean isFiltered()
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
- PlayerChatMessage getFilteredMessage(ServerPlayer,PlayerChatMessage,TextFilter$FilteredText)
- PlayerChatMessage lambda$broadcastChatMessage$4(ServerPlayer,PlayerChatMessage,PlayerChatMessage,ServerPlayer)
- PlayerChatMessage lambda$broadcastChatMessage$5(PlayerChatMessage,ServerPlayer)
+ SignedMessage lambda$broadcastChatMessage$4(ServerPlayer,SignedMessage,SignedMessage,ServerPlayer)
+ SignedMessage lambda$broadcastChatMessage$5(SignedMessage,ServerPlayer)
- void broadcastChatMessage(PlayerChatMessage,ChatSender,ResourceKey)
- void broadcastChatMessage(PlayerChatMessage,Function,ChatSender,ResourceKey)
- void broadcastChatMessage(PlayerChatMessage,TextFilter$FilteredText,ServerPlayer,ResourceKey)
+ void broadcastChatMessage(SignedMessage,ChatSender,ResourceKey)
+ void broadcastChatMessage(SignedMessage,Function,ChatSender,ResourceKey)
+ void broadcastChatMessage(SignedMessage,TextFilter$FilteredText,ServerPlayer,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.damagesource.DamageSource
</summary>

```diff
- DamageSource sonicBoom(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.AnimationState
</summary>

```diff
+ void updateTime(boolean,float)
- void updateTime(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
</summary>

```diff
- boolean lambda$stop$1(Holder)
+ boolean lambda$stop$1(PoiType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.LocateHidingPlace
</summary>

```diff
- boolean lambda$checkExtraStartConditions$0(Holder)
+ boolean lambda$checkExtraStartConditions$0(PoiType)
- boolean lambda$start$2(Holder)
+ boolean lambda$start$2(PoiType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
</summary>

```diff
+ void <init>(PoiType,MemoryModuleType)
- void <init>(Predicate,MemoryModuleType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
</summary>

```diff
- boolean lambda$getCorePackage$0(Holder)
- boolean lambda$getCorePackage$1(Holder)
- boolean lambda$getMeetPackage$3(Holder)
- boolean lambda$getRestPackage$2(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.YieldJobSite
</summary>

```diff
- boolean nearbyWantsJobsite(Holder,Villager,BlockPos)
+ boolean nearbyWantsJobsite(PoiType,Villager,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.warden.SonicBoom
</summary>

```diff
+ boolean lambda$tick$0(Warden,LivingEntity)
- boolean lambda$tick$1(Warden,LivingEntity)
- void lambda$tick$0(Warden,LivingEntity)
+ void lambda$tick$1(Warden,ServerLevel,LivingEntity)
- void lambda$tick$2(Warden,ServerLevel,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.NearestBedSensor
</summary>

```diff
- boolean lambda$doTick$1(Holder)
+ boolean lambda$doTick$1(Long2LongMap$Entry)
- boolean lambda$doTick$2(Long2LongMap$Entry)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiRecord
</summary>

```diff
- Holder getPoiType()
- Holder lambda$codec$1(PoiRecord)
+ PoiType getPoiType()
+ PoiType lambda$codec$1(PoiRecord)
- void <init>(BlockPos,Holder,int,Runnable)
- void <init>(BlockPos,Holder,Runnable)
+ void <init>(BlockPos,PoiType,int,Runnable)
+ void <init>(BlockPos,PoiType,Runnable)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiType
</summary>

```diff
- boolean equals(Object)
+ boolean lambda$new$6(PoiType)
- boolean lambda$static$0(Holder)
+ boolean lambda$static$1(PoiType)
+ boolean lambda$static$2(PoiType)
+ boolean lambda$static$4(BlockState)
+ int getMaxTickets()
+ int getValidRange()
- int hashCode()
- int maxTickets()
- int validRange()
+ Optional forState(BlockState)
+ PoiType register(String,Set,int,int)
+ PoiType register(String,Set,int,Predicate,int)
+ PoiType registerBlockStates(PoiType)
+ Predicate getPredicate()
+ Set getBlockStates(Block)
+ Set lambda$static$0()
- Set matchingStates()
+ Stream lambda$static$3(Block)
+ Stream lambda$static$5(Block)
+ String getName()
- void <init>(Set,int,int)
+ void <init>(String,Set,int,int)
+ void <init>(String,Set,int,Predicate,int)
+ void lambda$registerBlockStates$7(PoiType,BlockState)
```

</details>
</details>
<hr/>