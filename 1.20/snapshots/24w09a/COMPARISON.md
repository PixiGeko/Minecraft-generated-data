## Comparison with [24w07a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w07a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>DataPack version</td><td><pre>32</pre></td><td><pre>33</pre></td></tr><tr><td>ResourcePack version</td><td><pre>26</pre></td><td><pre>28</pre></td></tr><tr><td>World version</td><td><pre>3817</pre></td><td><pre>3819</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742001</pre></td><td><pre>1073742002</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>com.github.oshi:oshi-core</td><td><pre>6.4.5</pre></td><td><pre>6.4.10</pre></td></tr><tr><td>com.mojang:logging</td><td><pre>1.1.1</pre></td><td><pre>1.2.7</pre></td></tr><tr><td>commons-io:commons-io</td><td><pre>2.13.0</pre></td><td><pre>2.15.1</pre></td></tr><tr><td>net.java.dev.jna:jna-platform</td><td><pre>5.13.0</pre></td><td><pre>5.14.0</pre></td></tr><tr><td>net.java.dev.jna:jna</td><td><pre>5.13.0</pre></td><td><pre>5.14.0</pre></td></tr><tr><td>org.apache.commons:commons-compress</td><td><pre>1.22</pre></td><td><pre>1.26.0</pre></td></tr><tr><td>org.apache.commons:commons-lang3</td><td><pre>3.13.0</pre></td><td><pre>3.14.0</pre></td></tr><tr><td>org.apache.logging.log4j:log4j-api</td><td><pre>2.19.0</pre></td><td><pre>2.22.1</pre></td></tr><tr><td>org.apache.logging.log4j:log4j-core</td><td><pre>2.19.0</pre></td><td><pre>2.22.1</pre></td></tr><tr><td>org.apache.logging.log4j:log4j-slf4j2-impl</td><td><pre>2.19.0</pre></td><td><pre>2.22.1</pre></td></tr><tr><td>org.slf4j:slf4j-api</td><td><pre>2.0.7</pre></td><td><pre>2.0.9</pre></td></tr></table>
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
+ data_component_type.txt
```

</details>
<details>
<summary>
loot_function_type
</summary>

```diff
+ minecraft:copy_components
+ minecraft:copy_custom_data
- minecraft:copy_nbt
+ minecraft:set_components
+ minecraft:set_custom_data
- minecraft:set_nbt
```

</details>
<details>
<summary>
potion
</summary>

```diff
- minecraft:empty
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.wet_sponge.dries
+ minecraft:entity.bogged.shear
+ minecraft:entity.donkey.jump
+ minecraft:entity.mule.jump
+ minecraft:item.wolf_armor.break
+ minecraft:item.wolf_armor.crack
+ minecraft:item.wolf_armor.damage
+ minecraft:item.wolf_armor.repair
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
+ universal_tags/data_component_type.json
```

</details>
<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
+ minecraft:copy_components
+ minecraft:copy_custom_data
- minecraft:copy_nbt
+ minecraft:set_components
+ minecraft:set_custom_data
- minecraft:set_nbt
```

</details>
<details>
<summary>
universal_tags/potion.json
</summary>

```diff
- minecraft:empty
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.wet_sponge.dries
+ minecraft:entity.bogged.shear
+ minecraft:entity.donkey.jump
+ minecraft:entity.mule.jump
+ minecraft:item.wolf_armor.break
+ minecraft:item.wolf_armor.crack
+ minecraft:item.wolf_armor.damage
+ minecraft:item.wolf_armor.repair
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

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>tree</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:acacia_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>acacia</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
activator_rail
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:powered_rail</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
air
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:air</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 80,
    "id": "minecraft:fire_resistance"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:amethyst</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_cluster
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:amethyst_cluster</pre></td></tr><tr><td>aabb_offset</td><td><pre>/</pre></td><td><pre>3</pre></td></tr><tr><td>height</td><td><pre>/</pre></td><td><pre>7</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ancient_debris
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:andesite"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
anvil
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:anvil</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
attached_melon_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:attached_stem</pre></td></tr><tr><td>fruit</td><td><pre>/</pre></td><td><pre>minecraft:melon</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>seed</td><td><pre>/</pre></td><td><pre>minecraft:melon_seeds</pre></td></tr><tr><td>stem</td><td><pre>/</pre></td><td><pre>minecraft:melon_stem</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
attached_pumpkin_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:attached_stem</pre></td></tr><tr><td>fruit</td><td><pre>/</pre></td><td><pre>minecraft:pumpkin</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>seed</td><td><pre>/</pre></td><td><pre>minecraft:pumpkin_seeds</pre></td></tr><tr><td>stem</td><td><pre>/</pre></td><td><pre>minecraft:pumpkin_stem</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:azalea</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azure_bluet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "id": "minecraft:blindness"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bamboo_stalk</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:bamboo_mosaic"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bamboo_sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:bamboo_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>bamboo</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrel
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:barrel</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrier
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:barrier</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
basalt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beacon
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:beacon</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bedrock
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beehive
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:beehive</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:beetroot</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_nest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:beehive</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bell
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bell</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
big_dripleaf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:big_dripleaf</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
big_dripleaf_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:big_dripleaf_stem</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>tree</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:birch_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>birch</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:blackstone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>black</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>black</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:black_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>black</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:black_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>black</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>black</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>black</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>black</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blast_furnace
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:blast_furnace</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:blue_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:blue_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_ice
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:half_transparent</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_orchid
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 140,
    "id": "minecraft:saturation"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bookshelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_plant</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_brain_coral</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_brain_coral_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_brain_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_wall_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_brain_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewing_stand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:brewing_stand</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>brown</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>brown</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:brown_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>brown</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:brown_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:mushroom</pre></td></tr><tr><td>feature</td><td><pre>/</pre></td><td><pre>minecraft:huge_brown_mushroom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:huge_mushroom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>brown</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>brown</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>brown</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>brown</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_column
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bubble_column</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_plant</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_bubble_coral</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_bubble_coral_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_bubble_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_wall_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_bubble_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
budding_amethyst
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:budding_amethyst</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:cactus</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:cake</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calcite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calibrated_sculk_sensor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:calibrated_sculk_sensor</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
campfire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:campfire</pre></td></tr><tr><td>fire_damage</td><td><pre>/</pre></td><td><pre>1</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>spawn_particles</td><td><pre>/</pre></td><td><pre>true</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:carrot</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cartography_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:cartography_table</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carved_pumpkin
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:carved_pumpkin</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cauldron
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:cauldron</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_air
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:air</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_vines
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:cave_vines</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_vines_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:cave_vines_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:chain</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain_command_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:command</pre></td></tr><tr><td>automatic</td><td><pre>/</pre></td><td><pre>true</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:cherry_leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>tree</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:cherry_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>cherry</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:chest</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chipped_anvil
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:anvil</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_bookshelf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:chiseled_book_shelf</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_nether_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_polished_blackstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_quartz_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_red_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_flower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:chorus_flower</pre></td></tr><tr><td>plant</td><td><pre>/</pre></td><td><pre>minecraft:chorus_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:chorus_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 2,
    "min_inclusive": 0
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coarse_dirt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:cobbled_deepslate"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:cobblestone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobweb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:web</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cocoa
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:cocoa</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:command</pre></td></tr><tr><td>automatic</td><td><pre>/</pre></td><td><pre>false</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
comparator
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:comparator</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
composter
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:composter</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
conduit
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:conduit</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_bulb</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_grate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>0</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_trap_door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cornflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 120,
    "id": "minecraft:jump_boost"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_tiles
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_nether_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_polished_blackstone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafter
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:crafter</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafting_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:crafting_table</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>creeper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>creeper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fungus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fungus</pre></td></tr><tr><td>feature</td><td><pre>/</pre></td><td><pre>minecraft:crimson_fungus_planted</pre></td></tr><tr><td>grows_on</td><td><pre>/</pre></td><td><pre>minecraft:crimson_nylium</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hyphae
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_nylium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:nylium</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:roots</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:crimson_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>crimson</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crying_obsidian
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:crying_obsidian</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:cut_copper"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>unaffected</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>cyan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>cyan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:cyan_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>cyan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:cyan_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>cyan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>cyan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>cyan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>cyan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
damaged_anvil
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:anvil</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dandelion
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 140,
    "id": "minecraft:saturation"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>tree</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:dark_oak_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>dark_oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:dark_prismarine"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
daylight_detector
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:daylight_detector</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:dead_bush</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:base_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
decorated_pot
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:decorated_pot</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:deepslate_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_coal_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 2,
    "min_inclusive": 0
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_copper_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>0</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_diamond_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 7,
    "min_inclusive": 3
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_emerald_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 7,
    "min_inclusive": 3
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_gold_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>0</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_iron_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>0</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_lapis_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 5,
    "min_inclusive": 2
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_redstone_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:redstone_ore</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tiles
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:deepslate_tiles"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
detector_rail
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:detector_rail</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 7,
    "min_inclusive": 3
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:diorite"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt_path
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:dirt_path</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dispenser
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:dispenser</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_egg
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:dragon_egg</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>dragon</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>dragon</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dripstone_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dropper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:dropper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 7,
    "min_inclusive": 3
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanting_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:enchantment_table</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ender_chest</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_gateway
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:end_gateway</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_portal
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:end_portal</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_portal_frame
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:end_portal_frame</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:end_rod</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:end_stone_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_bulb</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_grate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_trap_door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:exposed_cut_copper"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>exposed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
farmland
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:farm</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tall_grass</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fire</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_plant</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_fire_coral</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_fire_coral_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_fire_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_wall_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_fire_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fletching_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fletching_table</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:azalea</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_pot
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:air</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frogspawn
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:frogspawn</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frosted_ice
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:frosted_ice</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:furnace</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gilded_blackstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:transparent</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:iron_bars</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_lichen
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glow_lichen</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>0</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:granite"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grass_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:grass</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gravel
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:colored_falling</pre></td></tr><tr><td>falling_dust_color</td><td><pre>/</pre></td><td><pre>#FF807C7B</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:gray_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:gray_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>green</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>green</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:green_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>green</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:green_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>green</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>green</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>green</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>green</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grindstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:grindstone</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hanging_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:hanging_roots</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hay_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:hay</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_weighted_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weighted_pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>iron</pre></td></tr><tr><td>max_weight</td><td><pre>/</pre></td><td><pre>150</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:honey</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:hopper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_plant</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_horn_coral</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_horn_coral_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_horn_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_wall_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_horn_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ice
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ice</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_chiseled_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:infested</pre></td></tr><tr><td>host</td><td><pre>/</pre></td><td><pre>minecraft:chiseled_stone_bricks</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cobblestone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:infested</pre></td></tr><tr><td>host</td><td><pre>/</pre></td><td><pre>minecraft:cobblestone</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cracked_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:infested</pre></td></tr><tr><td>host</td><td><pre>/</pre></td><td><pre>minecraft:cracked_stone_bricks</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:infested_rotated_pillar</pre></td></tr><tr><td>host</td><td><pre>/</pre></td><td><pre>minecraft:deepslate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_mossy_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:infested</pre></td></tr><tr><td>host</td><td><pre>/</pre></td><td><pre>minecraft:mossy_stone_bricks</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:infested</pre></td></tr><tr><td>host</td><td><pre>/</pre></td><td><pre>minecraft:stone</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:infested</pre></td></tr><tr><td>host</td><td><pre>/</pre></td><td><pre>minecraft:stone_bricks</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_bars
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:iron_bars</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>iron</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>0</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>iron</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jack_o_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:jack_o_lantern</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jigsaw
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:jigsaw</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jukebox
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:jukebox</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>tree</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:jungle_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>jungle</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
kelp
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:kelp</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
kelp_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:kelp_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ladder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ladder</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:lantern</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 5,
    "min_inclusive": 2
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:amethyst_cluster</pre></td></tr><tr><td>aabb_offset</td><td><pre>/</pre></td><td><pre>3</pre></td></tr><tr><td>height</td><td><pre>/</pre></td><td><pre>5</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_fern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:double_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lava
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:liquid</pre></td></tr><tr><td>fluid</td><td><pre>/</pre></td><td><pre>minecraft:lava</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lava_cauldron
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:lava_cauldron</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lectern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:lectern</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lever
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:lever</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:light</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lightning_rod
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:lightning_rod</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:light_blue_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:light_blue_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_blue</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:light_gray_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:light_gray_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>light_gray</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_weighted_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weighted_pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>gold</pre></td></tr><tr><td>max_weight</td><td><pre>/</pre></td><td><pre>15</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lilac
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tall_flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_of_the_valley
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 240,
    "id": "minecraft:poison"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_pad
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:waterlily</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>lime</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>lime</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:lime_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>lime</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:lime_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>lime</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>lime</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>lime</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>lime</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lodestone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
loom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:loom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>magenta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>magenta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:magenta_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>magenta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:magenta_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>magenta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>magenta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>magenta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>magenta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:magma</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:mangrove_leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_propagule
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:mangrove_propagule</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>tree</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:mangrove_roots</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:mangrove_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>mangrove</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
medium_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:amethyst_cluster</pre></td></tr><tr><td>aabb_offset</td><td><pre>/</pre></td><td><pre>3</pre></td></tr><tr><td>height</td><td><pre>/</pre></td><td><pre>4</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stem</pre></td></tr><tr><td>attached_stem</td><td><pre>/</pre></td><td><pre>minecraft:attached_melon_stem</pre></td></tr><tr><td>fruit</td><td><pre>/</pre></td><td><pre>minecraft:melon</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>seed</td><td><pre>/</pre></td><td><pre>minecraft:melon_seeds</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:mossy_cobblestone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:mossy_stone_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:moss</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:carpet</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moving_piston
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:moving_piston</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:mud</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
muddy_mangrove_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:mud_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:huge_mushroom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mycelium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:mycelium</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherrack
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:netherrack</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:nether_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_gold_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 1,
    "min_inclusive": 0
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_portal
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:nether_portal</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_quartz_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:drop_experience</pre></td></tr><tr><td>experience</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 5,
    "min_inclusive": 2
  }
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_sprouts
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:nether_sprouts</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:nether_wart</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
note_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:note</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>tree</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:oak_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>oak</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
observer
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:observer</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
obsidian
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ochre_froglight
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>orange</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>orange</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:orange_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>orange</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:orange_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>orange</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>orange</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>orange</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 180,
    "id": "minecraft:weakness"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>orange</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxeye_daisy
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "id": "minecraft:regeneration"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_bulb</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_grate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_trap_door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:oxidized_cut_copper"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>oxidized</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_ice
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_mud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pearlescent_froglight
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
peony
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tall_flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
petrified_oak_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>piglin</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:piglinwallskull</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>pink</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>pink</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:pink_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>pink</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:pink_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_petals
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pink_petals</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>pink</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>pink</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>pink</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 180,
    "id": "minecraft:weakness"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>pink</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piston
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:piston_base</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>sticky</td><td><pre>/</pre></td><td><pre>false</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piston_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:piston_head</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_crop
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pitcher_crop</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:double_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
player_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:player_head</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
player_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:player_wall_head</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
podzol
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:snowy_dirt</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pointed_dripstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pointed_dripstone</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:polished_andesite"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_basalt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:polished_blackstone_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>stone</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>20</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>polished_blackstone</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:polished_blackstone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:polished_deepslate"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:polished_diorite"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:polished_granite"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:polished_tuff"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poppy
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 100,
    "id": "minecraft:night_vision"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potatoes
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:potato</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_acacia_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:acacia_sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_allium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:allium</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_azalea_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:azalea</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_azure_bluet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:azure_bluet</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_bamboo
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:bamboo</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_birch_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:birch_sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_blue_orchid
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:blue_orchid</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_brown_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:brown_mushroom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_cactus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:cactus</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_cherry_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:cherry_sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_cornflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:cornflower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_crimson_fungus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:crimson_fungus</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_crimson_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:crimson_roots</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_dandelion
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:dandelion</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_dark_oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:dark_oak_sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_dead_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:dead_bush</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_fern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:fern</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_flowering_azalea_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:flowering_azalea</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_jungle_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:jungle_sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_lily_of_the_valley
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:lily_of_the_valley</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_mangrove_propagule
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:mangrove_propagule</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_oak_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:oak_sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_orange_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:orange_tulip</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_oxeye_daisy
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:oxeye_daisy</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_pink_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:pink_tulip</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_poppy
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:poppy</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_red_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:red_mushroom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_red_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:red_tulip</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_spruce_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:spruce_sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_torchflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:torchflower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_warped_fungus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:warped_fungus</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_warped_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:warped_roots</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_white_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:white_tulip</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potted_wither_rose
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower_pot</pre></td></tr><tr><td>potted</td><td><pre>/</pre></td><td><pre>minecraft:wither_rose</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powder_snow
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:powder_snow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powder_snow_cauldron
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:layered_cauldron</pre></td></tr><tr><td>interactions</td><td><pre>/</pre></td><td><pre>powder_snow</pre></td></tr><tr><td>precipitation</td><td><pre>/</pre></td><td><pre>snow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powered_rail
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:powered_rail</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:prismarine_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:prismarine"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pumpkin</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stem</pre></td></tr><tr><td>attached_stem</td><td><pre>/</pre></td><td><pre>minecraft:attached_pumpkin_stem</pre></td></tr><tr><td>fruit</td><td><pre>/</pre></td><td><pre>minecraft:pumpkin</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>seed</td><td><pre>/</pre></td><td><pre>minecraft:pumpkin_seeds</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>purple</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>purple</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:purple_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>purple</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:purple_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>purple</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>purple</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>purple</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>purple</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_pillar
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:purpur_block"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_pillar
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:quartz_block"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rail
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rail</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:powered</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_lamp
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:redstone_lamp</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:redstone_ore</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:redstone_torch</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_wall_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:redstone_wall_torch</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_wire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:redstone_wire</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>red</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>red</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:red_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>red</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:red_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:mushroom</pre></td></tr><tr><td>feature</td><td><pre>/</pre></td><td><pre>minecraft:huge_red_mushroom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:huge_mushroom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:red_nether_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:colored_falling</pre></td></tr><tr><td>falling_dust_color</td><td><pre>/</pre></td><td><pre>#00A95821</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:red_sandstone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>red</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>red</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>red</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 180,
    "id": "minecraft:weakness"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>red</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
reinforced_deepslate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeater
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:repeater</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeating_command_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:command</pre></td></tr><tr><td>automatic</td><td><pre>/</pre></td><td><pre>false</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
respawn_anchor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:respawn_anchor</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rooted_dirt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rooted_dirt</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rose_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tall_flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:colored_falling</pre></td></tr><tr><td>falling_dust_color</td><td><pre>/</pre></td><td><pre>#00DBD3A0</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:sandstone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scaffolding
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:scaffolding</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sculk</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_catalyst
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sculk_catalyst</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_sensor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sculk_sensor</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_shrieker
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sculk_shrieker</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_vein
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sculk_vein</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
seagrass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:seagrass</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_pickle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sea_pickle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_grass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tall_grass</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shroomlight
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_skull
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>skeleton</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_wall_skull
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>skeleton</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slime</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:amethyst_cluster</pre></td></tr><tr><td>aabb_offset</td><td><pre>/</pre></td><td><pre>4</pre></td></tr><tr><td>height</td><td><pre>/</pre></td><td><pre>3</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_dripleaf
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:small_dripleaf</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smithing_table
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:smithing_table</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smoker
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:smoker</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_basalt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:smooth_quartz"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:smooth_red_sandstone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:smooth_sandstone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_egg
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sniffer_egg</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:snow_layer</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_campfire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:campfire</pre></td></tr><tr><td>fire_damage</td><td><pre>/</pre></td><td><pre>2</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>spawn_particles</td><td><pre>/</pre></td><td><pre>false</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_fire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:soul_fire</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_lantern
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:lantern</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:soul_sand</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_soil
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:torch</pre></td></tr><tr><td>particle_options</td><td><pre>/</pre></td><td><pre>minecraft:soul_fire_flame</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_wall_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_torch</pre></td></tr><tr><td>particle_options</td><td><pre>/</pre></td><td><pre>minecraft:soul_fire_flame</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spawner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:spawner</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sponge
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sponge</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spore_blossom
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:spore_blossom</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sapling
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sapling</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>tree</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:spruce_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>spruce</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sticky_piston
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:piston_base</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>sticky</td><td><pre>/</pre></td><td><pre>true</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stonecutter
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stonecutter</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:stone_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>stone</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>20</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>stone</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:stone"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_bamboo_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_hyphae
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_log
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_wood
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_hyphae
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:structure</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_void
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:structure_void</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar_cane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sugar_cane</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sunflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tall_flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_gravel
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:brushable</pre></td></tr><tr><td>brush_comleted_sound</td><td><pre>/</pre></td><td><pre>minecraft:item.brush.brushing.gravel.complete</pre></td></tr><tr><td>brush_sound</td><td><pre>/</pre></td><td><pre>minecraft:item.brush.brushing.gravel</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>turns_into</td><td><pre>/</pre></td><td><pre>minecraft:gravel</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:brushable</pre></td></tr><tr><td>brush_comleted_sound</td><td><pre>/</pre></td><td><pre>minecraft:item.brush.brushing.sand.complete</pre></td></tr><tr><td>brush_sound</td><td><pre>/</pre></td><td><pre>minecraft:item.brush.brushing.sand</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>turns_into</td><td><pre>/</pre></td><td><pre>minecraft:sand</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sweet_berry_bush
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:sweet_berry_bush</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_grass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:double_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_seagrass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tall_seagrass</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
target
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:target</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tinted_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tinted_glass</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tnt</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:torch</pre></td></tr><tr><td>particle_options</td><td><pre>/</pre></td><td><pre>minecraft:flame</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 100,
    "id": "minecraft:night_vision"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower_crop
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:torchflower_crop</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trapped_chest
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapped_chest</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_spawner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trial_spawner</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tripwire
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:tripwire</pre></td></tr><tr><td>hook</td><td><pre>/</pre></td><td><pre>minecraft:tripwire_hook</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tripwire_hook
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trip_wire_hook</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_plant</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_tube_coral</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_tube_coral_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_tube_coral_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_wall_fan
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:coral_wall_fan</pre></td></tr><tr><td>dead</td><td><pre>/</pre></td><td><pre>minecraft:dead_tube_coral_wall_fan</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_bricks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:tuff_bricks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:tuff"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_wall
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_egg
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:turtle_egg</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
twisting_vines
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:twisting_vines</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
twisting_vines_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:twisting_vines_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vault
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:vault</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
verdant_froglight
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vine
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:vine</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
void_air
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:air</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wall_torch
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_torch</pre></td></tr><tr><td>particle_options</td><td><pre>/</pre></td><td><pre>minecraft:flame</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_button
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:button</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>ticks_to_stay_pressed</td><td><pre>/</pre></td><td><pre>30</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence_gate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fence_gate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:fungus</pre></td></tr><tr><td>feature</td><td><pre>/</pre></td><td><pre>minecraft:warped_fungus_planted</pre></td></tr><tr><td>grows_on</td><td><pre>/</pre></td><td><pre>minecraft:warped_nylium</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:ceiling_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hyphae
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_nylium
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:nylium</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_planks
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_pressure_plate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:pressure_plate</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_roots
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:roots</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:standing_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:warped_planks"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stem
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:rotated_pillar</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wall_hanging_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_hanging_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wall_sign
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_sign</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>wood_type</td><td><pre>/</pre></td><td><pre>warped</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wart_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
water
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:liquid</pre></td></tr><tr><td>fluid</td><td><pre>/</pre></td><td><pre>minecraft:water</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
water_cauldron
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:layered_cauldron</pre></td></tr><tr><td>interactions</td><td><pre>/</pre></td><td><pre>water</pre></td></tr><tr><td>precipitation</td><td><pre>/</pre></td><td><pre>rain</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_block
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:copper_bulb_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:waterlogged_transparent</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:waxed_cut_copper"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:copper_bulb_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:waterlogged_transparent</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:waxed_exposed_cut_copper"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:copper_bulb_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:waterlogged_transparent</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:waxed_oxidized_cut_copper"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:copper_bulb_block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:waterlogged_transparent</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:trapdoor</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:waxed_weathered_cut_copper"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_chiseled_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_bulb
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_bulb</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_door
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_grate
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_grate</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_trap_door</pre></td></tr><tr><td>block_set_type</td><td><pre>/</pre></td><td><pre>copper</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_full</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_slab
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_slab</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_stairs
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weathering_copper_stair</pre></td></tr><tr><td>base_state</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:weathered_cut_copper"
}</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>weathering_state</td><td><pre>/</pre></td><td><pre>weathered</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weeping_vines
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weeping_vines</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weeping_vines_plant
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:weeping_vines_plant</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wet_sponge
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wet_sponge</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:crop</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>white</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>white</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:white_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>white</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:white_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>white</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>white</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>white</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_tulip
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:flower</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "duration": 180,
    "id": "minecraft:weakness"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>white</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_rose
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wither_rose</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>suspicious_stew_effects</td><td><pre>/</pre></td><td><pre>[
  {
    "id": "minecraft:wither"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_skull
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wither_skull</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_wall_skull
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wither_wall_skull</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>yellow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bed
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:bed</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>yellow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_candle
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_candle_cake
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:candle_cake</pre></td></tr><tr><td>candle</td><td><pre>/</pre></td><td><pre>minecraft:yellow_candle</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_carpet
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wool_carpet</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>yellow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete_powder
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:concrete_powder</pre></td></tr><tr><td>concrete</td><td><pre>/</pre></td><td><pre>minecraft:yellow_concrete</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_glazed_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:glazed_terracotta</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_shulker_box
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:shulker_box</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>yellow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>yellow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass_pane
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:stained_glass_pane</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>yellow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wall_banner
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_banner</pre></td></tr><tr><td>color</td><td><pre>/</pre></td><td><pre>yellow</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wool
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:block</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>zombie</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_wall_head
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w07a</th><th>24w09a</th></tr><tr><td>type</td><td><pre>/</pre></td><td><pre>minecraft:wall_skull</pre></td></tr><tr><td>kind</td><td><pre>/</pre></td><td><pre>zombie</pre></td></tr><tr><td>properties</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
attribute
</summary>

```diff
- attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> add
+ attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> add_multiplied_base
+ attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> add_multiplied_total
+ attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> add_value
- attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> multiply
- attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> multiply_base
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
andesite_slab_from_andesite_stonecutting.json
</summary>

```
Result: andesite_slab x1 -> andesite_slab x2
```

</details>
<details>
<summary>
blackstone_slab_from_blackstone_stonecutting.json
</summary>

```
Result: blackstone_slab x1 -> blackstone_slab x2
```

</details>
<details>
<summary>
brick_slab_from_bricks_stonecutting.json
</summary>

```
Result: brick_slab x1 -> brick_slab x2
```

</details>
<details>
<summary>
cobbled_deepslate_slab_from_cobbled_deepslate_stonecutting.json
</summary>

```
Result: cobbled_deepslate_slab x1 -> cobbled_deepslate_slab x2
```

</details>
<details>
<summary>
cobblestone_slab_from_cobblestone_stonecutting.json
</summary>

```
Result: cobblestone_slab x1 -> cobblestone_slab x2
```

</details>
<details>
<summary>
cut_copper_from_copper_block_stonecutting.json
</summary>

```
Result: cut_copper x1 -> cut_copper x4
```

</details>
<details>
<summary>
cut_copper_slab_from_copper_block_stonecutting.json
</summary>

```
Result: cut_copper_slab x1 -> cut_copper_slab x8
```

</details>
<details>
<summary>
cut_copper_slab_from_cut_copper_stonecutting.json
</summary>

```
Result: cut_copper_slab x1 -> cut_copper_slab x2
```

</details>
<details>
<summary>
cut_copper_stairs_from_copper_block_stonecutting.json
</summary>

```
Result: cut_copper_stairs x1 -> cut_copper_stairs x4
```

</details>
<details>
<summary>
cut_red_sandstone_slab_from_cut_red_sandstone_stonecutting.json
</summary>

```
Result: cut_red_sandstone_slab x1 -> cut_red_sandstone_slab x2
```

</details>
<details>
<summary>
cut_red_sandstone_slab_from_red_sandstone_stonecutting.json
</summary>

```
Result: cut_red_sandstone_slab x1 -> cut_red_sandstone_slab x2
```

</details>
<details>
<summary>
cut_sandstone_slab_from_cut_sandstone_stonecutting.json
</summary>

```
Result: cut_sandstone_slab x1 -> cut_sandstone_slab x2
```

</details>
<details>
<summary>
cut_sandstone_slab_from_sandstone_stonecutting.json
</summary>

```
Result: cut_sandstone_slab x1 -> cut_sandstone_slab x2
```

</details>
<details>
<summary>
dark_prismarine_slab_from_dark_prismarine_stonecutting.json
</summary>

```
Result: dark_prismarine_slab x1 -> dark_prismarine_slab x2
```

</details>
<details>
<summary>
deepslate_brick_slab_from_cobbled_deepslate_stonecutting.json
</summary>

```
Result: deepslate_brick_slab x1 -> deepslate_brick_slab x2
```

</details>
<details>
<summary>
deepslate_brick_slab_from_deepslate_bricks_stonecutting.json
</summary>

```
Result: deepslate_brick_slab x1 -> deepslate_brick_slab x2
```

</details>
<details>
<summary>
deepslate_brick_slab_from_polished_deepslate_stonecutting.json
</summary>

```
Result: deepslate_brick_slab x1 -> deepslate_brick_slab x2
```

</details>
<details>
<summary>
deepslate_tile_slab_from_cobbled_deepslate_stonecutting.json
</summary>

```
Result: deepslate_tile_slab x1 -> deepslate_tile_slab x2
```

</details>
<details>
<summary>
deepslate_tile_slab_from_deepslate_bricks_stonecutting.json
</summary>

```
Result: deepslate_tile_slab x1 -> deepslate_tile_slab x2
```

</details>
<details>
<summary>
deepslate_tile_slab_from_deepslate_tiles_stonecutting.json
</summary>

```
Result: deepslate_tile_slab x1 -> deepslate_tile_slab x2
```

</details>
<details>
<summary>
deepslate_tile_slab_from_polished_deepslate_stonecutting.json
</summary>

```
Result: deepslate_tile_slab x1 -> deepslate_tile_slab x2
```

</details>
<details>
<summary>
diorite_slab_from_diorite_stonecutting.json
</summary>

```
Result: diorite_slab x1 -> diorite_slab x2
```

</details>
<details>
<summary>
end_stone_brick_slab_from_end_stone_brick_stonecutting.json
</summary>

```
Result: end_stone_brick_slab x1 -> end_stone_brick_slab x2
```

</details>
<details>
<summary>
end_stone_brick_slab_from_end_stone_stonecutting.json
</summary>

```
Result: end_stone_brick_slab x1 -> end_stone_brick_slab x2
```

</details>
<details>
<summary>
exposed_cut_copper_from_exposed_copper_stonecutting.json
</summary>

```
Result: exposed_cut_copper x1 -> exposed_cut_copper x4
```

</details>
<details>
<summary>
exposed_cut_copper_slab_from_exposed_copper_stonecutting.json
</summary>

```
Result: exposed_cut_copper_slab x1 -> exposed_cut_copper_slab x8
```

</details>
<details>
<summary>
exposed_cut_copper_slab_from_exposed_cut_copper_stonecutting.json
</summary>

```
Result: exposed_cut_copper_slab x1 -> exposed_cut_copper_slab x2
```

</details>
<details>
<summary>
exposed_cut_copper_stairs_from_exposed_copper_stonecutting.json
</summary>

```
Result: exposed_cut_copper_stairs x1 -> exposed_cut_copper_stairs x4
```

</details>
<details>
<summary>
granite_slab_from_granite_stonecutting.json
</summary>

```
Result: granite_slab x1 -> granite_slab x2
```

</details>
<details>
<summary>
mossy_cobblestone_slab_from_mossy_cobblestone_stonecutting.json
</summary>

```
Result: mossy_cobblestone_slab x1 -> mossy_cobblestone_slab x2
```

</details>
<details>
<summary>
mossy_stone_brick_slab_from_mossy_stone_brick_stonecutting.json
</summary>

```
Result: mossy_stone_brick_slab x1 -> mossy_stone_brick_slab x2
```

</details>
<details>
<summary>
mud_brick_slab_from_mud_bricks_stonecutting.json
</summary>

```
Result: mud_brick_slab x1 -> mud_brick_slab x2
```

</details>
<details>
<summary>
nether_brick_slab_from_nether_bricks_stonecutting.json
</summary>

```
Result: nether_brick_slab x1 -> nether_brick_slab x2
```

</details>
<details>
<summary>
oxidized_cut_copper_from_oxidized_copper_stonecutting.json
</summary>

```
Result: oxidized_cut_copper x1 -> oxidized_cut_copper x4
```

</details>
<details>
<summary>
oxidized_cut_copper_slab_from_oxidized_copper_stonecutting.json
</summary>

```
Result: oxidized_cut_copper_slab x1 -> oxidized_cut_copper_slab x8
```

</details>
<details>
<summary>
oxidized_cut_copper_slab_from_oxidized_cut_copper_stonecutting.json
</summary>

```
Result: oxidized_cut_copper_slab x1 -> oxidized_cut_copper_slab x2
```

</details>
<details>
<summary>
oxidized_cut_copper_stairs_from_oxidized_copper_stonecutting.json
</summary>

```
Result: oxidized_cut_copper_stairs x1 -> oxidized_cut_copper_stairs x4
```

</details>
<details>
<summary>
polished_andesite_slab_from_andesite_stonecutting.json
</summary>

```
Result: polished_andesite_slab x1 -> polished_andesite_slab x2
```

</details>
<details>
<summary>
polished_andesite_slab_from_polished_andesite_stonecutting.json
</summary>

```
Result: polished_andesite_slab x1 -> polished_andesite_slab x2
```

</details>
<details>
<summary>
polished_blackstone_brick_slab_from_blackstone_stonecutting.json
</summary>

```
Result: polished_blackstone_brick_slab x1 -> polished_blackstone_brick_slab x2
```

</details>
<details>
<summary>
polished_blackstone_brick_slab_from_polished_blackstone_bricks_stonecutting.json
</summary>

```
Result: polished_blackstone_brick_slab x1 -> polished_blackstone_brick_slab x2
```

</details>
<details>
<summary>
polished_blackstone_brick_slab_from_polished_blackstone_stonecutting.json
</summary>

```
Result: polished_blackstone_brick_slab x1 -> polished_blackstone_brick_slab x2
```

</details>
<details>
<summary>
polished_blackstone_slab_from_blackstone_stonecutting.json
</summary>

```
Result: polished_blackstone_slab x1 -> polished_blackstone_slab x2
```

</details>
<details>
<summary>
polished_blackstone_slab_from_polished_blackstone_stonecutting.json
</summary>

```
Result: polished_blackstone_slab x1 -> polished_blackstone_slab x2
```

</details>
<details>
<summary>
polished_deepslate_slab_from_cobbled_deepslate_stonecutting.json
</summary>

```
Result: polished_deepslate_slab x1 -> polished_deepslate_slab x2
```

</details>
<details>
<summary>
polished_deepslate_slab_from_polished_deepslate_stonecutting.json
</summary>

```
Result: polished_deepslate_slab x1 -> polished_deepslate_slab x2
```

</details>
<details>
<summary>
polished_diorite_slab_from_diorite_stonecutting.json
</summary>

```
Result: polished_diorite_slab x1 -> polished_diorite_slab x2
```

</details>
<details>
<summary>
polished_diorite_slab_from_polished_diorite_stonecutting.json
</summary>

```
Result: polished_diorite_slab x1 -> polished_diorite_slab x2
```

</details>
<details>
<summary>
polished_granite_slab_from_granite_stonecutting.json
</summary>

```
Result: polished_granite_slab x1 -> polished_granite_slab x2
```

</details>
<details>
<summary>
polished_granite_slab_from_polished_granite_stonecutting.json
</summary>

```
Result: polished_granite_slab x1 -> polished_granite_slab x2
```

</details>
<details>
<summary>
prismarine_brick_slab_from_prismarine_stonecutting.json
</summary>

```
Result: prismarine_brick_slab x1 -> prismarine_brick_slab x2
```

</details>
<details>
<summary>
prismarine_slab_from_prismarine_stonecutting.json
</summary>

```
Result: prismarine_slab x1 -> prismarine_slab x2
```

</details>
<details>
<summary>
purpur_slab_from_purpur_block_stonecutting.json
</summary>

```
Result: purpur_slab x1 -> purpur_slab x2
```

</details>
<details>
<summary>
quartz_slab_from_stonecutting.json
</summary>

```
Result: quartz_slab x1 -> quartz_slab x2
```

</details>
<details>
<summary>
red_nether_brick_slab_from_red_nether_bricks_stonecutting.json
</summary>

```
Result: red_nether_brick_slab x1 -> red_nether_brick_slab x2
```

</details>
<details>
<summary>
red_sandstone_slab_from_red_sandstone_stonecutting.json
</summary>

```
Result: red_sandstone_slab x1 -> red_sandstone_slab x2
```

</details>
<details>
<summary>
sandstone_slab_from_sandstone_stonecutting.json
</summary>

```
Result: sandstone_slab x1 -> sandstone_slab x2
```

</details>
<details>
<summary>
smooth_quartz_slab_from_smooth_quartz_stonecutting.json
</summary>

```
Result: smooth_quartz_slab x1 -> smooth_quartz_slab x2
```

</details>
<details>
<summary>
smooth_red_sandstone_slab_from_smooth_red_sandstone_stonecutting.json
</summary>

```
Result: smooth_red_sandstone_slab x1 -> smooth_red_sandstone_slab x2
```

</details>
<details>
<summary>
smooth_sandstone_slab_from_smooth_sandstone_stonecutting.json
</summary>

```
Result: smooth_sandstone_slab x1 -> smooth_sandstone_slab x2
```

</details>
<details>
<summary>
smooth_stone_slab_from_smooth_stone_stonecutting.json
</summary>

```
Result: smooth_stone_slab x1 -> smooth_stone_slab x2
```

</details>
<details>
<summary>
stone_brick_slab_from_stone_bricks_stonecutting.json
</summary>

```
Result: stone_brick_slab x1 -> stone_brick_slab x2
```

</details>
<details>
<summary>
stone_brick_slab_from_stone_stonecutting.json
</summary>

```
Result: stone_brick_slab x1 -> stone_brick_slab x2
```

</details>
<details>
<summary>
stone_slab_from_stone_stonecutting.json
</summary>

```
Result: stone_slab x1 -> stone_slab x2
```

</details>
<details>
<summary>
waxed_cut_copper_from_waxed_copper_block_stonecutting.json
</summary>

```
Result: waxed_cut_copper x1 -> waxed_cut_copper x4
```

</details>
<details>
<summary>
waxed_cut_copper_slab_from_waxed_copper_block_stonecutting.json
</summary>

```
Result: waxed_cut_copper_slab x1 -> waxed_cut_copper_slab x8
```

</details>
<details>
<summary>
waxed_cut_copper_slab_from_waxed_cut_copper_stonecutting.json
</summary>

```
Result: waxed_cut_copper_slab x1 -> waxed_cut_copper_slab x2
```

</details>
<details>
<summary>
waxed_cut_copper_stairs_from_waxed_copper_block_stonecutting.json
</summary>

```
Result: waxed_cut_copper_stairs x1 -> waxed_cut_copper_stairs x4
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_from_waxed_exposed_copper_stonecutting.json
</summary>

```
Result: waxed_exposed_cut_copper x1 -> waxed_exposed_cut_copper x4
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_slab_from_waxed_exposed_copper_stonecutting.json
</summary>

```
Result: waxed_exposed_cut_copper_slab x1 -> waxed_exposed_cut_copper_slab x8
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_slab_from_waxed_exposed_cut_copper_stonecutting.json
</summary>

```
Result: waxed_exposed_cut_copper_slab x1 -> waxed_exposed_cut_copper_slab x2
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs_from_waxed_exposed_copper_stonecutting.json
</summary>

```
Result: waxed_exposed_cut_copper_stairs x1 -> waxed_exposed_cut_copper_stairs x4
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_from_waxed_oxidized_copper_stonecutting.json
</summary>

```
Result: waxed_oxidized_cut_copper x1 -> waxed_oxidized_cut_copper x4
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab_from_waxed_oxidized_copper_stonecutting.json
</summary>

```
Result: waxed_oxidized_cut_copper_slab x1 -> waxed_oxidized_cut_copper_slab x8
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab_from_waxed_oxidized_cut_copper_stonecutting.json
</summary>

```
Result: waxed_oxidized_cut_copper_slab x1 -> waxed_oxidized_cut_copper_slab x2
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs_from_waxed_oxidized_copper_stonecutting.json
</summary>

```
Result: waxed_oxidized_cut_copper_stairs x1 -> waxed_oxidized_cut_copper_stairs x4
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_from_waxed_weathered_copper_stonecutting.json
</summary>

```
Result: waxed_weathered_cut_copper x1 -> waxed_weathered_cut_copper x4
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_slab_from_waxed_weathered_copper_stonecutting.json
</summary>

```
Result: waxed_weathered_cut_copper_slab x1 -> waxed_weathered_cut_copper_slab x8
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_slab_from_waxed_weathered_cut_copper_stonecutting.json
</summary>

```
Result: waxed_weathered_cut_copper_slab x1 -> waxed_weathered_cut_copper_slab x2
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs_from_waxed_weathered_copper_stonecutting.json
</summary>

```
Result: waxed_weathered_cut_copper_stairs x1 -> waxed_weathered_cut_copper_stairs x4
```

</details>
<details>
<summary>
weathered_cut_copper_from_weathered_copper_stonecutting.json
</summary>

```
Result: weathered_cut_copper x1 -> weathered_cut_copper x4
```

</details>
<details>
<summary>
weathered_cut_copper_slab_from_weathered_copper_stonecutting.json
</summary>

```
Result: weathered_cut_copper_slab x1 -> weathered_cut_copper_slab x8
```

</details>
<details>
<summary>
weathered_cut_copper_slab_from_weathered_cut_copper_stonecutting.json
</summary>

```
Result: weathered_cut_copper_slab x1 -> weathered_cut_copper_slab x2
```

</details>
<details>
<summary>
weathered_cut_copper_stairs_from_weathered_copper_stonecutting.json
</summary>

```
Result: weathered_cut_copper_stairs x1 -> weathered_cut_copper_stairs x4
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
+ arguments.item.component.expected: Expected item component
+ arguments.item.component.malformed: Malformed '%s' component: '%s'
+ arguments.item.component.unknown: Unknown item component '%s'
+ chunk.toast.checkLog: See log for more details
+ chunk.toast.loadFailure: Failed to load chunk at %s
+ chunk.toast.lowDiskSpace: Low disk space!
+ chunk.toast.lowDiskSpace.description: Might not be able to save the world.
+ chunk.toast.saveFailure: Failed to save chunk at %s
+ item.canUse.unknown: Unknown
+ item.components: %s component(s)
+ mco.backup.narration: Backup from %s
+ mco.client.outdated.stable.version: Your client version (%s) is not compatible with Realms.

Please use the most recent version of Minecraft.
+ mco.client.unsupported.snapshot.version: Your client version (%s) is not compatible with Realms.

Realms is not available for this snapshot version.
+ mco.invited.player.narration: Invited player %s
+ options.accessibility.menu_background_blurriness: Menu Background Blurriness
+ options.accessibility.menu_background_blurriness.tooltip: Changes the blurriness of menu backgrounds
+ selectWorld.warning.lowDiskSpace.description: There is not much space left on your device.
Running out of disk space while in game can lead to your world being damaged.
+ selectWorld.warning.lowDiskSpace.title: Warning! Low disk space!
+ subtitles.block.candle.extinguish: Candle extinguishes
+ subtitles.block.wet_sponge.dries: Sponge dries
+ subtitles.entity.donkey.jump: Donkey jumps
+ subtitles.entity.mule.jump: Mule jumps
+ subtitles.item.wolf_armor.break: Wolf Armor breaks
+ subtitles.item.wolf_armor.crack: Wolf Armor cracks
+ subtitles.item.wolf_armor.damage: Wolf Armor takes damage
+ subtitles.item.wolf_armor.repair: Wolf Armor is repaired
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
+ reports/items.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/shearing/bogged.json
+ minecraft/loot_tables/shearing/bogged.json
+ minecraft/tags/damage_type/bypasses_wolf_armor.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/block/vault_top_off.png
- minecraft/textures/block/vault_top_on.png
+ minecraft/textures/block/vault_top.png
+ minecraft/textures/entity/wolf/wolf_armor_crackiness_high.png
+ minecraft/textures/entity/wolf/wolf_armor_crackiness_low.png
+ minecraft/textures/entity/wolf/wolf_armor_crackiness_medium.png
+ minecraft/textures/entity/wolf/wolf_armor_overlay.png
- minecraft/textures/gui/light_dirt_background.png
+ minecraft/textures/gui/menu_background.png
+ minecraft/textures/gui/menu_list_background.png
- minecraft/textures/gui/options_background.png
- minecraft/textures/gui/sprites/backup/changes_highlighted.png
- minecraft/textures/gui/sprites/backup/changes.png
- minecraft/textures/gui/sprites/backup/restore_highlighted.png
- minecraft/textures/gui/sprites/backup/restore.png
- minecraft/textures/gui/sprites/player_list/make_operator_highlighted.png
- minecraft/textures/gui/sprites/player_list/remove_operator_highlighted.png
- minecraft/textures/gui/sprites/player_list/remove_player_highlighted.png
+ minecraft/textures/gui/sprites/widget/scroller_background.png
+ minecraft/textures/gui/sprites/widget/scroller_background.png.mcmeta
+ minecraft/textures/item/wolf_armor_overlay.png
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
- net.minecraft.package-info
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeMap
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.attributes.Attributes
+ XXX.ai.attributes.AttributeSupplier
- XXX.ai.attributes.AttributeSupplier$Builder
- XXX.ai.attributes.DefaultAttributes
- XXX.ai.attributes.package-info
+ XXX.ai.attributes.RangedAttribute
+ XXX.ai.behavior.AcquirePoi
- XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
+ XXX.ai.behavior.AnimalMakeLove
- XXX.ai.behavior.AnimalPanic
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.BabyFollowAdult
+ XXX.ai.behavior.BackUpIfTooClose
- XXX.ai.behavior.BecomePassiveIfMemoryPresent
+ XXX.ai.behavior.Behavior
- XXX.ai.behavior.Behavior$Status
+ XXX.ai.behavior.BehaviorControl
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosTracker
- XXX.ai.behavior.CelebrateVillagersSurvivedRaid
+ XXX.ai.behavior.CopyMemoryWithExpiry
- XXX.ai.behavior.CountDownCooldownTicks
+ XXX.ai.behavior.Croak
- XXX.ai.behavior.CrossbowAttack
+ XXX.ai.behavior.CrossbowAttack$CrossbowState
- XXX.ai.behavior.DismountOrSkipMounting
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityTracker
+ XXX.ai.behavior.EraseMemoryIf
- XXX.ai.behavior.FollowTemptation
+ XXX.ai.behavior.GateBehavior
- XXX.ai.behavior.GateBehavior$OrderPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy$1
+ XXX.ai.behavior.GateBehavior$RunningPolicy$2
- XXX.ai.behavior.GiveGiftToHero
+ XXX.ai.behavior.GoAndGiveItemsToTarget
- XXX.ai.behavior.GoToClosestVillage
+ XXX.ai.behavior.GoToPotentialJobSite
- XXX.ai.behavior.GoToTargetLocation
+ XXX.ai.behavior.GoToWantedItem
- XXX.ai.behavior.HarvestFarmland
+ XXX.ai.behavior.InsideBrownianWalk
- XXX.ai.behavior.InteractWith
+ XXX.ai.behavior.InteractWithDoor
- XXX.ai.behavior.JumpOnBed
+ XXX.ai.behavior.LocateHidingPlace
- XXX.ai.behavior.LongJumpMidJump
+ XXX.ai.behavior.LongJumpToPreferredBlock
- XXX.ai.behavior.LongJumpToRandomPos
+ XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
- XXX.ai.behavior.LongJumpUtil
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MeleeAttack
- XXX.ai.behavior.Mount
+ XXX.ai.behavior.MoveToSkySeeingSpot
- XXX.ai.behavior.MoveToTargetSink
+ XXX.ai.behavior.OneShot
+ XXX.ai.behavior.package-info
- XXX.ai.behavior.PlayTagWithOtherKids
+ XXX.ai.behavior.PoiCompetitorScan
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.PrepareRamNearestTarget
- XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ XXX.ai.behavior.RamTarget
- XXX.ai.behavior.RandomLookAround
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetEntityLookTargetSometimes
- XXX.ai.behavior.SetEntityLookTargetSometimes$Ticker
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.ShufflingList
- XXX.ai.behavior.ShufflingList$WeightedEntry
+ XXX.ai.behavior.ShufflingList$WeightedEntry$1
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TriggerGate
+ XXX.ai.behavior.TryFindLand
- XXX.ai.behavior.TryFindLandNearWater
+ XXX.ai.behavior.TryFindWater
- XXX.ai.behavior.TryLaySpawnOnWaterNearLand
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VillageBoundRandomStroll
+ XXX.ai.behavior.VillagerCalmDown
- XXX.ai.behavior.VillagerGoalPackages
+ XXX.ai.behavior.VillagerMakeLove
- XXX.ai.behavior.VillagerPanicTrigger
+ XXX.ai.behavior.WakeUp
- XXX.ai.behavior.WorkAtComposter
+ XXX.ai.behavior.WorkAtPoi
- XXX.ai.behavior.YieldJobSite
- XXX.ai.control.BodyRotationControl
+ XXX.ai.control.Control
- XXX.ai.control.FlyingMoveControl
+ XXX.ai.control.JumpControl
- XXX.ai.control.LookControl
+ XXX.ai.control.MoveControl
- XXX.ai.control.MoveControl$Operation
+ XXX.ai.control.package-info
+ XXX.ai.control.SmoothSwimmingLookControl
- XXX.ai.control.SmoothSwimmingMoveControl
- XXX.ai.goal.AvoidEntityGoal
+ XXX.ai.goal.BegGoal
- XXX.ai.goal.BoatGoals
+ XXX.ai.goal.BreakDoorGoal
- XXX.ai.goal.BreathAirGoal
+ XXX.ai.goal.BreedGoal
- XXX.ai.goal.CatLieOnBedGoal
+ XXX.ai.goal.CatSitOnBlockGoal
- XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
+ XXX.ai.goal.DolphinJumpGoal
- XXX.ai.goal.DoorInteractGoal
+ XXX.ai.goal.EatBlockGoal
- XXX.ai.goal.FleeSunGoal
+ XXX.ai.goal.FloatGoal
- XXX.ai.goal.FollowBoatGoal
+ XXX.ai.goal.FollowFlockLeaderGoal
- XXX.ai.goal.FollowMobGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.GolemRandomStrollInVillageGoal
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillageGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
+ XXX.ai.goal.package-info
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
+ XXX.ai.goal.RandomLookAroundGoal
- XXX.ai.goal.RandomStandGoal
+ XXX.ai.goal.RandomStrollGoal
- XXX.ai.goal.RandomSwimmingGoal
+ XXX.ai.goal.RangedAttackGoal
- XXX.ai.goal.RangedBowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ XXX.ai.goal.RemoveBlockGoal
- XXX.ai.goal.RestrictSunGoal
+ XXX.ai.goal.RunAroundLikeCrazyGoal
- XXX.ai.goal.SitWhenOrderedToGoal
+ XXX.ai.goal.StrollThroughVillageGoal
- XXX.ai.goal.SwellGoal
+ XXX.ai.goal.TemptGoal
- XXX.ai.goal.TradeWithPlayerGoal
+ XXX.ai.goal.TryFindWaterGoal
- XXX.ai.goal.UseItemGoal
+ XXX.ai.goal.WaterAvoidingRandomFlyingGoal
- XXX.ai.goal.WaterAvoidingRandomStrollGoal
+ XXX.ai.goal.WrappedGoal
- XXX.ai.goal.ZombieAttackGoal
+ XXX.ai.gossip.GossipContainer
- XXX.ai.gossip.GossipContainer$EntityGossips
+ XXX.ai.gossip.GossipContainer$GossipEntry
- XXX.ai.gossip.GossipType
+ XXX.ai.gossip.package-info
- XXX.ai.memory.ExpirableValue
+ XXX.ai.memory.MemoryModuleType
- XXX.ai.memory.MemoryStatus
+ XXX.ai.memory.NearestVisibleLivingEntities
+ XXX.ai.memory.package-info
- XXX.ai.memory.WalkTarget
- XXX.ai.navigation.AmphibiousPathNavigation
+ XXX.ai.navigation.FlyingPathNavigation
- XXX.ai.navigation.GroundPathNavigation
- XXX.ai.navigation.package-info
+ XXX.ai.navigation.PathNavigation
- XXX.ai.navigation.WallClimberNavigation
+ XXX.ai.navigation.WaterBoundPathNavigation
- XXX.ai.sensing.AdultSensor
+ XXX.ai.sensing.AxolotlAttackablesSensor
- XXX.ai.sensing.BreezeAttackEntitySensor
+ XXX.ai.sensing.DummySensor
- XXX.ai.sensing.FrogAttackablesSensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.IsInWaterSensor
+ XXX.ai.sensing.MobSensor
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestItemSensor
- XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.NearestVisibleLivingEntitySensor
+ XXX.ai.sensing.package-info
- XXX.ai.sensing.PiglinBruteSpecificSensor
+ XXX.ai.sensing.PiglinSpecificSensor
- XXX.ai.sensing.PlayerSensor
+ XXX.ai.sensing.SecondaryPoiSensor
- XXX.ai.sensing.Sensing
+ XXX.ai.sensing.Sensor
- XXX.ai.sensing.SensorType
+ XXX.ai.sensing.TemptingSensor
- XXX.ai.sensing.VillagerBabiesSensor
+ XXX.ai.sensing.VillagerHostilesSensor
- XXX.ai.sensing.WardenEntitySensor
+ XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
- XXX.ai.util.AirAndWaterRandomPos
+ XXX.ai.util.AirRandomPos
- XXX.ai.util.DefaultRandomPos
+ XXX.ai.util.GoalUtils
- XXX.ai.util.HoverRandomPos
+ XXX.ai.util.LandRandomPos
+ XXX.ai.util.package-info
- XXX.ai.util.RandomPos
- XXX.ai.village.package-info
- XXX.ai.village.ReputationEventType
+ XXX.ai.village.ReputationEventType$1
- XXX.ai.village.VillageSiege
+ XXX.ai.village.VillageSiege$State
+ XXX.behavior.declarative.BehaviorBuilder
- XXX.behavior.declarative.BehaviorBuilder$1
+ XXX.behavior.declarative.BehaviorBuilder$Constant
- XXX.behavior.declarative.BehaviorBuilder$Constant$1
+ XXX.behavior.declarative.BehaviorBuilder$Instance
- XXX.behavior.declarative.BehaviorBuilder$Instance$1
+ XXX.behavior.declarative.BehaviorBuilder$Instance$2
- XXX.behavior.declarative.BehaviorBuilder$Instance$3
+ XXX.behavior.declarative.BehaviorBuilder$Instance$4
- XXX.behavior.declarative.BehaviorBuilder$Instance$5
+ XXX.behavior.declarative.BehaviorBuilder$Instance$Mu
- XXX.behavior.declarative.BehaviorBuilder$Mu
+ XXX.behavior.declarative.BehaviorBuilder$PureMemory
- XXX.behavior.declarative.BehaviorBuilder$PureMemory$1
+ XXX.behavior.declarative.BehaviorBuilder$TriggerWithResult
- XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper
+ XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
- XXX.behavior.declarative.MemoryAccessor
+ XXX.behavior.declarative.MemoryCondition
- XXX.behavior.declarative.MemoryCondition$Absent
+ XXX.behavior.declarative.MemoryCondition$Present
- XXX.behavior.declarative.MemoryCondition$Registered
- XXX.behavior.declarative.package-info
+ XXX.behavior.declarative.Trigger
- XXX.behavior.warden.Digging
+ XXX.behavior.warden.Emerging
- XXX.behavior.warden.ForceUnmount
+ XXX.behavior.warden.package-info
+ XXX.behavior.warden.Roar
- XXX.behavior.warden.SetRoarTarget
+ XXX.behavior.warden.SetWardenLookTarget
- XXX.behavior.warden.Sniffing
+ XXX.behavior.warden.SonicBoom
- XXX.behavior.warden.TryToSniff
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BannerPatternLayers
- XXX.block.entity.BannerPatternLayers$Layer
- XXX.block.entity.BeehiveBlockEntity$Occupant
+ XXX.block.entity.BellBlockEntity
- XXX.block.entity.BellBlockEntity$ResonationEndAction
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityTicker
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$BlockEntitySupplier
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.BrushableBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.ChiseledBookShelfBlockEntity
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.ContainerOpenersCounter
+ XXX.block.entity.CrafterBlockEntity
- XXX.block.entity.CrafterBlockEntity$1
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity$Decorations
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.SculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.SculkShriekerBlockEntity
- XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SignText
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SkullBlockEntity$1
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.entity.TrialSpawnerBlockEntity
+ XXX.block.grower.package-info
- XXX.block.grower.TreeGrower
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.BlockBehaviour
+ XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase
+ XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$OffsetFunction
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
+ XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.block.state.StateHolder$1
- XXX.chunk.status.ChunkStatus
- XXX.chunk.status.ChunkStatus$LoadingTask
- XXX.chunk.status.ChunkType
- XXX.chunk.status.WorldGenContext
- XXX.chunk.storage.ChunkSerializer$ChunkReadException
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RecreatingChunkStorage
+ XXX.chunk.storage.RecreatingSimpleRegionStorage
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.RegionStorageInfo
- XXX.chunk.storage.SectionStorage
+ XXX.chunk.storage.SimpleRegionStorage
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.DataCommands$StringProcessor
+ XXX.commands.data.EntityDataAccessor
- XXX.commands.data.EntityDataAccessor$1
+ XXX.commands.data.package-info
+ XXX.commands.data.StorageDataAccessor
- XXX.commands.data.StorageDataAccessor$1
- XXX.common.custom.BeeDebugPayload
+ XXX.common.custom.BeeDebugPayload$BeeInfo
- XXX.common.custom.BrainDebugPayload
+ XXX.common.custom.BrainDebugPayload$BrainDump
- XXX.common.custom.BrandPayload
+ XXX.common.custom.BreezeDebugPayload
- XXX.common.custom.BreezeDebugPayload$BreezeInfo
+ XXX.common.custom.CustomPacketPayload
- XXX.common.custom.CustomPacketPayload$1
+ XXX.common.custom.CustomPacketPayload$FallbackProvider
- XXX.common.custom.CustomPacketPayload$Type
+ XXX.common.custom.CustomPacketPayload$TypeAndCodec
- XXX.common.custom.DiscardedPayload
+ XXX.common.custom.GameEventDebugPayload
- XXX.common.custom.GameEventListenerDebugPayload
+ XXX.common.custom.GameTestAddMarkerDebugPayload
- XXX.common.custom.GameTestClearMarkersDebugPayload
+ XXX.common.custom.GoalDebugPayload
- XXX.common.custom.GoalDebugPayload$DebugGoal
+ XXX.common.custom.HiveDebugPayload
- XXX.common.custom.HiveDebugPayload$HiveInfo
+ XXX.common.custom.NeighborUpdatesDebugPayload
+ XXX.common.custom.package-info
- XXX.common.custom.PathfindingDebugPayload
+ XXX.common.custom.PoiAddedDebugPayload
- XXX.common.custom.PoiRemovedDebugPayload
+ XXX.common.custom.PoiTicketCountDebugPayload
- XXX.common.custom.RaidsDebugPayload
+ XXX.common.custom.StructuresDebugPayload
- XXX.common.custom.StructuresDebugPayload$PieceInfo
+ XXX.common.custom.VillageSectionsDebugPayload
- XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.core.component.DataComponentHolder
- XXX.core.component.DataComponentMap$1
- XXX.core.component.DataComponentMap$Builder
- XXX.core.component.DataComponentPatch
- XXX.core.component.DataComponentPatch$Builder
- XXX.core.component.DataComponentPredicate
- XXX.core.component.DataComponentType
- XXX.core.component.DataComponentType$Builder$SimpleType
- XXX.core.component.PatchedDataComponentMap
- XXX.core.component.TypedDataComponent$1
- XXX.data.info.ItemListReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLootSubProvider
- XXX.data.loot.EntityLootSubProvider
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableProvider$1
+ XXX.data.loot.LootTableProvider$SubProviderEntry
- XXX.data.loot.LootTableSubProvider
+ XXX.data.loot.package-info
- XXX.data.metadata.package-info
+ XXX.data.metadata.PackMetadataGenerator
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ItemModelGenerators$TrimModelData
+ XXX.data.models.ModelProvider
+ XXX.data.models.package-info
- XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeBuilder
- XXX.data.recipes.RecipeBuilder$1
+ XXX.data.recipes.RecipeCategory
- XXX.data.recipes.RecipeOutput
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.RecipeProvider$1
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SmithingTransformRecipeBuilder
- XXX.data.recipes.SmithingTrimRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.registries.package-info
- XXX.data.registries.RegistriesDatapackGenerator
+ XXX.data.registries.RegistryPatchGenerator
- XXX.data.registries.UpdateOneTwentyOneRegistries
+ XXX.data.registries.VanillaRegistries
+ XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
- XXX.data.structures.SnbtDatafixer
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$StructureConversionException
- XXX.data.structures.SnbtToNbt$TaskResult
+ XXX.data.structures.StructureUpdater
+ XXX.data.tags.BannerPatternTagsProvider
- XXX.data.tags.BiomeTagsProvider
+ XXX.data.tags.CatVariantTagsProvider
- XXX.data.tags.DamageTypeTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.GameEventTagsProvider
+ XXX.data.tags.InstrumentTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
- XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
+ XXX.data.tags.PaintingVariantTagsProvider
- XXX.data.tags.PoiTypeTagsProvider
+ XXX.data.tags.StructureTagsProvider
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$1CombinedData
- XXX.data.tags.TagsProvider$TagAppender
+ XXX.data.tags.TagsProvider$TagLookup
- XXX.data.tags.TradeRebalanceStructureTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneBiomeTagsProvider
- XXX.data.tags.UpdateOneTwentyOneBlockTagsProvider
- XXX.data.tags.UpdateOneTwentyOneDamageTypes
+ XXX.data.tags.UpdateOneTwentyOneDamageTypeTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneEntityTypeTagsProvider
- XXX.data.tags.UpdateOneTwentyOneItemTagsProvider
+ XXX.data.tags.VanillaBlockTagsProvider
- XXX.data.tags.VanillaItemTagsProvider
+ XXX.data.tags.WorldPresetTagsProvider
+ XXX.data.worldgen.AncientCityStructurePieces
- XXX.data.worldgen.AncientCityStructurePools
+ XXX.data.worldgen.BastionBridgePools
- XXX.data.worldgen.BastionHoglinStablePools
+ XXX.data.worldgen.BastionHousingUnitsPools
- XXX.data.worldgen.BastionPieces
+ XXX.data.worldgen.BastionSharedPools
- XXX.data.worldgen.BastionTreasureRoomPools
+ XXX.data.worldgen.BiomeDefaultFeatures
- XXX.data.worldgen.BootstrapContext
+ XXX.data.worldgen.Carvers
- XXX.data.worldgen.DesertVillagePools
+ XXX.data.worldgen.DimensionTypes
- XXX.data.worldgen.NoiseData
+ XXX.data.worldgen.package-info
+ XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.PlainVillagePools
+ XXX.data.worldgen.Pools
- XXX.data.worldgen.ProcessorLists
+ XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.SnowyVillagePools
- XXX.data.worldgen.Structures
+ XXX.data.worldgen.StructureSets
+ XXX.data.worldgen.SurfaceRuleData
- XXX.data.worldgen.TaigaVillagePools
+ XXX.data.worldgen.TerrainProvider
- XXX.data.worldgen.TrailRuinsStructurePools
+ XXX.data.worldgen.TrialChambersStructurePools
- XXX.data.worldgen.UpdateOneTwentyOnePools
+ XXX.data.worldgen.UpdateOneTwentyOneProcessorLists
+ XXX.data.worldgen.UpdateOneTwentyOneStructures
- XXX.data.worldgen.UpdateOneTwentyOneStructureSets
- XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.AreaEffectCloudPotionFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BannerPatternFormatFix
- XXX.datafix.fixes.BeehiveFieldRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlendingDataFix
- XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityRenameFix
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockPosFormatAndRenamesFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.CauldronRenameFix
- XXX.datafix.fixes.CavesAndCliffsRenames
+ XXX.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
+ XXX.datafix.fixes.ChunkDeleteLightFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.DecoratedPotFieldRenameFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
- XXX.datafix.fixes.ItemStackComponentizationFix
- XXX.datafix.fixes.package-info
- XXX.datafix.fixes.TippedArrowPotionToItemFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.VariantRenameFix
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WeaponSmithChestLootTableFix
- XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- XXX.datafix.fixes.WriteAndReadFix
+ XXX.datafix.fixes.ZombieVillagerRebuildXpFix
- XXX.datafix.schemas.NamespacedSchema
+ XXX.datafix.schemas.NamespacedSchema$1
- XXX.datafix.schemas.V100
+ XXX.datafix.schemas.V102
- XXX.datafix.schemas.V1022
+ XXX.datafix.schemas.V106
- XXX.datafix.schemas.V107
+ XXX.datafix.schemas.V1125
- XXX.datafix.schemas.V135
+ XXX.datafix.schemas.V143
- XXX.datafix.schemas.V1451
+ XXX.datafix.schemas.V1451_1
- XXX.datafix.schemas.V1451_2
+ XXX.datafix.schemas.V1451_3
- XXX.datafix.schemas.V1451_4
+ XXX.datafix.schemas.V1451_5
- XXX.datafix.schemas.V1451_6
+ XXX.datafix.schemas.V1451_6$1
- XXX.datafix.schemas.V1451_6$2
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1466
+ XXX.datafix.schemas.V1470
- XXX.datafix.schemas.V1481
+ XXX.datafix.schemas.V1483
- XXX.datafix.schemas.V1486
+ XXX.datafix.schemas.V1510
- XXX.datafix.schemas.V1800
+ XXX.datafix.schemas.V1801
- XXX.datafix.schemas.V1904
+ XXX.datafix.schemas.V1906
- XXX.datafix.schemas.V1909
+ XXX.datafix.schemas.V1920
- XXX.datafix.schemas.V1928
+ XXX.datafix.schemas.V1929
- XXX.datafix.schemas.V1931
+ XXX.datafix.schemas.V2100
- XXX.datafix.schemas.V2501
+ XXX.datafix.schemas.V2502
- XXX.datafix.schemas.V2505
+ XXX.datafix.schemas.V2509
- XXX.datafix.schemas.V2519
+ XXX.datafix.schemas.V2522
- XXX.datafix.schemas.V2551
+ XXX.datafix.schemas.V2568
- XXX.datafix.schemas.V2571
+ XXX.datafix.schemas.V2684
- XXX.datafix.schemas.V2686
+ XXX.datafix.schemas.V2688
- XXX.datafix.schemas.V2704
+ XXX.datafix.schemas.V2707
- XXX.datafix.schemas.V2831
+ XXX.datafix.schemas.V2832
- XXX.datafix.schemas.V2842
+ XXX.datafix.schemas.V3076
- XXX.datafix.schemas.V3078
+ XXX.datafix.schemas.V3081
- XXX.datafix.schemas.V3082
+ XXX.datafix.schemas.V3083
- XXX.datafix.schemas.V3202
+ XXX.datafix.schemas.V3203
- XXX.datafix.schemas.V3204
+ XXX.datafix.schemas.V3325
- XXX.datafix.schemas.V3326
+ XXX.datafix.schemas.V3327
- XXX.datafix.schemas.V3328
+ XXX.datafix.schemas.V3438
- XXX.datafix.schemas.V3448
+ XXX.datafix.schemas.V3682
- XXX.datafix.schemas.V3683
+ XXX.datafix.schemas.V3685
- XXX.datafix.schemas.V3689
+ XXX.datafix.schemas.V3799
- XXX.datafix.schemas.V3807
+ XXX.datafix.schemas.V3808
- XXX.datafix.schemas.V3808_1
+ XXX.datafix.schemas.V3816
- XXX.datafix.schemas.V3818
- XXX.datafix.schemas.V3818_4
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.EndDragonFight$Data
- XXX.dimension.end.package-info
- XXX.entity.ai.Brain
+ XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$MemoryValue
+ XXX.entity.ai.Brain$Provider
+ XXX.entity.ai.package-info
+ XXX.entity.ambient.AmbientCreature
- XXX.entity.ambient.Bat
+ XXX.entity.ambient.package-info
- XXX.entity.animal.AbstractFish
+ XXX.entity.animal.AbstractFish$FishMoveControl
- XXX.entity.animal.AbstractFish$FishSwimGoal
+ XXX.entity.animal.AbstractGolem
- XXX.entity.animal.AbstractSchoolingFish
+ XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- XXX.entity.animal.Animal
+ XXX.entity.animal.Bee
- XXX.entity.animal.Bee$1
+ XXX.entity.animal.Bee$BaseBeeGoal
- XXX.entity.animal.Bee$BeeAttackGoal
+ XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
- XXX.entity.animal.Bee$BeeEnterHiveGoal
+ XXX.entity.animal.Bee$BeeGoToHiveGoal
- XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ XXX.entity.animal.Bee$BeeGrowCropGoal
- XXX.entity.animal.Bee$BeeHurtByOtherGoal
+ XXX.entity.animal.Bee$BeeLocateHiveGoal
- XXX.entity.animal.Bee$BeeLookControl
+ XXX.entity.animal.Bee$BeePollinateGoal
- XXX.entity.animal.Bee$BeeWanderGoal
+ XXX.entity.animal.Bucketable
- XXX.entity.animal.Cat
+ XXX.entity.animal.Cat$CatAvoidEntityGoal
- XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
+ XXX.entity.animal.Cat$CatTemptGoal
- XXX.entity.animal.CatVariant
+ XXX.entity.animal.Chicken
- XXX.entity.animal.Cod
+ XXX.entity.animal.Cow
- XXX.entity.animal.Dolphin
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.Fox$DefendTrustedTargetGoal
+ XXX.entity.animal.Fox$FaceplantGoal
- XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
+ XXX.entity.animal.Fox$FoxBehaviorGoal
- XXX.entity.animal.Fox$FoxBreedGoal
+ XXX.entity.animal.Fox$FoxEatBerriesGoal
- XXX.entity.animal.Fox$FoxFloatGoal
+ XXX.entity.animal.Fox$FoxFollowParentGoal
- XXX.entity.animal.Fox$FoxGroupData
+ XXX.entity.animal.Fox$FoxLookAtPlayerGoal
- XXX.entity.animal.Fox$FoxLookControl
+ XXX.entity.animal.Fox$FoxMeleeAttackGoal
- XXX.entity.animal.Fox$FoxMoveControl
+ XXX.entity.animal.Fox$FoxPanicGoal
- XXX.entity.animal.Fox$FoxPounceGoal
+ XXX.entity.animal.Fox$FoxSearchForItemsGoal
- XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
+ XXX.entity.animal.Fox$PerchAndSearchGoal
- XXX.entity.animal.Fox$SeekShelterGoal
+ XXX.entity.animal.Fox$SleepGoal
- XXX.entity.animal.Fox$StalkPreyGoal
+ XXX.entity.animal.Fox$Type
- XXX.entity.animal.FrogVariant
+ XXX.entity.animal.IronGolem
- XXX.entity.trialspawner.package-info
+ XXX.entity.trialspawner.PlayerDetector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
+ XXX.entity.trialspawner.TrialSpawner
- XXX.entity.trialspawner.TrialSpawner$StateAccessor
+ XXX.entity.trialspawner.TrialSpawnerConfig
- XXX.entity.trialspawner.TrialSpawnerData
+ XXX.entity.trialspawner.TrialSpawnerState
- XXX.entity.trialspawner.TrialSpawnerState$1
+ XXX.entity.trialspawner.TrialSpawnerState$LightLevel
- XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
+ XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
+ XXX.entity.vault.package-info
+ XXX.entity.vault.VaultBlockEntity
- XXX.entity.vault.VaultBlockEntity$Client
+ XXX.entity.vault.VaultBlockEntity$Server
- XXX.entity.vault.VaultClientData
+ XXX.entity.vault.VaultConfig
- XXX.entity.vault.VaultServerData
+ XXX.entity.vault.VaultSharedData
- XXX.entity.vault.VaultState
+ XXX.entity.vault.VaultState$1
- XXX.entity.vault.VaultState$2
+ XXX.entity.vault.VaultState$3
- XXX.entity.vault.VaultState$4
+ XXX.entity.vault.VaultState$5
- XXX.entity.vault.VaultState$LightLevel
+ XXX.feature.configurations.BlockColumnConfiguration
- XXX.feature.configurations.BlockColumnConfiguration$Layer
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration
- XXX.feature.configurations.CountConfiguration
+ XXX.feature.configurations.DeltaFeatureConfiguration
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.DripstoneClusterConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.GeodeConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LargeDripstoneConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MultifaceGrowthConfiguration
+ XXX.feature.configurations.NetherForestVegetationConfig
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$TargetBlockState
+ XXX.feature.configurations.package-info
+ XXX.feature.configurations.PointedDripstoneConfiguration
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.ReplaceSphereConfiguration
- XXX.feature.configurations.RootSystemConfiguration
+ XXX.feature.configurations.SculkPatchConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.TwistingVinesConfig
+ XXX.feature.configurations.UnderwaterMagmaConfiguration
- XXX.feature.configurations.VegetationPatchConfiguration
- XXX.feature.featuresize.FeatureSize
+ XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.featuresize.TwoLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.CherryFoliagePlacer
+ XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.rootplacers.AboveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacer
+ XXX.feature.rootplacers.package-info
+ XXX.feature.rootplacers.RootPlacer
- XXX.feature.rootplacers.RootPlacerType
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.AttachedToLeavesDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecorator$Context
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.CherryTrunkPlacer
+ XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.ForkingTrunkPlacer
+ XXX.feature.trunkplacers.GiantTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
- XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gameevent.vibrations.VibrationSystem
- XXX.gameevent.vibrations.VibrationSystem$Data
+ XXX.gameevent.vibrations.VibrationSystem$Listener
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.gameevent.vibrations.VibrationSystem$User
+ XXX.gametest.framework.AfterBatch
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.ExhaustedAttemptsException
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchFactory
+ XXX.gametest.framework.GameTestBatchListener
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestHelper$1
- XXX.gametest.framework.GameTestHelper$2
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestRunner$1
- XXX.gametest.framework.GameTestRunner$Builder
+ XXX.gametest.framework.GameTestRunner$GameTestBatcher
- XXX.gametest.framework.GameTestRunner$StructureSpawner
+ XXX.gametest.framework.GameTestSequence
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.GlobalTestReporter
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
- XXX.gametest.framework.ReportGameListener
+ XXX.gametest.framework.RetryOptions
- XXX.gametest.framework.StructureBlockPosFinder
+ XXX.gametest.framework.StructureGridSpawner
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$Runner
+ XXX.gametest.framework.TestCommand$TestBatchSummaryDisplayer
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFinder
- XXX.gametest.framework.TestFinder$Builder
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestFunctionFinder
- XXX.gametest.framework.TestReporter
- XXX.goal.target.DefendVillageTargetGoal
+ XXX.goal.target.HurtByTargetGoal
- XXX.goal.target.NearestAttackableTargetGoal
+ XXX.goal.target.NearestAttackableWitchTargetGoal
- XXX.goal.target.NearestHealableRaiderTargetGoal
+ XXX.goal.target.NonTameRandomTargetGoal
- XXX.goal.target.OwnerHurtByTargetGoal
+ XXX.goal.target.OwnerHurtTargetGoal
- XXX.goal.target.package-info
- XXX.goal.target.ResetUniversalAngerTargetGoal
+ XXX.goal.target.TargetGoal
- XXX.item.component.BlockItemStateProperties
- XXX.item.component.BundleContents$Mutable
- XXX.item.component.CustomData
- XXX.item.component.DebugStickState
- XXX.item.component.FireworkExplosion
- XXX.item.component.Fireworks
- XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Entry
- XXX.item.component.ItemContainerContents$Slot
- XXX.item.component.LodestoneTarget
- XXX.item.component.MapDecorations$Entry
- XXX.item.component.MapPostProcessing
- XXX.item.component.SeededContainerLoot
- XXX.item.component.SuspiciousStewEffects$Entry
- XXX.item.component.Unbreakable
- XXX.item.component.WrittenBookContent
- XXX.item.enchantment.ItemEnchantments
- XXX.item.trading.ItemCost
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.biome.AmbientMoodSettings
- XXX.level.biome.AmbientParticleSettings
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeGenerationSettings$PlainBuilder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSources
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.Climate
- XXX.level.biome.Climate$DistanceMetric
+ XXX.level.biome.Climate$Parameter
- XXX.level.biome.Climate$ParameterList
+ XXX.level.biome.Climate$ParameterPoint
- XXX.level.biome.Climate$RTree
+ XXX.level.biome.Climate$RTree$Leaf
- XXX.level.biome.Climate$RTree$Node
+ XXX.level.biome.Climate$RTree$SubTree
- XXX.level.biome.Climate$Sampler
+ XXX.level.biome.Climate$SpawnFinder
- XXX.level.biome.Climate$SpawnFinder$Result
+ XXX.level.biome.Climate$TargetPoint
- XXX.level.biome.FeatureSorter
+ XXX.level.biome.FeatureSorter$1FeatureData
- XXX.level.biome.FeatureSorter$StepFeatureData
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.MobSpawnSettings
+ XXX.level.biome.MobSpawnSettings$Builder
- XXX.level.biome.MobSpawnSettings$MobSpawnCost
+ XXX.level.biome.MobSpawnSettings$SpawnerData
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- XXX.level.biome.MultiNoiseBiomeSourceParameterLists
+ XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.package-info
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCandleBlock
- XXX.level.block.AbstractCauldronBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AmethystBlock
- XXX.level.block.AmethystClusterBlock
+ XXX.level.block.AmethystClusterBlock$1
- XXX.level.block.AnvilBlock
+ XXX.level.block.AttachedStemBlock
- XXX.level.block.AzaleaBlock
+ XXX.level.block.BambooSaplingBlock
- XXX.level.block.BambooStalkBlock
+ XXX.level.block.BannerBlock
- XXX.level.block.BarrelBlock
+ XXX.level.block.BarrierBlock
- XXX.level.block.BaseCoralFanBlock
+ XXX.level.block.BaseCoralPlantBlock
- XXX.level.block.BaseCoralPlantTypeBlock
+ XXX.level.block.BaseCoralWallFanBlock
- XXX.level.block.BaseEntityBlock
+ XXX.level.block.BaseFireBlock
- XXX.level.block.BasePressurePlateBlock
+ XXX.level.block.BaseRailBlock
- XXX.level.block.BaseRailBlock$1
+ XXX.level.block.BaseTorchBlock
- XXX.level.block.BeaconBeamBlock
+ XXX.level.block.BeaconBlock
- XXX.level.block.BedBlock
+ XXX.level.block.BedBlock$1
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BigDripleafBlock
+ XXX.level.block.BigDripleafStemBlock
- XXX.level.block.BigDripleafStemBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$BlockStatePairKey
+ XXX.level.block.Blocks
- XXX.level.block.BlockTypes
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BonemealableBlock$1
- XXX.level.block.BonemealableBlock$Type
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BrushableBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CalibratedSculkSensorBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CandleBlock
- XXX.level.block.CandleCakeBlock
+ XXX.level.block.CarpetBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.CaveVines
+ XXX.level.block.CaveVinesBlock
- XXX.level.block.CaveVinesPlantBlock
+ XXX.level.block.CeilingHangingSignBlock
- XXX.level.block.ChainBlock
+ XXX.level.block.ChainBlock$1
- XXX.level.block.ChangeOverTimeBlock
+ XXX.level.block.CherryLeavesBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$4
- XXX.level.block.ChiseledBookShelfBlock
+ XXX.level.block.ChiseledBookShelfBlock$1
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.CocoaBlock$1
- XXX.level.block.ColoredFallingBlock
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CopperBulbBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CrafterBlock
+ XXX.level.block.CrafterBlock$1
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
+ XXX.level.block.DecoratedPotBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DirtPathBlock
+ XXX.level.block.DispenserBlock
- XXX.level.block.DoorBlock
+ XXX.level.block.DoorBlock$1
- XXX.level.block.DoubleBlockCombiner
+ XXX.level.block.DoubleBlockCombiner$BlockType
- XXX.level.block.DoubleBlockCombiner$Combiner
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- XXX.level.block.DoublePlantBlock
+ XXX.level.block.DragonEggBlock
- XXX.level.block.DropExperienceBlock
+ XXX.level.block.DropperBlock
- XXX.level.block.EnchantmentTableBlock
+ XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
- XXX.level.block.EntityBlock
+ XXX.level.block.EquipableCarvedPumpkinBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.Fallable
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GameMasterBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GlowLichenBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.GrowingPlantBlock
+ XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.GrowingPlantHeadBlock
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.InfestedRotatedPillarBlock
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LadderBlock$1
+ XXX.level.block.LanternBlock
- XXX.level.block.LavaCauldronBlock
+ XXX.level.block.LayeredCauldronBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LecternBlock$1
+ XXX.level.block.LevelEvent
- XXX.level.block.LeverBlock
+ XXX.level.block.LeverBlock$1
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MangroveLeavesBlock
+ XXX.level.block.MangrovePropaguleBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
+ XXX.level.block.MossBlock
- XXX.level.block.MudBlock
+ XXX.level.block.MultifaceBlock
- XXX.level.block.MultifaceSpreader
+ XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
- XXX.level.block.MultifaceSpreader$SpreadConfig
+ XXX.level.block.MultifaceSpreader$SpreadPos
- XXX.level.block.MultifaceSpreader$SpreadPredicate
+ XXX.level.block.MultifaceSpreader$SpreadType
- XXX.level.block.MultifaceSpreader$SpreadType$1
+ XXX.level.block.MultifaceSpreader$SpreadType$2
- XXX.level.block.MultifaceSpreader$SpreadType$3
+ XXX.level.block.MushroomBlock
- XXX.level.block.MyceliumBlock
+ XXX.level.block.NetherPortalBlock
- XXX.level.block.NetherPortalBlock$1
- XXX.level.block.NetherrackBlock
+ XXX.level.block.NetherSproutsBlock
- XXX.level.block.NetherVines
+ XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.NyliumBlock
+ XXX.level.block.ObserverBlock
- XXX.level.block.package-info
- XXX.level.block.PiglinWallSkullBlock
+ XXX.level.block.PinkPetalsBlock
- XXX.level.block.PipeBlock
+ XXX.level.block.PitcherCropBlock
- XXX.level.block.PitcherCropBlock$PosAndState
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
- XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.PotatoBlock
- XXX.level.block.PowderSnowBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailBlock$1
+ XXX.level.block.RailState
- XXX.level.block.RailState$1
- XXX.level.block.RedstoneLampBlock
+ XXX.level.block.RedStoneOreBlock
+ XXX.level.block.RedstoneTorchBlock
- XXX.level.block.RedstoneTorchBlock$Toggle
+ XXX.level.block.RedstoneWallTorchBlock
- XXX.level.block.RedStoneWireBlock
+ XXX.level.block.RedStoneWireBlock$1
- XXX.level.block.RenderShape
+ XXX.level.block.RepeaterBlock
- XXX.level.block.RespawnAnchorBlock
+ XXX.level.block.RespawnAnchorBlock$1
- XXX.level.block.RodBlock
+ XXX.level.block.RodBlock$1
- XXX.level.block.RootedDirtBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
- XXX.level.block.SculkBehaviour
+ XXX.level.block.SculkBehaviour$1
- XXX.level.block.SculkBlock
+ XXX.level.block.SculkCatalystBlock
- XXX.level.block.SculkSensorBlock
+ XXX.level.block.SculkShriekerBlock
- XXX.level.block.SculkSpreader
+ XXX.level.block.SculkSpreader$ChargeCursor
- XXX.level.block.SculkVeinBlock
+ XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
+ XXX.level.block.SeagrassBlock
- XXX.level.block.SeaPickleBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmallDripleafBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnifferEggBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
+ XXX.level.block.SpongeBlock
- XXX.level.block.SporeBlossomBlock
+ XXX.level.block.SpreadingSnowyDirtBlock
- XXX.level.block.StainedGlassBlock
+ XXX.level.block.StainedGlassPaneBlock
- XXX.level.block.StairBlock
+ XXX.level.block.StairBlock$1
- XXX.level.block.StandingSignBlock
+ XXX.level.block.StemBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SupportType
- XXX.level.block.SupportType$1
+ XXX.level.block.SupportType$2
- XXX.level.block.SupportType$3
+ XXX.level.block.SuspiciousEffectHolder
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BlockColumn
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.CarvingMask
+ XXX.level.chunk.CarvingMask$Mask
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkAccess$TicksToSave
- XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGenerators
+ XXX.level.chunk.ChunkGeneratorStructureState
+ XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.dimension.BuiltinDimensionTypes
- XXX.level.dimension.DimensionDefaults
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.DimensionType$MonsterSettings
+ XXX.level.dimension.LevelStem
+ XXX.level.dimension.package-info
- XXX.level.entity.ChunkEntities
+ XXX.level.entity.ChunkStatusUpdateListener
- XXX.level.entity.EntityAccess
+ XXX.level.entity.EntityInLevelCallback
- XXX.level.entity.EntityInLevelCallback$1
+ XXX.level.entity.EntityLookup
- XXX.level.entity.EntityPersistentStorage
+ XXX.level.entity.EntitySection
- XXX.level.entity.EntitySectionStorage
+ XXX.level.entity.EntityTickList
- XXX.level.entity.EntityTypeTest
+ XXX.level.entity.EntityTypeTest$1
- XXX.level.entity.EntityTypeTest$2
+ XXX.level.entity.LevelCallback
- XXX.level.entity.LevelEntityGetter
+ XXX.level.entity.LevelEntityGetterAdapter
- XXX.level.entity.package-info
- XXX.level.entity.PersistentEntitySectionManager
+ XXX.level.entity.PersistentEntitySectionManager$Callback
- XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ XXX.level.entity.TransientEntitySectionManager
- XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.entity.Visibility
+ XXX.level.gameevent.BlockPositionSource
- XXX.level.gameevent.BlockPositionSource$Type
+ XXX.level.gameevent.DynamicGameEventListener
- XXX.level.gameevent.EntityPositionSource
+ XXX.level.gameevent.EntityPositionSource$Type
- XXX.level.gameevent.EuclideanGameEventListenerRegistry
+ XXX.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
- XXX.level.gameevent.GameEvent
+ XXX.level.gameevent.GameEvent$Context
- XXX.level.gameevent.GameEvent$ListenerInfo
+ XXX.level.gameevent.GameEventDispatcher
- XXX.level.gameevent.GameEventListener
+ XXX.level.gameevent.GameEventListener$DeliveryMode
- XXX.level.gameevent.GameEventListener$Provider
+ XXX.level.gameevent.GameEventListenerRegistry
- XXX.level.gameevent.GameEventListenerRegistry$1
+ XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- XXX.level.gameevent.package-info
- XXX.level.gameevent.PositionSource
+ XXX.level.gameevent.PositionSourceType
+ XXX.level.levelgen.Aquifer
- XXX.level.levelgen.Aquifer$1
+ XXX.level.levelgen.Aquifer$FluidPicker
- XXX.level.levelgen.Aquifer$FluidStatus
+ XXX.level.levelgen.Aquifer$NoiseBasedAquifer
- XXX.level.levelgen.Beardifier
+ XXX.level.levelgen.Beardifier$1
- XXX.level.levelgen.Beardifier$Rigid
+ XXX.level.levelgen.BelowZeroRetrogen
- XXX.level.levelgen.BelowZeroRetrogen$1
+ XXX.level.levelgen.BitRandomSource
- XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Line
- XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.Column$Ray
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.Density
- XXX.level.levelgen.DensityFunction
+ XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$FunctionContext
+ XXX.level.levelgen.DensityFunction$NoiseHolder
- XXX.level.levelgen.DensityFunction$SimpleFunction
+ XXX.level.levelgen.DensityFunction$SinglePointContext
- XXX.level.levelgen.DensityFunction$Visitor
+ XXX.level.levelgen.DensityFunctions
- XXX.level.levelgen.DensityFunctions$1
+ XXX.level.levelgen.DensityFunctions$Ap2
- XXX.level.levelgen.DensityFunctions$BeardifierMarker
+ XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
- XXX.level.levelgen.DensityFunctions$BlendAlpha
+ XXX.level.levelgen.DensityFunctions$BlendDensity
- XXX.level.levelgen.DensityFunctions$BlendOffset
+ XXX.level.levelgen.DensityFunctions$Clamp
- XXX.level.levelgen.DensityFunctions$Constant
+ XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
- XXX.level.levelgen.DensityFunctions$HolderHolder
+ XXX.level.levelgen.DensityFunctions$Mapped
- XXX.level.levelgen.DensityFunctions$Mapped$Type
+ XXX.level.levelgen.DensityFunctions$Marker
- XXX.level.levelgen.DensityFunctions$Marker$Type
+ XXX.level.levelgen.DensityFunctions$MarkerOrMarked
- XXX.level.levelgen.DensityFunctions$MulOrAdd
+ XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
- XXX.level.levelgen.DensityFunctions$Noise
+ XXX.level.levelgen.DensityFunctions$PureTransformer
- XXX.level.levelgen.DensityFunctions$RangeChoice
+ XXX.level.levelgen.DensityFunctions$Shift
- XXX.level.levelgen.DensityFunctions$ShiftA
+ XXX.level.levelgen.DensityFunctions$ShiftB
+ XXX.level.levelgen.DensityFunctions$ShiftedNoise
- XXX.level.levelgen.DensityFunctions$ShiftNoise
- XXX.level.levelgen.DensityFunctions$Spline
+ XXX.level.levelgen.DensityFunctions$Spline$Coordinate
- XXX.level.levelgen.DensityFunctions$Spline$Point
+ XXX.level.levelgen.DensityFunctions$TransformerWithContext
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- XXX.level.levelgen.DensityFunctions$YClampedGradient
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.GeodeBlockSettings
- XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.LegacyRandomSource
- XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ XXX.level.levelgen.MarsagliaPolarGaussian
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$1
+ XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendAlpha
+ XXX.level.levelgen.NoiseChunk$BlendOffset
- XXX.level.levelgen.NoiseChunk$BlockStateFiller
+ XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheAllInCell
+ XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$FlatCache
+ XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- XXX.level.levelgen.NoiseChunk$NoiseInterpolator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouter
+ XXX.level.levelgen.NoiseRouterData
- XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- XXX.level.levelgen.Noises
+ XXX.level.levelgen.NoiseSettings
+ XXX.level.levelgen.OreVeinifier
- XXX.level.levelgen.OreVeinifier$VeinType
- XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.PositionalRandomFactory
- XXX.level.levelgen.RandomState
+ XXX.level.levelgen.RandomState$1
- XXX.level.levelgen.RandomState$1NoiseWiringHelper
+ XXX.level.levelgen.RandomSupport
- XXX.level.levelgen.RandomSupport$Seed128bit
+ XXX.level.levelgen.SingleThreadedRandomSource
- XXX.level.levelgen.SurfaceRules
+ XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
- XXX.level.levelgen.SurfaceRules$Bandlands
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ XXX.level.levelgen.SurfaceRules$BlockRuleSource
- XXX.level.levelgen.SurfaceRules$Condition
+ XXX.level.levelgen.SurfaceRules$ConditionSource
- XXX.level.levelgen.SurfaceRules$Context
+ XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- XXX.level.levelgen.SurfaceRules$Context$HoleCondition
+ XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ XXX.level.levelgen.SurfaceRules$Hole
- XXX.level.levelgen.SurfaceRules$LazyCondition
+ XXX.level.levelgen.SurfaceRules$LazyXZCondition
- XXX.level.levelgen.SurfaceRules$LazyYCondition
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ XXX.level.levelgen.SurfaceRules$NotCondition
- XXX.level.levelgen.SurfaceRules$NotConditionSource
+ XXX.level.levelgen.SurfaceRules$RuleSource
- XXX.level.levelgen.SurfaceRules$SequenceRule
+ XXX.level.levelgen.SurfaceRules$SequenceRuleSource
- XXX.level.levelgen.SurfaceRules$StateRule
+ XXX.level.levelgen.SurfaceRules$Steep
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- XXX.level.levelgen.SurfaceRules$SurfaceRule
+ XXX.level.levelgen.SurfaceRules$Temperature
- XXX.level.levelgen.SurfaceRules$TestRule
+ XXX.level.levelgen.SurfaceRules$TestRuleSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- XXX.level.levelgen.SurfaceRules$WaterConditionSource
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- XXX.level.levelgen.SurfaceRules$YConditionSource
+ XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- XXX.level.levelgen.SurfaceSystem
+ XXX.level.levelgen.SurfaceSystem$1
- XXX.level.levelgen.ThreadSafeLegacyRandomSource
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
+ XXX.level.levelgen.WorldDimensions
- XXX.level.levelgen.WorldDimensions$1Entry
+ XXX.level.levelgen.WorldDimensions$Complete
+ XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.WorldGenSettings
- XXX.level.levelgen.WorldOptions
+ XXX.level.levelgen.Xoroshiro128PlusPlus
- XXX.level.levelgen.XoroshiroRandomSource
+ XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.ChunkSkyLightSources
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$SectionState
- XXX.level.lighting.LayerLightSectionStorage$SectionType
- XXX.level.lighting.LeveledPriorityQueue
+ XXX.level.lighting.LeveledPriorityQueue$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEngine
+ XXX.level.lighting.LightEngine$QueueEntry
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightEngine$1
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.Fluid
+ XXX.level.material.Fluids
- XXX.level.material.FluidState
- XXX.level.material.FogType
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.MapColor
+ XXX.level.material.MapColor$Brightness
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.AmphibiousNodeEvaluator
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.Path$DebugData
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.PathType
- XXX.level.pathfinder.PathTypeCache
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.pathfinder.WalkNodeEvaluator$1
- XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalInfo
+ XXX.level.portal.PortalShape
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
+ XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ XXX.level.redstone.InstantNeighborUpdater
- XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedData$Factory
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DataVersion
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.FileNameDateFormatter
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelDataAndDimensions
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelCandidates
+ XXX.level.storage.LevelStorageSource$LevelDirectory
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelSummary$CorruptedLevelSummary
- XXX.level.storage.LevelSummary$SymlinkLevelSummary
+ XXX.level.storage.LevelVersion
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
- XXX.levelgen.blending.BlendingData$BiomeConsumer
+ XXX.levelgen.blending.BlendingData$DensityConsumer
- XXX.levelgen.blending.BlendingData$HeightConsumer
+ XXX.levelgen.blending.package-info
- XXX.levelgen.blockpredicates.AllOfPredicate
+ XXX.levelgen.blockpredicates.AnyOfPredicate
- XXX.levelgen.blockpredicates.BlockPredicate
+ XXX.levelgen.blockpredicates.BlockPredicateType
- XXX.levelgen.blockpredicates.CombiningPredicate
+ XXX.levelgen.blockpredicates.HasSturdyFacePredicate
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlocksPredicate
+ XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
+ XXX.levelgen.blockpredicates.MatchingFluidsPredicate
- XXX.levelgen.blockpredicates.NotPredicate
- XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.WouldSurvivePredicate
+ XXX.levelgen.carver.CanyonCarverConfiguration
- XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CarverDebugSettings
- XXX.levelgen.carver.CarvingContext
+ XXX.levelgen.carver.CaveCarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.WorldCarver
- XXX.levelgen.carver.WorldCarver$CarveSkipChecker
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockColumnFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskFeature
- XXX.levelgen.feature.DripstoneClusterFeature
+ XXX.levelgen.feature.DripstoneUtils
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FeatureCountTracker
+ XXX.levelgen.feature.FeatureCountTracker$1
- XXX.levelgen.feature.FeatureCountTracker$FeatureData
+ XXX.levelgen.feature.FeatureCountTracker$LevelData
- XXX.levelgen.feature.FeaturePlaceContext
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.FossilFeatureConfiguration
- XXX.levelgen.feature.GeodeFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.LakeFeature$Configuration
+ XXX.levelgen.feature.LargeDripstoneFeature
- XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.MultifaceGrowthFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PointedDripstoneFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SculkPatchFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TreeFeature$1
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorPreset
- XXX.levelgen.flat.FlatLevelGeneratorPresets
+ XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
- XXX.levelgen.heightproviders.BiasedToBottomHeight
+ XXX.levelgen.heightproviders.ConstantHeight
- XXX.levelgen.heightproviders.HeightProvider
+ XXX.levelgen.heightproviders.HeightProviderType
- XXX.levelgen.heightproviders.package-info
- XXX.levelgen.heightproviders.TrapezoidHeight
+ XXX.levelgen.heightproviders.UniformHeight
- XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
+ XXX.levelgen.heightproviders.WeightedListHeight
+ XXX.levelgen.material.MaterialRuleList
+ XXX.levelgen.material.package-info
- XXX.levelgen.material.WorldGenMaterialRule
+ XXX.levelgen.placement.BiomeFilter
- XXX.levelgen.placement.BlockPredicateFilter
+ XXX.levelgen.placement.CarvingMaskPlacement
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CountOnEveryLayerPlacement
- XXX.levelgen.placement.CountPlacement
+ XXX.levelgen.placement.EnvironmentScanPlacement
+ XXX.levelgen.placement.HeightmapPlacement
- XXX.levelgen.placement.HeightRangePlacement
- XXX.levelgen.placement.InSquarePlacement
+ XXX.levelgen.placement.NoiseBasedCountPlacement
- XXX.levelgen.placement.NoiseThresholdCountPlacement
+ XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.PlacedFeature
- XXX.levelgen.placement.PlacementContext
+ XXX.levelgen.placement.PlacementFilter
- XXX.levelgen.placement.PlacementModifier
+ XXX.levelgen.placement.PlacementModifierType
- XXX.levelgen.placement.RandomOffsetPlacement
+ XXX.levelgen.placement.RarityFilter
- XXX.levelgen.placement.RepeatingPlacement
+ XXX.levelgen.placement.SurfaceRelativeThresholdFilter
- XXX.levelgen.placement.SurfaceWaterDepthFilter
+ XXX.levelgen.presets.package-info
- XXX.levelgen.presets.WorldPreset
+ XXX.levelgen.presets.WorldPresets
- XXX.levelgen.presets.WorldPresets$Bootstrap
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuiltinStructures
- XXX.levelgen.structure.BuiltinStructureSets
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.PostPlacementProcessor
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.SinglePieceStructure
+ XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
- XXX.levelgen.structure.Structure
+ XXX.levelgen.structure.Structure$GenerationContext
- XXX.levelgen.structure.Structure$GenerationStub
+ XXX.levelgen.structure.Structure$StructureSettings
- XXX.levelgen.structure.StructureCheck
+ XXX.levelgen.structure.StructureCheckResult
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructurePieceAccessor
+ XXX.levelgen.structure.StructureSet
- XXX.levelgen.structure.StructureSet$StructureSelectionEntry
+ XXX.levelgen.structure.StructureSpawnOverride
- XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureType
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.TerrainAdjustment
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.NormalNoise$NoiseParameters
- XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.login.custom.CustomQueryAnswerPayload
+ XXX.login.custom.CustomQueryPayload
- XXX.login.custom.DiscardedQueryAnswerPayload
+ XXX.login.custom.DiscardedQueryPayload
- XXX.login.custom.package-info
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.NestedLootTable
+ XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaType
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyComponentsFunction$1
- XXX.loot.functions.CopyComponentsFunction$Source
- XXX.loot.functions.CopyCustomDataFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- XXX.loot.functions.CopyCustomDataFunction$Path
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FunctionReference
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetInstrumentFunction
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetNameFunction
- XXX.loot.packs.package-info
- XXX.loot.packs.TradeRebalanceChestLoot
+ XXX.loot.packs.TradeRebalanceLootTableProvider
- XXX.loot.packs.UpdateOneTwentyOneBlockLoot
+ XXX.loot.packs.UpdateOneTwentyOneChestLoot
- XXX.loot.packs.UpdateOneTwentyOneEntityLoot
+ XXX.loot.packs.UpdateOneTwentyOneLootTableProvider
- XXX.loot.packs.UpdateOneTwentyOneShearingLoot
- XXX.minecraft.data.package-info
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.Language$1
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.CompoundTag$2
- XXX.minecraft.nbt.DoubleTag
+ XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag
+ XXX.minecraft.nbt.EndTag$1
- XXX.minecraft.nbt.FloatTag
+ XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag
+ XXX.minecraft.nbt.IntArrayTag$1
- XXX.minecraft.nbt.IntTag
+ XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
+ XXX.minecraft.nbt.ListTag$2
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounterException
+ XXX.minecraft.nbt.NbtException
- XXX.minecraft.nbt.NbtFormatException
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
+ XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
- XXX.minecraft.nbt.NbtOps$HomogenousListCollector
+ XXX.minecraft.nbt.NbtOps$InitialListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ReportedNbtException
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
- XXX.minecraft.nbt.SnbtPrinterTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor$EntryResult
+ XXX.minecraft.nbt.StreamTagVisitor$ValueResult
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.StringTagVisitor
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagType$2
- XXX.minecraft.nbt.TagType$StaticSize
+ XXX.minecraft.nbt.TagType$VariableSize
- XXX.minecraft.nbt.TagTypes
+ XXX.minecraft.nbt.TagVisitor
- XXX.minecraft.nbt.TextComponentTagVisitor
- XXX.minecraft.network.BandwidthDebugMonitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.ClientboundPacketListener
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$3
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.HandlerNames
+ XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.PacketSendListener$1
+ XXX.minecraft.network.PacketSendListener$2
- XXX.minecraft.network.ProtocolInfo
+ XXX.minecraft.network.ProtocolInfo$Unbound
- XXX.minecraft.network.ProtocolSwapHandler
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.RegistryFriendlyByteBuf
+ XXX.minecraft.network.ServerboundPacketListener
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.TickablePacketListener
- XXX.minecraft.network.UnconfiguredPipelineHandler
+ XXX.minecraft.network.UnconfiguredPipelineHandler$Inbound
- XXX.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
+ XXX.minecraft.network.UnconfiguredPipelineHandler$Outbound
- XXX.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
+ XXX.minecraft.network.Utf8String
- XXX.minecraft.network.VarInt
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.network.VarLong
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.references.Blocks
+ XXX.minecraft.references.Items
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
- XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$LoadingFunction
+ XXX.minecraft.resources.RegistryDataLoader$RegistryData
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryOps$1
- XXX.minecraft.resources.RegistryOps$2
+ XXX.minecraft.resources.RegistryOps$RegistryInfo
- XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
+ XXX.minecraft.resources.ResourceKey
- XXX.minecraft.resources.ResourceKey$InternKey
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Dummy
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.Main
- XXX.minecraft.server.Main$1
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$Data
+ XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.ReloadableServerResources
+ XXX.minecraft.server.ReloadableServerResources$1
- XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
+ XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- XXX.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerInfo
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.ServerTickRateManager
- XXX.minecraft.server.Services
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$DataLoadContext
- XXX.minecraft.server.WorldLoader$DataLoadOutput
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
- XXX.minecraft.util.ExtraCodecs$7
- XXX.models.blockstates.BlockStateGenerator
+ XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
+ XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$C1
+ XXX.models.blockstates.PropertyDispatch$C2
- XXX.models.blockstates.PropertyDispatch$C3
+ XXX.models.blockstates.PropertyDispatch$C4
- XXX.models.blockstates.PropertyDispatch$C5
+ XXX.models.blockstates.PropertyDispatch$PentaFunction
- XXX.models.blockstates.PropertyDispatch$QuadFunction
+ XXX.models.blockstates.PropertyDispatch$TriFunction
- XXX.models.blockstates.Selector
+ XXX.models.blockstates.Variant
- XXX.models.blockstates.VariantProperties
+ XXX.models.blockstates.VariantProperties$Rotation
- XXX.models.blockstates.VariantProperty
+ XXX.models.blockstates.VariantProperty$Value
+ XXX.models.model.DelegatedModel
- XXX.models.model.ModelLocationUtils
+ XXX.models.model.ModelTemplate
- XXX.models.model.ModelTemplate$JsonFactory
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
- XXX.nbt.visitors.CollectFields
+ XXX.nbt.visitors.CollectToTag
- XXX.nbt.visitors.FieldSelector
+ XXX.nbt.visitors.FieldTree
+ XXX.nbt.visitors.package-info
- XXX.nbt.visitors.SkipAll
+ XXX.nbt.visitors.SkipAll$1
- XXX.nbt.visitors.SkipFields
- XXX.network.chat.ChatDecorator
+ XXX.network.chat.ChatType
- XXX.network.chat.ChatType$Bound
+ XXX.network.chat.ChatTypeDecoration
- XXX.network.chat.ChatTypeDecoration$Parameter
+ XXX.network.chat.ChatTypeDecoration$Parameter$Selector
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.Component$SerializerAdapter
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentContents$Type
- XXX.network.chat.ComponentSerialization
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.HoverEvent$LegacyConverter
- XXX.network.codec.ByteBufCodecs$24
- XXX.network.codec.ByteBufCodecs$26
- XXX.network.codec.ByteBufCodecs$3
+ XXX.network.codec.ByteBufCodecs$4
- XXX.network.codec.ByteBufCodecs$5
+ XXX.network.codec.ByteBufCodecs$6
- XXX.network.codec.ByteBufCodecs$7
+ XXX.network.codec.ByteBufCodecs$8
- XXX.network.codec.ByteBufCodecs$9
+ XXX.network.codec.IdDispatchCodec
- XXX.network.codec.IdDispatchCodec$Builder
+ XXX.network.codec.IdDispatchCodec$Entry
- XXX.network.codec.package-info
- XXX.network.codec.StreamCodec
+ XXX.network.codec.StreamCodec$1
- XXX.network.codec.StreamCodec$10
+ XXX.network.codec.StreamCodec$11
- XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$2
+ XXX.network.codec.StreamCodec$3
- XXX.network.codec.StreamCodec$4
+ XXX.network.codec.StreamCodec$5
- XXX.network.codec.StreamCodec$6
+ XXX.network.codec.StreamCodec$7
- XXX.network.codec.StreamCodec$8
+ XXX.network.codec.StreamCodec$9
- XXX.network.codec.StreamCodec$CodecOperation
+ XXX.network.codec.StreamDecoder
- XXX.network.codec.StreamEncoder
+ XXX.network.codec.StreamMemberEncoder
- XXX.network.protocol.BundleDelimiterPacket
+ XXX.network.protocol.BundlePacket
- XXX.network.protocol.BundlerInfo
+ XXX.network.protocol.BundlerInfo$1
- XXX.network.protocol.BundlerInfo$1$1
+ XXX.network.protocol.BundlerInfo$Bundler
- XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketType
+ XXX.network.protocol.PacketUtils
- XXX.network.protocol.ProtocolCodecBuilder
+ XXX.network.protocol.ProtocolInfoBuilder
- XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
+ XXX.network.protocol.ProtocolInfoBuilder$Implementation
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$ForValueType
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.package-info
- XXX.network.syncher.SyncedDataHolder
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$Builder
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
- XXX.pools.alias.Direct
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.Random
+ XXX.pools.alias.RandomGroup
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundDisconnectPacket
+ XXX.protocol.common.ClientboundKeepAlivePacket
- XXX.protocol.common.ClientboundPingPacket
+ XXX.protocol.common.ClientboundResourcePackPopPacket
- XXX.protocol.common.ClientboundResourcePackPushPacket
+ XXX.protocol.common.ClientboundStoreCookiePacket
- XXX.protocol.common.ClientboundTransferPacket
+ XXX.protocol.common.ClientboundUpdateTagsPacket
- XXX.protocol.common.ClientCommonPacketListener
- XXX.protocol.common.CommonPacketTypes
- XXX.protocol.common.package-info
- XXX.protocol.common.ServerboundClientInformationPacket
+ XXX.protocol.common.ServerboundCustomPayloadPacket
- XXX.protocol.common.ServerboundKeepAlivePacket
+ XXX.protocol.common.ServerboundPongPacket
- XXX.protocol.common.ServerboundResourcePackPacket
+ XXX.protocol.common.ServerboundResourcePackPacket$Action
+ XXX.protocol.common.ServerCommonPacketListener
- XXX.protocol.configuration.ClientboundFinishConfigurationPacket
+ XXX.protocol.configuration.ClientboundRegistryDataPacket
- XXX.protocol.configuration.ClientboundSelectKnownPacks
+ XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.configuration.ClientConfigurationPacketListener
- XXX.protocol.configuration.ConfigurationPacketTypes
+ XXX.protocol.configuration.ConfigurationProtocols
+ XXX.protocol.configuration.package-info
+ XXX.protocol.configuration.ServerboundFinishConfigurationPacket
- XXX.protocol.configuration.ServerboundSelectKnownPacks
- XXX.protocol.configuration.ServerConfigurationPacketListener
+ XXX.protocol.cookie.ClientboundCookieRequestPacket
- XXX.protocol.cookie.ClientCookiePacketListener
- XXX.protocol.cookie.CookiePacketTypes
+ XXX.protocol.cookie.package-info
- XXX.protocol.cookie.ServerboundCookieResponsePacket
+ XXX.protocol.cookie.ServerCookiePacketListener
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockChangedAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$AddOperation
+ XXX.protocol.game.ClientboundBossEventPacket$Handler
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundBossEventPacket$OperationType
- XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- XXX.protocol.game.ClientboundBundleDelimiterPacket
+ XXX.protocol.game.ClientboundBundlePacket
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChunkBatchFinishedPacket
- XXX.protocol.game.ClientboundChunkBatchStartPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket$Entry
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ XXX.protocol.game.ClientboundDamageEventPacket
- XXX.protocol.game.ClientboundDebugSamplePacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundGameEventPacket$Type
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundHurtAnimationPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
+ XXX.protocol.game.ClientboundLevelChunkPacketData
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
- XXX.protocol.game.ClientboundLevelChunkWithLightPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
- XXX.protocol.game.ClientboundLightUpdatePacketData
+ XXX.protocol.game.ClientboundLoginPacket
- XXX.protocol.game.ClientboundMapItemDataPacket
+ XXX.protocol.game.ClientboundMerchantOffersPacket
- XXX.protocol.game.ClientboundMoveEntityPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket$Pos
- XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
+ XXX.protocol.game.ClientboundMoveEntityPacket$Rot
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerChatPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
- XXX.protocol.game.ClientboundPlayerInfoRemovePacket
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResetScorePacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundServerDataPacket
+ XXX.protocol.game.ClientboundSetActionBarTextPacket
- XXX.protocol.game.ClientboundSetBorderCenterPacket
+ XXX.protocol.game.ClientboundSetBorderLerpSizePacket
- XXX.protocol.game.ClientboundSetBorderSizePacket
+ XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
- XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetSimulationDistancePacket
- XXX.protocol.game.ClientboundSetSubtitleTextPacket
+ XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesAnimationPacket
- XXX.protocol.game.ClientboundSetTitleTextPacket
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStartConfigurationPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundSystemChatPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundTickingStatePacket
- XXX.protocol.game.ClientboundTickingStepPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.CommonPlayerSpawnInfo
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.GamePacketTypes
- XXX.protocol.game.GameProtocols
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundChatSessionUpdatePacket
- XXX.protocol.game.ServerboundChunkBatchReceivedPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundContainerSlotStateChangedPacket
+ XXX.protocol.game.ServerboundDebugSampleSubscriptionPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQueryPacket
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemPacket
+ XXX.protocol.game.ServerboundPlaceRecipePacket
- XXX.protocol.game.ServerboundPlayerAbilitiesPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket
- XXX.protocol.game.ServerboundPlayerActionPacket$Action
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntent$1
- XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.HandshakePacketTypes
- XXX.protocol.handshake.HandshakeProtocols
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.LoginPacketTypes
- XXX.protocol.login.LoginProtocols
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryAnswerPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerboundLoginAcknowledgedPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.ping.ClientboundPongResponsePacket
+ XXX.protocol.ping.ClientPongPacketListener
- XXX.protocol.ping.package-info
+ XXX.protocol.ping.PingPacketTypes
+ XXX.protocol.ping.ServerboundPingRequestPacket
- XXX.protocol.ping.ServerPingPacketListener
- XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Favicon
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatusPacketListener
+ XXX.protocol.status.StatusPacketTypes
- XXX.protocol.status.StatusProtocols
+ XXX.recipes.packs.BundleRecipeProvider
+ XXX.recipes.packs.package-info
- XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
+ XXX.rule.blockentity.AppendLoot
- XXX.rule.blockentity.AppendStatic
+ XXX.rule.blockentity.Clear
+ XXX.rule.blockentity.package-info
- XXX.rule.blockentity.Passthrough
+ XXX.rule.blockentity.RuleBlockEntityModifier
- XXX.rule.blockentity.RuleBlockEntityModifierType
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapId
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
- XXX.server.advancements.AdvancementVisibilityEvaluator
+ XXX.server.advancements.AdvancementVisibilityEvaluator$Output
- XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ XXX.server.advancements.package-info
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.chase.ChaseClient
- XXX.server.chase.ChaseClient$TeleportTarget
+ XXX.server.chase.ChaseServer
- XXX.server.chase.ChaseServer$PlayerPosition
+ XXX.server.chase.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ChaseCommand
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$CommandFunction
+ XXX.server.commands.CloneCommands$DimensionAndPosition
- XXX.server.commands.CloneCommands$Mode
+ XXX.server.commands.DamageCommand
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DebugCommand$TraceCustomExecutor
+ XXX.server.commands.DebugCommand$TraceCustomExecutor$1
- XXX.server.commands.DebugCommand$Tracer
+ XXX.server.commands.DebugConfigCommand
- XXX.server.commands.DebugMobSpawningCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
- XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandGetter
+ XXX.server.commands.ExecuteCommand$CommandNumericPredicate
- XXX.server.commands.ExecuteCommand$CommandPredicate
+ XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
- XXX.server.commands.ExecuteCommand$IntBiPredicate
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillBiomeCommand
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
- XXX.server.commands.FunctionCommand$1
+ XXX.server.commands.FunctionCommand$1Accumulator
- XXX.server.commands.FunctionCommand$2
+ XXX.server.commands.FunctionCommand$3
- XXX.server.commands.FunctionCommand$4
+ XXX.server.commands.FunctionCommand$5
- XXX.server.commands.FunctionCommand$Callbacks
+ XXX.server.commands.FunctionCommand$FunctionCustomExecutor
- XXX.server.commands.GameModeCommand
+ XXX.server.commands.GameRuleCommand
- XXX.server.commands.GameRuleCommand$1
+ XXX.server.commands.GiveCommand
- XXX.server.commands.HelpCommand
+ XXX.server.commands.ItemCommands
- XXX.server.commands.JfrCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LootCommand
- XXX.server.commands.LootCommand$Callback
+ XXX.server.commands.LootCommand$DropConsumer
- XXX.server.commands.LootCommand$TailProvider
+ XXX.server.commands.MsgCommand
- XXX.server.commands.OpCommand
- XXX.server.commands.package-info
+ XXX.server.commands.PardonCommand
- XXX.server.commands.PardonIpCommand
+ XXX.server.commands.ParticleCommand
- XXX.server.commands.PerfCommand
+ XXX.server.commands.PlaceCommand
- XXX.server.commands.PlaySoundCommand
+ XXX.server.commands.PublishCommand
- XXX.server.commands.RaidCommand
+ XXX.server.commands.RandomCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ResetChunksCommand
+ XXX.server.commands.ReturnCommand
- XXX.server.commands.ReturnCommand$ReturnFailCustomExecutor
+ XXX.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
- XXX.server.commands.ReturnCommand$ReturnValueCustomExecutor
+ XXX.server.commands.RideCommand
- XXX.server.commands.SaveAllCommand
+ XXX.server.commands.SaveOffCommand
- XXX.server.commands.SaveOnCommand
+ XXX.server.commands.SayCommand
- XXX.server.commands.ScheduleCommand
+ XXX.server.commands.ScoreboardCommand
- XXX.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
+ XXX.server.commands.SeedCommand
- XXX.server.commands.ServerPackCommand
+ XXX.server.commands.SetBlockCommand
- XXX.server.commands.SetBlockCommand$Filter
+ XXX.server.commands.SetBlockCommand$Mode
- XXX.server.commands.SetPlayerIdleTimeoutCommand
+ XXX.server.commands.SetSpawnCommand
- XXX.server.commands.SetWorldSpawnCommand
+ XXX.server.commands.SpawnArmorTrimsCommand
- XXX.server.commands.SpectateCommand
+ XXX.server.commands.SpreadPlayersCommand
- XXX.server.commands.SpreadPlayersCommand$Position
+ XXX.server.commands.StopCommand
- XXX.server.commands.StopSoundCommand
+ XXX.server.commands.SummonCommand
- XXX.server.commands.TagCommand
+ XXX.server.commands.TeamCommand
- XXX.server.commands.TeamMsgCommand
+ XXX.server.commands.TeleportCommand
- XXX.server.commands.TeleportCommand$LookAt
+ XXX.server.commands.TeleportCommand$LookAtEntity
- XXX.server.commands.TeleportCommand$LookAtPosition
+ XXX.server.commands.TellRawCommand
- XXX.server.commands.TickCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TransferCommand
- XXX.server.commands.TriggerCommand
+ XXX.server.commands.WardenSpawnTrackerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
+ XXX.server.dedicated.DedicatedPlayerList
- XXX.server.dedicated.DedicatedServer
+ XXX.server.dedicated.DedicatedServer$1
- XXX.server.dedicated.DedicatedServerProperties
+ XXX.server.dedicated.DedicatedServerProperties$WorldDimensionData
- XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.package-info
+ XXX.server.dedicated.ServerWatchdog
- XXX.server.dedicated.ServerWatchdog$1
+ XXX.server.dedicated.Settings
- XXX.server.dedicated.Settings$MutableValue
- XXX.server.gui.MinecraftServerGui
+ XXX.server.gui.MinecraftServerGui$1
- XXX.server.gui.MinecraftServerGui$2
+ XXX.server.gui.package-info
+ XXX.server.gui.PlayerListComponent
- XXX.server.gui.StatsComponent
- XXX.server.level.BlockDestructionProgress
+ XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure
+ XXX.server.level.ChunkMap$1
- XXX.server.level.ChunkResult
- XXX.server.level.ChunkResult$Success
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Message
- XXX.server.level.ChunkTaskPriorityQueueSorter$Release
+ XXX.server.level.ChunkTracker
- XXX.server.level.ChunkTrackingView
+ XXX.server.level.ChunkTrackingView$1
- XXX.server.level.ChunkTrackingView$Positioned
+ XXX.server.level.ClientInformation
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FullChunkStatus
+ XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$ChunkAndHolder
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$2
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.TickingTracker
- XXX.server.level.WorldGenRegion
- XXX.server.network.CommonListenerCookie
+ XXX.server.network.ConfigurationTask
- XXX.server.network.ConfigurationTask$Type
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockSetType
- XXX.state.properties.BlockSetType$PressurePlateSensitivity
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ChestType$1
+ XXX.state.properties.ComparatorMode
- XXX.state.properties.DirectionProperty
+ XXX.state.properties.DoorHingeSide
- XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.DripstoneThickness
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.NoteBlockInstrument$Type
- XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$Value
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.RotationSegment
+ XXX.state.properties.SculkSensorPhase
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.Tilt
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootDataId
- XXX.storage.loot.LootDataManager
+ XXX.storage.loot.LootDataManager$1
- XXX.storage.loot.LootDataResolver
+ XXX.storage.loot.LootDataType
- XXX.storage.loot.LootDataType$Validator
+ XXX.storage.loot.LootParams
- XXX.storage.loot.LootParams$Builder
+ XXX.storage.loot.LootParams$DynamicDrop
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.ValidationContext
- XXX.structure.pieces.package-info
- XXX.structure.pieces.PieceGenerator
+ XXX.structure.pieces.PieceGenerator$Context
- XXX.structure.pieces.PieceGeneratorSupplier
+ XXX.structure.pieces.PieceGeneratorSupplier$Context
- XXX.structure.pieces.PiecesContainer
+ XXX.structure.pieces.StructurePiecesBuilder
+ XXX.structure.pieces.StructurePieceSerializationContext
- XXX.structure.pieces.StructurePieceType
+ XXX.structure.pieces.StructurePieceType$ContextlessType
- XXX.structure.pieces.StructurePieceType$StructureTemplateType
+ XXX.structure.placement.ConcentricRingsStructurePlacement
- XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.RandomSpreadType$1
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacement$ExclusionZone
+ XXX.structure.placement.StructurePlacement$FrequencyReducer
- XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
+ XXX.structure.placement.StructurePlacementType
+ XXX.structure.pools.EmptyPoolElement
- XXX.structure.pools.FeaturePoolElement
+ XXX.structure.pools.JigsawJunction
- XXX.structure.pools.JigsawPlacement
+ XXX.structure.pools.JigsawPlacement$PieceState
- XXX.structure.pools.JigsawPlacement$Placer
+ XXX.structure.pools.LegacySinglePoolElement
- XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
+ XXX.structure.pools.SinglePoolElement
- XXX.structure.pools.StructurePoolElement
+ XXX.structure.pools.StructurePoolElementType
- XXX.structure.pools.StructureTemplatePool
+ XXX.structure.pools.StructureTemplatePool$Projection
- XXX.structure.structures.BuriedTreasurePieces
+ XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.structure.structures.BuriedTreasureStructure
+ XXX.structure.structures.DesertPyramidPiece
- XXX.structure.structures.DesertPyramidStructure
+ XXX.structure.structures.EndCityPieces
- XXX.structure.structures.EndCityPieces$1
+ XXX.structure.structures.EndCityPieces$2
- XXX.structure.structures.EndCityPieces$3
+ XXX.structure.structures.EndCityPieces$4
- XXX.structure.structures.EndCityPieces$EndCityPiece
+ XXX.structure.structures.EndCityPieces$SectionGenerator
- XXX.structure.structures.EndCityStructure
+ XXX.structure.structures.IglooPieces
- XXX.structure.structures.IglooPieces$IglooPiece
+ XXX.structure.structures.IglooStructure
- XXX.structure.structures.JigsawStructure
+ XXX.structure.structures.JigsawStructure$1
- XXX.structure.structures.JungleTemplePiece
+ XXX.structure.structures.JungleTemplePiece$MossStoneSelector
- XXX.structure.structures.JungleTempleStructure
+ XXX.structure.structures.MineshaftPieces
- XXX.structure.structures.MineshaftPieces$1
+ XXX.structure.structures.MineshaftPieces$MineShaftCorridor
- XXX.structure.structures.MineshaftPieces$MineShaftCrossing
+ XXX.structure.structures.MineshaftPieces$MineShaftPiece
- XXX.structure.structures.MineshaftPieces$MineShaftRoom
+ XXX.structure.structures.MineshaftPieces$MineShaftStairs
- XXX.structure.structures.MineshaftStructure
+ XXX.structure.structures.MineshaftStructure$Type
- XXX.structure.structures.NetherFortressPieces
+ XXX.structure.structures.NetherFortressPieces$1
- XXX.structure.structures.NetherFortressPieces$BridgeCrossing
+ XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
- XXX.structure.structures.NetherFortressPieces$BridgeStraight
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ XXX.structure.structures.NetherFortressPieces$CastleEntrance
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
+ XXX.structure.structures.NetherFortressPieces$MonsterThrone
- XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
+ XXX.structure.structures.NetherFortressPieces$PieceWeight
- XXX.structure.structures.NetherFortressPieces$RoomCrossing
+ XXX.structure.structures.NetherFortressPieces$StairsRoom
- XXX.structure.structures.NetherFortressPieces$StartPiece
+ XXX.structure.structures.NetherFortressStructure
- XXX.structure.structures.NetherFossilPieces
+ XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
- XXX.structure.structures.NetherFossilStructure
+ XXX.structure.structures.OceanMonumentPieces
- XXX.structure.structures.OceanMonumentPieces$1
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
+ XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.structure.structures.OceanMonumentPieces$RoomDefinition
+ XXX.structure.structures.OceanMonumentStructure
- XXX.structure.structures.OceanRuinPieces
+ XXX.structure.structures.OceanRuinPieces$1
- XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
+ XXX.structure.structures.OceanRuinStructure
- XXX.structure.structures.OceanRuinStructure$Type
+ XXX.structure.structures.package-info
+ XXX.structure.structures.RuinedPortalPiece
- XXX.structure.structures.RuinedPortalPiece$Properties
+ XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
- XXX.structure.structures.RuinedPortalStructure
+ XXX.structure.structures.RuinedPortalStructure$Setup
- XXX.structure.structures.ShipwreckPieces
+ XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
- XXX.structure.structures.ShipwreckStructure
+ XXX.structure.structures.StrongholdPieces
- XXX.structure.structures.StrongholdPieces$1
+ XXX.structure.structures.StrongholdPieces$2
- XXX.structure.structures.StrongholdPieces$3
+ XXX.structure.structures.StrongholdPieces$ChestCorridor
- XXX.structure.structures.StrongholdPieces$FillerCorridor
+ XXX.structure.structures.StrongholdPieces$FiveCrossing
- XXX.structure.structures.StrongholdPieces$LeftTurn
+ XXX.structure.structures.StrongholdPieces$Library
- XXX.structure.structures.StrongholdPieces$PieceWeight
+ XXX.structure.structures.StrongholdPieces$PortalRoom
- XXX.structure.structures.StrongholdPieces$PrisonHall
+ XXX.structure.structures.StrongholdPieces$RightTurn
- XXX.structure.structures.StrongholdPieces$RoomCrossing
+ XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
- XXX.structure.structures.StrongholdPieces$StairsDown
+ XXX.structure.structures.StrongholdPieces$StartPiece
- XXX.structure.structures.StrongholdPieces$Straight
+ XXX.structure.structures.StrongholdPieces$StraightStairsDown
- XXX.structure.structures.StrongholdPieces$StrongholdPiece
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.structure.structures.StrongholdPieces$Turn
+ XXX.structure.structures.StrongholdStructure
- XXX.structure.structures.SwampHutPiece
+ XXX.structure.structures.SwampHutStructure
- XXX.structure.structures.WoodlandMansionPieces
+ XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$MansionGrid
- XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.structure.structures.WoodlandMansionPieces$PlacementData
- XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
- XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.structure.structures.WoodlandMansionStructure
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.CappedProcessor
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LavaSubmergedBlockProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.ProtectedBlockProcessor
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorList
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.StructureTemplateManager
+ XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- XXX.structure.templatesystem.StructureTemplateManager$Source
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.package-info
- XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
+ XXX.village.poi.PoiTypes
- XXX.world.entity.Crackiness
- XXX.world.entity.EquipmentSlotGroup
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.FlyingMob
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HasCustomInventoryScreen
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.Interaction
+ XXX.world.entity.Interaction$PlayerAction
- XXX.world.entity.ItemBasedSteering
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.LerpingModel
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MobSpawnType
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.Pose
+ XXX.world.entity.PowerableMob
- XXX.world.entity.RelativeMovement
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.Saddleable
+ XXX.world.entity.Shearable
- XXX.world.entity.SlotAccess
+ XXX.world.entity.SlotAccess$1
- XXX.world.entity.SlotAccess$2
+ XXX.world.entity.SlotAccess$3
- XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacementType
- XXX.world.entity.SpawnPlacementTypes
+ XXX.world.entity.SpawnPlacementTypes$1
+ XXX.world.entity.TamableAnimal
- XXX.world.entity.Targeting
+ XXX.world.entity.TraceableEntity
- XXX.world.entity.VariantHolder
+ XXX.world.entity.WalkAnimationState
+ XXX.world.item.ArmorItem$Type
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterial$Layer
- XXX.world.item.ArmorMaterials
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BannerPatternItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BoneMealItem$1
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$Builder
- XXX.world.item.CreativeModeTab$DisplayItemsGenerator
+ XXX.world.item.CreativeModeTab$ItemDisplayBuilder
- XXX.world.item.CreativeModeTab$ItemDisplayParameters
+ XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTab$Row
+ XXX.world.item.CreativeModeTab$TabVisibility
- XXX.world.item.CreativeModeTab$Type
+ XXX.world.item.CreativeModeTabs
- XXX.world.item.CrossbowItem
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
+ XXX.world.item.EnchantedGoldenAppleItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.Equipable
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.ItemStack$2
+ XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignApplicator
+ XXX.world.item.SignItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockCollisions
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ClipBlockStateContext
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$BooleanValue
+ XXX.world.level.GameRules$Category
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameRules$VisitorCaller
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.Level$1
+ XXX.world.level.Level$2
- XXX.world.level.Level$ExplosionInteraction
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelHeightAccessor
+ XXX.world.level.LevelHeightAccessor$1
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelTimeAccess
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.LocalMobCapCalculator
- XXX.world.level.LocalMobCapCalculator$MobCounts
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
+ XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ServerLevelAccessor
+ XXX.world.level.SignalGetter
- XXX.world.level.SpawnData
+ XXX.world.level.SpawnData$CustomSpawnRules
- XXX.world.level.Spawner
+ XXX.world.level.StructureManager
- XXX.world.level.WorldDataConfiguration
+ XXX.world.level.WorldGenLevel
+ XXX.worldgen.biome.BiomeData
- XXX.worldgen.biome.EndBiomes
+ XXX.worldgen.biome.NetherBiomes
- XXX.worldgen.biome.OverworldBiomes
+ XXX.worldgen.biome.package-info
- XXX.worldgen.features.AquaticFeatures
+ XXX.worldgen.features.CaveFeatures
- XXX.worldgen.features.EndFeatures
+ XXX.worldgen.features.FeatureUtils
- XXX.worldgen.features.MiscOverworldFeatures
+ XXX.worldgen.features.NetherFeatures
- XXX.worldgen.features.OreFeatures
- XXX.worldgen.features.package-info
+ XXX.worldgen.features.PileFeatures
- XXX.worldgen.features.TreeFeatures
+ XXX.worldgen.features.VegetationFeatures
- XXX.worldgen.placement.AquaticPlacements
+ XXX.worldgen.placement.CavePlacements
- XXX.worldgen.placement.EndPlacements
+ XXX.worldgen.placement.MiscOverworldPlacements
- XXX.worldgen.placement.NetherPlacements
+ XXX.worldgen.placement.OrePlacements
- XXX.worldgen.placement.package-info
- XXX.worldgen.placement.PlacementUtils
+ XXX.worldgen.placement.TreePlacements
- XXX.worldgen.placement.VegetationPlacements
+ XXX.worldgen.placement.VillagePlacements
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants -3M | +1P
```
```
net.minecraft.Util +3M -2M
```
```
XXX.advancements.critereon.BlockPredicate +6M -4M | +1P -2P
```
```
XXX.advancements.critereon.EntityTypePredicate -5M
```
```
XXX.advancements.critereon.FluidPredicate +2M -3M | +1P -2P
```
```
XXX.advancements.critereon.ItemPredicate$Builder +3M -2M | +3P -3P
```
```
XXX.advancements.critereon.LocationPredicate +2M -3M | +2P -2P
```
```
XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher +1M | +1P
```
```
XXX.advancements.critereon.StatePropertiesPredicate$ValueMatcher +4M | +1P
```
```
XXX.arguments.item.ItemParser$ItemResult +2M -2M | +1P -1P
```
```
XXX.arguments.item.ItemPredicateParser$1 +3M -3M | +1P
```
```
XXX.arguments.item.ItemSyntaxParser$State +11M -2M | +1P
```
```
XXX.arguments.item.ItemSyntaxParser$Visitor +2M -1M
```
```
XXX.minecraft.core.GlobalPos +1P
```
```
XXX.data.info.BlockListReport +4M -1M | +1P
```
```
XXX.loot.packs.VanillaGiftLoot +1M -1M
```
```
XXX.loot.packs.VanillaPiglinBarterLoot +1M -1M
```
```
XXX.network.chat.HoverEvent$Action +5M -5M
```
```
XXX.network.chat.Style$Serializer +1P -1P
```
```
XXX.network.codec.ByteBufCodecs$11 +3M -3M | +1P -1P
```
```
XXX.network.codec.ByteBufCodecs$13 +5M -3M | +2P
```
```
XXX.network.codec.ByteBufCodecs$15 +2M -2M
```
```
XXX.network.codec.ByteBufCodecs$17 +3M -3M | +1P -2P
```
```
XXX.network.codec.ByteBufCodecs$19 +4M -3M | +4P -2P
```
```
XXX.network.codec.ByteBufCodecs$20 +5M -4M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$22 +6M -1M | +2P -1P
```
```
XXX.server.level.ChunkHolder$ChunkSaveDebug +6M
```
```
XXX.server.network.ServerGamePacketListenerImpl +9M -10M
```
```
XXX.minecraft.util.ExtraCodecs +89M -81M | +1P -1P
```
```
XXX.minecraft.util.FastColor$ARGB32 +2M
```
```
XXX.minecraft.util.StringUtil +7M
```
```
XXX.util.datafix.ExtraDataFixUtils +9M
```
```
XXX.datafix.fixes.References +1M | +1P
```
```
XXX.jfr.stats.ChunkGenStat +2M -2M | +1P -1P
```
```
XXX.minecraft.world.ContainerHelper +3M -3M
```
```
XXX.minecraft.world.LockCode +4M | +1P
```
```
XXX.world.entity.AreaEffectCloud +2M -3M | +1P -4P
```
```
XXX.world.entity.EntityType +3M -3M | -1P
```
```
XXX.entity.animal.MushroomCow +1M -1M | +1P -1P
```
```
XXX.animal.axolotl.Axolotl +1M
```
```
XXX.animal.horse.Donkey +1M
```
```
XXX.entity.decoration.Painting +1M -2M | +2P -1P
```
```
XXX.entity.monster.CrossbowAttackMob -2M | -1P
```
```
XXX.entity.npc.InventoryCarrier +2M -2M
```
```
XXX.entity.npc.VillagerTrades +2M
```
```
XXX.entity.npc.VillagerTrades$EmeraldForItems +1M -1M | +1P -1P
```
```
XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems +1M -2M | +1P -2P
```
```
XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald +1M -1M | +1P -1P
```
```
XXX.entity.player.Inventory -1M
```
```
XXX.entity.projectile.FireworkRocketEntity +2M
```
```
XXX.entity.projectile.SpectralArrow +1M -1M | -1P
```
```
XXX.entity.projectile.ThrownPotion +2M -2M
```
```
XXX.projectile.windcharge.AbstractWindCharge +1M
```
```
XXX.projectile.windcharge.BreezeWindCharge +1P -1P
```
```
XXX.world.inventory.LoomMenu +1M
```
```
XXX.world.inventory.PlayerEnderChestContainer +2M -2M
```
```
XXX.inventory.tooltip.BundleTooltip +5M -3M | +1P -2P
```
```
XXX.world.item.AnimalArmorItem$BodyType +1M -1M | +1P
```
```
XXX.world.item.InstrumentItem +1M -3M | -1P
```
```
XXX.world.item.Item +3M -2M | +1P
```
```
XXX.world.item.Item$Properties +4M | +2P
```
```
XXX.world.item.ItemStack +43M -47M | +5P -20P
```
```
XXX.world.item.MapItem +1M -6M | -4P
```
```
XXX.world.item.SuspiciousStewItem -8M | -1P
```
```
XXX.world.item.WritableBookItem -1M
```
```
XXX.item.alchemy.Potion +2M -2M
```
```
XXX.item.alchemy.Potions -1M | -2P
```
```
XXX.item.armortrim.ArmorTrim +8M -7M | +2P -2P
```
```
XXX.item.crafting.RepairItemRecipe +2M -1M
```
```
XXX.level.block.TrapDoorBlock +1M -1M
```
```
XXX.level.block.WitherRoseBlock +1M -1M
```
```
XXX.block.entity.BannerBlockEntity +7M -7M | +3P -4P
```
```
XXX.block.entity.BaseContainerBlockEntity +3M -1M
```
```
XXX.block.entity.BeehiveBlockEntity$BeeData +4M -1M | +1P -2P
```
```
XXX.level.chunk.ImposterProtoChunk +2M -2M
```
```
XXX.level.chunk.ProtoChunk +2M -2M | +1P -1P
```
```
XXX.loot.functions.SetContainerContents +1M
```
```
XXX.loot.parameters.LootContextParamSets +1M | +1P
```
```
XXX.world.scores.Score +2M -2M
```
```
XXX.world.scores.Scoreboard +4M -4M
```
```
XXX.world.scores.ScoreboardSaveData +5M -5M
```

</details>
<details>
<summary>
net.minecraft.SharedConstants
</summary>

```diff
+ boolean isAllowedChatCharacter(char)
+ String filterText(String,boolean)
+ String filterText(String)
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ boolean isBlank(String)
+ boolean isWhitespace(int)
- List copyAndAdd(List,Object)
- Map copyAndPut(Map,Object,Object)
- String getRegisteredName(Registry,Object)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ App lambda$static$1(RecordCodecBuilder$Instance)
- boolean matches(BlockInWorld)
- boolean matchesBlockEntity(LevelReader,BlockEntity,NbtPredicate)
- boolean matchesState(BlockState)
- boolean requiresNbt()
+ List lambda$static$0(HolderSet)
+ Optional tag()
+ void <init>(Optional,Optional,Optional,Optional)
- void <init>(Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityTypePredicate
</summary>

```diff
+ DataResult lambda$static$4(EntityTypePredicate)
+ EntityTypePredicate lambda$static$0(TagKey)
+ EntityTypePredicate lambda$static$1(Holder)
+ EntityTypePredicate lambda$static$2(Either)
+ String lambda$static$3(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.FluidPredicate
</summary>

```diff
+ Optional fluid()
- Optional fluids()
+ Optional tag()
+ void <init>(Optional,Optional,Optional)
- void <init>(Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemPredicate$Builder
</summary>

```diff
- ItemPredicate$Builder hasComponents(DataComponentPredicate)
- ItemPredicate$Builder hasCustomData(CompoundTag)
+ ItemPredicate$Builder hasNbt(CompoundTag)
+ ItemPredicate$Builder isPotion(Holder)
- ItemPredicate$Builder isPotion(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate
</summary>

```diff
+ Optional biome()
- Optional biomes()
+ Optional of(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ Optional structure()
- Optional structures()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.StatePropertiesPredicate$ValueMatcher
</summary>

```diff
- Either lambda$static$7(StatePropertiesPredicate$ValueMatcher)
- Record lambda$static$4(StatePropertiesPredicate$ExactMatcher)
- Record lambda$static$5(StatePropertiesPredicate$RangedMatcher)
- StatePropertiesPredicate$ValueMatcher lambda$static$6(Either)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.ItemParser$ItemResult
</summary>

```diff
+ CompoundTag nbt()
- DataComponentMap components()
+ void <init>(Holder,CompoundTag)
- void <init>(Holder,DataComponentMap)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.ItemPredicateParser$1
</summary>

```diff
+ boolean lambda$visitNbt$2(CompoundTag,ItemStack)
- void <init>(ItemPredicateParser,List,DataComponentPredicate$Builder)
+ void <init>(ItemPredicateParser,List)
- void visitComponent(DataComponentType,Object)
- void visitCustomData(CompoundTag)
+ void visitNbt(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.ItemSyntaxParser$State
</summary>

```diff
- CommandSyntaxException lambda$readComponent$2(int,DataComponentType,String)
- CompletableFuture suggestAssignment(SuggestionsBuilder)
- CompletableFuture suggestComponentAssignment(SuggestionsBuilder)
- CompletableFuture suggestNextOrEndComponents(SuggestionsBuilder)
- CompletableFuture suggestStartComponentsOrNbt(SuggestionsBuilder)
+ CompletableFuture suggestStartNbt(SuggestionsBuilder)
- DataComponentType readComponentType(StringReader)
- ResourceLocation lambda$suggestComponentAssignment$3(Map$Entry)
- void lambda$suggestComponentAssignment$4(SuggestionsBuilder,Map$Entry)
- void readComponent(DataComponentType)
- void readComponents()
- void readCustomData()
+ void readNbt()
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.ItemSyntaxParser$Visitor
</summary>

```diff
- void visitComponent(DataComponentType,Object)
- void visitCustomData(CompoundTag)
+ void visitNbt(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.data.info.BlockListReport
</summary>

```diff
- AssertionError lambda$run$0(String,String)
- CompletionStage lambda$run$2(CachedOutput,Path,HolderLookup$Provider)
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
- void lambda$run$1(RegistryOps,JsonObject,Holder$Reference)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.VanillaGiftLoot
</summary>

```diff
+ void generate(BiConsumer)
- void generate(HolderLookup$Provider,BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
</summary>

```diff
+ void generate(BiConsumer)
- void generate(HolderLookup$Provider,BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.network.chat.HoverEvent$Action
</summary>

```diff
- DataResult lambda$static$0(Component,RegistryOps)
+ HoverEvent$Action[] lambda$static$0()
- HoverEvent$Action[] lambda$static$1()
+ HoverEvent$TypedHoverEvent lambda$new$1(Object)
- HoverEvent$TypedHoverEvent lambda$new$2(Object)
+ HoverEvent$TypedHoverEvent lambda$new$3(Object)
+ Object lambda$new$2(HoverEvent$TypedHoverEvent)
- Object lambda$new$3(HoverEvent$TypedHoverEvent)
+ void <init>(String,boolean,Codec,Function)
- void <init>(String,boolean,Codec,HoverEvent$LegacyConverter)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$11
</summary>

```diff
- String decode(ByteBuf)
+ Tag decode(ByteBuf)
- void <init>(int)
+ void <init>(Supplier)
- void encode(ByteBuf,String)
+ void encode(ByteBuf,Tag)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$13
</summary>

```diff
- DecoderException lambda$decode$0(Tag,String)
- EncoderException lambda$encode$1(Object,String)
- Object decode(RegistryFriendlyByteBuf)
+ Optional decode(ByteBuf)
+ void <init>()
- void <init>(StreamCodec,Codec)
+ void encode(ByteBuf,Optional)
- void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$15
</summary>

```diff
+ Quaternionf decode(ByteBuf)
- Vector3f decode(ByteBuf)
+ void encode(ByteBuf,Quaternionf)
- void encode(ByteBuf,Vector3f)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$17
</summary>

```diff
+ Collection decode(ByteBuf)
- Optional decode(ByteBuf)
+ void <init>(IntFunction,StreamCodec)
- void <init>(StreamCodec)
+ void encode(ByteBuf,Collection)
- void encode(ByteBuf,Optional)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$19
</summary>

```diff
- Map decode(ByteBuf)
+ Object decode(ByteBuf)
- void <init>(int,StreamCodec,StreamCodec,IntFunction)
+ void <init>(IntFunction,ToIntFunction)
- void encode(ByteBuf,Map)
+ void encode(ByteBuf,Object)
- void lambda$encode$0(StreamCodec,ByteBuf,StreamCodec,Object,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$20
</summary>

```diff
- Either decode(ByteBuf)
+ IdMap getRegistryOrThrow(RegistryFriendlyByteBuf)
+ Object decode(RegistryFriendlyByteBuf)
+ void <init>(Function,ResourceKey)
- void <init>(StreamCodec,StreamCodec)
- void encode(ByteBuf,Either)
+ void encode(RegistryFriendlyByteBuf,Object)
- void lambda$encode$0(ByteBuf,StreamCodec,Object)
- void lambda$encode$1(ByteBuf,StreamCodec,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$22
</summary>

```diff
- IdMap getRegistryOrThrow(RegistryFriendlyByteBuf)
- Object decode(Object)
- Object decode(RegistryFriendlyByteBuf)
+ void <clinit>()
- void <init>(Function,ResourceKey)
- void encode(Object,Object)
- void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
</summary>

```diff
- boolean equals(Object)
- CompletableFuture future()
- int hashCode()
- String source()
- String toString()
- Thread thread()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
- CommandSourceStack lambda$performChatCommand$8(CommandSigningContext,CommandSourceStack)
+ CommandSourceStack lambda$performChatCommand$9(CommandSigningContext,CommandSourceStack)
- Filterable filterableFromOutgoing(FilteredText)
- Filterable lambda$signBook$4(FilteredText)
+ String lambda$signBook$4(String)
+ StringTag lambda$updateBookPages$5(UnaryOperator,FilteredText)
- void lambda$handleChat$5(PlayerChatMessage,Component,FilteredText)
+ void lambda$handleChat$6(PlayerChatMessage,Component,FilteredText)
- void lambda$handleChat$6(ServerboundChatPacket,Optional)
+ void lambda$handleChat$7(ServerboundChatPacket,Optional)
- void lambda$handleChatCommand$7(ServerboundChatCommandPacket,Optional)
+ void lambda$handleChatCommand$8(ServerboundChatCommandPacket,Optional)
+ void lambda$handlePlaceRecipe$10(ServerboundPlaceRecipePacket,RecipeHolder)
- void lambda$handlePlaceRecipe$9(ServerboundPlaceRecipePacket,RecipeHolder)
- void lambda$handleSignUpdate$10(ServerboundSignUpdatePacket,List)
+ void lambda$handleSignUpdate$11(ServerboundSignUpdatePacket,List)
- void lambda$resetPlayerChatState$11(RemoteChatSession)
+ void lambda$resetPlayerChatState$12(RemoteChatSession)
+ void updateBookPages(List,UnaryOperator,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
- App lambda$intervalCodec$19(Codec,String,String,RecordCodecBuilder$Instance)
+ App lambda$intervalCodec$21(Codec,String,String,RecordCodecBuilder$Instance)
- App lambda$static$10(RecordCodecBuilder$Instance)
+ App lambda$static$12(RecordCodecBuilder$Instance)
- App lambda$static$69(RecordCodecBuilder$Instance)
+ App lambda$static$71(RecordCodecBuilder$Instance)
- BitSet lambda$static$65(LongStream)
+ BitSet lambda$static$67(LongStream)
- Codec lambda$lazyInitializedCodec$48(Supplier,Codec)
+ Codec lambda$lazyInitializedCodec$50(Supplier,Codec)
- Codec optionalEmptyMap(Codec)
- Codec sizeLimitedList(Codec,int)
- Codec sizeLimitedMap(Codec,int)
- Codec unboundedDispatchMap(Codec,Function)
- DataResult lambda$ensureHomogenous$52(Function,Collection)
+ DataResult lambda$ensureHomogenous$54(Function,Collection)
- DataResult lambda$floatRangeMinExclusiveWithMessage$42(float,float,Function,Float)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$44(float,float,Function,Float)
- DataResult lambda$idResolverCodec$26(Integer)
- DataResult lambda$idResolverCodec$27(IntFunction,Integer)
+ DataResult lambda$idResolverCodec$28(Integer)
+ DataResult lambda$idResolverCodec$29(IntFunction,Integer)
- DataResult lambda$idResolverCodec$29(ToIntFunction,int,Object)
+ DataResult lambda$idResolverCodec$31(ToIntFunction,int,Object)
- DataResult lambda$intervalCodec$16(BiFunction,List)
- DataResult lambda$intervalCodec$17(BiFunction,List)
+ DataResult lambda$intervalCodec$18(BiFunction,List)
+ DataResult lambda$intervalCodec$19(BiFunction,List)
- DataResult lambda$intervalCodec$20(BiFunction,Pair)
- DataResult lambda$intervalCodec$22(BiFunction,Object)
+ DataResult lambda$intervalCodec$22(BiFunction,Pair)
- DataResult lambda$intervalCodec$23(BiFunction,Either)
+ DataResult lambda$intervalCodec$24(BiFunction,Object)
+ DataResult lambda$intervalCodec$25(BiFunction,Either)
- DataResult lambda$intRangeWithMessage$37(int,int,Function,Integer)
+ DataResult lambda$intRangeWithMessage$39(int,int,Function,Integer)
- DataResult lambda$nonEmptyHolderSet$47(HolderSet)
+ DataResult lambda$nonEmptyHolderSet$49(HolderSet)
- DataResult lambda$nonEmptyList$45(List)
+ DataResult lambda$nonEmptyList$47(List)
- DataResult lambda$sizeLimitedList$89(int,List)
- DataResult lambda$sizeLimitedMap$91(int,Map)
- DataResult lambda$static$12(List)
+ DataResult lambda$static$14(List)
- DataResult lambda$static$15(Integer)
+ DataResult lambda$static$17(Integer)
+ DataResult lambda$static$2(String)
+ DataResult lambda$static$3(JsonElement)
- DataResult lambda$static$3(List)
+ DataResult lambda$static$5(List)
- DataResult lambda$static$54(String)
+ DataResult lambda$static$56(String)
- DataResult lambda$static$57(String)
- DataResult lambda$static$6(List)
+ DataResult lambda$static$61(String)
- DataResult lambda$static$62(String)
+ DataResult lambda$static$64(String)
- DataResult lambda$static$76(String)
+ DataResult lambda$static$8(List)
+ DataResult lambda$static$89(String)
- DataResult lambda$static$93(String)
- DataResult lambda$stringResolverCodec$31(String)
- DataResult lambda$stringResolverCodec$32(Function,String)
+ DataResult lambda$stringResolverCodec$33(String)
+ DataResult lambda$stringResolverCodec$34(Function,String)
- DataResult lambda$stringResolverCodec$34(Object)
- DataResult lambda$stringResolverCodec$35(Function,Object)
+ DataResult lambda$stringResolverCodec$36(Object)
+ DataResult lambda$stringResolverCodec$37(Function,Object)
- DataResult lambda$temporalCodec$55(DateTimeFormatter,String)
+ DataResult lambda$temporalCodec$57(DateTimeFormatter,String)
- Either lambda$intervalCodec$24(Function,Function,Object)
+ Either lambda$intervalCodec$26(Function,Function,Object)
- Either lambda$static$74(PropertyMap)
+ Either lambda$static$76(PropertyMap)
- ExtraCodecs$TagOrElementLocation lambda$static$60(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$61(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$62(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$63(ResourceLocation)
+ Float lambda$static$10(AxisAngle4f)
- Float lambda$static$8(AxisAngle4f)
- List lambda$intervalCodec$18(Function,Function,Object)
+ List lambda$intervalCodec$20(Function,Function,Object)
- List lambda$static$13(Matrix4f)
+ List lambda$static$15(Matrix4f)
- List lambda$static$4(Vector3f)
+ List lambda$static$6(Vector3f)
- List lambda$static$7(Quaternionf)
+ List lambda$static$9(Quaternionf)
- LongStream lambda$static$66(BitSet)
+ LongStream lambda$static$68(BitSet)
- Matrix4f lambda$static$11(List)
+ Matrix4f lambda$static$13(List)
- Object lambda$strictOptionalField$49(Object,Optional)
+ Object lambda$strictOptionalField$51(Object,Optional)
+ Object lambda$withAlternative$90(Object)
+ Object lambda$withAlternative$91(Object)
+ Object lambda$withAlternative$92(Either)
+ Object lambda$withAlternative$93(Object)
+ Object lambda$withAlternative$94(Function,Either)
- Object lambda$withAlternative$94(Object)
- Object lambda$withAlternative$95(Object)
- Object lambda$withAlternative$96(Either)
- Object lambda$withAlternative$97(Object)
- Object lambda$withAlternative$98(Function,Either)
- Optional lambda$static$64(OptionalLong)
+ Optional lambda$static$66(OptionalLong)
- Optional lambda$static$67(Property)
+ Optional lambda$static$69(Property)
- Optional lambda$strictOptionalField$50(Object,Object)
+ Optional lambda$strictOptionalField$52(Object,Object)
- OptionalLong lambda$static$63(Optional)
+ OptionalLong lambda$static$65(Optional)
- Pair lambda$intervalCodec$21(Function,Function,Object)
+ Pair lambda$intervalCodec$23(Function,Function,Object)
- Property lambda$static$68(String,String,Optional)
+ Property lambda$static$70(String,String,Optional)
- PropertyMap lambda$static$73(Either)
+ PropertyMap lambda$static$75(Either)
- Quaternionf lambda$static$5(List)
+ Quaternionf lambda$static$7(List)
- String lambda$ensureHomogenous$51(Object,Object,Object)
+ String lambda$ensureHomogenous$53(Object,Object,Object)
- String lambda$floatRangeMinExclusiveWithMessage$41(Function,Float)
+ String lambda$floatRangeMinExclusiveWithMessage$43(Function,Float)
- String lambda$idResolverCodec$25(Integer)
+ String lambda$idResolverCodec$27(Integer)
- String lambda$idResolverCodec$28(Object)
+ String lambda$idResolverCodec$30(Object)
- String lambda$intRange$40(int,int,Integer)
+ String lambda$intRange$42(int,int,Integer)
- String lambda$intRangeWithMessage$36(Function,Integer)
+ String lambda$intRangeWithMessage$38(Function,Integer)
- String lambda$nonEmptyHolderSet$46()
+ String lambda$nonEmptyHolderSet$48()
- String lambda$nonEmptyList$44()
+ String lambda$nonEmptyList$46()
- String lambda$sizeLimitedList$88(List,int)
- String lambda$sizeLimitedMap$90(Map,int)
- String lambda$static$14(Integer)
+ String lambda$static$16(Integer)
- String lambda$static$38(Integer)
- String lambda$static$39(Integer)
+ String lambda$static$40(Integer)
+ String lambda$static$41(Integer)
- String lambda$static$43(Float)
+ String lambda$static$45(Float)
- String lambda$static$53(String,PatternSyntaxException)
+ String lambda$static$55(String,PatternSyntaxException)
- String lambda$static$56()
+ String lambda$static$58()
- String lambda$static$58(byte[])
+ String lambda$static$60(byte[])
- String lambda$static$75(String)
+ String lambda$static$88(String)
- String lambda$static$92(String)
- String lambda$stringResolverCodec$30(String)
+ String lambda$stringResolverCodec$32(String)
- String lambda$stringResolverCodec$33(Object)
+ String lambda$stringResolverCodec$35(Object)
+ Vector3f lambda$static$11(AxisAngle4f)
- Vector3f lambda$static$2(List)
+ Vector3f lambda$static$4(List)
- Vector3f lambda$static$9(AxisAngle4f)
- void lambda$static$70(PropertyMap,String,List)
- void lambda$static$71(PropertyMap,Map)
- void lambda$static$72(PropertyMap,List)
+ void lambda$static$72(PropertyMap,String,List)
+ void lambda$static$73(PropertyMap,Map)
+ void lambda$static$74(PropertyMap,List)
```

</details>
<details>
<summary>
net.minecraft.util.FastColor$ARGB32
</summary>

```diff
- int color(int,int,int)
- int opaque(int)
```

</details>
<details>
<summary>
net.minecraft.util.StringUtil
</summary>

```diff
- boolean isAllowedChatCharacter(char)
- boolean isBlank(String)
- boolean isValidPlayerName(String)
- boolean isWhitespace(int)
- boolean lambda$isValidPlayerName$0(int)
- String filterText(String,boolean)
- String filterText(String)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.ExtraDataFixUtils
</summary>

```diff
- boolean asBoolean(DynamicLike,boolean)
- DataResult asBoolean(Dynamic)
- DataResult asBoolean(DynamicLike)
- Dynamic copyAndFixField(Dynamic,String,Dynamic,String,UnaryOperator)
- Dynamic copyField(Dynamic,String,Dynamic,String)
- String lambda$asBoolean$1(DynamicLike)
- Typed cast(Type,Typed)
- TypeTemplate lambda$optionalFields$0(Pair)
- TypeTemplate optionalFields(Pair[])
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.References
</summary>

```diff
- String lambda$static$36()
```

</details>
<details>
<summary>
net.minecraft.util.profiling.jfr.stats.ChunkGenStat
</summary>

```diff
+ ChunkStatus status()
- ChunkStatus status()
+ void <init>(Duration,ChunkPos,ColumnPos,ChunkStatus,String)
- void <init>(Duration,ChunkPos,ColumnPos,ChunkStatus,String)
```

</details>
<details>
<summary>
net.minecraft.world.ContainerHelper
</summary>

```diff
- CompoundTag saveAllItems(CompoundTag,NonNullList,boolean,HolderLookup$Provider)
+ CompoundTag saveAllItems(CompoundTag,NonNullList,boolean)
- CompoundTag saveAllItems(CompoundTag,NonNullList,HolderLookup$Provider)
+ CompoundTag saveAllItems(CompoundTag,NonNullList)
- void loadAllItems(CompoundTag,NonNullList,HolderLookup$Provider)
+ void loadAllItems(CompoundTag,NonNullList)
```

</details>
<details>
<summary>
net.minecraft.world.LockCode
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- String key()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
+ Holder getPotion()
- void lambda$readAdditionalSaveData$2(String)
+ void setFixedColor(int)
+ void setPotion(Holder)
- void setPotionContents(PotionContents)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
+ void lambda$appendCustomEntityStackConfig$3(ServerLevel,Player,CompoundTag,Entity)
- void lambda$appendCustomEntityStackConfig$3(ServerLevel,Player,CustomData,Entity)
- void lambda$appendCustomNameConfig$2(Component,Entity)
+ void lambda$appendCustomNameConfig$2(ItemStack,Entity)
+ void updateCustomEntityTag(Level,Player,Entity,CompoundTag)
- void updateCustomEntityTag(Level,Player,Entity,CustomData)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.MushroomCow
</summary>

```diff
+ void lambda$readAdditionalSaveData$1(List)
- void lambda$readAdditionalSaveData$1(SuspiciousStewEffects)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.axolotl.Axolotl
</summary>

```diff
- void lambda$saveToBucketTag$0(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Donkey
</summary>

```diff
- void playJumpSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.Painting
</summary>

```diff
+ Optional loadVariant(CompoundTag)
+ ResourceKey lambda$loadVariant$2(ResourceLocation)
- void lambda$storeVariant$2(CompoundTag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.CrossbowAttackMob
</summary>

```diff
+ Vector3f getProjectileShotVector(LivingEntity,Vec3,float)
+ void shootCrossbowProjectile(LivingEntity,LivingEntity,Projectile,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.InventoryCarrier
</summary>

```diff
- void readInventoryFromTag(CompoundTag,HolderLookup$Provider)
+ void readInventoryFromTag(CompoundTag)
- void writeInventoryToTag(CompoundTag,HolderLookup$Provider)
+ void writeInventoryToTag(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades
</summary>

```diff
- DataComponentPredicate$Builder lambda$potionCost$1(Holder,DataComponentPredicate$Builder)
- ItemCost potionCost(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
</summary>

```diff
- void <init>(ItemCost,int,int,int)
+ void <init>(ItemStack,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
</summary>

```diff
- void <init>(ItemCost,int,ItemStack,int,int,float)
+ void <init>(ItemLike,int,int,Item,int,int,int,float,boolean)
+ void <init>(ItemLike,int,int,ItemStack,int,int,int,float,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
</summary>

```diff
+ void <init>(List,int,float)
- void <init>(SuspiciousStewEffects,int,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Inventory
</summary>

```diff
+ void hurtArmor(DamageSource,float,int[])
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.FireworkRocketEntity
</summary>

```diff
- ItemStack getDefaultItem()
- List getExplosions()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.SpectralArrow
</summary>

```diff
- ItemStack getDefaultPickupItem()
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownPotion
</summary>

```diff
- void applySplash(Iterable,Entity)
+ void applySplash(List,Entity)
+ void makeAreaOfEffectCloud(ItemStack,Holder)
- void makeAreaOfEffectCloud(PotionContents)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.windcharge.AbstractWindCharge
</summary>

```diff
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.LoomMenu
</summary>

```diff
- BannerPatternLayers lambda$setupResultSlot$2(Holder,DyeColor,BannerPatternLayers)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.PlayerEnderChestContainer
</summary>

```diff
+ ListTag createTag()
- ListTag createTag(HolderLookup$Provider)
- void fromTag(ListTag,HolderLookup$Provider)
+ void fromTag(ListTag)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.tooltip.BundleTooltip
</summary>

```diff
- boolean equals(Object)
- BundleContents contents()
+ int getWeight()
- int hashCode()
+ NonNullList getItems()
- String toString()
- void <init>(BundleContents)
+ void <init>(NonNullList,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.AnimalArmorItem$BodyType
</summary>

```diff
- void <init>(String,int,Function,SoundEvent)
+ void <init>(String,int,Function)
```

</details>
<details>
<summary>
net.minecraft.world.item.InstrumentItem
</summary>

```diff
+ IllegalStateException lambda$setSoundVariantId$1()
- Integer lambda$getUseDuration$1(Holder)
+ Integer lambda$getUseDuration$2(Holder)
+ void setSoundVariantId(ItemStack,Holder)
```

</details>
<details>
<summary>
net.minecraft.world.item.Item
</summary>

```diff
+ boolean shouldOverrideMultiplayerNbt()
- DataComponentMap components()
- SoundEvent getBreakingSound()
- void verifyComponentsAfterLoad(ItemStack)
+ void verifyTagAfterLoad(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
- DataComponentMap buildComponents()
- Item$Properties attributes(ItemAttributeModifiers)
- Item$Properties component(DataComponentType,Object)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
+ App lambda$static$1(RecordCodecBuilder$Instance)
- App lambda$static$3(RecordCodecBuilder$Instance)
+ App lambda$static$6(RecordCodecBuilder$Instance)
+ App lambda$static$7(RecordCodecBuilder$Instance)
+ App lambda$static$8(RecordCodecBuilder$Instance)
- App lambda$static$9(RecordCodecBuilder$Instance)
- boolean canBreakBlockInAdventureMode(BlockInWorld)
- boolean canPlaceOnBlockInAdventureMode(BlockInWorld)
+ boolean hasAdventureModeBreakTagForBlock(Registry,BlockInWorld)
+ boolean hasAdventureModePlaceTagForBlock(Registry,BlockInWorld)
+ boolean hasCustomHoverName()
+ boolean hasTag()
+ boolean isUnbreakable()
- boolean listMatches(List,List)
+ boolean shouldShowInTooltip(int,ItemStack$TooltipPart)
- Codec lambda$static$4()
+ Collection expandBlockState(String)
+ CompoundTag getOrCreateTag()
+ CompoundTag getOrCreateTagElement(String)
+ CompoundTag getTag()
+ CompoundTag getTagElement(String)
+ CompoundTag save(CompoundTag)
- DataComponentMap getComponents()
- DataComponentPatch getComponentsPatch()
- DataComponentPatch lambda$static$2(ItemStack)
- DataResult lambda$static$1(Holder)
+ DataResult lambda$static$3(Item)
- DataResult validate(ItemStack)
+ IllegalArgumentException lambda$addAttributeModifier$17()
+ int getBaseRepairCost()
+ int getHideFlags()
- int hashItemAndComponents(ItemStack)
- int hashStackList(List)
+ ItemStack lambda$optionalFieldOf$11(Optional)
- ItemStack lambda$optionalFieldOf$12(Optional)
+ ItemStack lambda$static$5(Holder,Optional)
- ItemStack lambda$static$7(Optional)
- ItemStack lambda$validate$6(ItemStack)
+ ItemStack of(CompoundTag)
- ItemStack parseOptional(HolderLookup$Provider,CompoundTag)
+ ItemStack setHoverName(Component)
+ List lambda$expandBlockState$14(BlockStateParser$BlockResult)
+ List lambda$expandBlockState$16(BlockStateParser$TagResult)
+ ListTag getEnchantmentTags()
+ Multimap getAttributeModifiers(EquipmentSlot)
+ MutableComponent lambda$expandBlockState$15(Holder)
- Object remove(DataComponentType)
- Object set(DataComponentType,Object)
- Object update(DataComponentType,Object,Object,BiFunction)
- Object update(DataComponentType,Object,UnaryOperator)
+ Optional lambda$optionalFieldOf$12(ItemStack)
- Optional lambda$optionalFieldOf$13(ItemStack)
+ Optional lambda$static$0(ItemStack)
+ Optional lambda$static$4(ItemStack)
- Optional lambda$static$8(ItemStack)
- Optional parse(HolderLookup$Provider,Tag)
- SoundEvent getBreakingSound()
- String lambda$static$0()
+ String lambda$static$2()
- String lambda$validate$5(ItemStack)
- Style lambda$getDisplayName$16(Style)
+ Style lambda$getDisplayName$18(Style)
- Tag save(HolderLookup$Provider,Tag)
- Tag save(HolderLookup$Provider)
- Tag saveOptional(HolderLookup$Provider)
+ void <init>(CompoundTag)
- void <init>(Holder,int,DataComponentPatch)
+ void <init>(Holder,int,Optional)
- void <init>(ItemLike,int,PatchedDataComponentMap)
+ void addAttributeModifier(Holder,AttributeModifier,EquipmentSlot)
- void addAttributeTooltips(Consumer,Player)
- void addModifierTooltip(Consumer,Player,Holder,AttributeModifier)
+ void addTagElement(String,Tag)
- void addToTooltip(DataComponentType,Consumer,TooltipFlag)
+ void appendEnchantmentNames(List,ListTag)
- void applyComponents(DataComponentMap)
- void applyComponents(DataComponentPatch)
- void forEachModifier(EquipmentSlot,BiConsumer)
+ void hideTooltipPart(ItemStack$TooltipPart)
- void lambda$addAttributeTooltips$14(MutableBoolean,Consumer,EquipmentSlot,Player,Holder,AttributeModifier)
+ void lambda$appendEnchantmentNames$13(List,CompoundTag,Enchantment)
- void lambda$enchant$15(Enchantment,int,ItemEnchantments$Mutable)
+ void lambda$hurtAndBreak$10(LivingEntity,EquipmentSlot)
- void lambda$hurtAndBreak$11(LivingEntity,EquipmentSlot)
- void lambda$parse$10(String)
+ void lambda$static$9(DecimalFormat)
+ void removeTagKey(String)
+ void resetHoverName()
+ void setRepairCost(int)
+ void setTag(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ Component getTooltipForId(ItemStack)
+ int getColor(ItemStack)
+ MapId getMapId(ItemStack)
+ void createAndStoreSavedData(ItemStack,Level,int,int,int,boolean,boolean,ResourceKey)
+ void scaleMap(ItemStack,Level,int)
- void scaleMap(ItemStack,Level)
+ void storeMapData(ItemStack,MapId)
```

</details>
<details>
<summary>
net.minecraft.world.item.SuspiciousStewItem
</summary>

```diff
+ void appendMobEffects(ItemStack,List)
+ void lambda$appendHoverText$3(List,SuspiciousEffectHolder$EffectEntry)
+ void lambda$appendMobEffects$1(CompoundTag,Tag)
+ void lambda$finishUsingItem$4(LivingEntity,SuspiciousEffectHolder$EffectEntry)
+ void lambda$listPotionEffects$2(Consumer,List)
+ void lambda$saveMobEffects$0(CompoundTag,Tag)
+ void listPotionEffects(ItemStack,Consumer)
+ void saveMobEffects(ItemStack,List)
```

</details>
<details>
<summary>
net.minecraft.world.item.WritableBookItem
</summary>

```diff
+ boolean makeSureTagIsValid(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.Potion
</summary>

```diff
+ Holder byName(String)
+ String getName(Holder,String)
- String getName(Optional,String)
- String lambda$getName$0(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.Potions
</summary>

```diff
+ Holder register(ResourceKey,Potion)
```

</details>
<details>
<summary>
net.minecraft.world.item.armortrim.ArmorTrim
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
- App lambda$static$1(RecordCodecBuilder$Instance)
- Boolean lambda$static$0(ArmorTrim)
- Boolean lambda$static$2(ArmorTrim)
+ boolean setTrim(RegistryAccess,ItemStack,ArmorTrim)
- int hashCode()
+ Optional getTrim(RegistryAccess,ItemStack,boolean)
+ ResourceLocation lambda$new$2(Holder,Holder)
- ResourceLocation lambda$new$6(Holder,Holder)
+ String lambda$new$1(String,String)
- String lambda$new$5(String,String)
- void <init>(Holder,Holder,boolean)
- void addToTooltip(Consumer,TooltipFlag)
+ void appendUpgradeHoverText(ItemStack,RegistryAccess,List)
+ void lambda$getTrim$5(boolean,String)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.RepairItemRecipe
</summary>

```diff
- void lambda$assemble$0(ItemEnchantments,ItemEnchantments,ItemEnchantments$Mutable,Enchantment)
+ void lambda$assemble$0(Map,Map,ItemStack,Enchantment)
- void lambda$assemble$1(RegistryAccess,ItemEnchantments,ItemEnchantments,ItemEnchantments$Mutable)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TrapDoorBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WitherRoseBlock
</summary>

```diff
+ void <init>(List,BlockBehaviour$Properties)
- void <init>(SuspiciousStewEffects,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BannerBlockEntity
</summary>

```diff
- BannerPatternLayers getPatternsWithBase()
+ int getPatternCount(ItemStack)
+ List createPatterns(DyeColor,ListTag)
+ List getPatterns()
+ ListTag getItemPatterns(ItemStack)
- void <clinit>()
- void applyComponents(DataComponentMap)
- void collectComponents(DataComponentMap$Builder)
+ void fromItem(ItemStack)
- void lambda$load$0(String)
- void removeComponentsFromTag(CompoundTag)
+ void removeLastPattern(ItemStack)
+ void setCustomName(Component)
- void setPatterns(BannerPatternLayers)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BaseContainerBlockEntity
</summary>

```diff
- void applyComponents(DataComponentMap)
- void collectComponents(DataComponentMap$Builder)
- void removeComponentsFromTag(CompoundTag)
+ void setCustomName(Component)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
</summary>

```diff
- BeehiveBlockEntity$Occupant toOccupant()
- boolean hasNectar()
- boolean tick()
- void <init>(BeehiveBlockEntity$Occupant)
+ void <init>(CompoundTag,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
+ ChunkStatus getStatus()
- ChunkStatus getStatus()
+ void setStatus(ChunkStatus)
- void setStatus(ChunkStatus)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
+ ChunkStatus getStatus()
- ChunkStatus getStatus()
+ void setStatus(ChunkStatus)
- void setStatus(ChunkStatus)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetContainerContents
</summary>

```diff
- void lambda$run$5(CompoundTag,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
</summary>

```diff
- void lambda$static$19(LootContextParamSet$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.scores.Score
</summary>

```diff
+ CompoundTag write()
- CompoundTag write(HolderLookup$Provider)
- Score read(CompoundTag,HolderLookup$Provider)
+ Score read(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.scores.Scoreboard
</summary>

```diff
+ ListTag savePlayerScores()
- ListTag savePlayerScores(HolderLookup$Provider)
- void lambda$savePlayerScores$5(HolderLookup$Provider,String,ListTag,Objective,Score)
+ void lambda$savePlayerScores$5(String,ListTag,Objective,Score)
- void lambda$savePlayerScores$6(HolderLookup$Provider,ListTag,String,PlayerScores)
+ void lambda$savePlayerScores$6(ListTag,String,PlayerScores)
- void loadPlayerScores(ListTag,HolderLookup$Provider)
+ void loadPlayerScores(ListTag)
```

</details>
<details>
<summary>
net.minecraft.world.scores.ScoreboardSaveData
</summary>

```diff
+ ListTag saveObjectives()
- ListTag saveObjectives(HolderLookup$Provider)
+ ListTag saveTeams()
- ListTag saveTeams(HolderLookup$Provider)
- ScoreboardSaveData load(CompoundTag,HolderLookup$Provider)
+ ScoreboardSaveData load(CompoundTag)
- void loadObjectives(ListTag,HolderLookup$Provider)
+ void loadObjectives(ListTag)
- void loadTeams(ListTag,HolderLookup$Provider)
+ void loadTeams(ListTag)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.advancements.packs.package-info
- XXX.advancements.packs.UpdateOneTwentyOneAdvancementProvider
+ XXX.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
- XXX.advancements.packs.VanillaAdvancementProvider
+ XXX.advancements.packs.VanillaAdventureAdvancements
- XXX.advancements.packs.VanillaHusbandryAdvancements
+ XXX.advancements.packs.VanillaNetherAdvancements
- XXX.advancements.packs.VanillaStoryAdvancements
+ XXX.advancements.packs.VanillaTheEndAdvancements
+ XXX.animal.allay.Allay
- XXX.animal.allay.Allay$JukeboxListener
+ XXX.animal.allay.Allay$VibrationUser
- XXX.animal.allay.AllayAi
+ XXX.animal.allay.package-info
- XXX.animal.armadillo.Armadillo
+ XXX.animal.armadillo.Armadillo$1
- XXX.animal.armadillo.Armadillo$2
+ XXX.animal.armadillo.Armadillo$ArmadilloState
- XXX.animal.armadillo.Armadillo$ArmadilloState$1
+ XXX.animal.armadillo.Armadillo$ArmadilloState$2
- XXX.animal.armadillo.Armadillo$ArmadilloState$3
+ XXX.animal.armadillo.Armadillo$ArmadilloState$4
- XXX.animal.armadillo.ArmadilloAi
+ XXX.animal.armadillo.ArmadilloAi$1
- XXX.animal.armadillo.ArmadilloAi$ArmadilloBallUp
+ XXX.animal.armadillo.ArmadilloAi$ArmadilloPanic
- XXX.animal.armadillo.package-info
+ XXX.animal.axolotl.Axolotl
- XXX.animal.axolotl.Axolotl$AxolotlGroupData
+ XXX.animal.axolotl.Axolotl$AxolotlLookControl
- XXX.animal.axolotl.Axolotl$AxolotlMoveControl
+ XXX.animal.axolotl.Axolotl$Variant
- XXX.animal.axolotl.AxolotlAi
+ XXX.animal.axolotl.package-info
+ XXX.animal.axolotl.PlayDead
- XXX.animal.axolotl.ValidatePlayDead
- XXX.animal.camel.Camel
+ XXX.animal.camel.Camel$CamelBodyRotationControl
- XXX.animal.camel.Camel$CamelLookControl
+ XXX.animal.camel.Camel$CamelMoveControl
- XXX.animal.camel.CamelAi
+ XXX.animal.camel.CamelAi$CamelPanic
- XXX.animal.camel.CamelAi$RandomSitting
+ XXX.animal.camel.package-info
- XXX.animal.frog.Frog
+ XXX.animal.frog.Frog$FrogLookControl
- XXX.animal.frog.Frog$FrogNodeEvaluator
+ XXX.animal.frog.Frog$FrogPathNavigation
- XXX.animal.frog.FrogAi
- XXX.animal.frog.package-info
+ XXX.animal.frog.ShootTongue
- XXX.animal.frog.ShootTongue$1
+ XXX.animal.frog.ShootTongue$State
- XXX.animal.frog.Tadpole
+ XXX.animal.frog.TadpoleAi
+ XXX.animal.goat.Goat
- XXX.animal.goat.GoatAi
+ XXX.animal.goat.package-info
- XXX.animal.horse.AbstractChestedHorse
+ XXX.animal.horse.AbstractChestedHorse$1
- XXX.animal.horse.AbstractHorse
+ XXX.animal.horse.AbstractHorse$1
- XXX.animal.horse.AbstractHorse$2
+ XXX.animal.horse.Donkey
- XXX.animal.horse.Horse
+ XXX.animal.horse.Horse$HorseGroupData
- XXX.animal.horse.Llama
+ XXX.animal.horse.Llama$LlamaAttackWolfGoal
- XXX.animal.horse.Llama$LlamaGroupData
+ XXX.animal.horse.Llama$LlamaHurtByTargetGoal
- XXX.animal.horse.Llama$Variant
+ XXX.animal.horse.Markings
- XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.Variant
- XXX.animal.horse.ZombieHorse
- XXX.animal.sniffer.package-info
+ XXX.animal.sniffer.Sniffer
- XXX.animal.sniffer.Sniffer$1
+ XXX.animal.sniffer.Sniffer$State
- XXX.animal.sniffer.SnifferAi
+ XXX.animal.sniffer.SnifferAi$1
- XXX.animal.sniffer.SnifferAi$2
+ XXX.animal.sniffer.SnifferAi$3
- XXX.animal.sniffer.SnifferAi$Digging
+ XXX.animal.sniffer.SnifferAi$FeelingHappy
- XXX.animal.sniffer.SnifferAi$FinishedDigging
+ XXX.animal.sniffer.SnifferAi$Scenting
- XXX.animal.sniffer.SnifferAi$Searching
+ XXX.animal.sniffer.SnifferAi$Sniffing
+ XXX.arguments.blocks.BlockInput
- XXX.arguments.blocks.BlockPredicateArgument
+ XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
- XXX.arguments.blocks.BlockPredicateArgument$Result
+ XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
- XXX.arguments.blocks.BlockStateArgument
+ XXX.arguments.blocks.BlockStateParser
- XXX.arguments.blocks.BlockStateParser$BlockResult
+ XXX.arguments.blocks.BlockStateParser$TagResult
- XXX.arguments.blocks.package-info
+ XXX.arguments.coordinates.BlockPosArgument
- XXX.arguments.coordinates.ColumnPosArgument
+ XXX.arguments.coordinates.Coordinates
- XXX.arguments.coordinates.LocalCoordinates
+ XXX.arguments.coordinates.package-info
+ XXX.arguments.coordinates.RotationArgument
- XXX.arguments.coordinates.SwizzleArgument
+ XXX.arguments.coordinates.Vec2Argument
- XXX.arguments.coordinates.Vec3Argument
+ XXX.arguments.coordinates.WorldCoordinate
- XXX.arguments.coordinates.WorldCoordinates
- XXX.arguments.item.FunctionArgument
+ XXX.arguments.item.FunctionArgument$1
- XXX.arguments.item.FunctionArgument$2
+ XXX.arguments.item.FunctionArgument$Result
- XXX.arguments.item.ItemArgument
+ XXX.arguments.item.ItemInput
- XXX.arguments.item.ItemParser
+ XXX.arguments.item.ItemParser$1
- XXX.arguments.item.ItemParser$ItemResult
+ XXX.arguments.item.ItemPredicateArgument
- XXX.arguments.item.ItemPredicateArgument$Result
+ XXX.arguments.item.ItemPredicateParser
- XXX.arguments.item.ItemPredicateParser$1
+ XXX.arguments.item.ItemSyntaxParser
- XXX.arguments.item.ItemSyntaxParser$State
+ XXX.arguments.item.ItemSyntaxParser$SuggestionsVisitor
- XXX.arguments.item.ItemSyntaxParser$Visitor
+ XXX.arguments.item.package-info
+ XXX.arguments.selector.EntitySelector
- XXX.arguments.selector.EntitySelector$1
+ XXX.arguments.selector.EntitySelectorParser
- XXX.arguments.selector.package-info
+ XXX.atlas.sources.DirectoryLister
- XXX.atlas.sources.LazyLoadedImage
- XXX.atlas.sources.package-info
+ XXX.atlas.sources.PalettedPermutations
- XXX.atlas.sources.PalettedPermutations$PalettedSpriteSupplier
+ XXX.atlas.sources.SingleFile
- XXX.atlas.sources.SourceFilter
+ XXX.atlas.sources.Unstitcher
- XXX.atlas.sources.Unstitcher$Region
+ XXX.atlas.sources.Unstitcher$RegionInstance
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BannerPatternLayers$Builder
- XXX.block.entity.BannerPatterns
+ XXX.block.entity.BarrelBlockEntity
- XXX.block.entity.BarrelBlockEntity$1
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$BeeData
- XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ XXX.block.entity.DecoratedPotBlockEntity$Decorations
- XXX.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ XXX.block.entity.DecoratedPotPatterns
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.EnderChestBlockEntity$1
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.HangingSignBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.PotDecorations
- XXX.block.model.BakedQuad
+ XXX.block.model.BlockElement
- XXX.block.model.BlockElement$1
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementRotation
+ XXX.block.model.BlockFaceUV
- XXX.block.model.BlockFaceUV$Deserializer
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModel$GuiLight
- XXX.block.model.BlockModel$LoopException
+ XXX.block.model.BlockModelDefinition
- XXX.block.model.BlockModelDefinition$Context
+ XXX.block.model.BlockModelDefinition$Deserializer
- XXX.block.model.BlockModelDefinition$MissingVariantException
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$1
+ XXX.block.model.ItemModelGenerator$Span
- XXX.block.model.ItemModelGenerator$SpanFacing
+ XXX.block.model.ItemOverride
- XXX.block.model.ItemOverride$Deserializer
+ XXX.block.model.ItemOverride$Predicate
- XXX.block.model.ItemOverrides
+ XXX.block.model.ItemOverrides$BakedOverride
- XXX.block.model.ItemOverrides$PropertyMatcher
+ XXX.block.model.ItemTransform
- XXX.block.model.ItemTransform$Deserializer
+ XXX.block.model.ItemTransforms
- XXX.block.model.ItemTransforms$1
+ XXX.block.model.ItemTransforms$Deserializer
- XXX.block.model.MultiVariant
+ XXX.block.model.MultiVariant$Deserializer
+ XXX.block.model.package-info
- XXX.block.model.Variant
+ XXX.block.model.Variant$Deserializer
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
- XXX.chat.contents.BlockDataSource
+ XXX.chat.contents.DataSource
- XXX.chat.contents.DataSource$Type
+ XXX.chat.contents.EntityDataSource
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.NbtContents
+ XXX.chat.contents.package-info
+ XXX.chat.contents.PlainTextContents
- XXX.chat.contents.PlainTextContents$1
+ XXX.chat.contents.PlainTextContents$LiteralContents
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.StorageDataSource
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
- XXX.chat.numbers.BlankFormat
+ XXX.chat.numbers.BlankFormat$1
- XXX.chat.numbers.FixedFormat
+ XXX.chat.numbers.FixedFormat$1
- XXX.chat.numbers.NumberFormat
+ XXX.chat.numbers.NumberFormatType
- XXX.chat.numbers.NumberFormatTypes
+ XXX.chat.numbers.package-info
+ XXX.chat.numbers.StyledFormat
- XXX.chat.numbers.StyledFormat$1
+ XXX.chat.report.AbuseReportSender
- XXX.chat.report.AbuseReportSender$1
+ XXX.chat.report.AbuseReportSender$SendException
- XXX.chat.report.AbuseReportSender$Services
+ XXX.chat.report.BanReason
- XXX.chat.report.ChatReport
+ XXX.chat.report.ChatReport$Builder
- XXX.chat.report.ChatReportContextBuilder
+ XXX.chat.report.ChatReportContextBuilder$Collector
- XXX.chat.report.ChatReportContextBuilder$Handler
+ XXX.chat.report.NameReport
- XXX.chat.report.NameReport$Builder
- XXX.chat.report.package-info
+ XXX.chat.report.Report
- XXX.chat.report.Report$Builder
+ XXX.chat.report.Report$CannotBuildReason
- XXX.chat.report.Report$Result
+ XXX.chat.report.ReportEnvironment
- XXX.chat.report.ReportEnvironment$Server
+ XXX.chat.report.ReportEnvironment$Server$Realm
- XXX.chat.report.ReportEnvironment$Server$ThirdParty
+ XXX.chat.report.ReportingContext
+ XXX.chat.report.ReportReason
- XXX.chat.report.ReportType
- XXX.chat.report.SkinReport
+ XXX.chat.report.SkinReport$Builder
- XXX.chunk.status.ChunkStatus$GenerationTask
- XXX.chunk.status.ChunkStatusTasks
- XXX.chunk.status.package-info
- XXX.chunk.status.ToFullChunk
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.ChunkSerializer
- XXX.client.model.BoggedModel
+ XXX.client.model.BookModel
- XXX.client.model.BreezeModel
+ XXX.client.model.CamelModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestBoatModel
+ XXX.client.model.ChestedHorseModel
- XXX.client.model.ChestRaftModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColorableAgeableListModel
+ XXX.client.model.ColorableHierarchicalModel
- XXX.client.model.CowModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FoxModel
- XXX.client.model.FrogModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GoatModel
- XXX.client.model.GuardianModel
+ XXX.client.model.HeadedModel
- XXX.client.model.HierarchicalModel
+ XXX.client.model.HoglinModel
- XXX.client.model.HorseModel
+ XXX.client.model.HumanoidArmorModel
- XXX.client.model.HumanoidModel
+ XXX.client.model.HumanoidModel$1
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.ListModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
- XXX.client.model.MinecartModel
+ XXX.client.model.Model
- XXX.client.model.ModelUtils
+ XXX.client.model.OcelotModel
- XXX.client.model.package-info
- XXX.client.model.PandaModel
+ XXX.client.model.ParrotModel
- XXX.client.model.ParrotModel$1
+ XXX.client.model.ParrotModel$State
- XXX.client.model.PhantomModel
- XXX.client.model.PiglinHeadModel
+ XXX.client.model.PiglinModel
+ XXX.client.model.PigModel
- XXX.client.model.PlayerModel
+ XXX.client.model.PolarBearModel
- XXX.client.model.PufferfishBigModel
+ XXX.client.model.PufferfishMidModel
- XXX.client.model.PufferfishSmallModel
+ XXX.client.model.QuadrupedModel
- XXX.client.model.RabbitModel
+ XXX.client.model.RaftModel
- XXX.client.model.RavagerModel
+ XXX.client.model.SalmonModel
- XXX.client.model.SheepFurModel
+ XXX.client.model.SheepModel
- XXX.client.model.ShieldModel
+ XXX.client.model.ShulkerBulletModel
- XXX.client.model.ShulkerModel
+ XXX.client.model.SilverfishModel
- XXX.client.model.SkeletonModel
+ XXX.client.model.SkullModel
- XXX.client.model.SkullModelBase
+ XXX.client.model.SlimeModel
- XXX.client.model.SnifferModel
+ XXX.client.model.SnowGolemModel
- XXX.client.model.SpiderModel
+ XXX.client.model.SquidModel
- XXX.client.model.StriderModel
+ XXX.client.model.TadpoleModel
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerHeadModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WardenModel
- XXX.client.model.WaterPatchModel
+ XXX.client.model.WindChargeModel
- XXX.client.model.WitchModel
+ XXX.client.model.WitherBossModel
- XXX.client.model.WolfModel
+ XXX.client.model.ZombieModel
- XXX.client.model.ZombieVillagerModel
+ XXX.client.multiplayer.AccountProfileKeyPairManager
- XXX.client.multiplayer.ChunkBatchSizeCalculator
+ XXX.client.multiplayer.ClientAdvancements
- XXX.client.multiplayer.ClientAdvancements$Listener
+ XXX.client.multiplayer.ClientChunkCache
- XXX.client.multiplayer.ClientChunkCache$Storage
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl
- XXX.client.multiplayer.ClientCommonPacketListenerImpl$DeferredPacket
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen
- XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen$PendingRequest
+ XXX.client.multiplayer.ClientConfigurationPacketListenerImpl
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl$State
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientLevel$1
- XXX.client.multiplayer.ClientLevel$ClientLevelData
+ XXX.client.multiplayer.ClientLevel$EntityCallbacks
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientRegistryLayer
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.ClientSuggestionProvider$1
+ XXX.client.multiplayer.CommonListenerCookie
- XXX.client.multiplayer.DebugSampleSubscriber
+ XXX.client.multiplayer.KnownPacksManager
- XXX.client.multiplayer.LegacyServerPinger
+ XXX.client.multiplayer.LegacyServerPinger$Output
- XXX.client.multiplayer.LevelLoadStatusManager
+ XXX.client.multiplayer.LevelLoadStatusManager$1
- XXX.client.multiplayer.LevelLoadStatusManager$Status
+ XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
- XXX.client.multiplayer.PingDebugMonitor
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ProfileKeyPairManager
+ XXX.client.multiplayer.ProfileKeyPairManager$1
- XXX.client.multiplayer.RegistryDataCollector
+ XXX.client.multiplayer.RegistryDataCollector$ContentsCollector
- XXX.client.multiplayer.ServerData
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerData$State
+ XXX.client.multiplayer.ServerData$Type
- XXX.client.multiplayer.ServerList
+ XXX.client.multiplayer.ServerStatusPinger
- XXX.client.multiplayer.ServerStatusPinger$1
+ XXX.client.multiplayer.ServerStatusPinger$2
- XXX.client.multiplayer.TagCollector
+ XXX.client.multiplayer.TransferState
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BlockMarker
- XXX.client.particle.BlockMarker$Provider
+ XXX.client.particle.BreakingItemParticle
- XXX.client.particle.BreakingItemParticle$Provider
+ XXX.client.particle.BreakingItemParticle$SlimeProvider
- XXX.client.particle.BreakingItemParticle$SnowballProvider
+ XXX.client.particle.BubbleColumnUpParticle
- XXX.client.particle.BubbleColumnUpParticle$Provider
+ XXX.client.particle.BubbleParticle
- XXX.client.particle.BubbleParticle$Provider
+ XXX.client.particle.BubblePopParticle
- XXX.client.particle.BubblePopParticle$Provider
+ XXX.client.particle.CampfireSmokeParticle
- XXX.client.particle.CampfireSmokeParticle$CosyProvider
+ XXX.client.particle.CampfireSmokeParticle$SignalProvider
- XXX.client.particle.CherryParticle
+ XXX.client.particle.CritParticle
- XXX.client.particle.CritParticle$DamageIndicatorProvider
+ XXX.client.particle.CritParticle$MagicProvider
- XXX.client.particle.CritParticle$Provider
+ XXX.client.particle.DragonBreathParticle
- XXX.client.particle.DragonBreathParticle$Provider
+ XXX.client.particle.DripParticle
- XXX.client.particle.DripParticle$CoolingDripHangParticle
+ XXX.client.particle.DripParticle$DripHangParticle
- XXX.client.particle.DripParticle$DripLandParticle
+ XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
- XXX.client.particle.DripParticle$FallAndLandParticle
+ XXX.client.particle.DripParticle$FallingParticle
- XXX.client.particle.DripParticle$HoneyFallAndLandParticle
+ XXX.client.particle.DustColorTransitionParticle
- XXX.client.particle.DustColorTransitionParticle$Provider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$Provider
+ XXX.client.particle.DustParticleBase
- XXX.client.particle.DustPlumeParticle
+ XXX.client.particle.DustPlumeParticle$Provider
- XXX.client.particle.EndRodParticle
+ XXX.client.particle.EndRodParticle$Provider
- XXX.client.particle.ExplodeParticle
+ XXX.client.particle.ExplodeParticle$Provider
- XXX.client.particle.FallingDustParticle
+ XXX.client.particle.FallingDustParticle$Provider
- XXX.client.particle.FireworkParticles
+ XXX.client.particle.FireworkParticles$1
- XXX.client.particle.FireworkParticles$FlashProvider
+ XXX.client.particle.FireworkParticles$OverlayParticle
- XXX.client.particle.FireworkParticles$SparkParticle
+ XXX.client.particle.FireworkParticles$SparkProvider
- XXX.client.particle.FireworkParticles$Starter
+ XXX.client.particle.FlameParticle
- XXX.client.particle.FlameParticle$Provider
+ XXX.client.particle.FlameParticle$SmallFlameProvider
- XXX.client.particle.FlyTowardsPositionParticle
+ XXX.client.particle.FlyTowardsPositionParticle$EnchantProvider
- XXX.client.particle.FlyTowardsPositionParticle$NautilusProvider
+ XXX.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
- XXX.client.particle.GlowParticle
+ XXX.client.particle.GlowParticle$ElectricSparkProvider
- XXX.client.particle.GlowParticle$GlowSquidProvider
+ XXX.client.particle.GlowParticle$ScrapeProvider
- XXX.client.particle.GlowParticle$WaxOffProvider
+ XXX.client.particle.GlowParticle$WaxOnProvider
- XXX.client.particle.GustParticle
+ XXX.client.particle.GustParticle$Provider
- XXX.client.particle.GustSeedParticle
+ XXX.client.particle.GustSeedParticle$Provider
- XXX.client.particle.HeartParticle
+ XXX.client.particle.HeartParticle$AngryVillagerProvider
- XXX.client.particle.HeartParticle$Provider
+ XXX.client.particle.HugeExplosionParticle
- XXX.client.particle.HugeExplosionParticle$Provider
+ XXX.client.particle.HugeExplosionSeedParticle
- XXX.client.particle.HugeExplosionSeedParticle$Provider
+ XXX.client.particle.ItemPickupParticle
- XXX.client.particle.LargeSmokeParticle
+ XXX.client.particle.LargeSmokeParticle$Provider
- XXX.client.particle.LavaParticle
+ XXX.client.particle.LavaParticle$Provider
- XXX.client.particle.MobAppearanceParticle
+ XXX.client.particle.MobAppearanceParticle$Provider
- XXX.client.particle.NoRenderParticle
+ XXX.client.particle.NoteParticle
- XXX.client.particle.NoteParticle$Provider
+ XXX.client.particle.package-info
+ XXX.client.particle.Particle
- XXX.client.particle.Particle$LifetimeAlpha
+ XXX.client.particle.ParticleDescription
- XXX.client.particle.ParticleEngine
+ XXX.client.particle.ParticleEngine$1ParticleDefinition
- XXX.client.particle.ParticleEngine$MutableSpriteSet
+ XXX.client.particle.ParticleEngine$SpriteParticleRegistration
- XXX.client.particle.ParticleProvider
+ XXX.client.particle.ParticleProvider$Sprite
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.ParticleRenderType$1
- XXX.client.particle.ParticleRenderType$2
+ XXX.client.particle.ParticleRenderType$3
- XXX.client.particle.ParticleRenderType$4
+ XXX.client.particle.ParticleRenderType$5
- XXX.client.particle.ParticleRenderType$6
+ XXX.client.particle.PlayerCloudParticle
- XXX.client.particle.PlayerCloudParticle$Provider
+ XXX.client.particle.PlayerCloudParticle$SneezeProvider
- XXX.client.particle.PortalParticle
+ XXX.client.particle.PortalParticle$Provider
- XXX.client.particle.ReversePortalParticle
+ XXX.client.particle.ReversePortalParticle$ReversePortalProvider
- XXX.client.particle.RisingParticle
+ XXX.client.particle.SculkChargeParticle
- XXX.client.particle.SculkChargeParticle$Provider
+ XXX.client.particle.SculkChargePopParticle
- XXX.client.particle.SculkChargePopParticle$Provider
+ XXX.client.particle.ShriekParticle
- XXX.client.particle.ShriekParticle$Provider
+ XXX.client.particle.SimpleAnimatedParticle
- XXX.client.particle.SingleQuadParticle
+ XXX.client.particle.SingleQuadParticle$FacingCameraMode
- XXX.client.particle.SmokeParticle
+ XXX.client.particle.SmokeParticle$Provider
- XXX.client.particle.SnowflakeParticle
+ XXX.client.particle.SnowflakeParticle$Provider
- XXX.client.particle.SonicBoomParticle
+ XXX.client.particle.SonicBoomParticle$Provider
- XXX.client.particle.SoulParticle
+ XXX.client.particle.SoulParticle$EmissiveProvider
- XXX.client.particle.SoulParticle$Provider
+ XXX.client.particle.SpellParticle
- XXX.client.particle.SpellParticle$AmbientMobProvider
+ XXX.client.particle.SpellParticle$InstantProvider
- XXX.client.particle.SpellParticle$MobProvider
+ XXX.client.particle.SpellParticle$Provider
- XXX.client.particle.SpellParticle$WitchProvider
+ XXX.client.particle.SpitParticle
- XXX.client.particle.SpitParticle$Provider
+ XXX.client.particle.SplashParticle
- XXX.client.particle.SplashParticle$Provider
+ XXX.client.particle.SpriteSet
- XXX.client.particle.SquidInkParticle
+ XXX.client.particle.SquidInkParticle$GlowInkProvider
- XXX.client.particle.SquidInkParticle$Provider
+ XXX.client.particle.SuspendedParticle
- XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
+ XXX.client.particle.SuspendedParticle$UnderwaterProvider
- XXX.client.particle.SuspendedParticle$WarpedSporeProvider
+ XXX.client.particle.SuspendedTownParticle
- XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
+ XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- XXX.client.particle.SuspendedTownParticle$EggCrackProvider
+ XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
- XXX.client.particle.SuspendedTownParticle$Provider
+ XXX.client.particle.TerrainParticle
- XXX.client.particle.TerrainParticle$Provider
+ XXX.client.particle.TextureSheetParticle
- XXX.client.particle.TotemParticle
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
+ XXX.client.particle.TrialSpawnerDetectionParticle
- XXX.client.particle.TrialSpawnerDetectionParticle$Provider
+ XXX.client.particle.VibrationSignalParticle
- XXX.client.particle.VibrationSignalParticle$Provider
+ XXX.client.particle.WakeParticle
- XXX.client.particle.WakeParticle$Provider
+ XXX.client.particle.WaterCurrentDownParticle
- XXX.client.particle.WaterCurrentDownParticle$Provider
+ XXX.client.particle.WaterDropParticle
- XXX.client.particle.WaterDropParticle$Provider
+ XXX.client.particle.WhiteAshParticle
- XXX.client.particle.WhiteAshParticle$Provider
+ XXX.client.particle.WhiteSmokeParticle
- XXX.client.particle.WhiteSmokeParticle$Provider
- XXX.client.player.AbstractClientPlayer
+ XXX.client.player.Input
- XXX.client.player.KeyboardInput
+ XXX.client.player.LocalPlayer
+ XXX.client.player.package-info
- XXX.client.player.RemotePlayer
- XXX.client.profiling.ClientMetricsSamplersProvider
+ XXX.client.profiling.package-info
- XXX.client.quickplay.package-info
- XXX.client.quickplay.QuickPlay
+ XXX.client.quickplay.QuickPlayLog
- XXX.client.quickplay.QuickPlayLog$1
+ XXX.client.quickplay.QuickPlayLog$QuickPlayEntry
- XXX.client.quickplay.QuickPlayLog$QuickPlayWorld
+ XXX.client.quickplay.QuickPlayLog$Type
+ XXX.client.renderer.BiomeColors
- XXX.client.renderer.BlockEntityWithoutLevelRenderer
+ XXX.client.renderer.CubeMap
- XXX.client.renderer.DimensionSpecialEffects
+ XXX.client.renderer.DimensionSpecialEffects$EndEffects
- XXX.client.renderer.DimensionSpecialEffects$NetherEffects
+ XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
- XXX.client.renderer.DimensionSpecialEffects$SkyType
+ XXX.client.renderer.EffectInstance
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.FogRenderer
- XXX.client.renderer.FogRenderer$BlindnessFogFunction
+ XXX.client.renderer.FogRenderer$DarknessFogFunction
- XXX.client.renderer.FogRenderer$FogData
+ XXX.client.renderer.FogRenderer$FogMode
- XXX.client.renderer.FogRenderer$MobEffectFogFunction
+ XXX.client.renderer.GameRenderer
- XXX.client.renderer.GameRenderer$1
+ XXX.client.renderer.GameRenderer$ResourceCache
- XXX.client.renderer.GpuWarnlistManager
+ XXX.client.renderer.GpuWarnlistManager$Preparations
- XXX.client.renderer.ItemBlockRenderTypes
+ XXX.client.renderer.ItemInHandRenderer
- XXX.client.renderer.ItemInHandRenderer$1
+ XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
- XXX.client.renderer.ItemModelShaper
+ XXX.client.renderer.LevelRenderer
- XXX.client.renderer.LevelRenderer$TransparencyShaderException
+ XXX.client.renderer.LightTexture
- XXX.client.renderer.MultiBufferSource
+ XXX.client.renderer.MultiBufferSource$BufferSource
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ XXX.client.renderer.package-info
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$BooleanStateShard
+ XXX.client.renderer.RenderStateShard$ColorLogicStateShard
- XXX.client.renderer.RenderStateShard$CullStateShard
+ XXX.client.renderer.RenderStateShard$DepthTestStateShard
- XXX.client.renderer.RenderStateShard$EmptyTextureStateShard
+ XXX.client.renderer.RenderStateShard$LayeringStateShard
- XXX.client.renderer.RenderStateShard$LightmapStateShard
+ XXX.client.renderer.RenderStateShard$LineStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
- XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ XXX.client.renderer.RenderStateShard$OutputStateShard
- XXX.client.renderer.RenderStateShard$OverlayStateShard
+ XXX.client.renderer.RenderStateShard$ShaderStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
+ XXX.client.renderer.RenderStateShard$WriteMaskStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$CompositeRenderType
- XXX.client.renderer.RenderType$CompositeState
+ XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- XXX.client.renderer.RenderType$OutlineProperty
+ XXX.client.renderer.RunningTrimmedMean
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.SectionBufferBuilderPack
- XXX.client.renderer.SectionBufferBuilderPool
+ XXX.client.renderer.SectionOcclusionGraph
- XXX.client.renderer.SectionOcclusionGraph$GraphEvents
+ XXX.client.renderer.SectionOcclusionGraph$GraphState
- XXX.client.renderer.SectionOcclusionGraph$GraphStorage
+ XXX.client.renderer.SectionOcclusionGraph$Node
- XXX.client.renderer.SectionOcclusionGraph$SectionToNodeMap
+ XXX.client.renderer.ShaderInstance
- XXX.client.renderer.ShaderInstance$1
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.client.resources.ClientPackSource
+ XXX.client.resources.DefaultPlayerSkin
- XXX.client.resources.FoliageColorReloadListener
+ XXX.client.resources.GrassColorReloadListener
- XXX.client.resources.IndexedAssetSource
+ XXX.client.resources.LegacyStuffWrapper
- XXX.client.resources.MobEffectTextureManager
+ XXX.client.resources.package-info
+ XXX.client.resources.PaintingTextureManager
- XXX.client.resources.PlayerSkin
+ XXX.client.resources.PlayerSkin$Model
- XXX.client.resources.SkinManager
+ XXX.client.resources.SkinManager$1
- XXX.client.resources.SkinManager$2
+ XXX.client.resources.SkinManager$CacheKey
- XXX.client.resources.SkinManager$TextureCache
+ XXX.client.resources.SplashManager
- XXX.client.resources.TextureAtlasHolder
+ XXX.client.searchtree.FullTextSearchTree
- XXX.client.searchtree.IdSearchTree
+ XXX.client.searchtree.IntersectionIterator
- XXX.client.searchtree.MergingUniqueIterator
- XXX.client.searchtree.package-info
+ XXX.client.searchtree.PlainTextSearchTree
- XXX.client.searchtree.RefreshableSearchTree
+ XXX.client.searchtree.ResourceLocationSearchTree
- XXX.client.searchtree.ResourceLocationSearchTree$1
+ XXX.client.searchtree.ResourceLocationSearchTree$2
- XXX.client.searchtree.SearchRegistry
+ XXX.client.searchtree.SearchRegistry$Key
- XXX.client.searchtree.SearchRegistry$TreeBuilderSupplier
+ XXX.client.searchtree.SearchRegistry$TreeEntry
- XXX.client.searchtree.SearchTree
+ XXX.client.searchtree.SuffixArray
+ XXX.client.server.IntegratedPlayerList
- XXX.client.server.IntegratedServer
+ XXX.client.server.LanServer
- XXX.client.server.LanServerDetection
+ XXX.client.server.LanServerDetection$LanServerDetector
- XXX.client.server.LanServerDetection$LanServerList
+ XXX.client.server.LanServerPinger
- XXX.client.server.package-info
+ XXX.client.sounds.AudioStream
- XXX.client.sounds.ChannelAccess
+ XXX.client.sounds.ChannelAccess$ChannelHandle
- XXX.client.sounds.LoopingAudioStream
+ XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
- XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
+ XXX.client.sounds.MusicManager
- XXX.client.sounds.package-info
- XXX.client.sounds.SoundBufferLibrary
+ XXX.client.sounds.SoundEngine
- XXX.client.sounds.SoundEngine$DeviceCheckState
+ XXX.client.sounds.SoundEngineExecutor
- XXX.client.sounds.SoundEventListener
+ XXX.client.sounds.SoundManager
- XXX.client.sounds.SoundManager$1
+ XXX.client.sounds.SoundManager$2
- XXX.client.sounds.SoundManager$Preparations
+ XXX.client.sounds.SoundManager$Preparations$1
- XXX.client.sounds.WeighedSoundEvents
+ XXX.client.sounds.Weighted
+ XXX.client.telemetry.ClientTelemetryManager
- XXX.client.telemetry.package-info
- XXX.client.telemetry.TelemetryEventInstance
+ XXX.client.telemetry.TelemetryEventLog
- XXX.client.telemetry.TelemetryEventLogger
+ XXX.client.telemetry.TelemetryEventSender
- XXX.client.telemetry.TelemetryEventType
+ XXX.client.telemetry.TelemetryEventType$Builder
- XXX.client.telemetry.TelemetryLogManager
+ XXX.client.telemetry.TelemetryProperty
- XXX.client.telemetry.TelemetryProperty$Exporter
+ XXX.client.telemetry.TelemetryProperty$GameMode
- XXX.client.telemetry.TelemetryProperty$ServerType
+ XXX.client.telemetry.TelemetryPropertyMap
- XXX.client.telemetry.TelemetryPropertyMap$1
+ XXX.client.telemetry.TelemetryPropertyMap$Builder
- XXX.client.telemetry.WorldSessionTelemetryManager
+ XXX.client.tutorial.BundleTutorial
- XXX.client.tutorial.CompletedTutorialStepInstance
+ XXX.client.tutorial.CraftPlanksTutorialStep
- XXX.client.tutorial.FindTreeTutorialStepInstance
+ XXX.client.tutorial.MovementTutorialStepInstance
- XXX.client.tutorial.OpenInventoryTutorialStep
- XXX.client.tutorial.package-info
+ XXX.client.tutorial.PunchTreeTutorialStepInstance
- XXX.client.tutorial.Tutorial
+ XXX.client.tutorial.Tutorial$TimedToast
- XXX.client.tutorial.TutorialStepInstance
+ XXX.client.tutorial.TutorialSteps
- XXX.commands.arguments.AngleArgument
+ XXX.commands.arguments.AngleArgument$SingleAngle
- XXX.commands.arguments.ArgumentSignatures
+ XXX.commands.arguments.ArgumentSignatures$Entry
- XXX.commands.arguments.ArgumentSignatures$Signer
+ XXX.commands.arguments.ColorArgument
- XXX.commands.arguments.ComponentArgument
+ XXX.commands.arguments.CompoundTagArgument
- XXX.commands.arguments.DimensionArgument
+ XXX.commands.arguments.EntityAnchorArgument
- XXX.commands.arguments.EntityAnchorArgument$Anchor
+ XXX.commands.arguments.EntityArgument
- XXX.commands.arguments.EntityArgument$Info
+ XXX.commands.arguments.EntityArgument$Info$Template
- XXX.commands.arguments.GameModeArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.HeightmapTypeArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.NbtPathArgument
+ XXX.commands.arguments.NbtPathArgument$AllElementsNode
- XXX.commands.arguments.NbtPathArgument$CompoundChildNode
+ XXX.commands.arguments.NbtPathArgument$IndexedElementNode
- XXX.commands.arguments.NbtPathArgument$MatchElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchObjectNode
- XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ XXX.commands.arguments.NbtPathArgument$NbtPath
- XXX.commands.arguments.NbtPathArgument$Node
+ XXX.commands.arguments.NbtTagArgument
- XXX.commands.arguments.ObjectiveArgument
+ XXX.commands.arguments.ObjectiveCriteriaArgument
- XXX.commands.arguments.OperationArgument
+ XXX.commands.arguments.OperationArgument$Operation
- XXX.commands.arguments.OperationArgument$SimpleOperation
- XXX.commands.arguments.package-info
+ XXX.commands.arguments.ParticleArgument
- XXX.commands.arguments.RangeArgument
+ XXX.commands.arguments.RangeArgument$Floats
- XXX.commands.arguments.RangeArgument$Ints
+ XXX.commands.arguments.ResourceArgument
- XXX.commands.arguments.ResourceArgument$Info
+ XXX.commands.arguments.ResourceArgument$Info$Template
- XXX.commands.arguments.ResourceKeyArgument
+ XXX.commands.arguments.ResourceKeyArgument$Info
- XXX.commands.arguments.ResourceKeyArgument$Info$Template
+ XXX.commands.arguments.ResourceLocationArgument
- XXX.commands.arguments.ResourceOrTagArgument
+ XXX.commands.arguments.ResourceOrTagArgument$Info
- XXX.commands.arguments.ResourceOrTagArgument$Info$Template
+ XXX.commands.arguments.ResourceOrTagArgument$ResourceResult
- XXX.commands.arguments.ResourceOrTagArgument$Result
+ XXX.commands.arguments.ResourceOrTagArgument$TagResult
- XXX.commands.arguments.ResourceOrTagKeyArgument
+ XXX.commands.arguments.ResourceOrTagKeyArgument$Info
- XXX.commands.arguments.ResourceOrTagKeyArgument$Info$Template
+ XXX.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
- XXX.commands.arguments.ResourceOrTagKeyArgument$Result
+ XXX.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ XXX.commands.arguments.ScoreboardSlotArgument
- XXX.commands.arguments.ScoreHolderArgument
+ XXX.commands.arguments.ScoreHolderArgument$Info
- XXX.commands.arguments.ScoreHolderArgument$Info$Template
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.SignedArgument
+ XXX.commands.arguments.SlotArgument
- XXX.commands.arguments.StringRepresentableArgument
+ XXX.commands.arguments.StyleArgument
- XXX.commands.arguments.TeamArgument
+ XXX.commands.arguments.TemplateMirrorArgument
- XXX.commands.arguments.TemplateRotationArgument
+ XXX.commands.arguments.TimeArgument
- XXX.commands.arguments.TimeArgument$Info
+ XXX.commands.arguments.TimeArgument$Info$Template
- XXX.commands.arguments.UuidArgument
+ XXX.commands.execution.ChainModifiers
- XXX.commands.execution.CommandQueueEntry
+ XXX.commands.execution.CustomCommandExecutor
- XXX.commands.execution.CustomCommandExecutor$CommandAdapter
+ XXX.commands.execution.CustomCommandExecutor$WithErrorHandling
- XXX.commands.execution.CustomModifierExecutor
+ XXX.commands.execution.CustomModifierExecutor$ModifierAdapter
- XXX.commands.execution.EntryAction
+ XXX.commands.execution.ExecutionContext
- XXX.commands.execution.ExecutionControl
+ XXX.commands.execution.ExecutionControl$1
- XXX.commands.execution.Frame
+ XXX.commands.execution.Frame$FrameControl
- XXX.commands.execution.package-info
- XXX.commands.execution.TraceCallbacks
+ XXX.commands.execution.UnboundEntryAction
- XXX.commands.functions.CommandFunction
+ XXX.commands.functions.FunctionBuilder
- XXX.commands.functions.InstantiatedFunction
+ XXX.commands.functions.MacroFunction
- XXX.commands.functions.MacroFunction$Entry
+ XXX.commands.functions.MacroFunction$MacroEntry
- XXX.commands.functions.MacroFunction$PlainTextEntry
+ XXX.commands.functions.package-info
+ XXX.commands.functions.PlainTextFunction
- XXX.commands.functions.StringTemplate
+ XXX.commands.synchronization.ArgumentTypeInfo
- XXX.commands.synchronization.ArgumentTypeInfo$Template
+ XXX.commands.synchronization.ArgumentTypeInfos
- XXX.commands.synchronization.ArgumentUtils
+ XXX.commands.synchronization.package-info
+ XXX.commands.synchronization.SingletonArgumentInfo
- XXX.commands.synchronization.SingletonArgumentInfo$Template
+ XXX.commands.synchronization.SuggestionProviders
- XXX.commands.synchronization.SuggestionProviders$Wrapper
+ XXX.core.cauldron.CauldronInteraction
- XXX.core.cauldron.CauldronInteraction$InteractionMap
+ XXX.core.cauldron.package-info
- XXX.core.component.DataComponentHolder
- XXX.core.component.DataComponentMap$1
- XXX.core.component.DataComponentMap$Builder
- XXX.core.component.DataComponentPatch
- XXX.core.component.DataComponentPatch$Builder
- XXX.core.component.DataComponentPredicate
- XXX.core.component.DataComponentType
- XXX.core.component.DataComponentType$Builder$SimpleType
- XXX.core.component.PatchedDataComponentMap
- XXX.core.component.TypedDataComponent$1
- XXX.core.dispenser.AbstractProjectileDispenseBehavior
+ XXX.core.dispenser.BlockSource
- XXX.core.dispenser.BoatDispenseItemBehavior
+ XXX.core.dispenser.DefaultDispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior$1
- XXX.core.dispenser.DispenseItemBehavior$10
+ XXX.core.dispenser.DispenseItemBehavior$11
- XXX.core.dispenser.DispenseItemBehavior$12
+ XXX.core.dispenser.DispenseItemBehavior$13
- XXX.core.dispenser.DispenseItemBehavior$14
+ XXX.core.dispenser.DispenseItemBehavior$15
- XXX.core.dispenser.DispenseItemBehavior$16
+ XXX.core.dispenser.DispenseItemBehavior$17
- XXX.core.dispenser.DispenseItemBehavior$18
+ XXX.core.dispenser.DispenseItemBehavior$19
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$20
- XXX.core.dispenser.DispenseItemBehavior$21
+ XXX.core.dispenser.DispenseItemBehavior$22
- XXX.core.dispenser.DispenseItemBehavior$23
+ XXX.core.dispenser.DispenseItemBehavior$24
- XXX.core.dispenser.DispenseItemBehavior$25
+ XXX.core.dispenser.DispenseItemBehavior$26
- XXX.core.dispenser.DispenseItemBehavior$27
+ XXX.core.dispenser.DispenseItemBehavior$28
- XXX.core.dispenser.DispenseItemBehavior$29
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$7$1
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$8$1
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.DustColorTransitionOptions
- XXX.core.particles.DustColorTransitionOptions$1
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.DustParticleOptions$1
+ XXX.core.particles.DustParticleOptionsBase
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
- XXX.core.particles.ParticleGroup
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SculkChargeParticleOptions
+ XXX.core.particles.SculkChargeParticleOptions$1
- XXX.core.particles.ShriekParticleOption
+ XXX.core.particles.ShriekParticleOption$1
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
- XXX.core.particles.VibrationParticleOption
+ XXX.core.particles.VibrationParticleOption$1
+ XXX.core.registries.BuiltInRegistries
- XXX.core.registries.BuiltInRegistries$RegistryBootstrap
- XXX.core.registries.package-info
+ XXX.core.registries.Registries
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdvancementSubProvider
+ XXX.data.advancements.package-info
+ XXX.data.info.BiomeParametersDumpReport
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
- XXX.data.info.ItemListReport
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.EmptyItemInHotbarFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityGoatMissingStateFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingFieldsRenameFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntityShulkerColorFix
- XXX.datafix.fixes.EntityShulkerRotationFix
+ XXX.datafix.fixes.EntitySkeletonSplitFix
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityUUIDFix
- XXX.datafix.fixes.EntityVariantFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.FeatureFlagRemoveFix
- XXX.datafix.fixes.FilteredBooksFix
+ XXX.datafix.fixes.FilteredSignsFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.HorseBodyArmorItemFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LegacyDragonFightFix
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.MapBannerBlockPosFormatFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobEffectIdFix
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamedEntityWriteReadFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveDisplayNameFix
- XXX.datafix.fixes.ObjectiveRenderTypeFix
+ XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.PrimedTntBlockStateFixer
+ XXX.datafix.fixes.RandomSequenceSettingsFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RemapChunkStatusFix
+ XXX.datafix.fixes.RemoveGolemGossipFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.RenameEnchantmentsFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.ScoreboardDisplaySlotFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.SpawnerDataFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StatsCounterFix$StatType
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ XXX.datafix.fixes.StructureSettingsFlattenFix
- XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V3818_3
- XXX.datafix.schemas.V501
+ XXX.datafix.schemas.V700
- XXX.datafix.schemas.V701
+ XXX.datafix.schemas.V702
- XXX.datafix.schemas.V703
+ XXX.datafix.schemas.V704
- XXX.datafix.schemas.V704$1
+ XXX.datafix.schemas.V705
- XXX.datafix.schemas.V705$1
+ XXX.datafix.schemas.V808
- XXX.datafix.schemas.V99
+ XXX.datafix.schemas.V99$1
+ XXX.enderdragon.phases.AbstractDragonPhaseInstance
- XXX.enderdragon.phases.AbstractDragonSittingPhase
+ XXX.enderdragon.phases.DragonChargePlayerPhase
- XXX.enderdragon.phases.DragonDeathPhase
+ XXX.enderdragon.phases.DragonHoldingPatternPhase
- XXX.enderdragon.phases.DragonHoverPhase
+ XXX.enderdragon.phases.DragonLandingApproachPhase
- XXX.enderdragon.phases.DragonLandingPhase
+ XXX.enderdragon.phases.DragonPhaseInstance
- XXX.enderdragon.phases.DragonSittingAttackingPhase
+ XXX.enderdragon.phases.DragonSittingFlamingPhase
- XXX.enderdragon.phases.DragonSittingScanningPhase
+ XXX.enderdragon.phases.DragonStrafePlayerPhase
- XXX.enderdragon.phases.DragonTakeoffPhase
+ XXX.enderdragon.phases.EnderDragonPhase
- XXX.enderdragon.phases.EnderDragonPhaseManager
+ XXX.enderdragon.phases.package-info
+ XXX.entity.animal.MushroomCow
- XXX.entity.animal.MushroomCow$MushroomType
+ XXX.entity.animal.Ocelot
- XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ XXX.entity.animal.Ocelot$OcelotTemptGoal
- XXX.entity.animal.package-info
- XXX.entity.animal.Panda
+ XXX.entity.animal.Panda$Gene
- XXX.entity.animal.Panda$PandaAttackGoal
+ XXX.entity.animal.Panda$PandaAvoidGoal
- XXX.entity.animal.Panda$PandaBreedGoal
+ XXX.entity.animal.Panda$PandaHurtByTargetGoal
- XXX.entity.animal.Panda$PandaLieOnBackGoal
+ XXX.entity.animal.Panda$PandaLookAtPlayerGoal
- XXX.entity.animal.Panda$PandaMoveControl
+ XXX.entity.animal.Panda$PandaPanicGoal
- XXX.entity.animal.Panda$PandaRollGoal
+ XXX.entity.animal.Panda$PandaSitGoal
- XXX.entity.animal.Panda$PandaSneezeGoal
+ XXX.entity.animal.Parrot
- XXX.entity.animal.Parrot$1
+ XXX.entity.animal.Parrot$ParrotWanderGoal
- XXX.entity.animal.Parrot$Variant
+ XXX.entity.animal.Pig
- XXX.entity.animal.PolarBear
+ XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- XXX.entity.animal.PolarBear$PolarBearPanicGoal
+ XXX.entity.animal.Pufferfish
- XXX.entity.animal.Pufferfish$PufferfishPuffGoal
+ XXX.entity.animal.Rabbit
- XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ XXX.entity.animal.Rabbit$RabbitGroupData
- XXX.entity.animal.Rabbit$RabbitJumpControl
+ XXX.entity.animal.Rabbit$RabbitMoveControl
- XXX.entity.animal.Rabbit$RabbitPanicGoal
+ XXX.entity.animal.Rabbit$RaidGardenGoal
- XXX.entity.animal.Rabbit$Variant
+ XXX.entity.animal.Salmon
- XXX.entity.animal.Sheep
+ XXX.entity.animal.Sheep$1
- XXX.entity.animal.Sheep$2
+ XXX.entity.animal.ShoulderRidingEntity
- XXX.entity.animal.SnowGolem
+ XXX.entity.animal.Squid
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TropicalFish
+ XXX.entity.animal.TropicalFish$Base
- XXX.entity.animal.TropicalFish$Pattern
+ XXX.entity.animal.TropicalFish$TropicalFishGroupData
- XXX.entity.animal.TropicalFish$Variant
+ XXX.entity.animal.Turtle
- XXX.entity.animal.Turtle$TurtleBreedGoal
+ XXX.entity.animal.Turtle$TurtleGoHomeGoal
- XXX.entity.animal.Turtle$TurtleGoToWaterGoal
+ XXX.entity.animal.Turtle$TurtleLayEggGoal
- XXX.entity.animal.Turtle$TurtleMoveControl
+ XXX.entity.animal.Turtle$TurtlePanicGoal
- XXX.entity.animal.Turtle$TurtlePathNavigation
+ XXX.entity.animal.Turtle$TurtleRandomStrollGoal
- XXX.entity.animal.Turtle$TurtleTravelGoal
+ XXX.entity.animal.WaterAnimal
- XXX.entity.animal.Wolf
+ XXX.entity.animal.Wolf$WolfAvoidEntityGoal
- XXX.entity.animal.Wolf$WolfPanicGoal
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$1
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.ItemFrame$1
+ XXX.entity.decoration.ItemFrame$2
- XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
- XXX.entity.decoration.PaintingVariant
+ XXX.entity.decoration.PaintingVariants
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
- XXX.entity.layers.BreezeEyesLayer
+ XXX.entity.layers.BreezeWindLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseArmorLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
+ XXX.entity.layers.package-info
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.layers.PlayerItemInHandLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.SaddleLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.SkeletonClothingLayer
- XXX.entity.layers.SlimeOuterLayer
+ XXX.entity.layers.SnowGolemHeadLayer
- XXX.entity.layers.SpiderEyesLayer
+ XXX.entity.layers.SpinAttackEffectLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.TropicalFishPatternLayer$1
+ XXX.entity.layers.VillagerProfessionLayer
- XXX.entity.layers.WardenEmissiveLayer
+ XXX.entity.layers.WardenEmissiveLayer$AlphaFunction
- XXX.entity.layers.WardenEmissiveLayer$DrawSelector
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfArmorLayer
- XXX.entity.layers.WolfCollarLayer
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.Bogged
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
- XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Shulker
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ XXX.entity.monster.Shulker$ShulkerLookControl
- XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
+ XXX.entity.monster.Shulker$ShulkerPeekGoal
- XXX.entity.monster.Silverfish
+ XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ XXX.entity.monster.Skeleton
- XXX.entity.monster.Slime
+ XXX.entity.monster.Slime$SlimeAttackGoal
- XXX.entity.monster.Slime$SlimeFloatGoal
+ XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
- XXX.entity.monster.Slime$SlimeMoveControl
+ XXX.entity.monster.Slime$SlimeRandomDirectionGoal
- XXX.entity.monster.SpellcasterIllager
+ XXX.entity.monster.SpellcasterIllager$IllagerSpell
- XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- XXX.entity.monster.Spider
+ XXX.entity.monster.Spider$SpiderAttackGoal
- XXX.entity.monster.Spider$SpiderEffectsGroupData
+ XXX.entity.monster.Spider$SpiderTargetGoal
- XXX.entity.monster.Stray
+ XXX.entity.monster.Strider
- XXX.entity.monster.Strider$StriderGoToLavaGoal
+ XXX.entity.monster.Strider$StriderPathNavigation
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Witch
+ XXX.entity.monster.WitherSkeleton
- XXX.entity.monster.Zoglin
+ XXX.entity.monster.Zombie
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
- XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$FailureItemListing
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerTrades$TypeSpecificTrade
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Inventory
+ XXX.entity.player.package-info
- XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.PlayerRenderer
+ XXX.entity.player.ProfileKeyPair
- XXX.entity.player.ProfilePublicKey
+ XXX.entity.player.ProfilePublicKey$Data
- XXX.entity.player.ProfilePublicKey$ValidationException
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$1
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
- XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.ProjectileDeflection
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.Boat$1
- XXX.entity.vehicle.Boat$Status
+ XXX.entity.vehicle.Boat$Type
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestBoat$1
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
- XXX.entity.vehicle.VehicleEntity
+ XXX.execution.tasks.BuildContexts
- XXX.execution.tasks.BuildContexts$Continuation
+ XXX.execution.tasks.BuildContexts$TopLevel
- XXX.execution.tasks.BuildContexts$Unbound
+ XXX.execution.tasks.CallFunction
- XXX.execution.tasks.ContinuationTask
+ XXX.execution.tasks.ContinuationTask$TaskProvider
- XXX.execution.tasks.ExecuteCommand
+ XXX.execution.tasks.FallthroughTask
- XXX.execution.tasks.IsolatedCall
+ XXX.execution.tasks.package-info
- XXX.geom.builders.CubeDefinition
+ XXX.geom.builders.CubeDeformation
- XXX.geom.builders.CubeListBuilder
+ XXX.geom.builders.LayerDefinition
- XXX.geom.builders.MaterialDefinition
+ XXX.geom.builders.MeshDefinition
- XXX.geom.builders.package-info
- XXX.geom.builders.PartDefinition
+ XXX.geom.builders.UVPair
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.PotionContents
+ XXX.item.alchemy.Potions
+ XXX.item.armortrim.ArmorTrim
- XXX.item.armortrim.package-info
- XXX.item.armortrim.TrimMaterial
+ XXX.item.armortrim.TrimMaterials
- XXX.item.armortrim.TrimPattern
+ XXX.item.armortrim.TrimPatterns
- XXX.item.component.BundleContents
- XXX.item.component.ChargedProjectiles
- XXX.item.component.CustomModelData
- XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.ItemAttributeModifiers
- XXX.item.component.ItemAttributeModifiers$Builder
- XXX.item.component.ItemContainerContents
- XXX.item.component.ItemLore
- XXX.item.component.MapDecorations
- XXX.item.component.MapItemColor
- XXX.item.component.package-info
- XXX.item.component.ResolvableProfile
- XXX.item.component.SuspiciousStewEffects
- XXX.item.component.TooltipProvider
- XXX.item.component.WritableBookContent
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.AbstractCookingRecipe$Factory
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingBookCategory
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.DecoratedPotRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$TagValue
- XXX.item.crafting.Ingredient$Value
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeCache
+ XXX.item.crafting.RecipeCache$Entry
- XXX.item.crafting.RecipeHolder
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapedRecipePattern
+ XXX.item.crafting.ShapedRecipePattern$Data
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCraftingRecipeSerializer
- XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Factory
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmithingRecipe
- XXX.item.crafting.SmithingTransformRecipe
+ XXX.item.crafting.SmithingTransformRecipe$Serializer
- XXX.item.crafting.SmithingTrimRecipe
+ XXX.item.crafting.SmithingTrimRecipe$Serializer
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.SuspiciousStewRecipe
+ XXX.item.crafting.TippedArrowRecipe
+ XXX.item.enchantment.ArrowDamageEnchantment
- XXX.item.enchantment.ArrowFireEnchantment
+ XXX.item.enchantment.ArrowInfiniteEnchantment
- XXX.item.enchantment.ArrowKnockbackEnchantment
+ XXX.item.enchantment.ArrowPiercingEnchantment
- XXX.item.enchantment.BindingCurseEnchantment
+ XXX.item.enchantment.DamageEnchantment
- XXX.item.enchantment.DigDurabilityEnchantment
+ XXX.item.enchantment.DiggingEnchantment
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$Rarity
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.FireAspectEnchantment
+ XXX.item.enchantment.FishingSpeedEnchantment
- XXX.item.enchantment.FrostWalkerEnchantment
- XXX.item.enchantment.ItemEnchantments$Mutable
+ XXX.item.enchantment.KnockbackEnchantment
- XXX.item.enchantment.LootBonusEnchantment
+ XXX.item.enchantment.MendingEnchantment
- XXX.item.enchantment.MultiShotEnchantment
+ XXX.item.enchantment.OxygenEnchantment
+ XXX.item.enchantment.package-info
- XXX.item.enchantment.ProtectionEnchantment
+ XXX.item.enchantment.ProtectionEnchantment$Type
- XXX.item.enchantment.QuickChargeEnchantment
+ XXX.item.enchantment.SoulSpeedEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.SwiftSneakEnchantment
- XXX.item.enchantment.ThornsEnchantment
+ XXX.item.enchantment.TridentChannelingEnchantment
- XXX.item.enchantment.TridentImpalerEnchantment
+ XXX.item.enchantment.TridentLoyaltyEnchantment
- XXX.item.enchantment.TridentRiptideEnchantment
+ XXX.item.enchantment.UntouchingEnchantment
- XXX.item.enchantment.VanishingCurseEnchantment
+ XXX.item.enchantment.WaterWalkerEnchantment
- XXX.item.enchantment.WaterWorkerEnchantment
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.ChunkRegionIoEvent
+ XXX.jfr.event.ChunkRegionIoEvent$Fields
- XXX.jfr.event.ChunkRegionReadEvent
+ XXX.jfr.event.ChunkRegionWriteEvent
- XXX.jfr.event.NetworkSummaryEvent
+ XXX.jfr.event.NetworkSummaryEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent$SumAggregation
- XXX.jfr.event.package-info
+ XXX.jfr.event.PacketEvent
- XXX.jfr.event.PacketEvent$Fields
+ XXX.jfr.event.PacketReceivedEvent
- XXX.jfr.event.PacketSentEvent
+ XXX.jfr.event.ServerTickTimeEvent
- XXX.jfr.event.ServerTickTimeEvent$Fields
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.ChunkIdentification
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.IoSummary
- XXX.jfr.stats.IoSummary$CountAndSize
+ XXX.jfr.stats.package-info
+ XXX.jfr.stats.PacketIdentification
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
- XXX.level.block.TintedGlassBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TorchflowerCropBlock
- XXX.level.block.TransparentBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TrialSpawnerBlock
+ XXX.level.block.TripWireBlock
- XXX.level.block.TripWireBlock$1
+ XXX.level.block.TripWireHookBlock
- XXX.level.block.TripWireHookBlock$1
+ XXX.level.block.TurtleEggBlock
- XXX.level.block.TwistingVinesBlock
+ XXX.level.block.TwistingVinesPlantBlock
- XXX.level.block.VaultBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallHangingSignBlock
+ XXX.level.block.WallHangingSignBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WaterloggedTransparentBlock
+ XXX.level.block.WeatheringCopper
- XXX.level.block.WeatheringCopper$WeatherState
+ XXX.level.block.WeatheringCopperBulbBlock
- XXX.level.block.WeatheringCopperDoorBlock
+ XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringCopperGrateBlock
+ XXX.level.block.WeatheringCopperSlabBlock
- XXX.level.block.WeatheringCopperStairBlock
+ XXX.level.block.WeatheringCopperTrapDoorBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVinesBlock
- XXX.level.block.WeepingVinesPlantBlock
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoolCarpetBlock
+ XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$1
- XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunk$PostLoadProcessor
+ XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LevelChunkSection$1BlockCounter
- XXX.level.chunk.LightChunk
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.MissingPaletteEntryException
- XXX.level.chunk.package-info
- XXX.level.chunk.Palette
+ XXX.level.chunk.Palette$Factory
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$Configuration
+ XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PalettedContainer$Data
+ XXX.level.chunk.PalettedContainer$Strategy
- XXX.level.chunk.PalettedContainer$Strategy$1
+ XXX.level.chunk.PalettedContainer$Strategy$2
- XXX.level.chunk.PalettedContainerRO
+ XXX.level.chunk.PalettedContainerRO$PackedData
- XXX.level.chunk.PalettedContainerRO$Unpacker
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.SingleValuePalette
+ XXX.level.chunk.StructureAccess
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.pathfinder.PathfindingContext
+ XXX.level.storage.package-info
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$Event
- XXX.level.validation.ContentValidationException
+ XXX.level.validation.DirectoryValidator
- XXX.level.validation.DirectoryValidator$1
+ XXX.level.validation.ForbiddenSymlinkInfo
+ XXX.level.validation.package-info
- XXX.level.validation.PathAllowList
+ XXX.level.validation.PathAllowList$ConfigEntry
- XXX.level.validation.PathAllowList$EntryType
- XXX.loot.functions.CopyComponentsFunction
- XXX.loot.functions.CopyComponentsFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction
- XXX.loot.functions.CopyCustomDataFunction$CopyOperation
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.package-info
- XXX.loot.functions.SetComponentsFunction
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetCustomDataFunction
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.packs.UpdateOneTwentyOneShearingLoot
+ XXX.loot.packs.VanillaArchaeologyLoot
- XXX.loot.packs.VanillaBlockLoot
+ XXX.loot.packs.VanillaChestLoot
- XXX.loot.packs.VanillaEntityLoot
+ XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaGiftLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AllOfCondition
+ XXX.loot.predicates.AllOfCondition$Builder
- XXX.loot.predicates.AnyOfCondition
+ XXX.loot.predicates.AnyOfCondition$Builder
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.CompositeLootItemCondition
- XXX.loot.predicates.CompositeLootItemCondition$Builder
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.metadata.animation.AnimationFrame
- XXX.metadata.animation.AnimationMetadataSection
+ XXX.metadata.animation.AnimationMetadataSection$1
- XXX.metadata.animation.AnimationMetadataSection$FrameOutput
+ XXX.metadata.animation.AnimationMetadataSectionSerializer
- XXX.metadata.animation.FrameSize
- XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetaDataSection
- XXX.metadata.animation.VillagerMetaDataSection$Hat
+ XXX.metadata.animation.VillagerMetadataSectionSerializer
+ XXX.metadata.gui.GuiMetadataSection
- XXX.metadata.gui.GuiSpriteScaling
+ XXX.metadata.gui.GuiSpriteScaling$NineSlice
- XXX.metadata.gui.GuiSpriteScaling$NineSlice$Border
+ XXX.metadata.gui.GuiSpriteScaling$Stretch
- XXX.metadata.gui.GuiSpriteScaling$Tile
+ XXX.metadata.gui.GuiSpriteScaling$Type
- XXX.metadata.gui.package-info
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.package-info
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
- XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
+ XXX.metadata.texture.TextureMetadataSectionSerializer
+ XXX.metrics.profiling.ActiveMetricsRecorder
- XXX.metrics.profiling.InactiveMetricsRecorder
+ XXX.metrics.profiling.MetricsRecorder
- XXX.metrics.profiling.package-info
- XXX.metrics.profiling.ProfilerSamplerAdapter
+ XXX.metrics.profiling.ServerMetricsSamplersProvider
- XXX.metrics.profiling.ServerMetricsSamplersProvider$1
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ XXX.metrics.storage.MetricsPersister
+ XXX.metrics.storage.package-info
- XXX.metrics.storage.RecordedDeviation
+ XXX.minecraft.client.package-info
+ XXX.minecraft.commands.BrigadierExceptions
- XXX.minecraft.commands.CacheableFunction
+ XXX.minecraft.commands.CommandBuildContext
- XXX.minecraft.commands.CommandBuildContext$1
+ XXX.minecraft.commands.CommandResultCallback
- XXX.minecraft.commands.CommandResultCallback$1
+ XXX.minecraft.commands.Commands
- XXX.minecraft.commands.Commands$1
+ XXX.minecraft.commands.Commands$1$1
- XXX.minecraft.commands.Commands$CommandSelection
+ XXX.minecraft.commands.Commands$ParseFunction
+ XXX.minecraft.commands.CommandSigningContext
- XXX.minecraft.commands.CommandSigningContext$1
+ XXX.minecraft.commands.CommandSigningContext$SignedArguments
- XXX.minecraft.commands.CommandSource
+ XXX.minecraft.commands.CommandSource$1
- XXX.minecraft.commands.CommandSourceStack
- XXX.minecraft.commands.ExecutionCommandSource
+ XXX.minecraft.commands.FunctionInstantiationException
- XXX.minecraft.commands.package-info
- XXX.minecraft.commands.ParserUtils
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.core.AxisCycle
+ XXX.minecraft.core.AxisCycle$1
- XXX.minecraft.core.AxisCycle$2
+ XXX.minecraft.core.AxisCycle$3
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$4
- XXX.minecraft.core.BlockPos$5
+ XXX.minecraft.core.BlockPos$6
- XXX.minecraft.core.BlockPos$MutableBlockPos
+ XXX.minecraft.core.Cloner
- XXX.minecraft.core.Cloner$Factory
+ XXX.minecraft.core.Cursor3D
- XXX.minecraft.core.DefaultedMappedRegistry
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
+ XXX.minecraft.core.Holder
- XXX.minecraft.core.Holder$Direct
+ XXX.minecraft.core.Holder$Kind
- XXX.minecraft.core.Holder$Reference
+ XXX.minecraft.core.Holder$Reference$Type
- XXX.minecraft.core.HolderGetter
+ XXX.minecraft.core.HolderGetter$Provider
- XXX.minecraft.core.HolderLookup
+ XXX.minecraft.core.HolderLookup$Provider
- XXX.minecraft.core.HolderLookup$Provider$1
+ XXX.minecraft.core.HolderLookup$Provider$2
- XXX.minecraft.core.HolderLookup$RegistryLookup
+ XXX.minecraft.core.HolderLookup$RegistryLookup$1
- XXX.minecraft.core.HolderLookup$RegistryLookup$Delegate
+ XXX.minecraft.core.HolderOwner
- XXX.minecraft.core.HolderSet
+ XXX.minecraft.core.HolderSet$1
- XXX.minecraft.core.HolderSet$Direct
+ XXX.minecraft.core.HolderSet$ListBacked
- XXX.minecraft.core.HolderSet$Named
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.LayeredRegistryAccess
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.MappedRegistry$1
- XXX.minecraft.core.MappedRegistry$2
+ XXX.minecraft.core.NonNullList
- XXX.minecraft.core.package-info
- XXX.minecraft.core.Position
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.RegistrationInfo
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.Registry$1
+ XXX.minecraft.core.Registry$2
- XXX.minecraft.core.RegistryAccess
+ XXX.minecraft.core.RegistryAccess$1
- XXX.minecraft.core.RegistryAccess$1FrozenAccess
+ XXX.minecraft.core.RegistryAccess$Frozen
- XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ XXX.minecraft.core.RegistryAccess$RegistryEntry
- XXX.minecraft.core.RegistryCodecs
+ XXX.minecraft.core.RegistrySetBuilder
- XXX.minecraft.core.RegistrySetBuilder$1
+ XXX.minecraft.core.RegistrySetBuilder$1Entry
- XXX.minecraft.core.RegistrySetBuilder$2
+ XXX.minecraft.core.RegistrySetBuilder$3
- XXX.minecraft.core.RegistrySetBuilder$3$1
+ XXX.minecraft.core.RegistrySetBuilder$BuildState
- XXX.minecraft.core.RegistrySetBuilder$BuildState$1
+ XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookup
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookupWrapper
+ XXX.minecraft.core.RegistrySetBuilder$EmptyTagRegistryLookup
- XXX.minecraft.core.RegistrySetBuilder$LazyHolder
+ XXX.minecraft.core.RegistrySetBuilder$PatchedRegistries
- XXX.minecraft.core.RegistrySetBuilder$RegisteredValue
+ XXX.minecraft.core.RegistrySetBuilder$RegistryBootstrap
- XXX.minecraft.core.RegistrySetBuilder$RegistryContents
+ XXX.minecraft.core.RegistrySetBuilder$RegistryStub
- XXX.minecraft.core.RegistrySetBuilder$UniversalLookup
+ XXX.minecraft.core.RegistrySetBuilder$UniversalOwner
- XXX.minecraft.core.RegistrySetBuilder$ValueAndHolder
+ XXX.minecraft.core.RegistrySynchronization
- XXX.minecraft.core.RegistrySynchronization$PackedRegistryEntry
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.Rotations$1
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.UUIDUtil
- XXX.minecraft.core.UUIDUtil$1
+ XXX.minecraft.core.Vec3i
- XXX.minecraft.core.WritableRegistry
+ XXX.minecraft.data.BlockFamilies
- XXX.minecraft.data.BlockFamily
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.CachedOutput
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataGenerator$PackGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.DataProvider$Factory
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.HashCache$1
- XXX.minecraft.data.HashCache$CacheUpdater
+ XXX.minecraft.data.HashCache$ProviderCache
- XXX.minecraft.data.HashCache$ProviderCacheBuilder
+ XXX.minecraft.data.HashCache$UpdateFunction
- XXX.minecraft.data.HashCache$UpdateResult
+ XXX.minecraft.data.Main
- XXX.minecraft.data.PackOutput
+ XXX.minecraft.data.PackOutput$PathProvider
- XXX.minecraft.data.PackOutput$Target
+ XXX.minecraft.server.package-info
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BannerPatternTags
+ XXX.minecraft.tags.BiomeTags
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.CatVariantTags
- XXX.minecraft.tags.DamageTypeTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FlatLevelGeneratorPresetTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.InstrumentTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.PaintingVariantTags
- XXX.minecraft.tags.PoiTypeTags
+ XXX.minecraft.tags.StructureTags
- XXX.minecraft.tags.TagBuilder
+ XXX.minecraft.tags.TagEntry
- XXX.minecraft.tags.TagEntry$Lookup
+ XXX.minecraft.tags.TagFile
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagLoader$1
+ XXX.minecraft.tags.TagLoader$EntryWithSource
- XXX.minecraft.tags.TagLoader$SortingEntry
+ XXX.minecraft.tags.TagManager
- XXX.minecraft.tags.TagManager$LoadResult
+ XXX.minecraft.tags.TagNetworkSerialization
- XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.tags.TagNetworkSerialization$TagOutput
- XXX.minecraft.tags.WorldPresetTags
- XXX.minecraft.util.AbortableIterationConsumer
+ XXX.minecraft.util.AbortableIterationConsumer$Continuation
- XXX.minecraft.util.ArrayListDeque
+ XXX.minecraft.util.ArrayListDeque$DescendingIterator
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.Brightness
- XXX.minecraft.util.ByIdMap
+ XXX.minecraft.util.ByIdMap$1
- XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
+ XXX.minecraft.util.ClassInstanceMultiMap
- XXX.minecraft.util.ClassTreeIdRegistry
+ XXX.minecraft.util.ColorRGBA
- XXX.minecraft.util.CommonColors
+ XXX.minecraft.util.CommonLinks
- XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ XXX.minecraft.util.Crypt
- XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
+ XXX.minecraft.util.Crypt$SaltSignaturePair
- XXX.minecraft.util.Crypt$SaltSupplier
+ XXX.minecraft.util.CryptException
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.CubicSpline
+ XXX.minecraft.util.CubicSpline$1Point
- XXX.minecraft.util.CubicSpline$Builder
+ XXX.minecraft.util.CubicSpline$Constant
- XXX.minecraft.util.CubicSpline$CoordinateVisitor
+ XXX.minecraft.util.CubicSpline$Multipoint
- XXX.minecraft.util.DebugBuffer
+ XXX.minecraft.util.DelegateDataOutput
- XXX.minecraft.util.DependencySorter
+ XXX.minecraft.util.DependencySorter$Entry
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$5
- XXX.minecraft.util.ExtraCodecs$6
- XXX.minecraft.util.ExtraCodecs$8
+ XXX.minecraft.util.ExtraCodecs$EitherCodec
- XXX.minecraft.util.ExtraCodecs$RecursiveCodec
+ XXX.minecraft.util.ExtraCodecs$RecursiveMapCodec
- XXX.minecraft.util.ExtraCodecs$StrictOptionalFieldCodec
+ XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
- XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
+ XXX.minecraft.util.ExtraCodecs$XorCodec
- XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FastColor
- XXX.minecraft.util.FastColor$ABGR32
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FileZipper
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FutureChain
- XXX.minecraft.util.Graph
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.HttpUtil$DownloadProgressListener
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.JavaOps
- XXX.minecraft.util.JavaOps$1
+ XXX.minecraft.util.JavaOps$FixedMapBuilder
- XXX.minecraft.util.KeyDispatchDataCodec
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.MemoryReserve
- XXX.minecraft.util.ModCheck
+ XXX.minecraft.util.ModCheck$Confidence
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.NativeModuleLister
- XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
+ XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.package-info
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$Collector
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.ResourceLocationPattern
- XXX.minecraft.util.SegmentedAnglePrecision
+ XXX.minecraft.util.SequencedPriorityIterator
- XXX.minecraft.util.SignatureUpdater
+ XXX.minecraft.util.SignatureUpdater$Output
- XXX.minecraft.util.SignatureValidator
+ XXX.minecraft.util.Signer
- XXX.minecraft.util.SimpleBitStorage
+ XXX.minecraft.util.SimpleBitStorage$InitializationException
- XXX.minecraft.util.SingleKeyCache
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.SpawnUtil
+ XXX.minecraft.util.SpawnUtil$Strategy
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TaskChainer
+ XXX.minecraft.util.TaskChainer$1
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TimeSource
- XXX.minecraft.util.TimeSource$NanoTimeSource
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.ToFloatFunction
+ XXX.minecraft.util.ToFloatFunction$1
- XXX.minecraft.util.ToFloatFunction$2
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.ContainerHelper
- XXX.minecraft.world.ContainerListener
+ XXX.minecraft.world.Containers
- XXX.minecraft.world.Difficulty
+ XXX.minecraft.world.DifficultyInstance
- XXX.minecraft.world.InteractionHand
+ XXX.minecraft.world.InteractionResult
- XXX.minecraft.world.InteractionResultHolder
+ XXX.minecraft.world.ItemInteractionResult
- XXX.minecraft.world.ItemInteractionResult$1
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
- XXX.minecraft.world.package-info
+ XXX.minecraft.world.RandomizableContainer
- XXX.minecraft.world.RandomSequence
+ XXX.minecraft.world.RandomSequences
- XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
- XXX.minecraft.world.SimpleContainer
+ XXX.minecraft.world.SimpleMenuProvider
- XXX.minecraft.world.TickRateManager
+ XXX.minecraft.world.WorldlyContainer
- XXX.minecraft.world.WorldlyContainerHolder
+ XXX.model.dragon.DragonHeadModel
- XXX.model.dragon.package-info
+ XXX.model.geom.EntityModelSet
- XXX.model.geom.LayerDefinitions
+ XXX.model.geom.ModelLayerLocation
- XXX.model.geom.ModelLayers
+ XXX.model.geom.ModelPart
- XXX.model.geom.ModelPart$Cube
+ XXX.model.geom.ModelPart$Polygon
- XXX.model.geom.ModelPart$Vertex
+ XXX.model.geom.ModelPart$Visitor
+ XXX.model.geom.package-info
- XXX.model.geom.PartNames
+ XXX.model.geom.PartPose
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
- XXX.monster.breeze.Breeze
+ XXX.monster.breeze.Breeze$1
- XXX.monster.breeze.BreezeAi
+ XXX.monster.breeze.BreezeAi$SlideToTargetSink
- XXX.monster.breeze.BreezeUtil
+ XXX.monster.breeze.LongJump
+ XXX.monster.breeze.package-info
- XXX.monster.breeze.Shoot
+ XXX.monster.breeze.ShootWhenStuck
- XXX.monster.breeze.Slide
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.AbstractPiglin
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.PiglinArmPose
+ XXX.monster.piglin.PiglinBrute
- XXX.monster.piglin.PiglinBruteAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- XXX.monster.warden.AngerLevel
+ XXX.monster.warden.AngerManagement
- XXX.monster.warden.AngerManagement$1
+ XXX.monster.warden.AngerManagement$Sorter
+ XXX.monster.warden.package-info
- XXX.monster.warden.Warden
+ XXX.monster.warden.Warden$1
- XXX.monster.warden.Warden$1$1
+ XXX.monster.warden.Warden$2
- XXX.monster.warden.Warden$VibrationUser
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenSpawnTracker
- XXX.multiplayer.chat.ChatListener
+ XXX.multiplayer.chat.ChatListener$Message
- XXX.multiplayer.chat.ChatLog
+ XXX.multiplayer.chat.ChatTrustLevel
- XXX.multiplayer.chat.ChatTrustLevel$1
+ XXX.multiplayer.chat.LoggedChatEvent
- XXX.multiplayer.chat.LoggedChatEvent$Type
+ XXX.multiplayer.chat.LoggedChatMessage
- XXX.multiplayer.chat.LoggedChatMessage$Player
+ XXX.multiplayer.chat.LoggedChatMessage$System
- XXX.multiplayer.chat.package-info
- XXX.multiplayer.prediction.BlockStatePredictionHandler
+ XXX.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
+ XXX.multiplayer.prediction.package-info
- XXX.multiplayer.prediction.PredictiveAction
- XXX.multiplayer.resolver.AddressCheck
+ XXX.multiplayer.resolver.AddressCheck$1
- XXX.multiplayer.resolver.package-info
- XXX.multiplayer.resolver.ResolvedServerAddress
+ XXX.multiplayer.resolver.ResolvedServerAddress$1
- XXX.multiplayer.resolver.ServerAddress
+ XXX.multiplayer.resolver.ServerAddressResolver
- XXX.multiplayer.resolver.ServerNameResolver
+ XXX.multiplayer.resolver.ServerRedirectHandler
- XXX.network.chat.ComponentSerialization$FuzzyCodec
+ XXX.network.chat.ComponentSerialization$StrictEither
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.FilterMask
- XXX.network.chat.FilterMask$1
+ XXX.network.chat.FilterMask$Type
- XXX.network.chat.FormattedText
+ XXX.network.chat.FormattedText$1
- XXX.network.chat.FormattedText$2
+ XXX.network.chat.FormattedText$3
- XXX.network.chat.FormattedText$4
+ XXX.network.chat.FormattedText$ContentConsumer
- XXX.network.chat.FormattedText$StyledContentConsumer
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$LegacyConverter
+ XXX.network.chat.HoverEvent$TypedHoverEvent
- XXX.network.chat.LastSeenMessages
+ XXX.network.chat.LastSeenMessages$Packed
- XXX.network.chat.LastSeenMessages$Update
+ XXX.network.chat.LastSeenMessagesTracker
- XXX.network.chat.LastSeenMessagesTracker$Update
+ XXX.network.chat.LastSeenMessagesValidator
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
- XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$DecodeException
- XXX.network.chat.SignedMessageChain$Decoder
+ XXX.network.chat.SignedMessageChain$Encoder
- XXX.network.chat.SignedMessageLink
+ XXX.network.chat.SignedMessageValidator
- XXX.network.chat.SignedMessageValidator$KeyBased
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$1Collector
- XXX.network.chat.Style$Serializer
+ XXX.network.chat.SubStringSource
- XXX.network.chat.TextColor
+ XXX.network.chat.ThrowingComponent
+ XXX.network.codec.ByteBufCodecs
- XXX.network.codec.ByteBufCodecs$1
+ XXX.network.codec.ByteBufCodecs$10
- XXX.network.codec.ByteBufCodecs$11
+ XXX.network.codec.ByteBufCodecs$12
- XXX.network.codec.ByteBufCodecs$13
+ XXX.network.codec.ByteBufCodecs$14
- XXX.network.codec.ByteBufCodecs$15
+ XXX.network.codec.ByteBufCodecs$16
- XXX.network.codec.ByteBufCodecs$17
+ XXX.network.codec.ByteBufCodecs$18
- XXX.network.codec.ByteBufCodecs$19
+ XXX.network.codec.ByteBufCodecs$2
- XXX.network.codec.ByteBufCodecs$20
+ XXX.network.codec.ByteBufCodecs$21
- XXX.network.codec.ByteBufCodecs$22
- XXX.network.codec.ByteBufCodecs$24
- XXX.network.codec.ByteBufCodecs$26
- XXX.network.codec.StreamCodec$12
- XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.config.SynchronizeRegistriesTask
- XXX.packs.linkfs.DummyFileAttributes
+ XXX.packs.linkfs.LinkFileSystem
- XXX.packs.linkfs.LinkFileSystem$Builder
+ XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
+ XXX.packs.linkfs.LinkFSFileStore
- XXX.packs.linkfs.LinkFSPath
+ XXX.packs.linkfs.LinkFSPath$1
- XXX.packs.linkfs.LinkFSPath$2
+ XXX.packs.linkfs.LinkFSPath$3
- XXX.packs.linkfs.LinkFSProvider
+ XXX.packs.linkfs.LinkFSProvider$1
- XXX.packs.linkfs.LinkFSProvider$2
+ XXX.packs.linkfs.package-info
- XXX.packs.linkfs.PathContents
+ XXX.packs.linkfs.PathContents$1
- XXX.packs.linkfs.PathContents$2
+ XXX.packs.linkfs.PathContents$DirectoryContents
- XXX.packs.linkfs.PathContents$FileContents
- XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.MetadataSectionType
- XXX.packs.metadata.MetadataSectionType$1
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.BuiltInPackSource
- XXX.packs.repository.BuiltInPackSource$1
+ XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.FolderRepositorySource$FolderPackDetector
+ XXX.packs.repository.KnownPack
- XXX.packs.repository.Pack
+ XXX.packs.repository.Pack$Metadata
- XXX.packs.repository.Pack$Position
+ XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackDetector
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.PackSource$1
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
- XXX.packs.resources.CloseableResourceManager
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$ResourceWithSource
+ XXX.packs.resources.IoSupplier
- XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManager$Empty
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.ResourceMetadata
+ XXX.packs.resources.ResourceMetadata$1
- XXX.packs.resources.ResourceMetadata$2
+ XXX.packs.resources.ResourceMetadata$Builder
- XXX.packs.resources.ResourceMetadata$Builder$1
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
+ XXX.phys.shapes.ArrayVoxelShape
- XXX.phys.shapes.ArrayVoxelShape$1
+ XXX.phys.shapes.BitSetDiscreteVoxelShape
- XXX.phys.shapes.BooleanOp
+ XXX.phys.shapes.CollisionContext
- XXX.phys.shapes.CubePointRange
+ XXX.phys.shapes.CubeVoxelShape
- XXX.phys.shapes.DiscreteCubeMerger
+ XXX.phys.shapes.DiscreteVoxelShape
- XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- XXX.phys.shapes.EntityCollisionContext
+ XXX.phys.shapes.EntityCollisionContext$1
- XXX.phys.shapes.IdenticalMerger
+ XXX.phys.shapes.IndexMerger
- XXX.phys.shapes.IndexMerger$IndexConsumer
+ XXX.phys.shapes.IndirectMerger
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.player.inventory.Hotbar
- XXX.player.inventory.package-info
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
- XXX.profiling.metrics.MetricCategory
+ XXX.profiling.metrics.MetricSampler
- XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ XXX.profiling.metrics.MetricSampler$SamplerResult
- XXX.profiling.metrics.MetricSampler$ThresholdTest
+ XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- XXX.profiling.metrics.MetricsRegistry
+ XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- XXX.profiling.metrics.MetricsSamplerProvider
- XXX.profiling.metrics.package-info
+ XXX.profiling.metrics.ProfilerMeasured
+ XXX.projectile.windcharge.AbstractWindCharge
- XXX.projectile.windcharge.AbstractWindCharge$WindChargeDamageCalculator
+ XXX.projectile.windcharge.BreezeWindCharge
- XXX.projectile.windcharge.WindCharge
+ XXX.projectile.windcharge.WindCharge$WindChargePlayerDamageCalculator
- XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$1
- XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.ConstantValue
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
- XXX.renderer.block.BlockModelShaper
+ XXX.renderer.block.BlockRenderDispatcher
- XXX.renderer.block.BlockRenderDispatcher$1
+ XXX.renderer.block.LiquidBlockRenderer
- XXX.renderer.block.LiquidBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer
- XXX.renderer.block.ModelBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
- XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- XXX.renderer.block.ModelBlockRenderer$Cache
+ XXX.renderer.block.ModelBlockRenderer$Cache$1
- XXX.renderer.block.ModelBlockRenderer$Cache$2
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
- XXX.renderer.block.package-info
+ XXX.renderer.blockentity.BannerRenderer
- XXX.renderer.blockentity.BeaconRenderer
+ XXX.renderer.blockentity.BedRenderer
- XXX.renderer.blockentity.BellRenderer
+ XXX.renderer.blockentity.BlockEntityRenderDispatcher
- XXX.renderer.blockentity.BlockEntityRenderer
+ XXX.renderer.blockentity.BlockEntityRendererProvider
- XXX.renderer.blockentity.BlockEntityRendererProvider$Context
+ XXX.renderer.blockentity.BlockEntityRenderers
- XXX.renderer.blockentity.BrightnessCombiner
+ XXX.renderer.blockentity.BrushableBlockRenderer
- XXX.renderer.blockentity.BrushableBlockRenderer$1
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.DecoratedPotRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.HangingSignRenderer
+ XXX.renderer.blockentity.HangingSignRenderer$HangingSignModel
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.package-info
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.SignRenderer
- XXX.renderer.blockentity.SignRenderer$SignModel
+ XXX.renderer.blockentity.SkullBlockRenderer
- XXX.renderer.blockentity.SpawnerRenderer
+ XXX.renderer.blockentity.StructureBlockRenderer
- XXX.renderer.blockentity.StructureBlockRenderer$1
+ XXX.renderer.blockentity.TheEndGatewayRenderer
- XXX.renderer.blockentity.TheEndPortalRenderer
+ XXX.renderer.blockentity.TrialSpawnerRenderer
- XXX.renderer.blockentity.VaultRenderer
- XXX.renderer.chunk.package-info
- XXX.renderer.chunk.RenderChunk
+ XXX.renderer.chunk.RenderChunkRegion
- XXX.renderer.chunk.RenderRegionCache
+ XXX.renderer.chunk.RenderRegionCache$ChunkInfo
- XXX.renderer.chunk.SectionRenderDispatcher
+ XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection
- XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection$1
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask$CompileResults
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
- XXX.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
+ XXX.renderer.chunk.VisGraph
- XXX.renderer.chunk.VisGraph$1
+ XXX.renderer.chunk.VisibilitySet
+ XXX.renderer.culling.Frustum
- XXX.renderer.culling.package-info
+ XXX.renderer.debug.BeeDebugRenderer
- XXX.renderer.debug.BeeDebugRenderer$HiveDebugInfo
+ XXX.renderer.debug.BrainDebugRenderer
- XXX.renderer.debug.BrainDebugRenderer$PoiInfo
+ XXX.renderer.debug.BreezeDebugRenderer
- XXX.renderer.debug.ChunkBorderRenderer
+ XXX.renderer.debug.ChunkDebugRenderer
- XXX.renderer.debug.ChunkDebugRenderer$ChunkData
+ XXX.renderer.debug.CollisionBoxRenderer
- XXX.renderer.debug.DebugRenderer
+ XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
- XXX.renderer.debug.GameEventListenerRenderer
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
- XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
+ XXX.renderer.debug.GameTestDebugRenderer
- XXX.renderer.debug.GameTestDebugRenderer$Marker
+ XXX.renderer.debug.GoalSelectorDebugRenderer
- XXX.renderer.debug.GoalSelectorDebugRenderer$EntityGoalInfo
+ XXX.renderer.debug.HeightMapRenderer
- XXX.renderer.debug.HeightMapRenderer$1
+ XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.LightSectionDebugRenderer
+ XXX.renderer.debug.LightSectionDebugRenderer$1
- XXX.renderer.debug.LightSectionDebugRenderer$SectionData
+ XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.SolidFaceRenderer
+ XXX.renderer.debug.StructureRenderer
- XXX.renderer.debug.SupportBlockRenderer
+ XXX.renderer.debug.VillageSectionsDebugRenderer
- XXX.renderer.debug.WaterDebugRenderer
+ XXX.renderer.debug.WorldGenAttemptRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractZombieRenderer
+ XXX.renderer.entity.AllayRenderer
- XXX.renderer.entity.ArmadilloRenderer
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.AxolotlRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.BoggedRenderer
+ XXX.renderer.entity.BreezeRenderer
- XXX.renderer.entity.CamelRenderer
+ XXX.renderer.entity.CatRenderer
- XXX.renderer.entity.CaveSpiderRenderer
+ XXX.renderer.entity.ChestedHorseRenderer
- XXX.renderer.entity.ChickenRenderer
+ XXX.renderer.entity.CodRenderer
- XXX.renderer.entity.CowRenderer
+ XXX.renderer.entity.CreeperRenderer
- XXX.renderer.entity.DisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$1
- XXX.renderer.entity.DisplayRenderer$BlockDisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EnderDragonRenderer$DragonModel
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EntityRendererProvider
+ XXX.renderer.entity.EntityRendererProvider$Context
- XXX.renderer.entity.EntityRenderers
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.FrogRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GlowSquidRenderer
+ XXX.renderer.entity.GoatRenderer
- XXX.renderer.entity.GuardianRenderer
+ XXX.renderer.entity.HoglinRenderer
- XXX.renderer.entity.HorseRenderer
+ XXX.renderer.entity.HumanoidMobRenderer
- XXX.renderer.entity.HuskRenderer
+ XXX.renderer.entity.IllagerRenderer
- XXX.renderer.entity.IllusionerRenderer
+ XXX.renderer.entity.IllusionerRenderer$1
- XXX.renderer.entity.IronGolemRenderer
+ XXX.renderer.entity.ItemEntityRenderer
- XXX.renderer.entity.ItemFrameRenderer
+ XXX.renderer.entity.ItemRenderer
- XXX.renderer.entity.LeashKnotRenderer
+ XXX.renderer.entity.LightningBoltRenderer
- XXX.renderer.entity.LivingEntityRenderer
+ XXX.renderer.entity.LivingEntityRenderer$1
- XXX.renderer.entity.LlamaRenderer
+ XXX.renderer.entity.LlamaRenderer$1
- XXX.renderer.entity.LlamaSpitRenderer
+ XXX.renderer.entity.MagmaCubeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.NoopRenderer
- XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.package-info
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PandaRenderer
+ XXX.renderer.entity.ParrotRenderer
- XXX.renderer.entity.ParrotRenderer$1
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RabbitRenderer$1
+ XXX.renderer.entity.RavagerRenderer
- XXX.renderer.entity.RenderLayerParent
+ XXX.renderer.entity.SalmonRenderer
- XXX.renderer.entity.SheepRenderer
+ XXX.renderer.entity.ShulkerBulletRenderer
- XXX.renderer.entity.ShulkerRenderer
+ XXX.renderer.entity.SilverfishRenderer
- XXX.renderer.entity.SkeletonRenderer
+ XXX.renderer.entity.SlimeRenderer
- XXX.renderer.entity.SnifferRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.StriderRenderer
+ XXX.renderer.entity.TadpoleRenderer
- XXX.renderer.entity.ThrownItemRenderer
+ XXX.renderer.entity.ThrownTridentRenderer
- XXX.renderer.entity.TippableArrowRenderer
+ XXX.renderer.entity.TntMinecartRenderer
- XXX.renderer.entity.TntRenderer
+ XXX.renderer.entity.TropicalFishRenderer
- XXX.renderer.entity.TropicalFishRenderer$1
+ XXX.renderer.entity.TurtleRenderer
- XXX.renderer.entity.UndeadHorseRenderer
+ XXX.renderer.entity.VexRenderer
- XXX.renderer.entity.VillagerRenderer
+ XXX.renderer.entity.VindicatorRenderer
- XXX.renderer.entity.VindicatorRenderer$1
+ XXX.renderer.entity.WanderingTraderRenderer
- XXX.renderer.entity.WardenRenderer
+ XXX.renderer.entity.WindChargeRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.renderer.item.ClampedItemPropertyFunction
- XXX.renderer.item.CompassItemPropertyFunction
+ XXX.renderer.item.CompassItemPropertyFunction$CompassTarget
- XXX.renderer.item.CompassItemPropertyFunction$CompassWobble
+ XXX.renderer.item.ItemProperties
- XXX.renderer.item.ItemProperties$1
+ XXX.renderer.item.ItemPropertyFunction
- XXX.renderer.item.package-info
- XXX.renderer.texture.AbstractTexture
+ XXX.renderer.texture.Dumpable
- XXX.renderer.texture.DynamicTexture
+ XXX.renderer.texture.HttpTexture
- XXX.renderer.texture.MipmapGenerator
+ XXX.renderer.texture.MissingTextureAtlasSprite
- XXX.renderer.texture.OverlayTexture
+ XXX.renderer.texture.package-info
+ XXX.renderer.texture.PreloadedTexture
- XXX.renderer.texture.SimpleTexture
+ XXX.renderer.texture.SimpleTexture$TextureImage
- XXX.renderer.texture.SpriteContents
+ XXX.renderer.texture.SpriteContents$AnimatedTexture
- XXX.renderer.texture.SpriteContents$FrameInfo
+ XXX.renderer.texture.SpriteContents$InterpolationData
- XXX.renderer.texture.SpriteContents$Ticker
+ XXX.renderer.texture.SpriteLoader
- XXX.renderer.texture.SpriteLoader$Preparations
+ XXX.renderer.texture.SpriteTicker
- XXX.renderer.texture.Stitcher
+ XXX.renderer.texture.Stitcher$Entry
- XXX.renderer.texture.Stitcher$Holder
+ XXX.renderer.texture.Stitcher$Region
- XXX.renderer.texture.Stitcher$SpriteLoader
+ XXX.renderer.texture.StitcherException
- XXX.renderer.texture.TextureAtlas
+ XXX.renderer.texture.TextureAtlasSprite
- XXX.renderer.texture.TextureAtlasSprite$1
+ XXX.renderer.texture.TextureAtlasSprite$Ticker
- XXX.renderer.texture.TextureManager
+ XXX.renderer.texture.Tickable
+ XXX.resources.language.ClientLanguage
- XXX.resources.language.FormattedBidiReorder
+ XXX.resources.language.I18n
- XXX.resources.language.LanguageInfo
+ XXX.resources.language.LanguageManager
- XXX.resources.language.package-info
+ XXX.resources.metadata.package-info
+ XXX.resources.model.AtlasSet
- XXX.resources.model.AtlasSet$AtlasEntry
+ XXX.resources.model.AtlasSet$StitchResult
- XXX.resources.model.BakedModel
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BuiltInModel
+ XXX.resources.model.Material
- XXX.resources.model.ModelBaker
+ XXX.resources.model.ModelBakery
- XXX.resources.model.ModelBakery$BakedCacheKey
+ XXX.resources.model.ModelBakery$BlockStateDefinitionException
- XXX.resources.model.ModelBakery$LoadedJson
+ XXX.resources.model.ModelBakery$ModelBakerImpl
- XXX.resources.model.ModelBakery$ModelGroupKey
+ XXX.resources.model.ModelManager
- XXX.resources.model.ModelManager$ReloadState
+ XXX.resources.model.ModelResourceLocation
- XXX.resources.model.ModelState
+ XXX.resources.model.MultiPartBakedModel
- XXX.resources.model.MultiPartBakedModel$Builder
- XXX.resources.model.package-info
+ XXX.resources.model.SimpleBakedModel
- XXX.resources.model.SimpleBakedModel$Builder
+ XXX.resources.model.UnbakedModel
- XXX.resources.model.WeightedBakedModel
+ XXX.resources.model.WeightedBakedModel$Builder
- XXX.resources.server.DownloadedPackSource
+ XXX.resources.server.DownloadedPackSource$1
- XXX.resources.server.DownloadedPackSource$2
+ XXX.resources.server.DownloadedPackSource$3
- XXX.resources.server.DownloadedPackSource$4
+ XXX.resources.server.DownloadedPackSource$5
- XXX.resources.server.DownloadedPackSource$6
+ XXX.resources.server.DownloadedPackSource$7
- XXX.resources.server.DownloadedPackSource$8
- XXX.resources.server.package-info
+ XXX.resources.server.PackDownloader
- XXX.resources.server.PackLoadFeedback
+ XXX.resources.server.PackLoadFeedback$FinalResult
- XXX.resources.server.PackLoadFeedback$Update
+ XXX.resources.server.PackReloadConfig
- XXX.resources.server.PackReloadConfig$Callbacks
+ XXX.resources.server.PackReloadConfig$IdAndPath
- XXX.resources.server.ServerPackManager
+ XXX.resources.server.ServerPackManager$1
- XXX.resources.server.ServerPackManager$2
+ XXX.resources.server.ServerPackManager$ActivationStatus
- XXX.resources.server.ServerPackManager$PackDownloadStatus
+ XXX.resources.server.ServerPackManager$PackPromptStatus
- XXX.resources.server.ServerPackManager$RemovalReason
+ XXX.resources.server.ServerPackManager$ServerPackData
+ XXX.resources.sounds.AbstractSoundInstance
- XXX.resources.sounds.AbstractTickableSoundInstance
+ XXX.resources.sounds.AmbientSoundHandler
- XXX.resources.sounds.BeeAggressiveSoundInstance
+ XXX.resources.sounds.BeeFlyingSoundInstance
- XXX.resources.sounds.BeeSoundInstance
+ XXX.resources.sounds.BiomeAmbientSoundsHandler
- XXX.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
+ XXX.resources.sounds.BubbleColumnAmbientSoundHandler
- XXX.resources.sounds.ElytraOnPlayerSoundInstance
+ XXX.resources.sounds.EntityBoundSoundInstance
- XXX.resources.sounds.GuardianAttackSoundInstance
+ XXX.resources.sounds.MinecartSoundInstance
- XXX.resources.sounds.package-info
- XXX.resources.sounds.RidingMinecartSoundInstance
+ XXX.resources.sounds.SimpleSoundInstance
- XXX.resources.sounds.SnifferSoundInstance
+ XXX.resources.sounds.Sound
- XXX.resources.sounds.Sound$Type
+ XXX.resources.sounds.SoundEventRegistration
- XXX.resources.sounds.SoundEventRegistrationSerializer
+ XXX.resources.sounds.SoundInstance
- XXX.resources.sounds.SoundInstance$Attenuation
+ XXX.resources.sounds.TickableSoundInstance
- XXX.resources.sounds.UnderwaterAmbientSoundHandler
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances
- XXX.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.screens.achievement.package-info
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementTabType$Sprites
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.AdvancementWidgetType$1
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlsScreen
- XXX.screens.controls.KeyBindsList
+ XXX.screens.controls.KeyBindsList$CategoryEntry
- XXX.screens.controls.KeyBindsList$CategoryEntry$1
+ XXX.screens.controls.KeyBindsList$Entry
- XXX.screens.controls.KeyBindsList$KeyEntry
+ XXX.screens.controls.KeyBindsScreen
- XXX.screens.controls.package-info
+ XXX.screens.debug.GameModeSwitcherScreen
- XXX.screens.debug.GameModeSwitcherScreen$1
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
- XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ XXX.screens.debug.package-info
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractFurnaceScreen
- XXX.screens.inventory.AbstractSignEditScreen
+ XXX.screens.inventory.AnvilScreen
- XXX.screens.inventory.BeaconScreen
+ XXX.screens.inventory.BeaconScreen$1
- XXX.screens.inventory.BeaconScreen$BeaconButton
+ XXX.screens.inventory.BeaconScreen$BeaconCancelButton
- XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
+ XXX.screens.inventory.BeaconScreen$BeaconPowerButton
- XXX.screens.inventory.BeaconScreen$BeaconScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
+ XXX.screens.inventory.BlastFurnaceScreen
- XXX.screens.inventory.BookEditScreen
+ XXX.screens.inventory.BookEditScreen$DisplayCache
- XXX.screens.inventory.BookEditScreen$LineInfo
+ XXX.screens.inventory.BookEditScreen$Pos2i
- XXX.screens.inventory.BookViewScreen
+ XXX.screens.inventory.BookViewScreen$1
+ XXX.screens.inventory.BookViewScreen$WritableBookAccess
- XXX.selector.options.EntitySelectorOptions
+ XXX.selector.options.EntitySelectorOptions$Modifier
- XXX.selector.options.EntitySelectorOptions$Option
+ XXX.selector.options.package-info
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure
+ XXX.server.level.ChunkHolder$ChunkSaveDebug
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkLevel
+ XXX.server.level.ChunkLevel$1
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$1
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkResult$Fail
- XXX.server.network.Filterable
+ XXX.server.network.FilteredText
- XXX.server.network.LegacyProtocolUtils
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
+ XXX.server.network.PlayerChunkSender
- XXX.server.network.ServerCommonPacketListenerImpl
+ XXX.server.network.ServerConfigurationPacketListenerImpl
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerGamePacketListenerImpl$2
- XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerPlayerConnection
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.network.TextFilter
+ XXX.server.network.TextFilter$1
- XXX.server.network.TextFilterClient
+ XXX.server.network.TextFilterClient$IgnoreStrategy
- XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
+ XXX.server.network.TextFilterClient$MessageEncoder
- XXX.server.network.TextFilterClient$PlayerContext
+ XXX.server.network.TextFilterClient$RequestFailedException
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.BuiltInMetadata
- XXX.server.packs.CompositePackResources
+ XXX.server.packs.DownloadCacheCleaner
- XXX.server.packs.DownloadCacheCleaner$1
+ XXX.server.packs.DownloadCacheCleaner$PathAndPriority
- XXX.server.packs.DownloadCacheCleaner$PathAndTime
+ XXX.server.packs.DownloadQueue
- XXX.server.packs.DownloadQueue$BatchConfig
+ XXX.server.packs.DownloadQueue$BatchResult
- XXX.server.packs.DownloadQueue$DownloadRequest
+ XXX.server.packs.DownloadQueue$FileInfoEntry
- XXX.server.packs.DownloadQueue$LogEntry
+ XXX.server.packs.FeatureFlagsMetadataSection
- XXX.server.packs.FilePackResources
+ XXX.server.packs.FilePackResources$FileResourcesSupplier
- XXX.server.packs.FilePackResources$SharedZipFileAccess
+ XXX.server.packs.OverlayMetadataSection
- XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.packs.package-info
+ XXX.server.packs.PackLocationInfo
- XXX.server.packs.PackResources
+ XXX.server.packs.PackResources$ResourceOutput
- XXX.server.packs.PackSelectionConfig
+ XXX.server.packs.PackType
- XXX.server.packs.PathPackResources
+ XXX.server.packs.PathPackResources$PathResourcesSupplier
- XXX.server.packs.VanillaPackResources
+ XXX.server.packs.VanillaPackResourcesBuilder
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
+ XXX.storage.loot.package-info
+ XXX.synchronization.brigadier.DoubleArgumentInfo
- XXX.synchronization.brigadier.DoubleArgumentInfo$Template
+ XXX.synchronization.brigadier.FloatArgumentInfo
- XXX.synchronization.brigadier.FloatArgumentInfo$Template
+ XXX.synchronization.brigadier.IntegerArgumentInfo
- XXX.synchronization.brigadier.IntegerArgumentInfo$Template
+ XXX.synchronization.brigadier.LongArgumentInfo
- XXX.synchronization.brigadier.LongArgumentInfo$Template
- XXX.synchronization.brigadier.package-info
+ XXX.synchronization.brigadier.StringArgumentSerializer
- XXX.synchronization.brigadier.StringArgumentSerializer$1
+ XXX.synchronization.brigadier.StringArgumentSerializer$Template
+ XXX.telemetry.events.AggregatedTelemetryEvent
- XXX.telemetry.events.GameLoadTimesEvent
+ XXX.telemetry.events.GameLoadTimesEvent$Measurement
+ XXX.telemetry.events.package-info
- XXX.telemetry.events.PerformanceMetricsEvent
+ XXX.telemetry.events.WorldLoadEvent
- XXX.telemetry.events.WorldLoadEvent$1
+ XXX.telemetry.events.WorldLoadTimesEvent
- XXX.telemetry.events.WorldUnloadEvent
- XXX.texture.atlas.package-info
- XXX.texture.atlas.SpriteResourceLoader
+ XXX.texture.atlas.SpriteSource
- XXX.texture.atlas.SpriteSource$Output
+ XXX.texture.atlas.SpriteSource$SpriteSupplier
- XXX.texture.atlas.SpriteSourceList
+ XXX.texture.atlas.SpriteSourceList$1
+ XXX.texture.atlas.SpriteSources
- XXX.texture.atlas.SpriteSourceType
+ XXX.util.datafix.ComponentDataFixUtils
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.DataFixTypes$1
+ XXX.util.datafix.ExtraDataFixUtils
- XXX.util.datafix.FixWolfHealth
+ XXX.util.datafix.PackedBitStorage
+ XXX.util.debugchart.AbstractSampleLogger
- XXX.util.debugchart.DebugSampleSubscriptionTracker
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
+ XXX.util.debugchart.LocalSampleLogger
- XXX.util.debugchart.RemoteDebugSampleType
+ XXX.util.debugchart.RemoteSampleLogger
- XXX.util.debugchart.SampleLogger
+ XXX.util.debugchart.SampleStorage
- XXX.util.debugchart.TpsDebugDimensions
+ XXX.util.eventlog.EventLogDirectory
- XXX.util.eventlog.EventLogDirectory$CompressedFile
+ XXX.util.eventlog.EventLogDirectory$File
- XXX.util.eventlog.EventLogDirectory$FileId
+ XXX.util.eventlog.EventLogDirectory$FileList
- XXX.util.eventlog.EventLogDirectory$RawFile
+ XXX.util.eventlog.JsonEventLog
- XXX.util.eventlog.JsonEventLog$1
+ XXX.util.eventlog.JsonEventLogReader
- XXX.util.eventlog.JsonEventLogReader$1
+ XXX.util.eventlog.package-info
- XXX.util.profiling.ActiveProfiler
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
- XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.random.package-info
+ XXX.util.random.SimpleWeightedRandomList
- XXX.util.random.SimpleWeightedRandomList$Builder
+ XXX.util.random.Weight
- XXX.util.random.WeightedEntry
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedEntry$Wrapper
+ XXX.util.random.WeightedRandom
- XXX.util.random.WeightedRandomList
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
- XXX.util.thread.ProcessorHandle
+ XXX.util.thread.ProcessorHandle$1
- XXX.util.thread.ProcessorMailbox
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$IntRunnable
+ XXX.util.thread.StrictQueue$QueueStrictQueue
+ XXX.util.valueproviders.BiasedToBottomInt
- XXX.util.valueproviders.ClampedInt
+ XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ClampedNormalInt
+ XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.ConstantInt
+ XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.FloatProviderType
+ XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.MultipliedFloats
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.SampledFloat
+ XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformFloat
+ XXX.util.valueproviders.UniformInt
- XXX.util.valueproviders.WeightedListInt
- XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.util.worldupdate.WorldUpgrader$AbstractUpgrader
- XXX.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ XXX.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- XXX.util.worldupdate.WorldUpgrader$EntityUpgrader
+ XXX.util.worldupdate.WorldUpgrader$FileToUpgrade
- XXX.util.worldupdate.WorldUpgrader$PoiUpgrader
+ XXX.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
+ XXX.world.damagesource.CombatEntry
- XXX.world.damagesource.CombatRules
+ XXX.world.damagesource.CombatTracker
- XXX.world.damagesource.DamageEffects
+ XXX.world.damagesource.DamageScaling
- XXX.world.damagesource.DamageSource
+ XXX.world.damagesource.DamageSource$1
- XXX.world.damagesource.DamageSources
+ XXX.world.damagesource.DamageType
- XXX.world.damagesource.DamageTypes
+ XXX.world.damagesource.DeathMessageType
- XXX.world.damagesource.FallLocation
+ XXX.world.damagesource.package-info
- XXX.world.effect.AbsorptionMobEffect
+ XXX.world.effect.BadOmenMobEffect
- XXX.world.effect.HealOrHarmMobEffect
+ XXX.world.effect.HungerMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffect$AttributeTemplate
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
+ XXX.world.effect.MobEffectInstance$BlendState
- XXX.world.effect.MobEffectInstance$Details
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffectUtil
+ XXX.world.effect.package-info
+ XXX.world.effect.PoisonMobEffect
- XXX.world.effect.RegenerationMobEffect
+ XXX.world.effect.SaturationMobEffect
- XXX.world.effect.WitherMobEffect
- XXX.world.entity.AgeableMob
+ XXX.world.entity.AgeableMob$AgeableMobGroupData
- XXX.world.entity.AnimationState
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Attackable
- XXX.world.entity.Crackiness$Level
+ XXX.world.entity.Display
- XXX.world.entity.Display$1
+ XXX.world.entity.Display$BillboardConstraints
- XXX.world.entity.Display$BlockDisplay
+ XXX.world.entity.Display$BlockDisplay$BlockRenderState
- XXX.world.entity.Display$ColorInterpolator
+ XXX.world.entity.Display$FloatInterpolator
- XXX.world.entity.Display$GenericInterpolator
+ XXX.world.entity.Display$IntInterpolator
- XXX.world.entity.Display$ItemDisplay
+ XXX.world.entity.Display$ItemDisplay$1
- XXX.world.entity.Display$ItemDisplay$ItemRenderState
+ XXX.world.entity.Display$LinearFloatInterpolator
- XXX.world.entity.Display$LinearIntInterpolator
+ XXX.world.entity.Display$PosRotInterpolationTarget
- XXX.world.entity.Display$RenderState
+ XXX.world.entity.Display$TextDisplay
- XXX.world.entity.Display$TextDisplay$Align
+ XXX.world.entity.Display$TextDisplay$CachedInfo
- XXX.world.entity.Display$TextDisplay$CachedLine
+ XXX.world.entity.Display$TextDisplay$LineSplitter
- XXX.world.entity.Display$TextDisplay$TextRenderState
+ XXX.world.entity.Display$TransformationInterpolator
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveFunction
+ XXX.world.entity.Entity$MovementEmission
- XXX.world.entity.Entity$RemovalReason
+ XXX.world.entity.EntityAttachment
- XXX.world.entity.EntityAttachment$Fallback
+ XXX.world.entity.EntityAttachments
- XXX.world.entity.EntityAttachments$Builder
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$1
+ XXX.world.entity.EntityType$Builder
- XXX.world.entity.EntityType$EntityFactory
+ XXX.world.entity.EquipmentSlot
- XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.package-info
- XXX.world.flag.FeatureElement
+ XXX.world.flag.FeatureFlag
- XXX.world.flag.FeatureFlagRegistry
+ XXX.world.flag.FeatureFlagRegistry$Builder
- XXX.world.flag.FeatureFlags
- XXX.world.flag.FeatureFlagSet
+ XXX.world.flag.FeatureFlagUniverse
+ XXX.world.flag.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$Builder
- XXX.world.food.Foods
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractContainerMenu$1
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.AnvilMenu$1
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$FuelSlot
+ XXX.world.inventory.BrewingStandMenu$IngredientsSlot
- XXX.world.inventory.BrewingStandMenu$PotionSlot
+ XXX.world.inventory.CartographyTableMenu
- XXX.world.inventory.CartographyTableMenu$1
+ XXX.world.inventory.CartographyTableMenu$2
- XXX.world.inventory.CartographyTableMenu$3
+ XXX.world.inventory.CartographyTableMenu$4
- XXX.world.inventory.CartographyTableMenu$5
+ XXX.world.inventory.ChestMenu
- XXX.world.inventory.ClickAction
+ XXX.world.inventory.ClickType
- XXX.world.inventory.ContainerData
+ XXX.world.inventory.ContainerLevelAccess
- XXX.world.inventory.ContainerLevelAccess$1
+ XXX.world.inventory.ContainerLevelAccess$2
- XXX.world.inventory.ContainerListener
+ XXX.world.inventory.ContainerSynchronizer
- XXX.world.inventory.CrafterMenu
+ XXX.world.inventory.CrafterSlot
- XXX.world.inventory.CraftingContainer
+ XXX.world.inventory.CraftingMenu
- XXX.world.inventory.DataSlot
+ XXX.world.inventory.DataSlot$1
- XXX.world.inventory.DataSlot$2
+ XXX.world.inventory.DataSlot$3
- XXX.world.inventory.DispenserMenu
+ XXX.world.inventory.EnchantmentMenu
- XXX.world.inventory.EnchantmentMenu$1
+ XXX.world.inventory.EnchantmentMenu$2
- XXX.world.inventory.EnchantmentMenu$3
+ XXX.world.inventory.FurnaceFuelSlot
- XXX.world.inventory.FurnaceMenu
+ XXX.world.inventory.FurnaceResultSlot
- XXX.world.inventory.GrindstoneMenu
+ XXX.world.inventory.GrindstoneMenu$1
- XXX.world.inventory.GrindstoneMenu$2
+ XXX.world.inventory.GrindstoneMenu$3
- XXX.world.inventory.GrindstoneMenu$4
+ XXX.world.inventory.HopperMenu
- XXX.world.inventory.HorseInventoryMenu
+ XXX.world.inventory.HorseInventoryMenu$1
- XXX.world.inventory.HorseInventoryMenu$2
+ XXX.world.inventory.InventoryMenu
- XXX.world.inventory.InventoryMenu$1
+ XXX.world.inventory.InventoryMenu$2
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.ItemCombinerMenu$3
- XXX.world.inventory.ItemCombinerMenuSlotDefinition
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
+ XXX.world.inventory.LecternMenu
- XXX.world.inventory.LecternMenu$1
+ XXX.world.inventory.LoomMenu
- XXX.world.inventory.LoomMenu$1
+ XXX.world.inventory.LoomMenu$2
- XXX.world.inventory.LoomMenu$3
+ XXX.world.inventory.LoomMenu$4
- XXX.world.inventory.LoomMenu$5
+ XXX.world.inventory.LoomMenu$6
- XXX.world.inventory.MenuConstructor
+ XXX.world.inventory.MenuType
- XXX.world.inventory.MenuType$MenuSupplier
+ XXX.world.inventory.MerchantContainer
- XXX.world.inventory.MerchantMenu
+ XXX.world.inventory.MerchantResultSlot
- XXX.world.inventory.NonInteractiveResultSlot
- XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeCraftingHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
+ XXX.world.inventory.TransientCraftingContainer
- XXX.world.item.AdventureModePredicate
+ XXX.world.item.AirItem
- XXX.world.item.AnimalArmorItem
+ XXX.world.item.AnimalArmorItem$BodyType
- XXX.world.item.ArmorItem
+ XXX.world.item.ArmorItem$1
+ XXX.world.item.EggItem
- XXX.world.item.ElytraItem
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EnchantedBookItem
+ XXX.world.item.EnchantedGoldenAppleItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.InkSacItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$1
+ XXX.world.item.Item$Properties
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
+ XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUtils
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MapItem
- XXX.world.item.MapItem$1
- XXX.world.item.package-info
+ XXX.world.item.SmithingTemplateItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.Tier
+ XXX.world.item.TieredItem
- XXX.world.item.Tiers
+ XXX.world.item.TippedArrowItem
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.DisplaySlot
+ XXX.world.scores.DisplaySlot$1
- XXX.world.scores.Objective
- XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.ReadOnlyScoreInfo
+ XXX.world.scores.Score
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.ScoreHolder
- XXX.world.scores.ScoreHolder$1
+ XXX.world.scores.ScoreHolder$2
- XXX.world.scores.ScoreHolder$3
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.gui.screens.RealmsBackupScreen$Entry +9M -8M | +2P -5P
```
```
XXX.gui.screens.RealmsClientOutdatedScreen +4M -3M | +4P -2P
```
```
XXX.gui.screens.RealmsPlayerScreen +12M -13M | +4P -11P
```
```
XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList +1M -7M | +1P
```
```
net.minecraft.SharedConstants -3M | +1P
```
```
net.minecraft.Util +3M -2M
```
```
XXX.advancements.critereon.BlockPredicate +6M -4M | +1P -2P
```
```
XXX.advancements.critereon.EntityTypePredicate -5M
```
```
XXX.advancements.critereon.FluidPredicate +2M -3M | +1P -2P
```
```
XXX.advancements.critereon.ItemPredicate$Builder +3M -2M | +3P -3P
```
```
XXX.advancements.critereon.LocationPredicate +2M -3M | +2P -2P
```
```
XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher +1M | +1P
```
```
XXX.advancements.critereon.StatePropertiesPredicate$ValueMatcher +4M | +1P
```
```
XXX.client.gui.GuiGraphics +3M -3M
```
```
XXX.gui.components.Button +1P
```
```
XXX.gui.components.Checkbox +1M -1M
```
```
XXX.gui.components.DebugScreenOverlay +3M -5M
```
```
XXX.gui.components.ObjectSelectionList$Entry +1M
```
```
XXX.gui.components.OptionsList$Entry +3M -4M | +2P
```
```
XXX.gui.components.SpriteIconButton$Builder +1M | +1P
```
```
XXX.gui.components.SpriteIconButton$TextAndIcon +1M -1M
```
```
XXX.components.tabs.TabNavigationBar +1P -1P
```
```
XXX.components.toasts.SystemToast$SystemToastId +3P
```
```
XXX.gui.screens.AccessibilityOnboardingScreen +2M -1M | +2P -1P
```
```
XXX.gui.screens.ChatOptionsScreen +1M | +1P
```
```
XXX.gui.screens.CreateBuffetWorldScreen +1M -2M | +2P
```
```
XXX.gui.screens.CreateFlatWorldScreen$DetailsList -1M
```
```
XXX.gui.screens.LanguageSelectScreen +4M -4M | +1P
```
```
XXX.gui.screens.OptionsScreen +1M -1M | +2P
```
```
XXX.gui.screens.OutOfMemoryScreen +2M -1M | +4P -1P
```
```
XXX.gui.screens.PauseScreen +3M -2M
```
```
XXX.gui.screens.ShareToLanScreen +1M
```
```
XXX.gui.screens.SkinCustomizationScreen +1M -2M | +1P
```
```
XXX.gui.screens.TitleScreen +1M | +1P -3P
```
```
XXX.gui.screens.UnsupportedGraphicsWarningScreen -1M
```
```
XXX.gui.screens.VideoSettingsScreen +3M -4M | +1P
```
```
XXX.screens.achievement.StatsScreen$GeneralStatisticsList +1M
```
```
XXX.screens.achievement.StatsScreen$ItemStatisticsList +1M -2M | +6P
```
```
XXX.screens.multiplayer.SafetyScreen +4M -3M
```
```
XXX.screens.multiplayer.ServerSelectionList -1M
```
```
XXX.screens.multiplayer.WarningScreen +3M -3M | +5P -3P
```
```
XXX.screens.packs.PackSelectionScreen +8M -8M | +4P
```
```
XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList -1M
```
```
XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList -1M
```
```
XXX.screens.social.SocialInteractionsScreen +6M | +3P
```
```
XXX.screens.telemetry.TelemetryInfoScreen +4M -6M | +5P -2P
```
```
XXX.screens.worldselection.CreateWorldScreen +1M -1M | +3P -5P
```
```
XXX.screens.worldselection.ExperimentsScreen +1M -1M | +1P
```
```
XXX.data.loot.EntityLootSubProvider +1M -1M
```
```
XXX.data.loot.LootTableSubProvider +1P -1P
```
```
XXX.loot.packs.TradeRebalanceChestLoot +1M -1M
```
```
XXX.gametest.framework.GameTest +1P
```
```
XXX.gametest.framework.TestFinder$Builder +18M -9M | +2P
```
```
XXX.minecraft.network.FriendlyByteBuf -11M
```
```
XXX.network.chat.Component$Serializer +6M -7M
```
```
XXX.network.chat.ComponentSerialization +8M -9M | +3P -1P
```
```
XXX.network.chat.HoverEvent$EntityTooltipInfo +3M -2M
```
```
XXX.network.codec.ByteBufCodecs$5 +2M -2M
```
```
XXX.network.codec.ByteBufCodecs$7 +2M -2M
```
```
XXX.network.codec.ByteBufCodecs$9 +1M -1M | +1P
```
```
XXX.network.codec.StreamCodec +2M
```
```
XXX.minecraft.server.MinecraftServer +12M -9M
```
```
XXX.server.bossevents.CustomBossEvents +2M -2M
```
```
XXX.server.level.ChunkHolder +10M -12M | +3P -3P
```
```
XXX.server.level.ServerChunkCache +9M -11M | +1P -1P
```
```
XXX.server.level.ServerLevel +1M | +1P
```
```
XXX.level.progress.ProcessorChunkProgressListener +2M -2M
```
```
XXX.datafix.schemas.V3083 +1M -2M
```
```
XXX.ai.attributes.AttributeModifier +1M | +2P
```
```
XXX.entity.animal.Bee +1M
```
```
XXX.entity.animal.Bucketable +1M
```
```
XXX.entity.animal.IronGolem +1M -1M
```
```
XXX.world.item.ArmorItem$Type +1M -1M | +1P
```
```
XXX.world.item.AxeItem +1M -1M
```
```
XXX.world.item.BlockItem +3M -3M | -2P
```
```
XXX.world.item.BowItem +1M
```
```
XXX.world.item.BundleItem +1M -10M | -3P
```
```
XXX.world.item.CompassItem -6M | -4P
```
```
XXX.world.item.CreativeModeTabs +17M -18M
```
```
XXX.world.item.DebugStickItem -1M
```
```
XXX.world.item.MobBucketItem +1M | +1P
```
```
XXX.world.item.PickaxeItem +1M -1M
```
```
XXX.world.item.PlayerHeadItem +2M -1M | -1P
```
```
XXX.world.item.ProjectileWeaponItem +6M | +1P
```
```
XXX.world.item.ShovelItem +1M -1M
```
```
XXX.world.level.BaseCommandBlock +4M -3M | +1P -1P
```
```
XXX.world.level.Level +2M -2M
```
```
XXX.world.level.StructureManager +4M -3M
```
```
XXX.level.block.AbstractSkullBlock +1M -1M
```
```
XXX.level.block.BeaconBlock -1M
```
```
XXX.level.block.BrewingStandBlock +1M -2M
```
```
XXX.level.block.CactusBlock +1M -1M
```
```
XXX.level.block.ChorusPlantBlock +1M -1M
```
```
XXX.level.block.ComposterBlock +1M -1M
```
```
XXX.level.block.DecoratedPotBlock +3M -5M
```
```
XXX.level.block.DispenserBlock -1M
```
```
XXX.level.block.DragonEggBlock +1M -1M
```
```
XXX.level.block.EndPortalFrameBlock +1M -1M
```
```
XXX.level.block.EnderChestBlock +1M -1M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock +1M -1M
```
```
XXX.level.block.HopperBlock +1M -2M
```
```
XXX.level.block.LanternBlock +1M -1M
```
```
XXX.level.block.LecternBlock +1M -1M
```
```
XXX.level.block.PlayerHeadBlock -2M
```
```
XXX.level.block.PointedDripstoneBlock +1M -1M
```
```
XXX.level.block.SlabBlock +1M -1M
```
```
XXX.level.block.SnifferEggBlock +1M -1M
```
```
XXX.level.block.SuspiciousEffectHolder +1P -1P
```
```
XXX.block.entity.CommandBlockEntity +3M
```
```
XXX.block.entity.ShulkerBoxBlockEntity +4M -1M
```
```
XXX.entity.vault.VaultBlockEntity +2M -2M
```
```
XXX.block.piston.MovingPistonBlock +1M -1M
```
```
XXX.level.chunk.ChunkSource +1P -1P
```
```
XXX.level.levelgen.BelowZeroRetrogen +3M -3M | +1P -1P
```
```
XXX.level.storage.LevelStorageSource +1P
```
```
XXX.loot.entries.LootPoolEntries +1P -1P
```
```
XXX.loot.functions.CopyBlockState +1M -1M
```
```
XXX.loot.functions.LootItemFunctions +4P -2P
```
```
XXX.loot.functions.SetAttributesFunction +1M
```
```
XXX.loot.functions.SetBannerPatternFunction +3M -2M | +1P -2P
```
```
XXX.loot.functions.SetLoreFunction +2M -1M
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupScreen$Entry
</summary>

```diff
+ boolean mouseClicked(double,double,int)
+ Component getNarration()
- List children()
- List narratables()
- MutableComponent lambda$new$1(Supplier)
- MutableComponent lambda$new$3(Supplier)
- String getShortBackupDate()
+ void <clinit>()
+ void addChangesButton()
+ void addRestoreButton()
+ void lambda$addChangesButton$0(Button)
+ void lambda$addRestoreButton$1(Button)
- void lambda$new$0(Button)
- void lambda$new$2(Button)
+ void lambda$render$2(int,GuiGraphics,int,int,float,AbstractWidget)
- void lambda$restoreClicked$4(boolean)
- void restoreClicked()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsClientOutdatedScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- Component getErrorMessage()
+ Component[] getMessages()
- void lambda$init$1(RealmsClientOutdatedScreen,GuiEventListener)
- void onClose()
+ void render(GuiGraphics,int,int,float)
- void repositionElements()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
+ boolean shouldRemoveAndOpdeopButtonBeVisible(int)
- Font access$000(RealmsPlayerScreen)
- Font access$100(RealmsPlayerScreen)
- Font access$300(RealmsPlayerScreen)
- Font access$400(RealmsPlayerScreen)
- Font access$500(RealmsPlayerScreen)
- Font access$700(RealmsPlayerScreen)
- Font access$800(RealmsPlayerScreen)
+ int access$000(int)
+ int access$100(int)
- Minecraft access$600(RealmsPlayerScreen)
- Minecraft access$900(RealmsPlayerScreen)
+ void deop(int)
+ void lambda$init$2(Button)
- void lambda$init$2(RealmsPlayerScreen,GuiEventListener)
+ void lambda$init$3(Button)
+ void lambda$uninvite$4(PlayerInfo,boolean)
- void onClose()
+ void op(int)
+ void render(GuiGraphics,int,int,float)
- void repositionElements()
+ void uninvite(int)
+ void updateButtonStates()
+ void updateOps(Ops)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
</summary>

```diff
+ int getScrollbarPosition()
+ void addEntry(PlayerInfo)
- void renderHeader(GuiGraphics,int,int)
+ void selectInviteListItem(int)
+ void selectItem(int)
+ void setSelected(AbstractSelectionList$Entry)
+ void setSelected(RealmsPlayerScreen$Entry)
+ void updateButtons()
```

</details>
<details>
<summary>
net.minecraft.SharedConstants
</summary>

```diff
+ boolean isAllowedChatCharacter(char)
+ String filterText(String,boolean)
+ String filterText(String)
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ boolean isBlank(String)
+ boolean isWhitespace(int)
- List copyAndAdd(List,Object)
- Map copyAndPut(Map,Object,Object)
- String getRegisteredName(Registry,Object)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ App lambda$static$1(RecordCodecBuilder$Instance)
- boolean matches(BlockInWorld)
- boolean matchesBlockEntity(LevelReader,BlockEntity,NbtPredicate)
- boolean matchesState(BlockState)
- boolean requiresNbt()
+ List lambda$static$0(HolderSet)
+ Optional tag()
+ void <init>(Optional,Optional,Optional,Optional)
- void <init>(Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityTypePredicate
</summary>

```diff
+ DataResult lambda$static$4(EntityTypePredicate)
+ EntityTypePredicate lambda$static$0(TagKey)
+ EntityTypePredicate lambda$static$1(Holder)
+ EntityTypePredicate lambda$static$2(Either)
+ String lambda$static$3(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.FluidPredicate
</summary>

```diff
+ Optional fluid()
- Optional fluids()
+ Optional tag()
+ void <init>(Optional,Optional,Optional)
- void <init>(Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemPredicate$Builder
</summary>

```diff
- ItemPredicate$Builder hasComponents(DataComponentPredicate)
- ItemPredicate$Builder hasCustomData(CompoundTag)
+ ItemPredicate$Builder hasNbt(CompoundTag)
+ ItemPredicate$Builder isPotion(Holder)
- ItemPredicate$Builder isPotion(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate
</summary>

```diff
+ Optional biome()
- Optional biomes()
+ Optional of(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ Optional structure()
- Optional structures()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.StatePropertiesPredicate$ValueMatcher
</summary>

```diff
- Either lambda$static$7(StatePropertiesPredicate$ValueMatcher)
- Record lambda$static$4(StatePropertiesPredicate$ExactMatcher)
- Record lambda$static$5(StatePropertiesPredicate$RangedMatcher)
- StatePropertiesPredicate$ValueMatcher lambda$static$6(Either)
```

</details>
<details>
<summary>
net.minecraft.client.gui.GuiGraphics
</summary>

```diff
+ String lambda$renderItem$3(ItemStack)
- void fillRenderType(RenderType,int,int,int,int,int)
- void lambda$renderTooltip$3(List,TooltipComponent)
+ void lambda$renderTooltip$4(List,TooltipComponent)
- void lambda$renderTooltipInternal$4(int,int,int,int)
+ void lambda$renderTooltipInternal$5(int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.Checkbox
</summary>

```diff
+ int boxSize(Font)
- int getBoxSize(Font)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.DebugScreenOverlay
</summary>

```diff
+ LevelChunk lambda$getServerChunk$7(ChunkAccess)
- LevelChunk lambda$getServerChunk$7(ChunkResult)
+ LevelChunk lambda$getServerChunk$8(ChunkHolder$ChunkLoadingFailure)
+ LevelChunk lambda$getServerChunk$9(Either)
+ String lambda$getSystemInformation$10(TagKey)
+ String lambda$getSystemInformation$11(TagKey)
- String lambda$getSystemInformation$8(TagKey)
- String lambda$getSystemInformation$9(TagKey)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.ObjectSelectionList$Entry
</summary>

```diff
- boolean mouseClicked(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.OptionsList$Entry
</summary>

```diff
+ OptionsList$Entry big(Options,int,OptionInstance)
- OptionsList$Entry big(Options,OptionInstance,OptionsSubScreen)
+ OptionsList$Entry small(Options,int,OptionInstance,OptionInstance)
- OptionsList$Entry small(Options,OptionInstance,OptionInstance,OptionsSubScreen)
- void <init>(Map,OptionsSubScreen)
+ void <init>(Map)
+ void lambda$render$0(int,GuiGraphics,int,int,float,AbstractWidget)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.SpriteIconButton$Builder
</summary>

```diff
- SpriteIconButton$Builder narration(Button$CreateNarration)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.SpriteIconButton$TextAndIcon
</summary>

```diff
- void <init>(int,int,Component,int,int,ResourceLocation,Button$OnPress,Button$CreateNarration)
+ void <init>(int,int,Component,int,int,ResourceLocation,Button$OnPress)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.AccessibilityOnboardingScreen
</summary>

```diff
+ void renderBackground(GuiGraphics,int,int,float)
- void renderPanorama(GuiGraphics,float)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ChatOptionsScreen
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen
</summary>

```diff
+ void render(GuiGraphics,int,int,float)
+ void renderBackground(GuiGraphics,int,int,float)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
</summary>

```diff
+ int getScrollbarPosition()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen
</summary>

```diff
- void addFooter()
- void lambda$addFooter$0(Button)
- void lambda$addFooter$1(Button)
+ void lambda$init$0(Button)
+ void lambda$init$1(Button)
+ void render(GuiGraphics,int,int,float)
+ void renderBackground(GuiGraphics,int,int,float)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.OptionsScreen
</summary>

```diff
+ void render(GuiGraphics,int,int,float)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.OutOfMemoryScreen
</summary>

```diff
- void <clinit>()
+ void render(GuiGraphics,int,int,float)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PauseScreen
</summary>

```diff
- Screen lambda$createPauseMenu$5()
+ void lambda$createPauseMenu$5(Button)
- void lambda$createPauseMenu$6(Button)
+ void lambda$openScreenButton$6(Supplier,Button)
- void lambda$openScreenButton$7(Supplier,Button)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ShareToLanScreen
</summary>

```diff
- void onClose()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.SkinCustomizationScreen
</summary>

```diff
- void <clinit>()
+ void lambda$init$1(Button)
+ void render(GuiGraphics,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.TitleScreen
</summary>

```diff
- void renderPanorama(GuiGraphics,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.UnsupportedGraphicsWarningScreen
</summary>

```diff
+ void renderBackground(GuiGraphics,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.VideoSettingsScreen
</summary>

```diff
+ void lambda$init$2(Window,Button)
- void lambda$mouseClicked$2(Button)
+ void lambda$mouseClicked$4(Button)
- void onClose()
+ void render(GuiGraphics,int,int,float)
+ void renderBackground(GuiGraphics,int,int,float)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
</summary>

```diff
- int getRowWidth()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
</summary>

```diff
+ Component getString(Item)
- int getColumnX(int)
+ int getScrollbarPosition()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.SafetyScreen
</summary>

```diff
- Layout addFooterButtons()
+ void initButtons(int)
- void lambda$addFooterButtons$0(Button)
- void lambda$addFooterButtons$1(Button)
+ void lambda$initButtons$0(Button)
+ void lambda$initButtons$1(Button)
- void onClose()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
</summary>

```diff
+ int getScrollbarPosition()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.WarningScreen
</summary>

```diff
+ int getLineHeight()
- void lambda$init$0(LayoutSettings)
- void lambda$init$1(WarningScreen,GuiEventListener)
+ void render(GuiGraphics,int,int,float)
+ void renderTitle(GuiGraphics)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.packs.PackSelectionScreen
</summary>

```diff
+ ResourceLocation lambda$getPackIcon$8(Pack,String)
- ResourceLocation lambda$getPackIcon$9(Pack,String)
+ void lambda$copyPacks$3(Path,Path,MutableBoolean,Path)
+ void lambda$copyPacks$4(Path,MutableBoolean,Path)
- void lambda$copyPacks$4(Path,Path,MutableBoolean,Path)
- void lambda$copyPacks$5(Path,MutableBoolean,Path)
- void lambda$init$2(PackSelectionScreen,GuiEventListener)
+ void lambda$onFilesDrop$5()
- void lambda$onFilesDrop$7()
+ void lambda$onFilesDrop$7(List,boolean)
- void lambda$onFilesDrop$8(List,boolean)
+ void lambda$updateList$2(TransferableSelectionList,String,PackSelectionModel$Entry)
- void lambda$updateList$3(TransferableSelectionList,String,PackSelectionModel$Entry)
+ void render(GuiGraphics,int,int,float)
+ void renderBackground(GuiGraphics,int,int,float)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList
</summary>

```diff
+ int getScrollbarPosition()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
</summary>

```diff
+ int getScrollbarPosition()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.social.SocialInteractionsScreen
</summary>

```diff
- void <init>(Screen)
- void lambda$init$3(Button)
- void lambda$init$4(SocialInteractionsScreen,GuiEventListener)
- void onClose()
- void repositionElements()
- void setInitialFocus()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.telemetry.TelemetryInfoScreen
</summary>

```diff
+ GridLayout twoButtonContainer(AbstractWidget,AbstractWidget)
+ Layout createLowerSection()
- void lambda$init$0(Button)
+ void lambda$init$0(double)
- void lambda$init$1(double)
+ void lambda$init$1(TelemetryInfoScreen,GuiEventListener)
- void lambda$init$2(TelemetryInfoScreen,GuiEventListener)
+ void openLastScreen(Button)
+ void renderBackground(GuiGraphics,int,int,float)
- void repositionElements()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
</summary>

```diff
+ void renderDirtBackground(GuiGraphics)
- void renderMenuBackground(GuiGraphics)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.ExperimentsScreen
</summary>

```diff
- void <clinit>()
+ void renderBackground(GuiGraphics,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.data.loot.EntityLootSubProvider
</summary>

```diff
+ void generate(BiConsumer)
- void generate(HolderLookup$Provider,BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.TradeRebalanceChestLoot
</summary>

```diff
+ void generate(BiConsumer)
- void generate(HolderLookup$Provider,BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.TestFinder$Builder
</summary>

```diff
- boolean lambda$allTests$7(TestFunction)
- boolean lambda$allTestsInClass$9(TestFunction)
- boolean lambda$failedTests$11(boolean,TestFunction)
+ boolean lambda$failedTests$6(boolean,TestFunction)
- Object build(CommandSourceStack,TestFunctionFinder,StructureBlockPosFinder)
+ Stream lambda$allNearby$2(BlockPos,CommandSourceStack)
- Stream lambda$allNearby$5(BlockPos,CommandSourceStack)
+ Stream lambda$allTests$4()
- Stream lambda$allTests$8()
- Stream lambda$allTestsInClass$10(String)
+ Stream lambda$allTestsInClass$5(String)
- Stream lambda$byArgument$13(CommandContext,String)
+ Stream lambda$byArgument$8(CommandContext,String)
- Stream lambda$failedTests$12(boolean)
+ Stream lambda$failedTests$7(boolean)
+ Stream lambda$lookedAt$3(CommandSourceStack)
- Stream lambda$lookedAt$6(CommandSourceStack)
+ Stream lambda$nearest$1(BlockPos,CommandSourceStack)
- Stream lambda$nearest$4(BlockPos,CommandSourceStack)
+ Stream lambda$radius$0(int,CommandSourceStack)
- Stream lambda$radius$3(int,CommandSourceStack)
- Supplier lambda$createCopies$2(int,Supplier)
- Supplier lambda$new$0(Supplier)
- Supplier lambda$new$1(Supplier)
- TestFinder$Builder createMultipleCopies(int)
- UnaryOperator createCopies(int)
- void <init>(Function,UnaryOperator,UnaryOperator)
```

</details>
<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
+ Either readEither(StreamDecoder,StreamDecoder)
+ GameProfile readGameProfile()
+ Property readProperty()
+ PropertyMap readGameProfileProperties()
+ void lambda$readGameProfileProperties$8(PropertyMap,FriendlyByteBuf)
+ void lambda$writeEither$6(StreamEncoder,Object)
+ void lambda$writeEither$7(StreamEncoder,Object)
+ void writeEither(Either,StreamEncoder,StreamEncoder)
+ void writeGameProfile(GameProfile)
+ void writeGameProfileProperties(PropertyMap)
+ void writeProperty(Property)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Component$Serializer
</summary>

```diff
- JsonElement serialize(Component,HolderLookup$Provider)
+ JsonElement serialize(Component)
+ JsonElement toJsonTree(Component)
- MutableComponent deserialize(JsonElement,HolderLookup$Provider)
+ MutableComponent deserialize(JsonElement)
- MutableComponent fromJson(JsonElement,HolderLookup$Provider)
+ MutableComponent fromJson(JsonElement)
- MutableComponent fromJson(String,HolderLookup$Provider)
+ MutableComponent fromJson(String)
- MutableComponent fromJsonLenient(String,HolderLookup$Provider)
+ MutableComponent fromJsonLenient(String)
- String toJson(Component,HolderLookup$Provider)
+ String toJson(Component)
```

</details>
<details>
<summary>
net.minecraft.network.chat.ComponentSerialization
</summary>

```diff
- App lambda$createCodec$3(MapCodec,Codec,RecordCodecBuilder$Instance)
+ App lambda$createCodec$5(MapCodec,Codec,RecordCodecBuilder$Instance)
- Codec flatCodec(int)
- Codec lambda$createLegacyComponentMatcher$2(Function,StringRepresentable)
+ Codec lambda$createLegacyComponentMatcher$4(Function,StringRepresentable)
- Component lambda$createCodec$4(Either)
- Component lambda$createCodec$5(Component)
+ Component lambda$createCodec$7(Component)
+ Component lambda$createCodec$8(Either)
+ DataResult lambda$static$0(JsonElement)
+ DataResult lambda$static$1(Component)
- Either lambda$createCodec$7(Component)
+ Either lambda$createCodec$9(Component)
- MapEncoder lambda$createLegacyComponentMatcher$0(Function,Function,Object)
+ MapEncoder lambda$createLegacyComponentMatcher$2(Function,Function,Object)
- StringRepresentable[] lambda$createLegacyComponentMatcher$1(StringRepresentable[])
+ StringRepresentable[] lambda$createLegacyComponentMatcher$3(StringRepresentable[])
```

</details>
<details>
<summary>
net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
</summary>

```diff
- DataResult legacyCreate(Component,RegistryOps)
+ DataResult legacyCreate(Component)
- HoverEvent$EntityTooltipInfo lambda$legacyCreate$4(EntityType,UUID,Component)
+ String lambda$legacyCreate$4(Exception)
- String lambda$legacyCreate$5(Exception)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$5
</summary>

```diff
- Integer decode(ByteBuf)
+ Long decode(ByteBuf)
- void encode(ByteBuf,Integer)
+ void encode(ByteBuf,Long)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$7
</summary>

```diff
+ Double decode(ByteBuf)
- Float decode(ByteBuf)
+ void encode(ByteBuf,Double)
- void encode(ByteBuf,Float)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$9
</summary>

```diff
+ void <init>()
- void <init>(int)
```

</details>
<details>
<summary>
net.minecraft.network.codec.StreamCodec
</summary>

```diff
- StreamCodec composite(StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,Function6)
- StreamCodec recursive(UnaryOperator)
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
+ boolean lambda$getSelectedPacks$28(Collection,String)
- boolean lambda$getSelectedPacks$29(Collection,String)
+ CompletionStage lambda$reloadResources$26(RegistryAccess$Frozen,ImmutableList)
- CompletionStage lambda$reloadResources$27(RegistryAccess$Frozen,ImmutableList)
+ ImmutableList lambda$reloadResources$23(Collection)
- ImmutableList lambda$reloadResources$24(Collection)
+ MinecraftServer$ReloadableResources lambda$reloadResources$25(CloseableResourceManager,ReloadableServerResources)
- MinecraftServer$ReloadableResources lambda$reloadResources$26(CloseableResourceManager,ReloadableServerResources)
+ String lambda$dumpNativeModules$29(NativeModuleLister$NativeModuleInfo)
- String lambda$dumpNativeModules$30(NativeModuleLister$NativeModuleInfo)
- String lambda$fillSystemReport$23()
+ void lambda$reloadResources$24(CloseableResourceManager,ReloadableServerResources,Throwable)
- void lambda$reloadResources$25(CloseableResourceManager,ReloadableServerResources,Throwable)
+ void lambda$reloadResources$27(Collection,MinecraftServer$ReloadableResources)
- void lambda$reloadResources$28(Collection,MinecraftServer$ReloadableResources)
+ void lambda$startMetricsRecordingTick$30(Path)
- void lambda$startMetricsRecordingTick$32(Path)
+ void lambda$startRecordingMetrics$32(Consumer,ProfileResults)
- void lambda$startRecordingMetrics$33(Consumer,ProfileResults)
- void reportChunkLoadFailure(ChunkPos)
- void reportChunkSaveFailure(ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.server.bossevents.CustomBossEvents
</summary>

```diff
+ CompoundTag save()
- CompoundTag save(HolderLookup$Provider)
- void load(CompoundTag,HolderLookup$Provider)
+ void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkHolder
</summary>

```diff
- ChunkAccess lambda$updateChunkToSave$3(ChunkAccess,ChunkResult)
+ ChunkAccess lambda$updateChunkToSave$3(ChunkAccess)
+ ChunkAccess lambda$updateChunkToSave$4(ChunkAccess,ChunkHolder$ChunkLoadingFailure)
+ ChunkAccess lambda$updateChunkToSave$5(ChunkAccess,Either)
+ ChunkStatus getLastAvailableStatus()
- ChunkStatus getLastAvailableStatus()
+ CompletableFuture getFutureIfPresent(ChunkStatus)
- CompletableFuture getFutureIfPresent(ChunkStatus)
+ CompletableFuture getFutureIfPresentUnchecked(ChunkStatus)
- CompletableFuture getFutureIfPresentUnchecked(ChunkStatus)
+ CompletableFuture getOrScheduleFuture(ChunkStatus,ChunkMap)
- CompletableFuture getOrScheduleFuture(ChunkStatus,ChunkMap)
+ LevelChunk getFullChunk()
- Object lambda$addSendDependency$4(Object,Object)
+ Object lambda$addSendDependency$6(Object,Object)
- String lambda$updateFutures$8()
- void lambda$scheduleFullChunkPromotion$5(ChunkMap,FullChunkStatus)
- void lambda$scheduleFullChunkPromotion$6(CompletableFuture,LevelChunk)
+ void lambda$scheduleFullChunkPromotion$7(ChunkMap,FullChunkStatus)
- void lambda$scheduleFullChunkPromotion$7(CompletableFuture,ChunkResult)
+ void lambda$scheduleFullChunkPromotion$8(CompletableFuture,LevelChunk)
+ void lambda$scheduleFullChunkPromotion$9(CompletableFuture,Either)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache
</summary>

```diff
+ ChunkAccess getChunk(int,int,ChunkStatus,boolean)
- ChunkAccess getChunk(int,int,ChunkStatus,boolean)
+ ChunkAccess lambda$getChunk$0(int,int,ChunkStatus,boolean)
- ChunkAccess lambda$getChunk$0(int,int,ChunkStatus,boolean)
+ ChunkAccess lambda$getChunk$1(ChunkAccess)
+ ChunkAccess lambda$getChunk$2(boolean,ChunkHolder$ChunkLoadingFailure)
+ CompletableFuture getChunkFuture(int,int,ChunkStatus,boolean)
- CompletableFuture getChunkFuture(int,int,ChunkStatus,boolean)
+ CompletableFuture getChunkFutureMainThread(int,int,ChunkStatus,boolean)
- CompletableFuture getChunkFutureMainThread(int,int,ChunkStatus,boolean)
- CompletableFuture lambda$getChunkFuture$1(int,int,ChunkStatus,boolean)
+ CompletableFuture lambda$getChunkFuture$3(int,int,ChunkStatus,boolean)
- CompletionStage lambda$getChunkFuture$2(CompletableFuture)
+ CompletionStage lambda$getChunkFuture$4(CompletableFuture)
- void lambda$onLightUpdate$4(SectionPos,LightLayer)
+ void lambda$onLightUpdate$6(SectionPos,LightLayer)
- void lambda$tickChunks$3(ServerChunkCache$ChunkAndHolder)
+ void lambda$tickChunks$5(ServerChunkCache$ChunkAndHolder)
+ void storeInCache(long,ChunkAccess,ChunkStatus)
- void storeInCache(long,ChunkAccess,ChunkStatus)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- PathTypeCache getPathTypeCache()
```

</details>
<details>
<summary>
net.minecraft.server.level.progress.ProcessorChunkProgressListener
</summary>

```diff
+ void lambda$onStatusChange$1(ChunkPos,ChunkStatus)
- void lambda$onStatusChange$1(ChunkPos,ChunkStatus)
+ void onStatusChange(ChunkPos,ChunkStatus)
- void onStatusChange(ChunkPos,ChunkStatus)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V3083
</summary>

```diff
- TypeTemplate lambda$registerEntities$0(Schema)
+ TypeTemplate lambda$registerMob$0(Schema)
+ void registerMob(Schema,Map,String)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeModifier
</summary>

```diff
- String lambda$static$2(AttributeModifier)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
- void setHivePos(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bucketable
</summary>

```diff
- void lambda$saveDefaultDataToBucketTag$0(Mob,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.IronGolem
</summary>

```diff
- Crackiness$Level getCrackiness()
+ IronGolem$Crackiness getCrackiness()
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorItem$Type
</summary>

```diff
- void <init>(String,int,EquipmentSlot,int,String)
+ void <init>(String,int,EquipmentSlot,String)
```

</details>
<details>
<summary>
net.minecraft.world.item.AxeItem
</summary>

```diff
+ void <init>(Tier,float,float,Item$Properties)
- void <init>(Tier,Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.BlockItem
</summary>

```diff
+ BlockState lambda$updateState$0(BlockState,Property,Comparable)
+ BlockState updateState(BlockState,Property,String)
+ CompoundTag getBlockEntityData(ItemStack)
- void lambda$updateBlockEntityData$0(Consumer,BlockEntityType,CompoundTag)
- void updateBlockEntityComponents(Level,BlockPos,ItemStack)
- void updateBlockEntityData(ItemStack,BlockEntityType,Consumer)
```

</details>
<details>
<summary>
net.minecraft.world.item.BowItem
</summary>

```diff
- void shootProjectile(LivingEntity,Projectile,int,float,float,float,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.BundleItem
</summary>

```diff
+ boolean lambda$getMatchingItem$2(ItemStack,CompoundTag)
+ int add(ItemStack,ItemStack)
+ int getContentWeight(ItemStack)
+ int getWeight(ItemStack)
+ int lambda$getContentWeight$3(ItemStack)
+ Optional getMatchingItem(ItemStack,ListTag)
+ Optional removeOne(ItemStack)
+ Stream getContents(ItemStack)
- void lambda$dropContents$0(Player,ItemStack)
+ void lambda$overrideOtherStackedOnMe$1(Player,SlotAccess,ItemStack)
+ void lambda$overrideStackedOnOther$0(ItemStack,Slot,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.CompassItem
</summary>

```diff
+ boolean isLodestoneCompass(ItemStack)
+ GlobalPos getLodestonePosition(CompoundTag)
+ Optional getLodestoneDimension(CompoundTag)
+ void <clinit>()
+ void addLodestoneTags(ResourceKey,BlockPos,CompoundTag)
+ void lambda$addLodestoneTags$0(CompoundTag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs
</summary>

```diff
- boolean lambda$buildAllTabContents$48(CreativeModeTab)
+ boolean lambda$buildAllTabContents$49(CreativeModeTab)
- boolean lambda$buildAllTabContents$50(CreativeModeTab)
+ boolean lambda$buildAllTabContents$51(CreativeModeTab)
- boolean lambda$generateEnchantmentBookTypesAllLevels$40(Set,Enchantment)
+ boolean lambda$generateEnchantmentBookTypesAllLevels$41(Set,Enchantment)
- boolean lambda$generateEnchantmentBookTypesOnlyMaxLevel$37(Set,Enchantment)
+ boolean lambda$generateEnchantmentBookTypesOnlyMaxLevel$38(Set,Enchantment)
+ boolean lambda$generatePotionEffectTypes$35(Holder$Reference)
- ItemStack lambda$generateEnchantmentBookTypesAllLevels$41(Enchantment,int)
+ ItemStack lambda$generateEnchantmentBookTypesAllLevels$42(Enchantment,int)
- ItemStack lambda$generateEnchantmentBookTypesOnlyMaxLevel$38(Enchantment)
+ ItemStack lambda$generateEnchantmentBookTypesOnlyMaxLevel$39(Enchantment)
- ItemStack lambda$generateInstrumentTypes$44(Item,Holder)
+ ItemStack lambda$generateInstrumentTypes$45(Item,Holder)
- ItemStack lambda$generatePotionEffectTypes$35(Item,Holder$Reference)
+ ItemStack lambda$generatePotionEffectTypes$36(Item,Holder$Reference)
- Stream lambda$generateEnchantmentBookTypesAllLevels$42(Enchantment)
+ Stream lambda$generateEnchantmentBookTypesAllLevels$43(Enchantment)
- void lambda$buildAllTabContents$49(CreativeModeTab$ItemDisplayParameters,CreativeModeTab)
+ void lambda$buildAllTabContents$50(CreativeModeTab$ItemDisplayParameters,CreativeModeTab)
- void lambda$buildAllTabContents$51(CreativeModeTab$ItemDisplayParameters,CreativeModeTab)
+ void lambda$buildAllTabContents$52(CreativeModeTab$ItemDisplayParameters,CreativeModeTab)
- void lambda$generateEnchantmentBookTypesAllLevels$43(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generateEnchantmentBookTypesAllLevels$44(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
- void lambda$generateEnchantmentBookTypesOnlyMaxLevel$39(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generateEnchantmentBookTypesOnlyMaxLevel$40(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
- void lambda$generateInstrumentTypes$45(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generateInstrumentTypes$46(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
- void lambda$generateInstrumentTypes$46(Item,CreativeModeTab$Output,CreativeModeTab$TabVisibility,HolderSet$Named)
+ void lambda$generateInstrumentTypes$47(Item,CreativeModeTab$Output,CreativeModeTab$TabVisibility,HolderSet$Named)
- void lambda$generatePotionEffectTypes$36(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generatePotionEffectTypes$37(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
- void lambda$generatePresetPaintings$47(CreativeModeTab$Output,CreativeModeTab$TabVisibility,Holder$Reference)
+ void lambda$generatePresetPaintings$48(CreativeModeTab$Output,CreativeModeTab$TabVisibility,Holder$Reference)
```

</details>
<details>
<summary>
net.minecraft.world.item.DebugStickItem
</summary>

```diff
+ boolean isFoil(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.MobBucketItem
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.item.PickaxeItem
</summary>

```diff
+ void <init>(Tier,int,float,Item$Properties)
- void <init>(Tier,Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.PlayerHeadItem
</summary>

```diff
- void lambda$verifyComponentsAfterLoad$0(ItemStack,ResolvableProfile)
- void verifyComponentsAfterLoad(ItemStack)
+ void verifyTagAfterLoad(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.item.ProjectileWeaponItem
</summary>

```diff
- boolean hasInfiniteArrows(ItemStack,ItemStack,boolean)
- int getDurabilityUse(ItemStack)
- ItemStack useAmmo(ItemStack,ItemStack,LivingEntity,boolean)
- List draw(ItemStack,ItemStack,LivingEntity)
- Projectile createProjectile(Level,LivingEntity,ItemStack,ItemStack,boolean)
- void shoot(Level,LivingEntity,InteractionHand,ItemStack,List,float,float,boolean,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.ShovelItem
</summary>

```diff
+ void <init>(Tier,float,float,Item$Properties)
- void <init>(Tier,Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.BaseCommandBlock
</summary>

```diff
- Component getCustomName()
- CompoundTag save(CompoundTag,HolderLookup$Provider)
+ CompoundTag save(CompoundTag)
- void load(CompoundTag,HolderLookup$Provider)
+ void load(CompoundTag)
- void setCustomName(Component)
+ void setName(Component)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ ChunkAccess getChunk(int,int,ChunkStatus,boolean)
- ChunkAccess getChunk(int,int,ChunkStatus,boolean)
+ void createFireworks(double,double,double,double,double,double,CompoundTag)
- void createFireworks(double,double,double,double,double,double,List)
```

</details>
<details>
<summary>
net.minecraft.world.level.StructureManager
</summary>

```diff
- boolean lambda$getStructureWithPieceAt$0(TagKey,Holder)
+ Boolean lambda$getStructureWithPieceAt$0(TagKey,Holder$Reference)
- boolean lambda$getStructureWithPieceAt$1(Registry,Predicate,Structure)
+ boolean lambda$getStructureWithPieceAt$1(Registry,TagKey,Structure)
- StructureStart getStructureWithPieceAt(BlockPos,HolderSet)
- StructureStart getStructureWithPieceAt(BlockPos,Predicate)
+ StructureStart getStructureWithPieceAt(BlockPos,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractSkullBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
+ void setPlacedBy(Level,BlockPos,BlockState,LivingEntity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
+ void setPlacedBy(Level,BlockPos,BlockState,LivingEntity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CactusBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ComposterBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DecoratedPotBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
- void lambda$appendHoverText$1(List,Optional)
+ void lambda$appendHoverText$2(List,Item)
- void lambda$getDrops$0(DecoratedPotBlockEntity,Consumer)
+ void lambda$getDrops$1(DecoratedPotBlockEntity,Consumer)
+ void lambda$setPlacedBy$0(ItemStack,DecoratedPotBlockEntity)
+ void setPlacedBy(Level,BlockPos,BlockState,LivingEntity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ void setPlacedBy(Level,BlockPos,BlockState,LivingEntity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DragonEggBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndPortalFrameBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
+ void setPlacedBy(Level,BlockPos,BlockState,LivingEntity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LanternBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PlayerHeadBlock
</summary>

```diff
+ void initializeSkullOwner(Level,BlockPos,ItemStack)
+ void setPlacedBy(Level,BlockPos,BlockState,LivingEntity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PointedDripstoneBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlabBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SnifferEggBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.CommandBlockEntity
</summary>

```diff
- void applyComponents(DataComponentMap)
- void collectComponents(DataComponentMap$Builder)
- void removeComponentsFromTag(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
</summary>

```diff
- void applyComponents(DataComponentMap)
- void collectComponents(DataComponentMap$Builder)
- void loadFromTag(CompoundTag,HolderLookup$Provider)
+ void loadFromTag(CompoundTag)
- void removeComponentsFromTag(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultBlockEntity
</summary>

```diff
- Tag encode(Codec,Object,HolderLookup$Provider)
+ Tag encode(Codec,Object)
+ void lambda$getUpdateTag$0(CompoundTag)
- void lambda$getUpdateTag$0(HolderLookup$Provider,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.BelowZeroRetrogen
</summary>

```diff
+ ChunkStatus targetStatus()
- ChunkStatus targetStatus()
+ DataResult lambda$static$3(ChunkStatus)
- DataResult lambda$static$3(ChunkStatus)
+ void <init>(ChunkStatus,Optional)
- void <init>(ChunkStatus,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyBlockState
</summary>

```diff
- BlockItemStateProperties lambda$run$3(BlockState,BlockItemStateProperties)
+ String serialize(BlockState,Property)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
</summary>

```diff
- ItemAttributeModifiers lambda$run$3(LootContext,ItemAttributeModifiers)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
</summary>

```diff
- BannerPatternLayers lambda$run$3(BannerPatternLayers,BannerPatternLayers)
- BannerPatternLayers lambda$static$0(SetBannerPatternFunction)
+ List lambda$static$0(SetBannerPatternFunction)
- void <init>(List,BannerPatternLayers,boolean)
+ void <init>(List,List,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetLoreFunction
</summary>

```diff
- ItemLore lambda$run$5(LootContext,ItemLore)
- List updateLore(ItemLore,LootContext)
+ ListTag getLoreTag(ItemStack,boolean)
```

</details>
</details>
<hr/>