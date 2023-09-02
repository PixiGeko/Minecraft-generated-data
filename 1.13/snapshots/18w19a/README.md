<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w19a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w19a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-05-08T13:05:19+00:00</td></tr>
<tr><th>SHA1</th><td>56cac74df46a43a6385708beafeed1df79590eb2</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/56cac74df46a43a6385708beafeed1df79590eb2/18w19a.json">https://piston-meta.mojang.com/v1/packages/56cac74df46a43a6385708beafeed1df79590eb2/18w19a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/97ad982d57fb7b7cb9dc28ffd87c79538b1901f6/server.jar">https://piston-data.mojang.com/v1/objects/97ad982d57fb7b7cb9dc28ffd87c79538b1901f6/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/d52b2e8f15a764000c1ca6dabab4440069ff97a4/client.jar">https://piston-data.mojang.com/v1/objects/d52b2e8f15a764000c1ca6dabab4440069ff97a4/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w16a">18w16a</a>
## File structure

<details><summary>data/</summary>

```diff
-  minecraft/loot_tables/entities/puffer_fish.json
+  minecraft/loot_tables/entities/pufferfish.json
+  minecraft/tags/blocks/leaves.json
+  minecraft/tags/fluids
+  minecraft/tags/fluids/lava.json
+  minecraft/tags/fluids/water.json
+  minecraft/tags/items/fishes.json
+  minecraft/tags/items/leaves.json
```

</details>

<details><summary>assets/</summary>

```diff
-  minecraft/blockstates/sea_grass.json
+  minecraft/blockstates/seagrass.json
-  minecraft/blockstates/tall_sea_grass.json
+  minecraft/blockstates/tall_seagrass.json
-  minecraft/models/block/sea_grass.json
+  minecraft/models/block/seagrass.json
-  minecraft/models/block/tall_sea_grass_bottom.json
-  minecraft/models/block/tall_sea_grass_top.json
+  minecraft/models/block/tall_seagrass_bottom.json
+  minecraft/models/block/tall_seagrass_top.json
-  minecraft/models/item/puffer_fish_spawn_egg.json
+  minecraft/models/item/pufferfish_spawn_egg.json
-  minecraft/models/item/sea_grass.json
+  minecraft/models/item/seagrass.json
-  minecraft/textures/blocks/sea_grass.png
-  minecraft/textures/blocks/sea_grass.png.mcmeta
+  minecraft/textures/blocks/seagrass.png
+  minecraft/textures/blocks/seagrass.png.mcmeta
-  minecraft/textures/blocks/tall_sea_grass_bottom.png
-  minecraft/textures/blocks/tall_sea_grass_bottom.png.mcmeta
-  minecraft/textures/blocks/tall_sea_grass_top.png
-  minecraft/textures/blocks/tall_sea_grass_top.png.mcmeta
+  minecraft/textures/blocks/tall_seagrass_bottom.png
+  minecraft/textures/blocks/tall_seagrass_bottom.png.mcmeta
+  minecraft/textures/blocks/tall_seagrass_top.png
+  minecraft/textures/blocks/tall_seagrass_top.png.mcmeta
-  minecraft/textures/items/sea_grass.png
+  minecraft/textures/items/seagrass.png
+  minecraft/textures/items/turtle_egg.png
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/leaves.json
+ fluids/lava.json
+ fluids/water.json
+ items/fishes.json
+ items/leaves.json
```

</details>

<details><summary>blocks/ice.json</summary>

```diff
+ minecraft:frosted_ice
```

</details>

## Misc

<details><summary>loot_tables.txt</summary>

```diff
- entities/puffer_fish.json
+ entities/pufferfish.json
```

</details>

<details><summary>tags.txt</summary>

```diff
+ blocks/leaves.json
+ fluids/lava.json
+ fluids/water.json
+ items/fishes.json
+ items/leaves.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- blocks/sea_grass.png
- blocks/tall_sea_grass_bottom.png
- blocks/tall_sea_grass_top.png
- items/sea_grass.png
+ blocks/seagrass.png
+ blocks/tall_seagrass_bottom.png
+ blocks/tall_seagrass_top.png
+ items/seagrass.png
+ items/turtle_egg.png
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:brigadier:0.1.24
+ com.mojang:brigadier:0.1.25
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