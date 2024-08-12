## Comparison with [24w11a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w11a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Items](#items)
- [Commands](#commands)
- [Translations](#translations)
- [File structure](#file-structure)
- [Misc](#misc)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>DataPack version</td><td><code>35</code></td><td><code>36</code></td></tr><tr><td>ResourcePack version</td><td><code>29</code></td><td><code>30</code></td></tr><tr><td>World version</td><td><code>3823</code></td><td><code>3824</code></td></tr><tr><td>Protocol version</td><td><code>1073742004</code></td><td><code>1073742005</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ map_decoration_type.txt
```

</details>









<details>
<summary>
command_argument_type.txt
</summary>

```diff
+ minecraft:loot_modifier
+ minecraft:loot_predicate
+ minecraft:loot_table
```

</details>


<details>
<summary>
data_component_type.txt
</summary>

```diff
+ minecraft:fire_resistant
+ minecraft:food
+ minecraft:hide_tooltip
+ minecraft:max_damage
+ minecraft:max_stack_size
+ minecraft:rarity
+ minecraft:tool
```

</details>


<details>
<summary>
entity_sub_predicate_type.txt
</summary>

```diff
+ minecraft:wolf
```

</details>











<details>
<summary>
loot_function_type.txt
</summary>

```diff
+ minecraft:toggle_tooltips
```

</details>

<details>
<summary>
loot_number_provider_type.txt
</summary>

```diff
+ minecraft:storage
```

</details>


















<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:item.mace.smash_ground_heavy
```

</details>

<details>
<summary>
trigger_type.txt
</summary>

```diff
+ minecraft:crafter_recipe_crafted
+ minecraft:fall_after_explosion
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/map_decoration_type.json
```

</details>















<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:loot_modifier
+ minecraft:loot_predicate
+ minecraft:loot_table
```

</details>


<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:fire_resistant
+ minecraft:food
+ minecraft:hide_tooltip
+ minecraft:max_damage
+ minecraft:max_stack_size
+ minecraft:rarity
+ minecraft:tool
```

</details>


<details>
<summary>
universal_tags/entity_sub_predicate_type.json
</summary>

```diff
+ minecraft:wolf
```

</details>











<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
+ minecraft:toggle_tooltips
```

</details>

<details>
<summary>
universal_tags/loot_number_provider_type.json
</summary>

```diff
+ minecraft:storage
```

</details>


















<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:item.mace.smash_ground_heavy
```

</details>

<details>
<summary>
universal_tags/trigger_type.json
</summary>

```diff
+ minecraft:crafter_recipe_crafted
+ minecraft:fall_after_explosion
```

</details>
</details>
<details><summary>Items</summary>
<table><tr><th colspan="3">acacia_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_chest_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_sapling.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">acacia_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">activator_rail.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">air.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">allay_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">allium.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">amethyst_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">amethyst_cluster.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">amethyst_shard.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ancient_debris.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">andesite.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">andesite_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">andesite_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">andesite_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">angler_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">anvil.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">apple.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">archer_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">armadillo_scute.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">armadillo_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">armor_stand.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">arms_up_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">arrow.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">axolotl_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">axolotl_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">azalea.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">azalea_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">azure_bluet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">baked_potato.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_chest_raft.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_mosaic.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_mosaic_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_mosaic_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_raft.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bamboo_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">barrel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">barrier.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">basalt.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bat_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">beacon.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">bedrock.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">beef.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">beehive.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">beetroot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">beetroot_seeds.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">beetroot_soup.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bee_nest.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bee_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bell.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">big_dripleaf.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_chest_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_sapling.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">birch_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blackstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blackstone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blackstone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blackstone_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">black_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blade_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blast_furnace.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blaze_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blaze_rod.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blaze_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_ice.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_orchid.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">blue_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bogged_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bolt_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bone_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bone_meal.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">book.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bookshelf.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bow.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bowl.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brain_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brain_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brain_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bread.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">breeze_rod.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">breeze_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brewer_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brewing_stand.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brick.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_mushroom.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_mushroom_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brown_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">brush.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bubble_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bubble_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bubble_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">budding_amethyst.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">bundle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">burn_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cactus.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cake.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">calcite.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">calibrated_sculk_sensor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">camel_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">campfire.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">carrot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">carrot_on_a_stick.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cartography_table.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">carved_pumpkin.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cat_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cauldron.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cave_spider_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chain.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chainmail_boots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chainmail_chestplate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chainmail_helmet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chainmail_leggings.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chain_command_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">charcoal.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_chest_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_sapling.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cherry_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chest.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chest_minecart.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chicken.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chicken_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chipped_anvil.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_bookshelf.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_deepslate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_nether_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_polished_blackstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_quartz_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_red_sandstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_sandstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_tuff.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chiseled_tuff_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chorus_flower.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chorus_fruit.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">chorus_plant.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">clay.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">clay_ball.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">clock.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">coal.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">coal_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">coal_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">coarse_dirt.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">coast_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobbled_deepslate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobbled_deepslate_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobbled_deepslate_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobbled_deepslate_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobblestone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobblestone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobblestone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobblestone_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cobweb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cocoa_beans.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cod.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cod_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cod_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">command_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">command_block_minecart.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">comparator.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">compass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">composter.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">conduit.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">cooked_beef.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cooked_chicken.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cooked_cod.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cooked_mutton.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cooked_porkchop.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cooked_rabbit.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cooked_salmon.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cookie.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">copper_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">copper_bulb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">copper_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">copper_grate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">copper_ingot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">copper_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">copper_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cornflower.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cow_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cracked_deepslate_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cracked_deepslate_tiles.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cracked_nether_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cracked_polished_blackstone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cracked_stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crafter.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crafting_table.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">creeper_banner_pattern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">creeper_head.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">creeper_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_fungus.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_hyphae.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_nylium.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_roots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_stem.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crimson_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crossbow.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">crying_obsidian.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cut_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cut_copper_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cut_copper_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cut_red_sandstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cut_red_sandstone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cut_sandstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cut_sandstone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">cyan_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">damaged_anvil.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dandelion.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">danger_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_chest_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_sapling.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_oak_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_prismarine.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_prismarine_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dark_prismarine_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">daylight_detector.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_brain_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_brain_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_brain_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_bubble_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_bubble_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_bubble_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_bush.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_fire_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_fire_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_fire_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_horn_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_horn_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_horn_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_tube_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_tube_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dead_tube_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">debug_stick.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">decorated_pot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_coal_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_copper_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_diamond_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_emerald_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_gold_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_iron_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_lapis_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_redstone_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_tiles.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_tile_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_tile_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">deepslate_tile_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">detector_rail.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_axe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_boots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_chestplate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_helmet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_hoe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_horse_armor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_leggings.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_pickaxe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_shovel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diamond_sword.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diorite.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diorite_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diorite_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">diorite_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dirt.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dirt_path.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">disc_fragment_5.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dispenser.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dolphin_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">donkey_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dragon_breath.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">dragon_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">dragon_head.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">dried_kelp.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dried_kelp_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dripstone_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dropper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">drowned_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">dune_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">echo_shard.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">elder_guardian_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">elytra.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">emerald.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">emerald_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">emerald_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">enchanted_book.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">enchanted_golden_apple.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">enchanting_table.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">enderman_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">endermite_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ender_chest.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ender_dragon_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ender_eye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ender_pearl.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">end_crystal.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">end_portal_frame.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">end_rod.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">end_stone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">end_stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">end_stone_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">end_stone_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">end_stone_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">evoker_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">experience_bottle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">explorer_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_chiseled_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_copper_bulb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_copper_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_copper_grate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_copper_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_cut_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_cut_copper_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">exposed_cut_copper_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">eye_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">farmland.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">feather.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fermented_spider_eye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">filled_map.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">firework_rocket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">firework_star.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fire_charge.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fire_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fire_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fire_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fishing_rod.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fletching_table.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flint.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flint_and_steel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flowering_azalea.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flowering_azalea_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flower_banner_pattern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flower_pot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flow_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flow_banner_pattern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">flow_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">fox_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">friend_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">frogspawn.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">frog_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">furnace.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">furnace_minecart.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ghast_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ghast_tear.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gilded_blackstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glass_bottle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glistering_melon_slice.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">globe_banner_pattern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glowstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glowstone_dust.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glow_berries.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glow_ink_sac.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glow_item_frame.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glow_lichen.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">glow_squid_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">goat_horn.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">goat_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_apple.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">golden_axe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_boots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_carrot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_chestplate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_helmet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_hoe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_horse_armor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_leggings.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_pickaxe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_shovel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">golden_sword.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gold_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gold_ingot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gold_nugget.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gold_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">granite.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">granite_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">granite_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">granite_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">grass_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gravel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gray_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">green_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">grindstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">guardian_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">gunpowder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">guster_banner_pattern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">guster_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">hanging_roots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">hay_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">heartbreak_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">heart_of_the_sea.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">heart_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">heavy_core.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">heavy_weighted_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">hoglin_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">honeycomb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">honeycomb_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">honey_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">honey_bottle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">hopper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">hopper_minecart.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">horn_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">horn_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">horn_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">horse_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">host_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">howl_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">husk_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ice.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">infested_chiseled_stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">infested_cobblestone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">infested_cracked_stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">infested_deepslate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">infested_mossy_stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">infested_stone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">infested_stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ink_sac.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_axe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_bars.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_boots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_chestplate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_golem_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_helmet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_hoe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_horse_armor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_ingot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_leggings.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_nugget.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_pickaxe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_shovel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_sword.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">iron_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">item_frame.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jack_o_lantern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jigsaw.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">jukebox.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_chest_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_sapling.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">jungle_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">kelp.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">knowledge_book.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">ladder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lantern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lapis_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lapis_lazuli.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lapis_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">large_amethyst_bud.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">large_fern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lava_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lead.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">leather.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">leather_boots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">leather_chestplate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">leather_helmet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">leather_horse_armor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">leather_leggings.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lectern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lever.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">lightning_rod.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_blue_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_gray_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">light_weighted_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lilac.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lily_of_the_valley.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lily_pad.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lime_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lingering_potion.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">llama_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">lodestone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">loom.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mace.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magenta_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magma_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magma_cream.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">magma_cube_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_chest_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_propagule.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_roots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mangrove_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">map.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">medium_amethyst_bud.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">melon.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">melon_seeds.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">melon_slice.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">milk_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">minecart.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">miner_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mojang_banner_pattern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">mooshroom_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mossy_cobblestone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mossy_cobblestone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mossy_cobblestone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mossy_cobblestone_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mossy_stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mossy_stone_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mossy_stone_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mossy_stone_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">moss_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">moss_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mourner_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mud.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">muddy_mangrove_roots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mud_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mud_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mud_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mud_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mule_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mushroom_stem.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mushroom_stew.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">music_disc_11.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_13.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_5.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_blocks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_cat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_chirp.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_far.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_mall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_mellohi.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_otherside.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_pigstep.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_relic.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_stal.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_strad.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_wait.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">music_disc_ward.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">mutton.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">mycelium.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">name_tag.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nautilus_shell.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_axe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_boots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_chestplate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_helmet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_hoe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_ingot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_leggings.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_pickaxe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_scrap.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_shovel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_sword.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherite_upgrade_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">netherrack.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_brick.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_brick_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_gold_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_quartz_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_sprouts.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_star.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">nether_wart.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">nether_wart_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">note_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_chest_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_sapling.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oak_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">observer.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">obsidian.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ocelot_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ochre_froglight.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_tulip.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">orange_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxeye_daisy.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_chiseled_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_copper_bulb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_copper_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_copper_grate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_copper_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_cut_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_cut_copper_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">oxidized_cut_copper_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">packed_ice.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">packed_mud.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">painting.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">panda_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">paper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">parrot_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pearlescent_froglight.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">peony.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">petrified_oak_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">phantom_membrane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">phantom_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">piglin_banner_pattern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">piglin_brute_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">piglin_head.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">piglin_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pig_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pillager_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_petals.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_tulip.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pink_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">piston.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pitcher_plant.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pitcher_pod.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">player_head.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">plenty_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">podzol.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pointed_dripstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">poisonous_potato.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polar_bear_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_andesite.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_andesite_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_andesite_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_basalt.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_blackstone_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_deepslate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_deepslate_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_deepslate_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_deepslate_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_diorite.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_diorite_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_diorite_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_granite.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_granite_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_granite_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_tuff.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_tuff_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_tuff_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">polished_tuff_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">popped_chorus_fruit.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">poppy.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">porkchop.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">potato.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">potion.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">powder_snow_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">powered_rail.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine_crystals.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine_shard.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prismarine_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">prize_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pufferfish.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pufferfish_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pufferfish_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pumpkin.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pumpkin_pie.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">pumpkin_seeds.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purple_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purpur_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purpur_pillar.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purpur_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">purpur_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">quartz.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">quartz_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">quartz_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">quartz_pillar.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">quartz_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">quartz_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rabbit.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rabbit_foot.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rabbit_hide.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rabbit_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rabbit_stew.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rail.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">raiser_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ravager_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">raw_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">raw_copper_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">raw_gold.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">raw_gold_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">raw_iron.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">raw_iron_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">recovery_compass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">redstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">redstone_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">redstone_lamp.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">redstone_ore.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">redstone_torch.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_mushroom.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_mushroom_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_nether_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_nether_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_nether_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_nether_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_sand.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_sandstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_sandstone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_sandstone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_sandstone_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_tulip.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">red_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">reinforced_deepslate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">repeater.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">repeating_command_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">respawn_anchor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rib_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rooted_dirt.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rose_bush.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">rotten_flesh.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">saddle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">salmon.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">salmon_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">salmon_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sand.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sandstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sandstone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sandstone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sandstone_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">scaffolding.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">scrape_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sculk.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sculk_catalyst.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sculk_sensor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sculk_shrieker.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sculk_vein.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">seagrass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sea_lantern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sea_pickle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sentry_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">shaper_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sheaf_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">shears.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sheep_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">shelter_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">shield.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">short_grass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">shroomlight.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">shulker_shell.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">shulker_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">silence_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">silverfish_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">skeleton_horse_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">skeleton_skull.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">skeleton_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">skull_banner_pattern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">skull_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">slime_ball.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">slime_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">slime_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">small_amethyst_bud.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">small_dripleaf.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smithing_table.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smoker.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_basalt.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_quartz.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_quartz_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_quartz_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_red_sandstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_red_sandstone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_red_sandstone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_sandstone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_sandstone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_sandstone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_stone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">smooth_stone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sniffer_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sniffer_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">snort_pottery_sherd.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">snout_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">snow.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">snowball.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">snow_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">snow_golem_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">soul_campfire.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">soul_lantern.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">soul_sand.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">soul_soil.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">soul_torch.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spawner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spectral_arrow.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spider_eye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spider_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spire_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">splash_potion.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sponge.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spore_blossom.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_chest_boat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_leaves.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_sapling.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spruce_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">spyglass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">squid_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stick.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sticky_piston.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stonecutter.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_axe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_hoe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_pickaxe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_shovel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stone_sword.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stray_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">strider_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">string.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_acacia_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_acacia_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_bamboo_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_birch_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_birch_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_cherry_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_cherry_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_crimson_hyphae.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_crimson_stem.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_dark_oak_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_dark_oak_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_jungle_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_jungle_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_mangrove_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_mangrove_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_oak_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_oak_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_spruce_log.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_spruce_wood.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_warped_hyphae.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">stripped_warped_stem.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">structure_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">structure_void.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">sugar.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sugar_cane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sunflower.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">suspicious_gravel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">suspicious_sand.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">suspicious_stew.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">sweet_berries.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tadpole_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tadpole_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tall_grass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">target.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tide_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tinted_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tipped_arrow.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tnt.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tnt_minecart.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">torch.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">torchflower.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">torchflower_seeds.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">totem_of_undying.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">trader_llama_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">trapped_chest.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">trial_key.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">trial_spawner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">trident.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tripwire_hook.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tropical_fish.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tropical_fish_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tropical_fish_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tube_coral.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tube_coral_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tube_coral_fan.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tuff.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tuff_bricks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tuff_brick_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tuff_brick_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tuff_brick_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tuff_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tuff_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">tuff_wall.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">turtle_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">turtle_helmet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">turtle_scute.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">turtle_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">twisting_vines.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">vault.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">verdant_froglight.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">vex_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">vex_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">villager_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">vindicator_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">vine.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wandering_trader_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warden_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">ward_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_button.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_fence.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_fence_gate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_fungus.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_fungus_on_a_stick.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_hanging_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_hyphae.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_nylium.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_planks.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_pressure_plate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_roots.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_sign.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_stem.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">warped_wart_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">water_bucket.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_chiseled_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_copper_block.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_copper_bulb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_copper_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_copper_grate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_copper_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_cut_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_cut_copper_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_cut_copper_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_chiseled_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_copper_bulb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_copper_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_copper_grate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_copper_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_cut_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_cut_copper_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_exposed_cut_copper_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_chiseled_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_copper_bulb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_copper_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_copper_grate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_copper_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_cut_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_cut_copper_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_oxidized_cut_copper_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_chiseled_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_copper_bulb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_copper_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_copper_grate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_copper_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_cut_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_cut_copper_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">waxed_weathered_cut_copper_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wayfinder_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_chiseled_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_copper_bulb.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_copper_door.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_copper_grate.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_copper_trapdoor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_cut_copper.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_cut_copper_slab.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weathered_cut_copper_stairs.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">weeping_vines.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wet_sponge.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wheat.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wheat_seeds.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_tulip.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">white_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wild_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wind_charge.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">witch_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wither_rose.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wither_skeleton_skull.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">wither_skeleton_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wither_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wolf_armor.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wolf_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wooden_axe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wooden_hoe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wooden_pickaxe.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wooden_shovel.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">wooden_sword.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">writable_book.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">written_book.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_banner.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>16</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_bed.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_candle.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_carpet.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_concrete.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_concrete_powder.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_dye.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_glazed_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_shulker_box.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>1</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_stained_glass.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_stained_glass_pane.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_terracotta.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">yellow_wool.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">zoglin_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">zombie_head.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">zombie_horse_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">zombie_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">zombie_villager_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">zombified_piglin_spawn_egg.json</th></tr><tr><th></th><th align="left">24w11a</th><th>24w12a</th></tr><tr><td>minecraft:max_stack_size</td><td><code>-</code></td><td><code>64</code></td></tr><tr><td>minecraft:rarity</td><td><code>-</code></td><td><code>common</code></td></tr></table>
</details>
<details><summary>Commands</summary>
<details>
<summary>
execute
</summary>

```diff
+ execute if predicate <predicate: loot_predicate>
- execute if predicate <predicate: resource_location>
+ execute unless predicate <predicate: loot_predicate>
- execute unless predicate <predicate: resource_location>
```

</details>









<details>
<summary>
item
</summary>

```diff
+ item modify block <pos: block_pos> <slot: item_slot> <modifier: loot_modifier>
- item modify block <pos: block_pos> <slot: item_slot> <modifier: resource_location>
+ item modify entity <targets: entity> <slot: item_slot> <modifier: loot_modifier>
- item modify entity <targets: entity> <slot: item_slot> <modifier: resource_location>
+ item replace block <pos: block_pos> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: loot_modifier>
- item replace block <pos: block_pos> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace block <pos: block_pos> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: loot_modifier>
- item replace block <pos: block_pos> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace entity <targets: entity> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: loot_modifier>
- item replace entity <targets: entity> <slot: item_slot> from block <source: block_pos> <sourceSlot: item_slot> <modifier: resource_location>
+ item replace entity <targets: entity> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: loot_modifier>
- item replace entity <targets: entity> <slot: item_slot> from entity <source: entity> <sourceSlot: item_slot> <modifier: resource_location>
```

</details>





<details>
<summary>
loot
</summary>

```diff
+ loot give <players: entity> fish <loot_table: loot_table> <pos: block_pos> <tool: item_stack>
+ loot give <players: entity> fish <loot_table: loot_table> <pos: block_pos> mainhand
+ loot give <players: entity> fish <loot_table: loot_table> <pos: block_pos> offhand
- loot give <players: entity> fish <loot_table: resource_location> <pos: block_pos> <tool: item_stack>
- loot give <players: entity> fish <loot_table: resource_location> <pos: block_pos> mainhand
- loot give <players: entity> fish <loot_table: resource_location> <pos: block_pos> offhand
+ loot give <players: entity> loot <loot_table: loot_table>
- loot give <players: entity> loot <loot_table: resource_location>
+ loot insert <targetPos: block_pos> fish <loot_table: loot_table> <pos: block_pos> <tool: item_stack>
+ loot insert <targetPos: block_pos> fish <loot_table: loot_table> <pos: block_pos> mainhand
+ loot insert <targetPos: block_pos> fish <loot_table: loot_table> <pos: block_pos> offhand
- loot insert <targetPos: block_pos> fish <loot_table: resource_location> <pos: block_pos> <tool: item_stack>
- loot insert <targetPos: block_pos> fish <loot_table: resource_location> <pos: block_pos> mainhand
- loot insert <targetPos: block_pos> fish <loot_table: resource_location> <pos: block_pos> offhand
+ loot insert <targetPos: block_pos> loot <loot_table: loot_table>
- loot insert <targetPos: block_pos> loot <loot_table: resource_location>
+ loot replace block <targetPos: block_pos> <slot: item_slot> <count: integer> fish <loot_table: loot_table> <pos: block_pos> <tool: item_stack>
+ loot replace block <targetPos: block_pos> <slot: item_slot> <count: integer> fish <loot_table: loot_table> <pos: block_pos> mainhand
+ loot replace block <targetPos: block_pos> <slot: item_slot> <count: integer> fish <loot_table: loot_table> <pos: block_pos> offhand
- loot replace block <targetPos: block_pos> <slot: item_slot> <count: integer> fish <loot_table: resource_location> <pos: block_pos> <tool: item_stack>
- loot replace block <targetPos: block_pos> <slot: item_slot> <count: integer> fish <loot_table: resource_location> <pos: block_pos> mainhand
- loot replace block <targetPos: block_pos> <slot: item_slot> <count: integer> fish <loot_table: resource_location> <pos: block_pos> offhand
+ loot replace block <targetPos: block_pos> <slot: item_slot> <count: integer> loot <loot_table: loot_table>
- loot replace block <targetPos: block_pos> <slot: item_slot> <count: integer> loot <loot_table: resource_location>
+ loot replace block <targetPos: block_pos> <slot: item_slot> fish <loot_table: loot_table> <pos: block_pos> <tool: item_stack>
+ loot replace block <targetPos: block_pos> <slot: item_slot> fish <loot_table: loot_table> <pos: block_pos> mainhand
+ loot replace block <targetPos: block_pos> <slot: item_slot> fish <loot_table: loot_table> <pos: block_pos> offhand
- loot replace block <targetPos: block_pos> <slot: item_slot> fish <loot_table: resource_location> <pos: block_pos> <tool: item_stack>
- loot replace block <targetPos: block_pos> <slot: item_slot> fish <loot_table: resource_location> <pos: block_pos> mainhand
- loot replace block <targetPos: block_pos> <slot: item_slot> fish <loot_table: resource_location> <pos: block_pos> offhand
+ loot replace block <targetPos: block_pos> <slot: item_slot> loot <loot_table: loot_table>
- loot replace block <targetPos: block_pos> <slot: item_slot> loot <loot_table: resource_location>
+ loot replace entity <entities: entity> <slot: item_slot> <count: integer> fish <loot_table: loot_table> <pos: block_pos> <tool: item_stack>
+ loot replace entity <entities: entity> <slot: item_slot> <count: integer> fish <loot_table: loot_table> <pos: block_pos> mainhand
+ loot replace entity <entities: entity> <slot: item_slot> <count: integer> fish <loot_table: loot_table> <pos: block_pos> offhand
- loot replace entity <entities: entity> <slot: item_slot> <count: integer> fish <loot_table: resource_location> <pos: block_pos> <tool: item_stack>
- loot replace entity <entities: entity> <slot: item_slot> <count: integer> fish <loot_table: resource_location> <pos: block_pos> mainhand
- loot replace entity <entities: entity> <slot: item_slot> <count: integer> fish <loot_table: resource_location> <pos: block_pos> offhand
+ loot replace entity <entities: entity> <slot: item_slot> <count: integer> loot <loot_table: loot_table>
- loot replace entity <entities: entity> <slot: item_slot> <count: integer> loot <loot_table: resource_location>
+ loot replace entity <entities: entity> <slot: item_slot> fish <loot_table: loot_table> <pos: block_pos> <tool: item_stack>
+ loot replace entity <entities: entity> <slot: item_slot> fish <loot_table: loot_table> <pos: block_pos> mainhand
+ loot replace entity <entities: entity> <slot: item_slot> fish <loot_table: loot_table> <pos: block_pos> offhand
- loot replace entity <entities: entity> <slot: item_slot> fish <loot_table: resource_location> <pos: block_pos> <tool: item_stack>
- loot replace entity <entities: entity> <slot: item_slot> fish <loot_table: resource_location> <pos: block_pos> mainhand
- loot replace entity <entities: entity> <slot: item_slot> fish <loot_table: resource_location> <pos: block_pos> offhand
+ loot replace entity <entities: entity> <slot: item_slot> loot <loot_table: loot_table>
- loot replace entity <entities: entity> <slot: item_slot> loot <loot_table: resource_location>
+ loot spawn <targetPos: vec3> fish <loot_table: loot_table> <pos: block_pos> <tool: item_stack>
+ loot spawn <targetPos: vec3> fish <loot_table: loot_table> <pos: block_pos> mainhand
+ loot spawn <targetPos: vec3> fish <loot_table: loot_table> <pos: block_pos> offhand
- loot spawn <targetPos: vec3> fish <loot_table: resource_location> <pos: block_pos> <tool: item_stack>
- loot spawn <targetPos: vec3> fish <loot_table: resource_location> <pos: block_pos> mainhand
- loot spawn <targetPos: vec3> fish <loot_table: resource_location> <pos: block_pos> offhand
+ loot spawn <targetPos: vec3> loot <loot_table: loot_table>
- loot spawn <targetPos: vec3> loot <loot_table: resource_location>
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.adventure.blowback.description: Kill a Breeze with a deflected Breeze-shot Wind Charge
+ advancements.adventure.blowback.title: Blowback
+ advancements.adventure.crafters_crafting_crafters.description: Be near a Crafter when it crafts a Crafter
+ advancements.adventure.crafters_crafting_crafters.title: Crafters Crafting Crafters
+ advancements.adventure.lighten_up.description: Scrape a Copper Bulb with an Axe to make it brighter
+ advancements.adventure.lighten_up.title: Lighten Up
+ advancements.adventure.minecraft_trials_edition.description: Step foot in a Trial Chamber
+ advancements.adventure.minecraft_trials_edition.title: Minecraft: Trial(s) Edition
+ advancements.adventure.overoverkill.description: Deal 50 hearts of damage in a single hit using the Mace
+ advancements.adventure.overoverkill.title: Over-Overkill
+ advancements.adventure.under_lock_and_key.description: Use a Trial Key on a Vault
+ advancements.adventure.under_lock_and_key.title: Under Lock and Key
+ advancements.adventure.who_needs_rockets.description: Use a Wind Charge to launch yourself upward 7 blocks
+ advancements.adventure.who_needs_rockets.title: Who Needs Rockets?
+ argument.resource_or_id.failed_to_parse: Failed to parse structure: %s
+ argument.resource_or_id.invalid: Invalid id or tag
+ arguments.item.predicate.malformed: Malformed '%s' predicate: '%s'
+ arguments.item.predicate.unknown: Unknown item predicate '%s''
+ filled_map.trial_chambers: Trial Chambers Map
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/adventure/blowback.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/adventure/crafters_crafting_crafters.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/adventure/lighten_up.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/adventure/minecraft_trials_edition.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/adventure/overoverkill.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/adventure/under_lock_and_key.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/adventure/who_needs_rockets.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/worldgen/structure/on_trial_chambers_maps.json
+ minecraft/tags/blocks/incorrect_for_diamond_tool.json
+ minecraft/tags/blocks/incorrect_for_gold_tool.json
+ minecraft/tags/blocks/incorrect_for_iron_tool.json
+ minecraft/tags/blocks/incorrect_for_netherite_tool.json
+ minecraft/tags/blocks/incorrect_for_stone_tool.json
+ minecraft/tags/blocks/incorrect_for_wooden_tool.json
+ minecraft/tags/entity_types/sensitive_to_smite.json
+ minecraft/tags/items/armadillo_food.json
+ minecraft/tags/items/axolotl_food.json
- minecraft/tags/items/axolotl_tempt_items.json
+ minecraft/tags/items/bee_food.json
+ minecraft/tags/items/camel_food.json
+ minecraft/tags/items/cat_food.json
+ minecraft/tags/items/chicken_food.json
+ minecraft/tags/items/cow_food.json
+ minecraft/tags/items/frog_food.json
+ minecraft/tags/items/goat_food.json
+ minecraft/tags/items/hoglin_food.json
+ minecraft/tags/items/horse_food.json
+ minecraft/tags/items/horse_tempt_items.json
+ minecraft/tags/items/llama_food.json
+ minecraft/tags/items/llama_tempt_items.json
+ minecraft/tags/items/meat.json
+ minecraft/tags/items/ocelot_food.json
+ minecraft/tags/items/panda_food.json
+ minecraft/tags/items/parrot_food.json
+ minecraft/tags/items/parrot_poisonous_food.json
+ minecraft/tags/items/pig_food.json
+ minecraft/tags/items/rabbit_food.json
+ minecraft/tags/items/sheep_food.json
+ minecraft/tags/items/strider_food.json
+ minecraft/tags/items/strider_tempt_items.json
+ minecraft/tags/items/turtle_food.json
+ minecraft/tags/items/wolf_food.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/atlases/map_decorations.json
+ minecraft/textures/map/decorations/black_banner.png
+ minecraft/textures/map/decorations/blue_banner.png
+ minecraft/textures/map/decorations/blue_marker.png
+ minecraft/textures/map/decorations/brown_banner.png
+ minecraft/textures/map/decorations/cyan_banner.png
+ minecraft/textures/map/decorations/desert_village.png
+ minecraft/textures/map/decorations/frame.png
+ minecraft/textures/map/decorations/gray_banner.png
+ minecraft/textures/map/decorations/green_banner.png
+ minecraft/textures/map/decorations/jungle_temple.png
+ minecraft/textures/map/decorations/light_blue_banner.png
+ minecraft/textures/map/decorations/light_gray_banner.png
+ minecraft/textures/map/decorations/lime_banner.png
+ minecraft/textures/map/decorations/magenta_banner.png
+ minecraft/textures/map/decorations/ocean_monument.png
+ minecraft/textures/map/decorations/orange_banner.png
+ minecraft/textures/map/decorations/pink_banner.png
+ minecraft/textures/map/decorations/plains_village.png
+ minecraft/textures/map/decorations/player_off_limits.png
+ minecraft/textures/map/decorations/player_off_map.png
+ minecraft/textures/map/decorations/player.png
+ minecraft/textures/map/decorations/purple_banner.png
+ minecraft/textures/map/decorations/red_banner.png
+ minecraft/textures/map/decorations/red_marker.png
+ minecraft/textures/map/decorations/red_x.png
+ minecraft/textures/map/decorations/savanna_village.png
+ minecraft/textures/map/decorations/snowy_village.png
+ minecraft/textures/map/decorations/swamp_hut.png
+ minecraft/textures/map/decorations/taiga_village.png
+ minecraft/textures/map/decorations/target_point.png
+ minecraft/textures/map/decorations/target_x.png
+ minecraft/textures/map/decorations/trial_chambers.png
+ minecraft/textures/map/decorations/white_banner.png
+ minecraft/textures/map/decorations/woodland_mansion.png
+ minecraft/textures/map/decorations/yellow_banner.png
- minecraft/textures/map/map_icons.png
```

</details>
</details>
<details><summary>Misc</summary>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:loot_modifier
+ minecraft:loot_predicate
+ minecraft:loot_table
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
- net.minecraft.advancements.critereon.EntitySubPredicates$EntityHolderVariantPredicateType
- net.minecraft.advancements.critereon.FallAfterExplosionTrigger$TriggerInstance
- net.minecraft.commands.arguments.item.ComponentPredicateParser
- net.minecraft.commands.arguments.item.ComponentPredicateParser$Context
- net.minecraft.commands.arguments.item.ComponentPredicateParser$PredicateLookupRule
- net.minecraft.commands.arguments.item.ItemParser$SuggestionsVisitor
- net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Context
+ net.minecraft.commands.arguments.item.ItemPredicateParser$1
+ net.minecraft.commands.arguments.item.ItemSyntaxParser$State
+ net.minecraft.commands.arguments.item.ItemSyntaxParser$Visitor
- net.minecraft.commands.arguments.ResourceOrIdArgument$LootModifierArgument
- net.minecraft.commands.arguments.ResourceOrIdArgument$LootTableArgument
- net.minecraft.core.particles.ColorParticleOption$1
+ net.minecraft.core.particles.DustColorTransitionOptions
- net.minecraft.core.particles.DustColorTransitionOptions$1
+ net.minecraft.core.particles.DustParticleOptions
- net.minecraft.core.particles.DustParticleOptions$1
+ net.minecraft.core.particles.DustParticleOptionsBase
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleGroup
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SculkChargeParticleOptions
+ net.minecraft.core.particles.SculkChargeParticleOptions$1
- net.minecraft.core.particles.ShriekParticleOption
+ net.minecraft.core.particles.ShriekParticleOption$1
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption
+ net.minecraft.core.particles.VibrationParticleOption$1
+ net.minecraft.core.registries.BuiltInRegistries
- net.minecraft.core.registries.BuiltInRegistries$RegistryBootstrap
- net.minecraft.core.registries.package-info
+ net.minecraft.core.registries.Registries
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdvancementSubProvider
+ net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.packs.package-info
- net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdvancementProvider
+ net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
- net.minecraft.data.advancements.packs.VanillaAdvancementProvider
+ net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
- net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
+ net.minecraft.data.advancements.packs.VanillaNetherAdvancements
- net.minecraft.data.advancements.packs.VanillaStoryAdvancements
+ net.minecraft.data.advancements.packs.VanillaTheEndAdvancements
+ net.minecraft.data.BlockFamilies
- net.minecraft.data.BlockFamily
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.CachedOutput
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataGenerator$PackGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.DataProvider$Factory
- net.minecraft.data.HashCache
+ net.minecraft.data.HashCache$1
- net.minecraft.data.HashCache$CacheUpdater
+ net.minecraft.data.HashCache$ProviderCache
- net.minecraft.data.HashCache$ProviderCacheBuilder
+ net.minecraft.data.HashCache$UpdateFunction
- net.minecraft.data.HashCache$UpdateResult
+ net.minecraft.data.info.BiomeParametersDumpReport
- net.minecraft.data.info.BlockListReport
+ net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.ItemListReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLootSubProvider
- net.minecraft.data.loot.EntityLootSubProvider
+ net.minecraft.data.loot.LootTableProvider
+ net.minecraft.data.Main
- net.minecraft.data.PackOutput
+ net.minecraft.data.PackOutput$PathProvider
- net.minecraft.data.PackOutput$Target
+ net.minecraft.data.tags.package-info
- net.minecraft.data.tags.VanillaBlockTagsProvider
+ net.minecraft.data.tags.VanillaItemTagsProvider
- net.minecraft.data.tags.WorldPresetTagsProvider
- net.minecraft.data.worldgen.AncientCityStructurePieces
+ net.minecraft.data.worldgen.AncientCityStructurePools
- net.minecraft.data.worldgen.BastionBridgePools
+ net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionHousingUnitsPools
+ net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionSharedPools
+ net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.biome.BiomeData
+ net.minecraft.data.worldgen.biome.EndBiomes
- net.minecraft.data.worldgen.biome.NetherBiomes
+ net.minecraft.data.worldgen.biome.OverworldBiomes
- net.minecraft.data.worldgen.biome.package-info
- net.minecraft.data.worldgen.BiomeDefaultFeatures
+ net.minecraft.data.worldgen.BootstrapContext
- net.minecraft.data.worldgen.Carvers
+ net.minecraft.data.worldgen.DesertVillagePools
- net.minecraft.data.worldgen.DimensionTypes
+ net.minecraft.data.worldgen.features.AquaticFeatures
- net.minecraft.data.worldgen.features.CaveFeatures
+ net.minecraft.data.worldgen.features.EndFeatures
- net.minecraft.data.worldgen.features.FeatureUtils
+ net.minecraft.data.worldgen.features.MiscOverworldFeatures
- net.minecraft.data.worldgen.features.NetherFeatures
+ net.minecraft.data.worldgen.features.OreFeatures
+ net.minecraft.data.worldgen.features.package-info
- net.minecraft.data.worldgen.features.PileFeatures
+ net.minecraft.data.worldgen.features.TreeFeatures
- net.minecraft.data.worldgen.features.VegetationFeatures
+ net.minecraft.data.worldgen.NoiseData
- net.minecraft.data.worldgen.package-info
- net.minecraft.data.worldgen.PillagerOutpostPools
+ net.minecraft.data.worldgen.placement.AquaticPlacements
- net.minecraft.data.worldgen.placement.CavePlacements
+ net.minecraft.data.worldgen.placement.EndPlacements
- net.minecraft.data.worldgen.placement.MiscOverworldPlacements
+ net.minecraft.data.worldgen.placement.NetherPlacements
- net.minecraft.data.worldgen.placement.OrePlacements
+ net.minecraft.data.worldgen.placement.package-info
+ net.minecraft.data.worldgen.placement.PlacementUtils
- net.minecraft.data.worldgen.placement.TreePlacements
+ net.minecraft.data.worldgen.placement.VegetationPlacements
- net.minecraft.data.worldgen.placement.VillagePlacements
+ net.minecraft.data.worldgen.PlainVillagePools
- net.minecraft.data.worldgen.Pools
+ net.minecraft.data.worldgen.ProcessorLists
- net.minecraft.data.worldgen.SavannaVillagePools
+ net.minecraft.data.worldgen.SnowyVillagePools
+ net.minecraft.data.worldgen.Structures
- net.minecraft.data.worldgen.StructureSets
- net.minecraft.data.worldgen.SurfaceRuleData
+ net.minecraft.data.worldgen.TaigaVillagePools
- net.minecraft.data.worldgen.TerrainProvider
+ net.minecraft.data.worldgen.TrailRuinsStructurePools
- net.minecraft.data.worldgen.TrialChambersStructurePools
+ net.minecraft.data.worldgen.UpdateOneTwentyOnePools
- net.minecraft.data.worldgen.UpdateOneTwentyOneProcessorLists
- net.minecraft.data.worldgen.UpdateOneTwentyOneStructures
+ net.minecraft.data.worldgen.UpdateOneTwentyOneStructureSets
+ net.minecraft.data.worldgen.VillagePools
- net.minecraft.gametest.framework.AfterBatch
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.ExhaustedAttemptsException
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchFactory
- net.minecraft.gametest.framework.GameTestBatchListener
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestHelper$1
+ net.minecraft.gametest.framework.GameTestHelper$2
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestRunner$1
+ net.minecraft.gametest.framework.GameTestRunner$Builder
- net.minecraft.gametest.framework.GameTestRunner$GameTestBatcher
+ net.minecraft.gametest.framework.GameTestRunner$StructureSpawner
- net.minecraft.gametest.framework.GameTestSequence
+ net.minecraft.gametest.framework.GameTestSequence$Condition
- net.minecraft.gametest.framework.GameTestServer
+ net.minecraft.gametest.framework.GameTestServer$1
- net.minecraft.gametest.framework.GameTestTicker
+ net.minecraft.gametest.framework.GameTestTimeoutException
- net.minecraft.gametest.framework.GlobalTestReporter
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.ReportGameListener
- net.minecraft.gametest.framework.RetryOptions
+ net.minecraft.gametest.framework.StructureBlockPosFinder
- net.minecraft.gametest.framework.StructureGridSpawner
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.StructureUtils$1
+ net.minecraft.gametest.framework.TestClassNameArgument
- net.minecraft.gametest.framework.TestCommand
+ net.minecraft.gametest.framework.TestCommand$Runner
- net.minecraft.gametest.framework.TestCommand$TestBatchSummaryDisplayer
+ net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
- net.minecraft.gametest.framework.TestFinder
+ net.minecraft.gametest.framework.TestFinder$Builder
- net.minecraft.gametest.framework.TestFunction
+ net.minecraft.gametest.framework.TestFunctionArgument
- net.minecraft.gametest.framework.TestFunctionFinder
+ net.minecraft.gametest.framework.TestReporter
+ net.minecraft.locale.Language
- net.minecraft.locale.Language$1
+ net.minecraft.locale.package-info
- net.minecraft.nbt.ByteArrayTag
+ net.minecraft.nbt.ByteArrayTag$1
- net.minecraft.nbt.ByteTag
+ net.minecraft.nbt.ByteTag$1
- net.minecraft.nbt.ByteTag$Cache
+ net.minecraft.nbt.CollectionTag
- net.minecraft.nbt.CompoundTag
+ net.minecraft.nbt.CompoundTag$1
- net.minecraft.nbt.CompoundTag$2
+ net.minecraft.nbt.DoubleTag
- net.minecraft.nbt.DoubleTag$1
+ net.minecraft.nbt.EndTag
- net.minecraft.nbt.EndTag$1
+ net.minecraft.nbt.FloatTag
- net.minecraft.nbt.FloatTag$1
+ net.minecraft.nbt.IntArrayTag
- net.minecraft.nbt.IntArrayTag$1
+ net.minecraft.nbt.IntTag
- net.minecraft.nbt.IntTag$1
+ net.minecraft.nbt.IntTag$Cache
- net.minecraft.nbt.ListTag
+ net.minecraft.nbt.ListTag$1
- net.minecraft.nbt.ListTag$2
+ net.minecraft.nbt.LongArrayTag
- net.minecraft.nbt.LongArrayTag$1
+ net.minecraft.nbt.LongTag
- net.minecraft.nbt.LongTag$1
+ net.minecraft.nbt.LongTag$Cache
- net.minecraft.nbt.NbtAccounter
+ net.minecraft.nbt.NbtAccounterException
- net.minecraft.nbt.NbtException
+ net.minecraft.nbt.NbtFormatException
- net.minecraft.nbt.NbtIo
+ net.minecraft.nbt.NbtIo$1
- net.minecraft.nbt.NbtIo$StringFallbackDataOutput
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
+ net.minecraft.nbt.NbtOps$ByteListCollector
- net.minecraft.nbt.NbtOps$HeterogenousListCollector
+ net.minecraft.nbt.NbtOps$HomogenousListCollector
- net.minecraft.nbt.NbtOps$InitialListCollector
+ net.minecraft.nbt.NbtOps$IntListCollector
- net.minecraft.nbt.NbtOps$ListCollector
+ net.minecraft.nbt.NbtOps$LongListCollector
- net.minecraft.nbt.NbtOps$NbtRecordBuilder
+ net.minecraft.nbt.NbtUtils
- net.minecraft.nbt.NumericTag
- net.minecraft.nbt.package-info
+ net.minecraft.nbt.ReportedNbtException
- net.minecraft.nbt.ShortTag
+ net.minecraft.nbt.ShortTag$1
- net.minecraft.nbt.ShortTag$Cache
+ net.minecraft.nbt.SnbtPrinterTagVisitor
- net.minecraft.nbt.StreamTagVisitor
+ net.minecraft.nbt.StreamTagVisitor$EntryResult
- net.minecraft.nbt.StreamTagVisitor$ValueResult
+ net.minecraft.nbt.StringTag
- net.minecraft.nbt.StringTag$1
+ net.minecraft.nbt.StringTagVisitor
- net.minecraft.nbt.Tag
+ net.minecraft.nbt.TagParser
- net.minecraft.nbt.TagType
+ net.minecraft.nbt.TagType$1
- net.minecraft.nbt.TagType$2
+ net.minecraft.nbt.TagType$StaticSize
- net.minecraft.nbt.TagType$VariableSize
+ net.minecraft.nbt.TagTypes
- net.minecraft.nbt.TagVisitor
+ net.minecraft.nbt.TextComponentTagVisitor
+ net.minecraft.nbt.visitors.CollectFields
- net.minecraft.nbt.visitors.CollectToTag
+ net.minecraft.nbt.visitors.FieldSelector
- net.minecraft.nbt.visitors.FieldTree
- net.minecraft.nbt.visitors.package-info
+ net.minecraft.nbt.visitors.SkipAll
- net.minecraft.nbt.visitors.SkipAll$1
+ net.minecraft.nbt.visitors.SkipFields
+ net.minecraft.network.BandwidthDebugMonitor
+ net.minecraft.network.chat.ChatDecorator
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ChatType$Bound
- net.minecraft.network.chat.ChatTypeDecoration
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter
- net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
+ net.minecraft.network.chat.ClickEvent
- net.minecraft.network.chat.ClickEvent$Action
+ net.minecraft.network.chat.CommonComponents
- net.minecraft.network.chat.Component
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.Component$SerializerAdapter
+ net.minecraft.network.chat.ComponentContents
- net.minecraft.network.chat.ComponentContents$Type
+ net.minecraft.network.chat.ComponentSerialization
- net.minecraft.network.chat.ComponentSerialization$1
+ net.minecraft.network.chat.ComponentSerialization$FuzzyCodec
- net.minecraft.network.chat.ComponentSerialization$StrictEither
+ net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.contents.BlockDataSource
- net.minecraft.network.chat.contents.DataSource
+ net.minecraft.network.chat.contents.DataSource$Type
- net.minecraft.network.chat.contents.EntityDataSource
+ net.minecraft.network.chat.contents.KeybindContents
- net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.NbtContents
- net.minecraft.network.chat.contents.package-info
- net.minecraft.network.chat.contents.PlainTextContents
+ net.minecraft.network.chat.contents.PlainTextContents$1
- net.minecraft.network.chat.contents.PlainTextContents$LiteralContents
+ net.minecraft.network.chat.contents.ScoreContents
- net.minecraft.network.chat.contents.SelectorContents
+ net.minecraft.network.chat.contents.StorageDataSource
- net.minecraft.network.chat.contents.TranslatableContents
+ net.minecraft.network.chat.contents.TranslatableFormatException
- net.minecraft.network.chat.FilterMask
+ net.minecraft.network.chat.FilterMask$1
- net.minecraft.network.chat.FilterMask$Type
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$Action$1
+ net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
- net.minecraft.network.chat.HoverEvent$ItemStackInfo
+ net.minecraft.network.chat.HoverEvent$LegacyConverter
- net.minecraft.network.chat.HoverEvent$TypedHoverEvent
+ net.minecraft.network.chat.LastSeenMessages
- net.minecraft.network.chat.LastSeenMessages$Packed
+ net.minecraft.network.chat.LastSeenMessages$Update
- net.minecraft.network.chat.LastSeenMessagesTracker
+ net.minecraft.network.chat.LastSeenMessagesTracker$Update
- net.minecraft.network.chat.LastSeenMessagesValidator
+ net.minecraft.network.chat.LastSeenTrackedEntry
- net.minecraft.network.chat.LocalChatSession
+ net.minecraft.network.chat.MessageSignature
- net.minecraft.network.chat.MessageSignature$Packed
+ net.minecraft.network.chat.MessageSignatureCache
- net.minecraft.network.chat.MutableComponent
+ net.minecraft.network.chat.numbers.BlankFormat
- net.minecraft.network.chat.numbers.BlankFormat$1
+ net.minecraft.network.chat.numbers.FixedFormat
- net.minecraft.network.chat.numbers.FixedFormat$1
+ net.minecraft.network.chat.numbers.NumberFormat
- net.minecraft.network.chat.numbers.NumberFormatType
+ net.minecraft.network.chat.numbers.NumberFormatTypes
- net.minecraft.network.chat.numbers.package-info
- net.minecraft.network.chat.numbers.StyledFormat
+ net.minecraft.network.chat.numbers.StyledFormat$1
+ net.minecraft.network.chat.OutgoingChatMessage
- net.minecraft.network.chat.OutgoingChatMessage$Disguised
+ net.minecraft.network.chat.OutgoingChatMessage$Player
+ net.minecraft.network.chat.package-info
- net.minecraft.network.chat.PlayerChatMessage
+ net.minecraft.network.chat.RemoteChatSession
- net.minecraft.network.chat.RemoteChatSession$Data
+ net.minecraft.network.chat.SignableCommand
- net.minecraft.network.chat.SignableCommand$Argument
+ net.minecraft.network.chat.SignedMessageBody
- net.minecraft.network.chat.SignedMessageBody$Packed
+ net.minecraft.network.chat.SignedMessageChain
- net.minecraft.network.chat.SignedMessageChain$DecodeException
+ net.minecraft.network.chat.SignedMessageChain$Decoder
- net.minecraft.network.chat.SignedMessageChain$Encoder
+ net.minecraft.network.chat.SignedMessageLink
- net.minecraft.network.chat.SignedMessageValidator
+ net.minecraft.network.chat.SignedMessageValidator$KeyBased
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$1Collector
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.SubStringSource
+ net.minecraft.network.chat.TextColor
- net.minecraft.network.chat.ThrowingComponent
- net.minecraft.network.CipherBase
+ net.minecraft.network.CipherDecoder
- net.minecraft.network.CipherEncoder
+ net.minecraft.network.ClientboundPacketListener
- net.minecraft.network.codec.ByteBufCodecs
+ net.minecraft.network.codec.ByteBufCodecs$1
- net.minecraft.network.codec.ByteBufCodecs$10
+ net.minecraft.network.codec.ByteBufCodecs$11
- net.minecraft.network.codec.ByteBufCodecs$12
+ net.minecraft.network.codec.ByteBufCodecs$13
- net.minecraft.network.codec.ByteBufCodecs$14
+ net.minecraft.network.codec.ByteBufCodecs$15
- net.minecraft.network.codec.ByteBufCodecs$16
+ net.minecraft.network.codec.ByteBufCodecs$17
- net.minecraft.network.codec.ByteBufCodecs$18
+ net.minecraft.network.codec.ByteBufCodecs$19
- net.minecraft.network.codec.ByteBufCodecs$2
+ net.minecraft.network.codec.ByteBufCodecs$20
- net.minecraft.network.codec.ByteBufCodecs$21
+ net.minecraft.network.codec.ByteBufCodecs$22
- net.minecraft.network.codec.ByteBufCodecs$23
+ net.minecraft.network.codec.ByteBufCodecs$24
- net.minecraft.network.codec.ByteBufCodecs$25
+ net.minecraft.network.codec.ByteBufCodecs$26
- net.minecraft.network.codec.ByteBufCodecs$27
+ net.minecraft.network.codec.ByteBufCodecs$3
- net.minecraft.network.codec.ByteBufCodecs$4
+ net.minecraft.network.codec.ByteBufCodecs$5
- net.minecraft.network.codec.ByteBufCodecs$6
+ net.minecraft.network.codec.ByteBufCodecs$7
- net.minecraft.network.codec.ByteBufCodecs$8
+ net.minecraft.network.codec.ByteBufCodecs$9
- net.minecraft.network.codec.IdDispatchCodec
+ net.minecraft.network.codec.IdDispatchCodec$Builder
- net.minecraft.network.codec.IdDispatchCodec$Entry
+ net.minecraft.network.codec.package-info
+ net.minecraft.network.codec.StreamCodec
- net.minecraft.network.codec.StreamCodec$1
+ net.minecraft.network.codec.StreamCodec$10
- net.minecraft.network.codec.StreamCodec$11
+ net.minecraft.network.codec.StreamCodec$12
- net.minecraft.network.codec.StreamCodec$13
+ net.minecraft.network.codec.StreamCodec$2
- net.minecraft.network.codec.StreamCodec$3
+ net.minecraft.network.codec.StreamCodec$4
- net.minecraft.network.codec.StreamCodec$5
+ net.minecraft.network.codec.StreamCodec$6
- net.minecraft.network.codec.StreamCodec$7
+ net.minecraft.network.codec.StreamCodec$8
- net.minecraft.network.codec.StreamCodec$9
+ net.minecraft.network.codec.StreamCodec$CodecOperation
- net.minecraft.network.codec.StreamDecoder
+ net.minecraft.network.codec.StreamEncoder
- net.minecraft.network.codec.StreamMemberEncoder
- net.minecraft.network.CompressionDecoder
+ net.minecraft.network.CompressionEncoder
- net.minecraft.network.Connection
+ net.minecraft.network.Connection$1
- net.minecraft.network.Connection$2
+ net.minecraft.network.Connection$3
- net.minecraft.network.ConnectionProtocol
+ net.minecraft.network.FriendlyByteBuf
- net.minecraft.network.HandlerNames
- net.minecraft.network.package-info
+ net.minecraft.network.PacketBundlePacker
- net.minecraft.network.PacketBundleUnpacker
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
- net.minecraft.network.PacketSendListener
+ net.minecraft.network.PacketSendListener$1
- net.minecraft.network.PacketSendListener$2
+ net.minecraft.network.protocol.BundleDelimiterPacket
- net.minecraft.network.protocol.BundlePacket
+ net.minecraft.network.protocol.BundlerInfo
- net.minecraft.network.protocol.BundlerInfo$1
+ net.minecraft.network.protocol.BundlerInfo$1$1
- net.minecraft.network.protocol.BundlerInfo$Bundler
- net.minecraft.network.protocol.common.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.common.ClientboundDisconnectPacket
- net.minecraft.network.protocol.common.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.common.ClientboundPingPacket
- net.minecraft.network.protocol.common.ClientboundResourcePackPopPacket
+ net.minecraft.network.protocol.common.ClientboundResourcePackPushPacket
- net.minecraft.network.protocol.common.ClientboundStoreCookiePacket
+ net.minecraft.network.protocol.common.ClientboundTransferPacket
- net.minecraft.network.protocol.common.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.common.ClientCommonPacketListener
+ net.minecraft.network.protocol.common.CommonPacketTypes
+ net.minecraft.network.protocol.common.custom.BeeDebugPayload
- net.minecraft.network.protocol.common.custom.BeeDebugPayload$BeeInfo
+ net.minecraft.network.protocol.common.custom.BrainDebugPayload
- net.minecraft.network.protocol.common.custom.BrainDebugPayload$BrainDump
+ net.minecraft.network.protocol.common.custom.BrandPayload
- net.minecraft.network.protocol.common.custom.BreezeDebugPayload
+ net.minecraft.network.protocol.common.custom.BreezeDebugPayload$BreezeInfo
- net.minecraft.network.protocol.common.custom.CustomPacketPayload
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload$1
- net.minecraft.network.protocol.common.custom.CustomPacketPayload$FallbackProvider
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload$Type
- net.minecraft.network.protocol.common.custom.CustomPacketPayload$TypeAndCodec
+ net.minecraft.network.protocol.common.custom.DiscardedPayload
- net.minecraft.network.protocol.common.custom.GameEventDebugPayload
+ net.minecraft.network.protocol.common.custom.GameEventListenerDebugPayload
- net.minecraft.network.protocol.common.custom.GameTestAddMarkerDebugPayload
+ net.minecraft.network.protocol.common.custom.GameTestClearMarkersDebugPayload
- net.minecraft.network.protocol.common.custom.GoalDebugPayload
+ net.minecraft.network.protocol.common.custom.GoalDebugPayload$DebugGoal
- net.minecraft.network.protocol.common.custom.HiveDebugPayload
+ net.minecraft.network.protocol.common.custom.HiveDebugPayload$HiveInfo
- net.minecraft.network.protocol.common.custom.NeighborUpdatesDebugPayload
- net.minecraft.network.protocol.common.custom.package-info
+ net.minecraft.network.protocol.common.custom.PathfindingDebugPayload
- net.minecraft.network.protocol.common.custom.PoiAddedDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiRemovedDebugPayload
- net.minecraft.network.protocol.common.custom.PoiTicketCountDebugPayload
+ net.minecraft.network.protocol.common.custom.RaidsDebugPayload
- net.minecraft.network.protocol.common.custom.StructuresDebugPayload
+ net.minecraft.network.protocol.common.custom.StructuresDebugPayload$PieceInfo
- net.minecraft.network.protocol.common.custom.VillageSectionsDebugPayload
+ net.minecraft.network.protocol.common.custom.WorldGenAttemptDebugPayload
+ net.minecraft.network.protocol.common.package-info
+ net.minecraft.network.protocol.common.ServerboundClientInformationPacket
- net.minecraft.network.protocol.common.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.common.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.common.ServerboundPongPacket
+ net.minecraft.network.protocol.common.ServerboundResourcePackPacket
- net.minecraft.network.protocol.common.ServerboundResourcePackPacket$Action
- net.minecraft.network.protocol.common.ServerCommonPacketListener
+ net.minecraft.network.protocol.configuration.ClientboundFinishConfigurationPacket
- net.minecraft.network.protocol.configuration.ClientboundRegistryDataPacket
+ net.minecraft.network.protocol.configuration.ClientboundSelectKnownPacks
- net.minecraft.network.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
- net.minecraft.network.protocol.configuration.ClientConfigurationPacketListener
+ net.minecraft.network.protocol.configuration.ConfigurationPacketTypes
- net.minecraft.network.protocol.configuration.ConfigurationProtocols
- net.minecraft.network.protocol.configuration.package-info
- net.minecraft.network.protocol.configuration.ServerboundFinishConfigurationPacket
+ net.minecraft.network.protocol.configuration.ServerboundSelectKnownPacks
+ net.minecraft.network.protocol.configuration.ServerConfigurationPacketListener
- net.minecraft.network.protocol.cookie.ClientboundCookieRequestPacket
+ net.minecraft.network.protocol.cookie.ClientCookiePacketListener
+ net.minecraft.network.protocol.cookie.CookiePacketTypes
- net.minecraft.network.protocol.cookie.package-info
+ net.minecraft.network.protocol.cookie.ServerboundCookieResponsePacket
- net.minecraft.network.protocol.cookie.ServerCookiePacketListener
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockChangedAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ net.minecraft.network.protocol.game.ClientboundBundleDelimiterPacket
- net.minecraft.network.protocol.game.ClientboundBundlePacket
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChunkBatchFinishedPacket
+ net.minecraft.network.protocol.game.ClientboundChunkBatchStartPacket
- net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket
+ net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
- net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- net.minecraft.network.protocol.game.ClientboundDamageEventPacket
+ net.minecraft.network.protocol.game.ClientboundDebugSamplePacket
- net.minecraft.network.protocol.game.ClientboundDeleteChatPacket
+ net.minecraft.network.protocol.game.ClientboundDisguisedChatPacket
- net.minecraft.network.protocol.game.ClientboundEntityEventPacket
+ net.minecraft.network.protocol.game.ClientboundExplodePacket
- net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
+ net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
- net.minecraft.network.protocol.game.ClientboundHurtAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundInitializeBorderPacket
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ net.minecraft.network.protocol.game.ClientboundLevelChunkWithLightPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
- net.minecraft.network.protocol.game.ClientboundLoginPacket
+ net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
- net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
+ net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ClientboundOpenBookPacket
+ net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
- net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
+ net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
- net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerChatPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoRemovePacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
- net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundResetScorePacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundServerDataPacket
- net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
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
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
- net.minecraft.network.protocol.game.ClientboundSoundPacket
+ net.minecraft.network.protocol.game.ClientboundStartConfigurationPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundSystemChatPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundTickingStatePacket
+ net.minecraft.network.protocol.game.ClientboundTickingStepPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
+ net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.game.CommonPlayerSpawnInfo
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.GamePacketTypes
+ net.minecraft.network.protocol.game.GameProtocols
- net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQueryPacket
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatAckPacket
- net.minecraft.network.protocol.game.ServerboundChatCommandPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundChatSessionUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundChunkBatchReceivedPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundConfigurationAcknowledgedPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundContainerSlotStateChangedPacket
- net.minecraft.network.protocol.game.ServerboundDebugSampleSubscriptionPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQueryPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
+ net.minecraft.network.protocol.game.ServerboundPickItemPacket
- net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
+ net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ net.minecraft.network.protocol.game.ServerboundRenameItemPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
- net.minecraft.network.protocol.game.ServerboundSelectTradePacket
+ net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
- net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
+ net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
- net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
- net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundSwingPacket
- net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
- net.minecraft.network.protocol.game.ServerboundUseItemPacket
- net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.game.ServerPacketListener
+ net.minecraft.network.protocol.game.VecDeltaCodec
+ net.minecraft.network.protocol.handshake.ClientIntent
- net.minecraft.network.protocol.handshake.ClientIntent$1
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.HandshakePacketTypes
+ net.minecraft.network.protocol.handshake.HandshakeProtocols
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.custom.CustomQueryAnswerPayload
- net.minecraft.network.protocol.login.custom.CustomQueryPayload
+ net.minecraft.network.protocol.login.custom.DiscardedQueryAnswerPayload
- net.minecraft.network.protocol.login.custom.DiscardedQueryPayload
+ net.minecraft.network.protocol.login.custom.package-info
- net.minecraft.network.protocol.login.LoginPacketTypes
+ net.minecraft.network.protocol.login.LoginProtocols
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryAnswerPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerboundLoginAcknowledgedPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketType
- net.minecraft.network.protocol.PacketUtils
+ net.minecraft.network.protocol.ping.ClientboundPongResponsePacket
- net.minecraft.network.protocol.ping.ClientPongPacketListener
+ net.minecraft.network.protocol.ping.package-info
- net.minecraft.network.protocol.ping.PingPacketTypes
- net.minecraft.network.protocol.ping.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.ping.ServerPingPacketListener
+ net.minecraft.network.protocol.ProtocolCodecBuilder
- net.minecraft.network.protocol.ProtocolInfoBuilder
+ net.minecraft.network.protocol.ProtocolInfoBuilder$CodecEntry
- net.minecraft.network.protocol.ProtocolInfoBuilder$Implementation
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Favicon
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.protocol.status.StatusPacketTypes
+ net.minecraft.network.protocol.status.StatusProtocols
+ net.minecraft.network.ProtocolInfo
- net.minecraft.network.ProtocolInfo$Unbound
+ net.minecraft.network.ProtocolSwapHandler
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.RegistryFriendlyByteBuf
- net.minecraft.network.ServerboundPacketListener
+ net.minecraft.network.SkipPacketException
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializer$ForValueType
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SyncedDataHolder
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$Builder
- net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.network.syncher.SynchedEntityData$DataValue
- net.minecraft.network.TickablePacketListener
+ net.minecraft.network.UnconfiguredPipelineHandler
- net.minecraft.network.UnconfiguredPipelineHandler$Inbound
+ net.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
- net.minecraft.network.UnconfiguredPipelineHandler$Outbound
+ net.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
- net.minecraft.network.Utf8String
+ net.minecraft.network.VarInt
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.network.VarLong
+ net.minecraft.obfuscate.DontObfuscate
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.references.Blocks
- net.minecraft.references.Items
+ net.minecraft.resources.DelegatingOps
- net.minecraft.resources.FileToIdConverter
+ net.minecraft.resources.HolderSetCodec
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader
+ net.minecraft.resources.RegistryDataLoader$1
- net.minecraft.resources.RegistryDataLoader$Loader
+ net.minecraft.resources.RegistryDataLoader$LoadingFunction
- net.minecraft.resources.RegistryDataLoader$RegistryData
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryOps
- net.minecraft.resources.RegistryOps$1
+ net.minecraft.resources.RegistryOps$2
- net.minecraft.resources.RegistryOps$RegistryInfo
+ net.minecraft.resources.RegistryOps$RegistryInfoLookup
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceKey$InternKey
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Dummy
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
+ net.minecraft.server.Bootstrap$1
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.Eula
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$ReloadableResources
+ net.minecraft.server.MinecraftServer$ServerResourcePackInfo
- net.minecraft.server.MinecraftServer$TimeProfiler
+ net.minecraft.server.MinecraftServer$TimeProfiler$1
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$Data
- net.minecraft.server.RegistryLayer
- net.minecraft.server.ReloadableServerRegistries$EmptyTagLookupWrapper
- net.minecraft.util.datafix.schemas.package-info
+ net.minecraft.util.datafix.schemas.V3822
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
+ net.minecraft.util.debugchart.AbstractSampleLogger
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
+ net.minecraft.util.debugchart.LocalSampleLogger
- net.minecraft.util.debugchart.RemoteDebugSampleType
+ net.minecraft.util.debugchart.RemoteSampleLogger
- net.minecraft.util.debugchart.SampleLogger
+ net.minecraft.util.debugchart.SampleStorage
- net.minecraft.util.debugchart.TpsDebugDimensions
+ net.minecraft.util.eventlog.EventLogDirectory
- net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
+ net.minecraft.util.eventlog.EventLogDirectory$File
- net.minecraft.util.eventlog.EventLogDirectory$FileId
+ net.minecraft.util.eventlog.EventLogDirectory$FileList
- net.minecraft.util.eventlog.EventLogDirectory$RawFile
+ net.minecraft.util.eventlog.JsonEventLog
- net.minecraft.util.eventlog.JsonEventLog$1
+ net.minecraft.util.eventlog.JsonEventLogReader
- net.minecraft.util.eventlog.JsonEventLogReader$1
+ net.minecraft.util.eventlog.package-info
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.monitoring.jmx.package-info
+ net.minecraft.util.package-info
- net.minecraft.util.parsing.package-info
- net.minecraft.util.parsing.packrat.commands.Grammar
- net.minecraft.util.parsing.packrat.commands.ResourceLookupRule
- net.minecraft.util.parsing.packrat.commands.StringReaderParserState
- net.minecraft.util.parsing.packrat.commands.StringReaderTerms$TerminalCharacter
- net.minecraft.util.parsing.packrat.commands.TagParseRule
- net.minecraft.util.parsing.packrat.Control
- net.minecraft.util.parsing.packrat.ErrorCollector
- net.minecraft.util.parsing.packrat.ErrorEntry
- net.minecraft.util.parsing.packrat.package-info
- net.minecraft.util.parsing.packrat.ParseState$CacheEntry
- net.minecraft.util.parsing.packrat.Rule
- net.minecraft.util.parsing.packrat.Rule$SimpleRuleAction
- net.minecraft.util.parsing.packrat.Scope
- net.minecraft.util.parsing.packrat.Term
- net.minecraft.util.parsing.packrat.Term$2
- net.minecraft.util.parsing.packrat.Term$Marker
- net.minecraft.util.parsing.packrat.Term$Reference
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.item.component.Tool$Rule
+ net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
- net.minecraft.world.item.enchantment.BindingCurseEnchantment
+ net.minecraft.world.item.enchantment.DamageEnchantment
- net.minecraft.world.item.enchantment.DigDurabilityEnchantment
+ net.minecraft.world.item.enchantment.DiggingEnchantment
- net.minecraft.world.item.enchantment.Enchantment$Cost
+ net.minecraft.world.item.enchantment.Enchantment$Rarity
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.ItemEnchantments
- net.minecraft.world.item.enchantment.ItemEnchantments$Mutable
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.SwiftSneakEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemDisplayContext
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$1
- net.minecraft.world.item.ItemStack$2
- net.minecraft.world.item.package-info
+ net.minecraft.world.item.trading.ItemCost
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeGenerationSettings$PlainBuilder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.BiomeResolver
- net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSources
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
- net.minecraft.world.level.biome.Climate
+ net.minecraft.world.level.biome.Climate$DistanceMetric
- net.minecraft.world.level.biome.Climate$Parameter
+ net.minecraft.world.level.biome.Climate$ParameterList
- net.minecraft.world.level.biome.Climate$ParameterPoint
+ net.minecraft.world.level.biome.Climate$RTree
- net.minecraft.world.level.biome.Climate$RTree$Leaf
+ net.minecraft.world.level.biome.Climate$RTree$Node
- net.minecraft.world.level.biome.Climate$RTree$SubTree
+ net.minecraft.world.level.biome.Climate$Sampler
- net.minecraft.world.level.biome.Climate$SpawnFinder
+ net.minecraft.world.level.biome.Climate$SpawnFinder$Result
- net.minecraft.world.level.biome.Climate$TargetPoint
+ net.minecraft.world.level.biome.FeatureSorter
- net.minecraft.world.level.biome.FeatureSorter$1FeatureData
+ net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterLists
- net.minecraft.world.level.biome.OverworldBiomeBuilder
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
+ net.minecraft.world.level.block.AbstractCauldronBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
+ net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
+ net.minecraft.world.level.block.AnvilBlock
- net.minecraft.world.level.block.AttachedStemBlock
+ net.minecraft.world.level.block.AzaleaBlock
- net.minecraft.world.level.block.BambooSaplingBlock
+ net.minecraft.world.level.block.BambooStalkBlock
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
+ net.minecraft.world.level.block.BaseRailBlock$1
- net.minecraft.world.level.block.BaseTorchBlock
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
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BlockTypes
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BonemealableBlock$1
+ net.minecraft.world.level.block.BonemealableBlock$Type
- net.minecraft.world.level.block.BrewingStandBlock
+ net.minecraft.world.level.block.BrushableBlock
- net.minecraft.world.level.block.BubbleColumnBlock
+ net.minecraft.world.level.block.BucketPickup
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CalibratedSculkSensorBlock
+ net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleBlock
+ net.minecraft.world.level.block.CandleCakeBlock
- net.minecraft.world.level.block.CarpetBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.CaveVines
- net.minecraft.world.level.block.CaveVinesBlock
+ net.minecraft.world.level.block.CaveVinesPlantBlock
- net.minecraft.world.level.block.CeilingHangingSignBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
- net.minecraft.world.level.block.CherryLeavesBlock
+ net.minecraft.world.level.block.ChestBlock
- net.minecraft.world.level.block.ChestBlock$1
+ net.minecraft.world.level.block.ChestBlock$2
- net.minecraft.world.level.block.ChestBlock$2$1
+ net.minecraft.world.level.block.ChestBlock$3
- net.minecraft.world.level.block.ChestBlock$4
+ net.minecraft.world.level.block.ChiseledBookShelfBlock
- net.minecraft.world.level.block.ChiseledBookShelfBlock$1
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.ColoredFallingBlock
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CopperBulbBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CrafterBlock
- net.minecraft.world.level.block.CrafterBlock$1
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DecoratedPotBlock
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
+ net.minecraft.world.level.block.DropExperienceBlock
- net.minecraft.world.level.block.DropperBlock
+ net.minecraft.world.level.block.EnchantmentTableBlock
- net.minecraft.world.level.block.EnderChestBlock
- net.minecraft.world.level.block.EndGatewayBlock
+ net.minecraft.world.level.block.EndPortalBlock
- net.minecraft.world.level.block.EndPortalFrameBlock
+ net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPatternLayers
+ net.minecraft.world.level.block.entity.BannerPatternLayers$Builder
- net.minecraft.world.level.block.entity.BannerPatternLayers$Layer
+ net.minecraft.world.level.block.entity.BannerPatterns
- net.minecraft.world.level.block.entity.BarrelBlockEntity
+ net.minecraft.world.level.block.entity.BarrelBlockEntity$1
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$Occupant
+ net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
+ net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.BrushableBlockEntity
- net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.CrafterBlockEntity
- net.minecraft.world.level.block.entity.CrafterBlockEntity$1
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$WobbleStyle
- net.minecraft.world.level.block.entity.DecoratedPotPatterns
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.HangingSignBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.PotDecorations
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SignText
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity$1
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.entity.trialspawner.package-info
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$1
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$2
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawner
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawner$StateAccessor
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerConfig
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerData
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$1
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$LightLevel
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$ParticleEmission
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$SpinningMob
+ net.minecraft.world.level.block.entity.TrialSpawnerBlockEntity
- net.minecraft.world.level.block.entity.UpdateOneTwentyOneBannerPatterns
- net.minecraft.world.level.block.entity.vault.package-info
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity
+ net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Client
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Server
+ net.minecraft.world.level.block.entity.vault.VaultClientData
- net.minecraft.world.level.block.entity.vault.VaultConfig
+ net.minecraft.world.level.block.entity.vault.VaultServerData
- net.minecraft.world.level.block.entity.vault.VaultSharedData
+ net.minecraft.world.level.block.entity.vault.VaultState
- net.minecraft.world.level.block.entity.vault.VaultState$1
+ net.minecraft.world.level.block.entity.vault.VaultState$2
- net.minecraft.world.level.block.entity.vault.VaultState$3
+ net.minecraft.world.level.block.entity.vault.VaultState$4
- net.minecraft.world.level.block.entity.vault.VaultState$5
+ net.minecraft.world.level.block.entity.vault.VaultState$LightLevel
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.EquipableCarvedPumpkinBlock
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
+ net.minecraft.world.level.block.FrogspawnBlock
- net.minecraft.world.level.block.FrostedIceBlock
+ net.minecraft.world.level.block.FungusBlock
- net.minecraft.world.level.block.FurnaceBlock
+ net.minecraft.world.level.block.GameMasterBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GlowLichenBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GrindstoneBlock
- net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.TreeGrower
+ net.minecraft.world.level.block.GrowingPlantBlock
- net.minecraft.world.level.block.GrowingPlantBodyBlock
+ net.minecraft.world.level.block.GrowingPlantHeadBlock
- net.minecraft.world.level.block.HalfTransparentBlock
+ net.minecraft.world.level.block.HangingRootsBlock
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HeavyCoreBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.InfestedRotatedPillarBlock
- net.minecraft.world.level.block.IronBarsBlock
+ net.minecraft.world.level.block.JigsawBlock
- net.minecraft.world.level.block.JukeboxBlock
+ net.minecraft.world.level.block.KelpBlock
- net.minecraft.world.level.block.KelpPlantBlock
+ net.minecraft.world.level.block.LadderBlock
- net.minecraft.world.level.block.LadderBlock$1
+ net.minecraft.world.level.block.LanternBlock
- net.minecraft.world.level.block.LavaCauldronBlock
+ net.minecraft.world.level.block.LayeredCauldronBlock
- net.minecraft.world.level.block.LeavesBlock
+ net.minecraft.world.level.block.LecternBlock
- net.minecraft.world.level.block.LecternBlock$1
+ net.minecraft.world.level.block.LevelEvent
- net.minecraft.world.level.block.LeverBlock
+ net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.LightBlock
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MangroveLeavesBlock
+ net.minecraft.world.level.block.MangrovePropaguleBlock
- net.minecraft.world.level.block.MangroveRootsBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MudBlock
+ net.minecraft.world.level.block.MultifaceBlock
- net.minecraft.world.level.block.MultifaceSpreader
+ net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadConfig
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPredicate
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$1
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$3
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
+ net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PiglinWallSkullBlock
+ net.minecraft.world.level.block.PinkPetalsBlock
- net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.piston.MovingPistonBlock
- net.minecraft.world.level.block.piston.package-info
+ net.minecraft.world.level.block.piston.PistonBaseBlock
- net.minecraft.world.level.block.piston.PistonBaseBlock$1
+ net.minecraft.world.level.block.piston.PistonHeadBlock
- net.minecraft.world.level.block.piston.PistonHeadBlock$1
+ net.minecraft.world.level.block.piston.PistonMath
- net.minecraft.world.level.block.piston.PistonMath$1
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
+ net.minecraft.world.level.block.piston.PistonStructureResolver
+ net.minecraft.world.level.block.PitcherCropBlock
- net.minecraft.world.level.block.PitcherCropBlock$PosAndState
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PumpkinBlock
+ net.minecraft.world.level.block.RailBlock
- net.minecraft.world.level.block.RailBlock$1
+ net.minecraft.world.level.block.RailState
- net.minecraft.world.level.block.RailState$1
- net.minecraft.world.level.block.RedstoneLampBlock
+ net.minecraft.world.level.block.RedStoneOreBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock
- net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
+ net.minecraft.world.level.block.RedstoneWallTorchBlock
- net.minecraft.world.level.block.RedStoneWireBlock
+ net.minecraft.world.level.block.RedStoneWireBlock$1
- net.minecraft.world.level.block.RenderShape
+ net.minecraft.world.level.block.RepeaterBlock
- net.minecraft.world.level.block.RespawnAnchorBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock
+ net.minecraft.world.level.block.RodBlock$1
- net.minecraft.world.level.block.RootedDirtBlock
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
- net.minecraft.world.level.block.SculkBehaviour
+ net.minecraft.world.level.block.SculkBehaviour$1
- net.minecraft.world.level.block.SculkBlock
+ net.minecraft.world.level.block.SculkCatalystBlock
- net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.SculkShriekerBlock
- net.minecraft.world.level.block.SculkSpreader
+ net.minecraft.world.level.block.SculkSpreader$ChargeCursor
- net.minecraft.world.level.block.SculkVeinBlock
+ net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
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
+ net.minecraft.world.level.block.SnifferEggBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
+ net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.SporeBlossomBlock
+ net.minecraft.world.level.block.SpreadingSnowyDirtBlock
- net.minecraft.world.level.block.StainedGlassBlock
+ net.minecraft.world.level.block.StainedGlassPaneBlock
- net.minecraft.world.level.block.StairBlock
+ net.minecraft.world.level.block.StairBlock$1
- net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetFunction
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
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockSetType
+ net.minecraft.world.level.block.state.properties.BlockSetType$PressurePlateSensitivity
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ChestType$1
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument$Type
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.RotationSegment
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
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StonecutterBlock
+ net.minecraft.world.level.block.StructureBlock
- net.minecraft.world.level.block.StructureBlock$1
+ net.minecraft.world.level.block.StructureVoidBlock
- net.minecraft.world.level.block.SugarCaneBlock
+ net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$1
+ net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SupportType$3
+ net.minecraft.world.level.block.SuspiciousEffectHolder
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TorchflowerCropBlock
+ net.minecraft.world.level.block.TransparentBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TrialSpawnerBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVinesBlock
- net.minecraft.world.level.block.TwistingVinesPlantBlock
+ net.minecraft.world.level.block.VaultBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallHangingSignBlock
- net.minecraft.world.level.block.WallHangingSignBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WaterloggedTransparentBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperBulbBlock
+ net.minecraft.world.level.block.WeatheringCopperDoorBlock
- net.minecraft.world.level.block.WeatheringCopperFullBlock
+ net.minecraft.world.level.block.WeatheringCopperGrateBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
- net.minecraft.world.level.block.WeatheringCopperTrapDoorBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockCollisions
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.BlockColumn
- net.minecraft.world.level.chunk.BulkSectionAccess
+ net.minecraft.world.level.chunk.CarvingMask
- net.minecraft.world.level.chunk.CarvingMask$Mask
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
+ net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkGenerators
- net.minecraft.world.level.chunk.ChunkGeneratorStructureState
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$1
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunk$PostLoadProcessor
+ net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LevelChunkSection$1BlockCounter
- net.minecraft.world.level.chunk.LightChunk
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.MissingPaletteEntryException
- net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.Palette$Factory
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$Configuration
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PalettedContainer$Data
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
- net.minecraft.world.level.chunk.PalettedContainerRO
+ net.minecraft.world.level.chunk.PalettedContainerRO$PackedData
- net.minecraft.world.level.chunk.PalettedContainerRO$Unpacker
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.SingleValuePalette
+ net.minecraft.world.level.chunk.status.ChunkStatus
- net.minecraft.world.level.chunk.status.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.status.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.status.ChunkStatusTasks
+ net.minecraft.world.level.chunk.status.ChunkType
- net.minecraft.world.level.chunk.status.package-info
- net.minecraft.world.level.chunk.status.ToFullChunk
+ net.minecraft.world.level.chunk.status.WorldGenContext
+ net.minecraft.world.level.chunk.storage.ChunkScanAccess
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkSerializer$ChunkReadException
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RecreatingChunkStorage
- net.minecraft.world.level.chunk.storage.RecreatingSimpleRegionStorage
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.RegionStorageInfo
+ net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.storage.SimpleRegionStorage
+ net.minecraft.world.level.chunk.StructureAccess
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.dimension.BuiltinDimensionTypes
+ net.minecraft.world.level.dimension.DimensionDefaults
- net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.DimensionType$MonsterSettings
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.EndDragonFight$Data
+ net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
- net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.entity.ChunkEntities
- net.minecraft.world.level.entity.ChunkStatusUpdateListener
+ net.minecraft.world.level.entity.EntityAccess
- net.minecraft.world.level.entity.EntityInLevelCallback
+ net.minecraft.world.level.entity.EntityInLevelCallback$1
- net.minecraft.world.level.entity.EntityLookup
+ net.minecraft.world.level.entity.EntityPersistentStorage
- net.minecraft.world.level.entity.EntitySection
+ net.minecraft.world.level.entity.EntitySectionStorage
- net.minecraft.world.level.entity.EntityTickList
+ net.minecraft.world.level.entity.EntityTypeTest
- net.minecraft.world.level.entity.EntityTypeTest$1
+ net.minecraft.world.level.entity.EntityTypeTest$2
- net.minecraft.world.level.entity.LevelCallback
+ net.minecraft.world.level.entity.LevelEntityGetter
- net.minecraft.world.level.entity.LevelEntityGetterAdapter
+ net.minecraft.world.level.entity.package-info
+ net.minecraft.world.level.entity.PersistentEntitySectionManager
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager
+ net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
- net.minecraft.world.level.entity.Visibility
+ net.minecraft.world.level.EntityBasedExplosionDamageCalculator
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.ExplosionDamageCalculator
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.gameevent.BlockPositionSource
+ net.minecraft.world.level.gameevent.BlockPositionSource$Type
- net.minecraft.world.level.gameevent.DynamicGameEventListener
+ net.minecraft.world.level.gameevent.EntityPositionSource
- net.minecraft.world.level.gameevent.EntityPositionSource$Type
+ net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
+ net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEvent$Context
+ net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
- net.minecraft.world.level.gameevent.GameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
+ net.minecraft.world.level.gameevent.GameEventListener$Provider
- net.minecraft.world.level.gameevent.GameEventListenerRegistry
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$ListenerVisitor
+ net.minecraft.world.level.gameevent.package-info
+ net.minecraft.world.level.gameevent.PositionSource
- net.minecraft.world.level.gameevent.PositionSourceType
+ net.minecraft.world.level.gameevent.vibrations.package-info
- net.minecraft.world.level.gameevent.vibrations.VibrationInfo
+ net.minecraft.world.level.gameevent.vibrations.VibrationSelector
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Data
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Ticker
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
- net.minecraft.world.level.GameRules
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
- net.minecraft.world.level.Level$2
+ net.minecraft.world.level.Level$ExplosionInteraction
- net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.Aquifer
+ net.minecraft.world.level.levelgen.Aquifer$1
- net.minecraft.world.level.levelgen.Aquifer$FluidPicker
+ net.minecraft.world.level.levelgen.Aquifer$FluidStatus
- net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
+ net.minecraft.world.level.levelgen.Beardifier
- net.minecraft.world.level.levelgen.Beardifier$1
+ net.minecraft.world.level.levelgen.Beardifier$Rigid
- net.minecraft.world.level.levelgen.BelowZeroRetrogen
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
- net.minecraft.world.level.levelgen.BitRandomSource
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
+ net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
- net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
+ net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
- net.minecraft.world.level.levelgen.blending.BlendingData
+ net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
- net.minecraft.world.level.levelgen.blending.package-info
+ net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
+ net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
- net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.package-info
- net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
- net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CarverDebugSettings
+ net.minecraft.world.level.levelgen.carver.CarvingContext
- net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CaveWorldCarver
- net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
+ net.minecraft.world.level.levelgen.carver.NetherWorldCarver
- net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.WorldCarver
+ net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
+ net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Line
+ net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Density
+ net.minecraft.world.level.levelgen.DensityFunction
- net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
+ net.minecraft.world.level.levelgen.DensityFunction$FunctionContext
- net.minecraft.world.level.levelgen.DensityFunction$NoiseHolder
+ net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
- net.minecraft.world.level.levelgen.DensityFunction$SinglePointContext
+ net.minecraft.world.level.levelgen.DensityFunction$Visitor
- net.minecraft.world.level.levelgen.DensityFunctions
+ net.minecraft.world.level.levelgen.DensityFunctions$1
- net.minecraft.world.level.levelgen.DensityFunctions$Ap2
+ net.minecraft.world.level.levelgen.DensityFunctions$BeardifierMarker
- net.minecraft.world.level.levelgen.DensityFunctions$BeardifierOrMarker
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendAlpha
- net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendOffset
- net.minecraft.world.level.levelgen.DensityFunctions$Clamp
+ net.minecraft.world.level.levelgen.DensityFunctions$Constant
- net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ net.minecraft.world.level.levelgen.DensityFunctions$HolderHolder
- net.minecraft.world.level.levelgen.DensityFunctions$Mapped
+ net.minecraft.world.level.levelgen.DensityFunctions$Mapped$Type
- net.minecraft.world.level.levelgen.DensityFunctions$Marker
+ net.minecraft.world.level.levelgen.DensityFunctions$Marker$Type
- net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked
+ net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd
- net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$Noise
- net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer
+ net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice
- net.minecraft.world.level.levelgen.DensityFunctions$Shift
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftA
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftB
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftedNoise
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftNoise
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline
- net.minecraft.world.level.levelgen.DensityFunctions$Spline$Coordinate
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline$Point
- net.minecraft.world.level.levelgen.DensityFunctions$TransformerWithContext
+ net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
- net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
+ net.minecraft.world.level.levelgen.DensityFunctions$YClampedGradient
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockColumnFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
- net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
- net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DeltaFeature
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
- net.minecraft.world.level.levelgen.feature.DripstoneUtils
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$1
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$LevelData
+ net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
+ net.minecraft.world.level.levelgen.feature.featuresize.package-info
+ net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.CherryFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageSetter
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.GeodeFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature$Configuration
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.MultifaceGrowthFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.OreFeature
- net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.rootplacers.AboveRootPlacement
- net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacement
+ net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacer
- net.minecraft.world.level.levelgen.feature.rootplacers.package-info
- net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacer
+ net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacerType
- net.minecraft.world.level.levelgen.feature.RootSystemFeature
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.feature.SculkPatchFeature
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider$Rule
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.AttachedToLeavesDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator$Context
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.TreeFeature$1
- net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.CherryTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
- net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPreset
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.FlatLevelSource
+ net.minecraft.world.level.levelgen.GenerationStep
- net.minecraft.world.level.levelgen.GenerationStep$Carving
+ net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.GeodeBlockSettings
+ net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.GeodeLayerSettings
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
+ net.minecraft.world.level.levelgen.heightproviders.HeightProvider
- net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
+ net.minecraft.world.level.levelgen.heightproviders.package-info
+ net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
- net.minecraft.world.level.levelgen.heightproviders.UniformHeight
+ net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
- net.minecraft.world.level.levelgen.LegacyRandomSource
+ net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
- net.minecraft.world.level.levelgen.material.MaterialRuleList
- net.minecraft.world.level.levelgen.material.package-info
+ net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$1
- net.minecraft.world.level.levelgen.NoiseChunk$2
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
- net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
- net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
+ net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.NoiseRouter
- net.minecraft.world.level.levelgen.NoiseRouterData
+ net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.Noises
- net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.OreVeinifier
+ net.minecraft.world.level.levelgen.OreVeinifier$VeinType
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.placement.BiomeFilter
+ net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
- net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
+ net.minecraft.world.level.levelgen.placement.CaveSurface
- net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
+ net.minecraft.world.level.levelgen.placement.CountPlacement
- net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
- net.minecraft.world.level.levelgen.placement.HeightmapPlacement
+ net.minecraft.world.level.levelgen.placement.HeightRangePlacement
+ net.minecraft.world.level.levelgen.placement.InSquarePlacement
- net.minecraft.world.level.levelgen.placement.NoiseBasedCountPlacement
+ net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
- net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.PlacedFeature
+ net.minecraft.world.level.levelgen.placement.PlacementContext
- net.minecraft.world.level.levelgen.placement.PlacementFilter
+ net.minecraft.world.level.levelgen.placement.PlacementModifier
- net.minecraft.world.level.levelgen.placement.PlacementModifierType
+ net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
- net.minecraft.world.level.levelgen.placement.RarityFilter
+ net.minecraft.world.level.levelgen.placement.RepeatingPlacement
- net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdFilter
+ net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
- net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.presets.package-info
+ net.minecraft.world.level.levelgen.presets.WorldPreset
- net.minecraft.world.level.levelgen.presets.WorldPresets
+ net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
+ net.minecraft.world.level.levelgen.RandomState
- net.minecraft.world.level.levelgen.RandomState$1
+ net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
- net.minecraft.world.level.levelgen.RandomSupport
+ net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuiltinStructures
+ net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
- net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.pieces.package-info
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
+ net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
- net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
- net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.package-info
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.pools.alias.Direct
+ net.minecraft.world.level.levelgen.structure.pools.alias.package-info
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBinding
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBindings
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasLookup
+ net.minecraft.world.level.levelgen.structure.pools.alias.Random
- net.minecraft.world.level.levelgen.structure.pools.alias.RandomGroup
- net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
- net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
- net.minecraft.world.level.levelgen.structure.pools.package-info
- net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
+ net.minecraft.world.level.levelgen.structure.Structure
- net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
- net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
+ net.minecraft.world.level.levelgen.structure.StructureCheck
- net.minecraft.world.level.levelgen.structure.StructureCheckResult
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.structures.IglooStructure
+ net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure$1
+ net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
+ net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$1
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCrossing
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftRoom
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeCrossing
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeStraight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleStalkRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$NetherBridgePiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentBuilding
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$RoomDefinition
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.package-info
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$Properties
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
+ net.minecraft.world.level.levelgen.structure.structures.SwampHutPiece
- net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
- net.minecraft.world.level.levelgen.structure.StructureSet
+ net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureType
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.CappedProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProtectedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendLoot
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendStatic
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Clear
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Passthrough
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifier
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifierType
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
- net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.TerrainAdjustment
+ net.minecraft.world.level.levelgen.SurfaceRules
- net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Condition
- net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Context
- net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Hole
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$StateRule
- net.minecraft.world.level.levelgen.SurfaceRules$Steep
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
- net.minecraft.world.level.levelgen.SurfaceRules$Temperature
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRule
- net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ net.minecraft.world.level.levelgen.SurfaceSystem
- net.minecraft.world.level.levelgen.SurfaceSystem$1
+ net.minecraft.world.level.levelgen.synth.BlendedNoise
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NoiseUtils
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
+ net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
- net.minecraft.world.level.levelgen.VerticalAnchor
+ net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
- net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
+ net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
- net.minecraft.world.level.levelgen.WorldDimensions
+ net.minecraft.world.level.levelgen.WorldDimensions$1Entry
- net.minecraft.world.level.levelgen.WorldDimensions$Complete
- net.minecraft.world.level.levelgen.WorldGenerationContext
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
+ net.minecraft.world.level.levelgen.WorldOptions
- net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelHeightAccessor$1
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.ChunkSkyLightSources
- net.minecraft.world.level.lighting.DataLayerStorageMap
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
+ net.minecraft.world.level.lighting.LayerLightEventListener
- net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ net.minecraft.world.level.lighting.LayerLightSectionStorage
- net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionState
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionType
+ net.minecraft.world.level.lighting.LeveledPriorityQueue
- net.minecraft.world.level.lighting.LeveledPriorityQueue$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEngine
- net.minecraft.world.level.lighting.LightEngine$QueueEntry
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightEngine$1
- net.minecraft.world.level.lighting.SkyLightSectionStorage
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.material.FogType
- net.minecraft.world.level.material.LavaFluid
+ net.minecraft.world.level.material.LavaFluid$Flowing
- net.minecraft.world.level.material.LavaFluid$Source
+ net.minecraft.world.level.material.MapColor
- net.minecraft.world.level.material.MapColor$Brightness
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.Path$DebugData
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.PathfindingContext
- net.minecraft.world.level.pathfinder.PathType
+ net.minecraft.world.level.pathfinder.PathTypeCache
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator$1
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.redstone.CollectingNeighborUpdater
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- net.minecraft.world.level.redstone.InstantNeighborUpdater
+ net.minecraft.world.level.redstone.NeighborUpdater
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapDecorationTypes
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.saveddata.SavedData$Factory
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.SignalGetter
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.SpawnData$CustomSpawnRules
+ net.minecraft.world.level.Spawner
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Path
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead
+ net.minecraft.world.level.storage.loot.functions.FunctionReference
- net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
+ net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.ListOperation
+ net.minecraft.world.level.storage.loot.functions.ListOperation$Append
- net.minecraft.world.level.storage.loot.functions.ListOperation$Insert
+ net.minecraft.world.level.storage.loot.functions.ListOperation$ReplaceAll
- net.minecraft.world.level.storage.loot.functions.ListOperation$ReplaceSection
+ net.minecraft.world.level.storage.loot.functions.ListOperation$Type
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
+ net.minecraft.world.level.storage.loot.functions.SequenceFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetBookCoverFunction
+ net.minecraft.world.level.storage.loot.functions.SetComponentsFunction
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetCustomDataFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetFireworkExplosionFunction
+ net.minecraft.world.level.storage.loot.functions.SetFireworksFunction
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetPotionFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
- net.minecraft.world.level.storage.loot.functions.SetWritableBookPagesFunction
+ net.minecraft.world.level.storage.loot.functions.SetWrittenBookPagesFunction
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.functions.ToggleTooltips$ComponentToggle
+ net.minecraft.world.level.storage.loot.LootDataManager
+ net.minecraft.world.level.storage.loot.LootDataResolver
+ net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
+ net.minecraft.world.level.storage.loot.providers.score.package-info
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
- net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.StructureManager
+ net.minecraft.world.level.timers.FunctionCallback
- net.minecraft.world.level.timers.FunctionCallback$Serializer
+ net.minecraft.world.level.timers.FunctionTagCallback
- net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.package-info
+ net.minecraft.world.level.timers.TimerCallback
- net.minecraft.world.level.timers.TimerCallback$Serializer
+ net.minecraft.world.level.timers.TimerCallbacks
- net.minecraft.world.level.timers.TimerQueue
+ net.minecraft.world.level.timers.TimerQueue$Event
+ net.minecraft.world.level.validation.ContentValidationException
- net.minecraft.world.level.validation.DirectoryValidator
+ net.minecraft.world.level.validation.DirectoryValidator$1
- net.minecraft.world.level.validation.ForbiddenSymlinkInfo
- net.minecraft.world.level.validation.package-info
+ net.minecraft.world.level.validation.PathAllowList
- net.minecraft.world.level.validation.PathAllowList$ConfigEntry
+ net.minecraft.world.level.validation.PathAllowList$EntryType
+ net.minecraft.world.level.WorldDataConfiguration
- net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.package-info
- net.minecraft.world.phys.AABB
+ net.minecraft.world.phys.BlockHitResult
- net.minecraft.world.phys.EntityHitResult
+ net.minecraft.world.phys.HitResult
- net.minecraft.world.phys.HitResult$Type
+ net.minecraft.world.phys.package-info
- net.minecraft.world.phys.shapes.ArrayVoxelShape
+ net.minecraft.world.phys.shapes.ArrayVoxelShape$1
- net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
+ net.minecraft.world.phys.shapes.BooleanOp
- net.minecraft.world.phys.shapes.CollisionContext
+ net.minecraft.world.phys.shapes.CubePointRange
- net.minecraft.world.phys.shapes.CubeVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteCubeMerger
- net.minecraft.world.phys.shapes.DiscreteVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ net.minecraft.world.phys.shapes.EntityCollisionContext
- net.minecraft.world.phys.shapes.EntityCollisionContext$1
+ net.minecraft.world.phys.shapes.IdenticalMerger
- net.minecraft.world.phys.shapes.IndexMerger
+ net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
- net.minecraft.world.phys.shapes.IndirectMerger
+ net.minecraft.world.phys.shapes.NonOverlappingMerger
- net.minecraft.world.phys.shapes.OffsetDoubleList
- net.minecraft.world.phys.shapes.package-info
+ net.minecraft.world.phys.shapes.Shapes
- net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
+ net.minecraft.world.phys.shapes.SliceShape
- net.minecraft.world.phys.shapes.SubShape
+ net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.phys.Vec2
- net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
+ net.minecraft.world.scores.DisplaySlot
- net.minecraft.world.scores.DisplaySlot$1
+ net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
- net.minecraft.world.scores.PlayerScoreEntry
+ net.minecraft.world.scores.PlayerScores
- net.minecraft.world.scores.PlayerTeam
+ net.minecraft.world.scores.ReadOnlyScoreInfo
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.ScoreAccess
- net.minecraft.world.scores.Scoreboard
+ net.minecraft.world.scores.Scoreboard$1
- net.minecraft.world.scores.ScoreboardSaveData
- net.minecraft.world.scores.ScoreHolder
+ net.minecraft.world.scores.ScoreHolder$1
- net.minecraft.world.scores.ScoreHolder$2
+ net.minecraft.world.scores.ScoreHolder$3
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
- net.minecraft.world.ticks.BlackholeTickAccess
+ net.minecraft.world.ticks.BlackholeTickAccess$1
- net.minecraft.world.ticks.BlackholeTickAccess$2
+ net.minecraft.world.ticks.ContainerSingleItem
- net.minecraft.world.ticks.ContainerSingleItem$BlockContainerSingleItem
+ net.minecraft.world.ticks.LevelChunkTicks
- net.minecraft.world.ticks.LevelTickAccess
+ net.minecraft.world.ticks.LevelTicks
- net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
+ net.minecraft.world.ticks.package-info
+ net.minecraft.world.ticks.ProtoChunkTicks
- net.minecraft.world.ticks.SavedTick
+ net.minecraft.world.ticks.SavedTick$1
- net.minecraft.world.ticks.ScheduledTick
+ net.minecraft.world.ticks.ScheduledTick$1
- net.minecraft.world.ticks.SerializableTickContainer
+ net.minecraft.world.ticks.TickAccess
- net.minecraft.world.ticks.TickContainerAccess
+ net.minecraft.world.ticks.TickPriority
- net.minecraft.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +1M
```
```
XXX.minecraft.advancements.Advancement +2M -2M
```
```
XXX.minecraft.advancements.AdvancementRewards$Builder +2M -2M
```
```
XXX.minecraft.advancements.CriteriaTriggers +2P
```
```
XXX.advancements.critereon.LootTableTrigger +2M -2M
```
```
XXX.advancements.critereon.NbtPredicate +2P
```
```
XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance +1M
```
```
XXX.commands.arguments.NbtPathArgument$NbtPath +7M -3M | +1P
```
```
XXX.commands.arguments.ResourceLocationArgument +1M -5M | -2P
```
```
XXX.arguments.item.ItemParser +6M | +12P -1P
```
```
XXX.selector.options.EntitySelectorOptions +1M -1M
```
```
XXX.minecraft.core.HolderSet +1M
```
```
XXX.minecraft.core.HolderSet$Direct +1M | +1P
```
```
XXX.minecraft.server.ReloadableServerResources +7M -6M | +1P -1P
```
```
XXX.minecraft.server.ServerAdvancementManager +1M -1M | -1P
```
```
XXX.minecraft.server.WorldLoader +1M -1M
```
```
XXX.minecraft.tags.EntityTypeTags +1P
```
```
XXX.minecraft.tags.StructureTags +1P
```
```
XXX.minecraft.world.RandomizableContainer +2M -2M | +2P -2P
```
```
XXX.world.entity.EntityType +1M -1M | +1P -1P
```
```
XXX.world.entity.LivingEntity +2M -2M | +1P -1P
```
```
XXX.world.entity.Mob +2M -2M | +1P -1P
```
```
XXX.entity.animal.Animal -1M | +1P
```
```
XXX.entity.animal.Cat +5M -4M | +1P -1P
```
```
XXX.entity.animal.FrogVariant +3M -1M | +3P -3P
```
```
XXX.entity.animal.Ocelot +1M | -1P
```
```
XXX.entity.animal.Ocelot$OcelotTemptGoal +1M -1M
```
```
XXX.entity.animal.Parrot -2P
```
```
XXX.entity.animal.Pig +2M | -1P
```
```
XXX.entity.animal.Rabbit +1M -1M
```
```
XXX.entity.animal.Turtle +1M | -1P
```
```
XXX.animal.armadillo.ArmadilloAi +2M -1M | -1P
```
```
XXX.animal.axolotl.AxolotlAi +2M -1M
```
```
XXX.animal.camel.Camel -1P
```
```
XXX.animal.camel.CamelAi +2M -1M
```
```
XXX.animal.frog.Frog +3M -2M | +1P -1P
```
```
XXX.animal.frog.FrogAi +2M -1M
```
```
XXX.animal.goat.GoatAi +2M -1M
```
```
XXX.animal.horse.AbstractHorse +1M | -1P
```
```
XXX.animal.horse.Llama +1M | -1P
```
```
XXX.animal.sniffer.SnifferAi +4M -3M
```
```
XXX.entity.monster.Strider +1M | -2P
```
```
XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds +1M -1M | +1P -1P
```
```
XXX.projectile.windcharge.AbstractWindCharge -1M
```
```
XXX.entity.vehicle.AbstractMinecartContainer +3M -3M | +1P -1P
```
```
XXX.world.food.FoodData +1M -1M
```
```
XXX.world.food.FoodProperties$Builder +2M -3M | +2P -3P
```
```
XXX.world.item.AdventureModePredicate +2M
```
```
XXX.world.item.Rarity +5M -1M | +5P
```
```
XXX.item.armortrim.ArmorTrim +5M -3M
```
```
XXX.item.armortrim.TrimMaterials +1M -1M
```
```
XXX.item.armortrim.TrimPatterns +1M -1M
```
```
XXX.item.component.MapDecorations$Entry +2M -2M | +1P -1P
```
```
XXX.item.component.SeededContainerLoot +2M -2M | +1P -1P
```
```
XXX.item.component.Unbreakable +1M
```
```
XXX.item.component.WrittenBookContent +2M | +1P -1P
```
```
XXX.item.crafting.BannerDuplicateRecipe +2M -2M
```
```
XXX.item.crafting.BookCloningRecipe +2M -2M
```
```
XXX.item.crafting.DecoratedPotRecipe +2M -2M
```
```
XXX.item.crafting.FireworkStarFadeRecipe +2M -2M
```
```
XXX.item.crafting.MapCloningRecipe +2M -2M
```
```
XXX.item.crafting.Recipe +2P -2P
```
```
XXX.item.crafting.RecipeCache$Entry +2M -2M | +1P -1P
```
```
XXX.item.crafting.RepairItemRecipe +5M -3M
```
```
XXX.item.crafting.ShulkerBoxColoring +2M -2M
```
```
XXX.item.crafting.SingleItemRecipe +2M -2M
```
```
XXX.item.crafting.TippedArrowRecipe +2M -2M
```
```
XXX.item.enchantment.ArrowInfiniteEnchantment +1M -3M
```
```
XXX.item.enchantment.MendingEnchantment +1M -3M
```
```
XXX.item.enchantment.SoulSpeedEnchantment +1M -4M
```
```
XXX.item.enchantment.UntouchingEnchantment +1M -3M
```
```
XXX.item.enchantment.WaterWalkerEnchantment +1M -4M
```
```
XXX.saveddata.maps.MapItemSavedData +2M -2M
```
```
XXX.storage.loot.BuiltInLootTables +2M -2M | +103P -103P
```
```
XXX.storage.loot.LootContext +2M -2M | +1P -1P
```
```
XXX.storage.loot.LootDataType$Validator +1P -1P
```
```
XXX.storage.loot.LootTable +1P
```
```
XXX.storage.loot.ValidationContext +5M -5M | +1P -1P
```
```
XXX.loot.entries.NestedLootTable +6M -6M
```
```
XXX.loot.predicates.LootItemConditions +1P
```

</details>
















<details>
<summary>
net.minecraft.Util
</summary>

```diff
- List copyAndAdd(Object,List)
```

</details>






<details>
<summary>
net.minecraft.advancements.Advancement
</summary>

```diff
- void lambda$validate$9(ProblemReporter,HolderGetter$Provider,String,Criterion)
+ void lambda$validate$9(ProblemReporter,LootDataResolver,String,Criterion)
- void validate(ProblemReporter,HolderGetter$Provider)
+ void validate(ProblemReporter,LootDataResolver)
```

</details>



<details>
<summary>
net.minecraft.advancements.AdvancementRewards$Builder
</summary>

```diff
- AdvancementRewards$Builder addLootTable(ResourceKey)
+ AdvancementRewards$Builder addLootTable(ResourceLocation)
- AdvancementRewards$Builder loot(ResourceKey)
+ AdvancementRewards$Builder loot(ResourceLocation)
```

</details>



















































<details>
<summary>
net.minecraft.advancements.critereon.LootTableTrigger
</summary>

```diff
- boolean lambda$trigger$0(ResourceKey,LootTableTrigger$TriggerInstance)
+ boolean lambda$trigger$0(ResourceLocation,LootTableTrigger$TriggerInstance)
- void trigger(ServerPlayer,ResourceKey)
+ void trigger(ServerPlayer,ResourceLocation)
```

</details>












<details>
<summary>
net.minecraft.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
</summary>

```diff
- Criterion crafterCraftedItem(ResourceLocation)
```

</details>












































<details>
<summary>
net.minecraft.commands.arguments.NbtPathArgument$NbtPath
</summary>

```diff
- DataResult lambda$static$1(String)
+ Integer lambda$apply$0(Integer,Integer)
- Integer lambda$apply$2(Integer,Integer)
+ Integer lambda$set$2(NbtPathArgument$Node,MutableBoolean,Tag,Tag)
- Integer lambda$set$4(NbtPathArgument$Node,MutableBoolean,Tag,Tag)
- NbtPathArgument$NbtPath of(String)
- String lambda$static$0(String,CommandSyntaxException)
+ Tag lambda$set$1(MutableBoolean,Tag)
- Tag lambda$set$3(MutableBoolean,Tag)
- void <clinit>()
```

</details>








<details>
<summary>
net.minecraft.commands.arguments.ResourceLocationArgument
</summary>

```diff
- CommandSyntaxException lambda$getRecipe$2(ResourceLocation)
+ CommandSyntaxException lambda$getRecipe$4(ResourceLocation)
+ LootItemCondition getPredicate(CommandContext,String)
+ LootItemFunction getItemModifier(CommandContext,String)
+ Message lambda$static$2(Object)
+ Message lambda$static$3(Object)
```

</details>




























<details>
<summary>
net.minecraft.commands.arguments.item.ItemParser
</summary>

```diff
- Message lambda$static$0(Object)
- Message lambda$static$1(Object)
- Message lambda$static$2(Object,Object)
- Message lambda$static$3(Object)
- void <clinit>()
- void parse(StringReader,ItemParser$Visitor)
```

</details>




<details>
<summary>
net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
</summary>

```diff
- boolean lambda$bootStrap$61(ResourceKey,boolean,Entity)
+ boolean lambda$bootStrap$61(ResourceLocation,boolean,Entity)
```

</details>






















































<details>
<summary>
net.minecraft.core.HolderSet
</summary>

```diff
- HolderSet empty()
```

</details>
<details>
<summary>
net.minecraft.core.HolderSet$Direct
</summary>

```diff
- void <clinit>()
```

</details>




























































































































<details>
<summary>
net.minecraft.server.ReloadableServerResources
</summary>

```diff
- CompletableFuture loadResources(ResourceManager,LayeredRegistryAccess,FeatureFlagSet,Commands$CommandSelection,int,Executor,Executor)
+ CompletableFuture loadResources(ResourceManager,RegistryAccess$Frozen,FeatureFlagSet,Commands$CommandSelection,int,Executor,Executor)
- CompletionStage lambda$loadResources$2(FeatureFlagSet,Commands$CommandSelection,int,ResourceManager,Executor,Executor,LayeredRegistryAccess)
+ List lambda$updateRegistryTags$4(Map$Entry)
- List lambda$updateRegistryTags$5(Map$Entry)
+ LootDataManager getLootData()
- ReloadableServerRegistries$Holder fullRegistries()
+ TagKey lambda$updateRegistryTags$3(ResourceKey,Map$Entry)
- TagKey lambda$updateRegistryTags$4(ResourceKey,Map$Entry)
+ void lambda$updateRegistryTags$2(RegistryAccess,TagManager$LoadResult)
- void lambda$updateRegistryTags$3(TagManager$LoadResult)
- void updateRegistryTags()
+ void updateRegistryTags(RegistryAccess)
```

</details>


<details>
<summary>
net.minecraft.server.ServerAdvancementManager
</summary>

```diff
+ void <init>(HolderLookup$Provider,LootDataManager)
- void <init>(HolderLookup$Provider)
```

</details>




<details>
<summary>
net.minecraft.server.WorldLoader
</summary>

```diff
+ Object lambda$load$1(RegistryAccess$Frozen,WorldLoader$ResultFactory,CloseableResourceManager,LayeredRegistryAccess,WorldLoader$DataLoadOutput,ReloadableServerResources)
- Object lambda$load$1(WorldLoader$ResultFactory,CloseableResourceManager,LayeredRegistryAccess,WorldLoader$DataLoadOutput,ReloadableServerResources)
```

</details>









































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.RandomizableContainer
</summary>

```diff
- void setBlockEntityLootTable(BlockGetter,RandomSource,BlockPos,ResourceKey)
+ void setBlockEntityLootTable(BlockGetter,RandomSource,BlockPos,ResourceLocation)
- void setLootTable(ResourceKey,long)
+ void setLootTable(ResourceLocation,long)
```

</details>







































<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
- ResourceKey getDefaultLootTable()
+ ResourceLocation getDefaultLootTable()
```

</details>








<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- ResourceKey getLootTable()
+ ResourceLocation getLootTable()
- void addEatEffect(FoodProperties)
+ void addEatEffect(ItemStack,Level,LivingEntity)
```

</details>

<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- ResourceKey getDefaultLootTable()
- ResourceKey getLootTable()
+ ResourceLocation getDefaultLootTable()
+ ResourceLocation getLootTable()
```

</details>

















































































































































































<details>
<summary>
net.minecraft.world.entity.animal.Animal
</summary>

```diff
+ boolean isFood(ItemStack)
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.Cat
</summary>

```diff
- boolean lambda$registerGoals$0(ItemStack)
+ CatVariant getVariant()
- Holder getVariant()
- ResourceKey lambda$readAdditionalSaveData$1(ResourceLocation)
+ ResourceLocation getResourceLocation()
- ResourceLocation getTextureId()
+ void lambda$finalizeSpawn$0(Holder)
+ void setVariant(CatVariant)
- void setVariant(Holder)
```

</details>

















<details>
<summary>
net.minecraft.world.entity.animal.FrogVariant
</summary>

```diff
- FrogVariant bootstrap(Registry)
- FrogVariant register(Registry,ResourceKey,String)
+ FrogVariant register(String,String)
- ResourceKey createKey(String)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
- boolean lambda$registerGoals$0(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
</summary>

```diff
+ void <init>(Ocelot,double,Ingredient,boolean)
- void <init>(Ocelot,double,Predicate,boolean)
```

</details>








<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
- boolean lambda$registerGoals$0(ItemStack)
- boolean lambda$registerGoals$1(ItemStack)
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
+ boolean isTemptingItem(ItemStack)
- boolean lambda$registerGoals$0(ItemStack)
```

</details>










<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
- boolean lambda$registerGoals$1(ItemStack)
```

</details>














<details>
<summary>
net.minecraft.world.entity.animal.armadillo.ArmadilloAi
</summary>

```diff
- boolean lambda$getTemptations$5(ItemStack)
+ Ingredient getTemptations()
- Predicate getTemptations()
```

</details>




<details>
<summary>
net.minecraft.world.entity.animal.axolotl.AxolotlAi
</summary>

```diff
- boolean lambda$getTemptations$0(ItemStack)
+ Ingredient getTemptations()
- Predicate getTemptations()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.camel.CamelAi
</summary>

```diff
- boolean lambda$getTemptations$2(ItemStack)
+ Ingredient getTemptations()
- Predicate getTemptations()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.frog.Frog
</summary>

```diff
+ FrogVariant getVariant()
- Holder getVariant()
- ResourceKey lambda$readAdditionalSaveData$0(ResourceLocation)
+ void setVariant(FrogVariant)
- void setVariant(Holder)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.frog.FrogAi
</summary>

```diff
- boolean lambda$getTemptations$6(ItemStack)
+ Ingredient getTemptations()
- Predicate getTemptations()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.goat.GoatAi
</summary>

```diff
- boolean lambda$getTemptations$9(ItemStack)
+ Ingredient getTemptations()
- Predicate getTemptations()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- boolean lambda$addBehaviourGoals$7(ItemStack)
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- boolean lambda$registerGoals$0(ItemStack)
```

</details>








<details>
<summary>
net.minecraft.world.entity.animal.sniffer.SnifferAi
</summary>

```diff
- boolean lambda$getTemptations$0(ItemStack)
+ Double lambda$initIdleActivity$1(LivingEntity)
- Double lambda$initIdleActivity$2(LivingEntity)
+ Float lambda$initIdleActivity$0(LivingEntity)
- Float lambda$initIdleActivity$1(LivingEntity)
+ Ingredient getTemptations()
- Predicate getTemptations()
```

</details>






































































<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
- boolean lambda$registerGoals$0(ItemStack)
```

</details>







































<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
</summary>

```diff
- void <init>(int,TagKey,String,Holder,int,int)
+ void <init>(int,TagKey,String,MapDecoration$Type,int,int)
```

</details>



























<details>
<summary>
net.minecraft.world.entity.projectile.windcharge.AbstractWindCharge
</summary>

```diff
+ ClipContext$Block getClipType()
```

</details>












<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecartContainer
</summary>

```diff
- ResourceKey getLootTable()
+ ResourceLocation getLootTable()
- void setLootTable(ResourceKey,long)
- void setLootTable(ResourceKey)
+ void setLootTable(ResourceLocation,long)
+ void setLootTable(ResourceLocation)
```

</details>














<details>
<summary>
net.minecraft.world.food.FoodData
</summary>

```diff
+ void eat(Item,ItemStack)
- void eat(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.food.FoodProperties$Builder
</summary>

```diff
+ FoodProperties$Builder alwaysEat()
- FoodProperties$Builder alwaysEdible()
+ FoodProperties$Builder meat()
+ FoodProperties$Builder saturationMod(float)
- FoodProperties$Builder saturationModifier(float)
```

</details>

















































<details>
<summary>
net.minecraft.world.item.AdventureModePredicate
</summary>

```diff
- AdventureModePredicate withTooltip(boolean)
- void <init>(List,boolean,List)
```

</details>
















































<details>
<summary>
net.minecraft.world.item.Rarity
</summary>

```diff
- ChatFormatting color()
- int lambda$static$0(Rarity)
- int lambda$static$1(Rarity)
- String getSerializedName()
+ void <init>(String,int,ChatFormatting)
- void <init>(String,int,int,String,ChatFormatting)
```

</details>


















<details>
<summary>
net.minecraft.world.item.armortrim.ArmorTrim
</summary>

```diff
- ArmorTrim withTooltip(boolean)
- ResourceLocation lambda$new$4(Holder,Holder,Holder)
+ ResourceLocation lambda$new$4(Holder,Holder)
- ResourceLocation lambda$new$6(Holder,Holder,Holder)
+ ResourceLocation lambda$new$6(Holder,Holder)
- String getColorPaletteSuffix(Holder,Holder)
+ String getColorPaletteSuffix(Holder)
- void <init>(Holder,Holder,boolean,Function,Function)
```

</details>
<details>
<summary>
net.minecraft.world.item.armortrim.TrimMaterials
</summary>

```diff
- Optional getFromIngredient(HolderLookup$Provider,ItemStack)
+ Optional getFromIngredient(RegistryAccess,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.armortrim.TrimPatterns
</summary>

```diff
- Optional getFromTemplate(HolderLookup$Provider,ItemStack)
+ Optional getFromTemplate(RegistryAccess,ItemStack)
```

</details>











<details>
<summary>
net.minecraft.world.item.component.MapDecorations$Entry
</summary>

```diff
- Holder type()
+ MapDecoration$Type type()
- void <init>(Holder,double,double,float)
+ void <init>(MapDecoration$Type,double,double,float)
```

</details>

<details>
<summary>
net.minecraft.world.item.component.SeededContainerLoot
</summary>

```diff
- ResourceKey lootTable()
+ ResourceLocation lootTable()
- void <init>(ResourceKey,long)
+ void <init>(ResourceLocation,long)
```

</details>

<details>
<summary>
net.minecraft.world.item.component.Unbreakable
</summary>

```diff
- Unbreakable withTooltip(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.WrittenBookContent
</summary>

```diff
- Codec pageCodec(Codec)
- Codec pagesCodec(Codec)
```

</details>




<details>
<summary>
net.minecraft.world.item.crafting.BannerDuplicateRecipe
</summary>

```diff
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,HolderLookup$Provider)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.BookCloningRecipe
</summary>

```diff
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,HolderLookup$Provider)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.DecoratedPotRecipe
</summary>

```diff
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,HolderLookup$Provider)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.FireworkStarFadeRecipe
</summary>

```diff
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,HolderLookup$Provider)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.MapCloningRecipe
</summary>

```diff
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,HolderLookup$Provider)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
```

</details>

<details>
<summary>
net.minecraft.world.item.crafting.RecipeCache$Entry
</summary>

```diff
+ CraftingRecipe value()
- RecipeHolder value()
+ void <init>(NonNullList,CraftingRecipe)
- void <init>(NonNullList,RecipeHolder)
```

</details>



<details>
<summary>
net.minecraft.world.item.crafting.RepairItemRecipe
</summary>

```diff
- boolean canCombine(ItemStack,ItemStack)
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,HolderLookup$Provider)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
- Pair getItemsToCombine(CraftingContainer)
- void lambda$assemble$1(HolderLookup$Provider,ItemEnchantments,ItemEnchantments,ItemEnchantments$Mutable)
+ void lambda$assemble$1(RegistryAccess,ItemEnchantments,ItemEnchantments,ItemEnchantments$Mutable)
```

</details>



<details>
<summary>
net.minecraft.world.item.crafting.ShulkerBoxColoring
</summary>

```diff
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,HolderLookup$Provider)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
```

</details>

<details>
<summary>
net.minecraft.world.item.crafting.SingleItemRecipe
</summary>

```diff
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack getResultItem(HolderLookup$Provider)
+ ItemStack getResultItem(RegistryAccess)
```

</details>





<details>
<summary>
net.minecraft.world.item.crafting.TippedArrowRecipe
</summary>

```diff
- ItemStack assemble(Container,HolderLookup$Provider)
+ ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,HolderLookup$Provider)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.MendingEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.SoulSpeedEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMaxLevel()
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.UntouchingEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.WaterWalkerEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMaxLevel()
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>

<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- void addDecoration(Holder,LevelAccessor,String,double,double,double,Component)
+ void addDecoration(MapDecoration$Type,LevelAccessor,String,double,double,double,Component)
- void addTargetDecoration(ItemStack,BlockPos,String,Holder)
+ void addTargetDecoration(ItemStack,BlockPos,String,MapDecoration$Type)
```

</details>















<details>
<summary>
net.minecraft.world.level.storage.loot.BuiltInLootTables
</summary>

```diff
- ResourceKey register(ResourceKey)
- ResourceKey register(String)
+ ResourceLocation register(ResourceLocation)
+ ResourceLocation register(String)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.LootContext
</summary>

```diff
- HolderGetter$Provider getResolver()
+ LootDataResolver getResolver()
- void <init>(LootParams,RandomSource,HolderGetter$Provider)
+ void <init>(LootParams,RandomSource,LootDataResolver)
```

</details>






<details>
<summary>
net.minecraft.world.level.storage.loot.ValidationContext
</summary>

```diff
+ boolean hasVisitedElement(LootDataId)
- boolean hasVisitedElement(ResourceKey)
- HolderGetter$Provider resolver()
+ LootDataResolver resolver()
+ ValidationContext enterElement(String,LootDataId)
- ValidationContext enterElement(String,ResourceKey)
- void <init>(ProblemReporter,LootContextParamSet,HolderGetter$Provider,Set)
- void <init>(ProblemReporter,LootContextParamSet,HolderGetter$Provider)
+ void <init>(ProblemReporter,LootContextParamSet,LootDataResolver,Set)
+ void <init>(ProblemReporter,LootContextParamSet,LootDataResolver)
```

</details>










<details>
<summary>
net.minecraft.world.level.storage.loot.entries.NestedLootTable
</summary>

```diff
- LootPoolSingletonContainer lambda$lootTableReference$8(ResourceKey,int,int,List,List)
+ LootPoolSingletonContainer lambda$lootTableReference$8(ResourceLocation,int,int,List,List)
- LootPoolSingletonContainer$Builder lootTableReference(ResourceKey)
+ LootPoolSingletonContainer$Builder lootTableReference(ResourceLocation)
- LootTable lambda$createItemStack$2(LootContext,ResourceKey)
+ LootTable lambda$createItemStack$2(LootContext,ResourceLocation)
- void lambda$validate$4(ValidationContext,ResourceKey,Holder$Reference)
+ void lambda$validate$4(ValidationContext,ResourceLocation,LootDataId,LootTable)
- void lambda$validate$5(ValidationContext,ResourceKey)
+ void lambda$validate$5(ValidationContext,ResourceLocation)
- void lambda$validate$6(ValidationContext,ResourceKey)
+ void lambda$validate$6(ValidationContext,ResourceLocation)
```

</details>








































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.advancements.critereon.EntitySubPredicates$EntityHolderVariantPredicateType
- net.minecraft.advancements.critereon.FallAfterExplosionTrigger$TriggerInstance
+ net.minecraft.client.resources.language.ClientLanguage
- net.minecraft.client.resources.language.FormattedBidiReorder
+ net.minecraft.client.resources.language.I18n
- net.minecraft.client.resources.language.LanguageInfo
+ net.minecraft.client.resources.language.LanguageManager
- net.minecraft.client.resources.language.package-info
+ net.minecraft.client.resources.metadata.animation.AnimationFrame
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$FrameOutput
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
- net.minecraft.client.resources.metadata.animation.FrameSize
- net.minecraft.client.resources.metadata.animation.package-info
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
+ net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.gui.GuiMetadataSection
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$NineSlice
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$NineSlice$Border
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Stretch
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Tile
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Type
- net.minecraft.client.resources.metadata.gui.package-info
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSection
- net.minecraft.client.resources.metadata.language.package-info
+ net.minecraft.client.resources.metadata.package-info
- net.minecraft.client.resources.metadata.texture.package-info
- net.minecraft.client.resources.metadata.texture.TextureMetadataSection
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
- net.minecraft.client.resources.MobEffectTextureManager
+ net.minecraft.client.resources.model.AtlasSet
- net.minecraft.client.resources.model.AtlasSet$AtlasEntry
+ net.minecraft.client.resources.model.AtlasSet$StitchResult
- net.minecraft.client.resources.model.BakedModel
+ net.minecraft.client.resources.model.BlockModelRotation
- net.minecraft.client.resources.model.BuiltInModel
+ net.minecraft.client.resources.model.Material
- net.minecraft.client.resources.model.ModelBaker
+ net.minecraft.client.resources.model.ModelBakery
- net.minecraft.client.resources.model.ModelBakery$BakedCacheKey
+ net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
- net.minecraft.client.resources.model.ModelBakery$LoadedJson
+ net.minecraft.client.resources.model.ModelBakery$ModelBakerImpl
- net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
+ net.minecraft.client.resources.model.ModelManager
- net.minecraft.client.resources.model.ModelManager$ReloadState
+ net.minecraft.client.resources.model.ModelResourceLocation
- net.minecraft.client.resources.model.ModelState
+ net.minecraft.client.resources.model.MultiPartBakedModel
- net.minecraft.client.resources.model.MultiPartBakedModel$Builder
- net.minecraft.client.resources.model.package-info
+ net.minecraft.client.resources.model.SimpleBakedModel
- net.minecraft.client.resources.model.SimpleBakedModel$Builder
+ net.minecraft.client.resources.model.UnbakedModel
- net.minecraft.client.resources.model.WeightedBakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel$Builder
+ net.minecraft.client.resources.package-info
+ net.minecraft.client.resources.PaintingTextureManager
- net.minecraft.client.resources.PlayerSkin
+ net.minecraft.client.resources.PlayerSkin$Model
- net.minecraft.client.resources.server.DownloadedPackSource
+ net.minecraft.client.resources.server.DownloadedPackSource$1
- net.minecraft.client.resources.server.DownloadedPackSource$2
+ net.minecraft.client.resources.server.DownloadedPackSource$3
- net.minecraft.client.resources.server.DownloadedPackSource$4
+ net.minecraft.client.resources.server.DownloadedPackSource$5
- net.minecraft.client.resources.server.DownloadedPackSource$6
+ net.minecraft.client.resources.server.DownloadedPackSource$7
- net.minecraft.client.resources.server.DownloadedPackSource$8
- net.minecraft.client.resources.server.package-info
+ net.minecraft.client.resources.server.PackDownloader
- net.minecraft.client.resources.server.PackLoadFeedback
+ net.minecraft.client.resources.server.PackLoadFeedback$FinalResult
- net.minecraft.client.resources.server.PackLoadFeedback$Update
+ net.minecraft.client.resources.server.PackReloadConfig
- net.minecraft.client.resources.server.PackReloadConfig$Callbacks
+ net.minecraft.client.resources.server.PackReloadConfig$IdAndPath
- net.minecraft.client.resources.server.ServerPackManager
+ net.minecraft.client.resources.server.ServerPackManager$1
- net.minecraft.client.resources.server.ServerPackManager$2
+ net.minecraft.client.resources.server.ServerPackManager$ActivationStatus
- net.minecraft.client.resources.server.ServerPackManager$PackDownloadStatus
+ net.minecraft.client.resources.server.ServerPackManager$PackPromptStatus
- net.minecraft.client.resources.server.ServerPackManager$RemovalReason
+ net.minecraft.client.resources.server.ServerPackManager$ServerPackData
- net.minecraft.client.resources.SkinManager
+ net.minecraft.client.resources.SkinManager$1
- net.minecraft.client.resources.SkinManager$2
+ net.minecraft.client.resources.SkinManager$CacheKey
- net.minecraft.client.resources.SkinManager$TextureCache
+ net.minecraft.client.resources.sounds.AbstractSoundInstance
- net.minecraft.client.resources.sounds.AbstractTickableSoundInstance
+ net.minecraft.client.resources.sounds.AmbientSoundHandler
- net.minecraft.client.resources.sounds.BeeAggressiveSoundInstance
+ net.minecraft.client.resources.sounds.BeeFlyingSoundInstance
- net.minecraft.client.resources.sounds.BeeSoundInstance
+ net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
- net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
+ net.minecraft.client.resources.sounds.BubbleColumnAmbientSoundHandler
- net.minecraft.client.resources.sounds.ElytraOnPlayerSoundInstance
+ net.minecraft.client.resources.sounds.EntityBoundSoundInstance
- net.minecraft.client.resources.sounds.GuardianAttackSoundInstance
+ net.minecraft.client.resources.sounds.MinecartSoundInstance
- net.minecraft.client.resources.sounds.package-info
- net.minecraft.client.resources.sounds.RidingMinecartSoundInstance
+ net.minecraft.client.resources.sounds.SimpleSoundInstance
- net.minecraft.client.resources.sounds.SnifferSoundInstance
+ net.minecraft.client.resources.sounds.Sound
- net.minecraft.client.resources.sounds.Sound$Type
+ net.minecraft.client.resources.sounds.SoundEventRegistration
- net.minecraft.client.resources.sounds.SoundEventRegistrationSerializer
+ net.minecraft.client.resources.sounds.SoundInstance
- net.minecraft.client.resources.sounds.SoundInstance$Attenuation
+ net.minecraft.client.resources.sounds.TickableSoundInstance
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundHandler
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
+ net.minecraft.client.resources.SplashManager
- net.minecraft.client.resources.TextureAtlasHolder
+ net.minecraft.client.searchtree.FullTextSearchTree
- net.minecraft.client.searchtree.IdSearchTree
+ net.minecraft.client.searchtree.IntersectionIterator
- net.minecraft.client.searchtree.MergingUniqueIterator
- net.minecraft.client.searchtree.package-info
+ net.minecraft.client.searchtree.PlainTextSearchTree
- net.minecraft.client.searchtree.RefreshableSearchTree
+ net.minecraft.client.searchtree.ResourceLocationSearchTree
- net.minecraft.client.searchtree.ResourceLocationSearchTree$1
+ net.minecraft.client.searchtree.ResourceLocationSearchTree$2
- net.minecraft.client.searchtree.SearchRegistry
+ net.minecraft.client.searchtree.SearchRegistry$Key
- net.minecraft.client.searchtree.SearchRegistry$TreeBuilderSupplier
+ net.minecraft.client.searchtree.SearchRegistry$TreeEntry
- net.minecraft.client.searchtree.SearchTree
+ net.minecraft.client.searchtree.SuffixArray
+ net.minecraft.client.server.IntegratedPlayerList
- net.minecraft.client.server.IntegratedServer
+ net.minecraft.client.server.LanServer
- net.minecraft.client.server.LanServerDetection
+ net.minecraft.client.server.LanServerDetection$LanServerDetector
- net.minecraft.client.server.LanServerDetection$LanServerList
+ net.minecraft.client.server.LanServerPinger
- net.minecraft.client.server.package-info
+ net.minecraft.client.sounds.AudioStream
- net.minecraft.client.sounds.ChannelAccess
+ net.minecraft.client.sounds.ChannelAccess$ChannelHandle
- net.minecraft.client.sounds.LoopingAudioStream
+ net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
- net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
+ net.minecraft.client.sounds.MusicManager
- net.minecraft.client.sounds.package-info
- net.minecraft.client.sounds.SoundBufferLibrary
+ net.minecraft.client.sounds.SoundEngine
- net.minecraft.client.sounds.SoundEngine$DeviceCheckState
+ net.minecraft.client.sounds.SoundEngineExecutor
- net.minecraft.client.sounds.SoundEventListener
+ net.minecraft.client.sounds.SoundManager
- net.minecraft.client.sounds.SoundManager$1
+ net.minecraft.client.sounds.SoundManager$2
- net.minecraft.client.sounds.SoundManager$Preparations
+ net.minecraft.client.sounds.SoundManager$Preparations$1
- net.minecraft.client.sounds.WeighedSoundEvents
+ net.minecraft.client.sounds.Weighted
+ net.minecraft.client.telemetry.ClientTelemetryManager
+ net.minecraft.client.telemetry.events.AggregatedTelemetryEvent
- net.minecraft.client.telemetry.events.GameLoadTimesEvent
+ net.minecraft.client.telemetry.events.GameLoadTimesEvent$Measurement
+ net.minecraft.client.telemetry.events.package-info
- net.minecraft.client.telemetry.events.PerformanceMetricsEvent
+ net.minecraft.client.telemetry.events.WorldLoadEvent
- net.minecraft.client.telemetry.events.WorldLoadEvent$1
+ net.minecraft.client.telemetry.events.WorldLoadTimesEvent
- net.minecraft.client.telemetry.events.WorldUnloadEvent
- net.minecraft.client.telemetry.package-info
- net.minecraft.client.telemetry.TelemetryEventInstance
+ net.minecraft.client.telemetry.TelemetryEventLog
- net.minecraft.client.telemetry.TelemetryEventLogger
+ net.minecraft.client.telemetry.TelemetryEventSender
- net.minecraft.client.telemetry.TelemetryEventType
+ net.minecraft.client.telemetry.TelemetryEventType$Builder
- net.minecraft.client.telemetry.TelemetryLogManager
+ net.minecraft.client.telemetry.TelemetryProperty
- net.minecraft.client.telemetry.TelemetryProperty$Exporter
+ net.minecraft.client.telemetry.TelemetryProperty$GameMode
- net.minecraft.client.telemetry.TelemetryProperty$ServerType
+ net.minecraft.client.telemetry.TelemetryPropertyMap
- net.minecraft.client.telemetry.TelemetryPropertyMap$1
+ net.minecraft.client.telemetry.TelemetryPropertyMap$Builder
- net.minecraft.client.telemetry.WorldSessionTelemetryManager
+ net.minecraft.client.tutorial.BundleTutorial
- net.minecraft.client.tutorial.CompletedTutorialStepInstance
+ net.minecraft.client.tutorial.CraftPlanksTutorialStep
- net.minecraft.client.tutorial.FindTreeTutorialStepInstance
+ net.minecraft.client.tutorial.MovementTutorialStepInstance
- net.minecraft.client.tutorial.OpenInventoryTutorialStep
- net.minecraft.client.tutorial.package-info
+ net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
- net.minecraft.client.tutorial.Tutorial
+ net.minecraft.client.tutorial.Tutorial$TimedToast
- net.minecraft.client.tutorial.TutorialStepInstance
+ net.minecraft.client.tutorial.TutorialSteps
- net.minecraft.commands.arguments.AngleArgument
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.ArgumentSignatures
+ net.minecraft.commands.arguments.ArgumentSignatures$Entry
- net.minecraft.commands.arguments.ArgumentSignatures$Signer
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.BlockStateParser$BlockResult
- net.minecraft.commands.arguments.blocks.BlockStateParser$TagResult
+ net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.ColorArgument
- net.minecraft.commands.arguments.ComponentArgument
+ net.minecraft.commands.arguments.CompoundTagArgument
- net.minecraft.commands.arguments.coordinates.BlockPosArgument
+ net.minecraft.commands.arguments.coordinates.ColumnPosArgument
- net.minecraft.commands.arguments.coordinates.Coordinates
+ net.minecraft.commands.arguments.coordinates.LocalCoordinates
- net.minecraft.commands.arguments.coordinates.package-info
- net.minecraft.commands.arguments.coordinates.RotationArgument
+ net.minecraft.commands.arguments.coordinates.SwizzleArgument
- net.minecraft.commands.arguments.coordinates.Vec2Argument
+ net.minecraft.commands.arguments.coordinates.Vec3Argument
- net.minecraft.commands.arguments.coordinates.WorldCoordinate
+ net.minecraft.commands.arguments.coordinates.WorldCoordinates
- net.minecraft.commands.arguments.DimensionArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument
- net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
+ net.minecraft.commands.arguments.EntityArgument
- net.minecraft.commands.arguments.EntityArgument$Info
+ net.minecraft.commands.arguments.EntityArgument$Info$Template
- net.minecraft.commands.arguments.GameModeArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
- net.minecraft.commands.arguments.HeightmapTypeArgument
- net.minecraft.commands.arguments.item.ComponentPredicateParser$ComponentLookupRule
- net.minecraft.commands.arguments.item.ComponentPredicateParser$ElementLookupRule
- net.minecraft.commands.arguments.item.ComponentPredicateParser$TagLookupRule
+ net.minecraft.commands.arguments.item.FunctionArgument
- net.minecraft.commands.arguments.item.FunctionArgument$1
+ net.minecraft.commands.arguments.item.FunctionArgument$2
- net.minecraft.commands.arguments.item.FunctionArgument$Result
+ net.minecraft.commands.arguments.item.ItemArgument
- net.minecraft.commands.arguments.item.ItemInput
+ net.minecraft.commands.arguments.item.ItemParser
- net.minecraft.commands.arguments.item.ItemParser$1
+ net.minecraft.commands.arguments.item.ItemParser$ItemResult
- net.minecraft.commands.arguments.item.ItemParser$State
- net.minecraft.commands.arguments.item.ItemParser$Visitor
- net.minecraft.commands.arguments.item.ItemPredicateArgument$ComponentWrapper
- net.minecraft.commands.arguments.item.ItemPredicateArgument$PredicateWrapper
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
+ net.minecraft.commands.arguments.item.ItemPredicateParser$1
+ net.minecraft.commands.arguments.item.ItemSyntaxParser$State
+ net.minecraft.commands.arguments.item.ItemSyntaxParser$Visitor
- net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
- net.minecraft.commands.arguments.NbtPathArgument
+ net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
- net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
+ net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$NbtPath
- net.minecraft.commands.arguments.NbtPathArgument$Node
+ net.minecraft.commands.arguments.NbtTagArgument
- net.minecraft.commands.arguments.ObjectiveArgument
+ net.minecraft.commands.arguments.ObjectiveCriteriaArgument
- net.minecraft.commands.arguments.OperationArgument
+ net.minecraft.commands.arguments.OperationArgument$Operation
- net.minecraft.commands.arguments.OperationArgument$SimpleOperation
+ net.minecraft.commands.arguments.package-info
+ net.minecraft.commands.arguments.ParticleArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceArgument
- net.minecraft.commands.arguments.ResourceArgument$Info
+ net.minecraft.commands.arguments.ResourceArgument$Info$Template
- net.minecraft.commands.arguments.ResourceKeyArgument
+ net.minecraft.commands.arguments.ResourceKeyArgument$Info
- net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ResourceOrIdArgument
- net.minecraft.commands.arguments.ResourceOrIdArgument$LootPredicateArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
- net.minecraft.commands.arguments.ScoreHolderArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument$Info
- net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.arguments.selector.EntitySelector
+ net.minecraft.commands.arguments.selector.EntitySelector$1
- net.minecraft.commands.arguments.selector.EntitySelectorParser
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
- net.minecraft.commands.arguments.selector.options.package-info
+ net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.SignedArgument
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.SlotsArgument
+ net.minecraft.commands.arguments.StringRepresentableArgument
- net.minecraft.commands.arguments.StyleArgument
+ net.minecraft.commands.arguments.TeamArgument
- net.minecraft.commands.arguments.TemplateMirrorArgument
+ net.minecraft.commands.arguments.TemplateRotationArgument
- net.minecraft.commands.arguments.TimeArgument
+ net.minecraft.commands.arguments.TimeArgument$Info
- net.minecraft.commands.arguments.TimeArgument$Info$Template
+ net.minecraft.commands.arguments.UuidArgument
+ net.minecraft.commands.BrigadierExceptions
- net.minecraft.commands.CacheableFunction
+ net.minecraft.commands.CommandBuildContext
- net.minecraft.commands.CommandBuildContext$1
+ net.minecraft.commands.CommandResultCallback
- net.minecraft.commands.CommandResultCallback$1
+ net.minecraft.commands.Commands
- net.minecraft.commands.Commands$1
+ net.minecraft.commands.Commands$1$1
- net.minecraft.commands.Commands$CommandSelection
+ net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSigningContext
- net.minecraft.commands.CommandSigningContext$1
+ net.minecraft.commands.CommandSigningContext$SignedArguments
- net.minecraft.commands.CommandSource
+ net.minecraft.commands.CommandSource$1
- net.minecraft.commands.CommandSourceStack
- net.minecraft.commands.execution.ChainModifiers
+ net.minecraft.commands.execution.CommandQueueEntry
- net.minecraft.commands.execution.CustomCommandExecutor
+ net.minecraft.commands.execution.CustomCommandExecutor$CommandAdapter
- net.minecraft.commands.execution.CustomCommandExecutor$WithErrorHandling
+ net.minecraft.commands.execution.CustomModifierExecutor
- net.minecraft.commands.execution.CustomModifierExecutor$ModifierAdapter
+ net.minecraft.commands.execution.EntryAction
- net.minecraft.commands.execution.ExecutionContext
+ net.minecraft.commands.execution.ExecutionControl
- net.minecraft.commands.execution.ExecutionControl$1
+ net.minecraft.commands.execution.Frame
- net.minecraft.commands.execution.Frame$FrameControl
+ net.minecraft.commands.execution.package-info
- net.minecraft.commands.execution.tasks.BuildContexts
+ net.minecraft.commands.execution.tasks.BuildContexts$Continuation
- net.minecraft.commands.execution.tasks.BuildContexts$TopLevel
+ net.minecraft.commands.execution.tasks.BuildContexts$Unbound
- net.minecraft.commands.execution.tasks.CallFunction
+ net.minecraft.commands.execution.tasks.ContinuationTask
- net.minecraft.commands.execution.tasks.ContinuationTask$TaskProvider
+ net.minecraft.commands.execution.tasks.ExecuteCommand
- net.minecraft.commands.execution.tasks.FallthroughTask
+ net.minecraft.commands.execution.tasks.IsolatedCall
- net.minecraft.commands.execution.tasks.package-info
+ net.minecraft.commands.execution.TraceCallbacks
- net.minecraft.commands.execution.UnboundEntryAction
- net.minecraft.commands.ExecutionCommandSource
+ net.minecraft.commands.FunctionInstantiationException
+ net.minecraft.commands.functions.CommandFunction
- net.minecraft.commands.functions.FunctionBuilder
+ net.minecraft.commands.functions.InstantiatedFunction
- net.minecraft.commands.functions.MacroFunction
+ net.minecraft.commands.functions.MacroFunction$Entry
- net.minecraft.commands.functions.MacroFunction$MacroEntry
+ net.minecraft.commands.functions.MacroFunction$PlainTextEntry
- net.minecraft.commands.functions.package-info
- net.minecraft.commands.functions.PlainTextFunction
+ net.minecraft.commands.functions.StringTemplate
+ net.minecraft.commands.package-info
- net.minecraft.commands.ParserUtils
+ net.minecraft.commands.SharedSuggestionProvider
- net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- net.minecraft.commands.synchronization.ArgumentTypeInfo
+ net.minecraft.commands.synchronization.ArgumentTypeInfo$Template
- net.minecraft.commands.synchronization.ArgumentTypeInfos
+ net.minecraft.commands.synchronization.ArgumentUtils
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.LongArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.LongArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.package-info
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$Template
- net.minecraft.commands.synchronization.package-info
- net.minecraft.commands.synchronization.SingletonArgumentInfo
+ net.minecraft.commands.synchronization.SingletonArgumentInfo$Template
- net.minecraft.commands.synchronization.SuggestionProviders
+ net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
+ net.minecraft.core.AxisCycle
- net.minecraft.core.AxisCycle$1
+ net.minecraft.core.AxisCycle$2
- net.minecraft.core.AxisCycle$3
+ net.minecraft.core.BlockBox
- net.minecraft.core.BlockBox$1
+ net.minecraft.core.BlockMath
- net.minecraft.core.BlockPos
+ net.minecraft.core.BlockPos$1
- net.minecraft.core.BlockPos$2
+ net.minecraft.core.BlockPos$3
- net.minecraft.core.BlockPos$4
+ net.minecraft.core.BlockPos$5
- net.minecraft.core.BlockPos$6
+ net.minecraft.core.BlockPos$MutableBlockPos
- net.minecraft.core.cauldron.CauldronInteraction
+ net.minecraft.core.cauldron.CauldronInteraction$InteractionMap
- net.minecraft.core.cauldron.package-info
- net.minecraft.core.Cloner
+ net.minecraft.core.Cloner$Factory
+ net.minecraft.core.component.DataComponentHolder
- net.minecraft.core.component.DataComponentMap
+ net.minecraft.core.component.DataComponentMap$1
- net.minecraft.core.component.DataComponentMap$2
+ net.minecraft.core.component.DataComponentMap$Builder
- net.minecraft.core.component.DataComponentMap$Builder$SimpleMap
+ net.minecraft.core.component.DataComponentPatch
- net.minecraft.core.component.DataComponentPatch$1
+ net.minecraft.core.component.DataComponentPatch$Builder
- net.minecraft.core.component.DataComponentPatch$PatchKey
+ net.minecraft.core.component.DataComponentPredicate
- net.minecraft.core.component.DataComponentPredicate$Builder
- net.minecraft.core.component.DataComponents
+ net.minecraft.core.component.DataComponentType
- net.minecraft.core.component.DataComponentType$Builder
+ net.minecraft.core.component.DataComponentType$Builder$SimpleType
- net.minecraft.core.component.package-info
+ net.minecraft.core.component.PatchedDataComponentMap
- net.minecraft.core.component.TypedDataComponent
+ net.minecraft.core.component.TypedDataComponent$1
- net.minecraft.core.Cursor3D
+ net.minecraft.core.DefaultedMappedRegistry
- net.minecraft.core.DefaultedRegistry
+ net.minecraft.core.Direction
- net.minecraft.core.Direction$1
+ net.minecraft.core.Direction$Axis
- net.minecraft.core.Direction$Axis$1
+ net.minecraft.core.Direction$Axis$2
- net.minecraft.core.Direction$Axis$3
+ net.minecraft.core.Direction$AxisDirection
- net.minecraft.core.Direction$Plane
+ net.minecraft.core.Direction8
+ net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
- net.minecraft.core.dispenser.BlockSource
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
+ net.minecraft.core.dispenser.DispenseItemBehavior$25
- net.minecraft.core.dispenser.DispenseItemBehavior$26
+ net.minecraft.core.dispenser.DispenseItemBehavior$27
- net.minecraft.core.dispenser.DispenseItemBehavior$28
+ net.minecraft.core.dispenser.DispenseItemBehavior$29
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
- net.minecraft.core.dispenser.package-info
- net.minecraft.core.dispenser.ShearsDispenseItemBehavior
+ net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.FrontAndTop
+ net.minecraft.core.GlobalPos
- net.minecraft.core.Holder
+ net.minecraft.core.Holder$Direct
- net.minecraft.core.Holder$Kind
+ net.minecraft.core.Holder$Reference
- net.minecraft.core.Holder$Reference$Type
+ net.minecraft.core.HolderGetter
- net.minecraft.core.HolderGetter$Provider
+ net.minecraft.core.HolderLookup
- net.minecraft.core.HolderLookup$Provider
+ net.minecraft.core.HolderLookup$Provider$1
- net.minecraft.core.HolderLookup$Provider$2
+ net.minecraft.core.HolderLookup$RegistryLookup
- net.minecraft.core.HolderLookup$RegistryLookup$1
+ net.minecraft.core.HolderLookup$RegistryLookup$Delegate
- net.minecraft.core.HolderOwner
+ net.minecraft.core.HolderSet
- net.minecraft.core.HolderSet$1
+ net.minecraft.core.HolderSet$Direct
- net.minecraft.core.HolderSet$ListBacked
+ net.minecraft.core.HolderSet$Named
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.LayeredRegistryAccess
+ net.minecraft.core.MappedRegistry
- net.minecraft.core.MappedRegistry$1
+ net.minecraft.core.MappedRegistry$2
- net.minecraft.core.NonNullList
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
- net.minecraft.core.particles.ColorParticleOption
+ net.minecraft.core.Position
- net.minecraft.core.QuartPos
+ net.minecraft.core.RegistrationInfo
- net.minecraft.core.Registry
+ net.minecraft.core.Registry$1
- net.minecraft.core.Registry$2
+ net.minecraft.core.RegistryAccess
- net.minecraft.core.RegistryAccess$1
+ net.minecraft.core.RegistryAccess$1FrozenAccess
- net.minecraft.core.RegistryAccess$Frozen
+ net.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- net.minecraft.core.RegistryAccess$RegistryEntry
+ net.minecraft.core.RegistryCodecs
- net.minecraft.core.RegistrySetBuilder
+ net.minecraft.core.RegistrySetBuilder$1
- net.minecraft.core.RegistrySetBuilder$1Entry
+ net.minecraft.core.RegistrySetBuilder$2
- net.minecraft.core.RegistrySetBuilder$3
+ net.minecraft.core.RegistrySetBuilder$3$1
- net.minecraft.core.RegistrySetBuilder$BuildState
+ net.minecraft.core.RegistrySetBuilder$BuildState$1
- net.minecraft.core.RegistrySetBuilder$EmptyTagLookup
+ net.minecraft.core.RegistrySetBuilder$EmptyTagLookupWrapper
- net.minecraft.core.RegistrySetBuilder$EmptyTagRegistryLookup
+ net.minecraft.core.RegistrySetBuilder$LazyHolder
- net.minecraft.core.RegistrySetBuilder$PatchedRegistries
+ net.minecraft.core.RegistrySetBuilder$RegisteredValue
- net.minecraft.core.RegistrySetBuilder$RegistryBootstrap
+ net.minecraft.core.RegistrySetBuilder$RegistryContents
- net.minecraft.core.RegistrySetBuilder$RegistryStub
+ net.minecraft.core.RegistrySetBuilder$UniversalLookup
- net.minecraft.core.RegistrySetBuilder$UniversalOwner
+ net.minecraft.core.RegistrySetBuilder$ValueAndHolder
- net.minecraft.core.RegistrySynchronization
+ net.minecraft.core.RegistrySynchronization$PackedRegistryEntry
- net.minecraft.core.Rotations
+ net.minecraft.core.Rotations$1
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.UUIDUtil
+ net.minecraft.core.UUIDUtil$1
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
+ net.minecraft.data.loot.LootTableProvider$SubProviderEntry
- net.minecraft.data.loot.LootTableSubProvider
+ net.minecraft.data.loot.package-info
- net.minecraft.data.loot.packs.package-info
- net.minecraft.data.loot.packs.TradeRebalanceChestLoot
+ net.minecraft.data.loot.packs.TradeRebalanceLootTableProvider
- net.minecraft.data.loot.packs.UpdateOneTwentyOneBlockLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneChestLoot
- net.minecraft.data.loot.packs.UpdateOneTwentyOneEntityLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneLootTableProvider
- net.minecraft.data.loot.packs.UpdateOneTwentyOneShearingLoot
+ net.minecraft.data.loot.packs.VanillaArchaeologyLoot
- net.minecraft.data.loot.packs.VanillaBlockLoot
+ net.minecraft.data.loot.packs.VanillaChestLoot
- net.minecraft.data.loot.packs.VanillaEntityLoot
+ net.minecraft.data.loot.packs.VanillaFishingLoot
- net.minecraft.data.loot.packs.VanillaGiftLoot
+ net.minecraft.data.loot.packs.VanillaLootTableProvider
- net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
+ net.minecraft.data.loot.packs.VanillaShearingLoot
- net.minecraft.data.metadata.package-info
+ net.minecraft.data.metadata.PackMetadataGenerator
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
+ net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- net.minecraft.data.models.BlockModelGenerators$BookSlotModelCacheKey
+ net.minecraft.data.models.BlockModelGenerators$TintState
- net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
- net.minecraft.data.models.blockstates.Condition$CompositeCondition
+ net.minecraft.data.models.blockstates.Condition$Operation
- net.minecraft.data.models.blockstates.Condition$TerminalCondition
+ net.minecraft.data.models.blockstates.MultiPartGenerator
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
- net.minecraft.data.models.blockstates.package-info
+ net.minecraft.data.models.blockstates.PropertyDispatch
- net.minecraft.data.models.blockstates.PropertyDispatch$C1
+ net.minecraft.data.models.blockstates.PropertyDispatch$C2
- net.minecraft.data.models.blockstates.PropertyDispatch$C3
+ net.minecraft.data.models.blockstates.PropertyDispatch$C4
- net.minecraft.data.models.blockstates.PropertyDispatch$C5
+ net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
- net.minecraft.data.models.blockstates.Selector
+ net.minecraft.data.models.blockstates.Variant
- net.minecraft.data.models.blockstates.VariantProperties
+ net.minecraft.data.models.blockstates.VariantProperties$Rotation
- net.minecraft.data.models.blockstates.VariantProperty
+ net.minecraft.data.models.blockstates.VariantProperty$Value
+ net.minecraft.data.models.ItemModelGenerators
- net.minecraft.data.models.ItemModelGenerators$TrimModelData
+ net.minecraft.data.models.model.DelegatedModel
- net.minecraft.data.models.model.ModelLocationUtils
+ net.minecraft.data.models.model.ModelTemplate
- net.minecraft.data.models.model.ModelTemplate$JsonFactory
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.ModelProvider
+ net.minecraft.data.models.package-info
- net.minecraft.data.package-info
- net.minecraft.data.recipes.package-info
+ net.minecraft.data.recipes.packs.BundleRecipeProvider
+ net.minecraft.data.recipes.packs.package-info
- net.minecraft.data.recipes.packs.UpdateOneTwentyOneRecipeProvider
+ net.minecraft.data.recipes.packs.VanillaRecipeProvider
- net.minecraft.data.recipes.packs.VanillaRecipeProvider$TrimTemplate
+ net.minecraft.data.recipes.RecipeBuilder
- net.minecraft.data.recipes.RecipeBuilder$1
+ net.minecraft.data.recipes.RecipeCategory
- net.minecraft.data.recipes.RecipeOutput
+ net.minecraft.data.recipes.RecipeProvider
- net.minecraft.data.recipes.RecipeProvider$1
+ net.minecraft.data.recipes.ShapedRecipeBuilder
- net.minecraft.data.recipes.ShapelessRecipeBuilder
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder
- net.minecraft.data.recipes.SingleItemRecipeBuilder
+ net.minecraft.data.recipes.SmithingTransformRecipeBuilder
- net.minecraft.data.recipes.SmithingTrimRecipeBuilder
+ net.minecraft.data.recipes.SpecialRecipeBuilder
- net.minecraft.data.registries.package-info
- net.minecraft.data.registries.RegistriesDatapackGenerator
+ net.minecraft.data.registries.RegistryPatchGenerator
- net.minecraft.data.registries.UpdateOneTwentyOneRegistries
+ net.minecraft.data.registries.VanillaRegistries
+ net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtDatafixer
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
+ net.minecraft.data.structures.SnbtToNbt$StructureConversionException
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BannerPatternTagsProvider
- net.minecraft.data.tags.BiomeTagsProvider
+ net.minecraft.data.tags.CatVariantTagsProvider
- net.minecraft.data.tags.DamageTypeTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.GameEventTagsProvider
+ net.minecraft.data.tags.InstrumentTagsProvider
- net.minecraft.data.tags.IntrinsicHolderTagsProvider
+ net.minecraft.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
- net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.PaintingVariantTagsProvider
- net.minecraft.data.tags.PoiTypeTagsProvider
+ net.minecraft.data.tags.StructureTagsProvider
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$1CombinedData
- net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.data.tags.TagsProvider$TagLookup
- net.minecraft.data.tags.TradeRebalanceStructureTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneBannerPatternTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneBiomeTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneBlockTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneDamageTypes
- net.minecraft.data.tags.UpdateOneTwentyOneDamageTypeTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneEntityTypeTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneItemTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneStructureTagsProvider
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ net.minecraft.server.advancements.package-info
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.chase.ChaseClient
- net.minecraft.server.chase.ChaseClient$TeleportTarget
+ net.minecraft.server.chase.ChaseServer
- net.minecraft.server.chase.ChaseServer$PlayerPosition
+ net.minecraft.server.chase.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ChaseCommand
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$CommandFunction
+ net.minecraft.server.commands.CloneCommands$DimensionAndPosition
- net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.DamageCommand
+ net.minecraft.server.commands.data.BlockDataAccessor
- net.minecraft.server.commands.data.BlockDataAccessor$1
+ net.minecraft.server.commands.data.DataAccessor
- net.minecraft.server.commands.data.DataCommands
+ net.minecraft.server.commands.data.DataCommands$DataManipulator
- net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
+ net.minecraft.server.commands.data.DataCommands$DataProvider
- net.minecraft.server.commands.data.DataCommands$StringProcessor
+ net.minecraft.server.commands.data.EntityDataAccessor
- net.minecraft.server.commands.data.EntityDataAccessor$1
+ net.minecraft.server.commands.data.package-info
+ net.minecraft.server.commands.data.StorageDataAccessor
- net.minecraft.server.commands.data.StorageDataAccessor$1
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugCommand$TraceCustomExecutor
+ net.minecraft.server.commands.DebugCommand$TraceCustomExecutor$1
- net.minecraft.server.commands.DebugCommand$Tracer
+ net.minecraft.server.commands.DebugConfigCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandGetter
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
- net.minecraft.server.commands.ExecuteCommand$IntBiPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillBiomeCommand
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.FunctionCommand$1
+ net.minecraft.server.commands.FunctionCommand$1Accumulator
- net.minecraft.server.commands.FunctionCommand$2
+ net.minecraft.server.commands.FunctionCommand$3
- net.minecraft.server.commands.FunctionCommand$4
+ net.minecraft.server.commands.FunctionCommand$5
- net.minecraft.server.commands.FunctionCommand$Callbacks
+ net.minecraft.server.commands.FunctionCommand$FunctionCustomExecutor
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.JfrCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PerfCommand
+ net.minecraft.server.commands.PlaceCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RandomCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ResetChunksCommand
+ net.minecraft.server.commands.ReturnCommand
- net.minecraft.server.commands.ReturnCommand$ReturnFailCustomExecutor
+ net.minecraft.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
- net.minecraft.server.commands.ReturnCommand$ReturnValueCustomExecutor
+ net.minecraft.server.commands.RideCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.ServerPackCommand
+ net.minecraft.server.commands.SetBlockCommand
- net.minecraft.server.commands.SetBlockCommand$Filter
+ net.minecraft.server.commands.SetBlockCommand$Mode
- net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
+ net.minecraft.server.commands.SetSpawnCommand
- net.minecraft.server.commands.SetWorldSpawnCommand
+ net.minecraft.server.commands.SpawnArmorTrimsCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$Position
+ net.minecraft.server.commands.StopCommand
- net.minecraft.server.commands.StopSoundCommand
+ net.minecraft.server.commands.SummonCommand
- net.minecraft.server.commands.TagCommand
+ net.minecraft.server.commands.TeamCommand
- net.minecraft.server.commands.TeamMsgCommand
+ net.minecraft.server.commands.TeleportCommand
- net.minecraft.server.commands.TeleportCommand$LookAt
+ net.minecraft.server.commands.TeleportCommand$LookAtEntity
- net.minecraft.server.commands.TeleportCommand$LookAtPosition
+ net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.commands.TickCommand
+ net.minecraft.server.commands.TimeCommand
- net.minecraft.server.commands.TitleCommand
+ net.minecraft.server.commands.TransferCommand
- net.minecraft.server.commands.TriggerCommand
+ net.minecraft.server.commands.WardenSpawnTrackerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServerProperties
+ net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
- net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.dedicated.Settings$MutableValue
- net.minecraft.server.gui.MinecraftServerGui
+ net.minecraft.server.gui.MinecraftServerGui$1
- net.minecraft.server.gui.MinecraftServerGui$2
+ net.minecraft.server.gui.package-info
+ net.minecraft.server.gui.PlayerListComponent
- net.minecraft.server.gui.StatsComponent
- net.minecraft.server.level.BlockDestructionProgress
+ net.minecraft.server.level.ChunkHolder
- net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
+ net.minecraft.server.level.ChunkHolder$LevelChangeListener
- net.minecraft.server.level.ChunkHolder$PlayerProvider
+ net.minecraft.server.level.ChunkLevel
- net.minecraft.server.level.ChunkLevel$1
+ net.minecraft.server.level.ChunkMap
- net.minecraft.server.level.ChunkMap$DistanceManager
+ net.minecraft.server.level.ChunkMap$TrackedEntity
- net.minecraft.server.level.ChunkResult
+ net.minecraft.server.level.ChunkResult$Fail
- net.minecraft.server.level.ChunkResult$Success
+ net.minecraft.server.level.ChunkTaskPriorityQueue
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
+ net.minecraft.server.level.ChunkTracker
- net.minecraft.server.level.ChunkTrackingView
+ net.minecraft.server.level.ChunkTrackingView$1
- net.minecraft.server.level.ChunkTrackingView$Positioned
+ net.minecraft.server.level.ClientInformation
- net.minecraft.server.level.ColumnPos
+ net.minecraft.server.level.DemoMode
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.FullChunkStatus
+ net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayer$1
+ net.minecraft.server.level.ServerPlayer$2
- net.minecraft.server.level.ServerPlayerGameMode
+ net.minecraft.server.level.ThreadedLevelLightEngine
- net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
+ net.minecraft.server.level.Ticket
- net.minecraft.server.level.TicketType
+ net.minecraft.server.level.TickingTracker
- net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.network.CommonListenerCookie
+ net.minecraft.server.network.config.JoinWorldTask
- net.minecraft.server.network.config.package-info
- net.minecraft.server.network.config.ServerResourcePackConfigurationTask
+ net.minecraft.server.network.config.SynchronizeRegistriesTask
+ net.minecraft.server.network.ConfigurationTask
- net.minecraft.server.network.ConfigurationTask$Type
+ net.minecraft.server.network.Filterable
- net.minecraft.server.network.FilteredText
+ net.minecraft.server.network.LegacyProtocolUtils
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
- net.minecraft.server.network.PlayerChunkSender
+ net.minecraft.server.network.ServerCommonPacketListenerImpl
- net.minecraft.server.network.ServerConfigurationPacketListenerImpl
+ net.minecraft.server.network.ServerConnectionListener
- net.minecraft.server.network.ServerConnectionListener$1
+ net.minecraft.server.network.ServerConnectionListener$2
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- net.minecraft.server.network.ServerGamePacketListenerImpl
+ net.minecraft.server.network.ServerGamePacketListenerImpl$1
- net.minecraft.server.network.ServerGamePacketListenerImpl$2
+ net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
- net.minecraft.server.network.ServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl$State
+ net.minecraft.server.network.ServerPlayerConnection
- net.minecraft.server.network.ServerStatusPacketListenerImpl
+ net.minecraft.server.network.TextFilter
- net.minecraft.server.network.TextFilter$1
+ net.minecraft.server.network.TextFilterClient
- net.minecraft.server.network.TextFilterClient$IgnoreStrategy
+ net.minecraft.server.network.TextFilterClient$JoinOrLeaveEncoder
- net.minecraft.server.network.TextFilterClient$MessageEncoder
+ net.minecraft.server.network.TextFilterClient$PlayerContext
- net.minecraft.server.network.TextFilterClient$RequestFailedException
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractPackResources
- net.minecraft.server.packs.BuiltInMetadata
+ net.minecraft.server.packs.CompositePackResources
- net.minecraft.server.packs.DownloadCacheCleaner
+ net.minecraft.server.packs.DownloadCacheCleaner$1
- net.minecraft.server.packs.DownloadCacheCleaner$PathAndPriority
+ net.minecraft.server.packs.DownloadCacheCleaner$PathAndTime
- net.minecraft.server.packs.DownloadQueue
+ net.minecraft.server.packs.DownloadQueue$BatchConfig
- net.minecraft.server.packs.DownloadQueue$BatchResult
+ net.minecraft.server.packs.DownloadQueue$DownloadRequest
- net.minecraft.server.packs.DownloadQueue$FileInfoEntry
+ net.minecraft.server.packs.DownloadQueue$LogEntry
- net.minecraft.server.packs.FeatureFlagsMetadataSection
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.FilePackResources$FileResourcesSupplier
+ net.minecraft.server.packs.FilePackResources$SharedZipFileAccess
+ net.minecraft.server.packs.linkfs.DummyFileAttributes
- net.minecraft.server.packs.linkfs.LinkFileSystem
+ net.minecraft.server.packs.linkfs.LinkFileSystem$Builder
- net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
- net.minecraft.server.packs.linkfs.LinkFSFileStore
+ net.minecraft.server.packs.linkfs.LinkFSPath
- net.minecraft.server.packs.linkfs.LinkFSPath$1
+ net.minecraft.server.packs.linkfs.LinkFSPath$2
- net.minecraft.server.packs.linkfs.LinkFSPath$3
+ net.minecraft.server.packs.linkfs.LinkFSProvider
- net.minecraft.server.packs.linkfs.LinkFSProvider$1
+ net.minecraft.server.packs.linkfs.LinkFSProvider$2
- net.minecraft.server.packs.linkfs.package-info
+ net.minecraft.server.packs.linkfs.PathContents
- net.minecraft.server.packs.linkfs.PathContents$1
+ net.minecraft.server.packs.linkfs.PathContents$2
- net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
+ net.minecraft.server.packs.linkfs.PathContents$FileContents
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.MetadataSectionType
+ net.minecraft.server.packs.metadata.MetadataSectionType$1
+ net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.OverlayMetadataSection
+ net.minecraft.server.packs.OverlayMetadataSection$OverlayEntry
+ net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackLocationInfo
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackResources$ResourceOutput
+ net.minecraft.server.packs.PackSelectionConfig
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.PathPackResources
- net.minecraft.server.packs.PathPackResources$PathResourcesSupplier
- net.minecraft.server.packs.repository.BuiltInPackSource
+ net.minecraft.server.packs.repository.BuiltInPackSource$1
- net.minecraft.server.packs.repository.FolderRepositorySource
+ net.minecraft.server.packs.repository.FolderRepositorySource$FolderPackDetector
- net.minecraft.server.packs.repository.KnownPack
+ net.minecraft.server.packs.repository.Pack
- net.minecraft.server.packs.repository.Pack$Metadata
+ net.minecraft.server.packs.repository.Pack$Position
- net.minecraft.server.packs.repository.Pack$ResourcesSupplier
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackDetector
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.PackSource
+ net.minecraft.server.packs.repository.PackSource$1
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.resources.CloseableResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
- net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
+ net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
- net.minecraft.server.packs.resources.IoSupplier
+ net.minecraft.server.packs.resources.MultiPackResourceManager
- net.minecraft.server.packs.resources.package-info
- net.minecraft.server.packs.resources.PreparableReloadListener
+ net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
- net.minecraft.server.packs.resources.ProfiledReloadInstance
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceFilterSection
- net.minecraft.server.packs.resources.ResourceManager
+ net.minecraft.server.packs.resources.ResourceManager$Empty
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.ResourceMetadata
- net.minecraft.server.packs.resources.ResourceMetadata$1
+ net.minecraft.server.packs.resources.ResourceMetadata$2
- net.minecraft.server.packs.resources.ResourceMetadata$Builder
+ net.minecraft.server.packs.resources.ResourceMetadata$Builder$1
- net.minecraft.server.packs.resources.ResourceProvider
+ net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
- net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadInstance$1
+ net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
+ net.minecraft.server.packs.VanillaPackResources
- net.minecraft.server.packs.VanillaPackResourcesBuilder
+ net.minecraft.server.players.BanListEntry
- net.minecraft.server.players.GameProfileCache
+ net.minecraft.server.players.GameProfileCache$1
- net.minecraft.server.players.GameProfileCache$GameProfileInfo
+ net.minecraft.server.players.IpBanList
- net.minecraft.server.players.IpBanListEntry
+ net.minecraft.server.players.OldUsersConverter
- net.minecraft.server.players.OldUsersConverter$1
+ net.minecraft.server.players.OldUsersConverter$2
- net.minecraft.server.players.OldUsersConverter$3
+ net.minecraft.server.players.OldUsersConverter$4
- net.minecraft.server.players.OldUsersConverter$5
+ net.minecraft.server.players.OldUsersConverter$ConversionError
+ net.minecraft.server.players.package-info
- net.minecraft.server.players.PlayerList
+ net.minecraft.server.players.PlayerList$1
- net.minecraft.server.players.ServerOpList
+ net.minecraft.server.players.ServerOpListEntry
- net.minecraft.server.players.SleepStatus
+ net.minecraft.server.players.StoredUserEntry
- net.minecraft.server.players.StoredUserList
+ net.minecraft.server.players.UserBanList
- net.minecraft.server.players.UserBanListEntry
+ net.minecraft.server.players.UserWhiteList
- net.minecraft.server.players.UserWhiteListEntry
- net.minecraft.server.rcon.NetworkDataOutputStream
+ net.minecraft.server.rcon.package-info
+ net.minecraft.server.rcon.PktUtils
- net.minecraft.server.rcon.RconConsoleSource
- net.minecraft.server.rcon.thread.GenericThread
+ net.minecraft.server.rcon.thread.package-info
+ net.minecraft.server.rcon.thread.QueryThreadGs4
- net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
+ net.minecraft.server.rcon.thread.RconClient
- net.minecraft.server.rcon.thread.RconThread
- net.minecraft.server.ReloadableServerRegistries$EmptyTagLookupWrapper
- net.minecraft.server.ReloadableServerResources
+ net.minecraft.server.ReloadableServerResources$1
- net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
+ net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- net.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerInfo
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.ServerTickRateManager
- net.minecraft.server.Services
+ net.minecraft.server.TickTask
- net.minecraft.server.WorldLoader
+ net.minecraft.server.WorldLoader$DataLoadContext
- net.minecraft.server.WorldLoader$DataLoadOutput
+ net.minecraft.server.WorldLoader$InitConfig
- net.minecraft.server.WorldLoader$PackConfig
+ net.minecraft.server.WorldLoader$ResultFactory
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
- net.minecraft.sounds.Music
+ net.minecraft.sounds.Musics
+ net.minecraft.sounds.package-info
- net.minecraft.sounds.SoundEvent
+ net.minecraft.sounds.SoundEvents
- net.minecraft.sounds.SoundSource
- net.minecraft.stats.package-info
- net.minecraft.stats.RecipeBook
+ net.minecraft.stats.RecipeBookSettings
- net.minecraft.stats.RecipeBookSettings$TypeSettings
+ net.minecraft.stats.ServerRecipeBook
- net.minecraft.stats.ServerStatsCounter
+ net.minecraft.stats.Stat
- net.minecraft.stats.StatFormatter
- net.minecraft.stats.Stats
+ net.minecraft.stats.StatsCounter
+ net.minecraft.stats.StatType
+ net.minecraft.tags.BannerPatternTags
- net.minecraft.tags.BiomeTags
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.CatVariantTags
+ net.minecraft.tags.DamageTypeTags
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FlatLevelGeneratorPresetTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.InstrumentTags
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
- net.minecraft.tags.PaintingVariantTags
+ net.minecraft.tags.PoiTypeTags
- net.minecraft.tags.StructureTags
+ net.minecraft.tags.TagBuilder
- net.minecraft.tags.TagEntry
+ net.minecraft.tags.TagEntry$Lookup
- net.minecraft.tags.TagFile
+ net.minecraft.tags.TagKey
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagLoader$1
- net.minecraft.tags.TagLoader$EntryWithSource
+ net.minecraft.tags.TagLoader$SortingEntry
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$LoadResult
- net.minecraft.tags.TagNetworkSerialization
+ net.minecraft.tags.TagNetworkSerialization$NetworkPayload
- net.minecraft.tags.TagNetworkSerialization$TagOutput
+ net.minecraft.tags.WorldPresetTags
+ net.minecraft.util.AbortableIterationConsumer
- net.minecraft.util.AbortableIterationConsumer$Continuation
+ net.minecraft.util.ArrayListDeque
- net.minecraft.util.ArrayListDeque$DescendingIterator
+ net.minecraft.util.BitStorage
- net.minecraft.util.Brightness
+ net.minecraft.util.ByIdMap
- net.minecraft.util.ByIdMap$1
+ net.minecraft.util.ByIdMap$OutOfBoundsStrategy
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.ClassTreeIdRegistry
- net.minecraft.util.ColorRGBA
+ net.minecraft.util.CommonColors
- net.minecraft.util.CommonLinks
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.Crypt$ByteArrayToKeyFunction
- net.minecraft.util.Crypt$SaltSignaturePair
+ net.minecraft.util.Crypt$SaltSupplier
- net.minecraft.util.CryptException
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.CubicSpline
- net.minecraft.util.CubicSpline$1Point
+ net.minecraft.util.CubicSpline$Builder
- net.minecraft.util.CubicSpline$Constant
+ net.minecraft.util.CubicSpline$CoordinateVisitor
- net.minecraft.util.CubicSpline$Multipoint
- net.minecraft.util.datafix.ComponentDataFixUtils
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.DataFixTypes$1
- net.minecraft.util.datafix.ExtraDataFixUtils
+ net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
- net.minecraft.util.datafix.fixes.AbstractPoiSectionFix
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AreaEffectCloudPotionFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BannerPatternFormatFix
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehiveFieldRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlendingDataFix
- net.minecraft.util.datafix.fixes.BlendingDataRemoveFromNetherEndFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityRenameFix
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockPosFormatAndRenamesFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.CauldronRenameFix
- net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
+ net.minecraft.util.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
- net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkDeleteIgnoredLightDataFix
+ net.minecraft.util.datafix.fixes.ChunkDeleteLightFix
- net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- net.minecraft.util.datafix.fixes.ChunkRenamesFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix2
+ net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
- net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
+ net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
- net.minecraft.util.datafix.fixes.CriteriaRenameFix
+ net.minecraft.util.datafix.fixes.DecoratedPotFieldRenameFix
- net.minecraft.util.datafix.fixes.DropInvalidSignDataFix
+ net.minecraft.util.datafix.fixes.DyeItemRenameFix
- net.minecraft.util.datafix.fixes.EffectDurationFix
+ net.minecraft.util.datafix.fixes.EmptyItemInHotbarFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityGoatMissingStateFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingFieldsRenameFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
+ net.minecraft.util.datafix.fixes.EntityVariantFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.FeatureFlagRemoveFix
+ net.minecraft.util.datafix.fixes.FilteredBooksFix
- net.minecraft.util.datafix.fixes.FilteredSignsFix
+ net.minecraft.util.datafix.fixes.FixProjectileStoredItem
- net.minecraft.util.datafix.fixes.FixProjectileStoredItem$SubFixer
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GoatHornIdFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.HorseBodyArmorItemFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackComponentizationFix
- net.minecraft.util.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- net.minecraft.util.datafix.fixes.ItemStackComponentRemainderFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTagFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LegacyDragonFightFix
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelLegacyWorldGenSettingsFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.LodestoneCompassComponentFix
- net.minecraft.util.datafix.fixes.MapBannerBlockPosFormatFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobEffectIdFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NamedEntityWriteReadFix
- net.minecraft.util.datafix.fixes.NamespacedTypeRenameFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
+ net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerHeadBlockProfileFix
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
+ net.minecraft.util.datafix.fixes.PoiTypeRenameFix
- net.minecraft.util.datafix.fixes.PrimedTntBlockStateFixer
+ net.minecraft.util.datafix.fixes.RandomSequenceSettingsFix
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemapChunkStatusFix
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.RenameEnchantmentsFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.ScoreboardDisplaySlotFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix$StatType
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TippedArrowPotionToItemFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VariantRenameFix
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.FixWolfHealth
- net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
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
- net.minecraft.util.datafix.schemas.V1451_6$1
+ net.minecraft.util.datafix.schemas.V1451_6$2
- net.minecraft.util.datafix.schemas.V1460
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
+ net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
+ net.minecraft.util.datafix.schemas.V2831
- net.minecraft.util.datafix.schemas.V2832
+ net.minecraft.util.datafix.schemas.V2842
- net.minecraft.util.datafix.schemas.V3076
+ net.minecraft.util.datafix.schemas.V3078
- net.minecraft.util.datafix.schemas.V3081
+ net.minecraft.util.datafix.schemas.V3082
- net.minecraft.util.datafix.schemas.V3083
+ net.minecraft.util.datafix.schemas.V3202
- net.minecraft.util.datafix.schemas.V3203
+ net.minecraft.util.datafix.schemas.V3204
- net.minecraft.util.datafix.schemas.V3325
+ net.minecraft.util.datafix.schemas.V3326
- net.minecraft.util.datafix.schemas.V3327
+ net.minecraft.util.datafix.schemas.V3328
- net.minecraft.util.datafix.schemas.V3438
+ net.minecraft.util.datafix.schemas.V3448
- net.minecraft.util.datafix.schemas.V3682
+ net.minecraft.util.datafix.schemas.V3683
- net.minecraft.util.datafix.schemas.V3685
+ net.minecraft.util.datafix.schemas.V3689
- net.minecraft.util.datafix.schemas.V3799
+ net.minecraft.util.datafix.schemas.V3807
- net.minecraft.util.datafix.schemas.V3808
+ net.minecraft.util.datafix.schemas.V3808_1
- net.minecraft.util.datafix.schemas.V3816
+ net.minecraft.util.datafix.schemas.V3818
- net.minecraft.util.datafix.schemas.V3818_3
+ net.minecraft.util.datafix.schemas.V3818_4
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.DelegateDataOutput
+ net.minecraft.util.DependencySorter
- net.minecraft.util.DependencySorter$Entry
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.ExtraCodecs
+ net.minecraft.util.ExtraCodecs$1
- net.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ net.minecraft.util.ExtraCodecs$2
- net.minecraft.util.ExtraCodecs$3
+ net.minecraft.util.ExtraCodecs$4
- net.minecraft.util.ExtraCodecs$5
+ net.minecraft.util.ExtraCodecs$6
- net.minecraft.util.ExtraCodecs$7
+ net.minecraft.util.ExtraCodecs$8
- net.minecraft.util.ExtraCodecs$EitherCodec
+ net.minecraft.util.ExtraCodecs$RecursiveCodec
- net.minecraft.util.ExtraCodecs$RecursiveMapCodec
+ net.minecraft.util.ExtraCodecs$StrictOptionalFieldCodec
- net.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
+ net.minecraft.util.ExtraCodecs$TagOrElementLocation
- net.minecraft.util.ExtraCodecs$XorCodec
+ net.minecraft.util.FastBufferedInputStream
- net.minecraft.util.FastColor
+ net.minecraft.util.FastColor$ABGR32
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FileZipper
- net.minecraft.util.FormattedCharSequence
+ net.minecraft.util.FormattedCharSink
- net.minecraft.util.FutureChain
+ net.minecraft.util.Graph
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.HttpUtil$DownloadProgressListener
+ net.minecraft.util.InclusiveRange
- net.minecraft.util.JavaOps
+ net.minecraft.util.JavaOps$1
- net.minecraft.util.JavaOps$FixedMapBuilder
+ net.minecraft.util.KeyDispatchDataCodec
- net.minecraft.util.LazyLoadedValue
+ net.minecraft.util.LinearCongruentialGenerator
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- net.minecraft.util.MemoryReserve
+ net.minecraft.util.ModCheck
- net.minecraft.util.ModCheck$Confidence
+ net.minecraft.util.Mth
- net.minecraft.util.NativeModuleLister
+ net.minecraft.util.NativeModuleLister$NativeModuleInfo
- net.minecraft.util.NativeModuleLister$NativeModuleVersion
+ net.minecraft.util.OptionEnum
- net.minecraft.util.parsing.package-info
- net.minecraft.util.parsing.packrat.commands.Grammar
- net.minecraft.util.parsing.packrat.commands.ResourceLookupRule
- net.minecraft.util.parsing.packrat.commands.StringReaderParserState
- net.minecraft.util.parsing.packrat.commands.StringReaderTerms$TerminalCharacter
- net.minecraft.util.parsing.packrat.commands.TagParseRule
- net.minecraft.util.parsing.packrat.Control
- net.minecraft.util.parsing.packrat.ErrorCollector
- net.minecraft.util.parsing.packrat.ErrorEntry
- net.minecraft.util.parsing.packrat.package-info
- net.minecraft.util.parsing.packrat.ParseState$CacheEntry
- net.minecraft.util.parsing.packrat.Rule
- net.minecraft.util.parsing.packrat.Rule$SimpleRuleAction
- net.minecraft.util.parsing.packrat.Scope
- net.minecraft.util.parsing.packrat.Term
- net.minecraft.util.parsing.packrat.Term$2
- net.minecraft.util.parsing.packrat.Term$Marker
- net.minecraft.util.parsing.packrat.Term$Reference
- net.minecraft.util.ParticleUtils
+ net.minecraft.util.PngInfo
- net.minecraft.util.ProblemReporter
+ net.minecraft.util.ProblemReporter$Collector
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.jfr.callback.package-info
+ net.minecraft.util.profiling.jfr.callback.ProfiledDuration
- net.minecraft.util.profiling.jfr.Environment
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
+ net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent
- net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent$Fields
+ net.minecraft.util.profiling.jfr.event.ChunkRegionReadEvent
- net.minecraft.util.profiling.jfr.event.ChunkRegionWriteEvent
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
+ net.minecraft.util.profiling.jfr.event.package-info
- net.minecraft.util.profiling.jfr.event.PacketEvent
+ net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
- net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
+ net.minecraft.util.profiling.jfr.event.PacketSentEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
- net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
+ net.minecraft.util.profiling.jfr.JfrProfiler
- net.minecraft.util.profiling.jfr.JfrProfiler$1
+ net.minecraft.util.profiling.jfr.JvmProfiler
- net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
- net.minecraft.util.profiling.jfr.package-info
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
- net.minecraft.util.profiling.jfr.parse.JfrStatsResult
+ net.minecraft.util.profiling.jfr.parse.package-info
+ net.minecraft.util.profiling.jfr.Percentiles
- net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
+ net.minecraft.util.profiling.jfr.serialize.package-info
- net.minecraft.util.profiling.jfr.stats.ChunkGenStat
+ net.minecraft.util.profiling.jfr.stats.ChunkIdentification
- net.minecraft.util.profiling.jfr.stats.CpuLoadStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
- net.minecraft.util.profiling.jfr.stats.IoSummary
+ net.minecraft.util.profiling.jfr.stats.IoSummary$CountAndSize
- net.minecraft.util.profiling.jfr.stats.package-info
- net.minecraft.util.profiling.jfr.stats.PacketIdentification
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
+ net.minecraft.util.profiling.jfr.stats.TickTimeStat
- net.minecraft.util.profiling.jfr.stats.TimedStat
+ net.minecraft.util.profiling.jfr.stats.TimedStatSummary
- net.minecraft.util.profiling.jfr.SummaryReporter
+ net.minecraft.util.profiling.metrics.MetricCategory
- net.minecraft.util.profiling.metrics.MetricSampler
+ net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
- net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
+ net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
- net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ net.minecraft.util.profiling.metrics.MetricsRegistry
- net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ net.minecraft.util.profiling.metrics.MetricsSamplerProvider
+ net.minecraft.util.profiling.metrics.package-info
- net.minecraft.util.profiling.metrics.ProfilerMeasured
- net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.package-info
+ net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- net.minecraft.util.profiling.metrics.storage.MetricsPersister
- net.minecraft.util.profiling.metrics.storage.package-info
+ net.minecraft.util.profiling.metrics.storage.RecordedDeviation
+ net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.ProgressListener
- net.minecraft.util.random.package-info
- net.minecraft.util.random.SimpleWeightedRandomList
+ net.minecraft.util.random.SimpleWeightedRandomList$Builder
- net.minecraft.util.random.Weight
+ net.minecraft.util.random.WeightedEntry
- net.minecraft.util.random.WeightedEntry$IntrusiveBase
+ net.minecraft.util.random.WeightedEntry$Wrapper
- net.minecraft.util.random.WeightedRandom
+ net.minecraft.util.random.WeightedRandomList
+ net.minecraft.util.RandomSource
- net.minecraft.util.ResourceLocationPattern
+ net.minecraft.util.SegmentedAnglePrecision
- net.minecraft.util.SequencedPriorityIterator
+ net.minecraft.util.SignatureUpdater
- net.minecraft.util.SignatureUpdater$Output
+ net.minecraft.util.SignatureValidator
- net.minecraft.util.Signer
+ net.minecraft.util.SimpleBitStorage
- net.minecraft.util.SimpleBitStorage$InitializationException
+ net.minecraft.util.SingleKeyCache
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.SpawnUtil
- net.minecraft.util.SpawnUtil$Strategy
+ net.minecraft.util.StringDecomposer
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringRepresentable$1
- net.minecraft.util.StringRepresentable$EnumCodec
+ net.minecraft.util.StringRepresentable$StringRepresentableCodec
- net.minecraft.util.StringUtil
+ net.minecraft.util.TaskChainer
- net.minecraft.util.TaskChainer$1
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeSource
+ net.minecraft.util.TimeSource$NanoTimeSource
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.ToFloatFunction$1
+ net.minecraft.util.ToFloatFunction$2
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.valueproviders.BiasedToBottomInt
+ net.minecraft.util.valueproviders.ClampedInt
- net.minecraft.util.valueproviders.ClampedNormalFloat
+ net.minecraft.util.valueproviders.ClampedNormalInt
- net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.IntProviderType
- net.minecraft.util.valueproviders.MultipliedFloats
- net.minecraft.util.valueproviders.package-info
+ net.minecraft.util.valueproviders.SampledFloat
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$AbstractUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$ChunkUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$DimensionToUpgrade
+ net.minecraft.util.worldupdate.WorldUpgrader$EntityUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$FileToUpgrade
+ net.minecraft.util.worldupdate.WorldUpgrader$PoiUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
+ net.minecraft.util.ZeroBitStorage
- net.minecraft.world.BossEvent
+ net.minecraft.world.BossEvent$BossBarColor
- net.minecraft.world.BossEvent$BossBarOverlay
+ net.minecraft.world.Clearable
- net.minecraft.world.CompoundContainer
+ net.minecraft.world.Container
- net.minecraft.world.ContainerHelper
+ net.minecraft.world.ContainerListener
- net.minecraft.world.Containers
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageEffects
- net.minecraft.world.damagesource.DamageScaling
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.DamageSource$1
+ net.minecraft.world.damagesource.DamageSources
- net.minecraft.world.damagesource.DamageType
+ net.minecraft.world.damagesource.DamageTypes
- net.minecraft.world.damagesource.DeathMessageType
+ net.minecraft.world.damagesource.FallLocation
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsorptionMobEffect
- net.minecraft.world.effect.BadOmenMobEffect
+ net.minecraft.world.effect.HealOrHarmMobEffect
- net.minecraft.world.effect.HungerMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffect$AttributeTemplate
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffectInstance$BlendState
+ net.minecraft.world.effect.MobEffectInstance$Details
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
- net.minecraft.world.effect.PoisonMobEffect
+ net.minecraft.world.effect.RegenerationMobEffect
- net.minecraft.world.effect.SaturationMobEffect
+ net.minecraft.world.effect.WitherMobEffect
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AnimalPanic
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorControl
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
+ net.minecraft.world.entity.ai.behavior.Croak
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
- net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
- net.minecraft.world.entity.ai.behavior.declarative.package-info
+ net.minecraft.world.entity.ai.behavior.declarative.Trigger
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToTargetLocation
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LongJumpUtil
+ net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
- net.minecraft.world.entity.ai.behavior.LookAtTargetSink
+ net.minecraft.world.entity.ai.behavior.MeleeAttack
- net.minecraft.world.entity.ai.behavior.Mount
+ net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
- net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.OneShot
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomLookAround
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StayCloseToTarget
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TriggerGate
+ net.minecraft.world.entity.ai.behavior.TryFindLand
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.warden.Digging
+ net.minecraft.world.entity.ai.behavior.warden.Emerging
- net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
+ net.minecraft.world.entity.ai.behavior.warden.package-info
+ net.minecraft.world.entity.ai.behavior.warden.Roar
- net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
+ net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
- net.minecraft.world.entity.ai.behavior.warden.Sniffing
+ net.minecraft.world.entity.ai.behavior.warden.SonicBoom
- net.minecraft.world.entity.ai.behavior.warden.TryToSniff
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
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
- net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
+ net.minecraft.world.entity.ai.goal.DolphinJumpGoal
- net.minecraft.world.entity.ai.goal.DoorInteractGoal
+ net.minecraft.world.entity.ai.goal.EatBlockGoal
- net.minecraft.world.entity.ai.goal.FleeSunGoal
+ net.minecraft.world.entity.ai.goal.FloatGoal
- net.minecraft.world.entity.ai.goal.FollowBoatGoal
+ net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
- net.minecraft.world.entity.ai.goal.FollowMobGoal
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.ai.goal.RandomStandGoal
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
- net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
+ net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
- net.minecraft.world.entity.ai.goal.target.package-info
- net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
+ net.minecraft.world.entity.ai.goal.target.TargetGoal
+ net.minecraft.world.entity.ai.goal.TemptGoal
- net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
+ net.minecraft.world.entity.ai.goal.TryFindWaterGoal
- net.minecraft.world.entity.ai.goal.UseItemGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
+ net.minecraft.world.entity.ai.goal.WrappedGoal
- net.minecraft.world.entity.ai.goal.ZombieAttackGoal
+ net.minecraft.world.entity.ai.gossip.GossipContainer
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
- net.minecraft.world.entity.ai.sensing.BreezeAttackEntitySensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
+ net.minecraft.world.entity.ai.sensing.MobSensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
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
- net.minecraft.world.entity.ai.sensing.WardenEntitySensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
- net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.poi.PoiTypes
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.allay.Allay
- net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
+ net.minecraft.world.entity.animal.allay.Allay$VibrationUser
- net.minecraft.world.entity.animal.allay.AllayAi
+ net.minecraft.world.entity.animal.allay.package-info
- net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.armadillo.Armadillo
+ net.minecraft.world.entity.animal.armadillo.Armadillo$1
- net.minecraft.world.entity.animal.armadillo.Armadillo$2
+ net.minecraft.world.entity.animal.armadillo.Armadillo$ArmadilloState
- net.minecraft.world.entity.animal.armadillo.Armadillo$ArmadilloState$1
+ net.minecraft.world.entity.animal.armadillo.Armadillo$ArmadilloState$2
- net.minecraft.world.entity.animal.armadillo.Armadillo$ArmadilloState$3
+ net.minecraft.world.entity.animal.armadillo.Armadillo$ArmadilloState$4
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi
+ net.minecraft.world.entity.animal.armadillo.ArmadilloAi$1
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi$ArmadilloBallUp
+ net.minecraft.world.entity.animal.armadillo.ArmadilloAi$ArmadilloPanic
- net.minecraft.world.entity.animal.armadillo.package-info
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
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
- net.minecraft.world.entity.animal.camel.Camel
+ net.minecraft.world.entity.animal.camel.Camel$CamelBodyRotationControl
- net.minecraft.world.entity.animal.camel.Camel$CamelLookControl
+ net.minecraft.world.entity.animal.camel.Camel$CamelMoveControl
- net.minecraft.world.entity.animal.camel.CamelAi
+ net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
- net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
+ net.minecraft.world.entity.animal.camel.package-info
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.CatVariant
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
+ net.minecraft.world.entity.animal.Fox$FaceplantGoal
- net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
+ net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
- net.minecraft.world.entity.animal.Fox$FoxBreedGoal
+ net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
- net.minecraft.world.entity.animal.Fox$FoxFloatGoal
+ net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
- net.minecraft.world.entity.animal.Fox$FoxGroupData
+ net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
- net.minecraft.world.entity.animal.Fox$FoxLookControl
+ net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
- net.minecraft.world.entity.animal.Fox$FoxMoveControl
+ net.minecraft.world.entity.animal.Fox$FoxPanicGoal
- net.minecraft.world.entity.animal.Fox$FoxPounceGoal
+ net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
- net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
+ net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
- net.minecraft.world.entity.animal.Fox$SeekShelterGoal
+ net.minecraft.world.entity.animal.Fox$SleepGoal
- net.minecraft.world.entity.animal.Fox$StalkPreyGoal
+ net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.frog.Frog
+ net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
- net.minecraft.world.entity.animal.frog.Frog$FrogNodeEvaluator
+ net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
- net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
+ net.minecraft.world.entity.animal.frog.ShootTongue
- net.minecraft.world.entity.animal.frog.ShootTongue$1
+ net.minecraft.world.entity.animal.frog.ShootTongue$State
- net.minecraft.world.entity.animal.frog.Tadpole
+ net.minecraft.world.entity.animal.frog.TadpoleAi
- net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.GoatAi
+ net.minecraft.world.entity.animal.goat.package-info
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse$2
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
- net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
+ net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
- net.minecraft.world.entity.animal.horse.Llama$Variant
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
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
- net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Parrot$Variant
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Rabbit$Variant
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.sniffer.package-info
+ net.minecraft.world.entity.animal.sniffer.Sniffer
- net.minecraft.world.entity.animal.sniffer.Sniffer$1
+ net.minecraft.world.entity.animal.sniffer.Sniffer$State
- net.minecraft.world.entity.animal.sniffer.SnifferAi
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$1
- net.minecraft.world.entity.animal.sniffer.SnifferAi$2
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$3
- net.minecraft.world.entity.animal.sniffer.SnifferAi$Digging
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$FeelingHappy
- net.minecraft.world.entity.animal.sniffer.SnifferAi$FinishedDigging
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$Scenting
- net.minecraft.world.entity.animal.sniffer.SnifferAi$Searching
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$Sniffing
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$Base
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.TropicalFish$Variant
- net.minecraft.world.entity.animal.Turtle
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
+ net.minecraft.world.entity.animal.Wolf$WolfPackData
- net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
+ net.minecraft.world.entity.animal.WolfVariant
- net.minecraft.world.entity.animal.WolfVariants
+ net.minecraft.world.entity.AnimationState
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Attackable
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
- net.minecraft.world.entity.Crackiness
+ net.minecraft.world.entity.Crackiness$Level
- net.minecraft.world.entity.decoration.ArmorStand
+ net.minecraft.world.entity.decoration.ArmorStand$1
- net.minecraft.world.entity.decoration.GlowItemFrame
+ net.minecraft.world.entity.decoration.HangingEntity
- net.minecraft.world.entity.decoration.HangingEntity$1
+ net.minecraft.world.entity.decoration.ItemFrame
- net.minecraft.world.entity.decoration.ItemFrame$1
+ net.minecraft.world.entity.decoration.ItemFrame$2
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.decoration.PaintingVariant
+ net.minecraft.world.entity.decoration.PaintingVariants
- net.minecraft.world.entity.Display
+ net.minecraft.world.entity.Display$1
- net.minecraft.world.entity.Display$BillboardConstraints
+ net.minecraft.world.entity.Display$BlockDisplay
- net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
+ net.minecraft.world.entity.Display$ColorInterpolator
- net.minecraft.world.entity.Display$FloatInterpolator
+ net.minecraft.world.entity.Display$GenericInterpolator
- net.minecraft.world.entity.Display$IntInterpolator
+ net.minecraft.world.entity.Display$ItemDisplay
- net.minecraft.world.entity.Display$ItemDisplay$1
+ net.minecraft.world.entity.Display$ItemDisplay$ItemRenderState
- net.minecraft.world.entity.Display$LinearFloatInterpolator
+ net.minecraft.world.entity.Display$LinearIntInterpolator
- net.minecraft.world.entity.Display$PosRotInterpolationTarget
+ net.minecraft.world.entity.Display$RenderState
- net.minecraft.world.entity.Display$TextDisplay
+ net.minecraft.world.entity.Display$TextDisplay$Align
- net.minecraft.world.entity.Display$TextDisplay$CachedInfo
+ net.minecraft.world.entity.Display$TextDisplay$CachedLine
- net.minecraft.world.entity.Display$TextDisplay$LineSplitter
+ net.minecraft.world.entity.Display$TextDisplay$TextRenderState
- net.minecraft.world.entity.Display$TransformationInterpolator
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.Entity$MovementEmission
+ net.minecraft.world.entity.Entity$RemovalReason
- net.minecraft.world.entity.EntityAttachment
+ net.minecraft.world.entity.EntityAttachment$Fallback
- net.minecraft.world.entity.EntityAttachments
+ net.minecraft.world.entity.EntityAttachments$Builder
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
- net.minecraft.world.entity.EquipmentSlotGroup
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.Interaction
+ net.minecraft.world.entity.Interaction$PlayerAction
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.ItemEntity$1
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.Bogged
+ net.minecraft.world.entity.monster.breeze.Breeze
- net.minecraft.world.entity.monster.breeze.Breeze$1
+ net.minecraft.world.entity.monster.breeze.BreezeAi
- net.minecraft.world.entity.monster.breeze.BreezeAi$SlideToTargetSink
+ net.minecraft.world.entity.monster.breeze.BreezeUtil
- net.minecraft.world.entity.monster.breeze.LongJump
- net.minecraft.world.entity.monster.breeze.package-info
+ net.minecraft.world.entity.monster.breeze.Shoot
- net.minecraft.world.entity.monster.breeze.ShootWhenStuck
+ net.minecraft.world.entity.monster.breeze.Slide
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
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Shulker
+ net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
+ net.minecraft.world.entity.monster.Silverfish
- net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- net.minecraft.world.entity.monster.Skeleton
+ net.minecraft.world.entity.monster.Slime
- net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
+ net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
- net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ net.minecraft.world.entity.monster.Slime$SlimeMoveControl
- net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager
- net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ net.minecraft.world.entity.monster.Spider
- net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
+ net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
- net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
+ net.minecraft.world.entity.monster.Stray
- net.minecraft.world.entity.monster.Strider
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
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.Warden$VibrationUser
- net.minecraft.world.entity.monster.warden.WardenAi
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$FailureItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TypeSpecificTrade
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$2
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.ProfileKeyPair
+ net.minecraft.world.entity.player.ProfilePublicKey
- net.minecraft.world.entity.player.ProfilePublicKey$Data
+ net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.AbstractArrow
- net.minecraft.world.entity.projectile.AbstractArrow$1
+ net.minecraft.world.entity.projectile.AbstractArrow$Pickup
- net.minecraft.world.entity.projectile.AbstractHurtingProjectile
+ net.minecraft.world.entity.projectile.Arrow
- net.minecraft.world.entity.projectile.DragonFireball
+ net.minecraft.world.entity.projectile.EvokerFangs
- net.minecraft.world.entity.projectile.EyeOfEnder
+ net.minecraft.world.entity.projectile.Fireball
- net.minecraft.world.entity.projectile.FireworkRocketEntity
+ net.minecraft.world.entity.projectile.FishingHook
- net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$FishHookState
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.projectile.ItemSupplier
- net.minecraft.world.entity.projectile.LargeFireball
+ net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
- net.minecraft.world.entity.projectile.Projectile
+ net.minecraft.world.entity.projectile.ProjectileDeflection
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
- net.minecraft.world.entity.projectile.windcharge.AbstractWindCharge
+ net.minecraft.world.entity.projectile.windcharge.AbstractWindCharge$WindChargeDamageCalculator
- net.minecraft.world.entity.projectile.windcharge.BreezeWindCharge
+ net.minecraft.world.entity.projectile.windcharge.WindCharge
- net.minecraft.world.entity.projectile.windcharge.WindCharge$WindChargePlayerDamageCalculator
- net.minecraft.world.entity.projectile.WitherSkull
+ net.minecraft.world.entity.raid.package-info
+ net.minecraft.world.entity.raid.Raid
- net.minecraft.world.entity.raid.Raid$1
- net.minecraft.world.entity.raid.Raid$RaiderType
+ net.minecraft.world.entity.raid.Raid$RaidStatus
+ net.minecraft.world.entity.raid.Raider
- net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
+ net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- net.minecraft.world.entity.raid.Raider$RaiderCelebration
+ net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
- net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.RelativeMovement
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.schedule.Activity
+ net.minecraft.world.entity.schedule.Keyframe
- net.minecraft.world.entity.schedule.package-info
- net.minecraft.world.entity.schedule.Schedule
+ net.minecraft.world.entity.schedule.ScheduleBuilder
- net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
+ net.minecraft.world.entity.schedule.Timeline
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacementType
- net.minecraft.world.entity.SpawnPlacementTypes
+ net.minecraft.world.entity.SpawnPlacementTypes$1
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.Targeting
+ net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.VariantHolder
+ net.minecraft.world.entity.vehicle.AbstractMinecart
- net.minecraft.world.entity.vehicle.AbstractMinecart$1
+ net.minecraft.world.entity.vehicle.AbstractMinecart$Type
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.ChestBoat
- net.minecraft.world.entity.vehicle.ChestBoat$1
+ net.minecraft.world.entity.vehicle.ContainerEntity
- net.minecraft.world.entity.vehicle.ContainerEntity$1
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
- net.minecraft.world.entity.vehicle.package-info
+ net.minecraft.world.entity.vehicle.VehicleEntity
+ net.minecraft.world.entity.WalkAnimationState
+ net.minecraft.world.flag.FeatureElement
- net.minecraft.world.flag.FeatureFlag
+ net.minecraft.world.flag.FeatureFlagRegistry
- net.minecraft.world.flag.FeatureFlagRegistry$Builder
+ net.minecraft.world.flag.FeatureFlags
+ net.minecraft.world.flag.FeatureFlagSet
- net.minecraft.world.flag.FeatureFlagUniverse
- net.minecraft.world.flag.package-info
+ net.minecraft.world.food.FoodConstants
- net.minecraft.world.food.FoodData
+ net.minecraft.world.food.FoodProperties
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.inventory.AnvilMenu$1
- net.minecraft.world.inventory.BeaconMenu
+ net.minecraft.world.inventory.BeaconMenu$1
- net.minecraft.world.inventory.BeaconMenu$PaymentSlot
+ net.minecraft.world.inventory.BlastFurnaceMenu
- net.minecraft.world.inventory.BrewingStandMenu
+ net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
- net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
+ net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
- net.minecraft.world.inventory.CartographyTableMenu
+ net.minecraft.world.inventory.CartographyTableMenu$1
- net.minecraft.world.inventory.CartographyTableMenu$2
+ net.minecraft.world.inventory.CartographyTableMenu$3
- net.minecraft.world.inventory.CartographyTableMenu$4
+ net.minecraft.world.inventory.CartographyTableMenu$5
- net.minecraft.world.inventory.ChestMenu
+ net.minecraft.world.inventory.ClickAction
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
- net.minecraft.world.inventory.ContainerSynchronizer
+ net.minecraft.world.inventory.CrafterMenu
- net.minecraft.world.inventory.CrafterSlot
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
- net.minecraft.world.inventory.ItemCombinerMenu$3
+ net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
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
+ net.minecraft.world.inventory.NonInteractiveResultSlot
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeCraftingHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SlotRange
+ net.minecraft.world.inventory.SlotRange$1
- net.minecraft.world.inventory.SlotRanges
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.inventory.TransientCraftingContainer
- net.minecraft.world.item.AdventureModePredicate
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.PotionContents
- net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.AnimalArmorItem
+ net.minecraft.world.item.AnimalArmorItem$BodyType
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorItem$Type
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterial$Layer
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
- net.minecraft.world.item.armortrim.ArmorTrim
- net.minecraft.world.item.armortrim.package-info
+ net.minecraft.world.item.armortrim.TrimMaterial
- net.minecraft.world.item.armortrim.TrimMaterials
+ net.minecraft.world.item.armortrim.TrimPattern
- net.minecraft.world.item.armortrim.TrimPatterns
+ net.minecraft.world.item.armortrim.UpdateOneTwentyOneArmorTrims
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BoneMealItem$1
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BrushItem
+ net.minecraft.world.item.BrushItem$1
- net.minecraft.world.item.BrushItem$DustParticlesDelta
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.component.BlockItemStateProperties
- net.minecraft.world.item.component.BookContent
+ net.minecraft.world.item.component.BundleContents
- net.minecraft.world.item.component.BundleContents$Mutable
+ net.minecraft.world.item.component.ChargedProjectiles
- net.minecraft.world.item.component.CustomData
+ net.minecraft.world.item.component.CustomModelData
- net.minecraft.world.item.component.DebugStickState
+ net.minecraft.world.item.component.DyedItemColor
- net.minecraft.world.item.component.FireworkExplosion
+ net.minecraft.world.item.component.FireworkExplosion$Shape
- net.minecraft.world.item.component.Fireworks
+ net.minecraft.world.item.component.ItemAttributeModifiers
- net.minecraft.world.item.component.ItemAttributeModifiers$1
+ net.minecraft.world.item.component.ItemAttributeModifiers$Builder
- net.minecraft.world.item.component.ItemAttributeModifiers$Entry
+ net.minecraft.world.item.component.ItemContainerContents
- net.minecraft.world.item.component.ItemContainerContents$Slot
+ net.minecraft.world.item.component.ItemLore
- net.minecraft.world.item.component.LodestoneTracker
+ net.minecraft.world.item.component.MapDecorations
- net.minecraft.world.item.component.MapDecorations$Entry
+ net.minecraft.world.item.component.MapItemColor
- net.minecraft.world.item.component.MapPostProcessing
+ net.minecraft.world.item.component.package-info
+ net.minecraft.world.item.component.ResolvableProfile
- net.minecraft.world.item.component.SeededContainerLoot
+ net.minecraft.world.item.component.SuspiciousStewEffects
- net.minecraft.world.item.component.SuspiciousStewEffects$Entry
- net.minecraft.world.item.component.Tool$Rule
+ net.minecraft.world.item.component.TooltipProvider
- net.minecraft.world.item.component.Unbreakable
+ net.minecraft.world.item.component.WritableBookContent
- net.minecraft.world.item.component.WrittenBookContent
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.AbstractCookingRecipe$Factory
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CookingBookCategory
+ net.minecraft.world.item.crafting.CraftingBookCategory
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.DecoratedPotRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeCache
- net.minecraft.world.item.crafting.RecipeCache$Entry
+ net.minecraft.world.item.crafting.RecipeHolder
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeManager$1
- net.minecraft.world.item.crafting.RecipeManager$CachedCheck
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapedRecipePattern
- net.minecraft.world.item.crafting.ShapedRecipePattern$Data
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
+ net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Factory
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmithingRecipe
+ net.minecraft.world.item.crafting.SmithingTransformRecipe
- net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
+ net.minecraft.world.item.crafting.SmithingTrimRecipe
- net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$Builder
+ net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
- net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
- net.minecraft.world.item.CreativeModeTab$Output
+ net.minecraft.world.item.CreativeModeTab$Row
- net.minecraft.world.item.CreativeModeTab$TabVisibility
+ net.minecraft.world.item.CreativeModeTab$Type
- net.minecraft.world.item.CreativeModeTabs
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DiscFragmentItem
+ net.minecraft.world.item.DispensibleContainerItem
- net.minecraft.world.item.DoubleHighBlockItem
+ net.minecraft.world.item.DyeColor
- net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Cost
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.EndCrystalItem
- net.minecraft.world.item.EnderEyeItem
+ net.minecraft.world.item.EnderpearlItem
- net.minecraft.world.item.Equipable
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkStarItem
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.FoodOnAStickItem
- net.minecraft.world.item.GameMasterBlockItem
+ net.minecraft.world.item.GlowInkSacItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HangingSignItem
- net.minecraft.world.item.HoeItem
+ net.minecraft.world.item.HoneyBottleItem
- net.minecraft.world.item.HoneycombItem
+ net.minecraft.world.item.InkSacItem
- net.minecraft.world.item.Instrument
+ net.minecraft.world.item.InstrumentItem
- net.minecraft.world.item.Instruments
+ net.minecraft.world.item.Item
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStackLinkedSet
+ net.minecraft.world.item.ItemStackLinkedSet$1
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MaceItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MapItem$1
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlaceOnWaterBlockItem
+ net.minecraft.world.item.PlayerHeadItem
- net.minecraft.world.item.PotionItem
+ net.minecraft.world.item.ProjectileWeaponItem
- net.minecraft.world.item.Rarity
+ net.minecraft.world.item.RecordItem
- net.minecraft.world.item.SaddleItem
+ net.minecraft.world.item.ScaffoldingBlockItem
- net.minecraft.world.item.ServerItemCooldowns
+ net.minecraft.world.item.ShearsItem
- net.minecraft.world.item.ShieldItem
+ net.minecraft.world.item.ShovelItem
- net.minecraft.world.item.SignApplicator
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SmithingTemplateItem
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
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.WindChargeItem
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.ItemInteractionResult
+ net.minecraft.world.ItemInteractionResult$1
- net.minecraft.world.level.saveddata.maps.MapDecorationTypes
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapId
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DataVersion
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.FileNameDateFormatter
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelDataAndDimensions
+ net.minecraft.world.level.storage.LevelResource
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
+ net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.LevelSummary$BackupStatus
+ net.minecraft.world.level.storage.LevelSummary$CorruptedLevelSummary
- net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
+ net.minecraft.world.level.storage.LevelVersion
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.NestedLootTable
+ net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$1
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Source
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.ToggleTooltips$ComponentToggle
+ net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
+ net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootDataId
+ net.minecraft.world.level.storage.loot.LootDataManager$1
+ net.minecraft.world.level.storage.loot.LootDataType
- net.minecraft.world.level.storage.loot.LootDataType$Validator
+ net.minecraft.world.level.storage.loot.LootParams
- net.minecraft.world.level.storage.loot.LootParams$Builder
+ net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.ValidationContext
- net.minecraft.world.level.storage.PlayerDataStorage
+ net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
+ net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
- net.minecraft.world.RandomizableContainer
+ net.minecraft.world.RandomSequence
- net.minecraft.world.RandomSequences
+ net.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.TickRateManager
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.gui.screens.RealmsPlayerScreen +1M
```
```
net.minecraft.Util +1M
```
```
XXX.minecraft.advancements.Advancement +2M -2M
```
```
XXX.minecraft.advancements.AdvancementRewards$Builder +2M -2M
```
```
XXX.minecraft.advancements.CriteriaTriggers +2P
```
```
XXX.advancements.critereon.LootTableTrigger +2M -2M
```
```
XXX.advancements.critereon.NbtPredicate +2P
```
```
XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance +1M
```
```
XXX.minecraft.client.Minecraft +1M | +1P
```
```
XXX.client.gui.Gui +2M
```
```
XXX.client.gui.MapRenderer +1M -2M | +1P -2P
```
```
XXX.screens.worldselection.ExperimentsScreen +1M | +1P
```
```
XXX.renderer.item.ItemProperties +1M -1M
```
```
XXX.core.registries.BuiltInRegistries +4M -5M | +1P
```
```
XXX.core.registries.Registries +4P
```
```
XXX.minecraft.data.Main +1M
```
```
XXX.data.loot.LootTableProvider +4M -3M
```
```
XXX.data.worldgen.ProcessorLists +1M -1M
```
```
XXX.minecraft.resources.ResourceKey +1M
```
```
XXX.minecraft.resources.ResourceLocation +2M
```
```
XXX.minecraft.server.MinecraftServer +2M -2M
```
```
XXX.world.item.Item$Properties +1M -1M | -5P
```
```
XXX.world.item.ItemStack +2M -1M
```
```
XXX.item.enchantment.BindingCurseEnchantment +1M -3M
```
```
XXX.item.enchantment.DigDurabilityEnchantment +1M -5M
```
```
XXX.item.enchantment.EnchantmentHelper +1M
```
```
XXX.item.enchantment.FrostWalkerEnchantment +1M -4M
```
```
XXX.item.enchantment.ProtectionEnchantment +1M -4M
```
```
XXX.item.enchantment.ThornsEnchantment +1M -4M
```
```
XXX.block.entity.DecoratedPotBlockEntity +2M -2M | +1P -1P
```
```
XXX.block.entity.RandomizableContainerBlockEntity +2M -2M | +1P -1P
```
```
XXX.entity.trialspawner.TrialSpawner +1M -1M
```
```
XXX.entity.trialspawner.TrialSpawnerState +1M -1M
```
```
XXX.entity.vault.VaultBlockEntity$Server +1M -1M
```
```
XXX.entity.vault.VaultConfig +3M -3M | +1P -1P
```
```
XXX.levelgen.structure.StructurePiece +3M -3M
```
```
XXX.structure.structures.MineshaftPieces$MineShaftCorridor +1M -1M
```
```
XXX.rule.blockentity.AppendLoot +2M -2M | +1P -1P
```
```
XXX.saveddata.maps.MapBanner +1M -1M
```
```
XXX.saveddata.maps.MapDecoration +3M -3M | +1P -1P
```
```
XXX.loot.functions.ExplorationMapFunction +2M -2M | +2P -2P
```
```
XXX.loot.functions.ListOperation +4M
```
```
XXX.loot.functions.LootItemFunctions +2P
```
```
XXX.loot.functions.SetContainerLootTable +6M -6M | +1P -1P
```
```
XXX.loot.functions.SetLoreFunction$Builder +1M -1M | +1P -1P
```

</details>











































































































































<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
</summary>

```diff
- void repopulateInvitedList()
```

</details>









































<details>
<summary>
net.minecraft.Util
</summary>

```diff
- List copyAndAdd(Object,List)
```

</details>






<details>
<summary>
net.minecraft.advancements.Advancement
</summary>

```diff
- void lambda$validate$9(ProblemReporter,HolderGetter$Provider,String,Criterion)
+ void lambda$validate$9(ProblemReporter,LootDataResolver,String,Criterion)
- void validate(ProblemReporter,HolderGetter$Provider)
+ void validate(ProblemReporter,LootDataResolver)
```

</details>



<details>
<summary>
net.minecraft.advancements.AdvancementRewards$Builder
</summary>

```diff
- AdvancementRewards$Builder addLootTable(ResourceKey)
+ AdvancementRewards$Builder addLootTable(ResourceLocation)
- AdvancementRewards$Builder loot(ResourceKey)
+ AdvancementRewards$Builder loot(ResourceLocation)
```

</details>



















































<details>
<summary>
net.minecraft.advancements.critereon.LootTableTrigger
</summary>

```diff
- boolean lambda$trigger$0(ResourceKey,LootTableTrigger$TriggerInstance)
+ boolean lambda$trigger$0(ResourceLocation,LootTableTrigger$TriggerInstance)
- void trigger(ServerPlayer,ResourceKey)
+ void trigger(ServerPlayer,ResourceLocation)
```

</details>












<details>
<summary>
net.minecraft.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
</summary>

```diff
- Criterion crafterCraftedItem(ResourceLocation)
```

</details>






























<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- MapDecorationTextureManager getMapDecorationTextures()
```

</details>














































<details>
<summary>
net.minecraft.client.gui.Gui
</summary>

```diff
- void renderArmor(GuiGraphics,Player,int,int,int,int)
- void renderFood(GuiGraphics,Player,int,int)
```

</details>



<details>
<summary>
net.minecraft.client.gui.MapRenderer
</summary>

```diff
+ void <clinit>()
- void <init>(TextureManager,MapDecorationTextureManager)
+ void <init>(TextureManager)
```

</details>


























































































































































































































































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.ExperimentsScreen
</summary>

```diff
- Component getNarrationMessage()
```

</details>






























































































































































































































































































































































































































































<details>
<summary>
net.minecraft.client.renderer.item.ItemProperties
</summary>

```diff
+ ItemPropertyFunction getProperty(Item,ResourceLocation)
- ItemPropertyFunction getProperty(ItemStack,ResourceLocation)
```

</details>









































<details>
<summary>
net.minecraft.core.registries.BuiltInRegistries
</summary>

```diff
- Object lambda$internalRegister$49(BuiltInRegistries$RegistryBootstrap,WritableRegistry)
+ Object lambda$internalRegister$50(BuiltInRegistries$RegistryBootstrap,WritableRegistry)
+ Object lambda$static$48(Registry)
- String lambda$internalRegister$48(ResourceKey)
+ String lambda$internalRegister$49(ResourceKey)
- void lambda$createContents$50(ResourceLocation,Supplier)
+ void lambda$createContents$51(ResourceLocation,Supplier)
- void lambda$validate$51(Registry,Registry)
+ void lambda$validate$52(Registry,Registry)
```

</details>









<details>
<summary>
net.minecraft.data.Main
</summary>

```diff
- UpdateOneTwentyOneStructureTagsProvider lambda$createStandardGenerator$12(CompletableFuture,TagsProvider,PackOutput)
```

</details>











<details>
<summary>
net.minecraft.data.loot.LootTableProvider
</summary>

```diff
- ResourceLocation sequenceIdForLootTable(ResourceKey)
- void lambda$run$1(Map,LootTableProvider$SubProviderEntry,WritableRegistry,ResourceKey,LootTable$Builder)
+ void lambda$run$1(Map,Map,LootTableProvider$SubProviderEntry,ResourceLocation,LootTable$Builder)
+ void lambda$run$2(HolderLookup$Provider,Map,Map,LootTableProvider$SubProviderEntry)
- void lambda$run$2(HolderLookup$Provider,Map,WritableRegistry,LootTableProvider$SubProviderEntry)
- void lambda$run$3(ValidationContext,Holder$Reference)
+ void lambda$run$3(ValidationContext,ResourceLocation,LootTable)
```

</details>










<details>
<summary>
net.minecraft.data.worldgen.ProcessorLists
</summary>

```diff
- CappedProcessor trailsArchyLootProcessor(ResourceKey,int)
+ CappedProcessor trailsArchyLootProcessor(ResourceLocation,int)
```

</details>






















































































































































































































































































































































































<details>
<summary>
net.minecraft.resources.ResourceKey
</summary>

```diff
- ResourceKey registryKey()
```

</details>
<details>
<summary>
net.minecraft.resources.ResourceLocation
</summary>

```diff
- ResourceLocation readNonEmpty(StringReader)
- String readGreedy(StringReader)
```

</details>






<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- CompletionStage lambda$reloadResources$27(ImmutableList)
+ CompletionStage lambda$reloadResources$27(RegistryAccess$Frozen,ImmutableList)
+ LootDataManager getLootData()
- ReloadableServerRegistries$Holder reloadableRegistries()
```

</details>


























<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
- DataComponentMap buildAndValidateComponents()
+ Item$Properties defaultDurability(int)
```

</details>


<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- boolean canBeHurtBy(DamageSource)
+ boolean isEdible()
- void limitSize(int)
```

</details>

<details>
<summary>
net.minecraft.world.item.enchantment.BindingCurseEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.DigDurabilityEnchantment
</summary>

```diff
+ boolean canEnchant(ItemStack)
+ int getMaxCost(int)
+ int getMaxLevel()
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentHelper
</summary>

```diff
- float getSweepingDamageRatio(int)
```

</details>

<details>
<summary>
net.minecraft.world.item.enchantment.FrostWalkerEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMaxLevel()
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>

<details>
<summary>
net.minecraft.world.item.enchantment.ProtectionEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMaxLevel()
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition,ProtectionEnchantment$Type)
+ void <init>(Enchantment$Rarity,ProtectionEnchantment$Type,EquipmentSlot[])
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.ThornsEnchantment
</summary>

```diff
+ int getMaxCost(int)
+ int getMaxLevel()
+ int getMinCost(int)
- void <init>(Enchantment$EnchantmentDefinition)
+ void <init>(Enchantment$Rarity,EquipmentSlot[])
```

</details>




















































































































































































































































































<details>
<summary>
net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
</summary>

```diff
- ResourceKey getLootTable()
+ ResourceLocation getLootTable()
- void setLootTable(ResourceKey)
+ void setLootTable(ResourceLocation)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
</summary>

```diff
- ResourceKey getLootTable()
+ ResourceLocation getLootTable()
- void setLootTable(ResourceKey)
+ void setLootTable(ResourceLocation)
```

</details>














<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawner
</summary>

```diff
- void ejectReward(ServerLevel,BlockPos,ResourceKey)
+ void ejectReward(ServerLevel,BlockPos,ResourceLocation)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState
</summary>

```diff
- void lambda$tickAndGetNext$2(TrialSpawner,ServerLevel,BlockPos,ResourceKey)
+ void lambda$tickAndGetNext$2(TrialSpawner,ServerLevel,BlockPos,ResourceLocation)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Server
</summary>

```diff
- ItemStack getRandomDisplayItemFromLootTable(ServerLevel,BlockPos,ResourceKey)
+ ItemStack getRandomDisplayItemFromLootTable(ServerLevel,BlockPos,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultConfig
</summary>

```diff
- ResourceKey lootTable()
+ ResourceLocation lootTable()
- void <init>(ResourceKey,double,double,ItemStack,Optional,PlayerDetector,PlayerDetector$EntitySelector)
- void <init>(ResourceKey,double,double,ItemStack,Optional)
+ void <init>(ResourceLocation,double,double,ItemStack,Optional,PlayerDetector,PlayerDetector$EntitySelector)
+ void <init>(ResourceLocation,double,double,ItemStack,Optional)
```

</details>





















































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructurePiece
</summary>

```diff
- boolean createChest(ServerLevelAccessor,BoundingBox,RandomSource,BlockPos,ResourceKey,BlockState)
+ boolean createChest(ServerLevelAccessor,BoundingBox,RandomSource,BlockPos,ResourceLocation,BlockState)
- boolean createChest(WorldGenLevel,BoundingBox,RandomSource,int,int,int,ResourceKey)
+ boolean createChest(WorldGenLevel,BoundingBox,RandomSource,int,int,int,ResourceLocation)
- boolean createDispenser(WorldGenLevel,BoundingBox,RandomSource,int,int,int,Direction,ResourceKey)
+ boolean createDispenser(WorldGenLevel,BoundingBox,RandomSource,int,int,int,Direction,ResourceLocation)
```

</details>






































<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
</summary>

```diff
- boolean createChest(WorldGenLevel,BoundingBox,RandomSource,int,int,int,ResourceKey)
+ boolean createChest(WorldGenLevel,BoundingBox,RandomSource,int,int,int,ResourceLocation)
```

</details>







































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendLoot
</summary>

```diff
- ResourceKey lambda$static$0(AppendLoot)
+ ResourceLocation lambda$static$0(AppendLoot)
- void <init>(ResourceKey)
+ void <init>(ResourceLocation)
```

</details>













































<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapBanner
</summary>

```diff
- Holder getDecoration()
+ MapDecoration$Type getDecoration()
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapDecoration
</summary>

```diff
+ byte getImage()
- Holder type()
+ MapDecoration$Type type()
- ResourceLocation getSpriteLocation()
- void <init>(Holder,byte,byte,byte,Optional)
+ void <init>(MapDecoration$Type,byte,byte,byte,Optional)
```

</details>



<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
</summary>

```diff
- Holder lambda$static$1(ExplorationMapFunction)
+ MapDecoration$Type lambda$static$1(ExplorationMapFunction)
- void <init>(List,TagKey,Holder,byte,int,boolean)
+ void <init>(List,TagKey,MapDecoration$Type,byte,int,boolean)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ListOperation
</summary>

```diff
- Codec lambda$codec$0(ListOperation$Type)
- DataResult lambda$codec$2(int,ListOperation)
- MapCodec codec(int)
- String lambda$codec$1(int,int)
```

</details>












<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
</summary>

```diff
- LootItemConditionalFunction$Builder withLootTable(BlockEntityType,ResourceKey,long)
- LootItemConditionalFunction$Builder withLootTable(BlockEntityType,ResourceKey)
+ LootItemConditionalFunction$Builder withLootTable(BlockEntityType,ResourceLocation,long)
+ LootItemConditionalFunction$Builder withLootTable(BlockEntityType,ResourceLocation)
- LootItemFunction lambda$withLootTable$4(ResourceKey,BlockEntityType,List)
+ LootItemFunction lambda$withLootTable$4(ResourceLocation,BlockEntityType,List)
- LootItemFunction lambda$withLootTable$5(ResourceKey,long,BlockEntityType,List)
+ LootItemFunction lambda$withLootTable$5(ResourceLocation,long,BlockEntityType,List)
- ResourceKey lambda$static$0(SetContainerLootTable)
+ ResourceLocation lambda$static$0(SetContainerLootTable)
- void <init>(List,ResourceKey,long,Holder)
+ void <init>(List,ResourceLocation,long,Holder)
```

</details>




<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
</summary>

```diff
- SetLoreFunction$Builder setMode(ListOperation)
+ SetLoreFunction$Builder setReplace(boolean)
```

</details>
</details>