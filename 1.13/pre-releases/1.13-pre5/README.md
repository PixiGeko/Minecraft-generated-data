<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.13-pre5 ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.13-pre5</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2018-06-28T13:58:53+00:00</td></tr>
<tr><th>SHA1</th><td>f0500efb357283322169d38fd52d24e195d56e05</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/f0500efb357283322169d38fd52d24e195d56e05/1.13-pre5.json">https://piston-meta.mojang.com/v1/packages/f0500efb357283322169d38fd52d24e195d56e05/1.13-pre5.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/6d9ede222df5726059aba1b01f99c328bc16f1a5/server.jar">https://piston-data.mojang.com/v1/objects/6d9ede222df5726059aba1b01f99c328bc16f1a5/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/f3262055c586a075fc84f9d4bc76b3cf1a72d69c/client.jar">https://piston-data.mojang.com/v1/objects/f3262055c586a075fc84f9d4bc76b3cf1a72d69c/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre4">1.13-pre4</a>
## File structure

<details><summary>data/</summary>

```diff
-  minecraft/advancements/recipes/building_blocks/acacia_bark.json
+  minecraft/advancements/recipes/building_blocks/acacia_wood.json
-  minecraft/advancements/recipes/building_blocks/birch_bark.json
+  minecraft/advancements/recipes/building_blocks/birch_wood.json
-  minecraft/advancements/recipes/building_blocks/dark_oak_bark.json
+  minecraft/advancements/recipes/building_blocks/dark_oak_wood.json
-  minecraft/advancements/recipes/building_blocks/jungle_bark.json
+  minecraft/advancements/recipes/building_blocks/jungle_wood.json
-  minecraft/advancements/recipes/building_blocks/oak_bark.json
+  minecraft/advancements/recipes/building_blocks/oak_wood.json
-  minecraft/advancements/recipes/building_blocks/spruce_bark.json
+  minecraft/advancements/recipes/building_blocks/spruce_wood.json
-  minecraft/advancements/recipes/misc/chorus_fruit_popped.json
+  minecraft/advancements/recipes/misc/popped_chorus_fruit.json
-  minecraft/loot_tables/entities/evocation_illager.json
+  minecraft/loot_tables/entities/evoker.json
+  minecraft/loot_tables/entities/snow_golem.json
-  minecraft/loot_tables/entities/snowman.json
-  minecraft/loot_tables/entities/vindication_illager.json
+  minecraft/loot_tables/entities/vindicator.json
-  minecraft/recipes/acacia_bark.json
+  minecraft/recipes/acacia_wood.json
-  minecraft/recipes/birch_bark.json
+  minecraft/recipes/birch_wood.json
-  minecraft/recipes/chorus_fruit_popped.json
-  minecraft/recipes/dark_oak_bark.json
+  minecraft/recipes/dark_oak_wood.json
-  minecraft/recipes/jungle_bark.json
+  minecraft/recipes/jungle_wood.json
-  minecraft/recipes/oak_bark.json
+  minecraft/recipes/oak_wood.json
+  minecraft/recipes/popped_chorus_fruit.json
-  minecraft/recipes/spruce_bark.json
+  minecraft/recipes/spruce_wood.json
```

</details>

<details><summary>assets/</summary>

```diff
-  minecraft/blockstates/acacia_bark.json
+  minecraft/blockstates/acacia_wood.json
-  minecraft/blockstates/birch_bark.json
+  minecraft/blockstates/birch_wood.json
-  minecraft/blockstates/dark_oak_bark.json
+  minecraft/blockstates/dark_oak_wood.json
-  minecraft/blockstates/jungle_bark.json
+  minecraft/blockstates/jungle_wood.json
-  minecraft/blockstates/mob_spawner.json
+  minecraft/blockstates/nether_portal.json
-  minecraft/blockstates/oak_bark.json
+  minecraft/blockstates/oak_wood.json
-  minecraft/blockstates/portal.json
+  minecraft/blockstates/spawner.json
-  minecraft/blockstates/spruce_bark.json
+  minecraft/blockstates/spruce_wood.json
-  minecraft/blockstates/stripped_acacia_bark.json
+  minecraft/blockstates/stripped_acacia_wood.json
-  minecraft/blockstates/stripped_birch_bark.json
+  minecraft/blockstates/stripped_birch_wood.json
-  minecraft/blockstates/stripped_dark_oak_bark.json
+  minecraft/blockstates/stripped_dark_oak_wood.json
-  minecraft/blockstates/stripped_jungle_bark.json
+  minecraft/blockstates/stripped_jungle_wood.json
-  minecraft/blockstates/stripped_oak_bark.json
+  minecraft/blockstates/stripped_oak_wood.json
-  minecraft/blockstates/stripped_spruce_bark.json
+  minecraft/blockstates/stripped_spruce_wood.json
-  minecraft/models/block/acacia_bark.json
+  minecraft/models/block/acacia_wood.json
-  minecraft/models/block/birch_bark.json
+  minecraft/models/block/birch_wood.json
-  minecraft/models/block/dark_oak_bark.json
+  minecraft/models/block/dark_oak_wood.json
-  minecraft/models/block/jungle_bark.json
+  minecraft/models/block/jungle_wood.json
-  minecraft/models/block/mob_spawner.json
+  minecraft/models/block/nether_portal_ew.json
+  minecraft/models/block/nether_portal_ns.json
-  minecraft/models/block/oak_bark.json
+  minecraft/models/block/oak_wood.json
-  minecraft/models/block/portal_ew.json
-  minecraft/models/block/portal_ns.json
+  minecraft/models/block/spawner.json
-  minecraft/models/block/spruce_bark.json
+  minecraft/models/block/spruce_wood.json
-  minecraft/models/block/stripped_acacia_bark.json
+  minecraft/models/block/stripped_acacia_wood.json
-  minecraft/models/block/stripped_birch_bark.json
+  minecraft/models/block/stripped_birch_wood.json
-  minecraft/models/block/stripped_dark_oak_bark.json
+  minecraft/models/block/stripped_dark_oak_wood.json
-  minecraft/models/block/stripped_jungle_bark.json
+  minecraft/models/block/stripped_jungle_wood.json
-  minecraft/models/block/stripped_oak_bark.json
+  minecraft/models/block/stripped_oak_wood.json
-  minecraft/models/block/stripped_spruce_bark.json
+  minecraft/models/block/stripped_spruce_wood.json
-  minecraft/models/item/acacia_bark.json
+  minecraft/models/item/acacia_wood.json
-  minecraft/models/item/birch_bark.json
+  minecraft/models/item/birch_wood.json
-  minecraft/models/item/chorus_fruit_popped.json
-  minecraft/models/item/clownfish.json
-  minecraft/models/item/clownfish_bucket.json
-  minecraft/models/item/dark_oak_bark.json
+  minecraft/models/item/dark_oak_wood.json
-  minecraft/models/item/evocation_illager_spawn_egg.json
+  minecraft/models/item/evoker_spawn_egg.json
-  minecraft/models/item/jungle_bark.json
+  minecraft/models/item/jungle_wood.json
-  minecraft/models/item/mob_spawner.json
-  minecraft/models/item/oak_bark.json
+  minecraft/models/item/oak_wood.json
+  minecraft/models/item/popped_chorus_fruit.json
+  minecraft/models/item/spawner.json
-  minecraft/models/item/spruce_bark.json
+  minecraft/models/item/spruce_wood.json
-  minecraft/models/item/stripped_acacia_bark.json
+  minecraft/models/item/stripped_acacia_wood.json
-  minecraft/models/item/stripped_birch_bark.json
+  minecraft/models/item/stripped_birch_wood.json
-  minecraft/models/item/stripped_dark_oak_bark.json
+  minecraft/models/item/stripped_dark_oak_wood.json
-  minecraft/models/item/stripped_jungle_bark.json
+  minecraft/models/item/stripped_jungle_wood.json
-  minecraft/models/item/stripped_oak_bark.json
+  minecraft/models/item/stripped_oak_wood.json
-  minecraft/models/item/stripped_spruce_bark.json
+  minecraft/models/item/stripped_spruce_wood.json
+  minecraft/models/item/tropical_fish.json
+  minecraft/models/item/tropical_fish_bucket.json
-  minecraft/models/item/vindication_illager_spawn_egg.json
+  minecraft/models/item/vindicator_spawn_egg.json
-  minecraft/textures/block/mob_spawner.png
+  minecraft/textures/block/nether_portal.png
+  minecraft/textures/block/nether_portal.png.mcmeta
-  minecraft/textures/block/portal.png
-  minecraft/textures/block/portal.png.mcmeta
+  minecraft/textures/block/spawner.png
+  minecraft/textures/entity/end_crystal
+  minecraft/textures/entity/end_crystal/end_crystal.png
+  minecraft/textures/entity/end_crystal/end_crystal_beam.png
-  minecraft/textures/entity/endercrystal
-  minecraft/textures/entity/endercrystal/endercrystal.png
-  minecraft/textures/entity/endercrystal/endercrystal_beam.png
+  minecraft/textures/entity/illager/evoker_fangs.png
-  minecraft/textures/entity/illager/fangs.png
+  minecraft/textures/entity/illager/illusioner.png
-  minecraft/textures/entity/illager/illusionist.png
+  minecraft/textures/entity/snow_golem.png
-  minecraft/textures/entity/snowman.png
-  minecraft/textures/item/chorus_fruit_popped.png
-  minecraft/textures/item/clownfish.png
-  minecraft/textures/item/clownfish_bucket.png
+  minecraft/textures/item/popped_chorus_fruit.png
+  minecraft/textures/item/tropical_fish.png
+  minecraft/textures/item/tropical_fish_bucket.png
```

</details>

## Tags

<details><summary>blocks/acacia_logs.json</summary>

```diff
- minecraft:acacia_bark
- minecraft:stripped_acacia_bark
+ minecraft:acacia_wood
+ minecraft:stripped_acacia_wood
```

</details>

<details><summary>blocks/birch_logs.json</summary>

```diff
- minecraft:birch_bark
- minecraft:stripped_birch_bark
+ minecraft:birch_wood
+ minecraft:stripped_birch_wood
```

</details>

<details><summary>blocks/dark_oak_logs.json</summary>

```diff
- minecraft:dark_oak_bark
- minecraft:stripped_dark_oak_bark
+ minecraft:dark_oak_wood
+ minecraft:stripped_dark_oak_wood
```

</details>

<details><summary>blocks/jungle_logs.json</summary>

```diff
- minecraft:jungle_bark
- minecraft:stripped_jungle_bark
+ minecraft:jungle_wood
+ minecraft:stripped_jungle_wood
```

</details>

<details><summary>blocks/oak_logs.json</summary>

```diff
- minecraft:oak_bark
- minecraft:stripped_oak_bark
+ minecraft:oak_wood
+ minecraft:stripped_oak_wood
```

</details>

<details><summary>blocks/spruce_logs.json</summary>

```diff
- minecraft:spruce_bark
- minecraft:stripped_spruce_bark
+ minecraft:spruce_wood
+ minecraft:stripped_spruce_wood
```

</details>

<details><summary>items/acacia_logs.json</summary>

```diff
- minecraft:acacia_bark
- minecraft:stripped_acacia_bark
+ minecraft:acacia_wood
+ minecraft:stripped_acacia_wood
```

</details>

<details><summary>items/birch_logs.json</summary>

```diff
- minecraft:birch_bark
- minecraft:stripped_birch_bark
+ minecraft:birch_wood
+ minecraft:stripped_birch_wood
```

</details>

<details><summary>items/dark_oak_logs.json</summary>

```diff
- minecraft:dark_oak_bark
- minecraft:stripped_dark_oak_bark
+ minecraft:dark_oak_wood
+ minecraft:stripped_dark_oak_wood
```

</details>

<details><summary>items/fishes.json</summary>

```diff
- minecraft:clownfish
+ minecraft:tropical_fish
```

</details>

<details><summary>items/jungle_logs.json</summary>

```diff
- minecraft:jungle_bark
- minecraft:stripped_jungle_bark
+ minecraft:jungle_wood
+ minecraft:stripped_jungle_wood
```

</details>

<details><summary>items/oak_logs.json</summary>

```diff
- minecraft:oak_bark
- minecraft:stripped_oak_bark
+ minecraft:oak_wood
+ minecraft:stripped_oak_wood
```

</details>

<details><summary>items/spruce_logs.json</summary>

```diff
- minecraft:spruce_bark
- minecraft:stripped_spruce_bark
+ minecraft:spruce_wood
+ minecraft:stripped_spruce_wood
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
- recipes/building_blocks/acacia_bark.json
- recipes/building_blocks/birch_bark.json
- recipes/building_blocks/dark_oak_bark.json
- recipes/building_blocks/jungle_bark.json
- recipes/building_blocks/oak_bark.json
- recipes/building_blocks/spruce_bark.json
- recipes/misc/chorus_fruit_popped.json
+ recipes/building_blocks/acacia_wood.json
+ recipes/building_blocks/birch_wood.json
+ recipes/building_blocks/dark_oak_wood.json
+ recipes/building_blocks/jungle_wood.json
+ recipes/building_blocks/oak_wood.json
+ recipes/building_blocks/spruce_wood.json
+ recipes/misc/popped_chorus_fruit.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
- entities/evocation_illager.json
- entities/snowman.json
- entities/vindication_illager.json
+ entities/evoker.json
+ entities/snow_golem.json
+ entities/vindicator.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
- acacia_bark.json
- birch_bark.json
- chorus_fruit_popped.json
- dark_oak_bark.json
- jungle_bark.json
- oak_bark.json
- spruce_bark.json
+ acacia_wood.json
+ birch_wood.json
+ dark_oak_wood.json
+ jungle_wood.json
+ oak_wood.json
+ popped_chorus_fruit.json
+ spruce_wood.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- block/mob_spawner.png
- block/portal.png
- entity/endercrystal/endercrystal.png
- entity/endercrystal/endercrystal_beam.png
- entity/illager/fangs.png
- entity/illager/illusionist.png
- entity/snowman.png
- item/chorus_fruit_popped.png
- item/clownfish.png
- item/clownfish_bucket.png
+ block/nether_portal.png
+ block/spawner.png
+ entity/end_crystal/end_crystal.png
+ entity/end_crystal/end_crystal_beam.png
+ entity/illager/evoker_fangs.png
+ entity/illager/illusioner.png
+ entity/snow_golem.png
+ item/popped_chorus_fruit.png
+ item/tropical_fish.png
+ item/tropical_fish_bucket.png
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
- io.netty:netty-all:4.1.9.Final
+ com.mojang:datafixerupper:1.0.3
+ io.netty:netty-all:4.1.25.Final
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