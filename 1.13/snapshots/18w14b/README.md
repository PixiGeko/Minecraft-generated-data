<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w14b ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w14b</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-04-05T14:44:02+00:00</td></tr>
<tr><th>SHA1</th><td>8b4dc5007c1306f5823cfcefd4dbb1e944c8439e</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/8b4dc5007c1306f5823cfcefd4dbb1e944c8439e/18w14b.json">https://piston-meta.mojang.com/v1/packages/8b4dc5007c1306f5823cfcefd4dbb1e944c8439e/18w14b.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/85d6445fc4596e6b69fb00f0d3e5462dfeeb933c/server.jar">https://piston-data.mojang.com/v1/objects/85d6445fc4596e6b69fb00f0d3e5462dfeeb933c/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/d9b4fc98eb5242346ed0421f6ccd3c9032dc0514/client.jar">https://piston-data.mojang.com/v1/objects/d9b4fc98eb5242346ed0421f6ccd3c9032dc0514/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w14a">18w14a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/misc/cactus_green.json
+  minecraft/advancements/recipes/misc/lime_dye_from_smelting.json
+  minecraft/recipes/cactus_green.json
+  minecraft/recipes/lime_dye_from_smelting.json
+  minecraft/tags/blocks/live_coral.json
+  minecraft/tags/items/live_coral.json
```

</details>

<details><summary>assets/</summary>

```diff
-  minecraft/blockstates/blue_coral.json
-  minecraft/blockstates/blue_coral_fan.json
-  minecraft/blockstates/blue_coral_plant.json
-  minecraft/blockstates/blue_dead_coral.json
+  minecraft/blockstates/brain_coral.json
+  minecraft/blockstates/brain_coral_block.json
+  minecraft/blockstates/brain_coral_fan.json
+  minecraft/blockstates/bubble_coral.json
+  minecraft/blockstates/bubble_coral_block.json
+  minecraft/blockstates/bubble_coral_fan.json
+  minecraft/blockstates/dead_brain_coral_block.json
+  minecraft/blockstates/dead_bubble_coral_block.json
+  minecraft/blockstates/dead_fire_coral_block.json
+  minecraft/blockstates/dead_horn_coral_block.json
+  minecraft/blockstates/dead_tube_coral_block.json
+  minecraft/blockstates/fire_coral.json
+  minecraft/blockstates/fire_coral_block.json
+  minecraft/blockstates/fire_coral_fan.json
+  minecraft/blockstates/horn_coral.json
+  minecraft/blockstates/horn_coral_block.json
+  minecraft/blockstates/horn_coral_fan.json
-  minecraft/blockstates/pink_coral.json
-  minecraft/blockstates/pink_coral_fan.json
-  minecraft/blockstates/pink_coral_plant.json
-  minecraft/blockstates/pink_dead_coral.json
-  minecraft/blockstates/purple_coral.json
-  minecraft/blockstates/purple_coral_fan.json
-  minecraft/blockstates/purple_coral_plant.json
-  minecraft/blockstates/purple_dead_coral.json
-  minecraft/blockstates/red_coral.json
-  minecraft/blockstates/red_coral_fan.json
-  minecraft/blockstates/red_coral_plant.json
-  minecraft/blockstates/red_dead_coral.json
+  minecraft/blockstates/sea_pickle.json
+  minecraft/blockstates/tube_coral.json
+  minecraft/blockstates/tube_coral_block.json
+  minecraft/blockstates/tube_coral_fan.json
-  minecraft/blockstates/yellow_coral.json
-  minecraft/blockstates/yellow_coral_fan.json
-  minecraft/blockstates/yellow_coral_plant.json
-  minecraft/blockstates/yellow_dead_coral.json
-  minecraft/models/block/blue_coral.json
-  minecraft/models/block/blue_coral_fan.json
-  minecraft/models/block/blue_coral_plant.json
-  minecraft/models/block/blue_dead_coral.json
+  minecraft/models/block/brain_coral.json
+  minecraft/models/block/brain_coral_block.json
+  minecraft/models/block/brain_coral_fan.json
+  minecraft/models/block/bubble_coral.json
+  minecraft/models/block/bubble_coral_block.json
+  minecraft/models/block/bubble_coral_fan.json
+  minecraft/models/block/dead_brain_coral_block.json
+  minecraft/models/block/dead_bubble_coral_block.json
+  minecraft/models/block/dead_fire_coral_block.json
+  minecraft/models/block/dead_horn_coral_block.json
+  minecraft/models/block/dead_sea_pickle.json
+  minecraft/models/block/dead_tube_coral_block.json
+  minecraft/models/block/fire_coral.json
+  minecraft/models/block/fire_coral_block.json
+  minecraft/models/block/fire_coral_fan.json
+  minecraft/models/block/four_dead_sea_pickles.json
+  minecraft/models/block/four_sea_pickles.json
+  minecraft/models/block/horn_coral.json
+  minecraft/models/block/horn_coral_block.json
+  minecraft/models/block/horn_coral_fan.json
-  minecraft/models/block/pink_coral.json
-  minecraft/models/block/pink_coral_fan.json
-  minecraft/models/block/pink_coral_plant.json
-  minecraft/models/block/pink_dead_coral.json
-  minecraft/models/block/purple_coral.json
-  minecraft/models/block/purple_coral_fan.json
-  minecraft/models/block/purple_coral_plant.json
-  minecraft/models/block/purple_dead_coral.json
-  minecraft/models/block/red_coral.json
-  minecraft/models/block/red_coral_fan.json
-  minecraft/models/block/red_coral_plant.json
-  minecraft/models/block/red_dead_coral.json
+  minecraft/models/block/sea_pickle.json
+  minecraft/models/block/three_dead_sea_pickles.json
+  minecraft/models/block/three_sea_pickles.json
+  minecraft/models/block/tube_coral.json
+  minecraft/models/block/tube_coral_block.json
+  minecraft/models/block/tube_coral_fan.json
+  minecraft/models/block/two_dead_sea_pickles.json
+  minecraft/models/block/two_sea_pickles.json
-  minecraft/models/block/yellow_coral.json
-  minecraft/models/block/yellow_coral_fan.json
-  minecraft/models/block/yellow_coral_plant.json
-  minecraft/models/block/yellow_dead_coral.json
-  minecraft/models/item/blue_coral.json
-  minecraft/models/item/blue_coral_fan.json
-  minecraft/models/item/blue_coral_plant.json
-  minecraft/models/item/blue_dead_coral.json
+  minecraft/models/item/brain_coral.json
+  minecraft/models/item/brain_coral_block.json
+  minecraft/models/item/brain_coral_fan.json
+  minecraft/models/item/bubble_coral.json
+  minecraft/models/item/bubble_coral_block.json
+  minecraft/models/item/bubble_coral_fan.json
+  minecraft/models/item/dead_brain_coral_block.json
+  minecraft/models/item/dead_bubble_coral_block.json
+  minecraft/models/item/dead_fire_coral_block.json
+  minecraft/models/item/dead_horn_coral_block.json
+  minecraft/models/item/dead_tube_coral_block.json
+  minecraft/models/item/fire_coral.json
+  minecraft/models/item/fire_coral_block.json
+  minecraft/models/item/fire_coral_fan.json
+  minecraft/models/item/horn_coral.json
+  minecraft/models/item/horn_coral_block.json
+  minecraft/models/item/horn_coral_fan.json
-  minecraft/models/item/pink_coral.json
-  minecraft/models/item/pink_coral_fan.json
-  minecraft/models/item/pink_coral_plant.json
-  minecraft/models/item/pink_dead_coral.json
-  minecraft/models/item/purple_coral.json
-  minecraft/models/item/purple_coral_fan.json
-  minecraft/models/item/purple_coral_plant.json
-  minecraft/models/item/purple_dead_coral.json
-  minecraft/models/item/red_coral.json
-  minecraft/models/item/red_coral_fan.json
-  minecraft/models/item/red_coral_plant.json
-  minecraft/models/item/red_dead_coral.json
+  minecraft/models/item/sea_pickle.json
+  minecraft/models/item/tube_coral.json
+  minecraft/models/item/tube_coral_block.json
+  minecraft/models/item/tube_coral_fan.json
-  minecraft/models/item/yellow_coral.json
-  minecraft/models/item/yellow_coral_fan.json
-  minecraft/models/item/yellow_coral_plant.json
-  minecraft/models/item/yellow_dead_coral.json
-  minecraft/textures/blocks/blue_coral.png
-  minecraft/textures/blocks/blue_coral_fan.png
-  minecraft/textures/blocks/blue_coral_plant.png
-  minecraft/textures/blocks/blue_dead_coral.png
+  minecraft/textures/blocks/brain_coral.png
+  minecraft/textures/blocks/brain_coral_block.png
+  minecraft/textures/blocks/brain_coral_fan.png
+  minecraft/textures/blocks/bubble_coral.png
+  minecraft/textures/blocks/bubble_coral_block.png
+  minecraft/textures/blocks/bubble_coral_fan.png
+  minecraft/textures/blocks/dead_brain_coral_block.png
+  minecraft/textures/blocks/dead_bubble_coral_block.png
+  minecraft/textures/blocks/dead_fire_coral_block.png
+  minecraft/textures/blocks/dead_horn_coral_block.png
+  minecraft/textures/blocks/dead_tube_coral_block.png
+  minecraft/textures/blocks/fire_coral.png
+  minecraft/textures/blocks/fire_coral_block.png
+  minecraft/textures/blocks/fire_coral_fan.png
+  minecraft/textures/blocks/horn_coral.png
+  minecraft/textures/blocks/horn_coral_block.png
+  minecraft/textures/blocks/horn_coral_fan.png
-  minecraft/textures/blocks/pink_coral.png
-  minecraft/textures/blocks/pink_coral_fan.png
-  minecraft/textures/blocks/pink_coral_plant.png
-  minecraft/textures/blocks/pink_dead_coral.png
-  minecraft/textures/blocks/purple_coral.png
-  minecraft/textures/blocks/purple_coral_fan.png
-  minecraft/textures/blocks/purple_coral_plant.png
-  minecraft/textures/blocks/purple_dead_coral.png
-  minecraft/textures/blocks/red_coral.png
-  minecraft/textures/blocks/red_coral_fan.png
-  minecraft/textures/blocks/red_coral_plant.png
-  minecraft/textures/blocks/red_dead_coral.png
+  minecraft/textures/blocks/sea_pickle.png
+  minecraft/textures/blocks/tube_coral.png
+  minecraft/textures/blocks/tube_coral_block.png
+  minecraft/textures/blocks/tube_coral_fan.png
-  minecraft/textures/blocks/yellow_coral.png
-  minecraft/textures/blocks/yellow_coral_fan.png
-  minecraft/textures/blocks/yellow_coral_plant.png
-  minecraft/textures/blocks/yellow_dead_coral.png
+  minecraft/textures/items/sea_pickle.png
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/live_coral.json
+ items/live_coral.json
```

</details>

<details><summary>blocks/coral.json</summary>

```diff
- minecraft:blue_dead_coral
- minecraft:pink_dead_coral
- minecraft:purple_dead_coral
- minecraft:red_dead_coral
- minecraft:yellow_dead_coral
- minecraft:blue_coral
- minecraft:pink_coral
- minecraft:purple_coral
- minecraft:red_coral
- minecraft:yellow_coral
+ minecraft:dead_tube_coral_block
+ minecraft:dead_brain_coral_block
+ minecraft:dead_bubble_coral_block
+ minecraft:dead_fire_coral_block
+ minecraft:dead_horn_coral_block
+ #minecraft:live_coral
```

</details>

<details><summary>blocks/coral_plants.json</summary>

```diff
- minecraft:blue_coral_plant
- minecraft:pink_coral_plant
- minecraft:purple_coral_plant
- minecraft:red_coral_plant
- minecraft:yellow_coral_plant
+ minecraft:tube_coral
+ minecraft:brain_coral
+ minecraft:bubble_coral
+ minecraft:fire_coral
+ minecraft:horn_coral
```

</details>

<details><summary>items/coral.json</summary>

```diff
- minecraft:blue_dead_coral
- minecraft:pink_dead_coral
- minecraft:purple_dead_coral
- minecraft:red_dead_coral
- minecraft:yellow_dead_coral
- minecraft:blue_coral
- minecraft:pink_coral
- minecraft:purple_coral
- minecraft:red_coral
- minecraft:yellow_coral
+ minecraft:dead_tube_coral_block
+ minecraft:dead_brain_coral_block
+ minecraft:dead_bubble_coral_block
+ minecraft:dead_fire_coral_block
+ minecraft:dead_horn_coral_block
+ #minecraft:live_coral
```

</details>

<details><summary>items/coral_plants.json</summary>

```diff
- minecraft:blue_coral_plant
- minecraft:pink_coral_plant
- minecraft:purple_coral_plant
- minecraft:red_coral_plant
- minecraft:yellow_coral_plant
+ minecraft:tube_coral
+ minecraft:brain_coral
+ minecraft:bubble_coral
+ minecraft:fire_coral
+ minecraft:horn_coral
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/misc/cactus_green.json
+ recipes/misc/lime_dye_from_smelting.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
+ cactus_green.json
+ lime_dye_from_smelting.json
```

</details>

<details><summary>tags.txt</summary>

```diff
+ blocks/live_coral.json
+ items/live_coral.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- blocks/blue_coral.png
- blocks/blue_coral_fan.png
- blocks/blue_coral_plant.png
- blocks/blue_dead_coral.png
- blocks/pink_coral.png
- blocks/pink_coral_fan.png
- blocks/pink_coral_plant.png
- blocks/pink_dead_coral.png
- blocks/purple_coral.png
- blocks/purple_coral_fan.png
- blocks/purple_coral_plant.png
- blocks/purple_dead_coral.png
- blocks/red_coral.png
- blocks/red_coral_fan.png
- blocks/red_coral_plant.png
- blocks/red_dead_coral.png
- blocks/yellow_coral.png
- blocks/yellow_coral_fan.png
- blocks/yellow_coral_plant.png
- blocks/yellow_dead_coral.png
+ blocks/brain_coral.png
+ blocks/brain_coral_block.png
+ blocks/brain_coral_fan.png
+ blocks/bubble_coral.png
+ blocks/bubble_coral_block.png
+ blocks/bubble_coral_fan.png
+ blocks/dead_brain_coral_block.png
+ blocks/dead_bubble_coral_block.png
+ blocks/dead_fire_coral_block.png
+ blocks/dead_horn_coral_block.png
+ blocks/dead_tube_coral_block.png
+ blocks/fire_coral.png
+ blocks/fire_coral_block.png
+ blocks/fire_coral_fan.png
+ blocks/horn_coral.png
+ blocks/horn_coral_block.png
+ blocks/horn_coral_fan.png
+ blocks/sea_pickle.png
+ blocks/tube_coral.png
+ blocks/tube_coral_block.png
+ blocks/tube_coral_fan.png
+ items/sea_pickle.png
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