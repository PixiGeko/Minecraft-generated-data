<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w02a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w02a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-01-09T15:52:07+00:00</td></tr>
<tr><th>SHA1</th><td>5b51ed792b91ce4d281666c64c49084a134ac11d</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/5b51ed792b91ce4d281666c64c49084a134ac11d/19w02a.json">https://piston-meta.mojang.com/v1/packages/5b51ed792b91ce4d281666c64c49084a134ac11d/19w02a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/f8078dd487483a917645f7a5561290e28bd875c4/server.jar">https://piston-data.mojang.com/v1/objects/f8078dd487483a917645f7a5561290e28bd875c4/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/8664f5d1b428d5ba8a936ab9c097cc78821d06e6/client.jar">https://piston-data.mojang.com/v1/objects/8664f5d1b428d5ba8a936ab9c097cc78821d06e6/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w50a">18w50a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/decorations/campfire.json
+  minecraft/advancements/recipes/decorations/cartography_table.json
+  minecraft/advancements/recipes/food/baked_potato_from_campfire.json
+  minecraft/advancements/recipes/food/cooked_beef_from_campfire.json
+  minecraft/advancements/recipes/food/cooked_chicken_from_campfire.json
+  minecraft/advancements/recipes/food/cooked_cod_from_campfire.json
+  minecraft/advancements/recipes/food/cooked_mutton_from_campfire.json
+  minecraft/advancements/recipes/food/cooked_porkchop_from_campfire.json
+  minecraft/advancements/recipes/food/cooked_rabbit_from_campfire.json
+  minecraft/advancements/recipes/food/cooked_salmon_from_campfire.json
+  minecraft/advancements/recipes/food/dried_kelp_from_campfire.json
+  minecraft/advancements/recipes/redstone/lectern.json
+  minecraft/loot_tables/blocks/campfire.json
+  minecraft/recipes/baked_potato_from_campfire.json
+  minecraft/recipes/campfire.json
+  minecraft/recipes/cartography_table.json
+  minecraft/recipes/cooked_beef_from_campfire.json
+  minecraft/recipes/cooked_chicken_from_campfire.json
+  minecraft/recipes/cooked_cod_from_campfire.json
+  minecraft/recipes/cooked_mutton_from_campfire.json
+  minecraft/recipes/cooked_porkchop_from_campfire.json
+  minecraft/recipes/cooked_rabbit_from_campfire.json
+  minecraft/recipes/cooked_salmon_from_campfire.json
+  minecraft/recipes/dried_kelp_from_campfire.json
+  minecraft/recipes/lectern.json
+  minecraft/tags/items/coals.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/campfire.json
+  minecraft/models/block/campfire.json
+  minecraft/models/block/campfire_on.json
+  minecraft/models/item/campfire.json
+  minecraft/textures/block/campfire_fire.png
+  minecraft/textures/block/campfire_fire.png.mcmeta
+  minecraft/textures/block/campfire_side.png
+  minecraft/textures/block/campfire_top.png
+  minecraft/textures/block/campfire_top_on.png
+  minecraft/textures/block/campfire_top_on.png.mcmeta
+  minecraft/textures/gui/container/cartography_table.png
```

</details>

## Registries

<details><summary>list</summary>

```diff
+ menu.txt
```

</details>

<details><summary>block.txt</summary>

```diff
+ minecraft:campfire
```

</details>

<details><summary>block_entity_type.txt</summary>

```diff
+ minecraft:campfire
```

</details>

<details><summary>custom_stat.txt</summary>

```diff
+ minecraft:interact_with_lectern
+ minecraft:interact_with_campfire
```

</details>

<details><summary>feature.txt</summary>

```diff
- minecraft:new_village
```

</details>

<details><summary>item.txt</summary>

```diff
+ minecraft:campfire
```

</details>

<details><summary>particle_type.txt</summary>

```diff
+ minecraft:campfire_cosy_smoke
+ minecraft:campfire_signal_smoke
```

</details>

<details><summary>sound_event.txt</summary>

```diff
+ minecraft:item.book.page_turn
+ minecraft:item.book.put
+ minecraft:block.campfire.crackle
+ minecraft:ui.cartography_table.take_result
```

</details>

<details><summary>structure_feature.txt</summary>

```diff
- minecraft:new_village
```

</details>

<details><summary>structure_piece.txt</summary>

```diff
- minecraft:vibh
- minecraft:vidf
- minecraft:vif
- minecraft:vil
- minecraft:viph
- minecraft:vish
- minecraft:vismh
- minecraft:vist
- minecraft:vis
- minecraft:vistart
- minecraft:visr
- minecraft:vitrh
- minecraft:viw
```

</details>

## Commands

<details><summary>list</summary>

```diff
+ teammsg.txt
+ tm.txt
```

</details>

<details><summary>data.txt</summary>

```diff
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> value <value: nbt_tag>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> value <value: nbt_tag>
- data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> value <value: nbt_tag>
- data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> value <value: nbt_tag>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> value <value: nbt_tag>
```

</details>

<details><summary>locate.txt</summary>

```diff
- locate New_Village
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ items/coals.json
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/decorations/campfire.json
+ recipes/decorations/cartography_table.json
+ recipes/food/baked_potato_from_campfire.json
+ recipes/food/cooked_beef_from_campfire.json
+ recipes/food/cooked_chicken_from_campfire.json
+ recipes/food/cooked_cod_from_campfire.json
+ recipes/food/cooked_mutton_from_campfire.json
+ recipes/food/cooked_porkchop_from_campfire.json
+ recipes/food/cooked_rabbit_from_campfire.json
+ recipes/food/cooked_salmon_from_campfire.json
+ recipes/food/dried_kelp_from_campfire.json
+ recipes/redstone/lectern.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
+ blocks/campfire.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
+ baked_potato_from_campfire.json
+ campfire.json
+ cartography_table.json
+ cooked_beef_from_campfire.json
+ cooked_chicken_from_campfire.json
+ cooked_cod_from_campfire.json
+ cooked_mutton_from_campfire.json
+ cooked_porkchop_from_campfire.json
+ cooked_rabbit_from_campfire.json
+ cooked_salmon_from_campfire.json
+ dried_kelp_from_campfire.json
+ lectern.json
```

</details>

<details><summary>tags.txt</summary>

```diff
+ items/coals.json
```

</details>

<details><summary>textures.txt</summary>

```diff
+ block/campfire_fire.png
+ block/campfire_side.png
+ block/campfire_top.png
+ block/campfire_top_on.png
+ gui/container/cartography_table.png
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:datafixerupper:1.0.21
+ com.mojang:datafixerupper:2.0.23
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