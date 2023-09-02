<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w10a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w10a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-03-06T15:54:24+00:00</td></tr>
<tr><th>SHA1</th><td>fac132e97632d4beff518e7f3f8224c07f9239de</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/fac132e97632d4beff518e7f3f8224c07f9239de/18w10a.json">https://piston-meta.mojang.com/v1/packages/fac132e97632d4beff518e7f3f8224c07f9239de/18w10a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/7bb1cfb4560d2e99551b22a631b6087d43817a45/server.jar">https://piston-data.mojang.com/v1/objects/7bb1cfb4560d2e99551b22a631b6087d43817a45/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/fb24610e6fca6f83e8b45e3a46224601d4ca6c27/client.jar">https://piston-data.mojang.com/v1/objects/fb24610e6fca6f83e8b45e3a46224601d4ca6c27/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w09a">18w09a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/loot_tables/chests/buried_treasure.json
+  minecraft/loot_tables/entities/tropical_fish.json
+  minecraft/tags/blocks/coral_plants.json
+  minecraft/tags/items/coral_plants.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/blue_coral_plant.json
+  minecraft/blockstates/pink_coral_plant.json
+  minecraft/blockstates/purple_coral_plant.json
+  minecraft/blockstates/red_coral_plant.json
+  minecraft/blockstates/yellow_coral_plant.json
+  minecraft/models/block/blue_coral_plant.json
+  minecraft/models/block/pink_coral_plant.json
+  minecraft/models/block/purple_coral_plant.json
+  minecraft/models/block/red_coral_plant.json
+  minecraft/models/block/yellow_coral_plant.json
+  minecraft/models/item/blue_coral_plant.json
+  minecraft/models/item/clownfish_bucket.json
+  minecraft/models/item/pink_coral_plant.json
+  minecraft/models/item/purple_coral_plant.json
+  minecraft/models/item/red_coral_plant.json
+  minecraft/models/item/trident_in_hand.json
+  minecraft/models/item/tropical_fish_spawn_egg.json
+  minecraft/models/item/yellow_coral_plant.json
+  minecraft/textures/blocks/blue_coral_plant.png
+  minecraft/textures/blocks/pink_coral_plant.png
+  minecraft/textures/blocks/purple_coral_plant.png
+  minecraft/textures/blocks/red_coral_plant.png
+  minecraft/textures/blocks/yellow_coral_plant.png
+  minecraft/textures/entity/fish/tropical_a.png
+  minecraft/textures/entity/fish/tropical_a_pattern_1.png
+  minecraft/textures/entity/fish/tropical_a_pattern_2.png
+  minecraft/textures/entity/fish/tropical_a_pattern_3.png
+  minecraft/textures/entity/fish/tropical_a_pattern_4.png
+  minecraft/textures/entity/fish/tropical_a_pattern_5.png
+  minecraft/textures/entity/fish/tropical_a_pattern_6.png
+  minecraft/textures/entity/fish/tropical_b.png
+  minecraft/textures/entity/fish/tropical_b_pattern_1.png
+  minecraft/textures/entity/fish/tropical_b_pattern_2.png
+  minecraft/textures/entity/fish/tropical_b_pattern_3.png
+  minecraft/textures/entity/fish/tropical_b_pattern_4.png
+  minecraft/textures/entity/fish/tropical_b_pattern_5.png
+  minecraft/textures/entity/fish/tropical_b_pattern_6.png
+  minecraft/textures/entity/phantom_eyes.png
+  minecraft/textures/items/trident.png
```

</details>

## Commands

<details><summary>locate.txt</summary>

```diff
+ locate Buried_Treasure
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/coral_plants.json
+ items/coral_plants.json
```

</details>

<details><summary>blocks/waterlogged.json</summary>

```diff
+ #minecraft:coral_plants
```

</details>

## Misc

<details><summary>loot_tables.txt</summary>

```diff
+ chests/buried_treasure.json
+ entities/tropical_fish.json
```

</details>

<details><summary>tags.txt</summary>

```diff
+ blocks/coral_plants.json
+ items/coral_plants.json
```

</details>

<details><summary>textures.txt</summary>

```diff
+ blocks/blue_coral_plant.png
+ blocks/pink_coral_plant.png
+ blocks/purple_coral_plant.png
+ blocks/red_coral_plant.png
+ blocks/yellow_coral_plant.png
+ entity/fish/tropical_a.png
+ entity/fish/tropical_a_pattern_1.png
+ entity/fish/tropical_a_pattern_2.png
+ entity/fish/tropical_a_pattern_3.png
+ entity/fish/tropical_a_pattern_4.png
+ entity/fish/tropical_a_pattern_5.png
+ entity/fish/tropical_a_pattern_6.png
+ entity/fish/tropical_b.png
+ entity/fish/tropical_b_pattern_1.png
+ entity/fish/tropical_b_pattern_2.png
+ entity/fish/tropical_b_pattern_3.png
+ entity/fish/tropical_b_pattern_4.png
+ entity/fish/tropical_b_pattern_5.png
+ entity/fish/tropical_b_pattern_6.png
+ entity/phantom_eyes.png
+ items/trident.png
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