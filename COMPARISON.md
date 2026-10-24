## Comparison with [26.4-snapshot-4](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.4-snapshot-4)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [Packets](#packets)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.4-snapshot-4</th><th>26.4-snapshot-5</th></tr><tr><td>DataPack version</td><td><pre>124.0</pre></td><td><pre>125.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>100.1</pre></td><td><pre>100.2</pre></td></tr><tr><td>World version</td><td><pre>5124</pre></td><td><pre>5125</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742166</pre></td><td><pre>1073742167</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.4-snapshot-4</th><th>26.4-snapshot-5</th></tr><tr><td>com.mojang:authlib</td><td><pre>11.0.80</pre></td><td><pre>12.0.81</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
+ minecraft:chiseled_packed_ice
+ minecraft:packed_ice_brick_slab
+ minecraft:packed_ice_brick_stairs
+ minecraft:packed_ice_brick_wall
+ minecraft:packed_ice_bricks
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:chiseled_packed_ice
+ minecraft:packed_ice_brick_slab
+ minecraft:packed_ice_brick_stairs
+ minecraft:packed_ice_brick_wall
+ minecraft:packed_ice_bricks
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.ice.ambient
```

</details>
<details>
<summary>
worldgen/density_function_type
</summary>

```diff
- minecraft:interpolated
+ minecraft:upscale
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:chiseled_packed_ice
+ minecraft:packed_ice_brick_slab
+ minecraft:packed_ice_brick_stairs
+ minecraft:packed_ice_brick_wall
+ minecraft:packed_ice_bricks
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:chiseled_packed_ice
+ minecraft:packed_ice_brick_slab
+ minecraft:packed_ice_brick_stairs
+ minecraft:packed_ice_brick_wall
+ minecraft:packed_ice_bricks
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:chiseled_packed_ice
+ minecraft:packed_ice_brick_slab
+ minecraft:packed_ice_brick_stairs
+ minecraft:packed_ice_brick_wall
+ minecraft:packed_ice_bricks
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.ice.ambient
```

</details>
<details>
<summary>
universal_tags/worldgen/density_function_type.json
</summary>

```diff
- minecraft:interpolated
+ minecraft:upscale
```

</details>
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ chiseled_packed_ice.json
+ packed_ice_brick_slab.json
+ packed_ice_brick_stairs.json
+ packed_ice_brick_wall.json
+ packed_ice_bricks.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ chiseled_packed_ice_from_packed_ice_bricks_stonecutting.json
+ chiseled_packed_ice_from_packed_ice_stonecutting.json
+ chiseled_packed_ice.json
+ packed_ice_brick_slab_from_packed_ice_bricks_stonecutting.json
+ packed_ice_brick_slab_from_packed_ice_stonecutting.json
+ packed_ice_brick_slab.json
+ packed_ice_brick_stairs_from_packed_ice_bricks_stonecutting.json
+ packed_ice_brick_stairs_from_packed_ice_stonecutting.json
+ packed_ice_brick_stairs.json
+ packed_ice_brick_wall_from_packed_ice_bricks_stonecutting.json
+ packed_ice_brick_wall_from_packed_ice_stonecutting.json
+ packed_ice_brick_wall.json
+ packed_ice_bricks_from_packed_ice_stonecutting.json
+ packed_ice_bricks.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.adventure.what_goes_around_comes_around.description: Kill a Frostbite using an Ice Ball
+ advancements.adventure.what_goes_around_comes_around.title: What Goes Around Comes Around
+ block.minecraft.chiseled_packed_ice: Chiseled Packed Ice
+ block.minecraft.packed_ice_brick_slab: Packed Ice Brick Slab
+ block.minecraft.packed_ice_brick_stairs: Packed Ice Brick Stairs
+ block.minecraft.packed_ice_brick_wall: Packed Ice Brick Wall
+ block.minecraft.packed_ice_bricks: Packed Ice Bricks
+ options.preferDXGIPresent.experimental: Prefer DXGI Present
+ options.preferDXGIPresent.tooltip.experimental: Experimental. Attempts to use DirectX to present the game, which may improve compatibility with some IMEs and better support variable refresh rates.
+ subtitles.block.ice.ambient: Ice resonates
```

</details>
</details>
<hr/>
<details><summary><b><ins>PACKETS</ins></b><a name="packets"></a></summary>
<br/>
<details>
<summary>
[client] login
</summary>

```diff
+ minecraft:apply_options
- minecraft:hello
+ minecraft:key
- minecraft:login_compression
+ minecraft:setup_compression
```

</details>
<details>
<summary>
[server] login
</summary>

```diff
+ minecraft:options_applied
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
generated
</summary>

```diff
+ reports/minecraft/components/item/chiseled_packed_ice.json
+ reports/minecraft/components/item/packed_ice_brick_slab.json
+ reports/minecraft/components/item/packed_ice_brick_stairs.json
+ reports/minecraft/components/item/packed_ice_brick_wall.json
+ reports/minecraft/components/item/packed_ice_bricks.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/adventure/what_goes_around_comes_around.json
+ minecraft/advancement/recipes/building_blocks/chiseled_packed_ice_from_packed_ice_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/chiseled_packed_ice_from_packed_ice_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/chiseled_packed_ice.json
+ minecraft/advancement/recipes/building_blocks/packed_ice_brick_slab_from_packed_ice_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/packed_ice_brick_slab_from_packed_ice_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/packed_ice_brick_slab.json
+ minecraft/advancement/recipes/building_blocks/packed_ice_brick_stairs_from_packed_ice_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/packed_ice_brick_stairs_from_packed_ice_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/packed_ice_brick_stairs.json
+ minecraft/advancement/recipes/building_blocks/packed_ice_bricks_from_packed_ice_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/packed_ice_bricks.json
+ minecraft/advancement/recipes/decorations/packed_ice_brick_wall_from_packed_ice_bricks_stonecutting.json
+ minecraft/advancement/recipes/decorations/packed_ice_brick_wall_from_packed_ice_stonecutting.json
+ minecraft/advancement/recipes/decorations/packed_ice_brick_wall.json
+ minecraft/loot_table/blocks/chiseled_packed_ice.json
+ minecraft/loot_table/blocks/packed_ice_brick_slab.json
+ minecraft/loot_table/blocks/packed_ice_brick_stairs.json
+ minecraft/loot_table/blocks/packed_ice_brick_wall.json
+ minecraft/loot_table/blocks/packed_ice_bricks.json
+ minecraft/recipe/chiseled_packed_ice_from_packed_ice_bricks_stonecutting.json
+ minecraft/recipe/chiseled_packed_ice_from_packed_ice_stonecutting.json
+ minecraft/recipe/chiseled_packed_ice.json
+ minecraft/recipe/packed_ice_brick_slab_from_packed_ice_bricks_stonecutting.json
+ minecraft/recipe/packed_ice_brick_slab_from_packed_ice_stonecutting.json
+ minecraft/recipe/packed_ice_brick_slab.json
+ minecraft/recipe/packed_ice_brick_stairs_from_packed_ice_bricks_stonecutting.json
+ minecraft/recipe/packed_ice_brick_stairs_from_packed_ice_stonecutting.json
+ minecraft/recipe/packed_ice_brick_stairs.json
+ minecraft/recipe/packed_ice_brick_wall_from_packed_ice_bricks_stonecutting.json
+ minecraft/recipe/packed_ice_brick_wall_from_packed_ice_stonecutting.json
+ minecraft/recipe/packed_ice_brick_wall.json
+ minecraft/recipe/packed_ice_bricks_from_packed_ice_stonecutting.json
+ minecraft/recipe/packed_ice_bricks.json
- minecraft/tags/entity_type/freeze_immune_entity_types.json
- minecraft/tags/entity_type/ignores_poison_and_regen.json
+ minecraft/tags/entity_type/immune_to_freezing.json
+ minecraft/tags/entity_type/immune_to_poison.json
+ minecraft/tags/entity_type/immune_to_regeneration.json
+ minecraft/tags/entity_type/immune_to_weakness.json
+ minecraft/tags/entity_type/immune_to_wither.json
+ minecraft/tags/worldgen/biome/spawns_cold_variants_underground.json
- minecraft/tags/worldgen/biome/spawns_strays_without_powder_snow.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/chiseled_packed_ice.json
+ minecraft/blockstates/packed_ice_brick_slab.json
+ minecraft/blockstates/packed_ice_brick_stairs.json
+ minecraft/blockstates/packed_ice_brick_wall.json
+ minecraft/blockstates/packed_ice_bricks.json
+ minecraft/items/chiseled_packed_ice.json
+ minecraft/items/packed_ice_brick_slab.json
+ minecraft/items/packed_ice_brick_stairs.json
+ minecraft/items/packed_ice_brick_wall.json
+ minecraft/items/packed_ice_bricks.json
+ minecraft/models/block/chiseled_packed_ice.json
- minecraft/models/block/icicle_base.json
- minecraft/models/block/icicle.json
+ minecraft/models/block/packed_ice_brick_slab_top.json
+ minecraft/models/block/packed_ice_brick_slab.json
+ minecraft/models/block/packed_ice_brick_stairs_inner.json
+ minecraft/models/block/packed_ice_brick_stairs_outer.json
+ minecraft/models/block/packed_ice_brick_stairs.json
+ minecraft/models/block/packed_ice_brick_wall_inventory.json
+ minecraft/models/block/packed_ice_brick_wall_post.json
+ minecraft/models/block/packed_ice_brick_wall_side_tall.json
+ minecraft/models/block/packed_ice_brick_wall_side.json
+ minecraft/models/block/packed_ice_bricks.json
+ minecraft/models/block/template_icicle_base.json
+ minecraft/models/block/template_icicle.json
+ minecraft/textures/block/chiseled_packed_ice.png
+ minecraft/textures/block/packed_ice_bricks.png
```

</details>
</details>
<hr/>