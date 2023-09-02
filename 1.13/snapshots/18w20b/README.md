<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w20b ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w20b</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-05-16T14:35:35+00:00</td></tr>
<tr><th>SHA1</th><td>566f11647d85194f292d2300fa550631bf75510a</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/566f11647d85194f292d2300fa550631bf75510a/18w20b.json">https://piston-meta.mojang.com/v1/packages/566f11647d85194f292d2300fa550631bf75510a/18w20b.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/35304e17de5fbe503b10bad50192d14a38e5cec0/server.jar">https://piston-data.mojang.com/v1/objects/35304e17de5fbe503b10bad50192d14a38e5cec0/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/91aa79a2aa3c656221defebf5310c1ffacfd81ed/client.jar">https://piston-data.mojang.com/v1/objects/91aa79a2aa3c656221defebf5310c1ffacfd81ed/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w20a">18w20a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/brewing/glistering_melon_slice.json
-  minecraft/advancements/recipes/brewing/speckled_melon.json
+  minecraft/advancements/recipes/building_blocks/melon.json
-  minecraft/advancements/recipes/building_blocks/melon_block.json
+  minecraft/recipes/glistering_melon_slice.json
+  minecraft/recipes/melon.json
-  minecraft/recipes/melon_block.json
-  minecraft/recipes/speckled_melon.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/melon.json
-  minecraft/blockstates/melon_block.json
+  minecraft/models/block/melon.json
-  minecraft/models/block/melon_block.json
+  minecraft/models/item/glistering_melon_slice.json
-  minecraft/models/item/melon_block.json
+  minecraft/models/item/melon_slice.json
-  minecraft/models/item/speckled_melon.json
+  minecraft/textures/entity/conduit/closed_eye.png
-  minecraft/textures/entity/conduit/entity_core.png
+  minecraft/textures/entity/conduit/open_eye.png
+  minecraft/textures/items/glistering_melon_slice.png
-  minecraft/textures/items/melon.png
+  minecraft/textures/items/melon_slice.png
-  minecraft/textures/items/speckled_melon.png
```

</details>

## Tags

<details><summary>blocks/enderman_holdable.json</summary>

```diff
- minecraft:melon_block
+ minecraft:melon
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
- recipes/brewing/speckled_melon.json
- recipes/building_blocks/melon_block.json
+ recipes/brewing/glistering_melon_slice.json
+ recipes/building_blocks/melon.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
- melon_block.json
- speckled_melon.json
+ glistering_melon_slice.json
+ melon.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- entity/conduit/entity_core.png
- items/melon.png
- items/speckled_melon.png
+ entity/conduit/closed_eye.png
+ entity/conduit/open_eye.png
+ items/glistering_melon_slice.png
+ items/melon_slice.png
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