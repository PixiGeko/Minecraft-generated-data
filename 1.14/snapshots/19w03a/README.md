<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w03a ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w03a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-01-16T16:45:02+00:00</td></tr>
<tr><th>SHA1</th><td>e10947fbb39e5d58fb42000348be423e8c0cad64</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/e10947fbb39e5d58fb42000348be423e8c0cad64/19w03a.json">https://piston-meta.mojang.com/v1/packages/e10947fbb39e5d58fb42000348be423e8c0cad64/19w03a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/1e80738a5360887bc93a46bdffb07699a45bf5a1/server.jar">https://piston-data.mojang.com/v1/objects/1e80738a5360887bc93a46bdffb07699a45bf5a1/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/7280ee42cce1c0371c96c95c22170d3aea7068bb/client.jar">https://piston-data.mojang.com/v1/objects/7280ee42cce1c0371c96c95c22170d3aea7068bb/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w02a">19w02a</a>

# Folder structure

<details><summary>data/</summary>

```diff
+ minecraft/advancements/recipes/food/baked_potato_from_campfire_cooking.json
- minecraft/advancements/recipes/food/baked_potato_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_beef_from_campfire_cooking.json
- minecraft/advancements/recipes/food/cooked_beef_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_chicken_from_campfire_cooking.json
- minecraft/advancements/recipes/food/cooked_chicken_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_cod_from_campfire_cooking.json
- minecraft/advancements/recipes/food/cooked_cod_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_mutton_from_campfire_cooking.json
- minecraft/advancements/recipes/food/cooked_mutton_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_porkchop_from_campfire_cooking.json
- minecraft/advancements/recipes/food/cooked_porkchop_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_rabbit_from_campfire_cooking.json
- minecraft/advancements/recipes/food/cooked_rabbit_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_salmon_from_campfire_cooking.json
- minecraft/advancements/recipes/food/cooked_salmon_from_campfire.json
+ minecraft/advancements/recipes/food/dried_kelp_from_campfire_cooking.json
- minecraft/advancements/recipes/food/dried_kelp_from_campfire.json
+ minecraft/advancements/recipes/misc/composter.json
+ minecraft/loot_tables/blocks/composter.json
+ minecraft/recipes/baked_potato_from_campfire_cooking.json
- minecraft/recipes/baked_potato_from_campfire.json
+ minecraft/recipes/composter.json
+ minecraft/recipes/cooked_beef_from_campfire_cooking.json
- minecraft/recipes/cooked_beef_from_campfire.json
+ minecraft/recipes/cooked_chicken_from_campfire_cooking.json
- minecraft/recipes/cooked_chicken_from_campfire.json
+ minecraft/recipes/cooked_cod_from_campfire_cooking.json
- minecraft/recipes/cooked_cod_from_campfire.json
+ minecraft/recipes/cooked_mutton_from_campfire_cooking.json
- minecraft/recipes/cooked_mutton_from_campfire.json
+ minecraft/recipes/cooked_porkchop_from_campfire_cooking.json
- minecraft/recipes/cooked_porkchop_from_campfire.json
+ minecraft/recipes/cooked_rabbit_from_campfire_cooking.json
- minecraft/recipes/cooked_rabbit_from_campfire.json
+ minecraft/recipes/cooked_salmon_from_campfire_cooking.json
- minecraft/recipes/cooked_salmon_from_campfire.json
+ minecraft/recipes/dried_kelp_from_campfire_cooking.json
- minecraft/recipes/dried_kelp_from_campfire.json
+ minecraft/tags/blocks/wooden_fences.json
+ minecraft/tags/items/wooden_fences.json
```

</details>


<details><summary>assets/</summary>

```diff
+ minecraft/blockstates/composter.json
+ minecraft/models/block/campfire_off.json
- minecraft/models/block/campfire_on.json
+ minecraft/models/block/composter_contents_ready.json
+ minecraft/models/block/composter_contents1.json
+ minecraft/models/block/composter_contents2.json
+ minecraft/models/block/composter_contents3.json
+ minecraft/models/block/composter_contents4.json
+ minecraft/models/block/composter_contents5.json
+ minecraft/models/block/composter_contents6.json
+ minecraft/models/block/composter_contents7.json
+ minecraft/models/block/composter.json
+ minecraft/models/item/composter.json
+ minecraft/textures/block/campfire_log_lit.png
+ minecraft/textures/block/campfire_log_lit.png.mcmeta
+ minecraft/textures/block/campfire_log.png
- minecraft/textures/block/campfire_side.png
- minecraft/textures/block/campfire_top_on.png
- minecraft/textures/block/campfire_top_on.png.mcmeta
- minecraft/textures/block/campfire_top.png
+ minecraft/textures/block/composter_bottom.png
+ minecraft/textures/block/composter_compost.png
+ minecraft/textures/block/composter_ready.png
+ minecraft/textures/block/composter_side.png
+ minecraft/textures/block/composter_top.png
+ minecraft/textures/item/campfire.png
```

</details>


# Registries

<details><summary>List</summary>

```diff
+ recipe_serializer.txt
+ recipe_type.txt
```

</details>


<details><summary>block.txt</summary>

```diff
+ minecraft:composter
```

</details>


<details><summary>item.txt</summary>

```diff
+ minecraft:composter
```

</details>


<details><summary>sound_event.txt</summary>

```diff
+ minecraft:block.barrel.close
+ minecraft:block.barrel.open
+ minecraft:block.blastfurnace.fire_crackle
+ minecraft:block.composter.empty
+ minecraft:block.composter.fill
+ minecraft:block.composter.fill_success
+ minecraft:block.composter.ready
+ minecraft:block.crop.break
+ minecraft:block.nether_wart.break
+ minecraft:block.smoker.smoke
+ minecraft:block.sweet_berry_bush.break
+ minecraft:block.sweet_berry_bush.place
+ minecraft:entity.player.hurt_sweet_berry_bush
+ minecraft:item.crop.plant
+ minecraft:item.nether_wart.plant
+ minecraft:item.sweet_berries.pick_from_bush
```

</details>


# Tags

<details><summary>List</summary>

```diff
+ blocks/wooden_fences.json
+ items/wooden_fences.json
```

</details>


<details><summary>blocks/fences.json</summary>

```diff
+ #minecraft:wooden_fences
- minecraft:acacia_fence
- minecraft:birch_fence
- minecraft:dark_oak_fence
- minecraft:jungle_fence
- minecraft:oak_fence
- minecraft:spruce_fence
```

</details>


<details><summary>items/fences.json</summary>

```diff
+ #minecraft:wooden_fences
- minecraft:acacia_fence
- minecraft:birch_fence
- minecraft:dark_oak_fence
- minecraft:jungle_fence
- minecraft:oak_fence
- minecraft:spruce_fence
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ block.minecraft.composter
+ subtitles.block.barrel.close
+ subtitles.block.barrel.open
+ subtitles.block.blastfurnace.fire_crackle
+ subtitles.block.smoker.smoke
+ subtitles.item.berries.pick
+ subtitles.item.crop.plant
+ subtitles.item.nether_wart.plant
```

</details>


# Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/food/baked_potato_from_campfire_cooking.json
- recipes/food/baked_potato_from_campfire.json
+ recipes/food/cooked_beef_from_campfire_cooking.json
- recipes/food/cooked_beef_from_campfire.json
+ recipes/food/cooked_chicken_from_campfire_cooking.json
- recipes/food/cooked_chicken_from_campfire.json
+ recipes/food/cooked_cod_from_campfire_cooking.json
- recipes/food/cooked_cod_from_campfire.json
+ recipes/food/cooked_mutton_from_campfire_cooking.json
- recipes/food/cooked_mutton_from_campfire.json
+ recipes/food/cooked_porkchop_from_campfire_cooking.json
- recipes/food/cooked_porkchop_from_campfire.json
+ recipes/food/cooked_rabbit_from_campfire_cooking.json
- recipes/food/cooked_rabbit_from_campfire.json
+ recipes/food/cooked_salmon_from_campfire_cooking.json
- recipes/food/cooked_salmon_from_campfire.json
+ recipes/food/dried_kelp_from_campfire_cooking.json
- recipes/food/dried_kelp_from_campfire.json
+ recipes/misc/composter.json
```

</details>


<details><summary>loot_tables.txt</summary>

```diff
+ blocks/composter.json
```

</details>


<details><summary>recipes.txt</summary>

```diff
+ baked_potato_from_campfire_cooking.json
- baked_potato_from_campfire.json
+ composter.json
+ cooked_beef_from_campfire_cooking.json
- cooked_beef_from_campfire.json
+ cooked_chicken_from_campfire_cooking.json
- cooked_chicken_from_campfire.json
+ cooked_cod_from_campfire_cooking.json
- cooked_cod_from_campfire.json
+ cooked_mutton_from_campfire_cooking.json
- cooked_mutton_from_campfire.json
+ cooked_porkchop_from_campfire_cooking.json
- cooked_porkchop_from_campfire.json
+ cooked_rabbit_from_campfire_cooking.json
- cooked_rabbit_from_campfire.json
+ cooked_salmon_from_campfire_cooking.json
- cooked_salmon_from_campfire.json
+ dried_kelp_from_campfire_cooking.json
- dried_kelp_from_campfire.json
```

</details>


<details><summary>tags.txt</summary>

```diff
+ blocks/wooden_fences.json
+ items/wooden_fences.json
```

</details>


<details><summary>textures.txt</summary>

```diff
+ block/campfire_log_lit.png
+ block/campfire_log.png
- block/campfire_side.png
- block/campfire_top_on.png
- block/campfire_top.png
+ block/composter_bottom.png
+ block/composter_compost.png
+ block/composter_ready.png
+ block/composter_side.png
+ block/composter_top.png
+ item/campfire.png
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:realms:1.14.0
+ com.mojang:realms:1.14.1
```

</details>
