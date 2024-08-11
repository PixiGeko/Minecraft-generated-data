## Comparison with [20w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w14a)

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
<table><tr><th></th><th align="left">20w14a</th><th>20w15a</th></tr><tr><td>World version</td><td><code>2524</code></td><td><code>2525</code></td></tr><tr><td>Protocol version</td><td><code>710</code></td><td><code>711</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
biome.txt
</summary>

```diff
+ minecraft:basalt_deltas
```

</details>

<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:blackstone
+ minecraft:blackstone_slab
+ minecraft:blackstone_stairs
+ minecraft:blackstone_wall
+ minecraft:chiseled_nether_bricks
+ minecraft:chiseled_polished_blackstone
+ minecraft:cracked_nether_bricks
+ minecraft:cracked_polished_blackstone_bricks
+ minecraft:gilded_blackstone
+ minecraft:polished_blackstone
+ minecraft:polished_blackstone_brick_slab
+ minecraft:polished_blackstone_brick_stairs
+ minecraft:polished_blackstone_brick_wall
+ minecraft:polished_blackstone_bricks
+ minecraft:polished_blackstone_button
+ minecraft:polished_blackstone_pressure_plate
+ minecraft:polished_blackstone_slab
+ minecraft:polished_blackstone_stairs
+ minecraft:polished_blackstone_wall
+ minecraft:quartz_bricks
+ minecraft:soul_campfire
```

</details>











<details>
<summary>
feature.txt
</summary>

```diff
+ minecraft:basalt_columns
+ minecraft:delta_feature
+ minecraft:netherrack_replace_blobs
```

</details>


<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:blackstone
+ minecraft:blackstone_slab
+ minecraft:blackstone_stairs
+ minecraft:blackstone_wall
+ minecraft:chiseled_nether_bricks
+ minecraft:chiseled_polished_blackstone
+ minecraft:cracked_nether_bricks
+ minecraft:cracked_polished_blackstone_bricks
+ minecraft:gilded_blackstone
+ minecraft:piglin_banner_pattern
+ minecraft:polished_blackstone
+ minecraft:polished_blackstone_brick_slab
+ minecraft:polished_blackstone_brick_stairs
+ minecraft:polished_blackstone_brick_wall
+ minecraft:polished_blackstone_bricks
+ minecraft:polished_blackstone_button
+ minecraft:polished_blackstone_pressure_plate
+ minecraft:polished_blackstone_slab
+ minecraft:polished_blackstone_stairs
+ minecraft:polished_blackstone_wall
+ minecraft:quartz_bricks
+ minecraft:soul_campfire
```

</details>




<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:white_ash
```

</details>








<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:ambient.basalt_deltas.additions
+ minecraft:ambient.basalt_deltas.loop
+ minecraft:ambient.basalt_deltas.mood
+ minecraft:entity.strider.saddle
- minecraft:music.nether
+ minecraft:music.nether.basalt_deltas
+ minecraft:music.nether.crimson_forest
+ minecraft:music.nether.nether_wastes
+ minecraft:music.nether.soul_sand_valley
+ minecraft:music.nether.warped_forest
```

</details>





<details>
<summary>
surface_builder.txt
</summary>

```diff
+ minecraft:basalt_deltas
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:blackstone
+ minecraft:blackstone_slab
+ minecraft:blackstone_stairs
+ minecraft:blackstone_wall
+ minecraft:chiseled_nether_bricks
+ minecraft:chiseled_polished_blackstone
+ minecraft:cracked_nether_bricks
+ minecraft:cracked_polished_blackstone_bricks
+ minecraft:gilded_blackstone
+ minecraft:polished_blackstone
+ minecraft:polished_blackstone_brick_slab
+ minecraft:polished_blackstone_brick_stairs
+ minecraft:polished_blackstone_brick_wall
+ minecraft:polished_blackstone_bricks
+ minecraft:polished_blackstone_button
+ minecraft:polished_blackstone_pressure_plate
+ minecraft:polished_blackstone_slab
+ minecraft:polished_blackstone_stairs
+ minecraft:polished_blackstone_wall
+ minecraft:quartz_bricks
+ minecraft:soul_campfire
```

</details>






<details>
<summary>
universal_tags/biome.json
</summary>

```diff
+ minecraft:basalt_deltas
```

</details>

<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:blackstone
+ minecraft:blackstone_slab
+ minecraft:blackstone_stairs
+ minecraft:blackstone_wall
+ minecraft:chiseled_nether_bricks
+ minecraft:chiseled_polished_blackstone
+ minecraft:cracked_nether_bricks
+ minecraft:cracked_polished_blackstone_bricks
+ minecraft:gilded_blackstone
+ minecraft:polished_blackstone
+ minecraft:polished_blackstone_brick_slab
+ minecraft:polished_blackstone_brick_stairs
+ minecraft:polished_blackstone_brick_wall
+ minecraft:polished_blackstone_bricks
+ minecraft:polished_blackstone_button
+ minecraft:polished_blackstone_pressure_plate
+ minecraft:polished_blackstone_slab
+ minecraft:polished_blackstone_stairs
+ minecraft:polished_blackstone_wall
+ minecraft:quartz_bricks
+ minecraft:soul_campfire
```

</details>











<details>
<summary>
universal_tags/feature.json
</summary>

```diff
+ minecraft:basalt_columns
+ minecraft:delta_feature
+ minecraft:netherrack_replace_blobs
```

</details>


<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:blackstone
+ minecraft:blackstone_slab
+ minecraft:blackstone_stairs
+ minecraft:blackstone_wall
+ minecraft:chiseled_nether_bricks
+ minecraft:chiseled_polished_blackstone
+ minecraft:cracked_nether_bricks
+ minecraft:cracked_polished_blackstone_bricks
+ minecraft:gilded_blackstone
+ minecraft:piglin_banner_pattern
+ minecraft:polished_blackstone
+ minecraft:polished_blackstone_brick_slab
+ minecraft:polished_blackstone_brick_stairs
+ minecraft:polished_blackstone_brick_wall
+ minecraft:polished_blackstone_bricks
+ minecraft:polished_blackstone_button
+ minecraft:polished_blackstone_pressure_plate
+ minecraft:polished_blackstone_slab
+ minecraft:polished_blackstone_stairs
+ minecraft:polished_blackstone_wall
+ minecraft:quartz_bricks
+ minecraft:soul_campfire
```

</details>




<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:white_ash
```

</details>








<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:ambient.basalt_deltas.additions
+ minecraft:ambient.basalt_deltas.loop
+ minecraft:ambient.basalt_deltas.mood
+ minecraft:entity.strider.saddle
- minecraft:music.nether
+ minecraft:music.nether.basalt_deltas
+ minecraft:music.nether.crimson_forest
+ minecraft:music.nether.nether_wastes
+ minecraft:music.nether.soul_sand_valley
+ minecraft:music.nether.warped_forest
```

</details>





<details>
<summary>
universal_tags/surface_builder.json
</summary>

```diff
+ minecraft:basalt_deltas
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ blackstone_slab_from_blackstone_stonecutting.json
+ blackstone_slab.json
+ blackstone_stairs_from_blackstone_stonecutting.json
+ blackstone_stairs.json
+ blackstone_wall_from_blackstone_stonecutting.json
+ blackstone_wall.json
+ chiseled_nether_bricks_from_nether_bricks_stonecutting.json
+ chiseled_nether_bricks.json
+ chiseled_polished_blackstone_from_blackstone_stonecutting.json
+ chiseled_polished_blackstone_from_polished_blackstone_stonecutting.json
+ chiseled_polished_blackstone.json
+ cracked_nether_bricks.json
+ cracked_polished_blackstone_bricks.json
+ polished_blackstone_brick_slab_from_blackstone_stonecutting.json
+ polished_blackstone_brick_slab_from_polished_blackstone_bricks_stonecutting.json
+ polished_blackstone_brick_slab_from_polished_blackstone_stonecutting.json
+ polished_blackstone_brick_slab.json
+ polished_blackstone_brick_stairs_from_blackstone_stonecutting.json
+ polished_blackstone_brick_stairs_from_polished_blackstone_bricks_stonecutting.json
+ polished_blackstone_brick_stairs_from_polished_blackstone_stonecutting.json
+ polished_blackstone_brick_stairs.json
+ polished_blackstone_brick_wall_from_blackstone_stonecutting.json
+ polished_blackstone_brick_wall_from_polished_blackstone_bricks_stonecutting.json
+ polished_blackstone_brick_wall_from_polished_blackstone_stonecutting.json
+ polished_blackstone_brick_wall.json
+ polished_blackstone_bricks_from_blackstone_stonecutting.json
+ polished_blackstone_bricks_from_polished_blackstone_stonecutting.json
+ polished_blackstone_bricks.json
+ polished_blackstone_button.json
+ polished_blackstone_from_blackstone_stonecutting.json
+ polished_blackstone_pressure_plate.json
+ polished_blackstone_slab_from_blackstone_stonecutting.json
+ polished_blackstone_slab_from_polished_blackstone_stonecutting.json
+ polished_blackstone_slab.json
+ polished_blackstone_stairs_from_blackstone_stonecutting.json
+ polished_blackstone_stairs_from_polished_blackstone_stonecutting.json
+ polished_blackstone_stairs.json
+ polished_blackstone_wall_from_blackstone_stonecutting.json
+ polished_blackstone_wall_from_polished_blackstone_stonecutting.json
+ polished_blackstone_wall.json
+ polished_blackstone.json
+ quartz_bricks_from_quartz_block_stonecutting.json
+ quartz_bricks.json
+ soul_campfire.json
```

</details>





















































































































































































































































































<details>
<summary>
furnace.json
</summary>

```
A: #furnace_materials
B: cobblestone

Previous pattern:
[B | B | B]
[B |   | B]
[B | B | B]

New pattern:
[A | A | A]
[A |   | A]
[A | A | A]
```

</details>




































































































































































































































































































































































































































<details>
<summary>
soul_fire_torch.json
</summary>

```
A: #soul_fire_base_blocks
B: soul_soil
C: stick
D: unknown

Previous pattern:
[D]
[C]
[B]

New pattern:
[D]
[C]
[A]
```

</details>



















<details>
<summary>
stone_axe.json
</summary>

```
A: #stone_tool_materials
B: cobblestone
C: stick

Previous pattern:
[B | B]
[B | C]
[  | C]

New pattern:
[A | A]
[A | C]
[  | C]
```

</details>












<details>
<summary>
stone_hoe.json
</summary>

```
A: #stone_tool_materials
B: cobblestone
C: stick

Previous pattern:
[B | B]
[  | C]
[  | C]

New pattern:
[A | A]
[  | C]
[  | C]
```

</details>
<details>
<summary>
stone_pickaxe.json
</summary>

```
A: #stone_tool_materials
B: cobblestone
C: stick

Previous pattern:
[B | B | B]
[  | C |  ]
[  | C |  ]

New pattern:
[A | A | A]
[  | C |  ]
[  | C |  ]
```

</details>

<details>
<summary>
stone_shovel.json
</summary>

```
A: #stone_tool_materials
B: cobblestone
C: stick

Previous pattern:
[B]
[C]
[C]

New pattern:
[A]
[C]
[C]
```

</details>




<details>
<summary>
stone_sword.json
</summary>

```
A: #stone_tool_materials
B: cobblestone
C: stick

Previous pattern:
[B]
[B]
[C]

New pattern:
[A]
[A]
[C]
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ biome.minecraft.basalt_deltas: Basalt Deltas
+ block.minecraft.blackstone_slab: Blackstone Slab
+ block.minecraft.blackstone_stairs: Blackstone Stairs
+ block.minecraft.blackstone_wall: Blackstone Wall
+ block.minecraft.blackstone: Blackstone
+ block.minecraft.chiseled_nether_bricks: Chiseled Nether Bricks
+ block.minecraft.chiseled_polished_blackstone: Chiseled Polished Blackstone
+ block.minecraft.cracked_nether_bricks: Cracked Nether Bricks
+ block.minecraft.cracked_polished_blackstone_bricks: Cracked Polished Blackstone Bricks
+ block.minecraft.gilded_blackstone: Gilded Blackstone
+ block.minecraft.polished_blackstone_brick_slab: Polished Blackstone Brick Slab
+ block.minecraft.polished_blackstone_brick_stairs: Polished Blackstone Brick Stairs
+ block.minecraft.polished_blackstone_brick_wall: Polished Blackstone Brick Wall
+ block.minecraft.polished_blackstone_bricks: Polished Blackstone Bricks
+ block.minecraft.polished_blackstone_button: Polished Blackstone Button
+ block.minecraft.polished_blackstone_pressure_plate: Polished Blackstone Pressure Plate
+ block.minecraft.polished_blackstone_slab: Polished Blackstone Slab
+ block.minecraft.polished_blackstone_stairs: Polished Blackstone Stairs
+ block.minecraft.polished_blackstone_wall: Polished Blackstone Wall
+ block.minecraft.polished_blackstone: Polished Blackstone
+ block.minecraft.quartz_bricks: Quartz Bricks
+ block.minecraft.soul_campfire: Soul Campfire
+ chat.queue: [+%s pending lines]
+ item.minecraft.piglin_banner_pattern: Banner Pattern
+ item.minecraft.piglin_banner_pattern.desc: Piglin
+ options.chat.delay_none: Chat Delay: None
+ options.chat.delay: Chat Delay: %s seconds
+ options.chat.line_spacing: Line Spacing
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/blackstone_slab_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/blackstone_slab.json
+ minecraft/advancements/recipes/building_blocks/blackstone_stairs_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/blackstone_stairs.json
+ minecraft/advancements/recipes/building_blocks/blackstone_wall_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/blackstone_wall.json
+ minecraft/advancements/recipes/building_blocks/chiseled_nether_bricks_from_nether_bricks_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/chiseled_nether_bricks.json
+ minecraft/advancements/recipes/building_blocks/chiseled_polished_blackstone_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/chiseled_polished_blackstone_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/chiseled_polished_blackstone.json
+ minecraft/advancements/recipes/building_blocks/cracked_nether_bricks.json
+ minecraft/advancements/recipes/building_blocks/cracked_polished_blackstone_bricks.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_slab_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_slab_from_polished_blackstone_bricks_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_slab_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_slab.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_stairs_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_stairs_from_polished_blackstone_bricks_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_stairs_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_stairs.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_wall_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_wall_from_polished_blackstone_bricks_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_wall_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_brick_wall.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_bricks_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_bricks_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_bricks.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_slab_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_slab_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_slab.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_stairs_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_stairs_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_stairs.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_wall_from_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_wall_from_polished_blackstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone_wall.json
+ minecraft/advancements/recipes/building_blocks/polished_blackstone.json
+ minecraft/advancements/recipes/building_blocks/quartz_bricks_from_quartz_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/quartz_bricks.json
+ minecraft/advancements/recipes/decorations/soul_campfire.json
+ minecraft/advancements/recipes/redstone/polished_blackstone_button.json
+ minecraft/advancements/recipes/redstone/polished_blackstone_pressure_plate.json
+ minecraft/loot_tables/blocks/blackstone_slab.json
+ minecraft/loot_tables/blocks/blackstone_stairs.json
+ minecraft/loot_tables/blocks/blackstone_wall.json
+ minecraft/loot_tables/blocks/blackstone.json
+ minecraft/loot_tables/blocks/chiseled_nether_bricks.json
+ minecraft/loot_tables/blocks/chiseled_polished_blackstone.json
+ minecraft/loot_tables/blocks/cracked_nether_bricks.json
+ minecraft/loot_tables/blocks/cracked_polished_blackstone_bricks.json
+ minecraft/loot_tables/blocks/gilded_blackstone.json
+ minecraft/loot_tables/blocks/polished_blackstone_brick_slab.json
+ minecraft/loot_tables/blocks/polished_blackstone_brick_stairs.json
+ minecraft/loot_tables/blocks/polished_blackstone_brick_wall.json
+ minecraft/loot_tables/blocks/polished_blackstone_bricks.json
+ minecraft/loot_tables/blocks/polished_blackstone_button.json
+ minecraft/loot_tables/blocks/polished_blackstone_pressure_plate.json
+ minecraft/loot_tables/blocks/polished_blackstone_slab.json
+ minecraft/loot_tables/blocks/polished_blackstone_stairs.json
+ minecraft/loot_tables/blocks/polished_blackstone_wall.json
+ minecraft/loot_tables/blocks/polished_blackstone.json
+ minecraft/loot_tables/blocks/quartz_bricks.json
+ minecraft/loot_tables/blocks/soul_campfire.json
+ minecraft/recipes/blackstone_slab_from_blackstone_stonecutting.json
+ minecraft/recipes/blackstone_slab.json
+ minecraft/recipes/blackstone_stairs_from_blackstone_stonecutting.json
+ minecraft/recipes/blackstone_stairs.json
+ minecraft/recipes/blackstone_wall_from_blackstone_stonecutting.json
+ minecraft/recipes/blackstone_wall.json
+ minecraft/recipes/chiseled_nether_bricks_from_nether_bricks_stonecutting.json
+ minecraft/recipes/chiseled_nether_bricks.json
+ minecraft/recipes/chiseled_polished_blackstone_from_blackstone_stonecutting.json
+ minecraft/recipes/chiseled_polished_blackstone_from_polished_blackstone_stonecutting.json
+ minecraft/recipes/chiseled_polished_blackstone.json
+ minecraft/recipes/cracked_nether_bricks.json
+ minecraft/recipes/cracked_polished_blackstone_bricks.json
+ minecraft/recipes/polished_blackstone_brick_slab_from_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_slab_from_polished_blackstone_bricks_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_slab_from_polished_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_slab.json
+ minecraft/recipes/polished_blackstone_brick_stairs_from_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_stairs_from_polished_blackstone_bricks_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_stairs_from_polished_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_stairs.json
+ minecraft/recipes/polished_blackstone_brick_wall_from_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_wall_from_polished_blackstone_bricks_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_wall_from_polished_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_brick_wall.json
+ minecraft/recipes/polished_blackstone_bricks_from_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_bricks_from_polished_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_bricks.json
+ minecraft/recipes/polished_blackstone_button.json
+ minecraft/recipes/polished_blackstone_from_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_pressure_plate.json
+ minecraft/recipes/polished_blackstone_slab_from_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_slab_from_polished_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_slab.json
+ minecraft/recipes/polished_blackstone_stairs_from_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_stairs_from_polished_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_stairs.json
+ minecraft/recipes/polished_blackstone_wall_from_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_wall_from_polished_blackstone_stonecutting.json
+ minecraft/recipes/polished_blackstone_wall.json
+ minecraft/recipes/polished_blackstone.json
+ minecraft/recipes/quartz_bricks_from_quartz_block_stonecutting.json
+ minecraft/recipes/quartz_bricks.json
+ minecraft/recipes/soul_campfire.json
+ minecraft/tags/blocks/campfires.json
+ minecraft/tags/blocks/guarded_by_piglins.json
+ minecraft/tags/items/furnace_materials.json
+ minecraft/tags/items/soul_fire_base_blocks.json
+ minecraft/tags/items/stone_tool_materials.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/blackstone_slab.json
+ minecraft/blockstates/blackstone_stairs.json
+ minecraft/blockstates/blackstone_wall.json
+ minecraft/blockstates/blackstone.json
+ minecraft/blockstates/chiseled_nether_bricks.json
+ minecraft/blockstates/chiseled_polished_blackstone.json
+ minecraft/blockstates/cracked_nether_bricks.json
+ minecraft/blockstates/cracked_polished_blackstone_bricks.json
+ minecraft/blockstates/gilded_blackstone.json
+ minecraft/blockstates/polished_blackstone_brick_slab.json
+ minecraft/blockstates/polished_blackstone_brick_stairs.json
+ minecraft/blockstates/polished_blackstone_brick_wall.json
+ minecraft/blockstates/polished_blackstone_bricks.json
+ minecraft/blockstates/polished_blackstone_button.json
+ minecraft/blockstates/polished_blackstone_pressure_plate.json
+ minecraft/blockstates/polished_blackstone_slab.json
+ minecraft/blockstates/polished_blackstone_stairs.json
+ minecraft/blockstates/polished_blackstone_wall.json
+ minecraft/blockstates/polished_blackstone.json
+ minecraft/blockstates/quartz_bricks.json
+ minecraft/blockstates/soul_campfire.json
+ minecraft/models/block/blackstone_slab_top.json
+ minecraft/models/block/blackstone_slab.json
+ minecraft/models/block/blackstone_stairs_inner.json
+ minecraft/models/block/blackstone_stairs_outer.json
+ minecraft/models/block/blackstone_stairs.json
+ minecraft/models/block/blackstone_wall_inventory.json
+ minecraft/models/block/blackstone_wall_post.json
+ minecraft/models/block/blackstone_wall_side_tall.json
+ minecraft/models/block/blackstone_wall_side.json
+ minecraft/models/block/blackstone.json
+ minecraft/models/block/chiseled_nether_bricks.json
+ minecraft/models/block/chiseled_polished_blackstone.json
+ minecraft/models/block/cracked_nether_bricks.json
+ minecraft/models/block/cracked_polished_blackstone_bricks.json
+ minecraft/models/block/gilded_blackstone.json
+ minecraft/models/block/polished_blackstone_brick_slab_top.json
+ minecraft/models/block/polished_blackstone_brick_slab.json
+ minecraft/models/block/polished_blackstone_brick_stairs_inner.json
+ minecraft/models/block/polished_blackstone_brick_stairs_outer.json
+ minecraft/models/block/polished_blackstone_brick_stairs.json
+ minecraft/models/block/polished_blackstone_brick_wall_inventory.json
+ minecraft/models/block/polished_blackstone_brick_wall_post.json
+ minecraft/models/block/polished_blackstone_brick_wall_side_tall.json
+ minecraft/models/block/polished_blackstone_brick_wall_side.json
+ minecraft/models/block/polished_blackstone_bricks.json
+ minecraft/models/block/polished_blackstone_button_inventory.json
+ minecraft/models/block/polished_blackstone_button_pressed.json
+ minecraft/models/block/polished_blackstone_button.json
+ minecraft/models/block/polished_blackstone_pressure_plate_down.json
+ minecraft/models/block/polished_blackstone_pressure_plate.json
+ minecraft/models/block/polished_blackstone_slab_top.json
+ minecraft/models/block/polished_blackstone_slab.json
+ minecraft/models/block/polished_blackstone_stairs_inner.json
+ minecraft/models/block/polished_blackstone_stairs_outer.json
+ minecraft/models/block/polished_blackstone_stairs.json
+ minecraft/models/block/polished_blackstone_wall_inventory.json
+ minecraft/models/block/polished_blackstone_wall_post.json
+ minecraft/models/block/polished_blackstone_wall_side_tall.json
+ minecraft/models/block/polished_blackstone_wall_side.json
+ minecraft/models/block/polished_blackstone.json
+ minecraft/models/block/quartz_bricks.json
+ minecraft/models/block/soul_campfire.json
+ minecraft/models/block/template_campfire.json
+ minecraft/models/item/blackstone_slab.json
+ minecraft/models/item/blackstone_stairs.json
+ minecraft/models/item/blackstone_wall.json
+ minecraft/models/item/blackstone.json
+ minecraft/models/item/chiseled_nether_bricks.json
+ minecraft/models/item/chiseled_polished_blackstone.json
+ minecraft/models/item/cracked_nether_bricks.json
+ minecraft/models/item/cracked_polished_blackstone_bricks.json
+ minecraft/models/item/gilded_blackstone.json
+ minecraft/models/item/piglin_banner_pattern.json
+ minecraft/models/item/polished_blackstone_brick_slab.json
+ minecraft/models/item/polished_blackstone_brick_stairs.json
+ minecraft/models/item/polished_blackstone_brick_wall.json
+ minecraft/models/item/polished_blackstone_bricks.json
+ minecraft/models/item/polished_blackstone_button.json
+ minecraft/models/item/polished_blackstone_pressure_plate.json
+ minecraft/models/item/polished_blackstone_slab.json
+ minecraft/models/item/polished_blackstone_stairs.json
+ minecraft/models/item/polished_blackstone_wall.json
+ minecraft/models/item/polished_blackstone.json
+ minecraft/models/item/quartz_bricks.json
+ minecraft/models/item/soul_campfire.json
+ minecraft/particles/white_ash.json
+ minecraft/textures/block/blackstone_top.png
+ minecraft/textures/block/blackstone.png
+ minecraft/textures/block/chiseled_nether_bricks.png
+ minecraft/textures/block/chiseled_polished_blackstone.png
+ minecraft/textures/block/cracked_nether_bricks.png
+ minecraft/textures/block/cracked_polished_blackstone_bricks.png
+ minecraft/textures/block/gilded_blackstone.png
+ minecraft/textures/block/polished_blackstone_bricks.png
+ minecraft/textures/block/polished_blackstone.png
+ minecraft/textures/block/quartz_bricks.png
+ minecraft/textures/block/soul_campfire_fire.png
+ minecraft/textures/block/soul_campfire_fire.png.mcmeta
+ minecraft/textures/block/soul_campfire_log_lit.png
+ minecraft/textures/block/soul_campfire_log_lit.png.mcmeta
+ minecraft/textures/entity/banner/piglin.png
+ minecraft/textures/entity/shield/piglin.png
+ minecraft/textures/entity/strider/strider_cold.png
+ minecraft/textures/item/piglin_banner_pattern.png
+ minecraft/textures/item/soul_campfire.png
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
- net.minecraft.core.BlockPos$4
+ net.minecraft.core.BlockPos$MutableBlockPos
- net.minecraft.core.BlockSource
+ net.minecraft.core.BlockSourceImpl
- net.minecraft.core.Cursor3D
+ net.minecraft.core.DefaultedRegistry
- net.minecraft.core.Direction
+ net.minecraft.core.Direction$1
- net.minecraft.core.Direction$Axis
+ net.minecraft.core.Direction$Axis$1
- net.minecraft.core.Direction$Axis$2
+ net.minecraft.core.Direction$Axis$3
- net.minecraft.core.Direction$AxisDirection
+ net.minecraft.core.Direction$Plane
- net.minecraft.core.Direction8
- net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
+ net.minecraft.core.dispenser.BoatDispenseItemBehavior
- net.minecraft.core.dispenser.DefaultDispenseItemBehavior
+ net.minecraft.core.dispenser.DispenseItemBehavior
- net.minecraft.core.dispenser.DispenseItemBehavior$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$10
- net.minecraft.core.dispenser.DispenseItemBehavior$11
+ net.minecraft.core.dispenser.DispenseItemBehavior$12
- net.minecraft.core.dispenser.DispenseItemBehavior$13
+ net.minecraft.core.dispenser.DispenseItemBehavior$14
- net.minecraft.core.dispenser.DispenseItemBehavior$15
+ net.minecraft.core.dispenser.DispenseItemBehavior$16
- net.minecraft.core.dispenser.DispenseItemBehavior$17
+ net.minecraft.core.dispenser.DispenseItemBehavior$18
- net.minecraft.core.dispenser.DispenseItemBehavior$19
+ net.minecraft.core.dispenser.DispenseItemBehavior$2
- net.minecraft.core.dispenser.DispenseItemBehavior$20
+ net.minecraft.core.dispenser.DispenseItemBehavior$21
- net.minecraft.core.dispenser.DispenseItemBehavior$22
+ net.minecraft.core.dispenser.DispenseItemBehavior$23
- net.minecraft.core.dispenser.DispenseItemBehavior$24
- net.minecraft.core.dispenser.DispenseItemBehavior$3
+ net.minecraft.core.dispenser.DispenseItemBehavior$4
- net.minecraft.core.dispenser.DispenseItemBehavior$5
+ net.minecraft.core.dispenser.DispenseItemBehavior$6
- net.minecraft.core.dispenser.DispenseItemBehavior$7
+ net.minecraft.core.dispenser.DispenseItemBehavior$7$1
- net.minecraft.core.dispenser.DispenseItemBehavior$8
+ net.minecraft.core.dispenser.DispenseItemBehavior$8$1
- net.minecraft.core.dispenser.DispenseItemBehavior$9
+ net.minecraft.core.dispenser.OptionalDispenseItemBehavior
- net.minecraft.core.dispenser.ShearsDispenseItemBehavior
+ net.minecraft.core.FrontAndTop
- net.minecraft.core.GlobalPos
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.LocatableSource
- net.minecraft.core.Location
+ net.minecraft.core.MapFiller
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.NonNullList
- net.minecraft.core.Position
+ net.minecraft.core.PositionImpl
- net.minecraft.core.Registry
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.SerializableBoolean
+ net.minecraft.core.SerializableLong
- net.minecraft.core.SerializableUUID
+ net.minecraft.core.Source
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
- net.minecraft.data.tags.TagsProvider$1
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$Named
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.world.entity.animal.horse.Mule
+ net.minecraft.world.entity.animal.horse.SkeletonHorse
- net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
+ net.minecraft.world.entity.animal.horse.TraderLlama
- net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.ItemSteerableMount
- net.minecraft.world.entity.Saddleable
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
- net.minecraft.world.level.biome.BasaltDeltasBiome
+ net.minecraft.world.level.biome.BeachBiome
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$BiomeTempCategory
+ net.minecraft.world.level.biome.Biome$ClimateParameters
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$SpawnerData
- net.minecraft.world.level.biome.BiomeDefaultFeatures
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSourceSettings
+ net.minecraft.world.level.biome.BiomeSourceType
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.BirchForestBiome
- net.minecraft.world.level.biome.BirchForestHillsBiome
+ net.minecraft.world.level.biome.CheckerboardBiomeSourceSettings
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.ColdOceanBiome
- net.minecraft.world.level.biome.CrimsonForestBiome
+ net.minecraft.world.level.biome.DarkForestBiome
- net.minecraft.world.level.biome.DarkForestHillsBiome
+ net.minecraft.world.level.biome.DeepColdOceanBiome
- net.minecraft.world.level.biome.DeepFrozenOceanBiome
+ net.minecraft.world.level.biome.DeepLukeWarmOceanBiome
- net.minecraft.world.level.biome.DeepOceanBiome
+ net.minecraft.world.level.biome.DeepWarmOceanBiome
- net.minecraft.world.level.biome.DesertBiome
+ net.minecraft.world.level.biome.DesertHillsBiome
- net.minecraft.world.level.biome.DesertLakesBiome
+ net.minecraft.world.level.biome.EndBarrensBiome
- net.minecraft.world.level.biome.EndHighlandsBiome
+ net.minecraft.world.level.biome.EndMidlandsBiome
- net.minecraft.world.level.biome.ErodedBadlandsBiome
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSourceSettings
+ net.minecraft.world.level.biome.ForestBiome
- net.minecraft.world.level.biome.ForestFlowerBiome
+ net.minecraft.world.level.biome.FrozenOceanBiome
- net.minecraft.world.level.biome.FrozenRiverBiome
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.GiantSpruceTaigaBiome
- net.minecraft.world.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ net.minecraft.world.level.biome.GiantTreeTaigaBiome
- net.minecraft.world.level.biome.GiantTreeTaigaHillsBiome
+ net.minecraft.world.level.biome.GravellyMountainsBiome
- net.minecraft.world.level.biome.IceSpikesBiome
+ net.minecraft.world.level.biome.JungleBiome
- net.minecraft.world.level.biome.JungleEdgeBiome
+ net.minecraft.world.level.biome.JungleHillsBiome
- net.minecraft.world.level.biome.LukeWarmOceanBiome
+ net.minecraft.world.level.biome.ModifiedBadlandsPlateauBiome
- net.minecraft.world.level.biome.ModifiedGravellyMountainsBiome
+ net.minecraft.world.level.biome.ModifiedJungleBiome
- net.minecraft.world.level.biome.ModifiedJungleEdgeBiome
+ net.minecraft.world.level.biome.ModifiedWoodedBadlandsPlateauBiome
- net.minecraft.world.level.biome.MountainBiome
+ net.minecraft.world.level.biome.MountainEdgeBiome
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceSettings
- net.minecraft.world.level.biome.MushroomFieldsBiome
+ net.minecraft.world.level.biome.MushroomFieldsShoreBiome
- net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
+ net.minecraft.world.level.biome.NetherWastesBiome
- net.minecraft.world.level.biome.OceanBiome
+ net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.OverworldBiomeSourceSettings
+ net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.PlainsBiome
- net.minecraft.world.level.biome.RiverBiome
+ net.minecraft.world.level.biome.SavannaBiome
- net.minecraft.world.level.biome.SavannaPlateauBiome
+ net.minecraft.world.level.biome.ShatteredSavannaBiome
- net.minecraft.world.level.biome.ShatteredSavannaPlateauBiome
+ net.minecraft.world.level.biome.SmallEndIslandsBiome
- net.minecraft.world.level.biome.SnowyBeachBiome
+ net.minecraft.world.level.biome.SnowyMountainsBiome
- net.minecraft.world.level.biome.SnowyTaigaBiome
+ net.minecraft.world.level.biome.SnowyTaigaHillsBiome
- net.minecraft.world.level.biome.SnowyTaigaMountainsBiome
+ net.minecraft.world.level.biome.SnowyTundraBiome
- net.minecraft.world.level.biome.SoulSandValleyBiome
+ net.minecraft.world.level.biome.StoneShoreBiome
- net.minecraft.world.level.biome.SunflowerPlainsBiome
+ net.minecraft.world.level.biome.SwampBiome
- net.minecraft.world.level.biome.SwampHillsBiome
+ net.minecraft.world.level.biome.TaigaBiome
- net.minecraft.world.level.biome.TaigaHillsBiome
+ net.minecraft.world.level.biome.TaigaMountainsBiome
- net.minecraft.world.level.biome.TallBirchForestBiome
+ net.minecraft.world.level.biome.TallBirchHillsBiome
- net.minecraft.world.level.biome.TheEndBiome
+ net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.biome.TheEndBiomeSourceSettings
+ net.minecraft.world.level.biome.TheVoidBiome
- net.minecraft.world.level.biome.WarmOceanBiome
+ net.minecraft.world.level.biome.WarpedForestBiome
- net.minecraft.world.level.biome.WoodedBadlandsBiome
+ net.minecraft.world.level.biome.WoodedHillsBiome
- net.minecraft.world.level.biome.WoodedMountainBiome
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.BambooBlock
+ net.minecraft.world.level.block.BambooSaplingBlock
- net.minecraft.world.level.block.BannerBlock
+ net.minecraft.world.level.block.BarrelBlock
- net.minecraft.world.level.block.BarrierBlock
+ net.minecraft.world.level.block.BaseCoralFanBlock
- net.minecraft.world.level.block.BaseCoralPlantBlock
+ net.minecraft.world.level.block.BaseCoralPlantTypeBlock
- net.minecraft.world.level.block.BaseCoralWallFanBlock
+ net.minecraft.world.level.block.BaseEntityBlock
- net.minecraft.world.level.block.BaseFireBlock
+ net.minecraft.world.level.block.BasePressurePlateBlock
- net.minecraft.world.level.block.BaseRailBlock
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BrewingStandBlock
+ net.minecraft.world.level.block.BubbleColumnBlock
- net.minecraft.world.level.block.BucketPickup
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.ChestBlock
- net.minecraft.world.level.block.ChestBlock$1
+ net.minecraft.world.level.block.ChestBlock$2
- net.minecraft.world.level.block.ChestBlock$2$1
+ net.minecraft.world.level.block.ChestBlock$3
- net.minecraft.world.level.block.ChestBlock$4
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
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
- net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.EndRodBlock$1
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
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
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration$Builder
+ net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration$Builder
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSpheroidConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.VillageConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DarkOakFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SimulatedFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SnowyVillagePools
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaVillagePools
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.VillagePieces
+ net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceHeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.ChancePassthroughDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceTopSolidHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.ChorusPlantPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
- net.minecraft.world.level.levelgen.placement.CountBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.CountDepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.CountHeighmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.CountHeight64Decorator
- net.minecraft.world.level.levelgen.placement.CountHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.CountHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.CountTopSolidDecorator
+ net.minecraft.world.level.levelgen.placement.CountVeryBiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
- net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
+ net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.ForestRockPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FrequencyChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.FrequencyDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
- net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.ChanceRangeDecorator
+ net.minecraft.world.level.levelgen.placement.nether.CountRangeDecorator
- net.minecraft.world.level.levelgen.placement.nether.FireDecorator
+ net.minecraft.world.level.levelgen.placement.nether.LightGemChanceDecorator
- net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.nether.RandomCountRangeDecorator
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NoiseHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.NoiseHeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.RangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapRangeDecorator
- net.minecraft.world.level.levelgen.structure.BeardedStructureStart
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces
- net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces
+ net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructureFeatureIO
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureStart$1
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.BlockPos +4M -2M
```
```
XXX.minecraft.core.BlockPos$2 +1M -1M | +13P -7P
```
```
XXX.data.loot.BlockLoot +3M -1M
```
```
XXX.data.models.BlockModelGenerators +1M -1M
```
```
XXX.models.model.ModelTemplates +1P
```
```
XXX.models.model.TextureSlot +1P
```
```
XXX.minecraft.sounds.SoundEvents +9P -1P
```
```
XXX.minecraft.tags.BlockTags +1M | +2P
```
```
XXX.minecraft.tags.FluidTags +1M
```
```
XXX.minecraft.tags.StaticTagHelper +4M -1M | +1P
```
```
XXX.minecraft.tags.StaticTagHelper$Wrapper +1M -1M
```
```
XXX.minecraft.tags.Tag$Builder +7M -5M | +1P -1P
```
```
XXX.minecraft.tags.TagCollection +1M
```
```
XXX.entity.ai.Brain +6M -27M
```
```
XXX.entity.animal.MushroomCow +2M
```
```
XXX.entity.animal.Pig +3M -2M
```
```
XXX.animal.horse.AbstractHorse +5M -4M
```
```
XXX.animal.horse.Horse +7M -9M | -6P
```
```
XXX.animal.horse.Llama +4M -3M
```
```
XXX.entity.monster.Monster +1M
```
```
XXX.entity.monster.Zoglin +1M
```
```
XXX.monster.hoglin.Hoglin +1M
```
```
XXX.entity.schedule.Activity +2M | +1P
```
```
XXX.world.item.SpawnEggItem +1M -1M
```
```
XXX.item.enchantment.EnchantmentCategory$14 -2M
```
```
XXX.world.level.CollisionGetter$1 +1M -1M | +3P -2P
```
```
XXX.block.entity.BannerPattern +1P
```
```
XXX.block.entity.ShulkerBoxBlockEntity +1M
```
```
XXX.levelgen.feature.Feature +3P
```
```
XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder +3M -3M | +1P -6P
```
```
XXX.level.pathfinder.WalkNodeEvaluator +5M -3M
```

</details>






















































































































































<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- Iterable randomBetweenClosed(Random,int,int,int,int,int,int,int)
+ Iterator lambda$betweenClosed$4(int,int,int,int,int,int)
- Iterator lambda$betweenClosed$5(int,int,int,int,int,int)
- Iterator lambda$randomBetweenClosed$3(int,int,Random,int,int,int,int,int)
+ Iterator lambda$withinManhattan$3(int,int,int,int,int,int,int)
- Iterator lambda$withinManhattan$4(int,int,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos$2
</summary>

```diff
- void <init>(int,int,int,int,int,int,int)
+ void <init>(int,int,int,int,int,int)
```

</details>















<details>
<summary>
net.minecraft.data.loot.BlockLoot
</summary>

```diff
- LootTable$Builder lambda$accept$69(Block)
- LootTable$Builder lambda$accept$70(Block)
+ LootTable$Builder lambda$dropPottedContents$69(Block)
- LootTable$Builder lambda$dropPottedContents$71(Block)
```

</details>



<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
+ void createCampfire()
- void createCampfires(Block[])
```

</details>















































































































































































































































































































































































<details>
<summary>
net.minecraft.tags.BlockTags
</summary>

```diff
- void resetToEmpty()
```

</details>
<details>
<summary>
net.minecraft.tags.FluidTags
</summary>

```diff
- void resetToEmpty()
```

</details>
<details>
<summary>
net.minecraft.tags.StaticTagHelper
</summary>

```diff
- Tag lambda$null$1(Tag,ResourceLocation)
+ void lambda$reset$1(TagCollection,StaticTagHelper$Wrapper)
- void lambda$reset$3(TagCollection,StaticTagHelper$Wrapper)
- void lambda$resetToEmpty$2(Tag,StaticTagHelper$Wrapper)
- void resetToEmpty()
```

</details>
<details>
<summary>
net.minecraft.tags.StaticTagHelper$Wrapper
</summary>

```diff
- void rebind(Function)
+ void rebind(TagCollection)
```

</details>

<details>
<summary>
net.minecraft.tags.Tag$Builder
</summary>

```diff
- boolean lambda$getUnresolvedEntries$1(Function,Function,Tag$BuilderEntry)
+ boolean lambda$getUnresolvedEntries$1(Function,Function,Tag$Entry)
- Tag$Builder add(Tag$BuilderEntry)
- Tag$Builder add(Tag$Entry,String)
+ Tag$Builder add(Tag$Entry)
- Tag$Builder addElement(ResourceLocation,String)
+ Tag$Builder addElement(ResourceLocation)
- Tag$Builder addFromJson(JsonObject,String)
+ Tag$Builder addFromJson(JsonObject)
- Tag$Builder addTag(ResourceLocation,String)
+ Tag$Builder addTag(ResourceLocation)
- void lambda$addFromJson$2(String,Tag$Entry)
```

</details>
<details>
<summary>
net.minecraft.tags.TagCollection
</summary>

```diff
- Tag getEmptyTag()
```

</details>


















































































































































































<details>
<summary>
net.minecraft.world.entity.ai.Brain
</summary>

```diff
+ boolean lambda$activityRequirementsAreMet$23(Pair)
+ boolean lambda$eraseMemoriesForOtherActivitesThan$7(Activity,Activity)
+ boolean lambda$getActiveNonCoreActivity$6(Activity)
+ boolean lambda$getRunningBehaviorsStream$5(Behavior)
- boolean lambda$isMemoryValue$0(Object,Object)
+ boolean lambda$isMemoryValue$3(Object,Object)
+ boolean lambda$serialize$15(Map$Entry)
+ boolean lambda$startEachNonRunningBehavior$18(Map$Entry)
+ boolean lambda$startEachNonRunningBehavior$19(Behavior)
- List getRunningBehaviors()
- Map lambda$addActivityAndRemoveMemoriesWhenStopped$1(Integer)
+ Map lambda$null$8(Integer)
+ Pair lambda$createPriorityPairs$24(MutableInt,Behavior)
+ Pair lambda$serialize$16(DynamicOps,Map$Entry)
- Set lambda$addActivityAndRemoveMemoriesWhenStopped$2(Activity)
+ Set lambda$null$9(Activity)
+ Stream getRunningBehaviorsStream()
+ Stream lambda$getRunningBehaviorsStream$4(Map)
+ Stream lambda$startEachNonRunningBehavior$17(Map)
- void forgetOutdatedMemories()
+ void lambda$addActivityAndRemoveMemoriesWhenStopped$10(Activity,Pair)
+ void lambda$copyWithoutBehaviors$12(Brain,MemoryModuleType,Optional)
+ void lambda$new$0(MemoryModuleType)
+ void lambda$new$1(SensorType)
+ void lambda$new$2(Sensor)
+ void lambda$null$11(Brain,MemoryModuleType,ExpirableValue)
+ void lambda$startEachNonRunningBehavior$20(ServerLevel,LivingEntity,long,Behavior)
+ void lambda$stopAll$14(ServerLevel,LivingEntity,long,Behavior)
+ void lambda$tick$13(ServerLevel,LivingEntity,Sensor)
+ void lambda$tickEachRunningBehavior$21(ServerLevel,LivingEntity,long,Behavior)
+ void lambda$tickMemoryAndRemoveIfExpired$22(MemoryModuleType,ExpirableValue)
+ void tickMemoryAndRemoveIfExpired(MemoryModuleType,Optional)
- void tickSensors(ServerLevel,LivingEntity)
```

</details>





















































































































































<details>
<summary>
net.minecraft.world.entity.animal.MushroomCow
</summary>

```diff
- boolean readyForShearing()
- void shear(SoundSource)
```

</details>









<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
+ boolean hasSaddle()
- boolean isSaddleable()
- boolean isSaddled()
- void equipSaddle(SoundSource)
+ void setSaddle(boolean)
```

</details>






















<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ boolean canBeSaddled()
- boolean canWearArmor()
- boolean isSaddleable()
- boolean isWearingArmor()
+ boolean wearsArmor()
- void equipSaddle(SoundSource)
+ void setSaddled(boolean)
- void updateContainerEquipment()
+ void updateEquipment()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- boolean canWearArmor()
+ boolean wearsArmor()
- int getTypeVariant()
+ int getVariant()
- Markings getMarkings()
+ String getLayeredTextureHashName()
+ String[] getLayeredTextureLayers()
- Variant getVariant()
+ void clearLayeredTextureInfo()
+ void rebuildLayeredTextureInfo()
- void setTypeVariant(int)
+ void setVariant(int)
- void setVariantAndMarkings(Variant,Markings)
+ void tick()
- void updateContainerEquipment()
+ void updateEquipment()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
+ boolean canBeSaddled()
- boolean canWearArmor()
- boolean isSaddleable()
- boolean isWearingArmor()
+ boolean wearsArmor()
- void updateContainerEquipment()
+ void updateEquipment()
```

</details>
















































<details>
<summary>
net.minecraft.world.entity.monster.Monster
</summary>

```diff
- boolean shouldDropLoot()
```

</details>






























<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
- MobType getMobType()
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
- void ageBoundaryReached()
```

</details>














































<details>
<summary>
net.minecraft.world.entity.schedule.Activity
</summary>

```diff
- boolean equals(Object)
- int hashCode()
```

</details>















































































































<details>
<summary>
net.minecraft.world.item.SpawnEggItem
</summary>

```diff
+ Optional spawnOffspringFromSpawnEgg(Player,EntityType,Level,Vec3,ItemStack)
- Optional spawnOffspringFromSpawnEgg(Player,Mob,EntityType,Level,Vec3,ItemStack)
```

</details>








































<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentCategory$14
</summary>

```diff
+ boolean lambda$canEnchant$0(EnchantmentCategory)
+ boolean lambda$canEnchant$1(Item,EnchantmentCategory)
```

</details>



























<details>
<summary>
net.minecraft.world.level.CollisionGetter$1
</summary>

```diff
- void <init>(CollisionGetter,long,int,Entity,Cursor3D,BlockPos$MutableBlockPos,CollisionContext,AABB,VoxelShape)
+ void <init>(CollisionGetter,long,int,Entity,Cursor3D,BlockPos$MutableBlockPos,CollisionContext,VoxelShape)
```

</details>




























































































































<details>
<summary>
net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
</summary>

```diff
- boolean isClosed()
```

</details>







































































































































<details>
<summary>
net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
</summary>

```diff
- BlockState getPatchBlockState()
- ImmutableList getCeilingBlockStates()
- ImmutableList getFloorBlockStates()
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
+ void initNoise(long)
```

</details>























































<details>
<summary>
net.minecraft.world.level.pathfinder.WalkNodeEvaluator
</summary>

```diff
- BlockPathTypes checkNeighbourBlocks(BlockGetter,BlockPos$MutableBlockPos,BlockPathTypes)
+ BlockPathTypes checkNeighbourBlocks(BlockGetter,int,int,int,BlockPathTypes)
- BlockPathTypes getBlockPathTypeRaw(BlockGetter,BlockPos)
+ BlockPathTypes getBlockPathTypeRaw(BlockGetter,int,int,int)
- BlockPathTypes getBlockPathTypeStatic(BlockGetter,BlockPos$MutableBlockPos)
+ BlockPathTypes getBlockPathTypeStatic(BlockGetter,int,int,int)
- boolean hasPositiveMalus(BlockPos)
- boolean isBurningBlock(BlockState)
```

</details>
































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.particle.WhiteAshParticle$Provider
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
- net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
+ net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
- net.minecraft.client.renderer.entity.layers.ItemInHandLayer
+ net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
- net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
- net.minecraft.client.renderer.entity.layers.package-info
+ net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
- net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
+ net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
- net.minecraft.client.renderer.entity.layers.PiglinArmorLayer
+ net.minecraft.client.renderer.entity.layers.RenderLayer
- net.minecraft.client.renderer.entity.layers.SaddleLayer
+ net.minecraft.client.renderer.entity.layers.SheepFurLayer
- net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
+ net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
- net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
+ net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
- net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
+ net.minecraft.client.renderer.entity.layers.StrayClothingLayer
- net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
+ net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
- net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
+ net.minecraft.client.renderer.entity.layers.WitchItemLayer
- net.minecraft.client.renderer.entity.layers.WitherArmorLayer
+ net.minecraft.client.renderer.entity.layers.WolfCollarLayer
+ net.minecraft.client.renderer.entity.package-info
+ net.minecraft.client.renderer.entity.player.package-info
- net.minecraft.client.renderer.entity.player.PlayerRenderer
- net.minecraft.client.renderer.package-info
+ net.minecraft.client.renderer.texture.AbstractTexture
- net.minecraft.client.renderer.texture.AtlasSet
+ net.minecraft.client.renderer.texture.DynamicTexture
- net.minecraft.client.renderer.texture.HttpTexture
+ net.minecraft.client.renderer.texture.LayeredTexture
- net.minecraft.core.BlockPos$4
+ net.minecraft.core.BlockPos$MutableBlockPos
- net.minecraft.core.BlockSource
+ net.minecraft.core.BlockSourceImpl
- net.minecraft.core.Cursor3D
+ net.minecraft.core.DefaultedRegistry
- net.minecraft.core.Direction
+ net.minecraft.core.Direction$1
- net.minecraft.core.Direction$Axis
+ net.minecraft.core.Direction$Axis$1
- net.minecraft.core.Direction$Axis$2
+ net.minecraft.core.Direction$Axis$3
- net.minecraft.core.Direction$AxisDirection
+ net.minecraft.core.Direction$Plane
- net.minecraft.core.Direction8
- net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
+ net.minecraft.core.dispenser.BoatDispenseItemBehavior
- net.minecraft.core.dispenser.DefaultDispenseItemBehavior
+ net.minecraft.core.dispenser.DispenseItemBehavior
- net.minecraft.core.dispenser.DispenseItemBehavior$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$10
- net.minecraft.core.dispenser.DispenseItemBehavior$11
+ net.minecraft.core.dispenser.DispenseItemBehavior$12
- net.minecraft.core.dispenser.DispenseItemBehavior$13
+ net.minecraft.core.dispenser.DispenseItemBehavior$14
- net.minecraft.core.dispenser.DispenseItemBehavior$15
+ net.minecraft.core.dispenser.DispenseItemBehavior$16
- net.minecraft.core.dispenser.DispenseItemBehavior$17
+ net.minecraft.core.dispenser.DispenseItemBehavior$18
- net.minecraft.core.dispenser.DispenseItemBehavior$19
+ net.minecraft.core.dispenser.DispenseItemBehavior$2
- net.minecraft.core.dispenser.DispenseItemBehavior$20
+ net.minecraft.core.dispenser.DispenseItemBehavior$21
- net.minecraft.core.dispenser.DispenseItemBehavior$22
+ net.minecraft.core.dispenser.DispenseItemBehavior$23
- net.minecraft.core.dispenser.DispenseItemBehavior$24
- net.minecraft.core.dispenser.DispenseItemBehavior$3
+ net.minecraft.core.dispenser.DispenseItemBehavior$4
- net.minecraft.core.dispenser.DispenseItemBehavior$5
+ net.minecraft.core.dispenser.DispenseItemBehavior$6
- net.minecraft.core.dispenser.DispenseItemBehavior$7
+ net.minecraft.core.dispenser.DispenseItemBehavior$7$1
- net.minecraft.core.dispenser.DispenseItemBehavior$8
+ net.minecraft.core.dispenser.DispenseItemBehavior$8$1
- net.minecraft.core.dispenser.DispenseItemBehavior$9
+ net.minecraft.core.dispenser.OptionalDispenseItemBehavior
- net.minecraft.core.dispenser.ShearsDispenseItemBehavior
+ net.minecraft.core.FrontAndTop
- net.minecraft.core.GlobalPos
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.LocatableSource
- net.minecraft.core.Location
+ net.minecraft.core.MapFiller
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.NonNullList
- net.minecraft.core.Position
+ net.minecraft.core.PositionImpl
- net.minecraft.core.Registry
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.SerializableBoolean
+ net.minecraft.core.SerializableLong
- net.minecraft.core.SerializableUUID
+ net.minecraft.core.Source
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
- net.minecraft.data.tags.TagsProvider$1
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$Named
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.world.entity.animal.horse.Mule
+ net.minecraft.world.entity.animal.horse.SkeletonHorse
- net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
+ net.minecraft.world.entity.animal.horse.TraderLlama
- net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.ItemSteerableMount
- net.minecraft.world.entity.Saddleable
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
- net.minecraft.world.level.biome.BasaltDeltasBiome
+ net.minecraft.world.level.biome.BeachBiome
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$BiomeTempCategory
+ net.minecraft.world.level.biome.Biome$ClimateParameters
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$SpawnerData
- net.minecraft.world.level.biome.BiomeDefaultFeatures
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSourceSettings
+ net.minecraft.world.level.biome.BiomeSourceType
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.BirchForestBiome
- net.minecraft.world.level.biome.BirchForestHillsBiome
+ net.minecraft.world.level.biome.CheckerboardBiomeSourceSettings
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.ColdOceanBiome
- net.minecraft.world.level.biome.CrimsonForestBiome
+ net.minecraft.world.level.biome.DarkForestBiome
- net.minecraft.world.level.biome.DarkForestHillsBiome
+ net.minecraft.world.level.biome.DeepColdOceanBiome
- net.minecraft.world.level.biome.DeepFrozenOceanBiome
+ net.minecraft.world.level.biome.DeepLukeWarmOceanBiome
- net.minecraft.world.level.biome.DeepOceanBiome
+ net.minecraft.world.level.biome.DeepWarmOceanBiome
- net.minecraft.world.level.biome.DesertBiome
+ net.minecraft.world.level.biome.DesertHillsBiome
- net.minecraft.world.level.biome.DesertLakesBiome
+ net.minecraft.world.level.biome.EndBarrensBiome
- net.minecraft.world.level.biome.EndHighlandsBiome
+ net.minecraft.world.level.biome.EndMidlandsBiome
- net.minecraft.world.level.biome.ErodedBadlandsBiome
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSourceSettings
+ net.minecraft.world.level.biome.ForestBiome
- net.minecraft.world.level.biome.ForestFlowerBiome
+ net.minecraft.world.level.biome.FrozenOceanBiome
- net.minecraft.world.level.biome.FrozenRiverBiome
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.GiantSpruceTaigaBiome
- net.minecraft.world.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ net.minecraft.world.level.biome.GiantTreeTaigaBiome
- net.minecraft.world.level.biome.GiantTreeTaigaHillsBiome
+ net.minecraft.world.level.biome.GravellyMountainsBiome
- net.minecraft.world.level.biome.IceSpikesBiome
+ net.minecraft.world.level.biome.JungleBiome
- net.minecraft.world.level.biome.JungleEdgeBiome
+ net.minecraft.world.level.biome.JungleHillsBiome
- net.minecraft.world.level.biome.LukeWarmOceanBiome
+ net.minecraft.world.level.biome.ModifiedBadlandsPlateauBiome
- net.minecraft.world.level.biome.ModifiedGravellyMountainsBiome
+ net.minecraft.world.level.biome.ModifiedJungleBiome
- net.minecraft.world.level.biome.ModifiedJungleEdgeBiome
+ net.minecraft.world.level.biome.ModifiedWoodedBadlandsPlateauBiome
- net.minecraft.world.level.biome.MountainBiome
+ net.minecraft.world.level.biome.MountainEdgeBiome
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceSettings
- net.minecraft.world.level.biome.MushroomFieldsBiome
+ net.minecraft.world.level.biome.MushroomFieldsShoreBiome
- net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
+ net.minecraft.world.level.biome.NetherWastesBiome
- net.minecraft.world.level.biome.OceanBiome
+ net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.OverworldBiomeSourceSettings
+ net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.PlainsBiome
- net.minecraft.world.level.biome.RiverBiome
+ net.minecraft.world.level.biome.SavannaBiome
- net.minecraft.world.level.biome.SavannaPlateauBiome
+ net.minecraft.world.level.biome.ShatteredSavannaBiome
- net.minecraft.world.level.biome.ShatteredSavannaPlateauBiome
+ net.minecraft.world.level.biome.SmallEndIslandsBiome
- net.minecraft.world.level.biome.SnowyBeachBiome
+ net.minecraft.world.level.biome.SnowyMountainsBiome
- net.minecraft.world.level.biome.SnowyTaigaBiome
+ net.minecraft.world.level.biome.SnowyTaigaHillsBiome
- net.minecraft.world.level.biome.SnowyTaigaMountainsBiome
+ net.minecraft.world.level.biome.SnowyTundraBiome
- net.minecraft.world.level.biome.SoulSandValleyBiome
+ net.minecraft.world.level.biome.StoneShoreBiome
- net.minecraft.world.level.biome.SunflowerPlainsBiome
+ net.minecraft.world.level.biome.SwampBiome
- net.minecraft.world.level.biome.SwampHillsBiome
+ net.minecraft.world.level.biome.TaigaBiome
- net.minecraft.world.level.biome.TaigaHillsBiome
+ net.minecraft.world.level.biome.TaigaMountainsBiome
- net.minecraft.world.level.biome.TallBirchForestBiome
+ net.minecraft.world.level.biome.TallBirchHillsBiome
- net.minecraft.world.level.biome.TheEndBiome
+ net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.biome.TheEndBiomeSourceSettings
+ net.minecraft.world.level.biome.TheVoidBiome
- net.minecraft.world.level.biome.WarmOceanBiome
+ net.minecraft.world.level.biome.WarpedForestBiome
- net.minecraft.world.level.biome.WoodedBadlandsBiome
+ net.minecraft.world.level.biome.WoodedHillsBiome
- net.minecraft.world.level.biome.WoodedMountainBiome
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.BambooBlock
+ net.minecraft.world.level.block.BambooSaplingBlock
- net.minecraft.world.level.block.BannerBlock
+ net.minecraft.world.level.block.BarrelBlock
- net.minecraft.world.level.block.BarrierBlock
+ net.minecraft.world.level.block.BaseCoralFanBlock
- net.minecraft.world.level.block.BaseCoralPlantBlock
+ net.minecraft.world.level.block.BaseCoralPlantTypeBlock
- net.minecraft.world.level.block.BaseCoralWallFanBlock
+ net.minecraft.world.level.block.BaseEntityBlock
- net.minecraft.world.level.block.BaseFireBlock
+ net.minecraft.world.level.block.BasePressurePlateBlock
- net.minecraft.world.level.block.BaseRailBlock
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BrewingStandBlock
+ net.minecraft.world.level.block.BubbleColumnBlock
- net.minecraft.world.level.block.BucketPickup
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.ChestBlock
- net.minecraft.world.level.block.ChestBlock$1
+ net.minecraft.world.level.block.ChestBlock$2
- net.minecraft.world.level.block.ChestBlock$2$1
+ net.minecraft.world.level.block.ChestBlock$3
- net.minecraft.world.level.block.ChestBlock$4
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
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
- net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.EndRodBlock$1
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
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
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration$Builder
+ net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration$Builder
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSpheroidConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.VillageConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DarkOakFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SimulatedFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SnowyVillagePools
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaVillagePools
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.VillagePieces
+ net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceHeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.ChancePassthroughDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceTopSolidHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.ChorusPlantPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
- net.minecraft.world.level.levelgen.placement.CountBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.CountDepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.CountHeighmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.CountHeight64Decorator
- net.minecraft.world.level.levelgen.placement.CountHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.CountHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.CountTopSolidDecorator
+ net.minecraft.world.level.levelgen.placement.CountVeryBiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
- net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
+ net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.ForestRockPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FrequencyChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.FrequencyDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
- net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.ChanceRangeDecorator
+ net.minecraft.world.level.levelgen.placement.nether.CountRangeDecorator
- net.minecraft.world.level.levelgen.placement.nether.FireDecorator
+ net.minecraft.world.level.levelgen.placement.nether.LightGemChanceDecorator
- net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.nether.RandomCountRangeDecorator
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NoiseHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.NoiseHeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.RangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapRangeDecorator
- net.minecraft.world.level.levelgen.structure.BeardedStructureStart
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces
- net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces
+ net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructureFeatureIO
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureStart$1
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.NativeImage -1M
```
```
XXX.minecraft.client.Options +2P
```
```
XXX.renderer.entity.HorseRenderer +1M | +1P -1P
```
```
XXX.client.sounds.MusicManager$Music +2M | +6P -1P
```
```
XXX.minecraft.core.BlockPos +4M -2M
```
```
XXX.minecraft.core.BlockPos$2 +1M -1M | +13P -7P
```
```
XXX.data.loot.BlockLoot +3M -1M
```
```
XXX.data.models.BlockModelGenerators +1M -1M
```
```
XXX.models.model.ModelTemplates +1P
```
```
XXX.models.model.TextureSlot +1P
```
```
XXX.minecraft.sounds.SoundEvents +9P -1P
```
```
XXX.minecraft.tags.BlockTags +1M | +2P
```
```
XXX.minecraft.tags.FluidTags +1M
```
```
XXX.minecraft.tags.StaticTagHelper +4M -1M | +1P
```
```
XXX.minecraft.tags.StaticTagHelper$Wrapper +1M -1M
```
```
XXX.minecraft.tags.Tag$Builder +7M -5M | +1P -1P
```
```
XXX.minecraft.tags.TagCollection +1M
```
```
XXX.entity.ai.Brain +6M -27M
```
```
XXX.entity.animal.MushroomCow +2M
```
```
XXX.entity.animal.Pig +3M -2M
```
```
XXX.animal.horse.AbstractHorse +5M -4M
```
```
XXX.animal.horse.Horse +7M -9M | -6P
```
```
XXX.animal.horse.Llama +4M -3M
```
```
XXX.entity.monster.Monster +1M
```
```
XXX.entity.monster.Zoglin +1M
```
```
XXX.monster.hoglin.Hoglin +1M
```
```
XXX.entity.schedule.Activity +2M | +1P
```
```
XXX.world.item.SpawnEggItem +1M -1M
```
```
XXX.item.enchantment.EnchantmentCategory$14 -2M
```
```
XXX.world.level.CollisionGetter$1 +1M -1M | +3P -2P
```
```
XXX.block.entity.BannerPattern +1P
```
```
XXX.block.entity.ShulkerBoxBlockEntity +1M
```
```
XXX.levelgen.feature.Feature +3P
```
```
XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder +3M -3M | +1P -6P
```
```
XXX.level.pathfinder.WalkNodeEvaluator +5M -3M
```

</details>































<details>
<summary>
com.mojang.blaze3d.platform.NativeImage
</summary>

```diff
+ void blendPixel(int,int,int)
```

</details>








































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.client.renderer.entity.HorseRenderer
</summary>

```diff
- void lambda$static$0(EnumMap)
```

</details>













































































































<details>
<summary>
net.minecraft.client.sounds.MusicManager$Music
</summary>

```diff
- boolean access$000(MusicManager$Music)
- void <init>(String,int,SoundEvent,int,int,boolean)
```

</details>










































































<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- Iterable randomBetweenClosed(Random,int,int,int,int,int,int,int)
+ Iterator lambda$betweenClosed$4(int,int,int,int,int,int)
- Iterator lambda$betweenClosed$5(int,int,int,int,int,int)
- Iterator lambda$randomBetweenClosed$3(int,int,Random,int,int,int,int,int)
+ Iterator lambda$withinManhattan$3(int,int,int,int,int,int,int)
- Iterator lambda$withinManhattan$4(int,int,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos$2
</summary>

```diff
- void <init>(int,int,int,int,int,int,int)
+ void <init>(int,int,int,int,int,int)
```

</details>















<details>
<summary>
net.minecraft.data.loot.BlockLoot
</summary>

```diff
- LootTable$Builder lambda$accept$69(Block)
- LootTable$Builder lambda$accept$70(Block)
+ LootTable$Builder lambda$dropPottedContents$69(Block)
- LootTable$Builder lambda$dropPottedContents$71(Block)
```

</details>



<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
+ void createCampfire()
- void createCampfires(Block[])
```

</details>





















































































































































































































































































































































































<details>
<summary>
net.minecraft.tags.BlockTags
</summary>

```diff
- void resetToEmpty()
```

</details>
<details>
<summary>
net.minecraft.tags.FluidTags
</summary>

```diff
- void resetToEmpty()
```

</details>
<details>
<summary>
net.minecraft.tags.StaticTagHelper
</summary>

```diff
- Tag lambda$null$1(Tag,ResourceLocation)
+ void lambda$reset$1(TagCollection,StaticTagHelper$Wrapper)
- void lambda$reset$3(TagCollection,StaticTagHelper$Wrapper)
- void lambda$resetToEmpty$2(Tag,StaticTagHelper$Wrapper)
- void resetToEmpty()
```

</details>
<details>
<summary>
net.minecraft.tags.StaticTagHelper$Wrapper
</summary>

```diff
- void rebind(Function)
+ void rebind(TagCollection)
```

</details>

<details>
<summary>
net.minecraft.tags.Tag$Builder
</summary>

```diff
- boolean lambda$getUnresolvedEntries$1(Function,Function,Tag$BuilderEntry)
+ boolean lambda$getUnresolvedEntries$1(Function,Function,Tag$Entry)
- Tag$Builder add(Tag$BuilderEntry)
- Tag$Builder add(Tag$Entry,String)
+ Tag$Builder add(Tag$Entry)
- Tag$Builder addElement(ResourceLocation,String)
+ Tag$Builder addElement(ResourceLocation)
- Tag$Builder addFromJson(JsonObject,String)
+ Tag$Builder addFromJson(JsonObject)
- Tag$Builder addTag(ResourceLocation,String)
+ Tag$Builder addTag(ResourceLocation)
- void lambda$addFromJson$2(String,Tag$Entry)
```

</details>
<details>
<summary>
net.minecraft.tags.TagCollection
</summary>

```diff
- Tag getEmptyTag()
```

</details>


















































































































































































<details>
<summary>
net.minecraft.world.entity.ai.Brain
</summary>

```diff
+ boolean lambda$activityRequirementsAreMet$23(Pair)
+ boolean lambda$eraseMemoriesForOtherActivitesThan$7(Activity,Activity)
+ boolean lambda$getActiveNonCoreActivity$6(Activity)
+ boolean lambda$getRunningBehaviorsStream$5(Behavior)
- boolean lambda$isMemoryValue$0(Object,Object)
+ boolean lambda$isMemoryValue$3(Object,Object)
+ boolean lambda$serialize$15(Map$Entry)
+ boolean lambda$startEachNonRunningBehavior$18(Map$Entry)
+ boolean lambda$startEachNonRunningBehavior$19(Behavior)
- List getRunningBehaviors()
- Map lambda$addActivityAndRemoveMemoriesWhenStopped$1(Integer)
+ Map lambda$null$8(Integer)
+ Pair lambda$createPriorityPairs$24(MutableInt,Behavior)
+ Pair lambda$serialize$16(DynamicOps,Map$Entry)
- Set lambda$addActivityAndRemoveMemoriesWhenStopped$2(Activity)
+ Set lambda$null$9(Activity)
+ Stream getRunningBehaviorsStream()
+ Stream lambda$getRunningBehaviorsStream$4(Map)
+ Stream lambda$startEachNonRunningBehavior$17(Map)
- void forgetOutdatedMemories()
+ void lambda$addActivityAndRemoveMemoriesWhenStopped$10(Activity,Pair)
+ void lambda$copyWithoutBehaviors$12(Brain,MemoryModuleType,Optional)
+ void lambda$new$0(MemoryModuleType)
+ void lambda$new$1(SensorType)
+ void lambda$new$2(Sensor)
+ void lambda$null$11(Brain,MemoryModuleType,ExpirableValue)
+ void lambda$startEachNonRunningBehavior$20(ServerLevel,LivingEntity,long,Behavior)
+ void lambda$stopAll$14(ServerLevel,LivingEntity,long,Behavior)
+ void lambda$tick$13(ServerLevel,LivingEntity,Sensor)
+ void lambda$tickEachRunningBehavior$21(ServerLevel,LivingEntity,long,Behavior)
+ void lambda$tickMemoryAndRemoveIfExpired$22(MemoryModuleType,ExpirableValue)
+ void tickMemoryAndRemoveIfExpired(MemoryModuleType,Optional)
- void tickSensors(ServerLevel,LivingEntity)
```

</details>





















































































































































<details>
<summary>
net.minecraft.world.entity.animal.MushroomCow
</summary>

```diff
- boolean readyForShearing()
- void shear(SoundSource)
```

</details>









<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
+ boolean hasSaddle()
- boolean isSaddleable()
- boolean isSaddled()
- void equipSaddle(SoundSource)
+ void setSaddle(boolean)
```

</details>






















<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ boolean canBeSaddled()
- boolean canWearArmor()
- boolean isSaddleable()
- boolean isWearingArmor()
+ boolean wearsArmor()
- void equipSaddle(SoundSource)
+ void setSaddled(boolean)
- void updateContainerEquipment()
+ void updateEquipment()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- boolean canWearArmor()
+ boolean wearsArmor()
- int getTypeVariant()
+ int getVariant()
- Markings getMarkings()
+ String getLayeredTextureHashName()
+ String[] getLayeredTextureLayers()
- Variant getVariant()
+ void clearLayeredTextureInfo()
+ void rebuildLayeredTextureInfo()
- void setTypeVariant(int)
+ void setVariant(int)
- void setVariantAndMarkings(Variant,Markings)
+ void tick()
- void updateContainerEquipment()
+ void updateEquipment()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
+ boolean canBeSaddled()
- boolean canWearArmor()
- boolean isSaddleable()
- boolean isWearingArmor()
+ boolean wearsArmor()
- void updateContainerEquipment()
+ void updateEquipment()
```

</details>
















































<details>
<summary>
net.minecraft.world.entity.monster.Monster
</summary>

```diff
- boolean shouldDropLoot()
```

</details>






























<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
- MobType getMobType()
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
- void ageBoundaryReached()
```

</details>














































<details>
<summary>
net.minecraft.world.entity.schedule.Activity
</summary>

```diff
- boolean equals(Object)
- int hashCode()
```

</details>















































































































<details>
<summary>
net.minecraft.world.item.SpawnEggItem
</summary>

```diff
+ Optional spawnOffspringFromSpawnEgg(Player,EntityType,Level,Vec3,ItemStack)
- Optional spawnOffspringFromSpawnEgg(Player,Mob,EntityType,Level,Vec3,ItemStack)
```

</details>








































<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentCategory$14
</summary>

```diff
+ boolean lambda$canEnchant$0(EnchantmentCategory)
+ boolean lambda$canEnchant$1(Item,EnchantmentCategory)
```

</details>



























<details>
<summary>
net.minecraft.world.level.CollisionGetter$1
</summary>

```diff
- void <init>(CollisionGetter,long,int,Entity,Cursor3D,BlockPos$MutableBlockPos,CollisionContext,AABB,VoxelShape)
+ void <init>(CollisionGetter,long,int,Entity,Cursor3D,BlockPos$MutableBlockPos,CollisionContext,VoxelShape)
```

</details>




























































































































<details>
<summary>
net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
</summary>

```diff
- boolean isClosed()
```

</details>







































































































































<details>
<summary>
net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
</summary>

```diff
- BlockState getPatchBlockState()
- ImmutableList getCeilingBlockStates()
- ImmutableList getFloorBlockStates()
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderBaseConfiguration)
+ void apply(Random,ChunkAccess,Biome,int,int,int,double,BlockState,BlockState,int,long,SurfaceBuilderConfiguration)
+ void initNoise(long)
```

</details>























































<details>
<summary>
net.minecraft.world.level.pathfinder.WalkNodeEvaluator
</summary>

```diff
- BlockPathTypes checkNeighbourBlocks(BlockGetter,BlockPos$MutableBlockPos,BlockPathTypes)
+ BlockPathTypes checkNeighbourBlocks(BlockGetter,int,int,int,BlockPathTypes)
- BlockPathTypes getBlockPathTypeRaw(BlockGetter,BlockPos)
+ BlockPathTypes getBlockPathTypeRaw(BlockGetter,int,int,int)
- BlockPathTypes getBlockPathTypeStatic(BlockGetter,BlockPos$MutableBlockPos)
+ BlockPathTypes getBlockPathTypeStatic(BlockGetter,int,int,int)
- boolean hasPositiveMalus(BlockPos)
- boolean isBurningBlock(BlockState)
```

</details>
</details>