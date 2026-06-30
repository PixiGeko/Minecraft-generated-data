## Comparison with [26.3-snapshot-1](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.3-snapshot-1)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>DataPack version</td><td><pre>108.0</pre></td><td><pre>109.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>89.0</pre></td><td><pre>90.0</pre></td></tr><tr><td>World version</td><td><pre>4998</pre></td><td><pre>4999</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742147</pre></td><td><pre>1073742148</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>com.mojang:authlib</td><td><pre>9.0.75</pre></td><td><pre>10.0.76</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- block_type.txt
+ worldgen/carver_type.txt
- worldgen/carver.txt
```

</details>
<details>
<summary>
block_predicate_type
</summary>

```diff
+ minecraft:height_range
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:block_transformer
```

</details>
<details>
<summary>
int_provider_type
</summary>

```diff
+ minecraft:very_biased_to_bottom
```

</details>
<details>
<summary>
worldgen/block_state_provider_type
</summary>

```diff
+ minecraft:copy_properties_provider
```

</details>
<details>
<summary>
worldgen/feature_type
</summary>

```diff
- minecraft:basalt_columns
- minecraft:basalt_pillar
- minecraft:glowstone_blob
+ minecraft:overlay
+ minecraft:projected_random_patchy_square
+ minecraft:random_neighbor_spread
+ minecraft:single_block_pillar
+ minecraft:stepped_column_cluster
```

</details>
<details>
<summary>
worldgen/placement_modifier_type
</summary>

```diff
+ minecraft:offset
- minecraft:random_offset
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
- universal_tags/block_type.json
+ universal_tags/worldgen/carver_type.json
- universal_tags/worldgen/carver.json
```

</details>
<details>
<summary>
universal_tags/block_predicate_type.json
</summary>

```diff
+ minecraft:height_range
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:block_transformer
```

</details>
<details>
<summary>
universal_tags/int_provider_type.json
</summary>

```diff
+ minecraft:very_biased_to_bottom
```

</details>
<details>
<summary>
universal_tags/worldgen/block_state_provider_type.json
</summary>

```diff
+ minecraft:copy_properties_provider
```

</details>
<details>
<summary>
universal_tags/worldgen/feature_type.json
</summary>

```diff
- minecraft:basalt_columns
- minecraft:basalt_pillar
- minecraft:glowstone_blob
+ minecraft:overlay
+ minecraft:projected_random_patchy_square
+ minecraft:random_neighbor_spread
+ minecraft:single_block_pillar
+ minecraft:stepped_column_cluster
```

</details>
<details>
<summary>
universal_tags/worldgen/placement_modifier_type.json
</summary>

```diff
+ minecraft:offset
- minecraft:random_offset
```

</details>
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
acacia_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:acacia_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>acacia</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
activator_rail
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:powered_rail</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
air
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:air</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 60,
    "id": "minecraft:fire_resistance"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:amethyst</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_cluster
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:amethyst_cluster</pre></td><td><pre>/</pre></td></tr><tr><td>height</td><td><pre>7</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>width</td><td><pre>10</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ancient_debris
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:andesite"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
anvil
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:anvil</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
attached_melon_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:attached_stem</pre></td><td><pre>/</pre></td></tr><tr><td>fruit</td><td><pre>minecraft:melon</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>seed</td><td><pre>minecraft:melon_seeds</pre></td><td><pre>/</pre></td></tr><tr><td>stem</td><td><pre>minecraft:melon_stem</pre></td><td><pre>/</pre></td></tr><tr><td>support_blocks</td><td><pre>minecraft:supports_melon_stem</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
attached_pumpkin_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:attached_stem</pre></td><td><pre>/</pre></td></tr><tr><td>fruit</td><td><pre>minecraft:pumpkin</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>seed</td><td><pre>minecraft:pumpkin_seeds</pre></td><td><pre>/</pre></td></tr><tr><td>stem</td><td><pre>minecraft:pumpkin_stem</pre></td><td><pre>/</pre></td></tr><tr><td>support_blocks</td><td><pre>minecraft:supports_pumpkin_stem</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:azalea</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:untinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle</td><td><pre>{
  "type": "minecraft:tinted_leaves",
  "color": -9399763
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azure_bluet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 220,
    "id": "minecraft:blindness"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bamboo_stalk</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:bamboo_mosaic"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bamboo_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:bamboo_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>bamboo</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrel
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:barrel</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrier
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:barrier</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
basalt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beacon
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:beacon</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bedrock
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beehive
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:beehive</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:beetroot</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_nest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:beehive</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bell
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bell</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
big_dripleaf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:big_dripleaf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
big_dripleaf_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:big_dripleaf_stem</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:birch_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>birch</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:blackstone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>black</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>black</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:black_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>black</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:black_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>black</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>black</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>black</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>black</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:black_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blast_furnace
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:blast_furnace</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:blue_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:blue_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_ice
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:half_transparent</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_orchid
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 7,
    "id": "minecraft:saturation"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:blue_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bookshelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_brain_coral</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_brain_coral_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_brain_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_brain_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewing_stand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:brewing_stand</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>brown</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>brown</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:brown_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>brown</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:brown_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>feature</td><td><pre>minecraft:huge_brown_mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:huge_mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>brown</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>brown</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>brown</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>brown</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:brown_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_column
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bubble_column</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_bubble_coral</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_bubble_coral_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_bubble_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_bubble_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
budding_amethyst
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:budding_amethyst</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bush</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>shape_height</td><td><pre>13</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:cactus</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus_flower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:cactus_flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:cake</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calcite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calibrated_sculk_sensor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:calibrated_sculk_sensor</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
campfire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:campfire</pre></td><td><pre>/</pre></td></tr><tr><td>fire_damage</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>spawn_particles</td><td><pre>true</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:carrot</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cartography_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:cartography_table</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carved_pumpkin
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:jack_o_lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cauldron
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:cauldron</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_air
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:air</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_vines
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:cave_vines</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_vines_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:cave_vines_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain_command_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:command</pre></td><td><pre>/</pre></td></tr><tr><td>automatic</td><td><pre>true</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:untinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle</td><td><pre>{
  "type": "minecraft:cherry_leaves"
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:cherry_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>cherry</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.chest.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.chest.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chipped_anvil
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:anvil</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_bookshelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chiseled_book_shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_cinnabar
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_nether_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_polished_blackstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_quartz_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_red_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_resin_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_sulfur
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_flower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chorus_flower</pre></td><td><pre>/</pre></td></tr><tr><td>plant</td><td><pre>minecraft:chorus_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chorus_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cinnabar
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cinnabar_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cinnabar_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cinnabar_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:cinnabar_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cinnabar_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cinnabar_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cinnabar_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:cinnabar"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cinnabar_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
closed_eyeblossom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:eyeblossom</pre></td><td><pre>/</pre></td></tr><tr><td>open</td><td><pre>false</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 2,
  "min_inclusive": 0
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coarse_dirt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:cobbled_deepslate"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:cobblestone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobweb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:web</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cocoa
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:cocoa</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:command</pre></td><td><pre>/</pre></td></tr><tr><td>automatic</td><td><pre>false</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
comparator
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:comparator</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
composter
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:composter</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
conduit
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:conduit</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_bar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_bulb</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.copper_chest.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.copper_chest.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_golem_statue
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_golem_statue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_grate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>0</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:torch</pre></td><td><pre>/</pre></td></tr><tr><td>particle_options</td><td><pre>minecraft:copper_fire_flame</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_wall_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_torch</pre></td><td><pre>/</pre></td></tr><tr><td>particle_options</td><td><pre>minecraft:copper_fire_flame</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cornflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 100,
    "id": "minecraft:jump_boost"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_tiles
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_nether_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_polished_blackstone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafter
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:crafter</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafting_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:crafting_table</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_heart
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:creaking_heart</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>creeper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>creeper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fungus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nether_fungus</pre></td><td><pre>/</pre></td></tr><tr><td>feature</td><td><pre>minecraft:crimson_fungus_planted</pre></td><td><pre>/</pre></td></tr><tr><td>grows_on</td><td><pre>minecraft:crimson_nylium</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>support_blocks</td><td><pre>minecraft:supports_crimson_fungus</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hyphae
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_nylium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nylium</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nether_roots</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>support_blocks</td><td><pre>minecraft:supports_crimson_roots</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:crimson_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>crimson</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crying_obsidian
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:crying_obsidian</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:cut_copper"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>cyan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>cyan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:cyan_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>cyan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:cyan_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>cyan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>cyan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>cyan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>cyan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:cyan_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
damaged_anvil
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:anvil</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dandelion
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 7,
    "id": "minecraft:saturation"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:dark_oak_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>dark_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:dark_prismarine"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
daylight_detector
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:daylight_detector</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:dry_vegetation</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:base_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
decorated_pot
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:decorated_pot</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:deepslate_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_coal_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 2,
  "min_inclusive": 0
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_copper_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>0</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_diamond_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 7,
  "min_inclusive": 3
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_emerald_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 7,
  "min_inclusive": 3
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_gold_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>0</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_iron_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>0</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_lapis_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 5,
  "min_inclusive": 2
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_redstone_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:redstone_ore</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tiles
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:deepslate_tiles"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
detector_rail
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:detector_rail</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 7,
  "min_inclusive": 3
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:diorite"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt_path
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:path</pre></td><td><pre>/</pre></td></tr><tr><td>base_block</td><td><pre>minecraft:dirt</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dispenser
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:dispenser</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_egg
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:dragon_egg</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>dragon</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>dragon</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_ghast
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:dried_ghast</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dripstone_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dropper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:dropper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 7,
  "min_inclusive": 3
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanting_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:enchantment_table</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ender_chest</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_gateway
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:end_gateway</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_portal
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:end_portal</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_portal_frame
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:end_portal_frame</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:end_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:end_stone_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_bar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_bulb</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.copper_chest.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.copper_chest.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_golem_statue
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_golem_statue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_grate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:exposed_cut_copper"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_lightning_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
farmland
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:farmland</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>turns_into</td><td><pre>minecraft:dirt</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tall_grass</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fire</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firefly_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:firefly_bush</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_fire_coral</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_fire_coral_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_fire_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_fire_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fletching_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:azalea</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:untinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle</td><td><pre>{
  "type": "minecraft:tinted_leaves",
  "color": -9399763
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_pot
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:air</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frogspawn
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:frogspawn</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frosted_ice
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:frosted_ice</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:furnace</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gilded_blackstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:transparent</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:iron_bars</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_lichen
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glow_lichen</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_dandelion
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 7,
    "id": "minecraft:saturation"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>0</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:granite"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grass_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:grass</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gravel
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:colored_falling</pre></td><td><pre>/</pre></td></tr><tr><td>falling_dust_color</td><td><pre>#ff807c7b</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:gray_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:gray_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:gray_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>green</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>green</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:green_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>green</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:green_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>green</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>green</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>green</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>green</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:green_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grindstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:grindstone</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hanging_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:hanging_roots</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hay_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:hay</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_core
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:heavy_core</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_weighted_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weighted_pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>iron</pre></td><td><pre>/</pre></td></tr><tr><td>max_weight</td><td><pre>150</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:honey</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:hopper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_horn_coral</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_horn_coral_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_horn_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_horn_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ice
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ice</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_chiseled_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:infested</pre></td><td><pre>/</pre></td></tr><tr><td>host</td><td><pre>minecraft:chiseled_stone_bricks</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cobblestone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:infested</pre></td><td><pre>/</pre></td></tr><tr><td>host</td><td><pre>minecraft:cobblestone</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cracked_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:infested</pre></td><td><pre>/</pre></td></tr><tr><td>host</td><td><pre>minecraft:cracked_stone_bricks</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:infested_rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>host</td><td><pre>minecraft:deepslate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_mossy_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:infested</pre></td><td><pre>/</pre></td></tr><tr><td>host</td><td><pre>minecraft:mossy_stone_bricks</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:infested</pre></td><td><pre>/</pre></td></tr><tr><td>host</td><td><pre>minecraft:stone</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:infested</pre></td><td><pre>/</pre></td></tr><tr><td>host</td><td><pre>minecraft:stone_bricks</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:iron_bars</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>iron</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>0</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>iron</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jack_o_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:jack_o_lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jigsaw
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:jigsaw</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jukebox
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:jukebox</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:jungle_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>jungle</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
kelp
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:kelp</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
kelp_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:kelp_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ladder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ladder</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 5,
  "min_inclusive": 2
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:amethyst_cluster</pre></td><td><pre>/</pre></td></tr><tr><td>height</td><td><pre>5</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>width</td><td><pre>10</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_fern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:double_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lava
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:liquid</pre></td><td><pre>/</pre></td></tr><tr><td>fluid</td><td><pre>minecraft:lava</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lava_cauldron
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lava_cauldron</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leaf_litter
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:leaf_litter</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lectern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lectern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lever
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lever</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:light</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_lightning_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:light_blue_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:light_blue_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_blue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:light_blue_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:light_gray_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:light_gray_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>light_gray</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:light_gray_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_weighted_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weighted_pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>gold</pre></td><td><pre>/</pre></td></tr><tr><td>max_weight</td><td><pre>15</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lilac
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tall_flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_of_the_valley
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 220,
    "id": "minecraft:poison"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_pad
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lily_pad</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>lime</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>lime</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:lime_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>lime</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:lime_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>lime</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>lime</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>lime</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>lime</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:lime_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lodestone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
loom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:loom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>magenta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>magenta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:magenta_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>magenta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:magenta_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>magenta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>magenta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>magenta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>magenta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:magenta_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:magma</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:mangrove_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_propagule
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:mangrove_propagule</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:mangrove_roots</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:mangrove_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>mangrove</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
medium_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:amethyst_cluster</pre></td><td><pre>/</pre></td></tr><tr><td>height</td><td><pre>4</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>width</td><td><pre>10</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stem</pre></td><td><pre>/</pre></td></tr><tr><td>attached_stem</td><td><pre>minecraft:attached_melon_stem</pre></td><td><pre>/</pre></td></tr><tr><td>fruit</td><td><pre>minecraft:melon</pre></td><td><pre>/</pre></td></tr><tr><td>fruit_support_blocks</td><td><pre>minecraft:supports_melon_stem_fruit</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>seed</td><td><pre>minecraft:melon_seeds</pre></td><td><pre>/</pre></td></tr><tr><td>stem_support_blocks</td><td><pre>minecraft:supports_melon_stem</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:mossy_cobblestone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:mossy_stone_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bonemealable_feature_placer</pre></td><td><pre>/</pre></td></tr><tr><td>feature</td><td><pre>minecraft:moss_patch_bonemeal</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:carpet</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moving_piston
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:moving_piston</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:mud</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
muddy_mangrove_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:mud_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:huge_mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mycelium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:mycelium</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherrack
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:netherrack</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:nether_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_gold_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 1,
  "min_inclusive": 0
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_portal
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nether_portal</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_quartz_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:drop_experience</pre></td><td><pre>/</pre></td></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 5,
  "min_inclusive": 2
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_sprouts
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nether_sprouts</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nether_wart</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
note_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:note</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:oak_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
observer
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:observer</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
obsidian
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ochre_froglight
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
open_eyeblossom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:eyeblossom</pre></td><td><pre>/</pre></td></tr><tr><td>open</td><td><pre>true</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>orange</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>orange</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:orange_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>orange</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:orange_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_poplar_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:untinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>{
  "ambient_sound": "minecraft:block.poplar_leaves.ambient",
  "satisfying_blocks": "minecraft:required_for_poplar_leaf_ambience"
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle</td><td><pre>{
  "type": "minecraft:orange_poplar_leaves"
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>orange</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>orange</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>orange</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 140,
    "id": "minecraft:weakness"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>orange</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:orange_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxeye_daisy
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 140,
    "id": "minecraft:regeneration"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_bar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_bulb</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.copper_chest_oxidized.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.copper_chest_oxidized.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_golem_statue
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_golem_statue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_grate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:oxidized_cut_copper"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_lightning_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_ice
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_mud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_hanging_moss
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:hanging_moss</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bonemealable_feature_placer</pre></td><td><pre>/</pre></td></tr><tr><td>feature</td><td><pre>minecraft:pale_moss_patch_bonemeal</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:mossy_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:untinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle</td><td><pre>{
  "type": "minecraft:pale_oak_leaves"
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:pale_oak_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>pale_oak</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pearlescent_froglight
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
peony
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tall_flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
petrified_oak_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>piglin</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:piglinwallskull</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>pink</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>pink</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:pink_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>pink</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:pink_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_petals
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_bed</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>shape_height</td><td><pre>3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>pink</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>pink</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>pink</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 140,
    "id": "minecraft:weakness"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>pink</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:pink_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piston
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:piston_base</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>sticky</td><td><pre>false</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piston_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:piston_head</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_crop
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pitcher_crop</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:double_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
player_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:player_head</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
player_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:player_wall_head</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
podzol
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:snowy_dirt</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pointed_dripstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pointed_dripstone</pre></td><td><pre>/</pre></td></tr><tr><td>block_to_grow_on</td><td><pre>{
  "Name": "minecraft:dripstone_block"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_andesite"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_basalt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_blackstone_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>stone</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>20</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>polished_blackstone</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_blackstone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_cinnabar
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_cinnabar_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_cinnabar_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_cinnabar"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_cinnabar_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_deepslate"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_diorite"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_granite"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_sulfur
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_sulfur_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_sulfur_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_sulfur"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_sulfur_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:polished_tuff"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:poplar_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>poplar</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poplar_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poppy
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 100,
    "id": "minecraft:night_vision"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potatoes
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:potato</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potent_sulfur
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:potent_sulfur</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_acacia_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:acacia_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_allium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:allium</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_azalea_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:azalea</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_azure_bluet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:azure_bluet</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_bamboo
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:bamboo</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_birch_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:birch_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_blue_orchid
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:blue_orchid</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_brown_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:brown_mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_cactus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:cactus</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_cherry_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:cherry_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_closed_eyeblossom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:closed_eyeblossom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_cornflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:cornflower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_crimson_fungus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:crimson_fungus</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_crimson_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:crimson_roots</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_dandelion
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:dandelion</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_dark_oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:dark_oak_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_dead_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:dead_bush</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_fern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:fern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_flowering_azalea_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:flowering_azalea</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_golden_dandelion
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:golden_dandelion</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_jungle_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:jungle_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_lily_of_the_valley
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:lily_of_the_valley</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_mangrove_propagule
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:mangrove_propagule</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:oak_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_open_eyeblossom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:open_eyeblossom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_orange_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:orange_tulip</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_oxeye_daisy
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:oxeye_daisy</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_pale_oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:pale_oak_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_pink_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:pink_tulip</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_poplar_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:poplar_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_poppy
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:poppy</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_red_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:red_mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_red_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:red_tulip</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_spruce_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:spruce_sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_torchflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:torchflower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_warped_fungus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:warped_fungus</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_warped_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:warped_roots</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_white_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:white_tulip</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_wither_rose
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_pot</pre></td><td><pre>/</pre></td></tr><tr><td>potted</td><td><pre>minecraft:wither_rose</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powder_snow
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:powder_snow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powder_snow_cauldron
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:layered_cauldron</pre></td><td><pre>/</pre></td></tr><tr><td>interactions</td><td><pre>powder_snow</pre></td><td><pre>/</pre></td></tr><tr><td>precipitation</td><td><pre>snow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powered_rail
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:powered_rail</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:prismarine_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:prismarine"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pumpkin</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stem</pre></td><td><pre>/</pre></td></tr><tr><td>attached_stem</td><td><pre>minecraft:attached_pumpkin_stem</pre></td><td><pre>/</pre></td></tr><tr><td>fruit</td><td><pre>minecraft:pumpkin</pre></td><td><pre>/</pre></td></tr><tr><td>fruit_support_blocks</td><td><pre>minecraft:supports_pumpkin_stem_fruit</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>seed</td><td><pre>minecraft:pumpkin_seeds</pre></td><td><pre>/</pre></td></tr><tr><td>stem_support_blocks</td><td><pre>minecraft:supports_pumpkin_stem</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>purple</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>purple</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:purple_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>purple</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:purple_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>purple</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>purple</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>purple</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>purple</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:purple_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_pillar
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:purpur_block"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_pillar
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:quartz_block"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rail
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rail</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:powered</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_lamp
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:redstone_lamp</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:redstone_ore</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:redstone_torch</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_wall_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:redstone_wall_torch</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_wire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:redstone_wire</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>red</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>red</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:red_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>red</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:red_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>feature</td><td><pre>minecraft:huge_red_mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:huge_mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:red_nether_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_poplar_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:untinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>{
  "ambient_sound": "minecraft:block.poplar_leaves.ambient",
  "satisfying_blocks": "minecraft:required_for_poplar_leaf_ambience"
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle</td><td><pre>{
  "type": "minecraft:red_poplar_leaves"
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sand</pre></td><td><pre>/</pre></td></tr><tr><td>falling_dust_color</td><td><pre>#00a95821</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:red_sandstone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_shrub
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bush</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>shape_height</td><td><pre>13</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>red</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>red</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>red</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 140,
    "id": "minecraft:weakness"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>red</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:red_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
reinforced_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeater
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:repeater</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeating_command_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:command</pre></td><td><pre>/</pre></td></tr><tr><td>automatic</td><td><pre>false</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:resin_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_clump
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:multiface</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
respawn_anchor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:respawn_anchor</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rooted_dirt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rooted_dirt</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rose_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tall_flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sand</pre></td><td><pre>/</pre></td></tr><tr><td>falling_dust_color</td><td><pre>#00dbd3a0</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:sandstone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scaffolding
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:scaffolding</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sculk</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_catalyst
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sculk_catalyst</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_sensor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sculk_sensor</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_shrieker
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sculk_shrieker</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_vein
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sculk_vein</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
seagrass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:seagrass</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_pickle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sea_pickle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shelf_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf_mushroom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_dry_grass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:short_dry_grass</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_grass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tall_grass</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shroomlight
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_skull
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>skeleton</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_wall_skull
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>skeleton</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slime</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:amethyst_cluster</pre></td><td><pre>/</pre></td></tr><tr><td>height</td><td><pre>3</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>width</td><td><pre>8</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_dripleaf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:small_dripleaf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smithing_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:smithing_table</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smoker
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:smoker</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_basalt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:smooth_quartz"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:smooth_red_sandstone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:smooth_sandstone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_egg
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sniffer_egg</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:snow_layer</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_campfire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:campfire</pre></td><td><pre>/</pre></td></tr><tr><td>fire_damage</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>spawn_particles</td><td><pre>false</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_fire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:soul_fire</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:soul_sand</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_soil
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:torch</pre></td><td><pre>/</pre></td></tr><tr><td>particle_options</td><td><pre>minecraft:soul_fire_flame</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_wall_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_torch</pre></td><td><pre>/</pre></td></tr><tr><td>particle_options</td><td><pre>minecraft:soul_fire_flame</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spawner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:spawner</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sponge
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sponge</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spore_blossom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:spore_blossom</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:leaves</pre></td><td><pre>/</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>{
  "chance": 0,
  "nearby_same_leaves_required": 0,
  "nearby_satisfying_blocks_required": 0
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sapling</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>tree</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:spruce_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>spruce</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sticky_piston
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:piston_base</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>sticky</td><td><pre>true</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stonecutter
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stonecutter</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:stone_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>stone</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>20</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>stone</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:stone"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_bamboo_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_hyphae
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_poplar_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_poplar_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_hyphae
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:structure</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_void
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:structure_void</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar_cane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sugar_cane</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:sulfur_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur_spike
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sulfur_spike</pre></td><td><pre>/</pre></td></tr><tr><td>block_to_grow_on</td><td><pre>{
  "Name": "minecraft:sulfur"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:sulfur"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sulfur_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sunflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tall_flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_gravel
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:brushable</pre></td><td><pre>/</pre></td></tr><tr><td>brush_completed_sound</td><td><pre>minecraft:item.brush.brushing.gravel</pre></td><td><pre>/</pre></td></tr><tr><td>brush_sound</td><td><pre>minecraft:item.brush.brushing.gravel</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>turns_into</td><td><pre>minecraft:gravel</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:brushable</pre></td><td><pre>/</pre></td></tr><tr><td>brush_completed_sound</td><td><pre>minecraft:item.brush.brushing.sand</pre></td><td><pre>/</pre></td></tr><tr><td>brush_sound</td><td><pre>minecraft:item.brush.brushing.sand</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>turns_into</td><td><pre>minecraft:sand</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sweet_berry_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:sweet_berry_bush</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_dry_grass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tall_dry_grass</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_grass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:double_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_seagrass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tall_seagrass</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
target
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:target</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
test_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:test</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
test_instance_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:test_instance</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tinted_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tinted_glass</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tnt</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:torch</pre></td><td><pre>/</pre></td></tr><tr><td>particle_options</td><td><pre>minecraft:flame</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 100,
    "id": "minecraft:night_vision"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower_crop
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:torchflower_crop</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trapped_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapped_chest</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_spawner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trial_spawner</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tripwire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:tripwire</pre></td><td><pre>/</pre></td></tr><tr><td>hook</td><td><pre>minecraft:tripwire_hook</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tripwire_hook
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trip_wire_hook</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_plant</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_tube_coral</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_tube_coral_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_tube_coral_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>dead</td><td><pre>minecraft:dead_tube_coral_wall_fan</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:tuff_bricks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:tuff"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_egg
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:turtle_egg</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
twisting_vines
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:twisting_vines</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
twisting_vines_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:twisting_vines_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vault
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:vault</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
verdant_froglight
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vine
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:vine</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
void_air
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:air</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wall_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_torch</pre></td><td><pre>/</pre></td></tr><tr><td>particle_options</td><td><pre>minecraft:flame</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:button</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>30</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:fence_gate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nether_fungus</pre></td><td><pre>/</pre></td></tr><tr><td>feature</td><td><pre>minecraft:warped_fungus_planted</pre></td><td><pre>/</pre></td></tr><tr><td>grows_on</td><td><pre>minecraft:warped_nylium</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>support_blocks</td><td><pre>minecraft:supports_warped_fungus</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:ceiling_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hyphae
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_nylium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nylium</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:pressure_plate</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:nether_roots</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>support_blocks</td><td><pre>minecraft:supports_warped_roots</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_shelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shelf</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:standing_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:warped_planks"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:rotated_pillar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_hanging_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_sign</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>wood_type</td><td><pre>warped</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wart_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
water
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:liquid</pre></td><td><pre>/</pre></td></tr><tr><td>fluid</td><td><pre>minecraft:water</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
water_cauldron
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:layered_cauldron</pre></td><td><pre>/</pre></td></tr><tr><td>interactions</td><td><pre>water</pre></td><td><pre>/</pre></td></tr><tr><td>precipitation</td><td><pre>rain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:iron_bars</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_bulb_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.copper_chest.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.copper_chest.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_golem_statue
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_golem_statue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>unaffected</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:waterlogged_transparent</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:waxed_cut_copper"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:iron_bars</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_bulb_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.copper_chest.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.copper_chest.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_golem_statue
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_golem_statue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>exposed</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:waterlogged_transparent</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:waxed_exposed_cut_copper"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lightning_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lightning_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:iron_bars</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_bulb_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.copper_chest_oxidized.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.copper_chest_oxidized.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_golem_statue
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_golem_statue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>oxidized</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:waterlogged_transparent</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:waxed_oxidized_cut_copper"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lightning_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:iron_bars</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_bulb_block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.copper_chest_weathered.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.copper_chest_weathered.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_golem_statue
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:copper_golem_statue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:waterlogged_transparent</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:waxed_weathered_cut_copper"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:lightning_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_bar</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_bulb</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_chain</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_chest</pre></td><td><pre>/</pre></td></tr><tr><td>close_sound</td><td><pre>minecraft:block.copper_chest_weathered.close</pre></td><td><pre>/</pre></td></tr><tr><td>open_sound</td><td><pre>minecraft:block.copper_chest_weathered.open</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_door</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_golem_statue
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_golem_statue</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_grate</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_lantern</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trapdoor</pre></td><td><pre>/</pre></td></tr><tr><td>block_set_type</td><td><pre>copper</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_full</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:weathered_cut_copper"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_lightning_rod</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>weathering_state</td><td><pre>weathered</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weeping_vines
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weeping_vines</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weeping_vines_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weeping_vines_plant</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wet_sponge
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wet_sponge</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:crop</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>white</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>white</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:white_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>white</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:white_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>white</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>white</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>white</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 140,
    "id": "minecraft:weakness"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>white</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:white_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wildflowers
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:flower_bed</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>shape_height</td><td><pre>3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_rose
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wither_rose</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>[
  {
    "duration": 140,
    "id": "minecraft:wither"
  }
]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_skull
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wither_skull</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_wall_skull
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wither_wall_skull</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>yellow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:bed</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>yellow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:candle_cake</pre></td><td><pre>/</pre></td></tr><tr><td>candle</td><td><pre>minecraft:yellow_candle</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wool_carpet</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>yellow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:concrete_powder</pre></td><td><pre>/</pre></td></tr><tr><td>concrete</td><td><pre>minecraft:yellow_concrete</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:glazed_terracotta</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_poplar_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:untinted_particle_leaves</pre></td><td><pre>/</pre></td></tr><tr><td>ambient_leaves_block_sound_player</td><td><pre>{
  "ambient_sound": "minecraft:block.poplar_leaves.ambient",
  "satisfying_blocks": "minecraft:required_for_poplar_leaf_ambience"
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle</td><td><pre>{
  "type": "minecraft:yellow_poplar_leaves"
}</pre></td><td><pre>/</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:shulker_box</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>yellow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>yellow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stained_glass_pane</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>yellow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_banner</pre></td><td><pre>/</pre></td></tr><tr><td>color</td><td><pre>yellow</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:block</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wool_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:slab</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wool_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:stair</pre></td><td><pre>/</pre></td></tr><tr><td>base_state</td><td><pre>{
  "Name": "minecraft:yellow_wool"
}</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>zombie</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:wall_skull</pre></td><td><pre>/</pre></td></tr><tr><td>kind</td><td><pre>zombie</pre></td><td><pre>/</pre></td></tr><tr><td>properties</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
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
+ black_carpet.json
+ blue_carpet.json
+ brown_carpet.json
+ cyan_carpet.json
+ gray_carpet.json
+ green_carpet.json
+ light_blue_carpet.json
+ light_gray_carpet.json
+ lime_carpet.json
+ magenta_carpet.json
+ orange_carpet.json
+ pink_carpet.json
+ purple_carpet.json
+ red_carpet.json
+ white_carpet.json
+ yellow_carpet.json
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
- minecraft:block_type
+ minecraft:worldgen/carver_type
- minecraft:worldgen/configured_carver
```

</details>
<details>
<summary>
[registries] minecraft:worldgen/carver
</summary>
<table><tr><th></th><th align="left">26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr><tr><td>elements</td><td><pre>false</pre></td><td><pre>true</pre></td></tr><tr><td>stable</td><td><pre>true</pre></td><td><pre>false</pre></td></tr></table>
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
+ debug.improvedTransparency.off: Improved transparency: disabled
+ debug.improvedTransparency.on: Improved transparency: enabled
+ key.debug.improvedTransparency: Toggle Improved Transparency
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.3-snapshot-1</th><th>26.3-snapshot-2</th></tr>
<tr><th align="left"><div style="width:290px">options.improvedTransparency.tooltip</div></th><td>An experimental approach that uses screen shaders for drawing weather, clouds, and particles behind translucent blocks and water.

This will impact GPU performance.</td><td>An experimental approach that uses an order-independent transparency algorithm to avoid graphical issues normally present when looking through multiple layers of translucent objects.

This will impact performance.</td></tr>
</table>
<br/>
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
+ minecraft/advancement/recipes/decorations/black_carpet.json
+ minecraft/advancement/recipes/decorations/blue_carpet.json
+ minecraft/advancement/recipes/decorations/brown_carpet.json
+ minecraft/advancement/recipes/decorations/cyan_carpet.json
+ minecraft/advancement/recipes/decorations/gray_carpet.json
+ minecraft/advancement/recipes/decorations/green_carpet.json
+ minecraft/advancement/recipes/decorations/light_blue_carpet.json
+ minecraft/advancement/recipes/decorations/light_gray_carpet.json
+ minecraft/advancement/recipes/decorations/lime_carpet.json
+ minecraft/advancement/recipes/decorations/magenta_carpet.json
+ minecraft/advancement/recipes/decorations/orange_carpet.json
+ minecraft/advancement/recipes/decorations/pink_carpet.json
+ minecraft/advancement/recipes/decorations/purple_carpet.json
+ minecraft/advancement/recipes/decorations/red_carpet.json
+ minecraft/advancement/recipes/decorations/white_carpet.json
+ minecraft/advancement/recipes/decorations/yellow_carpet.json
+ minecraft/loot_table/till/rooted_dirt.json
+ minecraft/recipe/black_carpet.json
+ minecraft/recipe/blue_carpet.json
+ minecraft/recipe/brown_carpet.json
+ minecraft/recipe/cyan_carpet.json
+ minecraft/recipe/gray_carpet.json
+ minecraft/recipe/green_carpet.json
+ minecraft/recipe/light_blue_carpet.json
+ minecraft/recipe/light_gray_carpet.json
+ minecraft/recipe/lime_carpet.json
+ minecraft/recipe/magenta_carpet.json
+ minecraft/recipe/orange_carpet.json
+ minecraft/recipe/pink_carpet.json
+ minecraft/recipe/purple_carpet.json
+ minecraft/recipe/red_carpet.json
+ minecraft/recipe/white_carpet.json
+ minecraft/recipe/yellow_carpet.json
+ minecraft/tags/block/cannot_place_basalt_pillar_on.json
- minecraft/tags/block/nether_carver_replaceables.json
- minecraft/tags/block/overworld_carver_replaceables.json
+ minecraft/tags/block/turns_into_dirt_path.json
+ minecraft/tags/block/turns_into_farmland.json
+ minecraft/tags/item/dowses_campfires.json
+ minecraft/villager_trade/wandering_trader/emerald_poplar_log.json
+ minecraft/worldgen/carver/canyon.json
+ minecraft/worldgen/carver/cave_extra_underground.json
+ minecraft/worldgen/carver/cave.json
+ minecraft/worldgen/carver/nether_cave.json
- minecraft/worldgen/configured_carver/canyon.json
- minecraft/worldgen/configured_carver/cave_extra_underground.json
- minecraft/worldgen/configured_carver/cave.json
- minecraft/worldgen/configured_carver/nether_cave.json
+ minecraft/worldgen/density_function/overworld_large_biomes/temperature.json
+ minecraft/worldgen/density_function/overworld_large_biomes/vegetation.json
+ minecraft/worldgen/density_function/overworld/temperature.json
+ minecraft/worldgen/density_function/overworld/vegetation.json
- minecraft/worldgen/material_condition/above_water.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/post_effect/transparency.json
+ minecraft/shaders/core/clouds.fsh
+ minecraft/shaders/core/clouds.vsh
+ minecraft/shaders/core/oit_composite.fsh
- minecraft/shaders/core/rendertype_clouds.fsh
- minecraft/shaders/core/rendertype_clouds.vsh
- minecraft/shaders/core/rendertype_world_border.fsh
- minecraft/shaders/core/rendertype_world_border.vsh
+ minecraft/shaders/core/world_border.fsh
+ minecraft/shaders/core/world_border.vsh
+ minecraft/shaders/include/oit_add_transmittance.glsl
+ minecraft/shaders/include/oit_common.glsl
+ minecraft/shaders/include/oit_depth_bounds.glsl
+ minecraft/shaders/include/oit_depth_sample.glsl
+ minecraft/shaders/include/oit_sample.glsl
+ minecraft/shaders/include/oit.glsl
+ minecraft/shaders/include/texture_sampling.glsl
- minecraft/shaders/post/transparency.fsh
+ minecraft/textures/block/destroy_oit_stage_0.png
+ minecraft/textures/block/destroy_oit_stage_1.png
+ minecraft/textures/block/destroy_oit_stage_2.png
+ minecraft/textures/block/destroy_oit_stage_3.png
+ minecraft/textures/block/destroy_oit_stage_4.png
+ minecraft/textures/block/destroy_oit_stage_5.png
+ minecraft/textures/block/destroy_oit_stage_6.png
+ minecraft/textures/block/destroy_oit_stage_7.png
+ minecraft/textures/block/destroy_oit_stage_8.png
+ minecraft/textures/block/destroy_oit_stage_9.png
+ minecraft/textures/block/shelf_mushroom_particle.png
```

</details>
</details>
<hr/>