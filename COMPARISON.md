## Comparison with [26.2](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.2)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>DataPack version</td><td><pre>107.1</pre></td><td><pre>108.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>88.0</pre></td><td><pre>89.0</pre></td></tr><tr><td>World version</td><td><pre>4903</pre></td><td><pre>4998</pre></td></tr><tr><td>Protocol version</td><td><pre>776</pre></td><td><pre>1073742147</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- decorated_pot_pattern.txt
+ worldgen/feature_type.txt
- worldgen/feature.txt
+ worldgen/material_condition_type.txt
- worldgen/material_condition.txt
+ worldgen/material_rule_type.txt
- worldgen/material_rule.txt
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:black_wool_slab
+ minecraft:black_wool_stairs
+ minecraft:blue_wool_slab
+ minecraft:blue_wool_stairs
+ minecraft:brown_wool_slab
+ minecraft:brown_wool_stairs
+ minecraft:cyan_wool_slab
+ minecraft:cyan_wool_stairs
+ minecraft:gray_wool_slab
+ minecraft:gray_wool_stairs
+ minecraft:green_wool_slab
+ minecraft:green_wool_stairs
+ minecraft:light_blue_wool_slab
+ minecraft:light_blue_wool_stairs
+ minecraft:light_gray_wool_slab
+ minecraft:light_gray_wool_stairs
+ minecraft:lime_wool_slab
+ minecraft:lime_wool_stairs
+ minecraft:magenta_wool_slab
+ minecraft:magenta_wool_stairs
+ minecraft:orange_poplar_leaves
+ minecraft:orange_wool_slab
+ minecraft:orange_wool_stairs
+ minecraft:pink_wool_slab
+ minecraft:pink_wool_stairs
+ minecraft:poplar_button
+ minecraft:poplar_door
+ minecraft:poplar_fence
+ minecraft:poplar_fence_gate
+ minecraft:poplar_hanging_sign
+ minecraft:poplar_log
+ minecraft:poplar_planks
+ minecraft:poplar_pressure_plate
+ minecraft:poplar_sapling
+ minecraft:poplar_shelf
+ minecraft:poplar_sign
+ minecraft:poplar_slab
+ minecraft:poplar_stairs
+ minecraft:poplar_trapdoor
+ minecraft:poplar_wall_hanging_sign
+ minecraft:poplar_wall_sign
+ minecraft:poplar_wood
+ minecraft:potted_poplar_sapling
+ minecraft:purple_wool_slab
+ minecraft:purple_wool_stairs
+ minecraft:red_poplar_leaves
+ minecraft:red_shrub
+ minecraft:red_wool_slab
+ minecraft:red_wool_stairs
+ minecraft:shelf_mushroom
+ minecraft:stripped_poplar_log
+ minecraft:stripped_poplar_wood
+ minecraft:white_wool_slab
+ minecraft:white_wool_stairs
+ minecraft:yellow_poplar_leaves
+ minecraft:yellow_wool_slab
+ minecraft:yellow_wool_stairs
```

</details>
<details>
<summary>
block_type
</summary>

```diff
- minecraft:dirt_path
+ minecraft:leaves
+ minecraft:path
+ minecraft:shelf_mushroom
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
+ minecraft:slot_source
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:provides_pottery_pattern
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:poplar_boat
+ minecraft:poplar_chest_boat
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:black_wool_slab
+ minecraft:black_wool_stairs
+ minecraft:blue_wool_slab
+ minecraft:blue_wool_stairs
+ minecraft:brown_wool_slab
+ minecraft:brown_wool_stairs
+ minecraft:cyan_wool_slab
+ minecraft:cyan_wool_stairs
+ minecraft:gray_wool_slab
+ minecraft:gray_wool_stairs
+ minecraft:green_wool_slab
+ minecraft:green_wool_stairs
+ minecraft:light_blue_wool_slab
+ minecraft:light_blue_wool_stairs
+ minecraft:light_gray_wool_slab
+ minecraft:light_gray_wool_stairs
+ minecraft:lime_wool_slab
+ minecraft:lime_wool_stairs
+ minecraft:magenta_wool_slab
+ minecraft:magenta_wool_stairs
+ minecraft:orange_poplar_leaves
+ minecraft:orange_wool_slab
+ minecraft:orange_wool_stairs
+ minecraft:pink_wool_slab
+ minecraft:pink_wool_stairs
+ minecraft:poplar_boat
+ minecraft:poplar_button
+ minecraft:poplar_chest_boat
+ minecraft:poplar_door
+ minecraft:poplar_fence
+ minecraft:poplar_fence_gate
+ minecraft:poplar_hanging_sign
+ minecraft:poplar_log
+ minecraft:poplar_planks
+ minecraft:poplar_pressure_plate
+ minecraft:poplar_sapling
+ minecraft:poplar_shelf
+ minecraft:poplar_sign
+ minecraft:poplar_slab
+ minecraft:poplar_stairs
+ minecraft:poplar_trapdoor
+ minecraft:poplar_wood
+ minecraft:purple_wool_slab
+ minecraft:purple_wool_stairs
+ minecraft:red_poplar_leaves
+ minecraft:red_shrub
+ minecraft:red_wool_slab
+ minecraft:red_wool_stairs
+ minecraft:shelf_mushroom
+ minecraft:stripped_poplar_log
+ minecraft:stripped_poplar_wood
+ minecraft:white_wool_slab
+ minecraft:white_wool_stairs
+ minecraft:yellow_poplar_leaves
+ minecraft:yellow_wool_slab
+ minecraft:yellow_wool_stairs
```

</details>
<details>
<summary>
outgoing_rpc_methods
</summary>

```diff
+ minecraft:notification/world/upgrade_failed
+ minecraft:notification/world/upgrade_finished
+ minecraft:notification/world/upgrade_progress
+ minecraft:notification/world/upgrade_started
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:orange_poplar_leaves
+ minecraft:red_poplar_leaves
+ minecraft:yellow_poplar_leaves
```

</details>
<details>
<summary>
rule_test
</summary>

```diff
+ minecraft:all_of
+ minecraft:height_match
```

</details>
<details>
<summary>
slot_source_type
</summary>

```diff
+ minecraft:reference
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.poplar_leaves.ambient
+ minecraft:block.shelf_mushroom.bounce
+ minecraft:block.shelf_mushroom.break
+ minecraft:block.shelf_mushroom.fall
+ minecraft:block.shelf_mushroom.place
+ minecraft:block.shelf_mushroom.step
```

</details>
<details>
<summary>
test_environment_definition_type
</summary>

```diff
+ minecraft:dimension
```

</details>
<details>
<summary>
worldgen/foliage_placer_type
</summary>

```diff
+ minecraft:poplar_foliage_placer
```

</details>
<details>
<summary>
worldgen/structure_placement
</summary>

```diff
+ minecraft:dimension_origin
```

</details>
<details>
<summary>
worldgen/tree_decorator_type
</summary>

```diff
+ minecraft:shelf_mushroom
```

</details>
<details>
<summary>
worldgen/trunk_placer_type
</summary>

```diff
+ minecraft:poplar_trunk_placer
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- universal_tags/decorated_pot_pattern.json
+ universal_tags/worldgen/feature_type.json
- universal_tags/worldgen/feature.json
+ universal_tags/worldgen/material_condition_type.json
- universal_tags/worldgen/material_condition.json
+ universal_tags/worldgen/material_rule_type.json
- universal_tags/worldgen/material_rule.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:poplar_wall_hanging_sign
+ minecraft:poplar_wall_sign
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:black_wool_slab
+ minecraft:black_wool_stairs
+ minecraft:blue_wool_slab
+ minecraft:blue_wool_stairs
+ minecraft:brown_wool_slab
+ minecraft:brown_wool_stairs
+ minecraft:cyan_wool_slab
+ minecraft:cyan_wool_stairs
+ minecraft:gray_wool_slab
+ minecraft:gray_wool_stairs
+ minecraft:green_wool_slab
+ minecraft:green_wool_stairs
+ minecraft:light_blue_wool_slab
+ minecraft:light_blue_wool_stairs
+ minecraft:light_gray_wool_slab
+ minecraft:light_gray_wool_stairs
+ minecraft:lime_wool_slab
+ minecraft:lime_wool_stairs
+ minecraft:magenta_wool_slab
+ minecraft:magenta_wool_stairs
+ minecraft:orange_poplar_leaves
+ minecraft:orange_wool_slab
+ minecraft:orange_wool_stairs
+ minecraft:pink_wool_slab
+ minecraft:pink_wool_stairs
+ minecraft:poplar_button
+ minecraft:poplar_door
+ minecraft:poplar_fence
+ minecraft:poplar_fence_gate
+ minecraft:poplar_hanging_sign
+ minecraft:poplar_log
+ minecraft:poplar_planks
+ minecraft:poplar_pressure_plate
+ minecraft:poplar_sapling
+ minecraft:poplar_shelf
+ minecraft:poplar_sign
+ minecraft:poplar_slab
+ minecraft:poplar_stairs
+ minecraft:poplar_trapdoor
+ minecraft:poplar_wood
+ minecraft:potted_poplar_sapling
+ minecraft:purple_wool_slab
+ minecraft:purple_wool_stairs
+ minecraft:red_poplar_leaves
+ minecraft:red_shrub
+ minecraft:red_wool_slab
+ minecraft:red_wool_stairs
+ minecraft:shelf_mushroom
+ minecraft:stripped_poplar_log
+ minecraft:stripped_poplar_wood
+ minecraft:white_wool_slab
+ minecraft:white_wool_stairs
+ minecraft:yellow_poplar_leaves
+ minecraft:yellow_wool_slab
+ minecraft:yellow_wool_stairs
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:poplar_boat
+ minecraft:poplar_chest_boat
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:black_wool_slab
+ minecraft:black_wool_stairs
+ minecraft:blue_wool_slab
+ minecraft:blue_wool_stairs
+ minecraft:brown_wool_slab
+ minecraft:brown_wool_stairs
+ minecraft:cyan_wool_slab
+ minecraft:cyan_wool_stairs
+ minecraft:gray_wool_slab
+ minecraft:gray_wool_stairs
+ minecraft:green_wool_slab
+ minecraft:green_wool_stairs
+ minecraft:light_blue_wool_slab
+ minecraft:light_blue_wool_stairs
+ minecraft:light_gray_wool_slab
+ minecraft:light_gray_wool_stairs
+ minecraft:lime_wool_slab
+ minecraft:lime_wool_stairs
+ minecraft:magenta_wool_slab
+ minecraft:magenta_wool_stairs
+ minecraft:orange_poplar_leaves
+ minecraft:orange_wool_slab
+ minecraft:orange_wool_stairs
+ minecraft:pink_wool_slab
+ minecraft:pink_wool_stairs
+ minecraft:poplar_button
+ minecraft:poplar_door
+ minecraft:poplar_fence
+ minecraft:poplar_fence_gate
+ minecraft:poplar_hanging_sign
+ minecraft:poplar_log
+ minecraft:poplar_planks
+ minecraft:poplar_pressure_plate
+ minecraft:poplar_sapling
+ minecraft:poplar_shelf
+ minecraft:poplar_sign
+ minecraft:poplar_slab
+ minecraft:poplar_stairs
+ minecraft:poplar_trapdoor
+ minecraft:poplar_wall_hanging_sign
+ minecraft:poplar_wall_sign
+ minecraft:poplar_wood
+ minecraft:potted_poplar_sapling
+ minecraft:purple_wool_slab
+ minecraft:purple_wool_stairs
+ minecraft:red_poplar_leaves
+ minecraft:red_shrub
+ minecraft:red_wool_slab
+ minecraft:red_wool_stairs
+ minecraft:shelf_mushroom
+ minecraft:stripped_poplar_log
+ minecraft:stripped_poplar_wood
+ minecraft:white_wool_slab
+ minecraft:white_wool_stairs
+ minecraft:yellow_poplar_leaves
+ minecraft:yellow_wool_slab
+ minecraft:yellow_wool_stairs
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
- minecraft:dirt_path
+ minecraft:leaves
+ minecraft:path
+ minecraft:shelf_mushroom
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:slot_source
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:provides_pottery_pattern
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:poplar_boat
+ minecraft:poplar_chest_boat
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:black_wool_slab
+ minecraft:black_wool_stairs
+ minecraft:blue_wool_slab
+ minecraft:blue_wool_stairs
+ minecraft:brown_wool_slab
+ minecraft:brown_wool_stairs
+ minecraft:cyan_wool_slab
+ minecraft:cyan_wool_stairs
+ minecraft:gray_wool_slab
+ minecraft:gray_wool_stairs
+ minecraft:green_wool_slab
+ minecraft:green_wool_stairs
+ minecraft:light_blue_wool_slab
+ minecraft:light_blue_wool_stairs
+ minecraft:light_gray_wool_slab
+ minecraft:light_gray_wool_stairs
+ minecraft:lime_wool_slab
+ minecraft:lime_wool_stairs
+ minecraft:magenta_wool_slab
+ minecraft:magenta_wool_stairs
+ minecraft:orange_poplar_leaves
+ minecraft:orange_wool_slab
+ minecraft:orange_wool_stairs
+ minecraft:pink_wool_slab
+ minecraft:pink_wool_stairs
+ minecraft:poplar_boat
+ minecraft:poplar_button
+ minecraft:poplar_chest_boat
+ minecraft:poplar_door
+ minecraft:poplar_fence
+ minecraft:poplar_fence_gate
+ minecraft:poplar_hanging_sign
+ minecraft:poplar_log
+ minecraft:poplar_planks
+ minecraft:poplar_pressure_plate
+ minecraft:poplar_sapling
+ minecraft:poplar_shelf
+ minecraft:poplar_sign
+ minecraft:poplar_slab
+ minecraft:poplar_stairs
+ minecraft:poplar_trapdoor
+ minecraft:poplar_wood
+ minecraft:purple_wool_slab
+ minecraft:purple_wool_stairs
+ minecraft:red_poplar_leaves
+ minecraft:red_shrub
+ minecraft:red_wool_slab
+ minecraft:red_wool_stairs
+ minecraft:shelf_mushroom
+ minecraft:stripped_poplar_log
+ minecraft:stripped_poplar_wood
+ minecraft:white_wool_slab
+ minecraft:white_wool_stairs
+ minecraft:yellow_poplar_leaves
+ minecraft:yellow_wool_slab
+ minecraft:yellow_wool_stairs
```

</details>
<details>
<summary>
universal_tags/outgoing_rpc_methods.json
</summary>

```diff
+ minecraft:notification/world/upgrade_failed
+ minecraft:notification/world/upgrade_finished
+ minecraft:notification/world/upgrade_progress
+ minecraft:notification/world/upgrade_started
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:orange_poplar_leaves
+ minecraft:red_poplar_leaves
+ minecraft:yellow_poplar_leaves
```

</details>
<details>
<summary>
universal_tags/rule_test.json
</summary>

```diff
+ minecraft:all_of
+ minecraft:height_match
```

</details>
<details>
<summary>
universal_tags/slot_source_type.json
</summary>

```diff
+ minecraft:reference
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.poplar_leaves.ambient
+ minecraft:block.shelf_mushroom.bounce
+ minecraft:block.shelf_mushroom.break
+ minecraft:block.shelf_mushroom.fall
+ minecraft:block.shelf_mushroom.place
+ minecraft:block.shelf_mushroom.step
```

</details>
<details>
<summary>
universal_tags/test_environment_definition_type.json
</summary>

```diff
+ minecraft:dimension
```

</details>
<details>
<summary>
universal_tags/worldgen/foliage_placer_type.json
</summary>

```diff
+ minecraft:poplar_foliage_placer
```

</details>
<details>
<summary>
universal_tags/worldgen/structure_placement.json
</summary>

```diff
+ minecraft:dimension_origin
```

</details>
<details>
<summary>
universal_tags/worldgen/tree_decorator_type.json
</summary>

```diff
+ minecraft:shelf_mushroom
```

</details>
<details>
<summary>
universal_tags/worldgen/trunk_placer_type.json
</summary>

```diff
+ minecraft:poplar_trunk_placer
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
+ black_wool_slab.json
+ black_wool_stairs.json
+ blue_wool_slab.json
+ blue_wool_stairs.json
+ brown_wool_slab.json
+ brown_wool_stairs.json
+ cyan_wool_slab.json
+ cyan_wool_stairs.json
+ gray_wool_slab.json
+ gray_wool_stairs.json
+ green_wool_slab.json
+ green_wool_stairs.json
+ light_blue_wool_slab.json
+ light_blue_wool_stairs.json
+ light_gray_wool_slab.json
+ light_gray_wool_stairs.json
+ lime_wool_slab.json
+ lime_wool_stairs.json
+ magenta_wool_slab.json
+ magenta_wool_stairs.json
+ orange_poplar_leaves.json
+ orange_wool_slab.json
+ orange_wool_stairs.json
+ pink_wool_slab.json
+ pink_wool_stairs.json
+ poplar_button.json
+ poplar_door.json
+ poplar_fence_gate.json
+ poplar_fence.json
+ poplar_hanging_sign.json
+ poplar_log.json
+ poplar_planks.json
+ poplar_pressure_plate.json
+ poplar_sapling.json
+ poplar_shelf.json
+ poplar_sign.json
+ poplar_slab.json
+ poplar_stairs.json
+ poplar_trapdoor.json
+ poplar_wall_hanging_sign.json
+ poplar_wall_sign.json
+ poplar_wood.json
+ potted_poplar_sapling.json
+ purple_wool_slab.json
+ purple_wool_stairs.json
+ red_poplar_leaves.json
+ red_shrub.json
+ red_wool_slab.json
+ red_wool_stairs.json
+ shelf_mushroom.json
+ stripped_poplar_log.json
+ stripped_poplar_wood.json
+ white_wool_slab.json
+ white_wool_stairs.json
+ yellow_poplar_leaves.json
+ yellow_wool_slab.json
+ yellow_wool_stairs.json
```

</details>
<details>
<summary>
azalea_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>/</pre></td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>shape_height</td><td><pre>/</pre></td><td><pre>13</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>/</pre></td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt_path
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>type</td><td><pre>minecraft:dirt_path</pre></td><td><pre>minecraft:path</pre></td></tr><tr><td>base_block</td><td><pre>/</pre></td><td><pre>minecraft:dirt</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
farmland
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>turns_into</td><td><pre>/</pre></td><td><pre>minecraft:dirt</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>/</pre></td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>/</pre></td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_petals
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>shape_height</td><td><pre>/</pre></td><td><pre>3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>type</td><td><pre>minecraft:tinted_particle_leaves</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>/</pre></td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wildflowers
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>shape_height</td><td><pre>/</pre></td><td><pre>3</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ data get block <target: block_pos> <path: nbt_path> <scale: double>
- data get block <targetPos: block_pos> <path: nbt_path> <scale: double>
+ data merge block <target: block_pos> <nbt: nbt_compound_tag>
- data merge block <targetPos: block_pos> <nbt: nbt_compound_tag>
+ data modify block <target: block_pos> <targetPath: nbt_path> append from block <source: block_pos> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> append from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> append from storage <source: resource_location> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> append string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> append string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> append string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> append value <value: nbt_tag>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> from block <source: block_pos> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> from storage <source: resource_location> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> value <value: nbt_tag>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge from block <source: block_pos> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge from storage <source: resource_location> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge value <value: nbt_tag>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend from block <source: block_pos> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend from storage <source: resource_location> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend value <value: nbt_tag>
+ data modify block <target: block_pos> <targetPath: nbt_path> set from block <source: block_pos> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> set from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> set from storage <source: resource_location> <sourcePath: nbt_path>
+ data modify block <target: block_pos> <targetPath: nbt_path> set string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> set string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> set string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify block <target: block_pos> <targetPath: nbt_path> set value <value: nbt_tag>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> append from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> append from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> append from storage <source: resource_location> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> append string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> append string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> append string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> append value <value: nbt_tag>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> from storage <source: resource_location> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> value <value: nbt_tag>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> merge from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> merge from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> merge from storage <source: resource_location> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> merge string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> merge string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> merge string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> merge value <value: nbt_tag>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend from storage <source: resource_location> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend value <value: nbt_tag>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> set from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> set from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> set from storage <source: resource_location> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> set string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> set string entity <source: entity> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> set string storage <source: resource_location> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> set value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> append from block <source: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> append from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> append string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify entity <target: entity> <targetPath: nbt_path> append string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> from block <source: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify entity <target: entity> <targetPath: nbt_path> merge from block <source: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> merge from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> merge string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify entity <target: entity> <targetPath: nbt_path> merge string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify entity <target: entity> <targetPath: nbt_path> prepend from block <source: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> prepend from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> prepend string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify entity <target: entity> <targetPath: nbt_path> prepend string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify entity <target: entity> <targetPath: nbt_path> set from block <source: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> set from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> set string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify entity <target: entity> <targetPath: nbt_path> set string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify storage <target: resource_location> <targetPath: nbt_path> append from block <source: block_pos> <sourcePath: nbt_path>
- data modify storage <target: resource_location> <targetPath: nbt_path> append from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify storage <target: resource_location> <targetPath: nbt_path> append string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify storage <target: resource_location> <targetPath: nbt_path> append string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> from block <source: block_pos> <sourcePath: nbt_path>
- data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify storage <target: resource_location> <targetPath: nbt_path> merge from block <source: block_pos> <sourcePath: nbt_path>
- data modify storage <target: resource_location> <targetPath: nbt_path> merge from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify storage <target: resource_location> <targetPath: nbt_path> merge string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify storage <target: resource_location> <targetPath: nbt_path> merge string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify storage <target: resource_location> <targetPath: nbt_path> prepend from block <source: block_pos> <sourcePath: nbt_path>
- data modify storage <target: resource_location> <targetPath: nbt_path> prepend from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify storage <target: resource_location> <targetPath: nbt_path> prepend string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify storage <target: resource_location> <targetPath: nbt_path> prepend string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data modify storage <target: resource_location> <targetPath: nbt_path> set from block <source: block_pos> <sourcePath: nbt_path>
- data modify storage <target: resource_location> <targetPath: nbt_path> set from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify storage <target: resource_location> <targetPath: nbt_path> set string block <source: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
- data modify storage <target: resource_location> <targetPath: nbt_path> set string block <sourcePos: block_pos> <sourcePath: nbt_path> <start: integer> <end: integer>
+ data remove block <target: block_pos> <path: nbt_path>
- data remove block <targetPos: block_pos> <path: nbt_path>
```

</details>
<details>
<summary>
execute
</summary>

```diff
+ execute if data block <source: block_pos> <path: nbt_path>
- execute if data block <sourcePos: block_pos> <path: nbt_path>
- execute if items block <pos: block_pos> <slots: item_slots> <item_predicate: item_predicate>
+ execute if items block <source: block_pos> <slots: slot_source> <item_predicate: item_predicate>
- execute if items entity <entities: entity> <slots: item_slots> <item_predicate: item_predicate>
+ execute if items entity <source: entity> <slots: slot_source> <item_predicate: item_predicate>
+ execute if slots block <source: block_pos> <slots: slot_source>
+ execute if slots entity <source: entity> <slots: slot_source>
+ execute store result block <target: block_pos> <path: nbt_path> byte <scale: double>
+ execute store result block <target: block_pos> <path: nbt_path> double <scale: double>
+ execute store result block <target: block_pos> <path: nbt_path> float <scale: double>
+ execute store result block <target: block_pos> <path: nbt_path> int <scale: double>
+ execute store result block <target: block_pos> <path: nbt_path> long <scale: double>
+ execute store result block <target: block_pos> <path: nbt_path> short <scale: double>
- execute store result block <targetPos: block_pos> <path: nbt_path> byte <scale: double>
- execute store result block <targetPos: block_pos> <path: nbt_path> double <scale: double>
- execute store result block <targetPos: block_pos> <path: nbt_path> float <scale: double>
- execute store result block <targetPos: block_pos> <path: nbt_path> int <scale: double>
- execute store result block <targetPos: block_pos> <path: nbt_path> long <scale: double>
- execute store result block <targetPos: block_pos> <path: nbt_path> short <scale: double>
+ execute store success block <target: block_pos> <path: nbt_path> byte <scale: double>
+ execute store success block <target: block_pos> <path: nbt_path> double <scale: double>
+ execute store success block <target: block_pos> <path: nbt_path> float <scale: double>
+ execute store success block <target: block_pos> <path: nbt_path> int <scale: double>
+ execute store success block <target: block_pos> <path: nbt_path> long <scale: double>
+ execute store success block <target: block_pos> <path: nbt_path> short <scale: double>
- execute store success block <targetPos: block_pos> <path: nbt_path> byte <scale: double>
- execute store success block <targetPos: block_pos> <path: nbt_path> double <scale: double>
- execute store success block <targetPos: block_pos> <path: nbt_path> float <scale: double>
- execute store success block <targetPos: block_pos> <path: nbt_path> int <scale: double>
- execute store success block <targetPos: block_pos> <path: nbt_path> long <scale: double>
- execute store success block <targetPos: block_pos> <path: nbt_path> short <scale: double>
+ execute unless data block <source: block_pos> <path: nbt_path>
- execute unless data block <sourcePos: block_pos> <path: nbt_path>
- execute unless items block <pos: block_pos> <slots: item_slots> <item_predicate: item_predicate>
+ execute unless items block <source: block_pos> <slots: slot_source> <item_predicate: item_predicate>
- execute unless items entity <entities: entity> <slots: item_slots> <item_predicate: item_predicate>
+ execute unless items entity <source: entity> <slots: slot_source> <item_predicate: item_predicate>
+ execute unless slots block <source: block_pos> <slots: slot_source>
+ execute unless slots entity <source: entity> <slots: slot_source>
```

</details>
<details>
<summary>
function
</summary>

```diff
+ function <name: function> with block <source: block_pos> <path: nbt_path>
- function <name: function> with block <sourcePos: block_pos> <path: nbt_path>
```

</details>
<details>
<summary>
item
</summary>

```diff
+ item fill block <target: block_pos> <slots: slot_source> from block <source: block_pos> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item fill block <target: block_pos> <slots: slot_source> from entity <source: entity> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item fill block <target: block_pos> <slots: slot_source> with <item: item_stack> <count: integer>
+ item fill entity <target: entity> <slots: slot_source> from block <source: block_pos> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item fill entity <target: entity> <slots: slot_source> from entity <source: entity> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item fill entity <target: entity> <slots: slot_source> with <item: item_stack> <count: integer>
- item modify block <pos: block_pos> <slot: item_slot> <modifier: loot_modifier>
+ item modify block <target: block_pos> <slots: slot_source> <modifier: loot_modifier>
+ item modify entity <target: entity> <slots: slot_source> <modifier: loot_modifier>
- item modify entity <targets: entity> <slot: item_slot> <modifier: loot_modifier>
+ item override block <target: block_pos> <slots: slot_source> from block <source: block_pos> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item override block <target: block_pos> <slots: slot_source> from entity <source: entity> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item override block <target: block_pos> <slots: slot_source> with <item: item_stack> <count: integer>
+ item override entity <target: entity> <slots: slot_source> from block <source: block_pos> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item override entity <target: entity> <slots: slot_source> from entity <source: entity> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item override entity <target: entity> <slots: slot_source> with <item: item_stack> <count: integer>
- item replace block <pos: block_pos> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: loot_modifier>
- item replace block <pos: block_pos> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: loot_modifier>
- item replace block <pos: block_pos> <slot: item_slot> with <item: item_stack> <count: integer>
+ item replace block <target: block_pos> <slots: slot_source> from block <source: block_pos> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item replace block <target: block_pos> <slots: slot_source> from entity <source: entity> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item replace block <target: block_pos> <slots: slot_source> with <item: item_stack> <count: integer>
+ item replace entity <target: entity> <slots: slot_source> from block <source: block_pos> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item replace entity <target: entity> <slots: slot_source> from entity <source: entity> <sourceSlots: slot_source> <modifier: loot_modifier>
+ item replace entity <target: entity> <slots: slot_source> with <item: item_stack> <count: integer>
- item replace entity <targets: entity> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: loot_modifier>
- item replace entity <targets: entity> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: loot_modifier>
- item replace entity <targets: entity> <slot: item_slot> with <item: item_stack> <count: integer>
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
- black_carpet.json
+ black_wool_slab.json
+ black_wool_stairs.json
- blue_carpet.json
+ blue_wool_slab.json
+ blue_wool_stairs.json
- brown_carpet.json
+ brown_wool_slab.json
+ brown_wool_stairs.json
- cyan_carpet.json
+ cyan_wool_slab.json
+ cyan_wool_stairs.json
+ dye_black_wool_slab.json
+ dye_black_wool_stairs.json
+ dye_blue_wool_slab.json
+ dye_blue_wool_stairs.json
+ dye_brown_wool_slab.json
+ dye_brown_wool_stairs.json
+ dye_cyan_wool_slab.json
+ dye_cyan_wool_stairs.json
+ dye_gray_wool_slab.json
+ dye_gray_wool_stairs.json
+ dye_green_wool_slab.json
+ dye_green_wool_stairs.json
+ dye_light_blue_wool_slab.json
+ dye_light_blue_wool_stairs.json
+ dye_light_gray_wool_slab.json
+ dye_light_gray_wool_stairs.json
+ dye_lime_wool_slab.json
+ dye_lime_wool_stairs.json
+ dye_magenta_wool_slab.json
+ dye_magenta_wool_stairs.json
+ dye_orange_wool_slab.json
+ dye_orange_wool_stairs.json
+ dye_pink_wool_slab.json
+ dye_pink_wool_stairs.json
+ dye_purple_wool_slab.json
+ dye_purple_wool_stairs.json
+ dye_red_wool_slab.json
+ dye_red_wool_stairs.json
+ dye_white_wool_slab.json
+ dye_white_wool_stairs.json
+ dye_yellow_wool_slab.json
+ dye_yellow_wool_stairs.json
- gray_carpet.json
+ gray_wool_slab.json
+ gray_wool_stairs.json
- green_carpet.json
+ green_wool_slab.json
+ green_wool_stairs.json
- light_blue_carpet.json
+ light_blue_wool_slab.json
+ light_blue_wool_stairs.json
- light_gray_carpet.json
+ light_gray_wool_slab.json
+ light_gray_wool_stairs.json
- lime_carpet.json
+ lime_wool_slab.json
+ lime_wool_stairs.json
- magenta_carpet.json
+ magenta_wool_slab.json
+ magenta_wool_stairs.json
- orange_carpet.json
+ orange_wool_slab.json
+ orange_wool_stairs.json
- pink_carpet.json
+ pink_wool_slab.json
+ pink_wool_stairs.json
+ poplar_boat.json
+ poplar_button.json
+ poplar_chest_boat.json
+ poplar_door.json
+ poplar_fence_gate.json
+ poplar_fence.json
+ poplar_hanging_sign.json
+ poplar_planks.json
+ poplar_pressure_plate.json
+ poplar_shelf.json
+ poplar_sign.json
+ poplar_slab.json
+ poplar_stairs.json
+ poplar_trapdoor.json
+ poplar_wood.json
- purple_carpet.json
+ purple_wool_slab.json
+ purple_wool_stairs.json
+ rabbit_stew_from_shelf_mushroom.json
- red_carpet.json
+ red_wool_slab.json
+ red_wool_stairs.json
+ stripped_poplar_wood.json
- white_carpet.json
+ white_wool_slab.json
+ white_wool_stairs.json
- yellow_carpet.json
+ yellow_wool_slab.json
+ yellow_wool_stairs.json
```

</details>
<details>
<summary>
mushroom_stew.json
</summary>

```
Group: none -> mushroom_stew
```
```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_allium.json
</summary>

```
Ingredients
 #mushrooms x2
 allium x1
 bowl x1
 brown_mushroom x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_azure_bluet.json
</summary>

```
Ingredients
 #mushrooms x2
 azure_bluet x1
 bowl x1
 brown_mushroom x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_blue_orchid.json
</summary>

```
Ingredients
 #mushrooms x2
 blue_orchid x1
 bowl x1
 brown_mushroom x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_closed_eyeblossom.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 closed_eyeblossom x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_cornflower.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 cornflower x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_dandelion.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 dandelion x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_golden_dandelion.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 golden_dandelion x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_lily_of_the_valley.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 lily_of_the_valley x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_open_eyeblossom.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 open_eyeblossom x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_orange_tulip.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 orange_tulip x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_oxeye_daisy.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 oxeye_daisy x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_pink_tulip.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 pink_tulip x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_poppy.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 poppy x1
 red_mushroom x1
```

</details>
<details>
<summary>
suspicious_stew_from_red_tulip.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 red_mushroom x1
 red_tulip x1
```

</details>
<details>
<summary>
suspicious_stew_from_torchflower.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 red_mushroom x1
 torchflower x1
```

</details>
<details>
<summary>
suspicious_stew_from_white_tulip.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 red_mushroom x1
 white_tulip x1
```

</details>
<details>
<summary>
suspicious_stew_from_wither_rose.json
</summary>

```
Ingredients
 #mushrooms x2
 bowl x1
 brown_mushroom x1
 red_mushroom x1
 wither_rose x1
```

</details>
</details>
<hr/>
<details><summary><b><ins>DATAPACKS</ins></b><a name="datapacks"></a></summary>
<br/>
<details>
<summary>
[registries] List
</summary>

```diff
+ minecraft:slot_source
- minecraft:worldgen/configured_feature
+ minecraft:worldgen/feature_type
+ minecraft:worldgen/material_condition_type
+ minecraft:worldgen/material_rule_type
```

</details>
<details>
<summary>
[registries] minecraft:decorated_pot_pattern
</summary>
<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>elements</td><td><pre>false</pre></td><td><pre>true</pre></td></tr><tr><td>stable</td><td><pre>true</pre></td><td><pre>false</pre></td></tr></table>
</details>
<details>
<summary>
[registries] minecraft:worldgen/feature
</summary>
<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>elements</td><td><pre>false</pre></td><td><pre>true</pre></td></tr><tr><td>stable</td><td><pre>true</pre></td><td><pre>false</pre></td></tr></table>
</details>
<details>
<summary>
[registries] minecraft:worldgen/material_condition
</summary>
<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>elements</td><td><pre>false</pre></td><td><pre>true</pre></td></tr><tr><td>stable</td><td><pre>true</pre></td><td><pre>false</pre></td></tr></table>
</details>
<details>
<summary>
[registries] minecraft:worldgen/material_rule
</summary>
<table><tr><th></th><th align="left">26.2</th><th>26.3-snapshot-1</th></tr><tr><td>elements</td><td><pre>false</pre></td><td><pre>true</pre></td></tr><tr><td>stable</td><td><pre>true</pre></td><td><pre>false</pre></td></tr></table>
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
+ biome.minecraft.dappled_forest: Dappled Forest
+ block.minecraft.black_wool_slab: Black Wool Slab
+ block.minecraft.black_wool_stairs: Black Wool Stairs
+ block.minecraft.blue_wool_slab: Blue Wool Slab
+ block.minecraft.blue_wool_stairs: Blue Wool Stairs
+ block.minecraft.brown_wool_slab: Brown Wool Slab
+ block.minecraft.brown_wool_stairs: Brown Wool Stairs
+ block.minecraft.cyan_wool_slab: Cyan Wool Slab
+ block.minecraft.cyan_wool_stairs: Cyan Wool Stairs
+ block.minecraft.gray_wool_slab: Gray Wool Slab
+ block.minecraft.gray_wool_stairs: Gray Wool Stairs
+ block.minecraft.green_wool_slab: Green Wool Slab
+ block.minecraft.green_wool_stairs: Green Wool Stairs
+ block.minecraft.light_blue_wool_slab: Light Blue Wool Slab
+ block.minecraft.light_blue_wool_stairs: Light Blue Wool Stairs
+ block.minecraft.light_gray_wool_slab: Light Gray Wool Slab
+ block.minecraft.light_gray_wool_stairs: Light Gray Wool Stairs
+ block.minecraft.lime_wool_slab: Lime Wool Slab
+ block.minecraft.lime_wool_stairs: Lime Wool Stairs
+ block.minecraft.magenta_wool_slab: Magenta Wool Slab
+ block.minecraft.magenta_wool_stairs: Magenta Wool Stairs
+ block.minecraft.orange_poplar_leaves: Orange Poplar Leaves
+ block.minecraft.orange_wool_slab: Orange Wool Slab
+ block.minecraft.orange_wool_stairs: Orange Wool Stairs
+ block.minecraft.pink_wool_slab: Pink Wool Slab
+ block.minecraft.pink_wool_stairs: Pink Wool Stairs
+ block.minecraft.poplar_button: Poplar Button
+ block.minecraft.poplar_door: Poplar Door
+ block.minecraft.poplar_fence_gate: Poplar Fence Gate
+ block.minecraft.poplar_fence: Poplar Fence
+ block.minecraft.poplar_hanging_sign: Poplar Hanging Sign
+ block.minecraft.poplar_leaves: Poplar Leaves
+ block.minecraft.poplar_log: Poplar Log
+ block.minecraft.poplar_planks: Poplar Planks
+ block.minecraft.poplar_pressure_plate: Poplar Pressure Plate
+ block.minecraft.poplar_sapling: Poplar Sapling
+ block.minecraft.poplar_shelf: Poplar Shelf
+ block.minecraft.poplar_sign: Poplar Sign
+ block.minecraft.poplar_slab: Poplar Slab
+ block.minecraft.poplar_stairs: Poplar Stairs
+ block.minecraft.poplar_trapdoor: Poplar Trapdoor
+ block.minecraft.poplar_wall_hanging_sign: Poplar Wall Hanging Sign
+ block.minecraft.poplar_wall_sign: Poplar Wall Sign
+ block.minecraft.poplar_wood: Poplar Wood
+ block.minecraft.potted_poplar_sapling: Potted Poplar Sapling
+ block.minecraft.purple_wool_slab: Purple Wool Slab
+ block.minecraft.purple_wool_stairs: Purple Wool Stairs
+ block.minecraft.red_poplar_leaves: Red Poplar Leaves
+ block.minecraft.red_shrub: Red Shrub
+ block.minecraft.red_wool_slab: Red Wool Slab
+ block.minecraft.red_wool_stairs: Red Wool Stairs
+ block.minecraft.shelf_mushroom: Shelf Mushroom
+ block.minecraft.stripped_poplar_log: Stripped Poplar Log
+ block.minecraft.stripped_poplar_wood: Stripped Poplar Wood
+ block.minecraft.white_wool_slab: White Wool Slab
+ block.minecraft.white_wool_stairs: White Wool Stairs
+ block.minecraft.yellow_poplar_leaves: Yellow Poplar Leaves
+ block.minecraft.yellow_wool_slab: Yellow Wool Slab
+ block.minecraft.yellow_wool_stairs: Yellow Wool Stairs
+ commands.item.block.modify.success: Modified %s slot(s) at %s, %s, %s
+ commands.item.block.replace.success: Replaced %s slot(s) at %s, %s, %s
+ commands.item.block.replace.success.known_item: Replaced %s slot(s) at %s, %s, %s with %s
+ commands.item.entity.modify.success.multiple: Modified slot(s) on %s entities
+ commands.item.entity.modify.success.single: Modified %s slot(s) on %s
+ commands.item.entity.replace.success.multiple: Replaced slot(s) on %s entities
+ commands.item.entity.replace.success.multiple.known_item: Replaced slot(s) on %s entities with %s
+ commands.item.entity.replace.success.single: Replaced %s slot(s) on %s
+ commands.item.entity.replace.success.single.known_item: Replaced %s slot(s) on %s with %s
+ commands.item.source.no_such_slot.unnamed: The source does not have specified slots
+ commands.item.target.failed: No targets accepted items into specified slots
+ commands.item.target.failed.known_item: No targets accepted item %s into specified slots
+ commands.item.target.no_such_slot.unnamed: The target does not have specified slots
+ entity.minecraft.poplar_boat: Poplar Boat
+ entity.minecraft.poplar_chest_boat: Poplar Boat with Chest
+ item.minecraft.poplar_boat: Poplar Boat
+ item.minecraft.poplar_chest_boat: Poplar Boat with Chest
+ subtitles.block.shelf_mushroom.bounce: Something bounces on a Shelf Mushroom
+ test.player.coordinates: Player coordinates: [%s, %s, %s] in %s
+ test.run.coordinates: Test coordinates: [%s, %s, %s] in %s
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
+ reports/minecraft/components/item/black_wool_slab.json
+ reports/minecraft/components/item/black_wool_stairs.json
+ reports/minecraft/components/item/blue_wool_slab.json
+ reports/minecraft/components/item/blue_wool_stairs.json
+ reports/minecraft/components/item/brown_wool_slab.json
+ reports/minecraft/components/item/brown_wool_stairs.json
+ reports/minecraft/components/item/cyan_wool_slab.json
+ reports/minecraft/components/item/cyan_wool_stairs.json
+ reports/minecraft/components/item/gray_wool_slab.json
+ reports/minecraft/components/item/gray_wool_stairs.json
+ reports/minecraft/components/item/green_wool_slab.json
+ reports/minecraft/components/item/green_wool_stairs.json
+ reports/minecraft/components/item/light_blue_wool_slab.json
+ reports/minecraft/components/item/light_blue_wool_stairs.json
+ reports/minecraft/components/item/light_gray_wool_slab.json
+ reports/minecraft/components/item/light_gray_wool_stairs.json
+ reports/minecraft/components/item/lime_wool_slab.json
+ reports/minecraft/components/item/lime_wool_stairs.json
+ reports/minecraft/components/item/magenta_wool_slab.json
+ reports/minecraft/components/item/magenta_wool_stairs.json
+ reports/minecraft/components/item/orange_poplar_leaves.json
+ reports/minecraft/components/item/orange_wool_slab.json
+ reports/minecraft/components/item/orange_wool_stairs.json
+ reports/minecraft/components/item/pink_wool_slab.json
+ reports/minecraft/components/item/pink_wool_stairs.json
+ reports/minecraft/components/item/poplar_boat.json
+ reports/minecraft/components/item/poplar_button.json
+ reports/minecraft/components/item/poplar_chest_boat.json
+ reports/minecraft/components/item/poplar_door.json
+ reports/minecraft/components/item/poplar_fence_gate.json
+ reports/minecraft/components/item/poplar_fence.json
+ reports/minecraft/components/item/poplar_hanging_sign.json
+ reports/minecraft/components/item/poplar_log.json
+ reports/minecraft/components/item/poplar_planks.json
+ reports/minecraft/components/item/poplar_pressure_plate.json
+ reports/minecraft/components/item/poplar_sapling.json
+ reports/minecraft/components/item/poplar_shelf.json
+ reports/minecraft/components/item/poplar_sign.json
+ reports/minecraft/components/item/poplar_slab.json
+ reports/minecraft/components/item/poplar_stairs.json
+ reports/minecraft/components/item/poplar_trapdoor.json
+ reports/minecraft/components/item/poplar_wood.json
+ reports/minecraft/components/item/purple_wool_slab.json
+ reports/minecraft/components/item/purple_wool_stairs.json
+ reports/minecraft/components/item/red_poplar_leaves.json
+ reports/minecraft/components/item/red_shrub.json
+ reports/minecraft/components/item/red_wool_slab.json
+ reports/minecraft/components/item/red_wool_stairs.json
+ reports/minecraft/components/item/shelf_mushroom.json
+ reports/minecraft/components/item/stripped_poplar_log.json
+ reports/minecraft/components/item/stripped_poplar_wood.json
+ reports/minecraft/components/item/white_wool_slab.json
+ reports/minecraft/components/item/white_wool_stairs.json
+ reports/minecraft/components/item/yellow_poplar_leaves.json
+ reports/minecraft/components/item/yellow_wool_slab.json
+ reports/minecraft/components/item/yellow_wool_stairs.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/building_blocks/black_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/black_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/blue_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/blue_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/brown_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/brown_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/cyan_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/cyan_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_black_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_black_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_blue_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_blue_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_brown_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_brown_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_cyan_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_cyan_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_gray_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_gray_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_green_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_green_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_light_blue_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_light_blue_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_light_gray_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_light_gray_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_lime_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_lime_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_magenta_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_magenta_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_orange_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_orange_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_pink_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_pink_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_purple_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_purple_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_red_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_red_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_white_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_white_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/dye_yellow_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/dye_yellow_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/gray_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/gray_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/green_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/green_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/light_blue_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/light_blue_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/light_gray_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/light_gray_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/lime_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/lime_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/magenta_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/magenta_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/orange_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/orange_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/pink_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/pink_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/poplar_planks.json
+ minecraft/advancement/recipes/building_blocks/poplar_slab.json
+ minecraft/advancement/recipes/building_blocks/poplar_stairs.json
+ minecraft/advancement/recipes/building_blocks/poplar_wood.json
+ minecraft/advancement/recipes/building_blocks/purple_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/purple_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/red_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/red_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/stripped_poplar_wood.json
+ minecraft/advancement/recipes/building_blocks/white_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/white_wool_stairs.json
+ minecraft/advancement/recipes/building_blocks/yellow_wool_slab.json
+ minecraft/advancement/recipes/building_blocks/yellow_wool_stairs.json
- minecraft/advancement/recipes/decorations/black_carpet.json
- minecraft/advancement/recipes/decorations/blue_carpet.json
- minecraft/advancement/recipes/decorations/brown_carpet.json
- minecraft/advancement/recipes/decorations/cyan_carpet.json
- minecraft/advancement/recipes/decorations/gray_carpet.json
- minecraft/advancement/recipes/decorations/green_carpet.json
- minecraft/advancement/recipes/decorations/light_blue_carpet.json
- minecraft/advancement/recipes/decorations/light_gray_carpet.json
- minecraft/advancement/recipes/decorations/lime_carpet.json
- minecraft/advancement/recipes/decorations/magenta_carpet.json
- minecraft/advancement/recipes/decorations/orange_carpet.json
- minecraft/advancement/recipes/decorations/pink_carpet.json
+ minecraft/advancement/recipes/decorations/poplar_fence.json
+ minecraft/advancement/recipes/decorations/poplar_hanging_sign.json
+ minecraft/advancement/recipes/decorations/poplar_shelf.json
+ minecraft/advancement/recipes/decorations/poplar_sign.json
- minecraft/advancement/recipes/decorations/purple_carpet.json
- minecraft/advancement/recipes/decorations/red_carpet.json
- minecraft/advancement/recipes/decorations/white_carpet.json
- minecraft/advancement/recipes/decorations/yellow_carpet.json
+ minecraft/advancement/recipes/food/rabbit_stew_from_shelf_mushroom.json
+ minecraft/advancement/recipes/redstone/poplar_button.json
+ minecraft/advancement/recipes/redstone/poplar_door.json
+ minecraft/advancement/recipes/redstone/poplar_fence_gate.json
+ minecraft/advancement/recipes/redstone/poplar_pressure_plate.json
+ minecraft/advancement/recipes/redstone/poplar_trapdoor.json
+ minecraft/advancement/recipes/transportation/poplar_boat.json
+ minecraft/advancement/recipes/transportation/poplar_chest_boat.json
+ minecraft/decorated_pot_pattern/angler.json
+ minecraft/decorated_pot_pattern/archer.json
+ minecraft/decorated_pot_pattern/arms_up.json
+ minecraft/decorated_pot_pattern/blade.json
+ minecraft/decorated_pot_pattern/brewer.json
+ minecraft/decorated_pot_pattern/burn.json
+ minecraft/decorated_pot_pattern/danger.json
+ minecraft/decorated_pot_pattern/explorer.json
+ minecraft/decorated_pot_pattern/flow.json
+ minecraft/decorated_pot_pattern/friend.json
+ minecraft/decorated_pot_pattern/guster.json
+ minecraft/decorated_pot_pattern/heart.json
+ minecraft/decorated_pot_pattern/heartbreak.json
+ minecraft/decorated_pot_pattern/howl.json
+ minecraft/decorated_pot_pattern/miner.json
+ minecraft/decorated_pot_pattern/mourner.json
+ minecraft/decorated_pot_pattern/plenty.json
+ minecraft/decorated_pot_pattern/prize.json
+ minecraft/decorated_pot_pattern/scrape.json
+ minecraft/decorated_pot_pattern/sheaf.json
+ minecraft/decorated_pot_pattern/shelter.json
+ minecraft/decorated_pot_pattern/skull.json
+ minecraft/decorated_pot_pattern/snort.json
+ minecraft/loot_table/barrels/abandoned_camp_barrel.json
+ minecraft/loot_table/blocks/black_wool_slab.json
+ minecraft/loot_table/blocks/black_wool_stairs.json
+ minecraft/loot_table/blocks/blue_wool_slab.json
+ minecraft/loot_table/blocks/blue_wool_stairs.json
+ minecraft/loot_table/blocks/brown_wool_slab.json
+ minecraft/loot_table/blocks/brown_wool_stairs.json
+ minecraft/loot_table/blocks/cyan_wool_slab.json
+ minecraft/loot_table/blocks/cyan_wool_stairs.json
+ minecraft/loot_table/blocks/gray_wool_slab.json
+ minecraft/loot_table/blocks/gray_wool_stairs.json
+ minecraft/loot_table/blocks/green_wool_slab.json
+ minecraft/loot_table/blocks/green_wool_stairs.json
+ minecraft/loot_table/blocks/light_blue_wool_slab.json
+ minecraft/loot_table/blocks/light_blue_wool_stairs.json
+ minecraft/loot_table/blocks/light_gray_wool_slab.json
+ minecraft/loot_table/blocks/light_gray_wool_stairs.json
+ minecraft/loot_table/blocks/lime_wool_slab.json
+ minecraft/loot_table/blocks/lime_wool_stairs.json
+ minecraft/loot_table/blocks/magenta_wool_slab.json
+ minecraft/loot_table/blocks/magenta_wool_stairs.json
+ minecraft/loot_table/blocks/orange_poplar_leaves.json
+ minecraft/loot_table/blocks/orange_wool_slab.json
+ minecraft/loot_table/blocks/orange_wool_stairs.json
+ minecraft/loot_table/blocks/pink_wool_slab.json
+ minecraft/loot_table/blocks/pink_wool_stairs.json
+ minecraft/loot_table/blocks/poplar_button.json
+ minecraft/loot_table/blocks/poplar_door.json
+ minecraft/loot_table/blocks/poplar_fence_gate.json
+ minecraft/loot_table/blocks/poplar_fence.json
+ minecraft/loot_table/blocks/poplar_hanging_sign.json
+ minecraft/loot_table/blocks/poplar_log.json
+ minecraft/loot_table/blocks/poplar_planks.json
+ minecraft/loot_table/blocks/poplar_pressure_plate.json
+ minecraft/loot_table/blocks/poplar_sapling.json
+ minecraft/loot_table/blocks/poplar_shelf.json
+ minecraft/loot_table/blocks/poplar_sign.json
+ minecraft/loot_table/blocks/poplar_slab.json
+ minecraft/loot_table/blocks/poplar_stairs.json
+ minecraft/loot_table/blocks/poplar_trapdoor.json
+ minecraft/loot_table/blocks/poplar_wood.json
+ minecraft/loot_table/blocks/potted_poplar_sapling.json
+ minecraft/loot_table/blocks/purple_wool_slab.json
+ minecraft/loot_table/blocks/purple_wool_stairs.json
+ minecraft/loot_table/blocks/red_poplar_leaves.json
+ minecraft/loot_table/blocks/red_shrub.json
+ minecraft/loot_table/blocks/red_wool_slab.json
+ minecraft/loot_table/blocks/red_wool_stairs.json
+ minecraft/loot_table/blocks/shelf_mushroom.json
+ minecraft/loot_table/blocks/stripped_poplar_log.json
+ minecraft/loot_table/blocks/stripped_poplar_wood.json
+ minecraft/loot_table/blocks/white_wool_slab.json
+ minecraft/loot_table/blocks/white_wool_stairs.json
+ minecraft/loot_table/blocks/yellow_poplar_leaves.json
+ minecraft/loot_table/blocks/yellow_wool_slab.json
+ minecraft/loot_table/blocks/yellow_wool_stairs.json
+ minecraft/loot_table/chests/abandoned_camp_common_chest.json
+ minecraft/loot_table/chests/abandoned_camp_secret_chest.json
- minecraft/recipe/black_carpet.json
+ minecraft/recipe/black_wool_slab.json
+ minecraft/recipe/black_wool_stairs.json
- minecraft/recipe/blue_carpet.json
+ minecraft/recipe/blue_wool_slab.json
+ minecraft/recipe/blue_wool_stairs.json
- minecraft/recipe/brown_carpet.json
+ minecraft/recipe/brown_wool_slab.json
+ minecraft/recipe/brown_wool_stairs.json
- minecraft/recipe/cyan_carpet.json
+ minecraft/recipe/cyan_wool_slab.json
+ minecraft/recipe/cyan_wool_stairs.json
+ minecraft/recipe/dye_black_wool_slab.json
+ minecraft/recipe/dye_black_wool_stairs.json
+ minecraft/recipe/dye_blue_wool_slab.json
+ minecraft/recipe/dye_blue_wool_stairs.json
+ minecraft/recipe/dye_brown_wool_slab.json
+ minecraft/recipe/dye_brown_wool_stairs.json
+ minecraft/recipe/dye_cyan_wool_slab.json
+ minecraft/recipe/dye_cyan_wool_stairs.json
+ minecraft/recipe/dye_gray_wool_slab.json
+ minecraft/recipe/dye_gray_wool_stairs.json
+ minecraft/recipe/dye_green_wool_slab.json
+ minecraft/recipe/dye_green_wool_stairs.json
+ minecraft/recipe/dye_light_blue_wool_slab.json
+ minecraft/recipe/dye_light_blue_wool_stairs.json
+ minecraft/recipe/dye_light_gray_wool_slab.json
+ minecraft/recipe/dye_light_gray_wool_stairs.json
+ minecraft/recipe/dye_lime_wool_slab.json
+ minecraft/recipe/dye_lime_wool_stairs.json
+ minecraft/recipe/dye_magenta_wool_slab.json
+ minecraft/recipe/dye_magenta_wool_stairs.json
+ minecraft/recipe/dye_orange_wool_slab.json
+ minecraft/recipe/dye_orange_wool_stairs.json
+ minecraft/recipe/dye_pink_wool_slab.json
+ minecraft/recipe/dye_pink_wool_stairs.json
+ minecraft/recipe/dye_purple_wool_slab.json
+ minecraft/recipe/dye_purple_wool_stairs.json
+ minecraft/recipe/dye_red_wool_slab.json
+ minecraft/recipe/dye_red_wool_stairs.json
+ minecraft/recipe/dye_white_wool_slab.json
+ minecraft/recipe/dye_white_wool_stairs.json
+ minecraft/recipe/dye_yellow_wool_slab.json
+ minecraft/recipe/dye_yellow_wool_stairs.json
- minecraft/recipe/gray_carpet.json
+ minecraft/recipe/gray_wool_slab.json
+ minecraft/recipe/gray_wool_stairs.json
- minecraft/recipe/green_carpet.json
+ minecraft/recipe/green_wool_slab.json
+ minecraft/recipe/green_wool_stairs.json
- minecraft/recipe/light_blue_carpet.json
+ minecraft/recipe/light_blue_wool_slab.json
+ minecraft/recipe/light_blue_wool_stairs.json
- minecraft/recipe/light_gray_carpet.json
+ minecraft/recipe/light_gray_wool_slab.json
+ minecraft/recipe/light_gray_wool_stairs.json
- minecraft/recipe/lime_carpet.json
+ minecraft/recipe/lime_wool_slab.json
+ minecraft/recipe/lime_wool_stairs.json
- minecraft/recipe/magenta_carpet.json
+ minecraft/recipe/magenta_wool_slab.json
+ minecraft/recipe/magenta_wool_stairs.json
- minecraft/recipe/orange_carpet.json
+ minecraft/recipe/orange_wool_slab.json
+ minecraft/recipe/orange_wool_stairs.json
- minecraft/recipe/pink_carpet.json
+ minecraft/recipe/pink_wool_slab.json
+ minecraft/recipe/pink_wool_stairs.json
+ minecraft/recipe/poplar_boat.json
+ minecraft/recipe/poplar_button.json
+ minecraft/recipe/poplar_chest_boat.json
+ minecraft/recipe/poplar_door.json
+ minecraft/recipe/poplar_fence_gate.json
+ minecraft/recipe/poplar_fence.json
+ minecraft/recipe/poplar_hanging_sign.json
+ minecraft/recipe/poplar_planks.json
+ minecraft/recipe/poplar_pressure_plate.json
+ minecraft/recipe/poplar_shelf.json
+ minecraft/recipe/poplar_sign.json
+ minecraft/recipe/poplar_slab.json
+ minecraft/recipe/poplar_stairs.json
+ minecraft/recipe/poplar_trapdoor.json
+ minecraft/recipe/poplar_wood.json
- minecraft/recipe/purple_carpet.json
+ minecraft/recipe/purple_wool_slab.json
+ minecraft/recipe/purple_wool_stairs.json
+ minecraft/recipe/rabbit_stew_from_shelf_mushroom.json
- minecraft/recipe/red_carpet.json
+ minecraft/recipe/red_wool_slab.json
+ minecraft/recipe/red_wool_stairs.json
+ minecraft/recipe/stripped_poplar_wood.json
- minecraft/recipe/white_carpet.json
+ minecraft/recipe/white_wool_slab.json
+ minecraft/recipe/white_wool_stairs.json
- minecraft/recipe/yellow_carpet.json
+ minecraft/recipe/yellow_wool_slab.json
+ minecraft/recipe/yellow_wool_stairs.json
+ minecraft/structure/abandoned_camp/camp/bamboo_jungle/campsite_bamboo_jungle_1.nbt
+ minecraft/structure/abandoned_camp/camp/bamboo_jungle/campsite_bamboo_jungle_2.nbt
+ minecraft/structure/abandoned_camp/camp/bamboo_jungle/campsite_bamboo_jungle_3.nbt
+ minecraft/structure/abandoned_camp/camp/birch_forest/campsite_birch_forest_1.nbt
+ minecraft/structure/abandoned_camp/camp/birch_forest/campsite_birch_forest_2.nbt
+ minecraft/structure/abandoned_camp/camp/birch_forest/campsite_birch_forest_3.nbt
+ minecraft/structure/abandoned_camp/camp/cherry_grove/campsite_cherry_grove_1.nbt
+ minecraft/structure/abandoned_camp/camp/cherry_grove/campsite_cherry_grove_2.nbt
+ minecraft/structure/abandoned_camp/camp/cherry_grove/campsite_cherry_grove_3.nbt
+ minecraft/structure/abandoned_camp/camp/dappled_forest/campsite_dappled_forest_1.nbt
+ minecraft/structure/abandoned_camp/camp/dappled_forest/campsite_dappled_forest_2.nbt
+ minecraft/structure/abandoned_camp/camp/dappled_forest/campsite_dappled_forest_3.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_1.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_10.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_11.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_12.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_13.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_14.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_15.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_2.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_3.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_4.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_5.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_6.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_7.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_8.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_barrel_9.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_1.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_10.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_11.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_12.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_13.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_14.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_15.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_2.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_3.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_4.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_5.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_6.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_7.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_8.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_chest_9.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_1.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_10.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_11.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_12.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_13.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_14.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_15.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_2.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_3.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_4.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_5.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_6.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_7.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_8.nbt
+ minecraft/structure/abandoned_camp/camp/default/campsite_default_special_9.nbt
+ minecraft/structure/abandoned_camp/camp/flower_forest/campsite_flower_forest_1.nbt
+ minecraft/structure/abandoned_camp/camp/flower_forest/campsite_flower_forest_2.nbt
+ minecraft/structure/abandoned_camp/camp/flower_forest/campsite_flower_forest_3.nbt
+ minecraft/structure/abandoned_camp/camp/forest/campsite_forest_1.nbt
+ minecraft/structure/abandoned_camp/camp/forest/campsite_forest_2.nbt
+ minecraft/structure/abandoned_camp/camp/forest/campsite_forest_3.nbt
+ minecraft/structure/abandoned_camp/camp/meadow/campsite_meadow_1.nbt
+ minecraft/structure/abandoned_camp/camp/meadow/campsite_meadow_2.nbt
+ minecraft/structure/abandoned_camp/camp/meadow/campsite_meadow_3.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_birch_forest/campsite_old_growth_birch_forest_1.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_birch_forest/campsite_old_growth_birch_forest_2.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_birch_forest/campsite_old_growth_birch_forest_3.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_pine_taiga/campsite_old_growth_pine_taiga_1.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_pine_taiga/campsite_old_growth_pine_taiga_2.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_pine_taiga/campsite_old_growth_pine_taiga_3.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_spruce_taiga/campsite_old_growth_spruce_taiga_1.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_spruce_taiga/campsite_old_growth_spruce_taiga_2.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_spruce_taiga/campsite_old_growth_spruce_taiga_3.nbt
+ minecraft/structure/abandoned_camp/camp/pale_garden/campsite_pale_garden_1.nbt
+ minecraft/structure/abandoned_camp/camp/pale_garden/campsite_pale_garden_2.nbt
+ minecraft/structure/abandoned_camp/camp/pale_garden/campsite_pale_garden_3.nbt
+ minecraft/structure/abandoned_camp/camp/savanna/campsite_savanna_1.nbt
+ minecraft/structure/abandoned_camp/camp/savanna/campsite_savanna_2.nbt
+ minecraft/structure/abandoned_camp/camp/savanna/campsite_savanna_3.nbt
+ minecraft/structure/abandoned_camp/camp/snowy_taiga/campsite_snowy_taiga_1.nbt
+ minecraft/structure/abandoned_camp/camp/snowy_taiga/campsite_snowy_taiga_2.nbt
+ minecraft/structure/abandoned_camp/camp/snowy_taiga/campsite_snowy_taiga_3.nbt
+ minecraft/structure/abandoned_camp/camp/sparse_jungle/campsite_sparse_jungle_1.nbt
+ minecraft/structure/abandoned_camp/camp/sparse_jungle/campsite_sparse_jungle_2.nbt
+ minecraft/structure/abandoned_camp/camp/sparse_jungle/campsite_sparse_jungle_3.nbt
+ minecraft/structure/abandoned_camp/camp/swamp/campsite_swamp_1.nbt
+ minecraft/structure/abandoned_camp/camp/swamp/campsite_swamp_2.nbt
+ minecraft/structure/abandoned_camp/camp/swamp/campsite_swamp_3.nbt
+ minecraft/structure/abandoned_camp/camp/taiga/campsite_taiga_1.nbt
+ minecraft/structure/abandoned_camp/camp/taiga/campsite_taiga_2.nbt
+ minecraft/structure/abandoned_camp/camp/taiga/campsite_taiga_3.nbt
+ minecraft/structure/abandoned_camp/camp/windswept_forest/campsite_windswept_forest_1.nbt
+ minecraft/structure/abandoned_camp/camp/windswept_forest/campsite_windswept_forest_2.nbt
+ minecraft/structure/abandoned_camp/camp/windswept_forest/campsite_windswept_forest_3.nbt
+ minecraft/structure/abandoned_camp/camp/wooded_badlands/campsite_wooded_badlands_1.nbt
+ minecraft/structure/abandoned_camp/camp/wooded_badlands/campsite_wooded_badlands_2.nbt
+ minecraft/structure/abandoned_camp/camp/wooded_badlands/campsite_wooded_badlands_3.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_1.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_10.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_2.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_3.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_4.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_5.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_6.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_7.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_8.nbt
+ minecraft/structure/abandoned_camp/tent/bamboo_jungle/tent_bamboo_jungle_9.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_1.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_10.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_2.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_3.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_4.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_5.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_6.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_7.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_8.nbt
+ minecraft/structure/abandoned_camp/tent/birch_forest/tent_birch_forest_9.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_1.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_10.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_2.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_3.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_4.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_5.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_6.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_7.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_8.nbt
+ minecraft/structure/abandoned_camp/tent/cherry_grove/tent_cherry_grove_9.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_1.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_10.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_2.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_3.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_4.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_5.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_6.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_7.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_8.nbt
+ minecraft/structure/abandoned_camp/tent/dappled_forest/tent_dappled_forest_9.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_1.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_10.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_2.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_3.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_4.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_5.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_6.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_7.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_8.nbt
+ minecraft/structure/abandoned_camp/tent/flower_forest/tent_flower_forest_9.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_1.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_10.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_2.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_3.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_4.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_5.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_6.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_7.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_8.nbt
+ minecraft/structure/abandoned_camp/tent/forest/tent_forest_9.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_1.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_10.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_2.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_3.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_4.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_5.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_6.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_7.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_8.nbt
+ minecraft/structure/abandoned_camp/tent/meadow/tent_meadow_9.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_1.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_10.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_2.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_3.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_4.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_5.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_6.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_7.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_8.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_birch_forest/tent_old_growth_birch_forest_9.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_1.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_10.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_2.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_3.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_4.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_5.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_6.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_7.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_8.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_pine_taiga/tent_old_growth_pine_taiga_9.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_1.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_10.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_2.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_3.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_4.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_5.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_6.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_7.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_8.nbt
+ minecraft/structure/abandoned_camp/tent/old_growth_spruce_taiga/tent_old_growth_spruce_taiga_9.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_1.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_10.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_2.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_3.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_4.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_5.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_6.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_7.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_8.nbt
+ minecraft/structure/abandoned_camp/tent/pale_garden/tent_pale_garden_9.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_1.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_10.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_2.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_3.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_4.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_5.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_6.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_7.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_8.nbt
+ minecraft/structure/abandoned_camp/tent/savanna/tent_savanna_9.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_1.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_10.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_2.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_3.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_4.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_5.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_6.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_7.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_8.nbt
+ minecraft/structure/abandoned_camp/tent/snowy_taiga/tent_snowy_taiga_9.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_1.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_10.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_2.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_3.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_4.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_5.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_6.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_7.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_8.nbt
+ minecraft/structure/abandoned_camp/tent/sparse_jungle/tent_sparse_jungle_9.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_1.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_10.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_2.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_3.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_4.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_5.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_6.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_7.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_8.nbt
+ minecraft/structure/abandoned_camp/tent/swamp/tent_swamp_9.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_1.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_10.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_2.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_3.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_4.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_5.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_6.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_7.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_8.nbt
+ minecraft/structure/abandoned_camp/tent/taiga/tent_taiga_9.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_1.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_10.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_2.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_3.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_4.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_5.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_6.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_7.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_8.nbt
+ minecraft/structure/abandoned_camp/tent/windswept_forest/tent_windswept_forest_9.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_1.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_10.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_2.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_3.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_4.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_5.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_6.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_7.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_8.nbt
+ minecraft/structure/abandoned_camp/tent/wooded_badlands/tent_wooded_badlands_9.nbt
+ minecraft/tags/block/blocks_dolphin_jump.json
+ minecraft/tags/block/blocks_fluid_flow.json
+ minecraft/tags/block/blocks_lava_fire_spread.json
+ minecraft/tags/block/blocks_motion_in_heightmap_no_leaves.json
+ minecraft/tags/block/blocks_motion_in_heightmap.json
+ minecraft/tags/block/blocks_motion_no_leaves.json
+ minecraft/tags/block/blocks_motion.json
+ minecraft/tags/block/causes_suffocation.json
+ minecraft/tags/block/entities_can_teleport_to.json
+ minecraft/tags/block/ice_melts_when_destroyed_above.json
+ minecraft/tags/block/ores.json
+ minecraft/tags/block/poplar_logs.json
+ minecraft/tags/block/required_for_poplar_leaf_ambience.json
+ minecraft/tags/block/skulls.json
+ minecraft/tags/block/washed_away_by_fluids.json
+ minecraft/tags/block/wool_slabs.json
+ minecraft/tags/block/wool_stairs.json
+ minecraft/tags/damage_type/no_wolf_retaliation.json
+ minecraft/tags/entity_type/cannot_be_dismounted_by_item_usage.json
+ minecraft/tags/item/mushrooms.json
+ minecraft/tags/item/ores.json
+ minecraft/tags/item/poplar_logs.json
+ minecraft/tags/item/wool_slabs.json
+ minecraft/tags/item/wool_stairs.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_bamboo_jungle.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_birch_forest.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_cherry_grove.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_dappled_forest.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_flower_forest.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_forest.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_meadow.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_old_growth_birch_forest.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_old_growth_pine_taiga.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_old_growth_spruce_taiga.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_pale_garden.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_savanna.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_snowy_taiga.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_sparse_jungle.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_swamp.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_taiga.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_windswept_forest.json
+ minecraft/tags/worldgen/biome/has_structure/abandoned_camp_wooded_badlands.json
- minecraft/tags/worldgen/configured_feature/can_spawn_from_bone_meal.json
+ minecraft/tags/worldgen/feature/can_spawn_from_bone_meal.json
+ minecraft/villager_trade/wandering_trader/emerald_poplar_sapling.json
+ minecraft/villager_trade/wandering_trader/emerald_shelf_mushroom.json
+ minecraft/worldgen/biome/dappled_forest.json
- minecraft/worldgen/configured_feature/acacia.json
- minecraft/worldgen/configured_feature/amethyst_geode.json
- minecraft/worldgen/configured_feature/azalea_tree.json
- minecraft/worldgen/configured_feature/bamboo_no_podzol.json
- minecraft/worldgen/configured_feature/bamboo_some_podzol.json
- minecraft/worldgen/configured_feature/bamboo_vegetation.json
- minecraft/worldgen/configured_feature/basalt_blobs.json
- minecraft/worldgen/configured_feature/basalt_pillar.json
- minecraft/worldgen/configured_feature/berry_bush.json
- minecraft/worldgen/configured_feature/birch_bees_0002_leaf_litter.json
- minecraft/worldgen/configured_feature/birch_bees_0002.json
- minecraft/worldgen/configured_feature/birch_bees_002.json
- minecraft/worldgen/configured_feature/birch_bees_005.json
- minecraft/worldgen/configured_feature/birch_leaf_litter.json
- minecraft/worldgen/configured_feature/birch_tall.json
- minecraft/worldgen/configured_feature/birch.json
- minecraft/worldgen/configured_feature/blackstone_blobs.json
- minecraft/worldgen/configured_feature/blue_ice.json
- minecraft/worldgen/configured_feature/bonus_chest.json
- minecraft/worldgen/configured_feature/brown_mushroom.json
- minecraft/worldgen/configured_feature/bush.json
- minecraft/worldgen/configured_feature/cactus.json
- minecraft/worldgen/configured_feature/cave_vine_in_moss.json
- minecraft/worldgen/configured_feature/cave_vine.json
- minecraft/worldgen/configured_feature/cherry_bees_005.json
- minecraft/worldgen/configured_feature/cherry.json
- minecraft/worldgen/configured_feature/chorus_plant.json
- minecraft/worldgen/configured_feature/clay_pool_with_dripleaves.json
- minecraft/worldgen/configured_feature/clay_with_dripleaves.json
- minecraft/worldgen/configured_feature/crimson_forest_vegetation_bonemeal.json
- minecraft/worldgen/configured_feature/crimson_forest_vegetation.json
- minecraft/worldgen/configured_feature/crimson_fungus_planted.json
- minecraft/worldgen/configured_feature/crimson_fungus.json
- minecraft/worldgen/configured_feature/crimson_roots.json
- minecraft/worldgen/configured_feature/dark_forest_vegetation.json
- minecraft/worldgen/configured_feature/dark_oak_leaf_litter.json
- minecraft/worldgen/configured_feature/dark_oak.json
- minecraft/worldgen/configured_feature/dead_bush.json
- minecraft/worldgen/configured_feature/delta.json
- minecraft/worldgen/configured_feature/desert_well.json
- minecraft/worldgen/configured_feature/disk_clay.json
- minecraft/worldgen/configured_feature/disk_grass.json
- minecraft/worldgen/configured_feature/disk_gravel.json
- minecraft/worldgen/configured_feature/disk_sand.json
- minecraft/worldgen/configured_feature/dripleaf.json
- minecraft/worldgen/configured_feature/dripstone_cluster.json
- minecraft/worldgen/configured_feature/dry_grass.json
- minecraft/worldgen/configured_feature/end_gateway_delayed.json
- minecraft/worldgen/configured_feature/end_gateway_return.json
- minecraft/worldgen/configured_feature/end_island.json
- minecraft/worldgen/configured_feature/end_platform.json
- minecraft/worldgen/configured_feature/end_spike.json
- minecraft/worldgen/configured_feature/fallen_birch_tree.json
- minecraft/worldgen/configured_feature/fallen_jungle_tree.json
- minecraft/worldgen/configured_feature/fallen_oak_tree.json
- minecraft/worldgen/configured_feature/fallen_spruce_tree.json
- minecraft/worldgen/configured_feature/fallen_super_birch_tree.json
- minecraft/worldgen/configured_feature/fancy_oak_bees_0002_leaf_litter.json
- minecraft/worldgen/configured_feature/fancy_oak_bees_002.json
- minecraft/worldgen/configured_feature/fancy_oak_bees_005.json
- minecraft/worldgen/configured_feature/fancy_oak_bees.json
- minecraft/worldgen/configured_feature/fancy_oak_leaf_litter.json
- minecraft/worldgen/configured_feature/fancy_oak.json
- minecraft/worldgen/configured_feature/firefly_bush.json
- minecraft/worldgen/configured_feature/flower_cherry.json
- minecraft/worldgen/configured_feature/flower_default.json
- minecraft/worldgen/configured_feature/flower_flower_forest.json
- minecraft/worldgen/configured_feature/flower_meadow.json
- minecraft/worldgen/configured_feature/flower_pale_garden.json
- minecraft/worldgen/configured_feature/flower_plain.json
- minecraft/worldgen/configured_feature/flower_swamp.json
- minecraft/worldgen/configured_feature/forest_flowers.json
- minecraft/worldgen/configured_feature/forest_rock.json
- minecraft/worldgen/configured_feature/fossil_coal.json
- minecraft/worldgen/configured_feature/fossil_diamonds.json
- minecraft/worldgen/configured_feature/freeze_top_layer.json
- minecraft/worldgen/configured_feature/glow_lichen.json
- minecraft/worldgen/configured_feature/glowstone_extra.json
- minecraft/worldgen/configured_feature/grass_jungle.json
- minecraft/worldgen/configured_feature/grass.json
- minecraft/worldgen/configured_feature/huge_brown_mushroom.json
- minecraft/worldgen/configured_feature/huge_red_mushroom.json
- minecraft/worldgen/configured_feature/ice_patch.json
- minecraft/worldgen/configured_feature/ice_spike.json
- minecraft/worldgen/configured_feature/iceberg_blue.json
- minecraft/worldgen/configured_feature/iceberg_packed.json
- minecraft/worldgen/configured_feature/jungle_bush.json
- minecraft/worldgen/configured_feature/jungle_tree_no_vine.json
- minecraft/worldgen/configured_feature/jungle_tree.json
- minecraft/worldgen/configured_feature/kelp.json
- minecraft/worldgen/configured_feature/lake_lava.json
- minecraft/worldgen/configured_feature/large_basalt_columns.json
- minecraft/worldgen/configured_feature/large_dripstone.json
- minecraft/worldgen/configured_feature/large_fern.json
- minecraft/worldgen/configured_feature/leaf_litter.json
- minecraft/worldgen/configured_feature/lush_caves_clay.json
- minecraft/worldgen/configured_feature/mangrove_vegetation.json
- minecraft/worldgen/configured_feature/mangrove.json
- minecraft/worldgen/configured_feature/meadow_trees.json
- minecraft/worldgen/configured_feature/mega_jungle_tree.json
- minecraft/worldgen/configured_feature/mega_pine.json
- minecraft/worldgen/configured_feature/mega_spruce.json
- minecraft/worldgen/configured_feature/melon.json
- minecraft/worldgen/configured_feature/monster_room.json
- minecraft/worldgen/configured_feature/moss_patch_bonemeal.json
- minecraft/worldgen/configured_feature/moss_patch_ceiling.json
- minecraft/worldgen/configured_feature/moss_patch.json
- minecraft/worldgen/configured_feature/moss_vegetation.json
- minecraft/worldgen/configured_feature/mushroom_island_vegetation.json
- minecraft/worldgen/configured_feature/nether_sprouts_bonemeal.json
- minecraft/worldgen/configured_feature/nether_sprouts.json
- minecraft/worldgen/configured_feature/oak_bees_0002_leaf_litter.json
- minecraft/worldgen/configured_feature/oak_bees_002.json
- minecraft/worldgen/configured_feature/oak_bees_005.json
- minecraft/worldgen/configured_feature/oak_leaf_litter.json
- minecraft/worldgen/configured_feature/oak.json
- minecraft/worldgen/configured_feature/ore_ancient_debris_large.json
- minecraft/worldgen/configured_feature/ore_ancient_debris_small.json
- minecraft/worldgen/configured_feature/ore_andesite.json
- minecraft/worldgen/configured_feature/ore_blackstone.json
- minecraft/worldgen/configured_feature/ore_clay.json
- minecraft/worldgen/configured_feature/ore_coal_buried.json
- minecraft/worldgen/configured_feature/ore_coal.json
- minecraft/worldgen/configured_feature/ore_copper_large.json
- minecraft/worldgen/configured_feature/ore_copper_small.json
- minecraft/worldgen/configured_feature/ore_diamond_buried.json
- minecraft/worldgen/configured_feature/ore_diamond_large.json
- minecraft/worldgen/configured_feature/ore_diamond_medium.json
- minecraft/worldgen/configured_feature/ore_diamond_small.json
- minecraft/worldgen/configured_feature/ore_diorite.json
- minecraft/worldgen/configured_feature/ore_dirt.json
- minecraft/worldgen/configured_feature/ore_emerald.json
- minecraft/worldgen/configured_feature/ore_gold_buried.json
- minecraft/worldgen/configured_feature/ore_gold.json
- minecraft/worldgen/configured_feature/ore_granite.json
- minecraft/worldgen/configured_feature/ore_gravel_nether.json
- minecraft/worldgen/configured_feature/ore_gravel.json
- minecraft/worldgen/configured_feature/ore_infested.json
- minecraft/worldgen/configured_feature/ore_iron_small.json
- minecraft/worldgen/configured_feature/ore_iron.json
- minecraft/worldgen/configured_feature/ore_lapis_buried.json
- minecraft/worldgen/configured_feature/ore_lapis.json
- minecraft/worldgen/configured_feature/ore_magma.json
- minecraft/worldgen/configured_feature/ore_nether_gold.json
- minecraft/worldgen/configured_feature/ore_quartz.json
- minecraft/worldgen/configured_feature/ore_redstone.json
- minecraft/worldgen/configured_feature/ore_soul_sand.json
- minecraft/worldgen/configured_feature/ore_tuff.json
- minecraft/worldgen/configured_feature/pale_forest_flower.json
- minecraft/worldgen/configured_feature/pale_garden_vegetation.json
- minecraft/worldgen/configured_feature/pale_moss_patch_bonemeal.json
- minecraft/worldgen/configured_feature/pale_moss_patch.json
- minecraft/worldgen/configured_feature/pale_moss_vegetation.json
- minecraft/worldgen/configured_feature/pale_oak_bonemeal.json
- minecraft/worldgen/configured_feature/pale_oak_creaking.json
- minecraft/worldgen/configured_feature/pale_oak.json
- minecraft/worldgen/configured_feature/patch_fire.json
- minecraft/worldgen/configured_feature/patch_soul_fire.json
- minecraft/worldgen/configured_feature/pile_hay.json
- minecraft/worldgen/configured_feature/pile_ice.json
- minecraft/worldgen/configured_feature/pile_melon.json
- minecraft/worldgen/configured_feature/pile_pumpkin.json
- minecraft/worldgen/configured_feature/pile_snow.json
- minecraft/worldgen/configured_feature/pine.json
- minecraft/worldgen/configured_feature/pointed_dripstone.json
- minecraft/worldgen/configured_feature/pumpkin.json
- minecraft/worldgen/configured_feature/red_mushroom.json
- minecraft/worldgen/configured_feature/rooted_azalea_tree.json
- minecraft/worldgen/configured_feature/rooted_sulfur_spring.json
- minecraft/worldgen/configured_feature/sculk_patch_ancient_city.json
- minecraft/worldgen/configured_feature/sculk_patch_deep_dark.json
- minecraft/worldgen/configured_feature/sculk_vein.json
- minecraft/worldgen/configured_feature/sea_pickle.json
- minecraft/worldgen/configured_feature/seagrass_mid.json
- minecraft/worldgen/configured_feature/seagrass_short.json
- minecraft/worldgen/configured_feature/seagrass_slightly_less_short.json
- minecraft/worldgen/configured_feature/seagrass_tall.json
- minecraft/worldgen/configured_feature/small_basalt_columns.json
- minecraft/worldgen/configured_feature/spore_blossom.json
- minecraft/worldgen/configured_feature/spring_lava_frozen.json
- minecraft/worldgen/configured_feature/spring_lava_nether.json
- minecraft/worldgen/configured_feature/spring_lava_overworld.json
- minecraft/worldgen/configured_feature/spring_nether_closed.json
- minecraft/worldgen/configured_feature/spring_nether_open.json
- minecraft/worldgen/configured_feature/spring_water.json
- minecraft/worldgen/configured_feature/spruce.json
- minecraft/worldgen/configured_feature/sugar_cane.json
- minecraft/worldgen/configured_feature/sulfur_pool.json
- minecraft/worldgen/configured_feature/sulfur_spike_cluster.json
- minecraft/worldgen/configured_feature/sulfur_spike.json
- minecraft/worldgen/configured_feature/sulfur_spring.json
- minecraft/worldgen/configured_feature/sunflower.json
- minecraft/worldgen/configured_feature/super_birch_bees_0002.json
- minecraft/worldgen/configured_feature/super_birch_bees.json
- minecraft/worldgen/configured_feature/swamp_oak.json
- minecraft/worldgen/configured_feature/taiga_grass.json
- minecraft/worldgen/configured_feature/tall_grass.json
- minecraft/worldgen/configured_feature/tall_mangrove.json
- minecraft/worldgen/configured_feature/trees_badlands.json
- minecraft/worldgen/configured_feature/trees_birch_and_oak_leaf_litter.json
- minecraft/worldgen/configured_feature/trees_birch.json
- minecraft/worldgen/configured_feature/trees_flower_forest.json
- minecraft/worldgen/configured_feature/trees_grove.json
- minecraft/worldgen/configured_feature/trees_jungle.json
- minecraft/worldgen/configured_feature/trees_old_growth_pine_taiga.json
- minecraft/worldgen/configured_feature/trees_old_growth_spruce_taiga.json
- minecraft/worldgen/configured_feature/trees_plains.json
- minecraft/worldgen/configured_feature/trees_savanna.json
- minecraft/worldgen/configured_feature/trees_snowy.json
- minecraft/worldgen/configured_feature/trees_sparse_jungle.json
- minecraft/worldgen/configured_feature/trees_taiga.json
- minecraft/worldgen/configured_feature/trees_water.json
- minecraft/worldgen/configured_feature/trees_windswept_hills.json
- minecraft/worldgen/configured_feature/twisting_vines_bonemeal.json
- minecraft/worldgen/configured_feature/twisting_vines.json
- minecraft/worldgen/configured_feature/underwater_magma.json
- minecraft/worldgen/configured_feature/vines.json
- minecraft/worldgen/configured_feature/void_start_platform.json
- minecraft/worldgen/configured_feature/warm_ocean_vegetation.json
- minecraft/worldgen/configured_feature/warped_forest_vegetation_bonemeal.json
- minecraft/worldgen/configured_feature/warped_forest_vegetation.json
- minecraft/worldgen/configured_feature/warped_fungus_planted.json
- minecraft/worldgen/configured_feature/warped_fungus.json
- minecraft/worldgen/configured_feature/waterlily.json
- minecraft/worldgen/configured_feature/weeping_vines.json
- minecraft/worldgen/configured_feature/wildflower.json
+ minecraft/worldgen/feature/acacia.json
+ minecraft/worldgen/feature/amethyst_geode.json
+ minecraft/worldgen/feature/azalea_tree.json
+ minecraft/worldgen/feature/bamboo_no_podzol.json
+ minecraft/worldgen/feature/bamboo_some_podzol.json
+ minecraft/worldgen/feature/bamboo_vegetation.json
+ minecraft/worldgen/feature/basalt_blobs.json
+ minecraft/worldgen/feature/basalt_pillar.json
+ minecraft/worldgen/feature/berry_bush.json
+ minecraft/worldgen/feature/birch_bees_0002_leaf_litter.json
+ minecraft/worldgen/feature/birch_bees_0002.json
+ minecraft/worldgen/feature/birch_bees_002.json
+ minecraft/worldgen/feature/birch_bees_005.json
+ minecraft/worldgen/feature/birch_leaf_litter.json
+ minecraft/worldgen/feature/birch_tall.json
+ minecraft/worldgen/feature/birch.json
+ minecraft/worldgen/feature/blackstone_blobs.json
+ minecraft/worldgen/feature/blue_ice.json
+ minecraft/worldgen/feature/bonus_chest.json
+ minecraft/worldgen/feature/brown_mushroom.json
+ minecraft/worldgen/feature/bush.json
+ minecraft/worldgen/feature/cactus.json
+ minecraft/worldgen/feature/cave_vine_in_moss.json
+ minecraft/worldgen/feature/cave_vine.json
+ minecraft/worldgen/feature/cherry_bees_005.json
+ minecraft/worldgen/feature/cherry.json
+ minecraft/worldgen/feature/chorus_plant.json
+ minecraft/worldgen/feature/clay_pool_with_dripleaves.json
+ minecraft/worldgen/feature/clay_with_dripleaves.json
+ minecraft/worldgen/feature/crimson_forest_vegetation_bonemeal.json
+ minecraft/worldgen/feature/crimson_forest_vegetation.json
+ minecraft/worldgen/feature/crimson_fungus_planted.json
+ minecraft/worldgen/feature/crimson_fungus.json
+ minecraft/worldgen/feature/crimson_roots.json
+ minecraft/worldgen/feature/dark_forest_vegetation.json
+ minecraft/worldgen/feature/dark_oak_leaf_litter.json
+ minecraft/worldgen/feature/dark_oak.json
+ minecraft/worldgen/feature/dead_bush.json
+ minecraft/worldgen/feature/delta.json
+ minecraft/worldgen/feature/desert_well.json
+ minecraft/worldgen/feature/disk_clay.json
+ minecraft/worldgen/feature/disk_grass.json
+ minecraft/worldgen/feature/disk_gravel.json
+ minecraft/worldgen/feature/disk_sand.json
+ minecraft/worldgen/feature/dripleaf.json
+ minecraft/worldgen/feature/dripstone_cluster.json
+ minecraft/worldgen/feature/dry_grass.json
+ minecraft/worldgen/feature/end_gateway_delayed.json
+ minecraft/worldgen/feature/end_gateway_return.json
+ minecraft/worldgen/feature/end_island.json
+ minecraft/worldgen/feature/end_platform.json
+ minecraft/worldgen/feature/end_podium_active.json
+ minecraft/worldgen/feature/end_podium_inactive.json
+ minecraft/worldgen/feature/end_spike.json
+ minecraft/worldgen/feature/fallen_birch_tree.json
+ minecraft/worldgen/feature/fallen_jungle_tree.json
+ minecraft/worldgen/feature/fallen_oak_tree.json
+ minecraft/worldgen/feature/fallen_poplar_tree.json
+ minecraft/worldgen/feature/fallen_spruce_tree.json
+ minecraft/worldgen/feature/fallen_super_birch_tree.json
+ minecraft/worldgen/feature/fancy_oak_bees_0002_leaf_litter.json
+ minecraft/worldgen/feature/fancy_oak_bees_002.json
+ minecraft/worldgen/feature/fancy_oak_bees_005.json
+ minecraft/worldgen/feature/fancy_oak_bees.json
+ minecraft/worldgen/feature/fancy_oak_leaf_litter.json
+ minecraft/worldgen/feature/fancy_oak.json
+ minecraft/worldgen/feature/firefly_bush.json
+ minecraft/worldgen/feature/flower_cherry.json
+ minecraft/worldgen/feature/flower_default.json
+ minecraft/worldgen/feature/flower_flower_forest.json
+ minecraft/worldgen/feature/flower_meadow.json
+ minecraft/worldgen/feature/flower_pale_garden.json
+ minecraft/worldgen/feature/flower_plain.json
+ minecraft/worldgen/feature/flower_swamp.json
+ minecraft/worldgen/feature/forest_flowers.json
+ minecraft/worldgen/feature/forest_rock.json
+ minecraft/worldgen/feature/fossil_coal.json
+ minecraft/worldgen/feature/fossil_diamonds.json
+ minecraft/worldgen/feature/freeze_top_layer.json
+ minecraft/worldgen/feature/glow_lichen.json
+ minecraft/worldgen/feature/glowstone_extra.json
+ minecraft/worldgen/feature/grass_jungle.json
+ minecraft/worldgen/feature/grass.json
+ minecraft/worldgen/feature/huge_brown_mushroom.json
+ minecraft/worldgen/feature/huge_red_mushroom.json
+ minecraft/worldgen/feature/ice_patch.json
+ minecraft/worldgen/feature/ice_spike.json
+ minecraft/worldgen/feature/iceberg_blue.json
+ minecraft/worldgen/feature/iceberg_packed.json
+ minecraft/worldgen/feature/jungle_bush.json
+ minecraft/worldgen/feature/jungle_tree_no_vine.json
+ minecraft/worldgen/feature/jungle_tree.json
+ minecraft/worldgen/feature/kelp.json
+ minecraft/worldgen/feature/lake_lava.json
+ minecraft/worldgen/feature/large_basalt_columns.json
+ minecraft/worldgen/feature/large_dripstone.json
+ minecraft/worldgen/feature/large_fern.json
+ minecraft/worldgen/feature/leaf_litter.json
+ minecraft/worldgen/feature/lush_caves_clay.json
+ minecraft/worldgen/feature/mangrove_vegetation.json
+ minecraft/worldgen/feature/mangrove.json
+ minecraft/worldgen/feature/meadow_trees.json
+ minecraft/worldgen/feature/mega_jungle_tree.json
+ minecraft/worldgen/feature/mega_pine.json
+ minecraft/worldgen/feature/mega_spruce.json
+ minecraft/worldgen/feature/melon.json
+ minecraft/worldgen/feature/monster_room.json
+ minecraft/worldgen/feature/moss_patch_bonemeal.json
+ minecraft/worldgen/feature/moss_patch_ceiling.json
+ minecraft/worldgen/feature/moss_patch.json
+ minecraft/worldgen/feature/moss_vegetation.json
+ minecraft/worldgen/feature/mushroom_island_vegetation.json
+ minecraft/worldgen/feature/nether_sprouts_bonemeal.json
+ minecraft/worldgen/feature/nether_sprouts.json
+ minecraft/worldgen/feature/oak_bees_0002_leaf_litter.json
+ minecraft/worldgen/feature/oak_bees_002.json
+ minecraft/worldgen/feature/oak_bees_005.json
+ minecraft/worldgen/feature/oak_leaf_litter.json
+ minecraft/worldgen/feature/oak.json
+ minecraft/worldgen/feature/orange_poplar_leaf_litter.json
+ minecraft/worldgen/feature/orange_poplar.json
+ minecraft/worldgen/feature/ore_ancient_debris_large.json
+ minecraft/worldgen/feature/ore_ancient_debris_small.json
+ minecraft/worldgen/feature/ore_andesite.json
+ minecraft/worldgen/feature/ore_blackstone.json
+ minecraft/worldgen/feature/ore_clay.json
+ minecraft/worldgen/feature/ore_coal_buried.json
+ minecraft/worldgen/feature/ore_coal.json
+ minecraft/worldgen/feature/ore_copper_large.json
+ minecraft/worldgen/feature/ore_copper_small.json
+ minecraft/worldgen/feature/ore_diamond_buried.json
+ minecraft/worldgen/feature/ore_diamond_large.json
+ minecraft/worldgen/feature/ore_diamond_medium.json
+ minecraft/worldgen/feature/ore_diamond_small.json
+ minecraft/worldgen/feature/ore_diorite.json
+ minecraft/worldgen/feature/ore_dirt.json
+ minecraft/worldgen/feature/ore_emerald.json
+ minecraft/worldgen/feature/ore_gold_buried.json
+ minecraft/worldgen/feature/ore_gold.json
+ minecraft/worldgen/feature/ore_granite.json
+ minecraft/worldgen/feature/ore_gravel_nether.json
+ minecraft/worldgen/feature/ore_gravel.json
+ minecraft/worldgen/feature/ore_infested.json
+ minecraft/worldgen/feature/ore_iron_small.json
+ minecraft/worldgen/feature/ore_iron.json
+ minecraft/worldgen/feature/ore_lapis_buried.json
+ minecraft/worldgen/feature/ore_lapis.json
+ minecraft/worldgen/feature/ore_magma.json
+ minecraft/worldgen/feature/ore_nether_gold.json
+ minecraft/worldgen/feature/ore_quartz.json
+ minecraft/worldgen/feature/ore_redstone.json
+ minecraft/worldgen/feature/ore_soul_sand.json
+ minecraft/worldgen/feature/ore_tuff.json
+ minecraft/worldgen/feature/pale_forest_flower.json
+ minecraft/worldgen/feature/pale_garden_vegetation.json
+ minecraft/worldgen/feature/pale_moss_patch_bonemeal.json
+ minecraft/worldgen/feature/pale_moss_patch.json
+ minecraft/worldgen/feature/pale_moss_vegetation.json
+ minecraft/worldgen/feature/pale_oak_bonemeal.json
+ minecraft/worldgen/feature/pale_oak_creaking.json
+ minecraft/worldgen/feature/pale_oak.json
+ minecraft/worldgen/feature/patch_fire.json
+ minecraft/worldgen/feature/patch_soul_fire.json
+ minecraft/worldgen/feature/pile_hay.json
+ minecraft/worldgen/feature/pile_ice.json
+ minecraft/worldgen/feature/pile_melon.json
+ minecraft/worldgen/feature/pile_pumpkin.json
+ minecraft/worldgen/feature/pile_snow.json
+ minecraft/worldgen/feature/pine.json
+ minecraft/worldgen/feature/pointed_dripstone.json
+ minecraft/worldgen/feature/pumpkin.json
+ minecraft/worldgen/feature/red_mushroom.json
+ minecraft/worldgen/feature/red_poplar_leaf_litter.json
+ minecraft/worldgen/feature/red_poplar.json
+ minecraft/worldgen/feature/red_shrub.json
+ minecraft/worldgen/feature/rooted_azalea_tree.json
+ minecraft/worldgen/feature/rooted_sulfur_spring.json
+ minecraft/worldgen/feature/sculk_patch_ancient_city.json
+ minecraft/worldgen/feature/sculk_patch_deep_dark.json
+ minecraft/worldgen/feature/sculk_vein.json
+ minecraft/worldgen/feature/sea_pickle.json
+ minecraft/worldgen/feature/seagrass_mid.json
+ minecraft/worldgen/feature/seagrass_short.json
+ minecraft/worldgen/feature/seagrass_slightly_less_short.json
+ minecraft/worldgen/feature/seagrass_tall.json
+ minecraft/worldgen/feature/small_basalt_columns.json
+ minecraft/worldgen/feature/spore_blossom.json
+ minecraft/worldgen/feature/spring_lava_frozen.json
+ minecraft/worldgen/feature/spring_lava_nether.json
+ minecraft/worldgen/feature/spring_lava_overworld.json
+ minecraft/worldgen/feature/spring_nether_closed.json
+ minecraft/worldgen/feature/spring_nether_open.json
+ minecraft/worldgen/feature/spring_water.json
+ minecraft/worldgen/feature/spruce.json
+ minecraft/worldgen/feature/sugar_cane.json
+ minecraft/worldgen/feature/sulfur_pool.json
+ minecraft/worldgen/feature/sulfur_spike_cluster.json
+ minecraft/worldgen/feature/sulfur_spike.json
+ minecraft/worldgen/feature/sulfur_spring.json
+ minecraft/worldgen/feature/sunflower.json
+ minecraft/worldgen/feature/super_birch_bees_0002.json
+ minecraft/worldgen/feature/super_birch_bees.json
+ minecraft/worldgen/feature/swamp_oak.json
+ minecraft/worldgen/feature/taiga_grass.json
+ minecraft/worldgen/feature/tall_grass.json
+ minecraft/worldgen/feature/tall_mangrove.json
+ minecraft/worldgen/feature/trees_badlands.json
+ minecraft/worldgen/feature/trees_birch_and_oak_leaf_litter.json
+ minecraft/worldgen/feature/trees_birch.json
+ minecraft/worldgen/feature/trees_dappled_forest.json
+ minecraft/worldgen/feature/trees_flower_forest.json
+ minecraft/worldgen/feature/trees_grove.json
+ minecraft/worldgen/feature/trees_jungle.json
+ minecraft/worldgen/feature/trees_old_growth_pine_taiga.json
+ minecraft/worldgen/feature/trees_old_growth_spruce_taiga.json
+ minecraft/worldgen/feature/trees_plains.json
+ minecraft/worldgen/feature/trees_savanna.json
+ minecraft/worldgen/feature/trees_snowy.json
+ minecraft/worldgen/feature/trees_sparse_jungle.json
+ minecraft/worldgen/feature/trees_taiga.json
+ minecraft/worldgen/feature/trees_water.json
+ minecraft/worldgen/feature/trees_windswept_hills.json
+ minecraft/worldgen/feature/twisting_vines_bonemeal.json
+ minecraft/worldgen/feature/twisting_vines.json
+ minecraft/worldgen/feature/underwater_magma.json
+ minecraft/worldgen/feature/vines.json
+ minecraft/worldgen/feature/void_start_platform.json
+ minecraft/worldgen/feature/warm_ocean_vegetation.json
+ minecraft/worldgen/feature/warped_forest_vegetation_bonemeal.json
+ minecraft/worldgen/feature/warped_forest_vegetation.json
+ minecraft/worldgen/feature/warped_fungus_planted.json
+ minecraft/worldgen/feature/warped_fungus.json
+ minecraft/worldgen/feature/waterlily.json
+ minecraft/worldgen/feature/weeping_vines.json
+ minecraft/worldgen/feature/wildflower.json
+ minecraft/worldgen/feature/yellow_poplar_leaf_litter.json
+ minecraft/worldgen/feature/yellow_poplar.json
+ minecraft/worldgen/material_condition/above_water.json
+ minecraft/worldgen/material_condition/deep_under_floor.json
+ minecraft/worldgen/material_condition/not_under_deep_water.json
+ minecraft/worldgen/material_condition/not_underwater.json
+ minecraft/worldgen/material_condition/on_ceiling.json
+ minecraft/worldgen/material_condition/on_floor.json
+ minecraft/worldgen/material_condition/under_ceiling.json
+ minecraft/worldgen/material_condition/under_floor.json
+ minecraft/worldgen/material_condition/very_deep_under_floor.json
+ minecraft/worldgen/material_rule/bedrock_floor.json
+ minecraft/worldgen/material_rule/bedrock_roof.json
+ minecraft/worldgen/material_rule/end.json
+ minecraft/worldgen/material_rule/nether.json
+ minecraft/worldgen/material_rule/overworld_caves.json
+ minecraft/worldgen/material_rule/overworld_floating_islands.json
+ minecraft/worldgen/material_rule/overworld.json
+ minecraft/worldgen/material_rule/overworld/biome_surface.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/dappled_forest.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/default.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/dripstone_caves.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/frozen_peaks.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/grove.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/ice_spikes.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/jagged_peaks.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/mangrove_swamp.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/mushroom_fields.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/old_growth_pine_taiga.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/snowy_slopes.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/stony_peaks.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/stony_shore.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/sulfur_caves.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/windswept_gravelly_hills.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/windswept_hills.json
+ minecraft/worldgen/material_rule/overworld/biome_surface/windswept_savanna.json
+ minecraft/worldgen/material_rule/overworld/gravel_or_stone_if_ceiling.json
+ minecraft/worldgen/material_rule/overworld/powder_snow_surface.json
+ minecraft/worldgen/material_rule/overworld/powder_snow_under_surface.json
+ minecraft/worldgen/material_rule/overworld/sand_or_sandstone_if_ceiling.json
+ minecraft/worldgen/material_rule/overworld/sulfur_cave_bands.json
+ minecraft/worldgen/material_rule/overworld/surface.json
+ minecraft/worldgen/material_rule/overworld/under_biome_surface.json
+ minecraft/worldgen/material_rule/overworld/under_biome_surface/default.json
+ minecraft/worldgen/material_rule/overworld/under_biome_surface/frozen_peaks.json
+ minecraft/worldgen/material_rule/overworld/under_biome_surface/grove.json
+ minecraft/worldgen/material_rule/overworld/under_biome_surface/jagged_peaks.json
+ minecraft/worldgen/material_rule/overworld/under_biome_surface/snowy_slopes.json
+ minecraft/worldgen/material_rule/overworld/under_biome_surface/windswept_gravelly_hills.json
+ minecraft/worldgen/material_rule/overworld/under_biome_surface/windswept_savanna.json
+ minecraft/worldgen/material_rule/overworld/underground.json
+ minecraft/worldgen/noise/small_patch.json
+ minecraft/worldgen/placed_feature/brown_mushroom_dappled_forest.json
+ minecraft/worldgen/placed_feature/fallen_poplar_tree.json
+ minecraft/worldgen/placed_feature/orange_poplar_leaf_litter.json
+ minecraft/worldgen/placed_feature/patch_red_shrub.json
+ minecraft/worldgen/placed_feature/red_poplar_leaf_litter.json
+ minecraft/worldgen/placed_feature/trees_dappled_forest.json
+ minecraft/worldgen/placed_feature/yellow_poplar_leaf_litter.json
+ minecraft/worldgen/structure_set/abandoned_camp.json
+ minecraft/worldgen/structure/abandoned_camp_bamboo_jungle.json
+ minecraft/worldgen/structure/abandoned_camp_birch_forest.json
+ minecraft/worldgen/structure/abandoned_camp_cherry_grove.json
+ minecraft/worldgen/structure/abandoned_camp_dappled_forest.json
+ minecraft/worldgen/structure/abandoned_camp_flower_forest.json
+ minecraft/worldgen/structure/abandoned_camp_forest.json
+ minecraft/worldgen/structure/abandoned_camp_meadow.json
+ minecraft/worldgen/structure/abandoned_camp_old_growth_birch_forest.json
+ minecraft/worldgen/structure/abandoned_camp_old_growth_pine_taiga.json
+ minecraft/worldgen/structure/abandoned_camp_old_growth_spruce_taiga.json
+ minecraft/worldgen/structure/abandoned_camp_pale_garden.json
+ minecraft/worldgen/structure/abandoned_camp_savanna.json
+ minecraft/worldgen/structure/abandoned_camp_snowy_taiga.json
+ minecraft/worldgen/structure/abandoned_camp_sparse_jungle.json
+ minecraft/worldgen/structure/abandoned_camp_swamp.json
+ minecraft/worldgen/structure/abandoned_camp_taiga.json
+ minecraft/worldgen/structure/abandoned_camp_windswept_forest.json
+ minecraft/worldgen/structure/abandoned_camp_wooded_badlands.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/bamboo_jungle.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/birch_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/cherry_grove.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/dappled_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/flower_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/meadow.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/old_growth_birch_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/old_growth_pine_taiga.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/old_growth_spruce_taiga.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/pale_garden.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/savanna.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/snowy_taiga.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/sparse_jungle.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/swamp.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/taiga.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/windswept_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/camp/wooded_badlands.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/bamboo_jungle.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/birch_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/cherry_grove.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/dappled_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/flower_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/meadow.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/old_growth_birch_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/old_growth_pine_taiga.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/old_growth_spruce_taiga.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/pale_garden.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/savanna.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/snowy_taiga.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/sparse_jungle.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/swamp.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/taiga.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/windswept_forest.json
+ minecraft/worldgen/template_pool/abandoned_camp/tent/wooded_badlands.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/atlases/armor_trims.json
+ minecraft/blockstates/black_wool_slab.json
+ minecraft/blockstates/black_wool_stairs.json
+ minecraft/blockstates/blue_wool_slab.json
+ minecraft/blockstates/blue_wool_stairs.json
+ minecraft/blockstates/brown_wool_slab.json
+ minecraft/blockstates/brown_wool_stairs.json
+ minecraft/blockstates/cyan_wool_slab.json
+ minecraft/blockstates/cyan_wool_stairs.json
+ minecraft/blockstates/gray_wool_slab.json
+ minecraft/blockstates/gray_wool_stairs.json
+ minecraft/blockstates/green_wool_slab.json
+ minecraft/blockstates/green_wool_stairs.json
+ minecraft/blockstates/light_blue_wool_slab.json
+ minecraft/blockstates/light_blue_wool_stairs.json
+ minecraft/blockstates/light_gray_wool_slab.json
+ minecraft/blockstates/light_gray_wool_stairs.json
+ minecraft/blockstates/lime_wool_slab.json
+ minecraft/blockstates/lime_wool_stairs.json
+ minecraft/blockstates/magenta_wool_slab.json
+ minecraft/blockstates/magenta_wool_stairs.json
+ minecraft/blockstates/orange_poplar_leaves.json
+ minecraft/blockstates/orange_wool_slab.json
+ minecraft/blockstates/orange_wool_stairs.json
+ minecraft/blockstates/pink_wool_slab.json
+ minecraft/blockstates/pink_wool_stairs.json
+ minecraft/blockstates/poplar_button.json
+ minecraft/blockstates/poplar_door.json
+ minecraft/blockstates/poplar_fence_gate.json
+ minecraft/blockstates/poplar_fence.json
+ minecraft/blockstates/poplar_hanging_sign.json
+ minecraft/blockstates/poplar_log.json
+ minecraft/blockstates/poplar_planks.json
+ minecraft/blockstates/poplar_pressure_plate.json
+ minecraft/blockstates/poplar_sapling.json
+ minecraft/blockstates/poplar_shelf.json
+ minecraft/blockstates/poplar_sign.json
+ minecraft/blockstates/poplar_slab.json
+ minecraft/blockstates/poplar_stairs.json
+ minecraft/blockstates/poplar_trapdoor.json
+ minecraft/blockstates/poplar_wall_hanging_sign.json
+ minecraft/blockstates/poplar_wall_sign.json
+ minecraft/blockstates/poplar_wood.json
+ minecraft/blockstates/potted_poplar_sapling.json
+ minecraft/blockstates/purple_wool_slab.json
+ minecraft/blockstates/purple_wool_stairs.json
+ minecraft/blockstates/red_poplar_leaves.json
+ minecraft/blockstates/red_shrub.json
+ minecraft/blockstates/red_wool_slab.json
+ minecraft/blockstates/red_wool_stairs.json
+ minecraft/blockstates/shelf_mushroom.json
+ minecraft/blockstates/stripped_poplar_log.json
+ minecraft/blockstates/stripped_poplar_wood.json
+ minecraft/blockstates/white_wool_slab.json
+ minecraft/blockstates/white_wool_stairs.json
+ minecraft/blockstates/yellow_poplar_leaves.json
+ minecraft/blockstates/yellow_wool_slab.json
+ minecraft/blockstates/yellow_wool_stairs.json
+ minecraft/items/black_wool_slab.json
+ minecraft/items/black_wool_stairs.json
+ minecraft/items/blue_wool_slab.json
+ minecraft/items/blue_wool_stairs.json
+ minecraft/items/brown_wool_slab.json
+ minecraft/items/brown_wool_stairs.json
+ minecraft/items/cyan_wool_slab.json
+ minecraft/items/cyan_wool_stairs.json
+ minecraft/items/gray_wool_slab.json
+ minecraft/items/gray_wool_stairs.json
+ minecraft/items/green_wool_slab.json
+ minecraft/items/green_wool_stairs.json
+ minecraft/items/light_blue_wool_slab.json
+ minecraft/items/light_blue_wool_stairs.json
+ minecraft/items/light_gray_wool_slab.json
+ minecraft/items/light_gray_wool_stairs.json
+ minecraft/items/lime_wool_slab.json
+ minecraft/items/lime_wool_stairs.json
+ minecraft/items/magenta_wool_slab.json
+ minecraft/items/magenta_wool_stairs.json
+ minecraft/items/orange_poplar_leaves.json
+ minecraft/items/orange_wool_slab.json
+ minecraft/items/orange_wool_stairs.json
+ minecraft/items/pink_wool_slab.json
+ minecraft/items/pink_wool_stairs.json
+ minecraft/items/poplar_boat.json
+ minecraft/items/poplar_button.json
+ minecraft/items/poplar_chest_boat.json
+ minecraft/items/poplar_door.json
+ minecraft/items/poplar_fence_gate.json
+ minecraft/items/poplar_fence.json
+ minecraft/items/poplar_hanging_sign.json
+ minecraft/items/poplar_log.json
+ minecraft/items/poplar_planks.json
+ minecraft/items/poplar_pressure_plate.json
+ minecraft/items/poplar_sapling.json
+ minecraft/items/poplar_shelf.json
+ minecraft/items/poplar_sign.json
+ minecraft/items/poplar_slab.json
+ minecraft/items/poplar_stairs.json
+ minecraft/items/poplar_trapdoor.json
+ minecraft/items/poplar_wood.json
+ minecraft/items/purple_wool_slab.json
+ minecraft/items/purple_wool_stairs.json
+ minecraft/items/red_poplar_leaves.json
+ minecraft/items/red_shrub.json
+ minecraft/items/red_wool_slab.json
+ minecraft/items/red_wool_stairs.json
+ minecraft/items/shelf_mushroom.json
+ minecraft/items/stripped_poplar_log.json
+ minecraft/items/stripped_poplar_wood.json
+ minecraft/items/white_wool_slab.json
+ minecraft/items/white_wool_stairs.json
+ minecraft/items/yellow_poplar_leaves.json
+ minecraft/items/yellow_wool_slab.json
+ minecraft/items/yellow_wool_stairs.json
+ minecraft/models/block/black_wool_slab_top.json
+ minecraft/models/block/black_wool_slab.json
+ minecraft/models/block/black_wool_stairs_inner.json
+ minecraft/models/block/black_wool_stairs_outer.json
+ minecraft/models/block/black_wool_stairs.json
+ minecraft/models/block/blue_wool_slab_top.json
+ minecraft/models/block/blue_wool_slab.json
+ minecraft/models/block/blue_wool_stairs_inner.json
+ minecraft/models/block/blue_wool_stairs_outer.json
+ minecraft/models/block/blue_wool_stairs.json
+ minecraft/models/block/brown_wool_slab_top.json
+ minecraft/models/block/brown_wool_slab.json
+ minecraft/models/block/brown_wool_stairs_inner.json
+ minecraft/models/block/brown_wool_stairs_outer.json
+ minecraft/models/block/brown_wool_stairs.json
+ minecraft/models/block/cyan_wool_slab_top.json
+ minecraft/models/block/cyan_wool_slab.json
+ minecraft/models/block/cyan_wool_stairs_inner.json
+ minecraft/models/block/cyan_wool_stairs_outer.json
+ minecraft/models/block/cyan_wool_stairs.json
+ minecraft/models/block/gray_wool_slab_top.json
+ minecraft/models/block/gray_wool_slab.json
+ minecraft/models/block/gray_wool_stairs_inner.json
+ minecraft/models/block/gray_wool_stairs_outer.json
+ minecraft/models/block/gray_wool_stairs.json
+ minecraft/models/block/green_wool_slab_top.json
+ minecraft/models/block/green_wool_slab.json
+ minecraft/models/block/green_wool_stairs_inner.json
+ minecraft/models/block/green_wool_stairs_outer.json
+ minecraft/models/block/green_wool_stairs.json
+ minecraft/models/block/light_blue_wool_slab_top.json
+ minecraft/models/block/light_blue_wool_slab.json
+ minecraft/models/block/light_blue_wool_stairs_inner.json
+ minecraft/models/block/light_blue_wool_stairs_outer.json
+ minecraft/models/block/light_blue_wool_stairs.json
+ minecraft/models/block/light_gray_wool_slab_top.json
+ minecraft/models/block/light_gray_wool_slab.json
+ minecraft/models/block/light_gray_wool_stairs_inner.json
+ minecraft/models/block/light_gray_wool_stairs_outer.json
+ minecraft/models/block/light_gray_wool_stairs.json
+ minecraft/models/block/lime_wool_slab_top.json
+ minecraft/models/block/lime_wool_slab.json
+ minecraft/models/block/lime_wool_stairs_inner.json
+ minecraft/models/block/lime_wool_stairs_outer.json
+ minecraft/models/block/lime_wool_stairs.json
+ minecraft/models/block/magenta_wool_slab_top.json
+ minecraft/models/block/magenta_wool_slab.json
+ minecraft/models/block/magenta_wool_stairs_inner.json
+ minecraft/models/block/magenta_wool_stairs_outer.json
+ minecraft/models/block/magenta_wool_stairs.json
+ minecraft/models/block/orange_poplar_leaves.json
+ minecraft/models/block/orange_wool_slab_top.json
+ minecraft/models/block/orange_wool_slab.json
+ minecraft/models/block/orange_wool_stairs_inner.json
+ minecraft/models/block/orange_wool_stairs_outer.json
+ minecraft/models/block/orange_wool_stairs.json
+ minecraft/models/block/pink_wool_slab_top.json
+ minecraft/models/block/pink_wool_slab.json
+ minecraft/models/block/pink_wool_stairs_inner.json
+ minecraft/models/block/pink_wool_stairs_outer.json
+ minecraft/models/block/pink_wool_stairs.json
+ minecraft/models/block/poplar_button_inventory.json
+ minecraft/models/block/poplar_button_pressed.json
+ minecraft/models/block/poplar_button.json
+ minecraft/models/block/poplar_door_bottom_left_open.json
+ minecraft/models/block/poplar_door_bottom_left.json
+ minecraft/models/block/poplar_door_bottom_right_open.json
+ minecraft/models/block/poplar_door_bottom_right.json
+ minecraft/models/block/poplar_door_top_left_open.json
+ minecraft/models/block/poplar_door_top_left.json
+ minecraft/models/block/poplar_door_top_right_open.json
+ minecraft/models/block/poplar_door_top_right.json
+ minecraft/models/block/poplar_fence_gate_open.json
+ minecraft/models/block/poplar_fence_gate_wall_open.json
+ minecraft/models/block/poplar_fence_gate_wall.json
+ minecraft/models/block/poplar_fence_gate.json
+ minecraft/models/block/poplar_fence_inventory.json
+ minecraft/models/block/poplar_fence_post.json
+ minecraft/models/block/poplar_fence_side.json
+ minecraft/models/block/poplar_hanging_sign_attached_rot_0.json
+ minecraft/models/block/poplar_hanging_sign_attached_rot_1.json
+ minecraft/models/block/poplar_hanging_sign_attached_rot_2.json
+ minecraft/models/block/poplar_hanging_sign_attached_rot_3.json
+ minecraft/models/block/poplar_hanging_sign_rot_0.json
+ minecraft/models/block/poplar_hanging_sign_rot_1.json
+ minecraft/models/block/poplar_hanging_sign_rot_2.json
+ minecraft/models/block/poplar_hanging_sign_rot_3.json
+ minecraft/models/block/poplar_log_horizontal.json
+ minecraft/models/block/poplar_log.json
+ minecraft/models/block/poplar_planks.json
+ minecraft/models/block/poplar_pressure_plate_down.json
+ minecraft/models/block/poplar_pressure_plate.json
+ minecraft/models/block/poplar_sapling.json
+ minecraft/models/block/poplar_shelf_center.json
+ minecraft/models/block/poplar_shelf_inventory.json
+ minecraft/models/block/poplar_shelf_left.json
+ minecraft/models/block/poplar_shelf_right.json
+ minecraft/models/block/poplar_shelf_unconnected.json
+ minecraft/models/block/poplar_shelf_unpowered.json
+ minecraft/models/block/poplar_shelf.json
+ minecraft/models/block/poplar_sign_rot_0.json
+ minecraft/models/block/poplar_sign_rot_1.json
+ minecraft/models/block/poplar_sign_rot_2.json
+ minecraft/models/block/poplar_sign_rot_3.json
+ minecraft/models/block/poplar_slab_top.json
+ minecraft/models/block/poplar_slab.json
+ minecraft/models/block/poplar_stairs_inner.json
+ minecraft/models/block/poplar_stairs_outer.json
+ minecraft/models/block/poplar_stairs.json
+ minecraft/models/block/poplar_trapdoor_bottom.json
+ minecraft/models/block/poplar_trapdoor_open.json
+ minecraft/models/block/poplar_trapdoor_top.json
+ minecraft/models/block/poplar_wall_hanging_sign.json
+ minecraft/models/block/poplar_wall_sign.json
+ minecraft/models/block/poplar_wood.json
+ minecraft/models/block/potted_poplar_sapling.json
+ minecraft/models/block/purple_wool_slab_top.json
+ minecraft/models/block/purple_wool_slab.json
+ minecraft/models/block/purple_wool_stairs_inner.json
+ minecraft/models/block/purple_wool_stairs_outer.json
+ minecraft/models/block/purple_wool_stairs.json
+ minecraft/models/block/red_poplar_leaves.json
+ minecraft/models/block/red_shrub.json
+ minecraft/models/block/red_wool_slab_top.json
+ minecraft/models/block/red_wool_slab.json
+ minecraft/models/block/red_wool_stairs_inner.json
+ minecraft/models/block/red_wool_stairs_outer.json
+ minecraft/models/block/red_wool_stairs.json
+ minecraft/models/block/shelf_mushroom_stage0.json
+ minecraft/models/block/shelf_mushroom_stage1.json
+ minecraft/models/block/stripped_poplar_log_horizontal.json
+ minecraft/models/block/stripped_poplar_log.json
+ minecraft/models/block/stripped_poplar_wood.json
+ minecraft/models/block/template_cube_bottom_top_indented.json
- minecraft/models/block/template_farmland.json
+ minecraft/models/block/white_wool_slab_top.json
+ minecraft/models/block/white_wool_slab.json
+ minecraft/models/block/white_wool_stairs_inner.json
+ minecraft/models/block/white_wool_stairs_outer.json
+ minecraft/models/block/white_wool_stairs.json
+ minecraft/models/block/yellow_poplar_leaves.json
+ minecraft/models/block/yellow_wool_slab_top.json
+ minecraft/models/block/yellow_wool_slab.json
+ minecraft/models/block/yellow_wool_stairs_inner.json
+ minecraft/models/block/yellow_wool_stairs_outer.json
+ minecraft/models/block/yellow_wool_stairs.json
+ minecraft/models/item/poplar_boat.json
+ minecraft/models/item/poplar_chest_boat.json
+ minecraft/models/item/poplar_door.json
+ minecraft/models/item/poplar_hanging_sign.json
+ minecraft/models/item/poplar_sapling.json
+ minecraft/models/item/poplar_sign.json
+ minecraft/models/item/red_shrub.json
+ minecraft/particles/orange_poplar_leaves.json
+ minecraft/particles/red_poplar_leaves.json
+ minecraft/particles/yellow_poplar_leaves.json
+ minecraft/textures/block/orange_poplar_leaves.png
+ minecraft/textures/block/poplar_door_bottom.png
+ minecraft/textures/block/poplar_door_top.png
+ minecraft/textures/block/poplar_hanging_sign.png
+ minecraft/textures/block/poplar_log_top.png
+ minecraft/textures/block/poplar_log.png
+ minecraft/textures/block/poplar_planks.png
+ minecraft/textures/block/poplar_sapling.png
+ minecraft/textures/block/poplar_shelf.png
+ minecraft/textures/block/poplar_sign.png
+ minecraft/textures/block/poplar_trapdoor.png
+ minecraft/textures/block/red_poplar_leaves.png
+ minecraft/textures/block/red_shrub.png
+ minecraft/textures/block/shelf_mushroom_stage0.png
+ minecraft/textures/block/shelf_mushroom_stage1.png
+ minecraft/textures/block/stripped_poplar_log_top.png
+ minecraft/textures/block/stripped_poplar_log.png
+ minecraft/textures/block/yellow_poplar_leaves.png
+ minecraft/textures/entity/boat/poplar.png
+ minecraft/textures/entity/chest_boat/poplar.png
+ minecraft/textures/gui/hanging_signs/poplar.png
+ minecraft/textures/gui/signs/poplar.png
+ minecraft/textures/item/poplar_boat.png
+ minecraft/textures/item/poplar_chest_boat.png
+ minecraft/textures/item/poplar_door.png
+ minecraft/textures/item/poplar_hanging_sign.png
+ minecraft/textures/item/poplar_sign.png
+ minecraft/textures/palettes/trim_base.png
+ minecraft/textures/palettes/trim/amethyst.png
+ minecraft/textures/palettes/trim/copper_darker.png
+ minecraft/textures/palettes/trim/copper.png
+ minecraft/textures/palettes/trim/diamond_darker.png
+ minecraft/textures/palettes/trim/diamond.png
+ minecraft/textures/palettes/trim/emerald.png
+ minecraft/textures/palettes/trim/gold_darker.png
+ minecraft/textures/palettes/trim/gold.png
+ minecraft/textures/palettes/trim/iron_darker.png
+ minecraft/textures/palettes/trim/iron.png
+ minecraft/textures/palettes/trim/lapis.png
+ minecraft/textures/palettes/trim/netherite_darker.png
+ minecraft/textures/palettes/trim/netherite.png
+ minecraft/textures/palettes/trim/quartz.png
+ minecraft/textures/palettes/trim/redstone.png
+ minecraft/textures/palettes/trim/resin.png
+ minecraft/textures/particle/orange_poplar_1.png
+ minecraft/textures/particle/orange_poplar_2.png
+ minecraft/textures/particle/orange_poplar_3.png
+ minecraft/textures/particle/orange_poplar_4.png
+ minecraft/textures/particle/red_poplar_1.png
+ minecraft/textures/particle/red_poplar_2.png
+ minecraft/textures/particle/red_poplar_3.png
+ minecraft/textures/particle/red_poplar_4.png
+ minecraft/textures/particle/yellow_poplar_1.png
+ minecraft/textures/particle/yellow_poplar_2.png
+ minecraft/textures/particle/yellow_poplar_3.png
+ minecraft/textures/particle/yellow_poplar_4.png
- minecraft/textures/trims/color_palettes/amethyst.png
- minecraft/textures/trims/color_palettes/copper_darker.png
- minecraft/textures/trims/color_palettes/copper.png
- minecraft/textures/trims/color_palettes/diamond_darker.png
- minecraft/textures/trims/color_palettes/diamond.png
- minecraft/textures/trims/color_palettes/emerald.png
- minecraft/textures/trims/color_palettes/gold_darker.png
- minecraft/textures/trims/color_palettes/gold.png
- minecraft/textures/trims/color_palettes/iron_darker.png
- minecraft/textures/trims/color_palettes/iron.png
- minecraft/textures/trims/color_palettes/lapis.png
- minecraft/textures/trims/color_palettes/netherite_darker.png
- minecraft/textures/trims/color_palettes/netherite.png
- minecraft/textures/trims/color_palettes/quartz.png
- minecraft/textures/trims/color_palettes/redstone.png
- minecraft/textures/trims/color_palettes/resin.png
- minecraft/textures/trims/color_palettes/trim_palette.png
+ minecraft/textures/trims/entity/humanoid_leggings/bolt.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/coast.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/dune.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/eye.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/flow.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/host.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/raiser.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/rib.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/sentry.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/shaper.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/silence.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/snout.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/spire.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/tide.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/vex.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/ward.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/wayfinder.png.mcmeta
+ minecraft/textures/trims/entity/humanoid_leggings/wild.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/bolt.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/coast.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/dune.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/eye.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/flow.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/host.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/raiser.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/rib.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/sentry.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/shaper.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/silence.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/snout.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/spire.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/tide.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/vex.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/ward.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/wayfinder.png.mcmeta
+ minecraft/textures/trims/entity/humanoid/wild.png.mcmeta
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
parsers
</summary>

```diff
- minecraft:item_slots
+ minecraft:slot_source
```

</details>
<details>
<summary>
rpc-api-methods
</summary>

```diff
+ minecraft:notification/world/upgrade_failed
+ minecraft:notification/world/upgrade_finished
+ minecraft:notification/world/upgrade_progress
+ minecraft:notification/world/upgrade_started
```

</details>
</details>
<hr/>