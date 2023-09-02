<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w12a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w12a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-03-20T16:47:34+00:00</td></tr>
<tr><th>SHA1</th><td>91e9bb4b6af34b07c6a89c95696b988b8156702b</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/91e9bb4b6af34b07c6a89c95696b988b8156702b/19w12a.json">https://piston-meta.mojang.com/v1/packages/91e9bb4b6af34b07c6a89c95696b988b8156702b/19w12a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/dc1a1dfef026d38dfc04b360653172f5428f86ef/server.jar">https://piston-data.mojang.com/v1/objects/dc1a1dfef026d38dfc04b360653172f5428f86ef/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/15ee2d37e5ec79dbf51aa39b000616be94033d6a/client.jar">https://piston-data.mojang.com/v1/objects/15ee2d37e5ec79dbf51aa39b000616be94033d6a/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w11b">19w11b</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/building_blocks/cut_red_sandstone_slab.json
+  minecraft/advancements/recipes/building_blocks/cut_red_sandstone_slab_from_cut_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/cut_red_sandstone_slab_from_red_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/cut_sandstone_slab.json
+  minecraft/advancements/recipes/building_blocks/cut_sandstone_slab_from_cut_sandstone_stonecutting.json
+  minecraft/advancements/recipes/building_blocks/cut_sandstone_slab_from_sandstone_stonecutting.json
+  minecraft/loot_tables/blocks/cut_red_sandstone_slab.json
+  minecraft/loot_tables/blocks/cut_sandstone_slab.json
+  minecraft/recipes/cut_red_sandstone_slab.json
+  minecraft/recipes/cut_red_sandstone_slab_from_cut_red_sandstone_stonecutting.json
+  minecraft/recipes/cut_red_sandstone_slab_from_red_sandstone_stonecutting.json
+  minecraft/recipes/cut_sandstone_slab.json
+  minecraft/recipes/cut_sandstone_slab_from_cut_sandstone_stonecutting.json
+  minecraft/recipes/cut_sandstone_slab_from_sandstone_stonecutting.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/cut_red_sandstone_slab.json
+  minecraft/blockstates/cut_sandstone_slab.json
+  minecraft/models/block/cut_red_sandstone_slab.json
+  minecraft/models/block/cut_red_sandstone_slab_top.json
+  minecraft/models/block/cut_sandstone_slab.json
+  minecraft/models/block/cut_sandstone_slab_top.json
+  minecraft/models/item/cut_red_sandstone_slab.json
+  minecraft/models/item/cut_sandstone_slab.json
```

</details>

## Registries

<details><summary>activity.txt</summary>

```diff
+ minecraft:play
```

</details>

<details><summary>block.txt</summary>

```diff
+ minecraft:cut_sandstone_slab
+ minecraft:cut_red_sandstone_slab
```

</details>

<details><summary>item.txt</summary>

```diff
+ minecraft:cut_sandstone_slab
+ minecraft:cut_red_sandstone_slab
```

</details>

<details><summary>memory_module_type.txt</summary>

```diff
+ minecraft:secondary_job_site
+ minecraft:golem_spawn_conditions
```

</details>

<details><summary>sensor_type.txt</summary>

```diff
+ minecraft:secondary_pois
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/building_blocks/cut_red_sandstone_slab.json
+ recipes/building_blocks/cut_red_sandstone_slab_from_cut_red_sandstone_stonecutting.json
+ recipes/building_blocks/cut_red_sandstone_slab_from_red_sandstone_stonecutting.json
+ recipes/building_blocks/cut_sandstone_slab.json
+ recipes/building_blocks/cut_sandstone_slab_from_cut_sandstone_stonecutting.json
+ recipes/building_blocks/cut_sandstone_slab_from_sandstone_stonecutting.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
+ blocks/cut_red_sandstone_slab.json
+ blocks/cut_sandstone_slab.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
+ cut_red_sandstone_slab.json
+ cut_red_sandstone_slab_from_cut_red_sandstone_stonecutting.json
+ cut_red_sandstone_slab_from_red_sandstone_stonecutting.json
+ cut_sandstone_slab.json
+ cut_sandstone_slab_from_cut_sandstone_stonecutting.json
+ cut_sandstone_slab_from_sandstone_stonecutting.json
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:realms:1.14.1
- com.paulscode:codecjorbis:20101023
- com.paulscode:codecwav:20101023
- com.paulscode:libraryjavasound:20101123
- com.paulscode:soundsystem:20120107
+ com.mojang:realms:1.14.2
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