<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w46a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w46a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-11-15T13:43:14+00:00</td></tr>
<tr><th>SHA1</th><td>1b24c105bfb11d85b4f8cb946c89f762cf099aa2</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/1b24c105bfb11d85b4f8cb946c89f762cf099aa2/18w46a.json">https://piston-meta.mojang.com/v1/packages/1b24c105bfb11d85b4f8cb946c89f762cf099aa2/18w46a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/6681e24d2dc9ba60a6e7d1fbbf25b2af70ff9d1c/server.jar">https://piston-data.mojang.com/v1/objects/6681e24d2dc9ba60a6e7d1fbbf25b2af70ff9d1c/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/342ece78f131c72c4669c9aa27a7be542b911171/client.jar">https://piston-data.mojang.com/v1/objects/342ece78f131c72c4669c9aa27a7be542b911171/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w45a">18w45a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/decorations/lantern.json
+  minecraft/loot_tables/blocks/lantern.json
+  minecraft/loot_tables/entities/illusioner.json
+  minecraft/loot_tables/entities/mooshroom.json
-  minecraft/loot_tables/entities/mushroom_cow.json
+  minecraft/loot_tables/entities/pillager.json
+  minecraft/recipes/lantern.json
+  minecraft/tags/blocks/fences.json
+  minecraft/tags/items/fences.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/jigsaw.json
+  minecraft/blockstates/lantern.json
+  minecraft/models/block/hanging_lantern.json
+  minecraft/models/block/jigsaw.json
+  minecraft/models/block/lantern.json
+  minecraft/models/item/jigsaw.json
+  minecraft/models/item/lantern.json
-  minecraft/textures/block/cartography_table_front.png
-  minecraft/textures/block/cartography_table_side.png
+  minecraft/textures/block/cartography_table_side1.png
+  minecraft/textures/block/cartography_table_side2.png
+  minecraft/textures/block/cartography_table_side3.png
+  minecraft/textures/block/jigsaw_bottom.png
+  minecraft/textures/block/jigsaw_side.png
+  minecraft/textures/block/jigsaw_top.png
+  minecraft/textures/block/lantern.png
+  minecraft/textures/block/lantern.png.mcmeta
+  minecraft/textures/block/smithing_table_bottom.png
+  minecraft/textures/block/stonecutter_saw.png.mcmeta
+  minecraft/textures/item/lantern.png
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/fences.json
+ items/fences.json
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/decorations/lantern.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
- entities/mushroom_cow.json
+ blocks/lantern.json
+ entities/illusioner.json
+ entities/mooshroom.json
+ entities/pillager.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
+ lantern.json
```

</details>

<details><summary>tags.txt</summary>

```diff
+ blocks/fences.json
+ items/fences.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- block/cartography_table_front.png
- block/cartography_table_side.png
+ block/cartography_table_side1.png
+ block/cartography_table_side2.png
+ block/cartography_table_side3.png
+ block/jigsaw_bottom.png
+ block/jigsaw_side.png
+ block/jigsaw_top.png
+ block/lantern.png
+ block/smithing_table_bottom.png
+ item/lantern.png
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