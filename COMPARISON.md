## Comparison with [1.21.4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.4)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [Packets](#packets)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>DataPack version</td><td><pre>61</pre></td><td><pre>62</pre></td></tr><tr><td>ResourcePack version</td><td><pre>46</pre></td><td><pre>47</pre></td></tr><tr><td>World version</td><td><pre>4189</pre></td><td><pre>4298</pre></td></tr><tr><td>Protocol version</td><td><pre>769</pre></td><td><pre>1073742053</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>com.mojang:text2speech</td><td><pre>1.17.9</pre></td><td><pre>1.18.10</pre></td></tr></table>
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
+ ticket_type.txt
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:leaf_litter
+ minecraft:wildflowers
```

</details>
<details>
<summary>
block_type
</summary>

```diff
+ minecraft:flower_bed
+ minecraft:leaf_litter
- minecraft:particle_leaves
- minecraft:pink_petals
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:potion_duration_scale
+ minecraft:weapon
```

</details>
<details>
<summary>
entity_sub_predicate_type
</summary>

```diff
+ minecraft:pig
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:leaf_litter
+ minecraft:wildflowers
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:tinted_leaves
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.iron.break
+ minecraft:block.iron.fall
+ minecraft:block.iron.hit
+ minecraft:block.iron.place
+ minecraft:block.iron.step
+ minecraft:block.leaf_litter.break
+ minecraft:block.leaf_litter.fall
+ minecraft:block.leaf_litter.hit
+ minecraft:block.leaf_litter.place
+ minecraft:block.leaf_litter.step
```

</details>
<details>
<summary>
worldgen/tree_decorator_type
</summary>

```diff
+ minecraft:place_on_ground
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
+ universal_tags/ticket_type.json
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:leaf_litter
+ minecraft:wildflowers
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:leaf_litter
+ minecraft:wildflowers
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:flower_bed
+ minecraft:leaf_litter
- minecraft:particle_leaves
- minecraft:pink_petals
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:potion_duration_scale
+ minecraft:weapon
```

</details>
<details>
<summary>
universal_tags/entity_sub_predicate_type.json
</summary>

```diff
+ minecraft:pig
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:leaf_litter
+ minecraft:wildflowers
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:tinted_leaves
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.iron.break
+ minecraft:block.iron.fall
+ minecraft:block.iron.hit
+ minecraft:block.iron.place
+ minecraft:block.iron.step
+ minecraft:block.leaf_litter.break
+ minecraft:block.leaf_litter.fall
+ minecraft:block.leaf_litter.hit
+ minecraft:block.leaf_litter.place
+ minecraft:block.leaf_litter.step
```

</details>
<details>
<summary>
universal_tags/worldgen/tree_decorator_type.json
</summary>

```diff
+ minecraft:place_on_ground
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (REGISTRY)</ins></b><a name="items-(registry)"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ leaf_litter.json
+ wildflowers.json
```

</details>
<details>
<summary>
acacia_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.acacia_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.acacia_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.acacia_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.acacia_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_sapling"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_sapling"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.acacia_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.acacia_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
activator_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.activator_rail"}</pre></td><td><pre>{
  "translate": "block.minecraft.activator_rail"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
air
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.air"}</pre></td><td><pre>{
  "translate": "block.minecraft.air"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allay_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.allay_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.allay_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.allium"}</pre></td><td><pre>{
  "translate": "block.minecraft.allium"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.amethyst_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.amethyst_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_cluster
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.amethyst_cluster"}</pre></td><td><pre>{
  "translate": "block.minecraft.amethyst_cluster"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.amethyst_shard"}</pre></td><td><pre>{
  "translate": "item.minecraft.amethyst_shard"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ancient_debris
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.ancient_debris"}</pre></td><td><pre>{
  "translate": "block.minecraft.ancient_debris"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.andesite"}</pre></td><td><pre>{
  "translate": "block.minecraft.andesite"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.andesite_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.andesite_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.andesite_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.andesite_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.andesite_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.andesite_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
angler_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.angler_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.angler_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.anvil"}</pre></td><td><pre>{
  "translate": "block.minecraft.anvil"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.apple"}</pre></td><td><pre>{
  "translate": "item.minecraft.apple"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
archer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.archer_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.archer_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_scute
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.armadillo_scute"}</pre></td><td><pre>{
  "translate": "item.minecraft.armadillo_scute"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.armadillo_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.armadillo_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armor_stand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.armor_stand"}</pre></td><td><pre>{
  "translate": "item.minecraft.armor_stand"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arms_up_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.arms_up_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.arms_up_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.arrow"}</pre></td><td><pre>{
  "translate": "item.minecraft.arrow"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.axolotl_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.axolotl_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.axolotl_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.axolotl_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.azalea"}</pre></td><td><pre>{
  "translate": "block.minecraft.azalea"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.azalea_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.azalea_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azure_bluet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.azure_bluet"}</pre></td><td><pre>{
  "translate": "block.minecraft.azure_bluet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
baked_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.baked_potato"}</pre></td><td><pre>{
  "translate": "item.minecraft.baked_potato"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_chest_raft
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bamboo_chest_raft"}</pre></td><td><pre>{
  "translate": "item.minecraft.bamboo_chest_raft"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_mosaic"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_mosaic"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_mosaic_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_mosaic_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_mosaic_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_mosaic_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_raft
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bamboo_raft"}</pre></td><td><pre>{
  "translate": "item.minecraft.bamboo_raft"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bamboo_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.bamboo_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.barrel"}</pre></td><td><pre>{
  "translate": "block.minecraft.barrel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrier
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.barrier"}</pre></td><td><pre>{
  "translate": "block.minecraft.barrier"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.basalt"}</pre></td><td><pre>{
  "translate": "block.minecraft.basalt"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bat_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.bat_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beacon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.beacon"}</pre></td><td><pre>{
  "translate": "block.minecraft.beacon"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bedrock
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bedrock"}</pre></td><td><pre>{
  "translate": "block.minecraft.bedrock"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.beef"}</pre></td><td><pre>{
  "translate": "item.minecraft.beef"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beehive
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.beehive"}</pre></td><td><pre>{
  "translate": "block.minecraft.beehive"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.beetroot"}</pre></td><td><pre>{
  "translate": "item.minecraft.beetroot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.beetroot_seeds"}</pre></td><td><pre>{
  "translate": "item.minecraft.beetroot_seeds"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_soup
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.beetroot_soup"}</pre></td><td><pre>{
  "translate": "item.minecraft.beetroot_soup"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_nest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bee_nest"}</pre></td><td><pre>{
  "translate": "block.minecraft.bee_nest"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bee_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.bee_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bell"}</pre></td><td><pre>{
  "translate": "block.minecraft.bell"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
big_dripleaf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.big_dripleaf"}</pre></td><td><pre>{
  "translate": "block.minecraft.big_dripleaf"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.birch_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.birch_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.birch_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.birch_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_sapling"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_sapling"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.birch_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.birch_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blackstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.blackstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blackstone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.blackstone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blackstone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.blackstone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blackstone_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.blackstone_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.black_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.black_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.black_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.black_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.black_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.black_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blade_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.blade_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.blade_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blast_furnace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blast_furnace"}</pre></td><td><pre>{
  "translate": "block.minecraft.blast_furnace"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.blaze_powder"}</pre></td><td><pre>{
  "translate": "item.minecraft.blaze_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.blaze_rod"}</pre></td><td><pre>{
  "translate": "item.minecraft.blaze_rod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.blaze_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.blaze_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.blue_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.blue_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.blue_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.blue_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_ice"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_ice"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_orchid
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_orchid"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_orchid"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.blue_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.blue_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bogged_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bogged_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.bogged_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bolt_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bolt_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.bolt_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bone"}</pre></td><td><pre>{
  "translate": "item.minecraft.bone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bone_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.bone_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_meal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bone_meal"}</pre></td><td><pre>{
  "translate": "item.minecraft.bone_meal"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.book"}</pre></td><td><pre>{
  "translate": "item.minecraft.book"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bookshelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bookshelf"}</pre></td><td><pre>{
  "translate": "block.minecraft.bookshelf"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bordure_indented_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bordure_indented_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.bordure_indented_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bow"}</pre></td><td><pre>{
  "translate": "item.minecraft.bow"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bowl
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bowl"}</pre></td><td><pre>{
  "translate": "item.minecraft.bowl"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brain_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.brain_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brain_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.brain_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brain_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.brain_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bread
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bread"}</pre></td><td><pre>{
  "translate": "item.minecraft.bread"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.breeze_rod"}</pre></td><td><pre>{
  "translate": "item.minecraft.breeze_rod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.breeze_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.breeze_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.brewer_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.brewer_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewing_stand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brewing_stand"}</pre></td><td><pre>{
  "translate": "block.minecraft.brewing_stand"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.brick"}</pre></td><td><pre>{
  "translate": "item.minecraft.brick"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.brown_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.brown_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.brown_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.brown_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_mushroom"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_mushroom"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_mushroom_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_mushroom_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.brown_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.brown_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.brush"}</pre></td><td><pre>{
  "translate": "item.minecraft.brush"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bubble_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.bubble_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bubble_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.bubble_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.bubble_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.bubble_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
budding_amethyst
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.budding_amethyst"}</pre></td><td><pre>{
  "translate": "block.minecraft.budding_amethyst"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
burn_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.burn_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.burn_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cactus"}</pre></td><td><pre>{
  "translate": "block.minecraft.cactus"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cake
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cake"}</pre></td><td><pre>{
  "translate": "block.minecraft.cake"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calcite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.calcite"}</pre></td><td><pre>{
  "translate": "block.minecraft.calcite"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calibrated_sculk_sensor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.calibrated_sculk_sensor"}</pre></td><td><pre>{
  "translate": "block.minecraft.calibrated_sculk_sensor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
camel_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.camel_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.camel_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
campfire
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.campfire"}</pre></td><td><pre>{
  "translate": "block.minecraft.campfire"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.carrot"}</pre></td><td><pre>{
  "translate": "item.minecraft.carrot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot_on_a_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.carrot_on_a_stick"}</pre></td><td><pre>{
  "translate": "item.minecraft.carrot_on_a_stick"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cartography_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cartography_table"}</pre></td><td><pre>{
  "translate": "block.minecraft.cartography_table"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carved_pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.carved_pumpkin"}</pre></td><td><pre>{
  "translate": "block.minecraft.carved_pumpkin"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cat_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.cat_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cauldron
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cauldron"}</pre></td><td><pre>{
  "translate": "block.minecraft.cauldron"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cave_spider_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.cave_spider_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chain"}</pre></td><td><pre>{
  "translate": "block.minecraft.chain"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.chainmail_boots"}</pre></td><td><pre>{
  "translate": "item.minecraft.chainmail_boots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.chainmail_chestplate"}</pre></td><td><pre>{
  "translate": "item.minecraft.chainmail_chestplate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.chainmail_helmet"}</pre></td><td><pre>{
  "translate": "item.minecraft.chainmail_helmet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.chainmail_leggings"}</pre></td><td><pre>{
  "translate": "item.minecraft.chainmail_leggings"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain_command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chain_command_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.chain_command_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
charcoal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.charcoal"}</pre></td><td><pre>{
  "translate": "item.minecraft.charcoal"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cherry_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.cherry_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cherry_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.cherry_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_sapling"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_sapling"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cherry_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.cherry_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chest"}</pre></td><td><pre>{
  "translate": "block.minecraft.chest"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.chest_minecart"}</pre></td><td><pre>{
  "translate": "item.minecraft.chest_minecart"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.chicken"}</pre></td><td><pre>{
  "translate": "item.minecraft.chicken"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.chicken_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.chicken_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chipped_anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chipped_anvil"}</pre></td><td><pre>{
  "translate": "block.minecraft.chipped_anvil"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_bookshelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_bookshelf"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_bookshelf"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_deepslate"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_deepslate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_nether_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_nether_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_polished_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_polished_blackstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_polished_blackstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_quartz_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_quartz_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_quartz_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_red_sandstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_red_sandstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_resin_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_resin_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_resin_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_sandstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_sandstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_tuff"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_tuff"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chiseled_tuff_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.chiseled_tuff_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_flower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chorus_flower"}</pre></td><td><pre>{
  "translate": "block.minecraft.chorus_flower"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.chorus_fruit"}</pre></td><td><pre>{
  "translate": "item.minecraft.chorus_fruit"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_plant
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.chorus_plant"}</pre></td><td><pre>{
  "translate": "block.minecraft.chorus_plant"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.clay"}</pre></td><td><pre>{
  "translate": "block.minecraft.clay"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay_ball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.clay_ball"}</pre></td><td><pre>{
  "translate": "item.minecraft.clay_ball"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clock
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.clock"}</pre></td><td><pre>{
  "translate": "item.minecraft.clock"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
closed_eyeblossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.closed_eyeblossom"}</pre></td><td><pre>{
  "translate": "block.minecraft.closed_eyeblossom"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.coal"}</pre></td><td><pre>{
  "translate": "item.minecraft.coal"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.coal_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.coal_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.coal_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.coal_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coarse_dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.coarse_dirt"}</pre></td><td><pre>{
  "translate": "block.minecraft.coarse_dirt"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coast_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.coast_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.coast_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobbled_deepslate"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobbled_deepslate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobbled_deepslate_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobbled_deepslate_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobbled_deepslate_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobbled_deepslate_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobbled_deepslate_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobbled_deepslate_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobblestone"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobblestone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobblestone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobblestone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobblestone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobblestone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobblestone_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobblestone_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobweb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cobweb"}</pre></td><td><pre>{
  "translate": "block.minecraft.cobweb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cocoa_beans
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cocoa_beans"}</pre></td><td><pre>{
  "translate": "item.minecraft.cocoa_beans"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cod"}</pre></td><td><pre>{
  "translate": "item.minecraft.cod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cod_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.cod_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cod_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.cod_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.command_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.command_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.command_block_minecart"}</pre></td><td><pre>{
  "translate": "item.minecraft.command_block_minecart"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
comparator
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.comparator"}</pre></td><td><pre>{
  "translate": "block.minecraft.comparator"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.compass"}</pre></td><td><pre>{
  "translate": "item.minecraft.compass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
composter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.composter"}</pre></td><td><pre>{
  "translate": "block.minecraft.composter"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
conduit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.conduit"}</pre></td><td><pre>{
  "translate": "block.minecraft.conduit"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cooked_beef"}</pre></td><td><pre>{
  "translate": "item.minecraft.cooked_beef"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cooked_chicken"}</pre></td><td><pre>{
  "translate": "item.minecraft.cooked_chicken"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cooked_cod"}</pre></td><td><pre>{
  "translate": "item.minecraft.cooked_cod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cooked_mutton"}</pre></td><td><pre>{
  "translate": "item.minecraft.cooked_mutton"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cooked_porkchop"}</pre></td><td><pre>{
  "translate": "item.minecraft.cooked_porkchop"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cooked_rabbit"}</pre></td><td><pre>{
  "translate": "item.minecraft.cooked_rabbit"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cooked_salmon"}</pre></td><td><pre>{
  "translate": "item.minecraft.cooked_salmon"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cookie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cookie"}</pre></td><td><pre>{
  "translate": "item.minecraft.cookie"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.copper_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.copper_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.copper_bulb"}</pre></td><td><pre>{
  "translate": "block.minecraft.copper_bulb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.copper_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.copper_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.copper_grate"}</pre></td><td><pre>{
  "translate": "block.minecraft.copper_grate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.copper_ingot"}</pre></td><td><pre>{
  "translate": "item.minecraft.copper_ingot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.copper_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.copper_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.copper_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.copper_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cornflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cornflower"}</pre></td><td><pre>{
  "translate": "block.minecraft.cornflower"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cow_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cow_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.cow_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cracked_deepslate_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.cracked_deepslate_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_tiles
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cracked_deepslate_tiles"}</pre></td><td><pre>{
  "translate": "block.minecraft.cracked_deepslate_tiles"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cracked_nether_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.cracked_nether_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_polished_blackstone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cracked_polished_blackstone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.cracked_polished_blackstone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cracked_stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.cracked_stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crafter"}</pre></td><td><pre>{
  "translate": "block.minecraft.crafter"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafting_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crafting_table"}</pre></td><td><pre>{
  "translate": "block.minecraft.crafting_table"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_heart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.creaking_heart"}</pre></td><td><pre>{
  "translate": "block.minecraft.creaking_heart"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.creaking_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.creaking_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.creeper_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.creeper_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.creeper_head"}</pre></td><td><pre>{
  "translate": "block.minecraft.creeper_head"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.creeper_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.creeper_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fungus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_fungus"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_fungus"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_hyphae"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_hyphae"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_nylium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_nylium"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_nylium"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_roots"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_roots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_stem"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_stem"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crimson_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.crimson_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crossbow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.crossbow"}</pre></td><td><pre>{
  "translate": "item.minecraft.crossbow"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crying_obsidian
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.crying_obsidian"}</pre></td><td><pre>{
  "translate": "block.minecraft.crying_obsidian"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cut_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.cut_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cut_copper_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.cut_copper_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cut_copper_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.cut_copper_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cut_red_sandstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.cut_red_sandstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cut_red_sandstone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.cut_red_sandstone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cut_sandstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.cut_sandstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cut_sandstone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.cut_sandstone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cyan_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.cyan_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.cyan_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.cyan_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.cyan_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.cyan_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
damaged_anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.damaged_anvil"}</pre></td><td><pre>{
  "translate": "block.minecraft.damaged_anvil"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dandelion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dandelion"}</pre></td><td><pre>{
  "translate": "block.minecraft.dandelion"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
danger_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.danger_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.danger_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.dark_oak_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.dark_oak_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.dark_oak_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.dark_oak_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_sapling"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_sapling"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_oak_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_oak_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_prismarine"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_prismarine"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_prismarine_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_prismarine_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dark_prismarine_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.dark_prismarine_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
daylight_detector
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.daylight_detector"}</pre></td><td><pre>{
  "translate": "block.minecraft.daylight_detector"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_brain_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_brain_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_brain_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_brain_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_brain_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_brain_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_bubble_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_bubble_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_bubble_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_bubble_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_bubble_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_bubble_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_bush"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_bush"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_fire_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_fire_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_fire_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_fire_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_fire_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_fire_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_horn_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_horn_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_horn_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_horn_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_horn_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_horn_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_tube_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_tube_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_tube_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_tube_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dead_tube_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.dead_tube_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
debug_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.debug_stick"}</pre></td><td><pre>{
  "translate": "item.minecraft.debug_stick"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
decorated_pot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.decorated_pot"}</pre></td><td><pre>{
  "translate": "block.minecraft.decorated_pot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_coal_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_coal_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_coal_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_copper_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_copper_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_copper_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_diamond_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_diamond_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_diamond_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_emerald_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_emerald_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_emerald_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_gold_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_gold_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_iron_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_iron_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_iron_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_lapis_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_lapis_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_lapis_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_redstone_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_redstone_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_redstone_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tiles
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_tiles"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_tiles"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_tile_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_tile_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_tile_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_tile_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.deepslate_tile_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.deepslate_tile_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
detector_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.detector_rail"}</pre></td><td><pre>{
  "translate": "block.minecraft.detector_rail"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "can_disable_blocking": true,
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_axe"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_axe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.diamond_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.diamond_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_boots"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_boots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_chestplate"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_chestplate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_helmet"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_helmet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_hoe"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_hoe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_horse_armor"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_horse_armor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_leggings"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_leggings"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.diamond_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.diamond_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_pickaxe"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_pickaxe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_shovel"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_shovel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.diamond_sword"}</pre></td><td><pre>{
  "translate": "item.minecraft.diamond_sword"
}</pre></td></tr><tr><td>minecraft:tool</td><td><pre>{
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td><td><pre>{
  "can_destroy_blocks_in_creative": false,
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_instantly_mines",
      "speed": 3.4028235e+38
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.diorite"}</pre></td><td><pre>{
  "translate": "block.minecraft.diorite"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.diorite_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.diorite_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.diorite_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.diorite_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.diorite_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.diorite_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dirt"}</pre></td><td><pre>{
  "translate": "block.minecraft.dirt"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt_path
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dirt_path"}</pre></td><td><pre>{
  "translate": "block.minecraft.dirt_path"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
disc_fragment_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.disc_fragment_5"}</pre></td><td><pre>{
  "translate": "item.minecraft.disc_fragment_5"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dispenser
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dispenser"}</pre></td><td><pre>{
  "translate": "block.minecraft.dispenser"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dolphin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.dolphin_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.dolphin_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
donkey_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.donkey_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.donkey_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_breath
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.dragon_breath"}</pre></td><td><pre>{
  "translate": "item.minecraft.dragon_breath"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dragon_egg"}</pre></td><td><pre>{
  "translate": "block.minecraft.dragon_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dragon_head"}</pre></td><td><pre>{
  "translate": "block.minecraft.dragon_head"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.dried_kelp"}</pre></td><td><pre>{
  "translate": "item.minecraft.dried_kelp"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dried_kelp_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.dried_kelp_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dripstone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dripstone_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.dripstone_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dropper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.dropper"}</pre></td><td><pre>{
  "translate": "block.minecraft.dropper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
drowned_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.drowned_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.drowned_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dune_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.dune_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.dune_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
echo_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.echo_shard"}</pre></td><td><pre>{
  "translate": "item.minecraft.echo_shard"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elder_guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.elder_guardian_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.elder_guardian_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elytra
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.elytra"}</pre></td><td><pre>{
  "translate": "item.minecraft.elytra"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.emerald"}</pre></td><td><pre>{
  "translate": "item.minecraft.emerald"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.emerald_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.emerald_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.emerald_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.emerald_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.enchanted_book"}</pre></td><td><pre>{
  "translate": "item.minecraft.enchanted_book"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.enchanted_golden_apple"}</pre></td><td><pre>{
  "translate": "item.minecraft.enchanted_golden_apple"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanting_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.enchanting_table"}</pre></td><td><pre>{
  "translate": "block.minecraft.enchanting_table"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enderman_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.enderman_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.enderman_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
endermite_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.endermite_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.endermite_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.ender_chest"}</pre></td><td><pre>{
  "translate": "block.minecraft.ender_chest"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_dragon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ender_dragon_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.ender_dragon_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ender_eye"}</pre></td><td><pre>{
  "translate": "item.minecraft.ender_eye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_pearl
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ender_pearl"}</pre></td><td><pre>{
  "translate": "item.minecraft.ender_pearl"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_crystal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.end_crystal"}</pre></td><td><pre>{
  "translate": "item.minecraft.end_crystal"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_portal_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.end_portal_frame"}</pre></td><td><pre>{
  "translate": "block.minecraft.end_portal_frame"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.end_rod"}</pre></td><td><pre>{
  "translate": "block.minecraft.end_rod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.end_stone"}</pre></td><td><pre>{
  "translate": "block.minecraft.end_stone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.end_stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.end_stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.end_stone_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.end_stone_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.end_stone_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.end_stone_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.end_stone_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.end_stone_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
evoker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.evoker_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.evoker_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
experience_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.experience_bottle"}</pre></td><td><pre>{
  "translate": "item.minecraft.experience_bottle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
explorer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.explorer_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.explorer_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_chiseled_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_chiseled_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_copper_bulb"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_copper_bulb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_copper_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_copper_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_copper_grate"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_copper_grate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_copper_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_copper_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_cut_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_cut_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_cut_copper_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_cut_copper_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.exposed_cut_copper_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.exposed_cut_copper_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
eye_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.eye_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.eye_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
farmland
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.farmland"}</pre></td><td><pre>{
  "translate": "block.minecraft.farmland"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
feather
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.feather"}</pre></td><td><pre>{
  "translate": "item.minecraft.feather"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fermented_spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.fermented_spider_eye"}</pre></td><td><pre>{
  "translate": "item.minecraft.fermented_spider_eye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.fern"}</pre></td><td><pre>{
  "translate": "block.minecraft.fern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
field_masoned_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.field_masoned_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.field_masoned_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
filled_map
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.filled_map"}</pre></td><td><pre>{
  "translate": "item.minecraft.filled_map"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firework_rocket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.firework_rocket"}</pre></td><td><pre>{
  "translate": "item.minecraft.firework_rocket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firework_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.firework_star"}</pre></td><td><pre>{
  "translate": "item.minecraft.firework_star"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_charge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.fire_charge"}</pre></td><td><pre>{
  "translate": "item.minecraft.fire_charge"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.fire_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.fire_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.fire_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.fire_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.fire_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.fire_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fishing_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.fishing_rod"}</pre></td><td><pre>{
  "translate": "item.minecraft.fishing_rod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fletching_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.fletching_table"}</pre></td><td><pre>{
  "translate": "block.minecraft.fletching_table"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flint
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.flint"}</pre></td><td><pre>{
  "translate": "item.minecraft.flint"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flint_and_steel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.flint_and_steel"}</pre></td><td><pre>{
  "translate": "item.minecraft.flint_and_steel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.flowering_azalea"}</pre></td><td><pre>{
  "translate": "block.minecraft.flowering_azalea"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.flowering_azalea_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.flowering_azalea_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.flower_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.flower_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_pot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.flower_pot"}</pre></td><td><pre>{
  "translate": "block.minecraft.flower_pot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.flow_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.flow_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.flow_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.flow_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.flow_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.flow_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fox_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.fox_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.fox_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
friend_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.friend_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.friend_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frogspawn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.frogspawn"}</pre></td><td><pre>{
  "translate": "block.minecraft.frogspawn"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frog_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.frog_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.frog_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.furnace"}</pre></td><td><pre>{
  "translate": "block.minecraft.furnace"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.furnace_minecart"}</pre></td><td><pre>{
  "translate": "item.minecraft.furnace_minecart"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ghast_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.ghast_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_tear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ghast_tear"}</pre></td><td><pre>{
  "translate": "item.minecraft.ghast_tear"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gilded_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gilded_blackstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.gilded_blackstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.glass_bottle"}</pre></td><td><pre>{
  "translate": "item.minecraft.glass_bottle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glistering_melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.glistering_melon_slice"}</pre></td><td><pre>{
  "translate": "item.minecraft.glistering_melon_slice"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
globe_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.globe_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.globe_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.glowstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.glowstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone_dust
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.glowstone_dust"}</pre></td><td><pre>{
  "translate": "item.minecraft.glowstone_dust"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.glow_berries"}</pre></td><td><pre>{
  "translate": "item.minecraft.glow_berries"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_ink_sac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.glow_ink_sac"}</pre></td><td><pre>{
  "translate": "item.minecraft.glow_ink_sac"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_item_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.glow_item_frame"}</pre></td><td><pre>{
  "translate": "item.minecraft.glow_item_frame"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_lichen
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.glow_lichen"}</pre></td><td><pre>{
  "translate": "block.minecraft.glow_lichen"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.glow_squid_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.glow_squid_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_horn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.goat_horn"}</pre></td><td><pre>{
  "translate": "item.minecraft.goat_horn"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.goat_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.goat_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_apple"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_apple"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "can_disable_blocking": true,
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_axe"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_axe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_boots"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_boots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_carrot"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_carrot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_chestplate"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_chestplate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_helmet"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_helmet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_hoe"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_hoe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_horse_armor"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_horse_armor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_leggings"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_leggings"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_pickaxe"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_pickaxe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_shovel"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_shovel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.golden_sword"}</pre></td><td><pre>{
  "translate": "item.minecraft.golden_sword"
}</pre></td></tr><tr><td>minecraft:tool</td><td><pre>{
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td><td><pre>{
  "can_destroy_blocks_in_creative": false,
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_instantly_mines",
      "speed": 3.4028235e+38
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gold_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.gold_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.gold_ingot"}</pre></td><td><pre>{
  "translate": "item.minecraft.gold_ingot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.gold_nugget"}</pre></td><td><pre>{
  "translate": "item.minecraft.gold_nugget"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gold_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.gold_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.granite"}</pre></td><td><pre>{
  "translate": "block.minecraft.granite"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.granite_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.granite_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.granite_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.granite_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.granite_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.granite_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grass_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.grass_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.grass_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gravel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gravel"}</pre></td><td><pre>{
  "translate": "block.minecraft.gravel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.gray_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.gray_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.gray_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.gray_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.gray_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.gray_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.green_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.green_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.green_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.green_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.green_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.green_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grindstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.grindstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.grindstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.guardian_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.guardian_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gunpowder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.gunpowder"}</pre></td><td><pre>{
  "translate": "item.minecraft.gunpowder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.guster_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.guster_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.guster_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.guster_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hanging_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.hanging_roots"}</pre></td><td><pre>{
  "translate": "block.minecraft.hanging_roots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hay_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.hay_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.hay_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heartbreak_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.heartbreak_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.heartbreak_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_of_the_sea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.heart_of_the_sea"}</pre></td><td><pre>{
  "translate": "item.minecraft.heart_of_the_sea"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.heart_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.heart_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_core
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.heavy_core"}</pre></td><td><pre>{
  "translate": "block.minecraft.heavy_core"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_weighted_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.heavy_weighted_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.heavy_weighted_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.hoglin_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.hoglin_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.honeycomb"}</pre></td><td><pre>{
  "translate": "item.minecraft.honeycomb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.honeycomb_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.honeycomb_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.honey_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.honey_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.honey_bottle"}</pre></td><td><pre>{
  "translate": "item.minecraft.honey_bottle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.hopper"}</pre></td><td><pre>{
  "translate": "block.minecraft.hopper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.hopper_minecart"}</pre></td><td><pre>{
  "translate": "item.minecraft.hopper_minecart"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.horn_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.horn_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.horn_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.horn_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.horn_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.horn_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.horse_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.horse_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
host_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.host_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.host_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
howl_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.howl_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.howl_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
husk_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.husk_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.husk_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.ice"}</pre></td><td><pre>{
  "translate": "block.minecraft.ice"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_chiseled_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.infested_chiseled_stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.infested_chiseled_stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.infested_cobblestone"}</pre></td><td><pre>{
  "translate": "block.minecraft.infested_cobblestone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cracked_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.infested_cracked_stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.infested_cracked_stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.infested_deepslate"}</pre></td><td><pre>{
  "translate": "block.minecraft.infested_deepslate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_mossy_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.infested_mossy_stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.infested_mossy_stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.infested_stone"}</pre></td><td><pre>{
  "translate": "block.minecraft.infested_stone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.infested_stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.infested_stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ink_sac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ink_sac"}</pre></td><td><pre>{
  "translate": "item.minecraft.ink_sac"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "can_disable_blocking": true,
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_axe"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_axe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.iron_bars"}</pre></td><td><pre>{
  "translate": "block.minecraft.iron_bars"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.iron_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.iron_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_boots"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_boots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_chestplate"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_chestplate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.iron_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.iron_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_golem_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_golem_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_helmet"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_helmet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_hoe"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_hoe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_horse_armor"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_horse_armor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_ingot"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_ingot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_leggings"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_leggings"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_nugget"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_nugget"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.iron_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.iron_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_pickaxe"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_pickaxe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_shovel"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_shovel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.iron_sword"}</pre></td><td><pre>{
  "translate": "item.minecraft.iron_sword"
}</pre></td></tr><tr><td>minecraft:tool</td><td><pre>{
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td><td><pre>{
  "can_destroy_blocks_in_creative": false,
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_instantly_mines",
      "speed": 3.4028235e+38
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.iron_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.iron_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
item_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.item_frame"}</pre></td><td><pre>{
  "translate": "item.minecraft.item_frame"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jack_o_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jack_o_lantern"}</pre></td><td><pre>{
  "translate": "block.minecraft.jack_o_lantern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jigsaw
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jigsaw"}</pre></td><td><pre>{
  "translate": "block.minecraft.jigsaw"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jukebox
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jukebox"}</pre></td><td><pre>{
  "translate": "block.minecraft.jukebox"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.jungle_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.jungle_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.jungle_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.jungle_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_sapling"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_sapling"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.jungle_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.jungle_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.kelp"}</pre></td><td><pre>{
  "translate": "block.minecraft.kelp"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
knowledge_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.knowledge_book"}</pre></td><td><pre>{
  "translate": "item.minecraft.knowledge_book"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ladder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.ladder"}</pre></td><td><pre>{
  "translate": "block.minecraft.ladder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lantern"}</pre></td><td><pre>{
  "translate": "block.minecraft.lantern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lapis_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.lapis_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_lazuli
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.lapis_lazuli"}</pre></td><td><pre>{
  "translate": "item.minecraft.lapis_lazuli"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lapis_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.lapis_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.large_amethyst_bud"}</pre></td><td><pre>{
  "translate": "block.minecraft.large_amethyst_bud"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_fern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.large_fern"}</pre></td><td><pre>{
  "translate": "block.minecraft.large_fern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lava_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.lava_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.lava_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lead
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.lead"}</pre></td><td><pre>{
  "translate": "item.minecraft.lead"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.leather"}</pre></td><td><pre>{
  "translate": "item.minecraft.leather"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.leather_boots"}</pre></td><td><pre>{
  "translate": "item.minecraft.leather_boots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.leather_chestplate"}</pre></td><td><pre>{
  "translate": "item.minecraft.leather_chestplate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.leather_helmet"}</pre></td><td><pre>{
  "translate": "item.minecraft.leather_helmet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.leather_horse_armor"}</pre></td><td><pre>{
  "translate": "item.minecraft.leather_horse_armor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.leather_leggings"}</pre></td><td><pre>{
  "translate": "item.minecraft.leather_leggings"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lectern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lectern"}</pre></td><td><pre>{
  "translate": "block.minecraft.lectern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lever
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lever"}</pre></td><td><pre>{
  "translate": "block.minecraft.lever"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light"}</pre></td><td><pre>{
  "translate": "block.minecraft.light"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lightning_rod"}</pre></td><td><pre>{
  "translate": "block.minecraft.lightning_rod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.light_blue_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.light_blue_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.light_blue_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.light_blue_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_blue_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_blue_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.light_gray_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.light_gray_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.light_gray_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.light_gray_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_gray_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_gray_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_weighted_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.light_weighted_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.light_weighted_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lilac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lilac"}</pre></td><td><pre>{
  "translate": "block.minecraft.lilac"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_of_the_valley
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lily_of_the_valley"}</pre></td><td><pre>{
  "translate": "block.minecraft.lily_of_the_valley"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_pad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lily_pad"}</pre></td><td><pre>{
  "translate": "block.minecraft.lily_pad"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.lime_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.lime_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.lime_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.lime_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lime_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.lime_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lingering_potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:potion_duration_scale</td><td><pre>/</pre></td><td><pre>0.25</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.lingering_potion"}</pre></td><td><pre>{
  "translate": "item.minecraft.lingering_potion"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.llama_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.llama_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lodestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.lodestone"}</pre></td><td><pre>{
  "translate": "block.minecraft.lodestone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
loom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.loom"}</pre></td><td><pre>{
  "translate": "block.minecraft.loom"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mace"}</pre></td><td><pre>{
  "translate": "item.minecraft.mace"
}</pre></td></tr><tr><td>minecraft:tool</td><td><pre>{
  "damage_per_block": 2,
  "rules": []
}</pre></td><td><pre>{
  "can_destroy_blocks_in_creative": false,
  "damage_per_block": 2,
  "rules": []
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.magenta_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.magenta_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.magenta_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.magenta_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magenta_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.magenta_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.magma_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.magma_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cream
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.magma_cream"}</pre></td><td><pre>{
  "translate": "item.minecraft.magma_cream"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cube_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.magma_cube_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.magma_cube_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mangrove_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.mangrove_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mangrove_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.mangrove_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_propagule
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_propagule"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_propagule"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_roots"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_roots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mangrove_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.mangrove_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
map
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.map"}</pre></td><td><pre>{
  "translate": "item.minecraft.map"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
medium_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.medium_amethyst_bud"}</pre></td><td><pre>{
  "translate": "block.minecraft.medium_amethyst_bud"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.melon"}</pre></td><td><pre>{
  "translate": "block.minecraft.melon"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.melon_seeds"}</pre></td><td><pre>{
  "translate": "item.minecraft.melon_seeds"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.melon_slice"}</pre></td><td><pre>{
  "translate": "item.minecraft.melon_slice"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
milk_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.milk_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.milk_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.minecart"}</pre></td><td><pre>{
  "translate": "item.minecraft.minecart"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
miner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.miner_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.miner_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mojang_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mojang_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.mojang_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mooshroom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mooshroom_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.mooshroom_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mossy_cobblestone"}</pre></td><td><pre>{
  "translate": "block.minecraft.mossy_cobblestone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mossy_cobblestone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.mossy_cobblestone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mossy_cobblestone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.mossy_cobblestone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mossy_cobblestone_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.mossy_cobblestone_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mossy_stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.mossy_stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mossy_stone_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.mossy_stone_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mossy_stone_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.mossy_stone_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mossy_stone_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.mossy_stone_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.moss_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.moss_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.moss_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.moss_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mourner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mourner_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.mourner_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mud"}</pre></td><td><pre>{
  "translate": "block.minecraft.mud"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
muddy_mangrove_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.muddy_mangrove_roots"}</pre></td><td><pre>{
  "translate": "block.minecraft.muddy_mangrove_roots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mud_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.mud_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mud_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.mud_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mud_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.mud_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mud_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.mud_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mule_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mule_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.mule_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mushroom_stem"}</pre></td><td><pre>{
  "translate": "block.minecraft.mushroom_stem"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mushroom_stew"}</pre></td><td><pre>{
  "translate": "item.minecraft.mushroom_stew"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_11
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_11"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_11"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_13
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_13"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_13"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_5"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_5"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_blocks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_blocks"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_blocks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_cat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_cat"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_cat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_chirp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_chirp"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_chirp"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_creator"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_creator"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator_music_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_creator_music_box"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_creator_music_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_far
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_far"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_far"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_mall"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_mall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mellohi
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_mellohi"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_mellohi"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_otherside
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_otherside"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_otherside"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_pigstep
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_pigstep"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_pigstep"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_precipice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_precipice"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_precipice"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_relic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_relic"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_relic"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_stal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_stal"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_stal"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_strad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_strad"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_strad"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_wait
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_wait"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_wait"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_ward
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.music_disc_ward"}</pre></td><td><pre>{
  "translate": "item.minecraft.music_disc_ward"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.mutton"}</pre></td><td><pre>{
  "translate": "item.minecraft.mutton"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mycelium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.mycelium"}</pre></td><td><pre>{
  "translate": "block.minecraft.mycelium"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
name_tag
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.name_tag"}</pre></td><td><pre>{
  "translate": "item.minecraft.name_tag"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nautilus_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.nautilus_shell"}</pre></td><td><pre>{
  "translate": "item.minecraft.nautilus_shell"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "can_disable_blocking": true,
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_axe"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_axe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.netherite_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.netherite_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_boots"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_boots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_chestplate"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_chestplate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_helmet"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_helmet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_hoe"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_hoe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_ingot"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_ingot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_leggings"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_leggings"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_pickaxe"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_pickaxe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_scrap
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_scrap"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_scrap"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_shovel"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_shovel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_sword"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_sword"
}</pre></td></tr><tr><td>minecraft:tool</td><td><pre>{
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td><td><pre>{
  "can_destroy_blocks_in_creative": false,
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_instantly_mines",
      "speed": 3.4028235e+38
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_upgrade_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.netherite_upgrade_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.netherite_upgrade_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherrack
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.netherrack"}</pre></td><td><pre>{
  "translate": "block.minecraft.netherrack"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.nether_brick"}</pre></td><td><pre>{
  "translate": "item.minecraft.nether_brick"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_brick_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_brick_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_gold_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_gold_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_quartz_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_quartz_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_quartz_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_sprouts
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_sprouts"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_sprouts"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.nether_star"}</pre></td><td><pre>{
  "translate": "item.minecraft.nether_star"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.nether_wart"}</pre></td><td><pre>{
  "translate": "item.minecraft.nether_wart"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.nether_wart_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.nether_wart_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
note_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.note_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.note_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.oak_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.oak_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.oak_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.oak_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_sapling"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_sapling"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oak_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.oak_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
observer
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.observer"}</pre></td><td><pre>{
  "translate": "block.minecraft.observer"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
obsidian
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.obsidian"}</pre></td><td><pre>{
  "translate": "block.minecraft.obsidian"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ocelot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ocelot_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.ocelot_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ochre_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.ochre_froglight"}</pre></td><td><pre>{
  "translate": "block.minecraft.ochre_froglight"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ominous_bottle"}</pre></td><td><pre>{
  "translate": "item.minecraft.ominous_bottle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_trial_key
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ominous_trial_key"}</pre></td><td><pre>{
  "translate": "item.minecraft.ominous_trial_key"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
open_eyeblossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.open_eyeblossom"}</pre></td><td><pre>{
  "translate": "block.minecraft.open_eyeblossom"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.orange_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.orange_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.orange_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.orange_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_tulip"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_tulip"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.orange_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.orange_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxeye_daisy
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxeye_daisy"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxeye_daisy"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_chiseled_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_chiseled_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_copper_bulb"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_copper_bulb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_copper_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_copper_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_copper_grate"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_copper_grate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_copper_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_copper_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_cut_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_cut_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_cut_copper_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_cut_copper_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.oxidized_cut_copper_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.oxidized_cut_copper_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.packed_ice"}</pre></td><td><pre>{
  "translate": "block.minecraft.packed_ice"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_mud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.packed_mud"}</pre></td><td><pre>{
  "translate": "block.minecraft.packed_mud"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
painting
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.painting"}</pre></td><td><pre>{
  "translate": "item.minecraft.painting"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_hanging_moss
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_hanging_moss"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_hanging_moss"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_moss_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_moss_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_moss_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_moss_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pale_oak_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.pale_oak_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pale_oak_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.pale_oak_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_sapling"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_sapling"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pale_oak_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.pale_oak_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
panda_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.panda_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.panda_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
paper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.paper"}</pre></td><td><pre>{
  "translate": "item.minecraft.paper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
parrot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.parrot_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.parrot_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pearlescent_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pearlescent_froglight"}</pre></td><td><pre>{
  "translate": "block.minecraft.pearlescent_froglight"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
peony
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.peony"}</pre></td><td><pre>{
  "translate": "block.minecraft.peony"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
petrified_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.petrified_oak_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.petrified_oak_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_membrane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.phantom_membrane"}</pre></td><td><pre>{
  "translate": "item.minecraft.phantom_membrane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.phantom_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.phantom_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.piglin_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.piglin_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_brute_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.piglin_brute_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.piglin_brute_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.piglin_head"}</pre></td><td><pre>{
  "translate": "block.minecraft.piglin_head"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.piglin_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.piglin_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pig_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pig_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.pig_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pillager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pillager_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.pillager_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pink_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.pink_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pink_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.pink_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_petals
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_petals"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_petals"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_tulip"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_tulip"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pink_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.pink_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piston
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.piston"}</pre></td><td><pre>{
  "translate": "block.minecraft.piston"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_plant
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pitcher_plant"}</pre></td><td><pre>{
  "translate": "block.minecraft.pitcher_plant"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_pod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pitcher_pod"}</pre></td><td><pre>{
  "translate": "item.minecraft.pitcher_pod"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
player_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.player_head"}</pre></td><td><pre>{
  "translate": "block.minecraft.player_head"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
plenty_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.plenty_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.plenty_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
podzol
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.podzol"}</pre></td><td><pre>{
  "translate": "block.minecraft.podzol"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pointed_dripstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pointed_dripstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.pointed_dripstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poisonous_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.poisonous_potato"}</pre></td><td><pre>{
  "translate": "item.minecraft.poisonous_potato"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polar_bear_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.polar_bear_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.polar_bear_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_andesite"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_andesite"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_andesite_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_andesite_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_andesite_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_andesite_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_basalt"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_basalt"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_blackstone_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_blackstone_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_deepslate"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_deepslate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_deepslate_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_deepslate_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_deepslate_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_deepslate_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_deepslate_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_deepslate_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_diorite"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_diorite"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_diorite_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_diorite_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_diorite_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_diorite_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_granite"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_granite"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_granite_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_granite_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_granite_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_granite_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_tuff"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_tuff"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_tuff_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_tuff_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_tuff_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_tuff_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.polished_tuff_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.polished_tuff_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
popped_chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.popped_chorus_fruit"}</pre></td><td><pre>{
  "translate": "item.minecraft.popped_chorus_fruit"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poppy
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.poppy"}</pre></td><td><pre>{
  "translate": "block.minecraft.poppy"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.porkchop"}</pre></td><td><pre>{
  "translate": "item.minecraft.porkchop"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.potato"}</pre></td><td><pre>{
  "translate": "item.minecraft.potato"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.potion"}</pre></td><td><pre>{
  "translate": "item.minecraft.potion"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powder_snow_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.powder_snow_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.powder_snow_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powered_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.powered_rail"}</pre></td><td><pre>{
  "translate": "block.minecraft.powered_rail"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.prismarine"}</pre></td><td><pre>{
  "translate": "block.minecraft.prismarine"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.prismarine_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.prismarine_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.prismarine_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.prismarine_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.prismarine_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.prismarine_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_crystals
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.prismarine_crystals"}</pre></td><td><pre>{
  "translate": "item.minecraft.prismarine_crystals"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.prismarine_shard"}</pre></td><td><pre>{
  "translate": "item.minecraft.prismarine_shard"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.prismarine_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.prismarine_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.prismarine_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.prismarine_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.prismarine_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.prismarine_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prize_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.prize_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.prize_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pufferfish"}</pre></td><td><pre>{
  "translate": "item.minecraft.pufferfish"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pufferfish_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.pufferfish_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pufferfish_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.pufferfish_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.pumpkin"}</pre></td><td><pre>{
  "translate": "block.minecraft.pumpkin"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_pie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pumpkin_pie"}</pre></td><td><pre>{
  "translate": "item.minecraft.pumpkin_pie"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.pumpkin_seeds"}</pre></td><td><pre>{
  "translate": "item.minecraft.pumpkin_seeds"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.purple_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.purple_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.purple_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.purple_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purple_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.purple_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purpur_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.purpur_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_pillar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purpur_pillar"}</pre></td><td><pre>{
  "translate": "block.minecraft.purpur_pillar"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purpur_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.purpur_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.purpur_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.purpur_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.quartz"}</pre></td><td><pre>{
  "translate": "item.minecraft.quartz"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.quartz_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.quartz_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.quartz_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.quartz_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_pillar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.quartz_pillar"}</pre></td><td><pre>{
  "translate": "block.minecraft.quartz_pillar"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.quartz_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.quartz_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.quartz_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.quartz_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.rabbit"}</pre></td><td><pre>{
  "translate": "item.minecraft.rabbit"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_foot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.rabbit_foot"}</pre></td><td><pre>{
  "translate": "item.minecraft.rabbit_foot"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_hide
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.rabbit_hide"}</pre></td><td><pre>{
  "translate": "item.minecraft.rabbit_hide"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.rabbit_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.rabbit_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.rabbit_stew"}</pre></td><td><pre>{
  "translate": "item.minecraft.rabbit_stew"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.rail"}</pre></td><td><pre>{
  "translate": "block.minecraft.rail"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raiser_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.raiser_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.raiser_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ravager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ravager_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.ravager_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.raw_copper"}</pre></td><td><pre>{
  "translate": "item.minecraft.raw_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.raw_copper_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.raw_copper_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.raw_gold"}</pre></td><td><pre>{
  "translate": "item.minecraft.raw_gold"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.raw_gold_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.raw_gold_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.raw_iron"}</pre></td><td><pre>{
  "translate": "item.minecraft.raw_iron"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.raw_iron_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.raw_iron_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
recovery_compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.recovery_compass"}</pre></td><td><pre>{
  "translate": "item.minecraft.recovery_compass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.redstone"}</pre></td><td><pre>{
  "translate": "item.minecraft.redstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.redstone_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.redstone_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_lamp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.redstone_lamp"}</pre></td><td><pre>{
  "translate": "block.minecraft.redstone_lamp"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.redstone_ore"}</pre></td><td><pre>{
  "translate": "block.minecraft.redstone_ore"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.redstone_torch"}</pre></td><td><pre>{
  "translate": "block.minecraft.redstone_torch"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.red_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.red_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.red_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.red_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_mushroom"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_mushroom"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_mushroom_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_mushroom_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_nether_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_nether_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_nether_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_nether_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_nether_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_nether_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_nether_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_nether_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_sand"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_sand"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_sandstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_sandstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_sandstone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_sandstone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_sandstone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_sandstone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_sandstone_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_sandstone_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_tulip"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_tulip"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.red_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.red_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
reinforced_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.reinforced_deepslate"}</pre></td><td><pre>{
  "translate": "block.minecraft.reinforced_deepslate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeater
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.repeater"}</pre></td><td><pre>{
  "translate": "block.minecraft.repeater"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeating_command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.repeating_command_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.repeating_command_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.resin_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.resin_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.resin_brick"}</pre></td><td><pre>{
  "translate": "item.minecraft.resin_brick"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.resin_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.resin_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.resin_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.resin_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.resin_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.resin_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.resin_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.resin_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_clump
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.resin_clump"}</pre></td><td><pre>{
  "translate": "item.minecraft.resin_clump"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
respawn_anchor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.respawn_anchor"}</pre></td><td><pre>{
  "translate": "block.minecraft.respawn_anchor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rib_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.rib_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.rib_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rooted_dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.rooted_dirt"}</pre></td><td><pre>{
  "translate": "block.minecraft.rooted_dirt"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rose_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.rose_bush"}</pre></td><td><pre>{
  "translate": "block.minecraft.rose_bush"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rotten_flesh
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.rotten_flesh"}</pre></td><td><pre>{
  "translate": "item.minecraft.rotten_flesh"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
saddle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.saddle"}</pre></td><td><pre>{
  "translate": "item.minecraft.saddle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.salmon"}</pre></td><td><pre>{
  "translate": "item.minecraft.salmon"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.salmon_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.salmon_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.salmon_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.salmon_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sand"}</pre></td><td><pre>{
  "translate": "block.minecraft.sand"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sandstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.sandstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sandstone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.sandstone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sandstone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.sandstone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sandstone_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.sandstone_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scaffolding
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.scaffolding"}</pre></td><td><pre>{
  "translate": "block.minecraft.scaffolding"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scrape_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.scrape_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.scrape_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sculk"}</pre></td><td><pre>{
  "translate": "block.minecraft.sculk"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_catalyst
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sculk_catalyst"}</pre></td><td><pre>{
  "translate": "block.minecraft.sculk_catalyst"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_sensor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sculk_sensor"}</pre></td><td><pre>{
  "translate": "block.minecraft.sculk_sensor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_shrieker
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sculk_shrieker"}</pre></td><td><pre>{
  "translate": "block.minecraft.sculk_shrieker"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_vein
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sculk_vein"}</pre></td><td><pre>{
  "translate": "block.minecraft.sculk_vein"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
seagrass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.seagrass"}</pre></td><td><pre>{
  "translate": "block.minecraft.seagrass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sea_lantern"}</pre></td><td><pre>{
  "translate": "block.minecraft.sea_lantern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_pickle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sea_pickle"}</pre></td><td><pre>{
  "translate": "block.minecraft.sea_pickle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sentry_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.sentry_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.sentry_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shaper_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.shaper_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.shaper_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheaf_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.sheaf_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.sheaf_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shears
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.shears"}</pre></td><td><pre>{
  "translate": "item.minecraft.shears"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheep_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.sheep_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.sheep_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shelter_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.shelter_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.shelter_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shield
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.shield"}</pre></td><td><pre>{
  "translate": "item.minecraft.shield"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.short_grass"}</pre></td><td><pre>{
  "translate": "block.minecraft.short_grass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shroomlight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.shroomlight"}</pre></td><td><pre>{
  "translate": "block.minecraft.shroomlight"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.shulker_shell"}</pre></td><td><pre>{
  "translate": "item.minecraft.shulker_shell"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.shulker_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.shulker_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silence_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.silence_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.silence_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silverfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.silverfish_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.silverfish_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.skeleton_horse_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.skeleton_horse_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.skeleton_skull"}</pre></td><td><pre>{
  "translate": "block.minecraft.skeleton_skull"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.skeleton_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.skeleton_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.skull_banner_pattern"}</pre></td><td><pre>{
  "translate": "item.minecraft.skull_banner_pattern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.skull_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.skull_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_ball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.slime_ball"}</pre></td><td><pre>{
  "translate": "item.minecraft.slime_ball"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.slime_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.slime_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.slime_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.slime_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.small_amethyst_bud"}</pre></td><td><pre>{
  "translate": "block.minecraft.small_amethyst_bud"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_dripleaf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.small_dripleaf"}</pre></td><td><pre>{
  "translate": "block.minecraft.small_dripleaf"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smithing_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smithing_table"}</pre></td><td><pre>{
  "translate": "block.minecraft.smithing_table"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smoker
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smoker"}</pre></td><td><pre>{
  "translate": "block.minecraft.smoker"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_basalt"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_basalt"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_quartz"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_quartz"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_quartz_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_quartz_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_quartz_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_quartz_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_red_sandstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_red_sandstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_red_sandstone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_red_sandstone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_red_sandstone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_red_sandstone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_sandstone"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_sandstone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_sandstone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_sandstone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_sandstone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_sandstone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_stone"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_stone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.smooth_stone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.smooth_stone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sniffer_egg"}</pre></td><td><pre>{
  "translate": "block.minecraft.sniffer_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.sniffer_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.sniffer_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snort_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.snort_pottery_sherd"}</pre></td><td><pre>{
  "translate": "item.minecraft.snort_pottery_sherd"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snout_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.snout_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.snout_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.snow"}</pre></td><td><pre>{
  "translate": "block.minecraft.snow"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snowball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.snowball"}</pre></td><td><pre>{
  "translate": "item.minecraft.snowball"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.snow_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.snow_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.snow_golem_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.snow_golem_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_campfire
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.soul_campfire"}</pre></td><td><pre>{
  "translate": "block.minecraft.soul_campfire"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.soul_lantern"}</pre></td><td><pre>{
  "translate": "block.minecraft.soul_lantern"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.soul_sand"}</pre></td><td><pre>{
  "translate": "block.minecraft.soul_sand"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_soil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.soul_soil"}</pre></td><td><pre>{
  "translate": "block.minecraft.soul_soil"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.soul_torch"}</pre></td><td><pre>{
  "translate": "block.minecraft.soul_torch"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spawner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spawner"}</pre></td><td><pre>{
  "translate": "block.minecraft.spawner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spectral_arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.spectral_arrow"}</pre></td><td><pre>{
  "translate": "item.minecraft.spectral_arrow"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.spider_eye"}</pre></td><td><pre>{
  "translate": "item.minecraft.spider_eye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.spider_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.spider_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spire_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.spire_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.spire_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
splash_potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.splash_potion"}</pre></td><td><pre>{
  "translate": "item.minecraft.splash_potion"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sponge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sponge"}</pre></td><td><pre>{
  "translate": "block.minecraft.sponge"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spore_blossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spore_blossom"}</pre></td><td><pre>{
  "translate": "block.minecraft.spore_blossom"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.spruce_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.spruce_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.spruce_chest_boat"}</pre></td><td><pre>{
  "translate": "item.minecraft.spruce_chest_boat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_leaves"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_leaves"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_sapling"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_sapling"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.spruce_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.spruce_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spyglass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.spyglass"}</pre></td><td><pre>{
  "translate": "item.minecraft.spyglass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.squid_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.squid_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.stick"}</pre></td><td><pre>{
  "translate": "item.minecraft.stick"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sticky_piston
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sticky_piston"}</pre></td><td><pre>{
  "translate": "block.minecraft.sticky_piston"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stonecutter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stonecutter"}</pre></td><td><pre>{
  "translate": "block.minecraft.stonecutter"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "can_disable_blocking": true,
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.stone_axe"}</pre></td><td><pre>{
  "translate": "item.minecraft.stone_axe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.stone_hoe"}</pre></td><td><pre>{
  "translate": "item.minecraft.stone_hoe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.stone_pickaxe"}</pre></td><td><pre>{
  "translate": "item.minecraft.stone_pickaxe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.stone_shovel"}</pre></td><td><pre>{
  "translate": "item.minecraft.stone_shovel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stone_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.stone_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.stone_sword"}</pre></td><td><pre>{
  "translate": "item.minecraft.stone_sword"
}</pre></td></tr><tr><td>minecraft:tool</td><td><pre>{
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td><td><pre>{
  "can_destroy_blocks_in_creative": false,
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_instantly_mines",
      "speed": 3.4028235e+38
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stray_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.stray_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.stray_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
strider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.strider_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.strider_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
string
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.string"}</pre></td><td><pre>{
  "translate": "item.minecraft.string"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_acacia_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_acacia_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_acacia_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_acacia_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_bamboo_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_bamboo_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_bamboo_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_birch_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_birch_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_birch_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_birch_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_cherry_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_cherry_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_cherry_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_cherry_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_crimson_hyphae"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_crimson_hyphae"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_crimson_stem"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_crimson_stem"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_dark_oak_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_dark_oak_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_dark_oak_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_dark_oak_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_jungle_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_jungle_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_jungle_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_jungle_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_mangrove_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_mangrove_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_mangrove_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_mangrove_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_oak_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_oak_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_oak_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_oak_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_pale_oak_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_pale_oak_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_pale_oak_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_pale_oak_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_spruce_log"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_spruce_log"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_spruce_wood"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_spruce_wood"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_warped_hyphae"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_warped_hyphae"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.stripped_warped_stem"}</pre></td><td><pre>{
  "translate": "block.minecraft.stripped_warped_stem"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.structure_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.structure_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_void
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.structure_void"}</pre></td><td><pre>{
  "translate": "block.minecraft.structure_void"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.sugar"}</pre></td><td><pre>{
  "translate": "item.minecraft.sugar"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar_cane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sugar_cane"}</pre></td><td><pre>{
  "translate": "block.minecraft.sugar_cane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sunflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.sunflower"}</pre></td><td><pre>{
  "translate": "block.minecraft.sunflower"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_gravel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.suspicious_gravel"}</pre></td><td><pre>{
  "translate": "block.minecraft.suspicious_gravel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.suspicious_sand"}</pre></td><td><pre>{
  "translate": "block.minecraft.suspicious_sand"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.suspicious_stew"}</pre></td><td><pre>{
  "translate": "item.minecraft.suspicious_stew"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sweet_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.sweet_berries"}</pre></td><td><pre>{
  "translate": "item.minecraft.sweet_berries"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.tadpole_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.tadpole_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.tadpole_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.tadpole_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tall_grass"}</pre></td><td><pre>{
  "translate": "block.minecraft.tall_grass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
target
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.target"}</pre></td><td><pre>{
  "translate": "block.minecraft.target"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tide_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.tide_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.tide_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tinted_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tinted_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.tinted_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tipped_arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:potion_duration_scale</td><td><pre>/</pre></td><td><pre>0.125</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.tipped_arrow"}</pre></td><td><pre>{
  "translate": "item.minecraft.tipped_arrow"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tnt"}</pre></td><td><pre>{
  "translate": "block.minecraft.tnt"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.tnt_minecart"}</pre></td><td><pre>{
  "translate": "item.minecraft.tnt_minecart"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.torch"}</pre></td><td><pre>{
  "translate": "block.minecraft.torch"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.torchflower"}</pre></td><td><pre>{
  "translate": "block.minecraft.torchflower"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.torchflower_seeds"}</pre></td><td><pre>{
  "translate": "item.minecraft.torchflower_seeds"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
totem_of_undying
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.totem_of_undying"}</pre></td><td><pre>{
  "translate": "item.minecraft.totem_of_undying"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trader_llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.trader_llama_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.trader_llama_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trapped_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.trapped_chest"}</pre></td><td><pre>{
  "translate": "block.minecraft.trapped_chest"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_key
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.trial_key"}</pre></td><td><pre>{
  "translate": "item.minecraft.trial_key"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_spawner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.trial_spawner"}</pre></td><td><pre>{
  "translate": "block.minecraft.trial_spawner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trident
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.trident"}</pre></td><td><pre>{
  "translate": "item.minecraft.trident"
}</pre></td></tr><tr><td>minecraft:tool</td><td><pre>{
  "damage_per_block": 2,
  "rules": []
}</pre></td><td><pre>{
  "can_destroy_blocks_in_creative": false,
  "damage_per_block": 2,
  "rules": []
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tripwire_hook
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tripwire_hook"}</pre></td><td><pre>{
  "translate": "block.minecraft.tripwire_hook"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.tropical_fish"}</pre></td><td><pre>{
  "translate": "item.minecraft.tropical_fish"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.tropical_fish_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.tropical_fish_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.tropical_fish_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.tropical_fish_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tube_coral"}</pre></td><td><pre>{
  "translate": "block.minecraft.tube_coral"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tube_coral_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.tube_coral_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tube_coral_fan"}</pre></td><td><pre>{
  "translate": "block.minecraft.tube_coral_fan"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tuff"}</pre></td><td><pre>{
  "translate": "block.minecraft.tuff"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tuff_bricks"}</pre></td><td><pre>{
  "translate": "block.minecraft.tuff_bricks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tuff_brick_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.tuff_brick_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tuff_brick_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.tuff_brick_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tuff_brick_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.tuff_brick_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tuff_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.tuff_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tuff_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.tuff_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.tuff_wall"}</pre></td><td><pre>{
  "translate": "block.minecraft.tuff_wall"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.turtle_egg"}</pre></td><td><pre>{
  "translate": "block.minecraft.turtle_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.turtle_helmet"}</pre></td><td><pre>{
  "translate": "item.minecraft.turtle_helmet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_scute
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.turtle_scute"}</pre></td><td><pre>{
  "translate": "item.minecraft.turtle_scute"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.turtle_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.turtle_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
twisting_vines
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.twisting_vines"}</pre></td><td><pre>{
  "translate": "block.minecraft.twisting_vines"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vault
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.vault"}</pre></td><td><pre>{
  "translate": "block.minecraft.vault"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
verdant_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.verdant_froglight"}</pre></td><td><pre>{
  "translate": "block.minecraft.verdant_froglight"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.vex_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.vex_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.vex_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.vex_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.villager_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.villager_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vindicator_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.vindicator_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.vindicator_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.vine"}</pre></td><td><pre>{
  "translate": "block.minecraft.vine"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wandering_trader_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wandering_trader_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.wandering_trader_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warden_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.warden_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.warden_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ward_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.ward_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.ward_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_button"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_button"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_fence"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_fence"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_fence_gate"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_fence_gate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_fungus"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_fungus"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus_on_a_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.warped_fungus_on_a_stick"}</pre></td><td><pre>{
  "translate": "item.minecraft.warped_fungus_on_a_stick"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_hanging_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_hanging_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_hyphae"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_hyphae"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_nylium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_nylium"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_nylium"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_planks"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_planks"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_pressure_plate"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_pressure_plate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_roots"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_roots"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_sign"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_sign"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_stem"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_stem"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wart_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.warped_wart_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.warped_wart_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
water_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.water_bucket"}</pre></td><td><pre>{
  "translate": "item.minecraft.water_bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_chiseled_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_chiseled_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_copper_block"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_copper_block"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_copper_bulb"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_copper_bulb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_copper_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_copper_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_copper_grate"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_copper_grate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_copper_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_copper_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_cut_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_cut_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_cut_copper_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_cut_copper_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_cut_copper_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_cut_copper_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_chiseled_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_chiseled_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_copper_bulb"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_copper_bulb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_copper_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_copper_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_copper_grate"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_copper_grate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_copper_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_copper_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_cut_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_cut_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_cut_copper_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_cut_copper_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_exposed_cut_copper_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_exposed_cut_copper_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_chiseled_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_chiseled_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_copper_bulb"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_copper_bulb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_copper_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_copper_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_copper_grate"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_copper_grate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_copper_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_copper_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_cut_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_cut_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_cut_copper_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_cut_copper_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_oxidized_cut_copper_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_oxidized_cut_copper_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_chiseled_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_chiseled_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_copper_bulb"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_copper_bulb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_copper_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_copper_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_copper_grate"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_copper_grate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_copper_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_copper_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_cut_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_cut_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_cut_copper_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_cut_copper_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.waxed_weathered_cut_copper_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.waxed_weathered_cut_copper_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wayfinder_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wayfinder_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.wayfinder_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_chiseled_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_chiseled_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_copper_bulb"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_copper_bulb"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_copper_door"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_copper_door"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_copper_grate"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_copper_grate"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_copper_trapdoor"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_copper_trapdoor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_cut_copper"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_cut_copper"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_cut_copper_slab"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_cut_copper_slab"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weathered_cut_copper_stairs"}</pre></td><td><pre>{
  "translate": "block.minecraft.weathered_cut_copper_stairs"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weeping_vines
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.weeping_vines"}</pre></td><td><pre>{
  "translate": "block.minecraft.weeping_vines"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wet_sponge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.wet_sponge"}</pre></td><td><pre>{
  "translate": "block.minecraft.wet_sponge"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wheat"}</pre></td><td><pre>{
  "translate": "item.minecraft.wheat"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wheat_seeds"}</pre></td><td><pre>{
  "translate": "item.minecraft.wheat_seeds"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.white_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.white_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.white_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.white_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_tulip"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_tulip"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.white_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.white_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wild_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wild_armor_trim_smithing_template"}</pre></td><td><pre>{
  "translate": "item.minecraft.wild_armor_trim_smithing_template"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wind_charge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wind_charge"}</pre></td><td><pre>{
  "translate": "item.minecraft.wind_charge"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
witch_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.witch_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.witch_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_rose
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.wither_rose"}</pre></td><td><pre>{
  "translate": "block.minecraft.wither_rose"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.wither_skeleton_skull"}</pre></td><td><pre>{
  "translate": "block.minecraft.wither_skeleton_skull"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wither_skeleton_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.wither_skeleton_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wither_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.wither_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wolf_armor"}</pre></td><td><pre>{
  "translate": "item.minecraft.wolf_armor"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wolf_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.wolf_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "can_disable_blocking": true,
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wooden_axe"}</pre></td><td><pre>{
  "translate": "item.minecraft.wooden_axe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wooden_hoe"}</pre></td><td><pre>{
  "translate": "item.minecraft.wooden_hoe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wooden_pickaxe"}</pre></td><td><pre>{
  "translate": "item.minecraft.wooden_pickaxe"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{
  "damage_per_attack": 2
}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wooden_shovel"}</pre></td><td><pre>{
  "translate": "item.minecraft.wooden_shovel"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:weapon</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.wooden_sword"}</pre></td><td><pre>{
  "translate": "item.minecraft.wooden_sword"
}</pre></td></tr><tr><td>minecraft:tool</td><td><pre>{
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td><td><pre>{
  "can_destroy_blocks_in_creative": false,
  "damage_per_block": 2,
  "rules": [
    {
      "blocks": "minecraft:cobweb",
      "correct_for_drops": true,
      "speed": 15
    },
    {
      "blocks": "#minecraft:sword_instantly_mines",
      "speed": 3.4028235e+38
    },
    {
      "blocks": "#minecraft:sword_efficient",
      "speed": 1.5
    }
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
writable_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.writable_book"}</pre></td><td><pre>{
  "translate": "item.minecraft.writable_book"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
written_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.written_book"}</pre></td><td><pre>{
  "translate": "item.minecraft.written_book"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_banner"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_banner"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_bed"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_bed"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.yellow_bundle"}</pre></td><td><pre>{
  "translate": "item.minecraft.yellow_bundle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_candle"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_candle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_carpet"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_carpet"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_concrete"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_concrete"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_concrete_powder"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_concrete_powder"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.yellow_dye"}</pre></td><td><pre>{
  "translate": "item.minecraft.yellow_dye"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_glazed_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_glazed_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_shulker_box"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_shulker_box"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_stained_glass"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_stained_glass"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_stained_glass_pane"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_stained_glass_pane"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_terracotta"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_terracotta"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.yellow_wool"}</pre></td><td><pre>{
  "translate": "block.minecraft.yellow_wool"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.zoglin_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.zoglin_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"block.minecraft.zombie_head"}</pre></td><td><pre>{
  "translate": "block.minecraft.zombie_head"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.zombie_horse_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.zombie_horse_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.zombie_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.zombie_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.zombie_villager_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.zombie_villager_spawn_egg"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombified_piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>minecraft:item_name</td><td><pre>{"translate":"item.minecraft.zombified_piglin_spawn_egg"}</pre></td><td><pre>{
  "translate": "item.minecraft.zombified_piglin_spawn_egg"
}</pre></td></tr></table>
<br/>
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
+ leaf_litter.json
+ wildflowers.json
```

</details>
<details>
<summary>
acacia_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_cluster
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>width</td><td><pre>/</pre></td><td><pre>10</pre></td></tr><tr><td>aabb_offset</td><td><pre>3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>type</td><td><pre>minecraft:particle_leaves</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:cherry_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>10</pre></td></tr><tr><td>chance</td><td><pre>10</pre></td><td><pre>/</pre></td></tr><tr><td>particle</td><td><pre>{
  "type": "minecraft:cherry_leaves"
}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>width</td><td><pre>/</pre></td><td><pre>10</pre></td></tr><tr><td>aabb_offset</td><td><pre>3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
medium_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>width</td><td><pre>/</pre></td><td><pre>10</pre></td></tr><tr><td>aabb_offset</td><td><pre>3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>type</td><td><pre>minecraft:particle_leaves</pre></td><td><pre>minecraft:leaves</pre></td></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:pale_oak_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>50</pre></td></tr><tr><td>chance</td><td><pre>50</pre></td><td><pre>/</pre></td></tr><tr><td>particle</td><td><pre>{
  "type": "minecraft:pale_oak_leaves"
}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_petals
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>type</td><td><pre>minecraft:pink_petals</pre></td><td><pre>minecraft:flower_bed</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_amethyst_bud
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>width</td><td><pre>/</pre></td><td><pre>8</pre></td></tr><tr><td>aabb_offset</td><td><pre>4</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_leaves
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.4</th><th>25w02a</th></tr><tr><td>leaf_particle</td><td><pre>/</pre></td><td><pre>{
  "type": "minecraft:tinted_leaves"
}</pre></td></tr><tr><td>leaf_particle_chance</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
clone
</summary>

```diff
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict filtered <filter: block_predicate> force
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict filtered <filter: block_predicate> move
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict filtered <filter: block_predicate> normal
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict masked force
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict masked move
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict masked normal
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict replace force
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict replace move
+ clone <begin: block_pos> <end: block_pos> <destination: block_pos> strict replace normal
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict filtered <filter: block_predicate> force
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict filtered <filter: block_predicate> move
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict filtered <filter: block_predicate> normal
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict masked force
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict masked move
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict masked normal
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict replace force
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict replace move
+ clone <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict replace normal
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict filtered <filter: block_predicate> force
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict filtered <filter: block_predicate> move
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict filtered <filter: block_predicate> normal
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict masked force
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict masked move
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict masked normal
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict replace force
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict replace move
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> <destination: block_pos> strict replace normal
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict filtered <filter: block_predicate> force
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict filtered <filter: block_predicate> move
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict filtered <filter: block_predicate> normal
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict masked force
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict masked move
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict masked normal
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict replace force
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict replace move
+ clone from <sourceDimension: dimension> <begin: block_pos> <end: block_pos> to <targetDimension: dimension> <destination: block_pos> strict replace normal
```

</details>
<details>
<summary>
fill
</summary>

```diff
- fill <from: block_pos> <to: block_pos> <block: block_state> replace <filter: block_predicate>
+ fill <from: block_pos> <to: block_pos> <block: block_state> replace <filter: block_predicate> destroy
+ fill <from: block_pos> <to: block_pos> <block: block_state> replace <filter: block_predicate> hollow
+ fill <from: block_pos> <to: block_pos> <block: block_state> replace <filter: block_predicate> outline
+ fill <from: block_pos> <to: block_pos> <block: block_state> replace <filter: block_predicate> strict
+ fill <from: block_pos> <to: block_pos> <block: block_state> strict
```

</details>
<details>
<summary>
place
</summary>

```diff
- place template <template: resource_location> <pos: block_pos> <rotation: template_rotation> <mirror: template_mirror> <integrity: float> <seed: integer>
+ place template <template: resource_location> <pos: block_pos> <rotation: template_rotation> <mirror: template_mirror> <integrity: float> <seed: integer> strict
```

</details>
<details>
<summary>
setblock
</summary>

```diff
+ setblock <pos: block_pos> <block: block_state> strict
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
+ leaf_litter.json
+ yellow_dye_from_wildflowers.json
```

</details>
<details>
<summary>
gray_dye.json
</summary>

```
Group: none -> gray_dye
```

</details>
<details>
<summary>
lodestone.json
</summary>

```
A: chiseled_stone_bricks
B: iron_ingot
C: netherite_ingot

Previous pattern:
[A | A | A]
[A | C | A]
[A | A | A]

New pattern:
[A | A | A]
[A | B | A]
[A | A | A]
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
+ minecraft:pig_variant
+ minecraft:ticket_type
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
+ block.minecraft.leaf_litter: Leaf Litter
+ block.minecraft.wildflowers: Wildflowers
+ structure_block.strict: Strict Placement:
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.21.4</th><th>25w02a</th></tr>
<tr><th align="left"><div style="width:290px">commands.recipe.give.success.multiple</div></th><td>Unlocked %s recipes for %s players</td><td>Unlocked %s recipe(s) for %s players</td></tr>
<tr><th align="left"><div style="width:290px">commands.recipe.give.success.single</div></th><td>Unlocked %s recipes for %s</td><td>Unlocked %s recipe(s) for %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.recipe.take.success.multiple</div></th><td>Took %s recipes from %s players</td><td>Took %s recipe(s) from %s players</td></tr>
<tr><th align="left"><div style="width:290px">commands.recipe.take.success.single</div></th><td>Took %s recipes from %s</td><td>Took %s recipe(s) from %s</td></tr>
<tr><th align="left"><div style="width:290px">createWorld.customize.buffet.title</div></th><td>Buffet world customization</td><td>Single Biome Customization</td></tr>
<tr><th align="left"><div style="width:290px">createWorld.customize.presets.list</div></th><td>Alternatively, here's some we made earlier!</td><td>Alternatively, here are some we made earlier!</td></tr>
<tr><th align="left"><div style="width:290px">gameMode.hardcore</div></th><td>Hardcore Mode!</td><td>Hardcore Mode</td></tr>
<tr><th align="left"><div style="width:290px">item.modifiers.chest</div></th><td>When on Body:</td><td>When on Chest:</td></tr>
<tr><th align="left"><div style="width:290px">recipe.toast.title</div></th><td>New Recipes Unlocked!</td><td>New Recipe(s) Unlocked!</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.shulker_box.close</div></th><td>Shulker closes</td><td>Shulker box closes</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.shulker_box.open</div></th><td>Shulker opens</td><td>Shulker box opens</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>PACKETS</ins></b><a name="packets"></a></summary>
<br/>
<details>
<summary>
[client] play
</summary>

```diff
- minecraft:add_experience_orb
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
+ minecraft/advancement/recipes/misc/leaf_litter.json
+ minecraft/advancement/recipes/misc/yellow_dye_from_wildflowers.json
+ minecraft/loot_table/blocks/leaf_litter.json
+ minecraft/loot_table/blocks/wildflowers.json
+ minecraft/pig_variant/cold.json
+ minecraft/pig_variant/temperate.json
+ minecraft/pig_variant/warm.json
+ minecraft/recipe/leaf_litter.json
+ minecraft/recipe/yellow_dye_from_wildflowers.json
+ minecraft/tags/block/replaceable_by_mushrooms.json
+ minecraft/tags/block/sword_instantly_mines.json
+ minecraft/tags/item/book_cloning_target.json
+ minecraft/tags/worldgen/biome/spawns_cold_variant_farm_animals.json
+ minecraft/tags/worldgen/biome/spawns_warm_variant_farm_animals.json
+ minecraft/worldgen/configured_feature/birch_bees_0002_leaf_litter.json
+ minecraft/worldgen/configured_feature/birch_leaf_litter.json
+ minecraft/worldgen/configured_feature/dark_oak_leaf_litter.json
+ minecraft/worldgen/configured_feature/fancy_oak_bees_0002_leaf_litter.json
- minecraft/worldgen/configured_feature/fancy_oak_bees_0002.json
+ minecraft/worldgen/configured_feature/fancy_oak_leaf_litter.json
+ minecraft/worldgen/configured_feature/oak_bees_0002_leaf_litter.json
- minecraft/worldgen/configured_feature/oak_bees_0002.json
+ minecraft/worldgen/configured_feature/oak_leaf_litter.json
+ minecraft/worldgen/configured_feature/patch_grass_meadow.json
+ minecraft/worldgen/configured_feature/patch_leaf_litter.json
+ minecraft/worldgen/configured_feature/trees_birch_and_oak_leaf_litter.json
- minecraft/worldgen/configured_feature/trees_birch_and_oak.json
+ minecraft/worldgen/configured_feature/wildflowers_birch_forest.json
+ minecraft/worldgen/configured_feature/wildflowers_meadow.json
+ minecraft/worldgen/placed_feature/birch_bees_0002_leaf_litter.json
+ minecraft/worldgen/placed_feature/birch_leaf_litter.json
+ minecraft/worldgen/placed_feature/dark_oak_leaf_litter.json
+ minecraft/worldgen/placed_feature/fancy_oak_bees_0002_leaf_litter.json
- minecraft/worldgen/placed_feature/fancy_oak_bees_0002.json
+ minecraft/worldgen/placed_feature/fancy_oak_leaf_litter.json
+ minecraft/worldgen/placed_feature/oak_bees_0002_leaf_litter.json
- minecraft/worldgen/placed_feature/oak_bees_0002.json
+ minecraft/worldgen/placed_feature/oak_leaf_litter.json
+ minecraft/worldgen/placed_feature/patch_grass_meadow.json
+ minecraft/worldgen/placed_feature/patch_leaf_litter.json
+ minecraft/worldgen/placed_feature/trees_birch_and_oak_leaf_litter.json
- minecraft/worldgen/placed_feature/trees_birch_and_oak.json
+ minecraft/worldgen/placed_feature/wildflowers_birch_forest.json
+ minecraft/worldgen/placed_feature/wildflowers_meadow.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/leaf_litter.json
+ minecraft/blockstates/wildflowers.json
+ minecraft/items/leaf_litter.json
+ minecraft/items/wildflowers.json
- minecraft/models/block/creaking_heart_active_horizontal.json
- minecraft/models/block/creaking_heart_active.json
+ minecraft/models/block/creaking_heart_awake_horizontal.json
+ minecraft/models/block/creaking_heart_awake.json
+ minecraft/models/block/creaking_heart_dormant_horizontal.json
+ minecraft/models/block/creaking_heart_dormant.json
+ minecraft/models/block/leaf_litter_1.json
+ minecraft/models/block/leaf_litter_2.json
+ minecraft/models/block/leaf_litter_3.json
+ minecraft/models/block/leaf_litter_4.json
+ minecraft/models/block/template_leaf_litter_1.json
+ minecraft/models/block/template_leaf_litter_2.json
+ minecraft/models/block/template_leaf_litter_3.json
+ minecraft/models/block/template_leaf_litter_4.json
+ minecraft/models/block/wildflowers_1.json
+ minecraft/models/block/wildflowers_2.json
+ minecraft/models/block/wildflowers_3.json
+ minecraft/models/block/wildflowers_4.json
+ minecraft/models/item/leaf_litter.json
+ minecraft/models/item/wildflowers.json
+ minecraft/particles/tinted_leaves.json
- minecraft/textures/block/creaking_heart_active.png
+ minecraft/textures/block/creaking_heart_awake.png
+ minecraft/textures/block/creaking_heart_dormant.png
- minecraft/textures/block/creaking_heart_top_active.png
+ minecraft/textures/block/creaking_heart_top_awake.png
+ minecraft/textures/block/creaking_heart_top_dormant.png
+ minecraft/textures/block/leaf_litter.png
+ minecraft/textures/block/wildflowers_stem.png
+ minecraft/textures/block/wildflowers.png
+ minecraft/textures/entity/pig/cold_pig.png
+ minecraft/textures/entity/pig/warm_pig.png
+ minecraft/textures/item/wildflowers.png
+ minecraft/textures/particle/leaf_0.png
+ minecraft/textures/particle/leaf_1.png
+ minecraft/textures/particle/leaf_10.png
+ minecraft/textures/particle/leaf_11.png
+ minecraft/textures/particle/leaf_2.png
+ minecraft/textures/particle/leaf_3.png
+ minecraft/textures/particle/leaf_4.png
+ minecraft/textures/particle/leaf_5.png
+ minecraft/textures/particle/leaf_6.png
+ minecraft/textures/particle/leaf_7.png
+ minecraft/textures/particle/leaf_8.png
+ minecraft/textures/particle/leaf_9.png
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
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.Attribute$Sentiment
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
+ XXX.ai.behavior.StartAttacking$StartAttackingCondition
- XXX.ai.behavior.StartAttacking$TargetFinder
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopAttackingIfTargetInvalid$StopAttackCondition
+ XXX.ai.behavior.StopAttackingIfTargetInvalid$TargetErasedCallback
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
- XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
+ XXX.ai.targeting.TargetingConditions$Selector
+ XXX.ai.util.AirAndWaterRandomPos
- XXX.ai.util.AirRandomPos
+ XXX.ai.util.DefaultRandomPos
- XXX.ai.util.GoalUtils
+ XXX.ai.util.HoverRandomPos
- XXX.ai.util.LandRandomPos
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
- XXX.animal.allay.Allay
+ XXX.animal.allay.Allay$JukeboxListener
- XXX.animal.allay.Allay$VibrationUser
+ XXX.animal.allay.AllayAi
- XXX.animal.allay.package-info
+ XXX.animal.armadillo.Armadillo
- XXX.animal.armadillo.Armadillo$1
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
- XXX.animal.axolotl.Axolotl$AnimationState
+ XXX.animal.axolotl.Axolotl$AxolotlGroupData
- XXX.animal.axolotl.Axolotl$AxolotlLookControl
+ XXX.animal.axolotl.Axolotl$AxolotlMoveControl
- XXX.animal.axolotl.Axolotl$Variant
+ XXX.animal.axolotl.AxolotlAi
- XXX.animal.axolotl.package-info
- XXX.animal.axolotl.PlayDead
+ XXX.animal.axolotl.ValidatePlayDead
+ XXX.animal.camel.Camel
- XXX.animal.camel.Camel$CamelBodyRotationControl
+ XXX.animal.camel.Camel$CamelLookControl
- XXX.animal.camel.Camel$CamelMoveControl
+ XXX.animal.camel.CamelAi
- XXX.animal.camel.CamelAi$CamelPanic
+ XXX.animal.camel.CamelAi$RandomSitting
- XXX.animal.camel.package-info
+ XXX.animal.frog.Frog
- XXX.animal.frog.Frog$FrogLookControl
+ XXX.animal.frog.Frog$FrogNodeEvaluator
- XXX.animal.frog.Frog$FrogPathNavigation
+ XXX.animal.frog.FrogAi
- XXX.animal.frog.package-info
- XXX.animal.frog.ShootTongue
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
+ XXX.animal.sniffer.package-info
+ XXX.animal.sniffer.Sniffer
- XXX.animal.sniffer.Sniffer$State
+ XXX.animal.sniffer.SnifferAi
- XXX.animal.sniffer.SnifferAi$1
+ XXX.animal.sniffer.SnifferAi$2
- XXX.animal.sniffer.SnifferAi$3
+ XXX.animal.sniffer.SnifferAi$Digging
- XXX.animal.sniffer.SnifferAi$FeelingHappy
+ XXX.animal.sniffer.SnifferAi$FinishedDigging
- XXX.animal.sniffer.SnifferAi$Scenting
+ XXX.animal.sniffer.SnifferAi$Searching
- XXX.animal.sniffer.SnifferAi$Sniffing
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
+ XXX.block.piston.package-info
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
+ XXX.boss.enderdragon.DragonFlightHistory
- XXX.boss.enderdragon.DragonFlightHistory$Sample
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.DataSource$Type
- XXX.chat.contents.EntityDataSource
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.NbtContents
- XXX.chat.contents.package-info
- XXX.chat.contents.PlainTextContents
+ XXX.chat.contents.PlainTextContents$1
- XXX.chat.contents.PlainTextContents$LiteralContents
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.StorageDataSource
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
+ XXX.chat.numbers.BlankFormat
- XXX.chat.numbers.BlankFormat$1
+ XXX.chat.numbers.FixedFormat
- XXX.chat.numbers.FixedFormat$1
+ XXX.chat.numbers.NumberFormat
- XXX.chat.numbers.NumberFormatType
+ XXX.chat.numbers.NumberFormatTypes
- XXX.chat.numbers.package-info
- XXX.chat.numbers.StyledFormat
+ XXX.chat.numbers.StyledFormat$1
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
+ XXX.common.custom.BeeDebugPayload
- XXX.common.custom.BeeDebugPayload$BeeInfo
+ XXX.common.custom.BrainDebugPayload
- XXX.common.custom.BrainDebugPayload$BrainDump
+ XXX.common.custom.BrandPayload
- XXX.common.custom.BreezeDebugPayload
+ XXX.common.custom.BreezeDebugPayload$BreezeInfo
- XXX.common.custom.CustomPacketPayload
+ XXX.common.custom.CustomPacketPayload$1
- XXX.common.custom.CustomPacketPayload$FallbackProvider
+ XXX.common.custom.CustomPacketPayload$Type
- XXX.common.custom.CustomPacketPayload$TypeAndCodec
+ XXX.common.custom.DiscardedPayload
- XXX.common.custom.GameEventDebugPayload
+ XXX.common.custom.GameEventListenerDebugPayload
- XXX.common.custom.GameTestAddMarkerDebugPayload
+ XXX.common.custom.GameTestClearMarkersDebugPayload
- XXX.common.custom.GoalDebugPayload
+ XXX.common.custom.GoalDebugPayload$DebugGoal
- XXX.common.custom.HiveDebugPayload
+ XXX.common.custom.HiveDebugPayload$HiveInfo
- XXX.common.custom.NeighborUpdatesDebugPayload
- XXX.common.custom.package-info
+ XXX.common.custom.PathfindingDebugPayload
- XXX.common.custom.PoiAddedDebugPayload
+ XXX.common.custom.PoiRemovedDebugPayload
- XXX.common.custom.PoiTicketCountDebugPayload
+ XXX.common.custom.RaidsDebugPayload
- XXX.common.custom.RedstoneWireOrientationsDebugPayload
+ XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
- XXX.common.custom.StructuresDebugPayload
+ XXX.common.custom.StructuresDebugPayload$PieceInfo
- XXX.common.custom.VillageSectionsDebugPayload
+ XXX.common.custom.WorldGenAttemptDebugPayload
+ XXX.crafting.display.DisplayContentsFactory
- XXX.crafting.display.DisplayContentsFactory$ForRemainders
+ XXX.crafting.display.DisplayContentsFactory$ForStacks
- XXX.crafting.display.FurnaceRecipeDisplay
+ XXX.crafting.display.package-info
+ XXX.crafting.display.RecipeDisplay
- XXX.crafting.display.RecipeDisplay$Type
+ XXX.crafting.display.RecipeDisplayEntry
- XXX.crafting.display.RecipeDisplayId
+ XXX.crafting.display.RecipeDisplays
- XXX.crafting.display.ShapedCraftingRecipeDisplay
+ XXX.crafting.display.ShapelessCraftingRecipeDisplay
- XXX.crafting.display.SlotDisplay
+ XXX.crafting.display.SlotDisplay$AnyFuel
- XXX.crafting.display.SlotDisplay$Composite
+ XXX.crafting.display.SlotDisplay$Empty
- XXX.crafting.display.SlotDisplay$ItemSlotDisplay
+ XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
- XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
+ XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
- XXX.crafting.display.SlotDisplay$TagSlotDisplay
+ XXX.crafting.display.SlotDisplay$Type
- XXX.crafting.display.SlotDisplay$WithRemainder
+ XXX.crafting.display.SlotDisplayContext
- XXX.crafting.display.SlotDisplays
+ XXX.crafting.display.SmithingRecipeDisplay
- XXX.crafting.display.StonecutterRecipeDisplay
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockPosFormatAndRenamesFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityAttributeBaseValueFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityFieldsRenameFix
+ XXX.datafix.fixes.EntityGoatMissingStateFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntitySalmonSizeFix
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
+ XXX.datafix.fixes.EquippableAssetRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FoodToConsumableFix
- XXX.datafix.fixes.ForcedChunkToTicketFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.ItemStackTagRemainderFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.LockComponentPredicateFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NamedEntityWriteReadFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
+ XXX.datafix.fixes.NewVillageFix
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
- XXX.datafix.fixes.TextComponentHoverAndClickEventFix
- XXX.datafix.fixes.TextComponentStringifiedFlagsFix
+ XXX.datafix.fixes.TippedArrowPotionToItemFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.TrialSpawnerConfigFix
+ XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix
- XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix$VanillaTrialChambers
- XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1488
- XXX.datafix.schemas.V1925
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
+ XXX.datafix.schemas.V2831
- XXX.datafix.schemas.V2832
+ XXX.datafix.schemas.V2842
- XXX.datafix.schemas.V3076
+ XXX.datafix.schemas.V3078
- XXX.datafix.schemas.V3081
+ XXX.datafix.schemas.V3082
- XXX.datafix.schemas.V3083
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
- XXX.datafix.schemas.V3325
+ XXX.datafix.schemas.V3326
- XXX.datafix.schemas.V3327
+ XXX.datafix.schemas.V3328
- XXX.datafix.schemas.V3438
- XXX.datafix.schemas.V3813
+ XXX.datafix.schemas.V3816
- XXX.datafix.schemas.V3818
+ XXX.datafix.schemas.V3818_3
- XXX.datafix.schemas.V3818_4
+ XXX.datafix.schemas.V3818_5
- XXX.datafix.schemas.V3825
+ XXX.datafix.schemas.V3938
- XXX.datafix.schemas.V4059
+ XXX.datafix.schemas.V4067
- XXX.datafix.schemas.V4070
+ XXX.datafix.schemas.V4071
- XXX.datafix.schemas.V4290
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
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyMobEffect
+ XXX.enchantment.effects.ChangeItemDamage
- XXX.enchantment.effects.DamageEntity
+ XXX.enchantment.effects.DamageImmunity
- XXX.enchantment.effects.EnchantmentAttributeEffect
+ XXX.enchantment.effects.EnchantmentEntityEffect
- XXX.enchantment.effects.EnchantmentLocationBasedEffect
+ XXX.enchantment.effects.EnchantmentValueEffect
- XXX.enchantment.effects.ExplodeEffect
+ XXX.enchantment.effects.Ignite
- XXX.enchantment.effects.MultiplyValue
- XXX.enchantment.effects.package-info
+ XXX.enchantment.effects.PlaySoundEffect
- XXX.enchantment.effects.RemoveBinomial
+ XXX.enchantment.effects.ReplaceBlock
- XXX.enchantment.effects.ReplaceDisk
+ XXX.enchantment.effects.RunFunction
- XXX.enchantment.effects.SetBlockProperties
+ XXX.enchantment.effects.SetValue
- XXX.enchantment.effects.SpawnParticlesEffect
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
- XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
+ XXX.enchantment.effects.SummonEntityEffect
- XXX.enchantment.providers.EnchantmentProvider
+ XXX.enchantment.providers.EnchantmentProviderTypes
- XXX.enchantment.providers.EnchantmentsByCost
+ XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
+ XXX.enchantment.providers.package-info
- XXX.enchantment.providers.SingleEnchantment
+ XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
- XXX.enchantment.providers.VanillaEnchantmentProviders
- XXX.enderdragon.phases.AbstractDragonPhaseInstance
+ XXX.enderdragon.phases.AbstractDragonSittingPhase
- XXX.enderdragon.phases.DragonChargePlayerPhase
+ XXX.enderdragon.phases.DragonDeathPhase
- XXX.enderdragon.phases.DragonHoldingPatternPhase
+ XXX.enderdragon.phases.DragonHoverPhase
- XXX.enderdragon.phases.DragonLandingApproachPhase
+ XXX.enderdragon.phases.DragonLandingPhase
- XXX.enderdragon.phases.DragonPhaseInstance
+ XXX.enderdragon.phases.DragonSittingAttackingPhase
- XXX.enderdragon.phases.DragonSittingFlamingPhase
+ XXX.enderdragon.phases.DragonSittingScanningPhase
- XXX.enderdragon.phases.DragonStrafePlayerPhase
+ XXX.enderdragon.phases.DragonTakeoffPhase
- XXX.enderdragon.phases.EnderDragonPhase
+ XXX.enderdragon.phases.EnderDragonPhaseManager
- XXX.enderdragon.phases.package-info
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
+ XXX.entity.ai.package-info
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractFish
- XXX.entity.animal.AbstractFish$FishMoveControl
+ XXX.entity.animal.AbstractFish$FishSwimGoal
- XXX.entity.animal.AbstractGolem
+ XXX.entity.animal.AbstractSchoolingFish
- XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ XXX.entity.animal.AgeableWaterCreature
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
+ XXX.entity.animal.Bee$ValidateFlowerGoal
- XXX.entity.animal.Bee$ValidateHiveGoal
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
+ XXX.entity.animal.Fox$Variant
- XXX.entity.animal.FrogVariant
+ XXX.entity.animal.IronGolem
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$Variant
- XXX.entity.animal.Ocelot
+ XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
- XXX.entity.animal.Ocelot$OcelotTemptGoal
- XXX.entity.animal.package-info
+ XXX.entity.animal.Panda
- XXX.entity.animal.Panda$Gene
+ XXX.entity.animal.Panda$PandaAttackGoal
- XXX.entity.animal.Panda$PandaAvoidGoal
+ XXX.entity.animal.Panda$PandaBreedGoal
- XXX.entity.animal.Panda$PandaHurtByTargetGoal
+ XXX.entity.animal.Panda$PandaLieOnBackGoal
- XXX.entity.animal.Panda$PandaLookAtPlayerGoal
+ XXX.entity.animal.Panda$PandaMoveControl
- XXX.entity.animal.Panda$PandaPanicGoal
+ XXX.entity.animal.Panda$PandaRollGoal
- XXX.entity.animal.Panda$PandaSitGoal
+ XXX.entity.animal.Panda$PandaSneezeGoal
- XXX.entity.animal.Parrot
+ XXX.entity.animal.Parrot$1
- XXX.entity.animal.Parrot$ParrotWanderGoal
+ XXX.entity.animal.Parrot$Variant
- XXX.entity.animal.Pig
- XXX.entity.animal.PigVariant$ModelType
- XXX.entity.animal.TemperatureVariant
+ XXX.entity.animal.TropicalFish
- XXX.entity.animal.TropicalFish$Base
+ XXX.entity.animal.TropicalFish$Pattern
- XXX.entity.animal.TropicalFish$TropicalFishGroupData
+ XXX.entity.animal.TropicalFish$Variant
- XXX.entity.animal.Turtle
+ XXX.entity.animal.Turtle$TurtleBreedGoal
- XXX.entity.animal.Turtle$TurtleGoHomeGoal
+ XXX.entity.animal.Turtle$TurtleGoToWaterGoal
- XXX.entity.animal.Turtle$TurtleLayEggGoal
+ XXX.entity.animal.Turtle$TurtleMoveControl
- XXX.entity.animal.Turtle$TurtlePanicGoal
+ XXX.entity.animal.Turtle$TurtlePathNavigation
- XXX.entity.animal.Turtle$TurtleRandomStrollGoal
+ XXX.entity.animal.Turtle$TurtleTravelGoal
- XXX.entity.animal.WaterAnimal
+ XXX.entity.animal.Wolf
- XXX.entity.animal.Wolf$WolfAvoidEntityGoal
+ XXX.entity.animal.Wolf$WolfPackData
- XXX.entity.animal.WolfVariant
+ XXX.entity.animal.WolfVariants
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.ArmorStand$1
+ XXX.entity.decoration.BlockAttachedEntity
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
- XXX.entity.decoration.PaintingVariant
+ XXX.entity.decoration.PaintingVariants
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
+ XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
- XXX.entity.item.PrimedTnt$1
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.Bogged
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$EvokerAttackSpellGoal
- XXX.entity.monster.Evoker$EvokerCastingSpellGoal
+ XXX.entity.monster.Evoker$EvokerSummonSpellGoal
- XXX.entity.monster.Evoker$EvokerWololoSpellGoal
+ XXX.entity.monster.Ghast
- XXX.entity.monster.Ghast$GhastLookGoal
+ XXX.entity.monster.Ghast$GhastMoveControl
- XXX.entity.monster.Ghast$GhastShootFireballGoal
+ XXX.entity.monster.Ghast$RandomFloatAroundGoal
- XXX.entity.monster.Giant
+ XXX.entity.monster.Guardian
- XXX.entity.monster.Guardian$GuardianAttackGoal
+ XXX.entity.monster.Guardian$GuardianAttackSelector
- XXX.entity.monster.Guardian$GuardianMoveControl
+ XXX.entity.monster.Husk
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
+ XXX.entity.monster.package-info
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$AttackPhase
+ XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
+ XXX.entity.monster.Phantom$PhantomBodyRotationControl
- XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ XXX.entity.monster.Phantom$PhantomLookControl
- XXX.entity.monster.Phantom$PhantomMoveControl
+ XXX.entity.monster.Phantom$PhantomMoveTargetGoal
- XXX.entity.monster.Phantom$PhantomSweepAttackGoal
+ XXX.entity.monster.Pillager
- XXX.entity.monster.RangedAttackMob
+ XXX.entity.monster.Ravager
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$ShulkerAttackGoal
- XXX.entity.monster.Shulker$ShulkerBodyRotationControl
+ XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
- XXX.entity.monster.Shulker$ShulkerLookControl
+ XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
- XXX.entity.monster.Shulker$ShulkerPeekGoal
+ XXX.entity.monster.Silverfish
- XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- XXX.entity.monster.Skeleton
+ XXX.entity.monster.Slime
- XXX.entity.monster.Slime$SlimeAttackGoal
+ XXX.entity.monster.Slime$SlimeFloatGoal
- XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ XXX.entity.monster.Slime$SlimeMoveControl
- XXX.entity.monster.Slime$SlimeRandomDirectionGoal
+ XXX.entity.monster.SpellcasterIllager
- XXX.entity.monster.SpellcasterIllager$IllagerSpell
+ XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ XXX.entity.monster.Spider
- XXX.entity.monster.Spider$SpiderAttackGoal
+ XXX.entity.monster.Spider$SpiderEffectsGroupData
- XXX.entity.monster.Spider$SpiderTargetGoal
+ XXX.entity.monster.Stray
- XXX.entity.monster.Strider
+ XXX.entity.monster.Strider$StriderGoToLavaGoal
- XXX.entity.monster.Strider$StriderPathNavigation
+ XXX.entity.monster.Vex
- XXX.entity.monster.Vex$VexChargeAttackGoal
+ XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
- XXX.entity.monster.Vex$VexMoveControl
+ XXX.entity.monster.Vex$VexRandomMoveGoal
- XXX.entity.monster.Vindicator
+ XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
- XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zoglin
- XXX.entity.monster.Zombie
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
- XXX.entity.monster.ZombifiedPiglin
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$FailureItemListing
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerTrades$TypeSpecificTrade
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Input
+ XXX.entity.player.Input$1
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$2
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$IngredientInfo
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.Projectile$ProjectileFactory
+ XXX.entity.projectile.ProjectileDeflection
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
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
- XXX.entity.vehicle.AbstractBoat
+ XXX.entity.vehicle.AbstractBoat$Status
- XXX.entity.vehicle.AbstractChestBoat
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestRaft
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartBehavior
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.NewMinecartBehavior
- XXX.entity.vehicle.NewMinecartBehavior$1
+ XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
- XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
+ XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
- XXX.entity.vehicle.OldMinecartBehavior
+ XXX.entity.vehicle.OldMinecartBehavior$1
- XXX.entity.vehicle.package-info
- XXX.entity.vehicle.Raft
+ XXX.entity.vehicle.VehicleEntity
- XXX.equipment.trim.ArmorTrim
+ XXX.equipment.trim.package-info
+ XXX.equipment.trim.TrimMaterial
- XXX.equipment.trim.TrimMaterials
+ XXX.equipment.trim.TrimPattern
- XXX.equipment.trim.TrimPatterns
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.PlaceOnGroundDecorator
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecorator$Context
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.BendingTrunkPlacer
+ XXX.feature.trunkplacers.CherryTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
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
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.BlockItemStateProperties
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
+ XXX.item.component.Consumable
- XXX.item.component.Consumable$Builder
+ XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.ConsumableListener
+ XXX.item.component.Consumables
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
- XXX.item.component.DamageResistant
+ XXX.item.component.DeathProtection
- XXX.item.component.DebugStickState
+ XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion
+ XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.Fireworks
+ XXX.item.component.ItemAttributeModifiers
- XXX.item.component.ItemAttributeModifiers$1
+ XXX.item.component.ItemAttributeModifiers$Builder
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
- XXX.item.component.ResolvableProfile
+ XXX.item.component.SeededContainerLoot
- XXX.item.component.SuspiciousStewEffects
+ XXX.item.component.SuspiciousStewEffects$Entry
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipProvider
+ XXX.item.component.Unbreakable
- XXX.item.component.UseCooldown
+ XXX.item.component.UseRemainder
- XXX.item.component.UseRemainder$OnExtraCreatedRemainder
- XXX.item.crafting.package-info
- XXX.item.crafting.TransmuteResult
+ XXX.item.enchantment.ConditionalEffect
- XXX.item.enchantment.Enchantable
+ XXX.item.enchantment.EnchantedItemInUse
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$1
- XXX.item.enchantment.Enchantment$Builder
+ XXX.item.enchantment.Enchantment$Cost
- XXX.item.enchantment.Enchantment$EnchantmentDefinition
+ XXX.item.enchantment.EnchantmentEffectComponents
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.EnchantmentTarget
- XXX.item.enchantment.ItemEnchantments
+ XXX.item.enchantment.ItemEnchantments$Mutable
- XXX.item.enchantment.LevelBasedValue
+ XXX.item.enchantment.LevelBasedValue$Clamped
- XXX.item.enchantment.LevelBasedValue$Constant
+ XXX.item.enchantment.LevelBasedValue$Fraction
- XXX.item.enchantment.LevelBasedValue$LevelsSquared
+ XXX.item.enchantment.LevelBasedValue$Linear
- XXX.item.enchantment.LevelBasedValue$Lookup
+ XXX.item.enchantment.package-info
+ XXX.item.enchantment.Repairable
- XXX.item.enchantment.TargetedConditionalEffect
- XXX.item.equipment.ArmorMaterial
+ XXX.item.equipment.ArmorMaterials
- XXX.item.equipment.ArmorType
+ XXX.item.equipment.EquipmentAsset
- XXX.item.equipment.EquipmentAssets
+ XXX.item.equipment.Equippable
- XXX.item.equipment.Equippable$Builder
+ XXX.item.equipment.package-info
+ XXX.item.trading.ItemCost
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
- XXX.jfr.callback.package-info
+ XXX.jfr.callback.ProfiledDuration
+ XXX.jfr.event.ChunkGenerationEvent
- XXX.jfr.event.ChunkGenerationEvent$Fields
+ XXX.jfr.event.ChunkRegionIoEvent
- XXX.jfr.event.ChunkRegionIoEvent$Fields
+ XXX.jfr.event.ChunkRegionReadEvent
- XXX.jfr.event.ChunkRegionWriteEvent
+ XXX.jfr.event.NetworkSummaryEvent
- XXX.jfr.event.NetworkSummaryEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent$SumAggregation
+ XXX.jfr.event.package-info
- XXX.jfr.event.PacketEvent
+ XXX.jfr.event.PacketEvent$Fields
- XXX.jfr.event.PacketReceivedEvent
+ XXX.jfr.event.PacketSentEvent
- XXX.jfr.event.ServerTickTimeEvent
+ XXX.jfr.event.ServerTickTimeEvent$Fields
- XXX.jfr.event.StructureGenerationEvent
+ XXX.jfr.event.StructureGenerationEvent$Fields
- XXX.jfr.event.WorldLoadFinishedEvent
+ XXX.jfr.parse.JfrStatsParser
- XXX.jfr.parse.JfrStatsParser$1
+ XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
- XXX.jfr.parse.JfrStatsResult
+ XXX.jfr.parse.package-info
- XXX.jfr.serialize.JfrResultJsonSerializer
+ XXX.jfr.serialize.package-info
- XXX.jfr.stats.ChunkGenStat
+ XXX.jfr.stats.ChunkIdentification
- XXX.jfr.stats.CpuLoadStat
+ XXX.jfr.stats.FileIOStat
- XXX.jfr.stats.FileIOStat$Summary
+ XXX.jfr.stats.GcHeapStat
- XXX.jfr.stats.GcHeapStat$Summary
+ XXX.jfr.stats.GcHeapStat$Timing
- XXX.jfr.stats.IoSummary
+ XXX.jfr.stats.IoSummary$CountAndSize
+ XXX.jfr.stats.package-info
- XXX.jfr.stats.PacketIdentification
+ XXX.jfr.stats.StructureGenStat
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
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
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$ShapePairKey
+ XXX.level.block.Blocks
- XXX.level.block.BlockTypes
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BonemealableBlock$Type
- XXX.level.block.BonemealableFeaturePlacerBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BrushableBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
+ XXX.level.block.ChainBlock$1
- XXX.level.block.ChangeOverTimeBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChiseledBookShelfBlock
- XXX.level.block.ChiseledBookShelfBlock$1
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.FlowerBedBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrogspawnBlock
- XXX.level.block.FrostedIceBlock
+ XXX.level.block.FungusBlock
- XXX.level.block.FurnaceBlock
+ XXX.level.block.GameMasterBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GrindstoneBlock
+ XXX.level.block.HopperBlock$1
- XXX.level.block.HorizontalDirectionalBlock
+ XXX.level.block.HugeMushroomBlock
- XXX.level.block.IceBlock
+ XXX.level.block.InfestedBlock
- XXX.level.block.InfestedRotatedPillarBlock
+ XXX.level.block.IronBarsBlock
- XXX.level.block.JigsawBlock
+ XXX.level.block.JukeboxBlock
- XXX.level.block.KelpBlock
+ XXX.level.block.KelpPlantBlock
- XXX.level.block.LadderBlock
+ XXX.level.block.LadderBlock$1
- XXX.level.block.LeafLitterBlock
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
+ XXX.level.block.LightBlock
- XXX.level.block.LightningRodBlock
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LoomBlock
- XXX.level.block.MagmaBlock
+ XXX.level.block.MangroveLeavesBlock
- XXX.level.block.MangrovePropaguleBlock
+ XXX.level.block.MangroveRootsBlock
- XXX.level.block.Mirror
+ XXX.level.block.MossyCarpetBlock
- XXX.level.block.MossyCarpetBlock$1
+ XXX.level.block.MudBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MultifaceSpreadeableBlock
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
+ XXX.level.block.PipeBlock
- XXX.level.block.PitcherCropBlock
- XXX.level.block.PointedDripstoneBlock$1
+ XXX.level.block.PointedDripstoneBlock$FluidInfo
- XXX.level.block.Portal
+ XXX.level.block.Portal$Transition
- XXX.level.block.PotatoBlock
+ XXX.level.block.PowderSnowBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PumpkinBlock
- XXX.level.block.RailBlock
+ XXX.level.block.RailBlock$1
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RespawnAnchorBlock$1
+ XXX.level.block.RodBlock
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
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VaultBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallHangingSignBlock
- XXX.level.entity.UUIDLookup
+ XXX.level.levelgen.package-info
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
+ XXX.level.material.FlowingFluid$BlockStatePairKey
- XXX.level.material.FlowingFluid$SpreadContext
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
+ XXX.level.pathfinder.PathfindingContext
+ XXX.level.pathfinder.PathType
- XXX.level.pathfinder.PathTypeCache
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.pathfinder.WalkNodeEvaluator$1
+ XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalShape
+ XXX.level.portal.TeleportTransition
- XXX.level.portal.TeleportTransition$PostTeleportTransition
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
- XXX.level.redstone.CollectingNeighborUpdater
+ XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.DefaultRedstoneWireEvaluator
+ XXX.level.redstone.ExperimentalRedstoneUtils
- XXX.level.redstone.ExperimentalRedstoneWireEvaluator
+ XXX.level.redstone.InstantNeighborUpdater
- XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.Orientation
- XXX.level.redstone.Orientation$SideBias
+ XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.redstone.RedstoneWireEvaluator
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
+ XXX.level.saveddata.SavedData$Factory
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.FileNameDateFormatter
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelDataAndDimensions
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelSummary$CorruptedLevelSummary
+ XXX.level.storage.LevelSummary$SymlinkLevelSummary
- XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
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
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPreset
+ XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
+ XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.heightproviders.WeightedListHeight
- XXX.levelgen.material.MaterialRuleList
- XXX.levelgen.material.package-info
+ XXX.levelgen.material.WorldGenMaterialRule
- XXX.levelgen.placement.BiomeFilter
+ XXX.levelgen.placement.BlockPredicateFilter
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CountOnEveryLayerPlacement
- XXX.levelgen.placement.CountPlacement
+ XXX.levelgen.placement.EnvironmentScanPlacement
- XXX.levelgen.placement.FixedPlacement
- XXX.levelgen.placement.HeightmapPlacement
+ XXX.levelgen.placement.HeightRangePlacement
+ XXX.levelgen.placement.InSquarePlacement
- XXX.levelgen.placement.NoiseBasedCountPlacement
+ XXX.levelgen.placement.NoiseThresholdCountPlacement
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.PlacedFeature
+ XXX.levelgen.placement.PlacementContext
- XXX.levelgen.placement.PlacementFilter
+ XXX.levelgen.placement.PlacementModifier
- XXX.levelgen.placement.PlacementModifierType
+ XXX.levelgen.placement.RandomOffsetPlacement
- XXX.levelgen.placement.RarityFilter
+ XXX.levelgen.placement.RepeatingPlacement
- XXX.levelgen.placement.SurfaceRelativeThresholdFilter
+ XXX.levelgen.placement.SurfaceWaterDepthFilter
- XXX.levelgen.presets.package-info
+ XXX.levelgen.presets.WorldPreset
- XXX.levelgen.presets.WorldPresets
+ XXX.levelgen.presets.WorldPresets$Bootstrap
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuiltinStructures
+ XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationContext
+ XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.Structure$StructureSettings
+ XXX.levelgen.structure.Structure$StructureSettings$Builder
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
+ XXX.loot.functions.CopyComponentsFunction
- XXX.loot.functions.CopyComponentsFunction$Builder
+ XXX.loot.functions.CopyComponentsFunction$Source
- XXX.loot.functions.CopyCustomDataFunction
+ XXX.loot.functions.CopyCustomDataFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction$CopyOperation
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.EnchantedCountIncreaseFunction
- XXX.loot.functions.EnchantedCountIncreaseFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FilteredFunction
+ XXX.loot.functions.FunctionReference
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.ListOperation
+ XXX.loot.functions.ListOperation$Append
- XXX.loot.functions.ListOperation$Insert
+ XXX.loot.functions.ListOperation$ReplaceAll
- XXX.loot.functions.ListOperation$ReplaceSection
+ XXX.loot.functions.ListOperation$StandAlone
- XXX.loot.functions.ListOperation$Type
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.ModifyContainerContents
- XXX.loot.functions.package-info
+ XXX.loot.functions.SequenceFunction
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetBookCoverFunction
+ XXX.loot.functions.SetComponentsFunction
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetCustomDataFunction
- XXX.loot.functions.SetCustomModelDataFunction
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetFireworkExplosionFunction
- XXX.loot.functions.SetFireworksFunction
+ XXX.loot.functions.SetInstrumentFunction
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemFunction
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$Target
+ XXX.loot.functions.SetOminousBottleAmplifierFunction
- XXX.loot.functions.SetPotionFunction
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$EffectEntry
- XXX.loot.functions.SetWritableBookPagesFunction
+ XXX.loot.functions.SetWrittenBookPagesFunction
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.ToggleTooltips
- XXX.loot.functions.ToggleTooltips$ComponentToggle
+ XXX.loot.functions.ToggleTooltips$TooltipWither
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AllOfCondition
- XXX.loot.predicates.AllOfCondition$Builder
+ XXX.loot.predicates.AnyOfCondition
- XXX.loot.predicates.AnyOfCondition$Builder
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.CompositeLootItemCondition
+ XXX.loot.predicates.CompositeLootItemCondition$Builder
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.EnchantmentActiveCheck
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
- XXX.loot.predicates.LootItemRandomChanceWithEnchantedBonusCondition
+ XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
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
+ XXX.minecraft.network.package-info
- XXX.minecraft.server.package-info
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.RecipeBookSettings
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
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
+ XXX.minecraft.tags.EnchantmentTags
- XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.FlatLevelGeneratorPresetTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.InstrumentTags
+ XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
- XXX.minecraft.tags.PaintingVariantTags
+ XXX.minecraft.tags.PoiTypeTags
- XXX.minecraft.tags.StructureTags
+ XXX.minecraft.tags.TagBuilder
- XXX.minecraft.tags.TagEntry
+ XXX.minecraft.tags.TagEntry$Lookup
- XXX.minecraft.tags.TagFile
+ XXX.minecraft.tags.TagKey
- XXX.minecraft.tags.TagLoader
+ XXX.minecraft.tags.TagLoader$1
- XXX.minecraft.tags.TagLoader$ElementLookup
+ XXX.minecraft.tags.TagLoader$EntryWithSource
- XXX.minecraft.tags.TagLoader$LoadResult
+ XXX.minecraft.tags.TagLoader$SortingEntry
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.WorldPresetTags
+ XXX.minecraft.util.AbortableIterationConsumer
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
- XXX.minecraft.util.ARGB
+ XXX.minecraft.util.ArrayListDeque
- XXX.minecraft.util.ArrayListDeque$DescendingIterator
+ XXX.minecraft.util.ArrayListDeque$ReversedView
- XXX.minecraft.util.BinaryAnimator
+ XXX.minecraft.util.BinaryAnimator$EasingFunction
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.Brightness
- XXX.minecraft.util.ByIdMap
+ XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.ClassTreeIdRegistry
- XXX.minecraft.util.ColorRGBA
+ XXX.minecraft.util.CommonColors
- XXX.minecraft.util.CommonLinks
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DelegateDataOutput
+ XXX.minecraft.util.DependencySorter
- XXX.minecraft.util.DependencySorter$Entry
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.EncoderCache
- XXX.minecraft.util.EncoderCache$1
+ XXX.minecraft.util.EncoderCache$2
- XXX.minecraft.util.EncoderCache$Key
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.ExtraCodecs
+ XXX.minecraft.util.ExtraCodecs$1
- XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ XXX.minecraft.util.ExtraCodecs$2
- XXX.minecraft.util.ExtraCodecs$3
+ XXX.minecraft.util.ExtraCodecs$4
- XXX.minecraft.util.ExtraCodecs$5
+ XXX.minecraft.util.ExtraCodecs$6
- XXX.minecraft.util.ExtraCodecs$7
+ XXX.minecraft.util.ExtraCodecs$LateBoundIdMapper
- XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
+ XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
- XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.package-info
- XXX.minecraft.world.package-info
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
+ XXX.monster.breeze.Breeze
- XXX.monster.breeze.Breeze$1
+ XXX.monster.breeze.BreezeAi
- XXX.monster.breeze.BreezeAi$SlideToTargetSink
+ XXX.monster.breeze.BreezeUtil
- XXX.monster.breeze.LongJump
- XXX.monster.breeze.package-info
+ XXX.monster.breeze.Shoot
- XXX.monster.breeze.ShootWhenStuck
+ XXX.monster.breeze.Slide
+ XXX.monster.creaking.Creaking
- XXX.monster.creaking.Creaking$CreakingBodyRotationControl
+ XXX.monster.creaking.Creaking$CreakingJumpControl
- XXX.monster.creaking.Creaking$CreakingLookControl
+ XXX.monster.creaking.Creaking$CreakingMoveControl
- XXX.monster.creaking.Creaking$CreakingPathNavigation
+ XXX.monster.creaking.Creaking$HomeNodeEvaluator
- XXX.monster.creaking.CreakingAi
+ XXX.monster.creaking.CreakingAi$1
- XXX.monster.creaking.package-info
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.HoglinBase
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.AbstractPiglin
- XXX.monster.piglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.PiglinArmPose
- XXX.monster.piglin.PiglinBrute
+ XXX.monster.piglin.PiglinBruteAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
+ XXX.monster.piglin.StartAdmiringItemIfSeen
- XXX.monster.piglin.StartHuntingHoglin
+ XXX.monster.piglin.StopAdmiringIfItemTooFarAway
- XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ XXX.monster.warden.AngerLevel
- XXX.monster.warden.AngerManagement
+ XXX.monster.warden.AngerManagement$1
- XXX.monster.warden.AngerManagement$Sorter
- XXX.monster.warden.package-info
+ XXX.monster.warden.Warden
- XXX.monster.warden.Warden$1
+ XXX.monster.warden.Warden$1$1
- XXX.monster.warden.Warden$2
+ XXX.monster.warden.Warden$VibrationUser
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
- XXX.network.chat.ClickEvent$ChangePage
- XXX.network.chat.ClickEvent$OpenFile
- XXX.network.chat.ClickEvent$RunCommand
+ XXX.network.chat.HoverEvent$Action$1
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.HoverEvent$ShowItem
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
+ XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$1
- XXX.network.chat.SignedMessageChain$DecodeException
+ XXX.network.chat.SignedMessageChain$Decoder
- XXX.network.chat.SignedMessageChain$Encoder
+ XXX.network.chat.SignedMessageLink
- XXX.network.chat.SignedMessageValidator
+ XXX.network.chat.SignedMessageValidator$KeyBased
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$1Collector
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.SubStringSource
+ XXX.network.chat.TextColor
- XXX.network.chat.ThrowingComponent
- XXX.network.codec.ByteBufCodecs
+ XXX.network.codec.ByteBufCodecs$1
- XXX.network.codec.ByteBufCodecs$10
+ XXX.network.codec.ByteBufCodecs$11
- XXX.network.codec.ByteBufCodecs$12
+ XXX.network.codec.ByteBufCodecs$13
- XXX.network.codec.ByteBufCodecs$14
+ XXX.network.codec.ByteBufCodecs$15
- XXX.network.codec.ByteBufCodecs$16
+ XXX.network.codec.ByteBufCodecs$17
- XXX.network.codec.ByteBufCodecs$18
+ XXX.network.codec.ByteBufCodecs$19
- XXX.network.codec.ByteBufCodecs$2
+ XXX.network.codec.ByteBufCodecs$20
- XXX.network.codec.ByteBufCodecs$21
+ XXX.network.codec.ByteBufCodecs$22
- XXX.network.codec.ByteBufCodecs$23
+ XXX.network.codec.ByteBufCodecs$24
- XXX.network.codec.ByteBufCodecs$25
+ XXX.network.codec.ByteBufCodecs$26
- XXX.network.codec.ByteBufCodecs$27
+ XXX.network.codec.ByteBufCodecs$28
- XXX.network.codec.ByteBufCodecs$29
+ XXX.network.codec.ByteBufCodecs$3
- XXX.network.codec.ByteBufCodecs$30
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
+ XXX.network.codec.StreamCodec$13
- XXX.network.codec.StreamCodec$14
+ XXX.network.codec.StreamCodec$15
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
+ XXX.network.config.JoinWorldTask
- XXX.network.config.package-info
- XXX.network.config.ServerResourcePackConfigurationTask
+ XXX.network.config.SynchronizeRegistriesTask
- XXX.network.protocol.BundleDelimiterPacket
+ XXX.network.protocol.BundlePacket
- XXX.network.protocol.BundlerInfo
+ XXX.network.protocol.BundlerInfo$1
- XXX.network.protocol.BundlerInfo$1$1
+ XXX.network.protocol.BundlerInfo$Bundler
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketType
+ XXX.network.protocol.PacketUtils
- XXX.network.protocol.ProtocolCodecBuilder
+ XXX.network.protocol.ProtocolInfoBuilder
- XXX.network.protocol.ProtocolInfoBuilder$1
+ XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
- XXX.network.protocol.ProtocolInfoBuilder$Implementation
+ XXX.packrat.commands.Grammar
- XXX.packrat.commands.package-info
- XXX.packrat.commands.ResourceLocationParseRule
+ XXX.packrat.commands.ResourceLookupRule
- XXX.packrat.commands.ResourceSuggestion
+ XXX.packrat.commands.StringReaderParserState
- XXX.packrat.commands.StringReaderTerms
+ XXX.packrat.commands.StringReaderTerms$TerminalCharacter
- XXX.packrat.commands.StringReaderTerms$TerminalWord
+ XXX.packrat.commands.TagParseRule
+ XXX.packs.linkfs.DummyFileAttributes
- XXX.packs.linkfs.LinkFileSystem
+ XXX.packs.linkfs.LinkFileSystem$Builder
- XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
- XXX.packs.linkfs.LinkFSFileStore
+ XXX.packs.linkfs.LinkFSPath
- XXX.packs.linkfs.LinkFSPath$1
+ XXX.packs.linkfs.LinkFSPath$2
- XXX.packs.linkfs.LinkFSPath$3
+ XXX.packs.linkfs.LinkFSProvider
- XXX.packs.linkfs.LinkFSProvider$1
+ XXX.packs.linkfs.LinkFSProvider$2
- XXX.packs.linkfs.package-info
+ XXX.packs.linkfs.PathContents
- XXX.packs.linkfs.PathContents$1
+ XXX.packs.linkfs.PathContents$2
- XXX.packs.linkfs.PathContents$DirectoryContents
+ XXX.packs.linkfs.PathContents$FileContents
+ XXX.packs.metadata.MetadataSectionType
- XXX.packs.metadata.package-info
- XXX.packs.repository.BuiltInPackSource
+ XXX.packs.repository.BuiltInPackSource$1
- XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.FolderRepositorySource$FolderPackDetector
- XXX.packs.repository.KnownPack
+ XXX.packs.repository.Pack
- XXX.packs.repository.Pack$Metadata
+ XXX.packs.repository.Pack$Position
- XXX.packs.repository.Pack$ResourcesSupplier
- XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackDetector
+ XXX.packs.repository.PackRepository
- XXX.packs.repository.PackSource
+ XXX.packs.repository.PackSource$1
- XXX.packs.repository.RepositorySource
+ XXX.packs.repository.ServerPacksSource
+ XXX.packs.resources.CloseableResourceManager
- XXX.packs.resources.FallbackResourceManager
+ XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
- XXX.packs.resources.FallbackResourceManager$EntryStack
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- XXX.packs.resources.FallbackResourceManager$PackEntry
+ XXX.packs.resources.FallbackResourceManager$ResourceWithSource
- XXX.packs.resources.IoSupplier
+ XXX.packs.resources.MultiPackResourceManager
- XXX.packs.resources.package-info
- XXX.packs.resources.PreparableReloadListener
+ XXX.packs.resources.PreparableReloadListener$PreparationBarrier
- XXX.packs.resources.ProfiledReloadInstance
+ XXX.packs.resources.ProfiledReloadInstance$State
+ XXX.packs.resources.ReloadableResourceManager
- XXX.packs.resources.ReloadInstance
- XXX.packs.resources.Resource
+ XXX.packs.resources.ResourceFilterSection
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManager$Empty
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.ResourceMetadata
- XXX.packs.resources.ResourceMetadata$1
+ XXX.packs.resources.ResourceMetadata$2
- XXX.packs.resources.ResourceMetadata$Builder
+ XXX.packs.resources.ResourceMetadata$Builder$1
- XXX.packs.resources.ResourceProvider
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.parsing.packrat.Atom
+ XXX.parsing.packrat.Control
- XXX.parsing.packrat.Dictionary
+ XXX.parsing.packrat.ErrorCollector
- XXX.parsing.packrat.ErrorCollector$LongestOnly
+ XXX.parsing.packrat.ErrorEntry
+ XXX.parsing.packrat.package-info
- XXX.parsing.packrat.ParseState
+ XXX.parsing.packrat.ParseState$CacheEntry
- XXX.parsing.packrat.ParseState$CacheKey
+ XXX.parsing.packrat.Rule
- XXX.parsing.packrat.Rule$RuleAction
+ XXX.parsing.packrat.Rule$SimpleRuleAction
- XXX.parsing.packrat.Rule$WrappedTerm
+ XXX.parsing.packrat.Scope
- XXX.parsing.packrat.SuggestionSupplier
+ XXX.parsing.packrat.Term
- XXX.parsing.packrat.Term$1
+ XXX.parsing.packrat.Term$2
- XXX.parsing.packrat.Term$Alternative
+ XXX.parsing.packrat.Term$Marker
- XXX.parsing.packrat.Term$Maybe
+ XXX.parsing.packrat.Term$Reference
- XXX.parsing.packrat.Term$Sequence
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$1
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.MinecartCollisionContext
- XXX.phys.shapes.MinecartCollisionContext$1
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.pools.alias.Direct
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.Random
+ XXX.pools.alias.RandomGroup
- XXX.profiling.jfr.Environment
+ XXX.profiling.jfr.JfrProfiler
- XXX.profiling.jfr.JfrProfiler$1
+ XXX.profiling.jfr.JvmProfiler
- XXX.profiling.jfr.JvmProfiler$NoOpProfiler
- XXX.profiling.jfr.package-info
+ XXX.profiling.jfr.Percentiles
- XXX.profiling.jfr.SummaryReporter
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
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
- XXX.protocol.common.ClientboundCustomPayloadPacket
+ XXX.protocol.common.ClientboundCustomReportDetailsPacket
- XXX.protocol.common.ClientboundDisconnectPacket
+ XXX.protocol.common.ClientboundKeepAlivePacket
- XXX.protocol.common.ClientboundPingPacket
+ XXX.protocol.common.ClientboundResourcePackPopPacket
- XXX.protocol.common.ClientboundResourcePackPushPacket
+ XXX.protocol.common.ClientboundServerLinksPacket
- XXX.protocol.common.ClientboundStoreCookiePacket
+ XXX.protocol.common.ClientboundTransferPacket
- XXX.protocol.common.ClientboundUpdateTagsPacket
+ XXX.protocol.common.ClientCommonPacketListener
+ XXX.protocol.common.CommonPacketTypes
+ XXX.protocol.common.package-info
+ XXX.protocol.common.ServerboundClientInformationPacket
- XXX.protocol.common.ServerboundCustomPayloadPacket
+ XXX.protocol.common.ServerboundKeepAlivePacket
- XXX.protocol.common.ServerboundPongPacket
+ XXX.protocol.common.ServerboundResourcePackPacket
- XXX.protocol.common.ServerboundResourcePackPacket$Action
- XXX.protocol.common.ServerCommonPacketListener
+ XXX.protocol.configuration.ClientboundFinishConfigurationPacket
- XXX.protocol.configuration.ClientboundRegistryDataPacket
+ XXX.protocol.configuration.ClientboundResetChatPacket
- XXX.protocol.configuration.ClientboundSelectKnownPacks
+ XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
- XXX.protocol.configuration.ClientConfigurationPacketListener
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
- XXX.protocol.game.ClientGamePacketListener
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
+ XXX.providers.number.EnchantmentLevelProvider
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.StorageValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
+ XXX.rule.blockentity.AppendLoot
- XXX.rule.blockentity.AppendStatic
+ XXX.rule.blockentity.Clear
+ XXX.rule.blockentity.package-info
- XXX.rule.blockentity.Passthrough
+ XXX.rule.blockentity.RuleBlockEntityModifier
- XXX.rule.blockentity.RuleBlockEntityModifierType
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecorationType
- XXX.saveddata.maps.MapDecorationTypes
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapId
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.server.commands.FillCommand$Affector
- XXX.server.commands.FillCommand$Filter
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.FillCommand$NullableCommandFunction
- XXX.server.commands.package-info
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpawnArmorTrimsCommand
+ XXX.server.commands.SpectateCommand
- XXX.server.commands.SpreadPlayersCommand
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
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
+ XXX.server.level.ChunkGenerationTask
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkLevel
- XXX.server.level.ChunkLevel$1
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkResult
+ XXX.server.level.ChunkResult$Fail
- XXX.server.level.ChunkResult$Success
+ XXX.server.level.ChunkTaskDispatcher
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueue$TasksForChunk
- XXX.server.level.ChunkTracker
+ XXX.server.level.ChunkTrackingView
- XXX.server.level.ChunkTrackingView$1
+ XXX.server.level.ChunkTrackingView$Positioned
- XXX.server.level.ClientInformation
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.package-info
- XXX.server.level.ParticleStatus
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.SimulationChunkTracker
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.ThrottlingChunkTaskDispatcher
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.TicketType$TicketUse
+ XXX.server.level.WorldGenRegion
+ XXX.server.network.CommonListenerCookie
- XXX.server.network.ConfigurationTask
+ XXX.server.network.ConfigurationTask$Type
- XXX.server.network.Filterable
+ XXX.server.network.FilteredText
- XXX.server.network.LegacyProtocolUtils
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.LegacyTextFilter
+ XXX.server.network.LegacyTextFilter$1
- XXX.server.network.LegacyTextFilter$JoinOrLeaveEncoder
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
- XXX.server.network.PlayerChunkSender
+ XXX.server.network.PlayerSafetyServiceTextFilter
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
- XXX.server.network.ServerTextFilter
+ XXX.server.network.ServerTextFilter$IgnoreStrategy
- XXX.server.network.ServerTextFilter$MessageEncoder
+ XXX.server.network.ServerTextFilter$PlayerContext
- XXX.server.network.ServerTextFilter$RequestFailedException
+ XXX.server.network.TextFilter
- XXX.server.network.TextFilter$1
+ XXX.server.packs.AbstractPackResources
- XXX.server.packs.BuiltInMetadata
+ XXX.server.packs.CompositePackResources
- XXX.server.packs.DownloadCacheCleaner
+ XXX.server.packs.DownloadCacheCleaner$1
- XXX.server.packs.DownloadCacheCleaner$PathAndPriority
+ XXX.server.packs.DownloadCacheCleaner$PathAndTime
- XXX.server.packs.DownloadQueue
+ XXX.server.packs.DownloadQueue$BatchConfig
- XXX.server.packs.DownloadQueue$BatchResult
+ XXX.server.packs.DownloadQueue$DownloadRequest
- XXX.server.packs.DownloadQueue$FileInfoEntry
+ XXX.server.packs.DownloadQueue$LogEntry
- XXX.server.packs.FeatureFlagsMetadataSection
+ XXX.server.packs.FilePackResources
- XXX.server.packs.FilePackResources$FileResourcesSupplier
+ XXX.server.packs.FilePackResources$SharedZipFileAccess
- XXX.server.packs.OverlayMetadataSection
+ XXX.server.packs.OverlayMetadataSection$OverlayEntry
+ XXX.server.packs.package-info
- XXX.server.packs.PackLocationInfo
+ XXX.server.packs.PackResources
- XXX.server.packs.PackResources$ResourceOutput
+ XXX.server.packs.PackSelectionConfig
- XXX.server.packs.PackType
+ XXX.server.packs.PathPackResources
- XXX.server.packs.PathPackResources$PathResourcesSupplier
+ XXX.server.packs.VanillaPackResources
- XXX.server.packs.VanillaPackResourcesBuilder
+ XXX.server.players.BanListEntry
- XXX.server.players.GameProfileCache
+ XXX.server.players.GameProfileCache$1
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
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
- XXX.state.properties.ComparatorMode
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ContainerComponentManipulator
+ XXX.storage.loot.ContainerComponentManipulators
- XXX.storage.loot.ContainerComponentManipulators$1
+ XXX.storage.loot.ContainerComponentManipulators$2
- XXX.storage.loot.ContainerComponentManipulators$3
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootDataType
- XXX.storage.loot.LootDataType$Validator
+ XXX.storage.loot.LootParams
- XXX.storage.loot.LootParams$Builder
+ XXX.storage.loot.LootParams$DynamicDrop
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.package-info
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
+ XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.StructurePlacement
+ XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReducer
+ XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.DimensionPadding
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
+ XXX.structure.templatesystem.LiquidSettings
- XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.ProtectedBlockProcessor
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$JigsawBlockInfo
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.StructureTemplateManager
+ XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- XXX.structure.templatesystem.StructureTemplateManager$Source
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
- XXX.util.datafix.DataFixTypes$1
- XXX.util.datafix.ExtraDataFixUtils
+ XXX.util.datafix.FixWolfHealth
- XXX.util.datafix.LegacyComponentDataFixUtils
+ XXX.util.debugchart.AbstractSampleLogger
- XXX.util.debugchart.DebugSampleSubscriptionTracker
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
+ XXX.util.debugchart.LocalSampleLogger
+ XXX.util.debugchart.package-info
- XXX.util.debugchart.RemoteDebugSampleType
+ XXX.util.debugchart.RemoteSampleLogger
- XXX.util.debugchart.SampleLogger
+ XXX.util.debugchart.SampleStorage
- XXX.util.debugchart.TpsDebugDimensions
- XXX.util.eventlog.EventLogDirectory
+ XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$File
+ XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$FileList
+ XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog
+ XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader
+ XXX.util.eventlog.JsonEventLogReader$1
- XXX.util.eventlog.package-info
+ XXX.util.parsing.package-info
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
- XXX.util.profiling.Profiler
+ XXX.util.profiling.Profiler$Scope
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$CombinedProfileFiller
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.profiling.TracyZoneFiller
- XXX.util.profiling.TracyZoneFiller$PlotAndValue
+ XXX.util.profiling.Zone
+ XXX.util.random.SimpleWeightedRandomList
+ XXX.util.random.Weight
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedList
- XXX.util.random.WeightedList$Compact
- XXX.util.random.WeightedList$Selector
+ XXX.util.random.WeightedRandom
+ XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiRecord$Packed
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiSection$Packed
+ XXX.village.poi.PoiType
- XXX.village.poi.PoiTypes
+ XXX.world.entity.Display$RenderState
- XXX.world.entity.Display$TextDisplay
+ XXX.world.entity.Display$TextDisplay$Align
- XXX.world.entity.Display$TextDisplay$CachedInfo
+ XXX.world.entity.Display$TextDisplay$CachedLine
- XXX.world.entity.Display$TextDisplay$LineSplitter
+ XXX.world.entity.Display$TextDisplay$TextRenderState
- XXX.world.entity.Display$TransformationInterpolator
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySpawnReason
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.EquipmentSlotGroup
+ XXX.world.entity.EquipmentSlotGroup$1
- XXX.world.entity.EquipmentTable
+ XXX.world.entity.EquipmentUser
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.Interaction
- XXX.world.entity.Interaction$PlayerAction
- XXX.world.entity.InterpolationHandler$InterpolationData
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.Leashable
- XXX.world.entity.Leashable$LeashData
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OminousItemSpawner
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.package-info
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.PortalProcessor
+ XXX.world.entity.Pose
- XXX.world.entity.PositionMoveRotation
+ XXX.world.entity.Relative
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SlotAccess$4
- XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacementType
- XXX.world.entity.SpawnPlacementTypes
+ XXX.world.entity.SpawnPlacementTypes$1
+ XXX.world.entity.TamableAnimal
- XXX.world.entity.TamableAnimal$TamableAnimalPanicGoal
+ XXX.world.entity.Targeting
- XXX.world.entity.TraceableEntity
+ XXX.world.entity.VariantHolder
- XXX.world.entity.WalkAnimationState
+ XXX.world.flag.FeatureElement
- XXX.world.flag.FeatureFlag
+ XXX.world.flag.FeatureFlagRegistry
- XXX.world.flag.FeatureFlagRegistry$Builder
+ XXX.world.flag.FeatureFlags
+ XXX.world.flag.FeatureFlagSet
- XXX.world.flag.FeatureFlagUniverse
- XXX.world.flag.package-info
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AbstractCraftingMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AbstractFurnaceMenu$1
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.ArmorSlot
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
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.ItemCombinerMenu$3
+ XXX.world.inventory.ItemCombinerMenu$4
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
+ XXX.world.inventory.RecipeBookMenu$PostPlaceAction
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeCraftingHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SlotRange
+ XXX.world.inventory.SlotRange$1
- XXX.world.inventory.SlotRanges
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
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.EitherHolder
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.InkSacItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$Properties
+ XXX.world.item.Item$TooltipContext
- XXX.world.item.Item$TooltipContext$1
+ XXX.world.item.Item$TooltipContext$2
- XXX.world.item.Item$TooltipContext$3
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStack$4
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUseAnimation
+ XXX.world.item.ItemUtils
+ XXX.world.item.JukeboxPlayable
- XXX.world.item.JukeboxSong
+ XXX.world.item.JukeboxSongPlayer
- XXX.world.item.JukeboxSongPlayer$OnSongChanged
+ XXX.world.item.JukeboxSongs
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MaceItem
- XXX.world.item.MapItem
+ XXX.world.item.MapItem$1
- XXX.world.item.MinecartItem
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
- XXX.world.item.package-info
+ XXX.world.item.PickaxeItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.TippedArrowItem
- XXX.world.item.ToolMaterial
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.ChunkPos
+ XXX.world.level.ChunkPos$1
- XXX.world.level.ChunkPos$2
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
+ XXX.world.level.EmptyBlockAndTintGetter
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EntityBasedExplosionDamageCalculator
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.ExplosionDamageCalculator
- XXX.world.level.FoliageColor
+ XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.package-info
- XXX.world.level.TicketStorage$ChunkUpdated
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.phys.Vec3$1
+ XXX.world.scores.DisplaySlot
- XXX.world.scores.DisplaySlot$1
+ XXX.world.scores.Objective
+ XXX.world.scores.package-info
- XXX.world.scores.PlayerScoreEntry
+ XXX.world.scores.PlayerScores
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.ReadOnlyScoreInfo
- XXX.world.scores.Score
+ XXX.world.scores.ScoreAccess
- XXX.world.scores.Scoreboard
+ XXX.world.scores.Scoreboard$1
- XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.ScoreHolder
+ XXX.world.scores.ScoreHolder$1
- XXX.world.scores.ScoreHolder$2
+ XXX.world.scores.ScoreHolder$3
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
- XXX.world.ticks.BlackholeTickAccess
+ XXX.world.ticks.BlackholeTickAccess$1
- XXX.world.ticks.BlackholeTickAccess$2
+ XXX.world.ticks.ContainerSingleItem
- XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
+ XXX.world.ticks.LevelChunkTicks
- XXX.world.ticks.LevelTickAccess
+ XXX.world.ticks.LevelTicks
- XXX.world.ticks.LevelTicks$PosAndContainerConsumer
+ XXX.world.ticks.package-info
+ XXX.world.ticks.ProtoChunkTicks
- XXX.world.ticks.SavedTick
+ XXX.world.ticks.SavedTick$1
- XXX.world.ticks.ScheduledTick
+ XXX.world.ticks.ScheduledTick$1
- XXX.world.ticks.SerializableTickContainer
+ XXX.world.ticks.TickAccess
- XXX.world.ticks.TickContainerAccess
+ XXX.world.ticks.TickPriority
- XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.Direction$Axis$1 +1M
```
```
XXX.minecraft.core.Direction$Axis$3 +1M
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.worldgen.features.TreeFeatures +1M | +7P -2P
```
```
XXX.worldgen.placement.VegetationPlacements +5P -1P
```
```
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.gametest.framework.TestFunction +1M
```
```
XXX.network.chat.ClickEvent +1M -9M | +1P -2P
```
```
XXX.network.chat.ComponentSerialization +1M -1M | -1P
```
```
XXX.network.chat.HoverEvent +1M -8M | +1P -1P
```
```
XXX.protocol.game.ClientboundMoveEntityPacket +2M -2M
```
```
XXX.protocol.game.ClientboundUpdateAdvancementsPacket +2M -1M | +1P
```
```
XXX.protocol.game.GamePacketTypes -1P
```
```
XXX.protocol.game.ServerboundSetStructureBlockPacket +2M -1M | +2P
```
```
XXX.network.syncher.EntityDataSerializers +2P -1P
```
```
XXX.server.commands.AdvancementCommands +1M
```
```
XXX.server.commands.CloneCommands +18M -20M
```
```
XXX.server.commands.OpCommand +1M -1M
```
```
XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker -1M
```
```
XXX.server.level.ServerPlayer +1M -1M
```
```
XXX.minecraft.util.Unit +1P
```
```
XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix +5M -4M
```
```
XXX.datafix.fixes.BlockEntityCustomNameToComponentFix +4M -3M | +1P
```
```
XXX.datafix.fixes.ItemCustomNameToComponentFix +5M -3M
```
```
XXX.datafix.fixes.ItemLoreFix +6M -7M
```
```
XXX.datafix.fixes.ObjectiveRenderTypeFix +1M -1M
```
```
XXX.datafix.fixes.OminousBannerRarityFix +8M -6M
```
```
XXX.datafix.fixes.References +2P -1P
```
```
XXX.datafix.schemas.V1451_6 +1M -1M
```
```
XXX.util.valueproviders.WeightedListInt +2M -2M | +1P -1P
```
```
XXX.minecraft.world.Clearable -1M
```
```
XXX.world.effect.MobEffectInstance +7M -3M
```
```
XXX.world.effect.MobEffects +10P -10P
```
```
XXX.world.entity.AreaEffectCloud +2M -2M | +1P
```
```
XXX.world.entity.EntityAttachments$Builder +1M
```
```
XXX.world.entity.EntityEvent +1P
```
```
XXX.entity.animal.Sheep +2M -3M
```
```
XXX.world.item.DebugStickItem +1M -1M
```
```
XXX.world.item.SolidBucketItem +1M -1M
```
```
XXX.item.crafting.SmithingTransformRecipe$Serializer +2M -2M
```
```
XXX.item.crafting.TransmuteRecipe +1M -1M | +1P -1P
```
```
XXX.world.level.LevelAccessor +2M -2M | +2P -2P
```
```
XXX.world.level.NaturalSpawner +1M -1M
```
```
XXX.level.biome.Biome +1M
```
```
XXX.level.biome.MobSpawnSettings$Builder +3M -4M
```
```
XXX.level.biome.MobSpawnSettings$SpawnerData +6M -2M | +1P -1P
```
```
XXX.level.block.BeetrootBlock +1M | +1P -1P
```
```
XXX.level.block.BigDripleafStemBlock +1P -5P
```
```
XXX.level.block.CactusBlock +2P -3P
```
```
XXX.level.block.CandleBlock +1M -1M | +1P -4P
```
```
XXX.level.block.CeilingHangingSignBlock +1M | +2P -3P
```
```
XXX.level.block.ConduitBlock -1P
```
```
XXX.level.block.CoralPlantBlock -1P
```
```
XXX.level.block.CrafterBlock +1M -1M
```
```
XXX.level.block.CropBlock +1M | +1P -1P
```
```
XXX.level.block.DecoratedPotBlock +1M -1M | +1P -1P
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.DoorBlock$1 -1P
```
```
XXX.level.block.EndPortalFrameBlock +2P -3P
```
```
XXX.level.block.FenceGateBlock +2M | +6P -12P
```
```
XXX.level.block.FireBlock +2M -2M | +1P -6P
```
```
XXX.level.block.HangingMossBlock +2P -3P
```
```
XXX.level.block.LeverBlock +3M -1M | +1P -11P
```
```
XXX.level.block.PiglinWallSkullBlock +1P -1P
```
```
XXX.level.block.ScaffoldingBlock +4P -4P
```
```
XXX.level.block.SculkShriekerBlock +2M -4M | +1P -1P
```
```
XXX.level.block.SeagrassBlock +1M -1M | -1P
```
```
XXX.level.block.SoundType +2P
```
```
XXX.level.block.StemBlock +1M | +1P -2P
```
```
XXX.level.block.StructureVoidBlock -1P
```
```
XXX.level.block.SupportType$2 -1P
```
```
XXX.level.block.TallSeagrassBlock +1M -1M | -1P
```
```
XXX.level.block.TrapDoorBlock$1 -1P
```
```
XXX.level.block.WallSignBlock +1P -4P
```
```
XXX.level.block.WallTorchBlock +1P -2P
```
```
XXX.block.entity.BrushableBlockEntity +4M -4M
```
```
XXX.block.entity.CreakingHeartBlockEntity +2M
```
```
XXX.block.entity.LecternBlockEntity +1M
```
```
XXX.block.entity.SculkShriekerBlockEntity +1M
```
```
XXX.block.entity.StructureBlockEntity +2M | +1P
```
```
XXX.entity.trialspawner.TrialSpawnerConfig$Builder +2M -2M | +2P -2P
```
```
XXX.entity.trialspawner.TrialSpawnerState +1M -1M
```
```
XXX.block.piston.MovingPistonBlock -1M
```
```
XXX.block.piston.PistonBaseBlock$1 -1P
```
```
XXX.level.chunk.ChunkSource +2M -1M
```
```
XXX.level.chunk.EmptyLevelChunk +1M -1M
```
```
XXX.level.chunk.LevelChunk +1M -1M
```
```
XXX.level.chunk.ProtoChunk +1M -1M
```

</details>
<details>
<summary>
net.minecraft.core.Direction$Axis$1
</summary>

```diff
- boolean choose(boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.core.Direction$Axis$3
</summary>

```diff
- boolean choose(boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.TreeFeatures
</summary>

```diff
- TreeConfiguration$TreeConfigurationBuilder createDarkOak()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void tickBlock(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.TestFunction
</summary>

```diff
- void <init>(String,String,String,Rotation,int,long,boolean,boolean,Consumer)
```

</details>
<details>
<summary>
net.minecraft.network.chat.ClickEvent
</summary>

```diff
+ App lambda$static$2(RecordCodecBuilder$Instance)
+ boolean equals(Object)
+ ClickEvent$Action getAction()
+ ClickEvent$Action lambda$static$0(ClickEvent)
+ int hashCode()
- MapCodec lambda$static$0(ClickEvent$Action)
+ String getValue()
+ String lambda$static$1(ClickEvent)
+ String toString()
+ void <init>(ClickEvent$Action,String)
```

</details>
<details>
<summary>
net.minecraft.network.chat.ComponentSerialization
</summary>

```diff
+ Codec flatCodec(int)
- Codec flatRestrictedCodec(int)
```

</details>
<details>
<summary>
net.minecraft.network.chat.HoverEvent
</summary>

```diff
+ boolean equals(Object)
+ HoverEvent$Action getAction()
+ HoverEvent$TypedHoverEvent lambda$static$0(HoverEvent)
+ int hashCode()
- MapCodec lambda$static$0(HoverEvent$Action)
+ Object getValue(HoverEvent$Action)
+ String toString()
+ void <init>(HoverEvent$Action,Object)
+ void <init>(HoverEvent$TypedHoverEvent)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
</summary>

```diff
+ float getxRot()
- float getXRot()
+ float getyRot()
- float getYRot()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
</summary>

```diff
- boolean shouldShowAdvancements()
- void <init>(boolean,Collection,Set,Map,boolean)
+ void <init>(boolean,Collection,Set,Map)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
</summary>

```diff
- boolean isStrict()
- void <init>(BlockPos,StructureBlockEntity$UpdateType,StructureMode,String,BlockPos,Vec3i,Mirror,Rotation,String,boolean,boolean,boolean,boolean,float,long)
+ void <init>(BlockPos,StructureBlockEntity$UpdateType,StructureMode,String,BlockPos,Vec3i,Mirror,Rotation,String,boolean,boolean,boolean,float,long)
```

</details>
<details>
<summary>
net.minecraft.server.commands.AdvancementCommands
</summary>

```diff
- int perform(CommandSourceStack,Collection,AdvancementCommands$Action,Collection,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.commands.CloneCommands
</summary>

```diff
+ ArgumentBuilder destinationAndModeSuffix(CommandBuildContext,CloneCommands$CommandFunction,CloneCommands$CommandFunction)
- ArgumentBuilder destinationAndStrictSuffix(CommandBuildContext,CloneCommands$CommandFunction,CloneCommands$CommandFunction)
- ArgumentBuilder modeSuffix(CommandBuildContext,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,ArgumentBuilder)
+ ArgumentBuilder wrapWithCloneMode(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,ArgumentBuilder)
- ArgumentBuilder wrapWithCloneMode(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,ArgumentBuilder)
+ boolean lambda$destinationAndModeSuffix$10(BlockInWorld)
+ boolean lambda$destinationAndModeSuffix$12(BlockInWorld)
+ boolean lambda$destinationAndModeSuffix$14(BlockInWorld)
- boolean lambda$modeSuffix$10(BlockInWorld)
- boolean lambda$modeSuffix$12(BlockInWorld)
+ CloneCommands$DimensionAndPosition lambda$destinationAndModeSuffix$7(CloneCommands$CommandFunction,CommandContext)
+ CloneCommands$DimensionAndPosition lambda$destinationAndModeSuffix$8(CloneCommands$CommandFunction,CommandContext)
+ CloneCommands$DimensionAndPosition lambda$destinationAndModeSuffix$9(CloneCommands$CommandFunction,CommandContext)
- CloneCommands$DimensionAndPosition lambda$destinationAndStrictSuffix$7(CloneCommands$CommandFunction,CommandContext)
- CloneCommands$DimensionAndPosition lambda$destinationAndStrictSuffix$8(CloneCommands$CommandFunction,CommandContext)
- CloneCommands$DimensionAndPosition lambda$destinationAndStrictSuffix$9(CloneCommands$CommandFunction,CommandContext)
- Component lambda$clone$20(int)
+ Component lambda$clone$23(int)
- int clone(CommandSourceStack,CloneCommands$DimensionAndPosition,CloneCommands$DimensionAndPosition,CloneCommands$DimensionAndPosition,Predicate,CloneCommands$Mode,boolean)
+ int clone(CommandSourceStack,CloneCommands$DimensionAndPosition,CloneCommands$DimensionAndPosition,CloneCommands$DimensionAndPosition,Predicate,CloneCommands$Mode)
+ int lambda$destinationAndModeSuffix$11(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$destinationAndModeSuffix$15(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$destinationAndModeSuffix$17(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$destinationAndModeSuffix$19(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
- int lambda$modeSuffix$11(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
- int lambda$wrapWithCloneMode$16(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
- int lambda$wrapWithCloneMode$17(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
- int lambda$wrapWithCloneMode$18(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
- int lambda$wrapWithCloneMode$19(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
+ int lambda$wrapWithCloneMode$20(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$wrapWithCloneMode$21(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$wrapWithCloneMode$22(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ Predicate lambda$destinationAndModeSuffix$13(CommandContext)
+ Predicate lambda$destinationAndModeSuffix$16(CommandContext)
+ Predicate lambda$destinationAndModeSuffix$18(CommandContext)
- Predicate lambda$modeSuffix$13(CommandContext)
- Predicate lambda$modeSuffix$14(CommandContext)
- Predicate lambda$modeSuffix$15(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.OpCommand
</summary>

```diff
+ Component lambda$opPlayers$5(Collection)
- Component lambda$opPlayers$5(GameProfile)
```

</details>
<details>
<summary>
net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
</summary>

```diff
+ void dumpChunks(String)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- void removeVehicle()
+ void stopRiding()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
</summary>

```diff
+ boolean lambda$fix$1(String)
- boolean lambda$fix$2(String)
+ Dynamic lambda$fix$2(OptionalDynamic,Dynamic)
- Dynamic lambda$fix$3(Optional,Dynamic)
- Optional lambda$fix$1(OpticFinder,Typed)
- Typed fix(Typed,OpticFinder,OpticFinder)
+ Typed fix(Typed,OpticFinder)
- Typed lambda$makeRule$0(TaggedChoice$TaggedChoiceType,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$0(TaggedChoice$TaggedChoiceType,OpticFinder,Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
</summary>

```diff
- Dynamic fixTagCustomName(Dynamic)
+ Dynamic lambda$makeRule$0(Typed,OpticFinder,Dynamic)
- Typed lambda$makeRule$0(OpticFinder,Type,Type,Typed)
+ Typed lambda$makeRule$1(OpticFinder,Typed)
- void <clinit>()
+ void <init>(Schema,boolean)
- void <init>(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Pair lambda$makeRule$0(Pair)
+ Typed lambda$makeRule$0(Typed)
- Typed lambda$makeRule$2(OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$3(OpticFinder,OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$4(OpticFinder,OpticFinder,OpticFinder,OpticFinder,Typed)
+ void <init>(Schema,boolean)
- void <init>(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemLoreFix
</summary>

```diff
+ Dynamic lambda$makeRule$0(Dynamic)
+ Dynamic lambda$makeRule$1(Dynamic)
+ Dynamic lambda$makeRule$2(Dynamic)
- Pair lambda$makeRule$0(Pair)
+ Stream fixLoreList(Stream)
- Typed lambda$makeRule$1(OpticFinder,Typed)
- Typed lambda$makeRule$2(OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$3(OpticFinder,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$3(Typed)
- Typed lambda$makeRule$4(OpticFinder,OpticFinder,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$4(OpticFinder,Typed)
+ void <init>(Schema,boolean)
- void <init>(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
</summary>

```diff
+ void <init>(Schema,boolean)
- void <init>(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OminousBannerRarityFix
</summary>

```diff
+ boolean lambda$fix$2(String)
- boolean lambda$fix$3(String)
+ Dynamic lambda$fix$3(Dynamic)
- Dynamic lambda$fix$5(Dynamic)
- Optional lambda$fix$2(OpticFinder,Typed)
- Typed fix(Typed,OpticFinder,OpticFinder,OpticFinder)
+ Typed fix(Typed,OpticFinder)
- Typed lambda$fix$4(OpticFinder,Typed)
+ Typed lambda$fix$4(Typed)
- Typed lambda$fix$6(OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$0(TaggedChoice$TaggedChoiceType,OpticFinder,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$0(TaggedChoice$TaggedChoiceType,OpticFinder,Typed)
- Typed lambda$makeRule$1(OpticFinder,OpticFinder,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$1(OpticFinder,OpticFinder,Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1451_6
</summary>

```diff
- TypeTemplate lambda$registerTypes$2(Map,Schema)
+ TypeTemplate lambda$registerTypes$2(Map)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.WeightedListInt
</summary>

```diff
+ SimpleWeightedRandomList lambda$static$0(WeightedListInt)
+ void <init>(SimpleWeightedRandomList)
- void <init>(WeightedList)
- WeightedList lambda$static$0(WeightedListInt)
```

</details>
<details>
<summary>
net.minecraft.world.Clearable
</summary>

```diff
+ void tryClear(Object)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
- boolean downgradeToHiddenEffect()
+ boolean tick(LivingEntity,Runnable)
- boolean tickServer(ServerLevel,LivingEntity,Runnable)
+ int lambda$tickDownDuration$2(int)
- int lambda$tickDownDuration$3(int)
- int lambda$withScaledDuration$2(float,int)
+ int tickDownDuration()
- MobEffectInstance withScaledDuration(float)
- void tickClient()
- void tickDownDuration()
```

</details>
<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
+ int lambda$serverTick$1(int)
- void lambda$readAdditionalSaveData$1(String)
+ void lambda$readAdditionalSaveData$3(String)
- void setPotionDurationScale(float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityAttachments$Builder
</summary>

```diff
- List lambda$build$1(float,float,EntityAttachment)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Sheep
</summary>

```diff
- boolean lambda$registerGoals$0(ItemStack)
+ boolean lambda$registerGoals$1(ItemStack)
+ DyeColor lambda$static$0(DyeColor)
- void lambda$shear$1(ServerLevel,ItemStack)
+ void lambda$shear$2(ServerLevel,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.DebugStickItem
</summary>

```diff
+ boolean canAttackBlock(BlockState,Level,BlockPos,Player)
- boolean canDestroyBlock(ItemStack,BlockState,Level,BlockPos,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.SolidBucketItem
</summary>

```diff
- boolean emptyContents(LivingEntity,Level,BlockPos,BlockHitResult)
+ boolean emptyContents(Player,Level,BlockPos,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
</summary>

```diff
+ ItemStack lambda$static$3(SmithingTransformRecipe)
+ ItemStack lambda$static$8(SmithingTransformRecipe)
- TransmuteResult lambda$static$3(SmithingTransformRecipe)
- TransmuteResult lambda$static$8(SmithingTransformRecipe)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.TransmuteRecipe
</summary>

```diff
+ void <init>(String,CraftingBookCategory,Ingredient,Ingredient,Holder)
- void <init>(String,CraftingBookCategory,Ingredient,Ingredient,TransmuteResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
+ void blockUpdated(BlockPos,Block)
- void playSound(Entity,BlockPos,SoundEvent,SoundSource)
+ void playSound(Player,BlockPos,SoundEvent,SoundSource)
- void updateNeighborsAt(BlockPos,Block)
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
- WeightedList mobsAt(ServerLevel,StructureManager,ChunkGenerator,MobCategory,BlockPos,Holder)
+ WeightedRandomList mobsAt(ServerLevel,StructureManager,ChunkGenerator,MobCategory,BlockPos,Holder)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
- int getBaseGrassColor()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$Builder
</summary>

```diff
+ List lambda$new$1(MobCategory)
+ MobCategory lambda$new$0(MobCategory)
- MobSpawnSettings$Builder addSpawn(MobCategory,int,MobSpawnSettings$SpawnerData)
+ MobSpawnSettings$Builder addSpawn(MobCategory,MobSpawnSettings$SpawnerData)
- WeightedList lambda$build$1(Map$Entry)
- WeightedList$Builder lambda$new$0(MobCategory)
+ WeightedRandomList lambda$build$2(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
</summary>

```diff
- boolean equals(Object)
- EntityType type()
- int hashCode()
- int maxCount()
- int minCount()
+ void <init>(EntityType,int,int,int)
- void <init>(EntityType,int,int)
+ void <init>(EntityType,Weight,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeetrootBlock
</summary>

```diff
- VoxelShape lambda$static$0(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleBlock
</summary>

```diff
+ Int2ObjectMap lambda$static$1()
- void lambda$static$1(Int2ObjectOpenHashMap)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CeilingHangingSignBlock
</summary>

```diff
- Integer lambda$static$1(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
- void affectNeighborsAfterRemoval(BlockState,ServerLevel,BlockPos,boolean)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CropBlock
</summary>

```diff
- VoxelShape lambda$static$0(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DecoratedPotBlock
</summary>

```diff
- void affectNeighborsAfterRemoval(BlockState,ServerLevel,BlockPos,boolean)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
- void affectNeighborsAfterRemoval(BlockState,ServerLevel,BlockPos,boolean)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceGateBlock
</summary>

```diff
- VoxelShape lambda$static$2(VoxelShape)
- VoxelShape lambda$static$3(VoxelShape)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FireBlock
</summary>

```diff
+ boolean lambda$new$1(BlockState)
- Function makeShapes()
+ VoxelShape calculateShape(BlockState)
- VoxelShape lambda$makeShapes$1(Map,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
- Function makeShapes()
- void affectNeighborsAfterRemoval(BlockState,ServerLevel,BlockPos,boolean)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
- VoxelShape lambda$makeShapes$0(Map,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
- void lambda$getTicker$2(Level,BlockPos,BlockState,SculkShriekerBlockEntity)
+ void lambda$getTicker$3(Level,BlockPos,BlockState,SculkShriekerBlockEntity)
+ void lambda$onRemove$1(ServerLevel,SculkShriekerBlockEntity)
- void lambda$tick$1(ServerLevel,SculkShriekerBlockEntity)
+ void lambda$tick$2(ServerLevel,SculkShriekerBlockEntity)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SeagrassBlock
</summary>

```diff
- boolean canPlaceLiquid(LivingEntity,BlockGetter,BlockPos,BlockState,Fluid)
+ boolean canPlaceLiquid(Player,BlockGetter,BlockPos,BlockState,Fluid)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StemBlock
</summary>

```diff
- VoxelShape lambda$static$4(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TallSeagrassBlock
</summary>

```diff
- boolean canPlaceLiquid(LivingEntity,BlockGetter,BlockPos,BlockState,Fluid)
+ boolean canPlaceLiquid(Player,BlockGetter,BlockPos,BlockState,Fluid)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BrushableBlockEntity
</summary>

```diff
- boolean brush(long,ServerLevel,LivingEntity,Direction,ItemStack)
+ boolean brush(long,ServerLevel,Player,Direction,ItemStack)
- void brushingCompleted(ServerLevel,LivingEntity,ItemStack)
+ void brushingCompleted(ServerLevel,Player,ItemStack)
- void dropContent(ServerLevel,LivingEntity,ItemStack)
+ void dropContent(ServerLevel,Player,ItemStack)
- void unpackLootTable(ServerLevel,LivingEntity,ItemStack)
+ void unpackLootTable(ServerLevel,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.CreakingHeartBlockEntity
</summary>

```diff
- BlockState updateCreakingState(Level,BlockState,BlockPos,CreakingHeartBlockEntity)
- void preRemoveSideEffects(BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.LecternBlockEntity
</summary>

```diff
- void preRemoveSideEffects(BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
</summary>

```diff
- void preRemoveSideEffects(BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.StructureBlockEntity
</summary>

```diff
- boolean isStrict()
- void setStrict(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerConfig$Builder
</summary>

```diff
+ TrialSpawnerConfig$Builder lootTablesToEject(SimpleWeightedRandomList)
- TrialSpawnerConfig$Builder lootTablesToEject(WeightedList)
+ TrialSpawnerConfig$Builder spawnPotentialsDefinition(SimpleWeightedRandomList)
- TrialSpawnerConfig$Builder spawnPotentialsDefinition(WeightedList)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState
</summary>

```diff
- void lambda$tickAndGetNext$0(TrialSpawnerData,TrialSpawner,SpawnData)
+ void lambda$tickAndGetNext$0(TrialSpawnerData,TrialSpawner,WeightedEntry$Wrapper)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkSource
</summary>

```diff
- boolean updateChunkForced(ChunkPos,boolean)
- LongSet getForceLoadedChunks()
+ void updateChunkForced(ChunkPos,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.EmptyLevelChunk
</summary>

```diff
+ BlockState setBlockState(BlockPos,BlockState,boolean)
- BlockState setBlockState(BlockPos,BlockState,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
+ BlockState setBlockState(BlockPos,BlockState,boolean)
- BlockState setBlockState(BlockPos,BlockState,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
+ BlockState setBlockState(BlockPos,BlockState,boolean)
- BlockState setBlockState(BlockPos,BlockState,int)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.BlockUtil
- net.minecraft.BlockUtil$FoundRectangle
+ net.minecraft.BlockUtil$IntBounds
- net.minecraft.CharPredicate
+ net.minecraft.ChatFormatting
- net.minecraft.CrashReport
+ net.minecraft.CrashReportCategory
- net.minecraft.CrashReportCategory$Entry
+ net.minecraft.CrashReportDetail
- net.minecraft.DefaultUncaughtExceptionHandler
+ net.minecraft.DefaultUncaughtExceptionHandlerWithName
- net.minecraft.DetectedVersion
+ net.minecraft.FieldsAreNonnullByDefault
- net.minecraft.FileUtil
+ net.minecraft.MethodsReturnNonnullByDefault
- net.minecraft.Optionull
- net.minecraft.ReportedException
+ net.minecraft.ReportType
+ net.minecraft.ResourceLocationException
- net.minecraft.SharedConstants
+ net.minecraft.SuppressForbidden
- net.minecraft.SystemReport
+ net.minecraft.TracingExecutor
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$10
+ net.minecraft.Util$11
- net.minecraft.Util$2
+ net.minecraft.Util$5
- net.minecraft.Util$6
+ net.minecraft.Util$7
- net.minecraft.Util$8
+ net.minecraft.Util$9
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
+ net.minecraft.WorldVersion
- XXX.advancements.critereon.AnyBlockInteractionTrigger
+ XXX.advancements.critereon.AnyBlockInteractionTrigger$TriggerInstance
- XXX.advancements.critereon.BeeNestDestroyedTrigger
+ XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
- XXX.advancements.critereon.BlockPredicate
+ XXX.advancements.critereon.BlockPredicate$Builder
- XXX.advancements.critereon.BredAnimalsTrigger
+ XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
- XXX.advancements.critereon.BrewedPotionTrigger
+ XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
- XXX.advancements.critereon.ChangeDimensionTrigger
+ XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
- XXX.advancements.critereon.ChanneledLightningTrigger
+ XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
- XXX.advancements.critereon.CollectionContentsPredicate
+ XXX.advancements.critereon.CollectionContentsPredicate$Multiple
- XXX.advancements.critereon.CollectionContentsPredicate$Single
+ XXX.advancements.critereon.CollectionContentsPredicate$Zero
- XXX.advancements.critereon.CollectionCountsPredicate
+ XXX.advancements.critereon.CollectionCountsPredicate$Entry
- XXX.advancements.critereon.CollectionCountsPredicate$Multiple
+ XXX.advancements.critereon.CollectionCountsPredicate$Single
- XXX.advancements.critereon.CollectionCountsPredicate$Zero
+ XXX.advancements.critereon.CollectionPredicate
- XXX.advancements.critereon.ConstructBeaconTrigger
+ XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
- XXX.advancements.critereon.ConsumeItemTrigger
+ XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
- XXX.advancements.critereon.ContextAwarePredicate
+ XXX.advancements.critereon.CriterionValidator
- XXX.advancements.critereon.CuredZombieVillagerTrigger
+ XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- XXX.advancements.critereon.DamagePredicate
+ XXX.advancements.critereon.DamagePredicate$Builder
- XXX.advancements.critereon.DamageSourcePredicate
+ XXX.advancements.critereon.DamageSourcePredicate$Builder
- XXX.advancements.critereon.DefaultBlockInteractionTrigger
+ XXX.advancements.critereon.DefaultBlockInteractionTrigger$TriggerInstance
- XXX.advancements.critereon.DistancePredicate
+ XXX.advancements.critereon.DistanceTrigger
- XXX.advancements.critereon.DistanceTrigger$TriggerInstance
+ XXX.advancements.critereon.EffectsChangedTrigger
- XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantedItemTrigger
- XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantmentPredicate
- XXX.advancements.critereon.EnterBlockTrigger
+ XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
- XXX.advancements.critereon.EntityEquipmentPredicate
+ XXX.advancements.critereon.EntityEquipmentPredicate$Builder
- XXX.advancements.critereon.EntityFlagsPredicate
+ XXX.advancements.critereon.EntityFlagsPredicate$Builder
- XXX.advancements.critereon.EntityHurtPlayerTrigger
+ XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
- XXX.advancements.critereon.EntityPredicate
+ XXX.advancements.critereon.EntityPredicate$Builder
- XXX.advancements.critereon.EntityPredicate$LocationWrapper
+ XXX.advancements.critereon.EntitySubPredicate
- XXX.advancements.critereon.EntitySubPredicates
+ XXX.advancements.critereon.EntitySubPredicates$EntityHolderVariantPredicateType
- XXX.advancements.critereon.EntitySubPredicates$EntityHolderVariantPredicateType$Instance
+ XXX.advancements.critereon.EntitySubPredicates$EntityVariantPredicateType
- XXX.advancements.critereon.EntitySubPredicates$EntityVariantPredicateType$Instance
+ XXX.advancements.critereon.EntityTypePredicate
- XXX.advancements.critereon.FallAfterExplosionTrigger
+ XXX.advancements.critereon.FallAfterExplosionTrigger$TriggerInstance
- XXX.advancements.critereon.FilledBucketTrigger
+ XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
- XXX.advancements.critereon.FishingHookPredicate
+ XXX.advancements.critereon.FishingRodHookedTrigger
- XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ XXX.advancements.critereon.FluidPredicate
- XXX.advancements.critereon.FluidPredicate$Builder
+ XXX.advancements.critereon.GameTypePredicate
- XXX.advancements.critereon.ImpossibleTrigger
+ XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
- XXX.advancements.critereon.InputPredicate
+ XXX.advancements.critereon.InventoryChangeTrigger
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance$Slots
- XXX.advancements.critereon.ItemAttributeModifiersPredicate
+ XXX.advancements.critereon.ItemAttributeModifiersPredicate$EntryPredicate
- XXX.advancements.critereon.ItemBundlePredicate
+ XXX.advancements.critereon.ItemContainerPredicate
- XXX.advancements.critereon.ItemCustomDataPredicate
+ XXX.advancements.critereon.ItemDamagePredicate
- XXX.advancements.critereon.ItemDurabilityTrigger
+ XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- XXX.advancements.critereon.ItemEnchantmentsPredicate
+ XXX.advancements.critereon.ItemEnchantmentsPredicate$Enchantments
- XXX.advancements.critereon.ItemEnchantmentsPredicate$StoredEnchantments
+ XXX.advancements.critereon.ItemFireworkExplosionPredicate
- XXX.advancements.critereon.ItemFireworkExplosionPredicate$FireworkPredicate
+ XXX.advancements.critereon.ItemFireworksPredicate
- XXX.advancements.critereon.ItemJukeboxPlayablePredicate
+ XXX.advancements.critereon.ItemPotionsPredicate
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.ItemSubPredicate
+ XXX.advancements.critereon.ItemSubPredicate$Type
- XXX.advancements.critereon.ItemSubPredicates
+ XXX.advancements.critereon.ItemTrimPredicate
- XXX.advancements.critereon.ItemUsedOnLocationTrigger
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
- XXX.advancements.critereon.ItemWritableBookPredicate
+ XXX.advancements.critereon.ItemWritableBookPredicate$PagePredicate
- XXX.advancements.critereon.ItemWrittenBookPredicate
+ XXX.advancements.critereon.ItemWrittenBookPredicate$PagePredicate
- XXX.advancements.critereon.KilledByArrowTrigger
+ XXX.advancements.critereon.KilledByArrowTrigger$TriggerInstance
- XXX.advancements.critereon.KilledTrigger
+ XXX.advancements.critereon.KilledTrigger$TriggerInstance
- XXX.advancements.critereon.LevitationTrigger
+ XXX.advancements.critereon.LevitationTrigger$TriggerInstance
- XXX.advancements.critereon.LightningBoltPredicate
+ XXX.advancements.critereon.LightningStrikeTrigger
- XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
- XXX.advancements.critereon.LightPredicate
+ XXX.advancements.critereon.LightPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate
- XXX.advancements.critereon.LocationPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate$PositionPredicate
- XXX.advancements.critereon.LootTableTrigger
+ XXX.advancements.critereon.LootTableTrigger$TriggerInstance
- XXX.advancements.critereon.MinMaxBounds
+ XXX.advancements.critereon.MinMaxBounds$BoundsFactory
- XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
+ XXX.advancements.critereon.MinMaxBounds$Doubles
- XXX.advancements.critereon.MinMaxBounds$Ints
+ XXX.advancements.critereon.MobEffectsPredicate
- XXX.advancements.critereon.MobEffectsPredicate$Builder
+ XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.critereon.MovementPredicate
+ XXX.advancements.critereon.NbtPredicate
+ XXX.advancements.critereon.package-info
- XXX.advancements.critereon.PickedUpItemTrigger
+ XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerHurtEntityTrigger
+ XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerInteractTrigger
+ XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
- XXX.advancements.critereon.PlayerPredicate$Builder
+ XXX.advancements.critereon.PlayerPredicate$StatMatcher
- XXX.advancements.critereon.PlayerTrigger
+ XXX.advancements.critereon.PlayerTrigger$TriggerInstance
- XXX.advancements.critereon.RaiderPredicate
+ XXX.advancements.critereon.RecipeCraftedTrigger
- XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
+ XXX.advancements.critereon.RecipeUnlockedTrigger
- XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
+ XXX.advancements.critereon.SheepPredicate
- XXX.advancements.critereon.ShotCrossbowTrigger
+ XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.SimpleCriterionTrigger
+ XXX.advancements.critereon.SimpleCriterionTrigger$SimpleInstance
- XXX.advancements.critereon.SingleComponentItemPredicate
+ XXX.advancements.critereon.SlideDownBlockTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.SlimePredicate
- XXX.advancements.critereon.SlotsPredicate
+ XXX.advancements.critereon.StartRidingTrigger
- XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
+ XXX.advancements.critereon.StatePropertiesPredicate
- XXX.advancements.critereon.StatePropertiesPredicate$Builder
+ XXX.advancements.critereon.StatePropertiesPredicate$ExactMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$RangedMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$ValueMatcher
+ XXX.advancements.critereon.SummonedEntityTrigger
- XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.TagPredicate
- XXX.advancements.critereon.TameAnimalTrigger
+ XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
- XXX.advancements.critereon.TargetBlockTrigger
+ XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
- XXX.advancements.critereon.TradeTrigger
+ XXX.advancements.critereon.TradeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedEnderEyeTrigger
+ XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.UsingItemTrigger
+ XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
- XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.Attribute$Sentiment
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
+ XXX.ai.behavior.StartAttacking$StartAttackingCondition
- XXX.ai.behavior.StartAttacking$TargetFinder
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopAttackingIfTargetInvalid$StopAttackCondition
+ XXX.ai.behavior.StopAttackingIfTargetInvalid$TargetErasedCallback
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
- XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
+ XXX.ai.targeting.TargetingConditions$Selector
+ XXX.ai.util.AirAndWaterRandomPos
- XXX.ai.util.AirRandomPos
+ XXX.ai.util.DefaultRandomPos
- XXX.ai.util.GoalUtils
+ XXX.ai.util.HoverRandomPos
- XXX.ai.util.LandRandomPos
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
- XXX.animal.allay.Allay
+ XXX.animal.allay.Allay$JukeboxListener
- XXX.animal.allay.Allay$VibrationUser
+ XXX.animal.allay.AllayAi
- XXX.animal.allay.package-info
+ XXX.animal.armadillo.Armadillo
- XXX.animal.armadillo.Armadillo$1
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
- XXX.animal.axolotl.Axolotl$AnimationState
+ XXX.animal.axolotl.Axolotl$AxolotlGroupData
- XXX.animal.axolotl.Axolotl$AxolotlLookControl
+ XXX.animal.axolotl.Axolotl$AxolotlMoveControl
- XXX.animal.axolotl.Axolotl$Variant
+ XXX.animal.axolotl.AxolotlAi
- XXX.animal.axolotl.package-info
- XXX.animal.axolotl.PlayDead
+ XXX.animal.axolotl.ValidatePlayDead
+ XXX.animal.camel.Camel
- XXX.animal.camel.Camel$CamelBodyRotationControl
+ XXX.animal.camel.Camel$CamelLookControl
- XXX.animal.camel.Camel$CamelMoveControl
+ XXX.animal.camel.CamelAi
- XXX.animal.camel.CamelAi$CamelPanic
+ XXX.animal.camel.CamelAi$RandomSitting
- XXX.animal.camel.package-info
+ XXX.animal.frog.Frog
- XXX.animal.frog.Frog$FrogLookControl
+ XXX.animal.frog.Frog$FrogNodeEvaluator
- XXX.animal.frog.Frog$FrogPathNavigation
+ XXX.animal.frog.FrogAi
- XXX.animal.frog.package-info
- XXX.animal.frog.ShootTongue
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
+ XXX.animal.sniffer.package-info
+ XXX.animal.sniffer.Sniffer
- XXX.animal.sniffer.Sniffer$State
+ XXX.animal.sniffer.SnifferAi
- XXX.animal.sniffer.SnifferAi$1
+ XXX.animal.sniffer.SnifferAi$2
- XXX.animal.sniffer.SnifferAi$3
+ XXX.animal.sniffer.SnifferAi$Digging
- XXX.animal.sniffer.SnifferAi$FeelingHappy
+ XXX.animal.sniffer.SnifferAi$FinishedDigging
- XXX.animal.sniffer.SnifferAi$Scenting
+ XXX.animal.sniffer.SnifferAi$Searching
- XXX.animal.sniffer.SnifferAi$Sniffing
+ XXX.animation.definitions.ArmadilloAnimation
- XXX.animation.definitions.BatAnimation
+ XXX.animation.definitions.BreezeAnimation
- XXX.animation.definitions.CamelAnimation
+ XXX.animation.definitions.CreakingAnimation
- XXX.animation.definitions.FrogAnimation
+ XXX.animation.definitions.package-info
+ XXX.animation.definitions.SnifferAnimation
- XXX.animation.definitions.WardenAnimation
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
+ XXX.blaze3d.platform.GlConst
- XXX.blaze3d.platform.GlDebug
+ XXX.blaze3d.platform.GlDebug$LogEntry
- XXX.blaze3d.platform.GlStateManager
+ XXX.blaze3d.platform.GlStateManager$BlendState
- XXX.blaze3d.platform.GlStateManager$BooleanState
+ XXX.blaze3d.platform.GlStateManager$ColorLogicState
- XXX.blaze3d.platform.GlStateManager$ColorMask
+ XXX.blaze3d.platform.GlStateManager$CullState
- XXX.blaze3d.platform.GlStateManager$DepthState
+ XXX.blaze3d.platform.GlStateManager$DestFactor
- XXX.blaze3d.platform.GlStateManager$FramebufferState
+ XXX.blaze3d.platform.GlStateManager$LogicOp
- XXX.blaze3d.platform.GlStateManager$PolygonOffsetState
+ XXX.blaze3d.platform.GlStateManager$ScissorState
- XXX.blaze3d.platform.GlStateManager$SourceFactor
+ XXX.blaze3d.platform.GlStateManager$StencilFunc
- XXX.blaze3d.platform.GlStateManager$StencilState
+ XXX.blaze3d.platform.GlStateManager$TextureState
- XXX.blaze3d.platform.GlStateManager$Viewport
+ XXX.blaze3d.platform.GlUtil
- XXX.blaze3d.platform.GLX
- XXX.blaze3d.platform.IconSet
+ XXX.blaze3d.platform.InputConstants
- XXX.blaze3d.platform.InputConstants$Key
+ XXX.blaze3d.platform.InputConstants$Type
- XXX.blaze3d.platform.Lighting
+ XXX.blaze3d.platform.MacosUtil
- XXX.blaze3d.platform.Monitor
+ XXX.blaze3d.platform.MonitorCreator
- XXX.blaze3d.platform.NativeImage
+ XXX.blaze3d.platform.NativeImage$Format
- XXX.blaze3d.platform.NativeImage$InternalGlFormat
+ XXX.blaze3d.platform.NativeImage$WriteCallback
- XXX.blaze3d.platform.package-info
- XXX.blaze3d.platform.ScreenManager
+ XXX.blaze3d.platform.TextureUtil
- XXX.blaze3d.platform.VideoMode
+ XXX.blaze3d.platform.Window
- XXX.blaze3d.platform.Window$WindowInitFailed
+ XXX.blaze3d.platform.WindowEventHandler
+ XXX.blaze3d.preprocessor.GlslPreprocessor
- XXX.blaze3d.preprocessor.GlslPreprocessor$Context
+ XXX.blaze3d.preprocessor.package-info
- XXX.blaze3d.resource.CrossFrameResourcePool
+ XXX.blaze3d.resource.CrossFrameResourcePool$ResourceEntry
- XXX.blaze3d.resource.GraphicsResourceAllocator
+ XXX.blaze3d.resource.GraphicsResourceAllocator$1
+ XXX.blaze3d.resource.package-info
- XXX.blaze3d.resource.RenderTargetDescriptor
+ XXX.blaze3d.resource.ResourceDescriptor
- XXX.blaze3d.resource.ResourceHandle
- XXX.blaze3d.shaders.AbstractUniform
+ XXX.blaze3d.shaders.CompiledShader
- XXX.blaze3d.shaders.CompiledShader$Type
+ XXX.blaze3d.shaders.FogShape
+ XXX.blaze3d.shaders.package-info
- XXX.blaze3d.shaders.Uniform
+ XXX.blaze3d.systems.package-info
- XXX.blaze3d.systems.RenderSystem
+ XXX.blaze3d.systems.RenderSystem$1
- XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
+ XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
- XXX.blaze3d.systems.TimerQuery
+ XXX.blaze3d.systems.TimerQuery$FrameProfile
- XXX.blaze3d.systems.TimerQuery$TimerQueryLazyLoader
- XXX.blaze3d.vertex.BufferBuilder
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.ByteBufferBuilder
+ XXX.blaze3d.vertex.ByteBufferBuilder$Result
- XXX.blaze3d.vertex.DefaultVertexFormat
+ XXX.blaze3d.vertex.MeshData
- XXX.blaze3d.vertex.MeshData$1
+ XXX.blaze3d.vertex.MeshData$DrawState
- XXX.blaze3d.vertex.MeshData$SortState
- XXX.blaze3d.vertex.package-info
+ XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$Pose
+ XXX.blaze3d.vertex.SheetedDecalTextureGenerator
- XXX.blaze3d.vertex.Tesselator
+ XXX.blaze3d.vertex.VertexBuffer
- XXX.blaze3d.vertex.VertexConsumer
+ XXX.blaze3d.vertex.VertexFormat
- XXX.blaze3d.vertex.VertexFormat$Builder
+ XXX.blaze3d.vertex.VertexFormat$IndexType
- XXX.blaze3d.vertex.VertexFormat$Mode
+ XXX.blaze3d.vertex.VertexFormatElement
- XXX.blaze3d.vertex.VertexFormatElement$Type
+ XXX.blaze3d.vertex.VertexFormatElement$Usage
- XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
+ XXX.blaze3d.vertex.VertexMultiConsumer
- XXX.blaze3d.vertex.VertexMultiConsumer$Double
+ XXX.blaze3d.vertex.VertexMultiConsumer$Multiple
- XXX.blaze3d.vertex.VertexSorting
+ XXX.blaze3d.vertex.VertexSorting$DistanceFunction
+ XXX.block.piston.package-info
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
+ XXX.boss.enderdragon.DragonFlightHistory
- XXX.boss.enderdragon.DragonFlightHistory$Sample
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.DataSource$Type
- XXX.chat.contents.EntityDataSource
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.NbtContents
- XXX.chat.contents.package-info
- XXX.chat.contents.PlainTextContents
+ XXX.chat.contents.PlainTextContents$1
- XXX.chat.contents.PlainTextContents$LiteralContents
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.StorageDataSource
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
+ XXX.chat.numbers.BlankFormat
- XXX.chat.numbers.BlankFormat$1
+ XXX.chat.numbers.FixedFormat
- XXX.chat.numbers.FixedFormat$1
+ XXX.chat.numbers.NumberFormat
- XXX.chat.numbers.NumberFormatType
+ XXX.chat.numbers.NumberFormatTypes
- XXX.chat.numbers.package-info
- XXX.chat.numbers.StyledFormat
+ XXX.chat.numbers.StyledFormat$1
- XXX.chat.report.AbuseReportSender
+ XXX.chat.report.AbuseReportSender$1
- XXX.chat.report.AbuseReportSender$SendException
+ XXX.chat.report.AbuseReportSender$Services
- XXX.chat.report.BanReason
+ XXX.chat.report.ChatReport
- XXX.chat.report.ChatReport$Builder
+ XXX.chat.report.ChatReportContextBuilder
- XXX.chat.report.ChatReportContextBuilder$Collector
+ XXX.chat.report.ChatReportContextBuilder$Handler
- XXX.chat.report.NameReport
+ XXX.chat.report.NameReport$Builder
- XXX.chat.report.package-info
- XXX.chat.report.Report
+ XXX.chat.report.Report$Builder
- XXX.chat.report.Report$CannotBuildReason
+ XXX.chat.report.Report$Result
- XXX.chat.report.ReportEnvironment
+ XXX.chat.report.ReportEnvironment$Server
- XXX.chat.report.ReportEnvironment$Server$Realm
+ XXX.chat.report.ReportEnvironment$Server$ThirdParty
+ XXX.chat.report.ReportingContext
- XXX.chat.report.ReportReason
+ XXX.chat.report.ReportReason$1
- XXX.chat.report.ReportType
- XXX.chat.report.SkinReport
+ XXX.chat.report.SkinReport$Builder
- XXX.client.animation.AnimationChannel
+ XXX.client.animation.AnimationChannel$Interpolation
- XXX.client.animation.AnimationChannel$Interpolations
+ XXX.client.animation.AnimationChannel$Target
- XXX.client.animation.AnimationChannel$Targets
+ XXX.client.animation.AnimationDefinition
- XXX.client.animation.AnimationDefinition$Builder
+ XXX.client.animation.Keyframe
- XXX.client.animation.KeyframeAnimations
- XXX.client.animation.package-info
- XXX.client.data.Main
+ XXX.client.data.package-info
- XXX.client.gui.BundleMouseActions
+ XXX.client.gui.ComponentPath
- XXX.client.gui.ComponentPath$Leaf
+ XXX.client.gui.ComponentPath$Path
- XXX.client.gui.Font
+ XXX.client.gui.Font$DisplayMode
- XXX.client.gui.Font$StringRenderOutput
+ XXX.client.gui.Gui
- XXX.client.gui.Gui$1DisplayEntry
+ XXX.client.gui.Gui$HeartType
- XXX.client.gui.GuiGraphics
+ XXX.client.gui.GuiGraphics$ScissorStack
- XXX.client.gui.GuiSpriteManager
+ XXX.client.gui.ItemSlotMouseAction
- XXX.client.gui.LayeredDraw
+ XXX.client.gui.LayeredDraw$Layer
- XXX.client.gui.package-info
- XXX.client.main.GameConfig
+ XXX.client.main.GameConfig$FolderData
- XXX.client.main.GameConfig$GameData
+ XXX.client.main.GameConfig$QuickPlayData
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
+ XXX.client.main.package-info
- XXX.client.main.SilentInitException
- XXX.client.model.AbstractBoatModel
+ XXX.client.model.AbstractEquineModel
- XXX.client.model.AbstractPiglinModel
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AdultAndBabyModelPair
- XXX.client.model.ColdPigModel
+ XXX.client.model.CowModel
- XXX.client.model.CreakingModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DonkeyModel
- XXX.client.model.DrownedModel
+ XXX.client.model.ElytraModel
- XXX.client.model.EndCrystalModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FelineModel
- XXX.client.model.FoxModel
+ XXX.client.model.FrogModel
- XXX.client.model.GhastModel
+ XXX.client.model.GiantZombieModel
- XXX.client.model.GoatModel
+ XXX.client.model.GuardianModel
- XXX.client.model.HeadedModel
+ XXX.client.model.HoglinModel
- XXX.client.model.HorseModel
+ XXX.client.model.HumanoidArmorModel
- XXX.client.model.HumanoidModel
+ XXX.client.model.HumanoidModel$ArmPose
- XXX.client.model.IllagerModel
+ XXX.client.model.IronGolemModel
- XXX.client.model.LavaSlimeModel
+ XXX.client.model.LeashKnotModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
- XXX.client.model.MinecartModel
+ XXX.client.model.Model
- XXX.client.model.Model$Simple
+ XXX.client.model.OcelotModel
- XXX.client.model.package-info
- XXX.client.model.PandaModel
+ XXX.client.model.ParrotModel
- XXX.client.model.ParrotModel$Pose
+ XXX.client.model.PhantomModel
+ XXX.client.model.PiglinHeadModel
- XXX.client.model.PiglinModel
- XXX.client.model.PigModel
+ XXX.client.model.PlayerCapeModel
- XXX.client.model.PlayerEarsModel
+ XXX.client.model.PlayerModel
- XXX.client.model.PolarBearModel
+ XXX.client.model.PufferfishBigModel
- XXX.client.model.PufferfishMidModel
+ XXX.client.model.PufferfishSmallModel
- XXX.client.model.QuadrupedModel
+ XXX.client.model.RabbitModel
- XXX.client.model.RaftModel
+ XXX.client.model.RavagerModel
- XXX.client.model.SalmonModel
+ XXX.client.model.SheepFurModel
- XXX.client.model.SheepModel
+ XXX.client.model.ShieldModel
- XXX.client.model.ShulkerBulletModel
+ XXX.client.model.ShulkerModel
- XXX.client.model.SilverfishModel
+ XXX.client.model.SkeletonModel
- XXX.client.model.SkullModel
+ XXX.client.model.SkullModelBase
- XXX.client.model.SlimeModel
+ XXX.client.model.SnifferModel
- XXX.client.model.SnowGolemModel
+ XXX.client.model.SpiderModel
- XXX.client.model.SpinAttackEffectModel
+ XXX.client.model.SquidModel
- XXX.client.model.StriderModel
+ XXX.client.model.TadpoleModel
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerLikeModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WardenModel
- XXX.client.model.WindChargeModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.model.ZombifiedPiglinModel
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
- XXX.client.multiplayer.ClientRecipeContainer
+ XXX.client.multiplayer.ClientRegistryLayer
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.ClientSuggestionProvider$1
- XXX.client.multiplayer.CommonListenerCookie
+ XXX.client.multiplayer.DebugSampleSubscriber
- XXX.client.multiplayer.KnownPacksManager
+ XXX.client.multiplayer.LegacyServerPinger
- XXX.client.multiplayer.LegacyServerPinger$Output
+ XXX.client.multiplayer.LevelLoadStatusManager
- XXX.client.multiplayer.LevelLoadStatusManager$Status
+ XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
- XXX.client.multiplayer.PingDebugMonitor
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ProfileKeyPairManager
+ XXX.client.multiplayer.ProfileKeyPairManager$1
- XXX.client.multiplayer.RegistryDataCollector
+ XXX.client.multiplayer.RegistryDataCollector$ContentsCollector
- XXX.client.multiplayer.RegistryDataCollector$TagCollector
+ XXX.client.multiplayer.ServerData
- XXX.client.multiplayer.ServerData$ServerPackStatus
+ XXX.client.multiplayer.ServerData$State
- XXX.client.multiplayer.ServerData$Type
+ XXX.client.multiplayer.ServerList
- XXX.client.multiplayer.ServerStatusPinger
+ XXX.client.multiplayer.ServerStatusPinger$1
- XXX.client.multiplayer.ServerStatusPinger$2
+ XXX.client.multiplayer.SessionSearchTrees
- XXX.client.multiplayer.SessionSearchTrees$Key
+ XXX.client.multiplayer.TransferState
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BlockMarker
- XXX.client.particle.BlockMarker$Provider
+ XXX.client.particle.BreakingItemParticle
- XXX.client.particle.BreakingItemParticle$CobwebProvider
+ XXX.client.particle.BreakingItemParticle$ItemParticleProvider
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
- XXX.client.particle.CritParticle
+ XXX.client.particle.CritParticle$DamageIndicatorProvider
- XXX.client.particle.CritParticle$MagicProvider
+ XXX.client.particle.CritParticle$Provider
- XXX.client.particle.DragonBreathParticle
+ XXX.client.particle.DragonBreathParticle$Provider
- XXX.client.particle.DripParticle
+ XXX.client.particle.DripParticle$CoolingDripHangParticle
- XXX.client.particle.DripParticle$DripHangParticle
+ XXX.client.particle.DripParticle$DripLandParticle
- XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
+ XXX.client.particle.DripParticle$FallAndLandParticle
- XXX.client.particle.DripParticle$FallingParticle
+ XXX.client.particle.DripParticle$HoneyFallAndLandParticle
- XXX.client.particle.DustColorTransitionParticle
+ XXX.client.particle.DustColorTransitionParticle$Provider
- XXX.client.particle.DustParticle
+ XXX.client.particle.DustParticle$Provider
- XXX.client.particle.DustParticleBase
+ XXX.client.particle.DustPlumeParticle
- XXX.client.particle.DustPlumeParticle$Provider
+ XXX.client.particle.EndRodParticle
- XXX.client.particle.EndRodParticle$Provider
+ XXX.client.particle.ExplodeParticle
- XXX.client.particle.ExplodeParticle$Provider
+ XXX.client.particle.FallingDustParticle
- XXX.client.particle.FallingDustParticle$Provider
+ XXX.client.particle.FallingLeavesParticle
- XXX.client.particle.FallingLeavesParticle$CherryProvider
+ XXX.client.particle.FallingLeavesParticle$PaleOakProvider
- XXX.client.particle.FallingLeavesParticle$TintedLeavesProvider
- XXX.client.worldupload.package-info
- XXX.client.worldupload.RealmsCreateWorldFlow
+ XXX.client.worldupload.RealmsUploadCanceledException
- XXX.client.worldupload.RealmsUploadException
+ XXX.client.worldupload.RealmsUploadFailedException
- XXX.client.worldupload.RealmsUploadTooLargeException
+ XXX.client.worldupload.RealmsUploadWorldNotClosedException
- XXX.client.worldupload.RealmsUploadWorldPacker
+ XXX.client.worldupload.RealmsWorldUpload
- XXX.client.worldupload.RealmsWorldUploadStatusTracker
+ XXX.client.worldupload.RealmsWorldUploadStatusTracker$1
+ XXX.color.block.BlockColor
- XXX.color.block.BlockColors
+ XXX.color.block.BlockTintCache
- XXX.color.block.BlockTintCache$CacheData
+ XXX.color.block.BlockTintCache$LatestCacheInfo
- XXX.color.block.package-info
+ XXX.color.item.Constant
- XXX.color.item.CustomModelDataSource
+ XXX.color.item.Dye
- XXX.color.item.Firework
+ XXX.color.item.GrassColorSource
- XXX.color.item.ItemTintSource
+ XXX.color.item.ItemTintSources
- XXX.color.item.MapColor
+ XXX.color.item.package-info
+ XXX.color.item.Potion
- XXX.color.item.TeamColor
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
+ XXX.common.custom.BeeDebugPayload
- XXX.common.custom.BeeDebugPayload$BeeInfo
+ XXX.common.custom.BrainDebugPayload
- XXX.common.custom.BrainDebugPayload$BrainDump
+ XXX.common.custom.BrandPayload
- XXX.common.custom.BreezeDebugPayload
+ XXX.common.custom.BreezeDebugPayload$BreezeInfo
- XXX.common.custom.CustomPacketPayload
+ XXX.common.custom.CustomPacketPayload$1
- XXX.common.custom.CustomPacketPayload$FallbackProvider
+ XXX.common.custom.CustomPacketPayload$Type
- XXX.common.custom.CustomPacketPayload$TypeAndCodec
+ XXX.common.custom.DiscardedPayload
- XXX.common.custom.GameEventDebugPayload
+ XXX.common.custom.GameEventListenerDebugPayload
- XXX.common.custom.GameTestAddMarkerDebugPayload
+ XXX.common.custom.GameTestClearMarkersDebugPayload
- XXX.common.custom.GoalDebugPayload
+ XXX.common.custom.GoalDebugPayload$DebugGoal
- XXX.common.custom.HiveDebugPayload
+ XXX.common.custom.HiveDebugPayload$HiveInfo
- XXX.common.custom.NeighborUpdatesDebugPayload
- XXX.common.custom.package-info
+ XXX.common.custom.PathfindingDebugPayload
- XXX.common.custom.PoiAddedDebugPayload
+ XXX.common.custom.PoiRemovedDebugPayload
- XXX.common.custom.PoiTicketCountDebugPayload
+ XXX.common.custom.RaidsDebugPayload
- XXX.common.custom.RedstoneWireOrientationsDebugPayload
+ XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
- XXX.common.custom.StructuresDebugPayload
+ XXX.common.custom.StructuresDebugPayload$PieceInfo
- XXX.common.custom.VillageSectionsDebugPayload
+ XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.components.debugchart.AbstractDebugChart
+ XXX.components.debugchart.BandwidthDebugChart
- XXX.components.debugchart.FpsDebugChart
+ XXX.components.debugchart.PingDebugChart
- XXX.components.debugchart.ProfilerPieChart
+ XXX.components.debugchart.TpsDebugChart
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.tabs.GridLayoutTab
- XXX.components.tabs.package-info
- XXX.components.tabs.Tab
+ XXX.components.tabs.TabManager
- XXX.components.tabs.TabNavigationBar
+ XXX.components.tabs.TabNavigationBar$Builder
+ XXX.components.toasts.AdvancementToast
- XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.RecipeToast$Entry
- XXX.components.toasts.SystemToast
+ XXX.components.toasts.SystemToast$SystemToastId
- XXX.components.toasts.Toast
+ XXX.components.toasts.Toast$Visibility
- XXX.components.toasts.ToastManager
+ XXX.components.toasts.ToastManager$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
+ XXX.crafting.display.DisplayContentsFactory
- XXX.crafting.display.DisplayContentsFactory$ForRemainders
+ XXX.crafting.display.DisplayContentsFactory$ForStacks
- XXX.crafting.display.FurnaceRecipeDisplay
+ XXX.crafting.display.package-info
+ XXX.crafting.display.RecipeDisplay
- XXX.crafting.display.RecipeDisplay$Type
+ XXX.crafting.display.RecipeDisplayEntry
- XXX.crafting.display.RecipeDisplayId
+ XXX.crafting.display.RecipeDisplays
- XXX.crafting.display.ShapedCraftingRecipeDisplay
+ XXX.crafting.display.ShapelessCraftingRecipeDisplay
- XXX.crafting.display.SlotDisplay
+ XXX.crafting.display.SlotDisplay$AnyFuel
- XXX.crafting.display.SlotDisplay$Composite
+ XXX.crafting.display.SlotDisplay$Empty
- XXX.crafting.display.SlotDisplay$ItemSlotDisplay
+ XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
- XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
+ XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
- XXX.crafting.display.SlotDisplay$TagSlotDisplay
+ XXX.crafting.display.SlotDisplay$Type
- XXX.crafting.display.SlotDisplay$WithRemainder
+ XXX.crafting.display.SlotDisplayContext
- XXX.crafting.display.SlotDisplays
+ XXX.crafting.display.SmithingRecipeDisplay
- XXX.crafting.display.StonecutterRecipeDisplay
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
- XXX.data.models.BlockModelGenerators$PlantType
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.EquipmentAssetProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ItemModelGenerators$TrimMaterialData
+ XXX.data.models.ItemModelOutput
- XXX.data.models.ModelProvider
+ XXX.data.models.ModelProvider$BlockStateGeneratorCollector
- XXX.data.models.ModelProvider$ItemInfoCollector
+ XXX.data.models.ModelProvider$SimpleModelCollector
- XXX.data.models.package-info
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockPosFormatAndRenamesFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityAttributeBaseValueFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityFieldsRenameFix
+ XXX.datafix.fixes.EntityGoatMissingStateFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntitySalmonSizeFix
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
+ XXX.datafix.fixes.EquippableAssetRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FoodToConsumableFix
- XXX.datafix.fixes.ForcedChunkToTicketFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.ItemStackTagRemainderFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.LockComponentPredicateFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NamedEntityWriteReadFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
+ XXX.datafix.fixes.NewVillageFix
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
- XXX.datafix.fixes.TextComponentHoverAndClickEventFix
- XXX.datafix.fixes.TextComponentStringifiedFlagsFix
+ XXX.datafix.fixes.TippedArrowPotionToItemFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.TrialSpawnerConfigFix
+ XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix
- XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix$VanillaTrialChambers
- XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1488
- XXX.datafix.schemas.V1925
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
+ XXX.datafix.schemas.V2831
- XXX.datafix.schemas.V2832
+ XXX.datafix.schemas.V2842
- XXX.datafix.schemas.V3076
+ XXX.datafix.schemas.V3078
- XXX.datafix.schemas.V3081
+ XXX.datafix.schemas.V3082
- XXX.datafix.schemas.V3083
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
- XXX.datafix.schemas.V3325
+ XXX.datafix.schemas.V3326
- XXX.datafix.schemas.V3327
+ XXX.datafix.schemas.V3328
- XXX.datafix.schemas.V3438
- XXX.datafix.schemas.V3813
+ XXX.datafix.schemas.V3816
- XXX.datafix.schemas.V3818
+ XXX.datafix.schemas.V3818_3
- XXX.datafix.schemas.V3818_4
+ XXX.datafix.schemas.V3818_5
- XXX.datafix.schemas.V3825
+ XXX.datafix.schemas.V3938
- XXX.datafix.schemas.V4059
+ XXX.datafix.schemas.V4067
- XXX.datafix.schemas.V4070
+ XXX.datafix.schemas.V4071
- XXX.datafix.schemas.V4290
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
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyMobEffect
+ XXX.enchantment.effects.ChangeItemDamage
- XXX.enchantment.effects.DamageEntity
+ XXX.enchantment.effects.DamageImmunity
- XXX.enchantment.effects.EnchantmentAttributeEffect
+ XXX.enchantment.effects.EnchantmentEntityEffect
- XXX.enchantment.effects.EnchantmentLocationBasedEffect
+ XXX.enchantment.effects.EnchantmentValueEffect
- XXX.enchantment.effects.ExplodeEffect
+ XXX.enchantment.effects.Ignite
- XXX.enchantment.effects.MultiplyValue
- XXX.enchantment.effects.package-info
+ XXX.enchantment.effects.PlaySoundEffect
- XXX.enchantment.effects.RemoveBinomial
+ XXX.enchantment.effects.ReplaceBlock
- XXX.enchantment.effects.ReplaceDisk
+ XXX.enchantment.effects.RunFunction
- XXX.enchantment.effects.SetBlockProperties
+ XXX.enchantment.effects.SetValue
- XXX.enchantment.effects.SpawnParticlesEffect
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
- XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
+ XXX.enchantment.effects.SummonEntityEffect
- XXX.enchantment.providers.EnchantmentProvider
+ XXX.enchantment.providers.EnchantmentProviderTypes
- XXX.enchantment.providers.EnchantmentsByCost
+ XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
+ XXX.enchantment.providers.package-info
- XXX.enchantment.providers.SingleEnchantment
+ XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
- XXX.enchantment.providers.VanillaEnchantmentProviders
- XXX.enderdragon.phases.AbstractDragonPhaseInstance
+ XXX.enderdragon.phases.AbstractDragonSittingPhase
- XXX.enderdragon.phases.DragonChargePlayerPhase
+ XXX.enderdragon.phases.DragonDeathPhase
- XXX.enderdragon.phases.DragonHoldingPatternPhase
+ XXX.enderdragon.phases.DragonHoverPhase
- XXX.enderdragon.phases.DragonLandingApproachPhase
+ XXX.enderdragon.phases.DragonLandingPhase
- XXX.enderdragon.phases.DragonPhaseInstance
+ XXX.enderdragon.phases.DragonSittingAttackingPhase
- XXX.enderdragon.phases.DragonSittingFlamingPhase
+ XXX.enderdragon.phases.DragonSittingScanningPhase
- XXX.enderdragon.phases.DragonStrafePlayerPhase
+ XXX.enderdragon.phases.DragonTakeoffPhase
- XXX.enderdragon.phases.EnderDragonPhase
+ XXX.enderdragon.phases.EnderDragonPhaseManager
- XXX.enderdragon.phases.package-info
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
+ XXX.entity.ai.package-info
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractFish
- XXX.entity.animal.AbstractFish$FishMoveControl
+ XXX.entity.animal.AbstractFish$FishSwimGoal
- XXX.entity.animal.AbstractGolem
+ XXX.entity.animal.AbstractSchoolingFish
- XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ XXX.entity.animal.AgeableWaterCreature
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
+ XXX.entity.animal.Bee$ValidateFlowerGoal
- XXX.entity.animal.Bee$ValidateHiveGoal
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
+ XXX.entity.animal.Fox$Variant
- XXX.entity.animal.FrogVariant
+ XXX.entity.animal.IronGolem
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$Variant
- XXX.entity.animal.Ocelot
+ XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
- XXX.entity.animal.Ocelot$OcelotTemptGoal
- XXX.entity.animal.package-info
+ XXX.entity.animal.Panda
- XXX.entity.animal.Panda$Gene
+ XXX.entity.animal.Panda$PandaAttackGoal
- XXX.entity.animal.Panda$PandaAvoidGoal
+ XXX.entity.animal.Panda$PandaBreedGoal
- XXX.entity.animal.Panda$PandaHurtByTargetGoal
+ XXX.entity.animal.Panda$PandaLieOnBackGoal
- XXX.entity.animal.Panda$PandaLookAtPlayerGoal
+ XXX.entity.animal.Panda$PandaMoveControl
- XXX.entity.animal.Panda$PandaPanicGoal
+ XXX.entity.animal.Panda$PandaRollGoal
- XXX.entity.animal.Panda$PandaSitGoal
+ XXX.entity.animal.Panda$PandaSneezeGoal
- XXX.entity.animal.Parrot
+ XXX.entity.animal.Parrot$1
- XXX.entity.animal.Parrot$ParrotWanderGoal
+ XXX.entity.animal.Parrot$Variant
- XXX.entity.animal.Pig
- XXX.entity.animal.PigVariant$ModelType
- XXX.entity.animal.TemperatureVariant
+ XXX.entity.animal.TropicalFish
- XXX.entity.animal.TropicalFish$Base
+ XXX.entity.animal.TropicalFish$Pattern
- XXX.entity.animal.TropicalFish$TropicalFishGroupData
+ XXX.entity.animal.TropicalFish$Variant
- XXX.entity.animal.Turtle
+ XXX.entity.animal.Turtle$TurtleBreedGoal
- XXX.entity.animal.Turtle$TurtleGoHomeGoal
+ XXX.entity.animal.Turtle$TurtleGoToWaterGoal
- XXX.entity.animal.Turtle$TurtleLayEggGoal
+ XXX.entity.animal.Turtle$TurtleMoveControl
- XXX.entity.animal.Turtle$TurtlePanicGoal
+ XXX.entity.animal.Turtle$TurtlePathNavigation
- XXX.entity.animal.Turtle$TurtleRandomStrollGoal
+ XXX.entity.animal.Turtle$TurtleTravelGoal
- XXX.entity.animal.WaterAnimal
+ XXX.entity.animal.Wolf
- XXX.entity.animal.Wolf$WolfAvoidEntityGoal
+ XXX.entity.animal.Wolf$WolfPackData
- XXX.entity.animal.WolfVariant
+ XXX.entity.animal.WolfVariants
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.ArmorStand$1
+ XXX.entity.decoration.BlockAttachedEntity
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
- XXX.entity.decoration.PaintingVariant
+ XXX.entity.decoration.PaintingVariants
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
+ XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
- XXX.entity.item.PrimedTnt$1
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.Bogged
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$EvokerAttackSpellGoal
- XXX.entity.monster.Evoker$EvokerCastingSpellGoal
+ XXX.entity.monster.Evoker$EvokerSummonSpellGoal
- XXX.entity.monster.Evoker$EvokerWololoSpellGoal
+ XXX.entity.monster.Ghast
- XXX.entity.monster.Ghast$GhastLookGoal
+ XXX.entity.monster.Ghast$GhastMoveControl
- XXX.entity.monster.Ghast$GhastShootFireballGoal
+ XXX.entity.monster.Ghast$RandomFloatAroundGoal
- XXX.entity.monster.Giant
+ XXX.entity.monster.Guardian
- XXX.entity.monster.Guardian$GuardianAttackGoal
+ XXX.entity.monster.Guardian$GuardianAttackSelector
- XXX.entity.monster.Guardian$GuardianMoveControl
+ XXX.entity.monster.Husk
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
+ XXX.entity.monster.package-info
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$AttackPhase
+ XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
+ XXX.entity.monster.Phantom$PhantomBodyRotationControl
- XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ XXX.entity.monster.Phantom$PhantomLookControl
- XXX.entity.monster.Phantom$PhantomMoveControl
+ XXX.entity.monster.Phantom$PhantomMoveTargetGoal
- XXX.entity.monster.Phantom$PhantomSweepAttackGoal
+ XXX.entity.monster.Pillager
- XXX.entity.monster.RangedAttackMob
+ XXX.entity.monster.Ravager
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$ShulkerAttackGoal
- XXX.entity.monster.Shulker$ShulkerBodyRotationControl
+ XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
- XXX.entity.monster.Shulker$ShulkerLookControl
+ XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
- XXX.entity.monster.Shulker$ShulkerPeekGoal
+ XXX.entity.monster.Silverfish
- XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- XXX.entity.monster.Skeleton
+ XXX.entity.monster.Slime
- XXX.entity.monster.Slime$SlimeAttackGoal
+ XXX.entity.monster.Slime$SlimeFloatGoal
- XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ XXX.entity.monster.Slime$SlimeMoveControl
- XXX.entity.monster.Slime$SlimeRandomDirectionGoal
+ XXX.entity.monster.SpellcasterIllager
- XXX.entity.monster.SpellcasterIllager$IllagerSpell
+ XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ XXX.entity.monster.Spider
- XXX.entity.monster.Spider$SpiderAttackGoal
+ XXX.entity.monster.Spider$SpiderEffectsGroupData
- XXX.entity.monster.Spider$SpiderTargetGoal
+ XXX.entity.monster.Stray
- XXX.entity.monster.Strider
+ XXX.entity.monster.Strider$StriderGoToLavaGoal
- XXX.entity.monster.Strider$StriderPathNavigation
+ XXX.entity.monster.Vex
- XXX.entity.monster.Vex$VexChargeAttackGoal
+ XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
- XXX.entity.monster.Vex$VexMoveControl
+ XXX.entity.monster.Vex$VexRandomMoveGoal
- XXX.entity.monster.Vindicator
+ XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
- XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zoglin
- XXX.entity.monster.Zombie
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
- XXX.entity.monster.ZombifiedPiglin
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$FailureItemListing
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerTrades$TypeSpecificTrade
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Input
+ XXX.entity.player.Input$1
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$2
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$IngredientInfo
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.Projectile$ProjectileFactory
+ XXX.entity.projectile.ProjectileDeflection
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
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
- XXX.entity.vehicle.AbstractBoat
+ XXX.entity.vehicle.AbstractBoat$Status
- XXX.entity.vehicle.AbstractChestBoat
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestRaft
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartBehavior
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.NewMinecartBehavior
- XXX.entity.vehicle.NewMinecartBehavior$1
+ XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
- XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
+ XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
- XXX.entity.vehicle.OldMinecartBehavior
+ XXX.entity.vehicle.OldMinecartBehavior$1
- XXX.entity.vehicle.package-info
- XXX.entity.vehicle.Raft
+ XXX.entity.vehicle.VehicleEntity
- XXX.equipment.trim.ArmorTrim
+ XXX.equipment.trim.package-info
+ XXX.equipment.trim.TrimMaterial
- XXX.equipment.trim.TrimMaterials
+ XXX.equipment.trim.TrimPattern
- XXX.equipment.trim.TrimPatterns
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.PlaceOnGroundDecorator
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecorator$Context
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.BendingTrunkPlacer
+ XXX.feature.trunkplacers.CherryTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$Effect
- XXX.font.glyphs.BakedGlyph$GlyphInstance
+ XXX.font.glyphs.EmptyGlyph
+ XXX.font.glyphs.package-info
- XXX.font.glyphs.SpecialGlyphs
+ XXX.font.glyphs.SpecialGlyphs$1
- XXX.font.glyphs.SpecialGlyphs$PixelProvider
+ XXX.font.providers.BitmapProvider
- XXX.font.providers.BitmapProvider$Definition
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.BitmapProvider$Glyph$1
+ XXX.font.providers.FreeTypeUtil
- XXX.font.providers.GlyphProviderDefinition
+ XXX.font.providers.GlyphProviderDefinition$Conditional
- XXX.font.providers.GlyphProviderDefinition$Loader
+ XXX.font.providers.GlyphProviderDefinition$Reference
- XXX.font.providers.GlyphProviderType
+ XXX.font.providers.package-info
+ XXX.font.providers.ProviderReferenceDefinition
- XXX.font.providers.TrueTypeGlyphProviderDefinition
+ XXX.font.providers.TrueTypeGlyphProviderDefinition$Shift
- XXX.font.providers.UnihexProvider
+ XXX.font.providers.UnihexProvider$ByteContents
- XXX.font.providers.UnihexProvider$Definition
+ XXX.font.providers.UnihexProvider$Dimensions
- XXX.font.providers.UnihexProvider$Glyph
+ XXX.font.providers.UnihexProvider$Glyph$1
- XXX.font.providers.UnihexProvider$IntContents
+ XXX.font.providers.UnihexProvider$LineData
- XXX.font.providers.UnihexProvider$OverrideRange
+ XXX.font.providers.UnihexProvider$ReaderOutput
- XXX.font.providers.UnihexProvider$ShortContents
+ XXX.geom.builders.CubeDefinition
- XXX.geom.builders.CubeDeformation
+ XXX.geom.builders.CubeListBuilder
- XXX.geom.builders.LayerDefinition
+ XXX.geom.builders.MaterialDefinition
- XXX.geom.builders.MeshDefinition
+ XXX.geom.builders.MeshTransformer
- XXX.geom.builders.package-info
- XXX.geom.builders.PartDefinition
+ XXX.geom.builders.UVPair
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
- XXX.gui.components.AbstractButton
+ XXX.gui.components.AbstractContainerWidget
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractScrollArea
- XXX.gui.components.AbstractSelectionList
+ XXX.gui.components.AbstractSelectionList$1
- XXX.gui.components.AbstractSelectionList$Entry
+ XXX.gui.components.AbstractSelectionList$TrackedList
- XXX.gui.components.AbstractSliderButton
+ XXX.gui.components.AbstractStringWidget
- XXX.gui.components.AbstractTextAreaWidget
+ XXX.gui.components.AbstractWidget
- XXX.gui.components.BossHealthOverlay
+ XXX.gui.components.BossHealthOverlay$1
- XXX.gui.components.Button
+ XXX.gui.components.Button$Builder
- XXX.gui.components.Button$CreateNarration
+ XXX.gui.components.Button$OnPress
- XXX.gui.components.ChatComponent
+ XXX.gui.components.ChatComponent$DelayedMessageDeletion
- XXX.gui.components.ChatComponent$State
+ XXX.gui.components.Checkbox
- XXX.gui.components.Checkbox$Builder
+ XXX.gui.components.Checkbox$OnValueChange
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.CommonButtons
+ XXX.gui.components.ComponentRenderUtils
- XXX.gui.components.ContainerObjectSelectionList
+ XXX.gui.components.ContainerObjectSelectionList$1
- XXX.gui.components.ContainerObjectSelectionList$Entry
+ XXX.gui.components.CycleButton
- XXX.gui.components.CycleButton$Builder
+ XXX.gui.components.CycleButton$OnValueChange
- XXX.gui.components.CycleButton$ValueListSupplier
+ XXX.gui.components.CycleButton$ValueListSupplier$1
- XXX.gui.components.CycleButton$ValueListSupplier$2
+ XXX.gui.components.DebugScreenOverlay
- XXX.gui.components.DebugScreenOverlay$1
+ XXX.gui.components.DebugScreenOverlay$AllocationRateCalculator
- XXX.gui.components.EditBox
+ XXX.gui.components.FittingMultiLineTextWidget
- XXX.gui.components.FocusableTextWidget
+ XXX.gui.components.ImageButton
- XXX.gui.components.ImageWidget
+ XXX.gui.components.ImageWidget$Sprite
- XXX.gui.components.ImageWidget$Texture
+ XXX.gui.components.LerpingBossEvent
- XXX.gui.components.LoadingDotsWidget
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.LogoRenderer
- XXX.gui.components.MultiLineEditBox
+ XXX.gui.components.MultiLineLabel
- XXX.gui.components.MultiLineLabel$1
+ XXX.gui.components.MultiLineLabel$2
- XXX.gui.components.MultiLineLabel$TextAndWidth
+ XXX.gui.components.MultilineTextField
- XXX.gui.components.MultilineTextField$1
+ XXX.gui.components.MultilineTextField$StringView
+ XXX.gui.components.MultiLineTextWidget
- XXX.gui.components.MultiLineTextWidget$CacheKey
- XXX.gui.components.ObjectSelectionList
+ XXX.gui.components.ObjectSelectionList$Entry
- XXX.gui.components.OptionsList
+ XXX.gui.components.OptionsList$Entry
- XXX.gui.components.OptionsList$OptionEntry
- XXX.gui.components.package-info
+ XXX.gui.components.PlainTextButton
- XXX.gui.components.PlayerFaceRenderer
+ XXX.gui.components.PlayerSkinWidget
- XXX.gui.components.PlayerSkinWidget$Model
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$HealthState
+ XXX.gui.components.PlayerTabOverlay$ScoreDisplayEntry
- XXX.gui.components.PopupScreen
+ XXX.gui.components.PopupScreen$Builder
- XXX.gui.components.PopupScreen$ButtonOption
+ XXX.gui.components.Renderable
- XXX.gui.components.SplashRenderer
+ XXX.gui.components.SpriteIconButton
- XXX.gui.components.SpriteIconButton$Builder
+ XXX.gui.components.SpriteIconButton$CenteredIcon
- XXX.gui.components.SpriteIconButton$TextAndIcon
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.StringWidget
+ XXX.gui.components.SubtitleOverlay
- XXX.gui.components.SubtitleOverlay$SoundPlayedAt
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TabButton
+ XXX.gui.components.TabOrderedElement
- XXX.gui.components.Tooltip
+ XXX.gui.components.Whence
- XXX.gui.components.WidgetSprites
+ XXX.gui.components.WidgetTooltipHolder
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.CodepointMap
+ XXX.gui.font.CodepointMap$Output
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$BuilderId
- XXX.gui.font.FontManager$BuilderResult
+ XXX.gui.font.FontManager$FontDefinitionFile
- XXX.gui.font.FontManager$Preparation
+ XXX.gui.font.FontManager$UnresolvedBuilderBundle
- XXX.gui.font.FontOption
+ XXX.gui.font.FontOption$Filter
- XXX.gui.font.FontSet
+ XXX.gui.font.FontSet$GlyphInfoFilter
- XXX.gui.font.FontTexture
+ XXX.gui.font.FontTexture$Node
- XXX.gui.font.GlyphRenderTypes
+ XXX.gui.font.GlyphRenderTypes$1
- XXX.gui.font.package-info
- XXX.gui.font.TextFieldHelper
+ XXX.gui.font.TextFieldHelper$CursorStep
- XXX.gui.layouts.AbstractLayout
+ XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
- XXX.gui.layouts.CommonLayouts
+ XXX.gui.layouts.EqualSpacingLayout
- XXX.gui.layouts.EqualSpacingLayout$ChildContainer
+ XXX.gui.layouts.EqualSpacingLayout$Orientation
- XXX.gui.layouts.FrameLayout
+ XXX.gui.layouts.FrameLayout$ChildContainer
- XXX.gui.layouts.GridLayout
+ XXX.gui.layouts.GridLayout$CellInhabitant
- XXX.gui.layouts.GridLayout$RowHelper
+ XXX.gui.layouts.HeaderAndFooterLayout
- XXX.gui.layouts.Layout
+ XXX.gui.layouts.LayoutElement
- XXX.gui.layouts.LayoutSettings
+ XXX.gui.layouts.LayoutSettings$LayoutSettingsImpl
- XXX.gui.layouts.LinearLayout
+ XXX.gui.layouts.LinearLayout$Orientation
+ XXX.gui.layouts.package-info
- XXX.gui.layouts.SpacerElement
- XXX.gui.narration.NarratableEntry
+ XXX.gui.narration.NarratableEntry$NarrationPriority
- XXX.gui.narration.NarratedElementType
+ XXX.gui.narration.NarrationElementOutput
- XXX.gui.narration.NarrationSupplier
+ XXX.gui.narration.NarrationThunk
+ XXX.gui.narration.package-info
- XXX.gui.narration.ScreenNarrationCollector
+ XXX.gui.narration.ScreenNarrationCollector$1
- XXX.gui.narration.ScreenNarrationCollector$EntryKey
+ XXX.gui.narration.ScreenNarrationCollector$NarrationEntry
- XXX.gui.narration.ScreenNarrationCollector$Output
- XXX.gui.navigation.CommonInputs
+ XXX.gui.navigation.FocusNavigationEvent
- XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
+ XXX.gui.navigation.FocusNavigationEvent$InitialFocus
- XXX.gui.navigation.FocusNavigationEvent$TabNavigation
+ XXX.gui.navigation.package-info
+ XXX.gui.navigation.ScreenAxis
- XXX.gui.navigation.ScreenDirection
+ XXX.gui.navigation.ScreenPosition
- XXX.gui.navigation.ScreenPosition$1
+ XXX.gui.navigation.ScreenRectangle
- XXX.gui.navigation.ScreenRectangle$1
+ XXX.gui.screens.AccessibilityOnboardingScreen
- XXX.gui.screens.AddRealmPopupScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.BanNoticeScreens
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.ConnectScreen$2
+ XXX.gui.screens.CreateBuffetWorldScreen
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ XXX.gui.screens.CreditsAndAttributionScreen
- XXX.gui.screens.DatapackLoadFailureScreen
+ XXX.gui.screens.DeathScreen
- XXX.gui.screens.DeathScreen$TitleConfirmScreen
+ XXX.gui.screens.DemoIntroScreen
- XXX.gui.screens.DirectJoinServerScreen
+ XXX.gui.screens.DisconnectedScreen
- XXX.gui.screens.EditServerScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.FaviconTexture
+ XXX.gui.screens.GenericMessageScreen
- XXX.gui.screens.GenericWaitingScreen
+ XXX.gui.screens.InBedChatScreen
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingDotsText
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.NoticeWithLinkScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
+ XXX.gui.screens.package-info
- XXX.gui.screens.package-info
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PauseScreen$FeedbackSubScreen
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.RealmsBackupInfoScreen
- XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoList
+ XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
- XXX.gui.screens.RealmsBackupScreen
+ XXX.gui.screens.RealmsBackupScreen$1
- XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
+ XXX.gui.screens.RealmsBackupScreen$Entry
- XXX.gui.screens.RealmsBrokenWorldScreen
+ XXX.gui.screens.RealmsClientOutdatedScreen
- XXX.gui.screens.RealmsConfigureWorldScreen
+ XXX.gui.screens.RealmsConfigureWorldScreen$1
- XXX.gui.screens.RealmsConfirmScreen
+ XXX.gui.screens.RealmsCreateRealmScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
- XXX.gui.screens.RealmsGenericErrorScreen
+ XXX.gui.screens.RealmsGenericErrorScreen$ErrorMessage
- XXX.gui.screens.RealmsInviteScreen
+ XXX.gui.screens.RealmsLongRunningMcoTaskScreen
- XXX.gui.screens.RealmsLongRunningMcoTickTaskScreen
+ XXX.gui.screens.RealmsNotificationsScreen
- XXX.gui.screens.RealmsNotificationsScreen$1
+ XXX.gui.screens.RealmsNotificationsScreen$2
- XXX.gui.screens.RealmsNotificationsScreen$DataFetcherConfiguration
+ XXX.gui.screens.RealmsParentalConsentScreen
- XXX.gui.screens.RealmsPendingInvitesScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ XXX.gui.screens.RealmsPlayerScreen
- XXX.gui.screens.RealmsPlayerScreen$Entry
+ XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
- XXX.gui.screens.RealmsPopups
+ XXX.gui.screens.RealmsResetWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen$1
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsSelectFileToUploadScreen
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
- XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList
+ XXX.gui.screens.RealmsSettingsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
- XXX.gui.screens.RealmsSubscriptionInfoScreen
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$1
- XXX.gui.screens.RealmsTermsScreen
+ XXX.gui.screens.RealmsUploadScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.ReceivingLevelScreen$Reason
+ XXX.gui.screens.RecoverWorldDataScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$DeferredTooltipRendering
- XXX.gui.screens.Screen$NarratableSearchResult
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.TitleScreen
- XXX.gui.screens.UploadResult
+ XXX.gui.screens.UploadResult$Builder
+ XXX.gui.screens.WinScreen
- XXX.gui.screens.WinScreen$CreditsReader
+ XXX.gui.spectator.package-info
+ XXX.gui.spectator.PlayerMenuItem
- XXX.gui.spectator.RootSpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenu
- XXX.gui.spectator.SpectatorMenu$1
+ XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
- XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
+ XXX.gui.spectator.SpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenuItem
+ XXX.gui.spectator.SpectatorMenuListener
+ XXX.gui.task.DataFetcher
- XXX.gui.task.DataFetcher$ComputationResult
+ XXX.gui.task.DataFetcher$SubscribedTask
- XXX.gui.task.DataFetcher$Subscription
+ XXX.gui.task.DataFetcher$SuccessfulComputationResult
- XXX.gui.task.DataFetcher$Task
- XXX.gui.task.package-info
+ XXX.gui.task.RepeatedDelayStrategy
- XXX.gui.task.RepeatedDelayStrategy$1
+ XXX.gui.task.RepeatedDelayStrategy$2
- XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.ClientActivePlayersTooltip
- XXX.inventory.tooltip.ClientActivePlayersTooltip$ActivePlayersTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip
- XXX.inventory.tooltip.ClientTextTooltip
+ XXX.inventory.tooltip.ClientTooltipComponent
- XXX.inventory.tooltip.ClientTooltipPositioner
+ XXX.inventory.tooltip.DefaultTooltipPositioner
- XXX.inventory.tooltip.MenuTooltipPositioner
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
+ XXX.inventory.tooltip.TooltipRenderUtil
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.BlockItemStateProperties
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
+ XXX.item.component.Consumable
- XXX.item.component.Consumable$Builder
+ XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.ConsumableListener
+ XXX.item.component.Consumables
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
- XXX.item.component.DamageResistant
+ XXX.item.component.DeathProtection
- XXX.item.component.DebugStickState
+ XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion
+ XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.Fireworks
+ XXX.item.component.ItemAttributeModifiers
- XXX.item.component.ItemAttributeModifiers$1
+ XXX.item.component.ItemAttributeModifiers$Builder
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
- XXX.item.component.ResolvableProfile
+ XXX.item.component.SeededContainerLoot
- XXX.item.component.SuspiciousStewEffects
+ XXX.item.component.SuspiciousStewEffects$Entry
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipProvider
+ XXX.item.component.Unbreakable
- XXX.item.component.UseCooldown
+ XXX.item.component.UseRemainder
- XXX.item.component.UseRemainder$OnExtraCreatedRemainder
- XXX.item.crafting.package-info
- XXX.item.crafting.TransmuteResult
+ XXX.item.enchantment.ConditionalEffect
- XXX.item.enchantment.Enchantable
+ XXX.item.enchantment.EnchantedItemInUse
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$1
- XXX.item.enchantment.Enchantment$Builder
+ XXX.item.enchantment.Enchantment$Cost
- XXX.item.enchantment.Enchantment$EnchantmentDefinition
+ XXX.item.enchantment.EnchantmentEffectComponents
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.EnchantmentTarget
- XXX.item.enchantment.ItemEnchantments
+ XXX.item.enchantment.ItemEnchantments$Mutable
- XXX.item.enchantment.LevelBasedValue
+ XXX.item.enchantment.LevelBasedValue$Clamped
- XXX.item.enchantment.LevelBasedValue$Constant
+ XXX.item.enchantment.LevelBasedValue$Fraction
- XXX.item.enchantment.LevelBasedValue$LevelsSquared
+ XXX.item.enchantment.LevelBasedValue$Linear
- XXX.item.enchantment.LevelBasedValue$Lookup
+ XXX.item.enchantment.package-info
+ XXX.item.enchantment.Repairable
- XXX.item.enchantment.TargetedConditionalEffect
- XXX.item.equipment.ArmorMaterial
+ XXX.item.equipment.ArmorMaterials
- XXX.item.equipment.ArmorType
+ XXX.item.equipment.EquipmentAsset
- XXX.item.equipment.EquipmentAssets
+ XXX.item.equipment.Equippable
- XXX.item.equipment.Equippable$Builder
+ XXX.item.equipment.package-info
+ XXX.item.trading.ItemCost
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
- XXX.jfr.callback.package-info
+ XXX.jfr.callback.ProfiledDuration
+ XXX.jfr.event.ChunkGenerationEvent
- XXX.jfr.event.ChunkGenerationEvent$Fields
+ XXX.jfr.event.ChunkRegionIoEvent
- XXX.jfr.event.ChunkRegionIoEvent$Fields
+ XXX.jfr.event.ChunkRegionReadEvent
- XXX.jfr.event.ChunkRegionWriteEvent
+ XXX.jfr.event.NetworkSummaryEvent
- XXX.jfr.event.NetworkSummaryEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent$SumAggregation
+ XXX.jfr.event.package-info
- XXX.jfr.event.PacketEvent
+ XXX.jfr.event.PacketEvent$Fields
- XXX.jfr.event.PacketReceivedEvent
+ XXX.jfr.event.PacketSentEvent
- XXX.jfr.event.ServerTickTimeEvent
+ XXX.jfr.event.ServerTickTimeEvent$Fields
- XXX.jfr.event.StructureGenerationEvent
+ XXX.jfr.event.StructureGenerationEvent$Fields
- XXX.jfr.event.WorldLoadFinishedEvent
+ XXX.jfr.parse.JfrStatsParser
- XXX.jfr.parse.JfrStatsParser$1
+ XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
- XXX.jfr.parse.JfrStatsResult
+ XXX.jfr.parse.package-info
- XXX.jfr.serialize.JfrResultJsonSerializer
+ XXX.jfr.serialize.package-info
- XXX.jfr.stats.ChunkGenStat
+ XXX.jfr.stats.ChunkIdentification
- XXX.jfr.stats.CpuLoadStat
+ XXX.jfr.stats.FileIOStat
- XXX.jfr.stats.FileIOStat$Summary
+ XXX.jfr.stats.GcHeapStat
- XXX.jfr.stats.GcHeapStat$Summary
+ XXX.jfr.stats.GcHeapStat$Timing
- XXX.jfr.stats.IoSummary
+ XXX.jfr.stats.IoSummary$CountAndSize
+ XXX.jfr.stats.package-info
- XXX.jfr.stats.PacketIdentification
+ XXX.jfr.stats.StructureGenStat
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
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
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$ShapePairKey
+ XXX.level.block.Blocks
- XXX.level.block.BlockTypes
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BonemealableBlock$Type
- XXX.level.block.BonemealableFeaturePlacerBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BrushableBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
+ XXX.level.block.ChainBlock$1
- XXX.level.block.ChangeOverTimeBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChiseledBookShelfBlock
- XXX.level.block.ChiseledBookShelfBlock$1
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.FlowerBedBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrogspawnBlock
- XXX.level.block.FrostedIceBlock
+ XXX.level.block.FungusBlock
- XXX.level.block.FurnaceBlock
+ XXX.level.block.GameMasterBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GrindstoneBlock
+ XXX.level.block.HopperBlock$1
- XXX.level.block.HorizontalDirectionalBlock
+ XXX.level.block.HugeMushroomBlock
- XXX.level.block.IceBlock
+ XXX.level.block.InfestedBlock
- XXX.level.block.InfestedRotatedPillarBlock
+ XXX.level.block.IronBarsBlock
- XXX.level.block.JigsawBlock
+ XXX.level.block.JukeboxBlock
- XXX.level.block.KelpBlock
+ XXX.level.block.KelpPlantBlock
- XXX.level.block.LadderBlock
+ XXX.level.block.LadderBlock$1
- XXX.level.block.LeafLitterBlock
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
+ XXX.level.block.LightBlock
- XXX.level.block.LightningRodBlock
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LoomBlock
- XXX.level.block.MagmaBlock
+ XXX.level.block.MangroveLeavesBlock
- XXX.level.block.MangrovePropaguleBlock
+ XXX.level.block.MangroveRootsBlock
- XXX.level.block.Mirror
+ XXX.level.block.MossyCarpetBlock
- XXX.level.block.MossyCarpetBlock$1
+ XXX.level.block.MudBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MultifaceSpreadeableBlock
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
+ XXX.level.block.PipeBlock
- XXX.level.block.PitcherCropBlock
- XXX.level.block.PointedDripstoneBlock$1
+ XXX.level.block.PointedDripstoneBlock$FluidInfo
- XXX.level.block.Portal
+ XXX.level.block.Portal$Transition
- XXX.level.block.PotatoBlock
+ XXX.level.block.PowderSnowBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PumpkinBlock
- XXX.level.block.RailBlock
+ XXX.level.block.RailBlock$1
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RespawnAnchorBlock$1
+ XXX.level.block.RodBlock
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
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VaultBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallHangingSignBlock
- XXX.level.entity.UUIDLookup
+ XXX.level.levelgen.package-info
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
+ XXX.level.material.FlowingFluid$BlockStatePairKey
- XXX.level.material.FlowingFluid$SpreadContext
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
+ XXX.level.pathfinder.PathfindingContext
+ XXX.level.pathfinder.PathType
- XXX.level.pathfinder.PathTypeCache
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.pathfinder.WalkNodeEvaluator$1
+ XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalShape
+ XXX.level.portal.TeleportTransition
- XXX.level.portal.TeleportTransition$PostTeleportTransition
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
- XXX.level.redstone.CollectingNeighborUpdater
+ XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.DefaultRedstoneWireEvaluator
+ XXX.level.redstone.ExperimentalRedstoneUtils
- XXX.level.redstone.ExperimentalRedstoneWireEvaluator
+ XXX.level.redstone.InstantNeighborUpdater
- XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.Orientation
- XXX.level.redstone.Orientation$SideBias
+ XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.redstone.RedstoneWireEvaluator
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
+ XXX.level.saveddata.SavedData$Factory
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.FileNameDateFormatter
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelDataAndDimensions
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelSummary$CorruptedLevelSummary
+ XXX.level.storage.LevelSummary$SymlinkLevelSummary
- XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
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
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPreset
+ XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
+ XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.heightproviders.WeightedListHeight
- XXX.levelgen.material.MaterialRuleList
- XXX.levelgen.material.package-info
+ XXX.levelgen.material.WorldGenMaterialRule
- XXX.levelgen.placement.BiomeFilter
+ XXX.levelgen.placement.BlockPredicateFilter
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CountOnEveryLayerPlacement
- XXX.levelgen.placement.CountPlacement
+ XXX.levelgen.placement.EnvironmentScanPlacement
- XXX.levelgen.placement.FixedPlacement
- XXX.levelgen.placement.HeightmapPlacement
+ XXX.levelgen.placement.HeightRangePlacement
+ XXX.levelgen.placement.InSquarePlacement
- XXX.levelgen.placement.NoiseBasedCountPlacement
+ XXX.levelgen.placement.NoiseThresholdCountPlacement
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.PlacedFeature
+ XXX.levelgen.placement.PlacementContext
- XXX.levelgen.placement.PlacementFilter
+ XXX.levelgen.placement.PlacementModifier
- XXX.levelgen.placement.PlacementModifierType
+ XXX.levelgen.placement.RandomOffsetPlacement
- XXX.levelgen.placement.RarityFilter
+ XXX.levelgen.placement.RepeatingPlacement
- XXX.levelgen.placement.SurfaceRelativeThresholdFilter
+ XXX.levelgen.placement.SurfaceWaterDepthFilter
- XXX.levelgen.presets.package-info
+ XXX.levelgen.presets.WorldPreset
- XXX.levelgen.presets.WorldPresets
+ XXX.levelgen.presets.WorldPresets$Bootstrap
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuiltinStructures
+ XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationContext
+ XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.Structure$StructureSettings
+ XXX.levelgen.structure.Structure$StructureSettings$Builder
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
+ XXX.loot.functions.CopyComponentsFunction
- XXX.loot.functions.CopyComponentsFunction$Builder
+ XXX.loot.functions.CopyComponentsFunction$Source
- XXX.loot.functions.CopyCustomDataFunction
+ XXX.loot.functions.CopyCustomDataFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction$CopyOperation
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.EnchantedCountIncreaseFunction
- XXX.loot.functions.EnchantedCountIncreaseFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FilteredFunction
+ XXX.loot.functions.FunctionReference
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.ListOperation
+ XXX.loot.functions.ListOperation$Append
- XXX.loot.functions.ListOperation$Insert
+ XXX.loot.functions.ListOperation$ReplaceAll
- XXX.loot.functions.ListOperation$ReplaceSection
+ XXX.loot.functions.ListOperation$StandAlone
- XXX.loot.functions.ListOperation$Type
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.ModifyContainerContents
- XXX.loot.functions.package-info
+ XXX.loot.functions.SequenceFunction
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetBookCoverFunction
+ XXX.loot.functions.SetComponentsFunction
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetCustomDataFunction
- XXX.loot.functions.SetCustomModelDataFunction
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetFireworkExplosionFunction
- XXX.loot.functions.SetFireworksFunction
+ XXX.loot.functions.SetInstrumentFunction
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemFunction
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$Target
+ XXX.loot.functions.SetOminousBottleAmplifierFunction
- XXX.loot.functions.SetPotionFunction
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$EffectEntry
- XXX.loot.functions.SetWritableBookPagesFunction
+ XXX.loot.functions.SetWrittenBookPagesFunction
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.ToggleTooltips
- XXX.loot.functions.ToggleTooltips$ComponentToggle
+ XXX.loot.functions.ToggleTooltips$TooltipWither
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AllOfCondition
- XXX.loot.predicates.AllOfCondition$Builder
+ XXX.loot.predicates.AnyOfCondition
- XXX.loot.predicates.AnyOfCondition$Builder
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.CompositeLootItemCondition
+ XXX.loot.predicates.CompositeLootItemCondition$Builder
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.EnchantmentActiveCheck
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
- XXX.loot.predicates.LootItemRandomChanceWithEnchantedBonusCondition
+ XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
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
- XXX.minecraft.advancements.Advancement
+ XXX.minecraft.advancements.Advancement$Builder
- XXX.minecraft.advancements.AdvancementHolder
+ XXX.minecraft.advancements.AdvancementNode
- XXX.minecraft.advancements.AdvancementProgress
+ XXX.minecraft.advancements.AdvancementRequirements
- XXX.minecraft.advancements.AdvancementRequirements$Strategy
+ XXX.minecraft.advancements.AdvancementRewards
- XXX.minecraft.advancements.AdvancementRewards$Builder
+ XXX.minecraft.advancements.AdvancementTree
- XXX.minecraft.advancements.AdvancementTree$Listener
+ XXX.minecraft.advancements.AdvancementType
- XXX.minecraft.advancements.CriteriaTriggers
+ XXX.minecraft.advancements.Criterion
- XXX.minecraft.advancements.CriterionProgress
+ XXX.minecraft.advancements.CriterionTrigger
- XXX.minecraft.advancements.CriterionTrigger$Listener
+ XXX.minecraft.advancements.CriterionTriggerInstance
- XXX.minecraft.advancements.DisplayInfo
- XXX.minecraft.advancements.package-info
+ XXX.minecraft.advancements.TreeNodePosition
+ XXX.minecraft.client.AttackIndicatorStatus
- XXX.minecraft.client.Camera
+ XXX.minecraft.client.Camera$NearPlane
- XXX.minecraft.client.CameraType
+ XXX.minecraft.client.ClientBootstrap
- XXX.minecraft.client.ClientBrandRetriever
+ XXX.minecraft.client.ClientRecipeBook
- XXX.minecraft.client.CloudStatus
+ XXX.minecraft.client.CommandHistory
- XXX.minecraft.client.ComponentCollector
+ XXX.minecraft.client.DebugQueryHandler
- XXX.minecraft.client.DeltaTracker
+ XXX.minecraft.client.DeltaTracker$DefaultValue
- XXX.minecraft.client.DeltaTracker$Timer
+ XXX.minecraft.client.GameNarrator
- XXX.minecraft.client.GameNarrator$NarratorInitException
+ XXX.minecraft.client.GraphicsStatus
- XXX.minecraft.client.GuiMessage
+ XXX.minecraft.client.GuiMessage$Line
- XXX.minecraft.client.GuiMessageTag
+ XXX.minecraft.client.GuiMessageTag$Icon
- XXX.minecraft.client.HotbarManager
+ XXX.minecraft.client.InactivityFpsLimit
- XXX.minecraft.client.InputType
- XXX.minecraft.client.KeyboardHandler
+ XXX.minecraft.client.KeyboardHandler$1
+ XXX.minecraft.client.KeyMapping
- XXX.minecraft.client.Minecraft
+ XXX.minecraft.client.Minecraft$1
- XXX.minecraft.client.Minecraft$2
+ XXX.minecraft.client.Minecraft$ChatStatus
- XXX.minecraft.client.Minecraft$ChatStatus$1
+ XXX.minecraft.client.Minecraft$ChatStatus$2
- XXX.minecraft.client.Minecraft$ChatStatus$3
+ XXX.minecraft.client.Minecraft$ChatStatus$4
- XXX.minecraft.client.Minecraft$GameLoadCookie
+ XXX.minecraft.client.MouseHandler
- XXX.minecraft.client.NarratorStatus
+ XXX.minecraft.client.OptionInstance
- XXX.minecraft.client.OptionInstance$AltEnum
+ XXX.minecraft.client.OptionInstance$CaptionBasedToString
- XXX.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
+ XXX.minecraft.client.OptionInstance$CycleableValueSet
- XXX.minecraft.client.OptionInstance$CycleableValueSet$ValueSetter
+ XXX.minecraft.client.OptionInstance$Enum
- XXX.minecraft.client.OptionInstance$IntRange
+ XXX.minecraft.client.OptionInstance$IntRangeBase
- XXX.minecraft.client.OptionInstance$IntRangeBase$1
+ XXX.minecraft.client.OptionInstance$LazyEnum
- XXX.minecraft.client.OptionInstance$OptionInstanceSliderButton
+ XXX.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
- XXX.minecraft.client.OptionInstance$SliderableValueSet
+ XXX.minecraft.client.OptionInstance$TooltipSupplier
- XXX.minecraft.client.OptionInstance$UnitDouble
+ XXX.minecraft.client.OptionInstance$UnitDouble$1
- XXX.minecraft.client.OptionInstance$ValueSet
+ XXX.minecraft.client.Options
- XXX.minecraft.client.Options$1
+ XXX.minecraft.client.Options$2
- XXX.minecraft.client.Options$3
+ XXX.minecraft.client.Options$4
- XXX.minecraft.client.Options$5
+ XXX.minecraft.client.Options$FieldAccess
- XXX.minecraft.client.Options$OptionAccess
+ XXX.minecraft.client.package-info
+ XXX.minecraft.client.PeriodicNotificationManager
- XXX.minecraft.client.PeriodicNotificationManager$Notification
+ XXX.minecraft.client.PeriodicNotificationManager$NotificationTask
- XXX.minecraft.client.PrioritizeChunkUpdates
+ XXX.minecraft.client.ResourceLoadStateTracker
- XXX.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
+ XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason
- XXX.minecraft.client.ResourceLoadStateTracker$ReloadState
+ XXX.minecraft.client.Screenshot
- XXX.minecraft.client.ScrollWheelHandler
+ XXX.minecraft.client.StringSplitter
- XXX.minecraft.client.StringSplitter$1
+ XXX.minecraft.client.StringSplitter$FlatComponents
- XXX.minecraft.client.StringSplitter$LineBreakFinder
+ XXX.minecraft.client.StringSplitter$LineComponent
- XXX.minecraft.client.StringSplitter$LinePosConsumer
+ XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
- XXX.minecraft.client.StringSplitter$WidthProvider
+ XXX.minecraft.client.ToggleKeyMapping
- XXX.minecraft.client.User
+ XXX.minecraft.client.User$Type
+ XXX.minecraft.network.package-info
- XXX.minecraft.server.package-info
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.RecipeBookSettings
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
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
+ XXX.minecraft.tags.EnchantmentTags
- XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.FlatLevelGeneratorPresetTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.InstrumentTags
+ XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
- XXX.minecraft.tags.PaintingVariantTags
+ XXX.minecraft.tags.PoiTypeTags
- XXX.minecraft.tags.StructureTags
+ XXX.minecraft.tags.TagBuilder
- XXX.minecraft.tags.TagEntry
+ XXX.minecraft.tags.TagEntry$Lookup
- XXX.minecraft.tags.TagFile
+ XXX.minecraft.tags.TagKey
- XXX.minecraft.tags.TagLoader
+ XXX.minecraft.tags.TagLoader$1
- XXX.minecraft.tags.TagLoader$ElementLookup
+ XXX.minecraft.tags.TagLoader$EntryWithSource
- XXX.minecraft.tags.TagLoader$LoadResult
+ XXX.minecraft.tags.TagLoader$SortingEntry
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.WorldPresetTags
+ XXX.minecraft.util.AbortableIterationConsumer
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
- XXX.minecraft.util.ARGB
+ XXX.minecraft.util.ArrayListDeque
- XXX.minecraft.util.ArrayListDeque$DescendingIterator
+ XXX.minecraft.util.ArrayListDeque$ReversedView
- XXX.minecraft.util.BinaryAnimator
+ XXX.minecraft.util.BinaryAnimator$EasingFunction
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.Brightness
- XXX.minecraft.util.ByIdMap
+ XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.ClassTreeIdRegistry
- XXX.minecraft.util.ColorRGBA
+ XXX.minecraft.util.CommonColors
- XXX.minecraft.util.CommonLinks
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DelegateDataOutput
+ XXX.minecraft.util.DependencySorter
- XXX.minecraft.util.DependencySorter$Entry
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.EncoderCache
- XXX.minecraft.util.EncoderCache$1
+ XXX.minecraft.util.EncoderCache$2
- XXX.minecraft.util.EncoderCache$Key
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.ExtraCodecs
+ XXX.minecraft.util.ExtraCodecs$1
- XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ XXX.minecraft.util.ExtraCodecs$2
- XXX.minecraft.util.ExtraCodecs$3
+ XXX.minecraft.util.ExtraCodecs$4
- XXX.minecraft.util.ExtraCodecs$5
+ XXX.minecraft.util.ExtraCodecs$6
- XXX.minecraft.util.ExtraCodecs$7
+ XXX.minecraft.util.ExtraCodecs$LateBoundIdMapper
- XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
+ XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
- XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.package-info
- XXX.minecraft.world.package-info
+ XXX.model.dragon.DragonHeadModel
- XXX.model.dragon.EnderDragonModel
+ XXX.model.dragon.package-info
- XXX.model.geom.EntityModelSet
+ XXX.model.geom.LayerDefinitions
- XXX.model.geom.ModelLayerLocation
+ XXX.model.geom.ModelLayers
- XXX.model.geom.ModelPart
+ XXX.model.geom.ModelPart$Cube
- XXX.model.geom.ModelPart$Polygon
+ XXX.model.geom.ModelPart$Vertex
- XXX.model.geom.ModelPart$Visitor
+ XXX.model.geom.package-info
+ XXX.model.geom.PartNames
- XXX.model.geom.PartPose
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
- XXX.models.model.ItemModelUtils
+ XXX.models.model.ModelInstance
- XXX.models.model.ModelLocationUtils
+ XXX.models.model.ModelTemplate
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
+ XXX.mojang.math.Axis
- XXX.mojang.math.Constants
+ XXX.mojang.math.Divisor
- XXX.mojang.math.FieldsAreNonnullByDefault
+ XXX.mojang.math.GivensParameters
- XXX.mojang.math.MatrixUtil
+ XXX.mojang.math.MethodsReturnNonnullByDefault
- XXX.mojang.math.OctahedralGroup
+ XXX.mojang.math.OctahedralGroup$1
- XXX.mojang.math.package-info
- XXX.mojang.math.SymmetricGroup3
+ XXX.mojang.math.Transformation
+ XXX.mojang.realmsclient.package-info
+ XXX.mojang.realmsclient.RealmsAvailability
- XXX.mojang.realmsclient.RealmsAvailability$Result
+ XXX.mojang.realmsclient.RealmsAvailability$Type
- XXX.mojang.realmsclient.RealmsMainScreen
+ XXX.mojang.realmsclient.RealmsMainScreen$1
- XXX.mojang.realmsclient.RealmsMainScreen$2
+ XXX.mojang.realmsclient.RealmsMainScreen$AvailableSnapshotEntry
- XXX.mojang.realmsclient.RealmsMainScreen$ButtonEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$CrossButton
- XXX.mojang.realmsclient.RealmsMainScreen$EmptyEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$Entry
- XXX.mojang.realmsclient.RealmsMainScreen$LayoutState
+ XXX.mojang.realmsclient.RealmsMainScreen$NotificationButton
- XXX.mojang.realmsclient.RealmsMainScreen$NotificationMessageEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$ParentEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmsCall
- XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
- XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
+ XXX.mojang.realmsclient.Unit
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
+ XXX.monster.breeze.Breeze
- XXX.monster.breeze.Breeze$1
+ XXX.monster.breeze.BreezeAi
- XXX.monster.breeze.BreezeAi$SlideToTargetSink
+ XXX.monster.breeze.BreezeUtil
- XXX.monster.breeze.LongJump
- XXX.monster.breeze.package-info
+ XXX.monster.breeze.Shoot
- XXX.monster.breeze.ShootWhenStuck
+ XXX.monster.breeze.Slide
+ XXX.monster.creaking.Creaking
- XXX.monster.creaking.Creaking$CreakingBodyRotationControl
+ XXX.monster.creaking.Creaking$CreakingJumpControl
- XXX.monster.creaking.Creaking$CreakingLookControl
+ XXX.monster.creaking.Creaking$CreakingMoveControl
- XXX.monster.creaking.Creaking$CreakingPathNavigation
+ XXX.monster.creaking.Creaking$HomeNodeEvaluator
- XXX.monster.creaking.CreakingAi
+ XXX.monster.creaking.CreakingAi$1
- XXX.monster.creaking.package-info
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.HoglinBase
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.AbstractPiglin
- XXX.monster.piglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.PiglinArmPose
- XXX.monster.piglin.PiglinBrute
+ XXX.monster.piglin.PiglinBruteAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
+ XXX.monster.piglin.StartAdmiringItemIfSeen
- XXX.monster.piglin.StartHuntingHoglin
+ XXX.monster.piglin.StopAdmiringIfItemTooFarAway
- XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ XXX.monster.warden.AngerLevel
- XXX.monster.warden.AngerManagement
+ XXX.monster.warden.AngerManagement$1
- XXX.monster.warden.AngerManagement$Sorter
- XXX.monster.warden.package-info
+ XXX.monster.warden.Warden
- XXX.monster.warden.Warden$1
+ XXX.monster.warden.Warden$1$1
- XXX.monster.warden.Warden$2
+ XXX.monster.warden.Warden$VibrationUser
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
- XXX.multiplayer.chat.ChatListener
+ XXX.multiplayer.chat.ChatListener$Message
- XXX.multiplayer.chat.ChatLog
+ XXX.multiplayer.chat.ChatTrustLevel
- XXX.multiplayer.chat.LoggedChatEvent
+ XXX.multiplayer.chat.LoggedChatEvent$Type
- XXX.multiplayer.chat.LoggedChatMessage
+ XXX.multiplayer.chat.LoggedChatMessage$Player
- XXX.multiplayer.chat.LoggedChatMessage$System
+ XXX.multiplayer.chat.package-info
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
- XXX.network.chat.ClickEvent$ChangePage
- XXX.network.chat.ClickEvent$OpenFile
- XXX.network.chat.ClickEvent$RunCommand
+ XXX.network.chat.HoverEvent$Action$1
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.HoverEvent$ShowItem
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
+ XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$1
- XXX.network.chat.SignedMessageChain$DecodeException
+ XXX.network.chat.SignedMessageChain$Decoder
- XXX.network.chat.SignedMessageChain$Encoder
+ XXX.network.chat.SignedMessageLink
- XXX.network.chat.SignedMessageValidator
+ XXX.network.chat.SignedMessageValidator$KeyBased
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$1Collector
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.SubStringSource
+ XXX.network.chat.TextColor
- XXX.network.chat.ThrowingComponent
- XXX.network.codec.ByteBufCodecs
+ XXX.network.codec.ByteBufCodecs$1
- XXX.network.codec.ByteBufCodecs$10
+ XXX.network.codec.ByteBufCodecs$11
- XXX.network.codec.ByteBufCodecs$12
+ XXX.network.codec.ByteBufCodecs$13
- XXX.network.codec.ByteBufCodecs$14
+ XXX.network.codec.ByteBufCodecs$15
- XXX.network.codec.ByteBufCodecs$16
+ XXX.network.codec.ByteBufCodecs$17
- XXX.network.codec.ByteBufCodecs$18
+ XXX.network.codec.ByteBufCodecs$19
- XXX.network.codec.ByteBufCodecs$2
+ XXX.network.codec.ByteBufCodecs$20
- XXX.network.codec.ByteBufCodecs$21
+ XXX.network.codec.ByteBufCodecs$22
- XXX.network.codec.ByteBufCodecs$23
+ XXX.network.codec.ByteBufCodecs$24
- XXX.network.codec.ByteBufCodecs$25
+ XXX.network.codec.ByteBufCodecs$26
- XXX.network.codec.ByteBufCodecs$27
+ XXX.network.codec.ByteBufCodecs$28
- XXX.network.codec.ByteBufCodecs$29
+ XXX.network.codec.ByteBufCodecs$3
- XXX.network.codec.ByteBufCodecs$30
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
+ XXX.network.codec.StreamCodec$13
- XXX.network.codec.StreamCodec$14
+ XXX.network.codec.StreamCodec$15
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
+ XXX.network.config.JoinWorldTask
- XXX.network.config.package-info
- XXX.network.config.ServerResourcePackConfigurationTask
+ XXX.network.config.SynchronizeRegistriesTask
- XXX.network.protocol.BundleDelimiterPacket
+ XXX.network.protocol.BundlePacket
- XXX.network.protocol.BundlerInfo
+ XXX.network.protocol.BundlerInfo$1
- XXX.network.protocol.BundlerInfo$1$1
+ XXX.network.protocol.BundlerInfo$Bundler
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketType
+ XXX.network.protocol.PacketUtils
- XXX.network.protocol.ProtocolCodecBuilder
+ XXX.network.protocol.ProtocolInfoBuilder
- XXX.network.protocol.ProtocolInfoBuilder$1
+ XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
- XXX.network.protocol.ProtocolInfoBuilder$Implementation
- XXX.options.controls.ControlsScreen
+ XXX.options.controls.KeyBindsList
- XXX.options.controls.KeyBindsList$CategoryEntry
+ XXX.options.controls.KeyBindsList$CategoryEntry$1
- XXX.options.controls.KeyBindsList$Entry
+ XXX.options.controls.KeyBindsList$KeyEntry
- XXX.options.controls.KeyBindsScreen
+ XXX.options.controls.package-info
+ XXX.packrat.commands.Grammar
- XXX.packrat.commands.package-info
- XXX.packrat.commands.ResourceLocationParseRule
+ XXX.packrat.commands.ResourceLookupRule
- XXX.packrat.commands.ResourceSuggestion
+ XXX.packrat.commands.StringReaderParserState
- XXX.packrat.commands.StringReaderTerms
+ XXX.packrat.commands.StringReaderTerms$TerminalCharacter
- XXX.packrat.commands.StringReaderTerms$TerminalWord
+ XXX.packrat.commands.TagParseRule
+ XXX.packs.linkfs.DummyFileAttributes
- XXX.packs.linkfs.LinkFileSystem
+ XXX.packs.linkfs.LinkFileSystem$Builder
- XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
- XXX.packs.linkfs.LinkFSFileStore
+ XXX.packs.linkfs.LinkFSPath
- XXX.packs.linkfs.LinkFSPath$1
+ XXX.packs.linkfs.LinkFSPath$2
- XXX.packs.linkfs.LinkFSPath$3
+ XXX.packs.linkfs.LinkFSProvider
- XXX.packs.linkfs.LinkFSProvider$1
+ XXX.packs.linkfs.LinkFSProvider$2
- XXX.packs.linkfs.package-info
+ XXX.packs.linkfs.PathContents
- XXX.packs.linkfs.PathContents$1
+ XXX.packs.linkfs.PathContents$2
- XXX.packs.linkfs.PathContents$DirectoryContents
+ XXX.packs.linkfs.PathContents$FileContents
+ XXX.packs.metadata.MetadataSectionType
- XXX.packs.metadata.package-info
- XXX.packs.repository.BuiltInPackSource
+ XXX.packs.repository.BuiltInPackSource$1
- XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.FolderRepositorySource$FolderPackDetector
- XXX.packs.repository.KnownPack
+ XXX.packs.repository.Pack
- XXX.packs.repository.Pack$Metadata
+ XXX.packs.repository.Pack$Position
- XXX.packs.repository.Pack$ResourcesSupplier
- XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackDetector
+ XXX.packs.repository.PackRepository
- XXX.packs.repository.PackSource
+ XXX.packs.repository.PackSource$1
- XXX.packs.repository.RepositorySource
+ XXX.packs.repository.ServerPacksSource
+ XXX.packs.resources.CloseableResourceManager
- XXX.packs.resources.FallbackResourceManager
+ XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
- XXX.packs.resources.FallbackResourceManager$EntryStack
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- XXX.packs.resources.FallbackResourceManager$PackEntry
+ XXX.packs.resources.FallbackResourceManager$ResourceWithSource
- XXX.packs.resources.IoSupplier
+ XXX.packs.resources.MultiPackResourceManager
- XXX.packs.resources.package-info
- XXX.packs.resources.PreparableReloadListener
+ XXX.packs.resources.PreparableReloadListener$PreparationBarrier
- XXX.packs.resources.ProfiledReloadInstance
+ XXX.packs.resources.ProfiledReloadInstance$State
+ XXX.packs.resources.ReloadableResourceManager
- XXX.packs.resources.ReloadInstance
- XXX.packs.resources.Resource
+ XXX.packs.resources.ResourceFilterSection
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManager$Empty
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.ResourceMetadata
- XXX.packs.resources.ResourceMetadata$1
+ XXX.packs.resources.ResourceMetadata$2
- XXX.packs.resources.ResourceMetadata$Builder
+ XXX.packs.resources.ResourceMetadata$Builder$1
- XXX.packs.resources.ResourceProvider
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.parsing.packrat.Atom
+ XXX.parsing.packrat.Control
- XXX.parsing.packrat.Dictionary
+ XXX.parsing.packrat.ErrorCollector
- XXX.parsing.packrat.ErrorCollector$LongestOnly
+ XXX.parsing.packrat.ErrorEntry
+ XXX.parsing.packrat.package-info
- XXX.parsing.packrat.ParseState
+ XXX.parsing.packrat.ParseState$CacheEntry
- XXX.parsing.packrat.ParseState$CacheKey
+ XXX.parsing.packrat.Rule
- XXX.parsing.packrat.Rule$RuleAction
+ XXX.parsing.packrat.Rule$SimpleRuleAction
- XXX.parsing.packrat.Rule$WrappedTerm
+ XXX.parsing.packrat.Scope
- XXX.parsing.packrat.SuggestionSupplier
+ XXX.parsing.packrat.Term
- XXX.parsing.packrat.Term$1
+ XXX.parsing.packrat.Term$2
- XXX.parsing.packrat.Term$Alternative
+ XXX.parsing.packrat.Term$Marker
- XXX.parsing.packrat.Term$Maybe
+ XXX.parsing.packrat.Term$Reference
- XXX.parsing.packrat.Term$Sequence
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$1
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.MinecartCollisionContext
- XXX.phys.shapes.MinecartCollisionContext$1
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.pools.alias.Direct
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.Random
+ XXX.pools.alias.RandomGroup
- XXX.profiling.jfr.Environment
+ XXX.profiling.jfr.JfrProfiler
- XXX.profiling.jfr.JfrProfiler$1
+ XXX.profiling.jfr.JvmProfiler
- XXX.profiling.jfr.JvmProfiler$NoOpProfiler
- XXX.profiling.jfr.package-info
+ XXX.profiling.jfr.Percentiles
- XXX.profiling.jfr.SummaryReporter
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
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
- XXX.protocol.common.ClientboundCustomPayloadPacket
+ XXX.protocol.common.ClientboundCustomReportDetailsPacket
- XXX.protocol.common.ClientboundDisconnectPacket
+ XXX.protocol.common.ClientboundKeepAlivePacket
- XXX.protocol.common.ClientboundPingPacket
+ XXX.protocol.common.ClientboundResourcePackPopPacket
- XXX.protocol.common.ClientboundResourcePackPushPacket
+ XXX.protocol.common.ClientboundServerLinksPacket
- XXX.protocol.common.ClientboundStoreCookiePacket
+ XXX.protocol.common.ClientboundTransferPacket
- XXX.protocol.common.ClientboundUpdateTagsPacket
+ XXX.protocol.common.ClientCommonPacketListener
+ XXX.protocol.common.CommonPacketTypes
+ XXX.protocol.common.package-info
+ XXX.protocol.common.ServerboundClientInformationPacket
- XXX.protocol.common.ServerboundCustomPayloadPacket
+ XXX.protocol.common.ServerboundKeepAlivePacket
- XXX.protocol.common.ServerboundPongPacket
+ XXX.protocol.common.ServerboundResourcePackPacket
- XXX.protocol.common.ServerboundResourcePackPacket$Action
- XXX.protocol.common.ServerCommonPacketListener
+ XXX.protocol.configuration.ClientboundFinishConfigurationPacket
- XXX.protocol.configuration.ClientboundRegistryDataPacket
+ XXX.protocol.configuration.ClientboundResetChatPacket
- XXX.protocol.configuration.ClientboundSelectKnownPacks
+ XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
- XXX.protocol.configuration.ClientConfigurationPacketListener
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
- XXX.protocol.game.ClientGamePacketListener
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
+ XXX.providers.number.EnchantmentLevelProvider
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.StorageValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.realmsclient.client.FileDownload
+ XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
- XXX.realmsclient.client.FileDownload$ProgressListener
+ XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
- XXX.realmsclient.client.FileUpload
+ XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
+ XXX.realmsclient.client.package-info
- XXX.realmsclient.client.Ping
+ XXX.realmsclient.client.Ping$Region
- XXX.realmsclient.client.RealmsClient
+ XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
- XXX.realmsclient.client.RealmsClient$Environment
+ XXX.realmsclient.client.RealmsClientConfig
- XXX.realmsclient.client.RealmsError
+ XXX.realmsclient.client.RealmsError$AuthenticationError
- XXX.realmsclient.client.RealmsError$CustomError
+ XXX.realmsclient.client.RealmsError$ErrorWithJsonPayload
- XXX.realmsclient.client.RealmsError$ErrorWithRawPayload
+ XXX.realmsclient.client.Request
- XXX.realmsclient.client.Request$Delete
+ XXX.realmsclient.client.Request$Get
- XXX.realmsclient.client.Request$Post
+ XXX.realmsclient.client.Request$Put
- XXX.realmsclient.client.UploadStatus
+ XXX.realmsclient.dto.Backup
- XXX.realmsclient.dto.BackupList
+ XXX.realmsclient.dto.GuardedSerializer
- XXX.realmsclient.dto.Ops
+ XXX.realmsclient.dto.package-info
+ XXX.realmsclient.dto.PendingInvite
- XXX.realmsclient.dto.PendingInvitesList
+ XXX.realmsclient.dto.PingResult
- XXX.realmsclient.dto.PlayerInfo
+ XXX.realmsclient.dto.RealmsDescriptionDto
- XXX.realmsclient.dto.RealmsNews
+ XXX.realmsclient.dto.RealmsNotification
- XXX.realmsclient.dto.RealmsNotification$InfoPopup
+ XXX.realmsclient.dto.RealmsNotification$UrlButton
- XXX.realmsclient.dto.RealmsNotification$VisitUrl
+ XXX.realmsclient.dto.RealmsServer
- XXX.realmsclient.dto.RealmsServer$Compatibility
+ XXX.realmsclient.dto.RealmsServer$McoServerComparator
- XXX.realmsclient.dto.RealmsServer$State
+ XXX.realmsclient.dto.RealmsServer$WorldType
- XXX.realmsclient.dto.RealmsServerAddress
+ XXX.realmsclient.dto.RealmsServerList
- XXX.realmsclient.dto.RealmsServerPlayerLists
+ XXX.realmsclient.dto.RealmsSettings
- XXX.realmsclient.dto.RealmsText
+ XXX.realmsclient.dto.RealmsWorldOptions
- XXX.realmsclient.dto.RealmsWorldResetDto
+ XXX.realmsclient.dto.ReflectionBasedSerialization
- XXX.realmsclient.dto.RegionPingResult
+ XXX.realmsclient.dto.ServerActivity
- XXX.realmsclient.dto.ServerActivityList
+ XXX.realmsclient.dto.Subscription
- XXX.realmsclient.dto.Subscription$SubscriptionType
+ XXX.realmsclient.dto.UploadInfo
- XXX.realmsclient.dto.ValueObject
+ XXX.realmsclient.dto.WorldDownload
- XXX.realmsclient.dto.WorldTemplate
+ XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
- XXX.realmsclient.dto.WorldTemplatePaginatedList
- XXX.realmsclient.exception.package-info
- XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
+ XXX.realmsclient.exception.RealmsHttpException
- XXX.realmsclient.exception.RealmsServiceException
+ XXX.realmsclient.exception.RetryCallException
+ XXX.realmsclient.gui.package-info
+ XXX.realmsclient.gui.RealmsDataFetcher
- XXX.realmsclient.gui.RealmsDataFetcher$ServerListData
+ XXX.realmsclient.gui.RealmsNewsManager
- XXX.realmsclient.gui.RealmsServerList
+ XXX.realmsclient.gui.RealmsWorldSlotButton
- XXX.realmsclient.gui.RealmsWorldSlotButton$Action
+ XXX.realmsclient.gui.RealmsWorldSlotButton$State
- XXX.realmsclient.gui.RowButton
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.LevelType
+ XXX.realmsclient.util.package-info
- XXX.realmsclient.util.RealmsPersistence
+ XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- XXX.realmsclient.util.RealmsTextureManager
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
+ XXX.rule.blockentity.AppendLoot
- XXX.rule.blockentity.AppendStatic
+ XXX.rule.blockentity.Clear
+ XXX.rule.blockentity.package-info
- XXX.rule.blockentity.Passthrough
+ XXX.rule.blockentity.RuleBlockEntityModifier
- XXX.rule.blockentity.RuleBlockEntityModifierType
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecorationType
- XXX.saveddata.maps.MapDecorationTypes
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapId
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- XXX.screens.achievement.StatsScreen$ItemStatisticsList
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList
- XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$Sprites
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
+ XXX.screens.advancements.AdvancementWidgetType$1
+ XXX.screens.advancements.package-info
- XXX.screens.debug.GameModeSwitcherScreen
+ XXX.screens.debug.GameModeSwitcherScreen$1
- XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
- XXX.screens.debug.package-info
+ XXX.screens.inventory.AbstractCommandBlockEditScreen
- XXX.screens.inventory.AbstractCommandBlockEditScreen$1
+ XXX.screens.inventory.AbstractContainerScreen
- XXX.screens.inventory.AbstractFurnaceScreen
+ XXX.screens.inventory.AbstractRecipeBookScreen
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
+ XXX.screens.inventory.BookViewScreen$BookAccess
- XXX.screens.inventory.BrewingStandScreen
+ XXX.screens.inventory.CartographyTableScreen
- XXX.screens.inventory.CommandBlockEditScreen
+ XXX.screens.inventory.CommandBlockEditScreen$1
- XXX.screens.inventory.ContainerScreen
+ XXX.screens.inventory.CrafterScreen
- XXX.screens.inventory.CrafterScreen$1
+ XXX.screens.inventory.CraftingScreen
- XXX.screens.inventory.CreativeInventoryListener
+ XXX.screens.inventory.CreativeModeInventoryScreen
- XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ XXX.screens.inventory.CyclingSlotBackground
- XXX.screens.inventory.DispenserScreen
+ XXX.screens.inventory.EffectsInInventory
- XXX.screens.inventory.EnchantmentNames
+ XXX.screens.inventory.EnchantmentScreen
- XXX.screens.inventory.FurnaceScreen
+ XXX.screens.inventory.GrindstoneScreen
- XXX.screens.inventory.HangingSignEditScreen
+ XXX.screens.inventory.HopperScreen
- XXX.screens.inventory.HorseInventoryScreen
+ XXX.screens.inventory.InventoryScreen
- XXX.screens.inventory.ItemCombinerScreen
+ XXX.screens.inventory.JigsawBlockEditScreen
- XXX.screens.inventory.JigsawBlockEditScreen$1
+ XXX.screens.inventory.LecternScreen
- XXX.screens.inventory.LecternScreen$1
+ XXX.screens.inventory.LoomScreen
- XXX.screens.inventory.MenuAccess
+ XXX.screens.inventory.MerchantScreen
- XXX.screens.inventory.MerchantScreen$TradeOfferButton
+ XXX.screens.inventory.MinecartCommandBlockEditScreen
+ XXX.screens.inventory.package-info
- XXX.screens.inventory.PageButton
+ XXX.screens.inventory.ShulkerBoxScreen
- XXX.screens.inventory.SignEditScreen
+ XXX.screens.inventory.SmithingScreen
- XXX.screens.inventory.SmokerScreen
+ XXX.screens.inventory.StonecutterScreen
- XXX.screens.inventory.StructureBlockEditScreen
+ XXX.screens.inventory.StructureBlockEditScreen$1
- XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.multiplayer.JoinMultiplayerScreen
- XXX.screens.multiplayer.package-info
- XXX.screens.multiplayer.SafetyScreen
+ XXX.screens.multiplayer.ServerLinksScreen
- XXX.screens.multiplayer.ServerLinksScreen$LinkList
+ XXX.screens.multiplayer.ServerLinksScreen$LinkListEntry
- XXX.screens.multiplayer.ServerReconfigScreen
+ XXX.screens.multiplayer.ServerSelectionList
- XXX.screens.multiplayer.ServerSelectionList$1
+ XXX.screens.multiplayer.ServerSelectionList$Entry
- XXX.screens.multiplayer.ServerSelectionList$LANHeader
+ XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
+ XXX.screens.multiplayer.WarningScreen
+ XXX.screens.options.AccessibilityOptionsScreen
- XXX.screens.options.ChatOptionsScreen
+ XXX.screens.options.FontOptionsScreen
- XXX.screens.options.LanguageSelectScreen
+ XXX.screens.options.LanguageSelectScreen$LanguageSelectionList
- XXX.screens.options.LanguageSelectScreen$LanguageSelectionList$Entry
+ XXX.screens.options.MouseSettingsScreen
- XXX.screens.options.OnlineOptionsScreen
+ XXX.screens.options.OptionsScreen
- XXX.screens.options.OptionsSubScreen
- XXX.screens.options.package-info
+ XXX.screens.options.SkinCustomizationScreen
- XXX.screens.options.SoundOptionsScreen
+ XXX.screens.options.UnsupportedGraphicsWarningScreen
- XXX.screens.options.UnsupportedGraphicsWarningScreen$ButtonOption
+ XXX.screens.options.VideoSettingsScreen
- XXX.screens.packs.package-info
- XXX.screens.packs.PackSelectionModel
+ XXX.screens.packs.PackSelectionModel$Entry
- XXX.screens.packs.PackSelectionModel$EntryBase
+ XXX.screens.packs.PackSelectionModel$SelectedPackEntry
- XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
+ XXX.screens.packs.PackSelectionScreen
- XXX.screens.packs.PackSelectionScreen$1
+ XXX.screens.packs.PackSelectionScreen$Watcher
- XXX.screens.packs.TransferableSelectionList
+ XXX.screens.packs.TransferableSelectionList$PackEntry
+ XXX.screens.recipebook.CraftingRecipeBookComponent
- XXX.screens.recipebook.FurnaceRecipeBookComponent
+ XXX.screens.recipebook.GhostSlots
- XXX.screens.recipebook.GhostSlots$GhostSlot
+ XXX.screens.recipebook.OverlayRecipeComponent
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayCraftingRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
+ XXX.screens.recipebook.package-info
- XXX.screens.recipebook.RecipeBookComponent
+ XXX.screens.recipebook.RecipeBookComponent$TabInfo
- XXX.screens.recipebook.RecipeBookPage
+ XXX.screens.recipebook.RecipeBookTabButton
- XXX.screens.recipebook.RecipeButton
+ XXX.screens.recipebook.RecipeButton$ResolvedEntry
- XXX.screens.recipebook.RecipeCollection
+ XXX.screens.recipebook.RecipeCollection$CraftableStatus
- XXX.screens.recipebook.RecipeUpdateListener
+ XXX.screens.recipebook.SearchRecipeBookCategory
- XXX.screens.recipebook.SlotSelectTime
- XXX.screens.reporting.AbstractReportScreen
+ XXX.screens.reporting.AbstractReportScreen$DiscardReportWarningScreen
- XXX.screens.reporting.ChatReportScreen
+ XXX.screens.reporting.ChatSelectionLogFiller
- XXX.screens.reporting.ChatSelectionLogFiller$Output
+ XXX.screens.reporting.ChatSelectionScreen
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
+ XXX.screens.reporting.NameReportScreen
+ XXX.screens.reporting.package-info
- XXX.screens.reporting.ReportPlayerScreen
+ XXX.screens.reporting.ReportReasonSelectionScreen
- XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
+ XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
- XXX.screens.reporting.SkinReportScreen
+ XXX.screens.social.package-info
- XXX.screens.social.PlayerEntry
+ XXX.screens.social.PlayerEntry$1
- XXX.screens.social.PlayerEntry$2
+ XXX.screens.social.PlayerEntry$3
- XXX.screens.social.PlayerSocialManager
+ XXX.screens.social.SocialInteractionsPlayerList
- XXX.screens.social.SocialInteractionsScreen
+ XXX.screens.social.SocialInteractionsScreen$1
- XXX.screens.social.SocialInteractionsScreen$Page
- XXX.screens.telemetry.package-info
- XXX.screens.telemetry.TelemetryEventWidget
+ XXX.screens.telemetry.TelemetryEventWidget$Content
- XXX.screens.telemetry.TelemetryEventWidget$ContentBuilder
+ XXX.screens.telemetry.TelemetryInfoScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
+ XXX.screens.worldselection.CreateWorldCallback
- XXX.screens.worldselection.CreateWorldScreen
+ XXX.screens.worldselection.CreateWorldScreen$GameTab
- XXX.screens.worldselection.CreateWorldScreen$MoreTab
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$1
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab$2
- XXX.screens.worldselection.DataPackReloadCookie
+ XXX.screens.worldselection.EditGameRulesScreen
- XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
+ XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
- XXX.screens.worldselection.EditGameRulesScreen$GameRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList
- XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
+ XXX.screens.worldselection.EditWorldScreen
- XXX.screens.worldselection.ExperimentsScreen
+ XXX.screens.worldselection.ExperimentsScreen$ScrollArea
- XXX.screens.worldselection.InitialWorldCreationOptions
+ XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.package-info
- XXX.screens.worldselection.PresetEditor
+ XXX.screens.worldselection.SelectWorldScreen
- XXX.screens.worldselection.SwitchGrid
+ XXX.screens.worldselection.SwitchGrid$Builder
- XXX.screens.worldselection.SwitchGrid$InfoUnderneathSettings
+ XXX.screens.worldselection.SwitchGrid$LabeledSwitch
- XXX.screens.worldselection.SwitchGrid$SwitchBuilder
+ XXX.screens.worldselection.WorldCreationContext
- XXX.screens.worldselection.WorldCreationContext$DimensionsUpdater
+ XXX.screens.worldselection.WorldCreationContext$OptionsModifier
- XXX.screens.worldselection.WorldCreationContextMapper
+ XXX.screens.worldselection.WorldCreationUiState
- XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
+ XXX.screens.worldselection.WorldCreationUiState$WorldTypeEntry
- XXX.screens.worldselection.WorldOpenFlows
+ XXX.screens.worldselection.WorldOpenFlows$1Data
- XXX.screens.worldselection.WorldSelectionList
+ XXX.screens.worldselection.WorldSelectionList$Entry
- XXX.screens.worldselection.WorldSelectionList$LoadingHeader
+ XXX.screens.worldselection.WorldSelectionList$WorldListEntry
- XXX.server.commands.FillCommand$Affector
- XXX.server.commands.FillCommand$Filter
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.FillCommand$NullableCommandFunction
- XXX.server.commands.package-info
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpawnArmorTrimsCommand
+ XXX.server.commands.SpectateCommand
- XXX.server.commands.SpreadPlayersCommand
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
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
+ XXX.server.level.ChunkGenerationTask
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkLevel
- XXX.server.level.ChunkLevel$1
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkResult
+ XXX.server.level.ChunkResult$Fail
- XXX.server.level.ChunkResult$Success
+ XXX.server.level.ChunkTaskDispatcher
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueue$TasksForChunk
- XXX.server.level.ChunkTracker
+ XXX.server.level.ChunkTrackingView
- XXX.server.level.ChunkTrackingView$1
+ XXX.server.level.ChunkTrackingView$Positioned
- XXX.server.level.ClientInformation
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.package-info
- XXX.server.level.ParticleStatus
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.SimulationChunkTracker
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.ThrottlingChunkTaskDispatcher
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.TicketType$TicketUse
+ XXX.server.level.WorldGenRegion
+ XXX.server.network.CommonListenerCookie
- XXX.server.network.ConfigurationTask
+ XXX.server.network.ConfigurationTask$Type
- XXX.server.network.Filterable
+ XXX.server.network.FilteredText
- XXX.server.network.LegacyProtocolUtils
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.LegacyTextFilter
+ XXX.server.network.LegacyTextFilter$1
- XXX.server.network.LegacyTextFilter$JoinOrLeaveEncoder
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
- XXX.server.network.PlayerChunkSender
+ XXX.server.network.PlayerSafetyServiceTextFilter
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
- XXX.server.network.ServerTextFilter
+ XXX.server.network.ServerTextFilter$IgnoreStrategy
- XXX.server.network.ServerTextFilter$MessageEncoder
+ XXX.server.network.ServerTextFilter$PlayerContext
- XXX.server.network.ServerTextFilter$RequestFailedException
+ XXX.server.network.TextFilter
- XXX.server.network.TextFilter$1
+ XXX.server.packs.AbstractPackResources
- XXX.server.packs.BuiltInMetadata
+ XXX.server.packs.CompositePackResources
- XXX.server.packs.DownloadCacheCleaner
+ XXX.server.packs.DownloadCacheCleaner$1
- XXX.server.packs.DownloadCacheCleaner$PathAndPriority
+ XXX.server.packs.DownloadCacheCleaner$PathAndTime
- XXX.server.packs.DownloadQueue
+ XXX.server.packs.DownloadQueue$BatchConfig
- XXX.server.packs.DownloadQueue$BatchResult
+ XXX.server.packs.DownloadQueue$DownloadRequest
- XXX.server.packs.DownloadQueue$FileInfoEntry
+ XXX.server.packs.DownloadQueue$LogEntry
- XXX.server.packs.FeatureFlagsMetadataSection
+ XXX.server.packs.FilePackResources
- XXX.server.packs.FilePackResources$FileResourcesSupplier
+ XXX.server.packs.FilePackResources$SharedZipFileAccess
- XXX.server.packs.OverlayMetadataSection
+ XXX.server.packs.OverlayMetadataSection$OverlayEntry
+ XXX.server.packs.package-info
- XXX.server.packs.PackLocationInfo
+ XXX.server.packs.PackResources
- XXX.server.packs.PackResources$ResourceOutput
+ XXX.server.packs.PackSelectionConfig
- XXX.server.packs.PackType
+ XXX.server.packs.PathPackResources
- XXX.server.packs.PathPackResources$PathResourcesSupplier
+ XXX.server.packs.VanillaPackResources
- XXX.server.packs.VanillaPackResourcesBuilder
+ XXX.server.players.BanListEntry
- XXX.server.players.GameProfileCache
+ XXX.server.players.GameProfileCache$1
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
- XXX.spectator.categories.package-info
- XXX.spectator.categories.SpectatorPage
+ XXX.spectator.categories.TeleportToPlayerMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
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
- XXX.state.properties.ComparatorMode
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ContainerComponentManipulator
+ XXX.storage.loot.ContainerComponentManipulators
- XXX.storage.loot.ContainerComponentManipulators$1
+ XXX.storage.loot.ContainerComponentManipulators$2
- XXX.storage.loot.ContainerComponentManipulators$3
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootDataType
- XXX.storage.loot.LootDataType$Validator
+ XXX.storage.loot.LootParams
- XXX.storage.loot.LootParams$Builder
+ XXX.storage.loot.LootParams$DynamicDrop
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.package-info
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
+ XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.StructurePlacement
+ XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReducer
+ XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.DimensionPadding
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
+ XXX.structure.templatesystem.LiquidSettings
- XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.ProtectedBlockProcessor
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$JigsawBlockInfo
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.StructureTemplateManager
+ XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- XXX.structure.templatesystem.StructureTemplateManager$Source
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
- XXX.util.datafix.DataFixTypes$1
- XXX.util.datafix.ExtraDataFixUtils
+ XXX.util.datafix.FixWolfHealth
- XXX.util.datafix.LegacyComponentDataFixUtils
+ XXX.util.debugchart.AbstractSampleLogger
- XXX.util.debugchart.DebugSampleSubscriptionTracker
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
+ XXX.util.debugchart.LocalSampleLogger
+ XXX.util.debugchart.package-info
- XXX.util.debugchart.RemoteDebugSampleType
+ XXX.util.debugchart.RemoteSampleLogger
- XXX.util.debugchart.SampleLogger
+ XXX.util.debugchart.SampleStorage
- XXX.util.debugchart.TpsDebugDimensions
- XXX.util.eventlog.EventLogDirectory
+ XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$File
+ XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$FileList
+ XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog
+ XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader
+ XXX.util.eventlog.JsonEventLogReader$1
- XXX.util.eventlog.package-info
+ XXX.util.parsing.package-info
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
- XXX.util.profiling.Profiler
+ XXX.util.profiling.Profiler$Scope
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$CombinedProfileFiller
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.profiling.TracyZoneFiller
- XXX.util.profiling.TracyZoneFiller$PlotAndValue
+ XXX.util.profiling.Zone
+ XXX.util.random.SimpleWeightedRandomList
+ XXX.util.random.Weight
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedList
- XXX.util.random.WeightedList$Compact
- XXX.util.random.WeightedList$Selector
+ XXX.util.random.WeightedRandom
- XXX.util.task.CloseServerTask
+ XXX.util.task.ConnectTask
- XXX.util.task.DownloadTask
+ XXX.util.task.GetServerDetailsTask
- XXX.util.task.LongRunningTask
+ XXX.util.task.OpenServerTask
- XXX.util.task.package-info
- XXX.util.task.RealmCreationTask
+ XXX.util.task.ResettingTemplateWorldTask
- XXX.util.task.ResettingWorldTask
+ XXX.util.task.RestoreTask
- XXX.util.task.SwitchMinigameTask
+ XXX.util.task.SwitchSlotTask
+ XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiRecord$Packed
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiSection$Packed
+ XXX.village.poi.PoiType
- XXX.village.poi.PoiTypes
+ XXX.world.entity.Display$RenderState
- XXX.world.entity.Display$TextDisplay
+ XXX.world.entity.Display$TextDisplay$Align
- XXX.world.entity.Display$TextDisplay$CachedInfo
+ XXX.world.entity.Display$TextDisplay$CachedLine
- XXX.world.entity.Display$TextDisplay$LineSplitter
+ XXX.world.entity.Display$TextDisplay$TextRenderState
- XXX.world.entity.Display$TransformationInterpolator
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySpawnReason
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.EquipmentSlotGroup
+ XXX.world.entity.EquipmentSlotGroup$1
- XXX.world.entity.EquipmentTable
+ XXX.world.entity.EquipmentUser
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.Interaction
- XXX.world.entity.Interaction$PlayerAction
- XXX.world.entity.InterpolationHandler$InterpolationData
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.Leashable
- XXX.world.entity.Leashable$LeashData
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OminousItemSpawner
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.package-info
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.PortalProcessor
+ XXX.world.entity.Pose
- XXX.world.entity.PositionMoveRotation
+ XXX.world.entity.Relative
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SlotAccess$4
- XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacementType
- XXX.world.entity.SpawnPlacementTypes
+ XXX.world.entity.SpawnPlacementTypes$1
+ XXX.world.entity.TamableAnimal
- XXX.world.entity.TamableAnimal$TamableAnimalPanicGoal
+ XXX.world.entity.Targeting
- XXX.world.entity.TraceableEntity
+ XXX.world.entity.VariantHolder
- XXX.world.entity.WalkAnimationState
+ XXX.world.flag.FeatureElement
- XXX.world.flag.FeatureFlag
+ XXX.world.flag.FeatureFlagRegistry
- XXX.world.flag.FeatureFlagRegistry$Builder
+ XXX.world.flag.FeatureFlags
+ XXX.world.flag.FeatureFlagSet
- XXX.world.flag.FeatureFlagUniverse
- XXX.world.flag.package-info
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AbstractCraftingMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AbstractFurnaceMenu$1
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.ArmorSlot
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
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.ItemCombinerMenu$3
+ XXX.world.inventory.ItemCombinerMenu$4
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
+ XXX.world.inventory.RecipeBookMenu$PostPlaceAction
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeCraftingHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SlotRange
+ XXX.world.inventory.SlotRange$1
- XXX.world.inventory.SlotRanges
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
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.EitherHolder
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.InkSacItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$Properties
+ XXX.world.item.Item$TooltipContext
- XXX.world.item.Item$TooltipContext$1
+ XXX.world.item.Item$TooltipContext$2
- XXX.world.item.Item$TooltipContext$3
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStack$4
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUseAnimation
+ XXX.world.item.ItemUtils
+ XXX.world.item.JukeboxPlayable
- XXX.world.item.JukeboxSong
+ XXX.world.item.JukeboxSongPlayer
- XXX.world.item.JukeboxSongPlayer$OnSongChanged
+ XXX.world.item.JukeboxSongs
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MaceItem
- XXX.world.item.MapItem
+ XXX.world.item.MapItem$1
- XXX.world.item.MinecartItem
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
- XXX.world.item.package-info
+ XXX.world.item.PickaxeItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.TippedArrowItem
- XXX.world.item.ToolMaterial
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.ChunkPos
+ XXX.world.level.ChunkPos$1
- XXX.world.level.ChunkPos$2
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
+ XXX.world.level.EmptyBlockAndTintGetter
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EntityBasedExplosionDamageCalculator
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.ExplosionDamageCalculator
- XXX.world.level.FoliageColor
+ XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.package-info
- XXX.world.level.TicketStorage$ChunkUpdated
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.phys.Vec3$1
+ XXX.world.scores.DisplaySlot
- XXX.world.scores.DisplaySlot$1
+ XXX.world.scores.Objective
+ XXX.world.scores.package-info
- XXX.world.scores.PlayerScoreEntry
+ XXX.world.scores.PlayerScores
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.ReadOnlyScoreInfo
- XXX.world.scores.Score
+ XXX.world.scores.ScoreAccess
- XXX.world.scores.Scoreboard
+ XXX.world.scores.Scoreboard$1
- XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.ScoreHolder
+ XXX.world.scores.ScoreHolder$1
- XXX.world.scores.ScoreHolder$2
+ XXX.world.scores.ScoreHolder$3
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
- XXX.world.ticks.BlackholeTickAccess
+ XXX.world.ticks.BlackholeTickAccess$1
- XXX.world.ticks.BlackholeTickAccess$2
+ XXX.world.ticks.ContainerSingleItem
- XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
+ XXX.world.ticks.LevelChunkTicks
- XXX.world.ticks.LevelTickAccess
+ XXX.world.ticks.LevelTicks
- XXX.world.ticks.LevelTicks$PosAndContainerConsumer
+ XXX.world.ticks.package-info
+ XXX.world.ticks.ProtoChunkTicks
- XXX.world.ticks.SavedTick
+ XXX.world.ticks.SavedTick$1
- XXX.world.ticks.ScheduledTick
+ XXX.world.ticks.ScheduledTick$1
- XXX.world.ticks.SerializableTickContainer
+ XXX.world.ticks.TickAccess
- XXX.world.ticks.TickContainerAccess
+ XXX.world.ticks.TickPriority
- XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.audio.Library +1M -1M
```
```
XXX.blaze3d.platform.FramerateLimitTracker +2M
```
```
XXX.client.player.ClientInput +1M | +1P -2P
```
```
XXX.client.player.LocalPlayer +2M -5M | +2P -2P
```
```
XXX.client.renderer.GameRenderer +4P -1P
```
```
XXX.client.renderer.LevelRenderer +2M -2M
```
```
XXX.client.renderer.PostChain +2M -4M
```
```
XXX.client.renderer.PostChainConfig$Pass +2M
```
```
XXX.renderer.chunk.SectionRenderDispatcher$RenderSection +2M -2M | +1P -1P
```
```
XXX.renderer.entity.HorseRenderer -1M
```
```
XXX.renderer.entity.PandaRenderer -1M
```
```
XXX.renderer.entity.PigRenderer +4M -1M | +1P -1P
```
```
XXX.entity.layers.HorseMarkingLayer -1M | +1P
```
```
XXX.resources.model.ModelManager +18M -19M
```
```
XXX.resources.model.SimpleBakedModel$Builder +1M | +1P -1P
```
```
XXX.resources.model.WeightedBakedModel +1M -2M | +1P -1P
```
```
XXX.minecraft.core.Direction$Axis$1 +1M
```
```
XXX.minecraft.core.Direction$Axis$3 +1M
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.worldgen.features.TreeFeatures +1M | +7P -2P
```
```
XXX.worldgen.placement.VegetationPlacements +5P -1P
```
```
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.gametest.framework.TestFunction +1M
```
```
XXX.network.chat.ClickEvent +1M -9M | +1P -2P
```
```
XXX.network.chat.ComponentSerialization +1M -1M | -1P
```
```
XXX.network.chat.HoverEvent +1M -8M | +1P -1P
```
```
XXX.protocol.game.ClientboundMoveEntityPacket +2M -2M
```
```
XXX.protocol.game.ClientboundUpdateAdvancementsPacket +2M -1M | +1P
```
```
XXX.protocol.game.GamePacketTypes -1P
```
```
XXX.protocol.game.ServerboundSetStructureBlockPacket +2M -1M | +2P
```
```
XXX.network.syncher.EntityDataSerializers +2P -1P
```
```
XXX.server.commands.AdvancementCommands +1M
```
```
XXX.server.commands.CloneCommands +18M -20M
```
```
XXX.server.commands.OpCommand +1M -1M
```
```
XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker -1M
```
```
XXX.server.level.ServerPlayer +1M -1M
```
```
XXX.minecraft.util.Unit +1P
```
```
XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix +5M -4M
```
```
XXX.datafix.fixes.BlockEntityCustomNameToComponentFix +4M -3M | +1P
```
```
XXX.datafix.fixes.ItemCustomNameToComponentFix +5M -3M
```
```
XXX.datafix.fixes.ItemLoreFix +6M -7M
```
```
XXX.datafix.fixes.ObjectiveRenderTypeFix +1M -1M
```
```
XXX.datafix.fixes.OminousBannerRarityFix +8M -6M
```
```
XXX.datafix.fixes.References +2P -1P
```
```
XXX.datafix.schemas.V1451_6 +1M -1M
```
```
XXX.util.valueproviders.WeightedListInt +2M -2M | +1P -1P
```
```
XXX.minecraft.world.Clearable -1M
```
```
XXX.world.effect.MobEffectInstance +7M -3M
```
```
XXX.world.effect.MobEffects +10P -10P
```
```
XXX.world.entity.AreaEffectCloud +2M -2M | +1P
```
```
XXX.world.entity.EntityAttachments$Builder +1M
```
```
XXX.world.entity.EntityEvent +1P
```
```
XXX.entity.animal.Sheep +2M -3M
```
```
XXX.world.item.DebugStickItem +1M -1M
```
```
XXX.world.item.SolidBucketItem +1M -1M
```
```
XXX.item.crafting.SmithingTransformRecipe$Serializer +2M -2M
```
```
XXX.item.crafting.TransmuteRecipe +1M -1M | +1P -1P
```
```
XXX.world.level.LevelAccessor +2M -2M | +2P -2P
```
```
XXX.world.level.NaturalSpawner +1M -1M
```
```
XXX.level.biome.Biome +1M
```
```
XXX.level.biome.MobSpawnSettings$Builder +3M -4M
```
```
XXX.level.biome.MobSpawnSettings$SpawnerData +6M -2M | +1P -1P
```
```
XXX.level.block.BeetrootBlock +1M | +1P -1P
```
```
XXX.level.block.BigDripleafStemBlock +1P -5P
```
```
XXX.level.block.CactusBlock +2P -3P
```
```
XXX.level.block.CandleBlock +1M -1M | +1P -4P
```
```
XXX.level.block.CeilingHangingSignBlock +1M | +2P -3P
```
```
XXX.level.block.ConduitBlock -1P
```
```
XXX.level.block.CoralPlantBlock -1P
```
```
XXX.level.block.CrafterBlock +1M -1M
```
```
XXX.level.block.CropBlock +1M | +1P -1P
```
```
XXX.level.block.DecoratedPotBlock +1M -1M | +1P -1P
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.DoorBlock$1 -1P
```
```
XXX.level.block.EndPortalFrameBlock +2P -3P
```
```
XXX.level.block.FenceGateBlock +2M | +6P -12P
```
```
XXX.level.block.FireBlock +2M -2M | +1P -6P
```
```
XXX.level.block.HangingMossBlock +2P -3P
```
```
XXX.level.block.LeverBlock +3M -1M | +1P -11P
```
```
XXX.level.block.PiglinWallSkullBlock +1P -1P
```
```
XXX.level.block.ScaffoldingBlock +4P -4P
```
```
XXX.level.block.SculkShriekerBlock +2M -4M | +1P -1P
```
```
XXX.level.block.SeagrassBlock +1M -1M | -1P
```
```
XXX.level.block.SoundType +2P
```
```
XXX.level.block.StemBlock +1M | +1P -2P
```
```
XXX.level.block.StructureVoidBlock -1P
```
```
XXX.level.block.SupportType$2 -1P
```
```
XXX.level.block.TallSeagrassBlock +1M -1M | -1P
```
```
XXX.level.block.TrapDoorBlock$1 -1P
```
```
XXX.level.block.WallSignBlock +1P -4P
```
```
XXX.level.block.WallTorchBlock +1P -2P
```
```
XXX.block.entity.BrushableBlockEntity +4M -4M
```
```
XXX.block.entity.CreakingHeartBlockEntity +2M
```
```
XXX.block.entity.LecternBlockEntity +1M
```
```
XXX.block.entity.SculkShriekerBlockEntity +1M
```
```
XXX.block.entity.StructureBlockEntity +2M | +1P
```
```
XXX.entity.trialspawner.TrialSpawnerConfig$Builder +2M -2M | +2P -2P
```
```
XXX.entity.trialspawner.TrialSpawnerState +1M -1M
```
```
XXX.block.piston.MovingPistonBlock -1M
```
```
XXX.block.piston.PistonBaseBlock$1 -1P
```
```
XXX.level.chunk.ChunkSource +2M -1M
```
```
XXX.level.chunk.EmptyLevelChunk +1M -1M
```
```
XXX.level.chunk.LevelChunk +1M -1M
```
```
XXX.level.chunk.ProtoChunk +1M -1M
```

</details>
<details>
<summary>
com.mojang.blaze3d.audio.Library
</summary>

```diff
- IntBuffer createAttributes(MemoryStack,boolean)
+ void setHrtf(boolean)
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.FramerateLimitTracker
</summary>

```diff
- boolean isHeavilyThrottled()
- FramerateLimitTracker$FramerateThrottleReason getThrottleReason()
```

</details>
<details>
<summary>
net.minecraft.client.player.ClientInput
</summary>

```diff
- void scaleMoveDirection(float)
```

</details>
<details>
<summary>
net.minecraft.client.player.LocalPlayer
</summary>

```diff
+ boolean isEffectiveAi()
+ boolean isRidingCamel()
+ MobEffectInstance removeEffectNoUpdate(Holder)
- void applyInput()
+ void handleConfusionTransitionEffect(boolean)
- void handlePortalTransitionEffect(boolean)
+ void serverAiStep()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.LevelRenderer
</summary>

```diff
- void lambda$addCloudsPass$3(int,CloudStatus,float,Matrix4f,Matrix4f,Vec3,float)
+ void lambda$addCloudsPass$3(ResourceHandle,int,CloudStatus,float,Matrix4f,Matrix4f,Vec3,float)
- void lambda$addMainPass$1(FogParameters,DeltaTracker,Camera,ProfilerFiller,Matrix4f,Matrix4f,ResourceHandle,ResourceHandle,ResourceHandle,boolean,Frustum,ResourceHandle)
+ void lambda$addMainPass$1(FogParameters,DeltaTracker,Camera,ProfilerFiller,Matrix4f,Matrix4f,ResourceHandle,ResourceHandle,ResourceHandle,ResourceHandle,boolean,Frustum,ResourceHandle)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.PostChain
</summary>

```diff
- boolean lambda$load$0(PostChainConfig,ResourceLocation)
+ boolean lambda$load$2(PostChainConfig,ResourceLocation)
+ Stream lambda$load$0(PostChainConfig$Pass)
+ Stream lambda$load$1(PostChainConfig$Input)
- String lambda$createPass$1(String)
+ String lambda$createPass$3(String)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.PostChainConfig$Pass
</summary>

```diff
- Stream lambda$referencedTargets$3(PostChainConfig$Input)
- Stream referencedTargets()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection
</summary>

```diff
+ BlockPos getOrigin()
- BlockPos getRenderOrigin()
+ VertexSorting createVertexSorting()
- VertexSorting createVertexSorting(SectionPos)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.HorseRenderer
</summary>

```diff
+ void lambda$static$0(EnumMap)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.PandaRenderer
</summary>

```diff
+ void lambda$static$0(EnumMap)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.PigRenderer
</summary>

```diff
- Map bakeModels(EntityRendererProvider$Context)
+ void <clinit>()
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
- void render(LivingEntityRenderState,PoseStack,MultiBufferSource,int)
- void render(PigRenderState,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
</summary>

```diff
+ void lambda$static$0(EnumMap)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.ModelManager
</summary>

```diff
+ AtlasSet$StitchResult lambda$reload$3(Map$Entry)
- CompletableFuture[] lambda$loadModels$17(int)
+ CompletableFuture[] lambda$loadModels$18(int)
- CompletionStage lambda$loadBlockModels$11(Executor,Map)
+ CompletionStage lambda$loadBlockModels$12(Executor,Map)
- CompletionStage lambda$reload$6(ModelManager$ReloadState)
+ CompletionStage lambda$reload$7(ModelManager$ReloadState)
- EntityModelSet lambda$entityModels$20()
+ EntityModelSet lambda$entityModels$21()
- Map lambda$loadBlockModels$10(List)
+ Map lambda$loadBlockModels$11(List)
- Map lambda$loadBlockModels$8(ResourceManager)
+ Map lambda$loadBlockModels$9(ResourceManager)
- ModelManager$ReloadState lambda$reload$4(Map,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,UnbakedModel,CompletableFuture,Void)
+ ModelManager$ReloadState lambda$reload$5(Map,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,UnbakedModel,CompletableFuture,Void)
- ModelManager$ReloadState lambda$reload$5(ModelManager$ReloadState,Void)
+ ModelManager$ReloadState lambda$reload$6(ModelManager$ReloadState,Void)
+ Pair lambda$loadBlockModels$10(Map$Entry)
- Pair lambda$loadBlockModels$9(Map$Entry)
- SpecialBlockModelRenderer lambda$specialBlockModelRenderer$19()
+ SpecialBlockModelRenderer lambda$specialBlockModelRenderer$20()
- String lambda$loadModels$13(Material)
+ String lambda$loadModels$14(Material)
- String lambda$loadModels$15(String)
+ String lambda$loadModels$16(String)
- String lambda$reload$3(ResourceLocation)
+ String lambda$reload$4(ResourceLocation)
- void lambda$createBlockStateToModelDispatch$18(Map,Map,BakedModel,BlockState)
+ void lambda$createBlockStateToModelDispatch$19(Map,Map,BakedModel,BlockState)
- void lambda$discoverModelDependencies$12(ModelDiscovery,ClientItem)
+ void lambda$discoverModelDependencies$13(ModelDiscovery,ClientItem)
- void lambda$loadModels$14(String,Collection)
+ void lambda$loadModels$15(String,Collection)
- void lambda$loadModels$16(String,Collection)
+ void lambda$loadModels$17(String,Collection)
- void lambda$reload$7(ModelManager$ReloadState)
+ void lambda$reload$8(ModelManager$ReloadState)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.SimpleBakedModel$Builder
</summary>

```diff
- ImmutableList$Builder lambda$new$0(Direction)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.WeightedBakedModel
</summary>

```diff
+ List lambda$getQuads$0(BlockState,Direction,RandomSource,BakedModel)
+ void <init>(SimpleWeightedRandomList)
- void <init>(WeightedList)
```

</details>
<details>
<summary>
net.minecraft.core.Direction$Axis$1
</summary>

```diff
- boolean choose(boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.core.Direction$Axis$3
</summary>

```diff
- boolean choose(boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.TreeFeatures
</summary>

```diff
- TreeConfiguration$TreeConfigurationBuilder createDarkOak()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void tickBlock(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.TestFunction
</summary>

```diff
- void <init>(String,String,String,Rotation,int,long,boolean,boolean,Consumer)
```

</details>
<details>
<summary>
net.minecraft.network.chat.ClickEvent
</summary>

```diff
+ App lambda$static$2(RecordCodecBuilder$Instance)
+ boolean equals(Object)
+ ClickEvent$Action getAction()
+ ClickEvent$Action lambda$static$0(ClickEvent)
+ int hashCode()
- MapCodec lambda$static$0(ClickEvent$Action)
+ String getValue()
+ String lambda$static$1(ClickEvent)
+ String toString()
+ void <init>(ClickEvent$Action,String)
```

</details>
<details>
<summary>
net.minecraft.network.chat.ComponentSerialization
</summary>

```diff
+ Codec flatCodec(int)
- Codec flatRestrictedCodec(int)
```

</details>
<details>
<summary>
net.minecraft.network.chat.HoverEvent
</summary>

```diff
+ boolean equals(Object)
+ HoverEvent$Action getAction()
+ HoverEvent$TypedHoverEvent lambda$static$0(HoverEvent)
+ int hashCode()
- MapCodec lambda$static$0(HoverEvent$Action)
+ Object getValue(HoverEvent$Action)
+ String toString()
+ void <init>(HoverEvent$Action,Object)
+ void <init>(HoverEvent$TypedHoverEvent)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
</summary>

```diff
+ float getxRot()
- float getXRot()
+ float getyRot()
- float getYRot()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
</summary>

```diff
- boolean shouldShowAdvancements()
- void <init>(boolean,Collection,Set,Map,boolean)
+ void <init>(boolean,Collection,Set,Map)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
</summary>

```diff
- boolean isStrict()
- void <init>(BlockPos,StructureBlockEntity$UpdateType,StructureMode,String,BlockPos,Vec3i,Mirror,Rotation,String,boolean,boolean,boolean,boolean,float,long)
+ void <init>(BlockPos,StructureBlockEntity$UpdateType,StructureMode,String,BlockPos,Vec3i,Mirror,Rotation,String,boolean,boolean,boolean,float,long)
```

</details>
<details>
<summary>
net.minecraft.server.commands.AdvancementCommands
</summary>

```diff
- int perform(CommandSourceStack,Collection,AdvancementCommands$Action,Collection,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.commands.CloneCommands
</summary>

```diff
+ ArgumentBuilder destinationAndModeSuffix(CommandBuildContext,CloneCommands$CommandFunction,CloneCommands$CommandFunction)
- ArgumentBuilder destinationAndStrictSuffix(CommandBuildContext,CloneCommands$CommandFunction,CloneCommands$CommandFunction)
- ArgumentBuilder modeSuffix(CommandBuildContext,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,ArgumentBuilder)
+ ArgumentBuilder wrapWithCloneMode(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,ArgumentBuilder)
- ArgumentBuilder wrapWithCloneMode(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,ArgumentBuilder)
+ boolean lambda$destinationAndModeSuffix$10(BlockInWorld)
+ boolean lambda$destinationAndModeSuffix$12(BlockInWorld)
+ boolean lambda$destinationAndModeSuffix$14(BlockInWorld)
- boolean lambda$modeSuffix$10(BlockInWorld)
- boolean lambda$modeSuffix$12(BlockInWorld)
+ CloneCommands$DimensionAndPosition lambda$destinationAndModeSuffix$7(CloneCommands$CommandFunction,CommandContext)
+ CloneCommands$DimensionAndPosition lambda$destinationAndModeSuffix$8(CloneCommands$CommandFunction,CommandContext)
+ CloneCommands$DimensionAndPosition lambda$destinationAndModeSuffix$9(CloneCommands$CommandFunction,CommandContext)
- CloneCommands$DimensionAndPosition lambda$destinationAndStrictSuffix$7(CloneCommands$CommandFunction,CommandContext)
- CloneCommands$DimensionAndPosition lambda$destinationAndStrictSuffix$8(CloneCommands$CommandFunction,CommandContext)
- CloneCommands$DimensionAndPosition lambda$destinationAndStrictSuffix$9(CloneCommands$CommandFunction,CommandContext)
- Component lambda$clone$20(int)
+ Component lambda$clone$23(int)
- int clone(CommandSourceStack,CloneCommands$DimensionAndPosition,CloneCommands$DimensionAndPosition,CloneCommands$DimensionAndPosition,Predicate,CloneCommands$Mode,boolean)
+ int clone(CommandSourceStack,CloneCommands$DimensionAndPosition,CloneCommands$DimensionAndPosition,CloneCommands$DimensionAndPosition,Predicate,CloneCommands$Mode)
+ int lambda$destinationAndModeSuffix$11(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$destinationAndModeSuffix$15(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$destinationAndModeSuffix$17(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$destinationAndModeSuffix$19(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
- int lambda$modeSuffix$11(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
- int lambda$wrapWithCloneMode$16(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
- int lambda$wrapWithCloneMode$17(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
- int lambda$wrapWithCloneMode$18(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
- int lambda$wrapWithCloneMode$19(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,boolean,CommandContext)
+ int lambda$wrapWithCloneMode$20(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$wrapWithCloneMode$21(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ int lambda$wrapWithCloneMode$22(CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CloneCommands$CommandFunction,CommandContext)
+ Predicate lambda$destinationAndModeSuffix$13(CommandContext)
+ Predicate lambda$destinationAndModeSuffix$16(CommandContext)
+ Predicate lambda$destinationAndModeSuffix$18(CommandContext)
- Predicate lambda$modeSuffix$13(CommandContext)
- Predicate lambda$modeSuffix$14(CommandContext)
- Predicate lambda$modeSuffix$15(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.OpCommand
</summary>

```diff
+ Component lambda$opPlayers$5(Collection)
- Component lambda$opPlayers$5(GameProfile)
```

</details>
<details>
<summary>
net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
</summary>

```diff
+ void dumpChunks(String)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- void removeVehicle()
+ void stopRiding()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
</summary>

```diff
+ boolean lambda$fix$1(String)
- boolean lambda$fix$2(String)
+ Dynamic lambda$fix$2(OptionalDynamic,Dynamic)
- Dynamic lambda$fix$3(Optional,Dynamic)
- Optional lambda$fix$1(OpticFinder,Typed)
- Typed fix(Typed,OpticFinder,OpticFinder)
+ Typed fix(Typed,OpticFinder)
- Typed lambda$makeRule$0(TaggedChoice$TaggedChoiceType,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$0(TaggedChoice$TaggedChoiceType,OpticFinder,Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
</summary>

```diff
- Dynamic fixTagCustomName(Dynamic)
+ Dynamic lambda$makeRule$0(Typed,OpticFinder,Dynamic)
- Typed lambda$makeRule$0(OpticFinder,Type,Type,Typed)
+ Typed lambda$makeRule$1(OpticFinder,Typed)
- void <clinit>()
+ void <init>(Schema,boolean)
- void <init>(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Pair lambda$makeRule$0(Pair)
+ Typed lambda$makeRule$0(Typed)
- Typed lambda$makeRule$2(OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$3(OpticFinder,OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$4(OpticFinder,OpticFinder,OpticFinder,OpticFinder,Typed)
+ void <init>(Schema,boolean)
- void <init>(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemLoreFix
</summary>

```diff
+ Dynamic lambda$makeRule$0(Dynamic)
+ Dynamic lambda$makeRule$1(Dynamic)
+ Dynamic lambda$makeRule$2(Dynamic)
- Pair lambda$makeRule$0(Pair)
+ Stream fixLoreList(Stream)
- Typed lambda$makeRule$1(OpticFinder,Typed)
- Typed lambda$makeRule$2(OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$3(OpticFinder,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$3(Typed)
- Typed lambda$makeRule$4(OpticFinder,OpticFinder,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$4(OpticFinder,Typed)
+ void <init>(Schema,boolean)
- void <init>(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
</summary>

```diff
+ void <init>(Schema,boolean)
- void <init>(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OminousBannerRarityFix
</summary>

```diff
+ boolean lambda$fix$2(String)
- boolean lambda$fix$3(String)
+ Dynamic lambda$fix$3(Dynamic)
- Dynamic lambda$fix$5(Dynamic)
- Optional lambda$fix$2(OpticFinder,Typed)
- Typed fix(Typed,OpticFinder,OpticFinder,OpticFinder)
+ Typed fix(Typed,OpticFinder)
- Typed lambda$fix$4(OpticFinder,Typed)
+ Typed lambda$fix$4(Typed)
- Typed lambda$fix$6(OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$0(TaggedChoice$TaggedChoiceType,OpticFinder,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$0(TaggedChoice$TaggedChoiceType,OpticFinder,Typed)
- Typed lambda$makeRule$1(OpticFinder,OpticFinder,OpticFinder,OpticFinder,Typed)
+ Typed lambda$makeRule$1(OpticFinder,OpticFinder,Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1451_6
</summary>

```diff
- TypeTemplate lambda$registerTypes$2(Map,Schema)
+ TypeTemplate lambda$registerTypes$2(Map)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.WeightedListInt
</summary>

```diff
+ SimpleWeightedRandomList lambda$static$0(WeightedListInt)
+ void <init>(SimpleWeightedRandomList)
- void <init>(WeightedList)
- WeightedList lambda$static$0(WeightedListInt)
```

</details>
<details>
<summary>
net.minecraft.world.Clearable
</summary>

```diff
+ void tryClear(Object)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
- boolean downgradeToHiddenEffect()
+ boolean tick(LivingEntity,Runnable)
- boolean tickServer(ServerLevel,LivingEntity,Runnable)
+ int lambda$tickDownDuration$2(int)
- int lambda$tickDownDuration$3(int)
- int lambda$withScaledDuration$2(float,int)
+ int tickDownDuration()
- MobEffectInstance withScaledDuration(float)
- void tickClient()
- void tickDownDuration()
```

</details>
<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
+ int lambda$serverTick$1(int)
- void lambda$readAdditionalSaveData$1(String)
+ void lambda$readAdditionalSaveData$3(String)
- void setPotionDurationScale(float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityAttachments$Builder
</summary>

```diff
- List lambda$build$1(float,float,EntityAttachment)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Sheep
</summary>

```diff
- boolean lambda$registerGoals$0(ItemStack)
+ boolean lambda$registerGoals$1(ItemStack)
+ DyeColor lambda$static$0(DyeColor)
- void lambda$shear$1(ServerLevel,ItemStack)
+ void lambda$shear$2(ServerLevel,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.DebugStickItem
</summary>

```diff
+ boolean canAttackBlock(BlockState,Level,BlockPos,Player)
- boolean canDestroyBlock(ItemStack,BlockState,Level,BlockPos,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.SolidBucketItem
</summary>

```diff
- boolean emptyContents(LivingEntity,Level,BlockPos,BlockHitResult)
+ boolean emptyContents(Player,Level,BlockPos,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
</summary>

```diff
+ ItemStack lambda$static$3(SmithingTransformRecipe)
+ ItemStack lambda$static$8(SmithingTransformRecipe)
- TransmuteResult lambda$static$3(SmithingTransformRecipe)
- TransmuteResult lambda$static$8(SmithingTransformRecipe)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.TransmuteRecipe
</summary>

```diff
+ void <init>(String,CraftingBookCategory,Ingredient,Ingredient,Holder)
- void <init>(String,CraftingBookCategory,Ingredient,Ingredient,TransmuteResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
+ void blockUpdated(BlockPos,Block)
- void playSound(Entity,BlockPos,SoundEvent,SoundSource)
+ void playSound(Player,BlockPos,SoundEvent,SoundSource)
- void updateNeighborsAt(BlockPos,Block)
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
- WeightedList mobsAt(ServerLevel,StructureManager,ChunkGenerator,MobCategory,BlockPos,Holder)
+ WeightedRandomList mobsAt(ServerLevel,StructureManager,ChunkGenerator,MobCategory,BlockPos,Holder)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
- int getBaseGrassColor()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$Builder
</summary>

```diff
+ List lambda$new$1(MobCategory)
+ MobCategory lambda$new$0(MobCategory)
- MobSpawnSettings$Builder addSpawn(MobCategory,int,MobSpawnSettings$SpawnerData)
+ MobSpawnSettings$Builder addSpawn(MobCategory,MobSpawnSettings$SpawnerData)
- WeightedList lambda$build$1(Map$Entry)
- WeightedList$Builder lambda$new$0(MobCategory)
+ WeightedRandomList lambda$build$2(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
</summary>

```diff
- boolean equals(Object)
- EntityType type()
- int hashCode()
- int maxCount()
- int minCount()
+ void <init>(EntityType,int,int,int)
- void <init>(EntityType,int,int)
+ void <init>(EntityType,Weight,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeetrootBlock
</summary>

```diff
- VoxelShape lambda$static$0(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleBlock
</summary>

```diff
+ Int2ObjectMap lambda$static$1()
- void lambda$static$1(Int2ObjectOpenHashMap)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CeilingHangingSignBlock
</summary>

```diff
- Integer lambda$static$1(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
- void affectNeighborsAfterRemoval(BlockState,ServerLevel,BlockPos,boolean)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CropBlock
</summary>

```diff
- VoxelShape lambda$static$0(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DecoratedPotBlock
</summary>

```diff
- void affectNeighborsAfterRemoval(BlockState,ServerLevel,BlockPos,boolean)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
- void affectNeighborsAfterRemoval(BlockState,ServerLevel,BlockPos,boolean)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceGateBlock
</summary>

```diff
- VoxelShape lambda$static$2(VoxelShape)
- VoxelShape lambda$static$3(VoxelShape)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FireBlock
</summary>

```diff
+ boolean lambda$new$1(BlockState)
- Function makeShapes()
+ VoxelShape calculateShape(BlockState)
- VoxelShape lambda$makeShapes$1(Map,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
- Function makeShapes()
- void affectNeighborsAfterRemoval(BlockState,ServerLevel,BlockPos,boolean)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
- VoxelShape lambda$makeShapes$0(Map,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
- void lambda$getTicker$2(Level,BlockPos,BlockState,SculkShriekerBlockEntity)
+ void lambda$getTicker$3(Level,BlockPos,BlockState,SculkShriekerBlockEntity)
+ void lambda$onRemove$1(ServerLevel,SculkShriekerBlockEntity)
- void lambda$tick$1(ServerLevel,SculkShriekerBlockEntity)
+ void lambda$tick$2(ServerLevel,SculkShriekerBlockEntity)
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SeagrassBlock
</summary>

```diff
- boolean canPlaceLiquid(LivingEntity,BlockGetter,BlockPos,BlockState,Fluid)
+ boolean canPlaceLiquid(Player,BlockGetter,BlockPos,BlockState,Fluid)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StemBlock
</summary>

```diff
- VoxelShape lambda$static$4(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TallSeagrassBlock
</summary>

```diff
- boolean canPlaceLiquid(LivingEntity,BlockGetter,BlockPos,BlockState,Fluid)
+ boolean canPlaceLiquid(Player,BlockGetter,BlockPos,BlockState,Fluid)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BrushableBlockEntity
</summary>

```diff
- boolean brush(long,ServerLevel,LivingEntity,Direction,ItemStack)
+ boolean brush(long,ServerLevel,Player,Direction,ItemStack)
- void brushingCompleted(ServerLevel,LivingEntity,ItemStack)
+ void brushingCompleted(ServerLevel,Player,ItemStack)
- void dropContent(ServerLevel,LivingEntity,ItemStack)
+ void dropContent(ServerLevel,Player,ItemStack)
- void unpackLootTable(ServerLevel,LivingEntity,ItemStack)
+ void unpackLootTable(ServerLevel,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.CreakingHeartBlockEntity
</summary>

```diff
- BlockState updateCreakingState(Level,BlockState,BlockPos,CreakingHeartBlockEntity)
- void preRemoveSideEffects(BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.LecternBlockEntity
</summary>

```diff
- void preRemoveSideEffects(BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
</summary>

```diff
- void preRemoveSideEffects(BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.StructureBlockEntity
</summary>

```diff
- boolean isStrict()
- void setStrict(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerConfig$Builder
</summary>

```diff
+ TrialSpawnerConfig$Builder lootTablesToEject(SimpleWeightedRandomList)
- TrialSpawnerConfig$Builder lootTablesToEject(WeightedList)
+ TrialSpawnerConfig$Builder spawnPotentialsDefinition(SimpleWeightedRandomList)
- TrialSpawnerConfig$Builder spawnPotentialsDefinition(WeightedList)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState
</summary>

```diff
- void lambda$tickAndGetNext$0(TrialSpawnerData,TrialSpawner,SpawnData)
+ void lambda$tickAndGetNext$0(TrialSpawnerData,TrialSpawner,WeightedEntry$Wrapper)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ void onRemove(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkSource
</summary>

```diff
- boolean updateChunkForced(ChunkPos,boolean)
- LongSet getForceLoadedChunks()
+ void updateChunkForced(ChunkPos,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.EmptyLevelChunk
</summary>

```diff
+ BlockState setBlockState(BlockPos,BlockState,boolean)
- BlockState setBlockState(BlockPos,BlockState,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
+ BlockState setBlockState(BlockPos,BlockState,boolean)
- BlockState setBlockState(BlockPos,BlockState,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
+ BlockState setBlockState(BlockPos,BlockState,boolean)
- BlockState setBlockState(BlockPos,BlockState,int)
```

</details>
</details>
<hr/>