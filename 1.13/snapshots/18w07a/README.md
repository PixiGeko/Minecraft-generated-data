<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w07a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w07a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-02-14T17:34:13+00:00</td></tr>
<tr><th>SHA1</th><td>211e0152bce6081564fc9c40603463c04f89d835</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/211e0152bce6081564fc9c40603463c04f89d835/18w07a.json">https://piston-meta.mojang.com/v1/packages/211e0152bce6081564fc9c40603463c04f89d835/18w07a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/e90255faadbb7f009fa38a507f62f751dcc56c9b/server.jar">https://piston-data.mojang.com/v1/objects/e90255faadbb7f009fa38a507f62f751dcc56c9b/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/fa2960642589fc7bd3e14049ffe7d84a4d2bac1d/client.jar">https://piston-data.mojang.com/v1/objects/fa2960642589fc7bd3e14049ffe7d84a4d2bac1d/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w06a">18w06a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/building_blocks/dark_prismarine_slab.json
+  minecraft/advancements/recipes/building_blocks/dark_prismarine_stairs.json
+  minecraft/advancements/recipes/building_blocks/prismarine_bricks_slab.json
+  minecraft/advancements/recipes/building_blocks/prismarine_bricks_stairs.json
+  minecraft/advancements/recipes/building_blocks/prismarine_slab.json
+  minecraft/advancements/recipes/building_blocks/prismarine_stairs.json
+  minecraft/advancements/recipes/combat/turtle_helmet.json
+  minecraft/advancements/recipes/food/dried_kelp.json
+  minecraft/loot_tables/entities/phantom.json
+  minecraft/loot_tables/entities/turtle.json
+  minecraft/recipes/dark_prismarine_slab.json
+  minecraft/recipes/dark_prismarine_stairs.json
+  minecraft/recipes/dried_kelp.json
+  minecraft/recipes/prismarine_bricks_slab.json
+  minecraft/recipes/prismarine_bricks_stairs.json
+  minecraft/recipes/prismarine_slab.json
+  minecraft/recipes/prismarine_stairs.json
+  minecraft/recipes/turtle_helmet.json
+  minecraft/tags/blocks/acacia_logs.json
+  minecraft/tags/blocks/birch_logs.json
+  minecraft/tags/blocks/dark_oak_logs.json
+  minecraft/tags/blocks/jungle_logs.json
+  minecraft/tags/blocks/oak_logs.json
+  minecraft/tags/blocks/slabs.json
+  minecraft/tags/blocks/spruce_logs.json
+  minecraft/tags/blocks/stairs.json
+  minecraft/tags/blocks/water_hacked.json
+  minecraft/tags/items/acacia_logs.json
+  minecraft/tags/items/birch_logs.json
+  minecraft/tags/items/dark_oak_logs.json
+  minecraft/tags/items/jungle_logs.json
+  minecraft/tags/items/oak_logs.json
+  minecraft/tags/items/spruce_logs.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/bubble_column.json
+  minecraft/blockstates/dark_prismarine_slab.json
+  minecraft/blockstates/dark_prismarine_stairs.json
+  minecraft/blockstates/dried_kelp_block.json
+  minecraft/blockstates/kelp.json
+  minecraft/blockstates/kelp_top.json
+  minecraft/blockstates/prismarine_bricks_slab.json
+  minecraft/blockstates/prismarine_bricks_stairs.json
+  minecraft/blockstates/prismarine_slab.json
+  minecraft/blockstates/prismarine_stairs.json
+  minecraft/blockstates/sea_grass.json
+  minecraft/blockstates/stripped_acacia_log.json
+  minecraft/blockstates/stripped_birch_log.json
+  minecraft/blockstates/stripped_dark_oak_log.json
+  minecraft/blockstates/stripped_jungle_log.json
+  minecraft/blockstates/stripped_oak_log.json
+  minecraft/blockstates/stripped_spruce_log.json
+  minecraft/blockstates/tall_sea_grass.json
+  minecraft/blockstates/turtle_egg.json
+  minecraft/models/block/bubble_column.json
+  minecraft/models/block/dark_prismarine_slab.json
+  minecraft/models/block/dark_prismarine_slab_top.json
+  minecraft/models/block/dark_prismarine_stairs.json
+  minecraft/models/block/dark_prismarine_stairs_inner.json
+  minecraft/models/block/dark_prismarine_stairs_outer.json
+  minecraft/models/block/dried_kelp_block.json
+  minecraft/models/block/four_slightly_cracked_turtle_eggs.json
+  minecraft/models/block/four_turtle_eggs.json
+  minecraft/models/block/four_very_cracked_turtle_eggs.json
+  minecraft/models/block/half_slab_dark_prismarine.json
+  minecraft/models/block/half_slab_prismarine.json
+  minecraft/models/block/half_slab_prismarine_bricks.json
+  minecraft/models/block/kelp.json
+  minecraft/models/block/kelp_top.json
+  minecraft/models/block/prismarine_bricks_slab.json
+  minecraft/models/block/prismarine_bricks_slab_top.json
+  minecraft/models/block/prismarine_bricks_stairs.json
+  minecraft/models/block/prismarine_bricks_stairs_inner.json
+  minecraft/models/block/prismarine_bricks_stairs_outer.json
+  minecraft/models/block/prismarine_slab.json
+  minecraft/models/block/prismarine_slab_top.json
+  minecraft/models/block/prismarine_stairs.json
+  minecraft/models/block/prismarine_stairs_inner.json
+  minecraft/models/block/prismarine_stairs_outer.json
+  minecraft/models/block/sea_grass.json
+  minecraft/models/block/slightly_cracked_turtle_egg.json
+  minecraft/models/block/stripped_acacia_log.json
+  minecraft/models/block/stripped_birch_log.json
+  minecraft/models/block/stripped_dark_oak_log.json
+  minecraft/models/block/stripped_jungle_log.json
+  minecraft/models/block/stripped_oak_log.json
+  minecraft/models/block/stripped_spruce_log.json
+  minecraft/models/block/tall_sea_grass_bottom.json
+  minecraft/models/block/tall_sea_grass_top.json
+  minecraft/models/block/three_slightly_cracked_turtle_eggs.json
+  minecraft/models/block/three_turtle_eggs.json
+  minecraft/models/block/three_very_cracked_turtle_eggs.json
+  minecraft/models/block/turtle_egg.json
+  minecraft/models/block/two_slightly_cracked_turtle_eggs.json
+  minecraft/models/block/two_turtle_eggs.json
+  minecraft/models/block/two_very_cracked_turtle_eggs.json
+  minecraft/models/block/very_cracked_turtle_egg.json
+  minecraft/models/item/dark_prismarine_slab.json
+  minecraft/models/item/dark_prismarine_stairs.json
+  minecraft/models/item/dried_kelp.json
+  minecraft/models/item/dried_kelp_block.json
+  minecraft/models/item/kelp_top.json
+  minecraft/models/item/phantom_spawn_egg.json
+  minecraft/models/item/prismarine_bricks_slab.json
+  minecraft/models/item/prismarine_bricks_stairs.json
+  minecraft/models/item/prismarine_slab.json
+  minecraft/models/item/prismarine_stairs.json
+  minecraft/models/item/sea_grass.json
+  minecraft/models/item/stripped_acacia_log.json
+  minecraft/models/item/stripped_birch_log.json
+  minecraft/models/item/stripped_dark_oak_log.json
+  minecraft/models/item/stripped_jungle_log.json
+  minecraft/models/item/stripped_oak_log.json
+  minecraft/models/item/stripped_spruce_log.json
+  minecraft/models/item/trident.json
+  minecraft/models/item/trident_throwing.json
+  minecraft/models/item/turtle_egg.json
+  minecraft/models/item/turtle_helmet.json
+  minecraft/models/item/turtle_shell_piece.json
+  minecraft/models/item/turtle_spawn_egg.json
+  minecraft/textures/blocks/dried_kelp_bottom.png
+  minecraft/textures/blocks/dried_kelp_side.png
+  minecraft/textures/blocks/dried_kelp_side_mirror.png
+  minecraft/textures/blocks/dried_kelp_top.png
+  minecraft/textures/blocks/kelp_plant.png
+  minecraft/textures/blocks/kelp_plant.png.mcmeta
+  minecraft/textures/blocks/kelp_top.png
+  minecraft/textures/blocks/kelp_top.png.mcmeta
+  minecraft/textures/blocks/sea_grass.png
+  minecraft/textures/blocks/sea_grass.png.mcmeta
+  minecraft/textures/blocks/stripped_acacia_log.png
+  minecraft/textures/blocks/stripped_acacia_log_top.png
+  minecraft/textures/blocks/stripped_birch_log.png
+  minecraft/textures/blocks/stripped_birch_log_top.png
+  minecraft/textures/blocks/stripped_dark_oak_log.png
+  minecraft/textures/blocks/stripped_dark_oak_log_top.png
+  minecraft/textures/blocks/stripped_jungle_log.png
+  minecraft/textures/blocks/stripped_jungle_log_top.png
+  minecraft/textures/blocks/stripped_oak_log.png
+  minecraft/textures/blocks/stripped_oak_log_top.png
+  minecraft/textures/blocks/stripped_spruce_log.png
+  minecraft/textures/blocks/stripped_spruce_log_top.png
+  minecraft/textures/blocks/tall_sea_grass_bottom.png
+  minecraft/textures/blocks/tall_sea_grass_bottom.png.mcmeta
+  minecraft/textures/blocks/tall_sea_grass_top.png
+  minecraft/textures/blocks/tall_sea_grass_top.png.mcmeta
+  minecraft/textures/blocks/turtle_egg_not_cracked.png
+  minecraft/textures/blocks/turtle_egg_slightly_cracked.png
+  minecraft/textures/blocks/turtle_egg_very_cracked.png
+  minecraft/textures/entity/turtle
+  minecraft/textures/entity/turtle/big_sea_turtle.png
+  minecraft/textures/entity/phantom.png
+  minecraft/textures/entity/trident.png
+  minecraft/textures/items/dried_kelp.png
+  minecraft/textures/items/kelp.png
+  minecraft/textures/items/turtle_helmet.png
+  minecraft/textures/items/turtle_shell_piece.png
+  minecraft/textures/models/armor/turtle_layer_1.png
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/acacia_logs.json
+ blocks/birch_logs.json
+ blocks/dark_oak_logs.json
+ blocks/jungle_logs.json
+ blocks/oak_logs.json
+ blocks/slabs.json
+ blocks/spruce_logs.json
+ blocks/stairs.json
+ blocks/water_hacked.json
+ items/acacia_logs.json
+ items/birch_logs.json
+ items/dark_oak_logs.json
+ items/jungle_logs.json
+ items/oak_logs.json
+ items/spruce_logs.json
```

</details>

<details><summary>blocks/logs.json</summary>

```diff
- minecraft:oak_log
- minecraft:spruce_log
- minecraft:birch_log
- minecraft:jungle_log
- minecraft:acacia_log
- minecraft:dark_oak_log
- minecraft:oak_bark
- minecraft:spruce_bark
- minecraft:birch_bark
- minecraft:jungle_bark
- minecraft:acacia_bark
- minecraft:dark_oak_bark
+ #minecraft:dark_oak_logs
+ #minecraft:oak_logs
+ #minecraft:acacia_logs
+ #minecraft:birch_logs
+ #minecraft:jungle_logs
+ #minecraft:spruce_logs
```

</details>

<details><summary>items/logs.json</summary>

```diff
- minecraft:oak_log
- minecraft:spruce_log
- minecraft:birch_log
- minecraft:jungle_log
- minecraft:acacia_log
- minecraft:dark_oak_log
- minecraft:oak_bark
- minecraft:spruce_bark
- minecraft:birch_bark
- minecraft:jungle_bark
- minecraft:acacia_bark
- minecraft:dark_oak_bark
+ #minecraft:dark_oak_logs
+ #minecraft:oak_logs
+ #minecraft:acacia_logs
+ #minecraft:birch_logs
+ #minecraft:jungle_logs
+ #minecraft:spruce_logs
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/building_blocks/dark_prismarine_slab.json
+ recipes/building_blocks/dark_prismarine_stairs.json
+ recipes/building_blocks/prismarine_bricks_slab.json
+ recipes/building_blocks/prismarine_bricks_stairs.json
+ recipes/building_blocks/prismarine_slab.json
+ recipes/building_blocks/prismarine_stairs.json
+ recipes/combat/turtle_helmet.json
+ recipes/food/dried_kelp.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
+ entities/phantom.json
+ entities/turtle.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
+ dark_prismarine_slab.json
+ dark_prismarine_stairs.json
+ dried_kelp.json
+ prismarine_bricks_slab.json
+ prismarine_bricks_stairs.json
+ prismarine_slab.json
+ prismarine_stairs.json
+ turtle_helmet.json
```

</details>

<details><summary>tags.txt</summary>

```diff
+ blocks/acacia_logs.json
+ blocks/birch_logs.json
+ blocks/dark_oak_logs.json
+ blocks/jungle_logs.json
+ blocks/oak_logs.json
+ blocks/slabs.json
+ blocks/spruce_logs.json
+ blocks/stairs.json
+ blocks/water_hacked.json
+ items/acacia_logs.json
+ items/birch_logs.json
+ items/dark_oak_logs.json
+ items/jungle_logs.json
+ items/oak_logs.json
+ items/spruce_logs.json
```

</details>

<details><summary>textures.txt</summary>

```diff
+ blocks/dried_kelp_bottom.png
+ blocks/dried_kelp_side.png
+ blocks/dried_kelp_side_mirror.png
+ blocks/dried_kelp_top.png
+ blocks/kelp_plant.png
+ blocks/kelp_top.png
+ blocks/sea_grass.png
+ blocks/stripped_acacia_log.png
+ blocks/stripped_acacia_log_top.png
+ blocks/stripped_birch_log.png
+ blocks/stripped_birch_log_top.png
+ blocks/stripped_dark_oak_log.png
+ blocks/stripped_dark_oak_log_top.png
+ blocks/stripped_jungle_log.png
+ blocks/stripped_jungle_log_top.png
+ blocks/stripped_oak_log.png
+ blocks/stripped_oak_log_top.png
+ blocks/stripped_spruce_log.png
+ blocks/stripped_spruce_log_top.png
+ blocks/tall_sea_grass_bottom.png
+ blocks/tall_sea_grass_top.png
+ blocks/turtle_egg_not_cracked.png
+ blocks/turtle_egg_slightly_cracked.png
+ blocks/turtle_egg_very_cracked.png
+ entity/phantom.png
+ entity/trident.png
+ entity/turtle/big_sea_turtle.png
+ items/dried_kelp.png
+ items/kelp.png
+ items/turtle_helmet.png
+ items/turtle_shell_piece.png
+ models/armor/turtle_layer_1.png
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