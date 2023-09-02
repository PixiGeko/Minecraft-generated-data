<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.16.5-rc1 ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.16.5-rc1</td></tr>
<tr><th>Type</th><td>releases-candidate</td></tr>
<tr><th>Release time</th><td>2021-01-13T15:58:55+00:00</td></tr>
<tr><th>SHA1</th><td>79b63085fb7b4805877ee719f6518ab3c87b3833</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/79b63085fb7b4805877ee719f6518ab3c87b3833/1.16.5-rc1.json">https://piston-meta.mojang.com/v1/packages/79b63085fb7b4805877ee719f6518ab3c87b3833/1.16.5-rc1.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json">https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/ae3acf34bb6e2d8cc4e11a1d52036cdea3ea980b/server.jar">https://piston-data.mojang.com/v1/objects/ae3acf34bb6e2d8cc4e11a1d52036cdea3ea980b/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/81d5c793695d8cde63afddb40dde88e3a88132ac/server.txt">https://piston-data.mojang.com/v1/objects/81d5c793695d8cde63afddb40dde88e3a88132ac/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/2b12e44073c724c6af2050ad3b6116f9c732feb1/client.jar">https://piston-data.mojang.com/v1/objects/2b12e44073c724c6af2050ad3b6116f9c732feb1/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/e3dfb0001e1079a1af72ee21517330edf52e6192/client.txt">https://piston-data.mojang.com/v1/objects/e3dfb0001e1079a1af72ee21517330edf52e6192/client.txt</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/20w51a">20w51a</a>
## File structure

<details><summary>data/</summary>

```diff
-  minecraft/advancements/recipes/building_blocks/amethyst_block.json
-  minecraft/advancements/recipes/building_blocks/copper_block.json
-  minecraft/advancements/recipes/building_blocks/cut_copper.json
-  minecraft/advancements/recipes/building_blocks/cut_copper_slab.json
-  minecraft/advancements/recipes/building_blocks/cut_copper_stairs.json
-  minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper.json
-  minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper_slab.json
-  minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper_stairs.json
-  minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper.json
-  minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper_slab.json
-  minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper_stairs.json
-  minecraft/advancements/recipes/building_blocks/tinted_glass.json
-  minecraft/advancements/recipes/building_blocks/waxed_copper.json
-  minecraft/advancements/recipes/building_blocks/waxed_copper_cut_slab_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/waxed_copper_cut_stairs_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_waxed_block.json
-  minecraft/advancements/recipes/building_blocks/waxed_cut_copper_slab.json
-  minecraft/advancements/recipes/building_blocks/waxed_cut_copper_stairs.json
-  minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_copper.json
-  minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_waxed_block.json
-  minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab.json
-  minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs.json
-  minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_copper.json
-  minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_from_waxed_block.json
-  minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab.json
-  minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs.json
-  minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
-  minecraft/advancements/recipes/building_blocks/weathered_cut_copper.json
-  minecraft/advancements/recipes/building_blocks/weathered_cut_copper_slab.json
-  minecraft/advancements/recipes/building_blocks/weathered_cut_copper_stairs.json
-  minecraft/advancements/recipes/decorations/black_candle.json
-  minecraft/advancements/recipes/decorations/blue_candle.json
-  minecraft/advancements/recipes/decorations/brown_candle.json
-  minecraft/advancements/recipes/decorations/candle.json
-  minecraft/advancements/recipes/decorations/cyan_candle.json
-  minecraft/advancements/recipes/decorations/gray_candle.json
-  minecraft/advancements/recipes/decorations/green_candle.json
-  minecraft/advancements/recipes/decorations/light_blue_candle.json
-  minecraft/advancements/recipes/decorations/light_gray_candle.json
-  minecraft/advancements/recipes/decorations/lime_candle.json
-  minecraft/advancements/recipes/decorations/magenta_candle.json
-  minecraft/advancements/recipes/decorations/orange_candle.json
-  minecraft/advancements/recipes/decorations/pink_candle.json
-  minecraft/advancements/recipes/decorations/purple_candle.json
-  minecraft/advancements/recipes/decorations/red_candle.json
-  minecraft/advancements/recipes/decorations/white_candle.json
-  minecraft/advancements/recipes/decorations/yellow_candle.json
-  minecraft/advancements/recipes/misc/copper_ingot.json
-  minecraft/advancements/recipes/misc/copper_ingot_from_blasting.json
-  minecraft/advancements/recipes/misc/copper_ingot_from_copper_block.json
-  minecraft/advancements/recipes/misc/firework_rocket_simple.json
-  minecraft/advancements/recipes/redstone/lightning_rod.json
-  minecraft/advancements/recipes/tools/bundle.json
-  minecraft/advancements/recipes/tools/spyglass.json
-  minecraft/loot_tables/blocks/amethyst_block.json
-  minecraft/loot_tables/blocks/amethyst_cluster.json
-  minecraft/loot_tables/blocks/black_candle.json
-  minecraft/loot_tables/blocks/black_candle_cake.json
-  minecraft/loot_tables/blocks/blue_candle.json
-  minecraft/loot_tables/blocks/blue_candle_cake.json
-  minecraft/loot_tables/blocks/brown_candle.json
-  minecraft/loot_tables/blocks/brown_candle_cake.json
-  minecraft/loot_tables/blocks/budding_amethyst.json
-  minecraft/loot_tables/blocks/calcite.json
-  minecraft/loot_tables/blocks/candle.json
-  minecraft/loot_tables/blocks/candle_cake.json
-  minecraft/loot_tables/blocks/copper_block.json
-  minecraft/loot_tables/blocks/copper_ore.json
-  minecraft/loot_tables/blocks/cut_copper.json
-  minecraft/loot_tables/blocks/cut_copper_slab.json
-  minecraft/loot_tables/blocks/cut_copper_stairs.json
-  minecraft/loot_tables/blocks/cyan_candle.json
-  minecraft/loot_tables/blocks/cyan_candle_cake.json
-  minecraft/loot_tables/blocks/dirt_path.json
-  minecraft/loot_tables/blocks/dripstone_block.json
+  minecraft/loot_tables/blocks/grass_path.json
-  minecraft/loot_tables/blocks/gray_candle.json
-  minecraft/loot_tables/blocks/gray_candle_cake.json
-  minecraft/loot_tables/blocks/green_candle.json
-  minecraft/loot_tables/blocks/green_candle_cake.json
-  minecraft/loot_tables/blocks/large_amethyst_bud.json
-  minecraft/loot_tables/blocks/lava_cauldron.json
-  minecraft/loot_tables/blocks/light_blue_candle.json
-  minecraft/loot_tables/blocks/light_blue_candle_cake.json
-  minecraft/loot_tables/blocks/light_gray_candle.json
-  minecraft/loot_tables/blocks/light_gray_candle_cake.json
-  minecraft/loot_tables/blocks/lightly_weathered_copper_block.json
-  minecraft/loot_tables/blocks/lightly_weathered_cut_copper.json
-  minecraft/loot_tables/blocks/lightly_weathered_cut_copper_slab.json
-  minecraft/loot_tables/blocks/lightly_weathered_cut_copper_stairs.json
-  minecraft/loot_tables/blocks/lightning_rod.json
-  minecraft/loot_tables/blocks/lime_candle.json
-  minecraft/loot_tables/blocks/lime_candle_cake.json
-  minecraft/loot_tables/blocks/magenta_candle.json
-  minecraft/loot_tables/blocks/magenta_candle_cake.json
-  minecraft/loot_tables/blocks/medium_amethyst_bud.json
-  minecraft/loot_tables/blocks/orange_candle.json
-  minecraft/loot_tables/blocks/orange_candle_cake.json
-  minecraft/loot_tables/blocks/pink_candle.json
-  minecraft/loot_tables/blocks/pink_candle_cake.json
-  minecraft/loot_tables/blocks/pointed_dripstone.json
-  minecraft/loot_tables/blocks/powder_snow.json
-  minecraft/loot_tables/blocks/powder_snow_cauldron.json
-  minecraft/loot_tables/blocks/purple_candle.json
-  minecraft/loot_tables/blocks/purple_candle_cake.json
-  minecraft/loot_tables/blocks/red_candle.json
-  minecraft/loot_tables/blocks/red_candle_cake.json
-  minecraft/loot_tables/blocks/sculk_sensor.json
-  minecraft/loot_tables/blocks/semi_weathered_copper_block.json
-  minecraft/loot_tables/blocks/semi_weathered_cut_copper.json
-  minecraft/loot_tables/blocks/semi_weathered_cut_copper_slab.json
-  minecraft/loot_tables/blocks/semi_weathered_cut_copper_stairs.json
-  minecraft/loot_tables/blocks/small_amethyst_bud.json
-  minecraft/loot_tables/blocks/tinted_glass.json
-  minecraft/loot_tables/blocks/tuff.json
-  minecraft/loot_tables/blocks/water_cauldron.json
-  minecraft/loot_tables/blocks/waxed_copper.json
-  minecraft/loot_tables/blocks/waxed_cut_copper.json
-  minecraft/loot_tables/blocks/waxed_cut_copper_slab.json
-  minecraft/loot_tables/blocks/waxed_cut_copper_stairs.json
-  minecraft/loot_tables/blocks/waxed_lightly_weathered_copper.json
-  minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper.json
-  minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper_slab.json
-  minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper_stairs.json
-  minecraft/loot_tables/blocks/waxed_semi_weathered_copper.json
-  minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper.json
-  minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper_slab.json
-  minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper_stairs.json
-  minecraft/loot_tables/blocks/weathered_copper_block.json
-  minecraft/loot_tables/blocks/weathered_cut_copper.json
-  minecraft/loot_tables/blocks/weathered_cut_copper_slab.json
-  minecraft/loot_tables/blocks/weathered_cut_copper_stairs.json
-  minecraft/loot_tables/blocks/white_candle.json
-  minecraft/loot_tables/blocks/white_candle_cake.json
-  minecraft/loot_tables/blocks/yellow_candle.json
-  minecraft/loot_tables/blocks/yellow_candle_cake.json
-  minecraft/loot_tables/entities/axolotl.json
-  minecraft/recipes/amethyst_block.json
-  minecraft/recipes/black_candle.json
-  minecraft/recipes/blue_candle.json
-  minecraft/recipes/brown_candle.json
-  minecraft/recipes/bundle.json
-  minecraft/recipes/candle.json
-  minecraft/recipes/copper_block.json
-  minecraft/recipes/copper_ingot.json
-  minecraft/recipes/copper_ingot_from_blasting.json
-  minecraft/recipes/copper_ingot_from_copper_block.json
-  minecraft/recipes/cut_copper.json
-  minecraft/recipes/cut_copper_slab.json
-  minecraft/recipes/cut_copper_stairs.json
-  minecraft/recipes/cyan_candle.json
-  minecraft/recipes/firework_rocket_simple.json
-  minecraft/recipes/gray_candle.json
-  minecraft/recipes/green_candle.json
-  minecraft/recipes/light_blue_candle.json
-  minecraft/recipes/light_gray_candle.json
-  minecraft/recipes/lightly_weathered_cut_copper.json
-  minecraft/recipes/lightly_weathered_cut_copper_slab.json
-  minecraft/recipes/lightly_weathered_cut_copper_stairs.json
-  minecraft/recipes/lightning_rod.json
-  minecraft/recipes/lime_candle.json
-  minecraft/recipes/magenta_candle.json
-  minecraft/recipes/orange_candle.json
-  minecraft/recipes/pink_candle.json
-  minecraft/recipes/purple_candle.json
-  minecraft/recipes/red_candle.json
-  minecraft/recipes/semi_weathered_cut_copper.json
-  minecraft/recipes/semi_weathered_cut_copper_slab.json
-  minecraft/recipes/semi_weathered_cut_copper_stairs.json
-  minecraft/recipes/spyglass.json
-  minecraft/recipes/tinted_glass.json
-  minecraft/recipes/waxed_copper.json
-  minecraft/recipes/waxed_copper_cut_slab_from_honeycomb.json
-  minecraft/recipes/waxed_copper_cut_stairs_from_honeycomb.json
-  minecraft/recipes/waxed_cut_copper_from_honeycomb.json
-  minecraft/recipes/waxed_cut_copper_from_waxed_block.json
-  minecraft/recipes/waxed_cut_copper_slab.json
-  minecraft/recipes/waxed_cut_copper_stairs.json
-  minecraft/recipes/waxed_lightly_weathered_copper.json
-  minecraft/recipes/waxed_lightly_weathered_cut_copper_from_honeycomb.json
-  minecraft/recipes/waxed_lightly_weathered_cut_copper_from_waxed_block.json
-  minecraft/recipes/waxed_lightly_weathered_cut_copper_slab.json
-  minecraft/recipes/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
-  minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs.json
-  minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
-  minecraft/recipes/waxed_semi_weathered_copper.json
-  minecraft/recipes/waxed_semi_weathered_cut_copper_from_honeycomb.json
-  minecraft/recipes/waxed_semi_weathered_cut_copper_from_waxed_block.json
-  minecraft/recipes/waxed_semi_weathered_cut_copper_slab.json
-  minecraft/recipes/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
-  minecraft/recipes/waxed_semi_weathered_cut_copper_stairs.json
-  minecraft/recipes/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
-  minecraft/recipes/weathered_cut_copper.json
-  minecraft/recipes/weathered_cut_copper_slab.json
-  minecraft/recipes/weathered_cut_copper_stairs.json
-  minecraft/recipes/white_candle.json
-  minecraft/recipes/yellow_candle.json
-  minecraft/tags/blocks/candle_cakes.json
-  minecraft/tags/blocks/candles.json
-  minecraft/tags/blocks/cauldrons.json
-  minecraft/tags/blocks/crystal_sound_blocks.json
-  minecraft/tags/blocks/dripstone_replaceable_blocks.json
-  minecraft/tags/blocks/inside_step_sound_blocks.json
-  minecraft/tags/blocks/occludes_vibration_signals.json
-  minecraft/tags/entity_types/axolotl_always_hostiles.json
-  minecraft/tags/entity_types/axolotl_tempted_hostiles.json
-  minecraft/tags/entity_types/powder_snow_walkable_mobs.json
-  minecraft/tags/game_events
-  minecraft/tags/game_events/ignore_vibrations_stepping_carefully.json
-  minecraft/tags/game_events/vibrations.json
-  minecraft/tags/items/axolotl_tempt_items.json
-  minecraft/tags/items/candles.json
-  minecraft/tags/items/freeze_immune_wearables.json
-  minecraft/tags/items/ignored_by_piglin_babies.json
-  minecraft/tags/items/occludes_vibration_signals.json
-  minecraft/tags/items/piglin_food.json
```

</details>

<details><summary>assets/</summary>

```diff
-  minecraft/blockstates/amethyst_block.json
-  minecraft/blockstates/amethyst_cluster.json
-  minecraft/blockstates/black_candle.json
-  minecraft/blockstates/black_candle_cake.json
-  minecraft/blockstates/blue_candle.json
-  minecraft/blockstates/blue_candle_cake.json
-  minecraft/blockstates/brown_candle.json
-  minecraft/blockstates/brown_candle_cake.json
-  minecraft/blockstates/budding_amethyst.json
-  minecraft/blockstates/calcite.json
-  minecraft/blockstates/candle.json
-  minecraft/blockstates/candle_cake.json
-  minecraft/blockstates/copper_block.json
-  minecraft/blockstates/copper_ore.json
-  minecraft/blockstates/cut_copper.json
-  minecraft/blockstates/cut_copper_slab.json
-  minecraft/blockstates/cut_copper_stairs.json
-  minecraft/blockstates/cyan_candle.json
-  minecraft/blockstates/cyan_candle_cake.json
-  minecraft/blockstates/dirt_path.json
-  minecraft/blockstates/dripstone_block.json
+  minecraft/blockstates/grass_path.json
-  minecraft/blockstates/gray_candle.json
-  minecraft/blockstates/gray_candle_cake.json
-  minecraft/blockstates/green_candle.json
-  minecraft/blockstates/green_candle_cake.json
-  minecraft/blockstates/large_amethyst_bud.json
-  minecraft/blockstates/lava_cauldron.json
-  minecraft/blockstates/light_blue_candle.json
-  minecraft/blockstates/light_blue_candle_cake.json
-  minecraft/blockstates/light_gray_candle.json
-  minecraft/blockstates/light_gray_candle_cake.json
-  minecraft/blockstates/lightly_weathered_copper_block.json
-  minecraft/blockstates/lightly_weathered_cut_copper.json
-  minecraft/blockstates/lightly_weathered_cut_copper_slab.json
-  minecraft/blockstates/lightly_weathered_cut_copper_stairs.json
-  minecraft/blockstates/lightning_rod.json
-  minecraft/blockstates/lime_candle.json
-  minecraft/blockstates/lime_candle_cake.json
-  minecraft/blockstates/magenta_candle.json
-  minecraft/blockstates/magenta_candle_cake.json
-  minecraft/blockstates/medium_amethyst_bud.json
-  minecraft/blockstates/orange_candle.json
-  minecraft/blockstates/orange_candle_cake.json
-  minecraft/blockstates/pink_candle.json
-  minecraft/blockstates/pink_candle_cake.json
-  minecraft/blockstates/pointed_dripstone.json
-  minecraft/blockstates/powder_snow.json
-  minecraft/blockstates/powder_snow_cauldron.json
-  minecraft/blockstates/purple_candle.json
-  minecraft/blockstates/purple_candle_cake.json
-  minecraft/blockstates/red_candle.json
-  minecraft/blockstates/red_candle_cake.json
-  minecraft/blockstates/sculk_sensor.json
-  minecraft/blockstates/semi_weathered_copper_block.json
-  minecraft/blockstates/semi_weathered_cut_copper.json
-  minecraft/blockstates/semi_weathered_cut_copper_slab.json
-  minecraft/blockstates/semi_weathered_cut_copper_stairs.json
-  minecraft/blockstates/small_amethyst_bud.json
-  minecraft/blockstates/tinted_glass.json
-  minecraft/blockstates/tuff.json
-  minecraft/blockstates/water_cauldron.json
-  minecraft/blockstates/waxed_copper.json
-  minecraft/blockstates/waxed_cut_copper.json
-  minecraft/blockstates/waxed_cut_copper_slab.json
-  minecraft/blockstates/waxed_cut_copper_stairs.json
-  minecraft/blockstates/waxed_lightly_weathered_copper.json
-  minecraft/blockstates/waxed_lightly_weathered_cut_copper.json
-  minecraft/blockstates/waxed_lightly_weathered_cut_copper_slab.json
-  minecraft/blockstates/waxed_lightly_weathered_cut_copper_stairs.json
-  minecraft/blockstates/waxed_semi_weathered_copper.json
-  minecraft/blockstates/waxed_semi_weathered_cut_copper.json
-  minecraft/blockstates/waxed_semi_weathered_cut_copper_slab.json
-  minecraft/blockstates/waxed_semi_weathered_cut_copper_stairs.json
-  minecraft/blockstates/weathered_copper_block.json
-  minecraft/blockstates/weathered_cut_copper.json
-  minecraft/blockstates/weathered_cut_copper_slab.json
-  minecraft/blockstates/weathered_cut_copper_stairs.json
-  minecraft/blockstates/white_candle.json
-  minecraft/blockstates/white_candle_cake.json
-  minecraft/blockstates/yellow_candle.json
-  minecraft/blockstates/yellow_candle_cake.json
-  minecraft/models/block/amethyst_block.json
-  minecraft/models/block/amethyst_cluster.json
-  minecraft/models/block/black_candle_cake.json
-  minecraft/models/block/black_candle_four_candles.json
-  minecraft/models/block/black_candle_one_candle.json
-  minecraft/models/block/black_candle_three_candles.json
-  minecraft/models/block/black_candle_two_candles.json
-  minecraft/models/block/blue_candle_cake.json
-  minecraft/models/block/blue_candle_four_candles.json
-  minecraft/models/block/blue_candle_one_candle.json
-  minecraft/models/block/blue_candle_three_candles.json
-  minecraft/models/block/blue_candle_two_candles.json
-  minecraft/models/block/brown_candle_cake.json
-  minecraft/models/block/brown_candle_four_candles.json
-  minecraft/models/block/brown_candle_one_candle.json
-  minecraft/models/block/brown_candle_three_candles.json
-  minecraft/models/block/brown_candle_two_candles.json
-  minecraft/models/block/budding_amethyst.json
-  minecraft/models/block/calcite.json
-  minecraft/models/block/candle_cake.json
-  minecraft/models/block/candle_four_candles.json
-  minecraft/models/block/candle_one_candle.json
-  minecraft/models/block/candle_three_candles.json
-  minecraft/models/block/candle_two_candles.json
+  minecraft/models/block/cauldron_level1.json
+  minecraft/models/block/cauldron_level2.json
+  minecraft/models/block/cauldron_level3.json
-  minecraft/models/block/copper_block.json
-  minecraft/models/block/copper_ore.json
-  minecraft/models/block/cut_copper.json
-  minecraft/models/block/cut_copper_slab.json
-  minecraft/models/block/cut_copper_slab_top.json
-  minecraft/models/block/cut_copper_stairs.json
-  minecraft/models/block/cut_copper_stairs_inner.json
-  minecraft/models/block/cut_copper_stairs_outer.json
-  minecraft/models/block/cyan_candle_cake.json
-  minecraft/models/block/cyan_candle_four_candles.json
-  minecraft/models/block/cyan_candle_one_candle.json
-  minecraft/models/block/cyan_candle_three_candles.json
-  minecraft/models/block/cyan_candle_two_candles.json
-  minecraft/models/block/dirt_path.json
-  minecraft/models/block/dripstone_block.json
+  minecraft/models/block/grass_path.json
-  minecraft/models/block/gray_candle_cake.json
-  minecraft/models/block/gray_candle_four_candles.json
-  minecraft/models/block/gray_candle_one_candle.json
-  minecraft/models/block/gray_candle_three_candles.json
-  minecraft/models/block/gray_candle_two_candles.json
-  minecraft/models/block/green_candle_cake.json
-  minecraft/models/block/green_candle_four_candles.json
-  minecraft/models/block/green_candle_one_candle.json
-  minecraft/models/block/green_candle_three_candles.json
-  minecraft/models/block/green_candle_two_candles.json
-  minecraft/models/block/large_amethyst_bud.json
-  minecraft/models/block/lava_cauldron.json
-  minecraft/models/block/light_blue_candle_cake.json
-  minecraft/models/block/light_blue_candle_four_candles.json
-  minecraft/models/block/light_blue_candle_one_candle.json
-  minecraft/models/block/light_blue_candle_three_candles.json
-  minecraft/models/block/light_blue_candle_two_candles.json
-  minecraft/models/block/light_gray_candle_cake.json
-  minecraft/models/block/light_gray_candle_four_candles.json
-  minecraft/models/block/light_gray_candle_one_candle.json
-  minecraft/models/block/light_gray_candle_three_candles.json
-  minecraft/models/block/light_gray_candle_two_candles.json
-  minecraft/models/block/lightly_weathered_copper_block.json
-  minecraft/models/block/lightly_weathered_cut_copper.json
-  minecraft/models/block/lightly_weathered_cut_copper_slab.json
-  minecraft/models/block/lightly_weathered_cut_copper_slab_top.json
-  minecraft/models/block/lightly_weathered_cut_copper_stairs.json
-  minecraft/models/block/lightly_weathered_cut_copper_stairs_inner.json
-  minecraft/models/block/lightly_weathered_cut_copper_stairs_outer.json
-  minecraft/models/block/lightning_rod.json
-  minecraft/models/block/lime_candle_cake.json
-  minecraft/models/block/lime_candle_four_candles.json
-  minecraft/models/block/lime_candle_one_candle.json
-  minecraft/models/block/lime_candle_three_candles.json
-  minecraft/models/block/lime_candle_two_candles.json
-  minecraft/models/block/magenta_candle_cake.json
-  minecraft/models/block/magenta_candle_four_candles.json
-  minecraft/models/block/magenta_candle_one_candle.json
-  minecraft/models/block/magenta_candle_three_candles.json
-  minecraft/models/block/magenta_candle_two_candles.json
-  minecraft/models/block/medium_amethyst_bud.json
-  minecraft/models/block/orange_candle_cake.json
-  minecraft/models/block/orange_candle_four_candles.json
-  minecraft/models/block/orange_candle_one_candle.json
-  minecraft/models/block/orange_candle_three_candles.json
-  minecraft/models/block/orange_candle_two_candles.json
-  minecraft/models/block/pink_candle_cake.json
-  minecraft/models/block/pink_candle_four_candles.json
-  minecraft/models/block/pink_candle_one_candle.json
-  minecraft/models/block/pink_candle_three_candles.json
-  minecraft/models/block/pink_candle_two_candles.json
-  minecraft/models/block/pointed_dripstone.json
-  minecraft/models/block/pointed_dripstone_down_base.json
-  minecraft/models/block/pointed_dripstone_down_frustum.json
-  minecraft/models/block/pointed_dripstone_down_middle.json
-  minecraft/models/block/pointed_dripstone_down_tip.json
-  minecraft/models/block/pointed_dripstone_down_tip_merge.json
-  minecraft/models/block/pointed_dripstone_up_base.json
-  minecraft/models/block/pointed_dripstone_up_frustum.json
-  minecraft/models/block/pointed_dripstone_up_middle.json
-  minecraft/models/block/pointed_dripstone_up_tip.json
-  minecraft/models/block/pointed_dripstone_up_tip_merge.json
-  minecraft/models/block/powder_snow.json
-  minecraft/models/block/powder_snow_cauldron_full.json
-  minecraft/models/block/powder_snow_cauldron_level1.json
-  minecraft/models/block/powder_snow_cauldron_level2.json
-  minecraft/models/block/purple_candle_cake.json
-  minecraft/models/block/purple_candle_four_candles.json
-  minecraft/models/block/purple_candle_one_candle.json
-  minecraft/models/block/purple_candle_three_candles.json
-  minecraft/models/block/purple_candle_two_candles.json
-  minecraft/models/block/red_candle_cake.json
-  minecraft/models/block/red_candle_four_candles.json
-  minecraft/models/block/red_candle_one_candle.json
-  minecraft/models/block/red_candle_three_candles.json
-  minecraft/models/block/red_candle_two_candles.json
-  minecraft/models/block/sculk_sensor.json
-  minecraft/models/block/sculk_sensor_active.json
-  minecraft/models/block/sculk_sensor_inactive.json
-  minecraft/models/block/semi_weathered_copper_block.json
-  minecraft/models/block/semi_weathered_cut_copper.json
-  minecraft/models/block/semi_weathered_cut_copper_slab.json
-  minecraft/models/block/semi_weathered_cut_copper_slab_top.json
-  minecraft/models/block/semi_weathered_cut_copper_stairs.json
-  minecraft/models/block/semi_weathered_cut_copper_stairs_inner.json
-  minecraft/models/block/semi_weathered_cut_copper_stairs_outer.json
-  minecraft/models/block/small_amethyst_bud.json
-  minecraft/models/block/template_cake_with_candle.json
-  minecraft/models/block/template_candle.json
-  minecraft/models/block/template_cauldron_full.json
-  minecraft/models/block/template_cauldron_level1.json
-  minecraft/models/block/template_cauldron_level2.json
-  minecraft/models/block/template_four_candles.json
-  minecraft/models/block/template_three_candles.json
-  minecraft/models/block/template_two_candles.json
-  minecraft/models/block/tinted_glass.json
-  minecraft/models/block/tuff.json
-  minecraft/models/block/water_cauldron_full.json
-  minecraft/models/block/water_cauldron_level1.json
-  minecraft/models/block/water_cauldron_level2.json
-  minecraft/models/block/weathered_copper_block.json
-  minecraft/models/block/weathered_cut_copper.json
-  minecraft/models/block/weathered_cut_copper_slab.json
-  minecraft/models/block/weathered_cut_copper_slab_top.json
-  minecraft/models/block/weathered_cut_copper_stairs.json
-  minecraft/models/block/weathered_cut_copper_stairs_inner.json
-  minecraft/models/block/weathered_cut_copper_stairs_outer.json
-  minecraft/models/block/white_candle_cake.json
-  minecraft/models/block/white_candle_four_candles.json
-  minecraft/models/block/white_candle_one_candle.json
-  minecraft/models/block/white_candle_three_candles.json
-  minecraft/models/block/white_candle_two_candles.json
-  minecraft/models/block/yellow_candle_cake.json
-  minecraft/models/block/yellow_candle_four_candles.json
-  minecraft/models/block/yellow_candle_one_candle.json
-  minecraft/models/block/yellow_candle_three_candles.json
-  minecraft/models/block/yellow_candle_two_candles.json
-  minecraft/models/item/amethyst_block.json
-  minecraft/models/item/amethyst_cluster.json
-  minecraft/models/item/amethyst_shard.json
-  minecraft/models/item/axolotl_bucket.json
-  minecraft/models/item/axolotl_spawn_egg.json
-  minecraft/models/item/black_candle.json
-  minecraft/models/item/blue_candle.json
-  minecraft/models/item/brown_candle.json
-  minecraft/models/item/budding_amethyst.json
-  minecraft/models/item/bundle.json
-  minecraft/models/item/bundle_filled.json
-  minecraft/models/item/calcite.json
-  minecraft/models/item/candle.json
-  minecraft/models/item/copper_block.json
-  minecraft/models/item/copper_ingot.json
-  minecraft/models/item/copper_ore.json
-  minecraft/models/item/cut_copper.json
-  minecraft/models/item/cut_copper_slab.json
-  minecraft/models/item/cut_copper_stairs.json
-  minecraft/models/item/cyan_candle.json
-  minecraft/models/item/dirt_path.json
-  minecraft/models/item/dripstone_block.json
+  minecraft/models/item/grass_path.json
-  minecraft/models/item/gray_candle.json
-  minecraft/models/item/green_candle.json
-  minecraft/models/item/large_amethyst_bud.json
-  minecraft/models/item/light_blue_candle.json
-  minecraft/models/item/light_gray_candle.json
-  minecraft/models/item/lightly_weathered_copper_block.json
-  minecraft/models/item/lightly_weathered_cut_copper.json
-  minecraft/models/item/lightly_weathered_cut_copper_slab.json
-  minecraft/models/item/lightly_weathered_cut_copper_stairs.json
-  minecraft/models/item/lightning_rod.json
-  minecraft/models/item/lime_candle.json
-  minecraft/models/item/magenta_candle.json
-  minecraft/models/item/medium_amethyst_bud.json
-  minecraft/models/item/orange_candle.json
-  minecraft/models/item/pink_candle.json
-  minecraft/models/item/pointed_dripstone.json
-  minecraft/models/item/powder_snow_bucket.json
-  minecraft/models/item/purple_candle.json
-  minecraft/models/item/red_candle.json
-  minecraft/models/item/sculk_sensor.json
-  minecraft/models/item/semi_weathered_copper_block.json
-  minecraft/models/item/semi_weathered_cut_copper.json
-  minecraft/models/item/semi_weathered_cut_copper_slab.json
-  minecraft/models/item/semi_weathered_cut_copper_stairs.json
-  minecraft/models/item/small_amethyst_bud.json
-  minecraft/models/item/spyglass.json
-  minecraft/models/item/tinted_glass.json
-  minecraft/models/item/tuff.json
-  minecraft/models/item/waxed_copper.json
-  minecraft/models/item/waxed_cut_copper.json
-  minecraft/models/item/waxed_cut_copper_slab.json
-  minecraft/models/item/waxed_cut_copper_stairs.json
-  minecraft/models/item/waxed_lightly_weathered_copper.json
-  minecraft/models/item/waxed_lightly_weathered_cut_copper.json
-  minecraft/models/item/waxed_lightly_weathered_cut_copper_slab.json
-  minecraft/models/item/waxed_lightly_weathered_cut_copper_stairs.json
-  minecraft/models/item/waxed_semi_weathered_copper.json
-  minecraft/models/item/waxed_semi_weathered_cut_copper.json
-  minecraft/models/item/waxed_semi_weathered_cut_copper_slab.json
-  minecraft/models/item/waxed_semi_weathered_cut_copper_stairs.json
-  minecraft/models/item/weathered_copper_block.json
-  minecraft/models/item/weathered_cut_copper.json
-  minecraft/models/item/weathered_cut_copper_slab.json
-  minecraft/models/item/weathered_cut_copper_stairs.json
-  minecraft/models/item/white_candle.json
-  minecraft/models/item/yellow_candle.json
-  minecraft/particles/dripping_dripstone_lava.json
-  minecraft/particles/dripping_dripstone_water.json
-  minecraft/particles/dust_color_transition.json
-  minecraft/particles/falling_dripstone_lava.json
-  minecraft/particles/falling_dripstone_water.json
-  minecraft/particles/small_flame.json
-  minecraft/particles/snowflake.json
-  minecraft/particles/vibration.json
-  minecraft/textures/block/amethyst_block.png
-  minecraft/textures/block/amethyst_cluster.png
-  minecraft/textures/block/black_candle.png
-  minecraft/textures/block/blue_candle.png
-  minecraft/textures/block/brown_candle.png
-  minecraft/textures/block/budding_amethyst.png
-  minecraft/textures/block/calcite.png
-  minecraft/textures/block/calibrated_sculk_sensor_side.png
-  minecraft/textures/block/calibrated_sculk_sensor_top.png
-  minecraft/textures/block/candle.png
-  minecraft/textures/block/copper_block.png
-  minecraft/textures/block/copper_ore.png
-  minecraft/textures/block/cut_copper.png
-  minecraft/textures/block/cyan_candle.png
-  minecraft/textures/block/dirt_path_side.png
-  minecraft/textures/block/dirt_path_top.png
-  minecraft/textures/block/dripstone_block.png
+  minecraft/textures/block/grass_path_side.png
+  minecraft/textures/block/grass_path_top.png
-  minecraft/textures/block/gray_candle.png
-  minecraft/textures/block/green_candle.png
-  minecraft/textures/block/large_amethyst_bud.png
-  minecraft/textures/block/light_blue_candle.png
-  minecraft/textures/block/light_gray_candle.png
-  minecraft/textures/block/lightly_weathered_copper_block.png
-  minecraft/textures/block/lightly_weathered_cut_copper.png
-  minecraft/textures/block/lightning_rod.png
-  minecraft/textures/block/lime_candle.png
-  minecraft/textures/block/magenta_candle.png
-  minecraft/textures/block/medium_amethyst_bud.png
-  minecraft/textures/block/orange_candle.png
-  minecraft/textures/block/pink_candle.png
-  minecraft/textures/block/pointed_dripstone_down_base.png
-  minecraft/textures/block/pointed_dripstone_down_frustum.png
-  minecraft/textures/block/pointed_dripstone_down_middle.png
-  minecraft/textures/block/pointed_dripstone_down_tip.png
-  minecraft/textures/block/pointed_dripstone_down_tip_merge.png
-  minecraft/textures/block/pointed_dripstone_up_base.png
-  minecraft/textures/block/pointed_dripstone_up_frustum.png
-  minecraft/textures/block/pointed_dripstone_up_middle.png
-  minecraft/textures/block/pointed_dripstone_up_tip.png
-  minecraft/textures/block/pointed_dripstone_up_tip_merge.png
-  minecraft/textures/block/powder_snow.png
-  minecraft/textures/block/purple_candle.png
-  minecraft/textures/block/red_candle.png
-  minecraft/textures/block/sculk_sensor_bottom.png
-  minecraft/textures/block/sculk_sensor_side.png
-  minecraft/textures/block/sculk_sensor_tendril_active.png
-  minecraft/textures/block/sculk_sensor_tendril_active.png.mcmeta
-  minecraft/textures/block/sculk_sensor_tendril_inactive.png
-  minecraft/textures/block/sculk_sensor_tendril_inactive.png.mcmeta
-  minecraft/textures/block/sculk_sensor_top.png
-  minecraft/textures/block/semi_weathered_copper_block.png
-  minecraft/textures/block/semi_weathered_cut_copper.png
-  minecraft/textures/block/small_amethyst_bud.png
-  minecraft/textures/block/tinted_glass.png
-  minecraft/textures/block/tuff.png
-  minecraft/textures/block/weathered_copper_block.png
-  minecraft/textures/block/weathered_cut_copper.png
-  minecraft/textures/block/white_candle.png
-  minecraft/textures/block/yellow_candle.png
-  minecraft/textures/entity/axolotl
-  minecraft/textures/entity/axolotl/axolotl_blue.png
-  minecraft/textures/entity/axolotl/axolotl_cyan.png
-  minecraft/textures/entity/axolotl/axolotl_gold.png
-  minecraft/textures/entity/axolotl/axolotl_lucy.png
-  minecraft/textures/entity/axolotl/axolotl_wild.png
-  minecraft/textures/gui/container/bundle.png
-  minecraft/textures/item/amethyst_shard.png
-  minecraft/textures/item/axolotl_bucket.png
-  minecraft/textures/item/black_candle.png
-  minecraft/textures/item/blue_candle.png
-  minecraft/textures/item/brown_candle.png
-  minecraft/textures/item/bundle.png
-  minecraft/textures/item/bundle_filled.png
-  minecraft/textures/item/candle.png
-  minecraft/textures/item/copper_ingot.png
-  minecraft/textures/item/cyan_candle.png
-  minecraft/textures/item/gray_candle.png
-  minecraft/textures/item/green_candle.png
-  minecraft/textures/item/light_blue_candle.png
-  minecraft/textures/item/light_gray_candle.png
-  minecraft/textures/item/lime_candle.png
-  minecraft/textures/item/magenta_candle.png
-  minecraft/textures/item/orange_candle.png
-  minecraft/textures/item/pink_candle.png
-  minecraft/textures/item/pointed_dripstone.png
-  minecraft/textures/item/powder_snow_bucket.png
-  minecraft/textures/item/purple_candle.png
-  minecraft/textures/item/red_candle.png
-  minecraft/textures/item/spyglass.png
-  minecraft/textures/item/white_candle.png
-  minecraft/textures/item/yellow_candle.png
-  minecraft/textures/misc/powder_snow_outline.png
-  minecraft/textures/misc/spyglass_scope.png
-  minecraft/textures/particle/vibration.png
-  minecraft/textures/particle/vibration.png.mcmeta
```

</details>

<details><summary>minecraft-generated/</summary>

```diff
-  reports/biomes/dripstone_caves.json
```

</details>

## Registries

<details><summary>list</summary>

```diff
- game_event.txt
- loot_nbt_provider_type.txt
- loot_number_provider_type.txt
- loot_score_provider_type.txt
- position_source_type.txt
```

</details>

<details><summary>activity.txt</summary>

```diff
- minecraft:play_dead
```

</details>

<details><summary>block.txt</summary>

```diff
- minecraft:water_cauldron
- minecraft:lava_cauldron
- minecraft:powder_snow_cauldron
- minecraft:dirt_path
- minecraft:candle
- minecraft:white_candle
- minecraft:orange_candle
- minecraft:magenta_candle
- minecraft:light_blue_candle
- minecraft:yellow_candle
- minecraft:lime_candle
- minecraft:pink_candle
- minecraft:gray_candle
- minecraft:light_gray_candle
- minecraft:cyan_candle
- minecraft:purple_candle
- minecraft:blue_candle
- minecraft:brown_candle
- minecraft:green_candle
- minecraft:red_candle
- minecraft:black_candle
- minecraft:candle_cake
- minecraft:white_candle_cake
- minecraft:orange_candle_cake
- minecraft:magenta_candle_cake
- minecraft:light_blue_candle_cake
- minecraft:yellow_candle_cake
- minecraft:lime_candle_cake
- minecraft:pink_candle_cake
- minecraft:gray_candle_cake
- minecraft:light_gray_candle_cake
- minecraft:cyan_candle_cake
- minecraft:purple_candle_cake
- minecraft:blue_candle_cake
- minecraft:brown_candle_cake
- minecraft:green_candle_cake
- minecraft:red_candle_cake
- minecraft:black_candle_cake
- minecraft:amethyst_block
- minecraft:budding_amethyst
- minecraft:amethyst_cluster
- minecraft:large_amethyst_bud
- minecraft:medium_amethyst_bud
- minecraft:small_amethyst_bud
- minecraft:tuff
- minecraft:calcite
- minecraft:tinted_glass
- minecraft:powder_snow
- minecraft:sculk_sensor
- minecraft:weathered_copper_block
- minecraft:semi_weathered_copper_block
- minecraft:lightly_weathered_copper_block
- minecraft:copper_block
- minecraft:copper_ore
- minecraft:weathered_cut_copper
- minecraft:semi_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper
- minecraft:cut_copper
- minecraft:weathered_cut_copper_stairs
- minecraft:semi_weathered_cut_copper_stairs
- minecraft:lightly_weathered_cut_copper_stairs
- minecraft:cut_copper_stairs
- minecraft:weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:cut_copper_slab
- minecraft:waxed_copper
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_stairs
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_cut_copper_stairs
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_cut_copper_slab
- minecraft:lightning_rod
- minecraft:pointed_dripstone
- minecraft:dripstone_block
+ minecraft:grass_path
```

</details>

<details><summary>block_entity_type.txt</summary>

```diff
- minecraft:sculk_sensor
```

</details>

<details><summary>entity_type.txt</summary>

```diff
- minecraft:axolotl
```

</details>

<details><summary>item.txt</summary>

```diff
- minecraft:calcite
- minecraft:tuff
- minecraft:copper_ore
- minecraft:tinted_glass
- minecraft:dirt_path
- minecraft:copper_ingot
- minecraft:axolotl_bucket
- minecraft:bundle
- minecraft:axolotl_spawn_egg
- minecraft:candle
- minecraft:white_candle
- minecraft:orange_candle
- minecraft:magenta_candle
- minecraft:light_blue_candle
- minecraft:yellow_candle
- minecraft:lime_candle
- minecraft:pink_candle
- minecraft:gray_candle
- minecraft:light_gray_candle
- minecraft:cyan_candle
- minecraft:purple_candle
- minecraft:blue_candle
- minecraft:brown_candle
- minecraft:green_candle
- minecraft:red_candle
- minecraft:black_candle
- minecraft:amethyst_shard
- minecraft:amethyst_block
- minecraft:budding_amethyst
- minecraft:small_amethyst_bud
- minecraft:medium_amethyst_bud
- minecraft:large_amethyst_bud
- minecraft:amethyst_cluster
- minecraft:spyglass
- minecraft:copper_block
- minecraft:lightly_weathered_copper_block
- minecraft:semi_weathered_copper_block
- minecraft:weathered_copper_block
- minecraft:cut_copper
- minecraft:lightly_weathered_cut_copper
- minecraft:semi_weathered_cut_copper
- minecraft:weathered_cut_copper
- minecraft:cut_copper_stairs
- minecraft:lightly_weathered_cut_copper_stairs
- minecraft:semi_weathered_cut_copper_stairs
- minecraft:weathered_cut_copper_stairs
- minecraft:cut_copper_slab
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_slab
- minecraft:weathered_cut_copper_slab
- minecraft:waxed_copper
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_cut_copper_stairs
- minecraft:waxed_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:lightning_rod
- minecraft:powder_snow_bucket
- minecraft:pointed_dripstone
- minecraft:dripstone_block
- minecraft:sculk_sensor
+ minecraft:grass_path
```

</details>

<details><summary>loot_condition_type.txt</summary>

```diff
- minecraft:value_check
```

</details>

<details><summary>loot_function_type.txt</summary>

```diff
- minecraft:set_enchantments
- minecraft:set_banner_pattern
```

</details>

<details><summary>memory_module_type.txt</summary>

```diff
- minecraft:play_dead_ticks
- minecraft:tempting_player
- minecraft:temptation_cooldown_ticks
- minecraft:is_tempted
```

</details>

<details><summary>particle_type.txt</summary>

```diff
- minecraft:dust_color_transition
- minecraft:vibration
- minecraft:small_flame
- minecraft:snowflake
- minecraft:dripping_dripstone_lava
- minecraft:falling_dripstone_lava
- minecraft:dripping_dripstone_water
- minecraft:falling_dripstone_water
```

</details>

<details><summary>point_of_interest_type.txt</summary>

```diff
- minecraft:lightning_rod
```

</details>

<details><summary>sensor_type.txt</summary>

```diff
- minecraft:axolotl_hostiles
- minecraft:axolotl_temptations
```

</details>

<details><summary>sound_event.txt</summary>

```diff
- minecraft:block.amethyst_block.break
- minecraft:block.amethyst_block.chime
- minecraft:block.amethyst_block.fall
- minecraft:block.amethyst_block.hit
- minecraft:block.amethyst_block.place
- minecraft:block.amethyst_block.step
- minecraft:block.amethyst_cluster.break
- minecraft:block.amethyst_cluster.fall
- minecraft:block.amethyst_cluster.hit
- minecraft:block.amethyst_cluster.place
- minecraft:block.amethyst_cluster.step
- minecraft:entity.axolotl.attack
- minecraft:entity.axolotl.death
- minecraft:entity.axolotl.hurt
- minecraft:entity.axolotl.idle_air
- minecraft:entity.axolotl.idle_water
- minecraft:entity.axolotl.splash
- minecraft:entity.axolotl.swim
- minecraft:item.bucket.empty_axolotl
- minecraft:item.bucket.empty_powder_snow
- minecraft:item.bucket.fill_axolotl
- minecraft:item.bucket.fill_powder_snow
- minecraft:block.cake.add_candle
- minecraft:block.calcite.break
- minecraft:block.calcite.step
- minecraft:block.calcite.place
- minecraft:block.calcite.hit
- minecraft:block.calcite.fall
- minecraft:block.candle.ambient
- minecraft:block.candle.break
- minecraft:block.candle.extinguish
- minecraft:block.candle.fall
- minecraft:block.candle.hit
- minecraft:block.candle.place
- minecraft:block.candle.step
- minecraft:block.copper.break
- minecraft:block.copper.step
- minecraft:block.copper.place
- minecraft:block.copper.hit
- minecraft:block.copper.fall
- minecraft:block.dripstone_block.break
- minecraft:block.dripstone_block.step
- minecraft:block.dripstone_block.place
- minecraft:block.dripstone_block.hit
- minecraft:block.dripstone_block.fall
- minecraft:block.pointed_dripstone.break
- minecraft:block.pointed_dripstone.step
- minecraft:block.pointed_dripstone.place
- minecraft:block.pointed_dripstone.hit
- minecraft:block.pointed_dripstone.fall
- minecraft:block.pointed_dripstone.land
- minecraft:block.pointed_dripstone.drip_lava
- minecraft:block.pointed_dripstone.drip_water
- minecraft:block.pointed_dripstone.drip_lava_into_cauldron
- minecraft:block.pointed_dripstone.drip_water_into_cauldron
- minecraft:block.large_amethyst_bud.break
- minecraft:block.large_amethyst_bud.place
- minecraft:block.medium_amethyst_bud.break
- minecraft:block.medium_amethyst_bud.place
- minecraft:entity.minecart.inside.underwater
- minecraft:entity.player.hurt_freeze
- minecraft:block.powder_snow.break
- minecraft:block.powder_snow.fall
- minecraft:block.powder_snow.hit
- minecraft:block.powder_snow.place
- minecraft:block.powder_snow.step
- minecraft:block.sculk_sensor.clicking
- minecraft:block.sculk_sensor.clicking_stop
- minecraft:block.sculk_sensor.break
- minecraft:block.sculk_sensor.fall
- minecraft:block.sculk_sensor.hit
- minecraft:block.sculk_sensor.place
- minecraft:block.sculk_sensor.step
- minecraft:block.small_amethyst_bud.break
- minecraft:block.small_amethyst_bud.place
- minecraft:item.spyglass.use
- minecraft:item.spyglass.stop_using
- minecraft:block.tuff.break
- minecraft:block.tuff.step
- minecraft:block.tuff.place
- minecraft:block.tuff.hit
- minecraft:block.tuff.fall
```

</details>

<details><summary>worldgen/feature.txt</summary>

```diff
- minecraft:geode
- minecraft:dripstone_cluster
- minecraft:large_dripstone
- minecraft:small_dripstone
```

</details>

## Commands

<details><summary>list</summary>

```diff
- item.txt
+ replaceitem.txt
```

</details>

<details><summary>gamerule.txt</summary>

```diff
- gamerule freezeDamage <value: bool>
- gamerule playersSleepingPercentage <value: integer>
```

</details>

## Tags

<details><summary>list</summary>

```diff
- blocks/candles.json
- blocks/candle_cakes.json
- blocks/cauldrons.json
- blocks/crystal_sound_blocks.json
- blocks/dripstone_replaceable_blocks.json
- blocks/inside_step_sound_blocks.json
- blocks/occludes_vibration_signals.json
- entity_types/axolotl_always_hostiles.json
- entity_types/axolotl_tempted_hostiles.json
- entity_types/powder_snow_walkable_mobs.json
- game_events/ignore_vibrations_stepping_carefully.json
- game_events/vibrations.json
- items/axolotl_tempt_items.json
- items/candles.json
- items/freeze_immune_wearables.json
- items/ignored_by_piglin_babies.json
- items/occludes_vibration_signals.json
- items/piglin_food.json
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
- recipes/building_blocks/amethyst_block.json
- recipes/building_blocks/copper_block.json
- recipes/building_blocks/cut_copper.json
- recipes/building_blocks/cut_copper_slab.json
- recipes/building_blocks/cut_copper_stairs.json
- recipes/building_blocks/lightly_weathered_cut_copper.json
- recipes/building_blocks/lightly_weathered_cut_copper_slab.json
- recipes/building_blocks/lightly_weathered_cut_copper_stairs.json
- recipes/building_blocks/semi_weathered_cut_copper.json
- recipes/building_blocks/semi_weathered_cut_copper_slab.json
- recipes/building_blocks/semi_weathered_cut_copper_stairs.json
- recipes/building_blocks/tinted_glass.json
- recipes/building_blocks/waxed_copper.json
- recipes/building_blocks/waxed_copper_cut_slab_from_honeycomb.json
- recipes/building_blocks/waxed_copper_cut_stairs_from_honeycomb.json
- recipes/building_blocks/waxed_cut_copper_from_honeycomb.json
- recipes/building_blocks/waxed_cut_copper_from_waxed_block.json
- recipes/building_blocks/waxed_cut_copper_slab.json
- recipes/building_blocks/waxed_cut_copper_stairs.json
- recipes/building_blocks/waxed_lightly_weathered_copper.json
- recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_honeycomb.json
- recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_waxed_block.json
- recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab.json
- recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
- recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs.json
- recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
- recipes/building_blocks/waxed_semi_weathered_copper.json
- recipes/building_blocks/waxed_semi_weathered_cut_copper_from_honeycomb.json
- recipes/building_blocks/waxed_semi_weathered_cut_copper_from_waxed_block.json
- recipes/building_blocks/waxed_semi_weathered_cut_copper_slab.json
- recipes/building_blocks/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
- recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs.json
- recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
- recipes/building_blocks/weathered_cut_copper.json
- recipes/building_blocks/weathered_cut_copper_slab.json
- recipes/building_blocks/weathered_cut_copper_stairs.json
- recipes/decorations/black_candle.json
- recipes/decorations/blue_candle.json
- recipes/decorations/brown_candle.json
- recipes/decorations/candle.json
- recipes/decorations/cyan_candle.json
- recipes/decorations/gray_candle.json
- recipes/decorations/green_candle.json
- recipes/decorations/light_blue_candle.json
- recipes/decorations/light_gray_candle.json
- recipes/decorations/lime_candle.json
- recipes/decorations/magenta_candle.json
- recipes/decorations/orange_candle.json
- recipes/decorations/pink_candle.json
- recipes/decorations/purple_candle.json
- recipes/decorations/red_candle.json
- recipes/decorations/white_candle.json
- recipes/decorations/yellow_candle.json
- recipes/misc/copper_ingot.json
- recipes/misc/copper_ingot_from_blasting.json
- recipes/misc/copper_ingot_from_copper_block.json
- recipes/misc/firework_rocket_simple.json
- recipes/redstone/lightning_rod.json
- recipes/tools/bundle.json
- recipes/tools/spyglass.json
```

</details>

<details><summary>languages.txt</summary>

```diff
- zlm_arab.json
- realms/lang/zlm_arab.json
+ gv_im.json
+ mi_nz.json
+ swg.json
+ realms/lang/gv_im.json
+ realms/lang/mi_nz.json
+ realms/lang/swg.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
- blocks/amethyst_block.json
- blocks/amethyst_cluster.json
- blocks/black_candle.json
- blocks/black_candle_cake.json
- blocks/blue_candle.json
- blocks/blue_candle_cake.json
- blocks/brown_candle.json
- blocks/brown_candle_cake.json
- blocks/budding_amethyst.json
- blocks/calcite.json
- blocks/candle.json
- blocks/candle_cake.json
- blocks/copper_block.json
- blocks/copper_ore.json
- blocks/cut_copper.json
- blocks/cut_copper_slab.json
- blocks/cut_copper_stairs.json
- blocks/cyan_candle.json
- blocks/cyan_candle_cake.json
- blocks/dirt_path.json
- blocks/dripstone_block.json
- blocks/gray_candle.json
- blocks/gray_candle_cake.json
- blocks/green_candle.json
- blocks/green_candle_cake.json
- blocks/large_amethyst_bud.json
- blocks/lava_cauldron.json
- blocks/lightly_weathered_copper_block.json
- blocks/lightly_weathered_cut_copper.json
- blocks/lightly_weathered_cut_copper_slab.json
- blocks/lightly_weathered_cut_copper_stairs.json
- blocks/lightning_rod.json
- blocks/light_blue_candle.json
- blocks/light_blue_candle_cake.json
- blocks/light_gray_candle.json
- blocks/light_gray_candle_cake.json
- blocks/lime_candle.json
- blocks/lime_candle_cake.json
- blocks/magenta_candle.json
- blocks/magenta_candle_cake.json
- blocks/medium_amethyst_bud.json
- blocks/orange_candle.json
- blocks/orange_candle_cake.json
- blocks/pink_candle.json
- blocks/pink_candle_cake.json
- blocks/pointed_dripstone.json
- blocks/powder_snow.json
- blocks/powder_snow_cauldron.json
- blocks/purple_candle.json
- blocks/purple_candle_cake.json
- blocks/red_candle.json
- blocks/red_candle_cake.json
- blocks/sculk_sensor.json
- blocks/semi_weathered_copper_block.json
- blocks/semi_weathered_cut_copper.json
- blocks/semi_weathered_cut_copper_slab.json
- blocks/semi_weathered_cut_copper_stairs.json
- blocks/small_amethyst_bud.json
- blocks/tinted_glass.json
- blocks/tuff.json
- blocks/water_cauldron.json
- blocks/waxed_copper.json
- blocks/waxed_cut_copper.json
- blocks/waxed_cut_copper_slab.json
- blocks/waxed_cut_copper_stairs.json
- blocks/waxed_lightly_weathered_copper.json
- blocks/waxed_lightly_weathered_cut_copper.json
- blocks/waxed_lightly_weathered_cut_copper_slab.json
- blocks/waxed_lightly_weathered_cut_copper_stairs.json
- blocks/waxed_semi_weathered_copper.json
- blocks/waxed_semi_weathered_cut_copper.json
- blocks/waxed_semi_weathered_cut_copper_slab.json
- blocks/waxed_semi_weathered_cut_copper_stairs.json
- blocks/weathered_copper_block.json
- blocks/weathered_cut_copper.json
- blocks/weathered_cut_copper_slab.json
- blocks/weathered_cut_copper_stairs.json
- blocks/white_candle.json
- blocks/white_candle_cake.json
- blocks/yellow_candle.json
- blocks/yellow_candle_cake.json
- entities/axolotl.json
+ blocks/grass_path.json
```

</details>

<details><summary>particles.txt</summary>

```diff
- dripping_dripstone_lava.json
- dripping_dripstone_water.json
- dust_color_transition.json
- falling_dripstone_lava.json
- falling_dripstone_water.json
- small_flame.json
- snowflake.json
- vibration.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
- amethyst_block.json
- black_candle.json
- blue_candle.json
- brown_candle.json
- bundle.json
- candle.json
- copper_block.json
- copper_ingot.json
- copper_ingot_from_blasting.json
- copper_ingot_from_copper_block.json
- cut_copper.json
- cut_copper_slab.json
- cut_copper_stairs.json
- cyan_candle.json
- firework_rocket_simple.json
- gray_candle.json
- green_candle.json
- lightly_weathered_cut_copper.json
- lightly_weathered_cut_copper_slab.json
- lightly_weathered_cut_copper_stairs.json
- lightning_rod.json
- light_blue_candle.json
- light_gray_candle.json
- lime_candle.json
- magenta_candle.json
- orange_candle.json
- pink_candle.json
- purple_candle.json
- red_candle.json
- semi_weathered_cut_copper.json
- semi_weathered_cut_copper_slab.json
- semi_weathered_cut_copper_stairs.json
- spyglass.json
- tinted_glass.json
- waxed_copper.json
- waxed_copper_cut_slab_from_honeycomb.json
- waxed_copper_cut_stairs_from_honeycomb.json
- waxed_cut_copper_from_honeycomb.json
- waxed_cut_copper_from_waxed_block.json
- waxed_cut_copper_slab.json
- waxed_cut_copper_stairs.json
- waxed_lightly_weathered_copper.json
- waxed_lightly_weathered_cut_copper_from_honeycomb.json
- waxed_lightly_weathered_cut_copper_from_waxed_block.json
- waxed_lightly_weathered_cut_copper_slab.json
- waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
- waxed_lightly_weathered_cut_copper_stairs.json
- waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
- waxed_semi_weathered_copper.json
- waxed_semi_weathered_cut_copper_from_honeycomb.json
- waxed_semi_weathered_cut_copper_from_waxed_block.json
- waxed_semi_weathered_cut_copper_slab.json
- waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
- waxed_semi_weathered_cut_copper_stairs.json
- waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
- weathered_cut_copper.json
- weathered_cut_copper_slab.json
- weathered_cut_copper_stairs.json
- white_candle.json
- yellow_candle.json
```

</details>

<details><summary>sounds.txt</summary>

```diff
- block/amethyst/break1.ogg
- block/amethyst/break2.ogg
- block/amethyst/break3.ogg
- block/amethyst/break4.ogg
- block/amethyst/place1.ogg
- block/amethyst/place2.ogg
- block/amethyst/place3.ogg
- block/amethyst/place4.ogg
- block/amethyst/shimmer.ogg
- block/amethyst/step1.ogg
- block/amethyst/step10.ogg
- block/amethyst/step11.ogg
- block/amethyst/step12.ogg
- block/amethyst/step13.ogg
- block/amethyst/step14.ogg
- block/amethyst/step2.ogg
- block/amethyst/step3.ogg
- block/amethyst/step4.ogg
- block/amethyst/step5.ogg
- block/amethyst/step6.ogg
- block/amethyst/step7.ogg
- block/amethyst/step8.ogg
- block/amethyst/step9.ogg
- block/amethyst_cluster/break1.ogg
- block/amethyst_cluster/break2.ogg
- block/amethyst_cluster/break3.ogg
- block/amethyst_cluster/break4.ogg
- block/amethyst_cluster/place1.ogg
- block/amethyst_cluster/place2.ogg
- block/amethyst_cluster/place3.ogg
- block/amethyst_cluster/place4.ogg
- block/azalea/break1.ogg
- block/azalea/break2.ogg
- block/azalea/break3.ogg
- block/azalea/break4.ogg
- block/azalea/break5.ogg
- block/azalea/break6.ogg
- block/azalea/step1.ogg
- block/azalea/step2.ogg
- block/azalea/step3.ogg
- block/azalea/step4.ogg
- block/azalea/step5.ogg
- block/azalea/step6.ogg
- block/azalea_leaves/break1.ogg
- block/azalea_leaves/break2.ogg
- block/azalea_leaves/break3.ogg
- block/azalea_leaves/break4.ogg
- block/azalea_leaves/break5.ogg
- block/azalea_leaves/break6.ogg
- block/azalea_leaves/break7.ogg
- block/azalea_leaves/step1.ogg
- block/azalea_leaves/step2.ogg
- block/azalea_leaves/step3.ogg
- block/azalea_leaves/step4.ogg
- block/azalea_leaves/step5.ogg
- block/big_dripleaf/break1.ogg
- block/big_dripleaf/break2.ogg
- block/big_dripleaf/break3.ogg
- block/big_dripleaf/break4.ogg
- block/big_dripleaf/break5.ogg
- block/big_dripleaf/break6.ogg
- block/big_dripleaf/step1.ogg
- block/big_dripleaf/step2.ogg
- block/big_dripleaf/step3.ogg
- block/big_dripleaf/step4.ogg
- block/big_dripleaf/step5.ogg
- block/big_dripleaf/step6.ogg
- block/big_dripleaf/tilt_down1.ogg
- block/big_dripleaf/tilt_down2.ogg
- block/big_dripleaf/tilt_down3.ogg
- block/big_dripleaf/tilt_down4.ogg
- block/big_dripleaf/tilt_down5.ogg
- block/big_dripleaf/tilt_up1.ogg
- block/big_dripleaf/tilt_up2.ogg
- block/big_dripleaf/tilt_up3.ogg
- block/big_dripleaf/tilt_up4.ogg
- block/cake/add_candle1.ogg
- block/cake/add_candle2.ogg
- block/cake/add_candle3.ogg
- block/calcite/break1.ogg
- block/calcite/break2.ogg
- block/calcite/break3.ogg
- block/calcite/break4.ogg
- block/calcite/place1.ogg
- block/calcite/place2.ogg
- block/calcite/place3.ogg
- block/calcite/place4.ogg
- block/calcite/step1.ogg
- block/calcite/step2.ogg
- block/calcite/step3.ogg
- block/calcite/step4.ogg
- block/calcite/step5.ogg
- block/calcite/step6.ogg
- block/candle/ambient1.ogg
- block/candle/ambient2.ogg
- block/candle/ambient3.ogg
- block/candle/ambient4.ogg
- block/candle/ambient5.ogg
- block/candle/ambient6.ogg
- block/candle/ambient7.ogg
- block/candle/ambient8.ogg
- block/candle/ambient9.ogg
- block/candle/break1.ogg
- block/candle/break2.ogg
- block/candle/break3.ogg
- block/candle/break4.ogg
- block/candle/break5.ogg
- block/candle/extinguish1.ogg
- block/candle/extinguish2.ogg
- block/candle/extinguish3.ogg
- block/candle/step1.ogg
- block/candle/step2.ogg
- block/candle/step3.ogg
- block/candle/step4.ogg
- block/candle/step5.ogg
- block/cave_vines/break1.ogg
- block/cave_vines/break2.ogg
- block/cave_vines/break3.ogg
- block/cave_vines/break4.ogg
- block/cave_vines/break5.ogg
- block/copper/break1.ogg
- block/copper/break2.ogg
- block/copper/break3.ogg
- block/copper/break4.ogg
- block/copper/step1.ogg
- block/copper/step2.ogg
- block/copper/step3.ogg
- block/copper/step4.ogg
- block/copper/step5.ogg
- block/copper/step6.ogg
- block/deepslate/break1.ogg
- block/deepslate/break2.ogg
- block/deepslate/break3.ogg
- block/deepslate/break4.ogg
- block/deepslate/place1.ogg
- block/deepslate/place2.ogg
- block/deepslate/place3.ogg
- block/deepslate/place4.ogg
- block/deepslate/place5.ogg
- block/deepslate/place6.ogg
- block/deepslate/step1.ogg
- block/deepslate/step2.ogg
- block/deepslate/step3.ogg
- block/deepslate/step4.ogg
- block/deepslate/step5.ogg
- block/deepslate/step6.ogg
- block/deepslate_bricks/place1.ogg
- block/deepslate_bricks/place2.ogg
- block/deepslate_bricks/place3.ogg
- block/deepslate_bricks/place4.ogg
- block/deepslate_bricks/place5.ogg
- block/deepslate_bricks/place6.ogg
- block/deepslate_bricks/step1.ogg
- block/deepslate_bricks/step2.ogg
- block/deepslate_bricks/step3.ogg
- block/deepslate_bricks/step4.ogg
- block/deepslate_bricks/step5.ogg
- block/dripstone/break1.ogg
- block/dripstone/break2.ogg
- block/dripstone/break3.ogg
- block/dripstone/break4.ogg
- block/dripstone/break5.ogg
- block/dripstone/step1.ogg
- block/dripstone/step2.ogg
- block/dripstone/step3.ogg
- block/dripstone/step4.ogg
- block/dripstone/step5.ogg
- block/dripstone/step6.ogg
- block/hanging_roots/break1.ogg
- block/hanging_roots/break2.ogg
- block/hanging_roots/break3.ogg
- block/hanging_roots/break4.ogg
- block/hanging_roots/step1.ogg
- block/hanging_roots/step2.ogg
- block/hanging_roots/step3.ogg
- block/hanging_roots/step4.ogg
- block/hanging_roots/step5.ogg
- block/hanging_roots/step6.ogg
- block/moss/break1.ogg
- block/moss/break2.ogg
- block/moss/break3.ogg
- block/moss/break4.ogg
- block/moss/break5.ogg
- block/moss/step1.ogg
- block/moss/step2.ogg
- block/moss/step3.ogg
- block/moss/step4.ogg
- block/moss/step5.ogg
- block/moss/step6.ogg
- block/pointed_dripstone/drip_lava1.ogg
- block/pointed_dripstone/drip_lava2.ogg
- block/pointed_dripstone/drip_lava3.ogg
- block/pointed_dripstone/drip_lava4.ogg
- block/pointed_dripstone/drip_lava5.ogg
- block/pointed_dripstone/drip_lava6.ogg
- block/pointed_dripstone/drip_lava_cauldron1.ogg
- block/pointed_dripstone/drip_lava_cauldron2.ogg
- block/pointed_dripstone/drip_lava_cauldron3.ogg
- block/pointed_dripstone/drip_lava_cauldron4.ogg
- block/pointed_dripstone/drip_water1.ogg
- block/pointed_dripstone/drip_water10.ogg
- block/pointed_dripstone/drip_water11.ogg
- block/pointed_dripstone/drip_water12.ogg
- block/pointed_dripstone/drip_water13.ogg
- block/pointed_dripstone/drip_water14.ogg
- block/pointed_dripstone/drip_water15.ogg
- block/pointed_dripstone/drip_water2.ogg
- block/pointed_dripstone/drip_water3.ogg
- block/pointed_dripstone/drip_water4.ogg
- block/pointed_dripstone/drip_water5.ogg
- block/pointed_dripstone/drip_water6.ogg
- block/pointed_dripstone/drip_water7.ogg
- block/pointed_dripstone/drip_water8.ogg
- block/pointed_dripstone/drip_water9.ogg
- block/pointed_dripstone/drip_water_cauldron1.ogg
- block/pointed_dripstone/drip_water_cauldron2.ogg
- block/pointed_dripstone/drip_water_cauldron3.ogg
- block/pointed_dripstone/drip_water_cauldron4.ogg
- block/pointed_dripstone/drip_water_cauldron5.ogg
- block/pointed_dripstone/drip_water_cauldron6.ogg
- block/pointed_dripstone/drip_water_cauldron7.ogg
- block/pointed_dripstone/drip_water_cauldron8.ogg
- block/pointed_dripstone/land1.ogg
- block/pointed_dripstone/land2.ogg
- block/pointed_dripstone/land3.ogg
- block/pointed_dripstone/land4.ogg
- block/pointed_dripstone/land5.ogg
- block/powder_snow/break1.ogg
- block/powder_snow/break2.ogg
- block/powder_snow/break3.ogg
- block/powder_snow/break4.ogg
- block/powder_snow/break5.ogg
- block/powder_snow/break6.ogg
- block/powder_snow/break7.ogg
- block/powder_snow/step1.ogg
- block/powder_snow/step10.ogg
- block/powder_snow/step2.ogg
- block/powder_snow/step3.ogg
- block/powder_snow/step4.ogg
- block/powder_snow/step5.ogg
- block/powder_snow/step6.ogg
- block/powder_snow/step7.ogg
- block/powder_snow/step8.ogg
- block/powder_snow/step9.ogg
- block/rooted_dirt/break1.ogg
- block/rooted_dirt/break2.ogg
- block/rooted_dirt/break3.ogg
- block/rooted_dirt/break4.ogg
- block/rooted_dirt/step1.ogg
- block/rooted_dirt/step2.ogg
- block/rooted_dirt/step3.ogg
- block/rooted_dirt/step4.ogg
- block/rooted_dirt/step5.ogg
- block/rooted_dirt/step6.ogg
- block/sculk/step1.ogg
- block/sculk/step2.ogg
- block/sculk/step3.ogg
- block/sculk/step4.ogg
- block/sculk/step5.ogg
- block/sculk/step6.ogg
- block/sculk_sensor/break1.ogg
- block/sculk_sensor/break2.ogg
- block/sculk_sensor/break3.ogg
- block/sculk_sensor/break4.ogg
- block/sculk_sensor/break5.ogg
- block/sculk_sensor/place1.ogg
- block/sculk_sensor/place2.ogg
- block/sculk_sensor/place3.ogg
- block/sculk_sensor/place4.ogg
- block/sculk_sensor/place5.ogg
- block/sculk_sensor/sculk_clicking1.ogg
- block/sculk_sensor/sculk_clicking2.ogg
- block/sculk_sensor/sculk_clicking3.ogg
- block/sculk_sensor/sculk_clicking4.ogg
- block/sculk_sensor/sculk_clicking5.ogg
- block/sculk_sensor/sculk_clicking6.ogg
- block/sculk_sensor/sculk_clicking_stop1.ogg
- block/sculk_sensor/sculk_clicking_stop2.ogg
- block/sculk_sensor/sculk_clicking_stop3.ogg
- block/sculk_sensor/sculk_clicking_stop4.ogg
- block/sculk_sensor/sculk_clicking_stop5.ogg
- block/spore_blossom/break1.ogg
- block/spore_blossom/break2.ogg
- block/spore_blossom/break3.ogg
- block/spore_blossom/break4.ogg
- block/spore_blossom/break5.ogg
- block/spore_blossom/step1.ogg
- block/spore_blossom/step2.ogg
- block/spore_blossom/step3.ogg
- block/spore_blossom/step4.ogg
- block/spore_blossom/step5.ogg
- block/spore_blossom/step6.ogg
- block/tuff/break1.ogg
- block/tuff/break2.ogg
- block/tuff/break3.ogg
- block/tuff/break4.ogg
- block/tuff/break5.ogg
- block/tuff/step1.ogg
- block/tuff/step2.ogg
- block/tuff/step3.ogg
- block/tuff/step4.ogg
- block/tuff/step5.ogg
- block/tuff/step6.ogg
- block/vine/break1.ogg
- block/vine/break2.ogg
- block/vine/break3.ogg
- block/vine/break4.ogg
- entity/glow_squid/ambient1.ogg
- entity/glow_squid/ambient2.ogg
- entity/glow_squid/ambient3.ogg
- entity/glow_squid/ambient4.ogg
- entity/glow_squid/ambient5.ogg
- entity/glow_squid/death1.ogg
- entity/glow_squid/death2.ogg
- entity/glow_squid/death3.ogg
- entity/glow_squid/hurt1.ogg
- entity/glow_squid/hurt2.ogg
- entity/glow_squid/hurt3.ogg
- entity/glow_squid/hurt4.ogg
- entity/glow_squid/squirt1.ogg
- entity/glow_squid/squirt2.ogg
- entity/glow_squid/squirt3.ogg
- entity/player/hurt/freeze_hurt1.ogg
- entity/player/hurt/freeze_hurt2.ogg
- entity/player/hurt/freeze_hurt3.ogg
- entity/player/hurt/freeze_hurt4.ogg
- entity/player/hurt/freeze_hurt5.ogg
- item/axe/scrape1.ogg
- item/axe/scrape2.ogg
- item/axe/scrape3.ogg
- item/axe/wax_off1.ogg
- item/axe/wax_off2.ogg
- item/axe/wax_off3.ogg
- item/bonemeal/bonemeal1.ogg
- item/bonemeal/bonemeal2.ogg
- item/bonemeal/bonemeal3.ogg
- item/bonemeal/bonemeal4.ogg
- item/bonemeal/bonemeal5.ogg
- item/bucket/empty_powder_snow1.ogg
- item/bucket/empty_powder_snow2.ogg
- item/bucket/fill_axolotl1.ogg
- item/bucket/fill_axolotl2.ogg
- item/bucket/fill_axolotl3.ogg
- item/bucket/fill_powder_snow1.ogg
- item/bucket/fill_powder_snow2.ogg
- item/dye/dye.ogg
- item/honeycomb/wax_on1.ogg
- item/honeycomb/wax_on2.ogg
- item/honeycomb/wax_on3.ogg
- item/ink_sac/ink_sac1.ogg
- item/ink_sac/ink_sac2.ogg
- item/ink_sac/ink_sac3.ogg
- item/spyglass/stop.ogg
- item/spyglass/use.ogg
- minecart/inside_underwater1.ogg
- minecart/inside_underwater2.ogg
- minecart/inside_underwater3.ogg
- mob/axolotl/attack1.ogg
- mob/axolotl/attack2.ogg
- mob/axolotl/attack3.ogg
- mob/axolotl/attack4.ogg
- mob/axolotl/death1.ogg
- mob/axolotl/death2.ogg
- mob/axolotl/hurt1.ogg
- mob/axolotl/hurt2.ogg
- mob/axolotl/hurt3.ogg
- mob/axolotl/hurt4.ogg
- mob/axolotl/idle1.ogg
- mob/axolotl/idle2.ogg
- mob/axolotl/idle3.ogg
- mob/axolotl/idle4.ogg
- mob/axolotl/idle5.ogg
- mob/axolotl/idle_air1.ogg
- mob/axolotl/idle_air2.ogg
- mob/axolotl/idle_air3.ogg
- mob/axolotl/idle_air4.ogg
- mob/axolotl/idle_air5.ogg
- mob/goat/death1.ogg
- mob/goat/death2.ogg
- mob/goat/death3.ogg
- mob/goat/death4.ogg
- mob/goat/death5.ogg
- mob/goat/eat1.ogg
- mob/goat/eat2.ogg
- mob/goat/eat3.ogg
- mob/goat/hurt1.ogg
- mob/goat/hurt2.ogg
- mob/goat/hurt3.ogg
- mob/goat/hurt4.ogg
- mob/goat/idle1.ogg
- mob/goat/idle2.ogg
- mob/goat/idle3.ogg
- mob/goat/idle4.ogg
- mob/goat/idle5.ogg
- mob/goat/idle6.ogg
- mob/goat/idle7.ogg
- mob/goat/idle8.ogg
- mob/goat/impact1.ogg
- mob/goat/impact2.ogg
- mob/goat/impact3.ogg
- mob/goat/jump1.ogg
- mob/goat/jump2.ogg
- mob/goat/pre_ram1.ogg
- mob/goat/pre_ram2.ogg
- mob/goat/pre_ram3.ogg
- mob/goat/pre_ram4.ogg
- mob/goat/scream1.ogg
- mob/goat/scream2.ogg
- mob/goat/scream3.ogg
- mob/goat/scream4.ogg
- mob/goat/scream5.ogg
- mob/goat/scream6.ogg
- mob/goat/scream7.ogg
- mob/goat/scream8.ogg
- mob/goat/scream9.ogg
- mob/goat/screaming_death1.ogg
- mob/goat/screaming_death2.ogg
- mob/goat/screaming_death3.ogg
- mob/goat/screaming_hurt1.ogg
- mob/goat/screaming_hurt2.ogg
- mob/goat/screaming_hurt3.ogg
- mob/goat/screaming_milk1.ogg
- mob/goat/screaming_milk2.ogg
- mob/goat/screaming_milk3.ogg
- mob/goat/screaming_milk4.ogg
- mob/goat/screaming_milk5.ogg
- mob/goat/screaming_pre_ram1.ogg
- mob/goat/screaming_pre_ram2.ogg
- mob/goat/screaming_pre_ram3.ogg
- mob/goat/screaming_pre_ram4.ogg
- mob/goat/screaming_pre_ram5.ogg
- mob/goat/step1.ogg
- mob/goat/step2.ogg
- mob/goat/step3.ogg
- mob/goat/step4.ogg
- mob/goat/step5.ogg
- mob/goat/step6.ogg
- mob/stray/convert1.ogg
- mob/stray/convert2.ogg
- mob/stray/convert3.ogg
```

</details>

<details><summary>tags.txt</summary>

```diff
- blocks/candles.json
- blocks/candle_cakes.json
- blocks/cauldrons.json
- blocks/crystal_sound_blocks.json
- blocks/dripstone_replaceable_blocks.json
- blocks/inside_step_sound_blocks.json
- blocks/occludes_vibration_signals.json
- entity_types/axolotl_always_hostiles.json
- entity_types/axolotl_tempted_hostiles.json
- entity_types/powder_snow_walkable_mobs.json
- game_events/ignore_vibrations_stepping_carefully.json
- game_events/vibrations.json
- items/axolotl_tempt_items.json
- items/candles.json
- items/freeze_immune_wearables.json
- items/ignored_by_piglin_babies.json
- items/occludes_vibration_signals.json
- items/piglin_food.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- block/amethyst_block.png
- block/amethyst_cluster.png
- block/black_candle.png
- block/blue_candle.png
- block/brown_candle.png
- block/budding_amethyst.png
- block/calcite.png
- block/calibrated_sculk_sensor_side.png
- block/calibrated_sculk_sensor_top.png
- block/candle.png
- block/copper_block.png
- block/copper_ore.png
- block/cut_copper.png
- block/cyan_candle.png
- block/dirt_path_side.png
- block/dirt_path_top.png
- block/dripstone_block.png
- block/gray_candle.png
- block/green_candle.png
- block/large_amethyst_bud.png
- block/lightly_weathered_copper_block.png
- block/lightly_weathered_cut_copper.png
- block/lightning_rod.png
- block/light_blue_candle.png
- block/light_gray_candle.png
- block/lime_candle.png
- block/magenta_candle.png
- block/medium_amethyst_bud.png
- block/orange_candle.png
- block/pink_candle.png
- block/pointed_dripstone_down_base.png
- block/pointed_dripstone_down_frustum.png
- block/pointed_dripstone_down_middle.png
- block/pointed_dripstone_down_tip.png
- block/pointed_dripstone_down_tip_merge.png
- block/pointed_dripstone_up_base.png
- block/pointed_dripstone_up_frustum.png
- block/pointed_dripstone_up_middle.png
- block/pointed_dripstone_up_tip.png
- block/pointed_dripstone_up_tip_merge.png
- block/powder_snow.png
- block/purple_candle.png
- block/red_candle.png
- block/sculk_sensor_bottom.png
- block/sculk_sensor_side.png
- block/sculk_sensor_tendril_active.png
- block/sculk_sensor_tendril_inactive.png
- block/sculk_sensor_top.png
- block/semi_weathered_copper_block.png
- block/semi_weathered_cut_copper.png
- block/small_amethyst_bud.png
- block/tinted_glass.png
- block/tuff.png
- block/weathered_copper_block.png
- block/weathered_cut_copper.png
- block/white_candle.png
- block/yellow_candle.png
- entity/axolotl/axolotl_blue.png
- entity/axolotl/axolotl_cyan.png
- entity/axolotl/axolotl_gold.png
- entity/axolotl/axolotl_lucy.png
- entity/axolotl/axolotl_wild.png
- gui/container/bundle.png
- item/amethyst_shard.png
- item/axolotl_bucket.png
- item/black_candle.png
- item/blue_candle.png
- item/brown_candle.png
- item/bundle.png
- item/bundle_filled.png
- item/candle.png
- item/copper_ingot.png
- item/cyan_candle.png
- item/gray_candle.png
- item/green_candle.png
- item/light_blue_candle.png
- item/light_gray_candle.png
- item/lime_candle.png
- item/magenta_candle.png
- item/orange_candle.png
- item/pink_candle.png
- item/pointed_dripstone.png
- item/powder_snow_bucket.png
- item/purple_candle.png
- item/red_candle.png
- item/spyglass.png
- item/white_candle.png
- item/yellow_candle.png
- misc/powder_snow_outline.png
- misc/spyglass_scope.png
- particle/vibration.png
+ block/grass_path_side.png
+ block/grass_path_top.png
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:javabridge:1.1.23
+ com.mojang:javabridge:1.0.22
```

</details>

## Mappings













































<details><summary>com.mojang.blaze3d.systems.RenderSystem</summary>

```diff
- RenderSystem$AutoStorageIndexBuffer sharedSequential
- RenderSystem$AutoStorageIndexBuffer sharedSequentialQuad
+ void drawArrays(int,int,int)
+ void lambda$activeTexture$22(int)
+ void lambda$alphaFunc$0(int,float)
+ void lambda$bindTexture$25(int)
+ void lambda$blendColor$11(float,float,float,float)
+ void lambda$blendEquation$10(int)
+ void lambda$blendFunc$6(GlStateManager$DestFactor)
+ void lambda$blendFunc$7(int,int)
+ void lambda$blendFuncSeparate$8(GlStateManager$DestFactor)
+ void lambda$blendFuncSeparate$9(int,int,int,int)
+ void lambda$clear$35(int,boolean)
+ void lambda$clearColor$33(float,float,float,float)
+ void lambda$clearDepth$32(double)
+ void lambda$clearStencil$34(int)
+ void lambda$color3f$45(float,float,float)
+ void lambda$color4f$44(float,float,float,float)
+ void lambda$colorMask$28(boolean,boolean,boolean,boolean)
+ void lambda$colorMaterial$1(int,int)
+ void lambda$deleteTexture$24(int)
+ void lambda$depthFunc$4(int)
+ void lambda$depthMask$5(boolean)
+ void lambda$drawArrays$46(int,int,int)
+ void lambda$enableScissor$3(int,int,int,int)
+ void lambda$fog$17(int,float,float,float,float)
+ void lambda$fogDensity$14(float)
+ void lambda$fogEnd$16(float)
+ void lambda$fogi$18(int,int)
+ void lambda$fogMode$12(GlStateManager$FogMode)
+ void lambda$fogMode$13(int)
+ void lambda$fogStart$15(float)
+ void lambda$getString$51(Consumer)
+ void lambda$glBindBuffer$54(Supplier)
+ void lambda$glDeleteBuffers$55(int)
+ void lambda$glGenBuffers$72(Consumer)
+ void lambda$glMultiTexCoord2f$53(int,float,float)
+ void lambda$glUniform1$57(IntBuffer)
+ void lambda$glUniform1$61(FloatBuffer)
+ void lambda$glUniform1i$56(int,int)
+ void lambda$glUniform2$58(IntBuffer)
+ void lambda$glUniform2$62(FloatBuffer)
+ void lambda$glUniform3$59(IntBuffer)
+ void lambda$glUniform3$63(FloatBuffer)
+ void lambda$glUniform4$60(IntBuffer)
+ void lambda$glUniform4$64(FloatBuffer)
+ void lambda$glUniformMatrix2$65(FloatBuffer)
+ void lambda$glUniformMatrix3$66(FloatBuffer)
+ void lambda$glUniformMatrix4$67(FloatBuffer)
+ void lambda$lineWidth$47(float)
+ void lambda$logicOp$21(GlStateManager$LogicOp)
+ void lambda$matrixMode$36(int)
+ void lambda$multMatrix$43(Matrix4f)
+ void lambda$normal3f$2(float,float,float)
+ void lambda$ortho$37(double,double,double,double,double,double)
+ void lambda$pixelStore$48(int,int)
+ void lambda$pixelTransfer$49(int,float)
+ void lambda$polygonMode$19(int,int)
+ void lambda$polygonOffset$20(float,float)
+ void lambda$readPixels$50(ByteBuffer)
+ void lambda$renderCrosshair$52(int)
+ void lambda$rotatef$38(float,float,float,float)
+ void lambda$scaled$40(double,double,double)
+ void lambda$scalef$39(float,float,float)
+ void lambda$setupGui3DDiffuseLighting$71(Vector3f)
+ void lambda$setupGuiFlatDiffuseLighting$70(Vector3f)
+ void lambda$setupLevelDiffuseLighting$69(Matrix4f)
+ void lambda$setupOverlayColor$68(IntSupplier,int)
+ void lambda$shadeModel$26(int)
+ void lambda$stencilFunc$29(int,int,int)
+ void lambda$stencilMask$30(int)
+ void lambda$stencilOp$31(int,int,int)
+ void lambda$texParameter$23(int,int,int)
+ void lambda$translated$42(double,double,double)
+ void lambda$translatef$41(float,float,float)
+ void lambda$viewport$27(int,int,int,int)
- Logger access$200()
- RenderSystem$AutoStorageIndexBuffer getSequentialBuffer(VertexFormat$Mode,int)
- void drawElements(int,int,int)
- void lambda$activeTexture$23(int)
- void lambda$alphaFunc$1(int,float)
- void lambda$bindTexture$26(int)
- void lambda$blendColor$12(float,float,float,float)
- void lambda$blendEquation$11(int)
- void lambda$blendFunc$7(GlStateManager$DestFactor)
- void lambda$blendFunc$8(int,int)
- void lambda$blendFuncSeparate$10(int,int,int,int)
- void lambda$blendFuncSeparate$9(GlStateManager$DestFactor)
- void lambda$clear$36(int,boolean)
- void lambda$clearColor$34(float,float,float,float)
- void lambda$clearDepth$33(double)
- void lambda$clearStencil$35(int)
- void lambda$color3f$46(float,float,float)
- void lambda$color4f$45(float,float,float,float)
- void lambda$colorMask$29(boolean,boolean,boolean,boolean)
- void lambda$colorMaterial$2(int,int)
- void lambda$deleteTexture$25(int)
- void lambda$depthFunc$5(int)
- void lambda$depthMask$6(boolean)
- void lambda$drawElements$47(int,int,int)
- void lambda$enableScissor$4(int,int,int,int)
- void lambda$fog$18(int,float,float,float,float)
- void lambda$fogDensity$15(float)
- void lambda$fogEnd$17(float)
- void lambda$fogi$19(int,int)
- void lambda$fogMode$13(GlStateManager$FogMode)
- void lambda$fogMode$14(int)
- void lambda$fogStart$16(float)
- void lambda$getString$52(Consumer)
- void lambda$glBindBuffer$55(Supplier)
- void lambda$glDeleteBuffers$56(int)
- void lambda$glGenBuffers$73(Consumer)
- void lambda$glMultiTexCoord2f$54(int,float,float)
- void lambda$glUniform1$58(IntBuffer)
- void lambda$glUniform1$62(FloatBuffer)
- void lambda$glUniform1i$57(int,int)
- void lambda$glUniform2$59(IntBuffer)
- void lambda$glUniform2$63(FloatBuffer)
- void lambda$glUniform3$60(IntBuffer)
- void lambda$glUniform3$64(FloatBuffer)
- void lambda$glUniform4$61(IntBuffer)
- void lambda$glUniform4$65(FloatBuffer)
- void lambda$glUniformMatrix2$66(FloatBuffer)
- void lambda$glUniformMatrix3$67(FloatBuffer)
- void lambda$glUniformMatrix4$68(FloatBuffer)
- void lambda$lineWidth$48(float)
- void lambda$logicOp$22(GlStateManager$LogicOp)
- void lambda$matrixMode$37(int)
- void lambda$multMatrix$44(Matrix4f)
- void lambda$normal3f$3(float,float,float)
- void lambda$ortho$38(double,double,double,double,double,double)
- void lambda$pixelStore$49(int,int)
- void lambda$pixelTransfer$50(int,float)
- void lambda$polygonMode$20(int,int)
- void lambda$polygonOffset$21(float,float)
- void lambda$readPixels$51(ByteBuffer)
- void lambda$renderCrosshair$53(int)
- void lambda$rotatef$39(float,float,float,float)
- void lambda$scaled$41(double,double,double)
- void lambda$scalef$40(float,float,float)
- void lambda$setupGui3DDiffuseLighting$72(Vector3f)
- void lambda$setupGuiFlatDiffuseLighting$71(Vector3f)
- void lambda$setupLevelDiffuseLighting$70(Matrix4f)
- void lambda$setupOverlayColor$69(IntSupplier,int)
- void lambda$shadeModel$27(int)
- void lambda$static$0(IntConsumer,int)
- void lambda$stencilFunc$30(int,int,int)
- void lambda$stencilMask$31(int)
- void lambda$stencilOp$32(int,int,int)
- void lambda$texParameter$24(int,int,int)
- void lambda$translated$43(double,double,double)
- void lambda$translatef$42(float,float,float)
- void lambda$viewport$28(int,int,int,int)
```

</details>




<details><summary>com.mojang.math.Matrix4f</summary>

```diff
- void multiplyWithTranslation(float,float,float)
```

</details>





<details><summary>com.mojang.realmsclient.RealmsMainScreen</summary>

```diff
+ boolean access$7800(RealmsMainScreen)
+ boolean access$7802(RealmsMainScreen,boolean)
+ int access$8200(RealmsMainScreen)
+ int access$8300(RealmsMainScreen)
+ Minecraft access$8500(RealmsMainScreen)
+ ResourceLocation access$8400()
+ String access$8000(RealmsMainScreen)
+ void access$7600(PoseStack,int,int,int,int,boolean,boolean)
+ void access$7700(Button)
+ void access$7900(PoseStack,int,int,boolean,int,int,boolean,boolean)
+ void access$8100(PoseStack,int,int,int,int,boolean)
+ void access$8600(RealmsMainScreen)
- boolean access$8000(RealmsMainScreen)
- boolean access$8002(RealmsMainScreen,boolean)
- Component access$7600()
- Component access$7700()
- int access$8400(RealmsMainScreen)
- int access$8500(RealmsMainScreen)
- Minecraft access$8700(RealmsMainScreen)
- ResourceLocation access$8600()
- String access$8200(RealmsMainScreen)
- void access$7800(PoseStack,int,int,int,int,boolean,boolean)
- void access$7900(Button)
- void access$8100(PoseStack,int,int,boolean,int,int,boolean,boolean)
- void access$8300(PoseStack,int,int,int,int,boolean)
- void access$8800(RealmsMainScreen)
```

</details>






<details><summary>com.mojang.realmsclient.RealmsMainScreen$ServerEntry</summary>

```diff
+ RealmsServer access$8700(RealmsMainScreen$ServerEntry)
- RealmsServer access$8900(RealmsMainScreen$ServerEntry)
```

</details>




































<details><summary>com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen</summary>

```diff
- Component TEXT_UNKNOWN
- void <clinit>()
```

</details>


















<details><summary>com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen</summary>

```diff
+ RealmsResetWorldScreen$ResetType typeToReset
+ RealmsResetWorldScreen$ResetWorldInfo worldInfoToReset
+ WorldTemplate worldTemplateToReset
+ void access$900(ResourceLocation,boolean,boolean)
+ void callback(WorldTemplate)
+ void lambda$switchSlot$7()
+ void resetWorld(RealmsResetWorldScreen$ResetWorldInfo)
+ void resetWorld(WorldTemplate,int,boolean)
+ void resetWorldWithTemplate(WorldTemplate)
+ void switchSlot()
+ void triggerResetWorld(RealmsResetWorldScreen$ResetWorldInfo)
- void access$600(ResourceLocation,boolean,boolean)
- void generationSelectionCallback(WorldGenerationInfo)
- void lambda$generationSelectionCallback$8(WorldGenerationInfo)
- void lambda$templateSelectionCallback$7(WorldTemplate)
- void resetWorld(Runnable)
- void startTask(LongRunningTask)
- void templateSelectionCallback(WorldTemplate)
```

</details>


<details><summary>com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen</summary>

```diff
+ RealmsScreenWithCallback lastScreen
- Consumer callback
+ boolean keyPressed(int,int,int)
+ void <init>(RealmsServer$WorldType)
+ void <init>(WorldTemplatePaginatedList)
+ void backButtonClicked()
- void <init>(RealmsServer$WorldType)
- void <init>(WorldTemplatePaginatedList)
- void onClose()
```

</details>









<details><summary>com.mojang.realmsclient.util.task.GetServerDetailsTask</summary>

```diff
+ Void lambda$null$0(Throwable)
+ void lambda$null$1(RealmsServerAddress)
+ void lambda$run$2(RealmsServerAddress,boolean)
+ void sleep(int)
- CompletableFuture scheduleResourcePackDownload(RealmsServerAddress)
- RealmsLongConfirmationScreen resourcePackDownloadConfirmationScreen(Function)
- RealmsLongRunningMcoTaskScreen connectScreen(RealmsServerAddress)
- RealmsServerAddress fetchServerAddress()
- void lambda$null$0(RealmsServerAddress)
- Void lambda$null$1(Throwable)
- void lambda$resourcePackDownloadConfirmationScreen$2(Function,boolean)
```

</details>







<details><summary>net.minecraft.CrashReportCategory</summary>

```diff
+ String formatLocation(BlockPos)
+ String formatLocation(double,double,double)
+ String formatLocation(int,int,int)
+ String lambda$populateBlockDetails$0(BlockPos)
+ void populateBlockDetails(BlockState)
- String formatLocation(BlockPos)
- String formatLocation(LevelHeightAccessor,double,double,double)
- String formatLocation(LevelHeightAccessor,int,int,int)
- String lambda$populateBlockDetails$0(BlockPos)
- void populateBlockDetails(BlockState)
```

</details>






<details><summary>net.minecraft.Util</summary>

```diff
- DataResult fixedSize(DoubleStream,int)
- Object getRandom(Random)
```

</details>
















<details><summary>net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance</summary>

```diff
+ boolean matches(ItemStack,int)
- boolean matches(ItemStack,int)
```

</details>






<details><summary>net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance</summary>

```diff
+ boolean matches(BeaconBlockEntity)
- boolean matches(int)
```

</details>














<details><summary>net.minecraft.advancements.critereon.EntityTypePredicate</summary>

```diff
- JsonSyntaxException lambda$fromJson$1(ResourceLocation)
```

</details>

<details><summary>net.minecraft.advancements.critereon.EntityTypePredicate$TagPredicate</summary>

```diff
- IllegalStateException lambda$serializeToJson$0()
```

</details>




















































<details><summary>net.minecraft.client.Minecraft$1</summary>

```diff
+ int[] $SwitchMap$net$minecraft$world$entity$vehicle$AbstractMinecart$Type
```

</details>




















<details><summary>net.minecraft.client.gui.GuiComponent</summary>

```diff
- void fillGradient(PoseStack,int,int,int,int,int,int,int)
```

</details>









<details><summary>net.minecraft.client.gui.components.BossHealthOverlay</summary>

```diff
+ boolean hasBoss()
```

</details>








<details><summary>net.minecraft.client.gui.components.LerpingBossEvent</summary>

```diff
+ float getPercent()
+ void setPercent(float)
- float getProgress()
- void setProgress(float)
```

</details>






<details><summary>net.minecraft.client.gui.screens.inventory.LoomScreen</summary>

```diff
- void init()
```

</details>
































<details><summary>net.minecraft.client.gui.screens.worldselection.CreateWorldScreen</summary>

```diff
+ boolean displayOptions
+ Button commandsButton
+ Button difficultyButton
+ Button modeButton
+ Difficulty effectiveDifficulty
+ Difficulty selectedDifficulty
- boolean worldGenSettingsVisible
- CycleButton commandsButton
- CycleButton difficultyButton
- CycleButton modeButton
- Difficulty difficulty
+ boolean access$700(CreateWorldScreen)
+ boolean lambda$copyTempDataPackDirToNewWorld$18(Path)
+ boolean lambda$createTempDataPackDirFromExistingWorld$20(Path)
+ boolean lambda$tryApplyNewDataPacks$11(String)
+ Component access$100()
+ Component access$400(CreateWorldScreen)
+ Component access$500(CreateWorldScreen)
+ CreateWorldScreen$SelectedGameMode access$200(CreateWorldScreen)
+ Difficulty access$600(CreateWorldScreen)
+ Object lambda$tryApplyNewDataPacks$16(Throwable)
+ void lambda$copyTempDataPackDirToNewWorld$19(Path)
+ void lambda$createTempDataPackDirFromExistingWorld$21(Path)
+ void lambda$init$1(Button)
+ void lambda$init$2(Button)
+ void lambda$init$3(Button)
+ void lambda$init$4(Button)
+ void lambda$init$7(Button)
+ void lambda$init$8(Button)
+ void lambda$null$13(boolean)
+ void lambda$null$14()
+ void lambda$null$15(ServerResources)
+ void lambda$null$5(GameRules)
+ void lambda$null$6(Optional)
+ void lambda$removeTempDataPackDir$17(Path)
+ void lambda$tryApplyNewDataPacks$12()
+ void setDisplayOptions(boolean)
+ void toggleDisplayOptions()
+ void updateDisplayOptions()
- boolean lambda$copyTempDataPackDirToNewWorld$20(Path)
- boolean lambda$createTempDataPackDirFromExistingWorld$22(Path)
- boolean lambda$tryApplyNewDataPacks$13(String)
- Difficulty getEffectiveDifficulty()
- MutableComponent lambda$init$1(CycleButton)
- MutableComponent lambda$init$4(CycleButton)
- Object lambda$tryApplyNewDataPacks$18(Throwable)
- void lambda$copyTempDataPackDirToNewWorld$21(Path)
- void lambda$createTempDataPackDirFromExistingWorld$23(Path)
- void lambda$init$11(Button)
- void lambda$init$12(Button)
- void lambda$init$2(CreateWorldScreen$SelectedGameMode)
- void lambda$init$3(Difficulty)
- void lambda$init$5(Boolean)
- void lambda$init$6(Button)
- void lambda$null$15(boolean)
- void lambda$null$16()
- void lambda$null$17(ServerResources)
- void lambda$null$7(GameRules)
- void lambda$null$8(Optional)
- void lambda$removeTempDataPackDir$19(Path)
- void lambda$tryApplyNewDataPacks$14()
- void refreshWorldGenSettingsVisibility()
- void setWorldGenSettingsVisible(boolean)
- void toggleWorldGenSettingsVisibility()
```

</details>









<details><summary>net.minecraft.client.gui.spectator.PlayerMenuItem</summary>

```diff
+ TextComponent name
- Component name
```

</details>


















<details><summary>net.minecraft.client.model.ArmorStandModel</summary>

```diff
+ ModelPart bodyStick1
+ ModelPart bodyStick2
- ModelPart leftBodyStick
- ModelPart rightBodyStick
+ void <init>()
+ void <init>(float)
- LayerDefinition createBodyLayer()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.HoglinModel</summary>

```diff
+ ModelPart backLeftLeg
+ ModelPart backRightLeg
+ ModelPart frontLeftLeg
+ ModelPart frontRightLeg
- ModelPart leftFrontLeg
- ModelPart leftHindLeg
- ModelPart rightFrontLeg
- ModelPart rightHindLeg
+ void <init>()
- LayerDefinition createBodyLayer()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.SnowGolemModel</summary>

```diff
+ ModelPart arm1
+ ModelPart arm2
+ ModelPart piece1
+ ModelPart piece2
- ModelPart leftArm
- ModelPart rightArm
- ModelPart root
- ModelPart upperBody
+ Iterable parts()
+ void <init>()
- LayerDefinition createBodyLayer()
- ModelPart root()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.SquidModel</summary>

```diff
+ ImmutableList parts
+ ModelPart body
- ModelPart root
+ Iterable parts()
+ void <init>()
- LayerDefinition createBodyLayer()
- ModelPart lambda$new$0(ModelPart,int)
- ModelPart root()
- String createTentacleName(int)
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.TridentModel</summary>

```diff
+ ModelPart pole
- ModelPart root
+ void <init>()
- LayerDefinition createLayer()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.TropicalFishModelB</summary>

```diff
+ ModelPart body
+ ModelPart bottomFin
+ ModelPart leftFin
+ ModelPart rightFin
+ ModelPart topFin
- ModelPart root
+ Iterable parts()
+ void <init>(float)
- LayerDefinition createBodyLayer(CubeDeformation)
- ModelPart root()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.VexModel</summary>

```diff
+ void <init>()
- LayerDefinition createBodyLayer()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.VillagerModel</summary>

```diff
+ ModelPart arms
+ ModelPart body
+ ModelPart jacket
+ ModelPart leg0
+ ModelPart leg1
- ModelPart leftLeg
- ModelPart rightLeg
- ModelPart root
+ Iterable parts()
+ void <init>(float,int,int)
+ void <init>(float)
- MeshDefinition createBodyModel()
- ModelPart root()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.WitherBossModel</summary>

```diff
+ ImmutableList parts
+ ModelPart[] heads
+ ModelPart[] upperBodyParts
- ModelPart centerHead
- ModelPart leftHead
- ModelPart ribcage
- ModelPart rightHead
- ModelPart root
- ModelPart tail
+ ImmutableList parts()
+ Iterable parts()
+ void <init>(float)
- LayerDefinition createBodyLayer(CubeDeformation)
- ModelPart root()
- void <init>(ModelPart)
- void setupHeadRotation(ModelPart,int)
```

</details>

<details><summary>net.minecraft.client.model.ZombieModel</summary>

```diff
+ void <init>(float,boolean)
+ void <init>(float,float,int,int)
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.dragon.DragonHeadModel</summary>

```diff
+ void <init>(float)
- LayerDefinition createHeadLayer()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.model.geom.ModelPart</summary>

```diff
+ boolean mirror
+ float xTexSize
+ float yTexSize
+ int xTexOffs
+ int yTexOffs
+ ObjectList children
+ ObjectList cubes
- List cubes
- Map children
+ ModelPart addBox(float,float,float,float,float,float,boolean)
+ ModelPart addBox(float,float,float,float,float,float)
+ ModelPart addBox(String,float,float,float,int,int,int,float,int,int)
+ ModelPart createShallowCopy()
+ ModelPart setTexSize(int,int)
+ ModelPart texOffs(int,int)
+ void <init>()
+ void <init>(int,int,int,int)
+ void <init>(Model,int,int)
+ void <init>(Model)
+ void addBox(float,float,float,float,float,float,float,boolean)
+ void addBox(float,float,float,float,float,float,float,float,float)
+ void addBox(float,float,float,float,float,float,float)
+ void addBox(int,int,float,float,float,float,float,float,float,float,float,boolean,boolean)
+ void addChild(ModelPart)
- boolean isEmpty()
- ModelPart getChild(String)
- PartPose storePose()
- Stream getAllParts()
- void <init>(Map)
- void lambda$visit$0(ModelPart)
- void loadPose(PartPose)
- void visit(ModelPart$Visitor)
- void visit(String)
```

</details>



<details><summary>net.minecraft.client.multiplayer.ClientAdvancements</summary>

```diff
+ Map getProgress()
```

</details>

<details><summary>net.minecraft.client.multiplayer.ClientChunkCache</summary>

```diff
+ boolean isEntityTickingChunk(Entity)
+ LevelChunk replaceWithPacketData(CompoundTag,int,boolean)
- LevelChunk replaceWithPacketData(CompoundTag,int)
```

</details>


<details><summary>net.minecraft.client.multiplayer.ClientLevel</summary>

```diff
+ Int2ObjectMap entitiesById
- EntityTickList tickingEntities
- TransientEntitySectionManager entityStorage
+ int lambda$getBlockTint$7(ColorResolver)
+ String lambda$fillReportDetails$5()
+ String lambda$tickNonPassenger$1(Entity)
+ Vec3 getSkyColor(BlockPos,float)
+ void lambda$clearTintCaches$3(BlockTintCache)
+ void lambda$doAnimateTick$4(AmbientParticleSettings)
+ void lambda$onChunkLoaded$2(BlockTintCache)
+ void onChunkLoaded(int,int)
+ void onEntityRemoved(Entity)
+ void reAddEntitiesToChunk(LevelChunk)
+ void removeAllPendingEntityRemovals()
+ void removeEntity(int)
+ void setMapData(MapItemSavedData)
+ void updateChunkPos(Entity)
- EntityTickList access$100(ClientLevel)
- int lambda$getBlockTint$9(ColorResolver)
- LevelEntityGetter getEntities()
- List access$200(ClientLevel)
- String gatherChunkSourceStats()
- String lambda$fillReportDetails$7()
- String lambda$tickNonPassenger$2(Entity)
- Vec3 getSkyColor(Vec3,float)
- Vec3 lambda$getSkyColor$8(BiomeManager,int,int,int)
- void addDestroyBlockEffect(BlockState)
- void gameEvent(BlockPos)
- void lambda$clearTintCaches$4(BlockTintCache)
- void lambda$doAnimateTick$5(AmbientParticleSettings)
- void lambda$onChunkLoaded$3(BlockTintCache)
- void lambda$tickEntities$1(Entity)
- void onChunkLoaded(ChunkPos)
- void removeEntity(Entity$RemovalReason)
- void setMapData(MapItemSavedData)
```

</details>

<details><summary>net.minecraft.client.multiplayer.ClientLevel$ClientLevelData</summary>

```diff
+ void fillCrashReportCategory(CrashReportCategory)
- void fillCrashReportCategory(LevelHeightAccessor)
```

</details>

























<details><summary>net.minecraft.client.player.AbstractClientPlayer</summary>

```diff
+ ResourceLocation getSkullPath(String)
```

</details>












<details><summary>net.minecraft.client.renderer.GameRenderer</summary>

```diff
+ Matrix4f getProjectionMatrix(Camera,float,boolean)
- float getDepthFar()
- Matrix4f getProjectionMatrix(double)
```

</details>





<details><summary>net.minecraft.client.renderer.blockentity.ChestRenderer</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- LayerDefinition createDoubleBodyLeftLayer()
- LayerDefinition createDoubleBodyRightLayer()
- LayerDefinition createSingleBodyLayer()
- void <init>(BlockEntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.blockentity.EnchantTableRenderer</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.blockentity.PistonHeadRenderer</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.blockentity.SignRenderer</summary>

```diff
+ SignRenderer$SignModel signModel
- Font font
- Map signModels
+ FormattedCharSequence lambda$render$0(Component)
+ Material getMaterial(Block)
+ void <init>(BlockEntityRenderDispatcher)
- FormattedCharSequence lambda$render$2(Component)
- LayerDefinition createSignLayer()
- SignRenderer$SignModel createSignModel(WoodType)
- SignRenderer$SignModel lambda$new$1(WoodType)
- void <init>(BlockEntityRendererProvider$Context)
- WoodType getWoodType(Block)
- WoodType lambda$new$0(WoodType)
```

</details>

<details><summary>net.minecraft.client.renderer.blockentity.SkullBlockRenderer</summary>

```diff
+ Map MODEL_BY_TYPE
- Map modelByType
+ void <init>(BlockEntityRenderDispatcher)
+ void lambda$static$1(HashMap)
+ void renderSkull(MultiBufferSource,int)
- Map createSkullRenderers(EntityModelSet)
- void <init>(BlockEntityRendererProvider$Context)
- void renderSkull(RenderType)
```

</details>

<details><summary>net.minecraft.client.renderer.blockentity.StructureBlockRenderer</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>






<details><summary>net.minecraft.client.renderer.chunk.VisGraph</summary>

```diff
+ Set floodFill(BlockPos)
```

</details>









<details><summary>net.minecraft.client.renderer.debug.DebugRenderer</summary>

```diff
- GameEventListenerRenderer gameEventListenerRenderer
```

</details>

<details><summary>net.minecraft.client.renderer.entity.BeeRenderer</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.BoatRenderer</summary>

```diff
+ BoatModel model
+ ResourceLocation[] BOAT_TEXTURE_LOCATIONS
- Map boatResources
+ void <clinit>()
+ void <init>(EntityRenderDispatcher)
- Boat$Type lambda$new$0(Boat$Type)
- Pair lambda$new$1(Boat$Type)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.CaveSpiderRenderer</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.ChickenRenderer</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.CowRenderer</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.DolphinRenderer</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.DrownedRenderer</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.EndCrystalRenderer</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- LayerDefinition createBodyLayer()
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel</summary>

```diff
+ void <init>()
- void <init>(ModelPart)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.EndermiteRenderer</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.EntityRenderer</summary>

```diff
- Font font
+ EntityRenderDispatcher getDispatcher()
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>


<details><summary>net.minecraft.client.renderer.entity.layers.SheepFurLayer</summary>

```diff
+ void <init>(RenderLayerParent)
- void <init>(EntityModelSet)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.layers.SlimeOuterLayer</summary>

```diff
+ void <init>(RenderLayerParent)
- void <init>(EntityModelSet)
```

</details>


<details><summary>net.minecraft.client.renderer.entity.layers.StrayClothingLayer</summary>

```diff
+ void <init>(RenderLayerParent)
- void <init>(EntityModelSet)
```

</details>

<details><summary>net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer</summary>

```diff
+ void <init>(RenderLayerParent)
- void <init>(EntityModelSet)
```

</details>





<details><summary>net.minecraft.client.renderer.item.ItemProperties$1</summary>

```diff
+ float call(LivingEntity)
- float call(LivingEntity,int)
```

</details>

















<details><summary>net.minecraft.client.resources.DefaultClientPackResources</summary>

```diff
+ void <init>(AssetIndex)
- void <init>(AssetIndex)
```

</details>











<details><summary>net.minecraft.client.resources.metadata.animation.AnimationMetadataSection</summary>

```diff
+ boolean hasCustomFrameTime(int)
```

</details>

















<details><summary>net.minecraft.client.resources.sounds.AbstractSoundInstance</summary>

```diff
+ boolean priority
+ boolean hasPriority()
```

</details>




















<details><summary>net.minecraft.client.server.LanServer</summary>

```diff
+ boolean isUpToDate()
```

</details>





















<details><summary>net.minecraft.commands.CommandFunction$CommandEntry</summary>

```diff
+ void execute(ArrayDeque,int)
- void execute(Deque,int)
```

</details>

<details><summary>net.minecraft.commands.CommandFunction$FunctionEntry</summary>

```diff
+ void execute(ArrayDeque,int)
+ void lambda$execute$0(CommandFunction)
- void execute(Deque,int)
- void lambda$execute$0(CommandFunction)
```

</details>





<details><summary>net.minecraft.commands.arguments.AngleArgument</summary>

```diff
- SimpleCommandExceptionType ERROR_INVALID_ANGLE
```

</details>



























<details><summary>net.minecraft.core.BlockPos</summary>

```diff
+ boolean isOutsideBuildHeight(long)
- BlockPos atY(int)
```

</details>



<details><summary>net.minecraft.core.BlockPos$MutableBlockPos</summary>

```diff
+ void setX(int)
+ void setY(int)
+ void setZ(int)
- BlockPos$MutableBlockPos setX(int)
- BlockPos$MutableBlockPos setY(int)
- BlockPos$MutableBlockPos setZ(int)
- Vec3i setX(int)
- Vec3i setY(int)
- Vec3i setZ(int)
```

</details>

<details><summary>net.minecraft.core.BlockSourceImpl</summary>

```diff
+ Material getMaterial()
```

</details>



































<details><summary>net.minecraft.gametest.framework.GameTestSequence</summary>

```diff
+ GameTestSequence thenWait(Runnable)
+ GameTestSequence thenWait(Runnable)
+ void lambda$thenFail$3(Supplier)
+ void lambda$thenTrigger$4(GameTestSequence$Condition)
- GameTestSequence thenExecuteFor(Runnable)
- GameTestSequence thenWaitUntil(Runnable)
- GameTestSequence thenWaitUntil(Runnable)
- void lambda$thenExecuteFor$3(Runnable)
- void lambda$thenFail$4(Supplier)
- void lambda$thenTrigger$5(GameTestSequence$Condition)
```

</details>

<details><summary>net.minecraft.gametest.framework.GameTestServer</summary>

```diff
+ boolean publishServer(GameType,boolean,int)
+ void <init>(WritableRegistry)
- void <init>(Registry)
```

</details>

<details><summary>net.minecraft.gametest.framework.GameTestTicker</summary>

```diff
+ GameTestTicker singleton
- GameTestTicker SINGLETON
```

</details>

<details><summary>net.minecraft.gametest.framework.StructureUtils</summary>

```diff
- Logger LOGGER
+ boolean lambda$clearSpaceForStructure$1(Entity)
+ boolean lambda$findStructureBlockContainingPos$2(BlockPos)
+ int lambda$findNearestStructureBlock$3(BlockPos)
+ void lambda$clearSpaceForStructure$0(BlockPos)
- boolean lambda$clearSpaceForStructure$3(Entity)
- boolean lambda$findStructureBlockContainingPos$4(BlockPos)
- boolean lambda$main$0(Path)
- int lambda$findNearestStructureBlock$5(BlockPos)
- void lambda$clearSpaceForStructure$2(BlockPos)
- void lambda$main$1(Path)
- void main(String[])
```

</details>



<details><summary>net.minecraft.gametest.framework.TestFunction</summary>

```diff
- int maxAttempts
- int requiredSuccesses
- boolean isFlaky()
- int getMaxAttempts()
- int getRequiredSuccesses()
- void <init>(Consumer)
```

</details>













<details><summary>net.minecraft.nbt.ListTag</summary>

```diff
+ ByteSet INLINE_ELEMENT_TYPES
+ Component getPrettyDisplay(String,int)
+ void stripEmptyChildren()
- void accept(TagVisitor)
```

</details>

<details><summary>net.minecraft.nbt.LongArrayTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>

<details><summary>net.minecraft.nbt.LongTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>





<details><summary>net.minecraft.nbt.NumericTag</summary>

```diff
- String toString()
```

</details>


<details><summary>net.minecraft.nbt.Tag</summary>

```diff
+ ChatFormatting SYNTAX_HIGHLIGHTING_KEY
+ ChatFormatting SYNTAX_HIGHLIGHTING_NUMBER
+ ChatFormatting SYNTAX_HIGHLIGHTING_NUMBER_TYPE
+ ChatFormatting SYNTAX_HIGHLIGHTING_STRING
+ Component getPrettyDisplay(java.lang.String,int)
- void accept(net.minecraft.nbt.TagVisitor)
+ boolean isEmpty()
+ Component getPrettyDisplay()
+ void <clinit>()
+ void stripEmptyChildren()
```

</details>


































<details><summary>net.minecraft.network.protocol.game.ClientGamePacketListener</summary>

```diff
- void handleAddVibrationSignal(net.minecraft.network.protocol.game.ClientboundAddVibrationSignalPacket)
```

</details>























<details><summary>net.minecraft.server.commands.SpreadPlayersCommand$Position</summary>

```diff
+ double access$000(SpreadPlayersCommand$Position)
+ double access$002(SpreadPlayersCommand$Position,double)
+ void <init>(double,double)
+ void set(double,double)
- double access$200(SpreadPlayersCommand$Position)
- double access$202(SpreadPlayersCommand$Position,double)
- void <init>(SpreadPlayersCommand$1)
```

</details>















<details><summary>net.minecraft.server.dedicated.DedicatedServer</summary>

```diff
+ boolean publishServer(GameType,boolean,int)
- boolean isResourcePackRequired()
- GameType getForcedGameType()
```

</details>

<details><summary>net.minecraft.server.dedicated.DedicatedServerProperties</summary>

```diff
+ int maxBuildHeight
- boolean requireResourcePack
+ Integer lambda$new$2(Integer)
```

</details>











<details><summary>net.minecraft.server.level.ChunkMap</summary>

```diff
- ChunkStatusUpdateListener chunkStatusListener
+ ChunkAccess lambda$null$25(ChunkAccess)
+ ChunkHolder$FullChunkStatus lambda$null$24(ChunkHolder)
+ ChunkMap$DistanceManager getDistanceManager()
+ ChunkStatus lambda$getEntityTickingRangeFuture$2(int)
+ ChunkStatus lambda$postProcess$28(int)
+ CompletableFuture getEntityTickingRangeFuture(ChunkPos)
+ CompletableFuture postProcess(ChunkHolder)
+ CompletableFuture unpackTicks(ChunkHolder)
+ Either lambda$getEntityTickingRangeFuture$4(Either)
+ Either lambda$null$29(List)
+ Either lambda$null$33(LevelChunk)
+ Either lambda$postProcess$30(Either)
+ Either lambda$protoChunkToFullChunk$26(Either)
+ Either lambda$unpackTicks$37(Either)
+ int access$700(ServerPlayer,boolean)
+ Integer lambda$dumpChunks$41(LevelChunk)
+ LevelChunk lambda$null$36(ChunkAccess)
+ Optional lambda$dumpChunks$40(ChunkAccess)
+ void <init>(Supplier,int,boolean)
+ void lambda$null$32(ServerPlayer)
+ void lambda$postProcess$31(Runnable)
+ void lambda$postProcess$34(Either)
+ void lambda$postProcess$35(Runnable)
+ void lambda$protoChunkToFullChunk$27(Runnable)
+ void lambda$setViewDistance$39(ServerPlayer)
+ void lambda$unpackTicks$38(Runnable)
- ChunkAccess lambda$null$26(ChunkAccess)
- ChunkHolder$FullChunkStatus lambda$null$25(ChunkHolder)
- ChunkStatus lambda$prepareEntityTickingChunk$2(int)
- ChunkStatus lambda$prepareTickingChunk$29(int)
- CompletableFuture prepareAccessibleChunk(ChunkHolder)
- CompletableFuture prepareEntityTickingChunk(ChunkPos)
- CompletableFuture prepareTickingChunk(ChunkHolder)
- DistanceManager getDistanceManager()
- Either lambda$null$30(List)
- Either lambda$prepareAccessibleChunk$38(Either)
- Either lambda$prepareEntityTickingChunk$4(Either)
- Either lambda$prepareTickingChunk$31(Either)
- Either lambda$protoChunkToFullChunk$27(Either)
- LevelChunk lambda$null$37(List)
- Optional lambda$dumpChunks$41(ChunkAccess)
- void <init>(Supplier,int,boolean)
- void lambda$null$24(LevelChunk)
- void lambda$null$33(ServerPlayer)
- void lambda$null$34(LevelChunk)
- void lambda$prepareAccessibleChunk$39(Runnable)
- void lambda$prepareTickingChunk$32(Runnable)
- void lambda$prepareTickingChunk$35(Either)
- void lambda$prepareTickingChunk$36(Runnable)
- void lambda$protoChunkToFullChunk$28(Runnable)
- void lambda$setViewDistance$40(ServerPlayer)
- void onFullChunkStatusChange(ChunkHolder$FullChunkStatus)
- void postLoadProtoChunk(List)
```

</details>






<details><summary>net.minecraft.server.level.DemoMode</summary>

```diff
+ void <init>(ServerLevel)
- void <init>(ServerPlayer)
```

</details>















<details><summary>net.minecraft.server.packs.repository.Pack$PackConstructor</summary>

```diff
+ Pack create(java.lang.String,boolean,java.util.function.Supplier,net.minecraft.server.packs.PackResources,net.minecraft.server.packs.metadata.pack.PackMetadataSection,net.minecraft.server.packs.repository.Pack$Position,net.minecraft.server.packs.repository.PackSource)
- Pack create(java.lang.String,net.minecraft.network.chat.Component,boolean,java.util.function.Supplier,net.minecraft.server.packs.metadata.pack.PackMetadataSection,net.minecraft.server.packs.repository.Pack$Position,net.minecraft.server.packs.repository.PackSource)
```

</details>

<details><summary>net.minecraft.server.packs.repository.PackCompatibility</summary>

```diff
+ PackCompatibility forFormat(int)
- PackCompatibility forFormat(PackType)
- PackCompatibility forMetadata(PackType)
```

</details>


<details><summary>net.minecraft.server.packs.repository.ServerPacksSource</summary>

```diff
- PackMetadataSection BUILT_IN_METADATA
- void <clinit>()
```

</details>





<details><summary>net.minecraft.server.packs.resources.ReloadableResourceManager</summary>

```diff
+ ReloadInstance createFullReload(java.util.concurrent.Executor,java.util.concurrent.Executor,java.util.concurrent.CompletableFuture,java.util.List)
+ ReloadInstance createQueuedReload(java.util.concurrent.Executor,java.util.concurrent.Executor,java.util.concurrent.CompletableFuture)
- ReloadInstance createReload(java.util.concurrent.Executor,java.util.concurrent.Executor,java.util.concurrent.CompletableFuture,java.util.List)
```

</details>





<details><summary>net.minecraft.server.packs.resources.SimpleReloadableResourceManager</summary>

```diff
+ List recentlyRegistered
+ Object lambda$createFullReload$0(List)
+ ReloadInstance createFullReload(List)
+ ReloadInstance createQueuedReload(CompletableFuture)
+ ReloadInstance createReload(CompletableFuture)
- Object lambda$createReload$0(List)
- ReloadInstance createReload(List)
```

</details>









<details><summary>net.minecraft.server.players.PlayerList</summary>

```diff
+ GameType overrideGameMode
+ void blackList(GameProfile)
+ void setOverrideGameMode(GameType)
+ void updatePlayerGameMode(ServerLevel)
+ void whiteList(GameProfile)
- void lambda$remove$1(Entity)
```

</details>

<details><summary>net.minecraft.server.players.ServerOpList</summary>

```diff
+ GameProfile find(String)
+ int getOpLevel(GameProfile)
- String[] lambda$getUserList$0(int)
```

</details>


<details><summary>net.minecraft.server.players.UserBanList</summary>

```diff
+ GameProfile find(String)
- String[] lambda$getUserList$0(int)
```

</details>

<details><summary>net.minecraft.server.players.UserWhiteList</summary>

```diff
+ GameProfile find(String)
- String[] lambda$getUserList$0(int)
```

</details>








<details><summary>net.minecraft.sounds.SoundEvents</summary>

```diff
- SoundEvent AMETHYST_BLOCK_BREAK
- SoundEvent AMETHYST_BLOCK_CHIME
- SoundEvent AMETHYST_BLOCK_FALL
- SoundEvent AMETHYST_BLOCK_HIT
- SoundEvent AMETHYST_BLOCK_PLACE
- SoundEvent AMETHYST_BLOCK_STEP
- SoundEvent AMETHYST_CLUSTER_BREAK
- SoundEvent AMETHYST_CLUSTER_FALL
- SoundEvent AMETHYST_CLUSTER_HIT
- SoundEvent AMETHYST_CLUSTER_PLACE
- SoundEvent AMETHYST_CLUSTER_STEP
- SoundEvent AXOLOTL_ATTACK
- SoundEvent AXOLOTL_DEATH
- SoundEvent AXOLOTL_HURT
- SoundEvent AXOLOTL_IDLE_AIR
- SoundEvent AXOLOTL_IDLE_WATER
- SoundEvent AXOLOTL_SPLASH
- SoundEvent AXOLOTL_SWIM
- SoundEvent BUCKET_EMPTY_AXOLOTL
- SoundEvent BUCKET_EMPTY_POWDER_SNOW
- SoundEvent BUCKET_FILL_AXOLOTL
- SoundEvent BUCKET_FILL_POWDER_SNOW
- SoundEvent CAKE_ADD_CANDLE
- SoundEvent CALCITE_BREAK
- SoundEvent CALCITE_FALL
- SoundEvent CALCITE_HIT
- SoundEvent CALCITE_PLACE
- SoundEvent CALCITE_STEP
- SoundEvent CANDLE_AMBIENT
- SoundEvent CANDLE_BREAK
- SoundEvent CANDLE_EXTINGUISH
- SoundEvent CANDLE_FALL
- SoundEvent CANDLE_HIT
- SoundEvent CANDLE_PLACE
- SoundEvent CANDLE_STEP
- SoundEvent COPPER_BREAK
- SoundEvent COPPER_FALL
- SoundEvent COPPER_HIT
- SoundEvent COPPER_PLACE
- SoundEvent COPPER_STEP
- SoundEvent DRIPSTONE_BLOCK_BREAK
- SoundEvent DRIPSTONE_BLOCK_FALL
- SoundEvent DRIPSTONE_BLOCK_HIT
- SoundEvent DRIPSTONE_BLOCK_PLACE
- SoundEvent DRIPSTONE_BLOCK_STEP
- SoundEvent LARGE_AMETHYST_BUD_BREAK
- SoundEvent LARGE_AMETHYST_BUD_PLACE
- SoundEvent MEDIUM_AMETHYST_BUD_BREAK
- SoundEvent MEDIUM_AMETHYST_BUD_PLACE
- SoundEvent MINECART_INSIDE_UNDERWATER
- SoundEvent PLAYER_HURT_FREEZE
- SoundEvent POINTED_DRIPSTONE_BREAK
- SoundEvent POINTED_DRIPSTONE_DRIP_LAVA
- SoundEvent POINTED_DRIPSTONE_DRIP_LAVA_INTO_CAULDRON
- SoundEvent POINTED_DRIPSTONE_DRIP_WATER
- SoundEvent POINTED_DRIPSTONE_DRIP_WATER_INTO_CAULDRON
- SoundEvent POINTED_DRIPSTONE_FALL
- SoundEvent POINTED_DRIPSTONE_HIT
- SoundEvent POINTED_DRIPSTONE_LAND
- SoundEvent POINTED_DRIPSTONE_PLACE
- SoundEvent POINTED_DRIPSTONE_STEP
- SoundEvent POWDER_SNOW_BREAK
- SoundEvent POWDER_SNOW_FALL
- SoundEvent POWDER_SNOW_HIT
- SoundEvent POWDER_SNOW_PLACE
- SoundEvent POWDER_SNOW_STEP
- SoundEvent SCULK_CLICKING
- SoundEvent SCULK_CLICKING_STOP
- SoundEvent SCULK_SENSOR_BREAK
- SoundEvent SCULK_SENSOR_FALL
- SoundEvent SCULK_SENSOR_HIT
- SoundEvent SCULK_SENSOR_PLACE
- SoundEvent SCULK_SENSOR_STEP
- SoundEvent SMALL_AMETHYST_BUD_BREAK
- SoundEvent SMALL_AMETHYST_BUD_PLACE
- SoundEvent SPYGLASS_STOP_USING
- SoundEvent SPYGLASS_USE
- SoundEvent TUFF_BREAK
- SoundEvent TUFF_FALL
- SoundEvent TUFF_HIT
- SoundEvent TUFF_PLACE
- SoundEvent TUFF_STEP
```

</details>





<details><summary>net.minecraft.stats.StatType</summary>

```diff
+ int size()
```

</details>


<details><summary>net.minecraft.tags.BlockTags</summary>

```diff
- Tag$Named CANDLE_CAKES
- Tag$Named CANDLES
- Tag$Named CAULDRONS
- Tag$Named CRYSTAL_SOUND_BLOCKS
- Tag$Named DRIPSTONE_REPLACEABLE
- Tag$Named INSIDE_STEP_SOUND_BLOCKS
- Tag$Named OCCLUDES_VIBRATION_SIGNALS
+ List getWrappers()
```

</details>

<details><summary>net.minecraft.tags.FluidTags</summary>

```diff
- List KNOWN_TAGS
+ List getWrappers()
- List getStaticTags()
```

</details>

<details><summary>net.minecraft.tags.TagContainer</summary>

```diff
+ TagCollection getBlocks()
+ TagCollection getEntityTypes()
+ TagCollection getFluids()
+ TagCollection getItems()
- Logger LOGGER
- Map collections
+ TagContainer deserializeFromNetwork(FriendlyByteBuf)
+ TagContainer of(TagCollection)
+ void serializeToNetwork(FriendlyByteBuf)
- Logger access$000()
- Map serializeToNetwork(RegistryAccess)
- ResourceLocation getIdOrThrow(Supplier)
- Tag getTagOrThrow(Function)
- TagCollection get(ResourceKey)
- TagCollection getOrEmpty(ResourceKey)
- TagContainer deserializeFromNetwork(Map)
- void <init>(Map)
- void <init>(TagContainer$1)
- void acceptCap(TagCollection)
- void addTagsFromPayload(TagCollection$NetworkPayload)
- void getAll(TagContainer$CollectionConsumer)
- void lambda$deserializeFromNetwork$1(TagCollection$NetworkPayload)
- void lambda$getAll$0(TagCollection)
```

</details>

<details><summary>net.minecraft.tags.TagLoader</summary>

```diff
+ String name
+ boolean lambda$null$0(String)
+ CompletableFuture prepare(Executor)
+ Map lambda$prepare$2(ResourceManager)
+ Object lambda$load$3(ResourceLocation)
+ Tag$Builder lambda$null$1(ResourceLocation)
+ TagCollection load(Map)
+ void <init>(String)
+ void lambda$load$4(Tag$Builder)
- boolean isCyclic(ResourceLocation)
- boolean lambda$isCyclic$3(ResourceLocation)
- boolean lambda$load$0(String)
- Map load(ResourceManager)
- Object lambda$build$4(ResourceLocation)
- Tag$Builder lambda$load$1(ResourceLocation)
- TagCollection build(Map)
- TagCollection loadAndBuild(ResourceManager)
- void <init>(String)
- void addDependencyIfNotCyclic(ResourceLocation)
- void lambda$build$12(ResourceLocation)
- void lambda$build$6(Tag$Builder)
- void lambda$build$8(Tag$Builder)
- void lambda$null$10(Tag)
- void lambda$null$11(Tag$Builder)
- void lambda$null$5(ResourceLocation)
- void lambda$null$7(ResourceLocation)
- void lambda$null$9(Collection)
- void lambda$visitDependenciesAndElement$2(ResourceLocation)
- void visitDependenciesAndElement(BiConsumer)
```

</details>
























































<details><summary>net.minecraft.util.datafix.fixes.JigsawRotationFix</summary>

```diff
+ Map renames
- Map RENAMES
```

</details>























































<details><summary>net.minecraft.util.datafix.schemas.V99</summary>

```diff
+ Dynamic lambda$addNames$35(Dynamic)
+ Dynamic lambda$null$33(Dynamic)
+ Dynamic lambda$null$34(Dynamic)
+ void lambda$static$32(HashMap)
- Dynamic lambda$addNames$36(Dynamic)
- Dynamic lambda$null$34(Dynamic)
- Dynamic lambda$null$35(Dynamic)
- TypeTemplate lambda$registerTypes$32(Schema)
- void lambda$static$33(HashMap)
```

</details>























<details><summary>net.minecraft.world.Difficulty</summary>

```diff
+ Difficulty nextById()
```

</details>










<details><summary>net.minecraft.world.damagesource.DamageSource</summary>

```diff
- boolean damageHelmet
- DamageSource FALLING_STALACTITE
- DamageSource FREEZE
- boolean isDamageHelmet()
- DamageSource damageHelmet()
```

</details>





<details><summary>net.minecraft.world.effect.MobEffectInstance</summary>

```diff
+ boolean splash
+ void setSplash(boolean)
```

</details>



<details><summary>net.minecraft.world.entity.Entity</summary>

```diff
+ boolean forceChunkAddition
+ boolean forcedLoading
+ boolean inChunk
+ boolean movedSinceLastChunkCheck
+ boolean removed
+ int xChunk
+ int yChunk
+ int zChunk
+ List passengers
- boolean bodyIsInPowderSnow
- Entity$RemovalReason removalReason
- EntityDataAccessor DATA_TICKS_FROZEN
- EntityInLevelCallback levelCallback
- float crystalSoundIntensity
- ImmutableList passengers
- int lastCrystalSoundPlayTick
+ boolean checkAndResetForcedChunkAdditionFlag()
+ boolean checkAndResetUpdateChunkPos()
+ boolean hasOnePlayerPassenger()
+ boolean hasPassenger(Class)
+ boolean lambda$null$3(BlockPos)
+ boolean setSlot(ItemStack)
+ Collection getIndirectPassengers()
+ PortalInfo lambda$findDimensionEntryPoint$4(BlockUtil$FoundRectangle)
+ String lambda$fillCrashReportCategory$5()
+ Style lambda$getDisplayName$9(Style)
+ void burn(int)
+ void fillIndirectPassengers(Set)
+ void lambda$teleportTo$10(Entity)
+ void remove()
+ void setDropContainerContent(boolean)
+ void setLevel(Level)
- boolean canFreeze()
- boolean hasExactlyOnePlayerPassenger()
- boolean hasPassenger(Predicate)
- boolean isAlwaysTicking()
- boolean isFullyFrozen()
- boolean isRemoved()
- boolean lambda$hasExactlyOnePlayerPassenger$13(Entity)
- boolean lambda$hasIndirectPassenger$14(Entity)
- boolean lambda$null$4(BlockPos)
- boolean lambda$removePassenger$3(Entity)
- boolean occludesVibrations()
- boolean shouldBeSaved()
- ChunkPos chunkPosition()
- Entity getFirstPassenger()
- Entity$RemovalReason getRemovalReason()
- float getPercentFrozen()
- GameEventListenerRegistrar getGameEventListenerRegistrar()
- int getBlockX()
- int getBlockY()
- int getBlockZ()
- int getTicksFrozen()
- int getTicksRequiredToFreeze()
- ItemStack getPickResult()
- Iterable getIndirectPassengers()
- Iterator lambda$getIndirectPassengers$12()
- PortalInfo lambda$findDimensionEntryPoint$5(BlockUtil$FoundRectangle)
- SlotAccess getSlot(int)
- Stream getIndirectPassengersStream()
- Stream getPassengersAndSelf()
- String lambda$fillCrashReportCategory$9()
- Style lambda$getDisplayName$10(Style)
- void checkOutOfWorld()
- void discard()
- void gameEvent(GameEvent)
- void gameEvent(GameEvent)
- void lambda$teleportTo$11(Entity)
- void recreateFromPacket(ClientboundAddEntityPacket)
- void remove(Entity$RemovalReason)
- void setBodyIsInPowderSnow(boolean)
- void setLevelCallback(EntityInLevelCallback)
- void setRemoved(Entity$RemovalReason)
- void setTicksFrozen(int)
- void unsetRemoved()
```

</details>



<details><summary>net.minecraft.world.entity.EquipmentSlot</summary>

```diff
- int getIndex(int)
```

</details>

<details><summary>net.minecraft.world.entity.ExperienceOrb</summary>

```diff
+ int followingTime
+ int throwTime
+ int tickCount
- int count
+ void burn(int)
- boolean canMerge(ExperienceOrb,int,int)
- boolean canMerge(ExperienceOrb)
- boolean lambda$tryMergeToExisting$0(ExperienceOrb)
- boolean tryMergeToExisting(Vec3,int)
- SoundSource getSoundSource()
- void award(Vec3,int)
- void merge(ExperienceOrb)
- void scanForEntities()
```

</details>



<details><summary>net.minecraft.world.entity.LivingEntity</summary>

```diff
+ Iterable getHandSlots()
- UUID SPEED_MODIFIER_POWDER_SNOW_UUID
+ boolean lambda$isHolding$5(Item)
- boolean canBeTargeted()
- boolean canFreeze()
- boolean lambda$createEquipmentSlotAccess$11(ItemStack)
- boolean lambda$isHolding$5(ItemStack)
- EquipmentSlot getEquipmentSlot(int)
- EquipmentSlot getEquipmentSlotForItem(ItemStack)
- SlotAccess createEquipmentSlotAccess(EquipmentSlot)
- SlotAccess getSlot(int)
- void removeFrost()
- void tryAddFrost()
```

</details>

<details><summary>net.minecraft.world.entity.Mob</summary>

```diff
+ boolean isValidSlotForItem(ItemStack)
+ boolean setSlot(ItemStack)
+ EquipmentSlot getEquipmentSlotForItem(ItemStack)
- double getMeleeAttackRangeSqr(LivingEntity)
- ItemStack getPickResult()
```

</details>



<details><summary>net.minecraft.world.entity.NeutralMob</summary>

```diff
+ void readPersistentAngerSaveData(CompoundTag)
- void readPersistentAngerSaveData(CompoundTag)
```

</details>


<details><summary>net.minecraft.world.entity.PlayerRideableJumping</summary>

```diff
+ float getJumpRidingScale()
+ void setJumpRidingScale(float)
```

</details>


















<details><summary>net.minecraft.world.entity.ai.behavior.BehaviorUtils</summary>

```diff
+ boolean isWithinMeleeAttackRange(LivingEntity)
+ boolean lambda$null$5(LivingEntity)
+ LivingEntity lambda$getLivingEntityFromUUIDMemory$4(UUID)
+ Stream lambda$getNearbyVillagersWithCondition$7(List)
+ Villager lambda$null$6(LivingEntity)
- boolean isWithinMeleeAttackRange(LivingEntity)
- boolean lambda$null$6(LivingEntity)
- Entity lambda$getLivingEntityFromUUIDMemory$4(UUID)
- LivingEntity lambda$getLivingEntityFromUUIDMemory$5(Entity)
- Stream lambda$getNearbyVillagersWithCondition$8(List)
- Vec3 getRandomSwimmablePos(PathfinderMob,int,int)
- Villager lambda$null$7(LivingEntity)
```

</details>





<details><summary>net.minecraft.world.entity.ai.behavior.GiveGiftToHero</summary>

```diff
+ Map gifts
- Map GIFTS
```

</details>











<details><summary>net.minecraft.world.entity.ai.behavior.RandomStroll</summary>

```diff
- Vec3 getTargetPos(PathfinderMob)
```

</details>




<details><summary>net.minecraft.world.entity.ai.behavior.VillagerMakeLove</summary>

```diff
+ boolean lambda$isBreedingPossible$0(AgableMob)
- boolean lambda$isBreedingPossible$0(AgeableMob)
```

</details>








<details><summary>net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor</summary>

```diff
+ int compareMobDistance(LivingEntity)
+ int lambda$null$1(LivingEntity)
+ Optional getVisibleEntities(LivingEntity)
+ Optional lambda$getNearestHostile$2(List)
+ Set requires()
+ void doTick(LivingEntity)
- Optional lambda$getNearestHostile$1(List)
```

</details>






<details><summary>net.minecraft.world.entity.boss.enderdragon.EndCrystal</summary>

```diff
- ItemStack getPickResult()
```

</details>












<details><summary>net.minecraft.world.entity.decoration.ArmorStand</summary>

```diff
+ boolean setSlot(ItemStack)
- ItemStack getPickResult()
```

</details>


<details><summary>net.minecraft.world.entity.decoration.ItemFrame</summary>

```diff
+ boolean setSlot(ItemStack)
- ItemStack getPickResult()
- SlotAccess getSlot(int)
- void recreateFromPacket(ClientboundAddEntityPacket)
```

</details>






<details><summary>net.minecraft.world.entity.vehicle.MinecartSpawner</summary>

```diff
- Runnable ticker
- Runnable createTicker(Level)
- void lambda$createTicker$0(Level)
- void lambda$createTicker$1(Level)
```

</details>






<details><summary>net.minecraft.world.inventory.AbstractFurnaceMenu</summary>

```diff
+ void handlePlacement(ServerPlayer)
- boolean shouldMoveToInventory(int)
```

</details>









<details><summary>net.minecraft.world.item.ArmorItem</summary>

```diff
- SoundEvent getEquipSound()
```

</details>





<details><summary>net.minecraft.world.item.BlockItem</summary>

```diff
- boolean canFitInsideContainerItems()
- void onDestroyed(ItemEntity)
```

</details>




<details><summary>net.minecraft.world.item.DyeColor</summary>

```diff
+ int textureDiffuseColor
+ int textureDiffuseColorBGR
+ int getTextureDiffuseColorBGR()
```

</details>



<details><summary>net.minecraft.world.item.ElytraItem</summary>

```diff
- SoundEvent getEquipSound()
```

</details>















<details><summary>net.minecraft.world.level.EmptyBlockGetter</summary>

```diff
- int getHeight()
- int getMinBuildHeight()
```

</details>




<details><summary>net.minecraft.world.level.ForcedChunksSavedData</summary>

```diff
+ void load(CompoundTag)
- ForcedChunksSavedData load(CompoundTag)
- void <init>(LongSet)
```

</details>







<details><summary>net.minecraft.world.level.Level</summary>

```diff
+ boolean updatingBlockEntities
+ List blockEntitiesToUnload
+ List blockEntityList
+ List pendingBlockEntities
+ List tickableBlockEntities
+ void setMapData(net.minecraft.world.level.saveddata.maps.MapItemSavedData)
- boolean tickingBlockEntities
- LevelEntityGetter getEntities()
- List blockEntityTickers
- List pendingBlockEntityTickers
- String gatherChunkSourceStats()
- void setMapData(java.lang.String,net.minecraft.world.level.saveddata.maps.MapItemSavedData)
+ BlockEntity getPendingBlockEntityAt(BlockPos)
+ BlockState getTopBlockState(BlockPos)
+ boolean addBlockEntity(BlockEntity)
+ boolean isOutsideBuildHeight(BlockPos)
+ boolean isOutsideBuildHeight(int)
+ List getEntities(Predicate)
+ List getEntitiesOfClass(Predicate)
+ List getLoadedEntitiesOfClass(Predicate)
+ Object lambda$addBlockEntity$1(BlockEntity)
+ String gatherChunkSourceStats()
+ String lambda$tickBlockEntities$2(BlockEntity)
+ void addAllPendingBlockEntities(Collection)
+ void blockEntityChanged(BlockEntity)
+ void setBlockEntity(BlockEntity)
- List getEntities(Predicate)
- void addBlockEntityTicker(TickingBlockEntity)
- void addDestroyBlockEffect(BlockState)
- void blockEntityChanged(BlockPos)
- void lambda$getEntities$1(Entity)
- void lambda$getEntities$2(Entity)
- void postGameEventInRadius(BlockPos,int)
- void setBlockEntity(BlockEntity)
```

</details>

<details><summary>net.minecraft.world.level.LevelAccessor</summary>

```diff
- void gameEvent(net.minecraft.world.entity.Entity,net.minecraft.world.level.gameevent.GameEvent,net.minecraft.core.BlockPos)
+ int getHeight()
- int getLogicalHeight()
- void gameEvent(BlockPos)
- void gameEvent(Entity)
- void gameEvent(Entity)
```

</details>

<details><summary>net.minecraft.world.level.block.AnvilBlock</summary>

```diff
+ void onBroken(FallingBlockEntity)
- DamageSource getFallDamageSource()
- void onBrokenAfterFall(FallingBlockEntity)
```

</details>







<details><summary>net.minecraft.world.level.block.BaseRailBlock</summary>

```diff
- BooleanProperty WATERLOGGED
- BlockState updateShape(BlockPos)
- FluidState getFluidState(BlockState)
```

</details>


<details><summary>net.minecraft.world.level.block.BedBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.BeehiveBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>

<details><summary>net.minecraft.world.level.block.BellBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>

<details><summary>net.minecraft.world.level.block.BlastFurnaceBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>




<details><summary>net.minecraft.world.level.block.BubbleColumnBlock</summary>

```diff
+ Fluid takeLiquid(BlockState)
- ItemStack pickupBlock(BlockState)
- Optional getPickupSound()
```

</details>

<details><summary>net.minecraft.world.level.block.DoorBlock</summary>

```diff
+ void setOpen(BlockPos,boolean)
- void setOpen(BlockPos,boolean)
```

</details>





<details><summary>net.minecraft.world.level.block.DropperBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.EndGatewayBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>







<details><summary>net.minecraft.world.level.block.FurnaceBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>


<details><summary>net.minecraft.world.level.block.GrowingPlantBlock</summary>

```diff
+ boolean canAttachToBlock(Block)
- boolean canAttachTo(BlockState)
```

</details>



<details><summary>net.minecraft.world.level.block.HopperBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>




<details><summary>net.minecraft.world.level.block.JukeboxBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.KelpPlantBlock</summary>

```diff
- boolean canAttachTo(BlockState)
```

</details>







<details><summary>net.minecraft.world.level.block.SimpleWaterloggedBlock</summary>

```diff
+ Fluid takeLiquid(BlockState)
- ItemStack pickupBlock(BlockState)
- Optional getPickupSound()
```

</details>




<details><summary>net.minecraft.world.level.block.SmokerBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>


<details><summary>net.minecraft.world.level.block.SoulFireBlock</summary>

```diff
+ boolean canSurviveOnBlock(Block)
- boolean canSurviveOnBlock(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.SoundType</summary>

```diff
- SoundType AMETHYST
- SoundType AMETHYST_CLUSTER
- SoundType CALCITE
- SoundType CANDLE
- SoundType COPPER
- SoundType DRIPSTONE_BLOCK
- SoundType LARGE_AMETHYST_BUD
- SoundType MEDIUM_AMETHYST_BUD
- SoundType POINTED_DRIPSTONE
- SoundType POWDER_SNOW
- SoundType SCULK_SENSOR
- SoundType SMALL_AMETHYST_BUD
- SoundType TUFF
```

</details>



<details><summary>net.minecraft.world.level.block.StairBlock</summary>

```diff
+ void prepareRender(BlockPos)
```

</details>









<details><summary>net.minecraft.world.level.block.entity.BeaconBlockEntity</summary>

```diff
+ int getLevels()
+ void <init>()
+ void applyEffects()
+ void load(CompoundTag)
+ void playSound(SoundEvent)
+ void tick()
+ void updateBase(int,int,int)
- int updateBase(Level,int,int,int)
- void <init>(BlockState)
- void applyEffects(MobEffect)
- void load(CompoundTag)
- void playSound(SoundEvent)
- void setLevel(Level)
- void tick(BeaconBlockEntity)
```

</details>


<details><summary>net.minecraft.world.level.block.entity.BeehiveBlockEntity</summary>

```diff
+ boolean releaseOccupant(BeehiveBlockEntity$BeeReleaseStatus)
+ void <init>()
+ void load(CompoundTag)
+ void sendDebugPackets()
+ void tick()
+ void tickOccupants()
- boolean releaseOccupant(BlockPos)
- void <init>(BlockState)
- void load(CompoundTag)
- void serverTick(BeehiveBlockEntity)
- void tickOccupants(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.entity.BellBlockEntity</summary>

```diff
+ boolean areRaidersNearby()
+ boolean isRaiderWithinRange(LivingEntity)
+ boolean lambda$showBellParticles$0(LivingEntity)
+ void <init>()
+ void lambda$showBellParticles$1(LivingEntity)
+ void makeRaidersGlow(Level)
+ void playResonateSound()
+ void showBellParticles(Level)
+ void tick()
- boolean areRaidersNearby(List)
- boolean isRaiderWithinRange(LivingEntity)
- boolean lambda$makeRaidersGlow$0(LivingEntity)
- boolean lambda$showBellParticles$1(LivingEntity)
- boolean lambda$showBellParticles$2(LivingEntity)
- void <init>(BlockState)
- void clientTick(BellBlockEntity)
- void lambda$showBellParticles$3(LivingEntity)
- void makeRaidersGlow(List)
- void serverTick(BellBlockEntity)
- void showBellParticles(List)
- void tick(BellBlockEntity$ResonationEndAction)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity</summary>

```diff
+ void <init>()
+ void tick()
- void <init>(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.DropperBlockEntity</summary>

```diff
+ void <init>()
- void <init>(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.EnderChestBlockEntity</summary>

```diff
+ float oOpenness
+ float openness
+ int openCount
+ int tickInterval
- ChestLidController chestLidController
- ContainerOpenersCounter openersCounter
+ void <init>()
+ void setRemoved()
+ void startOpen()
+ void stopOpen()
+ void tick()
- void <init>(BlockState)
- void lidAnimateTick(EnderChestBlockEntity)
- void recheckOpen()
- void startOpen(Player)
- void stopOpen(Player)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity</summary>

```diff
+ boolean loadColorFromBlock
+ AABB getBoundingBox(Direction)
+ AABB getTopBoundingBox(Direction)
+ void <init>()
+ void <init>(DyeColor)
+ void doNeighborUpdates()
+ void load(CompoundTag)
+ void moveCollidedEntities()
+ void tick()
+ void updateAnimation()
- AABB getBoundingBox(Direction,float)
- AABB getTopBoundingBox(Direction,float)
- void <init>(BlockState)
- void <init>(BlockState)
- void doNeighborUpdates(BlockState)
- void load(CompoundTag)
- void moveCollidedEntities(BlockState,float)
- void tick(ShulkerBoxBlockEntity)
- void updateAnimation(ShulkerBoxBlockEntity)
```

</details>


<details><summary>net.minecraft.world.level.block.entity.SkullBlockEntity</summary>

```diff
+ void <init>()
+ void load(CompoundTag)
+ void tick()
- void <init>(BlockState)
- void dragonHeadAnimation(SkullBlockEntity)
- void load(CompoundTag)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.SpawnerBlockEntity</summary>

```diff
+ void <init>()
+ void load(CompoundTag)
+ void tick()
- void <init>(BlockState)
- void clientTick(SpawnerBlockEntity)
- void load(CompoundTag)
- void serverTick(SpawnerBlockEntity)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.StructureBlockEntity</summary>

```diff
+ Component getDisplayName()
+ void <init>()
+ void load(CompoundTag)
+ void nextMode()
- void <init>(BlockState)
- void load(CompoundTag)
```

</details>







<details><summary>net.minecraft.world.level.chunk.ImposterProtoChunk</summary>

```diff
+ LevelLightEngine getLightEngine()
+ void setBlockEntity(BlockEntity)
+ void setLastSaveTime(long)
- void setBlockEntity(BlockEntity)
```

</details>



<details><summary>net.minecraft.world.level.chunk.storage.OldChunkStorage</summary>

```diff
- LevelHeightAccessor OLD_LEVEL_HEIGHT
- void <clinit>()
```

</details>

<details><summary>net.minecraft.world.level.levelgen.DebugLevelSource</summary>

```diff
+ BlockGetter getBaseColumn(int,int)
- NoiseColumn getBaseColumn(int,int)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.FlatLevelSource</summary>

```diff
+ BlockGetter getBaseColumn(int,int)
- NoiseColumn getBaseColumn(int,int)
```

</details>



















<details><summary>net.minecraft.world.level.levelgen.feature.RuinedPortalFeature</summary>

```diff
+ BlockGetter lambda$findSuitableY$0(BlockPos)
+ int randomIntInclusive(Random,int,int)
- NoiseColumn lambda$findSuitableY$0(BlockPos)
```

</details>


































<details><summary>net.minecraft.world.level.material.Material</summary>

```diff
- Material AMETHYST
- Material POWDER_SNOW
- Material SCULK
```

</details>


<details><summary>net.minecraft.world.level.material.WaterFluid</summary>

```diff
- Optional getPickupSound()
```

</details>




<details><summary>net.minecraft.world.level.newbiome.context.BigContext</summary>

```diff
+ long getMixedSeed()
```

</details>

<details><summary>net.minecraft.world.level.newbiome.context.LazyAreaContext</summary>

```diff
+ long getMixedSeed()
```

</details>


























<details><summary>net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer</summary>

```diff
- boolean dirtyDecorations
+ Packet nextUpdatePacket(ItemStack)
+ void markDirty(int,int)
- MapItemSavedData$MapPatch createPatch()
- Packet access$200(MapItemSavedData$HoldingPlayer,int)
- Packet nextUpdatePacket(int)
- void <init>(MapItemSavedData$1)
- void access$300(MapItemSavedData$HoldingPlayer,int,int)
- void access$400(MapItemSavedData$HoldingPlayer)
- void markColorsDirty(int,int)
- void markDecorationsDirty()
```

</details>

<details><summary>net.minecraft.world.level.storage.CommandStorage$Container</summary>

```diff
+ void <init>(String)
+ void load(CompoundTag)
- CommandStorage$Container access$100(CompoundTag)
- CommandStorage$Container load(CompoundTag)
- void <init>()
- void <init>(CommandStorage$1)
```

</details>

<details><summary>net.minecraft.world.level.storage.DimensionDataStorage</summary>

```diff
+ SavedData computeIfAbsent(String)
+ SavedData get(String)
+ SavedData readSavedData(String)
+ void set(SavedData)
- SavedData computeIfAbsent(String)
- SavedData get(String)
- SavedData readSavedData(String)
- void lambda$save$0(SavedData)
- void set(SavedData)
```

</details>






<details><summary>net.minecraft.world.level.storage.PrimaryLevelData</summary>

```diff
+ void <init>(Lifecycle)
+ void fillCrashReportCategory(CrashReportCategory)
- void <init>(Lifecycle)
- void fillCrashReportCategory(LevelHeightAccessor)
```

</details>














































<details><summary>net.minecraft.world.level.storage.loot.functions.CopyNbtFunction</summary>

```diff
+ CopyNbtFunction$DataSource source
+ Function BLOCK_ENTITY_GETTER
+ Function ENTITY_GETTER
- NbtProvider source
+ CopyNbtFunction$Builder copyData(CopyNbtFunction$DataSource)
+ CopyNbtFunction$DataSource access$800(CopyNbtFunction)
+ Function access$600()
+ Function access$700()
+ List access$900(CopyNbtFunction)
+ Tag lambda$static$1(BlockEntity)
+ void <clinit>()
+ void <init>(CopyNbtFunction$1)
+ void <init>(List)
- CopyNbtFunction$Builder copyData(LootContext$EntityTarget)
- CopyNbtFunction$Builder copyData(NbtProvider)
- List access$700(CopyNbtFunction)
- NbtProvider access$600(CopyNbtFunction)
- void <init>(CopyNbtFunction$1)
- void <init>(List)
```

</details>

<details><summary>net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder</summary>

```diff
+ CopyNbtFunction$DataSource source
- NbtProvider source
+ void <init>(CopyNbtFunction$1)
+ void <init>(CopyNbtFunction$DataSource)
- void <init>(CopyNbtFunction$1)
- void <init>(NbtProvider)
```

</details>




<details><summary>net.minecraft.world.phys.shapes.Shapes</summary>

```diff
- VoxelShape create(double,double,double,double,double,double)
```

</details>


<details><summary>net.minecraft.world.phys.shapes.VoxelShape</summary>

```diff
+ boolean isFullWide(double,double,double)
+ boolean lambda$findIndex$4(Direction$Axis,double,int)
- boolean lambda$findIndex$4(Direction$Axis,int)
```

</details>

<details><summary>Added and removed classes</summary>

```diff
- com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
- com.mojang.blaze3d.vertex.BufferBuilder
+ com.mojang.blaze3d.vertex.BufferBuilder$1
- com.mojang.blaze3d.vertex.BufferBuilder$DrawState
+ com.mojang.blaze3d.vertex.BufferBuilder$State
- com.mojang.blaze3d.vertex.BufferUploader
+ com.mojang.blaze3d.vertex.BufferVertexConsumer
+ com.mojang.blaze3d.vertex.DefaultedVertexConsumer
- com.mojang.blaze3d.vertex.DefaultVertexFormat
- com.mojang.blaze3d.vertex.PoseStack
+ com.mojang.blaze3d.vertex.PoseStack$1
- com.mojang.blaze3d.vertex.PoseStack$Pose
+ com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
- com.mojang.blaze3d.vertex.Tesselator
+ com.mojang.blaze3d.vertex.VertexBuffer
- com.mojang.blaze3d.vertex.VertexConsumer
+ com.mojang.blaze3d.vertex.VertexFormat
- com.mojang.blaze3d.vertex.VertexFormat$1
- com.mojang.blaze3d.vertex.VertexFormat$Mode
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$2
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$FrameButton
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$ResetType
+ com.mojang.realmsclient.gui.screens.RealmsScreenWithCallback
- com.mojang.realmsclient.util.RealmsPersistence
+ com.mojang.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- com.mojang.realmsclient.util.RealmsTextureManager
+ com.mojang.realmsclient.util.RealmsTextureManager$1
- com.mojang.realmsclient.util.RealmsTextureManager$RealmsTexture
+ com.mojang.realmsclient.util.RealmsUtil
- com.mojang.realmsclient.util.RealmsUtil$1
+ com.mojang.realmsclient.util.SkinProcessor
- com.mojang.realmsclient.util.task.ResettingTemplateWorldTask
- com.mojang.realmsclient.util.TextRenderingUtils
+ com.mojang.realmsclient.util.TextRenderingUtils$Line
- com.mojang.realmsclient.util.TextRenderingUtils$LineSegment
+ com.mojang.realmsclient.util.UploadTokenCache
- com.mojang.realmsclient.util.WorldGenerationInfo
+ net.minecraft.client.Camera
- net.minecraft.client.CameraType
+ net.minecraft.client.ClientBrandRetriever
- net.minecraft.client.ClientRecipeBook
+ net.minecraft.client.CloudStatus
- net.minecraft.client.ComponentCollector
+ net.minecraft.client.CycleOption
- net.minecraft.client.CycleOption$OptionSetter
- net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$Builder
- net.minecraft.client.gui.components.CycleButton$TooltipSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
+ net.minecraft.client.gui.components.events.AbstractContainerEventHandler
- net.minecraft.client.gui.components.events.ContainerEventHandler
+ net.minecraft.client.gui.components.events.GuiEventListener
- net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.OptionButton
- net.minecraft.client.gui.components.OptionsList
+ net.minecraft.client.gui.components.OptionsList$Entry
+ net.minecraft.client.gui.components.package-info
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$1
- net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
+ net.minecraft.client.gui.components.SliderButton
+ net.minecraft.client.gui.components.spectator.package-info
- net.minecraft.client.gui.components.spectator.SpectatorGui
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.SubtitleOverlay
- net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
+ net.minecraft.client.gui.components.TickableWidget
- net.minecraft.client.gui.components.toasts.AdvancementToast
+ net.minecraft.client.gui.components.toasts.package-info
+ net.minecraft.client.gui.components.toasts.RecipeToast
- net.minecraft.client.gui.components.toasts.SystemToast
+ net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
- net.minecraft.client.gui.components.toasts.Toast
+ net.minecraft.client.gui.components.toasts.Toast$Visibility
- net.minecraft.client.gui.components.toasts.ToastComponent
+ net.minecraft.client.gui.components.toasts.ToastComponent$1
- net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
+ net.minecraft.client.gui.components.toasts.TutorialToast
- net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.TooltipAccessor
+ net.minecraft.client.gui.components.VolumeSlider
- net.minecraft.client.gui.components.Widget
- net.minecraft.client.gui.font.AllMissingGlyphProvider
+ net.minecraft.client.gui.font.FontManager
- net.minecraft.client.gui.font.FontManager$1
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontTexture
+ net.minecraft.client.gui.font.FontTexture$1
- net.minecraft.client.gui.font.FontTexture$Node
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
- net.minecraft.client.gui.font.glyphs.EmptyGlyph
+ net.minecraft.client.gui.font.glyphs.MissingGlyph
+ net.minecraft.client.gui.font.glyphs.package-info
- net.minecraft.client.gui.font.glyphs.WhiteGlyph
- net.minecraft.client.gui.font.package-info
+ net.minecraft.client.gui.font.providers.BitmapProvider
- net.minecraft.client.gui.font.providers.BitmapProvider$1
+ net.minecraft.client.gui.font.providers.BitmapProvider$Builder
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilder
- net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$1
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Builder
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- net.minecraft.client.gui.font.providers.package-info
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
+ net.minecraft.client.gui.font.TextFieldHelper
+ net.minecraft.client.gui.package-info
- net.minecraft.client.gui.screens.AccessibilityOptionsScreen
- net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$1
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ net.minecraft.client.gui.screens.achievement.StatsUpdateListener
- net.minecraft.client.gui.screens.advancements.AdvancementsScreen
+ net.minecraft.client.gui.screens.advancements.AdvancementTab
- net.minecraft.client.gui.screens.advancements.AdvancementTabType
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
- net.minecraft.client.gui.screens.advancements.AdvancementWidget
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
+ net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.AlertScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
- net.minecraft.client.gui.screens.ChatOptionsScreen
+ net.minecraft.client.gui.screens.ChatScreen
- net.minecraft.client.gui.screens.ChatScreen$1
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
- net.minecraft.client.gui.screens.controls.ControlList
+ net.minecraft.client.gui.screens.controls.ControlList$1
- net.minecraft.client.gui.screens.controls.ControlList$CategoryEntry
+ net.minecraft.client.gui.screens.controls.ControlList$Entry
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$2
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$1
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$1
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.DatapackLoadFailureScreen
- net.minecraft.client.gui.screens.DeathScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ net.minecraft.client.gui.screens.DemoIntroScreen
- net.minecraft.client.gui.screens.DirectJoinServerScreen
+ net.minecraft.client.gui.screens.DisconnectedScreen
- net.minecraft.client.gui.screens.EditServerScreen
+ net.minecraft.client.gui.screens.ErrorScreen
- net.minecraft.client.gui.screens.GenericDirtMessageScreen
+ net.minecraft.client.gui.screens.InBedChatScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
- net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.AnvilScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$1
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
- net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
- net.minecraft.client.gui.screens.inventory.BookViewScreen
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$1
- net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$WritableBookAccess
- net.minecraft.client.gui.screens.inventory.BookViewScreen$WrittenBookAccess
+ net.minecraft.client.gui.screens.inventory.BrewingStandScreen
- net.minecraft.client.gui.screens.inventory.CartographyTableScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.ContainerScreen
- net.minecraft.client.gui.screens.inventory.CraftingScreen
+ net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- net.minecraft.client.gui.screens.inventory.DispenserScreen
+ net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
- net.minecraft.client.gui.screens.inventory.EnchantmentNames
+ net.minecraft.client.gui.screens.inventory.EnchantmentScreen
- net.minecraft.client.gui.screens.inventory.FurnaceScreen
+ net.minecraft.client.gui.screens.inventory.GrindstoneScreen
- net.minecraft.client.gui.screens.inventory.HopperScreen
+ net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
- net.minecraft.client.gui.screens.inventory.InventoryScreen
+ net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
- net.minecraft.client.gui.screens.LanguageSelectScreen
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
+ net.minecraft.client.gui.screens.LevelLoadingScreen
- net.minecraft.client.gui.screens.LoadingOverlay
+ net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.MenuScreens
+ net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
- net.minecraft.client.gui.screens.MouseSettingsScreen
+ net.minecraft.client.gui.screens.OptionsScreen
- net.minecraft.client.gui.screens.OptionsSubScreen
+ net.minecraft.client.gui.screens.OutOfMemoryScreen
- net.minecraft.client.gui.screens.Overlay
+ net.minecraft.client.gui.screens.PauseScreen
- net.minecraft.client.gui.screens.PopupScreen
+ net.minecraft.client.gui.screens.PopupScreen$ButtonOption
- net.minecraft.client.gui.screens.PresetFlatWorldScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.ShareToLanScreen
- net.minecraft.client.gui.screens.SimpleOptionsSubScreen
+ net.minecraft.client.gui.screens.SkinCustomizationScreen
- net.minecraft.client.gui.screens.SoundOptionsScreen
+ net.minecraft.client.gui.screens.TitleScreen
- net.minecraft.client.gui.screens.VideoSettingsScreen
+ net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$2
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$4
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry$1
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$EntryFactory
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$GameRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList$1
+ net.minecraft.client.gui.screens.worldselection.EditWorldScreen
- net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
+ net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
- net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
+ net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent$1
+ net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent$3
- net.minecraft.client.model.BatModel
+ net.minecraft.client.model.BeeModel
- net.minecraft.client.model.BlazeModel
+ net.minecraft.client.model.BoatModel
- net.minecraft.client.model.BookModel
+ net.minecraft.client.model.CatModel
- net.minecraft.client.model.ChestedHorseModel
+ net.minecraft.client.model.ChickenModel
- net.minecraft.client.model.CodModel
+ net.minecraft.client.model.ColorableAgeableListModel
- net.minecraft.client.model.ColorableHierarchicalModel
+ net.minecraft.client.model.CowModel
- net.minecraft.client.model.CreeperModel
+ net.minecraft.client.model.DolphinModel
- net.minecraft.client.model.DrownedModel
+ net.minecraft.client.model.ElytraModel
- net.minecraft.client.model.EndermanModel
+ net.minecraft.client.model.EndermiteModel
- net.minecraft.client.model.EntityModel
+ net.minecraft.client.model.EvokerFangsModel
- net.minecraft.client.model.FoxModel
- net.minecraft.client.model.geom.builders.CubeDeformation
- net.minecraft.client.model.geom.builders.LayerDefinition
- net.minecraft.client.model.geom.builders.MeshDefinition
- net.minecraft.client.model.geom.builders.UVPair
- net.minecraft.client.model.geom.EntityModelSet
- net.minecraft.client.model.geom.ModelLayerLocation
- net.minecraft.client.model.geom.ModelPart$Visitor
- net.minecraft.client.model.geom.PartPose
+ net.minecraft.client.model.GhastModel
- net.minecraft.client.model.GiantZombieModel
+ net.minecraft.client.model.GuardianModel
- net.minecraft.client.model.HeadedModel
+ net.minecraft.client.model.HumanoidHeadModel
- net.minecraft.client.model.HumanoidModel
+ net.minecraft.client.model.HumanoidModel$1
- net.minecraft.client.model.HumanoidModel$ArmPose
+ net.minecraft.client.model.IllagerModel
- net.minecraft.client.model.IronGolemModel
+ net.minecraft.client.model.LavaSlimeModel
- net.minecraft.client.model.LeashKnotModel
+ net.minecraft.client.model.ListModel
- net.minecraft.client.model.LlamaModel
+ net.minecraft.client.model.LlamaSpitModel
- net.minecraft.client.model.MinecartModel
+ net.minecraft.client.model.Model
- net.minecraft.client.model.ModelUtils
+ net.minecraft.client.model.OcelotModel
- net.minecraft.client.model.PandaModel
+ net.minecraft.client.model.ParrotModel
- net.minecraft.client.model.ParrotModel$1
+ net.minecraft.client.model.ParrotModel$State
- net.minecraft.client.model.PhantomModel
- net.minecraft.client.model.PiglinModel
+ net.minecraft.client.model.PigModel
+ net.minecraft.client.model.PlayerModel
- net.minecraft.client.model.PolarBearModel
+ net.minecraft.client.model.PufferfishBigModel
- net.minecraft.client.model.PufferfishMidModel
+ net.minecraft.client.model.PufferfishSmallModel
- net.minecraft.client.model.QuadrupedModel
+ net.minecraft.client.model.RabbitModel
- net.minecraft.client.model.RavagerModel
+ net.minecraft.client.model.SalmonModel
- net.minecraft.client.model.SheepFurModel
+ net.minecraft.client.model.SheepModel
- net.minecraft.client.model.ShieldModel
+ net.minecraft.client.model.ShulkerBulletModel
- net.minecraft.client.model.ShulkerModel
+ net.minecraft.client.model.SilverfishModel
- net.minecraft.client.model.SkeletonModel
+ net.minecraft.client.model.SkullModel
- net.minecraft.client.model.SkullModelBase
- net.minecraft.client.multiplayer.ClientPacketListener
+ net.minecraft.client.multiplayer.ClientPacketListener$1
- net.minecraft.client.multiplayer.ClientSuggestionProvider
+ net.minecraft.client.multiplayer.MultiPlayerGameMode
+ net.minecraft.client.multiplayer.package-info
- net.minecraft.client.multiplayer.PlayerInfo
+ net.minecraft.client.multiplayer.ServerAddress
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.multiplayer.ServerStatusPinger$2$1
- net.minecraft.client.package-info
+ net.minecraft.client.particle.AshParticle
- net.minecraft.client.particle.AshParticle$Provider
+ net.minecraft.client.particle.AttackSweepParticle
- net.minecraft.client.particle.AttackSweepParticle$1
+ net.minecraft.client.particle.AttackSweepParticle$Provider
- net.minecraft.client.particle.BarrierParticle
+ net.minecraft.client.particle.BarrierParticle$1
- net.minecraft.client.particle.BarrierParticle$Provider
+ net.minecraft.client.particle.BaseAshSmokeParticle
- net.minecraft.client.particle.BreakingItemParticle
+ net.minecraft.client.particle.BreakingItemParticle$1
- net.minecraft.client.particle.BreakingItemParticle$Provider
+ net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
- net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
+ net.minecraft.client.particle.BubbleColumnUpParticle
- net.minecraft.client.particle.BubbleColumnUpParticle$1
+ net.minecraft.client.particle.BubbleColumnUpParticle$Provider
- net.minecraft.client.particle.BubbleParticle
+ net.minecraft.client.particle.BubbleParticle$1
- net.minecraft.client.particle.BubbleParticle$Provider
+ net.minecraft.client.particle.BubblePopParticle
- net.minecraft.client.particle.BubblePopParticle$1
+ net.minecraft.client.particle.BubblePopParticle$Provider
- net.minecraft.client.particle.CampfireSmokeParticle
+ net.minecraft.client.particle.CampfireSmokeParticle$1
- net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
+ net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
- net.minecraft.client.particle.CritParticle
+ net.minecraft.client.particle.CritParticle$1
- net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
+ net.minecraft.client.particle.CritParticle$MagicProvider
- net.minecraft.client.particle.CritParticle$Provider
+ net.minecraft.client.particle.DragonBreathParticle
- net.minecraft.client.particle.DragonBreathParticle$1
+ net.minecraft.client.particle.DragonBreathParticle$Provider
- net.minecraft.client.particle.DripParticle
+ net.minecraft.client.particle.DripParticle$1
- net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
+ net.minecraft.client.particle.DripParticle$DripHangParticle
- net.minecraft.client.particle.DripParticle$DripLandParticle
- net.minecraft.client.particle.DripParticle$DripstoneLavaFallProvider
- net.minecraft.client.particle.DripParticle$DripstoneWaterFallProvider
- net.minecraft.client.particle.DustColorTransitionParticle$Provider
+ net.minecraft.client.particle.DustParticle$1
- net.minecraft.client.particle.DustParticle$Provider
- net.minecraft.client.particle.FlameParticle$SmallFlameProvider
+ net.minecraft.client.particle.HeartParticle
- net.minecraft.client.particle.HeartParticle$1
+ net.minecraft.client.particle.HeartParticle$AngryVillagerProvider
- net.minecraft.client.particle.HeartParticle$Provider
+ net.minecraft.client.particle.HugeExplosionParticle
- net.minecraft.client.particle.HugeExplosionParticle$1
+ net.minecraft.client.particle.HugeExplosionParticle$Provider
- net.minecraft.client.particle.HugeExplosionSeedParticle
+ net.minecraft.client.particle.HugeExplosionSeedParticle$1
- net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
+ net.minecraft.client.particle.ItemPickupParticle
- net.minecraft.client.particle.LargeSmokeParticle
+ net.minecraft.client.particle.LargeSmokeParticle$Provider
- net.minecraft.client.particle.LavaParticle
+ net.minecraft.client.particle.LavaParticle$1
- net.minecraft.client.particle.LavaParticle$Provider
+ net.minecraft.client.particle.MobAppearanceParticle
- net.minecraft.client.particle.MobAppearanceParticle$1
+ net.minecraft.client.particle.MobAppearanceParticle$Provider
- net.minecraft.client.particle.NoRenderParticle
+ net.minecraft.client.particle.NoteParticle
- net.minecraft.client.particle.NoteParticle$1
+ net.minecraft.client.particle.NoteParticle$Provider
- net.minecraft.client.particle.Particle
+ net.minecraft.client.particle.ParticleDescription
- net.minecraft.client.particle.ParticleEngine
+ net.minecraft.client.particle.ParticleEngine$1
- net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
+ net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
- net.minecraft.client.particle.ParticleProvider
+ net.minecraft.client.particle.ParticleRenderType
- net.minecraft.client.particle.ParticleRenderType$1
+ net.minecraft.client.particle.ParticleRenderType$2
- net.minecraft.client.particle.ParticleRenderType$3
+ net.minecraft.client.particle.ParticleRenderType$4
- net.minecraft.client.particle.ParticleRenderType$5
+ net.minecraft.client.particle.ParticleRenderType$6
- net.minecraft.client.particle.PlayerCloudParticle
+ net.minecraft.client.particle.PlayerCloudParticle$1
- net.minecraft.client.particle.PlayerCloudParticle$Provider
+ net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
- net.minecraft.client.particle.PortalParticle
+ net.minecraft.client.particle.PortalParticle$Provider
- net.minecraft.client.particle.ReversePortalParticle
+ net.minecraft.client.particle.ReversePortalParticle$1
- net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
+ net.minecraft.client.particle.RisingParticle
- net.minecraft.client.particle.SimpleAnimatedParticle
+ net.minecraft.client.particle.SingleQuadParticle
- net.minecraft.client.particle.SmokeParticle
+ net.minecraft.client.particle.SmokeParticle$Provider
- net.minecraft.client.particle.SnowflakeParticle
- net.minecraft.client.particle.SoulParticle
+ net.minecraft.client.particle.SoulParticle$1
- net.minecraft.client.particle.SoulParticle$Provider
+ net.minecraft.client.particle.SpellParticle
- net.minecraft.client.particle.SpellParticle$1
+ net.minecraft.client.particle.SpellParticle$AmbientMobProvider
- net.minecraft.client.particle.SpellParticle$InstantProvider
+ net.minecraft.client.particle.SpellParticle$MobProvider
- net.minecraft.client.particle.SpellParticle$Provider
+ net.minecraft.client.particle.SpellParticle$WitchProvider
- net.minecraft.client.particle.SpitParticle
+ net.minecraft.client.particle.SpitParticle$1
- net.minecraft.client.particle.SpitParticle$Provider
+ net.minecraft.client.particle.SplashParticle
- net.minecraft.client.particle.SplashParticle$1
+ net.minecraft.client.particle.SplashParticle$Provider
- net.minecraft.client.particle.SpriteSet
+ net.minecraft.client.particle.SquidInkParticle
- net.minecraft.client.particle.SquidInkParticle$1
+ net.minecraft.client.particle.SquidInkParticle$Provider
- net.minecraft.client.particle.SuspendedParticle
+ net.minecraft.client.particle.SuspendedParticle$1
- net.minecraft.client.particle.SuspendedParticle$CrimsonSporeProvider
+ net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
- net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
+ net.minecraft.client.particle.SuspendedTownParticle
- net.minecraft.client.particle.SuspendedTownParticle$1
+ net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
- net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
- net.minecraft.client.particle.SuspendedTownParticle$Provider
+ net.minecraft.client.particle.TerrainParticle
- net.minecraft.client.particle.TerrainParticle$Provider
+ net.minecraft.client.particle.TextureSheetParticle
- net.minecraft.client.particle.TotemParticle
+ net.minecraft.client.particle.TotemParticle$1
- net.minecraft.client.particle.TotemParticle$Provider
+ net.minecraft.client.particle.TrackingEmitter
- net.minecraft.client.particle.VibrationSignalParticle
- net.minecraft.client.particle.VibrationSignalParticle$Provider
+ net.minecraft.client.renderer.banner.package-info
- net.minecraft.client.renderer.block.BlockModelShaper
+ net.minecraft.client.renderer.block.BlockRenderDispatcher
- net.minecraft.client.renderer.block.BlockRenderDispatcher$1
+ net.minecraft.client.renderer.block.LiquidBlockRenderer
+ net.minecraft.client.renderer.block.model.BakedQuad
- net.minecraft.client.renderer.block.model.BlockElement
+ net.minecraft.client.renderer.block.model.BlockElement$1
- net.minecraft.client.renderer.block.model.BlockElement$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementFace
- net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementRotation
- net.minecraft.client.renderer.block.model.BlockFaceUV
+ net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel
+ net.minecraft.client.renderer.block.model.BlockModel$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel$GuiLight
+ net.minecraft.client.renderer.block.model.BlockModel$LoopException
- net.minecraft.client.renderer.block.model.BlockModelDefinition
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
- net.minecraft.client.renderer.block.model.FaceBakery
+ net.minecraft.client.renderer.block.model.FaceBakery$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
- net.minecraft.client.renderer.block.model.ItemOverride
+ net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
- net.minecraft.client.renderer.block.model.ItemOverrides
+ net.minecraft.client.renderer.block.model.ItemTransform
- net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms
- net.minecraft.client.renderer.block.model.ItemTransforms$1
+ net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
+ net.minecraft.client.renderer.block.model.multipart.AndCondition
- net.minecraft.client.renderer.block.model.multipart.Condition
+ net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
- net.minecraft.client.renderer.block.model.multipart.MultiPart
+ net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
- net.minecraft.client.renderer.block.model.multipart.OrCondition
+ net.minecraft.client.renderer.block.model.multipart.package-info
+ net.minecraft.client.renderer.block.model.multipart.Selector
- net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
+ net.minecraft.client.renderer.block.model.MultiVariant
- net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
- net.minecraft.client.renderer.block.model.package-info
+ net.minecraft.client.renderer.block.model.Variant
- net.minecraft.client.renderer.block.model.Variant$Deserializer
- net.minecraft.client.renderer.block.ModelBlockRenderer
+ net.minecraft.client.renderer.block.ModelBlockRenderer$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
- net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
+ net.minecraft.client.renderer.block.package-info
- net.minecraft.client.renderer.block.statemap.package-info
+ net.minecraft.client.renderer.blockentity.BannerRenderer
- net.minecraft.client.renderer.blockentity.BeaconRenderer
+ net.minecraft.client.renderer.blockentity.BedRenderer
- net.minecraft.client.renderer.blockentity.BellRenderer
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
- net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
- net.minecraft.client.renderer.debug.GameEventListenerRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedListener
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer
- net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ net.minecraft.client.renderer.debug.HeightMapRenderer
- net.minecraft.client.renderer.debug.HeightMapRenderer$1
+ net.minecraft.client.renderer.debug.LightDebugRenderer
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
- net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
- net.minecraft.client.renderer.debug.WaterDebugRenderer
+ net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.entity.AbstractHorseRenderer
- net.minecraft.client.renderer.entity.AbstractZombieRenderer
+ net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
- net.minecraft.client.renderer.entity.AxolotlRenderer
- net.minecraft.client.renderer.entity.EntityRendererProvider$Context
- net.minecraft.client.renderer.entity.EvokerFangsRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer$1
+ net.minecraft.client.renderer.entity.ExperienceOrbRenderer
- net.minecraft.client.renderer.entity.FallingBlockRenderer
+ net.minecraft.client.renderer.entity.FireworkEntityRenderer
- net.minecraft.client.renderer.entity.FishingHookRenderer
+ net.minecraft.client.renderer.entity.FoxRenderer
- net.minecraft.client.renderer.entity.GhastRenderer
+ net.minecraft.client.renderer.entity.GiantMobRenderer
- net.minecraft.client.renderer.entity.GuardianRenderer
+ net.minecraft.client.renderer.entity.HoglinRenderer
- net.minecraft.client.renderer.entity.HorseRenderer
+ net.minecraft.client.renderer.entity.HumanoidMobRenderer
- net.minecraft.client.renderer.entity.HuskRenderer
+ net.minecraft.client.renderer.entity.IllagerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer$1
- net.minecraft.client.renderer.entity.IronGolemRenderer
+ net.minecraft.client.renderer.entity.ItemEntityRenderer
- net.minecraft.client.renderer.entity.ItemFrameRenderer
+ net.minecraft.client.renderer.entity.ItemRenderer
+ net.minecraft.client.renderer.entity.layers.ArrowLayer
- net.minecraft.client.renderer.entity.layers.BeeStingerLayer
+ net.minecraft.client.renderer.entity.layers.CapeLayer
- net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
+ net.minecraft.client.renderer.entity.layers.CatCollarLayer
- net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
+ net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
- net.minecraft.client.renderer.entity.layers.CustomHeadLayer
+ net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
- net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
+ net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
- net.minecraft.client.renderer.entity.layers.ElytraLayer
+ net.minecraft.client.renderer.entity.layers.EnderEyesLayer
- net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
+ net.minecraft.client.renderer.entity.layers.EyesLayer
- net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
+ net.minecraft.client.renderer.entity.layers.HorseArmorLayer
- net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
+ net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
- net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
+ net.minecraft.client.renderer.entity.layers.ItemInHandLayer
- net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
+ net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
- net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
+ net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
- net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
- net.minecraft.client.renderer.entity.LeashKnotRenderer
+ net.minecraft.client.renderer.entity.LightningBoltRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer$1
- net.minecraft.client.renderer.entity.LlamaRenderer
+ net.minecraft.client.renderer.entity.LlamaSpitRenderer
- net.minecraft.client.renderer.entity.MagmaCubeRenderer
+ net.minecraft.client.renderer.entity.MinecartRenderer
- net.minecraft.client.renderer.entity.MobRenderer
+ net.minecraft.client.renderer.entity.MushroomCowRenderer
- net.minecraft.client.renderer.entity.OcelotRenderer
+ net.minecraft.client.renderer.entity.PaintingRenderer
- net.minecraft.client.renderer.entity.PandaRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
- net.minecraft.client.renderer.entity.PolarBearRenderer
+ net.minecraft.client.renderer.entity.PufferfishRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer
+ net.minecraft.client.renderer.entity.RavagerRenderer
- net.minecraft.client.renderer.entity.RenderLayerParent
+ net.minecraft.client.renderer.entity.SalmonRenderer
- net.minecraft.client.renderer.entity.SheepRenderer
+ net.minecraft.client.renderer.entity.ShulkerBulletRenderer
- net.minecraft.client.renderer.entity.ShulkerRenderer
+ net.minecraft.client.renderer.entity.SilverfishRenderer
- net.minecraft.client.renderer.entity.SkeletonRenderer
+ net.minecraft.client.renderer.entity.SlimeRenderer
- net.minecraft.client.renderer.entity.SnowGolemRenderer
+ net.minecraft.client.renderer.entity.SpectralArrowRenderer
- net.minecraft.client.renderer.entity.SpiderRenderer
+ net.minecraft.client.renderer.entity.SquidRenderer
- net.minecraft.client.renderer.entity.StrayRenderer
+ net.minecraft.client.renderer.entity.StriderRenderer
- net.minecraft.client.renderer.entity.ThrownItemRenderer
+ net.minecraft.client.renderer.entity.ThrownTridentRenderer
- net.minecraft.client.renderer.entity.TippableArrowRenderer
+ net.minecraft.client.renderer.entity.TntMinecartRenderer
- net.minecraft.client.renderer.entity.TntRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer
- net.minecraft.client.renderer.entity.TurtleRenderer
+ net.minecraft.client.renderer.entity.UndeadHorseRenderer
- net.minecraft.client.renderer.entity.VexRenderer
+ net.minecraft.client.renderer.entity.VillagerRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer$1
- net.minecraft.client.renderer.entity.WanderingTraderRenderer
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZoglinRenderer
+ net.minecraft.client.renderer.entity.ZombieRenderer
- net.minecraft.client.renderer.entity.ZombieVillagerRenderer
- net.minecraft.client.renderer.ItemModelShaper
+ net.minecraft.client.renderer.LevelRenderer
- net.minecraft.client.renderer.LevelRenderer$1
+ net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
- net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
+ net.minecraft.client.renderer.LightTexture
- net.minecraft.client.renderer.MultiBufferSource
+ net.minecraft.client.renderer.MultiBufferSource$BufferSource
- net.minecraft.client.renderer.OutlineBufferSource
+ net.minecraft.client.renderer.OutlineBufferSource$1
- net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ net.minecraft.client.renderer.PanoramaRenderer
- net.minecraft.client.renderer.PostChain
+ net.minecraft.client.renderer.PostPass
- net.minecraft.client.renderer.Rect2i
+ net.minecraft.client.renderer.RenderBuffers
- net.minecraft.client.renderer.RenderStateShard
+ net.minecraft.client.renderer.RenderStateShard$AlphaStateShard
- net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
+ net.minecraft.client.renderer.RenderStateShard$CullStateShard
- net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
+ net.minecraft.client.renderer.RenderStateShard$DiffuseLightingStateShard
- net.minecraft.client.renderer.RenderStateShard$FogStateShard
+ net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
- net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
+ net.minecraft.client.renderer.RenderStateShard$LineStateShard
- net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$OutputStateShard
- net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
+ net.minecraft.client.renderer.RenderStateShard$PortalTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$ShadeModelStateShard
+ net.minecraft.client.renderer.RenderStateShard$TextureStateShard
- net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
- net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
+ net.minecraft.client.renderer.RenderType
- net.minecraft.client.renderer.RenderType$1
+ net.minecraft.client.renderer.RenderType$CompositeRenderType
- net.minecraft.client.renderer.RenderType$CompositeRenderType$EqualsStrategy
+ net.minecraft.client.renderer.RenderType$CompositeState
- net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ net.minecraft.client.renderer.RenderType$OutlineProperty
- net.minecraft.client.renderer.RunningTrimmedMean
+ net.minecraft.client.renderer.ScreenEffectRenderer
- net.minecraft.client.renderer.Sheets
+ net.minecraft.client.renderer.Sheets$1
- net.minecraft.client.renderer.SpriteCoordinateExpander
+ net.minecraft.client.renderer.ViewArea
- net.minecraft.client.renderer.VirtualScreen
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.package-info
- net.minecraft.commands.arguments.coordinates.BlockPosArgument
+ net.minecraft.commands.arguments.coordinates.ColumnPosArgument
- net.minecraft.commands.arguments.coordinates.Coordinates
+ net.minecraft.commands.arguments.coordinates.LocalCoordinates
- net.minecraft.commands.arguments.coordinates.package-info
- net.minecraft.commands.arguments.coordinates.RotationArgument
+ net.minecraft.commands.arguments.coordinates.SwizzleArgument
- net.minecraft.commands.arguments.coordinates.Vec2Argument
+ net.minecraft.commands.arguments.coordinates.Vec3Argument
- net.minecraft.commands.arguments.coordinates.WorldCoordinate
+ net.minecraft.commands.arguments.coordinates.WorldCoordinates
+ net.minecraft.commands.arguments.item.FunctionArgument
- net.minecraft.commands.arguments.item.FunctionArgument$1
+ net.minecraft.commands.arguments.item.FunctionArgument$2
- net.minecraft.commands.arguments.item.FunctionArgument$Result
+ net.minecraft.commands.arguments.item.ItemArgument
- net.minecraft.commands.arguments.item.ItemInput
+ net.minecraft.commands.arguments.item.ItemParser
- net.minecraft.commands.arguments.item.ItemPredicateArgument
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.NbtPathArgument$ListElementFunction
- net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$NbtPath
- net.minecraft.commands.arguments.NbtPathArgument$Node
+ net.minecraft.commands.arguments.NbtTagArgument
- net.minecraft.commands.arguments.ObjectiveArgument
+ net.minecraft.commands.arguments.ObjectiveCriteriaArgument
- net.minecraft.commands.arguments.OperationArgument
+ net.minecraft.commands.arguments.OperationArgument$Operation
- net.minecraft.commands.arguments.OperationArgument$SimpleOperation
+ net.minecraft.commands.arguments.package-info
+ net.minecraft.commands.arguments.ParticleArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ScoreboardSlotArgument
- net.minecraft.commands.arguments.ScoreHolderArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
- net.minecraft.commands.arguments.selector.EntitySelector
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.TeamArgument
+ net.minecraft.commands.arguments.TimeArgument
- net.minecraft.commands.arguments.UuidArgument
- net.minecraft.core.cauldron.CauldronInteraction
- net.minecraft.core.particles.DustColorTransitionOptions$1
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
+ net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption$1
- net.minecraft.core.Registry
+ net.minecraft.core.RegistryAccess
- net.minecraft.core.RegistryAccess$RegistryData
+ net.minecraft.core.RegistryAccess$RegistryHolder
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.SerializableUUID
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdventureAdvancements
+ net.minecraft.data.advancements.HusbandryAdvancements
- net.minecraft.data.advancements.NetherAdvancements
+ net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.StoryAdvancements
- net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.BuiltinRegistries
+ net.minecraft.data.DataGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.HashCache
- net.minecraft.data.info.BlockListReport
+ net.minecraft.data.info.CommandsReport
+ net.minecraft.data.info.package-info
- net.minecraft.data.info.RegistryDumpReport
- net.minecraft.data.loot.BlockLoot
+ net.minecraft.data.loot.ChestLoot
- net.minecraft.data.loot.EntityLoot
+ net.minecraft.data.loot.FishingLoot
- net.minecraft.data.loot.GiftLoot
+ net.minecraft.data.loot.LootTableProvider
+ net.minecraft.data.loot.package-info
- net.minecraft.data.loot.PiglinBarterLoot
- net.minecraft.data.Main
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
- net.minecraft.data.models.blockstates.Condition$1
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$1
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
+ net.minecraft.data.models.blockstates.PropertyDispatch
- net.minecraft.data.models.blockstates.PropertyDispatch$1
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
- net.minecraft.data.models.ItemModelGenerators
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.ModelProvider
+ net.minecraft.data.models.package-info
- net.minecraft.data.package-info
+ net.minecraft.data.recipes.FinishedRecipe
+ net.minecraft.data.recipes.package-info
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
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.tags.GameEventTagsProvider
+ net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$1
- net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.worldgen.BastionBridgePools
+ net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionHousingUnitsPools
+ net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionSharedPools
+ net.minecraft.data.worldgen.BastionTreasureRoomPools
+ net.minecraft.data.worldgen.biome.BiomeReport
- net.minecraft.data.worldgen.biome.Biomes
- net.minecraft.data.worldgen.biome.package-info
+ net.minecraft.data.worldgen.biome.VanillaBiomes
- net.minecraft.data.worldgen.BiomeDefaultFeatures
+ net.minecraft.data.worldgen.Carvers
- net.minecraft.data.worldgen.DesertVillagePools
+ net.minecraft.data.worldgen.Features
- net.minecraft.data.worldgen.Features$Configs
+ net.minecraft.data.worldgen.Features$Decorators
- net.minecraft.data.worldgen.Features$States
+ net.minecraft.data.worldgen.PillagerOutpostPools
- net.minecraft.data.worldgen.PlainVillagePools
+ net.minecraft.data.worldgen.Pools
- net.minecraft.data.worldgen.ProcessorLists
+ net.minecraft.data.worldgen.SavannaVillagePools
- net.minecraft.data.worldgen.SnowyVillagePools
+ net.minecraft.data.worldgen.StructureFeatures
- net.minecraft.data.worldgen.SurfaceBuilders
+ net.minecraft.data.worldgen.TaigaVillagePools
- net.minecraft.data.worldgen.VillagePools
- net.minecraft.gametest.framework.GameTest
+ net.minecraft.gametest.framework.GameTestAssertException
- net.minecraft.gametest.framework.GameTestAssertPosException
+ net.minecraft.gametest.framework.GameTestBatch
- net.minecraft.gametest.framework.GameTestBatchRunner
+ net.minecraft.gametest.framework.GameTestBatchRunner$1
- net.minecraft.gametest.framework.GameTestEvent
+ net.minecraft.gametest.framework.GameTestGenerator
- net.minecraft.gametest.framework.GameTestHelper
+ net.minecraft.gametest.framework.GameTestHelper$1
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GlobalTestReporter
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.nbt.SnbtPrinterTagVisitor
+ net.minecraft.nbt.StringTag
- net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.network.protocol.game.ClientboundAddVibrationSignalPacket
+ net.minecraft.network.protocol.game.ClientboundAnimatePacket
- net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
+ net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
- net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundBlockEventPacket
+ net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChatPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$1
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerAckPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
+ net.minecraft.network.protocol.game.ClientboundDisconnectPacket
- net.minecraft.network.protocol.game.ClientboundEntityEventPacket
+ net.minecraft.network.protocol.game.ClientboundExplodePacket
- net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
+ net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
- net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLoginPacket
- net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
+ net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
- net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ClientboundOpenBookPacket
- net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
+ net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
- net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$Event
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundResourcePackPacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
- net.minecraft.network.protocol.game.ClientboundSoundPacket
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundClientInformationPacket
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundContainerAckPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
+ net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
+ net.minecraft.network.protocol.game.ServerboundPickItemPacket
- net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
+ net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ net.minecraft.network.protocol.game.ServerboundRenameItemPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
- net.minecraft.network.protocol.game.ServerboundSelectTradePacket
+ net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
- net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
+ net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
- net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
- net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundSwingPacket
- net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
- net.minecraft.network.protocol.game.ServerboundUseItemPacket
- net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$10
+ net.minecraft.network.syncher.EntityDataSerializers$11
- net.minecraft.network.syncher.EntityDataSerializers$12
+ net.minecraft.network.syncher.EntityDataSerializers$13
- net.minecraft.network.syncher.EntityDataSerializers$14
+ net.minecraft.network.syncher.EntityDataSerializers$15
- net.minecraft.network.syncher.EntityDataSerializers$16
+ net.minecraft.network.syncher.EntityDataSerializers$17
- net.minecraft.network.syncher.EntityDataSerializers$18
+ net.minecraft.network.syncher.EntityDataSerializers$19
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
- net.minecraft.network.syncher.EntityDataSerializers$8
+ net.minecraft.network.syncher.EntityDataSerializers$9
- net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.obfuscate.DontObfuscateOrShrink
- net.minecraft.obfuscate.KeepAfterObfuscation
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
- net.minecraft.realms.NarrationHelper
- net.minecraft.realms.package-info
+ net.minecraft.realms.RealmsBridge
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RealmsServerAddress
- net.minecraft.realms.RepeatedNarrator
+ net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$1
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.AttributeCommand
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
+ net.minecraft.server.commands.ReplaceItemCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.SetBlockCommand
- net.minecraft.server.commands.SetBlockCommand$Filter
+ net.minecraft.server.commands.SetBlockCommand$Mode
- net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
+ net.minecraft.server.commands.SetSpawnCommand
- net.minecraft.server.commands.SetWorldSpawnCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.Eula
- net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$1
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$1
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.WorldGenRegion
+ net.minecraft.server.level.WorldGenTickList
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerConnectionListener
- net.minecraft.server.network.ServerConnectionListener$1
+ net.minecraft.server.network.ServerConnectionListener$2
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- net.minecraft.server.network.ServerGamePacketListenerImpl
+ net.minecraft.server.network.ServerGamePacketListenerImpl$1
- net.minecraft.server.network.ServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl$State
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerResources
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.TickTask
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$1
+ net.minecraft.tags.StaticTagHelper$Wrapper
- net.minecraft.tags.StaticTags
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$1
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$Named
- net.minecraft.tags.Tag$OptionalElementEntry
+ net.minecraft.tags.Tag$OptionalTagEntry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagCollection$1
- net.minecraft.tags.TagContainer$Builder
- net.minecraft.tags.TagManager$1
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.ExtraCodecs
+ net.minecraft.util.InsensitiveStringMap
- net.minecraft.util.IntRange
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.UniformFloat
+ net.minecraft.util.UniformInt
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.world.entity.AgableMob$AgableMobGroupData
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.ai.behavior.CountDownTemptationTicks
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
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
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.goal.AvoidEntityGoal
- net.minecraft.world.entity.ai.goal.BegGoal
+ net.minecraft.world.entity.ai.goal.BoatGoals
- net.minecraft.world.entity.ai.goal.BreakDoorGoal
+ net.minecraft.world.entity.ai.goal.BreathAirGoal
- net.minecraft.world.entity.ai.goal.BreedGoal
+ net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
- net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
+ net.minecraft.world.entity.ai.goal.DolphinJumpGoal
- net.minecraft.world.entity.ai.goal.DoorInteractGoal
+ net.minecraft.world.entity.ai.goal.EatBlockGoal
- net.minecraft.world.entity.ai.goal.FleeSunGoal
+ net.minecraft.world.entity.ai.goal.FloatGoal
- net.minecraft.world.entity.ai.goal.FollowBoatGoal
+ net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
- net.minecraft.world.entity.ai.goal.FollowMobGoal
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
- net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
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
- net.minecraft.world.entity.ai.goal.PlayGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
- net.minecraft.world.entity.ai.goal.TakeFlowerGoal
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
- net.minecraft.world.entity.ai.gossip.GossipContainer$1
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
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
- net.minecraft.world.entity.ai.sensing.AxolotlHostileSensor
- net.minecraft.world.entity.ai.sensing.HostilesSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
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
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
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
+ net.minecraft.world.entity.animal.Dolphin$DolphinMoveControl
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.Fox$1
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
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$1
- net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
+ net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
- net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
+ net.minecraft.world.entity.animal.horse.Markings
- net.minecraft.world.entity.animal.horse.Mule
+ net.minecraft.world.entity.animal.horse.package-info
+ net.minecraft.world.entity.animal.horse.SkeletonHorse
- net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
+ net.minecraft.world.entity.animal.horse.TraderLlama
- net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ net.minecraft.world.entity.animal.horse.Variant
- net.minecraft.world.entity.animal.horse.ZombieHorse
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
- net.minecraft.world.entity.animal.package-info
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
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$1
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$1
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
- net.minecraft.world.entity.animal.Turtle
+ net.minecraft.world.entity.animal.Turtle$1
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTemptGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.boss.BossMob
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
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
+ net.minecraft.world.entity.monster.Evoker$1
- net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
- net.minecraft.world.entity.monster.Ghast
+ net.minecraft.world.entity.monster.Ghast$GhastLookGoal
- net.minecraft.world.entity.monster.Ghast$GhastMoveControl
+ net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
- net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
+ net.minecraft.world.entity.monster.Giant
- net.minecraft.world.entity.monster.Guardian
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
- net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
+ net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.hoglin.package-info
- net.minecraft.world.entity.monster.Husk
+ net.minecraft.world.entity.monster.Illusioner
- net.minecraft.world.entity.monster.Illusioner$1
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$1
+ net.minecraft.world.entity.monster.Phantom$AttackPhase
- net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
- net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
+ net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- net.minecraft.world.entity.monster.Phantom$PhantomLookControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
+ net.minecraft.world.entity.monster.piglin.AbstractPiglin
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.PiglinAi
- net.minecraft.world.entity.monster.piglin.PiglinArmPose
+ net.minecraft.world.entity.monster.piglin.PiglinBrute
- net.minecraft.world.entity.monster.piglin.PiglinBruteAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- net.minecraft.world.entity.monster.Pillager
+ net.minecraft.world.entity.monster.RangedAttackMob
- net.minecraft.world.entity.monster.Ravager
+ net.minecraft.world.entity.monster.Ravager$1
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$1
+ net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
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
- net.minecraft.world.entity.monster.Strider$1
+ net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
- net.minecraft.world.entity.monster.Strider$StriderPathNavigation
+ net.minecraft.world.entity.monster.Vex
- net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
+ net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
- net.minecraft.world.entity.monster.Vex$VexMoveControl
+ net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
- net.minecraft.world.entity.monster.Vindicator
+ net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
- net.minecraft.world.entity.monster.Witch
+ net.minecraft.world.entity.monster.WitherSkeleton
- net.minecraft.world.entity.monster.Zoglin
+ net.minecraft.world.entity.monster.Zombie
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
+ net.minecraft.world.entity.npc.Villager
- net.minecraft.world.entity.npc.VillagerData
+ net.minecraft.world.entity.npc.VillagerDataHolder
- net.minecraft.world.entity.npc.VillagerProfession
+ net.minecraft.world.entity.npc.VillagerTrades
- net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.projectile.AbstractArrow
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
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.CraftingContainer
- net.minecraft.world.inventory.CraftingMenu
+ net.minecraft.world.inventory.DataSlot
- net.minecraft.world.inventory.DataSlot$1
+ net.minecraft.world.inventory.DataSlot$2
- net.minecraft.world.inventory.DataSlot$3
+ net.minecraft.world.inventory.DispenserMenu
- net.minecraft.world.inventory.EnchantmentMenu
+ net.minecraft.world.inventory.EnchantmentMenu$1
- net.minecraft.world.inventory.EnchantmentMenu$2
+ net.minecraft.world.inventory.EnchantmentMenu$3
- net.minecraft.world.inventory.FurnaceFuelSlot
+ net.minecraft.world.inventory.FurnaceMenu
- net.minecraft.world.inventory.FurnaceResultSlot
+ net.minecraft.world.inventory.GrindstoneMenu
- net.minecraft.world.inventory.GrindstoneMenu$1
+ net.minecraft.world.inventory.GrindstoneMenu$2
- net.minecraft.world.inventory.GrindstoneMenu$3
+ net.minecraft.world.inventory.GrindstoneMenu$4
- net.minecraft.world.inventory.HopperMenu
+ net.minecraft.world.inventory.HorseInventoryMenu
- net.minecraft.world.inventory.HorseInventoryMenu$1
+ net.minecraft.world.inventory.HorseInventoryMenu$2
- net.minecraft.world.inventory.InventoryMenu
+ net.minecraft.world.inventory.InventoryMenu$1
- net.minecraft.world.inventory.InventoryMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu
- net.minecraft.world.inventory.ItemCombinerMenu$1
+ net.minecraft.world.inventory.ItemCombinerMenu$2
- net.minecraft.world.inventory.LecternMenu
+ net.minecraft.world.inventory.LecternMenu$1
- net.minecraft.world.inventory.LoomMenu
+ net.minecraft.world.inventory.LoomMenu$1
- net.minecraft.world.inventory.LoomMenu$2
+ net.minecraft.world.inventory.LoomMenu$3
- net.minecraft.world.inventory.LoomMenu$4
+ net.minecraft.world.inventory.LoomMenu$5
- net.minecraft.world.inventory.LoomMenu$6
+ net.minecraft.world.inventory.MenuConstructor
- net.minecraft.world.inventory.MenuType
+ net.minecraft.world.inventory.MenuType$MenuSupplier
- net.minecraft.world.inventory.MerchantContainer
+ net.minecraft.world.inventory.MerchantMenu
- net.minecraft.world.inventory.MerchantResultSlot
+ net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
- net.minecraft.world.inventory.RecipeHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
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
+ net.minecraft.world.item.crafting.Ingredient$1
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
- net.minecraft.world.item.crafting.package-info
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
+ net.minecraft.world.item.crafting.SimpleRecipeSerializer
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmokingRecipe
+ net.minecraft.world.item.crafting.StonecutterRecipe
- net.minecraft.world.item.crafting.SuspiciousStewRecipe
+ net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
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
+ net.minecraft.world.item.enchantment.ArrowDamageEnchantment
- net.minecraft.world.item.enchantment.ArrowFireEnchantment
+ net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
- net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
+ net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
- net.minecraft.world.item.enchantment.BindingCurseEnchantment
+ net.minecraft.world.item.enchantment.DamageEnchantment
- net.minecraft.world.item.enchantment.DigDurabilityEnchantment
+ net.minecraft.world.item.enchantment.DiggingEnchantment
- net.minecraft.world.item.enchantment.Enchantment
+ net.minecraft.world.item.enchantment.Enchantment$Rarity
- net.minecraft.world.item.enchantment.EnchantmentCategory
+ net.minecraft.world.item.enchantment.EnchantmentCategory$1
- net.minecraft.world.item.enchantment.EnchantmentCategory$10
+ net.minecraft.world.item.enchantment.EnchantmentCategory$11
- net.minecraft.world.item.enchantment.EnchantmentCategory$12
+ net.minecraft.world.item.enchantment.EnchantmentCategory$13
- net.minecraft.world.item.enchantment.EnchantmentCategory$14
+ net.minecraft.world.item.enchantment.EnchantmentCategory$2
- net.minecraft.world.item.enchantment.EnchantmentCategory$3
+ net.minecraft.world.item.enchantment.EnchantmentCategory$4
- net.minecraft.world.item.enchantment.EnchantmentCategory$5
+ net.minecraft.world.item.enchantment.EnchantmentCategory$6
- net.minecraft.world.item.enchantment.EnchantmentCategory$7
+ net.minecraft.world.item.enchantment.EnchantmentCategory$8
- net.minecraft.world.item.enchantment.EnchantmentCategory$9
+ net.minecraft.world.item.enchantment.EnchantmentHelper
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
- net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
- net.minecraft.world.item.enchantment.FishingSpeedEnchantment
+ net.minecraft.world.item.enchantment.FrostWalkerEnchantment
- net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
- net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
+ net.minecraft.world.item.enchantment.ProtectionEnchantment
- net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.FishBucketItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$1
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
- net.minecraft.world.item.package-info
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
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateParameters
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$1
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$1
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$NoiseParameters
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
- net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractGlassBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleCakeBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
- net.minecraft.world.level.block.ChangeOverTimeFullBlock
- net.minecraft.world.level.block.ChangeOverTimeStairBlock
+ net.minecraft.world.level.block.ChestBlock
- net.minecraft.world.level.block.ChestBlock$1
+ net.minecraft.world.level.block.ChestBlock$2
- net.minecraft.world.level.block.ChestBlock$2$1
+ net.minecraft.world.level.block.ChestBlock$3
- net.minecraft.world.level.block.ChestBlock$4
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DirtPathBlock
- net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndRodBlock$1
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.Fallable
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GrassPathBlock
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.LavaCauldronBlock
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MushroomBlock
+ net.minecraft.world.level.block.MyceliumBlock
- net.minecraft.world.level.block.NetherPortalBlock
+ net.minecraft.world.level.block.NetherPortalBlock$1
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
+ net.minecraft.world.level.block.piston.PistonMath$1
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
- net.minecraft.world.level.block.PumpkinBlock
+ net.minecraft.world.level.block.RailBlock
- net.minecraft.world.level.block.RailBlock$1
+ net.minecraft.world.level.block.RailState
- net.minecraft.world.level.block.RailState$1
- net.minecraft.world.level.block.RedstoneLampBlock
+ net.minecraft.world.level.block.RedStoneOreBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock
- net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
+ net.minecraft.world.level.block.RedstoneWallTorchBlock
- net.minecraft.world.level.block.RedStoneWireBlock
+ net.minecraft.world.level.block.RedStoneWireBlock$1
- net.minecraft.world.level.block.RenderShape
+ net.minecraft.world.level.block.RepeaterBlock
- net.minecraft.world.level.block.RespawnAnchorBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
- net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.Seagrass
- net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.TallSeagrass
- net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TintedGlassBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVines
- net.minecraft.world.level.block.TwistingVinesPlantBlock
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVines
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$1
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkBiomeContainer
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
- net.minecraft.world.level.chunk.LevelChunk$1
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.OldDataLayer
+ net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.ProtoTickList
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ChunkTickList
+ net.minecraft.world.level.ChunkTickList$1
- net.minecraft.world.level.ChunkTickList$ScheduledTick
- net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.LevelStem
- net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.entity.ChunkStatusUpdateListener
- net.minecraft.world.level.entity.EntityInLevelCallback
- net.minecraft.world.level.entity.EntityLookup
- net.minecraft.world.level.entity.EntitySection
- net.minecraft.world.level.entity.EntityTickList
- net.minecraft.world.level.entity.EntityTypeTest$1
- net.minecraft.world.level.entity.LevelEntityGetter
- net.minecraft.world.level.entity.package-info
- net.minecraft.world.level.entity.PersistentEntitySectionManager
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
- net.minecraft.world.level.entity.TransientEntitySectionManager
- net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
- net.minecraft.world.level.gameevent.BlockPositionSource$Type
- net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEventDispatcher$1
- net.minecraft.world.level.gameevent.GameEventListenerRegistrar
- net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.VibrationListener
- net.minecraft.world.level.gameevent.vibrations.VibrationPath
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BaseDiskFeature
- net.minecraft.world.level.levelgen.feature.BastionFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
- net.minecraft.world.level.levelgen.feature.DeltaFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
- net.minecraft.world.level.levelgen.feature.DripstoneUtils
+ net.minecraft.world.level.levelgen.feature.EndCityFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
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
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.GeodeBlockSettings
- net.minecraft.world.level.levelgen.GeodeLayerSettings
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseSamplingSettings
+ net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.NoiseSlideSettings
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.BaseHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceDecorator
- net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
- net.minecraft.world.level.levelgen.placement.CountDecorator
+ net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.DecorationContext
+ net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
- net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
+ net.minecraft.world.level.levelgen.placement.EdgeDecorator
- net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.FeatureDecorator
- net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.HeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.HeightMapWorldSurfaceDecorator
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
+ net.minecraft.world.level.levelgen.placement.nether.FireDecorator
- net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
+ net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
- net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.RangeDecorator
+ net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
- net.minecraft.world.level.levelgen.placement.Spread32Decorator
+ net.minecraft.world.level.levelgen.placement.SquareDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
+ net.minecraft.world.level.levelgen.placement.VeryBiasedRangeDecorator
- net.minecraft.world.level.levelgen.structure.BeardedStructureStart
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces
- net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureStart$1
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ net.minecraft.world.level.levelgen.StructureSettings
- net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.package-info
+ net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.synth.SurfaceNoise
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelTimeAccess
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
+ net.minecraft.world.level.lighting.FlatDataLayer
- net.minecraft.world.level.lighting.LayerLightEngine
+ net.minecraft.world.level.lighting.LayerLightEventListener
- net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ net.minecraft.world.level.lighting.LayerLightSectionStorage
- net.minecraft.world.level.lighting.LayerLightSectionStorage$1
+ net.minecraft.world.level.lighting.LevelLightEngine
- net.minecraft.world.level.lighting.LightEventListener
+ net.minecraft.world.level.lighting.package-info
+ net.minecraft.world.level.lighting.SkyLightEngine
- net.minecraft.world.level.lighting.SkyLightSectionStorage
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$1
- net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ net.minecraft.world.level.lighting.SpatialLongSet
- net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
- net.minecraft.world.level.LightLayer
- net.minecraft.world.level.material.EmptyFluid
+ net.minecraft.world.level.material.FlowingFluid
- net.minecraft.world.level.material.FlowingFluid$1
+ net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FogType
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.TurtleNodeEvaluator
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.ConstantIntValue$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$DataSource
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$1
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$1
- net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$1
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$1
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
+ net.minecraft.world.level.storage.loot.IntLimiter$1
- net.minecraft.world.level.storage.loot.IntRange$1
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.ItemModifierManager
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$1
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$1
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$1
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$1
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$DefaultSerializer
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$1
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$DefaultSerializer
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.RandomIntGenerators
+ net.minecraft.world.level.storage.loot.RandomValueBounds$Serializer
+ net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.storage.threaded.package-info
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
+ net.minecraft.world.level.timers.FunctionCallback
- net.minecraft.world.level.timers.FunctionCallback$Serializer
+ net.minecraft.world.level.timers.FunctionTagCallback
- net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
+ net.minecraft.world.level.timers.TimerCallback
- net.minecraft.world.level.timers.TimerCallback$Serializer
+ net.minecraft.world.level.timers.TimerCallbacks
- net.minecraft.world.level.timers.TimerQueue
+ net.minecraft.world.level.timers.TimerQueue$1
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.level.WorldGenLevel
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
```

</details>











<details><summary>net.minecraft.DetectedVersion</summary>

```diff
+ int packVersion
- int dataPackVersion
- int resourcePackVersion
+ int getPackVersion()
- int getPackVersion(PackType)
```

</details>



















<details><summary>net.minecraft.advancements.critereon.BeeNestDestroyedTrigger</summary>

```diff
+ boolean lambda$trigger$1(BeeNestDestroyedTrigger$TriggerInstance)
+ void trigger(ItemStack,int)
- boolean lambda$trigger$1(BeeNestDestroyedTrigger$TriggerInstance)
- void trigger(ItemStack,int)
```

</details>

<details><summary>net.minecraft.advancements.critereon.BlockPredicate</summary>

```diff
- IllegalStateException lambda$serializeToJson$1()
- JsonSyntaxException lambda$fromJson$0(ResourceLocation)
```

</details>

<details><summary>net.minecraft.advancements.critereon.BredAnimalsTrigger</summary>

```diff
+ void trigger(AgableMob)
- void trigger(AgeableMob)
```

</details>




<details><summary>net.minecraft.advancements.critereon.ConstructBeaconTrigger</summary>

```diff
+ boolean lambda$trigger$0(ConstructBeaconTrigger$TriggerInstance)
+ void trigger(BeaconBlockEntity)
- boolean lambda$trigger$0(ConstructBeaconTrigger$TriggerInstance)
- void trigger(ServerPlayer,int)
```

</details>



















<details><summary>net.minecraft.advancements.critereon.FluidPredicate</summary>

```diff
- IllegalStateException lambda$serializeToJson$1()
- JsonSyntaxException lambda$fromJson$0(ResourceLocation)
```

</details>





<details><summary>net.minecraft.advancements.critereon.ItemPredicate</summary>

```diff
- IllegalStateException lambda$serializeToJson$3()
- JsonSyntaxException lambda$fromJson$2(ResourceLocation)
```

</details>






































<details><summary>net.minecraft.commands.CommandFunction$Entry</summary>

```diff
+ void execute(net.minecraft.server.ServerFunctionManager,net.minecraft.commands.CommandSourceStack,java.util.ArrayDeque,int)
- void execute(net.minecraft.server.ServerFunctionManager,net.minecraft.commands.CommandSourceStack,java.util.Deque,int)
```

</details>
































<details><summary>net.minecraft.core.BlockMath</summary>

```diff
+ EnumMap vanillaUvTransformGlobalToLocal
+ EnumMap vanillaUvTransformLocalToGlobal
- Map VANILLA_UV_TRANSFORM_GLOBAL_TO_LOCAL
- Map VANILLA_UV_TRANSFORM_LOCAL_TO_GLOBAL
```

</details>




<details><summary>net.minecraft.core.BlockSource</summary>

```diff
+ Material getMaterial()
```

</details>


<details><summary>net.minecraft.core.Direction</summary>

```diff
- Direction getFacingAxis(Direction$Axis)
```

</details>




<details><summary>net.minecraft.core.Direction8</summary>

```diff
+ int EAST_MASK
+ int NORTH_EAST_MASK
+ int NORTH_MASK
+ int NORTH_WEST_MASK
+ int SOUTH_EAST_MASK
+ int SOUTH_MASK
+ int SOUTH_WEST_MASK
+ int WEST_MASK
+ int getSideMask(boolean,boolean,boolean,boolean)
```

</details>
























<details><summary>net.minecraft.core.particles.DustParticleOptions</summary>

```diff
+ float b
+ float g
+ float r
+ float scale
- Vec3 REDSTONE_PARTICLE_COLOR
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ float getB()
+ float getG()
+ float getR()
+ float getScale()
+ Float lambda$null$0(DustParticleOptions)
+ Float lambda$null$2(DustParticleOptions)
+ Float lambda$null$3(DustParticleOptions)
+ String writeToString()
+ void <init>(float,float,float,float)
+ void writeToNetwork(FriendlyByteBuf)
- App lambda$static$2(RecordCodecBuilder$Instance)
- Vec3 lambda$null$0(DustParticleOptions)
- void <init>(Vec3,float)
```

</details>

<details><summary>net.minecraft.data.structures.StructureUpdater</summary>

```diff
- CompoundTag update(CompoundTag)
```

</details>












<details><summary>net.minecraft.nbt.ByteArrayTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>

<details><summary>net.minecraft.nbt.ByteTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>


<details><summary>net.minecraft.nbt.CompoundTag</summary>

```diff
+ Logger LOGGER
+ Pattern SIMPLE_VALUE
+ Component getPrettyDisplay(String,int)
+ Component handleEscapePretty(String)
+ String handleEscape(String)
+ void stripEmptyChildren()
- void accept(TagVisitor)
```

</details>

<details><summary>net.minecraft.nbt.DoubleTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>

<details><summary>net.minecraft.nbt.EndTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>

<details><summary>net.minecraft.nbt.FloatTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>

<details><summary>net.minecraft.nbt.IntArrayTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>

<details><summary>net.minecraft.nbt.IntTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>








<details><summary>net.minecraft.nbt.NbtUtils</summary>

```diff
- Comparator YXZ_LISTTAG_DOUBLE_COMPARATOR
- Comparator YXZ_LISTTAG_INT_COMPARATOR
- Splitter COLON_SPLITTER
- Splitter COMMA_SPLITTER
- Component toPrettyComponent(Tag)
- CompoundTag packStructureTemplate(CompoundTag)
- CompoundTag snbtToStructure(String)
- CompoundTag unpackBlockState(String)
- CompoundTag unpackStructureTemplate(CompoundTag)
- double lambda$static$3(ListTag)
- double lambda$static$4(ListTag)
- double lambda$static$5(ListTag)
- int lambda$static$0(ListTag)
- int lambda$static$1(ListTag)
- int lambda$static$2(ListTag)
- ListTag lambda$packStructureTemplate$7(CompoundTag)
- ListTag lambda$packStructureTemplate$8(CompoundTag)
- ListTag lambda$unpackStructureTemplate$10(CompoundTag)
- String lambda$packBlockState$11(String)
- String packBlockState(CompoundTag)
- String structureToSnbt(CompoundTag)
- void lambda$packStructureTemplate$6(ListTag)
- void lambda$packStructureTemplate$9(CompoundTag)
- void lambda$unpackBlockState$12(String)
```

</details>

<details><summary>net.minecraft.nbt.ShortTag</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>







<details><summary>net.minecraft.network.Connection</summary>

```diff
- ConnectionProtocol getCurrentProtocol()
```

</details>










<details><summary>net.minecraft.network.chat.CommonComponents</summary>

```diff
- MutableComponent optionNameValue(Component)
```

</details>

























































<details><summary>net.minecraft.server.dedicated.DedicatedPlayerList</summary>

```diff
+ void blackList(GameProfile)
+ void whiteList(GameProfile)
```

</details>









<details><summary>net.minecraft.server.level.ChunkHolder</summary>

```diff
+ int blockChangedLightSectionFilter
+ int skyChangedLightSectionFilter
- BitSet blockChangedLightSectionFilter
- BitSet skyChangedLightSectionFilter
- CompletableFuture pendingFullStateConfirmation
- LevelHeightAccessor levelHeightAccessor
+ Either lambda$updateFutures$5(Either)
+ void <init>(ChunkHolder$PlayerProvider)
+ void updateFutures(ChunkMap)
- Either lambda$updateFutures$8(Either)
- void <init>(ChunkHolder$PlayerProvider)
- void demoteFullChunk(ChunkHolder$FullChunkStatus)
- void lambda$null$6(LevelChunk)
- void lambda$scheduleFullChunkPromotion$5(ChunkHolder$FullChunkStatus)
- void lambda$scheduleFullChunkPromotion$7(Either)
- void scheduleFullChunkPromotion(ChunkHolder$FullChunkStatus)
- void updateFutures(Executor)
```

</details>


















<details><summary>net.minecraft.server.packs.PackType</summary>

```diff
- PackType bridgeType
+ void <init>(String)
- int getVersion(GameVersion)
- void <init>(PackType)
```

</details>

<details><summary>net.minecraft.server.packs.VanillaPackResources</summary>

```diff
- PackMetadataSection packMetadata
+ void <init>(String[])
- void <init>(String[])
```

</details>




<details><summary>net.minecraft.server.packs.repository.Pack</summary>

```diff
+ PackMetadataSection BROKEN_ASSETS_FALLBACK
+ void <init>(PackSource)
- void <init>(PackSource)
```

</details>


<details><summary>net.minecraft.server.packs.repository.PackRepository</summary>

```diff
+ void <init>(RepositorySource[])
+ void lambda$discoverAvailable$0(Pack)
- Pack lambda$new$0(PackSource)
- void <init>(RepositorySource[])
- void lambda$discoverAvailable$1(Pack)
```

</details>



























<details><summary>net.minecraft.server.rcon.RconConsoleSource</summary>

```diff
+ TextComponent RCON_COMPONENT
- Component RCON_COMPONENT
```

</details>

<details><summary>net.minecraft.server.rcon.thread.GenericThread</summary>

```diff
+ void run()
```

</details>





<details><summary>net.minecraft.sounds.SoundSource</summary>

```diff
+ Map BY_NAME
+ Set getNames()
+ SoundSource byName(String)
```

</details>







<details><summary>net.minecraft.tags.EntityTypeTags</summary>

```diff
- Tag$Named AXOLOTL_ALWAYS_HOSTILES
- Tag$Named AXOLOTL_TEMPTED_HOSTILES
- Tag$Named POWDER_SNOW_WALKABLE_MOBS
+ List getWrappers()
```

</details>

<details><summary>net.minecraft.tags.TagContainer$1</summary>

```diff
+ TagCollection val$blocks
+ TagCollection val$entityTypes
+ TagCollection val$fluids
+ TagCollection val$items
- Map val$result
- RegistryAccess val$access
- TagContainer this$0
+ TagCollection getBlocks()
+ TagCollection getEntityTypes()
+ TagCollection getFluids()
+ TagCollection getItems()
+ void <init>(TagCollection)
- void <init>(Map)
- void accept(TagCollection)
```

</details>

<details><summary>net.minecraft.tags.TagManager</summary>

```diff
+ TagLoader blocks
+ TagLoader entityTypes
+ TagLoader fluids
+ TagLoader items
- Logger LOGGER
- RegistryAccess registryAccess
+ String lambda$null$0(Map$Entry)
+ void <init>()
+ void lambda$reload$1(Void)
- CompletableFuture lambda$reload$1(TagManager$LoaderInfo)
- CompletableFuture[] lambda$reload$2(int)
- String lambda$null$4(Map$Entry)
- TagCollection lambda$createLoader$6(ResourceManager)
- TagManager$LoaderInfo createLoader(StaticTagHelper)
- void <clinit>()
- void <init>(RegistryAccess)
- void lambda$null$3(TagManager$LoaderInfo)
- void lambda$reload$0(StaticTagHelper)
- void lambda$reload$5(Void)
```

</details>













<details><summary>net.minecraft.util.Mth</summary>

```diff
+ int roundUp(int,int)
- double clampedMap(double,double,double,double,double)
- double map(double,double,double,double,double)
- double wobble(double)
- float normal(Random,float,float)
- float randomBetween(Random,float,float)
- int randomBetweenInclusive(Random,int,int)
- int roundToward(int,int)
```

</details>

























































<details><summary>net.minecraft.util.datafix.fixes.References</summary>

```diff
- DSL$TypeReference ENTITY_CHUNK
- String lambda$static$25()
```

</details>























<details><summary>net.minecraft.util.datafix.schemas.V1460</summary>

```diff
- TypeTemplate lambda$registerTypes$46(Schema)
```

</details>




































<details><summary>net.minecraft.world.BossEvent</summary>

```diff
+ float percent
- float progress
+ float getPercent()
+ void setPercent(float)
- float getProgress()
- void setProgress(float)
```

</details>









<details><summary>net.minecraft.world.SimpleContainer</summary>

```diff
+ boolean isSameItem(ItemStack)
```

</details>













<details><summary>net.minecraft.world.entity.AreaEffectCloud</summary>

```diff
+ boolean canUse()
+ List getEffects()
+ void use()
- boolean lambda$tick$0(Map$Entry)
```

</details>






<details><summary>net.minecraft.world.entity.LightningBolt</summary>

```diff
- void powerLightningRod()
```

</details>






















<details><summary>net.minecraft.world.entity.ai.behavior.BabyFollowAdult</summary>

```diff
+ float speedModifier
- Function speedModifier
+ AgableMob getNearestAdult(AgableMob)
+ boolean checkExtraStartConditions(AgableMob)
+ void start(AgableMob,long)
- AgeableMob getNearestAdult(AgeableMob)
- boolean checkExtraStartConditions(AgeableMob)
- Float lambda$new$0(LivingEntity)
- void <init>(Function)
- void start(AgeableMob,long)
```

</details>















<details><summary>net.minecraft.world.entity.ai.behavior.MeleeAttack</summary>

```diff
+ boolean lambda$isHoldingUsableProjectileWeapon$0(Item)
- boolean lambda$isHoldingUsableProjectileWeapon$0(ItemStack)
```

</details>



















<details><summary>net.minecraft.world.entity.animal.Cat</summary>

```diff
+ AgableMob getBreedOffspring(AgableMob)
+ Cat getBreedOffspring(AgableMob)
+ void usePlayerItem(ItemStack)
- AgeableMob getBreedOffspring(AgeableMob)
- Cat getBreedOffspring(AgeableMob)
- void usePlayerItem(ItemStack)
```

</details>


<details><summary>net.minecraft.world.entity.animal.Chicken</summary>

```diff
+ AgableMob getBreedOffspring(AgableMob)
+ Chicken getBreedOffspring(AgableMob)
- AgeableMob getBreedOffspring(AgeableMob)
- Chicken getBreedOffspring(AgeableMob)
```

</details>

<details><summary>net.minecraft.world.entity.animal.Cow</summary>

```diff
+ AgableMob getBreedOffspring(AgableMob)
+ Cow getBreedOffspring(AgableMob)
- AgeableMob getBreedOffspring(AgeableMob)
- Cow getBreedOffspring(AgeableMob)
```

</details>


<details><summary>net.minecraft.world.entity.animal.horse.AbstractHorse</summary>

```diff
+ AgableMob getBreedOffspring(AgableMob)
+ boolean setSlot(ItemStack)
+ float getJumpRidingScale()
+ void setJumpRidingScale(float)
+ void setOffspringAttributes(AbstractHorse)
- AgeableMob getBreedOffspring(AgeableMob)
- boolean lambda$getSlot$1(ItemStack)
- boolean lambda$getSlot$2(ItemStack)
- SlotAccess createEquipmentSlotAccess(Predicate)
- SlotAccess getSlot(int)
- void setOffspringAttributes(AbstractHorse)
```

</details>

<details><summary>net.minecraft.world.entity.boss.EnderDragonPart</summary>

```diff
- boolean shouldBeSaved()
```

</details>

<details><summary>net.minecraft.world.entity.boss.enderdragon.EnderDragon</summary>

```diff
+ void dropExperience(int)
```

</details>














<details><summary>net.minecraft.world.entity.decoration.ItemFrame$1</summary>

```diff
+ int[] $SwitchMap$net$minecraft$core$Direction$Axis
- ItemFrame this$0
+ void <clinit>()
- boolean set(ItemStack)
- ItemStack get()
- void <init>(ItemFrame)
```

</details>

<details><summary>net.minecraft.world.entity.vehicle.Boat</summary>

```diff
- boolean lambda$tickBubbleColumn$0(Entity)
- ItemStack getPickResult()
```

</details>





<details><summary>net.minecraft.world.entity.vehicle.MinecartHopper</summary>

```diff
+ Level getLevel()
```

</details>

<details><summary>net.minecraft.world.entity.vehicle.MinecartSpawner$1</summary>

```diff
+ BlockPos getPos()
+ Level getLevel()
+ void broadcastEvent(int)
- void broadcastEvent(BlockPos,int)
```

</details>





<details><summary>net.minecraft.world.inventory.AbstractContainerMenu</summary>

```diff
+ List slots
- NonNullList slots
+ boolean consideredTheSameItem(ItemStack)
+ Slot getSlotFor(Container,int)
+ void addItem(ItemStack)
+ void clearContainer(Container)
- void clearContainer(Container)
```

</details>



















<details><summary>net.minecraft.world.item.BucketItem</summary>

```diff
+ boolean emptyBucket(BlockHitResult)
- boolean emptyContents(BlockHitResult)
- void lambda$use$0(SoundEvent)
```

</details>









<details><summary>net.minecraft.world.item.FireworkRocketItem</summary>

```diff
- ItemStack getDefaultInstance()
```

</details>


<details><summary>net.minecraft.world.item.PickaxeItem</summary>

```diff
- Object2IntMap MIN_LEVEL_FOR_DROPS
- void lambda$static$0(Object2IntOpenHashMap)
```

</details>










<details><summary>net.minecraft.world.level.EntityGetter</summary>

```diff
+ List getEntitiesOfClass(java.lang.Class,net.minecraft.world.phys.AABB,java.util.function.Predicate)
- List getEntities(net.minecraft.world.level.entity.EntityTypeTest,net.minecraft.world.phys.AABB,java.util.function.Predicate)
+ List getLoadedEntitiesOfClass(AABB)
+ List getLoadedEntitiesOfClass(Predicate)
+ LivingEntity getNearestLoadedEntity(AABB)
- boolean lambda$getNearbyEntities$2(LivingEntity)
- boolean lambda$getNearestEntity$1(LivingEntity)
- List getEntitiesOfClass(Predicate)
```

</details>



<details><summary>net.minecraft.world.level.GameRules</summary>

```diff
- GameRules$Key RULE_FREEZE_DAMAGE
- GameRules$Key RULE_PLAYERS_SLEEPING_PERCENTAGE
+ void <init>(MinecraftServer)
```

</details>





<details><summary>net.minecraft.world.level.GameType</summary>

```diff
+ GameType NOT_SET
- Component longName
- Component shortName
- GameType DEFAULT_MODE
+ Component getDisplayName()
- Component getLongDisplayName()
- Component getShortDisplayName()
- GameType byNullableId(int)
- int getNullableId(GameType)
```

</details>



<details><summary>net.minecraft.world.level.block.AttachedStemBlock</summary>

```diff
- Supplier seedSupplier
+ Item getSeedItem()
+ void <init>(BlockBehaviour$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>


<details><summary>net.minecraft.world.level.block.BarrelBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>



<details><summary>net.minecraft.world.level.block.BaseEntityBlock</summary>

```diff
- BlockEntityTicker createTickerHelper(BlockEntityTicker)
```

</details>

<details><summary>net.minecraft.world.level.block.BasePressurePlateBlock</summary>

```diff
+ void checkPressed(BlockState,int)
- void checkPressed(BlockState,int)
```

</details>


<details><summary>net.minecraft.world.level.block.BeaconBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>




<details><summary>net.minecraft.world.level.block.Block</summary>

```diff
+ boolean is(Block)
+ boolean is(Tag)
+ boolean isExceptionForConnection(Block)
+ boolean shouldRenderFace(Direction)
+ int getTickDelay(LevelReader)
+ void handleRain(BlockPos)
+ void prepareRender(BlockPos)
- boolean isExceptionForConnection(BlockState)
- boolean shouldRenderFace(BlockPos)
- void handlePrecipitation(Biome$Precipitation)
```

</details>


<details><summary>net.minecraft.world.level.block.Blocks</summary>

```diff
+ Block GRASS_PATH
- Block AMETHYST_BLOCK
- Block AMETHYST_CLUSTER
- Block BLACK_CANDLE
- Block BLACK_CANDLE_CAKE
- Block BLUE_CANDLE
- Block BLUE_CANDLE_CAKE
- Block BROWN_CANDLE
- Block BROWN_CANDLE_CAKE
- Block BUDDING_AMETHYST
- Block CALCITE
- Block CANDLE
- Block CANDLE_CAKE
- Block COPPER_BLOCK
- Block COPPER_ORE
- Block CUT_COPPER
- Block CUT_COPPER_SLAB
- Block CUT_COPPER_STAIRS
- Block CYAN_CANDLE
- Block CYAN_CANDLE_CAKE
- Block DIRT_PATH
- Block DRIPSTONE_BLOCK
- Block GRAY_CANDLE
- Block GRAY_CANDLE_CAKE
- Block GREEN_CANDLE
- Block GREEN_CANDLE_CAKE
- Block LARGE_AMETHYST_BUD
- Block LAVA_CAULDRON
- Block LIGHT_BLUE_CANDLE
- Block LIGHT_BLUE_CANDLE_CAKE
- Block LIGHT_GRAY_CANDLE
- Block LIGHT_GRAY_CANDLE_CAKE
- Block LIGHTLY_WEATHERED_COPPER_BLOCK
- Block LIGHTLY_WEATHERED_CUT_COPPER
- Block LIGHTLY_WEATHERED_CUT_COPPER_SLAB
- Block LIGHTLY_WEATHERED_CUT_COPPER_STAIRS
- Block LIGHTNING_ROD
- Block LIME_CANDLE
- Block LIME_CANDLE_CAKE
- Block MAGENTA_CANDLE
- Block MAGENTA_CANDLE_CAKE
- Block MEDIUM_AMETHYST_BUD
- Block ORANGE_CANDLE
- Block ORANGE_CANDLE_CAKE
- Block PINK_CANDLE
- Block PINK_CANDLE_CAKE
- Block POINTED_DRIPSTONE
- Block POWDER_SNOW
- Block POWDER_SNOW_CAULDRON
- Block PURPLE_CANDLE
- Block PURPLE_CANDLE_CAKE
- Block RED_CANDLE
- Block RED_CANDLE_CAKE
- Block SCULK_SENSOR
- Block SEMI_WEATHERED_COPPER_BLOCK
- Block SEMI_WEATHERED_CUT_COPPER
- Block SEMI_WEATHERED_CUT_COPPER_SLAB
- Block SEMI_WEATHERED_CUT_COPPER_STAIRS
- Block SMALL_AMETHYST_BUD
- Block TINTED_GLASS
- Block TUFF
- Block WATER_CAULDRON
- Block WAXED_COPPER
- Block WAXED_CUT_COPPER
- Block WAXED_CUT_COPPER_SLAB
- Block WAXED_CUT_COPPER_STAIRS
- Block WAXED_LIGHTLY_WEATHERED_COPPER
- Block WAXED_LIGHTLY_WEATHERED_CUT_COPPER
- Block WAXED_LIGHTLY_WEATHERED_CUT_COPPER_SLAB
- Block WAXED_LIGHTLY_WEATHERED_CUT_COPPER_STAIRS
- Block WAXED_SEMI_WEATHERED_COPPER
- Block WAXED_SEMI_WEATHERED_CUT_COPPER
- Block WAXED_SEMI_WEATHERED_CUT_COPPER_SLAB
- Block WAXED_SEMI_WEATHERED_CUT_COPPER_STAIRS
- Block WEATHERED_COPPER_BLOCK
- Block WEATHERED_CUT_COPPER
- Block WEATHERED_CUT_COPPER_SLAB
- Block WEATHERED_CUT_COPPER_STAIRS
- Block WHITE_CANDLE
- Block WHITE_CANDLE_CAKE
- Block YELLOW_CANDLE
- Block YELLOW_CANDLE_CAKE
+ BlockEntityType lambda$static$12()
+ boolean lambda$static$13(EntityType)
+ boolean lambda$static$28(EntityType)
+ boolean lambda$static$30(EntityType)
+ ConfiguredFeature lambda$static$35()
+ ConfiguredFeature lambda$static$36()
+ int lambda$static$14(BlockState)
+ int lambda$static$15(BlockState)
+ int lambda$static$21(BlockState)
+ int lambda$static$22(BlockState)
+ int lambda$static$23(BlockState)
+ int lambda$static$24(BlockState)
+ int lambda$static$37(BlockState)
+ int lambda$static$8(BlockState)
+ int lambda$static$9(BlockState)
- BlockEntityType lambda$static$14()
- boolean lambda$static$15(EntityType)
- boolean lambda$static$35(EntityType)
- boolean lambda$static$37(EntityType)
- boolean lambda$static$48(BlockPos)
- ConfiguredFeature lambda$static$42()
- ConfiguredFeature lambda$static$43()
- ConfiguredFeature lambda$static$8()
- ConfiguredFeature lambda$static$9()
- int lambda$static$12(BlockState)
- int lambda$static$13(BlockState)
- int lambda$static$28(BlockState)
- int lambda$static$30(BlockState)
- int lambda$static$36(BlockState)
- int lambda$static$40(BlockState)
- int lambda$static$41(BlockState)
- int lambda$static$44(BlockState)
- int lambda$static$45(BlockState)
- int lambda$static$46(BlockState)
- int lambda$static$47(BlockState)
- Item lambda$static$21()
- Item lambda$static$22()
- Item lambda$static$23()
- Item lambda$static$24()
```

</details>

<details><summary>net.minecraft.world.level.block.BrewingStandBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>

<details><summary>net.minecraft.world.level.block.BucketPickup</summary>

```diff
+ Fluid takeLiquid(net.minecraft.world.level.LevelAccessor,net.minecraft.core.BlockPos,net.minecraft.world.level.block.state.BlockState)
- ItemStack pickupBlock(net.minecraft.world.level.LevelAccessor,net.minecraft.core.BlockPos,net.minecraft.world.level.block.state.BlockState)
- Optional getPickupSound()
```

</details>

<details><summary>net.minecraft.world.level.block.DispenserBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>






<details><summary>net.minecraft.world.level.block.EnchantmentTableBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>

<details><summary>net.minecraft.world.level.block.EndPortalBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.EndRodBlock</summary>

```diff
+ VoxelShape X_AXIS_AABB
+ VoxelShape Y_AXIS_AABB
+ VoxelShape Z_AXIS_AABB
+ BlockState mirror(Mirror)
+ BlockState rotate(Rotation)
+ boolean isPathfindable(PathComputationType)
+ void <clinit>()
+ VoxelShape getShape(CollisionContext)
```

</details>

<details><summary>net.minecraft.world.level.block.FallingBlock</summary>

```diff
+ void onBroken(FallingBlockEntity)
+ void onLand(FallingBlockEntity)
```

</details>

<details><summary>net.minecraft.world.level.block.FenceBlock</summary>

```diff
+ boolean isSameFence(Block)
- boolean isSameFence(BlockState)
```

</details>



<details><summary>net.minecraft.world.level.block.FlowerPotBlock</summary>

```diff
- boolean isEmpty()
```

</details>










<details><summary>net.minecraft.world.level.block.JigsawBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.KelpBlock</summary>

```diff
+ boolean canAttachToBlock(Block)
- boolean canAttachTo(BlockState)
```

</details>


<details><summary>net.minecraft.world.level.block.LecternBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>




<details><summary>net.minecraft.world.level.block.ShulkerBoxBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>

<details><summary>net.minecraft.world.level.block.SignBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>








<details><summary>net.minecraft.world.level.block.SpawnerBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
- BlockEntityTicker getTicker(BlockEntityType)
```

</details>




<details><summary>net.minecraft.world.level.block.StemBlock</summary>

```diff
- Supplier seedSupplier
+ Item getSeedItem()
+ void <init>(BlockBehaviour$Properties)
- void <init>(BlockBehaviour$Properties)
```

</details>


<details><summary>net.minecraft.world.level.block.StructureBlock</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockState)
```

</details>







<details><summary>net.minecraft.world.level.block.entity.BaseContainerBlockEntity</summary>

```diff
+ void <init>(BlockEntityType)
+ void load(CompoundTag)
- void <init>(BlockState)
- void load(CompoundTag)
```

</details>


<details><summary>net.minecraft.world.level.block.entity.BedBlockEntity</summary>

```diff
+ void <init>()
+ void <init>(DyeColor)
- void <init>(BlockState)
- void <init>(DyeColor)
```

</details>



<details><summary>net.minecraft.world.level.block.entity.BlockEntityType</summary>

```diff
+ Supplier factory
- BlockEntityType SCULK_SENSOR
- BlockEntityType$BlockEntitySupplier factory
+ BlockEntity create()
+ boolean isValid(Block)
+ void <init>(Type)
- BlockEntity create(BlockState)
- boolean isValid(BlockState)
- void <init>(Type)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.DispenserBlockEntity</summary>

```diff
+ void <init>()
+ void <init>(BlockEntityType)
+ void load(CompoundTag)
- void <init>(BlockState)
- void <init>(BlockState)
- void load(CompoundTag)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity</summary>

```diff
+ void <init>()
+ void load(CompoundTag)
+ void tick()
- void <init>(BlockState)
- void bookAnimationTick(EnchantmentTableBlockEntity)
- void load(CompoundTag)
```

</details>


<details><summary>net.minecraft.world.level.block.entity.SignBlockEntity</summary>

```diff
+ void <init>()
+ void load(CompoundTag)
- void <init>(BlockState)
- void load(CompoundTag)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.SmokerBlockEntity</summary>

```diff
+ void <init>()
- void <init>(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.block.entity.SpawnerBlockEntity$1</summary>

```diff
+ BlockPos getPos()
+ Level getLevel()
+ void broadcastEvent(int)
+ void setNextSpawnData(SpawnData)
- void broadcastEvent(BlockPos,int)
- void setNextSpawnData(SpawnData)
```

</details>








<details><summary>net.minecraft.world.level.chunk.LevelChunk</summary>

```diff
+ boolean lastSaveHadEntities
+ ClassInstanceMultiMap[] entitySections
+ long lastSaveTime
- Int2ObjectMap gameEventDispatcherSections
- Map tickersInLevel
- TickingBlockEntity NULL_TICKER
+ Block lambda$unpackTicks$9(BlockPos)
+ boolean lambda$getLights$6(BlockPos)
+ boolean lambda$replaceWithPacketData$4(BlockPos)
+ boolean lambda$replaceWithPacketData$5(BlockPos)
+ ClassInstanceMultiMap[] getEntitySections()
+ Entity lambda$new$0(Entity)
+ Fluid lambda$unpackTicks$10(BlockPos)
+ LevelLightEngine getLightEngine()
+ LongSet lambda$addReferenceForFeature$8(StructureFeature)
+ LongSet lambda$getReferencesForFeature$7(StructureFeature)
+ void <init>(ProtoChunk)
+ void addBlockEntity(BlockEntity)
+ void getEntities(Predicate)
+ void getEntities(Predicate)
+ void getEntitiesOfClass(Predicate)
+ void removeEntity(Entity,int)
+ void removeEntity(Entity)
+ void setBlockEntity(BlockEntity)
+ void setLastSaveHadEntities(boolean)
+ void setLastSaveTime(long)
- Block lambda$unpackTicks$8(BlockPos)
- boolean access$200(BlockPos)
- boolean isInLevel()
- boolean isPositionInSection(BlockPos)
- boolean isTicking(BlockPos)
- boolean lambda$getLights$5(BlockPos)
- boolean lambda$replaceWithPacketData$4(BlockEntity)
- Fluid lambda$unpackTicks$9(BlockPos)
- GameEventDispatcher getEventDispatcher(int)
- GameEventDispatcher lambda$getEventDispatcher$0(int)
- int getHeight()
- int getMinBuildHeight()
- Level access$300(LevelChunk)
- LevelChunk$RebindableTickingBlockEntityWrapper lambda$updateBlockEntityTicker$11(LevelChunk$RebindableTickingBlockEntityWrapper)
- Logger access$400()
- LongSet lambda$addReferenceForFeature$7(StructureFeature)
- LongSet lambda$getReferencesForFeature$6(StructureFeature)
- TickingBlockEntity createTicker(BlockEntityTicker)
- void <init>(Consumer)
- void addAndRegisterBlockEntity(BlockEntity)
- void addGameEventListener(BlockEntity)
- void invalidateAllBlockEntities()
- void lambda$registerAllBlockEntitiesAfterLevelLoad$10(BlockEntity)
- void onBlockEntityRemove(BlockEntity)
- void registerAllBlockEntitiesAfterLevelLoad()
- void removeBlockEntityTicker(BlockPos)
- void removeGameEventListener(BlockEntity)
- void setBlockEntity(BlockEntity)
- void updateBlockEntityTicker(BlockEntity)
```

</details>

<details><summary>net.minecraft.world.level.chunk.storage.IOWorker</summary>

```diff
+ Either lambda$load$2(ChunkPos)
- CompletableFuture loadAsync(ChunkPos)
- Either lambda$loadAsync$2(ChunkPos)
```

</details>

<details><summary>net.minecraft.world.level.chunk.storage.IOWorker$Priority</summary>

```diff
+ IOWorker$Priority HIGH
+ IOWorker$Priority LOW
- IOWorker$Priority BACKGROUND
- IOWorker$Priority FOREGROUND
- IOWorker$Priority SHUTDOWN
```

</details>

<details><summary>net.minecraft.world.level.levelgen.Decoratable</summary>

```diff
+ Object chance(int)
- Object rarity(int)
```

</details>






<details><summary>net.minecraft.world.level.levelgen.feature.IcebergFeature</summary>

```diff
+ boolean isIcebergBlock(Block)
- boolean isIcebergState(BlockState)
```

</details>
























<details><summary>net.minecraft.world.level.levelgen.feature.TreeFeature</summary>

```diff
+ boolean doPlace(TreeConfiguration)
+ void lambda$doPlace$6(FoliagePlacer$FoliageAttachment)
+ void simulate(FeatureConfiguration)
+ void simulate(TreeConfiguration)
- boolean doPlace(TreeConfiguration)
- void lambda$doPlace$6(FoliagePlacer$FoliageAttachment)
```

</details>






















<details><summary>net.minecraft.world.level.material.LavaFluid</summary>

```diff
- Optional getPickupSound()
```

</details>



































<details><summary>net.minecraft.world.level.storage.DerivedLevelData</summary>

```diff
+ void fillCrashReportCategory(CrashReportCategory)
- void fillCrashReportCategory(LevelHeightAccessor)
```

</details>

<details><summary>net.minecraft.world.level.storage.LevelData</summary>

```diff
+ String lambda$fillCrashReportCategory$0()
+ void fillCrashReportCategory(CrashReportCategory)
- String lambda$fillCrashReportCategory$0(LevelHeightAccessor)
- void fillCrashReportCategory(LevelHeightAccessor)
```

</details>






<details><summary>net.minecraft.world.level.storage.ServerLevelData</summary>

```diff
+ void fillCrashReportCategory(CrashReportCategory)
- void fillCrashReportCategory(LevelHeightAccessor)
```

</details>








<details><summary>net.minecraft.world.level.storage.loot.LootPool</summary>

```diff
+ RandomIntGenerator rolls
+ RandomValueBounds bonusRolls
- NumberProvider bonusRolls
- NumberProvider rolls
+ LootPoolEntryContainer[] access$200(LootPool)
+ RandomIntGenerator access$100(LootPool)
+ RandomValueBounds access$300(LootPool)
+ void <init>(LootPool$1)
+ void <init>(RandomValueBounds)
- LootPoolEntryContainer[] access$300(LootPool)
- NumberProvider access$100(LootPool)
- NumberProvider access$200(LootPool)
- void <init>(LootPool$1)
- void <init>(NumberProvider)
```

</details>

<details><summary>net.minecraft.world.level.storage.loot.LootPool$Builder</summary>

```diff
+ RandomIntGenerator rolls
+ RandomValueBounds bonusRolls
- NumberProvider bonusRolls
- NumberProvider rolls
+ LootPool$Builder setBonusRolls(RandomValueBounds)
+ LootPool$Builder setRolls(RandomIntGenerator)
- LootPool$Builder setBonusRolls(NumberProvider)
- LootPool$Builder setRolls(NumberProvider)
```

</details>

























<details><summary>net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer</summary>

```diff
- IllegalStateException lambda$serializeCustom$0()
- JsonParseException lambda$deserialize$1(ResourceLocation)
```

</details>


















<details><summary>net.minecraft.world.phys.shapes.SubShape</summary>

```diff
+ void setFull(int,int,int,boolean,boolean)
- int clampToShape(Direction$Axis,int)
- void fill(int,int,int)
```

</details>

<details><summary>Added and removed classes</summary>

```diff
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.blocks.BlockStateArgument
+ net.minecraft.commands.arguments.blocks.BlockStateParser
- net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.coordinates.BlockPosArgument
- net.minecraft.commands.arguments.coordinates.ColumnPosArgument
+ net.minecraft.commands.arguments.coordinates.Coordinates
- net.minecraft.commands.arguments.coordinates.LocalCoordinates
+ net.minecraft.commands.arguments.coordinates.package-info
+ net.minecraft.commands.arguments.coordinates.RotationArgument
- net.minecraft.commands.arguments.coordinates.SwizzleArgument
+ net.minecraft.commands.arguments.coordinates.Vec2Argument
- net.minecraft.commands.arguments.coordinates.Vec3Argument
+ net.minecraft.commands.arguments.coordinates.WorldCoordinate
- net.minecraft.commands.arguments.coordinates.WorldCoordinates
- net.minecraft.commands.arguments.item.FunctionArgument
+ net.minecraft.commands.arguments.item.FunctionArgument$1
- net.minecraft.commands.arguments.item.FunctionArgument$2
+ net.minecraft.commands.arguments.item.FunctionArgument$Result
- net.minecraft.commands.arguments.item.ItemArgument
+ net.minecraft.commands.arguments.item.ItemInput
- net.minecraft.commands.arguments.item.ItemParser
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$NbtPath
+ net.minecraft.commands.arguments.NbtPathArgument$Node
- net.minecraft.commands.arguments.NbtTagArgument
+ net.minecraft.commands.arguments.ObjectiveArgument
- net.minecraft.commands.arguments.ObjectiveCriteriaArgument
+ net.minecraft.commands.arguments.OperationArgument
- net.minecraft.commands.arguments.OperationArgument$Operation
+ net.minecraft.commands.arguments.OperationArgument$SimpleOperation
- net.minecraft.commands.arguments.package-info
- net.minecraft.commands.arguments.ParticleArgument
+ net.minecraft.commands.arguments.RangeArgument
- net.minecraft.commands.arguments.RangeArgument$Floats
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
- net.minecraft.commands.arguments.SlotArgument
+ net.minecraft.commands.arguments.TeamArgument
- net.minecraft.commands.arguments.TimeArgument
+ net.minecraft.commands.arguments.UuidArgument
- net.minecraft.core.particles.DustColorTransitionOptions
- net.minecraft.core.particles.DustParticleOptionsBase
+ net.minecraft.core.particles.ItemParticleOption
- net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.QuartPos
+ net.minecraft.core.Registry
- net.minecraft.core.RegistryAccess
+ net.minecraft.core.RegistryAccess$RegistryData
- net.minecraft.core.RegistryAccess$RegistryHolder
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.SerializableUUID
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
+ net.minecraft.data.BuiltinRegistries
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.HashCache
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLoot
- net.minecraft.data.loot.ChestLoot
+ net.minecraft.data.loot.EntityLoot
- net.minecraft.data.loot.FishingLoot
+ net.minecraft.data.loot.GiftLoot
- net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.PiglinBarterLoot
+ net.minecraft.data.Main
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
+ net.minecraft.data.models.BlockModelGenerators$TintState
- net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$1
- net.minecraft.data.models.blockstates.Condition$CompositeCondition
+ net.minecraft.data.models.blockstates.Condition$Operation
- net.minecraft.data.models.blockstates.Condition$TerminalCondition
+ net.minecraft.data.models.blockstates.MultiPartGenerator
- net.minecraft.data.models.blockstates.MultiPartGenerator$1
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
- net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
+ net.minecraft.data.models.blockstates.PropertyDispatch$1
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
+ net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.model.DelegatedModel
- net.minecraft.data.models.model.ModelLocationUtils
+ net.minecraft.data.models.model.ModelTemplate
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
- net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.package-info
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
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$StructureConversionException
- net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1
+ net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.data.worldgen.BastionBridgePools
- net.minecraft.data.worldgen.BastionHoglinStablePools
+ net.minecraft.data.worldgen.BastionHousingUnitsPools
- net.minecraft.data.worldgen.BastionPieces
+ net.minecraft.data.worldgen.BastionSharedPools
- net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.biome.BiomeReport
+ net.minecraft.data.worldgen.biome.Biomes
+ net.minecraft.data.worldgen.biome.package-info
- net.minecraft.data.worldgen.biome.VanillaBiomes
+ net.minecraft.data.worldgen.BiomeDefaultFeatures
- net.minecraft.data.worldgen.Carvers
+ net.minecraft.data.worldgen.DesertVillagePools
- net.minecraft.data.worldgen.Features
+ net.minecraft.data.worldgen.Features$Configs
- net.minecraft.data.worldgen.Features$Decorators
+ net.minecraft.data.worldgen.Features$States
- net.minecraft.data.worldgen.PillagerOutpostPools
+ net.minecraft.data.worldgen.PlainVillagePools
- net.minecraft.data.worldgen.Pools
+ net.minecraft.data.worldgen.ProcessorLists
- net.minecraft.data.worldgen.SavannaVillagePools
+ net.minecraft.data.worldgen.SnowyVillagePools
- net.minecraft.data.worldgen.StructureFeatures
+ net.minecraft.data.worldgen.SurfaceBuilders
- net.minecraft.data.worldgen.TaigaVillagePools
+ net.minecraft.data.worldgen.VillagePools
- net.minecraft.gametest.framework.AfterBatch
- net.minecraft.gametest.framework.ExhaustedAttemptsException
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestHelper$1
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestRunner$1
- net.minecraft.gametest.framework.JUnitLikeTestReporter
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.gametest.framework.ReportGameListener
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.StringTagVisitor
- net.minecraft.nbt.TagVisitor
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundChatPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$1
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerAckPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
- net.minecraft.network.protocol.game.ClientboundDisconnectPacket
+ net.minecraft.network.protocol.game.ClientboundEntityEventPacket
- net.minecraft.network.protocol.game.ClientboundExplodePacket
+ net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
- net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
+ net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundLevelEventPacket
- net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
- net.minecraft.network.protocol.game.ClientboundLoginPacket
+ net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
- net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
+ net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ClientboundOpenBookPacket
+ net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
- net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
+ net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
- net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$Event
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ net.minecraft.network.protocol.game.ClientboundRecipePacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket$State
+ net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
- net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundResourcePackPacket
- net.minecraft.network.protocol.game.ClientboundRespawnPacket
+ net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerAckPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.status.ClientboundPongResponsePacket
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$10
- net.minecraft.network.syncher.EntityDataSerializers$11
+ net.minecraft.network.syncher.EntityDataSerializers$12
- net.minecraft.network.syncher.EntityDataSerializers$13
+ net.minecraft.network.syncher.EntityDataSerializers$14
- net.minecraft.network.syncher.EntityDataSerializers$15
+ net.minecraft.network.syncher.EntityDataSerializers$16
- net.minecraft.network.syncher.EntityDataSerializers$17
+ net.minecraft.network.syncher.EntityDataSerializers$18
- net.minecraft.network.syncher.EntityDataSerializers$19
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.EntityDataSerializers$5
+ net.minecraft.network.syncher.EntityDataSerializers$6
- net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.EntityDataSerializers$8
- net.minecraft.network.syncher.EntityDataSerializers$9
+ net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.obfuscate.DontObfuscateOrShrink
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$1
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$1
+ net.minecraft.server.ConsoleInputSource
- net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.Eula
+ net.minecraft.server.level.FeatureSimulator
+ net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$1
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayerGameMode
+ net.minecraft.server.level.ThreadedLevelLightEngine
- net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
+ net.minecraft.server.level.Ticket
- net.minecraft.server.level.TicketType
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.level.WorldGenTickList
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$2
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerPlayerConnection
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerResources
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
- net.minecraft.tags.GameEventTags
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.SerializationTags
+ net.minecraft.tags.SetTag
- net.minecraft.tags.StaticTagHelper
+ net.minecraft.tags.StaticTagHelper$1
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.StaticTags
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$1
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$BuilderEntry
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$Named
+ net.minecraft.tags.Tag$OptionalElementEntry
- net.minecraft.tags.Tag$OptionalTagEntry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.TagCollection
+ net.minecraft.tags.TagCollection$1
- net.minecraft.tags.TagCollection$NetworkPayload
- net.minecraft.tags.TagContainer$CollectionConsumer
- net.minecraft.tags.TagManager$LoaderInfo
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
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
+ net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.ExtraCodecs$1
+ net.minecraft.util.IntRange
- net.minecraft.util.LazyLoadedValue
+ net.minecraft.util.LimitedCapacityList
- net.minecraft.util.UniformInt
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.world.entity.AgableMob
- net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.RandomSwim
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunIf
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.RunSometimes
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
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
+ net.minecraft.world.entity.ai.control.DolphinLookControl
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
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
+ net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.PlayGoal
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
+ net.minecraft.world.entity.ai.goal.TakeFlowerGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$1
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
- net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
+ net.minecraft.world.entity.animal.Bee
- net.minecraft.world.entity.animal.Bee$1
+ net.minecraft.world.entity.animal.Bee$BaseBeeGoal
- net.minecraft.world.entity.animal.Bee$BeeAttackGoal
+ net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
- net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
- net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
+ net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeLookControl
+ net.minecraft.world.entity.animal.Bee$BeePollinateGoal
- net.minecraft.world.entity.animal.Bee$BeeWanderGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$1
+ net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
- net.minecraft.world.entity.animal.Fox$FaceplantGoal
+ net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
- net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
+ net.minecraft.world.entity.animal.Fox$FoxBreedGoal
- net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
+ net.minecraft.world.entity.animal.Fox$FoxFloatGoal
- net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
+ net.minecraft.world.entity.animal.Fox$FoxGroupData
- net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Fox$FoxLookControl
- net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
+ net.minecraft.world.entity.animal.Fox$FoxMoveControl
- net.minecraft.world.entity.animal.Fox$FoxPanicGoal
+ net.minecraft.world.entity.animal.Fox$FoxPounceGoal
- net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
+ net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
- net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
+ net.minecraft.world.entity.animal.Fox$SeekShelterGoal
- net.minecraft.world.entity.animal.Fox$SleepGoal
+ net.minecraft.world.entity.animal.Fox$StalkPreyGoal
- net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
- net.minecraft.world.entity.animal.horse.Llama$1
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
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.IronGolem$Crackiness
+ net.minecraft.world.entity.animal.MushroomCow
- net.minecraft.world.entity.animal.MushroomCow$MushroomType
+ net.minecraft.world.entity.animal.Ocelot
- net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.package-info
- net.minecraft.world.entity.animal.Panda
+ net.minecraft.world.entity.animal.Panda$Gene
- net.minecraft.world.entity.animal.Panda$PandaAttackGoal
+ net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
- net.minecraft.world.entity.animal.Panda$PandaBreedGoal
+ net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
- net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
+ net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
- net.minecraft.world.entity.animal.Panda$PandaMoveControl
+ net.minecraft.world.entity.animal.Panda$PandaPanicGoal
- net.minecraft.world.entity.animal.Panda$PandaRollGoal
+ net.minecraft.world.entity.animal.Panda$PandaSitGoal
- net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
+ net.minecraft.world.entity.animal.Parrot
- net.minecraft.world.entity.animal.Parrot$1
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
- net.minecraft.world.entity.animal.Squid$1
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$1
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$1
+ net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
- net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
- net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
+ net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
- net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTemptGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
+ net.minecraft.world.entity.decoration.Motive
+ net.minecraft.world.entity.decoration.package-info
- net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.item.FallingBlockEntity
+ net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.CaveSpider
- net.minecraft.world.entity.monster.Creeper
+ net.minecraft.world.entity.monster.CrossbowAttackMob
- net.minecraft.world.entity.monster.Drowned
+ net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
- net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
+ net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
- net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
+ net.minecraft.world.entity.monster.ElderGuardian
- net.minecraft.world.entity.monster.EnderMan
+ net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
+ net.minecraft.world.entity.monster.Endermite
- net.minecraft.world.entity.monster.Enemy
+ net.minecraft.world.entity.monster.Evoker
- net.minecraft.world.entity.monster.Evoker$1
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
+ net.minecraft.world.entity.monster.Illusioner$1
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
+ net.minecraft.world.entity.monster.Phantom$1
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
- net.minecraft.world.entity.monster.Ravager$1
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.Ravager$RavagerNavigation
+ net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
- net.minecraft.world.entity.monster.Shulker
+ net.minecraft.world.entity.monster.Shulker$1
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
+ net.minecraft.world.entity.monster.Silverfish
- net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- net.minecraft.world.entity.monster.Skeleton
+ net.minecraft.world.entity.monster.Slime
- net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
+ net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
- net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ net.minecraft.world.entity.monster.Slime$SlimeMoveControl
- net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager
- net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ net.minecraft.world.entity.monster.Spider
- net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
+ net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
- net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
+ net.minecraft.world.entity.monster.Stray
- net.minecraft.world.entity.monster.Strider
+ net.minecraft.world.entity.monster.Strider$1
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
+ net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.package-info
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
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$Pickup
- net.minecraft.world.entity.projectile.AbstractHurtingProjectile
+ net.minecraft.world.entity.projectile.Arrow
- net.minecraft.world.entity.projectile.DragonFireball
+ net.minecraft.world.entity.projectile.EvokerFangs
- net.minecraft.world.entity.projectile.EyeOfEnder
+ net.minecraft.world.entity.projectile.Fireball
- net.minecraft.world.entity.projectile.FireworkRocketEntity
+ net.minecraft.world.entity.projectile.FishingHook
- net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$FishHookState
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.projectile.ItemSupplier
- net.minecraft.world.entity.projectile.LargeFireball
+ net.minecraft.world.entity.projectile.LlamaSpit
- net.minecraft.world.entity.projectile.package-info
- net.minecraft.world.entity.projectile.Projectile
+ net.minecraft.world.entity.projectile.ProjectileUtil
- net.minecraft.world.entity.projectile.ShulkerBullet
+ net.minecraft.world.entity.projectile.SmallFireball
- net.minecraft.world.entity.projectile.Snowball
+ net.minecraft.world.entity.projectile.SpectralArrow
- net.minecraft.world.entity.projectile.ThrowableItemProjectile
+ net.minecraft.world.entity.projectile.ThrowableProjectile
- net.minecraft.world.entity.projectile.ThrownEgg
+ net.minecraft.world.entity.projectile.ThrownEnderpearl
- net.minecraft.world.entity.projectile.ThrownExperienceBottle
+ net.minecraft.world.entity.projectile.ThrownPotion
- net.minecraft.world.entity.projectile.ThrownTrident
+ net.minecraft.world.entity.projectile.WitherSkull
+ net.minecraft.world.entity.raid.package-info
+ net.minecraft.world.entity.raid.Raid
- net.minecraft.world.entity.raid.Raid$1
- net.minecraft.world.entity.raid.Raid$RaiderType
+ net.minecraft.world.entity.raid.Raid$RaidStatus
+ net.minecraft.world.entity.raid.Raider
- net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
+ net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- net.minecraft.world.entity.raid.Raider$RaiderCelebration
+ net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
- net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.schedule.Activity
+ net.minecraft.world.entity.schedule.Keyframe
- net.minecraft.world.entity.schedule.package-info
- net.minecraft.world.entity.schedule.Schedule
+ net.minecraft.world.entity.schedule.ScheduleBuilder
- net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
+ net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.vehicle.AbstractMinecart
- net.minecraft.world.entity.vehicle.AbstractMinecart$1
+ net.minecraft.world.entity.vehicle.AbstractMinecart$Type
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
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
- net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.context.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext$1
+ net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.UseOnContext
- net.minecraft.world.item.crafting.AbstractCookingRecipe
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.FireworkRocketRecipe
+ net.minecraft.world.item.crafting.FireworkStarFadeRecipe
- net.minecraft.world.item.crafting.FireworkStarRecipe
+ net.minecraft.world.item.crafting.Ingredient
- net.minecraft.world.item.crafting.Ingredient$1
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
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$10
- net.minecraft.world.item.CreativeModeTab$11
+ net.minecraft.world.item.CreativeModeTab$12
- net.minecraft.world.item.CreativeModeTab$2
+ net.minecraft.world.item.CreativeModeTab$3
- net.minecraft.world.item.CreativeModeTab$4
+ net.minecraft.world.item.CreativeModeTab$5
- net.minecraft.world.item.CreativeModeTab$6
+ net.minecraft.world.item.CreativeModeTab$7
- net.minecraft.world.item.CreativeModeTab$8
+ net.minecraft.world.item.CreativeModeTab$9
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.DebugStickItem
- net.minecraft.world.item.DiggerItem
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
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.FoodOnAStickItem
- net.minecraft.world.item.GameMasterBlockItem
+ net.minecraft.world.item.HangingEntityItem
- net.minecraft.world.item.HoeItem
+ net.minecraft.world.item.HoneyBottleItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$1
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.ProjectileWeaponItem$Type
- net.minecraft.world.item.Rarity
+ net.minecraft.world.item.RecordItem
- net.minecraft.world.item.SaddleItem
+ net.minecraft.world.item.ScaffoldingBlockItem
- net.minecraft.world.item.ServerItemCooldowns
+ net.minecraft.world.item.ShearsItem
- net.minecraft.world.item.ShieldItem
+ net.minecraft.world.item.ShovelItem
- net.minecraft.world.item.SignItem
+ net.minecraft.world.item.SimpleFoiledItem
- net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.StandingAndWallBlockItem
+ net.minecraft.world.item.SuspiciousStewItem
- net.minecraft.world.item.SwordItem
+ net.minecraft.world.item.ThrowablePotionItem
- net.minecraft.world.item.Tier
+ net.minecraft.world.item.TieredItem
- net.minecraft.world.item.Tiers
+ net.minecraft.world.item.TippedArrowItem
- net.minecraft.world.item.TooltipFlag
+ net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$BiomeCategory
+ net.minecraft.world.level.biome.Biome$ClimateParameters
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$1
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.BiomeZoomer
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
+ net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$1
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$1
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$NoiseParameters
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
- net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
+ net.minecraft.world.level.biome.OverworldBiomeSource
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
+ net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.ChainBlock
+ net.minecraft.world.level.block.ChainBlock$1
- net.minecraft.world.level.block.ChangeOverTimeBlock
- net.minecraft.world.level.block.ChangeOverTimeSlabBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChorusFlowerBlock
+ net.minecraft.world.level.block.ChorusPlantBlock
- net.minecraft.world.level.block.CocoaBlock
+ net.minecraft.world.level.block.CocoaBlock$1
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DetectorRailBlock
- net.minecraft.world.level.block.DetectorRailBlock$1
+ net.minecraft.world.level.block.DiodeBlock
- net.minecraft.world.level.block.DirectionalBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickableBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.Lantern
- net.minecraft.world.level.block.LanternBlock
- net.minecraft.world.level.block.LayeredCauldronBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
- net.minecraft.world.level.block.NetherrackBlock
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
+ net.minecraft.world.level.block.NetherWartBlock
+ net.minecraft.world.level.block.NoteBlock
- net.minecraft.world.level.block.NyliumBlock
+ net.minecraft.world.level.block.ObserverBlock
- net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.piston.MovingPistonBlock
- net.minecraft.world.level.block.piston.package-info
+ net.minecraft.world.level.block.piston.PistonBaseBlock
- net.minecraft.world.level.block.piston.PistonBaseBlock$1
+ net.minecraft.world.level.block.piston.PistonHeadBlock
- net.minecraft.world.level.block.piston.PistonHeadBlock$1
+ net.minecraft.world.level.block.piston.PistonMath
- net.minecraft.world.level.block.piston.PistonMath$1
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
+ net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock$1
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlant
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlant
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$1
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkBiomeContainer
- net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.ChunkStatus
+ net.minecraft.world.level.chunk.ChunkStatus$ChunkType
- net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.OldDataLayer
- net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage$1
+ net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ChunkTickList
- net.minecraft.world.level.ChunkTickList$1
+ net.minecraft.world.level.ChunkTickList$ScheduledTick
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.entity.ChunkEntities
- net.minecraft.world.level.entity.EntityAccess
- net.minecraft.world.level.entity.EntityInLevelCallback$1
- net.minecraft.world.level.entity.EntityPersistentStorage
- net.minecraft.world.level.entity.EntitySectionStorage
- net.minecraft.world.level.entity.EntityTypeTest
- net.minecraft.world.level.entity.LevelCallback
- net.minecraft.world.level.entity.LevelEntityGetterAdapter
- net.minecraft.world.level.entity.PersistentEntitySectionManager$1
- net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager$1
- net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.gameevent.BlockPositionSource
- net.minecraft.world.level.gameevent.EntityPositionSource
- net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
- net.minecraft.world.level.gameevent.vibrations.package-info
- net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CaveWorldCarver
- net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
+ net.minecraft.world.level.levelgen.carver.NetherWorldCarver
- net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
- net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BaseDiskFeature
+ net.minecraft.world.level.levelgen.feature.BastionFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
- net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$Factory
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GeodeFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$1
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.SimulatedFeature
- net.minecraft.world.level.levelgen.feature.SmallDripstoneFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
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
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.NoiseSamplingSettings
- net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.NoiseSlideSettings
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.placement.BaseHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ChanceDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
+ net.minecraft.world.level.levelgen.placement.CountDecorator
- net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
+ net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
- net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.DecorationContext
- net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
+ net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.EdgeDecorator
+ net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.HeightmapDecorator
- net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.HeightMapWorldSurfaceDecorator
+ net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
- net.minecraft.world.level.levelgen.placement.nether.FireDecorator
+ net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
- net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
- net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
- net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.RangeDecorator
- net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
+ net.minecraft.world.level.levelgen.placement.Spread32Decorator
- net.minecraft.world.level.levelgen.placement.SquareDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
- net.minecraft.world.level.levelgen.placement.VeryBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.structure.BeardedStructureStart
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces
- net.minecraft.world.level.levelgen.structure.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.IglooPieces
+ net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
- net.minecraft.world.level.levelgen.structure.MineShaftPieces
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureStart$1
- net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.StructureSettings
+ net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.package-info
- net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.synth.SurfaceNoise
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.LevelHeightAccessor
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.lighting.BlockLightEngine
- net.minecraft.world.level.lighting.BlockLightSectionStorage
+ net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- net.minecraft.world.level.lighting.DataLayerStorageMap
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
- net.minecraft.world.level.lighting.FlatDataLayer
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$1
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SaveDataDirtyRunnable
- net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$1
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.ConstantIntValue
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$1
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$1
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$1
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
- net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
+ net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LimitCount$1
+ net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
+ net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$1
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$1
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$1
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$1
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
+ net.minecraft.world.level.storage.loot.IntLimiter
+ net.minecraft.world.level.storage.loot.IntLimiter$Serializer
- net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$Serializer
- net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$1
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$1
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$1
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$1
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$DefaultSerializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$1
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$1
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$1
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$1
- net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.RandomIntGenerator
+ net.minecraft.world.level.storage.loot.RandomValueBounds
- net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.threaded.package-info
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.TickList
+ net.minecraft.world.level.TickNextTickData
- net.minecraft.world.level.TickPriority
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$1
+ net.minecraft.world.level.timers.TimerQueue$Event
+ net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.package-info
- net.minecraft.world.phys.AABB
+ net.minecraft.world.phys.BlockHitResult
- net.minecraft.world.phys.EntityHitResult
+ net.minecraft.world.phys.HitResult
- net.minecraft.world.phys.HitResult$Type
+ net.minecraft.world.phys.package-info
- net.minecraft.world.phys.shapes.ArrayVoxelShape
+ net.minecraft.world.phys.shapes.ArrayVoxelShape$1
- net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
+ net.minecraft.world.phys.shapes.BooleanOp
- net.minecraft.world.phys.shapes.CollisionContext
+ net.minecraft.world.phys.shapes.CubePointRange
- net.minecraft.world.phys.shapes.CubeVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteCubeMerger
- net.minecraft.world.phys.shapes.DiscreteVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ net.minecraft.world.phys.shapes.EntityCollisionContext
- net.minecraft.world.phys.shapes.EntityCollisionContext$1
+ net.minecraft.world.phys.shapes.IdenticalMerger
- net.minecraft.world.phys.shapes.IndexMerger
+ net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
- net.minecraft.world.phys.shapes.IndirectMerger
+ net.minecraft.world.phys.shapes.IntPointRange
- net.minecraft.world.phys.shapes.package-info
+ net.minecraft.world.phys.shapes.WorldRegionIndirectVoxelShape
+ net.minecraft.world.phys.Vec2
- net.minecraft.world.phys.Vec3
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
+ net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
- net.minecraft.world.scores.PlayerTeam
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.Scoreboard
+ net.minecraft.world.scores.ScoreboardSaveData
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
```

</details>

<br/>
<html><table>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
<a href="https://github.com/PixiGeko/Minecraft-generated-data">Minecraft-generated-data</a>
<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
</table></html>
<br/>