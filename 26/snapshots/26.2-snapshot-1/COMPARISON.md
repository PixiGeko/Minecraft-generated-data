## Comparison with [26w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/26w14a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (models)](#items-(models))
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26w14a</th><th>26.2-snapshot-1</th></tr><tr><td>DataPack version</td><td><pre>101.1</pre></td><td><pre>101.2</pre></td></tr><tr><td>ResourcePack version</td><td><pre>84.0</pre></td><td><pre>85.0</pre></td></tr><tr><td>World version</td><td><pre>5000</pre></td><td><pre>4883</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742129</pre></td><td><pre>1073742130</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ org.lwjgl:lwjgl-shaderc (natives-linux) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-windows-arm64) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-windows-x86) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-windows) V3.4.1
+ org.lwjgl:lwjgl-shaderc V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-linux) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-windows-arm64) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-windows-x86) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-windows) V3.4.1
+ org.lwjgl:lwjgl-spvc V3.4.1
+ org.lwjgl:lwjgl-vma (natives-linux) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-windows-arm64) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-windows-x86) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-windows) V3.4.1
+ org.lwjgl:lwjgl-vma V3.4.1
+ org.lwjgl:lwjgl-vulkan (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-vulkan (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-vulkan V3.4.1
```

</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:air_drag_modifier
+ minecraft:bounciness
+ minecraft:friction_modifier
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
- minecraft:copper_trap
- minecraft:exposed_copper_trap
- minecraft:iron_trap
- minecraft:oxidized_copper_trap
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
- minecraft:waxed_copper_trap
- minecraft:waxed_exposed_copper_trap
- minecraft:waxed_oxidized_copper_trap
- minecraft:waxed_weathered_copper_trap
- minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
+ minecraft:potent_sulfur
```

</details>
<details>
<summary>
block_type
</summary>

```diff
+ minecraft:potent_sulfur
- minecraft:weathering_copper_trap_door
+ minecraft:weathering_copper_trapdoor
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
- minecraft:follow
+ minecraft:sulfur_cube_content
```

</details>
<details>
<summary>
entity_sub_predicate_type
</summary>

```diff
- minecraft:living_block
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
- minecraft:crafting_grid
- minecraft:hovering_item
+ minecraft:item
- minecraft:living_block
- minecraft:living_block_command
+ minecraft:sulfur_cube
```

</details>
<details>
<summary>
game_event
</summary>

```diff
+ minecraft:bounce
```

</details>
<details>
<summary>
item
</summary>

```diff
- minecraft:attack_action
- minecraft:build_action
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
- minecraft:copper_trap
- minecraft:crafting_action
- minecraft:exposed_copper_trap
- minecraft:follow_action
- minecraft:group_action
- minecraft:highlight_action
- minecraft:iron_trap
- minecraft:move_action
- minecraft:oxidized_copper_trap
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
- minecraft:punch_action
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_cube_bucket
+ minecraft:sulfur_cube_spawn_egg
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
- minecraft:waxed_copper_trap
- minecraft:waxed_exposed_copper_trap
- minecraft:waxed_oxidized_copper_trap
- minecraft:waxed_weathered_copper_trap
- minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:noxious_gas
+ minecraft:noxious_gas_cloud
+ minecraft:sulfur_bubbles
+ minecraft:sulfur_cube_goo
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.cinnabar.break
+ minecraft:block.cinnabar.fall
+ minecraft:block.cinnabar.hit
+ minecraft:block.cinnabar.place
+ minecraft:block.cinnabar.step
+ minecraft:block.potent_sulfur.break
+ minecraft:block.potent_sulfur.fall
+ minecraft:block.potent_sulfur.hit
+ minecraft:block.potent_sulfur.noxious_gas
+ minecraft:block.potent_sulfur.place
+ minecraft:block.potent_sulfur.step
+ minecraft:block.sulfur.break
+ minecraft:block.sulfur.fall
+ minecraft:block.sulfur.hit
+ minecraft:block.sulfur.place
+ minecraft:block.sulfur.step
+ minecraft:entity.small_sulfur_cube.death
+ minecraft:entity.small_sulfur_cube.hurt
+ minecraft:entity.small_sulfur_cube.jump
+ minecraft:entity.small_sulfur_cube.squish
+ minecraft:entity.sulfur_cube.absorb
+ minecraft:entity.sulfur_cube.bounce
+ minecraft:entity.sulfur_cube.death
+ minecraft:entity.sulfur_cube.eject
+ minecraft:entity.sulfur_cube.hit
+ minecraft:entity.sulfur_cube.hurt
+ minecraft:entity.sulfur_cube.jump
+ minecraft:entity.sulfur_cube.push
+ minecraft:entity.sulfur_cube.squish
```

</details>
<details>
<summary>
trigger_type
</summary>

```diff
- minecraft:barrel_roll
- minecraft:built_house
- minecraft:built_trap
- minecraft:end_portal_crafted
- minecraft:eye_frame_combination
- minecraft:nether_portal_crafted
- minecraft:use_item
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
- minecraft:dripstone_cluster
- minecraft:pointed_dripstone
+ minecraft:sequence
+ minecraft:speleothem
+ minecraft:speleothem_cluster
+ minecraft:template
```

</details>
<details>
<summary>
worldgen/material_rule
</summary>

```diff
+ minecraft:noise_gradient
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
- minecraft:leaf_litter
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
- minecraft:copper_trap
- minecraft:exposed_copper_trap
- minecraft:iron_trap
+ minecraft:leaf_litter
- minecraft:oxidized_copper_trap
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
- minecraft:waxed_copper_trap
- minecraft:waxed_exposed_copper_trap
- minecraft:waxed_oxidized_copper_trap
- minecraft:waxed_weathered_copper_trap
- minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
- minecraft:crafting_grid
- minecraft:hovering_item
+ minecraft:item
- minecraft:living_block
- minecraft:living_block_command
+ minecraft:sulfur_cube
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:sulfur_cube
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
- minecraft:leaf_litter
```

</details>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:air_drag_modifier
+ minecraft:bounciness
+ minecraft:friction_modifier
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
- minecraft:copper_trap
- minecraft:exposed_copper_trap
- minecraft:iron_trap
- minecraft:oxidized_copper_trap
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
- minecraft:waxed_copper_trap
- minecraft:waxed_exposed_copper_trap
- minecraft:waxed_oxidized_copper_trap
- minecraft:waxed_weathered_copper_trap
- minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:potent_sulfur
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:potent_sulfur
- minecraft:weathering_copper_trap_door
+ minecraft:weathering_copper_trapdoor
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
- minecraft:follow
+ minecraft:sulfur_cube_content
```

</details>
<details>
<summary>
universal_tags/entity_sub_predicate_type.json
</summary>

```diff
- minecraft:living_block
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
- minecraft:crafting_grid
- minecraft:hovering_item
+ minecraft:item
- minecraft:living_block
- minecraft:living_block_command
+ minecraft:sulfur_cube
```

</details>
<details>
<summary>
universal_tags/game_event.json
</summary>

```diff
+ minecraft:bounce
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:attack_action
- minecraft:build_action
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
- minecraft:copper_trap
- minecraft:crafting_action
- minecraft:exposed_copper_trap
- minecraft:follow_action
- minecraft:group_action
- minecraft:highlight_action
- minecraft:iron_trap
- minecraft:move_action
- minecraft:oxidized_copper_trap
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
- minecraft:punch_action
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_cube_bucket
+ minecraft:sulfur_cube_spawn_egg
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
- minecraft:waxed_copper_trap
- minecraft:waxed_exposed_copper_trap
- minecraft:waxed_oxidized_copper_trap
- minecraft:waxed_weathered_copper_trap
- minecraft:weathered_copper_trap
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:noxious_gas
+ minecraft:noxious_gas_cloud
+ minecraft:sulfur_bubbles
+ minecraft:sulfur_cube_goo
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.cinnabar.break
+ minecraft:block.cinnabar.fall
+ minecraft:block.cinnabar.hit
+ minecraft:block.cinnabar.place
+ minecraft:block.cinnabar.step
+ minecraft:block.potent_sulfur.break
+ minecraft:block.potent_sulfur.fall
+ minecraft:block.potent_sulfur.hit
+ minecraft:block.potent_sulfur.noxious_gas
+ minecraft:block.potent_sulfur.place
+ minecraft:block.potent_sulfur.step
+ minecraft:block.sulfur.break
+ minecraft:block.sulfur.fall
+ minecraft:block.sulfur.hit
+ minecraft:block.sulfur.place
+ minecraft:block.sulfur.step
+ minecraft:entity.small_sulfur_cube.death
+ minecraft:entity.small_sulfur_cube.hurt
+ minecraft:entity.small_sulfur_cube.jump
+ minecraft:entity.small_sulfur_cube.squish
+ minecraft:entity.sulfur_cube.absorb
+ minecraft:entity.sulfur_cube.bounce
+ minecraft:entity.sulfur_cube.death
+ minecraft:entity.sulfur_cube.eject
+ minecraft:entity.sulfur_cube.hit
+ minecraft:entity.sulfur_cube.hurt
+ minecraft:entity.sulfur_cube.jump
+ minecraft:entity.sulfur_cube.push
+ minecraft:entity.sulfur_cube.squish
```

</details>
<details>
<summary>
universal_tags/trigger_type.json
</summary>

```diff
- minecraft:barrel_roll
- minecraft:built_house
- minecraft:built_trap
- minecraft:end_portal_crafted
- minecraft:eye_frame_combination
- minecraft:nether_portal_crafted
- minecraft:use_item
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:dripstone_cluster
- minecraft:pointed_dripstone
+ minecraft:sequence
+ minecraft:speleothem
+ minecraft:speleothem_cluster
+ minecraft:template
```

</details>
<details>
<summary>
universal_tags/worldgen/material_rule.json
</summary>

```diff
+ minecraft:noise_gradient
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (MODELS)</ins></b><a name="items-(models)"></a></summary>
<br/>
<details>
<summary>
Model types
</summary>

```diff
+ minecraft:composite
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
+ chiseled_cinnabar.json
+ chiseled_sulfur.json
+ cinnabar_brick_slab.json
+ cinnabar_brick_stairs.json
+ cinnabar_brick_wall.json
+ cinnabar_bricks.json
+ cinnabar_slab.json
+ cinnabar_stairs.json
+ cinnabar_wall.json
+ cinnabar.json
- copper_trap.json
- exposed_copper_trap.json
- iron_trap.json
- oxidized_copper_trap.json
+ polished_cinnabar_slab.json
+ polished_cinnabar_stairs.json
+ polished_cinnabar_wall.json
+ polished_cinnabar.json
+ polished_sulfur_slab.json
+ polished_sulfur_stairs.json
+ polished_sulfur_wall.json
+ polished_sulfur.json
+ potent_sulfur.json
+ sulfur_brick_slab.json
+ sulfur_brick_stairs.json
+ sulfur_brick_wall.json
+ sulfur_bricks.json
+ sulfur_slab.json
+ sulfur_stairs.json
+ sulfur_wall.json
+ sulfur.json
- waxed_copper_trap.json
- waxed_exposed_copper_trap.json
- waxed_oxidized_copper_trap.json
- waxed_weathered_copper_trap.json
- weathered_copper_trap.json
```

</details>
<details>
<summary>
copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26w14a</th><th>26.2-snapshot-1</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trap_door</pre></td><td><pre>minecraft:weathering_copper_trapdoor</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26w14a</th><th>26.2-snapshot-1</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trap_door</pre></td><td><pre>minecraft:weathering_copper_trapdoor</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26w14a</th><th>26.2-snapshot-1</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trap_door</pre></td><td><pre>minecraft:weathering_copper_trapdoor</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26w14a</th><th>26.2-snapshot-1</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trap_door</pre></td><td><pre>minecraft:weathering_copper_trapdoor</pre></td></tr></table>
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
+ chiseled_cinnabar_from_cinnabar_stonecutting.json
+ chiseled_cinnabar.json
+ chiseled_sulfur_from_sulfur_stonecutting.json
+ chiseled_sulfur.json
+ cinnabar_brick_slab_from_cinnabar_bricks_stonecutting.json
+ cinnabar_brick_slab_from_cinnabar_stonecutting.json
+ cinnabar_brick_slab_from_polished_cinnabar_stonecutting.json
+ cinnabar_brick_slab.json
+ cinnabar_brick_stairs_from_cinnabar_bricks_stonecutting.json
+ cinnabar_brick_stairs_from_cinnabar_stonecutting.json
+ cinnabar_brick_stairs_from_polished_cinnabar_stonecutting.json
+ cinnabar_brick_stairs.json
+ cinnabar_brick_wall_from_cinnabar_bricks_stonecutting.json
+ cinnabar_brick_wall_from_cinnabar_stonecutting.json
+ cinnabar_brick_wall_from_polished_cinnabar_stonecutting.json
+ cinnabar_brick_wall.json
+ cinnabar_bricks_from_cinnabar_stonecutting.json
+ cinnabar_bricks_from_polished_cinnabar_stonecutting.json
+ cinnabar_bricks.json
+ cinnabar_slab_from_cinnabar_stonecutting.json
+ cinnabar_slab.json
+ cinnabar_stairs_from_cinnabar_stonecutting.json
+ cinnabar_stairs.json
+ cinnabar_wall_from_cinnabar_stonecutting.json
+ cinnabar_wall.json
+ polished_cinnabar_from_cinnabar_stonecutting.json
+ polished_cinnabar_slab_from_cinnabar_stonecutting.json
+ polished_cinnabar_slab_from_polished_cinnabar_stonecutting.json
+ polished_cinnabar_slab.json
+ polished_cinnabar_stairs_from_cinnabar_stonecutting.json
+ polished_cinnabar_stairs_from_polished_cinnabar_stonecutting.json
+ polished_cinnabar_stairs.json
+ polished_cinnabar_wall_from_cinnabar_stonecutting.json
+ polished_cinnabar_wall_from_polished_cinnabar_stonecutting.json
+ polished_cinnabar_wall.json
+ polished_cinnabar.json
+ polished_sulfur_from_sulfur_stonecutting.json
+ polished_sulfur_slab_from_polished_sulfur_stonecutting.json
+ polished_sulfur_slab_from_sulfur_stonecutting.json
+ polished_sulfur_slab.json
+ polished_sulfur_stairs_from_polished_sulfur_stonecutting.json
+ polished_sulfur_stairs_from_sulfur_stonecutting.json
+ polished_sulfur_stairs.json
+ polished_sulfur_wall_from_polished_sulfur_stonecutting.json
+ polished_sulfur_wall_from_sulfur_stonecutting.json
+ polished_sulfur_wall.json
+ polished_sulfur.json
+ potent_sulfur.json
+ sulfur_brick_slab_from_polished_sulfur_stonecutting.json
+ sulfur_brick_slab_from_sulfur_bricks_stonecutting.json
+ sulfur_brick_slab_from_sulfur_stonecutting.json
+ sulfur_brick_slab.json
+ sulfur_brick_stairs_from_polished_sulfur_stonecutting.json
+ sulfur_brick_stairs_from_sulfur_bricks_stonecutting.json
+ sulfur_brick_stairs_from_sulfur_stonecutting.json
+ sulfur_brick_stairs.json
+ sulfur_brick_wall_from_polished_sulfur_stonecutting.json
+ sulfur_brick_wall_from_sulfur_bricks_stonecutting.json
+ sulfur_brick_wall_from_sulfur_stonecutting.json
+ sulfur_brick_wall.json
+ sulfur_bricks_from_polished_sulfur_stonecutting.json
+ sulfur_bricks_from_sulfur_stonecutting.json
+ sulfur_bricks.json
+ sulfur_slab_from_sulfur_stonecutting.json
+ sulfur_slab.json
+ sulfur_stairs_from_sulfur_stonecutting.json
+ sulfur_stairs.json
+ sulfur_wall_from_sulfur_stonecutting.json
+ sulfur_wall.json
+ sulfur.json
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
+ minecraft:sulfur_cube_archetype
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
- advancements.adventure.barrel_roll.description: Make a barrel roll
- advancements.adventure.barrel_roll.title: Do a Barrel Roll!
- advancements.adventure.build_house.description: Watch 23 blocks and a door combine into a tiny house
- advancements.adventure.build_house.title: Tiny House, Assemble!
- advancements.adventure.build_trap.description: Watch out for 8 iron (or copper) bars, they're dangerous in groups. When you least expect it!
- advancements.adventure.build_trap.title: You Played Yourself
- advancements.adventure.craft_chest.description: Craft a Chest to keep track of your blocks
- advancements.adventure.craft_chest.title: Random Access Materials
- advancements.adventure.craft_sword.description: Craft a Sword
- advancements.adventure.craft_sword.title: Time to Fight!
- advancements.adventure.crafter.description: Automate your crafting with a Crafter
- advancements.adventure.crafter.title: Large Living Blocks Model
- advancements.adventure.crafting_table.description: Craft a Crafting Table
- advancements.adventure.crafting_table.title: Integrated Crafting Environment
- advancements.adventure.door.description: Craft a Door
- advancements.adventure.door.title: Seek Shelter
- advancements.adventure.end_portal.description: Watch twelve End Portal Frames with Eyes of Ender inserted combine into an End Portal
- advancements.adventure.end_portal.title: End of Line
- advancements.adventure.eye_frame_combination.description: Move an Eye of Ender close enough to an End Portal Frame for them to combine
- advancements.adventure.eye_frame_combination.title: Unifying Eye-Frame Interaction
- advancements.adventure.furnace.description: Make a furnace that can smelt things for you
- advancements.adventure.furnace.title: You're Cookin'
- advancements.adventure.iron_ingot.description: Make your way to the iron age
- advancements.adventure.iron_ingot.title: Ferrocious Ferrous
- advancements.adventure.mine_a_block.description: Punch a block until it comes alive
- advancements.adventure.mine_a_block.title: Mine a Block
- advancements.adventure.nether_portal.description: Watch twelve Obsidian and a Flint and Steel combine into a Nether Portal
- advancements.adventure.nether_portal.title: Nether-field Crafting
- advancements.adventure.obsidian.description: Mine some Obsidian
- advancements.adventure.obsidian.title: You require additional...
- advancements.adventure.wooden_pickaxe.description: Craft a tool that can mine for you
- advancements.adventure.wooden_pickaxe.title: Craft a Miner
- advancements.end.barrel_roll.description: Roll a barrel to the ends of the universe
- advancements.end.barrel_roll.title: Never Give Up! Trust Your Instincts!
- advancements.nether.barrel_roll.description: Do it! Do it now!
- advancements.nether.barrel_roll.title: Do a Barrel Roll! Do it! Do it! Do it in the Nether!
+ attribute.name.air_drag_modifier: Air Drag Modifier
+ attribute.name.bounciness: Bounciness
+ attribute.name.friction_modifier: Friction Modifier
+ biome.minecraft.sulfur_caves: Sulfur Caves
+ block.minecraft.chiseled_cinnabar: Chiseled Cinnabar
+ block.minecraft.chiseled_sulfur: Chiseled Sulfur
+ block.minecraft.cinnabar_brick_slab: Cinnabar Brick Slab
+ block.minecraft.cinnabar_brick_stairs: Cinnabar Brick Stairs
+ block.minecraft.cinnabar_brick_wall: Cinnabar Brick Wall
+ block.minecraft.cinnabar_bricks: Cinnabar Bricks
+ block.minecraft.cinnabar_slab: Cinnabar Slab
+ block.minecraft.cinnabar_stairs: Cinnabar Stairs
+ block.minecraft.cinnabar_wall: Cinnabar Wall
+ block.minecraft.cinnabar: Cinnabar
- block.minecraft.copper_trap: Copper Trap
- block.minecraft.exposed_copper_trap: Exposed Copper Trap
- block.minecraft.iron_trap: Iron Trap
- block.minecraft.oxidized_copper_trap: Oxidized Copper Trap
+ block.minecraft.polished_cinnabar_slab: Polished Cinnabar Slab
+ block.minecraft.polished_cinnabar_stairs: Polished Cinnabar Stairs
+ block.minecraft.polished_cinnabar_wall: Polished Cinnabar Wall
+ block.minecraft.polished_cinnabar: Polished Cinnabar
+ block.minecraft.polished_sulfur_slab: Polished Sulfur Slab
+ block.minecraft.polished_sulfur_stairs: Polished Sulfur Stairs
+ block.minecraft.polished_sulfur_wall: Polished Sulfur Wall
+ block.minecraft.polished_sulfur: Polished Sulfur Block
+ block.minecraft.potent_sulfur: Potent Sulfur
+ block.minecraft.sulfur_brick_slab: Sulfur Brick Slab
+ block.minecraft.sulfur_brick_stairs: Sulfur Brick Stairs
+ block.minecraft.sulfur_brick_wall: Sulfur Brick Wall
+ block.minecraft.sulfur_bricks: Sulfur Bricks
+ block.minecraft.sulfur_slab: Sulfur Slab
+ block.minecraft.sulfur_stairs: Sulfur Stairs
+ block.minecraft.sulfur_wall: Sulfur Wall
+ block.minecraft.sulfur: Sulfur
- block.minecraft.waxed_copper_trap: Waxed Copper Trap
- block.minecraft.waxed_exposed_copper_trap: Waxed Exposed Copper Trap
- block.minecraft.waxed_oxidized_copper_trap: Waxed Oxidized Copper Trap
- block.minecraft.waxed_weathered_copper_trap: Waxed Weathered Copper Trap
- block.minecraft.weathered_copper_trap: Weathered Copper Trap
- crafting.table.unable_to_place: The crafting grid needs a 2x2 block wide level surface
- entity.minecraft.crafting_action: Craft
- entity.minecraft.crafting_grid: Crafting Grid
- entity.minecraft.follow_action: Follow Me
- entity.minecraft.hovering_item: Crafting Results
- entity.minecraft.living_block_command: Living Block Command
- entity.minecraft.living_block: Living Block
- entity.minecraft.punch_action: Punch
+ entity.minecraft.sulfur_cube: Sulfur Cube
+ entity.minecraft.sulfur_cube.content: Contains: %s
- inventory.place_grid: Use the Craft action to place a crafting grid
- item.minecraft.attack_action: Attack / Mine
- item.minecraft.build_action: Build
- item.minecraft.crafting_action: Craft
- item.minecraft.follow_action: Follow Me
- item.minecraft.group_action: Group / Ungroup
- item.minecraft.highlight_action: Highlight
- item.minecraft.move_action: Move
- item.minecraft.punch_action: Punch
- item.minecraft.select_action: Select
- item.minecraft.select_group_action.details: Selected Group: %s
+ item.minecraft.sulfur_cube_bucket: Bucket of Sulfur Cube
+ item.minecraft.sulfur_cube_spawn_egg: Sulfur Cube Spawn Egg
- living_blocks.group.all: All
- living_blocks.group.aqua: Aqua
- living_blocks.group.blue: Blue
- living_blocks.group.lime: Lime
- living_blocks.group.none: None
- living_blocks.group.purple: Purple
- living_blocks.group.red: Red
- living_blocks.group.yellow: Yellow
+ options.graphicsApi: Graphics API
+ options.graphicsApi.default: Default
+ options.graphicsApi.opengl: Prefer OpenGL
+ options.graphicsApi.restart: You must restart your game to change the graphics API.
+ options.graphicsApi.tooltip: Which graphics API to use for rendering. Leave as Default unless you have a specific need to change this! Will take affect the next time you start the game.
+ options.graphicsApi.vulkan: Prefer Vulkan
+ subtitles.block.potent_sulfur.noxious_gas: Noxious gas appears
+ subtitles.entity.sulfur_cube.absorb: Sulfur Cube full
+ subtitles.entity.sulfur_cube.bounce: Sulfur Cube bounces
+ subtitles.entity.sulfur_cube.death: Sulfur Cube dies
+ subtitles.entity.sulfur_cube.eject: Block removed
+ subtitles.entity.sulfur_cube.hit: Sulfur Cube hit
+ subtitles.entity.sulfur_cube.hurt: Sulfur Cube hurts
+ subtitles.entity.sulfur_cube.push: Sulfur Cube pushed
+ subtitles.entity.sulfur_cube.squish: Sulfur Cube bounces
+ test.error.value_not_in_between: Expected %s to be in between %s and %s: was %s
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26w14a</th><th>26.2-snapshot-1</th></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.kill_a_mob.description</div></th><td>Have your sword kill any hostile monster</td><td>Kill any hostile monster</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.kill_a_mob.title</div></th><td>Monster Hunter (With Friends)</td><td>Monster Hunter</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.kill_all_mobs.description</div></th><td>Command an army of weapons to kill one of every hostile monster</td><td>Kill one of every hostile monster</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.ol_betsy.description</div></th><td>Aqcuire a Crossbow</td><td>Shoot a Crossbow</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.root.description</div></th><td>Herding and crafting your world</td><td>Adventure, exploration and combat</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.root.title</div></th><td>HerdCraft</td><td>Adventure</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.enter_the_end.description</div></th><td>Gather enough Eyes of Ender, find some End Portal Frames and enter the End</td><td>Enter the End Portal</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.enter_the_nether.description</div></th><td>Gather enough Obsidian and a Flint and Steel, then enter the Nether</td><td>Build, light, and enter a Nether Portal</td></tr>
<tr><th align="left"><div style="width:290px">argument.resource_or_id.invalid</div></th><td>Invalid id or tag</td><td>Invalid ID or tag</td></tr>
<tr><th align="left"><div style="width:290px">build.tooHigh</div></th><td>Height limit for building is %s</td><td>The height limit for building is %s</td></tr>
<tr><th align="left"><div style="width:290px">build.tooLow</div></th><td>Minimum height for building is %s</td><td>The minimum height for building is %s</td></tr>
<tr><th align="left"><div style="width:290px">command.failed</div></th><td>An unexpected error occurred trying to execute that command</td><td>An unexpected error occurred while trying to execute that command</td></tr>
<tr><th align="left"><div style="width:290px">commands.locate.biome.not_found</div></th><td>Could not find a biome of type "%s" within reasonable distance</td><td>Could not find a biome of type "%s" within a reasonable distance</td></tr>
<tr><th align="left"><div style="width:290px">commands.locate.poi.not_found</div></th><td>Could not find a point of interest of type "%s" within reasonable distance</td><td>Could not find a point of interest of type "%s" within a reasonable distance</td></tr>
<tr><th align="left"><div style="width:290px">commands.place.template.invalid</div></th><td>There is no template with id "%s"</td><td>There is no template with ID "%s"</td></tr>
<tr><th align="left"><div style="width:290px">commands.profile_fetch.id.failure</div></th><td>Failed to resolved profile for id %s</td><td>Failed to resolve profile for ID %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.profile_fetch.id.success</div></th><td>Resolved profile for id %s: %s</td><td>Resolved profile for ID %s: %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.schedule.cleared.failure</div></th><td>No schedules with id %s</td><td>No schedules with ID %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.schedule.cleared.success</div></th><td>Removed %s schedule(s) with id %s</td><td>Removed %s schedule(s) with ID %s</td></tr>
<tr><th align="left"><div style="width:290px">datapackFailure.title</div></th><td>Errors in currently selected data packs prevented the world from loading.

You can either try to load it with only the vanilla data pack ("safe mode"), or go back to the title screen and fix it manually.</td><td>Errors in the currently selected data pack(s) prevented the world from loading.

You can either try to load it with only the vanilla data pack ("Safe Mode"), or go back to the title screen and fix it manually.</td></tr>
<tr><th align="left"><div style="width:290px">filled_map.id</div></th><td>Id #%s</td><td>ID #%s</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.lavaSourceConversion.description</div></th><td>When flowing lava is surrounded on two sides by lava sources it converts into a source.</td><td>When flowing lava is surrounded on two sides by lava sources it, converts into a source.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.playersNetherPortalCreativeDelay</div></th><td>Player's Nether portal delay in creative mode</td><td>Player's Nether Portal delay in creative mode</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.playersNetherPortalCreativeDelay.description</div></th><td>Time (in ticks) that a creative mode player needs to stand in a Nether portal before changing dimensions.</td><td>Time (in ticks) that a creative mode player needs to stand in a Nether Portal before changing dimensions.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.playersNetherPortalDefaultDelay</div></th><td>Player's Nether portal delay in non-creative mode</td><td>Player's Nether Portal delay in non-creative mode</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.playersNetherPortalDefaultDelay.description</div></th><td>Time (in ticks) that a non-creative mode player needs to stand in a Nether portal before changing dimensions.</td><td>Time (in ticks) that a non-creative mode player needs to stand in a Nether Portal before changing dimensions.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.waterSourceConversion.description</div></th><td>When flowing water is surrounded on two sides by water sources it converts into a source.</td><td>When flowing water is surrounded on two sides by water sources, it converts into a source.</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.discard.title</div></th><td>Discard report and comments?</td><td>Discard Report and Comments?</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.draft.title</div></th><td>Edit draft chat report?</td><td>Edit Draft Chat Report?</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.error.title</div></th><td>Problem sending your report</td><td>Problem Sending Your Report</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.sending.title</div></th><td>Sending your report...</td><td>Sending Your Report...</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.sent.title</div></th><td>Report sent</td><td>Report Sent</td></tr>
<tr><th align="left"><div style="width:290px">gui.banned.title.permanent</div></th><td>Account permanently banned</td><td>Account Permanently Banned</td></tr>
<tr><th align="left"><div style="width:290px">gui.banned.title.temporary</div></th><td>Account temporarily suspended</td><td>Account Temporarily Suspended</td></tr>
<tr><th align="left"><div style="width:290px">gui.chatReport.discard.title</div></th><td>Discard report and comments?</td><td>Discard Report and Comments?</td></tr>
<tr><th align="left"><div style="width:290px">gui.chatReport.draft.title</div></th><td>Edit draft chat report?</td><td>Edit Draft Chat Report?</td></tr>
<tr><th align="left"><div style="width:290px">mco.configure.world.leave.question.line1</div></th><td>If you leave this Realm you won't see it unless you are invited again</td><td>If you leave this Realm, you won't see it unless you are invited again</td></tr>
<tr><th align="left"><div style="width:290px">mco.configure.world.restore.download.question.line1</div></th><td>The world will be downloaded and added to your single player worlds.</td><td>The world will be downloaded and added to your singleplayer worlds.</td></tr>
<tr><th align="left"><div style="width:290px">mco.selectServer.popup</div></th><td>Realms is a safe, simple way to enjoy an online Minecraft world with up to ten friends at a time. It supports loads of minigames and plenty of custom worlds! Only the owner of the realm needs to pay.</td><td>Realms is a safe, simple way to enjoy an online Minecraft world with up to ten friends at a time. It supports loads of minigames and plenty of custom worlds! Only the owner of the Realm needs to pay.</td></tr>
<tr><th align="left"><div style="width:290px">options.allowServerListing.tooltip</div></th><td>Servers may list online players as part of their public status.

With this option off your name will not show up in such lists.</td><td>Servers may list online players as part of their public status.

With this option off, your name will not show up in such lists.</td></tr>
<tr><th align="left"><div style="width:290px">options.directionalAudio.on.tooltip</div></th><td>Uses HRTF-based directional audio to improve the simulation of 3D sound. Requires HRTF compatible audio hardware, and is best experienced with headphones.</td><td>Uses HRTF-based directional audio to improve the simulation of 3D sound. Requires HRTF-compatible audio hardware, and is best experienced with headphones.</td></tr>
<tr><th align="left"><div style="width:290px">options.screenEffectScale.tooltip</div></th><td>Strength of nausea and Nether portal screen distortion effects.

At lower values, the nausea effect is replaced with a green overlay.</td><td>Strength of Nausea and Nether Portal screen distortion effects.

At lower values, the Nausea effect is replaced with a green overlay.</td></tr>
<tr><th align="left"><div style="width:290px">options.textureFiltering.anisotropic.tooltip</div></th><td>A hardware based filtering method, but impacts performance and significantly impacts video memory usage. May not be supported on all hardware.</td><td>A hardware-based filtering method, but impacts performance and significantly impacts video memory usage. May not be supported on all hardware.</td></tr>
<tr><th align="left"><div style="width:290px">options.textureFiltering.rgss.tooltip</div></th><td>(Rotated Grid Super Sampling)

A shader based filtering method that improves texture quality with a moderate performance impact.</td><td>(Rotated Grid Super Sampling)

A shader-based filtering method that improves texture quality with a moderate performance impact.</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.backupJoinSkipButton</div></th><td>I know what I'm doing!</td><td>I Know What I'm Doing!</td></tr>
</table>
<br/>
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
- reports/minecraft/components/item/attack_action.json
- reports/minecraft/components/item/build_action.json
+ reports/minecraft/components/item/chiseled_cinnabar.json
+ reports/minecraft/components/item/chiseled_sulfur.json
+ reports/minecraft/components/item/cinnabar_brick_slab.json
+ reports/minecraft/components/item/cinnabar_brick_stairs.json
+ reports/minecraft/components/item/cinnabar_brick_wall.json
+ reports/minecraft/components/item/cinnabar_bricks.json
+ reports/minecraft/components/item/cinnabar_slab.json
+ reports/minecraft/components/item/cinnabar_stairs.json
+ reports/minecraft/components/item/cinnabar_wall.json
+ reports/minecraft/components/item/cinnabar.json
- reports/minecraft/components/item/copper_trap.json
- reports/minecraft/components/item/crafting_action.json
- reports/minecraft/components/item/exposed_copper_trap.json
- reports/minecraft/components/item/follow_action.json
- reports/minecraft/components/item/group_action.json
- reports/minecraft/components/item/highlight_action.json
- reports/minecraft/components/item/iron_trap.json
- reports/minecraft/components/item/move_action.json
- reports/minecraft/components/item/oxidized_copper_trap.json
+ reports/minecraft/components/item/polished_cinnabar_slab.json
+ reports/minecraft/components/item/polished_cinnabar_stairs.json
+ reports/minecraft/components/item/polished_cinnabar_wall.json
+ reports/minecraft/components/item/polished_cinnabar.json
+ reports/minecraft/components/item/polished_sulfur_slab.json
+ reports/minecraft/components/item/polished_sulfur_stairs.json
+ reports/minecraft/components/item/polished_sulfur_wall.json
+ reports/minecraft/components/item/polished_sulfur.json
+ reports/minecraft/components/item/potent_sulfur.json
- reports/minecraft/components/item/punch_action.json
+ reports/minecraft/components/item/sulfur_brick_slab.json
+ reports/minecraft/components/item/sulfur_brick_stairs.json
+ reports/minecraft/components/item/sulfur_brick_wall.json
+ reports/minecraft/components/item/sulfur_bricks.json
+ reports/minecraft/components/item/sulfur_cube_bucket.json
+ reports/minecraft/components/item/sulfur_cube_spawn_egg.json
+ reports/minecraft/components/item/sulfur_slab.json
+ reports/minecraft/components/item/sulfur_stairs.json
+ reports/minecraft/components/item/sulfur_wall.json
+ reports/minecraft/components/item/sulfur.json
- reports/minecraft/components/item/waxed_copper_trap.json
- reports/minecraft/components/item/waxed_exposed_copper_trap.json
- reports/minecraft/components/item/waxed_oxidized_copper_trap.json
- reports/minecraft/components/item/waxed_weathered_copper_trap.json
- reports/minecraft/components/item/weathered_copper_trap.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/adventure/adventuring_time.json
+ minecraft/advancement/adventure/arbalistic.json
+ minecraft/advancement/adventure/avoid_vibration.json
- minecraft/advancement/adventure/barrel_roll.json
+ minecraft/advancement/adventure/blowback.json
+ minecraft/advancement/adventure/brush_armadillo.json
- minecraft/advancement/adventure/build_house.json
- minecraft/advancement/adventure/build_trap.json
+ minecraft/advancement/adventure/bullseye.json
- minecraft/advancement/adventure/craft_chest.json
+ minecraft/advancement/adventure/craft_decorated_pot_using_only_sherds.json
- minecraft/advancement/adventure/craft_end_portal.json
- minecraft/advancement/adventure/craft_nether_portal.json
- minecraft/advancement/adventure/craft_sword.json
- minecraft/advancement/adventure/craft_table.json
- minecraft/advancement/adventure/crafter.json
+ minecraft/advancement/adventure/crafters_crafting_crafters.json
- minecraft/advancement/adventure/door.json
- minecraft/advancement/adventure/end_barrel_roll.json
- minecraft/advancement/adventure/enter_the_end.json
- minecraft/advancement/adventure/eye_frame_combination.json
+ minecraft/advancement/adventure/fall_from_world_height.json
- minecraft/advancement/adventure/find_fortress.json
- minecraft/advancement/adventure/follow_ender_eye.json
- minecraft/advancement/adventure/furnace.json
+ minecraft/advancement/adventure/heart_transplanter.json
+ minecraft/advancement/adventure/hero_of_the_village.json
+ minecraft/advancement/adventure/honey_block_slide.json
- minecraft/advancement/adventure/iron_ingot.json
- minecraft/advancement/adventure/kill_dragon.json
+ minecraft/advancement/adventure/kill_mob_near_sculk_catalyst.json
+ minecraft/advancement/adventure/lighten_up.json
+ minecraft/advancement/adventure/lightning_rod_with_villager_no_fire.json
- minecraft/advancement/adventure/mine_a_block.json
+ minecraft/advancement/adventure/minecraft_trials_edition.json
- minecraft/advancement/adventure/nether_barrel_roll.json
- minecraft/advancement/adventure/obsidian.json
- minecraft/advancement/adventure/obtain_armor.json
- minecraft/advancement/adventure/obtain_blaze_rod.json
+ minecraft/advancement/adventure/ol_betsy.json
+ minecraft/advancement/adventure/overoverkill.json
+ minecraft/advancement/adventure/play_jukebox_in_meadows.json
+ minecraft/advancement/adventure/read_power_of_chiseled_bookshelf.json
+ minecraft/advancement/adventure/revaulting.json
+ minecraft/advancement/adventure/salvage_sherd.json
+ minecraft/advancement/adventure/shoot_arrow.json
+ minecraft/advancement/adventure/sleep_in_bed.json
+ minecraft/advancement/adventure/sniper_duel.json
+ minecraft/advancement/adventure/spear_many_mobs.json
+ minecraft/advancement/adventure/spyglass_at_dragon.json
+ minecraft/advancement/adventure/spyglass_at_ghast.json
+ minecraft/advancement/adventure/spyglass_at_parrot.json
+ minecraft/advancement/adventure/summon_iron_golem.json
+ minecraft/advancement/adventure/throw_trident.json
+ minecraft/advancement/adventure/totem_of_undying.json
+ minecraft/advancement/adventure/trade_at_world_height.json
+ minecraft/advancement/adventure/trade.json
+ minecraft/advancement/adventure/trim_with_all_exclusive_armor_patterns.json
+ minecraft/advancement/adventure/trim_with_any_armor_pattern.json
+ minecraft/advancement/adventure/two_birds_one_arrow.json
+ minecraft/advancement/adventure/under_lock_and_key.json
+ minecraft/advancement/adventure/use_lodestone.json
+ minecraft/advancement/adventure/very_very_frightening.json
+ minecraft/advancement/adventure/voluntary_exile.json
+ minecraft/advancement/adventure/walk_on_powder_snow_with_leather_boots.json
+ minecraft/advancement/adventure/who_needs_rockets.json
+ minecraft/advancement/adventure/whos_the_pillager_now.json
- minecraft/advancement/adventure/wooden_pickaxe.json
+ minecraft/advancement/end/dragon_breath.json
+ minecraft/advancement/end/dragon_egg.json
+ minecraft/advancement/end/elytra.json
+ minecraft/advancement/end/enter_end_gateway.json
+ minecraft/advancement/end/find_end_city.json
+ minecraft/advancement/end/kill_dragon.json
+ minecraft/advancement/end/levitate.json
+ minecraft/advancement/end/respawn_dragon.json
+ minecraft/advancement/end/root.json
+ minecraft/advancement/husbandry/allay_deliver_cake_to_note_block.json
+ minecraft/advancement/husbandry/allay_deliver_item_to_player.json
+ minecraft/advancement/husbandry/axolotl_in_a_bucket.json
+ minecraft/advancement/husbandry/balanced_diet.json
+ minecraft/advancement/husbandry/bred_all_animals.json
+ minecraft/advancement/husbandry/breed_an_animal.json
+ minecraft/advancement/husbandry/complete_catalogue.json
+ minecraft/advancement/husbandry/feed_snifflet.json
+ minecraft/advancement/husbandry/fishy_business.json
+ minecraft/advancement/husbandry/froglights.json
+ minecraft/advancement/husbandry/kill_axolotl_target.json
+ minecraft/advancement/husbandry/leash_all_frog_variants.json
+ minecraft/advancement/husbandry/make_a_sign_glow.json
+ minecraft/advancement/husbandry/obtain_netherite_hoe.json
+ minecraft/advancement/husbandry/obtain_sniffer_egg.json
+ minecraft/advancement/husbandry/place_dried_ghast_in_water.json
+ minecraft/advancement/husbandry/plant_any_sniffer_seed.json
+ minecraft/advancement/husbandry/plant_seed.json
+ minecraft/advancement/husbandry/remove_wolf_armor.json
+ minecraft/advancement/husbandry/repair_wolf_armor.json
+ minecraft/advancement/husbandry/ride_a_boat_with_a_goat.json
+ minecraft/advancement/husbandry/root.json
+ minecraft/advancement/husbandry/safely_harvest_honey.json
+ minecraft/advancement/husbandry/silk_touch_nest.json
+ minecraft/advancement/husbandry/tactical_fishing.json
+ minecraft/advancement/husbandry/tadpole_in_a_bucket.json
+ minecraft/advancement/husbandry/tame_an_animal.json
+ minecraft/advancement/husbandry/wax_off.json
+ minecraft/advancement/husbandry/wax_on.json
+ minecraft/advancement/husbandry/whole_pack.json
+ minecraft/advancement/nether/all_effects.json
+ minecraft/advancement/nether/all_potions.json
+ minecraft/advancement/nether/brew_potion.json
+ minecraft/advancement/nether/charge_respawn_anchor.json
+ minecraft/advancement/nether/create_beacon.json
+ minecraft/advancement/nether/create_full_beacon.json
+ minecraft/advancement/nether/distract_piglin.json
+ minecraft/advancement/nether/explore_nether.json
+ minecraft/advancement/nether/fast_travel.json
+ minecraft/advancement/nether/find_bastion.json
+ minecraft/advancement/nether/find_fortress.json
+ minecraft/advancement/nether/get_wither_skull.json
+ minecraft/advancement/nether/loot_bastion.json
+ minecraft/advancement/nether/netherite_armor.json
+ minecraft/advancement/nether/obtain_ancient_debris.json
+ minecraft/advancement/nether/obtain_blaze_rod.json
+ minecraft/advancement/nether/obtain_crying_obsidian.json
+ minecraft/advancement/nether/return_to_sender.json
+ minecraft/advancement/nether/ride_strider_in_overworld_lava.json
+ minecraft/advancement/nether/ride_strider.json
+ minecraft/advancement/nether/root.json
+ minecraft/advancement/nether/summon_wither.json
+ minecraft/advancement/nether/uneasy_alliance.json
+ minecraft/advancement/recipes/building_blocks/chiseled_cinnabar_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/chiseled_cinnabar.json
+ minecraft/advancement/recipes/building_blocks/chiseled_sulfur_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/chiseled_sulfur.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_slab_from_cinnabar_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_slab_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_slab_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_slab.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_stairs_from_cinnabar_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_stairs_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_stairs_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_stairs.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_bricks_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_bricks_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_bricks.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_slab_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_slab.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_stairs_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_slab_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_slab_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_slab.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_stairs_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_stairs_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_slab_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_slab_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_slab.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_stairs_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_stairs_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur.json
+ minecraft/advancement/recipes/building_blocks/potent_sulfur.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_slab_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_slab_from_sulfur_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_slab_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_slab.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_stairs_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_stairs_from_sulfur_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_stairs_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_stairs.json
+ minecraft/advancement/recipes/building_blocks/sulfur_bricks_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_bricks_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_bricks.json
+ minecraft/advancement/recipes/building_blocks/sulfur_slab_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_slab.json
+ minecraft/advancement/recipes/building_blocks/sulfur_stairs_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_stairs.json
+ minecraft/advancement/recipes/building_blocks/sulfur.json
+ minecraft/advancement/recipes/decorations/cinnabar_brick_wall_from_cinnabar_bricks_stonecutting.json
+ minecraft/advancement/recipes/decorations/cinnabar_brick_wall_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/cinnabar_brick_wall_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/cinnabar_brick_wall.json
+ minecraft/advancement/recipes/decorations/cinnabar_wall_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/cinnabar_wall.json
+ minecraft/advancement/recipes/decorations/polished_cinnabar_wall_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_cinnabar_wall_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_cinnabar_wall.json
+ minecraft/advancement/recipes/decorations/polished_sulfur_wall_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_sulfur_wall_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_sulfur_wall.json
+ minecraft/advancement/recipes/decorations/sulfur_brick_wall_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/sulfur_brick_wall_from_sulfur_bricks_stonecutting.json
+ minecraft/advancement/recipes/decorations/sulfur_brick_wall_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/sulfur_brick_wall.json
+ minecraft/advancement/recipes/decorations/sulfur_wall_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/sulfur_wall.json
+ minecraft/advancement/story/cure_zombie_villager.json
+ minecraft/advancement/story/deflect_arrow.json
+ minecraft/advancement/story/enchant_item.json
+ minecraft/advancement/story/enter_the_end.json
+ minecraft/advancement/story/enter_the_nether.json
+ minecraft/advancement/story/follow_ender_eye.json
+ minecraft/advancement/story/form_obsidian.json
+ minecraft/advancement/story/iron_tools.json
+ minecraft/advancement/story/lava_bucket.json
+ minecraft/advancement/story/mine_diamond.json
+ minecraft/advancement/story/mine_stone.json
+ minecraft/advancement/story/obtain_armor.json
+ minecraft/advancement/story/root.json
+ minecraft/advancement/story/shiny_gear.json
+ minecraft/advancement/story/smelt_iron.json
+ minecraft/advancement/story/upgrade_tools.json
+ minecraft/loot_table/blocks/chiseled_cinnabar.json
+ minecraft/loot_table/blocks/chiseled_sulfur.json
+ minecraft/loot_table/blocks/cinnabar_brick_slab.json
+ minecraft/loot_table/blocks/cinnabar_brick_stairs.json
+ minecraft/loot_table/blocks/cinnabar_brick_wall.json
+ minecraft/loot_table/blocks/cinnabar_bricks.json
+ minecraft/loot_table/blocks/cinnabar_slab.json
+ minecraft/loot_table/blocks/cinnabar_stairs.json
+ minecraft/loot_table/blocks/cinnabar_wall.json
+ minecraft/loot_table/blocks/cinnabar.json
- minecraft/loot_table/blocks/copper_trap.json
- minecraft/loot_table/blocks/exposed_copper_trap.json
- minecraft/loot_table/blocks/iron_trap.json
- minecraft/loot_table/blocks/oxidized_copper_trap.json
+ minecraft/loot_table/blocks/polished_cinnabar_slab.json
+ minecraft/loot_table/blocks/polished_cinnabar_stairs.json
+ minecraft/loot_table/blocks/polished_cinnabar_wall.json
+ minecraft/loot_table/blocks/polished_cinnabar.json
+ minecraft/loot_table/blocks/polished_sulfur_slab.json
+ minecraft/loot_table/blocks/polished_sulfur_stairs.json
+ minecraft/loot_table/blocks/polished_sulfur_wall.json
+ minecraft/loot_table/blocks/polished_sulfur.json
+ minecraft/loot_table/blocks/potent_sulfur.json
+ minecraft/loot_table/blocks/sulfur_brick_slab.json
+ minecraft/loot_table/blocks/sulfur_brick_stairs.json
+ minecraft/loot_table/blocks/sulfur_brick_wall.json
+ minecraft/loot_table/blocks/sulfur_bricks.json
+ minecraft/loot_table/blocks/sulfur_slab.json
+ minecraft/loot_table/blocks/sulfur_stairs.json
+ minecraft/loot_table/blocks/sulfur_wall.json
+ minecraft/loot_table/blocks/sulfur.json
- minecraft/loot_table/blocks/waxed_copper_trap.json
- minecraft/loot_table/blocks/waxed_exposed_copper_trap.json
- minecraft/loot_table/blocks/waxed_oxidized_copper_trap.json
- minecraft/loot_table/blocks/waxed_weathered_copper_trap.json
- minecraft/loot_table/blocks/weathered_copper_trap.json
+ minecraft/loot_table/entities/sulfur_cube.json
+ minecraft/recipe/chiseled_cinnabar_from_cinnabar_stonecutting.json
+ minecraft/recipe/chiseled_cinnabar.json
+ minecraft/recipe/chiseled_sulfur_from_sulfur_stonecutting.json
+ minecraft/recipe/chiseled_sulfur.json
+ minecraft/recipe/cinnabar_brick_slab_from_cinnabar_bricks_stonecutting.json
+ minecraft/recipe/cinnabar_brick_slab_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_slab_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_slab.json
+ minecraft/recipe/cinnabar_brick_stairs_from_cinnabar_bricks_stonecutting.json
+ minecraft/recipe/cinnabar_brick_stairs_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_stairs_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_stairs.json
+ minecraft/recipe/cinnabar_brick_wall_from_cinnabar_bricks_stonecutting.json
+ minecraft/recipe/cinnabar_brick_wall_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_wall_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_wall.json
+ minecraft/recipe/cinnabar_bricks_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_bricks_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_bricks.json
+ minecraft/recipe/cinnabar_slab_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_slab.json
+ minecraft/recipe/cinnabar_stairs_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_stairs.json
+ minecraft/recipe/cinnabar_wall_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_wall.json
+ minecraft/recipe/polished_cinnabar_from_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_slab_from_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_slab_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_slab.json
+ minecraft/recipe/polished_cinnabar_stairs_from_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_stairs_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_stairs.json
+ minecraft/recipe/polished_cinnabar_wall_from_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_wall_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_wall.json
+ minecraft/recipe/polished_cinnabar.json
+ minecraft/recipe/polished_sulfur_from_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_slab_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_slab_from_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_slab.json
+ minecraft/recipe/polished_sulfur_stairs_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_stairs_from_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_stairs.json
+ minecraft/recipe/polished_sulfur_wall_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_wall_from_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_wall.json
+ minecraft/recipe/polished_sulfur.json
+ minecraft/recipe/potent_sulfur.json
+ minecraft/recipe/sulfur_brick_slab_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_slab_from_sulfur_bricks_stonecutting.json
+ minecraft/recipe/sulfur_brick_slab_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_slab.json
+ minecraft/recipe/sulfur_brick_stairs_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_stairs_from_sulfur_bricks_stonecutting.json
+ minecraft/recipe/sulfur_brick_stairs_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_stairs.json
+ minecraft/recipe/sulfur_brick_wall_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_wall_from_sulfur_bricks_stonecutting.json
+ minecraft/recipe/sulfur_brick_wall_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_wall.json
+ minecraft/recipe/sulfur_bricks_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_bricks_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_bricks.json
+ minecraft/recipe/sulfur_slab_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_slab.json
+ minecraft/recipe/sulfur_stairs_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_stairs.json
+ minecraft/recipe/sulfur_wall_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_wall.json
+ minecraft/recipe/sulfur.json
- minecraft/structure/herding/nine_by_nine_copper_torch.nbt
- minecraft/structure/herding/nine_by_nine_soul_torch.nbt
- minecraft/structure/herding/nine_by_nine.nbt
+ minecraft/structure/spring/sulfur_spring_extra_large_1.nbt
+ minecraft/structure/spring/sulfur_spring_large_1.nbt
+ minecraft/structure/spring/sulfur_spring_large_2.nbt
+ minecraft/structure/spring/sulfur_spring_medium_1.nbt
+ minecraft/structure/spring/sulfur_spring_medium_2.nbt
+ minecraft/structure/spring/sulfur_spring_medium_3.nbt
+ minecraft/structure/spring/sulfur_spring_small_1.nbt
+ minecraft/structure/spring/sulfur_spring_small_2.nbt
+ minecraft/structure/spring/sulfur_spring_small_3.nbt
+ minecraft/structure/spring/sulfur_spring_small_4.nbt
+ minecraft/sulfur_cube_archetype/bouncy.json
+ minecraft/sulfur_cube_archetype/fast_flat.json
+ minecraft/sulfur_cube_archetype/fast_sliding.json
+ minecraft/sulfur_cube_archetype/high_resistance.json
+ minecraft/sulfur_cube_archetype/light.json
+ minecraft/sulfur_cube_archetype/regular.json
+ minecraft/sulfur_cube_archetype/slow_flat.json
+ minecraft/sulfur_cube_archetype/slow_sliding.json
+ minecraft/sulfur_cube_archetype/sticky.json
- minecraft/tags/block/builds_into_house.json
- minecraft/tags/block/concrete_powder.json
+ minecraft/tags/block/concrete_powders.json
+ minecraft/tags/block/concrete.json
- minecraft/tags/block/cow_food.json
+ minecraft/tags/block/glazed_terracotta.json
- minecraft/tags/block/living_block_takes_fall_damage.json
- minecraft/tags/block/pig_food.json
+ minecraft/tags/block/shears_extreme_breaking_speed.json
+ minecraft/tags/block/shears_major_breaking_speed.json
+ minecraft/tags/block/shears_minor_breaking_speed.json
- minecraft/tags/block/sheep_food.json
+ minecraft/tags/block/suppresses_bounce.json
+ minecraft/tags/damage_type/sulfur_cube_with_block_immune_to.json
- minecraft/tags/item/block_placers.json
+ minecraft/tags/item/concrete_powders.json
+ minecraft/tags/item/concrete.json
+ minecraft/tags/item/glazed_terracotta.json
+ minecraft/tags/item/sulfur_cube_archetype/bouncy.json
+ minecraft/tags/item/sulfur_cube_archetype/fast_flat.json
+ minecraft/tags/item/sulfur_cube_archetype/fast_sliding.json
+ minecraft/tags/item/sulfur_cube_archetype/high_resistance.json
+ minecraft/tags/item/sulfur_cube_archetype/light.json
+ minecraft/tags/item/sulfur_cube_archetype/regular.json
+ minecraft/tags/item/sulfur_cube_archetype/slow_flat.json
+ minecraft/tags/item/sulfur_cube_archetype/slow_sliding.json
+ minecraft/tags/item/sulfur_cube_archetype/sticky.json
+ minecraft/tags/item/sulfur_cube_food.json
+ minecraft/tags/item/sulfur_cube_swallowable.json
+ minecraft/worldgen/biome/sulfur_caves.json
+ minecraft/worldgen/configured_feature/rooted_sulfur_spring.json
+ minecraft/worldgen/configured_feature/sulfur_pool.json
+ minecraft/worldgen/configured_feature/sulfur_spring.json
+ minecraft/worldgen/noise/sulfur_cave_gradient.json
+ minecraft/worldgen/placed_feature/rooted_sulfur_spring.json
+ minecraft/worldgen/placed_feature/sulfur_pool.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/chiseled_cinnabar.json
+ minecraft/blockstates/chiseled_sulfur.json
+ minecraft/blockstates/cinnabar_brick_slab.json
+ minecraft/blockstates/cinnabar_brick_stairs.json
+ minecraft/blockstates/cinnabar_brick_wall.json
+ minecraft/blockstates/cinnabar_bricks.json
+ minecraft/blockstates/cinnabar_slab.json
+ minecraft/blockstates/cinnabar_stairs.json
+ minecraft/blockstates/cinnabar_wall.json
+ minecraft/blockstates/cinnabar.json
- minecraft/blockstates/copper_trap.json
- minecraft/blockstates/exposed_copper_trap.json
- minecraft/blockstates/iron_trap.json
- minecraft/blockstates/oxidized_copper_trap.json
+ minecraft/blockstates/polished_cinnabar_slab.json
+ minecraft/blockstates/polished_cinnabar_stairs.json
+ minecraft/blockstates/polished_cinnabar_wall.json
+ minecraft/blockstates/polished_cinnabar.json
+ minecraft/blockstates/polished_sulfur_slab.json
+ minecraft/blockstates/polished_sulfur_stairs.json
+ minecraft/blockstates/polished_sulfur_wall.json
+ minecraft/blockstates/polished_sulfur.json
+ minecraft/blockstates/potent_sulfur.json
+ minecraft/blockstates/sulfur_brick_slab.json
+ minecraft/blockstates/sulfur_brick_stairs.json
+ minecraft/blockstates/sulfur_brick_wall.json
+ minecraft/blockstates/sulfur_bricks.json
+ minecraft/blockstates/sulfur_slab.json
+ minecraft/blockstates/sulfur_stairs.json
+ minecraft/blockstates/sulfur_wall.json
+ minecraft/blockstates/sulfur.json
- minecraft/blockstates/waxed_copper_trap.json
- minecraft/blockstates/waxed_exposed_copper_trap.json
- minecraft/blockstates/waxed_oxidized_copper_trap.json
- minecraft/blockstates/waxed_weathered_copper_trap.json
- minecraft/blockstates/weathered_copper_trap.json
- minecraft/items/attack_action.json
- minecraft/items/build_action.json
+ minecraft/items/chiseled_cinnabar.json
+ minecraft/items/chiseled_sulfur.json
+ minecraft/items/cinnabar_brick_slab.json
+ minecraft/items/cinnabar_brick_stairs.json
+ minecraft/items/cinnabar_brick_wall.json
+ minecraft/items/cinnabar_bricks.json
+ minecraft/items/cinnabar_slab.json
+ minecraft/items/cinnabar_stairs.json
+ minecraft/items/cinnabar_wall.json
+ minecraft/items/cinnabar.json
- minecraft/items/copper_trap.json
- minecraft/items/crafting_action.json
- minecraft/items/exposed_copper_trap.json
- minecraft/items/follow_action.json
- minecraft/items/group_action.json
- minecraft/items/highlight_action.json
- minecraft/items/iron_trap.json
- minecraft/items/move_action.json
- minecraft/items/oxidized_copper_trap.json
+ minecraft/items/polished_cinnabar_slab.json
+ minecraft/items/polished_cinnabar_stairs.json
+ minecraft/items/polished_cinnabar_wall.json
+ minecraft/items/polished_cinnabar.json
+ minecraft/items/polished_sulfur_slab.json
+ minecraft/items/polished_sulfur_stairs.json
+ minecraft/items/polished_sulfur_wall.json
+ minecraft/items/polished_sulfur.json
+ minecraft/items/potent_sulfur.json
- minecraft/items/punch_action.json
+ minecraft/items/sulfur_brick_slab.json
+ minecraft/items/sulfur_brick_stairs.json
+ minecraft/items/sulfur_brick_wall.json
+ minecraft/items/sulfur_bricks.json
+ minecraft/items/sulfur_cube_bucket.json
+ minecraft/items/sulfur_cube_spawn_egg.json
+ minecraft/items/sulfur_slab.json
+ minecraft/items/sulfur_stairs.json
+ minecraft/items/sulfur_wall.json
+ minecraft/items/sulfur.json
- minecraft/items/waxed_copper_trap.json
- minecraft/items/waxed_exposed_copper_trap.json
- minecraft/items/waxed_oxidized_copper_trap.json
- minecraft/items/waxed_weathered_copper_trap.json
- minecraft/items/weathered_copper_trap.json
+ minecraft/models/block/chiseled_cinnabar.json
+ minecraft/models/block/chiseled_sulfur.json
+ minecraft/models/block/cinnabar_brick_slab_top.json
+ minecraft/models/block/cinnabar_brick_slab.json
+ minecraft/models/block/cinnabar_brick_stairs_inner.json
+ minecraft/models/block/cinnabar_brick_stairs_outer.json
+ minecraft/models/block/cinnabar_brick_stairs.json
+ minecraft/models/block/cinnabar_brick_wall_inventory.json
+ minecraft/models/block/cinnabar_brick_wall_post.json
+ minecraft/models/block/cinnabar_brick_wall_side_tall.json
+ minecraft/models/block/cinnabar_brick_wall_side.json
+ minecraft/models/block/cinnabar_bricks.json
+ minecraft/models/block/cinnabar_slab_top.json
+ minecraft/models/block/cinnabar_slab.json
+ minecraft/models/block/cinnabar_stairs_inner.json
+ minecraft/models/block/cinnabar_stairs_outer.json
+ minecraft/models/block/cinnabar_stairs.json
+ minecraft/models/block/cinnabar_wall_inventory.json
+ minecraft/models/block/cinnabar_wall_post.json
+ minecraft/models/block/cinnabar_wall_side_tall.json
+ minecraft/models/block/cinnabar_wall_side.json
+ minecraft/models/block/cinnabar.json
- minecraft/models/block/copper_trap.json
- minecraft/models/block/exposed_copper_trap.json
- minecraft/models/block/iron_trap.json
- minecraft/models/block/oxidized_copper_trap.json
+ minecraft/models/block/polished_cinnabar_slab_top.json
+ minecraft/models/block/polished_cinnabar_slab.json
+ minecraft/models/block/polished_cinnabar_stairs_inner.json
+ minecraft/models/block/polished_cinnabar_stairs_outer.json
+ minecraft/models/block/polished_cinnabar_stairs.json
+ minecraft/models/block/polished_cinnabar_wall_inventory.json
+ minecraft/models/block/polished_cinnabar_wall_post.json
+ minecraft/models/block/polished_cinnabar_wall_side_tall.json
+ minecraft/models/block/polished_cinnabar_wall_side.json
+ minecraft/models/block/polished_cinnabar.json
+ minecraft/models/block/polished_sulfur_slab_top.json
+ minecraft/models/block/polished_sulfur_slab.json
+ minecraft/models/block/polished_sulfur_stairs_inner.json
+ minecraft/models/block/polished_sulfur_stairs_outer.json
+ minecraft/models/block/polished_sulfur_stairs.json
+ minecraft/models/block/polished_sulfur_wall_inventory.json
+ minecraft/models/block/polished_sulfur_wall_post.json
+ minecraft/models/block/polished_sulfur_wall_side_tall.json
+ minecraft/models/block/polished_sulfur_wall_side.json
+ minecraft/models/block/polished_sulfur.json
+ minecraft/models/block/potent_sulfur.json
+ minecraft/models/block/sulfur_brick_slab_top.json
+ minecraft/models/block/sulfur_brick_slab.json
+ minecraft/models/block/sulfur_brick_stairs_inner.json
+ minecraft/models/block/sulfur_brick_stairs_outer.json
+ minecraft/models/block/sulfur_brick_stairs.json
+ minecraft/models/block/sulfur_brick_wall_inventory.json
+ minecraft/models/block/sulfur_brick_wall_post.json
+ minecraft/models/block/sulfur_brick_wall_side_tall.json
+ minecraft/models/block/sulfur_brick_wall_side.json
+ minecraft/models/block/sulfur_bricks.json
+ minecraft/models/block/sulfur_slab_top.json
+ minecraft/models/block/sulfur_slab.json
+ minecraft/models/block/sulfur_stairs_inner.json
+ minecraft/models/block/sulfur_stairs_outer.json
+ minecraft/models/block/sulfur_stairs.json
+ minecraft/models/block/sulfur_wall_inventory.json
+ minecraft/models/block/sulfur_wall_post.json
+ minecraft/models/block/sulfur_wall_side_tall.json
+ minecraft/models/block/sulfur_wall_side.json
+ minecraft/models/block/sulfur.json
- minecraft/models/block/waxed_copper_trap.json
- minecraft/models/block/waxed_exposed_copper_trap.json
- minecraft/models/block/waxed_oxidized_copper_trap.json
- minecraft/models/block/waxed_weathered_copper_trap.json
- minecraft/models/block/weathered_copper_trap.json
- minecraft/models/item/attack_action.json
- minecraft/models/item/attack_signalling_arrow.json
- minecraft/models/item/build_action.json
- minecraft/models/item/crafting_action.json
- minecraft/models/item/follow_action.json
- minecraft/models/item/group_action.json
- minecraft/models/item/highlight_action.json
- minecraft/models/item/move_action.json
- minecraft/models/item/punch_action.json
+ minecraft/models/item/sulfur_cube_bucket.json
+ minecraft/models/item/sulfur_cube_spawn_egg.json
+ minecraft/particles/noxious_gas.json
+ minecraft/particles/sulfur_bubbles.json
+ minecraft/particles/sulfur_cube_goo.json
- minecraft/shaders/core/rendertype_text_background_see_through.fsh
- minecraft/shaders/core/rendertype_text_background_see_through.vsh
- minecraft/shaders/core/rendertype_text_background.fsh
- minecraft/shaders/core/rendertype_text_background.vsh
- minecraft/shaders/core/rendertype_text_intensity_see_through.fsh
- minecraft/shaders/core/rendertype_text_intensity_see_through.vsh
- minecraft/shaders/core/rendertype_text_intensity.fsh
- minecraft/shaders/core/rendertype_text_intensity.vsh
- minecraft/shaders/core/rendertype_text_see_through.fsh
- minecraft/shaders/core/rendertype_text_see_through.vsh
- minecraft/shaders/core/rendertype_text.fsh
- minecraft/shaders/core/rendertype_text.vsh
+ minecraft/shaders/core/text_background.fsh
+ minecraft/shaders/core/text_background.vsh
+ minecraft/shaders/core/text.fsh
+ minecraft/shaders/core/text.vsh
+ minecraft/textures/block/chiseled_cinnabar.png
+ minecraft/textures/block/chiseled_sulfur.png
+ minecraft/textures/block/cinnabar_bricks.png
+ minecraft/textures/block/cinnabar.png
+ minecraft/textures/block/polished_cinnabar.png
+ minecraft/textures/block/polished_sulfur.png
+ minecraft/textures/block/potent_sulfur.png
+ minecraft/textures/block/sulfur_bricks.png
+ minecraft/textures/block/sulfur.png
- minecraft/textures/entity/command/attack.png
- minecraft/textures/entity/command/build.png
- minecraft/textures/entity/command/follow.png
- minecraft/textures/entity/command/move.png
- minecraft/textures/entity/crafting_grid/2x2.png
- minecraft/textures/entity/crafting_grid/3x3.png
+ minecraft/textures/entity/sulfur_cube/sulfur_cube_inner.png
+ minecraft/textures/entity/sulfur_cube/sulfur_cube_outer.png
- minecraft/textures/gui/title/background/af/panorama_0.png
- minecraft/textures/gui/title/background/af/panorama_1.png
- minecraft/textures/gui/title/background/af/panorama_2.png
- minecraft/textures/gui/title/background/af/panorama_3.png
- minecraft/textures/gui/title/background/af/panorama_4.png
- minecraft/textures/gui/title/background/af/panorama_5.png
- minecraft/textures/gui/title/herdcraft.png
- minecraft/textures/item/attack_action.png
- minecraft/textures/item/attack_signalling_arrow.png
- minecraft/textures/item/build_action.png
- minecraft/textures/item/crafting_action.png
- minecraft/textures/item/follow_action.png
- minecraft/textures/item/group_action_overlay.png
- minecraft/textures/item/group_action.png
- minecraft/textures/item/highlight_action.png
- minecraft/textures/item/move_action.png
- minecraft/textures/item/punch_action.png
- minecraft/textures/item/signalling_arrow.png
+ minecraft/textures/item/sulfur_cube_bucket.png
+ minecraft/textures/item/sulfur_cube_spawn_egg.png
+ minecraft/textures/particle/bubble_white.png
+ minecraft/textures/particle/noxious_gas_01.png
+ minecraft/textures/particle/noxious_gas_02.png
+ minecraft/textures/particle/noxious_gas_03.png
+ minecraft/textures/particle/noxious_gas_04.png
+ minecraft/textures/particle/noxious_gas_05.png
+ minecraft/textures/particle/noxious_gas_06.png
+ minecraft/textures/particle/noxious_gas_07.png
+ minecraft/textures/particle/noxious_gas_08.png
+ minecraft/textures/particle/sulfur_cube_goo.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
splashes
</summary>

```diff
+ ...!
+ .party()!
+ "Almost never" is an interesting concept!
+ "Autological" is!
+ [this splash text is now available]
+ §1C§2o§3l§4o§5r§6m§7a§8t§9i§ac
+ §kFUNKY LOL
+ /give @a hugs 64
+ #minecraftfarms
+ <3 Max & 99 & Ducky!
+ 1% sugar!
+ 100% pure!
+ 12 herbs and spices!
+ 12345 is a bad password!
- 15 minutes 6 seconds!
+ 15 years of Mining and Crafting!
+ 150 bpm for 400000 minutes!
+ 150% hyperbole!
+ 20 GOTO 10!
- 26w14a!
- 272 Cobblestone!
+ 4815162342 lines of code!
+ 90% bug free!
+ 90210!
- A blockade.
+ A riddle, wrapped in a mystery!
+ A skeleton popped out!
+ Absolutely fixed relatively broken coordinates
+ Absolutely no memes!
+ Afraid of the big, black bat!
+ Age of Wonders is better!
+ Ahhhhhh!
+ All inclusive!
+ All is full of love!
+ All rumors are true!
+ Also try Braid!
+ Also try Limbo!
+ Also try Minecraft Dungeons!
+ Also try Mount And Blade!
+ Also try Pixeljunk Shooter!
+ Also try Project Zomboid!
+ Also try Super Meat Boy!
+ Also try Terraria!
+ Also try VVVVVV!
+ Also try World of Goo!
+ Amplify and listen to BIPOC voices!
+ An illusion! What are you hiding?
+ And my pickaxe!
+ Any computer is a laptop if you're brave enough!
- Anything can be an entity if you try hard enough
+ As seen on TV!
+ Ask your doctor!
- Auto-Assembling Automata
+ Autonomous!
+ Awesome community!
+ Awesome game design right there!
+ Awesome!
+ Aww man!
+ Be anti-racist!
- Beautiful Block Balloons
+ Bees, bees, bees, bees!
+ Bekarton guards the gate!
+ Best in class!
+ Big Pointy Teeth!
+ Bigger than a bread box!
- Biggest herd in town!
+ Black lives matter!
- Blocked.
+ Blue warrior shot the food!
+ Board game version also available!
+ Boats FTW
+ Boots with the fur!
+ Bread is pain!
+ Bring it on!
+ Bring me Ray Cokes!
+ Bringing home the bacon!
+ BTAF used to be good!
+ Buckets of lava!
+ Bushy eyebrows!
+ Buzzy Bees!
+ Call your mother!
+ Casual gaming!
+ Ceci n'est pas une title screen!
+ Check it out!
+ Check out the far lands!
+ Chicken Jockey!
+ Child's play!
+ Classy!
+ Closed source!
+ Cloud computing!
+ Cogito ergo sum!
+ Collaborate and listen!
+ Complex cellular automata!
+ Consummate V's!
+ Contains infinite genders!
+ Contains simulated goats!
+ Conventional!
+ Cough or sneeze into your elbow!
+ Cow Tools!
- Cozy dirt house!
+ Create!
+ Croak team!
+ Cruising streets for gold!
- Cute Cuboid Companions
+ Cześć Polsko!
+ Déjà vu!
+ Déjà vu!
+ Do it all, everything!
+ Do not distribute!
+ Do you want to join my server?
+ Does barrel rolls!
+ Doesn't avoid double negatives!
+ Doesn't use the U-word!
+ Don't bother with the clones!
+ Don't feed avocados to parrots!
+ Don't feed chocolate to parrots!
- Don't let the wool float away
- Don't let your tools loose!
+ Don't look directly at the bugs!
+ Don’t touch your face!
+ Don't worry, be happy!
+ doot doot
+ Double buffered!
+ DRR! DRR! DRR!
+ Dungeon!
+ DungeonQuest is unfair!
+ Edit is a name!
+ Educate your friends on anti-racism!
+ Engage!
+ Enhanced!
- Enough balloons make you walk on water
+ Envision! Create! Share!
+ Eple (original edit)!
+ Euclidian!
+ Everybody do the Leif!
+ Excitement!
+ Exclusive!
+ Exploding creepers!
+ Extra things!
+ Fabulous graphics!
+ Falling off cliffs!
+ Falling with style!
+ Fan fiction!
+ Fantasy!
+ Fat free!
+ Feature packed!
- Fifteen years of ... whatever this is!
+ Finally complete!
+ Finally with ladders!
+ Find your claw!
+ Finger-licking!
- Flashes make so much light
+ Flashing letters!
+ Flavor with no seasoning!
+ Flaxkikare!
+ Flint and Steel!
+ Flower forest TM perfume
+ Fnord!
+ Follow the train, CJ!
+ Freaky!
+ Free dental!
+ From free range developers!
+ From the streets of Södermalm!
+ Full of stars!
+ Funk soul brother!
+ Gamers unite – separately in your own homes!
+ Gargamel plays it!
+ Gasp!
+ Get to the coppah!
+ Ghoughpteighbteau tchoghs!
+ Give us Gordon!
+ GNU Terry Pratchett
+ Go to the dentist!
- Gooey!
+ Google anlyticsed!
+ Got your nose!
+ GOTY!
+ Guaranteed!
+ Haha, LOL!
+ Haley loves Elan!
+ Hampsterdance!
+ Han shot first!
+ Hang out with your friends online!
+ Hard to label!
+ Has an ending!
+ Has working bookshelves!
+ Hat Fridays!
+ Haunted!
- Have you herd the news? The blocks came alive!
+ Heaps of hits on YouTube!
+ Helo Cymru!
+ Herregud!
+ Holy cow, man!
+ Home-made!
+ Homeomorphic to a 3-sphere!
+ Honey, I grew the bees!
+ Honey, I waxed the copper!
+ Hot tamale, hot hot tamale!
+ Hotter than the sun!
- Hungry, hungry chests
+ HURNERJSGER?
+ I have a suggestion.
+ I miss ADOM!
+ I need more context.
+ I see your vocabulary has improved!
+ I'm glad you're here!
+ idspispopd!
+ if not ok then return end
+ In case it isn't obvious, foxes aren't players.
+ Indev!
+ Indie!
+ Information wants to be free!
+ Ingots!
+ Inspirational!
+ Internet enabled!
+ It came from space.
+ It swings, it jives!
+ It's a game!
- It's alive!
+ It's finished!
+ It's groundbreaking!
+ It's here!
+ Jag känner en bot!
+ Jason! Jason! Jason!
+ Java 16 + 1 + 4 * 2 = 25!
+ Javalicious edition
+ Jeb has amazing hair!
+ Joel is neat!
+ Joule is neat too!
+ Jump up, jump up, and get down!
+ Kaaneeeedaaaa!
+ Keyboard compatible!
+ Khaaaaaaaaan!
+ Kick it root down!
+ Kind of dragon free!
+ Kinda like Lemmings!
+ Kiss the sky!
+ l33t!
- Large block the size of a small block
+ Larger than Earth!
+ Learn about allyship!
+ Legal in Finland!
+ Lennart lennart = new Lennart();
+ Less addictive than TV Tropes!
+ Let our battle's begin!
+ Let's danec!
+ Leveraging synergy!
- Lightning for the miners
- Like sleeping in a tumble dryer
+ Limited edition!
+ Lives in a pineapple under the sea!
+ Livestreamed!
+ Look mum, I'm in a splash!
+ Lots of truthiness!
+ Loved by millions!
+ Macroscopic!
+ Made by "real" people!
+ Made by Jeb!
+ Made in Sweden!
+ Made with lave!
+ Make me a table, a funky table!
+ MAP11 has two names!
- Marching Cubes!
+ Matt Damon!
+ May contain nuts!
+ May contain traces of citrus!
+ Meeting expectations!
+ Menger sponge!
+ Millions of peaches!
+ Minecraft Java Edition presents: Disgusting Bugs
+ Minecraft!
+ Mmmph, mmph!
+ Moderately attractive!
+ Monster infighting!
+ More addictive than lemonade!
+ More Digital!
+ More polygons!
+ More than 500 sold!
- Moving Block Entities!
+ Music by Aaron Cherof!
+ Music by Amos Roddy!
+ Music by C418!
+ Music by Hyper Potions!
+ Music by Kumi Tanioka!
+ Music by Lena Raine!
+ My life for Aiur!
+ Never dig down!
+ Nice to meet you!
- Nom nom nom!
+ Nooooooooooooo!
+ Not as cool as Spock!
+ Not linear!
+ Not on steam!
+ Now contains 32 random daily cats!
+ Now in 3D!
+ Now on OpenGL 3.3 core profile!
+ Now on Vulkan 1.2!
+ Now supports åäö!
+ Now with additional stuff!
+ Now with difficulty!
+ Now with extra hugs!
+ Now With Multiplayer!
+ Now you are thinking with pistons!
+ NP is not in P!
+ Octagonal!
+ Oh man!
+ Oh, ok, Pigmen!
+ OICU812!
+ Omnipotent!
+ One day, somewhere in the future, my work will be quoted!
+ One does not simply walk to the Far Lands
+ One of a kind!
+ PC gaming since 1873!
+ Peter Griffin!
+ Ph1lza had a good run!
+ Phobos anomaly!
+ Ping the human!
+ Pixels!
+ Place ALL the blocks!
+ Place hanging sign here
+ Plant a tree!
+ Plant-based light sources!
+ Play him off, keyboard cat!
+ Play Minecraft, Watch Topgear, Get Pig!
+ Played by cowboys!
+ pls rt
+ Plz reply to my tweet!
+ Pneumatic!
- Pogo Tools
+ Polynomial!
+ Prepare, but don’t hoard!
+ Pretty scary!
+ Pretty!
+ Pumpakungen!
+ Pumpkinhead!
+ Punching wood!
+ Put a little fence around it!
+ Put that cookie down!
+ Rainbow turtle?
+ Random splash!
+ Read more books!
+ Reference implementation!
+ Regional resources!
+ Remember to brush your... ...teeth
+ Replaced molten cheese with blood?
+ Representing Edsbyn!
+ Reticulating splines!
+ RIBBIT!
+ Ride the pig!
+ Rise from your grave!
+ Rita is the new top dog!
+ Rule #1: it's never my fault
+ Run, coward! I hunger!
+ Ryan also has amazing hair!
+ Save the world – stay inside!
+ Scary!
+ Scientific!
+ See you next Friday or so!
+ Seecret Friday update!
+ Sensational!
- Several blocks at a time!
+ Shop for your elders!
+ Should not be played while driving
+ Shriek like a Sculk Shrieker!
+ Singleplayer!
- Slice some blocks into the lime group
+ Slow acting portals!
+ Sniff sniff...
+ So fresh, so clean!
+ So sweet, like a nice bon bon!
+ Soap and water!
+ Something funny!
+ Something's not quite right...
+ Speak OUT against injustice and UP for equality!
+ Spiders everywhere!
+ sqrt(-1) love you!
+ Stand up for equality in your community!
+ Stay a while and listen!
+ Stay a while, stay forever!
+ Stay home and play games!
+ Stay safe!
+ Stay strong!
+ Stop being reasonable, this is the Internet!
+ Stop, hammertime!
+ Strange, but not a stranger!
+ Sublime!
+ Supercalifragilisticexpialidocious!
+ Support elderly relatives and friends!
+ Support local businesses!
+ Support the BIPOC community and creators!
+ Survive!
+ SWM forever!
+ Swords for everyone!
+ Synecdoche!
+ Take an eggbeater and beat it against a skillet!
+ Take frequent breaks!
+ Take her pillow!
+ Take the elevator to the mezzanine!
+ Technically good!
+ Technoblade never dies!
+ Technologic!
+ Teetsuuuuoooo!
+ Tell your friends!
+ Terrestrial!
+ Testificates!
+ Thank you for the fish!
+ That's no moon!
+ That's Numberwang!
+ That's super!
+ The bee's knees!
+ The creeper is a spy!
+ The cutest predator you'll ever meet!
+ The sky is the limit!
+ The sum of its parts!
- The true meaning of block game
+ The true meaning of covfefe
+ Thematic!
+ There's <<a cat on ,my keyboard!~
+ There's no stopping the Trollmaso
- They see me rolling!
+ This is good for Realms.
+ This is my true form!
+ This message will never appear on the splash screen, isn't that weird?
+ This parrot is no more! It has ceased to be!
- This portal is §mnot§r going to build itself
+ This sand is sus
+ This text is hard to read if you play the game at the default resolution, but at 1080p it's fine!
+ Thousands of colors!
+ Throw a blanket over it!
+ Throw yourself at the ground and miss
+ Tip your waiter!
+ Tougher than diamonds, rich like cream!
+ Treatment for your rash!
+ Truly gone fishing!
+ Try it!
+ Try the mushroom stew!
+ Try the Nether!
+ Turing complete!
+ Twittered about!
+ Tyrion would love it!
+ Ultimate edition!
+ umop-apisdn!
+ Undefeated!
+ Une baguette!
+ Uninflammable!
+ Uses LWJGL!
+ Vanilla!
+ Verlet integration!
+ Very fun!
+ Very influential in its circle!
+ Vote for net neutrality!
+ Warning! A huge battleship "STEVE" is approaching fast!
+ Wash your hands!
- Watch out for traps!
+ Water bottle!
+ Water proof!
- We solved the inventory problem!
+ Welcome to your Doom!
+ What do you expect?
- What is the collective noun for a group of blocks?
- What's an item entity?
- What's that mysterious clicking noise?
+ What's the question?
+ What's up, Doc?
+ Where there is not light, there can spider!
- Who Let the Blocks Out?
+ Who let the frogs out?
+ Who put it there?
+ Whoa, dude!
- Why, you stuck-up, half-witted, scruffy-looking block herder!
+ Woah.
+ Woo, 2pp!
+ Woo, facepunch!
+ Woo, reddit!
+ Woo, somethingawful!
+ Woo, tigsource!
+ Woo, worldofminecraft!
- Wool is lighter than air
+ Wow!
+ Yaaay!
+ Yay, puppies for everyone!
+ Yes, sir!
+ You are valid!
+ You are welcome here!
+ You can't explain that!
+ You're going too fast!
+ You've got a brand new key!
+ Your gender is valid!
+ Zoglin!?
+ Γεια σου Ελλάδα!
+ 한국 안녕하세요!
+ 你好中国！
+ 日本ハロー！
```

</details>
</details>
<hr/>