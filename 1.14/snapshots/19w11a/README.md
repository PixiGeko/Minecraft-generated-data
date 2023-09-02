<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w11a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w11a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-03-13T13:59:29+00:00</td></tr>
<tr><th>SHA1</th><td>ec8d1b45727e11cec93a813cc8b66bd48a6a3bad</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/ec8d1b45727e11cec93a813cc8b66bd48a6a3bad/19w11a.json">https://piston-meta.mojang.com/v1/packages/ec8d1b45727e11cec93a813cc8b66bd48a6a3bad/19w11a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/388221ffa9e8e1576e07f9839eadd2ac7bd51cbb/server.jar">https://piston-data.mojang.com/v1/objects/388221ffa9e8e1576e07f9839eadd2ac7bd51cbb/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/03e795efb9c91f2c4994826c45f3a99d2c695517/client.jar">https://piston-data.mojang.com/v1/objects/03e795efb9c91f2c4994826c45f3a99d2c695517/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w09a">19w09a</a>
## File structure

<details><summary>data/</summary>

```diff
-  minecraft/advancements/recipes/building_blocks/andesite_wall.json
-  minecraft/advancements/recipes/building_blocks/andesite_wall_from_andesite_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/brick_wall.json
-  minecraft/advancements/recipes/building_blocks/brick_wall_from_bricks_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/diorite_wall.json
-  minecraft/advancements/recipes/building_blocks/diorite_wall_from_diorite_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/end_stone_brick_wall.json
-  minecraft/advancements/recipes/building_blocks/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/end_stone_brick_wall_from_end_stone_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/granite_wall.json
-  minecraft/advancements/recipes/building_blocks/granite_wall_from_granite_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/mossy_stone_brick_wall.json
-  minecraft/advancements/recipes/building_blocks/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/nether_brick_wall.json
-  minecraft/advancements/recipes/building_blocks/nether_brick_wall_from_nether_bricks_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/prismarine_wall.json
-  minecraft/advancements/recipes/building_blocks/prismarine_wall_from_prismarine_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/red_nether_brick_wall.json
-  minecraft/advancements/recipes/building_blocks/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/red_sandstone_wall.json
-  minecraft/advancements/recipes/building_blocks/red_sandstone_wall_from_red_sandstone_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/sandstone_wall.json
-  minecraft/advancements/recipes/building_blocks/sandstone_wall_from_sandstone_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/stone_brick_wall.json
-  minecraft/advancements/recipes/building_blocks/stone_brick_wall_from_stone_bricks_stonecutting.json
-  minecraft/advancements/recipes/building_blocks/stone_brick_walls_from_stone_stonecutting.json
+  minecraft/advancements/recipes/decorations/andesite_wall.json
+  minecraft/advancements/recipes/decorations/andesite_wall_from_andesite_stonecutting.json
+  minecraft/advancements/recipes/decorations/brick_wall.json
+  minecraft/advancements/recipes/decorations/brick_wall_from_bricks_stonecutting.json
+  minecraft/advancements/recipes/decorations/diorite_wall.json
+  minecraft/advancements/recipes/decorations/diorite_wall_from_diorite_stonecutting.json
+  minecraft/advancements/recipes/decorations/end_stone_brick_wall.json
+  minecraft/advancements/recipes/decorations/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+  minecraft/advancements/recipes/decorations/end_stone_brick_wall_from_end_stone_stonecutting.json
+  minecraft/advancements/recipes/decorations/fletching_table.json
+  minecraft/advancements/recipes/decorations/granite_wall.json
+  minecraft/advancements/recipes/decorations/granite_wall_from_granite_stonecutting.json
+  minecraft/advancements/recipes/decorations/mossy_stone_brick_wall.json
+  minecraft/advancements/recipes/decorations/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+  minecraft/advancements/recipes/decorations/nether_brick_wall.json
+  minecraft/advancements/recipes/decorations/nether_brick_wall_from_nether_bricks_stonecutting.json
+  minecraft/advancements/recipes/decorations/prismarine_wall.json
+  minecraft/advancements/recipes/decorations/prismarine_wall_from_prismarine_stonecutting.json
+  minecraft/advancements/recipes/decorations/red_nether_brick_wall.json
+  minecraft/advancements/recipes/decorations/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
+  minecraft/advancements/recipes/decorations/red_sandstone_wall.json
+  minecraft/advancements/recipes/decorations/red_sandstone_wall_from_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/decorations/sandstone_wall.json
+  minecraft/advancements/recipes/decorations/sandstone_wall_from_sandstone_stonecutting.json
+  minecraft/advancements/recipes/decorations/smithing_table.json
+  minecraft/advancements/recipes/decorations/stone_brick_wall.json
+  minecraft/advancements/recipes/decorations/stone_brick_wall_from_stone_bricks_stonecutting.json
+  minecraft/advancements/recipes/decorations/stone_brick_walls_from_stone_stonecutting.json
+  minecraft/recipes/fletching_table.json
+  minecraft/recipes/smithing_table.json
+  minecraft/structures/village/desert/villagers
+  minecraft/structures/village/desert/villagers/nitwit.nbt
+  minecraft/structures/village/desert/villagers/unemployed.nbt
-  minecraft/structures/village/desert/zombie/villagers/armorer.nbt
-  minecraft/structures/village/desert/zombie/villagers/butcher.nbt
-  minecraft/structures/village/desert/zombie/villagers/cartographer.nbt
-  minecraft/structures/village/desert/zombie/villagers/cleric.nbt
-  minecraft/structures/village/desert/zombie/villagers/farmer.nbt
-  minecraft/structures/village/desert/zombie/villagers/fishermen.nbt
-  minecraft/structures/village/desert/zombie/villagers/fletcher.nbt
-  minecraft/structures/village/desert/zombie/villagers/leatherworker.nbt
-  minecraft/structures/village/desert/zombie/villagers/librarian.nbt
-  minecraft/structures/village/desert/zombie/villagers/shepherd.nbt
-  minecraft/structures/village/desert/zombie/villagers/toolsmith.nbt
-  minecraft/structures/village/desert/zombie/villagers/weaponsmith.nbt
-  minecraft/structures/village/plains/villagers/armorer.nbt
-  minecraft/structures/village/plains/villagers/butcher.nbt
-  minecraft/structures/village/plains/villagers/cartographer.nbt
-  minecraft/structures/village/plains/villagers/cleric.nbt
-  minecraft/structures/village/plains/villagers/farmer.nbt
-  minecraft/structures/village/plains/villagers/fishermen.nbt
-  minecraft/structures/village/plains/villagers/fletcher.nbt
-  minecraft/structures/village/plains/villagers/leatherworker.nbt
-  minecraft/structures/village/plains/villagers/librarian.nbt
-  minecraft/structures/village/plains/villagers/shepherd.nbt
-  minecraft/structures/village/plains/villagers/toolsmith.nbt
-  minecraft/structures/village/plains/villagers/weaponsmith.nbt
-  minecraft/structures/village/plains/zombie/villagers/armorer.nbt
-  minecraft/structures/village/plains/zombie/villagers/butcher.nbt
-  minecraft/structures/village/plains/zombie/villagers/cartographer.nbt
-  minecraft/structures/village/plains/zombie/villagers/cleric.nbt
-  minecraft/structures/village/plains/zombie/villagers/farmer.nbt
-  minecraft/structures/village/plains/zombie/villagers/fishermen.nbt
-  minecraft/structures/village/plains/zombie/villagers/fletcher.nbt
-  minecraft/structures/village/plains/zombie/villagers/leatherworker.nbt
-  minecraft/structures/village/plains/zombie/villagers/librarian.nbt
-  minecraft/structures/village/plains/zombie/villagers/shepherd.nbt
-  minecraft/structures/village/plains/zombie/villagers/toolsmith.nbt
-  minecraft/structures/village/plains/zombie/villagers/weaponsmith.nbt
+  minecraft/structures/village/savanna/villagers
+  minecraft/structures/village/savanna/villagers/nitwit.nbt
+  minecraft/structures/village/savanna/villagers/unemployed.nbt
-  minecraft/structures/village/savanna/zombie/villagers/armorer.nbt
-  minecraft/structures/village/savanna/zombie/villagers/butcher.nbt
-  minecraft/structures/village/savanna/zombie/villagers/cartographer.nbt
-  minecraft/structures/village/savanna/zombie/villagers/cleric.nbt
-  minecraft/structures/village/savanna/zombie/villagers/farmer.nbt
-  minecraft/structures/village/savanna/zombie/villagers/fishermen.nbt
-  minecraft/structures/village/savanna/zombie/villagers/fletcher.nbt
-  minecraft/structures/village/savanna/zombie/villagers/leatherworker.nbt
-  minecraft/structures/village/savanna/zombie/villagers/librarian.nbt
-  minecraft/structures/village/savanna/zombie/villagers/shepherd.nbt
-  minecraft/structures/village/savanna/zombie/villagers/toolsmith.nbt
-  minecraft/structures/village/savanna/zombie/villagers/weaponsmith.nbt
+  minecraft/structures/village/snowy/villagers
+  minecraft/structures/village/snowy/villagers/nitwit.nbt
+  minecraft/structures/village/snowy/villagers/unemployed.nbt
-  minecraft/structures/village/snowy/zombie/villagers/armorer.nbt
-  minecraft/structures/village/snowy/zombie/villagers/butcher.nbt
-  minecraft/structures/village/snowy/zombie/villagers/cartographer.nbt
-  minecraft/structures/village/snowy/zombie/villagers/cleric.nbt
-  minecraft/structures/village/snowy/zombie/villagers/farmer.nbt
-  minecraft/structures/village/snowy/zombie/villagers/fishermen.nbt
-  minecraft/structures/village/snowy/zombie/villagers/fletcher.nbt
-  minecraft/structures/village/snowy/zombie/villagers/leatherworker.nbt
-  minecraft/structures/village/snowy/zombie/villagers/librarian.nbt
-  minecraft/structures/village/snowy/zombie/villagers/shepherd.nbt
-  minecraft/structures/village/snowy/zombie/villagers/toolsmith.nbt
-  minecraft/structures/village/snowy/zombie/villagers/weaponsmith.nbt
+  minecraft/structures/village/taiga/villagers
+  minecraft/structures/village/taiga/villagers/nitwit.nbt
+  minecraft/structures/village/taiga/villagers/unemployed.nbt
-  minecraft/structures/village/taiga/zombie/villagers/armorer.nbt
-  minecraft/structures/village/taiga/zombie/villagers/butcher.nbt
-  minecraft/structures/village/taiga/zombie/villagers/cartographer.nbt
-  minecraft/structures/village/taiga/zombie/villagers/cleric.nbt
-  minecraft/structures/village/taiga/zombie/villagers/farmer.nbt
-  minecraft/structures/village/taiga/zombie/villagers/fishermen.nbt
-  minecraft/structures/village/taiga/zombie/villagers/fletcher.nbt
-  minecraft/structures/village/taiga/zombie/villagers/leatherworker.nbt
-  minecraft/structures/village/taiga/zombie/villagers/librarian.nbt
-  minecraft/structures/village/taiga/zombie/villagers/shepherd.nbt
-  minecraft/structures/village/taiga/zombie/villagers/toolsmith.nbt
-  minecraft/structures/village/taiga/zombie/villagers/weaponsmith.nbt
+  minecraft/tags/blocks/armorer_poi.json
+  minecraft/tags/blocks/butcher_poi.json
+  minecraft/tags/blocks/cartographer_poi.json
+  minecraft/tags/blocks/cleric_poi.json
+  minecraft/tags/blocks/farmer_poi.json
+  minecraft/tags/blocks/fisherman_poi.json
+  minecraft/tags/blocks/fletcher_poi.json
+  minecraft/tags/blocks/job_site_poi.json
+  minecraft/tags/blocks/leatherworker_poi.json
+  minecraft/tags/blocks/librarian_poi.json
+  minecraft/tags/blocks/mason_poi.json
+  minecraft/tags/blocks/meeting_site_poi.json
+  minecraft/tags/blocks/points_of_interest.json
+  minecraft/tags/blocks/shepherd_poi.json
+  minecraft/tags/blocks/toolsmith_poi.json
+  minecraft/tags/blocks/weaponsmith_poi.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/models/item/globe_banner_pattern.json
+  minecraft/textures/entity/banner/globe.png
+  minecraft/textures/item/globe_banner_pattern.png
```

</details>

## Registries

<details><summary>list</summary>

```diff
+ activity.txt
+ memory_module_type.txt
+ point_of_interest_type.txt
+ schedule.txt
+ sensor_type.txt
```

</details>

<details><summary>item.txt</summary>

```diff
+ minecraft:globe_banner_pattern
```

</details>

<details><summary>menu.txt</summary>

```diff
+ minecraft:generic_9x1
+ minecraft:generic_9x2
+ minecraft:generic_9x4
+ minecraft:generic_9x5
```

</details>

<details><summary>sound_event.txt</summary>

```diff
+ minecraft:entity.parrot.imitate.guardian
+ minecraft:entity.parrot.imitate.panda
+ minecraft:entity.parrot.imitate.pillager
+ minecraft:entity.parrot.imitate.ravager
+ minecraft:entity.villager.work_armorer
+ minecraft:entity.villager.work_butcher
+ minecraft:entity.villager.work_cartographer
+ minecraft:entity.villager.work_cleric
+ minecraft:entity.villager.work_farmer
+ minecraft:entity.villager.work_fisherman
+ minecraft:entity.villager.work_fletcher
+ minecraft:entity.villager.work_leatherworker
+ minecraft:entity.villager.work_librarian
+ minecraft:entity.villager.work_mason
+ minecraft:entity.villager.work_shepherd
+ minecraft:entity.villager.work_toolsmith
+ minecraft:entity.villager.work_weaponsmith
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/armorer_poi.json
+ blocks/butcher_poi.json
+ blocks/cartographer_poi.json
+ blocks/cleric_poi.json
+ blocks/farmer_poi.json
+ blocks/fisherman_poi.json
+ blocks/fletcher_poi.json
+ blocks/job_site_poi.json
+ blocks/leatherworker_poi.json
+ blocks/librarian_poi.json
+ blocks/mason_poi.json
+ blocks/meeting_site_poi.json
+ blocks/points_of_interest.json
+ blocks/shepherd_poi.json
+ blocks/toolsmith_poi.json
+ blocks/weaponsmith_poi.json
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
- recipes/building_blocks/andesite_wall.json
- recipes/building_blocks/andesite_wall_from_andesite_stonecutting.json
- recipes/building_blocks/brick_wall.json
- recipes/building_blocks/brick_wall_from_bricks_stonecutting.json
- recipes/building_blocks/diorite_wall.json
- recipes/building_blocks/diorite_wall_from_diorite_stonecutting.json
- recipes/building_blocks/end_stone_brick_wall.json
- recipes/building_blocks/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
- recipes/building_blocks/end_stone_brick_wall_from_end_stone_stonecutting.json
- recipes/building_blocks/granite_wall.json
- recipes/building_blocks/granite_wall_from_granite_stonecutting.json
- recipes/building_blocks/mossy_stone_brick_wall.json
- recipes/building_blocks/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
- recipes/building_blocks/nether_brick_wall.json
- recipes/building_blocks/nether_brick_wall_from_nether_bricks_stonecutting.json
- recipes/building_blocks/prismarine_wall.json
- recipes/building_blocks/prismarine_wall_from_prismarine_stonecutting.json
- recipes/building_blocks/red_nether_brick_wall.json
- recipes/building_blocks/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
- recipes/building_blocks/red_sandstone_wall.json
- recipes/building_blocks/red_sandstone_wall_from_red_sandstone_stonecutting.json
- recipes/building_blocks/sandstone_wall.json
- recipes/building_blocks/sandstone_wall_from_sandstone_stonecutting.json
- recipes/building_blocks/stone_brick_wall.json
- recipes/building_blocks/stone_brick_walls_from_stone_stonecutting.json
- recipes/building_blocks/stone_brick_wall_from_stone_bricks_stonecutting.json
+ recipes/decorations/andesite_wall.json
+ recipes/decorations/andesite_wall_from_andesite_stonecutting.json
+ recipes/decorations/brick_wall.json
+ recipes/decorations/brick_wall_from_bricks_stonecutting.json
+ recipes/decorations/diorite_wall.json
+ recipes/decorations/diorite_wall_from_diorite_stonecutting.json
+ recipes/decorations/end_stone_brick_wall.json
+ recipes/decorations/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+ recipes/decorations/end_stone_brick_wall_from_end_stone_stonecutting.json
+ recipes/decorations/fletching_table.json
+ recipes/decorations/granite_wall.json
+ recipes/decorations/granite_wall_from_granite_stonecutting.json
+ recipes/decorations/mossy_stone_brick_wall.json
+ recipes/decorations/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+ recipes/decorations/nether_brick_wall.json
+ recipes/decorations/nether_brick_wall_from_nether_bricks_stonecutting.json
+ recipes/decorations/prismarine_wall.json
+ recipes/decorations/prismarine_wall_from_prismarine_stonecutting.json
+ recipes/decorations/red_nether_brick_wall.json
+ recipes/decorations/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
+ recipes/decorations/red_sandstone_wall.json
+ recipes/decorations/red_sandstone_wall_from_red_sandstone_stonecutting.json
+ recipes/decorations/sandstone_wall.json
+ recipes/decorations/sandstone_wall_from_sandstone_stonecutting.json
+ recipes/decorations/smithing_table.json
+ recipes/decorations/stone_brick_wall.json
+ recipes/decorations/stone_brick_walls_from_stone_stonecutting.json
+ recipes/decorations/stone_brick_wall_from_stone_bricks_stonecutting.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
+ fletching_table.json
+ smithing_table.json
```

</details>

<details><summary>structures.txt</summary>

```diff
- village/desert/zombie/villagers/armorer.nbt
- village/desert/zombie/villagers/butcher.nbt
- village/desert/zombie/villagers/cartographer.nbt
- village/desert/zombie/villagers/cleric.nbt
- village/desert/zombie/villagers/farmer.nbt
- village/desert/zombie/villagers/fishermen.nbt
- village/desert/zombie/villagers/fletcher.nbt
- village/desert/zombie/villagers/leatherworker.nbt
- village/desert/zombie/villagers/librarian.nbt
- village/desert/zombie/villagers/shepherd.nbt
- village/desert/zombie/villagers/toolsmith.nbt
- village/desert/zombie/villagers/weaponsmith.nbt
- village/plains/villagers/armorer.nbt
- village/plains/villagers/butcher.nbt
- village/plains/villagers/cartographer.nbt
- village/plains/villagers/cleric.nbt
- village/plains/villagers/farmer.nbt
- village/plains/villagers/fishermen.nbt
- village/plains/villagers/fletcher.nbt
- village/plains/villagers/leatherworker.nbt
- village/plains/villagers/librarian.nbt
- village/plains/villagers/shepherd.nbt
- village/plains/villagers/toolsmith.nbt
- village/plains/villagers/weaponsmith.nbt
- village/plains/zombie/villagers/armorer.nbt
- village/plains/zombie/villagers/butcher.nbt
- village/plains/zombie/villagers/cartographer.nbt
- village/plains/zombie/villagers/cleric.nbt
- village/plains/zombie/villagers/farmer.nbt
- village/plains/zombie/villagers/fishermen.nbt
- village/plains/zombie/villagers/fletcher.nbt
- village/plains/zombie/villagers/leatherworker.nbt
- village/plains/zombie/villagers/librarian.nbt
- village/plains/zombie/villagers/shepherd.nbt
- village/plains/zombie/villagers/toolsmith.nbt
- village/plains/zombie/villagers/weaponsmith.nbt
- village/savanna/zombie/villagers/armorer.nbt
- village/savanna/zombie/villagers/butcher.nbt
- village/savanna/zombie/villagers/cartographer.nbt
- village/savanna/zombie/villagers/cleric.nbt
- village/savanna/zombie/villagers/farmer.nbt
- village/savanna/zombie/villagers/fishermen.nbt
- village/savanna/zombie/villagers/fletcher.nbt
- village/savanna/zombie/villagers/leatherworker.nbt
- village/savanna/zombie/villagers/librarian.nbt
- village/savanna/zombie/villagers/shepherd.nbt
- village/savanna/zombie/villagers/toolsmith.nbt
- village/savanna/zombie/villagers/weaponsmith.nbt
- village/snowy/zombie/villagers/armorer.nbt
- village/snowy/zombie/villagers/butcher.nbt
- village/snowy/zombie/villagers/cartographer.nbt
- village/snowy/zombie/villagers/cleric.nbt
- village/snowy/zombie/villagers/farmer.nbt
- village/snowy/zombie/villagers/fishermen.nbt
- village/snowy/zombie/villagers/fletcher.nbt
- village/snowy/zombie/villagers/leatherworker.nbt
- village/snowy/zombie/villagers/librarian.nbt
- village/snowy/zombie/villagers/shepherd.nbt
- village/snowy/zombie/villagers/toolsmith.nbt
- village/snowy/zombie/villagers/weaponsmith.nbt
- village/taiga/zombie/villagers/armorer.nbt
- village/taiga/zombie/villagers/butcher.nbt
- village/taiga/zombie/villagers/cartographer.nbt
- village/taiga/zombie/villagers/cleric.nbt
- village/taiga/zombie/villagers/farmer.nbt
- village/taiga/zombie/villagers/fishermen.nbt
- village/taiga/zombie/villagers/fletcher.nbt
- village/taiga/zombie/villagers/leatherworker.nbt
- village/taiga/zombie/villagers/librarian.nbt
- village/taiga/zombie/villagers/shepherd.nbt
- village/taiga/zombie/villagers/toolsmith.nbt
- village/taiga/zombie/villagers/weaponsmith.nbt
+ village/desert/villagers/nitwit.nbt
+ village/desert/villagers/unemployed.nbt
+ village/savanna/villagers/nitwit.nbt
+ village/savanna/villagers/unemployed.nbt
+ village/snowy/villagers/nitwit.nbt
+ village/snowy/villagers/unemployed.nbt
+ village/taiga/villagers/nitwit.nbt
+ village/taiga/villagers/unemployed.nbt
```

</details>

<details><summary>tags.txt</summary>

```diff
+ blocks/armorer_poi.json
+ blocks/butcher_poi.json
+ blocks/cartographer_poi.json
+ blocks/cleric_poi.json
+ blocks/farmer_poi.json
+ blocks/fisherman_poi.json
+ blocks/fletcher_poi.json
+ blocks/job_site_poi.json
+ blocks/leatherworker_poi.json
+ blocks/librarian_poi.json
+ blocks/mason_poi.json
+ blocks/meeting_site_poi.json
+ blocks/points_of_interest.json
+ blocks/shepherd_poi.json
+ blocks/toolsmith_poi.json
+ blocks/weaponsmith_poi.json
```

</details>

<details><summary>textures.txt</summary>

```diff
+ entity/banner/globe.png
+ item/globe_banner_pattern.png
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:text2speech:1.10.3
- com.mojang:text2speech:1.10.3
+ com.mojang:text2speech:1.11.2
+ com.mojang:text2speech:1.11.2
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