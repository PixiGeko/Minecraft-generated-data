## Comparison with [20w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w14a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">20w14a</th><th>20w15a</th></tr><tr><td>World version</td><td><pre>2524</pre></td><td><pre>2525</pre></td></tr><tr><td>Protocol version</td><td><pre>710</pre></td><td><pre>711</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w14a</th><th>20w15a</th></tr><tr><td>com.mojang:authlib</td><td><pre>1.5.25</pre></td><td><pre>1.6.25</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
biome
</summary>

```diff
+ minecraft:basalt_deltas
```

</details>
<details>
<summary>
block
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
feature
</summary>

```diff
+ minecraft:basalt_columns
+ minecraft:delta_feature
+ minecraft:netherrack_replace_blobs
```

</details>
<details>
<summary>
item
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
particle_type
</summary>

```diff
+ minecraft:white_ash
```

</details>
<details>
<summary>
sound_event
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
surface_builder
</summary>

```diff
+ minecraft:basalt_deltas
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
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ blackstone_slab.json
+ blackstone_stairs.json
+ blackstone_wall.json
+ blackstone.json
+ chiseled_nether_bricks.json
+ chiseled_polished_blackstone.json
+ cracked_nether_bricks.json
+ cracked_polished_blackstone_bricks.json
+ gilded_blackstone.json
+ polished_blackstone_brick_slab.json
+ polished_blackstone_brick_stairs.json
+ polished_blackstone_brick_wall.json
+ polished_blackstone_bricks.json
+ polished_blackstone_button.json
+ polished_blackstone_pressure_plate.json
+ polished_blackstone_slab.json
+ polished_blackstone_stairs.json
+ polished_blackstone_wall.json
+ polished_blackstone.json
+ quartz_bricks.json
+ soul_campfire.json
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.animal.horse.Mule
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.core.dispenser.AbstractProjectileDispenseBehavior
+ XXX.core.dispenser.BoatDispenseItemBehavior
- XXX.core.dispenser.DefaultDispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior$1
+ XXX.core.dispenser.DispenseItemBehavior$10
- XXX.core.dispenser.DispenseItemBehavior$11
+ XXX.core.dispenser.DispenseItemBehavior$12
- XXX.core.dispenser.DispenseItemBehavior$13
+ XXX.core.dispenser.DispenseItemBehavior$14
- XXX.core.dispenser.DispenseItemBehavior$15
+ XXX.core.dispenser.DispenseItemBehavior$16
- XXX.core.dispenser.DispenseItemBehavior$17
+ XXX.core.dispenser.DispenseItemBehavior$18
- XXX.core.dispenser.DispenseItemBehavior$19
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$20
+ XXX.core.dispenser.DispenseItemBehavior$21
- XXX.core.dispenser.DispenseItemBehavior$22
+ XXX.core.dispenser.DispenseItemBehavior$23
- XXX.core.dispenser.DispenseItemBehavior$24
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.data.tags.TagsProvider$1
- XXX.feature.blockplacers.BlockPlacer
+ XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.ColumnPlacer
+ XXX.feature.blockplacers.DoublePlantPlacer
+ XXX.feature.blockplacers.package-info
- XXX.feature.blockplacers.SimpleBlockPlacer
- XXX.feature.configurations.BlockBlobConfiguration
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.BuriedTreasureConfiguration
- XXX.feature.configurations.ChanceRangeDecoratorConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration$Builder
+ XXX.feature.configurations.CountFeatureConfiguration
- XXX.feature.configurations.CountRangeDecoratorConfiguration
+ XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DecoratorConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration$Builder
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.FeatureRadiusConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MegaTreeConfiguration
- XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.NoiseDependantDecoratorConfiguration
+ XXX.feature.configurations.NoneDecoratorConfiguration
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.package-info
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$1
+ XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- XXX.feature.configurations.RandomRandomFeatureConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSpheroidConfiguration
- XXX.feature.configurations.SeagrassFeatureConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SmallTreeConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.VillageConfiguration
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
- XXX.level.biome.BasaltDeltasBiome
+ XXX.level.biome.BeachBiome
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$BiomeCategory
- XXX.level.biome.Biome$BiomeTempCategory
+ XXX.level.biome.Biome$ClimateParameters
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$SpawnerData
- XXX.level.biome.BiomeDefaultFeatures
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSourceSettings
+ XXX.level.biome.BiomeSourceType
- XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.BiomeSpecialEffects$1
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeZoomer
+ XXX.level.biome.BirchForestBiome
- XXX.level.biome.BirchForestHillsBiome
+ XXX.level.biome.CheckerboardBiomeSourceSettings
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.ColdOceanBiome
- XXX.level.biome.CrimsonForestBiome
+ XXX.level.biome.DarkForestBiome
- XXX.level.biome.DarkForestHillsBiome
+ XXX.level.biome.DeepColdOceanBiome
- XXX.level.biome.DeepFrozenOceanBiome
+ XXX.level.biome.DeepLukeWarmOceanBiome
- XXX.level.biome.DeepOceanBiome
+ XXX.level.biome.DeepWarmOceanBiome
- XXX.level.biome.DesertBiome
+ XXX.level.biome.DesertHillsBiome
- XXX.level.biome.DesertLakesBiome
+ XXX.level.biome.EndBarrensBiome
- XXX.level.biome.EndHighlandsBiome
+ XXX.level.biome.EndMidlandsBiome
- XXX.level.biome.ErodedBadlandsBiome
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.FixedBiomeSourceSettings
+ XXX.level.biome.ForestBiome
- XXX.level.biome.ForestFlowerBiome
+ XXX.level.biome.FrozenOceanBiome
- XXX.level.biome.FrozenRiverBiome
+ XXX.level.biome.FuzzyOffsetBiomeZoomer
- XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ XXX.level.biome.GiantSpruceTaigaBiome
- XXX.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ XXX.level.biome.GiantTreeTaigaBiome
- XXX.level.biome.GiantTreeTaigaHillsBiome
+ XXX.level.biome.GravellyMountainsBiome
- XXX.level.biome.IceSpikesBiome
+ XXX.level.biome.JungleBiome
- XXX.level.biome.JungleEdgeBiome
+ XXX.level.biome.JungleHillsBiome
- XXX.level.biome.LukeWarmOceanBiome
+ XXX.level.biome.ModifiedBadlandsPlateauBiome
- XXX.level.biome.ModifiedGravellyMountainsBiome
+ XXX.level.biome.ModifiedJungleBiome
- XXX.level.biome.ModifiedJungleEdgeBiome
+ XXX.level.biome.ModifiedWoodedBadlandsPlateauBiome
- XXX.level.biome.MountainBiome
+ XXX.level.biome.MountainEdgeBiome
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceSettings
- XXX.level.biome.MushroomFieldsBiome
+ XXX.level.biome.MushroomFieldsShoreBiome
- XXX.level.biome.NearestNeighborBiomeZoomer
+ XXX.level.biome.NetherWastesBiome
- XXX.level.biome.OceanBiome
+ XXX.level.biome.OverworldBiomeSource
- XXX.level.biome.OverworldBiomeSourceSettings
+ XXX.level.biome.package-info
+ XXX.level.biome.PlainsBiome
- XXX.level.biome.RiverBiome
+ XXX.level.biome.SavannaBiome
- XXX.level.biome.SavannaPlateauBiome
+ XXX.level.biome.ShatteredSavannaBiome
- XXX.level.biome.ShatteredSavannaPlateauBiome
+ XXX.level.biome.SmallEndIslandsBiome
- XXX.level.biome.SnowyBeachBiome
+ XXX.level.biome.SnowyMountainsBiome
- XXX.level.biome.SnowyTaigaBiome
+ XXX.level.biome.SnowyTaigaHillsBiome
- XXX.level.biome.SnowyTaigaMountainsBiome
+ XXX.level.biome.SnowyTundraBiome
- XXX.level.biome.SoulSandValleyBiome
+ XXX.level.biome.StoneShoreBiome
- XXX.level.biome.SunflowerPlainsBiome
+ XXX.level.biome.SwampBiome
- XXX.level.biome.SwampHillsBiome
+ XXX.level.biome.TaigaBiome
- XXX.level.biome.TaigaHillsBiome
+ XXX.level.biome.TaigaMountainsBiome
- XXX.level.biome.TallBirchForestBiome
+ XXX.level.biome.TallBirchHillsBiome
- XXX.level.biome.TheEndBiome
+ XXX.level.biome.TheEndBiomeSource
- XXX.level.biome.TheEndBiomeSourceSettings
+ XXX.level.biome.TheVoidBiome
- XXX.level.biome.WarmOceanBiome
+ XXX.level.biome.WarpedForestBiome
- XXX.level.biome.WoodedBadlandsBiome
+ XXX.level.biome.WoodedHillsBiome
- XXX.level.biome.WoodedMountainBiome
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AnvilBlock
+ XXX.level.block.AttachedStemBlock
- XXX.level.block.BambooBlock
+ XXX.level.block.BambooSaplingBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BaseFireBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BedBlock$1
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$BlockStatePairKey
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.CocoaBlock$1
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DispenserBlock
+ XXX.level.block.DoorBlock
- XXX.level.block.DoorBlock$1
+ XXX.level.block.DoubleBlockCombiner
- XXX.level.block.DoubleBlockCombiner$BlockType
+ XXX.level.block.DoubleBlockCombiner$Combiner
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ XXX.level.block.DoublePlantBlock
- XXX.level.block.DragonEggBlock
+ XXX.level.block.DropperBlock
- XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
+ XXX.level.block.EndRodBlock$1
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FletchingTableBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GlassBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.levelgen.package-info
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureFeature
- XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DarkOakFeature
- XXX.levelgen.feature.DecoratedFeature
+ XXX.levelgen.feature.DecoratedFlowerFeature
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.SavannaVillagePools
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.ShipwreckFeature
+ XXX.levelgen.feature.ShipwreckFeature$FeatureStart
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SimulatedFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SnowyVillagePools
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$1
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.StrongholdFeature
+ XXX.levelgen.feature.StrongholdFeature$StrongholdStart
- XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.StructureFeature$StructureStartFactory
- XXX.levelgen.feature.StructurePieceType
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.TaigaVillagePools
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VillageFeature$FeatureStart
- XXX.levelgen.feature.VillagePieces
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
+ XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
+ XXX.levelgen.placement.ChanceDecoratorConfiguration
- XXX.levelgen.placement.ChanceHeightmapDecorator
+ XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.ChancePassthroughDecorator
+ XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
- XXX.levelgen.placement.ChorusPlantPlacementDecorator
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountBiasedRangeDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDecorator
- XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.CountDepthAverageDecorator
- XXX.levelgen.placement.CountHeighmapDoubleDecorator
+ XXX.levelgen.placement.CountHeight64Decorator
- XXX.levelgen.placement.CountHeightmap32Decorator
+ XXX.levelgen.placement.CountHeightmapDecorator
- XXX.levelgen.placement.CountTopSolidDecorator
+ XXX.levelgen.placement.CountVeryBiasedRangeDecorator
- XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DepthAverageConfigation
+ XXX.levelgen.placement.EmeraldPlacementDecorator
- XXX.levelgen.placement.EndGatewayPlacementDecorator
+ XXX.levelgen.placement.EndIslandPlacementDecorator
- XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.ForestRockPlacementDecorator
- XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
+ XXX.levelgen.placement.FrequencyDecoratorConfiguration
- XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ XXX.levelgen.placement.IcebergPlacementDecorator
- XXX.levelgen.placement.LakeLavaPlacementDecorator
+ XXX.levelgen.placement.LakeWaterPlacementDecorator
- XXX.levelgen.placement.MonsterRoomPlacementDecorator
+ XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- XXX.levelgen.placement.NoiseHeightmap32Decorator
+ XXX.levelgen.placement.NoiseHeightmapDoubleDecorator
- XXX.levelgen.placement.NopePlacementDecorator
+ XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.RangeDecoratorConfiguration
- XXX.levelgen.placement.SimpleFeatureDecorator
+ XXX.levelgen.placement.TopSolidHeightMapDecorator
- XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
- XXX.levelgen.structure.BeardedStructureStart
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
- XXX.levelgen.structure.JunglePyramidPiece$1
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
- XXX.levelgen.structure.MineShaftPieces$1
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
- XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
- XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
- XXX.levelgen.structure.NetherBridgePieces
+ XXX.levelgen.structure.NetherBridgePieces$1
- XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
- XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
- XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
- XXX.levelgen.structure.NetherBridgePieces$StartPiece
+ XXX.levelgen.structure.NetherFossilFeature
- XXX.levelgen.structure.NetherFossilFeature$FeatureStart
+ XXX.levelgen.structure.NetherFossilPieces
- XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ XXX.levelgen.structure.OceanMonumentPieces
- XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature
- XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ XXX.levelgen.structure.OceanRuinFeature$Type
- XXX.levelgen.structure.OceanRuinPieces
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PillagerOutpostPieces
+ XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.ShipwreckPieces
+ XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$1
- XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$3
- XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FillerCorridor
- XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$LeftTurn
- XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PieceWeight
- XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$PrisonHall
- XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$RoomCrossing
- XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StairsDown
- XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$Straight
- XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructureFeatureIO
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureStart$1
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
- XXX.levelgen.structure.WoodlandMansionPieces$1
+ XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
- XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
- XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.minecraft.core.BlockPos$4
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockSource
+ XXX.minecraft.core.BlockSourceImpl
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
+ XXX.minecraft.core.Direction$1
- XXX.minecraft.core.Direction$Axis
+ XXX.minecraft.core.Direction$Axis$1
- XXX.minecraft.core.Direction$Axis$2
+ XXX.minecraft.core.Direction$Axis$3
- XXX.minecraft.core.Direction$AxisDirection
+ XXX.minecraft.core.Direction$Plane
- XXX.minecraft.core.Direction8
+ XXX.minecraft.core.FrontAndTop
- XXX.minecraft.core.GlobalPos
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.LocatableSource
- XXX.minecraft.core.Location
+ XXX.minecraft.core.MapFiller
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.NonNullList
- XXX.minecraft.core.Position
+ XXX.minecraft.core.PositionImpl
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.SerializableBoolean
+ XXX.minecraft.core.SerializableLong
- XXX.minecraft.core.SerializableUUID
+ XXX.minecraft.core.Source
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
- XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$Entry
- XXX.minecraft.tags.Tag$Named
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.placement.nether.ChanceRangeDecorator
+ XXX.placement.nether.CountRangeDecorator
- XXX.placement.nether.FireDecorator
+ XXX.placement.nether.LightGemChanceDecorator
- XXX.placement.nether.MagmaDecorator
- XXX.placement.nether.package-info
+ XXX.placement.nether.RandomCountRangeDecorator
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.ItemSteerableMount
- XXX.world.entity.Saddleable
- XXX.world.item.Vanishable
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.Wearable
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.animal.horse.Mule
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.client.particle.WhiteAshParticle$Provider
- XXX.client.renderer.package-info
- XXX.core.dispenser.AbstractProjectileDispenseBehavior
+ XXX.core.dispenser.BoatDispenseItemBehavior
- XXX.core.dispenser.DefaultDispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior$1
+ XXX.core.dispenser.DispenseItemBehavior$10
- XXX.core.dispenser.DispenseItemBehavior$11
+ XXX.core.dispenser.DispenseItemBehavior$12
- XXX.core.dispenser.DispenseItemBehavior$13
+ XXX.core.dispenser.DispenseItemBehavior$14
- XXX.core.dispenser.DispenseItemBehavior$15
+ XXX.core.dispenser.DispenseItemBehavior$16
- XXX.core.dispenser.DispenseItemBehavior$17
+ XXX.core.dispenser.DispenseItemBehavior$18
- XXX.core.dispenser.DispenseItemBehavior$19
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$20
+ XXX.core.dispenser.DispenseItemBehavior$21
- XXX.core.dispenser.DispenseItemBehavior$22
+ XXX.core.dispenser.DispenseItemBehavior$23
- XXX.core.dispenser.DispenseItemBehavior$24
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.data.tags.TagsProvider$1
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
- XXX.entity.layers.package-info
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.layers.PiglinArmorLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.SaddleLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StrayClothingLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfCollarLayer
+ XXX.entity.player.package-info
- XXX.entity.player.PlayerRenderer
- XXX.feature.blockplacers.BlockPlacer
+ XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.ColumnPlacer
+ XXX.feature.blockplacers.DoublePlantPlacer
+ XXX.feature.blockplacers.package-info
- XXX.feature.blockplacers.SimpleBlockPlacer
- XXX.feature.configurations.BlockBlobConfiguration
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.BuriedTreasureConfiguration
- XXX.feature.configurations.ChanceRangeDecoratorConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration$Builder
+ XXX.feature.configurations.CountFeatureConfiguration
- XXX.feature.configurations.CountRangeDecoratorConfiguration
+ XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DecoratorConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration$Builder
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.FeatureRadiusConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MegaTreeConfiguration
- XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.NoiseDependantDecoratorConfiguration
+ XXX.feature.configurations.NoneDecoratorConfiguration
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.package-info
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$1
+ XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- XXX.feature.configurations.RandomRandomFeatureConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSpheroidConfiguration
- XXX.feature.configurations.SeagrassFeatureConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SmallTreeConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.VillageConfiguration
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
- XXX.level.biome.BasaltDeltasBiome
+ XXX.level.biome.BeachBiome
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$BiomeCategory
- XXX.level.biome.Biome$BiomeTempCategory
+ XXX.level.biome.Biome$ClimateParameters
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$SpawnerData
- XXX.level.biome.BiomeDefaultFeatures
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSourceSettings
+ XXX.level.biome.BiomeSourceType
- XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.BiomeSpecialEffects$1
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeZoomer
+ XXX.level.biome.BirchForestBiome
- XXX.level.biome.BirchForestHillsBiome
+ XXX.level.biome.CheckerboardBiomeSourceSettings
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.ColdOceanBiome
- XXX.level.biome.CrimsonForestBiome
+ XXX.level.biome.DarkForestBiome
- XXX.level.biome.DarkForestHillsBiome
+ XXX.level.biome.DeepColdOceanBiome
- XXX.level.biome.DeepFrozenOceanBiome
+ XXX.level.biome.DeepLukeWarmOceanBiome
- XXX.level.biome.DeepOceanBiome
+ XXX.level.biome.DeepWarmOceanBiome
- XXX.level.biome.DesertBiome
+ XXX.level.biome.DesertHillsBiome
- XXX.level.biome.DesertLakesBiome
+ XXX.level.biome.EndBarrensBiome
- XXX.level.biome.EndHighlandsBiome
+ XXX.level.biome.EndMidlandsBiome
- XXX.level.biome.ErodedBadlandsBiome
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.FixedBiomeSourceSettings
+ XXX.level.biome.ForestBiome
- XXX.level.biome.ForestFlowerBiome
+ XXX.level.biome.FrozenOceanBiome
- XXX.level.biome.FrozenRiverBiome
+ XXX.level.biome.FuzzyOffsetBiomeZoomer
- XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ XXX.level.biome.GiantSpruceTaigaBiome
- XXX.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ XXX.level.biome.GiantTreeTaigaBiome
- XXX.level.biome.GiantTreeTaigaHillsBiome
+ XXX.level.biome.GravellyMountainsBiome
- XXX.level.biome.IceSpikesBiome
+ XXX.level.biome.JungleBiome
- XXX.level.biome.JungleEdgeBiome
+ XXX.level.biome.JungleHillsBiome
- XXX.level.biome.LukeWarmOceanBiome
+ XXX.level.biome.ModifiedBadlandsPlateauBiome
- XXX.level.biome.ModifiedGravellyMountainsBiome
+ XXX.level.biome.ModifiedJungleBiome
- XXX.level.biome.ModifiedJungleEdgeBiome
+ XXX.level.biome.ModifiedWoodedBadlandsPlateauBiome
- XXX.level.biome.MountainBiome
+ XXX.level.biome.MountainEdgeBiome
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceSettings
- XXX.level.biome.MushroomFieldsBiome
+ XXX.level.biome.MushroomFieldsShoreBiome
- XXX.level.biome.NearestNeighborBiomeZoomer
+ XXX.level.biome.NetherWastesBiome
- XXX.level.biome.OceanBiome
+ XXX.level.biome.OverworldBiomeSource
- XXX.level.biome.OverworldBiomeSourceSettings
+ XXX.level.biome.package-info
+ XXX.level.biome.PlainsBiome
- XXX.level.biome.RiverBiome
+ XXX.level.biome.SavannaBiome
- XXX.level.biome.SavannaPlateauBiome
+ XXX.level.biome.ShatteredSavannaBiome
- XXX.level.biome.ShatteredSavannaPlateauBiome
+ XXX.level.biome.SmallEndIslandsBiome
- XXX.level.biome.SnowyBeachBiome
+ XXX.level.biome.SnowyMountainsBiome
- XXX.level.biome.SnowyTaigaBiome
+ XXX.level.biome.SnowyTaigaHillsBiome
- XXX.level.biome.SnowyTaigaMountainsBiome
+ XXX.level.biome.SnowyTundraBiome
- XXX.level.biome.SoulSandValleyBiome
+ XXX.level.biome.StoneShoreBiome
- XXX.level.biome.SunflowerPlainsBiome
+ XXX.level.biome.SwampBiome
- XXX.level.biome.SwampHillsBiome
+ XXX.level.biome.TaigaBiome
- XXX.level.biome.TaigaHillsBiome
+ XXX.level.biome.TaigaMountainsBiome
- XXX.level.biome.TallBirchForestBiome
+ XXX.level.biome.TallBirchHillsBiome
- XXX.level.biome.TheEndBiome
+ XXX.level.biome.TheEndBiomeSource
- XXX.level.biome.TheEndBiomeSourceSettings
+ XXX.level.biome.TheVoidBiome
- XXX.level.biome.WarmOceanBiome
+ XXX.level.biome.WarpedForestBiome
- XXX.level.biome.WoodedBadlandsBiome
+ XXX.level.biome.WoodedHillsBiome
- XXX.level.biome.WoodedMountainBiome
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AnvilBlock
+ XXX.level.block.AttachedStemBlock
- XXX.level.block.BambooBlock
+ XXX.level.block.BambooSaplingBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BaseFireBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BedBlock$1
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$BlockStatePairKey
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.CocoaBlock$1
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DispenserBlock
+ XXX.level.block.DoorBlock
- XXX.level.block.DoorBlock$1
+ XXX.level.block.DoubleBlockCombiner
- XXX.level.block.DoubleBlockCombiner$BlockType
+ XXX.level.block.DoubleBlockCombiner$Combiner
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ XXX.level.block.DoublePlantBlock
- XXX.level.block.DragonEggBlock
+ XXX.level.block.DropperBlock
- XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
+ XXX.level.block.EndRodBlock$1
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FletchingTableBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GlassBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.levelgen.package-info
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureFeature
- XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DarkOakFeature
- XXX.levelgen.feature.DecoratedFeature
+ XXX.levelgen.feature.DecoratedFlowerFeature
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.SavannaVillagePools
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.ShipwreckFeature
+ XXX.levelgen.feature.ShipwreckFeature$FeatureStart
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SimulatedFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SnowyVillagePools
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$1
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.StrongholdFeature
+ XXX.levelgen.feature.StrongholdFeature$StrongholdStart
- XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.StructureFeature$StructureStartFactory
- XXX.levelgen.feature.StructurePieceType
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.TaigaVillagePools
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VillageFeature$FeatureStart
- XXX.levelgen.feature.VillagePieces
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
+ XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
+ XXX.levelgen.placement.ChanceDecoratorConfiguration
- XXX.levelgen.placement.ChanceHeightmapDecorator
+ XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.ChancePassthroughDecorator
+ XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
- XXX.levelgen.placement.ChorusPlantPlacementDecorator
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountBiasedRangeDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDecorator
- XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.CountDepthAverageDecorator
- XXX.levelgen.placement.CountHeighmapDoubleDecorator
+ XXX.levelgen.placement.CountHeight64Decorator
- XXX.levelgen.placement.CountHeightmap32Decorator
+ XXX.levelgen.placement.CountHeightmapDecorator
- XXX.levelgen.placement.CountTopSolidDecorator
+ XXX.levelgen.placement.CountVeryBiasedRangeDecorator
- XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DepthAverageConfigation
+ XXX.levelgen.placement.EmeraldPlacementDecorator
- XXX.levelgen.placement.EndGatewayPlacementDecorator
+ XXX.levelgen.placement.EndIslandPlacementDecorator
- XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.ForestRockPlacementDecorator
- XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
+ XXX.levelgen.placement.FrequencyDecoratorConfiguration
- XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ XXX.levelgen.placement.IcebergPlacementDecorator
- XXX.levelgen.placement.LakeLavaPlacementDecorator
+ XXX.levelgen.placement.LakeWaterPlacementDecorator
- XXX.levelgen.placement.MonsterRoomPlacementDecorator
+ XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- XXX.levelgen.placement.NoiseHeightmap32Decorator
+ XXX.levelgen.placement.NoiseHeightmapDoubleDecorator
- XXX.levelgen.placement.NopePlacementDecorator
+ XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.RangeDecoratorConfiguration
- XXX.levelgen.placement.SimpleFeatureDecorator
+ XXX.levelgen.placement.TopSolidHeightMapDecorator
- XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
- XXX.levelgen.structure.BeardedStructureStart
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
- XXX.levelgen.structure.JunglePyramidPiece$1
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
- XXX.levelgen.structure.MineShaftPieces$1
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
- XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
- XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
- XXX.levelgen.structure.NetherBridgePieces
+ XXX.levelgen.structure.NetherBridgePieces$1
- XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
- XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
- XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
- XXX.levelgen.structure.NetherBridgePieces$StartPiece
+ XXX.levelgen.structure.NetherFossilFeature
- XXX.levelgen.structure.NetherFossilFeature$FeatureStart
+ XXX.levelgen.structure.NetherFossilPieces
- XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ XXX.levelgen.structure.OceanMonumentPieces
- XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature
- XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ XXX.levelgen.structure.OceanRuinFeature$Type
- XXX.levelgen.structure.OceanRuinPieces
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PillagerOutpostPieces
+ XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.ShipwreckPieces
+ XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$1
- XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$3
- XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FillerCorridor
- XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$LeftTurn
- XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PieceWeight
- XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$PrisonHall
- XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$RoomCrossing
- XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StairsDown
- XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$Straight
- XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructureFeatureIO
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureStart$1
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
- XXX.levelgen.structure.WoodlandMansionPieces$1
+ XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
- XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
- XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.minecraft.core.BlockPos$4
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockSource
+ XXX.minecraft.core.BlockSourceImpl
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
+ XXX.minecraft.core.Direction$1
- XXX.minecraft.core.Direction$Axis
+ XXX.minecraft.core.Direction$Axis$1
- XXX.minecraft.core.Direction$Axis$2
+ XXX.minecraft.core.Direction$Axis$3
- XXX.minecraft.core.Direction$AxisDirection
+ XXX.minecraft.core.Direction$Plane
- XXX.minecraft.core.Direction8
+ XXX.minecraft.core.FrontAndTop
- XXX.minecraft.core.GlobalPos
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.LocatableSource
- XXX.minecraft.core.Location
+ XXX.minecraft.core.MapFiller
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.NonNullList
- XXX.minecraft.core.Position
+ XXX.minecraft.core.PositionImpl
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.SerializableBoolean
+ XXX.minecraft.core.SerializableLong
- XXX.minecraft.core.SerializableUUID
+ XXX.minecraft.core.Source
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
- XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$Entry
- XXX.minecraft.tags.Tag$Named
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.placement.nether.ChanceRangeDecorator
+ XXX.placement.nether.CountRangeDecorator
- XXX.placement.nether.FireDecorator
+ XXX.placement.nether.LightGemChanceDecorator
- XXX.placement.nether.MagmaDecorator
- XXX.placement.nether.package-info
+ XXX.placement.nether.RandomCountRangeDecorator
+ XXX.renderer.entity.package-info
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.AtlasSet
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.LayeredTexture
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.ItemSteerableMount
- XXX.world.entity.Saddleable
- XXX.world.item.Vanishable
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.Wearable
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
<hr/>