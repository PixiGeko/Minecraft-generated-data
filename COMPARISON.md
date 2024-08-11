## Comparison with [21w07a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w07a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">21w07a</th><th>21w08a</th></tr><tr><td>World version</td><td><code>2695</code></td><td><code>2697</code></td></tr><tr><td>Protocol version</td><td><code>1073741839</code></td><td><code>1073741840</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ worldgen/float_provider_type.txt
```

</details>


<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:chiseled_deepslate
- minecraft:chiseled_grimstone
+ minecraft:cobbled_deepslate
+ minecraft:cobbled_deepslate_slab
+ minecraft:cobbled_deepslate_stairs
+ minecraft:cobbled_deepslate_wall
+ minecraft:deepslate
+ minecraft:deepslate_brick_slab
+ minecraft:deepslate_brick_stairs
+ minecraft:deepslate_brick_wall
+ minecraft:deepslate_bricks
+ minecraft:deepslate_diamond_ore
+ minecraft:deepslate_gold_ore
+ minecraft:deepslate_iron_ore
+ minecraft:deepslate_lapis_ore
+ minecraft:deepslate_redstone_ore
+ minecraft:deepslate_tile_slab
+ minecraft:deepslate_tile_stairs
+ minecraft:deepslate_tile_wall
+ minecraft:deepslate_tiles
- minecraft:grimstone
- minecraft:grimstone_brick_slab
- minecraft:grimstone_brick_stairs
- minecraft:grimstone_brick_wall
- minecraft:grimstone_bricks
- minecraft:grimstone_slab
- minecraft:grimstone_stairs
- minecraft:grimstone_tile_slab
- minecraft:grimstone_tile_stairs
- minecraft:grimstone_tile_wall
- minecraft:grimstone_tiles
- minecraft:grimstone_wall
+ minecraft:polished_deepslate
+ minecraft:polished_deepslate_slab
+ minecraft:polished_deepslate_stairs
+ minecraft:polished_deepslate_wall
- minecraft:polished_grimstone
- minecraft:polished_grimstone_slab
- minecraft:polished_grimstone_stairs
- minecraft:polished_grimstone_wall
+ minecraft:smooth_basalt
```

</details>







<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:chiseled_deepslate
- minecraft:chiseled_grimstone
+ minecraft:cobbled_deepslate
+ minecraft:cobbled_deepslate_slab
+ minecraft:cobbled_deepslate_stairs
+ minecraft:cobbled_deepslate_wall
+ minecraft:deepslate
+ minecraft:deepslate_brick_slab
+ minecraft:deepslate_brick_stairs
+ minecraft:deepslate_brick_wall
+ minecraft:deepslate_bricks
+ minecraft:deepslate_diamond_ore
+ minecraft:deepslate_gold_ore
+ minecraft:deepslate_iron_ore
+ minecraft:deepslate_lapis_ore
+ minecraft:deepslate_redstone_ore
+ minecraft:deepslate_tile_slab
+ minecraft:deepslate_tile_stairs
+ minecraft:deepslate_tile_wall
+ minecraft:deepslate_tiles
- minecraft:grimstone
- minecraft:grimstone_brick_slab
- minecraft:grimstone_brick_stairs
- minecraft:grimstone_brick_wall
- minecraft:grimstone_bricks
- minecraft:grimstone_slab
- minecraft:grimstone_stairs
- minecraft:grimstone_tile_slab
- minecraft:grimstone_tile_stairs
- minecraft:grimstone_tile_wall
- minecraft:grimstone_tiles
- minecraft:grimstone_wall
+ minecraft:polished_deepslate
+ minecraft:polished_deepslate_slab
+ minecraft:polished_deepslate_stairs
+ minecraft:polished_deepslate_wall
- minecraft:polished_grimstone
- minecraft:polished_grimstone_slab
- minecraft:polished_grimstone_stairs
- minecraft:polished_grimstone_wall
+ minecraft:smooth_basalt
```

</details>




















<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.deepslate_bricks.break
+ minecraft:block.deepslate_bricks.fall
+ minecraft:block.deepslate_bricks.hit
+ minecraft:block.deepslate_bricks.place
+ minecraft:block.deepslate_bricks.step
+ minecraft:block.deepslate_tiles.break
+ minecraft:block.deepslate_tiles.fall
+ minecraft:block.deepslate_tiles.hit
+ minecraft:block.deepslate_tiles.place
+ minecraft:block.deepslate_tiles.step
+ minecraft:block.deepslate.break
+ minecraft:block.deepslate.fall
+ minecraft:block.deepslate.hit
+ minecraft:block.deepslate.place
+ minecraft:block.deepslate.step
+ minecraft:block.polished_deepslate.break
+ minecraft:block.polished_deepslate.fall
+ minecraft:block.polished_deepslate.hit
+ minecraft:block.polished_deepslate.place
+ minecraft:block.polished_deepslate.step
```

</details>









<details>
<summary>
worldgen/feature.txt
</summary>

```diff
- minecraft:no_surface_ore
+ minecraft:scattered_ore
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/worldgen/float_provider_type.json
```

</details>

<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:chiseled_deepslate
- minecraft:chiseled_grimstone
+ minecraft:cobbled_deepslate
+ minecraft:cobbled_deepslate_slab
+ minecraft:cobbled_deepslate_stairs
+ minecraft:cobbled_deepslate_wall
+ minecraft:deepslate
+ minecraft:deepslate_brick_slab
+ minecraft:deepslate_brick_stairs
+ minecraft:deepslate_brick_wall
+ minecraft:deepslate_bricks
+ minecraft:deepslate_diamond_ore
+ minecraft:deepslate_gold_ore
+ minecraft:deepslate_iron_ore
+ minecraft:deepslate_lapis_ore
+ minecraft:deepslate_redstone_ore
+ minecraft:deepslate_tile_slab
+ minecraft:deepslate_tile_stairs
+ minecraft:deepslate_tile_wall
+ minecraft:deepslate_tiles
- minecraft:grimstone
- minecraft:grimstone_brick_slab
- minecraft:grimstone_brick_stairs
- minecraft:grimstone_brick_wall
- minecraft:grimstone_bricks
- minecraft:grimstone_slab
- minecraft:grimstone_stairs
- minecraft:grimstone_tile_slab
- minecraft:grimstone_tile_stairs
- minecraft:grimstone_tile_wall
- minecraft:grimstone_tiles
- minecraft:grimstone_wall
+ minecraft:polished_deepslate
+ minecraft:polished_deepslate_slab
+ minecraft:polished_deepslate_stairs
+ minecraft:polished_deepslate_wall
- minecraft:polished_grimstone
- minecraft:polished_grimstone_slab
- minecraft:polished_grimstone_stairs
- minecraft:polished_grimstone_wall
+ minecraft:smooth_basalt
```

</details>






<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:chiseled_deepslate
- minecraft:chiseled_grimstone
+ minecraft:cobbled_deepslate
+ minecraft:cobbled_deepslate_slab
+ minecraft:cobbled_deepslate_stairs
+ minecraft:cobbled_deepslate_wall
+ minecraft:deepslate
+ minecraft:deepslate_brick_slab
+ minecraft:deepslate_brick_stairs
+ minecraft:deepslate_brick_wall
+ minecraft:deepslate_bricks
+ minecraft:deepslate_diamond_ore
+ minecraft:deepslate_gold_ore
+ minecraft:deepslate_iron_ore
+ minecraft:deepslate_lapis_ore
+ minecraft:deepslate_redstone_ore
+ minecraft:deepslate_tile_slab
+ minecraft:deepslate_tile_stairs
+ minecraft:deepslate_tile_wall
+ minecraft:deepslate_tiles
- minecraft:grimstone
- minecraft:grimstone_brick_slab
- minecraft:grimstone_brick_stairs
- minecraft:grimstone_brick_wall
- minecraft:grimstone_bricks
- minecraft:grimstone_slab
- minecraft:grimstone_stairs
- minecraft:grimstone_tile_slab
- minecraft:grimstone_tile_stairs
- minecraft:grimstone_tile_wall
- minecraft:grimstone_tiles
- minecraft:grimstone_wall
+ minecraft:polished_deepslate
+ minecraft:polished_deepslate_slab
+ minecraft:polished_deepslate_stairs
+ minecraft:polished_deepslate_wall
- minecraft:polished_grimstone
- minecraft:polished_grimstone_slab
- minecraft:polished_grimstone_stairs
- minecraft:polished_grimstone_wall
+ minecraft:smooth_basalt
```

</details>







<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:chiseled_deepslate
- minecraft:chiseled_grimstone
+ minecraft:cobbled_deepslate
+ minecraft:cobbled_deepslate_slab
+ minecraft:cobbled_deepslate_stairs
+ minecraft:cobbled_deepslate_wall
+ minecraft:deepslate
+ minecraft:deepslate_brick_slab
+ minecraft:deepslate_brick_stairs
+ minecraft:deepslate_brick_wall
+ minecraft:deepslate_bricks
+ minecraft:deepslate_diamond_ore
+ minecraft:deepslate_gold_ore
+ minecraft:deepslate_iron_ore
+ minecraft:deepslate_lapis_ore
+ minecraft:deepslate_redstone_ore
+ minecraft:deepslate_tile_slab
+ minecraft:deepslate_tile_stairs
+ minecraft:deepslate_tile_wall
+ minecraft:deepslate_tiles
- minecraft:grimstone
- minecraft:grimstone_brick_slab
- minecraft:grimstone_brick_stairs
- minecraft:grimstone_brick_wall
- minecraft:grimstone_bricks
- minecraft:grimstone_slab
- minecraft:grimstone_stairs
- minecraft:grimstone_tile_slab
- minecraft:grimstone_tile_stairs
- minecraft:grimstone_tile_wall
- minecraft:grimstone_tiles
- minecraft:grimstone_wall
+ minecraft:polished_deepslate
+ minecraft:polished_deepslate_slab
+ minecraft:polished_deepslate_stairs
+ minecraft:polished_deepslate_wall
- minecraft:polished_grimstone
- minecraft:polished_grimstone_slab
- minecraft:polished_grimstone_stairs
- minecraft:polished_grimstone_wall
+ minecraft:smooth_basalt
```

</details>




















<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.deepslate_bricks.break
+ minecraft:block.deepslate_bricks.fall
+ minecraft:block.deepslate_bricks.hit
+ minecraft:block.deepslate_bricks.place
+ minecraft:block.deepslate_bricks.step
+ minecraft:block.deepslate_tiles.break
+ minecraft:block.deepslate_tiles.fall
+ minecraft:block.deepslate_tiles.hit
+ minecraft:block.deepslate_tiles.place
+ minecraft:block.deepslate_tiles.step
+ minecraft:block.deepslate.break
+ minecraft:block.deepslate.fall
+ minecraft:block.deepslate.hit
+ minecraft:block.deepslate.place
+ minecraft:block.deepslate.step
+ minecraft:block.polished_deepslate.break
+ minecraft:block.polished_deepslate.fall
+ minecraft:block.polished_deepslate.hit
+ minecraft:block.polished_deepslate.place
+ minecraft:block.polished_deepslate.step
```

</details>









<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:no_surface_ore
+ minecraft:scattered_ore
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ chiseled_deepslate_from_cobbled_deepslate_stonecutting.json
+ chiseled_deepslate.json
- chiseled_grimstone_from_grimstone_stonecutting.json
- chiseled_grimstone.json
+ cobbled_deepslate_slab_from_cobbled_deepslate_stonecutting.json
+ cobbled_deepslate_slab.json
+ cobbled_deepslate_stairs_from_cobbled_deepslate_stonecutting.json
+ cobbled_deepslate_stairs.json
+ cobbled_deepslate_wall_from_cobbled_deepslate_stonecutting.json
+ cobbled_deepslate_wall.json
+ deepslate_brick_slab_from_deepslate_bricks_stonecutting.json
+ deepslate_brick_slab.json
+ deepslate_brick_stairs_from_deepslate_bricks_stonecutting.json
+ deepslate_brick_stairs.json
+ deepslate_brick_wall_from_deepslate_bricks_stonecutting.json
+ deepslate_brick_wall.json
+ deepslate_tile_slab_from_deepslate_tiles_stonecutting.json
+ deepslate_tile_slab.json
+ deepslate_tile_stairs_from_deepslate_tiles_stonecutting.json
+ deepslate_tile_stairs.json
+ deepslate_tile_wall_from_deepslate_tiles_stonecutting.json
+ deepslate_tile_wall.json
- grimstone_brick_slab_from_grimstone_bricks_stonecutting.json
- grimstone_brick_slab.json
- grimstone_brick_stairs_from_grimstone_bricks_stonecutting.json
- grimstone_brick_stairs.json
- grimstone_brick_wall_from_grimstone_bricks_stonecutting.json
- grimstone_brick_wall.json
- grimstone_slab_from_grimstone_stonecutting.json
- grimstone_slab.json
- grimstone_stairs_from_grimstone_stonecutting.json
- grimstone_stairs.json
- grimstone_tile_slab_from_grimstone_tiles_stonecutting.json
- grimstone_tile_slab.json
- grimstone_tile_stairs_from_grimstone_tiles_stonecutting.json
- grimstone_tile_stairs.json
- grimstone_tile_wall_from_grimstone_tiles_stonecutting.json
- grimstone_tile_wall.json
- grimstone_wall_from_grimstone_stonecutting.json
- grimstone_wall.json
+ polished_deepslate_slab_from_polished_deepslate_stonecutting.json
+ polished_deepslate_slab.json
+ polished_deepslate_stairs_from_polished_deepslate_stonecutting.json
+ polished_deepslate_stairs.json
+ polished_deepslate_wall_from_polished_deepslate_stonecutting.json
+ polished_deepslate_wall.json
+ polished_deepslate.json
- polished_grimstone_slab_from_polished_grimstone_stonecutting.json
- polished_grimstone_slab.json
- polished_grimstone_stairs_from_polished_grimstone_stonecutting.json
- polished_grimstone_stairs.json
- polished_grimstone_wall_from_polished_grimstone_stonecutting.json
- polished_grimstone_wall.json
- polished_grimstone.json
+ smooth_basalt.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ block.minecraft.chiseled_deepslate: Chiseled Deepslate
- block.minecraft.chiseled_grimstone: Chiseled Grimstone
+ block.minecraft.cobbled_deepslate_slab: Cobbled Deepslate Slab
+ block.minecraft.cobbled_deepslate_stairs: Cobbled Deepslate Stairs
+ block.minecraft.cobbled_deepslate_wall: Cobbled Deepslate Wall
+ block.minecraft.cobbled_deepslate: Cobbled Deepslate
+ block.minecraft.deepslate_brick_slab: Deepslate Brick Slab
+ block.minecraft.deepslate_brick_stairs: Deepslate Brick Stairs
+ block.minecraft.deepslate_brick_wall: Deepslate Brick Wall
+ block.minecraft.deepslate_bricks: Deepslate Bricks
+ block.minecraft.deepslate_diamond_ore: Deepslate Diamond Ore
+ block.minecraft.deepslate_gold_ore: Deepslate Gold Ore
+ block.minecraft.deepslate_iron_ore: Deepslate Iron Ore
+ block.minecraft.deepslate_lapis_ore: Deepslate Lapis Lazuli Ore
+ block.minecraft.deepslate_redstone_ore: Deepslate Redstone Ore
+ block.minecraft.deepslate_tile_slab: Deepslate Tile Slab
+ block.minecraft.deepslate_tile_stairs: Deepslate Tile Stairs
+ block.minecraft.deepslate_tile_wall: Deepslate Tile Wall
+ block.minecraft.deepslate_tiles: Deepslate Tiles
+ block.minecraft.deepslate: Deepslate
- block.minecraft.grimstone_brick_slab: Grimstone Brick Slab
- block.minecraft.grimstone_brick_stairs: Grimstone Brick Stairs
- block.minecraft.grimstone_brick_wall: Grimstone Brick Wall
- block.minecraft.grimstone_bricks: Grimstone Bricks
- block.minecraft.grimstone_slab: Grimstone Slab
- block.minecraft.grimstone_stairs: Grimstone Stairs
- block.minecraft.grimstone_tile_slab: Grimstone Tile Slab
- block.minecraft.grimstone_tile_stairs: Grimstone Tile Stairs
- block.minecraft.grimstone_tile_wall: Grimstone Tile Wall
- block.minecraft.grimstone_tiles: Grimstone Tiles
- block.minecraft.grimstone_wall: Grimstone Wall
- block.minecraft.grimstone: Grimstone
+ block.minecraft.polished_deepslate_slab: Polished Deepslate Slab
+ block.minecraft.polished_deepslate_stairs: Polished Deepslate Stairs
+ block.minecraft.polished_deepslate_wall: Polished Deepslate Wall
+ block.minecraft.polished_deepslate: Polished Deepslate
- block.minecraft.polished_grimstone_slab: Polished Grimstone Slab
- block.minecraft.polished_grimstone_stairs: Polished Grimstone Stairs
- block.minecraft.polished_grimstone_wall: Polished Grimstone Wall
- block.minecraft.polished_grimstone: Polished Grimstone
+ block.minecraft.smooth_basalt: Smooth Basalt
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/chiseled_deepslate_from_cobbled_deepslate_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/chiseled_deepslate.json
- minecraft/advancements/recipes/building_blocks/chiseled_grimstone_from_grimstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/chiseled_grimstone.json
+ minecraft/advancements/recipes/building_blocks/cobbled_deepslate_slab_from_cobbled_deepslate_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cobbled_deepslate_slab.json
+ minecraft/advancements/recipes/building_blocks/cobbled_deepslate_stairs_from_cobbled_deepslate_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cobbled_deepslate_stairs.json
+ minecraft/advancements/recipes/building_blocks/deepslate_brick_slab_from_deepslate_bricks_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/deepslate_brick_slab.json
+ minecraft/advancements/recipes/building_blocks/deepslate_brick_stairs_from_deepslate_bricks_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/deepslate_brick_stairs.json
+ minecraft/advancements/recipes/building_blocks/deepslate_tile_slab_from_deepslate_tiles_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/deepslate_tile_slab.json
+ minecraft/advancements/recipes/building_blocks/deepslate_tile_stairs_from_deepslate_tiles_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/deepslate_tile_stairs.json
- minecraft/advancements/recipes/building_blocks/grimstone_brick_slab_from_grimstone_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/grimstone_brick_slab.json
- minecraft/advancements/recipes/building_blocks/grimstone_brick_stairs_from_grimstone_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/grimstone_brick_stairs.json
- minecraft/advancements/recipes/building_blocks/grimstone_slab_from_grimstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/grimstone_slab.json
- minecraft/advancements/recipes/building_blocks/grimstone_stairs_from_grimstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/grimstone_stairs.json
- minecraft/advancements/recipes/building_blocks/grimstone_tile_slab_from_grimstone_tiles_stonecutting.json
- minecraft/advancements/recipes/building_blocks/grimstone_tile_slab.json
- minecraft/advancements/recipes/building_blocks/grimstone_tile_stairs_from_grimstone_tiles_stonecutting.json
- minecraft/advancements/recipes/building_blocks/grimstone_tile_stairs.json
+ minecraft/advancements/recipes/building_blocks/polished_deepslate_slab_from_polished_deepslate_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_deepslate_slab.json
+ minecraft/advancements/recipes/building_blocks/polished_deepslate_stairs_from_polished_deepslate_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_deepslate_stairs.json
+ minecraft/advancements/recipes/building_blocks/polished_deepslate.json
- minecraft/advancements/recipes/building_blocks/polished_grimstone_slab_from_polished_grimstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/polished_grimstone_slab.json
- minecraft/advancements/recipes/building_blocks/polished_grimstone_stairs_from_polished_grimstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/polished_grimstone_stairs.json
- minecraft/advancements/recipes/building_blocks/polished_grimstone.json
+ minecraft/advancements/recipes/building_blocks/smooth_basalt.json
+ minecraft/advancements/recipes/decorations/cobbled_deepslate_wall_from_cobbled_deepslate_stonecutting.json
+ minecraft/advancements/recipes/decorations/cobbled_deepslate_wall.json
+ minecraft/advancements/recipes/decorations/deepslate_brick_wall_from_deepslate_bricks_stonecutting.json
+ minecraft/advancements/recipes/decorations/deepslate_brick_wall.json
+ minecraft/advancements/recipes/decorations/deepslate_tile_wall_from_deepslate_tiles_stonecutting.json
+ minecraft/advancements/recipes/decorations/deepslate_tile_wall.json
- minecraft/advancements/recipes/decorations/grimstone_brick_wall_from_grimstone_bricks_stonecutting.json
- minecraft/advancements/recipes/decorations/grimstone_brick_wall.json
- minecraft/advancements/recipes/decorations/grimstone_tile_wall_from_grimstone_tiles_stonecutting.json
- minecraft/advancements/recipes/decorations/grimstone_tile_wall.json
- minecraft/advancements/recipes/decorations/grimstone_wall_from_grimstone_stonecutting.json
- minecraft/advancements/recipes/decorations/grimstone_wall.json
- minecraft/advancements/recipes/decorations/honey_block.json
+ minecraft/advancements/recipes/decorations/polished_deepslate_wall_from_polished_deepslate_stonecutting.json
+ minecraft/advancements/recipes/decorations/polished_deepslate_wall.json
- minecraft/advancements/recipes/decorations/polished_grimstone_wall_from_polished_grimstone_stonecutting.json
- minecraft/advancements/recipes/decorations/polished_grimstone_wall.json
- minecraft/advancements/recipes/decorations/slime_block.json
+ minecraft/advancements/recipes/redstone/honey_block.json
+ minecraft/advancements/recipes/redstone/slime_block.json
+ minecraft/loot_tables/blocks/chiseled_deepslate.json
- minecraft/loot_tables/blocks/chiseled_grimstone.json
+ minecraft/loot_tables/blocks/cobbled_deepslate_slab.json
+ minecraft/loot_tables/blocks/cobbled_deepslate_stairs.json
+ minecraft/loot_tables/blocks/cobbled_deepslate_wall.json
+ minecraft/loot_tables/blocks/cobbled_deepslate.json
+ minecraft/loot_tables/blocks/deepslate_brick_slab.json
+ minecraft/loot_tables/blocks/deepslate_brick_stairs.json
+ minecraft/loot_tables/blocks/deepslate_brick_wall.json
+ minecraft/loot_tables/blocks/deepslate_bricks.json
+ minecraft/loot_tables/blocks/deepslate_diamond_ore.json
+ minecraft/loot_tables/blocks/deepslate_gold_ore.json
+ minecraft/loot_tables/blocks/deepslate_iron_ore.json
+ minecraft/loot_tables/blocks/deepslate_lapis_ore.json
+ minecraft/loot_tables/blocks/deepslate_redstone_ore.json
+ minecraft/loot_tables/blocks/deepslate_tile_slab.json
+ minecraft/loot_tables/blocks/deepslate_tile_stairs.json
+ minecraft/loot_tables/blocks/deepslate_tile_wall.json
+ minecraft/loot_tables/blocks/deepslate_tiles.json
+ minecraft/loot_tables/blocks/deepslate.json
- minecraft/loot_tables/blocks/grimstone_brick_slab.json
- minecraft/loot_tables/blocks/grimstone_brick_stairs.json
- minecraft/loot_tables/blocks/grimstone_brick_wall.json
- minecraft/loot_tables/blocks/grimstone_bricks.json
- minecraft/loot_tables/blocks/grimstone_slab.json
- minecraft/loot_tables/blocks/grimstone_stairs.json
- minecraft/loot_tables/blocks/grimstone_tile_slab.json
- minecraft/loot_tables/blocks/grimstone_tile_stairs.json
- minecraft/loot_tables/blocks/grimstone_tile_wall.json
- minecraft/loot_tables/blocks/grimstone_tiles.json
- minecraft/loot_tables/blocks/grimstone_wall.json
- minecraft/loot_tables/blocks/grimstone.json
+ minecraft/loot_tables/blocks/polished_deepslate_slab.json
+ minecraft/loot_tables/blocks/polished_deepslate_stairs.json
+ minecraft/loot_tables/blocks/polished_deepslate_wall.json
+ minecraft/loot_tables/blocks/polished_deepslate.json
- minecraft/loot_tables/blocks/polished_grimstone_slab.json
- minecraft/loot_tables/blocks/polished_grimstone_stairs.json
- minecraft/loot_tables/blocks/polished_grimstone_wall.json
- minecraft/loot_tables/blocks/polished_grimstone.json
+ minecraft/loot_tables/blocks/smooth_basalt.json
+ minecraft/recipes/chiseled_deepslate_from_cobbled_deepslate_stonecutting.json
+ minecraft/recipes/chiseled_deepslate.json
- minecraft/recipes/chiseled_grimstone_from_grimstone_stonecutting.json
- minecraft/recipes/chiseled_grimstone.json
+ minecraft/recipes/cobbled_deepslate_slab_from_cobbled_deepslate_stonecutting.json
+ minecraft/recipes/cobbled_deepslate_slab.json
+ minecraft/recipes/cobbled_deepslate_stairs_from_cobbled_deepslate_stonecutting.json
+ minecraft/recipes/cobbled_deepslate_stairs.json
+ minecraft/recipes/cobbled_deepslate_wall_from_cobbled_deepslate_stonecutting.json
+ minecraft/recipes/cobbled_deepslate_wall.json
+ minecraft/recipes/deepslate_brick_slab_from_deepslate_bricks_stonecutting.json
+ minecraft/recipes/deepslate_brick_slab.json
+ minecraft/recipes/deepslate_brick_stairs_from_deepslate_bricks_stonecutting.json
+ minecraft/recipes/deepslate_brick_stairs.json
+ minecraft/recipes/deepslate_brick_wall_from_deepslate_bricks_stonecutting.json
+ minecraft/recipes/deepslate_brick_wall.json
+ minecraft/recipes/deepslate_tile_slab_from_deepslate_tiles_stonecutting.json
+ minecraft/recipes/deepslate_tile_slab.json
+ minecraft/recipes/deepslate_tile_stairs_from_deepslate_tiles_stonecutting.json
+ minecraft/recipes/deepslate_tile_stairs.json
+ minecraft/recipes/deepslate_tile_wall_from_deepslate_tiles_stonecutting.json
+ minecraft/recipes/deepslate_tile_wall.json
- minecraft/recipes/grimstone_brick_slab_from_grimstone_bricks_stonecutting.json
- minecraft/recipes/grimstone_brick_slab.json
- minecraft/recipes/grimstone_brick_stairs_from_grimstone_bricks_stonecutting.json
- minecraft/recipes/grimstone_brick_stairs.json
- minecraft/recipes/grimstone_brick_wall_from_grimstone_bricks_stonecutting.json
- minecraft/recipes/grimstone_brick_wall.json
- minecraft/recipes/grimstone_slab_from_grimstone_stonecutting.json
- minecraft/recipes/grimstone_slab.json
- minecraft/recipes/grimstone_stairs_from_grimstone_stonecutting.json
- minecraft/recipes/grimstone_stairs.json
- minecraft/recipes/grimstone_tile_slab_from_grimstone_tiles_stonecutting.json
- minecraft/recipes/grimstone_tile_slab.json
- minecraft/recipes/grimstone_tile_stairs_from_grimstone_tiles_stonecutting.json
- minecraft/recipes/grimstone_tile_stairs.json
- minecraft/recipes/grimstone_tile_wall_from_grimstone_tiles_stonecutting.json
- minecraft/recipes/grimstone_tile_wall.json
- minecraft/recipes/grimstone_wall_from_grimstone_stonecutting.json
- minecraft/recipes/grimstone_wall.json
+ minecraft/recipes/polished_deepslate_slab_from_polished_deepslate_stonecutting.json
+ minecraft/recipes/polished_deepslate_slab.json
+ minecraft/recipes/polished_deepslate_stairs_from_polished_deepslate_stonecutting.json
+ minecraft/recipes/polished_deepslate_stairs.json
+ minecraft/recipes/polished_deepslate_wall_from_polished_deepslate_stonecutting.json
+ minecraft/recipes/polished_deepslate_wall.json
+ minecraft/recipes/polished_deepslate.json
- minecraft/recipes/polished_grimstone_slab_from_polished_grimstone_stonecutting.json
- minecraft/recipes/polished_grimstone_slab.json
- minecraft/recipes/polished_grimstone_stairs_from_polished_grimstone_stonecutting.json
- minecraft/recipes/polished_grimstone_stairs.json
- minecraft/recipes/polished_grimstone_wall_from_polished_grimstone_stonecutting.json
- minecraft/recipes/polished_grimstone_wall.json
- minecraft/recipes/polished_grimstone.json
+ minecraft/recipes/smooth_basalt.json
+ minecraft/tags/blocks/deepslate_ore_replaceables.json
+ minecraft/tags/blocks/diamond_ores.json
+ minecraft/tags/blocks/iron_ores.json
+ minecraft/tags/blocks/lapis_ores.json
+ minecraft/tags/blocks/redstone_ores.json
+ minecraft/tags/blocks/stone_ore_replaceables.json
+ minecraft/tags/items/diamond_ores.json
+ minecraft/tags/items/iron_ores.json
+ minecraft/tags/items/lapis_ores.json
+ minecraft/tags/items/redstone_ores.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/chiseled_deepslate.json
- minecraft/blockstates/chiseled_grimstone.json
+ minecraft/blockstates/cobbled_deepslate_slab.json
+ minecraft/blockstates/cobbled_deepslate_stairs.json
+ minecraft/blockstates/cobbled_deepslate_wall.json
+ minecraft/blockstates/cobbled_deepslate.json
+ minecraft/blockstates/deepslate_brick_slab.json
+ minecraft/blockstates/deepslate_brick_stairs.json
+ minecraft/blockstates/deepslate_brick_wall.json
+ minecraft/blockstates/deepslate_bricks.json
+ minecraft/blockstates/deepslate_diamond_ore.json
+ minecraft/blockstates/deepslate_gold_ore.json
+ minecraft/blockstates/deepslate_iron_ore.json
+ minecraft/blockstates/deepslate_lapis_ore.json
+ minecraft/blockstates/deepslate_redstone_ore.json
+ minecraft/blockstates/deepslate_tile_slab.json
+ minecraft/blockstates/deepslate_tile_stairs.json
+ minecraft/blockstates/deepslate_tile_wall.json
+ minecraft/blockstates/deepslate_tiles.json
+ minecraft/blockstates/deepslate.json
- minecraft/blockstates/grimstone_brick_slab.json
- minecraft/blockstates/grimstone_brick_stairs.json
- minecraft/blockstates/grimstone_brick_wall.json
- minecraft/blockstates/grimstone_bricks.json
- minecraft/blockstates/grimstone_slab.json
- minecraft/blockstates/grimstone_stairs.json
- minecraft/blockstates/grimstone_tile_slab.json
- minecraft/blockstates/grimstone_tile_stairs.json
- minecraft/blockstates/grimstone_tile_wall.json
- minecraft/blockstates/grimstone_tiles.json
- minecraft/blockstates/grimstone_wall.json
- minecraft/blockstates/grimstone.json
+ minecraft/blockstates/polished_deepslate_slab.json
+ minecraft/blockstates/polished_deepslate_stairs.json
+ minecraft/blockstates/polished_deepslate_wall.json
+ minecraft/blockstates/polished_deepslate.json
- minecraft/blockstates/polished_grimstone_slab.json
- minecraft/blockstates/polished_grimstone_stairs.json
- minecraft/blockstates/polished_grimstone_wall.json
- minecraft/blockstates/polished_grimstone.json
+ minecraft/blockstates/smooth_basalt.json
+ minecraft/models/block/chiseled_deepslate.json
- minecraft/models/block/chiseled_grimstone.json
+ minecraft/models/block/cobbled_deepslate_mirrored.json
+ minecraft/models/block/cobbled_deepslate_slab_top.json
+ minecraft/models/block/cobbled_deepslate_slab.json
+ minecraft/models/block/cobbled_deepslate_stairs_inner.json
+ minecraft/models/block/cobbled_deepslate_stairs_outer.json
+ minecraft/models/block/cobbled_deepslate_stairs.json
+ minecraft/models/block/cobbled_deepslate_wall_inventory.json
+ minecraft/models/block/cobbled_deepslate_wall_post.json
+ minecraft/models/block/cobbled_deepslate_wall_side_tall.json
+ minecraft/models/block/cobbled_deepslate_wall_side.json
+ minecraft/models/block/cobbled_deepslate.json
+ minecraft/models/block/cube_column_mirrored.json
+ minecraft/models/block/deepslate_brick_slab_top.json
+ minecraft/models/block/deepslate_brick_slab.json
+ minecraft/models/block/deepslate_brick_stairs_inner.json
+ minecraft/models/block/deepslate_brick_stairs_outer.json
+ minecraft/models/block/deepslate_brick_stairs.json
+ minecraft/models/block/deepslate_brick_wall_inventory.json
+ minecraft/models/block/deepslate_brick_wall_post.json
+ minecraft/models/block/deepslate_brick_wall_side_tall.json
+ minecraft/models/block/deepslate_brick_wall_side.json
+ minecraft/models/block/deepslate_bricks.json
+ minecraft/models/block/deepslate_diamond_ore.json
+ minecraft/models/block/deepslate_gold_ore.json
+ minecraft/models/block/deepslate_iron_ore.json
+ minecraft/models/block/deepslate_lapis_ore.json
+ minecraft/models/block/deepslate_mirrored.json
+ minecraft/models/block/deepslate_redstone_ore.json
+ minecraft/models/block/deepslate_tile_slab_top.json
+ minecraft/models/block/deepslate_tile_slab.json
+ minecraft/models/block/deepslate_tile_stairs_inner.json
+ minecraft/models/block/deepslate_tile_stairs_outer.json
+ minecraft/models/block/deepslate_tile_stairs.json
+ minecraft/models/block/deepslate_tile_wall_inventory.json
+ minecraft/models/block/deepslate_tile_wall_post.json
+ minecraft/models/block/deepslate_tile_wall_side_tall.json
+ minecraft/models/block/deepslate_tile_wall_side.json
+ minecraft/models/block/deepslate_tiles.json
+ minecraft/models/block/deepslate.json
- minecraft/models/block/grimstone_brick_slab_top.json
- minecraft/models/block/grimstone_brick_slab.json
- minecraft/models/block/grimstone_brick_stairs_inner.json
- minecraft/models/block/grimstone_brick_stairs_outer.json
- minecraft/models/block/grimstone_brick_stairs.json
- minecraft/models/block/grimstone_brick_wall_inventory.json
- minecraft/models/block/grimstone_brick_wall_post.json
- minecraft/models/block/grimstone_brick_wall_side_tall.json
- minecraft/models/block/grimstone_brick_wall_side.json
- minecraft/models/block/grimstone_bricks.json
- minecraft/models/block/grimstone_mirrored.json
- minecraft/models/block/grimstone_slab_top.json
- minecraft/models/block/grimstone_slab.json
- minecraft/models/block/grimstone_stairs_inner.json
- minecraft/models/block/grimstone_stairs_outer.json
- minecraft/models/block/grimstone_stairs.json
- minecraft/models/block/grimstone_tile_slab_top.json
- minecraft/models/block/grimstone_tile_slab.json
- minecraft/models/block/grimstone_tile_stairs_inner.json
- minecraft/models/block/grimstone_tile_stairs_outer.json
- minecraft/models/block/grimstone_tile_stairs.json
- minecraft/models/block/grimstone_tile_wall_inventory.json
- minecraft/models/block/grimstone_tile_wall_post.json
- minecraft/models/block/grimstone_tile_wall_side_tall.json
- minecraft/models/block/grimstone_tile_wall_side.json
- minecraft/models/block/grimstone_tiles.json
- minecraft/models/block/grimstone_wall_inventory.json
- minecraft/models/block/grimstone_wall_post.json
- minecraft/models/block/grimstone_wall_side_tall.json
- minecraft/models/block/grimstone_wall_side.json
- minecraft/models/block/grimstone.json
+ minecraft/models/block/polished_deepslate_slab_top.json
+ minecraft/models/block/polished_deepslate_slab.json
+ minecraft/models/block/polished_deepslate_stairs_inner.json
+ minecraft/models/block/polished_deepslate_stairs_outer.json
+ minecraft/models/block/polished_deepslate_stairs.json
+ minecraft/models/block/polished_deepslate_wall_inventory.json
+ minecraft/models/block/polished_deepslate_wall_post.json
+ minecraft/models/block/polished_deepslate_wall_side_tall.json
+ minecraft/models/block/polished_deepslate_wall_side.json
+ minecraft/models/block/polished_deepslate.json
- minecraft/models/block/polished_grimstone_slab_top.json
- minecraft/models/block/polished_grimstone_slab.json
- minecraft/models/block/polished_grimstone_stairs_inner.json
- minecraft/models/block/polished_grimstone_stairs_outer.json
- minecraft/models/block/polished_grimstone_stairs.json
- minecraft/models/block/polished_grimstone_wall_inventory.json
- minecraft/models/block/polished_grimstone_wall_post.json
- minecraft/models/block/polished_grimstone_wall_side_tall.json
- minecraft/models/block/polished_grimstone_wall_side.json
- minecraft/models/block/polished_grimstone.json
+ minecraft/models/block/smooth_basalt.json
+ minecraft/models/item/chiseled_deepslate.json
- minecraft/models/item/chiseled_grimstone.json
+ minecraft/models/item/cobbled_deepslate_slab.json
+ minecraft/models/item/cobbled_deepslate_stairs.json
+ minecraft/models/item/cobbled_deepslate_wall.json
+ minecraft/models/item/cobbled_deepslate.json
+ minecraft/models/item/deepslate_brick_slab.json
+ minecraft/models/item/deepslate_brick_stairs.json
+ minecraft/models/item/deepslate_brick_wall.json
+ minecraft/models/item/deepslate_bricks.json
+ minecraft/models/item/deepslate_diamond_ore.json
+ minecraft/models/item/deepslate_gold_ore.json
+ minecraft/models/item/deepslate_iron_ore.json
+ minecraft/models/item/deepslate_lapis_ore.json
+ minecraft/models/item/deepslate_redstone_ore.json
+ minecraft/models/item/deepslate_tile_slab.json
+ minecraft/models/item/deepslate_tile_stairs.json
+ minecraft/models/item/deepslate_tile_wall.json
+ minecraft/models/item/deepslate_tiles.json
+ minecraft/models/item/deepslate.json
- minecraft/models/item/grimstone_brick_slab.json
- minecraft/models/item/grimstone_brick_stairs.json
- minecraft/models/item/grimstone_brick_wall.json
- minecraft/models/item/grimstone_bricks.json
- minecraft/models/item/grimstone_slab.json
- minecraft/models/item/grimstone_stairs.json
- minecraft/models/item/grimstone_tile_slab.json
- minecraft/models/item/grimstone_tile_stairs.json
- minecraft/models/item/grimstone_tile_wall.json
- minecraft/models/item/grimstone_tiles.json
- minecraft/models/item/grimstone_wall.json
- minecraft/models/item/grimstone.json
+ minecraft/models/item/polished_deepslate_slab.json
+ minecraft/models/item/polished_deepslate_stairs.json
+ minecraft/models/item/polished_deepslate_wall.json
+ minecraft/models/item/polished_deepslate.json
- minecraft/models/item/polished_grimstone_slab.json
- minecraft/models/item/polished_grimstone_stairs.json
- minecraft/models/item/polished_grimstone_wall.json
- minecraft/models/item/polished_grimstone.json
+ minecraft/models/item/smooth_basalt.json
+ minecraft/textures/block/chiseled_deepslate.png
- minecraft/textures/block/chiseled_grimstone.png
+ minecraft/textures/block/cobbled_deepslate.png
+ minecraft/textures/block/deepslate_bricks.png
+ minecraft/textures/block/deepslate_diamond_ore.png
+ minecraft/textures/block/deepslate_gold_ore.png
+ minecraft/textures/block/deepslate_iron_ore.png
+ minecraft/textures/block/deepslate_lapis_ore.png
+ minecraft/textures/block/deepslate_redstone_ore.png
+ minecraft/textures/block/deepslate_tiles.png
+ minecraft/textures/block/deepslate_top.png
+ minecraft/textures/block/deepslate.png
- minecraft/textures/block/grimstone_bricks.png
- minecraft/textures/block/grimstone_tiles.png
- minecraft/textures/block/grimstone.png
+ minecraft/textures/block/polished_deepslate.png
- minecraft/textures/block/polished_grimstone.png
+ minecraft/textures/block/smooth_basalt.png
```

</details>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.particles.VibrationParticleOption$1
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.BlockFamilies
+ net.minecraft.data.BlockFamily
- net.minecraft.data.BlockFamily$1
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.BuiltinRegistries
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.HashCache
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLoot
- net.minecraft.data.loot.ChestLoot
+ net.minecraft.data.loot.EntityLoot
- net.minecraft.data.loot.FishingLoot
+ net.minecraft.data.loot.GiftLoot
- net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.PiglinBarterLoot
+ net.minecraft.data.Main
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChatPacket
- net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLoginPacket
- net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
+ net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
- net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ClientboundOpenBookPacket
- net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
+ net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
- net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$3
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$5
- net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
- net.minecraft.util.ClampedNormalFloat
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.ConstantFloat
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.CauldronRenameFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.DyeItemRenameFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ net.minecraft.util.datafix.fixes.NamedEntityFix
- net.minecraft.util.datafix.fixes.NewVillageFix
+ net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
- net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
+ net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenameBiomesFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.SwimStatsRenameFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
+ net.minecraft.util.datafix.schemas.V100
- net.minecraft.util.datafix.schemas.V102
+ net.minecraft.util.datafix.schemas.V1022
- net.minecraft.util.datafix.schemas.V106
+ net.minecraft.util.datafix.schemas.V107
- net.minecraft.util.datafix.schemas.V1125
+ net.minecraft.util.datafix.schemas.V135
- net.minecraft.util.datafix.schemas.V143
+ net.minecraft.util.datafix.schemas.V1451
- net.minecraft.util.datafix.schemas.V1451_1
+ net.minecraft.util.datafix.schemas.V1451_2
- net.minecraft.util.datafix.schemas.V1451_3
+ net.minecraft.util.datafix.schemas.V1451_4
- net.minecraft.util.datafix.schemas.V1451_5
+ net.minecraft.util.datafix.schemas.V1451_6
- net.minecraft.util.datafix.schemas.V1451_7
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1460$1
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2686
+ net.minecraft.util.datafix.schemas.V2688
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.FloatProvider
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$1
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.TrapezoidFloat
+ net.minecraft.util.Tuple
- net.minecraft.util.UniformFloat
+ net.minecraft.util.UniformInt
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
+ net.minecraft.world.damagesource.BadRespawnPointDamage
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.EntityDamageSource
+ net.minecraft.world.damagesource.IndirectEntityDamageSource
- net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsoptionMobEffect
- net.minecraft.world.effect.AttackDamageMobEffect
+ net.minecraft.world.effect.HealthBoostMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.AttributeMap
- net.minecraft.world.entity.ai.attributes.AttributeModifier
+ net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
+ net.minecraft.world.entity.ai.attributes.DefaultAttributes
+ net.minecraft.world.entity.ai.attributes.package-info
- net.minecraft.world.entity.ai.attributes.RangedAttribute
- net.minecraft.world.entity.ai.behavior.AcquirePoi
+ net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
- net.minecraft.world.entity.ai.behavior.AnimalMakeLove
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownTemptationTicks
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.RandomSwim
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunIf
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.RunSometimes
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WeightedList
+ net.minecraft.world.entity.ai.behavior.WeightedList$1
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.PlayGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.TakeFlowerGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$1
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlHostileSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HostilesSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
+ net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.AirRandomPos
+ net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
+ net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
- net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
+ net.minecraft.world.entity.animal.Bee
- net.minecraft.world.entity.animal.Bee$1
+ net.minecraft.world.entity.animal.Bee$BaseBeeGoal
- net.minecraft.world.entity.animal.Bee$BeeAttackGoal
+ net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
- net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
- net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
+ net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeLookControl
+ net.minecraft.world.entity.animal.Bee$BeePollinateGoal
- net.minecraft.world.entity.animal.Bee$BeeWanderGoal
+ net.minecraft.world.entity.animal.Bucketable
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$1
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$1
+ net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
- net.minecraft.world.entity.animal.Fox$FaceplantGoal
+ net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
- net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
+ net.minecraft.world.entity.animal.Fox$FoxBreedGoal
- net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
+ net.minecraft.world.entity.animal.Fox$FoxFloatGoal
- net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
+ net.minecraft.world.entity.animal.Fox$FoxGroupData
- net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Fox$FoxLookControl
- net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
+ net.minecraft.world.entity.animal.Fox$FoxMoveControl
- net.minecraft.world.entity.animal.Fox$FoxPanicGoal
+ net.minecraft.world.entity.animal.Fox$FoxPounceGoal
- net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
+ net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
- net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
+ net.minecraft.world.entity.animal.Fox$SeekShelterGoal
- net.minecraft.world.entity.animal.Fox$SleepGoal
+ net.minecraft.world.entity.animal.Fox$StalkPreyGoal
- net.minecraft.world.entity.animal.Fox$Type
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$1
- net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
+ net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
- net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
+ net.minecraft.world.entity.animal.horse.Markings
- net.minecraft.world.entity.animal.horse.Mule
+ net.minecraft.world.entity.animal.horse.package-info
+ net.minecraft.world.entity.animal.horse.SkeletonHorse
- net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
+ net.minecraft.world.entity.animal.horse.TraderLlama
- net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ net.minecraft.world.entity.animal.horse.Variant
- net.minecraft.world.entity.animal.horse.ZombieHorse
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.IronGolem$Crackiness
+ net.minecraft.world.entity.animal.MushroomCow
- net.minecraft.world.entity.animal.MushroomCow$MushroomType
+ net.minecraft.world.entity.animal.Ocelot
- net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
- net.minecraft.world.entity.animal.package-info
- net.minecraft.world.entity.animal.Panda
+ net.minecraft.world.entity.animal.Panda$Gene
- net.minecraft.world.entity.animal.Panda$PandaAttackGoal
+ net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
- net.minecraft.world.entity.animal.Panda$PandaBreedGoal
+ net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
- net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
+ net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
- net.minecraft.world.entity.animal.Panda$PandaMoveControl
+ net.minecraft.world.entity.animal.Panda$PandaPanicGoal
- net.minecraft.world.entity.animal.Panda$PandaRollGoal
+ net.minecraft.world.entity.animal.Panda$PandaSitGoal
- net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
+ net.minecraft.world.entity.animal.Parrot
- net.minecraft.world.entity.animal.Parrot$1
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$1
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$1
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$1
+ net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
- net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
- net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
+ net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
- net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.boss.enderdragon.EndCrystal
+ net.minecraft.world.entity.boss.enderdragon.EnderDragon
- net.minecraft.world.entity.boss.enderdragon.package-info
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
+ net.minecraft.world.entity.boss.enderdragon.phases.package-info
+ net.minecraft.world.entity.boss.EnderDragonPart
- net.minecraft.world.entity.boss.package-info
+ net.minecraft.world.entity.boss.wither.package-info
+ net.minecraft.world.entity.boss.wither.WitherBoss
- net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
- net.minecraft.world.entity.decoration.ArmorStand
+ net.minecraft.world.entity.decoration.ArmorStand$1
- net.minecraft.world.entity.decoration.HangingEntity
+ net.minecraft.world.entity.decoration.HangingEntity$1
- net.minecraft.world.entity.decoration.ItemFrame
+ net.minecraft.world.entity.decoration.ItemFrame$1
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.Entity$MovementEmission
+ net.minecraft.world.entity.Entity$RemovalReason
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$1
- net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
- net.minecraft.world.entity.monster.Ghast
+ net.minecraft.world.entity.monster.Ghast$GhastLookGoal
- net.minecraft.world.entity.monster.Ghast$GhastMoveControl
+ net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
- net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
+ net.minecraft.world.entity.monster.Giant
- net.minecraft.world.entity.monster.Guardian
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
- net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
+ net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.hoglin.package-info
- net.minecraft.world.entity.monster.Husk
+ net.minecraft.world.entity.monster.Illusioner
- net.minecraft.world.entity.monster.Illusioner$1
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$1
+ net.minecraft.world.entity.monster.Phantom$AttackPhase
- net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
- net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
+ net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- net.minecraft.world.entity.monster.Phantom$PhantomLookControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
+ net.minecraft.world.entity.monster.piglin.AbstractPiglin
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.PiglinAi
- net.minecraft.world.entity.monster.piglin.PiglinArmPose
+ net.minecraft.world.entity.monster.piglin.PiglinBrute
- net.minecraft.world.entity.monster.piglin.PiglinBruteAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- net.minecraft.world.entity.monster.Pillager
+ net.minecraft.world.entity.monster.RangedAttackMob
- net.minecraft.world.entity.monster.Ravager
+ net.minecraft.world.entity.monster.Ravager$1
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$1
+ net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
- net.minecraft.world.entity.monster.Strider$1
+ net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
- net.minecraft.world.entity.monster.Strider$StriderPathNavigation
+ net.minecraft.world.entity.monster.Vex
- net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
+ net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
- net.minecraft.world.entity.monster.Vex$VexMoveControl
+ net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
- net.minecraft.world.entity.monster.Vindicator
+ net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
- net.minecraft.world.entity.monster.Witch
+ net.minecraft.world.entity.monster.WitherSkeleton
- net.minecraft.world.entity.monster.Zoglin
+ net.minecraft.world.entity.monster.Zombie
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
+ net.minecraft.world.entity.npc.Villager
- net.minecraft.world.entity.npc.VillagerData
+ net.minecraft.world.entity.npc.VillagerDataHolder
- net.minecraft.world.entity.npc.VillagerProfession
+ net.minecraft.world.entity.npc.VillagerTrades
- net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.AbstractArrow
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacements$Type
- net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$1
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.CraftingContainer
- net.minecraft.world.inventory.CraftingMenu
+ net.minecraft.world.inventory.DataSlot
- net.minecraft.world.inventory.DataSlot$1
+ net.minecraft.world.inventory.DataSlot$2
- net.minecraft.world.inventory.DataSlot$3
+ net.minecraft.world.inventory.DispenserMenu
- net.minecraft.world.inventory.EnchantmentMenu
+ net.minecraft.world.inventory.EnchantmentMenu$1
- net.minecraft.world.inventory.EnchantmentMenu$2
+ net.minecraft.world.inventory.EnchantmentMenu$3
- net.minecraft.world.inventory.FurnaceFuelSlot
+ net.minecraft.world.inventory.FurnaceMenu
- net.minecraft.world.inventory.FurnaceResultSlot
+ net.minecraft.world.inventory.GrindstoneMenu
- net.minecraft.world.inventory.GrindstoneMenu$1
+ net.minecraft.world.inventory.GrindstoneMenu$2
- net.minecraft.world.inventory.GrindstoneMenu$3
+ net.minecraft.world.inventory.GrindstoneMenu$4
- net.minecraft.world.inventory.HopperMenu
+ net.minecraft.world.inventory.HorseInventoryMenu
- net.minecraft.world.inventory.HorseInventoryMenu$1
+ net.minecraft.world.inventory.HorseInventoryMenu$2
- net.minecraft.world.inventory.InventoryMenu
+ net.minecraft.world.inventory.InventoryMenu$1
- net.minecraft.world.inventory.InventoryMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu
- net.minecraft.world.inventory.ItemCombinerMenu$1
+ net.minecraft.world.inventory.ItemCombinerMenu$2
- net.minecraft.world.inventory.LecternMenu
+ net.minecraft.world.inventory.LecternMenu$1
- net.minecraft.world.inventory.LoomMenu
+ net.minecraft.world.inventory.LoomMenu$1
- net.minecraft.world.inventory.LoomMenu$2
+ net.minecraft.world.inventory.LoomMenu$3
- net.minecraft.world.inventory.LoomMenu$4
+ net.minecraft.world.inventory.LoomMenu$5
- net.minecraft.world.inventory.LoomMenu$6
+ net.minecraft.world.inventory.MenuConstructor
- net.minecraft.world.inventory.MenuType
+ net.minecraft.world.inventory.MenuType$MenuSupplier
- net.minecraft.world.inventory.MerchantContainer
+ net.minecraft.world.inventory.MerchantMenu
- net.minecraft.world.inventory.MerchantResultSlot
+ net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
- net.minecraft.world.inventory.RecipeHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$1
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
- net.minecraft.world.item.crafting.package-info
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
+ net.minecraft.world.item.crafting.SimpleRecipeSerializer
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmokingRecipe
+ net.minecraft.world.item.crafting.StonecutterRecipe
- net.minecraft.world.item.crafting.SuspiciousStewRecipe
+ net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$11
- net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$2
- net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$4
- net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$6
- net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$8
- net.minecraft.world.item.CreativeModeTab$9
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
+ net.minecraft.world.item.enchantment.ArrowDamageEnchantment
- net.minecraft.world.item.enchantment.ArrowFireEnchantment
+ net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
- net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
+ net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
- net.minecraft.world.item.enchantment.BindingCurseEnchantment
+ net.minecraft.world.item.enchantment.DamageEnchantment
- net.minecraft.world.item.enchantment.DigDurabilityEnchantment
+ net.minecraft.world.item.enchantment.DiggingEnchantment
- net.minecraft.world.item.enchantment.Enchantment
+ net.minecraft.world.item.enchantment.Enchantment$Rarity
- net.minecraft.world.item.enchantment.EnchantmentCategory
+ net.minecraft.world.item.enchantment.EnchantmentCategory$1
- net.minecraft.world.item.enchantment.EnchantmentCategory$10
+ net.minecraft.world.item.enchantment.EnchantmentCategory$11
- net.minecraft.world.item.enchantment.EnchantmentCategory$12
+ net.minecraft.world.item.enchantment.EnchantmentCategory$13
- net.minecraft.world.item.enchantment.EnchantmentCategory$14
+ net.minecraft.world.item.enchantment.EnchantmentCategory$2
- net.minecraft.world.item.enchantment.EnchantmentCategory$3
+ net.minecraft.world.item.enchantment.EnchantmentCategory$4
- net.minecraft.world.item.enchantment.EnchantmentCategory$5
+ net.minecraft.world.item.enchantment.EnchantmentCategory$6
- net.minecraft.world.item.enchantment.EnchantmentCategory$7
+ net.minecraft.world.item.enchantment.EnchantmentCategory$8
- net.minecraft.world.item.enchantment.EnchantmentCategory$9
+ net.minecraft.world.item.enchantment.EnchantmentHelper
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
- net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
- net.minecraft.world.item.enchantment.FishingSpeedEnchantment
+ net.minecraft.world.item.enchantment.FrostWalkerEnchantment
- net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
- net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
+ net.minecraft.world.item.enchantment.ProtectionEnchantment
- net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$1
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateParameters
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$1
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$1
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$NoiseParameters
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
- net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
+ net.minecraft.world.level.block.AbstractCauldronBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractGlassBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
+ net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock
+ net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.AzaleaBlock
+ net.minecraft.world.level.block.BambooBlock
- net.minecraft.world.level.block.BambooSaplingBlock
+ net.minecraft.world.level.block.BannerBlock
- net.minecraft.world.level.block.BarrelBlock
+ net.minecraft.world.level.block.BarrierBlock
- net.minecraft.world.level.block.BaseCoralFanBlock
+ net.minecraft.world.level.block.BaseCoralPlantBlock
- net.minecraft.world.level.block.BaseCoralPlantTypeBlock
+ net.minecraft.world.level.block.BaseCoralWallFanBlock
- net.minecraft.world.level.block.BaseEntityBlock
+ net.minecraft.world.level.block.BaseFireBlock
- net.minecraft.world.level.block.BasePressurePlateBlock
+ net.minecraft.world.level.block.BaseRailBlock
- net.minecraft.world.level.block.BaseRailBlock$1
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BigDripleafBlock
- net.minecraft.world.level.block.BigDripleafStemBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$BlockStatePairKey
+ net.minecraft.world.level.block.Blocks
- net.minecraft.world.level.block.BonemealableBlock
+ net.minecraft.world.level.block.BrewingStandBlock
- net.minecraft.world.level.block.BubbleColumnBlock
+ net.minecraft.world.level.block.BucketPickup
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CandleCakeBlock
+ net.minecraft.world.level.block.CarpetBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.CaveVinesBlock
+ net.minecraft.world.level.block.CaveVinesBodyBlock
- net.minecraft.world.level.block.CaveVinesHeadBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChorusFlowerBlock
+ net.minecraft.world.level.block.ChorusPlantBlock
- net.minecraft.world.level.block.CocoaBlock
+ net.minecraft.world.level.block.CocoaBlock$1
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DetectorRailBlock
- net.minecraft.world.level.block.DetectorRailBlock$1
+ net.minecraft.world.level.block.DiodeBlock
- net.minecraft.world.level.block.DirectionalBlock
+ net.minecraft.world.level.block.DirtPathBlock
- net.minecraft.world.level.block.DispenserBlock
+ net.minecraft.world.level.block.DoorBlock
- net.minecraft.world.level.block.DoorBlock$1
+ net.minecraft.world.level.block.DoubleBlockCombiner
- net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
+ net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ net.minecraft.world.level.block.DoublePlantBlock
- net.minecraft.world.level.block.DragonEggBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BellBlockEntity
+ net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
+ net.minecraft.world.level.block.entity.BlockEntityType
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ net.minecraft.world.level.block.Fallable
- net.minecraft.world.level.block.FallingBlock
+ net.minecraft.world.level.block.FarmBlock
- net.minecraft.world.level.block.FenceBlock
+ net.minecraft.world.level.block.FenceGateBlock
- net.minecraft.world.level.block.FenceGateBlock$1
+ net.minecraft.world.level.block.FireBlock
- net.minecraft.world.level.block.FletchingTableBlock
+ net.minecraft.world.level.block.FlowerBlock
- net.minecraft.world.level.block.FlowerPotBlock
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GlowLichenBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GravelBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.GrowingPlantBlock
+ net.minecraft.world.level.block.GrowingPlantBodyBlock
- net.minecraft.world.level.block.GrowingPlantHeadBlock
+ net.minecraft.world.level.block.HalfTransparentBlock
- net.minecraft.world.level.block.HangingRootsBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.IronBarsBlock
- net.minecraft.world.level.block.JigsawBlock
+ net.minecraft.world.level.block.JukeboxBlock
- net.minecraft.world.level.block.KelpBlock
+ net.minecraft.world.level.block.KelpPlantBlock
- net.minecraft.world.level.block.LadderBlock
+ net.minecraft.world.level.block.LadderBlock$1
- net.minecraft.world.level.block.LanternBlock
+ net.minecraft.world.level.block.LavaCauldronBlock
- net.minecraft.world.level.block.LayeredCauldronBlock
+ net.minecraft.world.level.block.LeavesBlock
- net.minecraft.world.level.block.LecternBlock
+ net.minecraft.world.level.block.LecternBlock$1
- net.minecraft.world.level.block.LevelEvent
+ net.minecraft.world.level.block.LeverBlock
- net.minecraft.world.level.block.LeverBlock$1
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
- net.minecraft.world.level.block.NetherrackBlock
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
+ net.minecraft.world.level.block.NetherWartBlock
+ net.minecraft.world.level.block.NoteBlock
- net.minecraft.world.level.block.NyliumBlock
+ net.minecraft.world.level.block.ObserverBlock
- net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
+ net.minecraft.world.level.block.piston.PistonMath$1
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RespawnAnchorBlock$1
+ net.minecraft.world.level.block.RodBlock
- net.minecraft.world.level.block.RodBlock$1
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmallDripleafBlock
+ net.minecraft.world.level.block.SmithingTableBlock
- net.minecraft.world.level.block.SmokerBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
+ net.minecraft.world.level.block.SporeBlossomBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$1
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$1
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ChunkTickList
+ net.minecraft.world.level.ChunkTickList$1
- net.minecraft.world.level.ChunkTickList$ScheduledTick
+ net.minecraft.world.level.ClipBlockStateContext
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.CollisionSpliterator
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
- net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.NoiseEffect
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
- net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelTimeAccess
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
- net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.Snooper
+ net.minecraft.world.Snooper$1
- net.minecraft.world.SnooperPopulator
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.advancements.Criterion +1M
```
```
XXX.data.worldgen.Carvers +1P
```
```
XXX.data.worldgen.Features +10P
```
```
XXX.minecraft.network.ConnectionProtocol +1M -1M
```
```
XXX.minecraft.network.ConnectionProtocol$PacketSet +2M -2M | +1P -1P
```
```
XXX.minecraft.network.FriendlyByteBuf +11M -1M
```
```
XXX.network.protocol.Packet -1P
```
```
XXX.protocol.game.ClientboundAddEntityPacket +1M -2M
```
```
XXX.protocol.game.ClientboundAddMobPacket +1M -2M
```
```
XXX.protocol.game.ClientboundAddPlayerPacket +1M -2M
```
```
XXX.protocol.game.ClientboundAnimatePacket +1M -2M
```
```
XXX.protocol.game.ClientboundBlockBreakAckPacket +1M -2M
```
```
XXX.protocol.game.ClientboundBlockEntityDataPacket +1M -2M
```
```
XXX.protocol.game.ClientboundBlockUpdatePacket +1M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$1 +4M -1M | -1P
```
```
XXX.protocol.game.ClientboundCommandSuggestionsPacket +3M -2M
```
```
XXX.protocol.game.ClientboundContainerAckPacket +1M -2M
```
```
XXX.protocol.game.ClientboundContainerSetContentPacket +1M -2M
```
```
XXX.protocol.game.ClientboundContainerSetSlotPacket +1M -2M
```
```
XXX.protocol.game.ClientboundCustomPayloadPacket +1M -2M | -1P
```
```
XXX.protocol.game.ClientboundDisconnectPacket +1M -2M
```
```
XXX.protocol.game.ClientboundExplodePacket +3M -2M
```
```
XXX.protocol.game.ClientboundGameEventPacket +1M -2M
```
```
XXX.protocol.game.ClientboundHorseScreenOpenPacket +1M -2M
```
```
XXX.protocol.game.ClientboundPlayerLookAtPacket +1M -2M
```
```
XXX.protocol.game.ClientboundRemoveMobEffectPacket +1M -2M
```
```
XXX.protocol.game.ClientboundRespawnPacket +1M -2M
```
```
XXX.protocol.game.ClientboundSectionBlocksUpdatePacket +1M -3M
```
```
XXX.protocol.game.ClientboundSoundEntityPacket +1M -2M
```
```
XXX.protocol.game.ClientboundStopSoundPacket +1M -2M
```
```
XXX.protocol.game.ClientboundTagQueryPacket +1M -2M
```
```
XXX.protocol.game.ClientboundTeleportEntityPacket +1M -2M
```
```
XXX.protocol.game.ClientboundUpdateAttributesPacket +5M -2M
```
```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +1M -2M
```
```
XXX.protocol.game.ClientboundUpdateTagsPacket +4M -3M
```
```
XXX.protocol.game.ServerboundAcceptTeleportationPacket +1M -2M
```
```
XXX.protocol.game.ServerboundChangeDifficultyPacket +1M -2M
```
```
XXX.protocol.game.ServerboundClientCommandPacket +1M -2M
```
```
XXX.protocol.game.ServerboundClientInformationPacket +1M -2M
```
```
XXX.protocol.game.ServerboundContainerAckPacket +1M -2M
```
```
XXX.protocol.game.ServerboundContainerClickPacket +1M -2M
```
```
XXX.protocol.game.ServerboundCustomPayloadPacket +1M -2M
```
```
XXX.protocol.game.ServerboundEntityTagQuery +1M -2M
```
```
XXX.protocol.game.ServerboundMoveVehiclePacket +1M -2M
```
```
XXX.protocol.game.ServerboundPickItemPacket +1M -2M
```
```
XXX.protocol.game.ServerboundPlayerAbilitiesPacket +1M -2M
```
```
XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket +1M -2M
```
```
XXX.protocol.game.ServerboundRenameItemPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSetBeaconPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSetCommandBlockPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSetCreativeModeSlotPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSetStructureBlockPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSwingPacket +1M -2M
```
```
XXX.protocol.game.ServerboundUseItemOnPacket +1M -2M
```
```
XXX.protocol.login.ClientboundGameProfilePacket +1M -2M
```
```
XXX.protocol.login.ClientboundLoginCompressionPacket +1M -2M
```
```
XXX.protocol.login.ServerboundHelloPacket +1M -2M
```
```
XXX.protocol.status.ClientboundStatusResponsePacket +1M -2M
```
```
XXX.protocol.status.ServerboundPingRequestPacket +1M -2M
```
```
XXX.server.commands.TitleCommand +1M -1M
```
```
XXX.server.level.ServerBossEvent +1M -1M
```
```
XXX.server.network.ServerGamePacketListenerImpl$1 +6M -1M | +2P -4P
```
```
XXX.minecraft.sounds.SoundEvents +20P
```
```
XXX.minecraft.tags.BlockTags +6P
```
```
XXX.minecraft.tags.ItemTags +4P
```
```
XXX.level.levelgen.VerticalAnchor$AboveBottom +1M -1M
```
```
XXX.level.levelgen.VerticalAnchor$BelowTop +1M -1M
```
```
XXX.levelgen.carver.CarverConfiguration +5M | +2P -1P
```
```
XXX.levelgen.carver.ConfiguredWorldCarver +2M -2M
```
```
XXX.levelgen.feature.BuriedTreasureFeature +2M -2M
```
```
XXX.levelgen.feature.EndCityFeature +4M -4M
```
```
XXX.levelgen.feature.IglooFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.JigsawFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.JunglePyramidFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter +2M -2M
```
```
XXX.levelgen.feature.MineshaftFeature$MineShaftStart +3M -3M
```
```
XXX.levelgen.feature.NetherFortressFeature +2M -2M
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.StrongholdFeature +2M -2M
```
```
XXX.levelgen.feature.StructureFeature +2M -2M
```
```
XXX.levelgen.feature.SwamplandHutFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart +3M -3M
```
```
XXX.feature.configurations.DripstoneClusterConfiguration +6M -8M | +2P -4P
```
```
XXX.feature.configurations.OreConfiguration +7M -3M | +2P -2P
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftPiece +1M -2M
```
```
XXX.levelgen.structure.NoiseAffectingStructureStart +1M -1M
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +3M -3M
```
```
XXX.levelgen.structure.StructureStart$1 +3M -3M
```
```
XXX.saveddata.maps.MapItemSavedData +1M -1M
```

</details>
























<details>
<summary>
net.minecraft.advancements.Criterion
</summary>

```diff
- void lambda$serializeToNetwork$0(FriendlyByteBuf,Criterion)
```

</details>























































































































































































































































































<details>
<summary>
net.minecraft.network.ConnectionProtocol
</summary>

```diff
- Packet createPacket(PacketFlow,int,FriendlyByteBuf)
+ Packet createPacket(PacketFlow,int)
```

</details>
<details>
<summary>
net.minecraft.network.ConnectionProtocol$PacketSet
</summary>

```diff
- ConnectionProtocol$PacketSet addPacket(Class,Function)
+ ConnectionProtocol$PacketSet addPacket(Class,Supplier)
- Packet createPacket(int,FriendlyByteBuf)
+ Packet createPacket(int)
```

</details>
<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- Collection readCollection(IntFunction,Function)
- IntList readIntIdList()
- List readList(Function)
- Map readMap(Function,Function)
- Map readMap(IntFunction,Function,Function)
- void lambda$readWithCodec$0(CompoundTag,DataResult$PartialResult)
+ void lambda$writeCollection$0(BiConsumer,Object)
- void lambda$writeMap$2(BiConsumer,BiConsumer,Object,Object)
- void lambda$writeWithCodec$1(Object,DataResult$PartialResult)
- void readWithCount(Consumer)
- void writeIntIdList(IntList)
- void writeMap(Map,BiConsumer,BiConsumer)
```

</details>
























<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAddEntityPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAddMobPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAnimatePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
</summary>

```diff
- ClientboundBossEventPacket$OperationType getType()
+ void <clinit>()
- void <init>()
- void dispatch(UUID,ClientboundBossEventPacket$Handler)
- void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
</summary>

```diff
- Suggestion lambda$new$0(StringRange,FriendlyByteBuf)
+ void <init>()
- void <init>(FriendlyByteBuf)
- void lambda$write$1(FriendlyByteBuf,Suggestion)
+ void read(FriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.ClientboundContainerAckPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundDisconnectPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundExplodePacket
</summary>

```diff
- BlockPos lambda$new$0(int,int,int,FriendlyByteBuf)
+ void <init>()
- void <init>(FriendlyByteBuf)
- void lambda$write$1(int,int,int,FriendlyByteBuf,BlockPos)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundGameEventPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRespawnPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void initFields(int)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundStopSoundPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundTagQueryPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
</summary>

```diff
- AttributeModifier lambda$null$0(FriendlyByteBuf)
- ClientboundUpdateAttributesPacket$AttributeSnapshot lambda$new$1(FriendlyByteBuf)
+ void <init>()
- void <init>(FriendlyByteBuf)
- void lambda$null$2(FriendlyByteBuf,AttributeModifier)
- void lambda$write$3(FriendlyByteBuf,ClientboundUpdateAttributesPacket$AttributeSnapshot)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
</summary>

```diff
- ResourceKey lambda$new$0(FriendlyByteBuf)
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void lambda$write$0(FriendlyByteBuf,ResourceKey,TagCollection$NetworkPayload)
- void lambda$write$1(FriendlyByteBuf,ResourceKey)
- void lambda$write$2(FriendlyByteBuf,TagCollection$NetworkPayload)
+ void read(FriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundClientCommandPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundClientInformationPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundContainerAckPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundContainerClickPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundEntityTagQuery
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundPickItemPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundRenameItemPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSwingPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>



<details>
<summary>
net.minecraft.network.protocol.login.ClientboundGameProfilePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.login.ServerboundHelloPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>



<details>
<summary>
net.minecraft.network.protocol.status.ServerboundPingRequestPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


















































































<details>
<summary>
net.minecraft.server.commands.TitleCommand
</summary>

```diff
+ int showTitle(CommandSourceStack,Collection,Component,ClientboundSetTitlesPacket$Type)
- int showTitle(CommandSourceStack,Collection,Component,String,Function)
```

</details>































<details>
<summary>
net.minecraft.server.level.ServerBossEvent
</summary>

```diff
+ void broadcast(ClientboundBossEventPacket$Operation)
- void broadcast(Function)
```

</details>















<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl$1
</summary>

```diff
- InteractionResult lambda$onInteraction$0(Vec3,ServerPlayer,Entity,InteractionHand)
+ void <clinit>()
- void <init>(ServerGamePacketListenerImpl,Entity)
- void onAttack()
- void onInteraction(InteractionHand,Vec3)
- void onInteraction(InteractionHand)
- void performInteraction(InteractionHand,ServerGamePacketListenerImpl$EntityInteraction)
```

</details>







































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
</summary>

```diff
+ int resolveY(DecorationContext)
- int resolveY(WorldGenerationContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
</summary>

```diff
+ int resolveY(DecorationContext)
- int resolveY(WorldGenerationContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarverConfiguration
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- CarverDebugSettings getDebugSettings()
- Float lambda$null$0(CarverConfiguration)
- void <init>(float,CarverDebugSettings)
- void <init>(float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
</summary>

```diff
- boolean carve(CarvingContext,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
+ boolean carve(ChunkAccess,Function,Random,int,int,int,int,int,BitSet)
+ boolean isStartChunk(Random,int,int)
- boolean isStartChunk(Random)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,ProbabilityFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,ProbabilityFeatureConfiguration,LevelHeightAccessor)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndCityFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
- int access$000(ChunkPos,ChunkGenerator,LevelHeightAccessor)
+ int access$000(int,int,ChunkGenerator,LevelHeightAccessor)
- int getYPositionForFeature(ChunkPos,ChunkGenerator,LevelHeightAccessor)
+ int getYPositionForFeature(int,int,ChunkGenerator,LevelHeightAccessor)
```

</details>









<details>
<summary>
net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart
</summary>

```diff
- void <init>(JigsawFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(JigsawFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,JigsawConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,JigsawConfiguration,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
</summary>

```diff
- void <init>(int,Random,FloatProvider,LargeDripstoneFeature$1)
- void <init>(int,Random,FloatProvider)
+ void <init>(int,Random,UniformFloat,LargeDripstoneFeature$1)
+ void <init>(int,Random,UniformFloat)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,MineshaftConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration,LevelHeightAccessor)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,ShipwreckConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration,LevelHeightAccessor)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- StructureStart createStart(ChunkPos,BoundingBox,int,long)
+ StructureStart createStart(int,int,BoundingBox,int,long)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
</summary>

```diff
- App lambda$static$11(RecordCodecBuilder$Instance)
+ App lambda$static$13(RecordCodecBuilder$Instance)
+ Float lambda$null$10(DripstoneClusterConfiguration)
+ Float lambda$null$9(DripstoneClusterConfiguration)
- FloatProvider lambda$null$6(DripstoneClusterConfiguration)
- FloatProvider lambda$null$7(DripstoneClusterConfiguration)
- Integer lambda$null$10(DripstoneClusterConfiguration)
+ Integer lambda$null$11(DripstoneClusterConfiguration)
+ Integer lambda$null$12(DripstoneClusterConfiguration)
- Integer lambda$null$9(DripstoneClusterConfiguration)
+ UniformFloat lambda$null$6(DripstoneClusterConfiguration)
+ UniformFloat lambda$null$7(DripstoneClusterConfiguration)
- void <init>(int,UniformInt,UniformInt,int,int,UniformInt,FloatProvider,FloatProvider,float,int,int)
+ void <init>(int,UniformInt,UniformInt,int,int,UniformInt,UniformFloat,UniformFloat,float,float,float,int,int)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
</summary>

```diff
+ BlockState lambda$null$1(OreConfiguration)
- Float lambda$null$2(OreConfiguration)
- Integer lambda$null$1(OreConfiguration)
+ Integer lambda$null$2(OreConfiguration)
- List lambda$null$0(OreConfiguration)
- OreConfiguration$TargetBlockState target(RuleTest,BlockState)
+ RuleTest lambda$null$0(OreConfiguration)
- void <init>(List,int,float)
- void <init>(List,int)
- void <init>(RuleTest,BlockState,int,float)
```

</details>











































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
</summary>

```diff
+ boolean air(BlockGetter,BlockPos$MutableBlockPos,int,int,int)
- boolean edgesLiquid(BlockGetter,BoundingBox)
+ boolean edgesLiquidOrFloatingInAir(BlockGetter,BoundingBox)
```

</details>












<details>
<summary>
net.minecraft.world.level.levelgen.structure.NoiseAffectingStructureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
```

</details>












<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,OceanRuinConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration,LevelHeightAccessor)
```

</details>


















<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart$1
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,MineshaftConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration,LevelHeightAccessor)
```

</details>

































































































<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- void addClientSideDecorations(List)
+ void addClientSideDecorations(MapDecoration[])
```

</details>

























































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.gui.components.Button
+ net.minecraft.client.gui.components.Button$OnPress
- net.minecraft.client.gui.components.Button$OnTooltip
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.Checkbox
+ net.minecraft.client.gui.components.CommandSuggestions
- net.minecraft.client.gui.components.CommandSuggestions$1
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.ComponentRenderUtils
+ net.minecraft.client.gui.components.ContainerObjectSelectionList
- net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
+ net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$1
+ net.minecraft.client.gui.components.CycleButton$Builder
- net.minecraft.client.gui.components.CycleButton$OnValueChange
+ net.minecraft.client.gui.components.CycleButton$TooltipSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
+ net.minecraft.client.gui.components.DebugScreenOverlay
- net.minecraft.client.gui.components.DebugScreenOverlay$1
+ net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.ImageButton
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.particle.package-info
- net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
+ net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
- net.minecraft.client.particle.SuspendedTownParticle
+ net.minecraft.client.particle.SuspendedTownParticle$1
- net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
+ net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ net.minecraft.client.particle.SuspendedTownParticle$Provider
- net.minecraft.client.particle.TerrainParticle
+ net.minecraft.client.particle.TerrainParticle$Provider
- net.minecraft.client.particle.TextureSheetParticle
+ net.minecraft.client.particle.TotemParticle
- net.minecraft.client.particle.TotemParticle$1
+ net.minecraft.client.particle.TotemParticle$Provider
- net.minecraft.client.particle.TrackingEmitter
+ net.minecraft.client.particle.VibrationSignalParticle
- net.minecraft.client.particle.VibrationSignalParticle$1
+ net.minecraft.client.particle.VibrationSignalParticle$Provider
- net.minecraft.client.particle.WakeParticle
+ net.minecraft.client.particle.WakeParticle$1
- net.minecraft.client.particle.WakeParticle$Provider
+ net.minecraft.client.particle.WaterCurrentDownParticle
- net.minecraft.client.particle.WaterCurrentDownParticle$1
+ net.minecraft.client.particle.WaterCurrentDownParticle$Provider
- net.minecraft.client.particle.WaterDropParticle
+ net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.particle.WhiteAshParticle
+ net.minecraft.client.particle.WhiteAshParticle$Provider
+ net.minecraft.client.player.AbstractClientPlayer
- net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
+ net.minecraft.client.player.KeyboardInput
- net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
- net.minecraft.client.renderer.banner.package-info
+ net.minecraft.client.renderer.BiomeColors
+ net.minecraft.client.renderer.block.BlockModelShaper
- net.minecraft.client.renderer.block.BlockRenderDispatcher
+ net.minecraft.client.renderer.block.BlockRenderDispatcher$1
- net.minecraft.client.renderer.block.LiquidBlockRenderer
- net.minecraft.client.renderer.block.model.BakedQuad
+ net.minecraft.client.renderer.block.model.BlockElement
- net.minecraft.client.renderer.block.model.BlockElement$1
+ net.minecraft.client.renderer.block.model.BlockElement$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementFace
+ net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementRotation
+ net.minecraft.client.renderer.block.model.BlockFaceUV
- net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel
- net.minecraft.client.renderer.block.model.BlockModel$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel$GuiLight
- net.minecraft.client.renderer.block.model.BlockModel$LoopException
+ net.minecraft.client.renderer.block.model.BlockModelDefinition
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
- net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
+ net.minecraft.client.renderer.block.model.FaceBakery
- net.minecraft.client.renderer.block.model.FaceBakery$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator
- net.minecraft.client.renderer.block.model.ItemModelGenerator$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
- net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
+ net.minecraft.client.renderer.block.model.ItemOverride
- net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
+ net.minecraft.client.renderer.block.model.ItemOverride$Predicate
- net.minecraft.client.renderer.block.model.ItemOverrides
+ net.minecraft.client.renderer.block.model.ItemOverrides$1
- net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
+ net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
- net.minecraft.client.renderer.block.model.ItemTransform
+ net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms
+ net.minecraft.client.renderer.block.model.ItemTransforms$1
- net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
- net.minecraft.client.renderer.block.model.multipart.AndCondition
+ net.minecraft.client.renderer.block.model.multipart.Condition
- net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
+ net.minecraft.client.renderer.block.model.multipart.MultiPart
- net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
+ net.minecraft.client.renderer.block.model.multipart.OrCondition
- net.minecraft.client.renderer.block.model.multipart.package-info
- net.minecraft.client.renderer.block.model.multipart.Selector
+ net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
- net.minecraft.client.renderer.block.model.MultiVariant
+ net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
+ net.minecraft.client.renderer.block.model.package-info
- net.minecraft.client.renderer.block.model.Variant
+ net.minecraft.client.renderer.block.model.Variant$Deserializer
+ net.minecraft.client.renderer.block.ModelBlockRenderer
- net.minecraft.client.renderer.block.ModelBlockRenderer$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
+ net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
- net.minecraft.client.renderer.block.package-info
+ net.minecraft.client.renderer.block.statemap.package-info
- net.minecraft.client.renderer.blockentity.BannerRenderer
+ net.minecraft.client.renderer.blockentity.BeaconRenderer
- net.minecraft.client.renderer.blockentity.BedRenderer
+ net.minecraft.client.renderer.blockentity.BellRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
- net.minecraft.client.renderer.blockentity.BlockEntityRenderers
+ net.minecraft.client.renderer.blockentity.BrightnessCombiner
- net.minecraft.client.renderer.blockentity.CampfireRenderer
+ net.minecraft.client.renderer.blockentity.ChestRenderer
- net.minecraft.client.renderer.blockentity.ConduitRenderer
+ net.minecraft.client.renderer.blockentity.EnchantTableRenderer
- net.minecraft.client.renderer.blockentity.LecternRenderer
+ net.minecraft.client.renderer.blockentity.package-info
+ net.minecraft.client.renderer.blockentity.PistonHeadRenderer
- net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
+ net.minecraft.client.renderer.blockentity.SkullBlockRenderer
- net.minecraft.client.renderer.blockentity.SpawnerRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
+ net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
- net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
- net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
- net.minecraft.client.renderer.chunk.package-info
- net.minecraft.client.renderer.chunk.RenderChunkRegion
+ net.minecraft.client.renderer.chunk.VisGraph
- net.minecraft.client.renderer.chunk.VisGraph$1
+ net.minecraft.client.renderer.chunk.VisibilitySet
+ net.minecraft.client.renderer.ChunkBufferBuilderPack
- net.minecraft.client.renderer.CubeMap
+ net.minecraft.client.renderer.culling.Frustum
- net.minecraft.client.renderer.culling.package-info
+ net.minecraft.client.renderer.debug.BeeDebugRenderer
- net.minecraft.client.renderer.debug.BeeDebugRenderer$BeeInfo
+ net.minecraft.client.renderer.debug.BeeDebugRenderer$HiveInfo
- net.minecraft.client.renderer.debug.BrainDebugRenderer
+ net.minecraft.client.renderer.debug.BrainDebugRenderer$BrainDump
- net.minecraft.client.renderer.debug.BrainDebugRenderer$PoiInfo
+ net.minecraft.client.renderer.debug.CaveDebugRenderer
+ net.minecraft.client.renderer.DimensionSpecialEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
- net.minecraft.client.renderer.EffectInstance
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$1
+ net.minecraft.client.renderer.FaceInfo$Constants
- net.minecraft.client.renderer.FaceInfo$VertexInfo
+ net.minecraft.client.renderer.FogRenderer
- net.minecraft.client.renderer.FogRenderer$FogMode
+ net.minecraft.client.renderer.GameRenderer
- net.minecraft.client.renderer.GpuWarnlistManager
+ net.minecraft.client.renderer.GpuWarnlistManager$1
- net.minecraft.client.renderer.GpuWarnlistManager$Preparations
+ net.minecraft.client.renderer.ItemBlockRenderTypes
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
- net.minecraft.client.renderer.ItemInHandRenderer$HandRenderSelection
+ net.minecraft.client.renderer.ItemModelShaper
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$1
- net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
+ net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
- net.minecraft.client.renderer.LightTexture
+ net.minecraft.client.renderer.MultiBufferSource
- net.minecraft.client.renderer.MultiBufferSource$BufferSource
+ net.minecraft.client.renderer.OutlineBufferSource
- net.minecraft.client.renderer.OutlineBufferSource$1
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.PanoramaRenderer
+ net.minecraft.client.renderer.PostChain
- net.minecraft.client.renderer.PostPass
+ net.minecraft.client.renderer.Rect2i
- net.minecraft.client.renderer.RenderBuffers
+ net.minecraft.client.renderer.RenderStateShard
- net.minecraft.client.renderer.RenderStateShard$AlphaStateShard
+ net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
- net.minecraft.client.renderer.RenderStateShard$CullStateShard
+ net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
- net.minecraft.client.renderer.RenderStateShard$DiffuseLightingStateShard
+ net.minecraft.client.renderer.RenderStateShard$FogStateShard
- net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
+ net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
- net.minecraft.client.renderer.RenderStateShard$LineStateShard
+ net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$OutputStateShard
+ net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
- net.minecraft.client.renderer.RenderStateShard$PortalTexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$ShadeModelStateShard
- net.minecraft.client.renderer.RenderStateShard$TextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
+ net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
- net.minecraft.client.renderer.RenderType
+ net.minecraft.client.renderer.RenderType$1
- net.minecraft.client.renderer.RenderType$CompositeRenderType
+ net.minecraft.client.renderer.RenderType$CompositeRenderType$EqualsStrategy
- net.minecraft.client.renderer.RenderType$CompositeState
+ net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- net.minecraft.client.renderer.RenderType$OutlineProperty
+ net.minecraft.client.renderer.RunningTrimmedMean
- net.minecraft.client.renderer.ScreenEffectRenderer
+ net.minecraft.client.renderer.Sheets
- net.minecraft.client.renderer.Sheets$1
+ net.minecraft.client.renderer.SpriteCoordinateExpander
- net.minecraft.client.renderer.ViewArea
+ net.minecraft.client.renderer.VirtualScreen
+ net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.particles.VibrationParticleOption$1
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.BlockFamilies
+ net.minecraft.data.BlockFamily
- net.minecraft.data.BlockFamily$1
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.BuiltinRegistries
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.HashCache
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLoot
- net.minecraft.data.loot.ChestLoot
+ net.minecraft.data.loot.EntityLoot
- net.minecraft.data.loot.FishingLoot
+ net.minecraft.data.loot.GiftLoot
- net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.PiglinBarterLoot
+ net.minecraft.data.Main
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChatPacket
- net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLoginPacket
- net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
+ net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
- net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ClientboundOpenBookPacket
- net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
+ net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
- net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$3
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$5
- net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
- net.minecraft.util.ClampedNormalFloat
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.ConstantFloat
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.CauldronRenameFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.DyeItemRenameFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ net.minecraft.util.datafix.fixes.NamedEntityFix
- net.minecraft.util.datafix.fixes.NewVillageFix
+ net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
- net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
+ net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenameBiomesFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.SwimStatsRenameFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
+ net.minecraft.util.datafix.schemas.V100
- net.minecraft.util.datafix.schemas.V102
+ net.minecraft.util.datafix.schemas.V1022
- net.minecraft.util.datafix.schemas.V106
+ net.minecraft.util.datafix.schemas.V107
- net.minecraft.util.datafix.schemas.V1125
+ net.minecraft.util.datafix.schemas.V135
- net.minecraft.util.datafix.schemas.V143
+ net.minecraft.util.datafix.schemas.V1451
- net.minecraft.util.datafix.schemas.V1451_1
+ net.minecraft.util.datafix.schemas.V1451_2
- net.minecraft.util.datafix.schemas.V1451_3
+ net.minecraft.util.datafix.schemas.V1451_4
- net.minecraft.util.datafix.schemas.V1451_5
+ net.minecraft.util.datafix.schemas.V1451_6
- net.minecraft.util.datafix.schemas.V1451_7
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1460$1
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2686
+ net.minecraft.util.datafix.schemas.V2688
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.FloatProvider
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$1
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.TrapezoidFloat
+ net.minecraft.util.Tuple
- net.minecraft.util.UniformFloat
+ net.minecraft.util.UniformInt
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
+ net.minecraft.world.damagesource.BadRespawnPointDamage
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.EntityDamageSource
+ net.minecraft.world.damagesource.IndirectEntityDamageSource
- net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsoptionMobEffect
- net.minecraft.world.effect.AttackDamageMobEffect
+ net.minecraft.world.effect.HealthBoostMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.AttributeMap
- net.minecraft.world.entity.ai.attributes.AttributeModifier
+ net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
+ net.minecraft.world.entity.ai.attributes.DefaultAttributes
+ net.minecraft.world.entity.ai.attributes.package-info
- net.minecraft.world.entity.ai.attributes.RangedAttribute
- net.minecraft.world.entity.ai.behavior.AcquirePoi
+ net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
- net.minecraft.world.entity.ai.behavior.AnimalMakeLove
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownTemptationTicks
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.RandomSwim
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunIf
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.RunSometimes
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WeightedList
+ net.minecraft.world.entity.ai.behavior.WeightedList$1
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.PlayGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.TakeFlowerGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$1
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlHostileSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HostilesSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
+ net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.AirRandomPos
+ net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
+ net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
- net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
+ net.minecraft.world.entity.animal.Bee
- net.minecraft.world.entity.animal.Bee$1
+ net.minecraft.world.entity.animal.Bee$BaseBeeGoal
- net.minecraft.world.entity.animal.Bee$BeeAttackGoal
+ net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
- net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
- net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
+ net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeLookControl
+ net.minecraft.world.entity.animal.Bee$BeePollinateGoal
- net.minecraft.world.entity.animal.Bee$BeeWanderGoal
+ net.minecraft.world.entity.animal.Bucketable
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$1
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$1
+ net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
- net.minecraft.world.entity.animal.Fox$FaceplantGoal
+ net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
- net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
+ net.minecraft.world.entity.animal.Fox$FoxBreedGoal
- net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
+ net.minecraft.world.entity.animal.Fox$FoxFloatGoal
- net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
+ net.minecraft.world.entity.animal.Fox$FoxGroupData
- net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Fox$FoxLookControl
- net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
+ net.minecraft.world.entity.animal.Fox$FoxMoveControl
- net.minecraft.world.entity.animal.Fox$FoxPanicGoal
+ net.minecraft.world.entity.animal.Fox$FoxPounceGoal
- net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
+ net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
- net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
+ net.minecraft.world.entity.animal.Fox$SeekShelterGoal
- net.minecraft.world.entity.animal.Fox$SleepGoal
+ net.minecraft.world.entity.animal.Fox$StalkPreyGoal
- net.minecraft.world.entity.animal.Fox$Type
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$1
- net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
+ net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
- net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
+ net.minecraft.world.entity.animal.horse.Markings
- net.minecraft.world.entity.animal.horse.Mule
+ net.minecraft.world.entity.animal.horse.package-info
+ net.minecraft.world.entity.animal.horse.SkeletonHorse
- net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
+ net.minecraft.world.entity.animal.horse.TraderLlama
- net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ net.minecraft.world.entity.animal.horse.Variant
- net.minecraft.world.entity.animal.horse.ZombieHorse
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.IronGolem$Crackiness
+ net.minecraft.world.entity.animal.MushroomCow
- net.minecraft.world.entity.animal.MushroomCow$MushroomType
+ net.minecraft.world.entity.animal.Ocelot
- net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
- net.minecraft.world.entity.animal.package-info
- net.minecraft.world.entity.animal.Panda
+ net.minecraft.world.entity.animal.Panda$Gene
- net.minecraft.world.entity.animal.Panda$PandaAttackGoal
+ net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
- net.minecraft.world.entity.animal.Panda$PandaBreedGoal
+ net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
- net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
+ net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
- net.minecraft.world.entity.animal.Panda$PandaMoveControl
+ net.minecraft.world.entity.animal.Panda$PandaPanicGoal
- net.minecraft.world.entity.animal.Panda$PandaRollGoal
+ net.minecraft.world.entity.animal.Panda$PandaSitGoal
- net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
+ net.minecraft.world.entity.animal.Parrot
- net.minecraft.world.entity.animal.Parrot$1
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$1
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$1
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$1
+ net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
- net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
- net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
+ net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
- net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.boss.enderdragon.EndCrystal
+ net.minecraft.world.entity.boss.enderdragon.EnderDragon
- net.minecraft.world.entity.boss.enderdragon.package-info
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
+ net.minecraft.world.entity.boss.enderdragon.phases.package-info
+ net.minecraft.world.entity.boss.EnderDragonPart
- net.minecraft.world.entity.boss.package-info
+ net.minecraft.world.entity.boss.wither.package-info
+ net.minecraft.world.entity.boss.wither.WitherBoss
- net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
- net.minecraft.world.entity.decoration.ArmorStand
+ net.minecraft.world.entity.decoration.ArmorStand$1
- net.minecraft.world.entity.decoration.HangingEntity
+ net.minecraft.world.entity.decoration.HangingEntity$1
- net.minecraft.world.entity.decoration.ItemFrame
+ net.minecraft.world.entity.decoration.ItemFrame$1
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.Entity$MovementEmission
+ net.minecraft.world.entity.Entity$RemovalReason
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$1
- net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
- net.minecraft.world.entity.monster.Ghast
+ net.minecraft.world.entity.monster.Ghast$GhastLookGoal
- net.minecraft.world.entity.monster.Ghast$GhastMoveControl
+ net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
- net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
+ net.minecraft.world.entity.monster.Giant
- net.minecraft.world.entity.monster.Guardian
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
- net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
+ net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.hoglin.package-info
- net.minecraft.world.entity.monster.Husk
+ net.minecraft.world.entity.monster.Illusioner
- net.minecraft.world.entity.monster.Illusioner$1
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$1
+ net.minecraft.world.entity.monster.Phantom$AttackPhase
- net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
- net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
+ net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- net.minecraft.world.entity.monster.Phantom$PhantomLookControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
+ net.minecraft.world.entity.monster.piglin.AbstractPiglin
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.PiglinAi
- net.minecraft.world.entity.monster.piglin.PiglinArmPose
+ net.minecraft.world.entity.monster.piglin.PiglinBrute
- net.minecraft.world.entity.monster.piglin.PiglinBruteAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- net.minecraft.world.entity.monster.Pillager
+ net.minecraft.world.entity.monster.RangedAttackMob
- net.minecraft.world.entity.monster.Ravager
+ net.minecraft.world.entity.monster.Ravager$1
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$1
+ net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
- net.minecraft.world.entity.monster.Strider$1
+ net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
- net.minecraft.world.entity.monster.Strider$StriderPathNavigation
+ net.minecraft.world.entity.monster.Vex
- net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
+ net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
- net.minecraft.world.entity.monster.Vex$VexMoveControl
+ net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
- net.minecraft.world.entity.monster.Vindicator
+ net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
- net.minecraft.world.entity.monster.Witch
+ net.minecraft.world.entity.monster.WitherSkeleton
- net.minecraft.world.entity.monster.Zoglin
+ net.minecraft.world.entity.monster.Zombie
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
+ net.minecraft.world.entity.npc.Villager
- net.minecraft.world.entity.npc.VillagerData
+ net.minecraft.world.entity.npc.VillagerDataHolder
- net.minecraft.world.entity.npc.VillagerProfession
+ net.minecraft.world.entity.npc.VillagerTrades
- net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.AbstractArrow
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacements$Type
- net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$1
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.CraftingContainer
- net.minecraft.world.inventory.CraftingMenu
+ net.minecraft.world.inventory.DataSlot
- net.minecraft.world.inventory.DataSlot$1
+ net.minecraft.world.inventory.DataSlot$2
- net.minecraft.world.inventory.DataSlot$3
+ net.minecraft.world.inventory.DispenserMenu
- net.minecraft.world.inventory.EnchantmentMenu
+ net.minecraft.world.inventory.EnchantmentMenu$1
- net.minecraft.world.inventory.EnchantmentMenu$2
+ net.minecraft.world.inventory.EnchantmentMenu$3
- net.minecraft.world.inventory.FurnaceFuelSlot
+ net.minecraft.world.inventory.FurnaceMenu
- net.minecraft.world.inventory.FurnaceResultSlot
+ net.minecraft.world.inventory.GrindstoneMenu
- net.minecraft.world.inventory.GrindstoneMenu$1
+ net.minecraft.world.inventory.GrindstoneMenu$2
- net.minecraft.world.inventory.GrindstoneMenu$3
+ net.minecraft.world.inventory.GrindstoneMenu$4
- net.minecraft.world.inventory.HopperMenu
+ net.minecraft.world.inventory.HorseInventoryMenu
- net.minecraft.world.inventory.HorseInventoryMenu$1
+ net.minecraft.world.inventory.HorseInventoryMenu$2
- net.minecraft.world.inventory.InventoryMenu
+ net.minecraft.world.inventory.InventoryMenu$1
- net.minecraft.world.inventory.InventoryMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu
- net.minecraft.world.inventory.ItemCombinerMenu$1
+ net.minecraft.world.inventory.ItemCombinerMenu$2
- net.minecraft.world.inventory.LecternMenu
+ net.minecraft.world.inventory.LecternMenu$1
- net.minecraft.world.inventory.LoomMenu
+ net.minecraft.world.inventory.LoomMenu$1
- net.minecraft.world.inventory.LoomMenu$2
+ net.minecraft.world.inventory.LoomMenu$3
- net.minecraft.world.inventory.LoomMenu$4
+ net.minecraft.world.inventory.LoomMenu$5
- net.minecraft.world.inventory.LoomMenu$6
+ net.minecraft.world.inventory.MenuConstructor
- net.minecraft.world.inventory.MenuType
+ net.minecraft.world.inventory.MenuType$MenuSupplier
- net.minecraft.world.inventory.MerchantContainer
+ net.minecraft.world.inventory.MerchantMenu
- net.minecraft.world.inventory.MerchantResultSlot
+ net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
- net.minecraft.world.inventory.RecipeHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$1
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
- net.minecraft.world.item.crafting.package-info
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
+ net.minecraft.world.item.crafting.SimpleRecipeSerializer
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmokingRecipe
+ net.minecraft.world.item.crafting.StonecutterRecipe
- net.minecraft.world.item.crafting.SuspiciousStewRecipe
+ net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$11
- net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$2
- net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$4
- net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$6
- net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$8
- net.minecraft.world.item.CreativeModeTab$9
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
+ net.minecraft.world.item.enchantment.ArrowDamageEnchantment
- net.minecraft.world.item.enchantment.ArrowFireEnchantment
+ net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
- net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
+ net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
- net.minecraft.world.item.enchantment.BindingCurseEnchantment
+ net.minecraft.world.item.enchantment.DamageEnchantment
- net.minecraft.world.item.enchantment.DigDurabilityEnchantment
+ net.minecraft.world.item.enchantment.DiggingEnchantment
- net.minecraft.world.item.enchantment.Enchantment
+ net.minecraft.world.item.enchantment.Enchantment$Rarity
- net.minecraft.world.item.enchantment.EnchantmentCategory
+ net.minecraft.world.item.enchantment.EnchantmentCategory$1
- net.minecraft.world.item.enchantment.EnchantmentCategory$10
+ net.minecraft.world.item.enchantment.EnchantmentCategory$11
- net.minecraft.world.item.enchantment.EnchantmentCategory$12
+ net.minecraft.world.item.enchantment.EnchantmentCategory$13
- net.minecraft.world.item.enchantment.EnchantmentCategory$14
+ net.minecraft.world.item.enchantment.EnchantmentCategory$2
- net.minecraft.world.item.enchantment.EnchantmentCategory$3
+ net.minecraft.world.item.enchantment.EnchantmentCategory$4
- net.minecraft.world.item.enchantment.EnchantmentCategory$5
+ net.minecraft.world.item.enchantment.EnchantmentCategory$6
- net.minecraft.world.item.enchantment.EnchantmentCategory$7
+ net.minecraft.world.item.enchantment.EnchantmentCategory$8
- net.minecraft.world.item.enchantment.EnchantmentCategory$9
+ net.minecraft.world.item.enchantment.EnchantmentHelper
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
- net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
- net.minecraft.world.item.enchantment.FishingSpeedEnchantment
+ net.minecraft.world.item.enchantment.FrostWalkerEnchantment
- net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
- net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
+ net.minecraft.world.item.enchantment.ProtectionEnchantment
- net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$1
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateParameters
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$1
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$1
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$NoiseParameters
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
- net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
+ net.minecraft.world.level.block.AbstractCauldronBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractGlassBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
+ net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock
+ net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.AzaleaBlock
+ net.minecraft.world.level.block.BambooBlock
- net.minecraft.world.level.block.BambooSaplingBlock
+ net.minecraft.world.level.block.BannerBlock
- net.minecraft.world.level.block.BarrelBlock
+ net.minecraft.world.level.block.BarrierBlock
- net.minecraft.world.level.block.BaseCoralFanBlock
+ net.minecraft.world.level.block.BaseCoralPlantBlock
- net.minecraft.world.level.block.BaseCoralPlantTypeBlock
+ net.minecraft.world.level.block.BaseCoralWallFanBlock
- net.minecraft.world.level.block.BaseEntityBlock
+ net.minecraft.world.level.block.BaseFireBlock
- net.minecraft.world.level.block.BasePressurePlateBlock
+ net.minecraft.world.level.block.BaseRailBlock
- net.minecraft.world.level.block.BaseRailBlock$1
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BigDripleafBlock
- net.minecraft.world.level.block.BigDripleafStemBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$BlockStatePairKey
+ net.minecraft.world.level.block.Blocks
- net.minecraft.world.level.block.BonemealableBlock
+ net.minecraft.world.level.block.BrewingStandBlock
- net.minecraft.world.level.block.BubbleColumnBlock
+ net.minecraft.world.level.block.BucketPickup
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CandleCakeBlock
+ net.minecraft.world.level.block.CarpetBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.CaveVinesBlock
+ net.minecraft.world.level.block.CaveVinesBodyBlock
- net.minecraft.world.level.block.CaveVinesHeadBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChorusFlowerBlock
+ net.minecraft.world.level.block.ChorusPlantBlock
- net.minecraft.world.level.block.CocoaBlock
+ net.minecraft.world.level.block.CocoaBlock$1
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DetectorRailBlock
- net.minecraft.world.level.block.DetectorRailBlock$1
+ net.minecraft.world.level.block.DiodeBlock
- net.minecraft.world.level.block.DirectionalBlock
+ net.minecraft.world.level.block.DirtPathBlock
- net.minecraft.world.level.block.DispenserBlock
+ net.minecraft.world.level.block.DoorBlock
- net.minecraft.world.level.block.DoorBlock$1
+ net.minecraft.world.level.block.DoubleBlockCombiner
- net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
+ net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ net.minecraft.world.level.block.DoublePlantBlock
- net.minecraft.world.level.block.DragonEggBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BellBlockEntity
+ net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
+ net.minecraft.world.level.block.entity.BlockEntityType
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ net.minecraft.world.level.block.Fallable
- net.minecraft.world.level.block.FallingBlock
+ net.minecraft.world.level.block.FarmBlock
- net.minecraft.world.level.block.FenceBlock
+ net.minecraft.world.level.block.FenceGateBlock
- net.minecraft.world.level.block.FenceGateBlock$1
+ net.minecraft.world.level.block.FireBlock
- net.minecraft.world.level.block.FletchingTableBlock
+ net.minecraft.world.level.block.FlowerBlock
- net.minecraft.world.level.block.FlowerPotBlock
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GlowLichenBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GravelBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.GrowingPlantBlock
+ net.minecraft.world.level.block.GrowingPlantBodyBlock
- net.minecraft.world.level.block.GrowingPlantHeadBlock
+ net.minecraft.world.level.block.HalfTransparentBlock
- net.minecraft.world.level.block.HangingRootsBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.IronBarsBlock
- net.minecraft.world.level.block.JigsawBlock
+ net.minecraft.world.level.block.JukeboxBlock
- net.minecraft.world.level.block.KelpBlock
+ net.minecraft.world.level.block.KelpPlantBlock
- net.minecraft.world.level.block.LadderBlock
+ net.minecraft.world.level.block.LadderBlock$1
- net.minecraft.world.level.block.LanternBlock
+ net.minecraft.world.level.block.LavaCauldronBlock
- net.minecraft.world.level.block.LayeredCauldronBlock
+ net.minecraft.world.level.block.LeavesBlock
- net.minecraft.world.level.block.LecternBlock
+ net.minecraft.world.level.block.LecternBlock$1
- net.minecraft.world.level.block.LevelEvent
+ net.minecraft.world.level.block.LeverBlock
- net.minecraft.world.level.block.LeverBlock$1
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
- net.minecraft.world.level.block.NetherrackBlock
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
+ net.minecraft.world.level.block.NetherWartBlock
+ net.minecraft.world.level.block.NoteBlock
- net.minecraft.world.level.block.NyliumBlock
+ net.minecraft.world.level.block.ObserverBlock
- net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
+ net.minecraft.world.level.block.piston.PistonMath$1
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RespawnAnchorBlock$1
+ net.minecraft.world.level.block.RodBlock
- net.minecraft.world.level.block.RodBlock$1
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmallDripleafBlock
+ net.minecraft.world.level.block.SmithingTableBlock
- net.minecraft.world.level.block.SmokerBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
+ net.minecraft.world.level.block.SporeBlossomBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$1
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$1
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ChunkTickList
+ net.minecraft.world.level.ChunkTickList$1
- net.minecraft.world.level.ChunkTickList$ScheduledTick
+ net.minecraft.world.level.ClipBlockStateContext
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.CollisionSpliterator
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
- net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.NoiseEffect
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
- net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelTimeAccess
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
- net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.Snooper
+ net.minecraft.world.Snooper$1
- net.minecraft.world.SnooperPopulator
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.advancements.AdvancementProgress +2M
```
```
XXX.gui.components.BossHealthOverlay +1M
```
```
XXX.client.multiplayer.ClientPacketListener +27M -14M
```
```
XXX.client.particle.Particle +1M
```
```
XXX.client.particle.ParticleEngine +4M -1M | +1P
```
```
XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider -1P
```
```
XXX.renderer.debug.DebugRenderer -1P
```
```
XXX.data.worldgen.Carvers +1P
```
```
XXX.data.worldgen.Features +10P
```
```
XXX.minecraft.network.ConnectionProtocol +1M -1M
```
```
XXX.minecraft.network.ConnectionProtocol$PacketSet +2M -2M | +1P -1P
```
```
XXX.minecraft.network.FriendlyByteBuf +11M -1M
```
```
XXX.network.protocol.Packet -1P
```
```
XXX.protocol.game.ClientboundAddEntityPacket +1M -2M
```
```
XXX.protocol.game.ClientboundAddMobPacket +1M -2M
```
```
XXX.protocol.game.ClientboundAddPlayerPacket +1M -2M
```
```
XXX.protocol.game.ClientboundAnimatePacket +1M -2M
```
```
XXX.protocol.game.ClientboundBlockBreakAckPacket +1M -2M
```
```
XXX.protocol.game.ClientboundBlockEntityDataPacket +1M -2M
```
```
XXX.protocol.game.ClientboundBlockUpdatePacket +1M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$1 +4M -1M | -1P
```
```
XXX.protocol.game.ClientboundCommandSuggestionsPacket +3M -2M
```
```
XXX.protocol.game.ClientboundContainerAckPacket +1M -2M
```
```
XXX.protocol.game.ClientboundContainerSetContentPacket +1M -2M
```
```
XXX.protocol.game.ClientboundContainerSetSlotPacket +1M -2M
```
```
XXX.protocol.game.ClientboundCustomPayloadPacket +1M -2M | -1P
```
```
XXX.protocol.game.ClientboundDisconnectPacket +1M -2M
```
```
XXX.protocol.game.ClientboundExplodePacket +3M -2M
```
```
XXX.protocol.game.ClientboundGameEventPacket +1M -2M
```
```
XXX.protocol.game.ClientboundHorseScreenOpenPacket +1M -2M
```
```
XXX.protocol.game.ClientboundPlayerLookAtPacket +1M -2M
```
```
XXX.protocol.game.ClientboundRemoveMobEffectPacket +1M -2M
```
```
XXX.protocol.game.ClientboundRespawnPacket +1M -2M
```
```
XXX.protocol.game.ClientboundSectionBlocksUpdatePacket +1M -3M
```
```
XXX.protocol.game.ClientboundSoundEntityPacket +1M -2M
```
```
XXX.protocol.game.ClientboundStopSoundPacket +1M -2M
```
```
XXX.protocol.game.ClientboundTagQueryPacket +1M -2M
```
```
XXX.protocol.game.ClientboundTeleportEntityPacket +1M -2M
```
```
XXX.protocol.game.ClientboundUpdateAttributesPacket +5M -2M
```
```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +1M -2M
```
```
XXX.protocol.game.ClientboundUpdateTagsPacket +4M -3M
```
```
XXX.protocol.game.ServerboundAcceptTeleportationPacket +1M -2M
```
```
XXX.protocol.game.ServerboundChangeDifficultyPacket +1M -2M
```
```
XXX.protocol.game.ServerboundClientCommandPacket +1M -2M
```
```
XXX.protocol.game.ServerboundClientInformationPacket +1M -2M
```
```
XXX.protocol.game.ServerboundContainerAckPacket +1M -2M
```
```
XXX.protocol.game.ServerboundContainerClickPacket +1M -2M
```
```
XXX.protocol.game.ServerboundCustomPayloadPacket +1M -2M
```
```
XXX.protocol.game.ServerboundEntityTagQuery +1M -2M
```
```
XXX.protocol.game.ServerboundMoveVehiclePacket +1M -2M
```
```
XXX.protocol.game.ServerboundPickItemPacket +1M -2M
```
```
XXX.protocol.game.ServerboundPlayerAbilitiesPacket +1M -2M
```
```
XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket +1M -2M
```
```
XXX.protocol.game.ServerboundRenameItemPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSetBeaconPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSetCommandBlockPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSetCreativeModeSlotPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSetStructureBlockPacket +1M -2M
```
```
XXX.protocol.game.ServerboundSwingPacket +1M -2M
```
```
XXX.protocol.game.ServerboundUseItemOnPacket +1M -2M
```
```
XXX.protocol.login.ClientboundGameProfilePacket +1M -2M
```
```
XXX.protocol.login.ClientboundLoginCompressionPacket +1M -2M
```
```
XXX.protocol.login.ServerboundHelloPacket +1M -2M
```
```
XXX.protocol.status.ClientboundStatusResponsePacket +1M -2M
```
```
XXX.protocol.status.ServerboundPingRequestPacket +1M -2M
```
```
XXX.server.commands.TitleCommand +1M -1M
```
```
XXX.server.level.ServerBossEvent +1M -1M
```
```
XXX.server.network.ServerGamePacketListenerImpl$1 +6M -1M | +2P -4P
```
```
XXX.minecraft.sounds.SoundEvents +20P
```
```
XXX.minecraft.tags.BlockTags +6P
```
```
XXX.minecraft.tags.ItemTags +4P
```
```
XXX.level.levelgen.VerticalAnchor$AboveBottom +1M -1M
```
```
XXX.level.levelgen.VerticalAnchor$BelowTop +1M -1M
```
```
XXX.levelgen.carver.CarverConfiguration +5M | +2P -1P
```
```
XXX.levelgen.carver.ConfiguredWorldCarver +2M -2M
```
```
XXX.levelgen.feature.BuriedTreasureFeature +2M -2M
```
```
XXX.levelgen.feature.EndCityFeature +4M -4M
```
```
XXX.levelgen.feature.IglooFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.JigsawFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.JunglePyramidFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter +2M -2M
```
```
XXX.levelgen.feature.MineshaftFeature$MineShaftStart +3M -3M
```
```
XXX.levelgen.feature.NetherFortressFeature +2M -2M
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.StrongholdFeature +2M -2M
```
```
XXX.levelgen.feature.StructureFeature +2M -2M
```
```
XXX.levelgen.feature.SwamplandHutFeature$FeatureStart +3M -3M
```
```
XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart +3M -3M
```
```
XXX.feature.configurations.DripstoneClusterConfiguration +6M -8M | +2P -4P
```
```
XXX.feature.configurations.OreConfiguration +7M -3M | +2P -2P
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftPiece +1M -2M
```
```
XXX.levelgen.structure.NoiseAffectingStructureStart +1M -1M
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +3M -3M
```
```
XXX.levelgen.structure.StructureStart$1 +3M -3M
```
```
XXX.saveddata.maps.MapItemSavedData +1M -1M
```

</details>




































































































































































<details>
<summary>
net.minecraft.advancements.AdvancementProgress
</summary>

```diff
- void <init>(Map)
- void lambda$serializeToNetwork$1(FriendlyByteBuf,CriterionProgress)
```

</details>





















































































































<details>
<summary>
net.minecraft.client.gui.components.BossHealthOverlay
</summary>

```diff
- Map access$000(BossHealthOverlay)
```

</details>





































































































































































































































<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
- IllegalArgumentException lambda$handleCustomPayload$10(ResourceLocation)
+ IllegalArgumentException lambda$handleCustomPayload$9(ResourceLocation)
- void handleInitializeBorder(ClientboundInitializeBorderPacket)
+ void handlePlayerCombat(ClientboundPlayerCombatPacket)
- void handlePlayerCombatEnd(ClientboundPlayerCombatEndPacket)
- void handlePlayerCombatEnter(ClientboundPlayerCombatEnterPacket)
- void handlePlayerCombatKill(ClientboundPlayerCombatKillPacket)
+ void handleSetBorder(ClientboundSetBorderPacket)
- void handleSetBorderCenter(ClientboundSetBorderCenterPacket)
- void handleSetBorderLerpSize(ClientboundSetBorderLerpSizePacket)
- void handleSetBorderSize(ClientboundSetBorderSizePacket)
- void handleSetBorderWarningDelay(ClientboundSetBorderWarningDelayPacket)
- void handleSetBorderWarningDistance(ClientboundSetBorderWarningDistancePacket)
+ void handleSetTitles(ClientboundSetTitlesPacket)
- void handleTitlesClear(ClientboundClearTitlesPacket)
+ void lambda$downloadCallback$7()
- void lambda$downloadCallback$8()
+ Void lambda$downloadCallback$8(Throwable)
- Void lambda$downloadCallback$9(Throwable)
+ void lambda$handleAddOrRemoveRecipes$3(ClientRecipeBook,Recipe)
- void lambda$handleAddOrRemoveRecipes$4(ClientRecipeBook,Recipe)
+ void lambda$handleAddOrRemoveRecipes$4(ClientRecipeBook,RecipeCollection)
- void lambda$handleAddOrRemoveRecipes$5(ClientRecipeBook,RecipeCollection)
+ void lambda$handleChunkBlocksUpdate$0(int,BlockPos,BlockState)
- void lambda$handleChunkBlocksUpdate$1(int,BlockPos,BlockState)
+ void lambda$handleGameEvent$2()
- void lambda$handleGameEvent$3()
+ void lambda$handlePlaceRecipe$10(AbstractContainerMenu,Recipe)
- void lambda$handlePlaceRecipe$12(AbstractContainerMenu,Recipe)
- void lambda$handleRemoveEntity$0(int)
+ void lambda$handleResourcePack$6(String,String,boolean)
- void lambda$handleResourcePack$7(String,String,boolean)
+ void lambda$handleSetEquipment$1(Entity,Pair)
- void lambda$handleSetEquipment$2(Entity,Pair)
- void lambda$handleSetPlayerTeamPacket$11(PlayerTeam,ClientboundSetPlayerTeamPacket$Parameters)
+ void lambda$null$5(String,String,boolean,boolean)
- void lambda$null$6(String,String,boolean,boolean)
- void setActionBarText(ClientboundSetActionBarTextPacket)
- void setSubtitleText(ClientboundSetSubtitleTextPacket)
- void setTitlesAnimation(ClientboundSetTitlesAnimationPacket)
- void setTitleText(ClientboundSetTitleTextPacket)
```

</details>
































































<details>
<summary>
net.minecraft.client.particle.Particle
</summary>

```diff
- Optional getParticleGroup()
```

</details>
<details>
<summary>
net.minecraft.client.particle.ParticleEngine
</summary>

```diff
- boolean hasSpaceInParticleLimit(ParticleGroup)
- void lambda$destroy$10(BlockPos,BlockState,double,double,double,double,double,double)
+ void lambda$destroy$9(BlockPos,BlockState,double,double,double,double,double,double)
- void lambda$tickParticleList$9(ParticleGroup)
- void updateCount(ParticleGroup,int)
```

</details>






























































































































































































































































































































































































































<details>
<summary>
net.minecraft.network.ConnectionProtocol
</summary>

```diff
- Packet createPacket(PacketFlow,int,FriendlyByteBuf)
+ Packet createPacket(PacketFlow,int)
```

</details>
<details>
<summary>
net.minecraft.network.ConnectionProtocol$PacketSet
</summary>

```diff
- ConnectionProtocol$PacketSet addPacket(Class,Function)
+ ConnectionProtocol$PacketSet addPacket(Class,Supplier)
- Packet createPacket(int,FriendlyByteBuf)
+ Packet createPacket(int)
```

</details>
<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- Collection readCollection(IntFunction,Function)
- IntList readIntIdList()
- List readList(Function)
- Map readMap(Function,Function)
- Map readMap(IntFunction,Function,Function)
- void lambda$readWithCodec$0(CompoundTag,DataResult$PartialResult)
+ void lambda$writeCollection$0(BiConsumer,Object)
- void lambda$writeMap$2(BiConsumer,BiConsumer,Object,Object)
- void lambda$writeWithCodec$1(Object,DataResult$PartialResult)
- void readWithCount(Consumer)
- void writeIntIdList(IntList)
- void writeMap(Map,BiConsumer,BiConsumer)
```

</details>
























<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAddEntityPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAddMobPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundAnimatePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
</summary>

```diff
- ClientboundBossEventPacket$OperationType getType()
+ void <clinit>()
- void <init>()
- void dispatch(UUID,ClientboundBossEventPacket$Handler)
- void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
</summary>

```diff
- Suggestion lambda$new$0(StringRange,FriendlyByteBuf)
+ void <init>()
- void <init>(FriendlyByteBuf)
- void lambda$write$1(FriendlyByteBuf,Suggestion)
+ void read(FriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.ClientboundContainerAckPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundDisconnectPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundExplodePacket
</summary>

```diff
- BlockPos lambda$new$0(int,int,int,FriendlyByteBuf)
+ void <init>()
- void <init>(FriendlyByteBuf)
- void lambda$write$1(int,int,int,FriendlyByteBuf,BlockPos)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundGameEventPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRespawnPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void initFields(int)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundStopSoundPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundTagQueryPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
</summary>

```diff
- AttributeModifier lambda$null$0(FriendlyByteBuf)
- ClientboundUpdateAttributesPacket$AttributeSnapshot lambda$new$1(FriendlyByteBuf)
+ void <init>()
- void <init>(FriendlyByteBuf)
- void lambda$null$2(FriendlyByteBuf,AttributeModifier)
- void lambda$write$3(FriendlyByteBuf,ClientboundUpdateAttributesPacket$AttributeSnapshot)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
</summary>

```diff
- ResourceKey lambda$new$0(FriendlyByteBuf)
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void lambda$write$0(FriendlyByteBuf,ResourceKey,TagCollection$NetworkPayload)
- void lambda$write$1(FriendlyByteBuf,ResourceKey)
- void lambda$write$2(FriendlyByteBuf,TagCollection$NetworkPayload)
+ void read(FriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundClientCommandPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundClientInformationPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundContainerAckPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundContainerClickPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundEntityTagQuery
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundPickItemPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundRenameItemPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSwingPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>



<details>
<summary>
net.minecraft.network.protocol.login.ClientboundGameProfilePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.login.ServerboundHelloPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>



<details>
<summary>
net.minecraft.network.protocol.status.ServerboundPingRequestPacket
</summary>

```diff
+ void <init>()
- void <init>(FriendlyByteBuf)
+ void read(FriendlyByteBuf)
```

</details>
























































































<details>
<summary>
net.minecraft.server.commands.TitleCommand
</summary>

```diff
+ int showTitle(CommandSourceStack,Collection,Component,ClientboundSetTitlesPacket$Type)
- int showTitle(CommandSourceStack,Collection,Component,String,Function)
```

</details>































<details>
<summary>
net.minecraft.server.level.ServerBossEvent
</summary>

```diff
+ void broadcast(ClientboundBossEventPacket$Operation)
- void broadcast(Function)
```

</details>















<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl$1
</summary>

```diff
- InteractionResult lambda$onInteraction$0(Vec3,ServerPlayer,Entity,InteractionHand)
+ void <clinit>()
- void <init>(ServerGamePacketListenerImpl,Entity)
- void onAttack()
- void onInteraction(InteractionHand,Vec3)
- void onInteraction(InteractionHand)
- void performInteraction(InteractionHand,ServerGamePacketListenerImpl$EntityInteraction)
```

</details>







































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
</summary>

```diff
+ int resolveY(DecorationContext)
- int resolveY(WorldGenerationContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
</summary>

```diff
+ int resolveY(DecorationContext)
- int resolveY(WorldGenerationContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarverConfiguration
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- CarverDebugSettings getDebugSettings()
- Float lambda$null$0(CarverConfiguration)
- void <init>(float,CarverDebugSettings)
- void <init>(float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
</summary>

```diff
- boolean carve(CarvingContext,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
+ boolean carve(ChunkAccess,Function,Random,int,int,int,int,int,BitSet)
+ boolean isStartChunk(Random,int,int)
- boolean isStartChunk(Random)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,ProbabilityFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,ProbabilityFeatureConfiguration,LevelHeightAccessor)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndCityFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
- int access$000(ChunkPos,ChunkGenerator,LevelHeightAccessor)
+ int access$000(int,int,ChunkGenerator,LevelHeightAccessor)
- int getYPositionForFeature(ChunkPos,ChunkGenerator,LevelHeightAccessor)
+ int getYPositionForFeature(int,int,ChunkGenerator,LevelHeightAccessor)
```

</details>









<details>
<summary>
net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart
</summary>

```diff
- void <init>(JigsawFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(JigsawFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,JigsawConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,JigsawConfiguration,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
</summary>

```diff
- void <init>(int,Random,FloatProvider,LargeDripstoneFeature$1)
- void <init>(int,Random,FloatProvider)
+ void <init>(int,Random,UniformFloat,LargeDripstoneFeature$1)
+ void <init>(int,Random,UniformFloat)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,MineshaftConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration,LevelHeightAccessor)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,ShipwreckConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration,LevelHeightAccessor)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,ChunkPos,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
- StructureStart createStart(ChunkPos,BoundingBox,int,long)
+ StructureStart createStart(int,int,BoundingBox,int,long)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
</summary>

```diff
- App lambda$static$11(RecordCodecBuilder$Instance)
+ App lambda$static$13(RecordCodecBuilder$Instance)
+ Float lambda$null$10(DripstoneClusterConfiguration)
+ Float lambda$null$9(DripstoneClusterConfiguration)
- FloatProvider lambda$null$6(DripstoneClusterConfiguration)
- FloatProvider lambda$null$7(DripstoneClusterConfiguration)
- Integer lambda$null$10(DripstoneClusterConfiguration)
+ Integer lambda$null$11(DripstoneClusterConfiguration)
+ Integer lambda$null$12(DripstoneClusterConfiguration)
- Integer lambda$null$9(DripstoneClusterConfiguration)
+ UniformFloat lambda$null$6(DripstoneClusterConfiguration)
+ UniformFloat lambda$null$7(DripstoneClusterConfiguration)
- void <init>(int,UniformInt,UniformInt,int,int,UniformInt,FloatProvider,FloatProvider,float,int,int)
+ void <init>(int,UniformInt,UniformInt,int,int,UniformInt,UniformFloat,UniformFloat,float,float,float,int,int)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
</summary>

```diff
+ BlockState lambda$null$1(OreConfiguration)
- Float lambda$null$2(OreConfiguration)
- Integer lambda$null$1(OreConfiguration)
+ Integer lambda$null$2(OreConfiguration)
- List lambda$null$0(OreConfiguration)
- OreConfiguration$TargetBlockState target(RuleTest,BlockState)
+ RuleTest lambda$null$0(OreConfiguration)
- void <init>(List,int,float)
- void <init>(List,int)
- void <init>(RuleTest,BlockState,int,float)
```

</details>











































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
</summary>

```diff
+ boolean air(BlockGetter,BlockPos$MutableBlockPos,int,int,int)
- boolean edgesLiquid(BlockGetter,BoundingBox)
+ boolean edgesLiquidOrFloatingInAir(BlockGetter,BoundingBox)
```

</details>












<details>
<summary>
net.minecraft.world.level.levelgen.structure.NoiseAffectingStructureStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
```

</details>












<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,OceanRuinConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration,LevelHeightAccessor)
```

</details>


















<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart$1
</summary>

```diff
- void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
+ void <init>(StructureFeature,int,int,BoundingBox,int,long)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,FeatureConfiguration,LevelHeightAccessor)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Biome,MineshaftConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration,LevelHeightAccessor)
```

</details>

































































































<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- void addClientSideDecorations(List)
+ void addClientSideDecorations(MapDecoration[])
```

</details>
</details>