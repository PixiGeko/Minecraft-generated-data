<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w04a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w04a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-01-24T15:31:52+00:00</td></tr>
<tr><th>SHA1</th><td>4eeb1dae750f4152927fe51c5065ca7aa3d53e3e</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/4eeb1dae750f4152927fe51c5065ca7aa3d53e3e/19w04a.json">https://piston-meta.mojang.com/v1/packages/4eeb1dae750f4152927fe51c5065ca7aa3d53e3e/19w04a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/261edfd76c32c9f675c12264b6fa03f670c3325c/server.jar">https://piston-data.mojang.com/v1/objects/261edfd76c32c9f675c12264b6fa03f670c3325c/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/4a075e5ceae3fc15efd36222daeb832c94e16946/client.jar">https://piston-data.mojang.com/v1/objects/4a075e5ceae3fc15efd36222daeb832c94e16946/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w03c">19w03c</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/building_blocks/andesite_slab_from_andesite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/andesite_stairs_from_andesite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/andesite_wall_from_andesite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/brick_slab_from_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/brick_stairs_from_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/brick_wall_from_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/chiseled_quartz_block_from_quartz_block_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/chiseled_red_sandstone_from_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/chiseled_sandstone_from_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/chiseled_stone_bricks_stone_from_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/cobblestone_slab_from_cobblestone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/cobblestone_stairs_from_cobblestone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/cut_red_sandstone_from_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/cut_sandstone_from_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/dark_prismarine_slab_from_dark_prismarine_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/dark_prismarine_stairs_from_dark_prismarine_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/diorite_slab_from_diorite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/diorite_stairs_from_diorite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/diorite_wall_from_diorite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/end_stone_brick_slab_from_end_stone_brick_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/end_stone_brick_slab_from_end_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/end_stone_brick_stairs_from_end_stone_brick_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/end_stone_brick_stairs_from_end_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/end_stone_brick_wall_from_end_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/end_stone_bricks_from_end_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/granite_slab_from_granite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/granite_stairs_from_granite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/granite_wall_from_granite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/mossy_cobblestone_slab_from_mossy_cobblestone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/mossy_cobblestone_stairs_from_mossy_cobblestone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/mossy_stone_brick_slab_from_mossy_stone_brick_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/mossy_stone_brick_stairs_from_mossy_stone_brick_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/nether_brick_slab_from_nether_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/nether_brick_stairs_from_nether_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/nether_brick_wall_from_nether_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_andesite_from_andesite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_andesite_slab_from_polished_andesite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_andesite_stairs_from_polished_andesite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_diorite_from_diorite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_diorite_slab_from_polished_diorite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_diorite_stairs_from_polished_diorite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_granite_from_granite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_granite_slab_from_polished_granite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/polished_granite_stairs_from_polished_granite_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/prismarine_brick_slab_from_prismarine_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/prismarine_brick_stairs_from_prismarine_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/prismarine_slab_from_prismarine_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/prismarine_stairs_from_prismarine_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/prismarine_wall_from_prismarine_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/purpur_pillar_from_purpur_block_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/purpur_slab_from_purpur_block_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/purpur_stairs_from_purpur_block_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/quartz_pillar_from_quartz_block_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/quartz_slab_from_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/quartz_stairs_from_quartz_block_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/red_nether_brick_slab_from_red_nether_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/red_nether_brick_stairs_from_red_nether_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/red_sandstone_slab_from_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/red_sandstone_stairs_from_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/red_sandstone_wall_from_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/sandstone_slab_from_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/sandstone_stairs_from_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/sandstone_wall_from_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/smooth_quartz_slab_from_smooth_quartz_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/smooth_quartz_stairs_from_smooth_quartz_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/smooth_red_sandstone_slab_from_smooth_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/smooth_red_sandstone_stairs_from_smooth_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/smooth_sandstone_slab_from_smooth_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/smooth_sandstone_stairs_from_smooth_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_brick_slab_from_stone_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_brick_slab_from_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_brick_stairs_from_stone_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_brick_stairs_from_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_brick_wall_from_stone_bricks_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_brick_walls_from_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_bricks_from_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_slab_from_stone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/stone_stairs_from_stone_stonecutting.json
+  minecraft/advancements/recipes/decorations/cobblestone_wall_from_cobblestone_stonecutting.json
+  minecraft/advancements/recipes/decorations/mossy_cobblestone_wall_from_mossy_cobblestone_stonecutting.json
+  minecraft/advancements/recipes/decorations/stonecutter.json
+  minecraft/recipes/andesite_slab_from_andesite_stonecutting.json
+  minecraft/recipes/andesite_stairs_from_andesite_stonecutting.json
+  minecraft/recipes/andesite_wall_from_andesite_stonecutting.json
+  minecraft/recipes/brick_slab_from_bricks_stonecutting.json
+  minecraft/recipes/brick_stairs_from_bricks_stonecutting.json
+  minecraft/recipes/brick_wall_from_bricks_stonecutting.json
+  minecraft/recipes/chiseled_quartz_block_from_quartz_block_stonecutting.json
+  minecraft/recipes/chiseled_red_sandstone_from_red_sandstone_stonecutting.json
+  minecraft/recipes/chiseled_sandstone_from_sandstone_stonecutting.json
+  minecraft/recipes/chiseled_stone_bricks_stone_from_stonecutting.json
+  minecraft/recipes/cobblestone_slab_from_cobblestone_stonecutting.json
+  minecraft/recipes/cobblestone_stairs_from_cobblestone_stonecutting.json
+  minecraft/recipes/cobblestone_wall_from_cobblestone_stonecutting.json
+  minecraft/recipes/cut_red_sandstone_from_red_sandstone_stonecutting.json
+  minecraft/recipes/cut_sandstone_from_sandstone_stonecutting.json
+  minecraft/recipes/dark_prismarine_slab_from_dark_prismarine_stonecutting.json
+  minecraft/recipes/dark_prismarine_stairs_from_dark_prismarine_stonecutting.json
+  minecraft/recipes/diorite_slab_from_diorite_stonecutting.json
+  minecraft/recipes/diorite_stairs_from_diorite_stonecutting.json
+  minecraft/recipes/diorite_wall_from_diorite_stonecutting.json
+  minecraft/recipes/end_stone_brick_slab_from_end_stone_brick_stonecutting.json
+  minecraft/recipes/end_stone_brick_slab_from_end_stone_stonecutting.json
+  minecraft/recipes/end_stone_brick_stairs_from_end_stone_brick_stonecutting.json
+  minecraft/recipes/end_stone_brick_stairs_from_end_stone_stonecutting.json
+  minecraft/recipes/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+  minecraft/recipes/end_stone_brick_wall_from_end_stone_stonecutting.json
+  minecraft/recipes/end_stone_bricks_from_end_stone_stonecutting.json
+  minecraft/recipes/granite_slab_from_granite_stonecutting.json
+  minecraft/recipes/granite_stairs_from_granite_stonecutting.json
+  minecraft/recipes/granite_wall_from_granite_stonecutting.json
+  minecraft/recipes/mossy_cobblestone_slab_from_mossy_cobblestone_stonecutting.json
+  minecraft/recipes/mossy_cobblestone_stairs_from_mossy_cobblestone_stonecutting.json
+  minecraft/recipes/mossy_cobblestone_wall_from_mossy_cobblestone_stonecutting.json
+  minecraft/recipes/mossy_stone_brick_slab_from_mossy_stone_brick_stonecutting.json
+  minecraft/recipes/mossy_stone_brick_stairs_from_mossy_stone_brick_stonecutting.json
+  minecraft/recipes/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+  minecraft/recipes/nether_brick_slab_from_nether_bricks_stonecutting.json
+  minecraft/recipes/nether_brick_stairs_from_nether_bricks_stonecutting.json
+  minecraft/recipes/nether_brick_wall_from_nether_bricks_stonecutting.json
+  minecraft/recipes/polished_andesite_from_andesite_stonecutting.json
+  minecraft/recipes/polished_andesite_slab_from_polished_andesite_stonecutting.json
+  minecraft/recipes/polished_andesite_stairs_from_polished_andesite_stonecutting.json
+  minecraft/recipes/polished_diorite_from_diorite_stonecutting.json
+  minecraft/recipes/polished_diorite_slab_from_polished_diorite_stonecutting.json
+  minecraft/recipes/polished_diorite_stairs_from_polished_diorite_stonecutting.json
+  minecraft/recipes/polished_granite_from_granite_stonecutting.json
+  minecraft/recipes/polished_granite_slab_from_polished_granite_stonecutting.json
+  minecraft/recipes/polished_granite_stairs_from_polished_granite_stonecutting.json
+  minecraft/recipes/prismarine_brick_slab_from_prismarine_stonecutting.json
+  minecraft/recipes/prismarine_brick_stairs_from_prismarine_stonecutting.json
+  minecraft/recipes/prismarine_slab_from_prismarine_stonecutting.json
+  minecraft/recipes/prismarine_stairs_from_prismarine_stonecutting.json
+  minecraft/recipes/prismarine_wall_from_prismarine_stonecutting.json
+  minecraft/recipes/purpur_pillar_from_purpur_block_stonecutting.json
+  minecraft/recipes/purpur_slab_from_purpur_block_stonecutting.json
+  minecraft/recipes/purpur_stairs_from_purpur_block_stonecutting.json
+  minecraft/recipes/quartz_pillar_from_quartz_block_stonecutting.json
+  minecraft/recipes/quartz_slab_from_stonecutting.json
+  minecraft/recipes/quartz_stairs_from_quartz_block_stonecutting.json
+  minecraft/recipes/red_nether_brick_slab_from_red_nether_bricks_stonecutting.json
+  minecraft/recipes/red_nether_brick_stairs_from_red_nether_bricks_stonecutting.json
+  minecraft/recipes/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
+  minecraft/recipes/red_sandstone_slab_from_red_sandstone_stonecutting.json
+  minecraft/recipes/red_sandstone_stairs_from_red_sandstone_stonecutting.json
+  minecraft/recipes/red_sandstone_wall_from_red_sandstone_stonecutting.json
+  minecraft/recipes/sandstone_slab_from_sandstone_stonecutting.json
+  minecraft/recipes/sandstone_stairs_from_sandstone_stonecutting.json
+  minecraft/recipes/sandstone_wall_from_sandstone_stonecutting.json
+  minecraft/recipes/smooth_quartz_slab_from_smooth_quartz_stonecutting.json
+  minecraft/recipes/smooth_quartz_stairs_from_smooth_quartz_stonecutting.json
+  minecraft/recipes/smooth_red_sandstone_slab_from_smooth_red_sandstone_stonecutting.json
+  minecraft/recipes/smooth_red_sandstone_stairs_from_smooth_red_sandstone_stonecutting.json
+  minecraft/recipes/smooth_sandstone_slab_from_smooth_sandstone_stonecutting.json
+  minecraft/recipes/smooth_sandstone_stairs_from_smooth_sandstone_stonecutting.json
+  minecraft/recipes/stone_brick_slab_from_stone_bricks_stonecutting.json
+  minecraft/recipes/stone_brick_slab_from_stone_stonecutting.json
+  minecraft/recipes/stone_brick_stairs_from_stone_bricks_stonecutting.json
+  minecraft/recipes/stone_brick_stairs_from_stone_stonecutting.json
+  minecraft/recipes/stone_brick_wall_from_stone_bricks_stonecutting.json
+  minecraft/recipes/stone_brick_walls_from_stone_stonecutting.json
+  minecraft/recipes/stone_bricks_from_stone_stonecutting.json
+  minecraft/recipes/stone_slab_from_stone_stonecutting.json
+  minecraft/recipes/stone_stairs_from_stone_stonecutting.json
+  minecraft/recipes/stonecutter.json
+  minecraft/structures/village/desert/zombie
+  minecraft/structures/village/desert/zombie/houses
+  minecraft/structures/village/desert/zombie/houses/desert_medium_house_1.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_medium_house_2.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_small_house_1.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_small_house_2.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_small_house_3.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_small_house_4.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_small_house_5.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_small_house_6.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_small_house_7.nbt
+  minecraft/structures/village/desert/zombie/houses/desert_small_house_8.nbt
+  minecraft/structures/village/desert/zombie/streets
+  minecraft/structures/village/desert/zombie/streets/corner_01.nbt
+  minecraft/structures/village/desert/zombie/streets/corner_02.nbt
+  minecraft/structures/village/desert/zombie/streets/crossroad_01.nbt
+  minecraft/structures/village/desert/zombie/streets/crossroad_02.nbt
+  minecraft/structures/village/desert/zombie/streets/crossroad_03.nbt
+  minecraft/structures/village/desert/zombie/streets/square_01.nbt
+  minecraft/structures/village/desert/zombie/streets/square_02.nbt
+  minecraft/structures/village/desert/zombie/streets/straight_01.nbt
+  minecraft/structures/village/desert/zombie/streets/straight_02.nbt
+  minecraft/structures/village/desert/zombie/streets/straight_03.nbt
+  minecraft/structures/village/desert/zombie/streets/turn_01.nbt
+  minecraft/structures/village/desert/zombie/terminators
+  minecraft/structures/village/desert/zombie/terminators/terminator_02.nbt
+  minecraft/structures/village/desert/zombie/town_centers
+  minecraft/structures/village/desert/zombie/town_centers/desert_meeting_point_1.nbt
+  minecraft/structures/village/desert/zombie/town_centers/desert_meeting_point_2.nbt
+  minecraft/structures/village/desert/zombie/town_centers/desert_meeting_point_3.nbt
+  minecraft/structures/village/desert/zombie/villagers
+  minecraft/structures/village/desert/zombie/villagers/armorer.nbt
+  minecraft/structures/village/desert/zombie/villagers/butcher.nbt
+  minecraft/structures/village/desert/zombie/villagers/cartographer.nbt
+  minecraft/structures/village/desert/zombie/villagers/cleric.nbt
+  minecraft/structures/village/desert/zombie/villagers/farmer.nbt
+  minecraft/structures/village/desert/zombie/villagers/fishermen.nbt
+  minecraft/structures/village/desert/zombie/villagers/fletcher.nbt
+  minecraft/structures/village/desert/zombie/villagers/leatherworker.nbt
+  minecraft/structures/village/desert/zombie/villagers/librarian.nbt
+  minecraft/structures/village/desert/zombie/villagers/nitwit.nbt
+  minecraft/structures/village/desert/zombie/villagers/shepherd.nbt
+  minecraft/structures/village/desert/zombie/villagers/toolsmith.nbt
+  minecraft/structures/village/desert/zombie/villagers/unemployed.nbt
+  minecraft/structures/village/desert/zombie/villagers/weaponsmith.nbt
+  minecraft/structures/village/taiga/houses/taiga_medium_house_4.nbt
+  minecraft/structures/village/taiga/zombie
+  minecraft/structures/village/taiga/zombie/houses
+  minecraft/structures/village/taiga/zombie/houses/taiga_armorer_house_2.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_cartographer_house_1.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_fisher_cottage_1.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_large_farm_2.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_library_1.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_medium_house_1.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_medium_house_2.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_medium_house_3.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_medium_house_4.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_shepherds_house_1.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_small_house_1.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_small_house_2.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_small_house_3.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_small_house_4.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_small_house_5.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_temple_1.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_tool_smith_1.nbt
+  minecraft/structures/village/taiga/zombie/houses/taiga_weaponsmith_2.nbt
+  minecraft/structures/village/taiga/zombie/streets
+  minecraft/structures/village/taiga/zombie/streets/corner_01.nbt
+  minecraft/structures/village/taiga/zombie/streets/corner_02.nbt
+  minecraft/structures/village/taiga/zombie/streets/corner_03.nbt
+  minecraft/structures/village/taiga/zombie/streets/crossroad_01.nbt
+  minecraft/structures/village/taiga/zombie/streets/crossroad_02.nbt
+  minecraft/structures/village/taiga/zombie/streets/crossroad_03.nbt
+  minecraft/structures/village/taiga/zombie/streets/crossroad_04.nbt
+  minecraft/structures/village/taiga/zombie/streets/crossroad_05.nbt
+  minecraft/structures/village/taiga/zombie/streets/crossroad_06.nbt
+  minecraft/structures/village/taiga/zombie/streets/straight_01.nbt
+  minecraft/structures/village/taiga/zombie/streets/straight_02.nbt
+  minecraft/structures/village/taiga/zombie/streets/straight_03.nbt
+  minecraft/structures/village/taiga/zombie/streets/straight_04.nbt
+  minecraft/structures/village/taiga/zombie/streets/straight_05.nbt
+  minecraft/structures/village/taiga/zombie/streets/straight_06.nbt
+  minecraft/structures/village/taiga/zombie/streets/turn_01.nbt
+  minecraft/structures/village/taiga/zombie/town_centers
+  minecraft/structures/village/taiga/zombie/town_centers/taiga_meeting_point_1.nbt
+  minecraft/structures/village/taiga/zombie/town_centers/taiga_meeting_point_2.nbt
+  minecraft/structures/village/taiga/zombie/villagers
+  minecraft/structures/village/taiga/zombie/villagers/armorer.nbt
+  minecraft/structures/village/taiga/zombie/villagers/butcher.nbt
+  minecraft/structures/village/taiga/zombie/villagers/cartographer.nbt
+  minecraft/structures/village/taiga/zombie/villagers/cleric.nbt
+  minecraft/structures/village/taiga/zombie/villagers/farmer.nbt
+  minecraft/structures/village/taiga/zombie/villagers/fishermen.nbt
+  minecraft/structures/village/taiga/zombie/villagers/fletcher.nbt
+  minecraft/structures/village/taiga/zombie/villagers/leatherworker.nbt
+  minecraft/structures/village/taiga/zombie/villagers/librarian.nbt
+  minecraft/structures/village/taiga/zombie/villagers/nitwit.nbt
+  minecraft/structures/village/taiga/zombie/villagers/shepherd.nbt
+  minecraft/structures/village/taiga/zombie/villagers/toolsmith.nbt
+  minecraft/structures/village/taiga/zombie/villagers/unemployed.nbt
+  minecraft/structures/village/taiga/zombie/villagers/weaponsmith.nbt
+  minecraft/structures/village/taiga/taiga_decoration_5.nbt
+  minecraft/structures/village/taiga/taiga_decoration_6.nbt
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/textures/gui/container/stonecutter.png
```

</details>

## Registries

<details><summary>menu.txt</summary>

```diff
+ minecraft:stonecutter
```

</details>

<details><summary>recipe_serializer.txt</summary>

```diff
+ minecraft:stonecutting
```

</details>

<details><summary>recipe_type.txt</summary>

```diff
+ minecraft:stonecutting
```

</details>

<details><summary>sound_event.txt</summary>

```diff
+ minecraft:ui.stonecutter.take_result
+ minecraft:ui.stonecutter.select_recipe
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/building_blocks/andesite_slab_from_andesite_stonecutting.json
+ recipes/building_blocks/andesite_stairs_from_andesite_stonecutting.json
+ recipes/building_blocks/andesite_wall_from_andesite_stonecutting.json
+ recipes/building_blocks/brick_slab_from_bricks_stonecutting.json
+ recipes/building_blocks/brick_stairs_from_bricks_stonecutting.json
+ recipes/building_blocks/brick_wall_from_bricks_stonecutting.json
+ recipes/building_blocks/chiseled_quartz_block_from_quartz_block_stonecutting.json
+ recipes/building_blocks/chiseled_red_sandstone_from_red_sandstone_stonecutting.json
+ recipes/building_blocks/chiseled_sandstone_from_sandstone_stonecutting.json
+ recipes/building_blocks/chiseled_stone_bricks_stone_from_stonecutting.json
+ recipes/building_blocks/cobblestone_slab_from_cobblestone_stonecutting.json
+ recipes/building_blocks/cobblestone_stairs_from_cobblestone_stonecutting.json
+ recipes/building_blocks/cut_red_sandstone_from_red_sandstone_stonecutting.json
+ recipes/building_blocks/cut_sandstone_from_sandstone_stonecutting.json
+ recipes/building_blocks/dark_prismarine_slab_from_dark_prismarine_stonecutting.json
+ recipes/building_blocks/dark_prismarine_stairs_from_dark_prismarine_stonecutting.json
+ recipes/building_blocks/diorite_slab_from_diorite_stonecutting.json
+ recipes/building_blocks/diorite_stairs_from_diorite_stonecutting.json
+ recipes/building_blocks/diorite_wall_from_diorite_stonecutting.json
+ recipes/building_blocks/end_stone_bricks_from_end_stone_stonecutting.json
+ recipes/building_blocks/end_stone_brick_slab_from_end_stone_brick_stonecutting.json
+ recipes/building_blocks/end_stone_brick_slab_from_end_stone_stonecutting.json
+ recipes/building_blocks/end_stone_brick_stairs_from_end_stone_brick_stonecutting.json
+ recipes/building_blocks/end_stone_brick_stairs_from_end_stone_stonecutting.json
+ recipes/building_blocks/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+ recipes/building_blocks/end_stone_brick_wall_from_end_stone_stonecutting.json
+ recipes/building_blocks/granite_slab_from_granite_stonecutting.json
+ recipes/building_blocks/granite_stairs_from_granite_stonecutting.json
+ recipes/building_blocks/granite_wall_from_granite_stonecutting.json
+ recipes/building_blocks/mossy_cobblestone_slab_from_mossy_cobblestone_stonecutting.json
+ recipes/building_blocks/mossy_cobblestone_stairs_from_mossy_cobblestone_stonecutting.json
+ recipes/building_blocks/mossy_stone_brick_slab_from_mossy_stone_brick_stonecutting.json
+ recipes/building_blocks/mossy_stone_brick_stairs_from_mossy_stone_brick_stonecutting.json
+ recipes/building_blocks/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+ recipes/building_blocks/nether_brick_slab_from_nether_bricks_stonecutting.json
+ recipes/building_blocks/nether_brick_stairs_from_nether_bricks_stonecutting.json
+ recipes/building_blocks/nether_brick_wall_from_nether_bricks_stonecutting.json
+ recipes/building_blocks/polished_andesite_from_andesite_stonecutting.json
+ recipes/building_blocks/polished_andesite_slab_from_polished_andesite_stonecutting.json
+ recipes/building_blocks/polished_andesite_stairs_from_polished_andesite_stonecutting.json
+ recipes/building_blocks/polished_diorite_from_diorite_stonecutting.json
+ recipes/building_blocks/polished_diorite_slab_from_polished_diorite_stonecutting.json
+ recipes/building_blocks/polished_diorite_stairs_from_polished_diorite_stonecutting.json
+ recipes/building_blocks/polished_granite_from_granite_stonecutting.json
+ recipes/building_blocks/polished_granite_slab_from_polished_granite_stonecutting.json
+ recipes/building_blocks/polished_granite_stairs_from_polished_granite_stonecutting.json
+ recipes/building_blocks/prismarine_brick_slab_from_prismarine_stonecutting.json
+ recipes/building_blocks/prismarine_brick_stairs_from_prismarine_stonecutting.json
+ recipes/building_blocks/prismarine_slab_from_prismarine_stonecutting.json
+ recipes/building_blocks/prismarine_stairs_from_prismarine_stonecutting.json
+ recipes/building_blocks/prismarine_wall_from_prismarine_stonecutting.json
+ recipes/building_blocks/purpur_pillar_from_purpur_block_stonecutting.json
+ recipes/building_blocks/purpur_slab_from_purpur_block_stonecutting.json
+ recipes/building_blocks/purpur_stairs_from_purpur_block_stonecutting.json
+ recipes/building_blocks/quartz_pillar_from_quartz_block_stonecutting.json
+ recipes/building_blocks/quartz_slab_from_stonecutting.json
+ recipes/building_blocks/quartz_stairs_from_quartz_block_stonecutting.json
+ recipes/building_blocks/red_nether_brick_slab_from_red_nether_bricks_stonecutting.json
+ recipes/building_blocks/red_nether_brick_stairs_from_red_nether_bricks_stonecutting.json
+ recipes/building_blocks/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
+ recipes/building_blocks/red_sandstone_slab_from_red_sandstone_stonecutting.json
+ recipes/building_blocks/red_sandstone_stairs_from_red_sandstone_stonecutting.json
+ recipes/building_blocks/red_sandstone_wall_from_red_sandstone_stonecutting.json
+ recipes/building_blocks/sandstone_slab_from_sandstone_stonecutting.json
+ recipes/building_blocks/sandstone_stairs_from_sandstone_stonecutting.json
+ recipes/building_blocks/sandstone_wall_from_sandstone_stonecutting.json
+ recipes/building_blocks/smooth_quartz_slab_from_smooth_quartz_stonecutting.json
+ recipes/building_blocks/smooth_quartz_stairs_from_smooth_quartz_stonecutting.json
+ recipes/building_blocks/smooth_red_sandstone_slab_from_smooth_red_sandstone_stonecutting.json
+ recipes/building_blocks/smooth_red_sandstone_stairs_from_smooth_red_sandstone_stonecutting.json
+ recipes/building_blocks/smooth_sandstone_slab_from_smooth_sandstone_stonecutting.json
+ recipes/building_blocks/smooth_sandstone_stairs_from_smooth_sandstone_stonecutting.json
+ recipes/building_blocks/stone_bricks_from_stone_stonecutting.json
+ recipes/building_blocks/stone_brick_slab_from_stone_bricks_stonecutting.json
+ recipes/building_blocks/stone_brick_slab_from_stone_stonecutting.json
+ recipes/building_blocks/stone_brick_stairs_from_stone_bricks_stonecutting.json
+ recipes/building_blocks/stone_brick_stairs_from_stone_stonecutting.json
+ recipes/building_blocks/stone_brick_walls_from_stone_stonecutting.json
+ recipes/building_blocks/stone_brick_wall_from_stone_bricks_stonecutting.json
+ recipes/building_blocks/stone_slab_from_stone_stonecutting.json
+ recipes/building_blocks/stone_stairs_from_stone_stonecutting.json
+ recipes/decorations/cobblestone_wall_from_cobblestone_stonecutting.json
+ recipes/decorations/mossy_cobblestone_wall_from_mossy_cobblestone_stonecutting.json
+ recipes/decorations/stonecutter.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
+ andesite_slab_from_andesite_stonecutting.json
+ andesite_stairs_from_andesite_stonecutting.json
+ andesite_wall_from_andesite_stonecutting.json
+ brick_slab_from_bricks_stonecutting.json
+ brick_stairs_from_bricks_stonecutting.json
+ brick_wall_from_bricks_stonecutting.json
+ chiseled_quartz_block_from_quartz_block_stonecutting.json
+ chiseled_red_sandstone_from_red_sandstone_stonecutting.json
+ chiseled_sandstone_from_sandstone_stonecutting.json
+ chiseled_stone_bricks_stone_from_stonecutting.json
+ cobblestone_slab_from_cobblestone_stonecutting.json
+ cobblestone_stairs_from_cobblestone_stonecutting.json
+ cobblestone_wall_from_cobblestone_stonecutting.json
+ cut_red_sandstone_from_red_sandstone_stonecutting.json
+ cut_sandstone_from_sandstone_stonecutting.json
+ dark_prismarine_slab_from_dark_prismarine_stonecutting.json
+ dark_prismarine_stairs_from_dark_prismarine_stonecutting.json
+ diorite_slab_from_diorite_stonecutting.json
+ diorite_stairs_from_diorite_stonecutting.json
+ diorite_wall_from_diorite_stonecutting.json
+ end_stone_bricks_from_end_stone_stonecutting.json
+ end_stone_brick_slab_from_end_stone_brick_stonecutting.json
+ end_stone_brick_slab_from_end_stone_stonecutting.json
+ end_stone_brick_stairs_from_end_stone_brick_stonecutting.json
+ end_stone_brick_stairs_from_end_stone_stonecutting.json
+ end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+ end_stone_brick_wall_from_end_stone_stonecutting.json
+ granite_slab_from_granite_stonecutting.json
+ granite_stairs_from_granite_stonecutting.json
+ granite_wall_from_granite_stonecutting.json
+ mossy_cobblestone_slab_from_mossy_cobblestone_stonecutting.json
+ mossy_cobblestone_stairs_from_mossy_cobblestone_stonecutting.json
+ mossy_cobblestone_wall_from_mossy_cobblestone_stonecutting.json
+ mossy_stone_brick_slab_from_mossy_stone_brick_stonecutting.json
+ mossy_stone_brick_stairs_from_mossy_stone_brick_stonecutting.json
+ mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+ nether_brick_slab_from_nether_bricks_stonecutting.json
+ nether_brick_stairs_from_nether_bricks_stonecutting.json
+ nether_brick_wall_from_nether_bricks_stonecutting.json
+ polished_andesite_from_andesite_stonecutting.json
+ polished_andesite_slab_from_polished_andesite_stonecutting.json
+ polished_andesite_stairs_from_polished_andesite_stonecutting.json
+ polished_diorite_from_diorite_stonecutting.json
+ polished_diorite_slab_from_polished_diorite_stonecutting.json
+ polished_diorite_stairs_from_polished_diorite_stonecutting.json
+ polished_granite_from_granite_stonecutting.json
+ polished_granite_slab_from_polished_granite_stonecutting.json
+ polished_granite_stairs_from_polished_granite_stonecutting.json
+ prismarine_brick_slab_from_prismarine_stonecutting.json
+ prismarine_brick_stairs_from_prismarine_stonecutting.json
+ prismarine_slab_from_prismarine_stonecutting.json
+ prismarine_stairs_from_prismarine_stonecutting.json
+ prismarine_wall_from_prismarine_stonecutting.json
+ purpur_pillar_from_purpur_block_stonecutting.json
+ purpur_slab_from_purpur_block_stonecutting.json
+ purpur_stairs_from_purpur_block_stonecutting.json
+ quartz_pillar_from_quartz_block_stonecutting.json
+ quartz_slab_from_stonecutting.json
+ quartz_stairs_from_quartz_block_stonecutting.json
+ red_nether_brick_slab_from_red_nether_bricks_stonecutting.json
+ red_nether_brick_stairs_from_red_nether_bricks_stonecutting.json
+ red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
+ red_sandstone_slab_from_red_sandstone_stonecutting.json
+ red_sandstone_stairs_from_red_sandstone_stonecutting.json
+ red_sandstone_wall_from_red_sandstone_stonecutting.json
+ sandstone_slab_from_sandstone_stonecutting.json
+ sandstone_stairs_from_sandstone_stonecutting.json
+ sandstone_wall_from_sandstone_stonecutting.json
+ smooth_quartz_slab_from_smooth_quartz_stonecutting.json
+ smooth_quartz_stairs_from_smooth_quartz_stonecutting.json
+ smooth_red_sandstone_slab_from_smooth_red_sandstone_stonecutting.json
+ smooth_red_sandstone_stairs_from_smooth_red_sandstone_stonecutting.json
+ smooth_sandstone_slab_from_smooth_sandstone_stonecutting.json
+ smooth_sandstone_stairs_from_smooth_sandstone_stonecutting.json
+ stonecutter.json
+ stone_bricks_from_stone_stonecutting.json
+ stone_brick_slab_from_stone_bricks_stonecutting.json
+ stone_brick_slab_from_stone_stonecutting.json
+ stone_brick_stairs_from_stone_bricks_stonecutting.json
+ stone_brick_stairs_from_stone_stonecutting.json
+ stone_brick_walls_from_stone_stonecutting.json
+ stone_brick_wall_from_stone_bricks_stonecutting.json
+ stone_slab_from_stone_stonecutting.json
+ stone_stairs_from_stone_stonecutting.json
```

</details>

<details><summary>structures.txt</summary>

```diff
+ village/desert/zombie/houses/desert_medium_house_1.nbt
+ village/desert/zombie/houses/desert_medium_house_2.nbt
+ village/desert/zombie/houses/desert_small_house_1.nbt
+ village/desert/zombie/houses/desert_small_house_2.nbt
+ village/desert/zombie/houses/desert_small_house_3.nbt
+ village/desert/zombie/houses/desert_small_house_4.nbt
+ village/desert/zombie/houses/desert_small_house_5.nbt
+ village/desert/zombie/houses/desert_small_house_6.nbt
+ village/desert/zombie/houses/desert_small_house_7.nbt
+ village/desert/zombie/houses/desert_small_house_8.nbt
+ village/desert/zombie/streets/corner_01.nbt
+ village/desert/zombie/streets/corner_02.nbt
+ village/desert/zombie/streets/crossroad_01.nbt
+ village/desert/zombie/streets/crossroad_02.nbt
+ village/desert/zombie/streets/crossroad_03.nbt
+ village/desert/zombie/streets/square_01.nbt
+ village/desert/zombie/streets/square_02.nbt
+ village/desert/zombie/streets/straight_01.nbt
+ village/desert/zombie/streets/straight_02.nbt
+ village/desert/zombie/streets/straight_03.nbt
+ village/desert/zombie/streets/turn_01.nbt
+ village/desert/zombie/terminators/terminator_02.nbt
+ village/desert/zombie/town_centers/desert_meeting_point_1.nbt
+ village/desert/zombie/town_centers/desert_meeting_point_2.nbt
+ village/desert/zombie/town_centers/desert_meeting_point_3.nbt
+ village/desert/zombie/villagers/armorer.nbt
+ village/desert/zombie/villagers/butcher.nbt
+ village/desert/zombie/villagers/cartographer.nbt
+ village/desert/zombie/villagers/cleric.nbt
+ village/desert/zombie/villagers/farmer.nbt
+ village/desert/zombie/villagers/fishermen.nbt
+ village/desert/zombie/villagers/fletcher.nbt
+ village/desert/zombie/villagers/leatherworker.nbt
+ village/desert/zombie/villagers/librarian.nbt
+ village/desert/zombie/villagers/nitwit.nbt
+ village/desert/zombie/villagers/shepherd.nbt
+ village/desert/zombie/villagers/toolsmith.nbt
+ village/desert/zombie/villagers/unemployed.nbt
+ village/desert/zombie/villagers/weaponsmith.nbt
+ village/taiga/houses/taiga_medium_house_4.nbt
+ village/taiga/taiga_decoration_5.nbt
+ village/taiga/taiga_decoration_6.nbt
+ village/taiga/zombie/houses/taiga_armorer_house_2.nbt
+ village/taiga/zombie/houses/taiga_cartographer_house_1.nbt
+ village/taiga/zombie/houses/taiga_fisher_cottage_1.nbt
+ village/taiga/zombie/houses/taiga_large_farm_2.nbt
+ village/taiga/zombie/houses/taiga_library_1.nbt
+ village/taiga/zombie/houses/taiga_medium_house_1.nbt
+ village/taiga/zombie/houses/taiga_medium_house_2.nbt
+ village/taiga/zombie/houses/taiga_medium_house_3.nbt
+ village/taiga/zombie/houses/taiga_medium_house_4.nbt
+ village/taiga/zombie/houses/taiga_shepherds_house_1.nbt
+ village/taiga/zombie/houses/taiga_small_house_1.nbt
+ village/taiga/zombie/houses/taiga_small_house_2.nbt
+ village/taiga/zombie/houses/taiga_small_house_3.nbt
+ village/taiga/zombie/houses/taiga_small_house_4.nbt
+ village/taiga/zombie/houses/taiga_small_house_5.nbt
+ village/taiga/zombie/houses/taiga_temple_1.nbt
+ village/taiga/zombie/houses/taiga_tool_smith_1.nbt
+ village/taiga/zombie/houses/taiga_weaponsmith_2.nbt
+ village/taiga/zombie/streets/corner_01.nbt
+ village/taiga/zombie/streets/corner_02.nbt
+ village/taiga/zombie/streets/corner_03.nbt
+ village/taiga/zombie/streets/crossroad_01.nbt
+ village/taiga/zombie/streets/crossroad_02.nbt
+ village/taiga/zombie/streets/crossroad_03.nbt
+ village/taiga/zombie/streets/crossroad_04.nbt
+ village/taiga/zombie/streets/crossroad_05.nbt
+ village/taiga/zombie/streets/crossroad_06.nbt
+ village/taiga/zombie/streets/straight_01.nbt
+ village/taiga/zombie/streets/straight_02.nbt
+ village/taiga/zombie/streets/straight_03.nbt
+ village/taiga/zombie/streets/straight_04.nbt
+ village/taiga/zombie/streets/straight_05.nbt
+ village/taiga/zombie/streets/straight_06.nbt
+ village/taiga/zombie/streets/turn_01.nbt
+ village/taiga/zombie/town_centers/taiga_meeting_point_1.nbt
+ village/taiga/zombie/town_centers/taiga_meeting_point_2.nbt
+ village/taiga/zombie/villagers/armorer.nbt
+ village/taiga/zombie/villagers/butcher.nbt
+ village/taiga/zombie/villagers/cartographer.nbt
+ village/taiga/zombie/villagers/cleric.nbt
+ village/taiga/zombie/villagers/farmer.nbt
+ village/taiga/zombie/villagers/fishermen.nbt
+ village/taiga/zombie/villagers/fletcher.nbt
+ village/taiga/zombie/villagers/leatherworker.nbt
+ village/taiga/zombie/villagers/librarian.nbt
+ village/taiga/zombie/villagers/nitwit.nbt
+ village/taiga/zombie/villagers/shepherd.nbt
+ village/taiga/zombie/villagers/toolsmith.nbt
+ village/taiga/zombie/villagers/unemployed.nbt
+ village/taiga/zombie/villagers/weaponsmith.nbt
```

</details>

<details><summary>textures.txt</summary>

```diff
+ gui/container/stonecutter.png
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