<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w07b ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w07b</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-02-15T14:28:42+00:00</td></tr>
<tr><th>SHA1</th><td>dea62b145246671ae46ed157e6ef2cd2de485a1e</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/dea62b145246671ae46ed157e6ef2cd2de485a1e/18w07b.json">https://piston-meta.mojang.com/v1/packages/dea62b145246671ae46ed157e6ef2cd2de485a1e/18w07b.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/669811c0df3fedef8a15f1b31c96df966b9aee79/server.jar">https://piston-data.mojang.com/v1/objects/669811c0df3fedef8a15f1b31c96df966b9aee79/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/e1aeafe25aa454e35e53bd489523bed51aa5e826/client.jar">https://piston-data.mojang.com/v1/objects/e1aeafe25aa454e35e53bd489523bed51aa5e826/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w07a">18w07a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/tags/blocks/rails.json
+  minecraft/tags/blocks/sand.json
+  minecraft/tags/blocks/waterlogged.json
+  minecraft/tags/items/anvil.json
+  minecraft/tags/items/rails.json
+  minecraft/tags/items/sand.json
+  minecraft/tags/items/slabs.json
+  minecraft/tags/items/stairs.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/models/item/scute.json
-  minecraft/models/item/turtle_shell_piece.json
+  minecraft/textures/items/scute.png
-  minecraft/textures/items/turtle_shell_piece.png
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/rails.json
+ blocks/sand.json
+ blocks/waterlogged.json
+ items/anvil.json
+ items/rails.json
+ items/sand.json
+ items/slabs.json
+ items/stairs.json
```

</details>

<details><summary>blocks/water_hacked.json</summary>

```diff
- minecraft:bubble_column
- minecraft:kelp
- minecraft:kelp_top
- minecraft:sea_grass
- minecraft:tall_sea_grass
+ #minecraft:waterlogged
```

</details>

## Misc

<details><summary>tags.txt</summary>

```diff
+ blocks/rails.json
+ blocks/sand.json
+ blocks/waterlogged.json
+ items/anvil.json
+ items/rails.json
+ items/sand.json
+ items/slabs.json
+ items/stairs.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- items/turtle_shell_piece.png
+ items/scute.png
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