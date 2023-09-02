<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w10b ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w10b</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-03-07T15:56:01+00:00</td></tr>
<tr><th>SHA1</th><td>316ed74ddf2fa0ae65adb2a170ed5aacdada4d51</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/316ed74ddf2fa0ae65adb2a170ed5aacdada4d51/18w10b.json">https://piston-meta.mojang.com/v1/packages/316ed74ddf2fa0ae65adb2a170ed5aacdada4d51/18w10b.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/b45d7194b91327c8fd2c1d0d5a738b80c9600562/server.jar">https://piston-data.mojang.com/v1/objects/b45d7194b91327c8fd2c1d0d5a738b80c9600562/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/383e0396f585fcc5a487f04fcb77a9743a0e44c3/client.jar">https://piston-data.mojang.com/v1/objects/383e0396f585fcc5a487f04fcb77a9743a0e44c3/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w10a">18w10a</a>
## File structure

<details><summary>data/</summary>

```diff
-  minecraft/advancements/recipes/decorations/purple_shulker_box.json
+  minecraft/advancements/recipes/decorations/shulker_box.json
-  minecraft/recipes/purple_shulker_box.json
+  minecraft/recipes/shulker_box.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/blue_dead_coral.json
-  minecraft/blockstates/dead_coral.json
+  minecraft/blockstates/pink_dead_coral.json
+  minecraft/blockstates/purple_dead_coral.json
+  minecraft/blockstates/red_dead_coral.json
+  minecraft/blockstates/yellow_dead_coral.json
+  minecraft/models/block/blue_dead_coral.json
-  minecraft/models/block/dead_coral.json
+  minecraft/models/block/pink_dead_coral.json
+  minecraft/models/block/purple_dead_coral.json
+  minecraft/models/block/red_dead_coral.json
+  minecraft/models/block/yellow_dead_coral.json
+  minecraft/models/item/blue_dead_coral.json
-  minecraft/models/item/dead_coral.json
+  minecraft/models/item/pink_dead_coral.json
+  minecraft/models/item/purple_dead_coral.json
+  minecraft/models/item/red_dead_coral.json
+  minecraft/models/item/shulker_box.json
+  minecraft/models/item/yellow_dead_coral.json
+  minecraft/textures/blocks/blue_dead_coral.png
-  minecraft/textures/blocks/dead_coral.png
+  minecraft/textures/blocks/pink_dead_coral.png
+  minecraft/textures/blocks/purple_dead_coral.png
+  minecraft/textures/blocks/red_dead_coral.png
+  minecraft/textures/blocks/shulker_top.png
+  minecraft/textures/blocks/yellow_dead_coral.png
+  minecraft/textures/entity/shulker/shulker.png
```

</details>

## Tags

<details><summary>blocks/coral.json</summary>

```diff
- minecraft:dead_coral
+ minecraft:blue_dead_coral
+ minecraft:pink_dead_coral
+ minecraft:purple_dead_coral
+ minecraft:red_dead_coral
+ minecraft:yellow_dead_coral
```

</details>

<details><summary>items/coral.json</summary>

```diff
- minecraft:dead_coral
+ minecraft:blue_dead_coral
+ minecraft:pink_dead_coral
+ minecraft:purple_dead_coral
+ minecraft:red_dead_coral
+ minecraft:yellow_dead_coral
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
- recipes/decorations/purple_shulker_box.json
+ recipes/decorations/shulker_box.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
- purple_shulker_box.json
+ shulker_box.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- blocks/dead_coral.png
+ blocks/blue_dead_coral.png
+ blocks/pink_dead_coral.png
+ blocks/purple_dead_coral.png
+ blocks/red_dead_coral.png
+ blocks/shulker_top.png
+ blocks/yellow_dead_coral.png
+ entity/shulker/shulker.png
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