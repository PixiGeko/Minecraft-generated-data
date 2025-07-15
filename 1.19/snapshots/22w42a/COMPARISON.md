## Comparison with [1.19.2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.2)

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
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.19.2</th><th>22w42a</th></tr><tr><td>ResourcePack version</td><td><pre>9</pre></td><td><pre>11</pre></td></tr><tr><td>World version</td><td><pre>3120</pre></td><td><pre>3205</pre></td></tr><tr><td>Protocol version</td><td><pre>760</pre></td><td><pre>1073741928</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.19.2</th><th>22w42a</th></tr><tr><td>com.mojang:authlib</td><td><pre>3.11.49</pre></td><td><pre>3.13.56</pre></td></tr><tr><td>com.mojang:javabridge</td><td><pre>1.2.24</pre></td><td><pre>2.0.25</pre></td></tr></table>
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
+ minecraft:acacia_hanging_sign
+ minecraft:acacia_wall_hanging_sign
+ minecraft:bamboo_button
+ minecraft:bamboo_door
+ minecraft:bamboo_fence
+ minecraft:bamboo_fence_gate
+ minecraft:bamboo_hanging_sign
+ minecraft:bamboo_mosaic
+ minecraft:bamboo_mosaic_slab
+ minecraft:bamboo_mosaic_stairs
+ minecraft:bamboo_planks
+ minecraft:bamboo_pressure_plate
+ minecraft:bamboo_sign
+ minecraft:bamboo_slab
+ minecraft:bamboo_stairs
+ minecraft:bamboo_trapdoor
+ minecraft:bamboo_wall_hanging_sign
+ minecraft:bamboo_wall_sign
+ minecraft:birch_hanging_sign
+ minecraft:birch_wall_hanging_sign
+ minecraft:chiseled_bookshelf
+ minecraft:crimson_hanging_sign
+ minecraft:crimson_wall_hanging_sign
+ minecraft:dark_oak_hanging_sign
+ minecraft:dark_oak_wall_hanging_sign
+ minecraft:jungle_hanging_sign
+ minecraft:jungle_wall_hanging_sign
+ minecraft:mangrove_hanging_sign
+ minecraft:mangrove_wall_hanging_sign
+ minecraft:oak_hanging_sign
+ minecraft:oak_wall_hanging_sign
+ minecraft:spruce_hanging_sign
+ minecraft:spruce_wall_hanging_sign
+ minecraft:warped_hanging_sign
+ minecraft:warped_wall_hanging_sign
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
+ minecraft:chiseled_bookshelf
+ minecraft:hanging_sign
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
- minecraft:entity_summon
- minecraft:item_enchantment
- minecraft:mob_effect
+ minecraft:resource_key
+ minecraft:resource_or_tag_key
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:camel
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:acacia_hanging_sign
+ minecraft:bamboo_button
+ minecraft:bamboo_chest_raft
+ minecraft:bamboo_door
+ minecraft:bamboo_fence
+ minecraft:bamboo_fence_gate
+ minecraft:bamboo_hanging_sign
+ minecraft:bamboo_mosaic
+ minecraft:bamboo_mosaic_slab
+ minecraft:bamboo_mosaic_stairs
+ minecraft:bamboo_planks
+ minecraft:bamboo_pressure_plate
+ minecraft:bamboo_raft
+ minecraft:bamboo_sign
+ minecraft:bamboo_slab
+ minecraft:bamboo_stairs
+ minecraft:bamboo_trapdoor
+ minecraft:birch_hanging_sign
+ minecraft:camel_spawn_egg
+ minecraft:chiseled_bookshelf
+ minecraft:crimson_hanging_sign
+ minecraft:dark_oak_hanging_sign
+ minecraft:jungle_hanging_sign
+ minecraft:mangrove_hanging_sign
+ minecraft:oak_hanging_sign
+ minecraft:spruce_hanging_sign
+ minecraft:warped_hanging_sign
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:gaze_cooldown_ticks
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
+ minecraft:camel_temptations
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.bamboo_wood_button.click_off
+ minecraft:block.bamboo_wood_button.click_on
+ minecraft:block.bamboo_wood_door.close
+ minecraft:block.bamboo_wood_door.open
+ minecraft:block.bamboo_wood_fence_gate.close
+ minecraft:block.bamboo_wood_fence_gate.open
+ minecraft:block.bamboo_wood_pressure_plate.click_off
+ minecraft:block.bamboo_wood_pressure_plate.click_on
+ minecraft:block.bamboo_wood_trapdoor.close
+ minecraft:block.bamboo_wood_trapdoor.open
+ minecraft:block.bamboo_wood.break
+ minecraft:block.bamboo_wood.fall
+ minecraft:block.bamboo_wood.hit
+ minecraft:block.bamboo_wood.place
+ minecraft:block.bamboo_wood.step
+ minecraft:block.hanging_sign.break
+ minecraft:block.hanging_sign.fall
+ minecraft:block.hanging_sign.hit
+ minecraft:block.hanging_sign.place
+ minecraft:block.hanging_sign.step
+ minecraft:block.nether_wood_button.click_off
+ minecraft:block.nether_wood_button.click_on
+ minecraft:block.nether_wood_door.close
+ minecraft:block.nether_wood_door.open
+ minecraft:block.nether_wood_fence_gate.close
+ minecraft:block.nether_wood_fence_gate.open
+ minecraft:block.nether_wood_pressure_plate.click_off
+ minecraft:block.nether_wood_pressure_plate.click_on
+ minecraft:block.nether_wood_trapdoor.close
+ minecraft:block.nether_wood_trapdoor.open
+ minecraft:block.nether_wood.break
+ minecraft:block.nether_wood.fall
+ minecraft:block.nether_wood.hit
+ minecraft:block.nether_wood.place
+ minecraft:block.nether_wood.step
+ minecraft:entity.camel.ambient
+ minecraft:entity.camel.dash
+ minecraft:entity.camel.dash_ready
+ minecraft:entity.camel.death
+ minecraft:entity.camel.eat
+ minecraft:entity.camel.hurt
+ minecraft:entity.camel.saddle
+ minecraft:entity.camel.sit
+ minecraft:entity.camel.stand
+ minecraft:entity.camel.step
+ minecraft:entity.camel.step_sand
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
+ minecraft:acacia_hanging_sign
+ minecraft:acacia_wall_hanging_sign
+ minecraft:bamboo_button
+ minecraft:bamboo_door
+ minecraft:bamboo_fence
+ minecraft:bamboo_fence_gate
+ minecraft:bamboo_hanging_sign
+ minecraft:bamboo_mosaic
+ minecraft:bamboo_mosaic_slab
+ minecraft:bamboo_mosaic_stairs
+ minecraft:bamboo_planks
+ minecraft:bamboo_pressure_plate
+ minecraft:bamboo_sign
+ minecraft:bamboo_slab
+ minecraft:bamboo_stairs
+ minecraft:bamboo_trapdoor
+ minecraft:bamboo_wall_hanging_sign
+ minecraft:bamboo_wall_sign
+ minecraft:birch_hanging_sign
+ minecraft:birch_wall_hanging_sign
+ minecraft:chiseled_bookshelf
+ minecraft:crimson_hanging_sign
+ minecraft:crimson_wall_hanging_sign
+ minecraft:dark_oak_hanging_sign
+ minecraft:dark_oak_wall_hanging_sign
+ minecraft:jungle_hanging_sign
+ minecraft:jungle_wall_hanging_sign
+ minecraft:mangrove_hanging_sign
+ minecraft:mangrove_wall_hanging_sign
+ minecraft:oak_hanging_sign
+ minecraft:oak_wall_hanging_sign
+ minecraft:spruce_hanging_sign
+ minecraft:spruce_wall_hanging_sign
+ minecraft:warped_hanging_sign
+ minecraft:warped_wall_hanging_sign
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:camel
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:camel
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:acacia_hanging_sign
+ minecraft:bamboo_button
+ minecraft:bamboo_door
+ minecraft:bamboo_fence
+ minecraft:bamboo_fence_gate
+ minecraft:bamboo_hanging_sign
+ minecraft:bamboo_mosaic
+ minecraft:bamboo_mosaic_slab
+ minecraft:bamboo_mosaic_stairs
+ minecraft:bamboo_planks
+ minecraft:bamboo_pressure_plate
+ minecraft:bamboo_sign
+ minecraft:bamboo_slab
+ minecraft:bamboo_stairs
+ minecraft:bamboo_trapdoor
+ minecraft:birch_hanging_sign
+ minecraft:chiseled_bookshelf
+ minecraft:crimson_hanging_sign
+ minecraft:dark_oak_hanging_sign
+ minecraft:jungle_hanging_sign
+ minecraft:mangrove_hanging_sign
+ minecraft:oak_hanging_sign
+ minecraft:spruce_hanging_sign
+ minecraft:warped_hanging_sign
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:acacia_hanging_sign
+ minecraft:acacia_wall_hanging_sign
+ minecraft:bamboo_button
+ minecraft:bamboo_door
+ minecraft:bamboo_fence
+ minecraft:bamboo_fence_gate
+ minecraft:bamboo_hanging_sign
+ minecraft:bamboo_mosaic
+ minecraft:bamboo_mosaic_slab
+ minecraft:bamboo_mosaic_stairs
+ minecraft:bamboo_planks
+ minecraft:bamboo_pressure_plate
+ minecraft:bamboo_sign
+ minecraft:bamboo_slab
+ minecraft:bamboo_stairs
+ minecraft:bamboo_trapdoor
+ minecraft:bamboo_wall_hanging_sign
+ minecraft:bamboo_wall_sign
+ minecraft:birch_hanging_sign
+ minecraft:birch_wall_hanging_sign
+ minecraft:chiseled_bookshelf
+ minecraft:crimson_hanging_sign
+ minecraft:crimson_wall_hanging_sign
+ minecraft:dark_oak_hanging_sign
+ minecraft:dark_oak_wall_hanging_sign
+ minecraft:jungle_hanging_sign
+ minecraft:jungle_wall_hanging_sign
+ minecraft:mangrove_hanging_sign
+ minecraft:mangrove_wall_hanging_sign
+ minecraft:oak_hanging_sign
+ minecraft:oak_wall_hanging_sign
+ minecraft:spruce_hanging_sign
+ minecraft:spruce_wall_hanging_sign
+ minecraft:warped_hanging_sign
+ minecraft:warped_wall_hanging_sign
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:chiseled_bookshelf
+ minecraft:hanging_sign
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
- minecraft:entity_summon
- minecraft:item_enchantment
- minecraft:mob_effect
+ minecraft:resource_key
+ minecraft:resource_or_tag_key
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:camel
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:acacia_hanging_sign
+ minecraft:bamboo_button
+ minecraft:bamboo_chest_raft
+ minecraft:bamboo_door
+ minecraft:bamboo_fence
+ minecraft:bamboo_fence_gate
+ minecraft:bamboo_hanging_sign
+ minecraft:bamboo_mosaic
+ minecraft:bamboo_mosaic_slab
+ minecraft:bamboo_mosaic_stairs
+ minecraft:bamboo_planks
+ minecraft:bamboo_pressure_plate
+ minecraft:bamboo_raft
+ minecraft:bamboo_sign
+ minecraft:bamboo_slab
+ minecraft:bamboo_stairs
+ minecraft:bamboo_trapdoor
+ minecraft:birch_hanging_sign
+ minecraft:camel_spawn_egg
+ minecraft:chiseled_bookshelf
+ minecraft:crimson_hanging_sign
+ minecraft:dark_oak_hanging_sign
+ minecraft:jungle_hanging_sign
+ minecraft:mangrove_hanging_sign
+ minecraft:oak_hanging_sign
+ minecraft:spruce_hanging_sign
+ minecraft:warped_hanging_sign
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:gaze_cooldown_ticks
```

</details>
<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:camel_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.bamboo_wood_button.click_off
+ minecraft:block.bamboo_wood_button.click_on
+ minecraft:block.bamboo_wood_door.close
+ minecraft:block.bamboo_wood_door.open
+ minecraft:block.bamboo_wood_fence_gate.close
+ minecraft:block.bamboo_wood_fence_gate.open
+ minecraft:block.bamboo_wood_pressure_plate.click_off
+ minecraft:block.bamboo_wood_pressure_plate.click_on
+ minecraft:block.bamboo_wood_trapdoor.close
+ minecraft:block.bamboo_wood_trapdoor.open
+ minecraft:block.bamboo_wood.break
+ minecraft:block.bamboo_wood.fall
+ minecraft:block.bamboo_wood.hit
+ minecraft:block.bamboo_wood.place
+ minecraft:block.bamboo_wood.step
+ minecraft:block.hanging_sign.break
+ minecraft:block.hanging_sign.fall
+ minecraft:block.hanging_sign.hit
+ minecraft:block.hanging_sign.place
+ minecraft:block.hanging_sign.step
+ minecraft:block.nether_wood_button.click_off
+ minecraft:block.nether_wood_button.click_on
+ minecraft:block.nether_wood_door.close
+ minecraft:block.nether_wood_door.open
+ minecraft:block.nether_wood_fence_gate.close
+ minecraft:block.nether_wood_fence_gate.open
+ minecraft:block.nether_wood_pressure_plate.click_off
+ minecraft:block.nether_wood_pressure_plate.click_on
+ minecraft:block.nether_wood_trapdoor.close
+ minecraft:block.nether_wood_trapdoor.open
+ minecraft:block.nether_wood.break
+ minecraft:block.nether_wood.fall
+ minecraft:block.nether_wood.hit
+ minecraft:block.nether_wood.place
+ minecraft:block.nether_wood.step
+ minecraft:entity.camel.ambient
+ minecraft:entity.camel.dash
+ minecraft:entity.camel.dash_ready
+ minecraft:entity.camel.death
+ minecraft:entity.camel.eat
+ minecraft:entity.camel.hurt
+ minecraft:entity.camel.saddle
+ minecraft:entity.camel.sit
+ minecraft:entity.camel.stand
+ minecraft:entity.camel.step
+ minecraft:entity.camel.step_sand
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
+ acacia_hanging_sign.json
+ acacia_wall_hanging_sign.json
+ bamboo_button.json
+ bamboo_door.json
+ bamboo_fence_gate.json
+ bamboo_fence.json
+ bamboo_hanging_sign.json
+ bamboo_mosaic_slab.json
+ bamboo_mosaic_stairs.json
+ bamboo_mosaic.json
+ bamboo_planks.json
+ bamboo_pressure_plate.json
+ bamboo_sign.json
+ bamboo_slab.json
+ bamboo_stairs.json
+ bamboo_trapdoor.json
+ bamboo_wall_hanging_sign.json
+ bamboo_wall_sign.json
+ birch_hanging_sign.json
+ birch_wall_hanging_sign.json
+ chiseled_bookshelf.json
+ crimson_hanging_sign.json
+ crimson_wall_hanging_sign.json
+ dark_oak_hanging_sign.json
+ dark_oak_wall_hanging_sign.json
+ jungle_hanging_sign.json
+ jungle_wall_hanging_sign.json
+ mangrove_hanging_sign.json
+ mangrove_wall_hanging_sign.json
+ oak_hanging_sign.json
+ oak_wall_hanging_sign.json
+ spruce_hanging_sign.json
+ spruce_wall_hanging_sign.json
+ warped_hanging_sign.json
+ warped_wall_hanging_sign.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
effect
</summary>

```diff
- effect clear <targets: entity> <effect: mob_effect>
+ effect clear <targets: entity> <effect: resource>
- effect give <targets: entity> <effect: mob_effect> <seconds: integer> <amplifier: integer> <hideParticles: bool>
+ effect give <targets: entity> <effect: resource> <seconds: integer> <amplifier: integer> <hideParticles: bool>
```

</details>
<details>
<summary>
enchant
</summary>

```diff
- enchant <targets: entity> <enchantment: item_enchantment> <level: integer>
+ enchant <targets: entity> <enchantment: resource> <level: integer>
```

</details>
<details>
<summary>
locate
</summary>

```diff
+ locate structure <structure: resource_or_tag_key>
- locate structure <structure: resource_or_tag>
```

</details>
<details>
<summary>
place
</summary>

```diff
+ place feature <feature: resource_key> <pos: block_pos>
- place feature <feature: resource> <pos: block_pos>
+ place jigsaw <pool: resource_key> <target: resource_location> <max_depth: integer> <position: block_pos>
- place jigsaw <pool: resource> <target: resource_location> <max_depth: integer> <position: block_pos>
+ place structure <structure: resource_key> <pos: block_pos>
- place structure <structure: resource> <pos: block_pos>
```

</details>
<details>
<summary>
summon
</summary>

```diff
- summon <entity: entity_summon> <pos: vec3> <nbt: nbt_compound_tag>
+ summon <entity: resource> <pos: vec3> <nbt: nbt_compound_tag>
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
acacia_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
acacia_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
acacia_chest_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
acacia_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
acacia_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
acacia_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
acacia_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
acacia_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
acacia_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
acacia_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
acacia_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
acacia_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
acacia_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
activator_rail.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
amethyst_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
andesite.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
andesite_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
andesite_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
andesite_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
anvil.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
armor_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
armor_stand.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
arrow.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
baked_potato.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
baked_potato_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
baked_potato_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
banner_duplicate.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
barrel.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
beacon.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
beehive.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
beetroot_soup.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
birch_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
birch_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
birch_chest_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
birch_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
birch_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
birch_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
birch_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
birch_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
birch_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
birch_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
birch_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
birch_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
birch_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
blackstone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
blackstone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
blackstone_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
black_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_dye_from_wither_rose.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
black_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
black_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
black_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
black_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
blast_furnace.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blaze_powder.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
blue_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_dye_from_cornflower.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
blue_ice.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
blue_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
blue_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
blue_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
blue_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
bone_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
bone_meal.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
bone_meal_from_bone_block.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
book.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
bookshelf.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
book_cloning.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
bow.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
bowl.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
bread.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brewing_stand.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brick.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
brown_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
brown_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
brown_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
brown_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
brown_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
bucket.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cake.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
campfire.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
carrot_on_a_stick.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cartography_table.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cauldron.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
chain.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
charcoal.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
chest.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
chest_minecart.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
chiseled_deepslate.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
chiseled_nether_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
chiseled_polished_blackstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
chiseled_quartz_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
chiseled_red_sandstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
chiseled_sandstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
chiseled_stone_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
clay.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
clock.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
coal.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
coal_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
coal_from_blasting_coal_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
coal_from_blasting_deepslate_coal_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
coal_from_smelting_coal_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
coal_from_smelting_deepslate_coal_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
coarse_dirt.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cobbled_deepslate_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cobbled_deepslate_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cobbled_deepslate_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cobblestone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cobblestone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cobblestone_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
comparator.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
compass.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
composter.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
conduit.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cooked_beef.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_beef_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_beef_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_chicken.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_chicken_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_chicken_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_cod.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_cod_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_cod_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_mutton.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_mutton_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_mutton_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_porkchop.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_porkchop_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_porkchop_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_rabbit.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_rabbit_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_rabbit_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_salmon.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_salmon_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cooked_salmon_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
cookie.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
copper_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
copper_ingot.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
copper_ingot_from_blasting_copper_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
copper_ingot_from_blasting_deepslate_copper_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
copper_ingot_from_blasting_raw_copper.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
copper_ingot_from_smelting_copper_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
copper_ingot_from_smelting_deepslate_copper_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
copper_ingot_from_smelting_raw_copper.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
copper_ingot_from_waxed_copper_block.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cracked_deepslate_bricks.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
cracked_deepslate_tiles.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
cracked_nether_bricks.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
cracked_polished_blackstone_bricks.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
cracked_stone_bricks.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
crafting_table.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
creeper_banner_pattern.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
crimson_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
crimson_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
crimson_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
crimson_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
crimson_hyphae.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
crimson_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
crimson_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
crimson_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
crimson_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
crimson_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
crimson_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
crossbow.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
cut_copper.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cut_copper_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cut_copper_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cut_red_sandstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cut_red_sandstone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cut_sandstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cut_sandstone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cyan_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cyan_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
cyan_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cyan_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
cyan_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
cyan_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
dark_oak_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
dark_oak_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
dark_oak_chest_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
dark_oak_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
dark_oak_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
dark_oak_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
dark_oak_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
dark_oak_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
dark_oak_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
dark_oak_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
dark_oak_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
dark_oak_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
dark_oak_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
dark_prismarine.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
dark_prismarine_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
dark_prismarine_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
daylight_detector.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
deepslate.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
deepslate_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
deepslate_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
deepslate_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
deepslate_brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
deepslate_tiles.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
deepslate_tile_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
deepslate_tile_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
deepslate_tile_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
detector_rail.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
diamond.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
diamond_axe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diamond_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
diamond_boots.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diamond_chestplate.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diamond_from_blasting_deepslate_diamond_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
diamond_from_blasting_diamond_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
diamond_from_smelting_deepslate_diamond_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
diamond_from_smelting_diamond_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
diamond_helmet.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diamond_hoe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diamond_leggings.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diamond_pickaxe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diamond_shovel.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diamond_sword.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
diorite.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
diorite_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
diorite_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
diorite_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
dispenser.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
dried_kelp.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
dried_kelp_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
dried_kelp_from_campfire_cooking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
dried_kelp_from_smelting.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
dried_kelp_from_smoking.json
</summary>

```
Category: none -> food
```

</details>
<details>
<summary>
dripstone_block.json
</summary>

```
Category: none -> building
Group: pointed_dripstone -> none
```

</details>
<details>
<summary>
dropper.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
emerald.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
emerald_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
emerald_from_blasting_deepslate_emerald_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
emerald_from_blasting_emerald_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
emerald_from_smelting_deepslate_emerald_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
emerald_from_smelting_emerald_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
enchanting_table.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
ender_chest.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
ender_eye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
end_crystal.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
end_rod.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
end_stone_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
end_stone_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
end_stone_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
end_stone_brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
exposed_cut_copper.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
exposed_cut_copper_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
exposed_cut_copper_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
fermented_spider_eye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
firework_rocket.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
firework_rocket_simple.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
firework_star.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
firework_star_fade.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
fire_charge.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
fishing_rod.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
fletching_table.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
flint_and_steel.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
flower_banner_pattern.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
flower_pot.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
furnace.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
furnace_minecart.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
glass.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
glass_bottle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
glistering_melon_slice.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
glowstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
glow_item_frame.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
golden_apple.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
golden_axe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
golden_boots.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
golden_carrot.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
golden_chestplate.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
golden_helmet.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
golden_hoe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
golden_leggings.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
golden_pickaxe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
golden_shovel.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
golden_sword.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
gold_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
gold_ingot_from_blasting_deepslate_gold_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_blasting_gold_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_blasting_nether_gold_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_blasting_raw_gold.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_gold_block.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_nuggets.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_smelting_deepslate_gold_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_smelting_gold_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_smelting_nether_gold_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_ingot_from_smelting_raw_gold.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_nugget.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_nugget_from_blasting.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gold_nugget_from_smelting.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
granite.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
granite_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
granite_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
granite_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
gray_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
gray_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
gray_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
gray_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
gray_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
green_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
green_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
green_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
green_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
green_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
green_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
grindstone.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
hay_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
heavy_weighted_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
honeycomb_block.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
honey_block.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
honey_bottle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
hopper.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
hopper_minecart.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_axe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_bars.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
iron_boots.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_chestplate.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
iron_helmet.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_hoe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_ingot_from_blasting_deepslate_iron_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_ingot_from_blasting_iron_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_ingot_from_blasting_raw_iron.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_ingot_from_iron_block.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_ingot_from_nuggets.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_ingot_from_smelting_deepslate_iron_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_ingot_from_smelting_iron_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_ingot_from_smelting_raw_iron.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_leggings.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_nugget.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_nugget_from_blasting.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_nugget_from_smelting.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
iron_pickaxe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_shovel.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_sword.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
iron_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
item_frame.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
jack_o_lantern.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
jukebox.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
jungle_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
jungle_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
jungle_chest_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
jungle_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
jungle_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
jungle_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
jungle_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
jungle_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
jungle_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
jungle_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
jungle_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
jungle_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
jungle_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
ladder.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lantern.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lapis_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
lapis_lazuli.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lapis_lazuli_from_blasting_deepslate_lapis_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lapis_lazuli_from_blasting_lapis_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lapis_lazuli_from_smelting_deepslate_lapis_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lapis_lazuli_from_smelting_lapis_ore.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lead.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
leather.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
leather_boots.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
leather_chestplate.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
leather_helmet.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
leather_horse_armor.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
leather_leggings.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
lectern.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
lever.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
lightning_rod.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
light_blue_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
light_blue_dye_from_blue_orchid.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_dye_from_blue_white_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
light_blue_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
light_blue_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_blue_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
light_blue_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
light_gray_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
light_gray_dye_from_azure_bluet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_dye_from_black_white_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_dye_from_gray_white_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_dye_from_oxeye_daisy.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_dye_from_white_tulip.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
light_gray_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
light_gray_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
light_gray_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
light_gray_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
light_weighted_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
lime_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
lime_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_dye_from_smelting.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
lime_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
lime_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
lime_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
lime_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
lodestone.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
loom.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
magenta_dye_from_allium.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_dye_from_blue_red_pink.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_dye_from_blue_red_white_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_dye_from_lilac.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_dye_from_purple_and_pink.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
magenta_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
magenta_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
magenta_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
magenta_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
magma_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
magma_cream.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mangrove_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mangrove_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
mangrove_chest_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mangrove_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
mangrove_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mangrove_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
mangrove_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mangrove_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
mangrove_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mangrove_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mangrove_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mangrove_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
mangrove_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
map.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
map_cloning.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
map_extending.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
melon.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
melon_seeds.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
minecart.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mojang_banner_pattern.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mossy_cobblestone_from_moss_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mossy_cobblestone_from_vine.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mossy_cobblestone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mossy_cobblestone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mossy_cobblestone_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mossy_stone_bricks_from_moss_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mossy_stone_bricks_from_vine.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mossy_stone_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mossy_stone_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mossy_stone_brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
moss_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
muddy_mangrove_roots.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mud_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mud_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mud_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
mud_brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
mushroom_stew.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
music_disc_5.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
netherite_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
netherite_ingot.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
netherite_ingot_from_netherite_block.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
netherite_scrap.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
netherite_scrap_from_blasting.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
nether_brick.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
nether_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
nether_brick_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
nether_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
nether_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
nether_brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
nether_wart_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
note_block.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
oak_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
oak_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
oak_chest_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
oak_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
oak_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
oak_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
oak_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
oak_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
oak_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
oak_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
oak_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
oak_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
oak_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
observer.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
orange_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
orange_dye_from_orange_tulip.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_dye_from_red_yellow.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
orange_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
orange_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
orange_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
orange_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
oxidized_cut_copper.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
oxidized_cut_copper_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
oxidized_cut_copper_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
packed_ice.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
packed_mud.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
painting.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
paper.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
pink_dye_from_peony.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_dye_from_pink_tulip.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_dye_from_red_white_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
pink_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
pink_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pink_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
pink_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
piston.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
polished_andesite.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_andesite_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_andesite_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_basalt.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_blackstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_blackstone_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_blackstone_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_blackstone_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_blackstone_brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
polished_blackstone_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
polished_blackstone_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
polished_blackstone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_blackstone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_blackstone_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
polished_deepslate.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_deepslate_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_deepslate_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_deepslate_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
polished_diorite.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_diorite_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_diorite_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_granite.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_granite_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
polished_granite_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
popped_chorus_fruit.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
powered_rail.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
prismarine.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
prismarine_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
prismarine_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
prismarine_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
prismarine_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
prismarine_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
prismarine_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pumpkin_pie.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
pumpkin_seeds.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
purple_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
purple_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
purple_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
purple_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
purple_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
purpur_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
purpur_pillar.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
purpur_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
purpur_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
quartz.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
quartz_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
quartz_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
quartz_from_blasting.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
quartz_pillar.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
quartz_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
quartz_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
rabbit_stew_from_brown_mushroom.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
rabbit_stew_from_red_mushroom.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
rail.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
raw_copper.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
raw_copper_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
raw_gold.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
raw_gold_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
raw_iron.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
raw_iron_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
recovery_compass.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
redstone.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
redstone_block.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
redstone_from_blasting_deepslate_redstone_ore.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
redstone_from_blasting_redstone_ore.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
redstone_from_smelting_deepslate_redstone_ore.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
redstone_from_smelting_redstone_ore.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
redstone_lamp.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
redstone_torch.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
red_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_dye_from_beetroot.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_dye_from_poppy.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_dye_from_rose_bush.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_dye_from_tulip.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
red_nether_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_nether_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_nether_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_nether_brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_sandstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_sandstone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_sandstone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_sandstone_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
red_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
red_wool.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
repair_item.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
repeater.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
respawn_anchor.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
sandstone.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
sandstone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
sandstone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
sandstone_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
scaffolding.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
sea_lantern.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
shears.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
shield.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
shield_decoration.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
shulker_box.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
shulker_box_coloring.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
skull_banner_pattern.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
slime_ball.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
slime_block.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
smithing_table.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
smoker.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
smooth_basalt.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
smooth_quartz.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
smooth_quartz_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
smooth_quartz_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
smooth_red_sandstone.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
smooth_red_sandstone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
smooth_red_sandstone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
smooth_sandstone.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
smooth_sandstone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
smooth_sandstone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
smooth_stone.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
smooth_stone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
snow.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
snow_block.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
soul_campfire.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
soul_lantern.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
soul_torch.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
spectral_arrow.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
sponge.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
spruce_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
spruce_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
spruce_chest_boat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
spruce_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
spruce_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
spruce_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
spruce_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
spruce_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
spruce_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
spruce_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
spruce_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
spruce_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
spruce_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
spyglass.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
stick.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
sticky_piston.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
stick_from_bamboo_item.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
stone.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
stonecutter.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
stone_axe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
stone_bricks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stone_brick_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stone_brick_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stone_brick_wall.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
stone_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
stone_hoe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
stone_pickaxe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
stone_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
stone_shovel.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
stone_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stone_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stone_sword.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
stripped_acacia_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stripped_birch_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stripped_crimson_hyphae.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stripped_dark_oak_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stripped_jungle_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stripped_mangrove_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stripped_oak_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stripped_spruce_wood.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
stripped_warped_hyphae.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
sugar_from_honey_bottle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
sugar_from_sugar_cane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
suspicious_stew.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
target.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
tinted_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
tipped_arrow.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
tnt.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
tnt_minecart.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
torch.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
trapped_chest.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
tripwire_hook.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
turtle_helmet.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
warped_button.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
warped_door.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
warped_fence.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
warped_fence_gate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
warped_fungus_on_a_stick.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
warped_hyphae.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
warped_planks.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
warped_pressure_plate.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
warped_sign.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
warped_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
warped_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
warped_trapdoor.json
</summary>

```
Category: none -> redstone
```

</details>
<details>
<summary>
waxed_copper_block_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_cut_copper.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_cut_copper_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_cut_copper_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_cut_copper_slab_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_cut_copper_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_cut_copper_stairs_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_exposed_copper_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_exposed_cut_copper.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_slab_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_oxidized_copper_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_weathered_copper_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_weathered_cut_copper.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_slab_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs_from_honeycomb.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
weathered_cut_copper.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
weathered_cut_copper_slab.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
weathered_cut_copper_stairs.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
wheat.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
white_dye.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_dye_from_lily_of_the_valley.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
white_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
white_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
white_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
white_wool_from_string.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
wooden_axe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
wooden_hoe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
wooden_pickaxe.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
wooden_shovel.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
wooden_sword.json
</summary>

```
Category: none -> equipment
```

</details>
<details>
<summary>
writable_book.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_banner.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_bed_from_white_bed.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_candle.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_carpet_from_white_carpet.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_concrete_powder.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
yellow_dye_from_dandelion.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_dye_from_sunflower.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_glazed_terracotta.json
</summary>

```
Category: none -> blocks
```

</details>
<details>
<summary>
yellow_stained_glass.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
yellow_stained_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: none -> misc
```

</details>
<details>
<summary>
yellow_terracotta.json
</summary>

```
Category: none -> building
```

</details>
<details>
<summary>
yellow_wool.json
</summary>

```
Category: none -> building
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
+ argument.resource_tag.invalid_type: Tag '%s' has wrong type '%s' (expected '%s')
+ argument.resource_tag.not_found: Can't find tag '%s' of type '%s'
+ argument.resource.invalid_type: Element '%s' has wrong type '%s' (expected '%s')
+ argument.resource.not_found: Can't find element '%s' of type '%s'
- attribute.unknown: Unknown attribute
+ block.minecraft.acacia_hanging_sign: Acacia Hanging Sign
+ block.minecraft.acacia_wall_hanging_sign: Acacia Wall Hanging Sign
+ block.minecraft.bamboo_button: Bamboo Button
+ block.minecraft.bamboo_door: Bamboo Door
+ block.minecraft.bamboo_fence_gate: Bamboo Fence Gate
+ block.minecraft.bamboo_fence: Bamboo Fence
+ block.minecraft.bamboo_hanging_sign: Bamboo Hanging Sign
+ block.minecraft.bamboo_mosaic_slab: Bamboo Mosaic Slab
+ block.minecraft.bamboo_mosaic_stairs: Bamboo Mosaic Stairs
+ block.minecraft.bamboo_mosaic: Bamboo Mosaic
+ block.minecraft.bamboo_planks: Bamboo Planks
+ block.minecraft.bamboo_pressure_plate: Bamboo Pressure Plate
+ block.minecraft.bamboo_sign: Bamboo Sign
+ block.minecraft.bamboo_slab: Bamboo Slab
+ block.minecraft.bamboo_stairs: Bamboo Stairs
+ block.minecraft.bamboo_trapdoor: Bamboo Trapdoor
+ block.minecraft.bamboo_wall_hanging_sign: Bamboo Wall Hanging Sign
+ block.minecraft.bamboo_wall_sign: Bamboo Wall Sign
+ block.minecraft.birch_hanging_sign: Birch Hanging Sign
+ block.minecraft.birch_wall_hanging_sign: Birch Wall Hanging Sign
+ block.minecraft.chiseled_bookshelf: Chiseled Bookshelf
+ block.minecraft.crimson_hanging_sign: Crimson Hanging Sign
+ block.minecraft.crimson_wall_hanging_sign: Crimson Wall Hanging Sign
+ block.minecraft.dark_oak_hanging_sign: Dark Oak Hanging Sign
+ block.minecraft.dark_oak_wall_hanging_sign: Dark Oak Wall Hanging Sign
+ block.minecraft.jungle_hanging_sign: Jungle Hanging Sign
+ block.minecraft.jungle_wall_hanging_sign: Jungle Wall Hanging Sign
+ block.minecraft.mangrove_hanging_sign: Mangrove Hanging Sign
+ block.minecraft.mangrove_wall_hanging_sign: Mangrove Wall Hanging Sign
+ block.minecraft.oak_hanging_sign: Oak Hanging Sign
+ block.minecraft.oak_wall_hanging_sign: Oak Wall Hanging Sign
+ block.minecraft.spruce_hanging_sign: Spruce Hanging Sign
+ block.minecraft.spruce_wall_hanging_sign: Spruce Wall Hanging Sign
+ block.minecraft.warped_hanging_sign: Warped Hanging Sign
+ block.minecraft.warped_wall_hanging_sign: Warped Wall Hanging Sign
+ chat.deleted_marker: This chat message has been deleted by the server.
+ chat.disabled.chain_broken: Chat disabled due to broken chain. Please try reconnecting.
+ chat.filtered: Filtered by the server.
- chat.previewInput: Press [%s] to preview
- chat.tag.filtered: This message has been filtered by the server.
- chat.tag.modified.original: Original text: %s
+ chat.tag.system: Server message. Cannot be reported.
- chatPreview.warning.check: Do not notify again for this server
- chatPreview.warning.content: Chat Preview allows the server to see your messages before they are sent to other players. This allows a server to send you a preview of your chat messages with custom modifications and styling applied.

The Chat Preview behavior can be changed in your Chat Settings. Current setting is: [%s]
- chatPreview.warning.title: This server uses Chat Preview
- chatPreview.warning.toast: This server uses Chat Preview and can see your messages before they are sent to other players. You can turn this off in Chat Settings.
- chatPreview.warning.toast.title: Chat Preview is enabled
+ commands.datapack.enable.failed.no_flags: Pack '%s' cannot be enabled, since required flags are not enabled in this world: %s!
- commands.locate.biome.invalid: There is no biome with type "%s"
- commands.locate.poi.invalid: There is no point of interest with type "%s"
+ dataPack.bundle.description: Enables experimental Bundle item
+ dataPack.update_1_20.description: New features and content for Minecraft 1.20
+ dataPack.vanilla.name: Default
- effect.effectNotFound: Unknown effect: %s
- enchantment.unknown: Unknown enchantment: %s
+ entity.minecraft.camel: Camel
+ entity.not_summonable: Can't summon entity of type %s
- entity.notFound: Unknown entity: %s
+ hanging_sign.edit: Edit Hanging Sign Message
+ item.disabled: Disabled item
+ item.minecraft.bamboo_chest_raft: Bamboo Raft with Chest
+ item.minecraft.bamboo_raft: Bamboo Raft
+ item.minecraft.camel_spawn_egg: Camel Spawn Egg
- itemGroup.brewing: Brewing
+ itemGroup.consumables: Consumables
+ itemGroup.crafting: Crafting
- itemGroup.decorations: Decoration Blocks
- itemGroup.food: Foodstuffs
+ itemGroup.functional: Functional Blocks
- itemGroup.materials: Materials
- itemGroup.misc: Miscellaneous
+ itemGroup.nature: Nature Blocks
+ itemGroup.spawnEggs: Spawn Eggs
- itemGroup.transportation: Transportation
+ mco.account.privacy.info: Read more about Mojang and privacy laws
+ mco.account.privacyinfo: Mojang implements certain procedures to help protect children and their privacy including complying with the Children’s Online Privacy Protection Act (COPPA) and General Data Protection Regulation (GDPR).

You may need to obtain parental consent before accessing your Realms account.

If you have an older Minecraft account (you log in with your username), you need to migrate the account to a Mojang account in order to access Realms.
+ mco.account.update: Update account
+ mco.activity.noactivity: No activity for the past %s days
+ mco.activity.title: Player activity
+ mco.backup.button.download: Download latest
+ mco.backup.button.reset: Reset world
+ mco.backup.button.restore: Restore
+ mco.backup.button.upload: Upload world
+ mco.backup.changes.tooltip: Changes
+ mco.backup.generate.world: Generate world
+ mco.backup.nobackups: This realm doesn't have any backups currently.
+ mco.backup.restoring: Restoring your realm
+ mco.brokenworld.download: Download
+ mco.brokenworld.downloaded: Downloaded
+ mco.brokenworld.message.line1: Please reset or select another world.
+ mco.brokenworld.message.line2: You can also choose to download the world to singleplayer.
+ mco.brokenworld.minigame.title: This minigame is no longer supported
+ mco.brokenworld.nonowner.error: Please wait for the realm owner to reset the world
+ mco.brokenworld.nonowner.title: World is out of date
+ mco.brokenworld.play: Play
+ mco.brokenworld.reset: Reset
+ mco.brokenworld.title: Your current world is no longer supported
+ mco.client.incompatible.msg.line1: Your client is not compatible with Realms.
+ mco.client.incompatible.msg.line2: Please use the most recent version of Minecraft.
+ mco.client.incompatible.msg.line3: Realms is not compatible with snapshot versions.
+ mco.client.incompatible.title: Client incompatible!
+ mco.configure.current.minigame: Current
+ mco.configure.world.activityfeed.disabled: Player feed temporarily disabled
+ mco.configure.world.backup: World backups
+ mco.configure.world.buttons.activity: Player activity
+ mco.configure.world.buttons.close: Close realm
+ mco.configure.world.buttons.delete: Delete
+ mco.configure.world.buttons.done: Done
+ mco.configure.world.buttons.edit: Settings
+ mco.configure.world.buttons.invite: Invite player
+ mco.configure.world.buttons.moreoptions: More options
+ mco.configure.world.buttons.open: Open realm
+ mco.configure.world.buttons.options: World options
+ mco.configure.world.buttons.players: Players
+ mco.configure.world.buttons.resetworld: Reset world
+ mco.configure.world.buttons.settings: Settings
+ mco.configure.world.buttons.subscription: Subscription
+ mco.configure.world.buttons.switchminigame: Switch minigame
+ mco.configure.world.close.question.line1: Your realm will become unavailable.
+ mco.configure.world.close.question.line2: Are you sure you want to continue?
+ mco.configure.world.closing: Closing the realm...
+ mco.configure.world.commandBlocks: Command blocks
+ mco.configure.world.delete.button: Delete realm
+ mco.configure.world.delete.question.line1: Your realm will be permanently deleted
+ mco.configure.world.delete.question.line2: Are you sure you want to continue?
+ mco.configure.world.description: Realm description
+ mco.configure.world.edit.slot.name: World name
+ mco.configure.world.edit.subscreen.adventuremap: Some settings are disabled since your current world is an adventure
+ mco.configure.world.edit.subscreen.experience: Some settings are disabled since your current world is an experience
+ mco.configure.world.edit.subscreen.inspiration: Some settings are disabled since your current world is an inspiration
+ mco.configure.world.forceGameMode: Force game mode
+ mco.configure.world.invite.narration: You have %s new invites
+ mco.configure.world.invite.profile.name: Name
+ mco.configure.world.invited: Invited
+ mco.configure.world.invites.normal.tooltip: Normal user
+ mco.configure.world.invites.ops.tooltip: Operator
+ mco.configure.world.invites.remove.tooltip: Remove
+ mco.configure.world.leave.question.line1: If you leave this realm you won't see it unless you are invited again
+ mco.configure.world.leave.question.line2: Are you sure you want to continue?
+ mco.configure.world.location: Location
+ mco.configure.world.name: Realm name
+ mco.configure.world.opening: Opening the realm...
+ mco.configure.world.players.error: A player with the provided name does not exist
+ mco.configure.world.players.title: Players
+ mco.configure.world.pvp: PVP
+ mco.configure.world.reset.question.line1: Your world will be regenerated and your current world will be lost
+ mco.configure.world.reset.question.line2: Are you sure you want to continue?
+ mco.configure.world.resourcepack.question.line1: You need a custom resource pack to play on this realm
+ mco.configure.world.resourcepack.question.line2: Do you want to download it and play?
+ mco.configure.world.restore.download.question.line1: The world will be downloaded and added to your single player worlds.
+ mco.configure.world.restore.download.question.line2: Do you want to continue?
+ mco.configure.world.restore.question.line1: Your world will be restored to date '%s' (%s)
+ mco.configure.world.restore.question.line2: Are you sure you want to continue?
+ mco.configure.world.settings.title: Settings
+ mco.configure.world.slot: World %s
+ mco.configure.world.slot.empty: Empty
+ mco.configure.world.slot.switch.question.line1: Your realm will be switched to another world
+ mco.configure.world.slot.switch.question.line2: Are you sure you want to continue?
+ mco.configure.world.slot.tooltip: Switch to world
+ mco.configure.world.slot.tooltip.active: Join
+ mco.configure.world.slot.tooltip.minigame: Switch to minigame
+ mco.configure.world.spawn_toggle.message: Turning this option off will REMOVE ALL existing entities of that type
+ mco.configure.world.spawn_toggle.message.npc: Turning this option off will REMOVE ALL existing entities of that type, like Villagers
+ mco.configure.world.spawn_toggle.title: Warning!
+ mco.configure.world.spawnAnimals: Spawn animals
+ mco.configure.world.spawnMonsters: Spawn monsters
+ mco.configure.world.spawnNPCs: Spawn NPCs
+ mco.configure.world.spawnProtection: Spawn protection
+ mco.configure.world.status: Status
+ mco.configure.world.subscription.day: day
+ mco.configure.world.subscription.days: days
+ mco.configure.world.subscription.expired: Expired
+ mco.configure.world.subscription.extend: Extend subscription
+ mco.configure.world.subscription.less_than_a_day: Less than a day
+ mco.configure.world.subscription.month: month
+ mco.configure.world.subscription.months: months
+ mco.configure.world.subscription.recurring.daysleft: Renewed automatically in
+ mco.configure.world.subscription.start: Start date
+ mco.configure.world.subscription.timeleft: Time left
+ mco.configure.world.subscription.title: Your subscription
+ mco.configure.world.subscription.unknown: Unknown
+ mco.configure.world.switch.slot: Create world
+ mco.configure.world.switch.slot.subtitle: This world is empty, choose how to create your world
+ mco.configure.world.title: Configure realm:
+ mco.configure.world.uninvite.question: Are you sure that you want to uninvite
+ mco.configure.worlds.title: Worlds
+ mco.connect.authorizing: Logging in...
+ mco.connect.connecting: Connecting to the realm...
+ mco.connect.failed: Failed to connect to the realm
+ mco.connect.success: Done
+ mco.create.world: Create
+ mco.create.world.error: You must enter a name!
+ mco.create.world.reset.title: Creating world...
+ mco.create.world.skip: Skip
+ mco.create.world.subtitle: Optionally, select what world to put on your new realm
+ mco.create.world.wait: Creating the realm...
+ mco.download.cancelled: Download cancelled
+ mco.download.confirmation.line1: The world you are going to download is larger than %s
+ mco.download.confirmation.line2: You won't be able to upload this world to your realm again
+ mco.download.done: Download done
+ mco.download.downloading: Downloading
+ mco.download.extracting: Extracting
+ mco.download.failed: Download failed
+ mco.download.preparing: Preparing download
+ mco.download.title: Downloading latest world
+ mco.error.invalid.session.message: Please try restarting Minecraft
+ mco.error.invalid.session.title: Invalid session
+ mco.errorMessage.6001: Client outdated
+ mco.errorMessage.6002: Terms of service not accepted
+ mco.errorMessage.6003: Download limit reached
+ mco.errorMessage.6004: Upload limit reached
+ mco.errorMessage.connectionFailure: An error occurred, please try again later.
+ mco.errorMessage.serviceBusy: Realms is busy at the moment.
Please try connecting to your Realm again in a couple of minutes.
+ mco.gui.button: Button
+ mco.gui.ok: Ok
+ mco.invites.button.accept: Accept
+ mco.invites.button.reject: Reject
+ mco.invites.nopending: No pending invites!
+ mco.invites.pending: New invites!
+ mco.invites.title: Pending Invites
+ mco.minigame.world.changeButton: Select another minigame
+ mco.minigame.world.info.line1: This will temporarily replace your world with a minigame!
+ mco.minigame.world.info.line2: You can later return to your original world without losing anything.
+ mco.minigame.world.noSelection: Please make a selection
+ mco.minigame.world.restore: Ending minigame...
+ mco.minigame.world.restore.question.line1: The minigame will end and your realm will be restored.
+ mco.minigame.world.restore.question.line2: Are you sure you want to continue?
+ mco.minigame.world.selected: Selected minigame:
+ mco.minigame.world.slot.screen.title: Switching world...
+ mco.minigame.world.startButton: Switch
+ mco.minigame.world.starting.screen.title: Starting minigame...
+ mco.minigame.world.stopButton: End minigame
+ mco.minigame.world.switch.new: Select another minigame?
+ mco.minigame.world.switch.title: Switch minigame
+ mco.minigame.world.title: Switch realm to minigame
+ mco.news: Realms news
+ mco.reset.world.adventure: Adventures
+ mco.reset.world.experience: Experiences
+ mco.reset.world.generate: New world
+ mco.reset.world.inspiration: Inspiration
+ mco.reset.world.resetting.screen.title: Resetting world...
+ mco.reset.world.seed: Seed (Optional)
+ mco.reset.world.template: World templates
+ mco.reset.world.title: Reset world
+ mco.reset.world.upload: Upload world
+ mco.reset.world.warning: This will replace the current world of your realm
+ mco.selectServer.buy: Buy a realm!
+ mco.selectServer.close: Close
+ mco.selectServer.closed: Closed realm
+ mco.selectServer.closeserver: Close realm
+ mco.selectServer.configure: Configure realm
+ mco.selectServer.create: Create realm
+ mco.selectServer.expired: Expired realm
+ mco.selectServer.expiredList: Your subscription has expired
+ mco.selectServer.expiredRenew: Renew
+ mco.selectServer.expiredSubscribe: Subscribe
+ mco.selectServer.expiredTrial: Your trial has ended
+ mco.selectServer.expires.day: Expires in a day
+ mco.selectServer.expires.days: Expires in %s days
+ mco.selectServer.expires.soon: Expires soon
+ mco.selectServer.leave: Leave realm
+ mco.selectServer.mapOnlySupportedForVersion: This map is unsupported in %s
+ mco.selectServer.minigame: Minigame:
+ mco.selectServer.minigameNotSupportedInVersion: Can't play this minigame in %s
+ mco.selectServer.note: Note:
+ mco.selectServer.open: Open realm
+ mco.selectServer.openserver: Open realm
+ mco.selectServer.play: Play
+ mco.selectServer.popup: Realms is a safe, simple way to enjoy an online Minecraft world with up to ten friends at a time.   It supports loads of minigames and plenty of custom worlds! Only the owner of the realm needs to pay.
+ mco.selectServer.purchase: Add Realm
+ mco.selectServer.trial: Get a trial!
+ mco.selectServer.uninitialized: Click to start your new realm!
+ mco.template.button.publisher: Publisher
+ mco.template.button.select: Select
+ mco.template.button.trailer: Trailer
+ mco.template.default.name: World template
+ mco.template.info.tooltip: Publisher website
+ mco.template.name: Template
+ mco.template.select.failure: We couldn't retrieve the list of content for this category.
Please check your internet connection, or try again later.
+ mco.template.select.narrate.authors: Authors: %s
+ mco.template.select.narrate.version: version %s
+ mco.template.select.none: Oops, it looks like this content category is currently empty.
Please check back later for new content, or if you're a creator,
%s.
+ mco.template.select.none.linkTitle: consider submitting something yourself
+ mco.template.title: World templates
+ mco.template.title.minigame: Minigames
+ mco.template.trailer.tooltip: Map trailer
+ mco.terms.buttons.agree: Agree
+ mco.terms.buttons.disagree: Don't agree
+ mco.terms.sentence.1: I agree to the Minecraft Realms
+ mco.terms.sentence.2: Terms of Service
+ mco.terms.title: Realms Terms of Service
+ mco.trial.message.line1: Want to get your own realm?
+ mco.trial.message.line2: Click here for more info!
+ mco.upload.button.name: Upload
+ mco.upload.cancelled: Upload cancelled
+ mco.upload.close.failure: Could not close your realm, please try again later
+ mco.upload.done: Upload done
+ mco.upload.failed: Upload failed! (%s)
+ mco.upload.hardcore: Hardcore worlds can't be uploaded!
+ mco.upload.preparing: Preparing your world
+ mco.upload.select.world.none: No singleplayer worlds found!
+ mco.upload.select.world.subtitle: Please select a singleplayer world to upload
+ mco.upload.select.world.title: Upload world
+ mco.upload.size.failure.line1: '%s' is too big!
+ mco.upload.size.failure.line2: It is %s. The maximum allowed size is %s.
+ mco.upload.uploading: Uploading '%s'
+ mco.upload.verifying: Verifying your world
+ options.accessibility.panorama_speed: Panorama Scroll Speed
- options.chatPreview: Chat Preview
- options.chatPreview.confirm: When Sending
- options.chatPreview.live: While Typing
- options.chatPreview.tooltip.confirm: If a server uses Chat Previews: A chat preview is only generated when attempting to send a message that does not have a preview or is waiting for a preview.
Sending the message requires confirmation.
- options.chatPreview.tooltip.live: If a server uses Chat Previews: Any modifications applied to your chat messages by a server will be dynamically sent for previewing as the chat message is typed.
- options.chatPreview.tooltip.off: Any modifications applied to your chat messages by a server will not be previewed and will be treated as insecure.
+ pack.source.feature: feature
+ resourcePack.programmer_art.name: Programmer Art
+ resourcePack.vanilla.name: Default
+ selectWorld.experimental: Experimental
+ selectWorld.experimental.details: Details
+ selectWorld.experimental.details.entry: Required experimental features: %s
+ selectWorld.experimental.details.title: Experimental feature requirements
+ selectWorld.experimental.message: Be careful!
Some of the selected packs require features that are still under development. Your world might crash, break or not work with future updates.
+ selectWorld.experimental.title: Experimental Features Warning
- selectWorld.import_worldgen_settings.deprecated.question: Some features used are deprecated and will stop working in the future. Do you wish to proceed?
- selectWorld.import_worldgen_settings.deprecated.title: Warning! These settings are using deprecated features
- selectWorld.import_worldgen_settings.experimental.question: These settings are experimental and could one day stop working. Do you wish to proceed?
- selectWorld.import_worldgen_settings.experimental.title: Warning! These settings are using experimental features
+ selectWorld.warning.deprecated.question: Some features used are deprecated and will stop working in the future. Do you wish to proceed?
+ selectWorld.warning.deprecated.title: Warning! These settings are using deprecated features
+ selectWorld.warning.experimental.question: These settings are experimental and could one day stop working. Do you wish to proceed?
+ selectWorld.warning.experimental.title: Warning! These settings are using experimental features
+ subtitles.entity.camel.ambient: Camel grunts
+ subtitles.entity.camel.dash_ready: Camel recovers
+ subtitles.entity.camel.dash: Camel yeets
+ subtitles.entity.camel.death: Camel dies
+ subtitles.entity.camel.eat: Camel eats
+ subtitles.entity.camel.hurt: Camel hurts
+ subtitles.entity.camel.saddle: Saddle equips
+ subtitles.entity.camel.sit: Camel sits down
+ subtitles.entity.camel.stand: Camel stands up
+ subtitles.entity.camel.step_sand: Camel sands
+ subtitles.entity.camel.step: Camel steps
+ subtitles.entity.tadpole.grow_up: Tadpole grows up
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.19.2</th><th>22w42a</th></tr>
<tr><th align="left"><div style="width:290px">chat.tag.not_secure</div></th><td>This message is not secure, which means that it might have been modified by the server</td><td>Unverified message. Cannot be reported.</td></tr>
<tr><th align="left"><div style="width:290px">chat.tag.modified</div></th><td>This message has been modified by the server.</td><td>Message modified by the server. Original:</td></tr>
<tr><th align="left"><div style="width:290px">resourcePack.vanilla.description</div></th><td>The default resources for Minecraft</td><td>The default look and feel of Minecraft</td></tr>
<tr><th align="left"><div style="width:290px">itemGroup.redstone</div></th><td>Redstone</td><td>Redstone Blocks</td></tr>
<tr><th align="left"><div style="width:290px">itemGroup.tools</div></th><td>Tools</td><td>Tools & Utilities</td></tr>
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
- reports/minecraft/chat_type/chat.json
- reports/minecraft/chat_type/emote_command.json
- reports/minecraft/chat_type/msg_command_incoming.json
- reports/minecraft/chat_type/msg_command_outgoing.json
- reports/minecraft/chat_type/say_command.json
- reports/minecraft/chat_type/team_msg_command_incoming.json
- reports/minecraft/chat_type/team_msg_command_outgoing.json
- reports/minecraft/dimension_type/overworld_caves.json
- reports/minecraft/dimension_type/overworld.json
- reports/minecraft/dimension_type/the_end.json
- reports/minecraft/dimension_type/the_nether.json
- reports/minecraft/worldgen/biome/badlands.json
- reports/minecraft/worldgen/biome/bamboo_jungle.json
- reports/minecraft/worldgen/biome/basalt_deltas.json
- reports/minecraft/worldgen/biome/beach.json
- reports/minecraft/worldgen/biome/birch_forest.json
- reports/minecraft/worldgen/biome/cold_ocean.json
- reports/minecraft/worldgen/biome/crimson_forest.json
- reports/minecraft/worldgen/biome/dark_forest.json
- reports/minecraft/worldgen/biome/deep_cold_ocean.json
- reports/minecraft/worldgen/biome/deep_dark.json
- reports/minecraft/worldgen/biome/deep_frozen_ocean.json
- reports/minecraft/worldgen/biome/deep_lukewarm_ocean.json
- reports/minecraft/worldgen/biome/deep_ocean.json
- reports/minecraft/worldgen/biome/desert.json
- reports/minecraft/worldgen/biome/dripstone_caves.json
- reports/minecraft/worldgen/biome/end_barrens.json
- reports/minecraft/worldgen/biome/end_highlands.json
- reports/minecraft/worldgen/biome/end_midlands.json
- reports/minecraft/worldgen/biome/eroded_badlands.json
- reports/minecraft/worldgen/biome/flower_forest.json
- reports/minecraft/worldgen/biome/forest.json
- reports/minecraft/worldgen/biome/frozen_ocean.json
- reports/minecraft/worldgen/biome/frozen_peaks.json
- reports/minecraft/worldgen/biome/frozen_river.json
- reports/minecraft/worldgen/biome/grove.json
- reports/minecraft/worldgen/biome/ice_spikes.json
- reports/minecraft/worldgen/biome/jagged_peaks.json
- reports/minecraft/worldgen/biome/jungle.json
- reports/minecraft/worldgen/biome/lukewarm_ocean.json
- reports/minecraft/worldgen/biome/lush_caves.json
- reports/minecraft/worldgen/biome/mangrove_swamp.json
- reports/minecraft/worldgen/biome/meadow.json
- reports/minecraft/worldgen/biome/mushroom_fields.json
- reports/minecraft/worldgen/biome/nether_wastes.json
- reports/minecraft/worldgen/biome/ocean.json
- reports/minecraft/worldgen/biome/old_growth_birch_forest.json
- reports/minecraft/worldgen/biome/old_growth_pine_taiga.json
- reports/minecraft/worldgen/biome/old_growth_spruce_taiga.json
- reports/minecraft/worldgen/biome/plains.json
- reports/minecraft/worldgen/biome/river.json
- reports/minecraft/worldgen/biome/savanna_plateau.json
- reports/minecraft/worldgen/biome/savanna.json
- reports/minecraft/worldgen/biome/small_end_islands.json
- reports/minecraft/worldgen/biome/snowy_beach.json
- reports/minecraft/worldgen/biome/snowy_plains.json
- reports/minecraft/worldgen/biome/snowy_slopes.json
- reports/minecraft/worldgen/biome/snowy_taiga.json
- reports/minecraft/worldgen/biome/soul_sand_valley.json
- reports/minecraft/worldgen/biome/sparse_jungle.json
- reports/minecraft/worldgen/biome/stony_peaks.json
- reports/minecraft/worldgen/biome/stony_shore.json
- reports/minecraft/worldgen/biome/sunflower_plains.json
- reports/minecraft/worldgen/biome/swamp.json
- reports/minecraft/worldgen/biome/taiga.json
- reports/minecraft/worldgen/biome/the_end.json
- reports/minecraft/worldgen/biome/the_void.json
- reports/minecraft/worldgen/biome/warm_ocean.json
- reports/minecraft/worldgen/biome/warped_forest.json
- reports/minecraft/worldgen/biome/windswept_forest.json
- reports/minecraft/worldgen/biome/windswept_gravelly_hills.json
- reports/minecraft/worldgen/biome/windswept_hills.json
- reports/minecraft/worldgen/biome/windswept_savanna.json
- reports/minecraft/worldgen/biome/wooded_badlands.json
- reports/minecraft/worldgen/configured_carver/canyon.json
- reports/minecraft/worldgen/configured_carver/cave_extra_underground.json
- reports/minecraft/worldgen/configured_carver/cave.json
- reports/minecraft/worldgen/configured_carver/nether_cave.json
- reports/minecraft/worldgen/configured_feature/acacia.json
- reports/minecraft/worldgen/configured_feature/amethyst_geode.json
- reports/minecraft/worldgen/configured_feature/azalea_tree.json
- reports/minecraft/worldgen/configured_feature/bamboo_no_podzol.json
- reports/minecraft/worldgen/configured_feature/bamboo_some_podzol.json
- reports/minecraft/worldgen/configured_feature/bamboo_vegetation.json
- reports/minecraft/worldgen/configured_feature/basalt_blobs.json
- reports/minecraft/worldgen/configured_feature/basalt_pillar.json
- reports/minecraft/worldgen/configured_feature/birch_bees_0002.json
- reports/minecraft/worldgen/configured_feature/birch_bees_002.json
- reports/minecraft/worldgen/configured_feature/birch_bees_005.json
- reports/minecraft/worldgen/configured_feature/birch_tall.json
- reports/minecraft/worldgen/configured_feature/birch.json
- reports/minecraft/worldgen/configured_feature/blackstone_blobs.json
- reports/minecraft/worldgen/configured_feature/blue_ice.json
- reports/minecraft/worldgen/configured_feature/bonus_chest.json
- reports/minecraft/worldgen/configured_feature/cave_vine_in_moss.json
- reports/minecraft/worldgen/configured_feature/cave_vine.json
- reports/minecraft/worldgen/configured_feature/chorus_plant.json
- reports/minecraft/worldgen/configured_feature/clay_pool_with_dripleaves.json
- reports/minecraft/worldgen/configured_feature/clay_with_dripleaves.json
- reports/minecraft/worldgen/configured_feature/crimson_forest_vegetation_bonemeal.json
- reports/minecraft/worldgen/configured_feature/crimson_forest_vegetation.json
- reports/minecraft/worldgen/configured_feature/crimson_fungus_planted.json
- reports/minecraft/worldgen/configured_feature/crimson_fungus.json
- reports/minecraft/worldgen/configured_feature/dark_forest_vegetation.json
- reports/minecraft/worldgen/configured_feature/dark_oak.json
- reports/minecraft/worldgen/configured_feature/delta.json
- reports/minecraft/worldgen/configured_feature/desert_well.json
- reports/minecraft/worldgen/configured_feature/disk_clay.json
- reports/minecraft/worldgen/configured_feature/disk_grass.json
- reports/minecraft/worldgen/configured_feature/disk_gravel.json
- reports/minecraft/worldgen/configured_feature/disk_sand.json
- reports/minecraft/worldgen/configured_feature/dripleaf.json
- reports/minecraft/worldgen/configured_feature/dripstone_cluster.json
- reports/minecraft/worldgen/configured_feature/end_gateway_delayed.json
- reports/minecraft/worldgen/configured_feature/end_gateway_return.json
- reports/minecraft/worldgen/configured_feature/end_island.json
- reports/minecraft/worldgen/configured_feature/end_spike.json
- reports/minecraft/worldgen/configured_feature/fancy_oak_bees_0002.json
- reports/minecraft/worldgen/configured_feature/fancy_oak_bees_002.json
- reports/minecraft/worldgen/configured_feature/fancy_oak_bees_005.json
- reports/minecraft/worldgen/configured_feature/fancy_oak_bees.json
- reports/minecraft/worldgen/configured_feature/fancy_oak.json
- reports/minecraft/worldgen/configured_feature/flower_default.json
- reports/minecraft/worldgen/configured_feature/flower_flower_forest.json
- reports/minecraft/worldgen/configured_feature/flower_meadow.json
- reports/minecraft/worldgen/configured_feature/flower_plain.json
- reports/minecraft/worldgen/configured_feature/flower_swamp.json
- reports/minecraft/worldgen/configured_feature/forest_flowers.json
- reports/minecraft/worldgen/configured_feature/forest_rock.json
- reports/minecraft/worldgen/configured_feature/fossil_coal.json
- reports/minecraft/worldgen/configured_feature/fossil_diamonds.json
- reports/minecraft/worldgen/configured_feature/freeze_top_layer.json
- reports/minecraft/worldgen/configured_feature/glow_lichen.json
- reports/minecraft/worldgen/configured_feature/glowstone_extra.json
- reports/minecraft/worldgen/configured_feature/huge_brown_mushroom.json
- reports/minecraft/worldgen/configured_feature/huge_red_mushroom.json
- reports/minecraft/worldgen/configured_feature/ice_patch.json
- reports/minecraft/worldgen/configured_feature/ice_spike.json
- reports/minecraft/worldgen/configured_feature/iceberg_blue.json
- reports/minecraft/worldgen/configured_feature/iceberg_packed.json
- reports/minecraft/worldgen/configured_feature/jungle_bush.json
- reports/minecraft/worldgen/configured_feature/jungle_tree_no_vine.json
- reports/minecraft/worldgen/configured_feature/jungle_tree.json
- reports/minecraft/worldgen/configured_feature/kelp.json
- reports/minecraft/worldgen/configured_feature/lake_lava.json
- reports/minecraft/worldgen/configured_feature/large_basalt_columns.json
- reports/minecraft/worldgen/configured_feature/large_dripstone.json
- reports/minecraft/worldgen/configured_feature/lush_caves_clay.json
- reports/minecraft/worldgen/configured_feature/mangrove_vegetation.json
- reports/minecraft/worldgen/configured_feature/mangrove.json
- reports/minecraft/worldgen/configured_feature/meadow_trees.json
- reports/minecraft/worldgen/configured_feature/mega_jungle_tree.json
- reports/minecraft/worldgen/configured_feature/mega_pine.json
- reports/minecraft/worldgen/configured_feature/mega_spruce.json
- reports/minecraft/worldgen/configured_feature/monster_room.json
- reports/minecraft/worldgen/configured_feature/moss_patch_bonemeal.json
- reports/minecraft/worldgen/configured_feature/moss_patch_ceiling.json
- reports/minecraft/worldgen/configured_feature/moss_patch.json
- reports/minecraft/worldgen/configured_feature/moss_vegetation.json
- reports/minecraft/worldgen/configured_feature/mushroom_island_vegetation.json
- reports/minecraft/worldgen/configured_feature/nether_sprouts_bonemeal.json
- reports/minecraft/worldgen/configured_feature/nether_sprouts.json
- reports/minecraft/worldgen/configured_feature/oak_bees_0002.json
- reports/minecraft/worldgen/configured_feature/oak_bees_002.json
- reports/minecraft/worldgen/configured_feature/oak_bees_005.json
- reports/minecraft/worldgen/configured_feature/oak.json
- reports/minecraft/worldgen/configured_feature/ore_ancient_debris_large.json
- reports/minecraft/worldgen/configured_feature/ore_ancient_debris_small.json
- reports/minecraft/worldgen/configured_feature/ore_andesite.json
- reports/minecraft/worldgen/configured_feature/ore_blackstone.json
- reports/minecraft/worldgen/configured_feature/ore_clay.json
- reports/minecraft/worldgen/configured_feature/ore_coal_buried.json
- reports/minecraft/worldgen/configured_feature/ore_coal.json
- reports/minecraft/worldgen/configured_feature/ore_copper_large.json
- reports/minecraft/worldgen/configured_feature/ore_copper_small.json
- reports/minecraft/worldgen/configured_feature/ore_diamond_buried.json
- reports/minecraft/worldgen/configured_feature/ore_diamond_large.json
- reports/minecraft/worldgen/configured_feature/ore_diamond_small.json
- reports/minecraft/worldgen/configured_feature/ore_diorite.json
- reports/minecraft/worldgen/configured_feature/ore_dirt.json
- reports/minecraft/worldgen/configured_feature/ore_emerald.json
- reports/minecraft/worldgen/configured_feature/ore_gold_buried.json
- reports/minecraft/worldgen/configured_feature/ore_gold.json
- reports/minecraft/worldgen/configured_feature/ore_granite.json
- reports/minecraft/worldgen/configured_feature/ore_gravel_nether.json
- reports/minecraft/worldgen/configured_feature/ore_gravel.json
- reports/minecraft/worldgen/configured_feature/ore_infested.json
- reports/minecraft/worldgen/configured_feature/ore_iron_small.json
- reports/minecraft/worldgen/configured_feature/ore_iron.json
- reports/minecraft/worldgen/configured_feature/ore_lapis_buried.json
- reports/minecraft/worldgen/configured_feature/ore_lapis.json
- reports/minecraft/worldgen/configured_feature/ore_magma.json
- reports/minecraft/worldgen/configured_feature/ore_nether_gold.json
- reports/minecraft/worldgen/configured_feature/ore_quartz.json
- reports/minecraft/worldgen/configured_feature/ore_redstone.json
- reports/minecraft/worldgen/configured_feature/ore_soul_sand.json
- reports/minecraft/worldgen/configured_feature/ore_tuff.json
- reports/minecraft/worldgen/configured_feature/patch_berry_bush.json
- reports/minecraft/worldgen/configured_feature/patch_brown_mushroom.json
- reports/minecraft/worldgen/configured_feature/patch_cactus.json
- reports/minecraft/worldgen/configured_feature/patch_crimson_roots.json
- reports/minecraft/worldgen/configured_feature/patch_dead_bush.json
- reports/minecraft/worldgen/configured_feature/patch_fire.json
- reports/minecraft/worldgen/configured_feature/patch_grass_jungle.json
- reports/minecraft/worldgen/configured_feature/patch_grass.json
- reports/minecraft/worldgen/configured_feature/patch_large_fern.json
- reports/minecraft/worldgen/configured_feature/patch_melon.json
- reports/minecraft/worldgen/configured_feature/patch_pumpkin.json
- reports/minecraft/worldgen/configured_feature/patch_red_mushroom.json
- reports/minecraft/worldgen/configured_feature/patch_soul_fire.json
- reports/minecraft/worldgen/configured_feature/patch_sugar_cane.json
- reports/minecraft/worldgen/configured_feature/patch_sunflower.json
- reports/minecraft/worldgen/configured_feature/patch_taiga_grass.json
- reports/minecraft/worldgen/configured_feature/patch_tall_grass.json
- reports/minecraft/worldgen/configured_feature/patch_waterlily.json
- reports/minecraft/worldgen/configured_feature/pile_hay.json
- reports/minecraft/worldgen/configured_feature/pile_ice.json
- reports/minecraft/worldgen/configured_feature/pile_melon.json
- reports/minecraft/worldgen/configured_feature/pile_pumpkin.json
- reports/minecraft/worldgen/configured_feature/pile_snow.json
- reports/minecraft/worldgen/configured_feature/pine.json
- reports/minecraft/worldgen/configured_feature/pointed_dripstone.json
- reports/minecraft/worldgen/configured_feature/rooted_azalea_tree.json
- reports/minecraft/worldgen/configured_feature/sculk_patch_ancient_city.json
- reports/minecraft/worldgen/configured_feature/sculk_patch_deep_dark.json
- reports/minecraft/worldgen/configured_feature/sculk_vein.json
- reports/minecraft/worldgen/configured_feature/sea_pickle.json
- reports/minecraft/worldgen/configured_feature/seagrass_mid.json
- reports/minecraft/worldgen/configured_feature/seagrass_short.json
- reports/minecraft/worldgen/configured_feature/seagrass_simple.json
- reports/minecraft/worldgen/configured_feature/seagrass_slightly_less_short.json
- reports/minecraft/worldgen/configured_feature/seagrass_tall.json
- reports/minecraft/worldgen/configured_feature/single_piece_of_grass.json
- reports/minecraft/worldgen/configured_feature/small_basalt_columns.json
- reports/minecraft/worldgen/configured_feature/spore_blossom.json
- reports/minecraft/worldgen/configured_feature/spring_lava_frozen.json
- reports/minecraft/worldgen/configured_feature/spring_lava_nether.json
- reports/minecraft/worldgen/configured_feature/spring_lava_overworld.json
- reports/minecraft/worldgen/configured_feature/spring_nether_closed.json
- reports/minecraft/worldgen/configured_feature/spring_nether_open.json
- reports/minecraft/worldgen/configured_feature/spring_water.json
- reports/minecraft/worldgen/configured_feature/spruce.json
- reports/minecraft/worldgen/configured_feature/super_birch_bees_0002.json
- reports/minecraft/worldgen/configured_feature/super_birch_bees.json
- reports/minecraft/worldgen/configured_feature/swamp_oak.json
- reports/minecraft/worldgen/configured_feature/tall_mangrove.json
- reports/minecraft/worldgen/configured_feature/trees_birch_and_oak.json
- reports/minecraft/worldgen/configured_feature/trees_flower_forest.json
- reports/minecraft/worldgen/configured_feature/trees_grove.json
- reports/minecraft/worldgen/configured_feature/trees_jungle.json
- reports/minecraft/worldgen/configured_feature/trees_old_growth_pine_taiga.json
- reports/minecraft/worldgen/configured_feature/trees_old_growth_spruce_taiga.json
- reports/minecraft/worldgen/configured_feature/trees_plains.json
- reports/minecraft/worldgen/configured_feature/trees_savanna.json
- reports/minecraft/worldgen/configured_feature/trees_sparse_jungle.json
- reports/minecraft/worldgen/configured_feature/trees_taiga.json
- reports/minecraft/worldgen/configured_feature/trees_water.json
- reports/minecraft/worldgen/configured_feature/trees_windswept_hills.json
- reports/minecraft/worldgen/configured_feature/twisting_vines_bonemeal.json
- reports/minecraft/worldgen/configured_feature/twisting_vines.json
- reports/minecraft/worldgen/configured_feature/underwater_magma.json
- reports/minecraft/worldgen/configured_feature/vines.json
- reports/minecraft/worldgen/configured_feature/void_start_platform.json
- reports/minecraft/worldgen/configured_feature/warm_ocean_vegetation.json
- reports/minecraft/worldgen/configured_feature/warped_forest_vegetation_bonemeal.json
- reports/minecraft/worldgen/configured_feature/warped_forest_vegetation.json
- reports/minecraft/worldgen/configured_feature/warped_fungus_planted.json
- reports/minecraft/worldgen/configured_feature/warped_fungus.json
- reports/minecraft/worldgen/configured_feature/weeping_vines.json
- reports/minecraft/worldgen/density_function/end/base_3d_noise.json
- reports/minecraft/worldgen/density_function/end/sloped_cheese.json
- reports/minecraft/worldgen/density_function/nether/base_3d_noise.json
- reports/minecraft/worldgen/density_function/overworld_amplified/depth.json
- reports/minecraft/worldgen/density_function/overworld_amplified/factor.json
- reports/minecraft/worldgen/density_function/overworld_amplified/jaggedness.json
- reports/minecraft/worldgen/density_function/overworld_amplified/offset.json
- reports/minecraft/worldgen/density_function/overworld_amplified/sloped_cheese.json
- reports/minecraft/worldgen/density_function/overworld_large_biomes/continents.json
- reports/minecraft/worldgen/density_function/overworld_large_biomes/depth.json
- reports/minecraft/worldgen/density_function/overworld_large_biomes/erosion.json
- reports/minecraft/worldgen/density_function/overworld_large_biomes/factor.json
- reports/minecraft/worldgen/density_function/overworld_large_biomes/jaggedness.json
- reports/minecraft/worldgen/density_function/overworld_large_biomes/offset.json
- reports/minecraft/worldgen/density_function/overworld_large_biomes/sloped_cheese.json
- reports/minecraft/worldgen/density_function/overworld/base_3d_noise.json
- reports/minecraft/worldgen/density_function/overworld/caves/entrances.json
- reports/minecraft/worldgen/density_function/overworld/caves/noodle.json
- reports/minecraft/worldgen/density_function/overworld/caves/pillars.json
- reports/minecraft/worldgen/density_function/overworld/caves/spaghetti_2d_thickness_modulator.json
- reports/minecraft/worldgen/density_function/overworld/caves/spaghetti_2d.json
- reports/minecraft/worldgen/density_function/overworld/caves/spaghetti_roughness_function.json
- reports/minecraft/worldgen/density_function/overworld/continents.json
- reports/minecraft/worldgen/density_function/overworld/depth.json
- reports/minecraft/worldgen/density_function/overworld/erosion.json
- reports/minecraft/worldgen/density_function/overworld/factor.json
- reports/minecraft/worldgen/density_function/overworld/jaggedness.json
- reports/minecraft/worldgen/density_function/overworld/offset.json
- reports/minecraft/worldgen/density_function/overworld/ridges_folded.json
- reports/minecraft/worldgen/density_function/overworld/ridges.json
- reports/minecraft/worldgen/density_function/overworld/sloped_cheese.json
- reports/minecraft/worldgen/density_function/shift_x.json
- reports/minecraft/worldgen/density_function/shift_z.json
- reports/minecraft/worldgen/density_function/y.json
- reports/minecraft/worldgen/density_function/zero.json
- reports/minecraft/worldgen/flat_level_generator_preset/bottomless_pit.json
- reports/minecraft/worldgen/flat_level_generator_preset/classic_flat.json
- reports/minecraft/worldgen/flat_level_generator_preset/desert.json
- reports/minecraft/worldgen/flat_level_generator_preset/overworld.json
- reports/minecraft/worldgen/flat_level_generator_preset/redstone_ready.json
- reports/minecraft/worldgen/flat_level_generator_preset/snowy_kingdom.json
- reports/minecraft/worldgen/flat_level_generator_preset/the_void.json
- reports/minecraft/worldgen/flat_level_generator_preset/tunnelers_dream.json
- reports/minecraft/worldgen/flat_level_generator_preset/water_world.json
- reports/minecraft/worldgen/noise_settings/amplified.json
- reports/minecraft/worldgen/noise_settings/caves.json
- reports/minecraft/worldgen/noise_settings/end.json
- reports/minecraft/worldgen/noise_settings/floating_islands.json
- reports/minecraft/worldgen/noise_settings/large_biomes.json
- reports/minecraft/worldgen/noise_settings/nether.json
- reports/minecraft/worldgen/noise_settings/overworld.json
- reports/minecraft/worldgen/noise/aquifer_barrier.json
- reports/minecraft/worldgen/noise/aquifer_fluid_level_floodedness.json
- reports/minecraft/worldgen/noise/aquifer_fluid_level_spread.json
- reports/minecraft/worldgen/noise/aquifer_lava.json
- reports/minecraft/worldgen/noise/badlands_pillar_roof.json
- reports/minecraft/worldgen/noise/badlands_pillar.json
- reports/minecraft/worldgen/noise/badlands_surface.json
- reports/minecraft/worldgen/noise/calcite.json
- reports/minecraft/worldgen/noise/cave_cheese.json
- reports/minecraft/worldgen/noise/cave_entrance.json
- reports/minecraft/worldgen/noise/cave_layer.json
- reports/minecraft/worldgen/noise/clay_bands_offset.json
- reports/minecraft/worldgen/noise/continentalness_large.json
- reports/minecraft/worldgen/noise/continentalness.json
- reports/minecraft/worldgen/noise/erosion_large.json
- reports/minecraft/worldgen/noise/erosion.json
- reports/minecraft/worldgen/noise/gravel_layer.json
- reports/minecraft/worldgen/noise/gravel.json
- reports/minecraft/worldgen/noise/ice.json
- reports/minecraft/worldgen/noise/iceberg_pillar_roof.json
- reports/minecraft/worldgen/noise/iceberg_pillar.json
- reports/minecraft/worldgen/noise/iceberg_surface.json
- reports/minecraft/worldgen/noise/jagged.json
- reports/minecraft/worldgen/noise/nether_state_selector.json
- reports/minecraft/worldgen/noise/nether_wart.json
- reports/minecraft/worldgen/noise/netherrack.json
- reports/minecraft/worldgen/noise/noodle_ridge_a.json
- reports/minecraft/worldgen/noise/noodle_ridge_b.json
- reports/minecraft/worldgen/noise/noodle_thickness.json
- reports/minecraft/worldgen/noise/noodle.json
- reports/minecraft/worldgen/noise/offset.json
- reports/minecraft/worldgen/noise/ore_gap.json
- reports/minecraft/worldgen/noise/ore_vein_a.json
- reports/minecraft/worldgen/noise/ore_vein_b.json
- reports/minecraft/worldgen/noise/ore_veininess.json
- reports/minecraft/worldgen/noise/packed_ice.json
- reports/minecraft/worldgen/noise/patch.json
- reports/minecraft/worldgen/noise/pillar_rareness.json
- reports/minecraft/worldgen/noise/pillar_thickness.json
- reports/minecraft/worldgen/noise/pillar.json
- reports/minecraft/worldgen/noise/powder_snow.json
- reports/minecraft/worldgen/noise/ridge.json
- reports/minecraft/worldgen/noise/soul_sand_layer.json
- reports/minecraft/worldgen/noise/spaghetti_2d_elevation.json
- reports/minecraft/worldgen/noise/spaghetti_2d_modulator.json
- reports/minecraft/worldgen/noise/spaghetti_2d_thickness.json
- reports/minecraft/worldgen/noise/spaghetti_2d.json
- reports/minecraft/worldgen/noise/spaghetti_3d_1.json
- reports/minecraft/worldgen/noise/spaghetti_3d_2.json
- reports/minecraft/worldgen/noise/spaghetti_3d_rarity.json
- reports/minecraft/worldgen/noise/spaghetti_3d_thickness.json
- reports/minecraft/worldgen/noise/spaghetti_roughness_modulator.json
- reports/minecraft/worldgen/noise/spaghetti_roughness.json
- reports/minecraft/worldgen/noise/surface_secondary.json
- reports/minecraft/worldgen/noise/surface_swamp.json
- reports/minecraft/worldgen/noise/surface.json
- reports/minecraft/worldgen/noise/temperature_large.json
- reports/minecraft/worldgen/noise/temperature.json
- reports/minecraft/worldgen/noise/vegetation_large.json
- reports/minecraft/worldgen/noise/vegetation.json
- reports/minecraft/worldgen/placed_feature/acacia_checked.json
- reports/minecraft/worldgen/placed_feature/acacia.json
- reports/minecraft/worldgen/placed_feature/amethyst_geode.json
- reports/minecraft/worldgen/placed_feature/bamboo_light.json
- reports/minecraft/worldgen/placed_feature/bamboo_vegetation.json
- reports/minecraft/worldgen/placed_feature/bamboo.json
- reports/minecraft/worldgen/placed_feature/basalt_blobs.json
- reports/minecraft/worldgen/placed_feature/basalt_pillar.json
- reports/minecraft/worldgen/placed_feature/birch_bees_0002.json
- reports/minecraft/worldgen/placed_feature/birch_bees_002.json
- reports/minecraft/worldgen/placed_feature/birch_checked.json
- reports/minecraft/worldgen/placed_feature/birch_tall.json
- reports/minecraft/worldgen/placed_feature/blackstone_blobs.json
- reports/minecraft/worldgen/placed_feature/blue_ice.json
- reports/minecraft/worldgen/placed_feature/brown_mushroom_nether.json
- reports/minecraft/worldgen/placed_feature/brown_mushroom_normal.json
- reports/minecraft/worldgen/placed_feature/brown_mushroom_old_growth.json
- reports/minecraft/worldgen/placed_feature/brown_mushroom_swamp.json
- reports/minecraft/worldgen/placed_feature/brown_mushroom_taiga.json
- reports/minecraft/worldgen/placed_feature/cave_vines.json
- reports/minecraft/worldgen/placed_feature/chorus_plant.json
- reports/minecraft/worldgen/placed_feature/classic_vines_cave_feature.json
- reports/minecraft/worldgen/placed_feature/crimson_forest_vegetation.json
- reports/minecraft/worldgen/placed_feature/crimson_fungi.json
- reports/minecraft/worldgen/placed_feature/dark_forest_vegetation.json
- reports/minecraft/worldgen/placed_feature/dark_oak_checked.json
- reports/minecraft/worldgen/placed_feature/delta.json
- reports/minecraft/worldgen/placed_feature/desert_well.json
- reports/minecraft/worldgen/placed_feature/disk_clay.json
- reports/minecraft/worldgen/placed_feature/disk_grass.json
- reports/minecraft/worldgen/placed_feature/disk_gravel.json
- reports/minecraft/worldgen/placed_feature/disk_sand.json
- reports/minecraft/worldgen/placed_feature/dripstone_cluster.json
- reports/minecraft/worldgen/placed_feature/end_gateway_return.json
- reports/minecraft/worldgen/placed_feature/end_island_decorated.json
- reports/minecraft/worldgen/placed_feature/end_spike.json
- reports/minecraft/worldgen/placed_feature/fancy_oak_bees_0002.json
- reports/minecraft/worldgen/placed_feature/fancy_oak_bees_002.json
- reports/minecraft/worldgen/placed_feature/fancy_oak_bees.json
- reports/minecraft/worldgen/placed_feature/fancy_oak_checked.json
- reports/minecraft/worldgen/placed_feature/flower_default.json
- reports/minecraft/worldgen/placed_feature/flower_flower_forest.json
- reports/minecraft/worldgen/placed_feature/flower_forest_flowers.json
- reports/minecraft/worldgen/placed_feature/flower_meadow.json
- reports/minecraft/worldgen/placed_feature/flower_plain.json
- reports/minecraft/worldgen/placed_feature/flower_plains.json
- reports/minecraft/worldgen/placed_feature/flower_swamp.json
- reports/minecraft/worldgen/placed_feature/flower_warm.json
- reports/minecraft/worldgen/placed_feature/forest_flowers.json
- reports/minecraft/worldgen/placed_feature/forest_rock.json
- reports/minecraft/worldgen/placed_feature/fossil_lower.json
- reports/minecraft/worldgen/placed_feature/fossil_upper.json
- reports/minecraft/worldgen/placed_feature/freeze_top_layer.json
- reports/minecraft/worldgen/placed_feature/glow_lichen.json
- reports/minecraft/worldgen/placed_feature/glowstone_extra.json
- reports/minecraft/worldgen/placed_feature/glowstone.json
- reports/minecraft/worldgen/placed_feature/grass_bonemeal.json
- reports/minecraft/worldgen/placed_feature/ice_patch.json
- reports/minecraft/worldgen/placed_feature/ice_spike.json
- reports/minecraft/worldgen/placed_feature/iceberg_blue.json
- reports/minecraft/worldgen/placed_feature/iceberg_packed.json
- reports/minecraft/worldgen/placed_feature/jungle_bush.json
- reports/minecraft/worldgen/placed_feature/jungle_tree.json
- reports/minecraft/worldgen/placed_feature/kelp_cold.json
- reports/minecraft/worldgen/placed_feature/kelp_warm.json
- reports/minecraft/worldgen/placed_feature/lake_lava_surface.json
- reports/minecraft/worldgen/placed_feature/lake_lava_underground.json
- reports/minecraft/worldgen/placed_feature/large_basalt_columns.json
- reports/minecraft/worldgen/placed_feature/large_dripstone.json
- reports/minecraft/worldgen/placed_feature/lush_caves_ceiling_vegetation.json
- reports/minecraft/worldgen/placed_feature/lush_caves_clay.json
- reports/minecraft/worldgen/placed_feature/lush_caves_vegetation.json
- reports/minecraft/worldgen/placed_feature/mangrove_checked.json
- reports/minecraft/worldgen/placed_feature/mega_jungle_tree_checked.json
- reports/minecraft/worldgen/placed_feature/mega_pine_checked.json
- reports/minecraft/worldgen/placed_feature/mega_spruce_checked.json
- reports/minecraft/worldgen/placed_feature/monster_room_deep.json
- reports/minecraft/worldgen/placed_feature/monster_room.json
- reports/minecraft/worldgen/placed_feature/mushroom_island_vegetation.json
- reports/minecraft/worldgen/placed_feature/nether_sprouts.json
- reports/minecraft/worldgen/placed_feature/oak_bees_0002.json
- reports/minecraft/worldgen/placed_feature/oak_bees_002.json
- reports/minecraft/worldgen/placed_feature/oak_checked.json
- reports/minecraft/worldgen/placed_feature/oak.json
- reports/minecraft/worldgen/placed_feature/ore_ancient_debris_large.json
- reports/minecraft/worldgen/placed_feature/ore_andesite_lower.json
- reports/minecraft/worldgen/placed_feature/ore_andesite_upper.json
- reports/minecraft/worldgen/placed_feature/ore_blackstone.json
- reports/minecraft/worldgen/placed_feature/ore_clay.json
- reports/minecraft/worldgen/placed_feature/ore_coal_lower.json
- reports/minecraft/worldgen/placed_feature/ore_coal_upper.json
- reports/minecraft/worldgen/placed_feature/ore_copper_large.json
- reports/minecraft/worldgen/placed_feature/ore_copper.json
- reports/minecraft/worldgen/placed_feature/ore_debris_small.json
- reports/minecraft/worldgen/placed_feature/ore_diamond_buried.json
- reports/minecraft/worldgen/placed_feature/ore_diamond_large.json
- reports/minecraft/worldgen/placed_feature/ore_diamond.json
- reports/minecraft/worldgen/placed_feature/ore_diorite_lower.json
- reports/minecraft/worldgen/placed_feature/ore_diorite_upper.json
- reports/minecraft/worldgen/placed_feature/ore_dirt.json
- reports/minecraft/worldgen/placed_feature/ore_emerald.json
- reports/minecraft/worldgen/placed_feature/ore_gold_deltas.json
- reports/minecraft/worldgen/placed_feature/ore_gold_extra.json
- reports/minecraft/worldgen/placed_feature/ore_gold_lower.json
- reports/minecraft/worldgen/placed_feature/ore_gold_nether.json
- reports/minecraft/worldgen/placed_feature/ore_gold.json
- reports/minecraft/worldgen/placed_feature/ore_granite_lower.json
- reports/minecraft/worldgen/placed_feature/ore_granite_upper.json
- reports/minecraft/worldgen/placed_feature/ore_gravel_nether.json
- reports/minecraft/worldgen/placed_feature/ore_gravel.json
- reports/minecraft/worldgen/placed_feature/ore_infested.json
- reports/minecraft/worldgen/placed_feature/ore_iron_middle.json
- reports/minecraft/worldgen/placed_feature/ore_iron_small.json
- reports/minecraft/worldgen/placed_feature/ore_iron_upper.json
- reports/minecraft/worldgen/placed_feature/ore_lapis_buried.json
- reports/minecraft/worldgen/placed_feature/ore_lapis.json
- reports/minecraft/worldgen/placed_feature/ore_magma.json
- reports/minecraft/worldgen/placed_feature/ore_quartz_deltas.json
- reports/minecraft/worldgen/placed_feature/ore_quartz_nether.json
- reports/minecraft/worldgen/placed_feature/ore_redstone_lower.json
- reports/minecraft/worldgen/placed_feature/ore_redstone.json
- reports/minecraft/worldgen/placed_feature/ore_soul_sand.json
- reports/minecraft/worldgen/placed_feature/ore_tuff.json
- reports/minecraft/worldgen/placed_feature/patch_berry_bush.json
- reports/minecraft/worldgen/placed_feature/patch_berry_common.json
- reports/minecraft/worldgen/placed_feature/patch_berry_rare.json
- reports/minecraft/worldgen/placed_feature/patch_cactus_decorated.json
- reports/minecraft/worldgen/placed_feature/patch_cactus_desert.json
- reports/minecraft/worldgen/placed_feature/patch_cactus.json
- reports/minecraft/worldgen/placed_feature/patch_crimson_roots.json
- reports/minecraft/worldgen/placed_feature/patch_dead_bush_2.json
- reports/minecraft/worldgen/placed_feature/patch_dead_bush_badlands.json
- reports/minecraft/worldgen/placed_feature/patch_dead_bush.json
- reports/minecraft/worldgen/placed_feature/patch_fire.json
- reports/minecraft/worldgen/placed_feature/patch_grass_badlands.json
- reports/minecraft/worldgen/placed_feature/patch_grass_forest.json
- reports/minecraft/worldgen/placed_feature/patch_grass_jungle.json
- reports/minecraft/worldgen/placed_feature/patch_grass_normal.json
- reports/minecraft/worldgen/placed_feature/patch_grass_plain.json
- reports/minecraft/worldgen/placed_feature/patch_grass_savanna.json
- reports/minecraft/worldgen/placed_feature/patch_grass_taiga_2.json
- reports/minecraft/worldgen/placed_feature/patch_grass_taiga.json
- reports/minecraft/worldgen/placed_feature/patch_large_fern.json
- reports/minecraft/worldgen/placed_feature/patch_melon_sparse.json
- reports/minecraft/worldgen/placed_feature/patch_melon.json
- reports/minecraft/worldgen/placed_feature/patch_pumpkin.json
- reports/minecraft/worldgen/placed_feature/patch_soul_fire.json
- reports/minecraft/worldgen/placed_feature/patch_sugar_cane_badlands.json
- reports/minecraft/worldgen/placed_feature/patch_sugar_cane_desert.json
- reports/minecraft/worldgen/placed_feature/patch_sugar_cane_swamp.json
- reports/minecraft/worldgen/placed_feature/patch_sugar_cane.json
- reports/minecraft/worldgen/placed_feature/patch_sunflower.json
- reports/minecraft/worldgen/placed_feature/patch_taiga_grass.json
- reports/minecraft/worldgen/placed_feature/patch_tall_grass_2.json
- reports/minecraft/worldgen/placed_feature/patch_tall_grass.json
- reports/minecraft/worldgen/placed_feature/patch_waterlily.json
- reports/minecraft/worldgen/placed_feature/pile_hay.json
- reports/minecraft/worldgen/placed_feature/pile_ice.json
- reports/minecraft/worldgen/placed_feature/pile_melon.json
- reports/minecraft/worldgen/placed_feature/pile_pumpkin.json
- reports/minecraft/worldgen/placed_feature/pile_snow.json
- reports/minecraft/worldgen/placed_feature/pine_checked.json
- reports/minecraft/worldgen/placed_feature/pine_on_snow.json
- reports/minecraft/worldgen/placed_feature/pine.json
- reports/minecraft/worldgen/placed_feature/pointed_dripstone.json
- reports/minecraft/worldgen/placed_feature/red_mushroom_nether.json
- reports/minecraft/worldgen/placed_feature/red_mushroom_normal.json
- reports/minecraft/worldgen/placed_feature/red_mushroom_old_growth.json
- reports/minecraft/worldgen/placed_feature/red_mushroom_swamp.json
- reports/minecraft/worldgen/placed_feature/red_mushroom_taiga.json
- reports/minecraft/worldgen/placed_feature/rooted_azalea_tree.json
- reports/minecraft/worldgen/placed_feature/sculk_patch_ancient_city.json
- reports/minecraft/worldgen/placed_feature/sculk_patch_deep_dark.json
- reports/minecraft/worldgen/placed_feature/sculk_vein.json
- reports/minecraft/worldgen/placed_feature/sea_pickle.json
- reports/minecraft/worldgen/placed_feature/seagrass_cold.json
- reports/minecraft/worldgen/placed_feature/seagrass_deep_cold.json
- reports/minecraft/worldgen/placed_feature/seagrass_deep_warm.json
- reports/minecraft/worldgen/placed_feature/seagrass_deep.json
- reports/minecraft/worldgen/placed_feature/seagrass_normal.json
- reports/minecraft/worldgen/placed_feature/seagrass_river.json
- reports/minecraft/worldgen/placed_feature/seagrass_simple.json
- reports/minecraft/worldgen/placed_feature/seagrass_swamp.json
- reports/minecraft/worldgen/placed_feature/seagrass_warm.json
- reports/minecraft/worldgen/placed_feature/small_basalt_columns.json
- reports/minecraft/worldgen/placed_feature/spore_blossom.json
- reports/minecraft/worldgen/placed_feature/spring_closed_double.json
- reports/minecraft/worldgen/placed_feature/spring_closed.json
- reports/minecraft/worldgen/placed_feature/spring_delta.json
- reports/minecraft/worldgen/placed_feature/spring_lava_frozen.json
- reports/minecraft/worldgen/placed_feature/spring_lava.json
- reports/minecraft/worldgen/placed_feature/spring_open.json
- reports/minecraft/worldgen/placed_feature/spring_water.json
- reports/minecraft/worldgen/placed_feature/spruce_checked.json
- reports/minecraft/worldgen/placed_feature/spruce_on_snow.json
- reports/minecraft/worldgen/placed_feature/spruce.json
- reports/minecraft/worldgen/placed_feature/super_birch_bees_0002.json
- reports/minecraft/worldgen/placed_feature/super_birch_bees.json
- reports/minecraft/worldgen/placed_feature/tall_mangrove_checked.json
- reports/minecraft/worldgen/placed_feature/trees_badlands.json
- reports/minecraft/worldgen/placed_feature/trees_birch_and_oak.json
- reports/minecraft/worldgen/placed_feature/trees_birch.json
- reports/minecraft/worldgen/placed_feature/trees_flower_forest.json
- reports/minecraft/worldgen/placed_feature/trees_grove.json
- reports/minecraft/worldgen/placed_feature/trees_jungle.json
- reports/minecraft/worldgen/placed_feature/trees_mangrove.json
- reports/minecraft/worldgen/placed_feature/trees_meadow.json
- reports/minecraft/worldgen/placed_feature/trees_old_growth_pine_taiga.json
- reports/minecraft/worldgen/placed_feature/trees_old_growth_spruce_taiga.json
- reports/minecraft/worldgen/placed_feature/trees_plains.json
- reports/minecraft/worldgen/placed_feature/trees_savanna.json
- reports/minecraft/worldgen/placed_feature/trees_snowy.json
- reports/minecraft/worldgen/placed_feature/trees_sparse_jungle.json
- reports/minecraft/worldgen/placed_feature/trees_swamp.json
- reports/minecraft/worldgen/placed_feature/trees_taiga.json
- reports/minecraft/worldgen/placed_feature/trees_water.json
- reports/minecraft/worldgen/placed_feature/trees_windswept_forest.json
- reports/minecraft/worldgen/placed_feature/trees_windswept_hills.json
- reports/minecraft/worldgen/placed_feature/trees_windswept_savanna.json
- reports/minecraft/worldgen/placed_feature/twisting_vines.json
- reports/minecraft/worldgen/placed_feature/underwater_magma.json
- reports/minecraft/worldgen/placed_feature/vines.json
- reports/minecraft/worldgen/placed_feature/void_start_platform.json
- reports/minecraft/worldgen/placed_feature/warm_ocean_vegetation.json
- reports/minecraft/worldgen/placed_feature/warped_forest_vegetation.json
- reports/minecraft/worldgen/placed_feature/warped_fungi.json
- reports/minecraft/worldgen/placed_feature/weeping_vines.json
- reports/minecraft/worldgen/processor_list/ancient_city_generic_degradation.json
- reports/minecraft/worldgen/processor_list/ancient_city_start_degradation.json
- reports/minecraft/worldgen/processor_list/ancient_city_walls_degradation.json
- reports/minecraft/worldgen/processor_list/bastion_generic_degradation.json
- reports/minecraft/worldgen/processor_list/bottom_rampart.json
- reports/minecraft/worldgen/processor_list/bridge.json
- reports/minecraft/worldgen/processor_list/empty.json
- reports/minecraft/worldgen/processor_list/entrance_replacement.json
- reports/minecraft/worldgen/processor_list/farm_desert.json
- reports/minecraft/worldgen/processor_list/farm_plains.json
- reports/minecraft/worldgen/processor_list/farm_savanna.json
- reports/minecraft/worldgen/processor_list/farm_snowy.json
- reports/minecraft/worldgen/processor_list/farm_taiga.json
- reports/minecraft/worldgen/processor_list/fossil_coal.json
- reports/minecraft/worldgen/processor_list/fossil_diamonds.json
- reports/minecraft/worldgen/processor_list/fossil_rot.json
- reports/minecraft/worldgen/processor_list/high_rampart.json
- reports/minecraft/worldgen/processor_list/high_wall.json
- reports/minecraft/worldgen/processor_list/housing.json
- reports/minecraft/worldgen/processor_list/mossify_10_percent.json
- reports/minecraft/worldgen/processor_list/mossify_20_percent.json
- reports/minecraft/worldgen/processor_list/mossify_70_percent.json
- reports/minecraft/worldgen/processor_list/outpost_rot.json
- reports/minecraft/worldgen/processor_list/rampart_degradation.json
- reports/minecraft/worldgen/processor_list/roof.json
- reports/minecraft/worldgen/processor_list/side_wall_degradation.json
- reports/minecraft/worldgen/processor_list/stable_degradation.json
- reports/minecraft/worldgen/processor_list/street_plains.json
- reports/minecraft/worldgen/processor_list/street_savanna.json
- reports/minecraft/worldgen/processor_list/street_snowy_or_taiga.json
- reports/minecraft/worldgen/processor_list/treasure_rooms.json
- reports/minecraft/worldgen/processor_list/zombie_desert.json
- reports/minecraft/worldgen/processor_list/zombie_plains.json
- reports/minecraft/worldgen/processor_list/zombie_savanna.json
- reports/minecraft/worldgen/processor_list/zombie_snowy.json
- reports/minecraft/worldgen/processor_list/zombie_taiga.json
- reports/minecraft/worldgen/structure_set/ancient_cities.json
- reports/minecraft/worldgen/structure_set/buried_treasures.json
- reports/minecraft/worldgen/structure_set/desert_pyramids.json
- reports/minecraft/worldgen/structure_set/end_cities.json
- reports/minecraft/worldgen/structure_set/igloos.json
- reports/minecraft/worldgen/structure_set/jungle_temples.json
- reports/minecraft/worldgen/structure_set/mineshafts.json
- reports/minecraft/worldgen/structure_set/nether_complexes.json
- reports/minecraft/worldgen/structure_set/nether_fossils.json
- reports/minecraft/worldgen/structure_set/ocean_monuments.json
- reports/minecraft/worldgen/structure_set/ocean_ruins.json
- reports/minecraft/worldgen/structure_set/pillager_outposts.json
- reports/minecraft/worldgen/structure_set/ruined_portals.json
- reports/minecraft/worldgen/structure_set/shipwrecks.json
- reports/minecraft/worldgen/structure_set/strongholds.json
- reports/minecraft/worldgen/structure_set/swamp_huts.json
- reports/minecraft/worldgen/structure_set/villages.json
- reports/minecraft/worldgen/structure_set/woodland_mansions.json
- reports/minecraft/worldgen/structure/ancient_city.json
- reports/minecraft/worldgen/structure/bastion_remnant.json
- reports/minecraft/worldgen/structure/buried_treasure.json
- reports/minecraft/worldgen/structure/desert_pyramid.json
- reports/minecraft/worldgen/structure/end_city.json
- reports/minecraft/worldgen/structure/fortress.json
- reports/minecraft/worldgen/structure/igloo.json
- reports/minecraft/worldgen/structure/jungle_pyramid.json
- reports/minecraft/worldgen/structure/mansion.json
- reports/minecraft/worldgen/structure/mineshaft_mesa.json
- reports/minecraft/worldgen/structure/mineshaft.json
- reports/minecraft/worldgen/structure/monument.json
- reports/minecraft/worldgen/structure/nether_fossil.json
- reports/minecraft/worldgen/structure/ocean_ruin_cold.json
- reports/minecraft/worldgen/structure/ocean_ruin_warm.json
- reports/minecraft/worldgen/structure/pillager_outpost.json
- reports/minecraft/worldgen/structure/ruined_portal_desert.json
- reports/minecraft/worldgen/structure/ruined_portal_jungle.json
- reports/minecraft/worldgen/structure/ruined_portal_mountain.json
- reports/minecraft/worldgen/structure/ruined_portal_nether.json
- reports/minecraft/worldgen/structure/ruined_portal_ocean.json
- reports/minecraft/worldgen/structure/ruined_portal_swamp.json
- reports/minecraft/worldgen/structure/ruined_portal.json
- reports/minecraft/worldgen/structure/shipwreck_beached.json
- reports/minecraft/worldgen/structure/shipwreck.json
- reports/minecraft/worldgen/structure/stronghold.json
- reports/minecraft/worldgen/structure/swamp_hut.json
- reports/minecraft/worldgen/structure/village_desert.json
- reports/minecraft/worldgen/structure/village_plains.json
- reports/minecraft/worldgen/structure/village_savanna.json
- reports/minecraft/worldgen/structure/village_snowy.json
- reports/minecraft/worldgen/structure/village_taiga.json
- reports/minecraft/worldgen/template_pool/ancient_city/city_center.json
- reports/minecraft/worldgen/template_pool/ancient_city/city_center/walls.json
- reports/minecraft/worldgen/template_pool/ancient_city/city/entrance.json
- reports/minecraft/worldgen/template_pool/ancient_city/sculk.json
- reports/minecraft/worldgen/template_pool/ancient_city/structures.json
- reports/minecraft/worldgen/template_pool/ancient_city/walls.json
- reports/minecraft/worldgen/template_pool/ancient_city/walls/no_corners.json
- reports/minecraft/worldgen/template_pool/bastion/blocks/gold.json
- reports/minecraft/worldgen/template_pool/bastion/bridge/bridge_pieces.json
- reports/minecraft/worldgen/template_pool/bastion/bridge/connectors.json
- reports/minecraft/worldgen/template_pool/bastion/bridge/legs.json
- reports/minecraft/worldgen/template_pool/bastion/bridge/rampart_plates.json
- reports/minecraft/worldgen/template_pool/bastion/bridge/ramparts.json
- reports/minecraft/worldgen/template_pool/bastion/bridge/starting_pieces.json
- reports/minecraft/worldgen/template_pool/bastion/bridge/walls.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/connectors.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/inner.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/outer.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/mirrored_starting_pieces.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/posts.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/rampart_plates.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/ramparts.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/inner.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/outer.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/stairs.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/starting_pieces.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/wall_bases.json
- reports/minecraft/worldgen/template_pool/bastion/hoglin_stable/walls.json
- reports/minecraft/worldgen/template_pool/bastion/mobs/hoglin.json
- reports/minecraft/worldgen/template_pool/bastion/mobs/piglin_melee.json
- reports/minecraft/worldgen/template_pool/bastion/mobs/piglin.json
- reports/minecraft/worldgen/template_pool/bastion/starts.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/bases.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/bases/centers.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/brains.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/connectors.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/corners/bottom.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/corners/edges.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/corners/middle.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/corners/top.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/entrances.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/extensions/houses.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/extensions/large_pool.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/extensions/small_pool.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/ramparts.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/roofs.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/stairs.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/walls.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/walls/bottom.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/walls/mid.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/walls/outer.json
- reports/minecraft/worldgen/template_pool/bastion/treasure/walls/top.json
- reports/minecraft/worldgen/template_pool/bastion/units/center_pieces.json
- reports/minecraft/worldgen/template_pool/bastion/units/edge_wall_units.json
- reports/minecraft/worldgen/template_pool/bastion/units/edges.json
- reports/minecraft/worldgen/template_pool/bastion/units/fillers/stage_0.json
- reports/minecraft/worldgen/template_pool/bastion/units/large_ramparts.json
- reports/minecraft/worldgen/template_pool/bastion/units/pathways.json
- reports/minecraft/worldgen/template_pool/bastion/units/rampart_plates.json
- reports/minecraft/worldgen/template_pool/bastion/units/ramparts.json
- reports/minecraft/worldgen/template_pool/bastion/units/stages/rot/stage_1.json
- reports/minecraft/worldgen/template_pool/bastion/units/stages/stage_0.json
- reports/minecraft/worldgen/template_pool/bastion/units/stages/stage_1.json
- reports/minecraft/worldgen/template_pool/bastion/units/stages/stage_2.json
- reports/minecraft/worldgen/template_pool/bastion/units/stages/stage_3.json
- reports/minecraft/worldgen/template_pool/bastion/units/wall_units.json
- reports/minecraft/worldgen/template_pool/bastion/units/walls/wall_bases.json
- reports/minecraft/worldgen/template_pool/empty.json
- reports/minecraft/worldgen/template_pool/pillager_outpost/base_plates.json
- reports/minecraft/worldgen/template_pool/pillager_outpost/feature_plates.json
- reports/minecraft/worldgen/template_pool/pillager_outpost/features.json
- reports/minecraft/worldgen/template_pool/pillager_outpost/towers.json
- reports/minecraft/worldgen/template_pool/village/common/animals.json
- reports/minecraft/worldgen/template_pool/village/common/butcher_animals.json
- reports/minecraft/worldgen/template_pool/village/common/cats.json
- reports/minecraft/worldgen/template_pool/village/common/iron_golem.json
- reports/minecraft/worldgen/template_pool/village/common/sheep.json
- reports/minecraft/worldgen/template_pool/village/common/well_bottoms.json
- reports/minecraft/worldgen/template_pool/village/desert/decor.json
- reports/minecraft/worldgen/template_pool/village/desert/houses.json
- reports/minecraft/worldgen/template_pool/village/desert/streets.json
- reports/minecraft/worldgen/template_pool/village/desert/terminators.json
- reports/minecraft/worldgen/template_pool/village/desert/town_centers.json
- reports/minecraft/worldgen/template_pool/village/desert/villagers.json
- reports/minecraft/worldgen/template_pool/village/desert/zombie/decor.json
- reports/minecraft/worldgen/template_pool/village/desert/zombie/houses.json
- reports/minecraft/worldgen/template_pool/village/desert/zombie/streets.json
- reports/minecraft/worldgen/template_pool/village/desert/zombie/terminators.json
- reports/minecraft/worldgen/template_pool/village/desert/zombie/villagers.json
- reports/minecraft/worldgen/template_pool/village/plains/decor.json
- reports/minecraft/worldgen/template_pool/village/plains/houses.json
- reports/minecraft/worldgen/template_pool/village/plains/streets.json
- reports/minecraft/worldgen/template_pool/village/plains/terminators.json
- reports/minecraft/worldgen/template_pool/village/plains/town_centers.json
- reports/minecraft/worldgen/template_pool/village/plains/trees.json
- reports/minecraft/worldgen/template_pool/village/plains/villagers.json
- reports/minecraft/worldgen/template_pool/village/plains/zombie/decor.json
- reports/minecraft/worldgen/template_pool/village/plains/zombie/houses.json
- reports/minecraft/worldgen/template_pool/village/plains/zombie/streets.json
- reports/minecraft/worldgen/template_pool/village/plains/zombie/villagers.json
- reports/minecraft/worldgen/template_pool/village/savanna/decor.json
- reports/minecraft/worldgen/template_pool/village/savanna/houses.json
- reports/minecraft/worldgen/template_pool/village/savanna/streets.json
- reports/minecraft/worldgen/template_pool/village/savanna/terminators.json
- reports/minecraft/worldgen/template_pool/village/savanna/town_centers.json
- reports/minecraft/worldgen/template_pool/village/savanna/trees.json
- reports/minecraft/worldgen/template_pool/village/savanna/villagers.json
- reports/minecraft/worldgen/template_pool/village/savanna/zombie/decor.json
- reports/minecraft/worldgen/template_pool/village/savanna/zombie/houses.json
- reports/minecraft/worldgen/template_pool/village/savanna/zombie/streets.json
- reports/minecraft/worldgen/template_pool/village/savanna/zombie/terminators.json
- reports/minecraft/worldgen/template_pool/village/savanna/zombie/villagers.json
- reports/minecraft/worldgen/template_pool/village/snowy/decor.json
- reports/minecraft/worldgen/template_pool/village/snowy/houses.json
- reports/minecraft/worldgen/template_pool/village/snowy/streets.json
- reports/minecraft/worldgen/template_pool/village/snowy/terminators.json
- reports/minecraft/worldgen/template_pool/village/snowy/town_centers.json
- reports/minecraft/worldgen/template_pool/village/snowy/trees.json
- reports/minecraft/worldgen/template_pool/village/snowy/villagers.json
- reports/minecraft/worldgen/template_pool/village/snowy/zombie/decor.json
- reports/minecraft/worldgen/template_pool/village/snowy/zombie/houses.json
- reports/minecraft/worldgen/template_pool/village/snowy/zombie/streets.json
- reports/minecraft/worldgen/template_pool/village/snowy/zombie/villagers.json
- reports/minecraft/worldgen/template_pool/village/taiga/decor.json
- reports/minecraft/worldgen/template_pool/village/taiga/houses.json
- reports/minecraft/worldgen/template_pool/village/taiga/streets.json
- reports/minecraft/worldgen/template_pool/village/taiga/terminators.json
- reports/minecraft/worldgen/template_pool/village/taiga/town_centers.json
- reports/minecraft/worldgen/template_pool/village/taiga/villagers.json
- reports/minecraft/worldgen/template_pool/village/taiga/zombie/decor.json
- reports/minecraft/worldgen/template_pool/village/taiga/zombie/houses.json
- reports/minecraft/worldgen/template_pool/village/taiga/zombie/streets.json
- reports/minecraft/worldgen/template_pool/village/taiga/zombie/villagers.json
- reports/minecraft/worldgen/world_preset/amplified.json
- reports/minecraft/worldgen/world_preset/debug_all_block_states.json
- reports/minecraft/worldgen/world_preset/flat.json
- reports/minecraft/worldgen/world_preset/large_biomes.json
- reports/minecraft/worldgen/world_preset/normal.json
- reports/minecraft/worldgen/world_preset/single_biome_surface.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/chat_type/chat.json
+ minecraft/chat_type/emote_command.json
+ minecraft/chat_type/msg_command_incoming.json
+ minecraft/chat_type/msg_command_outgoing.json
+ minecraft/chat_type/say_command.json
+ minecraft/chat_type/team_msg_command_incoming.json
+ minecraft/chat_type/team_msg_command_outgoing.json
+ minecraft/datapacks/bundle/data/minecraft/advancements/recipes/tools/bundle.json
+ minecraft/datapacks/bundle/data/minecraft/recipes/bundle.json
+ minecraft/datapacks/bundle/pack.mcmeta
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/bamboo_mosaic_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/bamboo_mosaic_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/bamboo_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/bamboo_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/chiseled_bookshelf.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/acacia_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/bamboo_fence.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/bamboo_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/bamboo_mosaic.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/bamboo_planks.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/bamboo_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/crimson_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/dark_oak_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/jungle_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/mangrove_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/oak_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/spruce_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/warped_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/bamboo_button.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/bamboo_door.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/bamboo_fence_gate.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/bamboo_pressure_plate.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/bamboo_trapdoor.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/transportation/bamboo_chest_raft.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/transportation/bamboo_raft.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/acacia_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_button.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_door.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_fence_gate.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_fence.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_mosaic_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_mosaic_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_mosaic.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_planks.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_pressure_plate.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/bamboo_trapdoor.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/birch_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/chiseled_bookshelf.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/crimson_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/dark_oak_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/jungle_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/mangrove_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/oak_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/spruce_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/warped_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/acacia_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_button.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_chest_raft.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_door.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_fence_gate.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_fence.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_mosaic_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_mosaic_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_mosaic.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_planks.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_pressure_plate.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_raft.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/bamboo_trapdoor.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/chiseled_bookshelf.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/crimson_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/dark_oak_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/jungle_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/mangrove_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/oak_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/spruce_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/warped_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/all_hanging_signs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/ceiling_hanging_signs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/fence_gates.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/mineable/axe.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/planks.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/standing_signs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wall_hanging_signs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wall_signs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wooden_buttons.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wooden_doors.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wooden_fences.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wooden_pressure_plates.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wooden_slabs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wooden_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/wooden_trapdoors.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/boats.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/bookshelf_books.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/buttons.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/chest_boats.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/doors.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/fences.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/hanging_signs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/planks.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/signs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/slabs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/trapdoors.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/wooden_buttons.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/wooden_doors.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/wooden_fences.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/wooden_pressure_plates.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/wooden_slabs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/wooden_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/wooden_trapdoors.json
+ minecraft/datapacks/update_1_20/pack.mcmeta
+ minecraft/dimension_type/overworld_caves.json
+ minecraft/dimension_type/overworld.json
+ minecraft/dimension_type/the_end.json
+ minecraft/dimension_type/the_nether.json
+ minecraft/loot_tables/blocks/acacia_hanging_sign.json
+ minecraft/loot_tables/blocks/bamboo_button.json
+ minecraft/loot_tables/blocks/bamboo_door.json
+ minecraft/loot_tables/blocks/bamboo_fence_gate.json
+ minecraft/loot_tables/blocks/bamboo_fence.json
+ minecraft/loot_tables/blocks/bamboo_hanging_sign.json
+ minecraft/loot_tables/blocks/bamboo_mosaic_slab.json
+ minecraft/loot_tables/blocks/bamboo_mosaic_stairs.json
+ minecraft/loot_tables/blocks/bamboo_mosaic.json
+ minecraft/loot_tables/blocks/bamboo_planks.json
+ minecraft/loot_tables/blocks/bamboo_pressure_plate.json
+ minecraft/loot_tables/blocks/bamboo_sign.json
+ minecraft/loot_tables/blocks/bamboo_slab.json
+ minecraft/loot_tables/blocks/bamboo_stairs.json
+ minecraft/loot_tables/blocks/bamboo_trapdoor.json
+ minecraft/loot_tables/blocks/birch_hanging_sign.json
+ minecraft/loot_tables/blocks/chiseled_bookshelf.json
+ minecraft/loot_tables/blocks/crimson_hanging_sign.json
+ minecraft/loot_tables/blocks/dark_oak_hanging_sign.json
+ minecraft/loot_tables/blocks/jungle_hanging_sign.json
+ minecraft/loot_tables/blocks/mangrove_hanging_sign.json
+ minecraft/loot_tables/blocks/oak_hanging_sign.json
+ minecraft/loot_tables/blocks/spruce_hanging_sign.json
+ minecraft/loot_tables/blocks/warped_hanging_sign.json
+ minecraft/loot_tables/entities/camel.json
+ minecraft/structures/village/desert/camel_spawn.nbt
+ minecraft/tags/blocks/invalid_spawn_inside.json
+ minecraft/tags/blocks/stripped_logs.json
+ minecraft/tags/items/stripped_logs.json
+ minecraft/worldgen/biome/badlands.json
+ minecraft/worldgen/biome/bamboo_jungle.json
+ minecraft/worldgen/biome/basalt_deltas.json
+ minecraft/worldgen/biome/beach.json
+ minecraft/worldgen/biome/birch_forest.json
+ minecraft/worldgen/biome/cold_ocean.json
+ minecraft/worldgen/biome/crimson_forest.json
+ minecraft/worldgen/biome/dark_forest.json
+ minecraft/worldgen/biome/deep_cold_ocean.json
+ minecraft/worldgen/biome/deep_dark.json
+ minecraft/worldgen/biome/deep_frozen_ocean.json
+ minecraft/worldgen/biome/deep_lukewarm_ocean.json
+ minecraft/worldgen/biome/deep_ocean.json
+ minecraft/worldgen/biome/desert.json
+ minecraft/worldgen/biome/dripstone_caves.json
+ minecraft/worldgen/biome/end_barrens.json
+ minecraft/worldgen/biome/end_highlands.json
+ minecraft/worldgen/biome/end_midlands.json
+ minecraft/worldgen/biome/eroded_badlands.json
+ minecraft/worldgen/biome/flower_forest.json
+ minecraft/worldgen/biome/forest.json
+ minecraft/worldgen/biome/frozen_ocean.json
+ minecraft/worldgen/biome/frozen_peaks.json
+ minecraft/worldgen/biome/frozen_river.json
+ minecraft/worldgen/biome/grove.json
+ minecraft/worldgen/biome/ice_spikes.json
+ minecraft/worldgen/biome/jagged_peaks.json
+ minecraft/worldgen/biome/jungle.json
+ minecraft/worldgen/biome/lukewarm_ocean.json
+ minecraft/worldgen/biome/lush_caves.json
+ minecraft/worldgen/biome/mangrove_swamp.json
+ minecraft/worldgen/biome/meadow.json
+ minecraft/worldgen/biome/mushroom_fields.json
+ minecraft/worldgen/biome/nether_wastes.json
+ minecraft/worldgen/biome/ocean.json
+ minecraft/worldgen/biome/old_growth_birch_forest.json
+ minecraft/worldgen/biome/old_growth_pine_taiga.json
+ minecraft/worldgen/biome/old_growth_spruce_taiga.json
+ minecraft/worldgen/biome/plains.json
+ minecraft/worldgen/biome/river.json
+ minecraft/worldgen/biome/savanna_plateau.json
+ minecraft/worldgen/biome/savanna.json
+ minecraft/worldgen/biome/small_end_islands.json
+ minecraft/worldgen/biome/snowy_beach.json
+ minecraft/worldgen/biome/snowy_plains.json
+ minecraft/worldgen/biome/snowy_slopes.json
+ minecraft/worldgen/biome/snowy_taiga.json
+ minecraft/worldgen/biome/soul_sand_valley.json
+ minecraft/worldgen/biome/sparse_jungle.json
+ minecraft/worldgen/biome/stony_peaks.json
+ minecraft/worldgen/biome/stony_shore.json
+ minecraft/worldgen/biome/sunflower_plains.json
+ minecraft/worldgen/biome/swamp.json
+ minecraft/worldgen/biome/taiga.json
+ minecraft/worldgen/biome/the_end.json
+ minecraft/worldgen/biome/the_void.json
+ minecraft/worldgen/biome/warm_ocean.json
+ minecraft/worldgen/biome/warped_forest.json
+ minecraft/worldgen/biome/windswept_forest.json
+ minecraft/worldgen/biome/windswept_gravelly_hills.json
+ minecraft/worldgen/biome/windswept_hills.json
+ minecraft/worldgen/biome/windswept_savanna.json
+ minecraft/worldgen/biome/wooded_badlands.json
+ minecraft/worldgen/configured_carver/canyon.json
+ minecraft/worldgen/configured_carver/cave_extra_underground.json
+ minecraft/worldgen/configured_carver/cave.json
+ minecraft/worldgen/configured_carver/nether_cave.json
+ minecraft/worldgen/configured_feature/acacia.json
+ minecraft/worldgen/configured_feature/amethyst_geode.json
+ minecraft/worldgen/configured_feature/azalea_tree.json
+ minecraft/worldgen/configured_feature/bamboo_no_podzol.json
+ minecraft/worldgen/configured_feature/bamboo_some_podzol.json
+ minecraft/worldgen/configured_feature/bamboo_vegetation.json
+ minecraft/worldgen/configured_feature/basalt_blobs.json
+ minecraft/worldgen/configured_feature/basalt_pillar.json
+ minecraft/worldgen/configured_feature/birch_bees_0002.json
+ minecraft/worldgen/configured_feature/birch_bees_002.json
+ minecraft/worldgen/configured_feature/birch_bees_005.json
+ minecraft/worldgen/configured_feature/birch_tall.json
+ minecraft/worldgen/configured_feature/birch.json
+ minecraft/worldgen/configured_feature/blackstone_blobs.json
+ minecraft/worldgen/configured_feature/blue_ice.json
+ minecraft/worldgen/configured_feature/bonus_chest.json
+ minecraft/worldgen/configured_feature/cave_vine_in_moss.json
+ minecraft/worldgen/configured_feature/cave_vine.json
+ minecraft/worldgen/configured_feature/chorus_plant.json
+ minecraft/worldgen/configured_feature/clay_pool_with_dripleaves.json
+ minecraft/worldgen/configured_feature/clay_with_dripleaves.json
+ minecraft/worldgen/configured_feature/crimson_forest_vegetation_bonemeal.json
+ minecraft/worldgen/configured_feature/crimson_forest_vegetation.json
+ minecraft/worldgen/configured_feature/crimson_fungus_planted.json
+ minecraft/worldgen/configured_feature/crimson_fungus.json
+ minecraft/worldgen/configured_feature/dark_forest_vegetation.json
+ minecraft/worldgen/configured_feature/dark_oak.json
+ minecraft/worldgen/configured_feature/delta.json
+ minecraft/worldgen/configured_feature/desert_well.json
+ minecraft/worldgen/configured_feature/disk_clay.json
+ minecraft/worldgen/configured_feature/disk_grass.json
+ minecraft/worldgen/configured_feature/disk_gravel.json
+ minecraft/worldgen/configured_feature/disk_sand.json
+ minecraft/worldgen/configured_feature/dripleaf.json
+ minecraft/worldgen/configured_feature/dripstone_cluster.json
+ minecraft/worldgen/configured_feature/end_gateway_delayed.json
+ minecraft/worldgen/configured_feature/end_gateway_return.json
+ minecraft/worldgen/configured_feature/end_island.json
+ minecraft/worldgen/configured_feature/end_spike.json
+ minecraft/worldgen/configured_feature/fancy_oak_bees_0002.json
+ minecraft/worldgen/configured_feature/fancy_oak_bees_002.json
+ minecraft/worldgen/configured_feature/fancy_oak_bees_005.json
+ minecraft/worldgen/configured_feature/fancy_oak_bees.json
+ minecraft/worldgen/configured_feature/fancy_oak.json
+ minecraft/worldgen/configured_feature/flower_default.json
+ minecraft/worldgen/configured_feature/flower_flower_forest.json
+ minecraft/worldgen/configured_feature/flower_meadow.json
+ minecraft/worldgen/configured_feature/flower_plain.json
+ minecraft/worldgen/configured_feature/flower_swamp.json
+ minecraft/worldgen/configured_feature/forest_flowers.json
+ minecraft/worldgen/configured_feature/forest_rock.json
+ minecraft/worldgen/configured_feature/fossil_coal.json
+ minecraft/worldgen/configured_feature/fossil_diamonds.json
+ minecraft/worldgen/configured_feature/freeze_top_layer.json
+ minecraft/worldgen/configured_feature/glow_lichen.json
+ minecraft/worldgen/configured_feature/glowstone_extra.json
+ minecraft/worldgen/configured_feature/huge_brown_mushroom.json
+ minecraft/worldgen/configured_feature/huge_red_mushroom.json
+ minecraft/worldgen/configured_feature/ice_patch.json
+ minecraft/worldgen/configured_feature/ice_spike.json
+ minecraft/worldgen/configured_feature/iceberg_blue.json
+ minecraft/worldgen/configured_feature/iceberg_packed.json
+ minecraft/worldgen/configured_feature/jungle_bush.json
+ minecraft/worldgen/configured_feature/jungle_tree_no_vine.json
+ minecraft/worldgen/configured_feature/jungle_tree.json
+ minecraft/worldgen/configured_feature/kelp.json
+ minecraft/worldgen/configured_feature/lake_lava.json
+ minecraft/worldgen/configured_feature/large_basalt_columns.json
+ minecraft/worldgen/configured_feature/large_dripstone.json
+ minecraft/worldgen/configured_feature/lush_caves_clay.json
+ minecraft/worldgen/configured_feature/mangrove_vegetation.json
+ minecraft/worldgen/configured_feature/mangrove.json
+ minecraft/worldgen/configured_feature/meadow_trees.json
+ minecraft/worldgen/configured_feature/mega_jungle_tree.json
+ minecraft/worldgen/configured_feature/mega_pine.json
+ minecraft/worldgen/configured_feature/mega_spruce.json
+ minecraft/worldgen/configured_feature/monster_room.json
+ minecraft/worldgen/configured_feature/moss_patch_bonemeal.json
+ minecraft/worldgen/configured_feature/moss_patch_ceiling.json
+ minecraft/worldgen/configured_feature/moss_patch.json
+ minecraft/worldgen/configured_feature/moss_vegetation.json
+ minecraft/worldgen/configured_feature/mushroom_island_vegetation.json
+ minecraft/worldgen/configured_feature/nether_sprouts_bonemeal.json
+ minecraft/worldgen/configured_feature/nether_sprouts.json
+ minecraft/worldgen/configured_feature/oak_bees_0002.json
+ minecraft/worldgen/configured_feature/oak_bees_002.json
+ minecraft/worldgen/configured_feature/oak_bees_005.json
+ minecraft/worldgen/configured_feature/oak.json
+ minecraft/worldgen/configured_feature/ore_ancient_debris_large.json
+ minecraft/worldgen/configured_feature/ore_ancient_debris_small.json
+ minecraft/worldgen/configured_feature/ore_andesite.json
+ minecraft/worldgen/configured_feature/ore_blackstone.json
+ minecraft/worldgen/configured_feature/ore_clay.json
+ minecraft/worldgen/configured_feature/ore_coal_buried.json
+ minecraft/worldgen/configured_feature/ore_coal.json
+ minecraft/worldgen/configured_feature/ore_copper_large.json
+ minecraft/worldgen/configured_feature/ore_copper_small.json
+ minecraft/worldgen/configured_feature/ore_diamond_buried.json
+ minecraft/worldgen/configured_feature/ore_diamond_large.json
+ minecraft/worldgen/configured_feature/ore_diamond_small.json
+ minecraft/worldgen/configured_feature/ore_diorite.json
+ minecraft/worldgen/configured_feature/ore_dirt.json
+ minecraft/worldgen/configured_feature/ore_emerald.json
+ minecraft/worldgen/configured_feature/ore_gold_buried.json
+ minecraft/worldgen/configured_feature/ore_gold.json
+ minecraft/worldgen/configured_feature/ore_granite.json
+ minecraft/worldgen/configured_feature/ore_gravel_nether.json
+ minecraft/worldgen/configured_feature/ore_gravel.json
+ minecraft/worldgen/configured_feature/ore_infested.json
+ minecraft/worldgen/configured_feature/ore_iron_small.json
+ minecraft/worldgen/configured_feature/ore_iron.json
+ minecraft/worldgen/configured_feature/ore_lapis_buried.json
+ minecraft/worldgen/configured_feature/ore_lapis.json
+ minecraft/worldgen/configured_feature/ore_magma.json
+ minecraft/worldgen/configured_feature/ore_nether_gold.json
+ minecraft/worldgen/configured_feature/ore_quartz.json
+ minecraft/worldgen/configured_feature/ore_redstone.json
+ minecraft/worldgen/configured_feature/ore_soul_sand.json
+ minecraft/worldgen/configured_feature/ore_tuff.json
+ minecraft/worldgen/configured_feature/patch_berry_bush.json
+ minecraft/worldgen/configured_feature/patch_brown_mushroom.json
+ minecraft/worldgen/configured_feature/patch_cactus.json
+ minecraft/worldgen/configured_feature/patch_crimson_roots.json
+ minecraft/worldgen/configured_feature/patch_dead_bush.json
+ minecraft/worldgen/configured_feature/patch_fire.json
+ minecraft/worldgen/configured_feature/patch_grass_jungle.json
+ minecraft/worldgen/configured_feature/patch_grass.json
+ minecraft/worldgen/configured_feature/patch_large_fern.json
+ minecraft/worldgen/configured_feature/patch_melon.json
+ minecraft/worldgen/configured_feature/patch_pumpkin.json
+ minecraft/worldgen/configured_feature/patch_red_mushroom.json
+ minecraft/worldgen/configured_feature/patch_soul_fire.json
+ minecraft/worldgen/configured_feature/patch_sugar_cane.json
+ minecraft/worldgen/configured_feature/patch_sunflower.json
+ minecraft/worldgen/configured_feature/patch_taiga_grass.json
+ minecraft/worldgen/configured_feature/patch_tall_grass.json
+ minecraft/worldgen/configured_feature/patch_waterlily.json
+ minecraft/worldgen/configured_feature/pile_hay.json
+ minecraft/worldgen/configured_feature/pile_ice.json
+ minecraft/worldgen/configured_feature/pile_melon.json
+ minecraft/worldgen/configured_feature/pile_pumpkin.json
+ minecraft/worldgen/configured_feature/pile_snow.json
+ minecraft/worldgen/configured_feature/pine.json
+ minecraft/worldgen/configured_feature/pointed_dripstone.json
+ minecraft/worldgen/configured_feature/rooted_azalea_tree.json
+ minecraft/worldgen/configured_feature/sculk_patch_ancient_city.json
+ minecraft/worldgen/configured_feature/sculk_patch_deep_dark.json
+ minecraft/worldgen/configured_feature/sculk_vein.json
+ minecraft/worldgen/configured_feature/sea_pickle.json
+ minecraft/worldgen/configured_feature/seagrass_mid.json
+ minecraft/worldgen/configured_feature/seagrass_short.json
+ minecraft/worldgen/configured_feature/seagrass_simple.json
+ minecraft/worldgen/configured_feature/seagrass_slightly_less_short.json
+ minecraft/worldgen/configured_feature/seagrass_tall.json
+ minecraft/worldgen/configured_feature/single_piece_of_grass.json
+ minecraft/worldgen/configured_feature/small_basalt_columns.json
+ minecraft/worldgen/configured_feature/spore_blossom.json
+ minecraft/worldgen/configured_feature/spring_lava_frozen.json
+ minecraft/worldgen/configured_feature/spring_lava_nether.json
+ minecraft/worldgen/configured_feature/spring_lava_overworld.json
+ minecraft/worldgen/configured_feature/spring_nether_closed.json
+ minecraft/worldgen/configured_feature/spring_nether_open.json
+ minecraft/worldgen/configured_feature/spring_water.json
+ minecraft/worldgen/configured_feature/spruce.json
+ minecraft/worldgen/configured_feature/super_birch_bees_0002.json
+ minecraft/worldgen/configured_feature/super_birch_bees.json
+ minecraft/worldgen/configured_feature/swamp_oak.json
+ minecraft/worldgen/configured_feature/tall_mangrove.json
+ minecraft/worldgen/configured_feature/trees_birch_and_oak.json
+ minecraft/worldgen/configured_feature/trees_flower_forest.json
+ minecraft/worldgen/configured_feature/trees_grove.json
+ minecraft/worldgen/configured_feature/trees_jungle.json
+ minecraft/worldgen/configured_feature/trees_old_growth_pine_taiga.json
+ minecraft/worldgen/configured_feature/trees_old_growth_spruce_taiga.json
+ minecraft/worldgen/configured_feature/trees_plains.json
+ minecraft/worldgen/configured_feature/trees_savanna.json
+ minecraft/worldgen/configured_feature/trees_sparse_jungle.json
+ minecraft/worldgen/configured_feature/trees_taiga.json
+ minecraft/worldgen/configured_feature/trees_water.json
+ minecraft/worldgen/configured_feature/trees_windswept_hills.json
+ minecraft/worldgen/configured_feature/twisting_vines_bonemeal.json
+ minecraft/worldgen/configured_feature/twisting_vines.json
+ minecraft/worldgen/configured_feature/underwater_magma.json
+ minecraft/worldgen/configured_feature/vines.json
+ minecraft/worldgen/configured_feature/void_start_platform.json
+ minecraft/worldgen/configured_feature/warm_ocean_vegetation.json
+ minecraft/worldgen/configured_feature/warped_forest_vegetation_bonemeal.json
+ minecraft/worldgen/configured_feature/warped_forest_vegetation.json
+ minecraft/worldgen/configured_feature/warped_fungus_planted.json
+ minecraft/worldgen/configured_feature/warped_fungus.json
+ minecraft/worldgen/configured_feature/weeping_vines.json
+ minecraft/worldgen/density_function/end/base_3d_noise.json
+ minecraft/worldgen/density_function/end/sloped_cheese.json
+ minecraft/worldgen/density_function/nether/base_3d_noise.json
+ minecraft/worldgen/density_function/overworld_amplified/depth.json
+ minecraft/worldgen/density_function/overworld_amplified/factor.json
+ minecraft/worldgen/density_function/overworld_amplified/jaggedness.json
+ minecraft/worldgen/density_function/overworld_amplified/offset.json
+ minecraft/worldgen/density_function/overworld_amplified/sloped_cheese.json
+ minecraft/worldgen/density_function/overworld_large_biomes/continents.json
+ minecraft/worldgen/density_function/overworld_large_biomes/depth.json
+ minecraft/worldgen/density_function/overworld_large_biomes/erosion.json
+ minecraft/worldgen/density_function/overworld_large_biomes/factor.json
+ minecraft/worldgen/density_function/overworld_large_biomes/jaggedness.json
+ minecraft/worldgen/density_function/overworld_large_biomes/offset.json
+ minecraft/worldgen/density_function/overworld_large_biomes/sloped_cheese.json
+ minecraft/worldgen/density_function/overworld/base_3d_noise.json
+ minecraft/worldgen/density_function/overworld/caves/entrances.json
+ minecraft/worldgen/density_function/overworld/caves/noodle.json
+ minecraft/worldgen/density_function/overworld/caves/pillars.json
+ minecraft/worldgen/density_function/overworld/caves/spaghetti_2d_thickness_modulator.json
+ minecraft/worldgen/density_function/overworld/caves/spaghetti_2d.json
+ minecraft/worldgen/density_function/overworld/caves/spaghetti_roughness_function.json
+ minecraft/worldgen/density_function/overworld/continents.json
+ minecraft/worldgen/density_function/overworld/depth.json
+ minecraft/worldgen/density_function/overworld/erosion.json
+ minecraft/worldgen/density_function/overworld/factor.json
+ minecraft/worldgen/density_function/overworld/jaggedness.json
+ minecraft/worldgen/density_function/overworld/offset.json
+ minecraft/worldgen/density_function/overworld/ridges_folded.json
+ minecraft/worldgen/density_function/overworld/ridges.json
+ minecraft/worldgen/density_function/overworld/sloped_cheese.json
+ minecraft/worldgen/density_function/shift_x.json
+ minecraft/worldgen/density_function/shift_z.json
+ minecraft/worldgen/density_function/y.json
+ minecraft/worldgen/density_function/zero.json
+ minecraft/worldgen/flat_level_generator_preset/bottomless_pit.json
+ minecraft/worldgen/flat_level_generator_preset/classic_flat.json
+ minecraft/worldgen/flat_level_generator_preset/desert.json
+ minecraft/worldgen/flat_level_generator_preset/overworld.json
+ minecraft/worldgen/flat_level_generator_preset/redstone_ready.json
+ minecraft/worldgen/flat_level_generator_preset/snowy_kingdom.json
+ minecraft/worldgen/flat_level_generator_preset/the_void.json
+ minecraft/worldgen/flat_level_generator_preset/tunnelers_dream.json
+ minecraft/worldgen/flat_level_generator_preset/water_world.json
+ minecraft/worldgen/noise_settings/amplified.json
+ minecraft/worldgen/noise_settings/caves.json
+ minecraft/worldgen/noise_settings/end.json
+ minecraft/worldgen/noise_settings/floating_islands.json
+ minecraft/worldgen/noise_settings/large_biomes.json
+ minecraft/worldgen/noise_settings/nether.json
+ minecraft/worldgen/noise_settings/overworld.json
+ minecraft/worldgen/noise/aquifer_barrier.json
+ minecraft/worldgen/noise/aquifer_fluid_level_floodedness.json
+ minecraft/worldgen/noise/aquifer_fluid_level_spread.json
+ minecraft/worldgen/noise/aquifer_lava.json
+ minecraft/worldgen/noise/badlands_pillar_roof.json
+ minecraft/worldgen/noise/badlands_pillar.json
+ minecraft/worldgen/noise/badlands_surface.json
+ minecraft/worldgen/noise/calcite.json
+ minecraft/worldgen/noise/cave_cheese.json
+ minecraft/worldgen/noise/cave_entrance.json
+ minecraft/worldgen/noise/cave_layer.json
+ minecraft/worldgen/noise/clay_bands_offset.json
+ minecraft/worldgen/noise/continentalness_large.json
+ minecraft/worldgen/noise/continentalness.json
+ minecraft/worldgen/noise/erosion_large.json
+ minecraft/worldgen/noise/erosion.json
+ minecraft/worldgen/noise/gravel_layer.json
+ minecraft/worldgen/noise/gravel.json
+ minecraft/worldgen/noise/ice.json
+ minecraft/worldgen/noise/iceberg_pillar_roof.json
+ minecraft/worldgen/noise/iceberg_pillar.json
+ minecraft/worldgen/noise/iceberg_surface.json
+ minecraft/worldgen/noise/jagged.json
+ minecraft/worldgen/noise/nether_state_selector.json
+ minecraft/worldgen/noise/nether_wart.json
+ minecraft/worldgen/noise/netherrack.json
+ minecraft/worldgen/noise/noodle_ridge_a.json
+ minecraft/worldgen/noise/noodle_ridge_b.json
+ minecraft/worldgen/noise/noodle_thickness.json
+ minecraft/worldgen/noise/noodle.json
+ minecraft/worldgen/noise/offset.json
+ minecraft/worldgen/noise/ore_gap.json
+ minecraft/worldgen/noise/ore_vein_a.json
+ minecraft/worldgen/noise/ore_vein_b.json
+ minecraft/worldgen/noise/ore_veininess.json
+ minecraft/worldgen/noise/packed_ice.json
+ minecraft/worldgen/noise/patch.json
+ minecraft/worldgen/noise/pillar_rareness.json
+ minecraft/worldgen/noise/pillar_thickness.json
+ minecraft/worldgen/noise/pillar.json
+ minecraft/worldgen/noise/powder_snow.json
+ minecraft/worldgen/noise/ridge.json
+ minecraft/worldgen/noise/soul_sand_layer.json
+ minecraft/worldgen/noise/spaghetti_2d_elevation.json
+ minecraft/worldgen/noise/spaghetti_2d_modulator.json
+ minecraft/worldgen/noise/spaghetti_2d_thickness.json
+ minecraft/worldgen/noise/spaghetti_2d.json
+ minecraft/worldgen/noise/spaghetti_3d_1.json
+ minecraft/worldgen/noise/spaghetti_3d_2.json
+ minecraft/worldgen/noise/spaghetti_3d_rarity.json
+ minecraft/worldgen/noise/spaghetti_3d_thickness.json
+ minecraft/worldgen/noise/spaghetti_roughness_modulator.json
+ minecraft/worldgen/noise/spaghetti_roughness.json
+ minecraft/worldgen/noise/surface_secondary.json
+ minecraft/worldgen/noise/surface_swamp.json
+ minecraft/worldgen/noise/surface.json
+ minecraft/worldgen/noise/temperature_large.json
+ minecraft/worldgen/noise/temperature.json
+ minecraft/worldgen/noise/vegetation_large.json
+ minecraft/worldgen/noise/vegetation.json
+ minecraft/worldgen/placed_feature/acacia_checked.json
+ minecraft/worldgen/placed_feature/acacia.json
+ minecraft/worldgen/placed_feature/amethyst_geode.json
+ minecraft/worldgen/placed_feature/bamboo_light.json
+ minecraft/worldgen/placed_feature/bamboo_vegetation.json
+ minecraft/worldgen/placed_feature/bamboo.json
+ minecraft/worldgen/placed_feature/basalt_blobs.json
+ minecraft/worldgen/placed_feature/basalt_pillar.json
+ minecraft/worldgen/placed_feature/birch_bees_0002.json
+ minecraft/worldgen/placed_feature/birch_bees_002.json
+ minecraft/worldgen/placed_feature/birch_checked.json
+ minecraft/worldgen/placed_feature/birch_tall.json
+ minecraft/worldgen/placed_feature/blackstone_blobs.json
+ minecraft/worldgen/placed_feature/blue_ice.json
+ minecraft/worldgen/placed_feature/brown_mushroom_nether.json
+ minecraft/worldgen/placed_feature/brown_mushroom_normal.json
+ minecraft/worldgen/placed_feature/brown_mushroom_old_growth.json
+ minecraft/worldgen/placed_feature/brown_mushroom_swamp.json
+ minecraft/worldgen/placed_feature/brown_mushroom_taiga.json
+ minecraft/worldgen/placed_feature/cave_vines.json
+ minecraft/worldgen/placed_feature/chorus_plant.json
+ minecraft/worldgen/placed_feature/classic_vines_cave_feature.json
+ minecraft/worldgen/placed_feature/crimson_forest_vegetation.json
+ minecraft/worldgen/placed_feature/crimson_fungi.json
+ minecraft/worldgen/placed_feature/dark_forest_vegetation.json
+ minecraft/worldgen/placed_feature/dark_oak_checked.json
+ minecraft/worldgen/placed_feature/delta.json
+ minecraft/worldgen/placed_feature/desert_well.json
+ minecraft/worldgen/placed_feature/disk_clay.json
+ minecraft/worldgen/placed_feature/disk_grass.json
+ minecraft/worldgen/placed_feature/disk_gravel.json
+ minecraft/worldgen/placed_feature/disk_sand.json
+ minecraft/worldgen/placed_feature/dripstone_cluster.json
+ minecraft/worldgen/placed_feature/end_gateway_return.json
+ minecraft/worldgen/placed_feature/end_island_decorated.json
+ minecraft/worldgen/placed_feature/end_spike.json
+ minecraft/worldgen/placed_feature/fancy_oak_bees_0002.json
+ minecraft/worldgen/placed_feature/fancy_oak_bees_002.json
+ minecraft/worldgen/placed_feature/fancy_oak_bees.json
+ minecraft/worldgen/placed_feature/fancy_oak_checked.json
+ minecraft/worldgen/placed_feature/flower_default.json
+ minecraft/worldgen/placed_feature/flower_flower_forest.json
+ minecraft/worldgen/placed_feature/flower_forest_flowers.json
+ minecraft/worldgen/placed_feature/flower_meadow.json
+ minecraft/worldgen/placed_feature/flower_plain.json
+ minecraft/worldgen/placed_feature/flower_plains.json
+ minecraft/worldgen/placed_feature/flower_swamp.json
+ minecraft/worldgen/placed_feature/flower_warm.json
+ minecraft/worldgen/placed_feature/forest_flowers.json
+ minecraft/worldgen/placed_feature/forest_rock.json
+ minecraft/worldgen/placed_feature/fossil_lower.json
+ minecraft/worldgen/placed_feature/fossil_upper.json
+ minecraft/worldgen/placed_feature/freeze_top_layer.json
+ minecraft/worldgen/placed_feature/glow_lichen.json
+ minecraft/worldgen/placed_feature/glowstone_extra.json
+ minecraft/worldgen/placed_feature/glowstone.json
+ minecraft/worldgen/placed_feature/grass_bonemeal.json
+ minecraft/worldgen/placed_feature/ice_patch.json
+ minecraft/worldgen/placed_feature/ice_spike.json
+ minecraft/worldgen/placed_feature/iceberg_blue.json
+ minecraft/worldgen/placed_feature/iceberg_packed.json
+ minecraft/worldgen/placed_feature/jungle_bush.json
+ minecraft/worldgen/placed_feature/jungle_tree.json
+ minecraft/worldgen/placed_feature/kelp_cold.json
+ minecraft/worldgen/placed_feature/kelp_warm.json
+ minecraft/worldgen/placed_feature/lake_lava_surface.json
+ minecraft/worldgen/placed_feature/lake_lava_underground.json
+ minecraft/worldgen/placed_feature/large_basalt_columns.json
+ minecraft/worldgen/placed_feature/large_dripstone.json
+ minecraft/worldgen/placed_feature/lush_caves_ceiling_vegetation.json
+ minecraft/worldgen/placed_feature/lush_caves_clay.json
+ minecraft/worldgen/placed_feature/lush_caves_vegetation.json
+ minecraft/worldgen/placed_feature/mangrove_checked.json
+ minecraft/worldgen/placed_feature/mega_jungle_tree_checked.json
+ minecraft/worldgen/placed_feature/mega_pine_checked.json
+ minecraft/worldgen/placed_feature/mega_spruce_checked.json
+ minecraft/worldgen/placed_feature/monster_room_deep.json
+ minecraft/worldgen/placed_feature/monster_room.json
+ minecraft/worldgen/placed_feature/mushroom_island_vegetation.json
+ minecraft/worldgen/placed_feature/nether_sprouts.json
+ minecraft/worldgen/placed_feature/oak_bees_0002.json
+ minecraft/worldgen/placed_feature/oak_bees_002.json
+ minecraft/worldgen/placed_feature/oak_checked.json
+ minecraft/worldgen/placed_feature/oak.json
+ minecraft/worldgen/placed_feature/ore_ancient_debris_large.json
+ minecraft/worldgen/placed_feature/ore_andesite_lower.json
+ minecraft/worldgen/placed_feature/ore_andesite_upper.json
+ minecraft/worldgen/placed_feature/ore_blackstone.json
+ minecraft/worldgen/placed_feature/ore_clay.json
+ minecraft/worldgen/placed_feature/ore_coal_lower.json
+ minecraft/worldgen/placed_feature/ore_coal_upper.json
+ minecraft/worldgen/placed_feature/ore_copper_large.json
+ minecraft/worldgen/placed_feature/ore_copper.json
+ minecraft/worldgen/placed_feature/ore_debris_small.json
+ minecraft/worldgen/placed_feature/ore_diamond_buried.json
+ minecraft/worldgen/placed_feature/ore_diamond_large.json
+ minecraft/worldgen/placed_feature/ore_diamond.json
+ minecraft/worldgen/placed_feature/ore_diorite_lower.json
+ minecraft/worldgen/placed_feature/ore_diorite_upper.json
+ minecraft/worldgen/placed_feature/ore_dirt.json
+ minecraft/worldgen/placed_feature/ore_emerald.json
+ minecraft/worldgen/placed_feature/ore_gold_deltas.json
+ minecraft/worldgen/placed_feature/ore_gold_extra.json
+ minecraft/worldgen/placed_feature/ore_gold_lower.json
+ minecraft/worldgen/placed_feature/ore_gold_nether.json
+ minecraft/worldgen/placed_feature/ore_gold.json
+ minecraft/worldgen/placed_feature/ore_granite_lower.json
+ minecraft/worldgen/placed_feature/ore_granite_upper.json
+ minecraft/worldgen/placed_feature/ore_gravel_nether.json
+ minecraft/worldgen/placed_feature/ore_gravel.json
+ minecraft/worldgen/placed_feature/ore_infested.json
+ minecraft/worldgen/placed_feature/ore_iron_middle.json
+ minecraft/worldgen/placed_feature/ore_iron_small.json
+ minecraft/worldgen/placed_feature/ore_iron_upper.json
+ minecraft/worldgen/placed_feature/ore_lapis_buried.json
+ minecraft/worldgen/placed_feature/ore_lapis.json
+ minecraft/worldgen/placed_feature/ore_magma.json
+ minecraft/worldgen/placed_feature/ore_quartz_deltas.json
+ minecraft/worldgen/placed_feature/ore_quartz_nether.json
+ minecraft/worldgen/placed_feature/ore_redstone_lower.json
+ minecraft/worldgen/placed_feature/ore_redstone.json
+ minecraft/worldgen/placed_feature/ore_soul_sand.json
+ minecraft/worldgen/placed_feature/ore_tuff.json
+ minecraft/worldgen/placed_feature/patch_berry_bush.json
+ minecraft/worldgen/placed_feature/patch_berry_common.json
+ minecraft/worldgen/placed_feature/patch_berry_rare.json
+ minecraft/worldgen/placed_feature/patch_cactus_decorated.json
+ minecraft/worldgen/placed_feature/patch_cactus_desert.json
+ minecraft/worldgen/placed_feature/patch_cactus.json
+ minecraft/worldgen/placed_feature/patch_crimson_roots.json
+ minecraft/worldgen/placed_feature/patch_dead_bush_2.json
+ minecraft/worldgen/placed_feature/patch_dead_bush_badlands.json
+ minecraft/worldgen/placed_feature/patch_dead_bush.json
+ minecraft/worldgen/placed_feature/patch_fire.json
+ minecraft/worldgen/placed_feature/patch_grass_badlands.json
+ minecraft/worldgen/placed_feature/patch_grass_forest.json
+ minecraft/worldgen/placed_feature/patch_grass_jungle.json
+ minecraft/worldgen/placed_feature/patch_grass_normal.json
+ minecraft/worldgen/placed_feature/patch_grass_plain.json
+ minecraft/worldgen/placed_feature/patch_grass_savanna.json
+ minecraft/worldgen/placed_feature/patch_grass_taiga_2.json
+ minecraft/worldgen/placed_feature/patch_grass_taiga.json
+ minecraft/worldgen/placed_feature/patch_large_fern.json
+ minecraft/worldgen/placed_feature/patch_melon_sparse.json
+ minecraft/worldgen/placed_feature/patch_melon.json
+ minecraft/worldgen/placed_feature/patch_pumpkin.json
+ minecraft/worldgen/placed_feature/patch_soul_fire.json
+ minecraft/worldgen/placed_feature/patch_sugar_cane_badlands.json
+ minecraft/worldgen/placed_feature/patch_sugar_cane_desert.json
+ minecraft/worldgen/placed_feature/patch_sugar_cane_swamp.json
+ minecraft/worldgen/placed_feature/patch_sugar_cane.json
+ minecraft/worldgen/placed_feature/patch_sunflower.json
+ minecraft/worldgen/placed_feature/patch_taiga_grass.json
+ minecraft/worldgen/placed_feature/patch_tall_grass_2.json
+ minecraft/worldgen/placed_feature/patch_tall_grass.json
+ minecraft/worldgen/placed_feature/patch_waterlily.json
+ minecraft/worldgen/placed_feature/pile_hay.json
+ minecraft/worldgen/placed_feature/pile_ice.json
+ minecraft/worldgen/placed_feature/pile_melon.json
+ minecraft/worldgen/placed_feature/pile_pumpkin.json
+ minecraft/worldgen/placed_feature/pile_snow.json
+ minecraft/worldgen/placed_feature/pine_checked.json
+ minecraft/worldgen/placed_feature/pine_on_snow.json
+ minecraft/worldgen/placed_feature/pine.json
+ minecraft/worldgen/placed_feature/pointed_dripstone.json
+ minecraft/worldgen/placed_feature/red_mushroom_nether.json
+ minecraft/worldgen/placed_feature/red_mushroom_normal.json
+ minecraft/worldgen/placed_feature/red_mushroom_old_growth.json
+ minecraft/worldgen/placed_feature/red_mushroom_swamp.json
+ minecraft/worldgen/placed_feature/red_mushroom_taiga.json
+ minecraft/worldgen/placed_feature/rooted_azalea_tree.json
+ minecraft/worldgen/placed_feature/sculk_patch_ancient_city.json
+ minecraft/worldgen/placed_feature/sculk_patch_deep_dark.json
+ minecraft/worldgen/placed_feature/sculk_vein.json
+ minecraft/worldgen/placed_feature/sea_pickle.json
+ minecraft/worldgen/placed_feature/seagrass_cold.json
+ minecraft/worldgen/placed_feature/seagrass_deep_cold.json
+ minecraft/worldgen/placed_feature/seagrass_deep_warm.json
+ minecraft/worldgen/placed_feature/seagrass_deep.json
+ minecraft/worldgen/placed_feature/seagrass_normal.json
+ minecraft/worldgen/placed_feature/seagrass_river.json
+ minecraft/worldgen/placed_feature/seagrass_simple.json
+ minecraft/worldgen/placed_feature/seagrass_swamp.json
+ minecraft/worldgen/placed_feature/seagrass_warm.json
+ minecraft/worldgen/placed_feature/small_basalt_columns.json
+ minecraft/worldgen/placed_feature/spore_blossom.json
+ minecraft/worldgen/placed_feature/spring_closed_double.json
+ minecraft/worldgen/placed_feature/spring_closed.json
+ minecraft/worldgen/placed_feature/spring_delta.json
+ minecraft/worldgen/placed_feature/spring_lava_frozen.json
+ minecraft/worldgen/placed_feature/spring_lava.json
+ minecraft/worldgen/placed_feature/spring_open.json
+ minecraft/worldgen/placed_feature/spring_water.json
+ minecraft/worldgen/placed_feature/spruce_checked.json
+ minecraft/worldgen/placed_feature/spruce_on_snow.json
+ minecraft/worldgen/placed_feature/spruce.json
+ minecraft/worldgen/placed_feature/super_birch_bees_0002.json
+ minecraft/worldgen/placed_feature/super_birch_bees.json
+ minecraft/worldgen/placed_feature/tall_mangrove_checked.json
+ minecraft/worldgen/placed_feature/trees_badlands.json
+ minecraft/worldgen/placed_feature/trees_birch_and_oak.json
+ minecraft/worldgen/placed_feature/trees_birch.json
+ minecraft/worldgen/placed_feature/trees_flower_forest.json
+ minecraft/worldgen/placed_feature/trees_grove.json
+ minecraft/worldgen/placed_feature/trees_jungle.json
+ minecraft/worldgen/placed_feature/trees_mangrove.json
+ minecraft/worldgen/placed_feature/trees_meadow.json
+ minecraft/worldgen/placed_feature/trees_old_growth_pine_taiga.json
+ minecraft/worldgen/placed_feature/trees_old_growth_spruce_taiga.json
+ minecraft/worldgen/placed_feature/trees_plains.json
+ minecraft/worldgen/placed_feature/trees_savanna.json
+ minecraft/worldgen/placed_feature/trees_snowy.json
+ minecraft/worldgen/placed_feature/trees_sparse_jungle.json
+ minecraft/worldgen/placed_feature/trees_swamp.json
+ minecraft/worldgen/placed_feature/trees_taiga.json
+ minecraft/worldgen/placed_feature/trees_water.json
+ minecraft/worldgen/placed_feature/trees_windswept_forest.json
+ minecraft/worldgen/placed_feature/trees_windswept_hills.json
+ minecraft/worldgen/placed_feature/trees_windswept_savanna.json
+ minecraft/worldgen/placed_feature/twisting_vines.json
+ minecraft/worldgen/placed_feature/underwater_magma.json
+ minecraft/worldgen/placed_feature/vines.json
+ minecraft/worldgen/placed_feature/void_start_platform.json
+ minecraft/worldgen/placed_feature/warm_ocean_vegetation.json
+ minecraft/worldgen/placed_feature/warped_forest_vegetation.json
+ minecraft/worldgen/placed_feature/warped_fungi.json
+ minecraft/worldgen/placed_feature/weeping_vines.json
+ minecraft/worldgen/processor_list/ancient_city_generic_degradation.json
+ minecraft/worldgen/processor_list/ancient_city_start_degradation.json
+ minecraft/worldgen/processor_list/ancient_city_walls_degradation.json
+ minecraft/worldgen/processor_list/bastion_generic_degradation.json
+ minecraft/worldgen/processor_list/bottom_rampart.json
+ minecraft/worldgen/processor_list/bridge.json
+ minecraft/worldgen/processor_list/empty.json
+ minecraft/worldgen/processor_list/entrance_replacement.json
+ minecraft/worldgen/processor_list/farm_desert.json
+ minecraft/worldgen/processor_list/farm_plains.json
+ minecraft/worldgen/processor_list/farm_savanna.json
+ minecraft/worldgen/processor_list/farm_snowy.json
+ minecraft/worldgen/processor_list/farm_taiga.json
+ minecraft/worldgen/processor_list/fossil_coal.json
+ minecraft/worldgen/processor_list/fossil_diamonds.json
+ minecraft/worldgen/processor_list/fossil_rot.json
+ minecraft/worldgen/processor_list/high_rampart.json
+ minecraft/worldgen/processor_list/high_wall.json
+ minecraft/worldgen/processor_list/housing.json
+ minecraft/worldgen/processor_list/mossify_10_percent.json
+ minecraft/worldgen/processor_list/mossify_20_percent.json
+ minecraft/worldgen/processor_list/mossify_70_percent.json
+ minecraft/worldgen/processor_list/outpost_rot.json
+ minecraft/worldgen/processor_list/rampart_degradation.json
+ minecraft/worldgen/processor_list/roof.json
+ minecraft/worldgen/processor_list/side_wall_degradation.json
+ minecraft/worldgen/processor_list/stable_degradation.json
+ minecraft/worldgen/processor_list/street_plains.json
+ minecraft/worldgen/processor_list/street_savanna.json
+ minecraft/worldgen/processor_list/street_snowy_or_taiga.json
+ minecraft/worldgen/processor_list/treasure_rooms.json
+ minecraft/worldgen/processor_list/zombie_desert.json
+ minecraft/worldgen/processor_list/zombie_plains.json
+ minecraft/worldgen/processor_list/zombie_savanna.json
+ minecraft/worldgen/processor_list/zombie_snowy.json
+ minecraft/worldgen/processor_list/zombie_taiga.json
+ minecraft/worldgen/structure_set/ancient_cities.json
+ minecraft/worldgen/structure_set/buried_treasures.json
+ minecraft/worldgen/structure_set/desert_pyramids.json
+ minecraft/worldgen/structure_set/end_cities.json
+ minecraft/worldgen/structure_set/igloos.json
+ minecraft/worldgen/structure_set/jungle_temples.json
+ minecraft/worldgen/structure_set/mineshafts.json
+ minecraft/worldgen/structure_set/nether_complexes.json
+ minecraft/worldgen/structure_set/nether_fossils.json
+ minecraft/worldgen/structure_set/ocean_monuments.json
+ minecraft/worldgen/structure_set/ocean_ruins.json
+ minecraft/worldgen/structure_set/pillager_outposts.json
+ minecraft/worldgen/structure_set/ruined_portals.json
+ minecraft/worldgen/structure_set/shipwrecks.json
+ minecraft/worldgen/structure_set/strongholds.json
+ minecraft/worldgen/structure_set/swamp_huts.json
+ minecraft/worldgen/structure_set/villages.json
+ minecraft/worldgen/structure_set/woodland_mansions.json
+ minecraft/worldgen/structure/ancient_city.json
+ minecraft/worldgen/structure/bastion_remnant.json
+ minecraft/worldgen/structure/buried_treasure.json
+ minecraft/worldgen/structure/desert_pyramid.json
+ minecraft/worldgen/structure/end_city.json
+ minecraft/worldgen/structure/fortress.json
+ minecraft/worldgen/structure/igloo.json
+ minecraft/worldgen/structure/jungle_pyramid.json
+ minecraft/worldgen/structure/mansion.json
+ minecraft/worldgen/structure/mineshaft_mesa.json
+ minecraft/worldgen/structure/mineshaft.json
+ minecraft/worldgen/structure/monument.json
+ minecraft/worldgen/structure/nether_fossil.json
+ minecraft/worldgen/structure/ocean_ruin_cold.json
+ minecraft/worldgen/structure/ocean_ruin_warm.json
+ minecraft/worldgen/structure/pillager_outpost.json
+ minecraft/worldgen/structure/ruined_portal_desert.json
+ minecraft/worldgen/structure/ruined_portal_jungle.json
+ minecraft/worldgen/structure/ruined_portal_mountain.json
+ minecraft/worldgen/structure/ruined_portal_nether.json
+ minecraft/worldgen/structure/ruined_portal_ocean.json
+ minecraft/worldgen/structure/ruined_portal_swamp.json
+ minecraft/worldgen/structure/ruined_portal.json
+ minecraft/worldgen/structure/shipwreck_beached.json
+ minecraft/worldgen/structure/shipwreck.json
+ minecraft/worldgen/structure/stronghold.json
+ minecraft/worldgen/structure/swamp_hut.json
+ minecraft/worldgen/structure/village_desert.json
+ minecraft/worldgen/structure/village_plains.json
+ minecraft/worldgen/structure/village_savanna.json
+ minecraft/worldgen/structure/village_snowy.json
+ minecraft/worldgen/structure/village_taiga.json
+ minecraft/worldgen/template_pool/ancient_city/city_center.json
+ minecraft/worldgen/template_pool/ancient_city/city_center/walls.json
+ minecraft/worldgen/template_pool/ancient_city/city/entrance.json
+ minecraft/worldgen/template_pool/ancient_city/sculk.json
+ minecraft/worldgen/template_pool/ancient_city/structures.json
+ minecraft/worldgen/template_pool/ancient_city/walls.json
+ minecraft/worldgen/template_pool/ancient_city/walls/no_corners.json
+ minecraft/worldgen/template_pool/bastion/blocks/gold.json
+ minecraft/worldgen/template_pool/bastion/bridge/bridge_pieces.json
+ minecraft/worldgen/template_pool/bastion/bridge/connectors.json
+ minecraft/worldgen/template_pool/bastion/bridge/legs.json
+ minecraft/worldgen/template_pool/bastion/bridge/rampart_plates.json
+ minecraft/worldgen/template_pool/bastion/bridge/ramparts.json
+ minecraft/worldgen/template_pool/bastion/bridge/starting_pieces.json
+ minecraft/worldgen/template_pool/bastion/bridge/walls.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/connectors.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/inner.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/outer.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/mirrored_starting_pieces.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/posts.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/rampart_plates.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/ramparts.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/inner.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/outer.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/stairs.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/starting_pieces.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/wall_bases.json
+ minecraft/worldgen/template_pool/bastion/hoglin_stable/walls.json
+ minecraft/worldgen/template_pool/bastion/mobs/hoglin.json
+ minecraft/worldgen/template_pool/bastion/mobs/piglin_melee.json
+ minecraft/worldgen/template_pool/bastion/mobs/piglin.json
+ minecraft/worldgen/template_pool/bastion/starts.json
+ minecraft/worldgen/template_pool/bastion/treasure/bases.json
+ minecraft/worldgen/template_pool/bastion/treasure/bases/centers.json
+ minecraft/worldgen/template_pool/bastion/treasure/brains.json
+ minecraft/worldgen/template_pool/bastion/treasure/connectors.json
+ minecraft/worldgen/template_pool/bastion/treasure/corners/bottom.json
+ minecraft/worldgen/template_pool/bastion/treasure/corners/edges.json
+ minecraft/worldgen/template_pool/bastion/treasure/corners/middle.json
+ minecraft/worldgen/template_pool/bastion/treasure/corners/top.json
+ minecraft/worldgen/template_pool/bastion/treasure/entrances.json
+ minecraft/worldgen/template_pool/bastion/treasure/extensions/houses.json
+ minecraft/worldgen/template_pool/bastion/treasure/extensions/large_pool.json
+ minecraft/worldgen/template_pool/bastion/treasure/extensions/small_pool.json
+ minecraft/worldgen/template_pool/bastion/treasure/ramparts.json
+ minecraft/worldgen/template_pool/bastion/treasure/roofs.json
+ minecraft/worldgen/template_pool/bastion/treasure/stairs.json
+ minecraft/worldgen/template_pool/bastion/treasure/walls.json
+ minecraft/worldgen/template_pool/bastion/treasure/walls/bottom.json
+ minecraft/worldgen/template_pool/bastion/treasure/walls/mid.json
+ minecraft/worldgen/template_pool/bastion/treasure/walls/outer.json
+ minecraft/worldgen/template_pool/bastion/treasure/walls/top.json
+ minecraft/worldgen/template_pool/bastion/units/center_pieces.json
+ minecraft/worldgen/template_pool/bastion/units/edge_wall_units.json
+ minecraft/worldgen/template_pool/bastion/units/edges.json
+ minecraft/worldgen/template_pool/bastion/units/fillers/stage_0.json
+ minecraft/worldgen/template_pool/bastion/units/large_ramparts.json
+ minecraft/worldgen/template_pool/bastion/units/pathways.json
+ minecraft/worldgen/template_pool/bastion/units/rampart_plates.json
+ minecraft/worldgen/template_pool/bastion/units/ramparts.json
+ minecraft/worldgen/template_pool/bastion/units/stages/rot/stage_1.json
+ minecraft/worldgen/template_pool/bastion/units/stages/stage_0.json
+ minecraft/worldgen/template_pool/bastion/units/stages/stage_1.json
+ minecraft/worldgen/template_pool/bastion/units/stages/stage_2.json
+ minecraft/worldgen/template_pool/bastion/units/stages/stage_3.json
+ minecraft/worldgen/template_pool/bastion/units/wall_units.json
+ minecraft/worldgen/template_pool/bastion/units/walls/wall_bases.json
+ minecraft/worldgen/template_pool/empty.json
+ minecraft/worldgen/template_pool/pillager_outpost/base_plates.json
+ minecraft/worldgen/template_pool/pillager_outpost/feature_plates.json
+ minecraft/worldgen/template_pool/pillager_outpost/features.json
+ minecraft/worldgen/template_pool/pillager_outpost/towers.json
+ minecraft/worldgen/template_pool/village/common/animals.json
+ minecraft/worldgen/template_pool/village/common/butcher_animals.json
+ minecraft/worldgen/template_pool/village/common/cats.json
+ minecraft/worldgen/template_pool/village/common/iron_golem.json
+ minecraft/worldgen/template_pool/village/common/sheep.json
+ minecraft/worldgen/template_pool/village/common/well_bottoms.json
+ minecraft/worldgen/template_pool/village/desert/camel.json
+ minecraft/worldgen/template_pool/village/desert/decor.json
+ minecraft/worldgen/template_pool/village/desert/houses.json
+ minecraft/worldgen/template_pool/village/desert/streets.json
+ minecraft/worldgen/template_pool/village/desert/terminators.json
+ minecraft/worldgen/template_pool/village/desert/town_centers.json
+ minecraft/worldgen/template_pool/village/desert/villagers.json
+ minecraft/worldgen/template_pool/village/desert/zombie/decor.json
+ minecraft/worldgen/template_pool/village/desert/zombie/houses.json
+ minecraft/worldgen/template_pool/village/desert/zombie/streets.json
+ minecraft/worldgen/template_pool/village/desert/zombie/terminators.json
+ minecraft/worldgen/template_pool/village/desert/zombie/villagers.json
+ minecraft/worldgen/template_pool/village/plains/decor.json
+ minecraft/worldgen/template_pool/village/plains/houses.json
+ minecraft/worldgen/template_pool/village/plains/streets.json
+ minecraft/worldgen/template_pool/village/plains/terminators.json
+ minecraft/worldgen/template_pool/village/plains/town_centers.json
+ minecraft/worldgen/template_pool/village/plains/trees.json
+ minecraft/worldgen/template_pool/village/plains/villagers.json
+ minecraft/worldgen/template_pool/village/plains/zombie/decor.json
+ minecraft/worldgen/template_pool/village/plains/zombie/houses.json
+ minecraft/worldgen/template_pool/village/plains/zombie/streets.json
+ minecraft/worldgen/template_pool/village/plains/zombie/villagers.json
+ minecraft/worldgen/template_pool/village/savanna/decor.json
+ minecraft/worldgen/template_pool/village/savanna/houses.json
+ minecraft/worldgen/template_pool/village/savanna/streets.json
+ minecraft/worldgen/template_pool/village/savanna/terminators.json
+ minecraft/worldgen/template_pool/village/savanna/town_centers.json
+ minecraft/worldgen/template_pool/village/savanna/trees.json
+ minecraft/worldgen/template_pool/village/savanna/villagers.json
+ minecraft/worldgen/template_pool/village/savanna/zombie/decor.json
+ minecraft/worldgen/template_pool/village/savanna/zombie/houses.json
+ minecraft/worldgen/template_pool/village/savanna/zombie/streets.json
+ minecraft/worldgen/template_pool/village/savanna/zombie/terminators.json
+ minecraft/worldgen/template_pool/village/savanna/zombie/villagers.json
+ minecraft/worldgen/template_pool/village/snowy/decor.json
+ minecraft/worldgen/template_pool/village/snowy/houses.json
+ minecraft/worldgen/template_pool/village/snowy/streets.json
+ minecraft/worldgen/template_pool/village/snowy/terminators.json
+ minecraft/worldgen/template_pool/village/snowy/town_centers.json
+ minecraft/worldgen/template_pool/village/snowy/trees.json
+ minecraft/worldgen/template_pool/village/snowy/villagers.json
+ minecraft/worldgen/template_pool/village/snowy/zombie/decor.json
+ minecraft/worldgen/template_pool/village/snowy/zombie/houses.json
+ minecraft/worldgen/template_pool/village/snowy/zombie/streets.json
+ minecraft/worldgen/template_pool/village/snowy/zombie/villagers.json
+ minecraft/worldgen/template_pool/village/taiga/decor.json
+ minecraft/worldgen/template_pool/village/taiga/houses.json
+ minecraft/worldgen/template_pool/village/taiga/streets.json
+ minecraft/worldgen/template_pool/village/taiga/terminators.json
+ minecraft/worldgen/template_pool/village/taiga/town_centers.json
+ minecraft/worldgen/template_pool/village/taiga/villagers.json
+ minecraft/worldgen/template_pool/village/taiga/zombie/decor.json
+ minecraft/worldgen/template_pool/village/taiga/zombie/houses.json
+ minecraft/worldgen/template_pool/village/taiga/zombie/streets.json
+ minecraft/worldgen/template_pool/village/taiga/zombie/villagers.json
+ minecraft/worldgen/world_preset/amplified.json
+ minecraft/worldgen/world_preset/debug_all_block_states.json
+ minecraft/worldgen/world_preset/flat.json
+ minecraft/worldgen/world_preset/large_biomes.json
+ minecraft/worldgen/world_preset/normal.json
+ minecraft/worldgen/world_preset/single_biome_surface.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/acacia_hanging_sign.json
+ minecraft/blockstates/acacia_wall_hanging_sign.json
+ minecraft/blockstates/bamboo_button.json
+ minecraft/blockstates/bamboo_door.json
+ minecraft/blockstates/bamboo_fence_gate.json
+ minecraft/blockstates/bamboo_fence.json
+ minecraft/blockstates/bamboo_hanging_sign.json
+ minecraft/blockstates/bamboo_mosaic_slab.json
+ minecraft/blockstates/bamboo_mosaic_stairs.json
+ minecraft/blockstates/bamboo_mosaic.json
+ minecraft/blockstates/bamboo_planks.json
+ minecraft/blockstates/bamboo_pressure_plate.json
+ minecraft/blockstates/bamboo_sign.json
+ minecraft/blockstates/bamboo_slab.json
+ minecraft/blockstates/bamboo_stairs.json
+ minecraft/blockstates/bamboo_trapdoor.json
+ minecraft/blockstates/bamboo_wall_hanging_sign.json
+ minecraft/blockstates/bamboo_wall_sign.json
+ minecraft/blockstates/birch_hanging_sign.json
+ minecraft/blockstates/birch_wall_hanging_sign.json
+ minecraft/blockstates/chiseled_bookshelf.json
+ minecraft/blockstates/crimson_hanging_sign.json
+ minecraft/blockstates/crimson_wall_hanging_sign.json
+ minecraft/blockstates/dark_oak_hanging_sign.json
+ minecraft/blockstates/dark_oak_wall_hanging_sign.json
+ minecraft/blockstates/jungle_hanging_sign.json
+ minecraft/blockstates/jungle_wall_hanging_sign.json
+ minecraft/blockstates/mangrove_hanging_sign.json
+ minecraft/blockstates/mangrove_wall_hanging_sign.json
+ minecraft/blockstates/oak_hanging_sign.json
+ minecraft/blockstates/oak_wall_hanging_sign.json
+ minecraft/blockstates/spruce_hanging_sign.json
+ minecraft/blockstates/spruce_wall_hanging_sign.json
+ minecraft/blockstates/warped_hanging_sign.json
+ minecraft/blockstates/warped_wall_hanging_sign.json
+ minecraft/models/block/acacia_hanging_sign.json
+ minecraft/models/block/bamboo_button_inventory.json
+ minecraft/models/block/bamboo_button_pressed.json
+ minecraft/models/block/bamboo_button.json
+ minecraft/models/block/bamboo_door_bottom_left_open.json
+ minecraft/models/block/bamboo_door_bottom_left.json
+ minecraft/models/block/bamboo_door_bottom_right_open.json
+ minecraft/models/block/bamboo_door_bottom_right.json
+ minecraft/models/block/bamboo_door_top_left_open.json
+ minecraft/models/block/bamboo_door_top_left.json
+ minecraft/models/block/bamboo_door_top_right_open.json
+ minecraft/models/block/bamboo_door_top_right.json
+ minecraft/models/block/bamboo_fence_gate_open.json
+ minecraft/models/block/bamboo_fence_gate_wall_open.json
+ minecraft/models/block/bamboo_fence_gate_wall.json
+ minecraft/models/block/bamboo_fence_gate.json
+ minecraft/models/block/bamboo_fence_inventory.json
+ minecraft/models/block/bamboo_fence_post.json
+ minecraft/models/block/bamboo_fence_side_east.json
+ minecraft/models/block/bamboo_fence_side_north.json
+ minecraft/models/block/bamboo_fence_side_south.json
+ minecraft/models/block/bamboo_fence_side_west.json
+ minecraft/models/block/bamboo_hanging_sign.json
+ minecraft/models/block/bamboo_mosaic_slab_top.json
+ minecraft/models/block/bamboo_mosaic_slab.json
+ minecraft/models/block/bamboo_mosaic_stairs_inner.json
+ minecraft/models/block/bamboo_mosaic_stairs_outer.json
+ minecraft/models/block/bamboo_mosaic_stairs.json
+ minecraft/models/block/bamboo_mosaic.json
+ minecraft/models/block/bamboo_planks.json
+ minecraft/models/block/bamboo_pressure_plate_down.json
+ minecraft/models/block/bamboo_pressure_plate.json
+ minecraft/models/block/bamboo_sign.json
+ minecraft/models/block/bamboo_slab_top.json
+ minecraft/models/block/bamboo_slab.json
+ minecraft/models/block/bamboo_stairs_inner.json
+ minecraft/models/block/bamboo_stairs_outer.json
+ minecraft/models/block/bamboo_stairs.json
+ minecraft/models/block/bamboo_trapdoor_bottom.json
+ minecraft/models/block/bamboo_trapdoor_open.json
+ minecraft/models/block/bamboo_trapdoor_top.json
+ minecraft/models/block/birch_hanging_sign.json
+ minecraft/models/block/chiseled_bookshelf_stage0.json
+ minecraft/models/block/chiseled_bookshelf_stage1.json
+ minecraft/models/block/chiseled_bookshelf_stage2.json
+ minecraft/models/block/chiseled_bookshelf_stage3.json
+ minecraft/models/block/chiseled_bookshelf_stage4.json
+ minecraft/models/block/chiseled_bookshelf_stage5.json
+ minecraft/models/block/chiseled_bookshelf_stage6.json
+ minecraft/models/block/crimson_hanging_sign.json
+ minecraft/models/block/custom_fence_inventory.json
+ minecraft/models/block/custom_fence_post.json
+ minecraft/models/block/custom_fence_side_east.json
+ minecraft/models/block/custom_fence_side_north.json
+ minecraft/models/block/custom_fence_side_south.json
+ minecraft/models/block/custom_fence_side_west.json
+ minecraft/models/block/dark_oak_hanging_sign.json
+ minecraft/models/block/jungle_hanging_sign.json
+ minecraft/models/block/mangrove_hanging_sign.json
+ minecraft/models/block/oak_hanging_sign.json
+ minecraft/models/block/spruce_hanging_sign.json
+ minecraft/models/block/template_chiseled_bookshelf.json
+ minecraft/models/block/template_custom_fence_gate_open.json
+ minecraft/models/block/template_custom_fence_gate_wall_open.json
+ minecraft/models/block/template_custom_fence_gate_wall.json
+ minecraft/models/block/template_custom_fence_gate.json
+ minecraft/models/block/warped_hanging_sign.json
+ minecraft/models/item/acacia_hanging_sign.json
+ minecraft/models/item/bamboo_button.json
+ minecraft/models/item/bamboo_chest_raft.json
+ minecraft/models/item/bamboo_door.json
+ minecraft/models/item/bamboo_fence_gate.json
+ minecraft/models/item/bamboo_fence.json
+ minecraft/models/item/bamboo_hanging_sign.json
+ minecraft/models/item/bamboo_mosaic_slab.json
+ minecraft/models/item/bamboo_mosaic_stairs.json
+ minecraft/models/item/bamboo_mosaic.json
+ minecraft/models/item/bamboo_planks.json
+ minecraft/models/item/bamboo_pressure_plate.json
+ minecraft/models/item/bamboo_raft.json
+ minecraft/models/item/bamboo_sign.json
+ minecraft/models/item/bamboo_slab.json
+ minecraft/models/item/bamboo_stairs.json
+ minecraft/models/item/bamboo_trapdoor.json
+ minecraft/models/item/birch_hanging_sign.json
+ minecraft/models/item/camel_spawn_egg.json
+ minecraft/models/item/chiseled_bookshelf.json
+ minecraft/models/item/crimson_hanging_sign.json
+ minecraft/models/item/dark_oak_hanging_sign.json
+ minecraft/models/item/jungle_hanging_sign.json
+ minecraft/models/item/mangrove_hanging_sign.json
+ minecraft/models/item/oak_hanging_sign.json
+ minecraft/models/item/spruce_hanging_sign.json
+ minecraft/models/item/warped_hanging_sign.json
- minecraft/particles/block_marker.json
- minecraft/particles/block.json
- minecraft/particles/elder_guardian.json
- minecraft/particles/explosion_emitter.json
- minecraft/particles/item_slime.json
- minecraft/particles/item_snowball.json
- minecraft/particles/item.json
+ minecraft/textures/block/bamboo_door_bottom.png
+ minecraft/textures/block/bamboo_door_top.png
+ minecraft/textures/block/bamboo_fence_gate_particle.png
+ minecraft/textures/block/bamboo_fence_gate.png
+ minecraft/textures/block/bamboo_fence_particle.png
+ minecraft/textures/block/bamboo_fence.png
+ minecraft/textures/block/bamboo_mosaic.png
+ minecraft/textures/block/bamboo_planks.png
+ minecraft/textures/block/bamboo_trapdoor.png
+ minecraft/textures/block/chiseled_bookshelf_side.png
+ minecraft/textures/block/chiseled_bookshelf_stage0.png
+ minecraft/textures/block/chiseled_bookshelf_stage1.png
+ minecraft/textures/block/chiseled_bookshelf_stage2.png
+ minecraft/textures/block/chiseled_bookshelf_stage3.png
+ minecraft/textures/block/chiseled_bookshelf_stage4.png
+ minecraft/textures/block/chiseled_bookshelf_stage5.png
+ minecraft/textures/block/chiseled_bookshelf_stage6.png
+ minecraft/textures/block/chiseled_bookshelf_top.png
+ minecraft/textures/entity/boat/bamboo.png
+ minecraft/textures/entity/camel/camel.png
+ minecraft/textures/entity/chest_boat/bamboo.png
+ minecraft/textures/entity/signs/bamboo.png
+ minecraft/textures/entity/signs/hanging/acacia.png
+ minecraft/textures/entity/signs/hanging/bamboo.png
+ minecraft/textures/entity/signs/hanging/birch.png
+ minecraft/textures/entity/signs/hanging/crimson.png
+ minecraft/textures/entity/signs/hanging/dark_oak.png
+ minecraft/textures/entity/signs/hanging/jungle.png
+ minecraft/textures/entity/signs/hanging/mangrove.png
+ minecraft/textures/entity/signs/hanging/oak.png
+ minecraft/textures/entity/signs/hanging/spruce.png
+ minecraft/textures/entity/signs/hanging/warped.png
+ minecraft/textures/gui/checkmark.png
+ minecraft/textures/gui/hanging_signs/acacia.png
+ minecraft/textures/gui/hanging_signs/bamboo.png
+ minecraft/textures/gui/hanging_signs/birch.png
+ minecraft/textures/gui/hanging_signs/crimson.png
+ minecraft/textures/gui/hanging_signs/dark_oak.png
+ minecraft/textures/gui/hanging_signs/jungle.png
+ minecraft/textures/gui/hanging_signs/mangrove.png
+ minecraft/textures/gui/hanging_signs/oak.png
+ minecraft/textures/gui/hanging_signs/spruce.png
+ minecraft/textures/gui/hanging_signs/warped.png
+ minecraft/textures/item/acacia_hanging_sign.png
+ minecraft/textures/item/bamboo_chest_raft.png
+ minecraft/textures/item/bamboo_door.png
+ minecraft/textures/item/bamboo_hanging_sign.png
+ minecraft/textures/item/bamboo_raft.png
+ minecraft/textures/item/bamboo_sign.png
+ minecraft/textures/item/birch_hanging_sign.png
+ minecraft/textures/item/crimson_hanging_sign.png
+ minecraft/textures/item/dark_oak_hanging_sign.png
+ minecraft/textures/item/jungle_hanging_sign.png
+ minecraft/textures/item/mangrove_hanging_sign.png
+ minecraft/textures/item/oak_hanging_sign.png
+ minecraft/textures/item/spruce_hanging_sign.png
+ minecraft/textures/item/warped_hanging_sign.png
- realms/lang/en_us.json
- realms/textures/gui/realms/checkmark.png
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
+ Contains infinite genders!
+ I'm glad you're here!
+ You are valid!
+ You are welcome here!
+ Your gender is valid!
```

</details>
<details>
<summary>
parsers
</summary>

```diff
- minecraft:entity_summon
- minecraft:item_enchantment
- minecraft:mob_effect
+ minecraft:resource_key
+ minecraft:resource_or_tag_key
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
- XXX.advancements.packs.package-info
- XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaHusbandryAdvancements
- XXX.advancements.packs.VanillaStoryAdvancements
- XXX.ai.behavior.package-info
- XXX.ai.behavior.RandomLookAround
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.RandomSwim
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunIf
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.RunSometimes
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFrom
- XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ XXX.ai.behavior.SetWalkTargetFromBlockMemory
- XXX.ai.behavior.SetWalkTargetFromLookTarget
+ XXX.ai.behavior.ShowTradesToPlayer
- XXX.ai.behavior.ShufflingList
+ XXX.ai.behavior.ShufflingList$WeightedEntry
- XXX.ai.behavior.ShufflingList$WeightedEntry$1
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StayCloseToTarget
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.TryFindLand
- XXX.ai.behavior.TryFindLandNearWater
+ XXX.ai.behavior.TryFindWater
- XXX.ai.behavior.TryLaySpawnOnWaterNearLand
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerMakeLove
+ XXX.ai.behavior.VillagerPanicTrigger
- XXX.ai.behavior.WakeUp
+ XXX.ai.behavior.WorkAtComposter
- XXX.ai.behavior.WorkAtPoi
+ XXX.ai.behavior.YieldJobSite
+ XXX.ai.control.BodyRotationControl
- XXX.ai.control.Control
+ XXX.ai.control.FlyingMoveControl
- XXX.ai.control.JumpControl
+ XXX.ai.control.LookControl
- XXX.ai.control.MoveControl
+ XXX.ai.control.MoveControl$Operation
- XXX.ai.control.package-info
- XXX.ai.control.SmoothSwimmingLookControl
+ XXX.ai.control.SmoothSwimmingMoveControl
+ XXX.ai.goal.AvoidEntityGoal
- XXX.ai.goal.BegGoal
+ XXX.ai.goal.BoatGoals
- XXX.ai.goal.BreakDoorGoal
+ XXX.ai.goal.BreathAirGoal
- XXX.ai.goal.BreedGoal
+ XXX.ai.goal.CatLieOnBedGoal
- XXX.ai.goal.CatSitOnBlockGoal
+ XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
- XXX.ai.goal.DolphinJumpGoal
+ XXX.ai.goal.DoorInteractGoal
- XXX.ai.goal.EatBlockGoal
+ XXX.ai.goal.FleeSunGoal
- XXX.ai.goal.FloatGoal
+ XXX.ai.goal.FollowBoatGoal
- XXX.ai.goal.FollowFlockLeaderGoal
+ XXX.ai.goal.FollowMobGoal
- XXX.ai.goal.FollowOwnerGoal
+ XXX.ai.goal.FollowParentGoal
- XXX.ai.goal.Goal
+ XXX.ai.goal.Goal$Flag
- XXX.ai.goal.GoalSelector
+ XXX.ai.goal.GoalSelector$1
- XXX.ai.goal.GoalSelector$2
+ XXX.ai.goal.GolemRandomStrollInVillageGoal
- XXX.ai.goal.InteractGoal
+ XXX.ai.goal.JumpGoal
- XXX.ai.goal.LandOnOwnersShoulderGoal
+ XXX.ai.goal.LeapAtTargetGoal
- XXX.ai.goal.LlamaFollowCaravanGoal
+ XXX.ai.goal.LookAtPlayerGoal
- XXX.ai.goal.LookAtTradingPlayerGoal
+ XXX.ai.goal.MeleeAttackGoal
- XXX.ai.goal.MoveBackToVillageGoal
+ XXX.ai.goal.MoveThroughVillageGoal
- XXX.ai.goal.MoveToBlockGoal
+ XXX.ai.goal.MoveTowardsRestrictionGoal
- XXX.ai.goal.MoveTowardsTargetGoal
+ XXX.ai.goal.OcelotAttackGoal
- XXX.ai.goal.OfferFlowerGoal
+ XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.PanicGoal
+ XXX.ai.goal.PathfindToRaidGoal
- XXX.ai.goal.RandomLookAroundGoal
- XXX.animal.camel.Camel$1
- XXX.animal.camel.CamelAi
- XXX.animal.camel.CamelAi$RandomSitting
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
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Markings
- XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.Variant
- XXX.animal.horse.ZombieHorse
+ XXX.behavior.warden.Digging
- XXX.behavior.warden.Emerging
+ XXX.behavior.warden.ForceUnmount
- XXX.behavior.warden.package-info
- XXX.behavior.warden.Roar
+ XXX.behavior.warden.SetRoarTarget
- XXX.behavior.warden.SetWardenLookTarget
+ XXX.behavior.warden.Sniffing
- XXX.behavior.warden.SonicBoom
+ XXX.behavior.warden.TryToSniff
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
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
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.SculkShriekerBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
- XXX.block.grower.AbstractMegaTreeGrower
+ XXX.block.grower.AbstractTreeGrower
- XXX.block.grower.AcaciaTreeGrower
+ XXX.block.grower.AzaleaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.MangroveTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
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
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
+ XXX.commands.arguments.MessageArgument$Message
- XXX.commands.arguments.MessageArgument$Part
+ XXX.commands.arguments.MobEffectArgument
+ XXX.commands.arguments.RangeArgument
- XXX.commands.arguments.RangeArgument$Floats
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceArgument
- XXX.commands.arguments.ResourceArgument$Info$Template
- XXX.commands.arguments.ResourceOrTagArgument$Info
- XXX.commands.arguments.ResourceOrTagArgument$ResourceResult
- XXX.commands.arguments.ResourceOrTagArgument$TagResult
- XXX.commands.arguments.ResourceOrTagKeyArgument$Info
- XXX.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
- XXX.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ XXX.commands.arguments.ResourceOrTagLocationArgument$Info
+ XXX.commands.arguments.ResourceOrTagLocationArgument$ResourceResult
+ XXX.commands.arguments.ResourceOrTagLocationArgument$TagResult
+ XXX.core.cauldron.CauldronInteraction
- XXX.core.cauldron.package-info
+ XXX.core.dispenser.AbstractProjectileDispenseBehavior
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
- XXX.data.advancements.AdvancementSubProvider
+ XXX.data.advancements.AdventureAdvancements
+ XXX.data.advancements.NetherAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.info.BiomeParametersDumpReport
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
- XXX.data.info.RegistryDumpReport
+ XXX.data.info.WorldgenRegistryDumpReport
+ XXX.data.loot.BlockLoot
- XXX.data.loot.BlockLootSubProvider
+ XXX.data.loot.EntityLoot
+ XXX.data.loot.GiftLoot
- XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableSubProvider
+ XXX.data.loot.PiglinBarterLoot
- XXX.data.metadata.PackMetadataGenerator
- XXX.data.recipes.CraftingRecipeBuilder$1
- XXX.data.recipes.FinishedRecipe
+ XXX.data.recipes.RecipeBuilder
- XXX.data.recipes.RecipeCategory
+ XXX.data.tags.BlockTagsProvider
- XXX.data.tags.CatVariantTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.GameEventTagsProvider
+ XXX.data.tags.InstrumentTagsProvider
- XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
+ XXX.data.tags.PaintingVariantTagsProvider
- XXX.data.tags.PoiTypeTagsProvider
+ XXX.data.tags.StructureTagsProvider
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.UpdateOneTwentyBlockTagsProvider
- XXX.data.tags.VanillaBlockTagsProvider
- XXX.data.tags.WorldPresetTagsProvider
- XXX.data.worldgen.AncientCityStructurePieces
+ XXX.data.worldgen.AncientCityStructurePools
- XXX.data.worldgen.BastionBridgePools
+ XXX.data.worldgen.BastionHoglinStablePools
- XXX.data.worldgen.BastionHousingUnitsPools
+ XXX.data.worldgen.BastionPieces
- XXX.data.worldgen.BastionSharedPools
+ XXX.data.worldgen.BastionTreasureRoomPools
- XXX.data.worldgen.BiomeDefaultFeatures
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenameBiomesFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.SavedDataVillageCropFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimpleRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ XXX.datafix.fixes.StructureSettingsFlattenFix
- XXX.datafix.fixes.TeamDisplayNameFix
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
+ XXX.datafix.schemas.V1451_7
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
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
- XXX.datafix.schemas.V3203
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
- XXX.entity.animal.package-info
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
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
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
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.Ravager$RavagerNavigation
- XXX.entity.monster.Ravager$RavagerNodeEvaluator
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
- XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
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
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
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
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
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
- XXX.entity.vehicle.package-info
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
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
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
+ XXX.feature.rootplacers.RootPlacer
- XXX.feature.rootplacers.RootPlacerType
+ XXX.gameevent.vibrations.VibrationListener$VibrationListenerConfig
- XXX.gameevent.vibrations.VibrationSelector
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$TagValue
- XXX.item.crafting.Ingredient$Value
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeManager$1
- XXX.item.crafting.RecipeManager$CachedCheck
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.ShulkerBoxColoring
+ XXX.item.crafting.SimpleCookingSerializer
- XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ XXX.item.crafting.SimpleRecipeSerializer
+ XXX.level.biome.AmbientAdditionsSettings
- XXX.level.biome.AmbientMoodSettings
+ XXX.level.biome.AmbientParticleSettings
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$ClimateSettings
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$TemperatureModifier
- XXX.level.biome.Biome$TemperatureModifier$1
+ XXX.level.biome.Biome$TemperatureModifier$2
- XXX.level.biome.BiomeGenerationSettings
+ XXX.level.biome.BiomeGenerationSettings$Builder
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
+ XXX.level.biome.MultiNoiseBiomeSource$Preset
- XXX.level.biome.MultiNoiseBiomeSource$PresetInstance
+ XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.package-info
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCandleBlock
- XXX.level.block.AbstractCauldronBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AmethystBlock
+ XXX.level.block.AmethystClusterBlock
- XXX.level.block.AmethystClusterBlock$1
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.AzaleaBlock
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
+ XXX.level.block.BaseRailBlock$1
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
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CampfireBlock
- XXX.level.block.CandleBlock
+ XXX.level.block.CandleCakeBlock
- XXX.level.block.CarpetBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.CaveVines
- XXX.level.block.CaveVinesBlock
+ XXX.level.block.CaveVinesPlantBlock
- XXX.level.block.CeilingHangingSignBlock
- XXX.level.block.ChiseledBookShelfBlock
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
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.Fallable
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FletchingTableBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrogspawnBlock
- XXX.level.block.FrostedIceBlock
+ XXX.level.block.FungusBlock
- XXX.level.block.FurnaceBlock
+ XXX.level.block.GameMasterBlock
- XXX.level.block.GlassBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GlowLichenBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GravelBlock
+ XXX.level.block.GrindstoneBlock
- XXX.level.block.GrindstoneBlock$1
+ XXX.level.block.GrowingPlantBlock
- XXX.level.block.GrowingPlantBodyBlock
+ XXX.level.block.GrowingPlantHeadBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HangingRootsBlock
- XXX.level.block.HayBlock
+ XXX.level.block.HoneyBlock
- XXX.level.block.HopperBlock
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
- XXX.level.block.LanternBlock
+ XXX.level.block.LavaCauldronBlock
- XXX.level.block.LayeredCauldronBlock
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LeverBlock$1
+ XXX.level.block.LightBlock
- XXX.level.block.LightningRodBlock
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LoomBlock
- XXX.level.block.MagmaBlock
+ XXX.level.block.MangroveLeavesBlock
- XXX.level.block.MangrovePropaguleBlock
+ XXX.level.block.MangroveRootsBlock
- XXX.level.block.MelonBlock
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
+ XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
- XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.PotatoBlock
- XXX.level.block.PowderSnowBlock
+ XXX.level.block.PowderSnowCauldronBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PressurePlateBlock$Sensitivity
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
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
+ XXX.level.block.SculkBehaviour
- XXX.level.block.SculkBehaviour$1
+ XXX.level.block.SculkBlock
- XXX.level.block.SculkCatalystBlock
+ XXX.level.block.SculkSensorBlock
- XXX.level.block.SculkShriekerBlock
+ XXX.level.block.SculkSpreader
- XXX.level.block.SculkSpreader$ChargeCursor
+ XXX.level.block.SculkVeinBlock
- XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- XXX.level.block.SeagrassBlock
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SignBlock
- XXX.level.block.SimpleWaterloggedBlock
+ XXX.level.block.SkullBlock
- XXX.level.block.SkullBlock$Type
+ XXX.level.block.SkullBlock$Types
- XXX.level.block.SlabBlock
+ XXX.level.block.SlabBlock$1
- XXX.level.block.SlimeBlock
+ XXX.level.block.SmallDripleafBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
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
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.WallHangingSignBlock$1
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
+ XXX.level.gameevent.EuclideanGameEventDispatcher
- XXX.level.gameevent.EuclideanGameEventListenerRegistry
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
- XXX.level.gameevent.GameEventListenerRegistry$1
- XXX.level.gameevent.package-info
- XXX.level.gameevent.PositionSource
+ XXX.level.gameevent.PositionSourceType
- XXX.level.levelgen.RandomState$1
+ XXX.level.levelgen.RandomState$1NoiseWiringHelper
- XXX.level.levelgen.RandomSupport
+ XXX.level.levelgen.RandomSupport$Seed128bit
- XXX.level.levelgen.SingleThreadedRandomSource
+ XXX.level.levelgen.SurfaceRules
- XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ XXX.level.levelgen.SurfaceRules$Bandlands
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- XXX.level.levelgen.SurfaceRules$BlockRuleSource
+ XXX.level.levelgen.SurfaceRules$Condition
- XXX.level.levelgen.SurfaceRules$ConditionSource
+ XXX.level.levelgen.SurfaceRules$Context
- XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ XXX.level.levelgen.SurfaceRules$Context$HoleCondition
- XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- XXX.level.levelgen.SurfaceRules$Hole
+ XXX.level.levelgen.SurfaceRules$LazyCondition
- XXX.level.levelgen.SurfaceRules$LazyXZCondition
+ XXX.level.levelgen.SurfaceRules$LazyYCondition
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- XXX.level.levelgen.SurfaceRules$NotCondition
+ XXX.level.levelgen.SurfaceRules$NotConditionSource
- XXX.level.levelgen.SurfaceRules$RuleSource
+ XXX.level.levelgen.SurfaceRules$SequenceRule
- XXX.level.levelgen.SurfaceRules$SequenceRuleSource
+ XXX.level.levelgen.SurfaceRules$StateRule
- XXX.level.levelgen.SurfaceRules$Steep
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ XXX.level.levelgen.SurfaceRules$SurfaceRule
- XXX.level.levelgen.SurfaceRules$Temperature
+ XXX.level.levelgen.SurfaceRules$TestRule
- XXX.level.levelgen.SurfaceRules$TestRuleSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource
- XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ XXX.level.levelgen.SurfaceRules$YConditionSource
- XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ XXX.level.levelgen.SurfaceSystem
- XXX.level.levelgen.SurfaceSystem$1
+ XXX.level.levelgen.ThreadSafeLegacyRandomSource
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldDimensions
- XXX.level.levelgen.WorldDimensions$Complete
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.MaterialColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
- XXX.level.redstone.CollectingNeighborUpdater
+ XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
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
- XXX.level.storage.LevelVersion
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
+ XXX.levelgen.blending.Blender$BlendingOutput
- XXX.levelgen.blending.Blender$CellValueGetter
+ XXX.levelgen.blending.Blender$DistanceGetter
- XXX.levelgen.blending.BlendingData
+ XXX.levelgen.blending.BlendingData$BiomeConsumer
- XXX.levelgen.blending.BlendingData$DensityConsumer
+ XXX.levelgen.blending.BlendingData$HeightConsumer
- XXX.levelgen.blending.package-info
+ XXX.levelgen.blockpredicates.AllOfPredicate
- XXX.levelgen.blockpredicates.AnyOfPredicate
+ XXX.levelgen.blockpredicates.BlockPredicate
- XXX.levelgen.blockpredicates.BlockPredicateType
+ XXX.levelgen.blockpredicates.CombiningPredicate
- XXX.levelgen.blockpredicates.HasSturdyFacePredicate
+ XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ XXX.levelgen.blockpredicates.MatchingBlocksPredicate
- XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
- XXX.levelgen.blockpredicates.MatchingFluidsPredicate
+ XXX.levelgen.blockpredicates.NotPredicate
+ XXX.levelgen.blockpredicates.package-info
- XXX.levelgen.blockpredicates.ReplaceablePredicate
+ XXX.levelgen.blockpredicates.SolidPredicate
- XXX.levelgen.blockpredicates.StateTestingPredicate
+ XXX.levelgen.blockpredicates.TrueBlockPredicate
- XXX.levelgen.blockpredicates.WouldSurvivePredicate
- XXX.levelgen.carver.CanyonCarverConfiguration
+ XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CarverDebugSettings
+ XXX.levelgen.carver.CarvingContext
- XXX.levelgen.carver.CaveCarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.package-info
- XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.carver.WorldCarver$CarveSkipChecker
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockColumnFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskFeature
+ XXX.levelgen.feature.DripstoneClusterFeature
- XXX.levelgen.feature.DripstoneUtils
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeatureCountTracker
- XXX.levelgen.feature.FeatureCountTracker$1
+ XXX.levelgen.feature.FeatureCountTracker$FeatureData
- XXX.levelgen.feature.FeatureCountTracker$LevelData
+ XXX.levelgen.feature.FeaturePlaceContext
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.FossilFeatureConfiguration
+ XXX.levelgen.feature.GeodeFeature
- XXX.levelgen.feature.GlowstoneFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LakeFeature$Configuration
- XXX.levelgen.feature.LargeDripstoneFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.MultifaceGrowthFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
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
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
- XXX.loot.packs.UpdateOneTwentyBlockLoot
- XXX.loot.packs.VanillaBlockLoot
- XXX.loot.packs.VanillaEntityLoot
- XXX.loot.packs.VanillaGiftLoot
- XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
- XXX.minecraft.core.HolderSet
+ XXX.minecraft.core.HolderSet$Direct
- XXX.minecraft.core.HolderSet$ListBacked
+ XXX.minecraft.core.HolderSet$Named
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.LayeredRegistryAccess
- XXX.minecraft.core.package-info
- XXX.minecraft.core.RegistryAccess$Frozen
+ XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ XXX.minecraft.core.RegistryAccess$WritableRegistryAccess
+ XXX.minecraft.core.RegistryCodecs$1
- XXX.minecraft.core.RegistryCodecs$RegistryEntry
- XXX.minecraft.core.RegistrySynchronization$NetworkedRegistryData
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.UUIDUtil
+ XXX.minecraft.core.Vec3i
- XXX.minecraft.core.WritableRegistry
+ XXX.minecraft.data.BlockFamilies
- XXX.minecraft.data.BlockFamily
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.BuiltinRegistries
- XXX.minecraft.data.BuiltinRegistries$RegistryBootstrap
+ XXX.minecraft.data.CachedOutput
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataGenerator$PathProvider
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.HashCache$CacheUpdater
- XXX.minecraft.data.HashCache$ProviderCache
+ XXX.minecraft.data.Main
- XXX.minecraft.data.PackOutput
- XXX.minecraft.data.PackOutput$Target
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
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
- XXX.minecraft.nbt.NbtOps$InitialListCollector
- XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryLoader$Bound
+ XXX.minecraft.resources.RegistryResourceAccess$1
+ XXX.minecraft.resources.RegistryResourceAccess$InMemoryStorage
+ XXX.minecraft.resources.RegistryResourceAccess$ParsedEntry
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.WorldLoader$DataLoadOutput
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
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenAi$1
+ XXX.monster.warden.WardenSpawnTracker
+ XXX.network.chat.ChatPreviewCache
+ XXX.network.chat.ChatPreviewThrottler
+ XXX.network.chat.ChatSender
+ XXX.network.chat.LastSeenMessages$Entry
- XXX.network.chat.LastSeenMessages$Packed
- XXX.network.chat.LastSeenMessagesValidator
+ XXX.network.chat.LastSeenMessagesValidator$ErrorCondition
- XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignature$Unpacker
+ XXX.network.chat.MessageSigner
- XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage$Disguised
+ XXX.network.chat.OutgoingPlayerChatMessage
+ XXX.network.chat.OutgoingPlayerChatMessage$Tracked
- XXX.network.chat.PlayerChatMessage
+ XXX.network.chat.PreviewableCommand
- XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand$Argument
+ XXX.network.chat.SignedMessageBody
- XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain$DecodeException
+ XXX.network.chat.SignedMessageChain$Decoder
- XXX.network.chat.SignedMessageChain$Encoder
+ XXX.network.chat.SignedMessageChain$Link
+ XXX.network.chat.SignedMessageValidator$State
+ XXX.network.protocol.package-info
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializer$1
- XXX.network.syncher.EntityDataSerializer$ForValueType
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
- XXX.packs.linkfs.LinkFileSystem
- XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
- XXX.packs.linkfs.LinkFSFileStore
- XXX.packs.linkfs.LinkFSPath$1
- XXX.packs.linkfs.LinkFSPath$3
- XXX.packs.linkfs.LinkFSProvider$1
- XXX.packs.linkfs.package-info
- XXX.packs.linkfs.PathContents$1
- XXX.packs.linkfs.PathContents$DirectoryContents
+ XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.MetadataSectionType
+ XXX.packs.metadata.package-info
- XXX.packs.repository.Pack$Info
+ XXX.packs.repository.Pack$PackConstructor
- XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.PackSource$1
- XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$ResourceWithSource
+ XXX.packs.resources.Resource$IoSupplier
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceFilterSection$1
+ XXX.protocol.game.ClientboundClearTitlesPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
- XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- XXX.protocol.game.ClientboundCustomPayloadPacket
+ XXX.protocol.game.ClientboundCustomSoundPacket
- XXX.protocol.game.ClientboundDeleteChatPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundPlayerChatPacket
- XXX.protocol.game.ClientboundPlayerCombatEndPacket
+ XXX.protocol.game.ClientboundPlayerCombatEnterPacket
- XXX.protocol.game.ClientboundPlayerCombatKillPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$1
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$3
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$5
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
+ XXX.protocol.game.ClientboundSetDisplayChatPreviewPacket
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
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundSystemChatPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$1
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundInteractPacket$ActionType
+ XXX.protocol.game.ServerboundInteractPacket$Handler
- XXX.protocol.game.ServerboundInteractPacket$InteractionAction
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
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
- XXX.protocol.game.ServerboundPongPacket
+ XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ XXX.protocol.game.ServerboundRenameItemPacket
- XXX.protocol.game.ServerboundResourcePackPacket
+ XXX.protocol.game.ServerboundResourcePackPacket$Action
- XXX.protocol.game.ServerboundSeenAdvancementsPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSignUpdatePacket
+ XXX.protocol.game.ServerboundSwingPacket
- XXX.protocol.game.ServerboundTeleportToEntityPacket
+ XXX.protocol.game.ServerboundUseItemOnPacket
- XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.game.VecDeltaCodec
+ XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.status.ClientboundPongResponsePacket
- XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundPingRequestPacket
+ XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Players$Serializer
- XXX.protocol.status.ServerStatus$Serializer
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatus$Version$Serializer
+ XXX.protocol.status.ServerStatusPacketListener
- XXX.recipes.packs.package-info
- XXX.recipes.packs.UpdateOneTwentyRecipeProvider
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.server.packs.BuiltInMetadata
- XXX.server.packs.package-info
+ XXX.server.packs.PackResources
- XXX.server.packs.PackResources$ResourceOutput
- XXX.server.packs.PathPackResources
+ XXX.server.packs.ResourcePackFileNotFoundException
- XXX.server.packs.VanillaPackResourcesBuilder
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$Value
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.RotationSegment
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
- XXX.structure.pools.package-info
+ XXX.structure.pools.SinglePoolElement
- XXX.structure.pools.StructurePoolElement
+ XXX.structure.pools.StructurePoolElementType
- XXX.structure.pools.StructureTemplatePool
+ XXX.structure.pools.StructureTemplatePool$Projection
+ XXX.structure.structures.BuriedTreasurePieces
- XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.structure.structures.BuriedTreasureStructure
- XXX.structure.structures.DesertPyramidPiece
+ XXX.structure.structures.DesertPyramidStructure
- XXX.structure.structures.EndCityPieces
+ XXX.structure.structures.EndCityPieces$1
- XXX.structure.structures.EndCityPieces$2
+ XXX.structure.structures.EndCityPieces$3
- XXX.structure.structures.EndCityPieces$4
+ XXX.structure.structures.EndCityPieces$EndCityPiece
- XXX.structure.structures.EndCityPieces$SectionGenerator
+ XXX.structure.structures.EndCityStructure
- XXX.structure.structures.IglooPieces
+ XXX.structure.structures.IglooPieces$IglooPiece
- XXX.structure.structures.IglooStructure
+ XXX.structure.structures.JigsawStructure
- XXX.structure.structures.JigsawStructure$1
+ XXX.structure.structures.JungleTemplePiece
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
+ XXX.structure.structures.JungleTempleStructure
- XXX.structure.structures.MineshaftPieces
+ XXX.structure.structures.MineshaftPieces$1
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
+ XXX.structure.structures.MineshaftPieces$MineShaftCrossing
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
+ XXX.structure.structures.MineshaftPieces$MineShaftRoom
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
+ XXX.structure.structures.MineshaftStructure
- XXX.structure.structures.MineshaftStructure$Type
+ XXX.structure.structures.NetherFortressPieces
- XXX.structure.structures.NetherFortressPieces$1
+ XXX.structure.structures.NetherFortressPieces$BridgeCrossing
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
+ XXX.structure.structures.NetherFortressPieces$BridgeStraight
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
+ XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
- XXX.structure.structures.NetherFortressPieces$PieceWeight
+ XXX.structure.structures.NetherFortressPieces$RoomCrossing
- XXX.structure.structures.NetherFortressPieces$StairsRoom
+ XXX.structure.structures.NetherFortressPieces$StartPiece
- XXX.structure.structures.NetherFortressStructure
+ XXX.structure.structures.NetherFossilPieces
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
+ XXX.structure.structures.NetherFossilStructure
- XXX.structure.structures.OceanMonumentPieces
+ XXX.structure.structures.OceanMonumentPieces$1
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.structure.structures.OceanMonumentPieces$RoomDefinition
- XXX.structure.structures.OceanMonumentStructure
+ XXX.structure.structures.OceanRuinPieces
- XXX.structure.structures.OceanRuinPieces$1
+ XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
- XXX.structure.structures.OceanRuinStructure
+ XXX.structure.structures.OceanRuinStructure$Type
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
+ XXX.structure.structures.RuinedPortalPiece$Properties
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
+ XXX.structure.structures.RuinedPortalStructure
- XXX.structure.structures.RuinedPortalStructure$Setup
+ XXX.structure.structures.ShipwreckPieces
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
+ XXX.structure.structures.ShipwreckStructure
- XXX.structure.structures.StrongholdPieces
+ XXX.structure.structures.StrongholdPieces$1
- XXX.structure.structures.StrongholdPieces$2
+ XXX.structure.structures.StrongholdPieces$3
- XXX.structure.structures.StrongholdPieces$ChestCorridor
+ XXX.structure.structures.StrongholdPieces$FillerCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
+ XXX.structure.structures.StrongholdPieces$LeftTurn
- XXX.structure.structures.StrongholdPieces$Library
+ XXX.structure.structures.StrongholdPieces$PieceWeight
- XXX.structure.structures.StrongholdPieces$PortalRoom
+ XXX.structure.structures.StrongholdPieces$PrisonHall
- XXX.structure.structures.StrongholdPieces$RightTurn
+ XXX.structure.structures.StrongholdPieces$RoomCrossing
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
+ XXX.structure.structures.StrongholdPieces$StairsDown
- XXX.structure.structures.StrongholdPieces$StartPiece
+ XXX.structure.structures.StrongholdPieces$Straight
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.structure.structures.StrongholdPieces$Turn
- XXX.structure.structures.StrongholdStructure
+ XXX.structure.structures.SwampHutPiece
- XXX.structure.structures.SwampHutStructure
+ XXX.structure.structures.WoodlandMansionPieces
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
+ XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
+ XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
+ XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.structures.WoodlandMansionStructure
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
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
+ XXX.world.entity.package-info
- XXX.world.flag.FeatureFlag
- XXX.world.flag.FeatureFlagRegistry$Builder
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
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.AnvilMenu$1
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$FuelSlot
- XXX.world.inventory.BrewingStandMenu$IngredientsSlot
+ XXX.world.inventory.BrewingStandMenu$PotionSlot
- XXX.world.inventory.CartographyTableMenu
+ XXX.world.inventory.CartographyTableMenu$1
- XXX.world.inventory.CartographyTableMenu$2
+ XXX.world.inventory.CartographyTableMenu$3
- XXX.world.inventory.CartographyTableMenu$4
+ XXX.world.inventory.CartographyTableMenu$5
- XXX.world.inventory.ChestMenu
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.ContainerSynchronizer
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DispenserMenu
- XXX.world.inventory.EnchantmentMenu
+ XXX.world.inventory.EnchantmentMenu$1
- XXX.world.inventory.EnchantmentMenu$2
+ XXX.world.inventory.EnchantmentMenu$3
- XXX.world.inventory.FurnaceFuelSlot
+ XXX.world.inventory.FurnaceMenu
- XXX.world.inventory.FurnaceResultSlot
+ XXX.world.inventory.GrindstoneMenu
- XXX.world.inventory.GrindstoneMenu$1
+ XXX.world.inventory.GrindstoneMenu$2
- XXX.world.inventory.GrindstoneMenu$3
+ XXX.world.inventory.GrindstoneMenu$4
- XXX.world.inventory.HopperMenu
+ XXX.world.inventory.HorseInventoryMenu
- XXX.world.inventory.HorseInventoryMenu$1
+ XXX.world.inventory.HorseInventoryMenu$2
- XXX.world.inventory.InventoryMenu
+ XXX.world.inventory.InventoryMenu$1
- XXX.world.inventory.InventoryMenu$2
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.LecternMenu
+ XXX.world.inventory.LecternMenu$1
- XXX.world.inventory.LoomMenu
+ XXX.world.inventory.LoomMenu$1
- XXX.world.inventory.LoomMenu$2
+ XXX.world.inventory.LoomMenu$3
- XXX.world.inventory.LoomMenu$4
+ XXX.world.inventory.LoomMenu$5
- XXX.world.inventory.LoomMenu$6
+ XXX.world.inventory.MenuConstructor
- XXX.world.inventory.MenuType
+ XXX.world.inventory.MenuType$MenuSupplier
- XXX.world.inventory.MerchantContainer
+ XXX.world.inventory.MerchantMenu
- XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeHolder
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
+ XXX.world.item.AdventureModeCheck
- XXX.world.item.AirItem
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorItem$1
+ XXX.world.item.ArmorMaterial
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
- XXX.world.item.BookItem
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BowlFoodItem
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$10
+ XXX.world.item.CreativeModeTab$12
+ XXX.world.item.CreativeModeTab$3
+ XXX.world.item.CreativeModeTab$5
+ XXX.world.item.CreativeModeTab$7
+ XXX.world.item.CreativeModeTab$9
- XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTabs
- XXX.world.item.CreativeModeTabs$10
- XXX.world.item.CreativeModeTabs$12
- XXX.world.item.CreativeModeTabs$3
- XXX.world.item.CreativeModeTabs$5
- XXX.world.item.CreativeModeTabs$7
- XXX.world.item.CreativeModeTabs$9
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneyBottleItem
+ XXX.world.item.HoneycombItem
- XXX.world.item.HorseArmorItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$1
- XXX.world.item.Item$Properties
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUtils
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MapItem
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignItem
- XXX.world.item.SimpleFoiledItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
- XXX.world.item.TieredItem
+ XXX.world.item.Tiers
- XXX.world.item.TippedArrowItem
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.Vanishable
- XXX.world.item.Wearable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.package-info
- XXX.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util -1M
```
```
XXX.minecraft.commands.CommandBuildContext$1 +1M
```
```
XXX.minecraft.commands.CommandSourceStack +2M -2M
```
```
XXX.minecraft.commands.SharedSuggestionProvider +1P
```
```
XXX.commands.arguments.MessageArgument +8M -8M | -1P
```
```
XXX.commands.arguments.ParticleArgument +5M -4M | +1P
```
```
XXX.selector.options.EntitySelectorOptions$Option +6M | +1P -1P
```
```
XXX.commands.synchronization.SuggestionProviders +3M -2M
```
```
XXX.minecraft.core.DefaultedRegistry +1M -1M
```
```
XXX.minecraft.core.HolderLookup$RegistryLookup +3M
```
```
XXX.minecraft.core.Registry +5M -5M | +2P -2P
```
```
XXX.minecraft.core.RegistryAccess$1 +3M -2M
```
```
XXX.minecraft.core.RegistryAccess$RegistryEntry -1M
```
```
XXX.data.models.BlockModelGenerators +10M -5M
```
```
XXX.data.models.ModelProvider +1M -1M | +2P -2P
```
```
XXX.models.model.TextureMapping +4M
```
```
XXX.data.recipes.ShapedRecipeBuilder +3M -3M | +1P
```
```
XXX.data.recipes.ShapelessRecipeBuilder +3M -3M | +1P
```
```
XXX.data.recipes.SimpleCookingRecipeBuilder +9M -6M | +3P -1P
```
```
XXX.data.recipes.SingleItemRecipeBuilder +3M -3M | +1P
```
```
XXX.data.recipes.SpecialRecipeBuilder +2M -2M | +1P -1P
```
```
XXX.data.recipes.UpgradeRecipeBuilder +2M -2M | +1P
```
```
XXX.data.structures.SnbtToNbt +1M -1M | +2P -1P
```
```
XXX.data.tags.BannerPatternTagsProvider +1M -1M
```
```
XXX.gametest.framework.GameTestHelper$1 +1M -1M
```
```
XXX.minecraft.network.FriendlyByteBuf +7M -1M
```
```
XXX.network.chat.ChatDecorator -2M
```
```
XXX.network.chat.LastSeenMessagesTracker +6M -2M | +4P -3P
```
```
XXX.network.chat.SignedMessageValidator +3M -1M | +3P -2P
```
```
XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument +2P
```
```
XXX.protocol.game.ClientboundServerDataPacket +1M -2M | -1P
```
```
XXX.protocol.game.ServerboundChatAckPacket +2M -2M | +1P -1P
```
```
XXX.protocol.game.ServerboundChatPacket +1M -3M | -1P
```
```
XXX.minecraft.resources.RegistryOps +1M -5M | -2P
```
```
XXX.minecraft.resources.ResourceLocation +6M
```
```
XXX.minecraft.server.ServerFunctionLibrary +7M -8M | +1P -3P
```
```
XXX.minecraft.server.WorldLoader +4M -1M | +1P
```
```
XXX.minecraft.server.WorldLoader$PackConfig +3M -2M | +2P -1P
```
```
XXX.minecraft.server.WorldLoader$WorldDataSupplier +1P -1P
```
```
XXX.server.commands.EffectCommands +3M -3M
```
```
XXX.server.commands.EnchantCommand +2M -2M
```
```
XXX.server.commands.LocateCommand +18M -15M | -2P
```
```
XXX.server.commands.SummonCommand +2M -2M
```
```
XXX.server.commands.WardenSpawnTrackerCommand +1M
```
```
XXX.server.dedicated.DedicatedServer -1M
```
```
XXX.server.dedicated.DedicatedServerProperties +4M -1M | +4P -3P
```
```
XXX.server.level.WorldGenRegion +1M
```
```
XXX.server.network.ServerGamePacketListenerImpl +14M -27M | +5P -4P
```
```
XXX.server.network.ServerLoginPacketListenerImpl +1M -1M | +1P -1P
```
```
XXX.server.packs.FilePackResources +6M -4M | +2P
```
```
XXX.packs.repository.FolderRepositorySource +8M -6M | +3P -2P
```
```
XXX.packs.repository.ServerPacksSource +7M -2M | +5P -3P
```
```
XXX.packs.resources.MultiPackResourceManager +1M
```
```
XXX.packs.resources.ResourceProvider +2M
```
```
XXX.server.players.PlayerList +4M -5M | +1P -1P
```
```
XXX.minecraft.tags.ItemTags +3P
```
```
XXX.minecraft.tags.TagNetworkSerialization +1M -1M
```
```
XXX.minecraft.util.Crypt +1P
```
```
XXX.minecraft.util.FutureChain +4M -2M | +2P -1P
```
```
XXX.minecraft.util.TaskChainer$DelayedTask +1P
```
```
XXX.world.entity.AnimationState +1M
```
```
XXX.world.entity.Entity +6M -1M | -1P
```
```
XXX.world.entity.LivingEntity +3M -1M
```
```
XXX.world.entity.PlayerRideableJumping +1M
```
```
XXX.world.entity.Saddleable +1M
```
```
XXX.ai.attributes.AttributeMap +4M
```
```
XXX.ai.behavior.BlockPosTracker +1M
```
```
XXX.ai.behavior.LongJumpToRandomPos +5M -5M | +1P -1P
```
```
XXX.ai.memory.MemoryModuleType +1P
```
```
XXX.ai.sensing.TemptingSensor +1M
```
```
XXX.village.poi.PoiTypes +1M -1M
```
```
XXX.animal.allay.AllayAi +1P
```
```
XXX.item.crafting.SmeltingRecipe +1M -1M
```
```
XXX.item.crafting.TippedArrowRecipe +1M -1M
```
```
XXX.world.level.CommonLevelAccessor -1P
```
```
XXX.world.level.LevelReader +1M | +2P
```
```
XXX.world.level.StructureManager +2M -2M | +1P -1P
```
```
XXX.level.block.SupportType$2 +1M | +1P
```
```
XXX.level.block.TrapDoorBlock +1M -1M | +2P
```
```
XXX.level.chunk.ChunkAccess +1M -1M
```
```
XXX.level.chunk.ChunkGenerator +28M -22M | +1P
```
```
XXX.level.gameevent.GameEventDispatcher +4M -1M | +1P -5P
```
```
XXX.gameevent.vibrations.VibrationListener +13M -6M | +3P -2P
```
```
XXX.levelgen.presets.WorldPreset +1M -4M
```
```
XXX.storage.loot.LootTable +2M -2M
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ CompletableFuture failedFuture(Throwable)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandBuildContext$1
</summary>

```diff
- HolderSet$Named lambda$get$0(TagKey)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
+ ChatSender asChatSender()
- FeatureFlagSet enabledFeatures()
- void sendChatMessage(OutgoingChatMessage,boolean,ChatType$Bound)
+ void sendChatMessage(OutgoingPlayerChatMessage,boolean,ChatType$Bound)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.MessageArgument
</summary>

```diff
+ Class getValueType()
- CompletableFuture filterPlainText(CommandSourceStack,PlayerChatMessage)
- CompletableFuture lambda$resolveDisguisedMessage$3(CompletableFuture,Consumer,PlayerChatMessage,Executor)
- CompletableFuture lambda$resolveSignedMessage$1(CompletableFuture,CompletableFuture,PlayerChatMessage,Consumer,Executor)
+ CompletableFuture resolvePreview(CommandSourceStack,MessageArgument$Message)
+ CompletableFuture resolvePreview(CommandSourceStack,Object)
+ MessageArgument$ChatMessage getChatMessage(CommandContext,String)
+ Object lambda$logResolutionFailure$0(CommandSourceStack,Throwable)
+ String getSignableText(MessageArgument$Message)
+ String getSignableText(Object)
- void lambda$resolveDisguisedMessage$2(Consumer,PlayerChatMessage,Component)
- void lambda$resolveSignedMessage$0(PlayerChatMessage,CompletableFuture,CompletableFuture,Consumer,Void)
+ void logResolutionFailure(CommandSourceStack,CompletableFuture)
- void resolveChatMessage(CommandContext,String,Consumer)
- void resolveDisguisedMessage(Consumer,CommandSourceStack,PlayerChatMessage)
- void resolveSignedMessage(Consumer,CommandSourceStack,PlayerChatMessage)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.ParticleArgument
</summary>

```diff
+ CommandSyntaxException lambda$readParticle$1(ResourceLocation)
- CommandSyntaxException lambda$readParticleType$1(ResourceLocation)
+ ParticleArgument particle()
- ParticleArgument particle(CommandBuildContext)
- ParticleOptions readParticle(StringReader,HolderLookup)
+ ParticleOptions readParticle(StringReader)
- ParticleType readParticleType(StringReader,HolderLookup)
+ void <init>()
- void <init>(CommandBuildContext)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
</summary>

```diff
- boolean equals(Object)
- Component description()
- EntitySelectorOptions$Modifier modifier()
- int hashCode()
- Predicate canUse()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.commands.synchronization.SuggestionProviders
</summary>

```diff
- boolean lambda$static$3(CommandContext,EntityType)
+ CompletableFuture lambda$static$4(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$static$5(CommandContext,SuggestionsBuilder)
+ Message lambda$static$3(EntityType)
- Message lambda$static$4(EntityType)
```

</details>
<details>
<summary>
net.minecraft.core.DefaultedRegistry
</summary>

```diff
- void <init>(String,ResourceKey,Lifecycle,boolean)
+ void <init>(String,ResourceKey,Lifecycle,Function)
```

</details>
<details>
<summary>
net.minecraft.core.HolderLookup$RegistryLookup
</summary>

```diff
- boolean lambda$filterFeatures$0(FeatureFlagSet,Object)
- HolderLookup filterElements(Predicate)
- HolderLookup filterFeatures(FeatureFlagSet)
```

</details>
<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ DefaultedRegistry registerDefaulted(ResourceKey,String,Function,Registry$RegistryBootstrap)
+ DefaultedRegistry registerDefaulted(ResourceKey,String,Lifecycle,Function,Registry$RegistryBootstrap)
- DefaultedRegistry registerDefaultedWithIntrusiveHolders(ResourceKey,String,Lifecycle,Registry$RegistryBootstrap)
- DefaultedRegistry registerDefaultedWithIntrusiveHolders(ResourceKey,String,Registry$RegistryBootstrap)
+ Holder getHolderOrThrow(ResourceKey)
- Holder$Reference getHolderOrThrow(ResourceKey)
+ Lifecycle lifecycle()
+ Registry registerSimple(ResourceKey,Lifecycle,Function,Registry$RegistryBootstrap)
- ResourceKey levelStemToLevel(ResourceKey)
- ResourceKey levelToLevelStem(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess$1
</summary>

```diff
+ Optional ownedRegistry(ResourceKey)
- Optional registry(ResourceKey)
- RegistryAccess$Frozen freeze()
+ Stream ownedRegistries()
- Stream registries()
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess$RegistryEntry
</summary>

```diff
+ RegistryAccess$RegistryEntry fromHolder(Holder$Reference)
```

</details>
<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- BlockStateGenerator createCustomFence(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
- BlockStateGenerator createFenceGate(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,boolean)
+ BlockStateGenerator createFenceGate(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
- ResourceLocation lambda$createChiseledBookshelf$45(Integer)
- Variant lambda$createChiseledBookshelf$46(List,Integer)
+ Variant lambda$createJigsaw$46(FrontAndTop)
- Variant lambda$createJigsaw$48(FrontAndTop)
+ Variant lambda$createRespawnAnchor$45(ResourceLocation[],Integer)
- Variant lambda$createRespawnAnchor$47(ResourceLocation[],Integer)
- void createChiseledBookshelf()
- void createHangingSign(Block,Block,Block)
+ void lambda$run$47(BlockFamily)
+ void lambda$run$48(SpawnEggItem)
- void lambda$run$49(BlockFamily)
- void lambda$run$50(SpawnEggItem)
```

</details>
<details>
<summary>
net.minecraft.data.models.ModelProvider
</summary>

```diff
+ void <init>(DataGenerator)
- void <init>(PackOutput)
```

</details>
<details>
<summary>
net.minecraft.data.models.model.TextureMapping
</summary>

```diff
- String lambda$getBlockTexture$0(String,String)
- String lambda$getItemTexture$1(String,String)
- TextureMapping customParticle(Block)
- TextureMapping fence(Block)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapedRecipeBuilder
</summary>

```diff
+ ShapedRecipeBuilder shaped(ItemLike,int)
+ ShapedRecipeBuilder shaped(ItemLike)
- ShapedRecipeBuilder shaped(RecipeCategory,ItemLike,int)
- ShapedRecipeBuilder shaped(RecipeCategory,ItemLike)
+ void <init>(ItemLike,int)
- void <init>(RecipeCategory,ItemLike,int)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapelessRecipeBuilder
</summary>

```diff
+ ShapelessRecipeBuilder shapeless(ItemLike,int)
+ ShapelessRecipeBuilder shapeless(ItemLike)
- ShapelessRecipeBuilder shapeless(RecipeCategory,ItemLike,int)
- ShapelessRecipeBuilder shapeless(RecipeCategory,ItemLike)
+ void <init>(ItemLike,int)
- void <init>(RecipeCategory,ItemLike,int)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.SimpleCookingRecipeBuilder
</summary>

```diff
- CookingBookCategory determineBlastingRecipeCategory(ItemLike)
- CookingBookCategory determineRecipeCategory(RecipeSerializer,ItemLike)
- CookingBookCategory determineSmeltingRecipeCategory(ItemLike)
+ SimpleCookingRecipeBuilder blasting(Ingredient,ItemLike,float,int)
- SimpleCookingRecipeBuilder blasting(Ingredient,RecipeCategory,ItemLike,float,int)
+ SimpleCookingRecipeBuilder campfireCooking(Ingredient,ItemLike,float,int)
- SimpleCookingRecipeBuilder campfireCooking(Ingredient,RecipeCategory,ItemLike,float,int)
+ SimpleCookingRecipeBuilder cooking(Ingredient,ItemLike,float,int,SimpleCookingSerializer)
- SimpleCookingRecipeBuilder generic(Ingredient,RecipeCategory,ItemLike,float,int,RecipeSerializer)
+ SimpleCookingRecipeBuilder smelting(Ingredient,ItemLike,float,int)
- SimpleCookingRecipeBuilder smelting(Ingredient,RecipeCategory,ItemLike,float,int)
+ SimpleCookingRecipeBuilder smoking(Ingredient,ItemLike,float,int)
- SimpleCookingRecipeBuilder smoking(Ingredient,RecipeCategory,ItemLike,float,int)
+ void <init>(ItemLike,Ingredient,float,int,SimpleCookingSerializer)
- void <init>(RecipeCategory,CookingBookCategory,ItemLike,Ingredient,float,int,RecipeSerializer)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.SingleItemRecipeBuilder
</summary>

```diff
+ SingleItemRecipeBuilder stonecutting(Ingredient,ItemLike,int)
+ SingleItemRecipeBuilder stonecutting(Ingredient,ItemLike)
- SingleItemRecipeBuilder stonecutting(Ingredient,RecipeCategory,ItemLike,int)
- SingleItemRecipeBuilder stonecutting(Ingredient,RecipeCategory,ItemLike)
- void <init>(RecipeCategory,RecipeSerializer,Ingredient,ItemLike,int)
+ void <init>(RecipeSerializer,Ingredient,ItemLike,int)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.SpecialRecipeBuilder
</summary>

```diff
- SpecialRecipeBuilder special(RecipeSerializer)
+ SpecialRecipeBuilder special(SimpleRecipeSerializer)
- void <init>(RecipeSerializer)
+ void <init>(SimpleRecipeSerializer)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.UpgradeRecipeBuilder
</summary>

```diff
+ UpgradeRecipeBuilder smithing(Ingredient,Ingredient,Item)
- UpgradeRecipeBuilder smithing(Ingredient,Ingredient,RecipeCategory,Item)
+ void <init>(RecipeSerializer,Ingredient,Ingredient,Item)
- void <init>(RecipeSerializer,Ingredient,Ingredient,RecipeCategory,Item)
```

</details>
<details>
<summary>
net.minecraft.data.structures.SnbtToNbt
</summary>

```diff
+ void <init>(DataGenerator)
- void <init>(PackOutput,Iterable)
```

</details>
<details>
<summary>
net.minecraft.data.tags.BannerPatternTagsProvider
</summary>

```diff
+ void <init>(DataGenerator)
- void <init>(PackOutput)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper$1
</summary>

```diff
+ void <init>(GameTestHelper,Level,BlockPos,float,GameProfile,ProfilePublicKey)
- void <init>(GameTestHelper,Level,BlockPos,float,GameProfile)
```

</details>
<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- BitSet readFixedBitSet(int)
- EnumSet readEnumSet(Class)
- PropertyMap readGameProfileProperties()
+ void lambda$readGameProfile$6(PropertyMap,FriendlyByteBuf)
- void lambda$readGameProfileProperties$6(PropertyMap,FriendlyByteBuf)
- void writeEnumSet(EnumSet,Class)
- void writeFixedBitSet(BitSet,int)
- void writeGameProfileProperties(PropertyMap)
```

</details>
<details>
<summary>
net.minecraft.network.chat.ChatDecorator
</summary>

```diff
+ CompletableFuture decorate(ServerPlayer,PlayerChatMessage)
+ PlayerChatMessage attachIfNotDecorated(PlayerChatMessage,Component)
```

</details>
<details>
<summary>
net.minecraft.network.chat.LastSeenMessagesTracker
</summary>

```diff
- boolean addPending(MessageSignature,boolean)
- int getAndClearOffset()
- int offset()
+ LastSeenMessages get()
- LastSeenMessagesTracker$Update generateAndApplyUpdate()
- void addEntry(LastSeenTrackedEntry)
- void ignorePending(MessageSignature)
+ void push(LastSeenMessages$Entry)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageValidator
</summary>

```diff
- boolean lambda$static$0(PlayerChatMessage)
- boolean lambda$static$1(PlayerChatMessage)
+ SignedMessageValidator create(ProfilePublicKey,boolean)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundServerDataPacket
</summary>

```diff
+ boolean previewsChat()
+ void <init>(Component,String,boolean,boolean)
- void <init>(Component,String,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundChatAckPacket
</summary>

```diff
- int offset()
+ LastSeenMessages$Update lastSeenMessages()
- void <init>(int)
+ void <init>(LastSeenMessages$Update)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundChatPacket
</summary>

```diff
+ boolean signedPreview()
+ MessageSigner getSigner(ServerPlayer)
+ void <init>(String,Instant,long,MessageSignature,boolean,LastSeenMessages$Update)
- void <init>(String,Instant,long,MessageSignature,LastSeenMessages$Update)
```

</details>
<details>
<summary>
net.minecraft.resources.RegistryOps
</summary>

```diff
+ DynamicOps getAsJson()
+ Optional registryLoader()
+ RegistryOps createAndLoad(DynamicOps,RegistryAccess$Writable,RegistryResourceAccess)
+ RegistryOps createAndLoad(DynamicOps,RegistryAccess$Writable,ResourceManager)
+ void <init>(DynamicOps,RegistryAccess,Optional)
- void <init>(DynamicOps,RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.resources.ResourceLocation
</summary>

```diff
- ResourceLocation withPath(String)
- ResourceLocation withPath(UnaryOperator)
- ResourceLocation withPrefix(String)
- String assertValidNamespace(String,String)
- String assertValidPath(String,String)
- void <init>(String,String,ResourceLocation$Dummy)
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionLibrary
</summary>

```diff
+ boolean lambda$reload$1(ResourceLocation)
- CommandFunction lambda$reload$2(Map$Entry,ResourceLocation,CommandSourceStack)
+ CommandFunction lambda$reload$3(Map$Entry,ResourceLocation,CommandSourceStack)
- CompletionStage lambda$reload$4(Executor,Map)
+ CompletionStage lambda$reload$5(Executor,Map)
- Map lambda$reload$1(ResourceManager)
+ Map lambda$reload$2(ResourceManager)
- Map lambda$reload$3(Map,Void,Throwable)
+ Map lambda$reload$4(Map,Void,Throwable)
- Object lambda$reload$5(ResourceLocation,ImmutableMap$Builder,CommandFunction,Throwable)
+ Object lambda$reload$6(ResourceLocation,ImmutableMap$Builder,CommandFunction,Throwable)
- void lambda$reload$6(ImmutableMap$Builder,ResourceLocation,CompletableFuture)
+ void lambda$reload$7(ImmutableMap$Builder,ResourceLocation,CompletableFuture)
- void lambda$reload$7(Pair)
+ void lambda$reload$8(Pair)
```

</details>
<details>
<summary>
net.minecraft.server.WorldLoader
</summary>

```diff
- LayeredRegistryAccess loadAndReplaceLayer(ResourceManager,LayeredRegistryAccess,RegistryLayer,List)
- Object lambda$load$1(RegistryAccess$Frozen,WorldLoader$ResultFactory,CloseableResourceManager,LayeredRegistryAccess,WorldLoader$DataLoadOutput,ReloadableServerResources)
+ Object lambda$load$1(RegistryAccess$Frozen,WorldLoader$ResultFactory,CloseableResourceManager,Object,ReloadableServerResources)
- RegistryAccess$Frozen loadLayer(ResourceManager,LayeredRegistryAccess,RegistryLayer,List)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.server.WorldLoader$PackConfig
</summary>

```diff
- boolean initMode()
+ DataPackConfig initialDataPacks()
+ void <init>(PackRepository,DataPackConfig,boolean)
- void <init>(PackRepository,WorldDataConfiguration,boolean,boolean)
- WorldDataConfiguration initialDataConfig()
```

</details>
<details>
<summary>
net.minecraft.server.commands.EffectCommands
</summary>

```diff
- int clearEffect(CommandSourceStack,Collection,Holder)
+ int clearEffect(CommandSourceStack,Collection,MobEffect)
- int giveEffect(CommandSourceStack,Collection,Holder,Integer,int,boolean)
+ int giveEffect(CommandSourceStack,Collection,MobEffect,Integer,int,boolean)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.server.commands.EnchantCommand
</summary>

```diff
+ int enchant(CommandSourceStack,Collection,Enchantment,int)
- int enchant(CommandSourceStack,Collection,Holder,int)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.server.commands.LocateCommand
</summary>

```diff
- boolean lambda$register$4(CommandSourceStack)
+ boolean lambda$register$6(CommandSourceStack)
- CommandSyntaxException lambda$locateStructure$10(ResourceOrTagKeyArgument$Result)
+ CommandSyntaxException lambda$locateStructure$12(ResourceOrTagLocationArgument$Result)
+ HolderSet$Direct lambda$getHolders$10(Holder)
- HolderSet$Direct lambda$getHolders$8(Holder)
- int lambda$register$5(CommandContext)
- int lambda$register$6(CommandContext)
+ int lambda$register$8(CommandContext)
+ int lambda$register$9(CommandContext)
- int locateBiome(CommandSourceStack,ResourceOrTagArgument$Result)
+ int locateBiome(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int locatePoi(CommandSourceStack,ResourceOrTagArgument$Result)
+ int locatePoi(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int locateStructure(CommandSourceStack,ResourceOrTagKeyArgument$Result)
+ int locateStructure(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int showLocateResult(CommandSourceStack,BlockPos,Pair,String,boolean,String)
- int showLocateResult(CommandSourceStack,ResourceOrTagArgument$Result,BlockPos,Pair,String,boolean)
- int showLocateResult(CommandSourceStack,ResourceOrTagKeyArgument$Result,BlockPos,Pair,String,boolean)
+ int showLocateResult(CommandSourceStack,ResourceOrTagLocationArgument$Result,BlockPos,Pair,String,boolean)
+ Message lambda$static$4(Object)
+ Message lambda$static$5(Object)
- Optional getHolders(ResourceOrTagKeyArgument$Result,Registry)
+ Optional getHolders(ResourceOrTagLocationArgument$Result,Registry)
+ Optional lambda$getHolders$11(Registry,ResourceKey)
- Optional lambda$getHolders$9(Registry,ResourceKey)
- String getElementName(Pair)
- String lambda$getElementName$11(ResourceKey)
- String lambda$showLocateResult$12(ResourceOrTagArgument$Result,Holder$Reference)
+ String lambda$showLocateResult$13(ResourceKey)
- String lambda$showLocateResult$13(ResourceOrTagArgument$Result,Pair,HolderSet$Named)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SummonCommand
</summary>

```diff
- int spawnEntity(CommandSourceStack,Holder$Reference,Vec3,CompoundTag,boolean)
+ int spawnEntity(CommandSourceStack,ResourceLocation,Vec3,CompoundTag,boolean)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WardenSpawnTrackerCommand
</summary>

```diff
- void lambda$setWarningLevel$3(int,WardenSpawnTracker)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
+ boolean previewsChat()
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerProperties
</summary>

```diff
- DataPackConfig getDatapackConfig(String,String)
- FeatureFlagSet getFeatures(String)
- void lambda$getFeatures$4(String,Consumer)
- WorldDimensions createDimensions(RegistryAccess)
+ WorldGenSettings getWorldGenSettings(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
- FeatureFlagSet enabledFeatures()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
+ boolean handlesPreviewRequests()
+ boolean tryHandleChat(String,Instant,LastSeenMessages$Update)
+ boolean verifyChatMessage(PlayerChatMessage)
+ ChatMessageContent getSignedContent(ServerboundChatPacket)
+ CompletableFuture getPreviewedArgument(CommandSourceStack,PreviewableCommand)
- CompletableFuture lambda$handleChat$9(CompletableFuture,CompletableFuture,PlayerChatMessage,Executor)
+ CompletableFuture lambda$handleChat$9(PlayerChatMessage)
+ CompletableFuture lambda$handleChatPreview$14(ServerboundChatPreviewPacket)
+ CompletableFuture queryChatPreview(String)
+ CompletableFuture queryCommandPreview(String)
+ CompletableFuture queryPreview(String)
+ Component lambda$queryChatPreview$16(Component,Component)
+ Map collectSignedArguments(ServerboundChatCommandPacket,PreviewableCommand)
- Map collectSignedArguments(ServerboundChatCommandPacket,SignableCommand,LastSeenMessages)
- Optional tryHandleChat(String,Instant,LastSeenMessages$Update)
- Optional unpackAndApplyLastSeen(LastSeenMessages$Update)
+ Packet lambda$sendPreviewResponse$15(int)
- PlayerChatMessage getSignedMessage(ServerboundChatPacket,LastSeenMessages)
+ PlayerChatMessage getSignedMessage(ServerboundChatPacket)
+ SignedMessageChain$Decoder signedMessageDecoder()
+ void handleChatPreview(ServerboundChatPreviewPacket)
- void handleMessageDecodeFailure(SignedMessageChain$DecodeException)
+ void handleValidationFailure(Set)
- void lambda$handleChat$10(ServerboundChatPacket,Optional)
+ void lambda$handleChat$10(ServerboundChatPacket)
+ void lambda$handleChat$8(CompletableFuture,CompletableFuture,Void)
- void lambda$handleChat$8(PlayerChatMessage,CompletableFuture,CompletableFuture,Void)
- void lambda$handleChatCommand$11(ServerboundChatCommandPacket,Optional)
+ void lambda$handleChatCommand$11(ServerboundChatCommandPacket)
+ void lambda$handleChatPreview$13(int,Component)
- void lambda$handlePlaceRecipe$13(ServerboundPlaceRecipePacket,Recipe)
+ void lambda$handlePlaceRecipe$19(ServerboundPlaceRecipePacket,Recipe)
- void lambda$handleSignUpdate$14(ServerboundSignUpdatePacket,List)
+ void lambda$handleSignUpdate$20(ServerboundSignUpdatePacket,List)
+ void lambda$queryChatPreview$17(String,Component)
+ void lambda$queryCommandPreview$18(String,Component)
- void performChatCommand(ServerboundChatCommandPacket,LastSeenMessages)
+ void performChatCommand(ServerboundChatCommandPacket)
- void sendDisguisedChatMessage(Component,ChatType$Bound)
- void sendPlayerChatMessage(PlayerChatMessage,ChatType$Bound)
+ void sendPreviewResponse(int,Component)
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerLoginPacketListenerImpl
</summary>

```diff
+ ProfilePublicKey validatePublicKey(ProfilePublicKey$Data,UUID,SignatureValidator,boolean)
- RemoteChatSession validateChatSession(RemoteChatSession$Data,GameProfile,SignatureValidator,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.packs.FilePackResources
</summary>

```diff
+ boolean hasResource(String)
+ Collection getResources(PackType,String,String,Predicate)
+ InputStream getResource(String)
- IoSupplier getResource(PackType,ResourceLocation)
- IoSupplier getResource(String)
- IoSupplier getRootResource(String[])
- String getPathFromLocation(PackType,ResourceLocation)
+ void <init>(File)
- void <init>(String,File)
- void listResources(PackType,String,String,PackResources$ResourceOutput)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.FolderRepositorySource
</summary>

```diff
+ boolean lambda$static$0(File)
- Pack$ResourcesSupplier detectPackResources(Path)
+ PackResources lambda$createSupplier$1(File)
+ PackResources lambda$createSupplier$2(File)
- PackResources lambda$detectPackResources$1(Path,String)
- PackResources lambda$detectPackResources$2(File,String)
- String nameFromPath(Path)
+ Supplier createSupplier(File)
+ void <init>(File,PackSource)
- void <init>(Path,PackType,PackSource)
- void discoverPacks(Path,BiConsumer)
- void lambda$loadPacks$0(Consumer,Path,Pack$ResourcesSupplier)
+ void loadPacks(Consumer,Pack$PackConstructor)
- void loadPacks(Consumer)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.ServerPacksSource
</summary>

```diff
- Component getPackTitle(String)
- Pack createBuiltinPack(String,Pack$ResourcesSupplier,Component)
- Pack createVanillaPack(PackResources)
- PackRepository createPackRepository(LevelStorageSource$LevelStorageAccess)
- PackRepository createPackRepository(Path)
- PackResources lambda$createVanillaPack$0(PackResources,String)
+ PackResources lambda$loadPacks$0()
- VanillaPackResources createVanillaPackSource()
+ void loadPacks(Consumer,Pack$PackConstructor)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.MultiPackResourceManager
</summary>

```diff
- void checkTrailingDirectoryPath(String)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceProvider
</summary>

```diff
- Optional lambda$fromMap$1(Map,ResourceLocation)
- ResourceProvider fromMap(Map)
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ boolean verifyChatTrusted(PlayerChatMessage,ChatSender)
- boolean verifyChatTrusted(PlayerChatMessage)
+ ServerPlayer getPlayerForLogin(GameProfile,ProfilePublicKey)
- ServerPlayer getPlayerForLogin(GameProfile,RemoteChatSession)
- void <init>(MinecraftServer,LayeredRegistryAccess,PlayerDataStorage,int)
+ void <init>(MinecraftServer,RegistryAccess$Frozen,PlayerDataStorage,int)
+ void broadcastChatMessage(PlayerChatMessage,Predicate,ServerPlayer,ChatSender,ChatType$Bound)
- void broadcastChatMessage(PlayerChatMessage,Predicate,ServerPlayer,ChatType$Bound)
+ void broadcastMessageHeader(PlayerChatMessage,Set)
```

</details>
<details>
<summary>
net.minecraft.tags.TagNetworkSerialization
</summary>

```diff
- Map serializeTagsToNetwork(LayeredRegistryAccess)
+ Map serializeTagsToNetwork(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.util.FutureChain
</summary>

```diff
+ CompletionStage lambda$append$0(TaskChainer$DelayedTask,Object)
- CompletionStage lambda$append$1(TaskChainer$DelayedTask,Object)
+ Object lambda$append$1(Throwable)
- Object lambda$append$2(Throwable)
- void close()
- void lambda$new$0(Executor,Runnable)
```

</details>
<details>
<summary>
net.minecraft.world.entity.AnimationState
</summary>

```diff
- void animateWhen(boolean,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean allowsDismounting(Entity)
+ ChatSender asChatSender()
- Packet getAddEntityPacket()
- Vec3 getLeashOffset(float)
- void addDeltaMovement(Vec3)
- void checkSlowFallDistance()
- void teleportRelative(double,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean equipmentHasChanged(ItemStack,ItemStack)
- double getAttributeBaseValue(Holder)
- double getAttributeValue(Holder)
+ Packet getAddEntityPacket()
```

</details>
<details>
<summary>
net.minecraft.world.entity.PlayerRideableJumping
</summary>

```diff
- int getJumpCooldown()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Saddleable
</summary>

```diff
- SoundEvent getSaddleSoundEvent()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeMap
</summary>

```diff
- AttributeInstance getInstance(Holder)
- boolean hasAttribute(Holder)
- boolean hasModifier(Holder,UUID)
- double getModifierValue(Holder,UUID)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.BlockPosTracker
</summary>

```diff
- void <init>(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
</summary>

```diff
- boolean defaultAcceptableLandingSpot(Mob,BlockPos)
- boolean isClearTransition(Mob,EntityDimensions,Vec3,Vec3)
+ boolean isClearTransition(Mob,Vec3,Vec3)
+ boolean lambda$new$0(BlockState)
- boolean lambda$start$0(BlockPos,BlockPos)
+ boolean lambda$start$1(BlockPos,BlockPos)
- LongJumpToRandomPos$PossibleJump lambda$start$1(BlockPos,BlockPos)
+ LongJumpToRandomPos$PossibleJump lambda$start$2(BlockPos,BlockPos)
- void <init>(UniformInt,int,int,float,Function,BiPredicate)
+ void <init>(UniformInt,int,int,float,Function,Predicate)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.TemptingSensor
</summary>

```diff
- boolean lambda$doTick$2(PathfinderMob,ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiTypes
</summary>

```diff
- void registerBlockStates(Holder,Set)
+ void registerBlockStates(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmeltingRecipe
</summary>

```diff
- void <init>(ResourceLocation,String,CookingBookCategory,Ingredient,ItemStack,float,int)
+ void <init>(ResourceLocation,String,Ingredient,ItemStack,float,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.TippedArrowRecipe
</summary>

```diff
- void <init>(ResourceLocation,CraftingBookCategory)
+ void <init>(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelReader
</summary>

```diff
- HolderLookup holderLookup(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.level.StructureManager
</summary>

```diff
+ Boolean lambda$getStructureWithPieceAt$0(TagKey,Holder)
- Boolean lambda$getStructureWithPieceAt$0(TagKey,Holder$Reference)
+ void <init>(LevelAccessor,WorldGenSettings,StructureCheck)
- void <init>(LevelAccessor,WorldOptions,StructureCheck)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SupportType$2
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TrapDoorBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,SoundEvent,SoundEvent)
+ void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
+ GameEventDispatcher getEventDispatcher(int)
- GameEventListenerRegistry getListenerRegistry(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
- boolean hasBiomesForStructureSet(StructureSet)
+ boolean lambda$getMobsAt$15(StructureManager,BlockPos,StructureStart)
+ boolean lambda$getMobsAt$16(BlockPos,StructureStart)
- boolean lambda$getMobsAt$20(StructureManager,BlockPos,StructureStart)
- boolean lambda$getMobsAt$21(BlockPos,StructureStart)
- boolean lambda$new$3(Holder)
- ChunkAccess lambda$createBiomes$12(ChunkAccess,RandomState)
+ ChunkAccess lambda$createBiomes$7(ChunkAccess,RandomState)
- ChunkPos lambda$generateRingPositions$10(int,int,HolderSet,RandomSource,RandomState)
- Integer lambda$applyBiomeDecoration$14(Structure)
+ Integer lambda$applyBiomeDecoration$9(Structure)
+ List lambda$generatePositions$4(Structure)
- List lambda$generatePositions$8(Structure)
- List lambda$generateRingPositions$11(Stopwatch,Holder,List)
+ List lambda$generateRingPositions$6(ConcentricRingsStructurePlacement,RandomState,Holder)
+ List lambda$new$2(Function,Holder)
+ List lambda$new$3(BiomeSource,Function)
- List lambda$new$4(Optional,Registry)
- List lambda$new$5(Function,Holder)
- List lambda$new$6(BiomeSource,Function)
- List possibleStructureSets()
- Set lambda$findNearestMapStructure$13(StructurePlacement)
+ Set lambda$findNearestMapStructure$8(StructurePlacement)
- Stream lambda$hasBiomesForStructureSet$7(StructureSet$StructureSelectionEntry)
- Stream lambda$new$2(Registry)
+ Stream possibleStructureSets()
+ String lambda$applyBiomeDecoration$11(Registry,Structure)
+ String lambda$applyBiomeDecoration$14(Registry,PlacedFeature)
- String lambda$applyBiomeDecoration$16(Registry,Structure)
- String lambda$applyBiomeDecoration$19(Registry,PlacedFeature)
+ String lambda$createReferences$19(StructureStart,Registry)
+ String lambda$createReferences$20(Optional,StructureStart)
+ String lambda$createReferences$21(StructureStart)
+ String lambda$createReferences$22(StructureStart)
- String lambda$createReferences$24(StructureStart,Registry)
- String lambda$createReferences$25(Optional,StructureStart)
- String lambda$createReferences$26(StructureStart)
- String lambda$createReferences$27(StructureStart)
+ void lambda$applyBiomeDecoration$10(WorldGenLevel,Set,ChunkPos)
+ void lambda$applyBiomeDecoration$12(WorldGenLevel,StructureManager,WorldgenRandom,ChunkAccess,ChunkPos,StructureStart)
+ void lambda$applyBiomeDecoration$13(IntSet,FeatureSorter$StepFeatureData,PlacedFeature)
- void lambda$applyBiomeDecoration$15(WorldGenLevel,Set,ChunkPos)
- void lambda$applyBiomeDecoration$17(WorldGenLevel,StructureManager,WorldgenRandom,ChunkAccess,ChunkPos,StructureStart)
- void lambda$applyBiomeDecoration$18(IntSet,FeatureSorter$StepFeatureData,PlacedFeature)
+ void lambda$createStructures$18(StructureManager,SectionPos,ChunkAccess,RandomState,long,ChunkPos,RegistryAccess,StructureTemplateManager,Holder)
- void lambda$createStructures$23(StructureManager,SectionPos,ChunkAccess,RandomState,long,ChunkPos,RegistryAccess,StructureTemplateManager,Holder)
+ void lambda$generatePositions$5(Set,RandomState,Holder)
- void lambda$generatePositions$9(Set,RandomState,Holder)
+ void lambda$getMobsAt$17(MutableBoolean,Predicate,StructureStart)
- void lambda$getMobsAt$22(MutableBoolean,Predicate,StructureStart)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.GameEventDispatcher
</summary>

```diff
+ void <clinit>()
- void <init>(ServerLevel)
- void handleGameEventMessagesInQueue(List)
- void lambda$post$0(List,GameEvent,Vec3,GameEvent$Context,GameEventListener,Vec3)
- void post(GameEvent,Vec3,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationListener
</summary>

```diff
- boolean handleGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
+ boolean handleGameEvent(ServerLevel,GameEvent$Message)
- boolean lambda$isOccluded$10(BlockState)
+ boolean lambda$isOccluded$7(BlockState)
+ Float lambda$codec$3(VibrationListener)
- int getGameEventFrequency(GameEvent)
+ VibrationListener lambda$codec$5(VibrationListener$VibrationListenerConfig,PositionSource,Integer,Optional,Float,Integer)
- VibrationListener lambda$codec$5(VibrationListener$VibrationListenerConfig,PositionSource,Integer,Optional,VibrationSelector,Integer)
- VibrationSelector lambda$codec$3(VibrationListener)
- void <clinit>()
- void <init>(PositionSource,int,VibrationListener$VibrationListenerConfig,VibrationInfo,VibrationSelector,int)
+ void <init>(PositionSource,int,VibrationListener$VibrationListenerConfig,VibrationListener$ReceivingEvent,float,int)
- void <init>(PositionSource,int,VibrationListener$VibrationListenerConfig)
- void forceGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- void lambda$forceGameEvent$9(ServerLevel,GameEvent,GameEvent$Context,Vec3,Vec3)
- void lambda$static$7(Object2IntOpenHashMap)
- void lambda$tick$8(ServerLevel,VibrationInfo)
+ void scheduleSignal(ServerLevel,GameEvent,GameEvent$Context,Vec3,Vec3)
- void scheduleVibration(ServerLevel,GameEvent,GameEvent$Context,Vec3,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPreset
</summary>

```diff
+ IllegalStateException lambda$overworldOrThrow$3()
+ LevelStem overworldOrThrow()
- WorldDimensions createWorldDimensions()
+ WorldGenSettings createWorldGenSettings(long,boolean,boolean)
+ WorldGenSettings recreateWorldGenSettings(WorldGenSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootTable
</summary>

```diff
+ Consumer createStackSplitter(Consumer)
- Consumer createStackSplitter(LootContext,Consumer)
+ void lambda$createStackSplitter$0(Consumer,ItemStack)
- void lambda$createStackSplitter$0(LootContext,Consumer,ItemStack)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- XXX.advancements.packs.VanillaAdventureAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
- XXX.ai.behavior.package-info
- XXX.ai.behavior.RandomLookAround
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.RandomSwim
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunIf
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.RunSometimes
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFrom
- XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ XXX.ai.behavior.SetWalkTargetFromBlockMemory
- XXX.ai.behavior.SetWalkTargetFromLookTarget
+ XXX.ai.behavior.ShowTradesToPlayer
- XXX.ai.behavior.ShufflingList
+ XXX.ai.behavior.ShufflingList$WeightedEntry
- XXX.ai.behavior.ShufflingList$WeightedEntry$1
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StayCloseToTarget
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.TryFindLand
- XXX.ai.behavior.TryFindLandNearWater
+ XXX.ai.behavior.TryFindWater
- XXX.ai.behavior.TryLaySpawnOnWaterNearLand
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerMakeLove
+ XXX.ai.behavior.VillagerPanicTrigger
- XXX.ai.behavior.WakeUp
+ XXX.ai.behavior.WorkAtComposter
- XXX.ai.behavior.WorkAtPoi
+ XXX.ai.behavior.YieldJobSite
+ XXX.ai.control.BodyRotationControl
- XXX.ai.control.Control
+ XXX.ai.control.FlyingMoveControl
- XXX.ai.control.JumpControl
+ XXX.ai.control.LookControl
- XXX.ai.control.MoveControl
+ XXX.ai.control.MoveControl$Operation
- XXX.ai.control.package-info
- XXX.ai.control.SmoothSwimmingLookControl
+ XXX.ai.control.SmoothSwimmingMoveControl
+ XXX.ai.goal.AvoidEntityGoal
- XXX.ai.goal.BegGoal
+ XXX.ai.goal.BoatGoals
- XXX.ai.goal.BreakDoorGoal
+ XXX.ai.goal.BreathAirGoal
- XXX.ai.goal.BreedGoal
+ XXX.ai.goal.CatLieOnBedGoal
- XXX.ai.goal.CatSitOnBlockGoal
+ XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
- XXX.ai.goal.DolphinJumpGoal
+ XXX.ai.goal.DoorInteractGoal
- XXX.ai.goal.EatBlockGoal
+ XXX.ai.goal.FleeSunGoal
- XXX.ai.goal.FloatGoal
+ XXX.ai.goal.FollowBoatGoal
- XXX.ai.goal.FollowFlockLeaderGoal
+ XXX.ai.goal.FollowMobGoal
- XXX.ai.goal.FollowOwnerGoal
+ XXX.ai.goal.FollowParentGoal
- XXX.ai.goal.Goal
+ XXX.ai.goal.Goal$Flag
- XXX.ai.goal.GoalSelector
+ XXX.ai.goal.GoalSelector$1
- XXX.ai.goal.GoalSelector$2
+ XXX.ai.goal.GolemRandomStrollInVillageGoal
- XXX.ai.goal.InteractGoal
+ XXX.ai.goal.JumpGoal
- XXX.ai.goal.LandOnOwnersShoulderGoal
+ XXX.ai.goal.LeapAtTargetGoal
- XXX.ai.goal.LlamaFollowCaravanGoal
+ XXX.ai.goal.LookAtPlayerGoal
- XXX.ai.goal.LookAtTradingPlayerGoal
+ XXX.ai.goal.MeleeAttackGoal
- XXX.ai.goal.MoveBackToVillageGoal
+ XXX.ai.goal.MoveThroughVillageGoal
- XXX.ai.goal.MoveToBlockGoal
+ XXX.ai.goal.MoveTowardsRestrictionGoal
- XXX.ai.goal.MoveTowardsTargetGoal
+ XXX.ai.goal.OcelotAttackGoal
- XXX.ai.goal.OfferFlowerGoal
+ XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.PanicGoal
+ XXX.ai.goal.PathfindToRaidGoal
- XXX.ai.goal.RandomLookAroundGoal
- XXX.animal.camel.Camel$1
- XXX.animal.camel.CamelAi
- XXX.animal.camel.CamelAi$RandomSitting
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
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Markings
- XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.Variant
- XXX.animal.horse.ZombieHorse
- XXX.animation.definitions.CamelAnimation
+ XXX.behavior.warden.Digging
- XXX.behavior.warden.Emerging
+ XXX.behavior.warden.ForceUnmount
- XXX.behavior.warden.package-info
- XXX.behavior.warden.Roar
+ XXX.behavior.warden.SetRoarTarget
- XXX.behavior.warden.SetWardenLookTarget
+ XXX.behavior.warden.Sniffing
- XXX.behavior.warden.SonicBoom
+ XXX.behavior.warden.TryToSniff
+ XXX.blaze3d.platform.PngInfo
+ XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
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
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.SculkShriekerBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
- XXX.block.grower.AbstractMegaTreeGrower
+ XXX.block.grower.AbstractTreeGrower
- XXX.block.grower.AcaciaTreeGrower
+ XXX.block.grower.AzaleaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.MangroveTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
+ XXX.block.model.BakedQuad
- XXX.block.model.BlockElement
+ XXX.block.model.BlockElement$1
- XXX.block.model.BlockElement$Deserializer
+ XXX.block.model.BlockElementFace
- XXX.block.model.BlockElementFace$Deserializer
+ XXX.block.model.BlockElementRotation
- XXX.block.model.BlockFaceUV
+ XXX.block.model.BlockFaceUV$Deserializer
- XXX.block.model.BlockModel
+ XXX.block.model.BlockModel$Deserializer
- XXX.block.model.BlockModel$GuiLight
+ XXX.block.model.BlockModel$LoopException
- XXX.block.model.BlockModelDefinition
+ XXX.block.model.BlockModelDefinition$Context
- XXX.block.model.BlockModelDefinition$Deserializer
+ XXX.block.model.BlockModelDefinition$MissingVariantException
- XXX.block.model.FaceBakery
+ XXX.block.model.FaceBakery$1
- XXX.block.model.ItemModelGenerator
+ XXX.block.model.ItemModelGenerator$1
- XXX.block.model.ItemModelGenerator$Span
+ XXX.block.model.ItemModelGenerator$SpanFacing
- XXX.block.model.ItemOverride
+ XXX.block.model.ItemOverride$Deserializer
- XXX.block.model.ItemOverride$Predicate
+ XXX.block.model.ItemOverrides
- XXX.block.model.ItemOverrides$BakedOverride
+ XXX.block.model.ItemOverrides$PropertyMatcher
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.ItemTransforms$TransformType
- XXX.block.model.MultiVariant
+ XXX.block.model.MultiVariant$Deserializer
+ XXX.block.model.package-info
- XXX.block.model.Variant
+ XXX.block.model.Variant$Deserializer
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
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
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chat.report.ChatReportBuilder$ReferencedMessageVisitor
- XXX.chat.report.ChatReportBuilder$Result
- XXX.chat.report.ChatReportContextBuilder$Collector
+ XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolation
+ XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Target
+ XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition
+ XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.Keyframe
+ XXX.client.animation.KeyframeAnimations
- XXX.client.gui.package-info
- XXX.client.main.GameConfig
+ XXX.client.main.GameConfig$FolderData
- XXX.client.main.GameConfig$GameData
+ XXX.client.main.GameConfig$ServerData
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
- XXX.client.main.Main$3
- XXX.client.main.package-info
+ XXX.client.main.SilentInitException
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AgeableListModel
+ XXX.client.model.AllayModel
- XXX.client.model.AnimationUtils
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.AxolotlModel
+ XXX.client.model.BatModel
- XXX.client.model.BeeModel
+ XXX.client.model.BlazeModel
- XXX.client.model.BoatModel
+ XXX.client.model.BookModel
- XXX.client.model.CamelModel
- XXX.client.model.ChestBoatModel
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
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.ClientSuggestionProvider$1
- XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ProfileKeyPairManager
+ XXX.client.multiplayer.ProfileKeyPairManager$Result
+ XXX.client.multiplayer.ServerData$ChatPreview
- XXX.client.multiplayer.ServerData$ServerPackStatus
+ XXX.client.multiplayer.ServerList
- XXX.client.multiplayer.ServerStatusPinger
+ XXX.client.multiplayer.ServerStatusPinger$1
- XXX.client.multiplayer.ServerStatusPinger$2
+ XXX.client.multiplayer.ServerStatusPinger$2$1
- XXX.client.particle.package-info
- XXX.client.particle.ParticleEngine$MutableSpriteSet
+ XXX.client.particle.ParticleEngine$SpriteParticleRegistration
- XXX.client.particle.ParticleProvider
+ XXX.client.particle.ParticleRenderType
- XXX.client.particle.ParticleRenderType$1
+ XXX.client.particle.ParticleRenderType$2
- XXX.client.particle.ParticleRenderType$3
+ XXX.client.particle.ParticleRenderType$4
- XXX.client.particle.ParticleRenderType$5
+ XXX.client.particle.ParticleRenderType$6
- XXX.client.particle.PlayerCloudParticle
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$Provider
+ XXX.client.particle.ReversePortalParticle
- XXX.client.particle.ReversePortalParticle$ReversePortalProvider
+ XXX.client.particle.RisingParticle
- XXX.client.particle.SculkChargeParticle
+ XXX.client.particle.SculkChargeParticle$Provider
- XXX.client.particle.SculkChargePopParticle
+ XXX.client.particle.SculkChargePopParticle$Provider
- XXX.client.particle.ShriekParticle
+ XXX.client.particle.ShriekParticle$Provider
- XXX.client.particle.SimpleAnimatedParticle
+ XXX.client.particle.SingleQuadParticle
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
- XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ XXX.client.particle.SuspendedTownParticle$Provider
- XXX.client.particle.TerrainParticle
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$Provider
+ XXX.client.particle.TrackingEmitter
- XXX.client.particle.VibrationSignalParticle
+ XXX.client.particle.VibrationSignalParticle$Provider
- XXX.client.particle.WakeParticle
+ XXX.client.particle.WakeParticle$Provider
- XXX.client.particle.WaterCurrentDownParticle
+ XXX.client.particle.WaterCurrentDownParticle$Provider
- XXX.client.particle.WaterDropParticle
+ XXX.client.particle.WaterDropParticle$Provider
- XXX.client.particle.WhiteAshParticle
+ XXX.client.particle.WhiteAshParticle$Provider
+ XXX.client.player.AbstractClientPlayer
- XXX.client.player.Input
+ XXX.client.player.KeyboardInput
- XXX.client.player.LocalPlayer
- XXX.client.player.package-info
+ XXX.client.player.RemotePlayer
+ XXX.client.profiling.ClientMetricsSamplersProvider
- XXX.client.profiling.package-info
+ XXX.client.renderer.BiomeColors
- XXX.client.renderer.BlockEntityWithoutLevelRenderer
+ XXX.client.renderer.ChunkBufferBuilderPack
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.DimensionSpecialEffects
- XXX.client.renderer.DimensionSpecialEffects$EndEffects
+ XXX.client.renderer.DimensionSpecialEffects$NetherEffects
- XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
+ XXX.client.renderer.DimensionSpecialEffects$SkyType
- XXX.client.renderer.EffectInstance
+ XXX.client.renderer.FaceInfo
- XXX.client.renderer.FaceInfo$Constants
+ XXX.client.renderer.FaceInfo$VertexInfo
- XXX.client.renderer.FogRenderer
+ XXX.client.renderer.FogRenderer$BlindnessFogFunction
- XXX.client.renderer.FogRenderer$DarknessFogFunction
+ XXX.client.renderer.FogRenderer$FogData
- XXX.client.renderer.FogRenderer$FogMode
+ XXX.client.renderer.FogRenderer$MobEffectFogFunction
- XXX.client.renderer.GameRenderer
- XXX.client.renderer.GameRenderer$ResourceCache
+ XXX.client.renderer.GpuWarnlistManager
- XXX.client.renderer.GpuWarnlistManager$Preparations
+ XXX.client.renderer.ItemBlockRenderTypes
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
+ XXX.client.renderer.ItemModelShaper
- XXX.client.renderer.LevelRenderer
+ XXX.client.renderer.LevelRenderer$RenderChunkInfo
- XXX.client.renderer.LevelRenderer$RenderChunkStorage
+ XXX.client.renderer.LevelRenderer$RenderInfoMap
- XXX.client.renderer.LevelRenderer$TransparencyShaderException
+ XXX.client.renderer.LightTexture
- XXX.client.renderer.MultiBufferSource
+ XXX.client.renderer.MultiBufferSource$BufferSource
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$BooleanStateShard
+ XXX.client.renderer.RenderStateShard$CullStateShard
- XXX.client.renderer.RenderStateShard$DepthTestStateShard
+ XXX.client.renderer.RenderStateShard$EmptyTextureStateShard
- XXX.client.renderer.RenderStateShard$LayeringStateShard
+ XXX.client.renderer.RenderStateShard$LightmapStateShard
- XXX.client.renderer.RenderStateShard$LineStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
+ XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
- XXX.client.renderer.RenderStateShard$OutputStateShard
+ XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$ShaderStateShard
+ XXX.client.renderer.RenderStateShard$TextureStateShard
- XXX.client.renderer.RenderStateShard$TexturingStateShard
+ XXX.client.renderer.RenderStateShard$TransparencyStateShard
- XXX.client.renderer.RenderStateShard$WriteMaskStateShard
+ XXX.client.renderer.RenderType
- XXX.client.renderer.RenderType$CompositeRenderType
+ XXX.client.renderer.RenderType$CompositeState
- XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ XXX.client.renderer.RenderType$OutlineProperty
- XXX.client.renderer.RunningTrimmedMean
+ XXX.client.renderer.ScreenEffectRenderer
- XXX.client.renderer.ShaderInstance
+ XXX.client.renderer.ShaderInstance$1
- XXX.client.renderer.Sheets
+ XXX.client.renderer.Sheets$1
- XXX.client.renderer.SpriteCoordinateExpander
+ XXX.client.renderer.ViewArea
- XXX.client.renderer.VirtualScreen
+ XXX.client.resources.ClientPackSource$2
+ XXX.client.resources.DefaultPlayerSkin
- XXX.client.resources.DownloadedPackSource
+ XXX.client.resources.FoliageColorReloadListener
- XXX.client.resources.GrassColorReloadListener
+ XXX.client.resources.LegacyPackResourcesAdapter
- XXX.client.resources.LegacyStuffWrapper
+ XXX.client.resources.MobEffectTextureManager
+ XXX.commands.arguments.EntitySummonArgument
- XXX.commands.arguments.GameProfileArgument
+ XXX.commands.arguments.GameProfileArgument$Result
- XXX.commands.arguments.GameProfileArgument$SelectorResult
+ XXX.commands.arguments.ItemEnchantmentArgument
+ XXX.commands.arguments.MessageArgument$ChatMessage
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
+ XXX.commands.arguments.PreviewedArgument
- XXX.commands.arguments.RangeArgument
+ XXX.commands.arguments.RangeArgument$Floats
- XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceArgument$Info
- XXX.commands.arguments.ResourceOrTagArgument
- XXX.commands.arguments.ResourceOrTagArgument$Info$Template
- XXX.commands.arguments.ResourceOrTagArgument$Result
- XXX.commands.arguments.ResourceOrTagKeyArgument
- XXX.commands.arguments.ResourceOrTagKeyArgument$Info$Template
- XXX.commands.arguments.ResourceOrTagKeyArgument$Result
+ XXX.commands.arguments.ResourceOrTagLocationArgument
+ XXX.commands.arguments.ResourceOrTagLocationArgument$Info$Template
+ XXX.commands.arguments.ResourceOrTagLocationArgument$Result
- XXX.core.cauldron.CauldronInteraction
+ XXX.core.cauldron.package-info
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
+ XXX.core.dispenser.DispenseItemBehavior$25
- XXX.core.dispenser.DispenseItemBehavior$26
+ XXX.core.dispenser.DispenseItemBehavior$27
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
- XXX.core.dispenser.package-info
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.BlockParticleOption$1
- XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustColorTransitionOptions$1
- XXX.core.particles.DustParticleOptions
+ XXX.core.particles.DustParticleOptions$1
- XXX.core.particles.DustParticleOptionsBase
+ XXX.core.particles.ItemParticleOption
- XXX.core.particles.ItemParticleOption$1
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleGroup
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleOptions$Deserializer
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
+ XXX.core.particles.SculkChargeParticleOptions
- XXX.core.particles.SculkChargeParticleOptions$1
+ XXX.core.particles.ShriekParticleOption
- XXX.core.particles.ShriekParticleOption$1
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
+ XXX.core.particles.VibrationParticleOption
- XXX.core.particles.VibrationParticleOption$1
+ XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.StoryAdvancements
- XXX.data.info.BiomeParametersDumpReport
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.ChestLoot
- XXX.data.loot.EntityLootSubProvider
+ XXX.data.loot.FishingLoot
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableProvider$SubProviderEntry
- XXX.data.metadata.package-info
- XXX.data.recipes.CraftingRecipeBuilder
- XXX.data.recipes.CraftingRecipeBuilder$CraftingResult
+ XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.RecipeBuilder
+ XXX.data.tags.CatVariantTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.InstrumentTagsProvider
+ XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.UpdateOneTwentyItemTagsProvider
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
- XXX.data.worldgen.BuiltinRegistriesDatapackGenerator
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenameBiomesFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.SavedDataVillageCropFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimpleRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ XXX.datafix.fixes.StructureSettingsFlattenFix
- XXX.datafix.fixes.TeamDisplayNameFix
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
+ XXX.datafix.schemas.V1451_7
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
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
- XXX.datafix.schemas.V3203
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
- XXX.entity.animal.package-info
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
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
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
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.Ravager$RavagerNavigation
- XXX.entity.monster.Ravager$RavagerNodeEvaluator
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
- XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
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
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
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
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
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
- XXX.entity.vehicle.package-info
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
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
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
+ XXX.feature.rootplacers.RootPlacer
- XXX.feature.rootplacers.RootPlacerType
+ XXX.font.providers.package-info
- XXX.font.providers.TrueTypeGlyphProviderBuilder
+ XXX.gameevent.vibrations.VibrationListener$VibrationListenerConfig
- XXX.gameevent.vibrations.VibrationSelector
- XXX.gametest.framework.GameTestHelper$2
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
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
- XXX.gametest.framework.package-info
- XXX.gametest.framework.ReportGameListener
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
+ XXX.gui.chat.ChatPreviewAnimator
+ XXX.gui.chat.ChatPreviewRequests
+ XXX.gui.chat.ChatPreviewRequests$QueryIdGenerator
+ XXX.gui.chat.ClientChatPreview$Preview
- XXX.gui.components.Checkbox
+ XXX.gui.components.CommandSuggestions
- XXX.gui.components.CommandSuggestions$SuggestionsList
+ XXX.gui.components.ComponentRenderUtils
- XXX.gui.components.ContainerObjectSelectionList
+ XXX.gui.components.ContainerObjectSelectionList$Entry
- XXX.gui.components.CycleButton
+ XXX.gui.components.CycleButton$Builder
- XXX.gui.components.CycleButton$OnValueChange
+ XXX.gui.components.CycleButton$ValueListSupplier
- XXX.gui.components.CycleButton$ValueListSupplier$1
+ XXX.gui.components.CycleButton$ValueListSupplier$2
- XXX.gui.components.DebugScreenOverlay
+ XXX.gui.components.DebugScreenOverlay$1
- XXX.gui.components.DebugScreenOverlay$AllocationRateCalculator
+ XXX.gui.components.EditBox
- XXX.gui.components.ImageButton
+ XXX.gui.components.LerpingBossEvent
- XXX.gui.components.LockIconButton
+ XXX.gui.components.LockIconButton$Icon
- XXX.gui.components.MultiLineEditBox
+ XXX.gui.components.MultiLineLabel
- XXX.gui.components.MultiLineLabel$1
+ XXX.gui.components.MultiLineLabel$2
- XXX.gui.components.MultiLineLabel$TextWithWidth
+ XXX.gui.components.MultilineTextField
- XXX.gui.components.MultilineTextField$1
+ XXX.gui.components.MultilineTextField$StringView
- XXX.gui.components.ObjectSelectionList
+ XXX.gui.components.ObjectSelectionList$Entry
- XXX.gui.components.OptionsList
+ XXX.gui.components.OptionsList$Entry
- XXX.gui.components.PlainTextButton
+ XXX.gui.components.PlayerFaceRenderer
- XXX.gui.components.PlayerTabOverlay
+ XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
- XXX.gui.components.StateSwitchingButton
+ XXX.gui.components.SubtitleOverlay
- XXX.gui.components.SubtitleOverlay$Subtitle
+ XXX.gui.components.TooltipAccessor
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
+ XXX.gui.screens.AccessibilityOptionsScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.BanNoticeScreen
- XXX.gui.screens.ChatOptionsScreen
+ XXX.gui.screens.ChatScreen
- XXX.gui.screens.ChatScreen$1
+ XXX.gui.screens.ConfirmLinkScreen
- XXX.gui.screens.ConfirmScreen
+ XXX.gui.screens.ConnectScreen
- XXX.gui.screens.ConnectScreen$1
+ XXX.gui.screens.CreateBuffetWorldScreen
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ XXX.gui.screens.DatapackLoadFailureScreen
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DemoIntroScreen
- XXX.gui.screens.DirectJoinServerScreen
+ XXX.gui.screens.DisconnectedScreen
- XXX.gui.screens.EditServerScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.GenericDirtMessageScreen
+ XXX.gui.screens.GenericWaitingScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingDotsText
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.MouseSettingsScreen
+ XXX.gui.screens.OnlineOptionsScreen
- XXX.gui.screens.OptionsScreen
+ XXX.gui.screens.OptionsSubScreen
- XXX.gui.screens.OutOfMemoryScreen
+ XXX.gui.screens.Overlay
- XXX.gui.screens.PauseScreen
+ XXX.gui.screens.PopupScreen
- XXX.gui.screens.PopupScreen$ButtonOption
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$NarratableSearchResult
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SimpleOptionsSubScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.TitleScreen$1
- XXX.gui.screens.TitleScreen$WarningLabel
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
+ XXX.gui.screens.WinScreen$CreditsReader
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
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.ClientBundleTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip$Texture
- XXX.inventory.tooltip.ClientTextTooltip
+ XXX.inventory.tooltip.ClientTooltipComponent
- XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$TagValue
- XXX.item.crafting.Ingredient$Value
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeManager$1
- XXX.item.crafting.RecipeManager$CachedCheck
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.ShulkerBoxColoring
+ XXX.item.crafting.SimpleCookingSerializer
- XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ XXX.item.crafting.SimpleRecipeSerializer
+ XXX.level.biome.AmbientAdditionsSettings
- XXX.level.biome.AmbientMoodSettings
+ XXX.level.biome.AmbientParticleSettings
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$ClimateSettings
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$TemperatureModifier
- XXX.level.biome.Biome$TemperatureModifier$1
+ XXX.level.biome.Biome$TemperatureModifier$2
- XXX.level.biome.BiomeGenerationSettings
+ XXX.level.biome.BiomeGenerationSettings$Builder
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
+ XXX.level.biome.MultiNoiseBiomeSource$Preset
- XXX.level.biome.MultiNoiseBiomeSource$PresetInstance
+ XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.package-info
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCandleBlock
- XXX.level.block.AbstractCauldronBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AmethystBlock
+ XXX.level.block.AmethystClusterBlock
- XXX.level.block.AmethystClusterBlock$1
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.AzaleaBlock
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
+ XXX.level.block.BaseRailBlock$1
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
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CampfireBlock
- XXX.level.block.CandleBlock
+ XXX.level.block.CandleCakeBlock
- XXX.level.block.CarpetBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.CaveVines
- XXX.level.block.CaveVinesBlock
+ XXX.level.block.CaveVinesPlantBlock
- XXX.level.block.CeilingHangingSignBlock
- XXX.level.block.ChiseledBookShelfBlock
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
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.Fallable
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FletchingTableBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrogspawnBlock
- XXX.level.block.FrostedIceBlock
+ XXX.level.block.FungusBlock
- XXX.level.block.FurnaceBlock
+ XXX.level.block.GameMasterBlock
- XXX.level.block.GlassBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GlowLichenBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GravelBlock
+ XXX.level.block.GrindstoneBlock
- XXX.level.block.GrindstoneBlock$1
+ XXX.level.block.GrowingPlantBlock
- XXX.level.block.GrowingPlantBodyBlock
+ XXX.level.block.GrowingPlantHeadBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HangingRootsBlock
- XXX.level.block.HayBlock
+ XXX.level.block.HoneyBlock
- XXX.level.block.HopperBlock
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
- XXX.level.block.LanternBlock
+ XXX.level.block.LavaCauldronBlock
- XXX.level.block.LayeredCauldronBlock
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LeverBlock$1
+ XXX.level.block.LightBlock
- XXX.level.block.LightningRodBlock
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LoomBlock
- XXX.level.block.MagmaBlock
+ XXX.level.block.MangroveLeavesBlock
- XXX.level.block.MangrovePropaguleBlock
+ XXX.level.block.MangroveRootsBlock
- XXX.level.block.MelonBlock
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
+ XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
- XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.PotatoBlock
- XXX.level.block.PowderSnowBlock
+ XXX.level.block.PowderSnowCauldronBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PressurePlateBlock$Sensitivity
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
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
+ XXX.level.block.SculkBehaviour
- XXX.level.block.SculkBehaviour$1
+ XXX.level.block.SculkBlock
- XXX.level.block.SculkCatalystBlock
+ XXX.level.block.SculkSensorBlock
- XXX.level.block.SculkShriekerBlock
+ XXX.level.block.SculkSpreader
- XXX.level.block.SculkSpreader$ChargeCursor
+ XXX.level.block.SculkVeinBlock
- XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- XXX.level.block.SeagrassBlock
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SignBlock
- XXX.level.block.SimpleWaterloggedBlock
+ XXX.level.block.SkullBlock
- XXX.level.block.SkullBlock$Type
+ XXX.level.block.SkullBlock$Types
- XXX.level.block.SlabBlock
+ XXX.level.block.SlabBlock$1
- XXX.level.block.SlimeBlock
+ XXX.level.block.SmallDripleafBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
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
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.WallHangingSignBlock$1
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
+ XXX.level.gameevent.EuclideanGameEventDispatcher
- XXX.level.gameevent.EuclideanGameEventListenerRegistry
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
- XXX.level.gameevent.GameEventListenerRegistry$1
- XXX.level.gameevent.package-info
- XXX.level.gameevent.PositionSource
+ XXX.level.gameevent.PositionSourceType
- XXX.level.levelgen.RandomState$1
+ XXX.level.levelgen.RandomState$1NoiseWiringHelper
- XXX.level.levelgen.RandomSupport
+ XXX.level.levelgen.RandomSupport$Seed128bit
- XXX.level.levelgen.SingleThreadedRandomSource
+ XXX.level.levelgen.SurfaceRules
- XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ XXX.level.levelgen.SurfaceRules$Bandlands
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- XXX.level.levelgen.SurfaceRules$BlockRuleSource
+ XXX.level.levelgen.SurfaceRules$Condition
- XXX.level.levelgen.SurfaceRules$ConditionSource
+ XXX.level.levelgen.SurfaceRules$Context
- XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ XXX.level.levelgen.SurfaceRules$Context$HoleCondition
- XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- XXX.level.levelgen.SurfaceRules$Hole
+ XXX.level.levelgen.SurfaceRules$LazyCondition
- XXX.level.levelgen.SurfaceRules$LazyXZCondition
+ XXX.level.levelgen.SurfaceRules$LazyYCondition
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- XXX.level.levelgen.SurfaceRules$NotCondition
+ XXX.level.levelgen.SurfaceRules$NotConditionSource
- XXX.level.levelgen.SurfaceRules$RuleSource
+ XXX.level.levelgen.SurfaceRules$SequenceRule
- XXX.level.levelgen.SurfaceRules$SequenceRuleSource
+ XXX.level.levelgen.SurfaceRules$StateRule
- XXX.level.levelgen.SurfaceRules$Steep
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ XXX.level.levelgen.SurfaceRules$SurfaceRule
- XXX.level.levelgen.SurfaceRules$Temperature
+ XXX.level.levelgen.SurfaceRules$TestRule
- XXX.level.levelgen.SurfaceRules$TestRuleSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource
- XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ XXX.level.levelgen.SurfaceRules$YConditionSource
- XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ XXX.level.levelgen.SurfaceSystem
- XXX.level.levelgen.SurfaceSystem$1
+ XXX.level.levelgen.ThreadSafeLegacyRandomSource
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldDimensions
- XXX.level.levelgen.WorldDimensions$Complete
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.MaterialColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
- XXX.level.redstone.CollectingNeighborUpdater
+ XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
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
- XXX.level.storage.LevelVersion
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
+ XXX.levelgen.blending.Blender$BlendingOutput
- XXX.levelgen.blending.Blender$CellValueGetter
+ XXX.levelgen.blending.Blender$DistanceGetter
- XXX.levelgen.blending.BlendingData
+ XXX.levelgen.blending.BlendingData$BiomeConsumer
- XXX.levelgen.blending.BlendingData$DensityConsumer
+ XXX.levelgen.blending.BlendingData$HeightConsumer
- XXX.levelgen.blending.package-info
+ XXX.levelgen.blockpredicates.AllOfPredicate
- XXX.levelgen.blockpredicates.AnyOfPredicate
+ XXX.levelgen.blockpredicates.BlockPredicate
- XXX.levelgen.blockpredicates.BlockPredicateType
+ XXX.levelgen.blockpredicates.CombiningPredicate
- XXX.levelgen.blockpredicates.HasSturdyFacePredicate
+ XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ XXX.levelgen.blockpredicates.MatchingBlocksPredicate
- XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
- XXX.levelgen.blockpredicates.MatchingFluidsPredicate
+ XXX.levelgen.blockpredicates.NotPredicate
+ XXX.levelgen.blockpredicates.package-info
- XXX.levelgen.blockpredicates.ReplaceablePredicate
+ XXX.levelgen.blockpredicates.SolidPredicate
- XXX.levelgen.blockpredicates.StateTestingPredicate
+ XXX.levelgen.blockpredicates.TrueBlockPredicate
- XXX.levelgen.blockpredicates.WouldSurvivePredicate
- XXX.levelgen.carver.CanyonCarverConfiguration
+ XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CarverDebugSettings
+ XXX.levelgen.carver.CarvingContext
- XXX.levelgen.carver.CaveCarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.package-info
- XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.carver.WorldCarver$CarveSkipChecker
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockColumnFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskFeature
+ XXX.levelgen.feature.DripstoneClusterFeature
- XXX.levelgen.feature.DripstoneUtils
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeatureCountTracker
- XXX.levelgen.feature.FeatureCountTracker$1
+ XXX.levelgen.feature.FeatureCountTracker$FeatureData
- XXX.levelgen.feature.FeatureCountTracker$LevelData
+ XXX.levelgen.feature.FeaturePlaceContext
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.FossilFeatureConfiguration
+ XXX.levelgen.feature.GeodeFeature
- XXX.levelgen.feature.GlowstoneFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LakeFeature$Configuration
- XXX.levelgen.feature.LargeDripstoneFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.MultifaceGrowthFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
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
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
- XXX.loot.packs.package-info
- XXX.loot.packs.UpdateOneTwentyLootTableProvider
- XXX.loot.packs.VanillaChestLoot
- XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaLootTableProvider
- XXX.metadata.animation.FrameSize
- XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetaDataSection
- XXX.metadata.animation.VillagerMetaDataSection$Hat
+ XXX.metadata.animation.VillagerMetadataSectionSerializer
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.LanguageMetadataSectionSerializer
+ XXX.metadata.language.package-info
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.metadata.texture.package-info
+ XXX.metadata.texture.TextureMetadataSection
- XXX.metadata.texture.TextureMetadataSectionSerializer
- XXX.minecraft.client.ClientTelemetryManager
+ XXX.minecraft.client.ClientTelemetryManager$1
- XXX.minecraft.client.ClientTelemetryManager$PlayerInfo
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.ComponentCollector
+ XXX.minecraft.client.DebugQueryHandler
- XXX.minecraft.client.Game
+ XXX.minecraft.client.Game$Metrics
- XXX.minecraft.client.GameNarrator
+ XXX.minecraft.client.GraphicsStatus
- XXX.minecraft.client.GraphicsStatus$1
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.GuiMessage$Line
+ XXX.minecraft.client.GuiMessageTag
- XXX.minecraft.client.GuiMessageTag$Icon
+ XXX.minecraft.client.HotbarManager
+ XXX.minecraft.client.KeyboardHandler
- XXX.minecraft.client.KeyboardHandler$1
- XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.Minecraft
- XXX.minecraft.client.Minecraft$1
+ XXX.minecraft.client.Minecraft$ChatStatus
- XXX.minecraft.client.Minecraft$ChatStatus$1
+ XXX.minecraft.client.Minecraft$ChatStatus$2
- XXX.minecraft.client.Minecraft$ChatStatus$3
+ XXX.minecraft.client.Minecraft$ChatStatus$4
- XXX.minecraft.client.MouseHandler
+ XXX.minecraft.client.NarratorStatus
- XXX.minecraft.client.OptionInstance
+ XXX.minecraft.client.OptionInstance$AltEnum
- XXX.minecraft.client.OptionInstance$CaptionBasedToString
+ XXX.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
- XXX.minecraft.client.OptionInstance$CycleableValueSet
+ XXX.minecraft.client.OptionInstance$CycleableValueSet$ValueSetter
- XXX.minecraft.client.OptionInstance$Enum
+ XXX.minecraft.client.OptionInstance$IntRange
- XXX.minecraft.client.OptionInstance$IntRangeBase
+ XXX.minecraft.client.OptionInstance$IntRangeBase$1
- XXX.minecraft.client.OptionInstance$LazyEnum
+ XXX.minecraft.client.OptionInstance$OptionInstanceSliderButton
- XXX.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
+ XXX.minecraft.client.OptionInstance$SliderableValueSet
- XXX.minecraft.client.OptionInstance$TooltipSupplier
+ XXX.minecraft.client.OptionInstance$TooltipSupplierFactory
- XXX.minecraft.client.OptionInstance$UnitDouble
+ XXX.minecraft.client.OptionInstance$UnitDouble$1
- XXX.minecraft.client.OptionInstance$ValueSet
+ XXX.minecraft.client.Options
- XXX.minecraft.client.Options$1
+ XXX.minecraft.client.Options$2
- XXX.minecraft.client.Options$3
+ XXX.minecraft.client.Options$4
- XXX.minecraft.client.Options$FieldAccess
+ XXX.minecraft.client.ParticleStatus
- XXX.minecraft.client.PeriodicNotificationManager
+ XXX.minecraft.client.PeriodicNotificationManager$Notification
- XXX.minecraft.client.PeriodicNotificationManager$NotificationTask
+ XXX.minecraft.client.PrioritizeChunkUpdates
- XXX.minecraft.client.Realms32BitWarningStatus
+ XXX.minecraft.client.RecipeBookCategories
- XXX.minecraft.client.RecipeBookCategories$1
+ XXX.minecraft.client.ResourceLoadStateTracker
- XXX.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
+ XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason
- XXX.minecraft.client.ResourceLoadStateTracker$ReloadState
+ XXX.minecraft.client.Screenshot
- XXX.minecraft.client.Session
+ XXX.minecraft.client.StringSplitter
- XXX.minecraft.client.StringSplitter$1
+ XXX.minecraft.client.StringSplitter$FlatComponents
- XXX.minecraft.client.StringSplitter$LineBreakFinder
+ XXX.minecraft.client.StringSplitter$LineComponent
- XXX.minecraft.client.StringSplitter$LinePosConsumer
+ XXX.minecraft.client.StringSplitter$Span
+ XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
- XXX.minecraft.client.StringSplitter$WidthProvider
+ XXX.minecraft.client.Timer
- XXX.minecraft.client.ToggleKeyMapping
+ XXX.minecraft.client.User
- XXX.minecraft.client.User$Type
- XXX.minecraft.core.HolderLookup$RegistryLookup$1
+ XXX.minecraft.core.HolderSet
- XXX.minecraft.core.HolderSet$Direct
+ XXX.minecraft.core.HolderSet$ListBacked
- XXX.minecraft.core.HolderSet$Named
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.package-info
- XXX.minecraft.core.RegistryAccess$1FrozenAccess
+ XXX.minecraft.core.RegistryAccess$Frozen
- XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ XXX.minecraft.core.RegistryAccess$RegistryData
+ XXX.minecraft.core.RegistryAccess$Writable
+ XXX.minecraft.core.RegistryCodecs$RegistryEntry
- XXX.minecraft.core.RegistrySynchronization
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.UUIDUtil
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
- XXX.minecraft.data.BlockFamilies
+ XXX.minecraft.data.BlockFamily
- XXX.minecraft.data.BlockFamily$Builder
+ XXX.minecraft.data.BlockFamily$Variant
- XXX.minecraft.data.BuiltinRegistries
+ XXX.minecraft.data.BuiltinRegistries$RegistryBootstrap
- XXX.minecraft.data.CachedOutput
+ XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataGenerator$Target
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.HashCache$CacheUpdater
+ XXX.minecraft.data.HashCache$ProviderCache
- XXX.minecraft.data.Main
- XXX.minecraft.data.PackOutput$PathProvider
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.Language$1
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CompoundTag
+ XXX.minecraft.nbt.CompoundTag$1
- XXX.minecraft.nbt.CompoundTag$2
+ XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.DoubleTag$1
+ XXX.minecraft.nbt.EndTag
- XXX.minecraft.nbt.EndTag$1
+ XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.FloatTag$1
+ XXX.minecraft.nbt.IntArrayTag
- XXX.minecraft.nbt.IntArrayTag$1
+ XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$1
+ XXX.minecraft.nbt.IntTag$Cache
- XXX.minecraft.nbt.ListTag
+ XXX.minecraft.nbt.ListTag$1
- XXX.minecraft.nbt.ListTag$2
+ XXX.minecraft.nbt.LongArrayTag
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
+ XXX.minecraft.nbt.LongTag$Cache
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtIo$1
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
- XXX.minecraft.nbt.NbtOps$HomogenousListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.obfuscate.DontObfuscate
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.DisconnectedRealmsScreen
- XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryLoader$Bound
+ XXX.minecraft.resources.RegistryResourceAccess$1
+ XXX.minecraft.resources.RegistryResourceAccess$InMemoryStorage
+ XXX.minecraft.resources.RegistryResourceAccess$ParsedEntry
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
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
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenAi$1
+ XXX.monster.warden.WardenSpawnTracker
- XXX.multiplayer.chat.ChatListener
+ XXX.multiplayer.chat.ChatListener$1
+ XXX.multiplayer.chat.ChatListener$Message
- XXX.multiplayer.chat.ChatLog
+ XXX.multiplayer.chat.ChatLog$1
+ XXX.multiplayer.chat.ChatLog$Selection
+ XXX.multiplayer.chat.ChatTrustLevel
- XXX.multiplayer.chat.ChatTrustLevel$1
+ XXX.multiplayer.chat.LoggedChatEvent
- XXX.multiplayer.chat.LoggedChatMessage
+ XXX.multiplayer.chat.LoggedChatMessage$Player
- XXX.multiplayer.chat.LoggedChatMessage$System
+ XXX.multiplayer.chat.LoggedChatMessageLink
+ XXX.multiplayer.chat.RollingMemoryChatLog
+ XXX.network.chat.ChatMessageContent
+ XXX.network.chat.ChatPreviewCache$Result
+ XXX.network.chat.ChatPreviewThrottler$Request
- XXX.network.chat.LastSeenMessagesTracker$Update
+ XXX.network.chat.LastSeenMessagesValidator
- XXX.network.chat.LastSeenTrackedEntry
- XXX.network.chat.MessageSignature$Packer
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
- XXX.network.chat.OutgoingChatMessage$Player
+ XXX.network.chat.OutgoingPlayerChatMessage$NotTracked
+ XXX.network.chat.PlayerChatMessage
+ XXX.network.chat.PreviewableCommand$Argument
- XXX.network.chat.RemoteChatSession
- XXX.network.chat.SignableCommand
- XXX.network.chat.SignedMessageBody
- XXX.network.chat.SignedMessageChain$Decoder
+ XXX.network.chat.SignedMessageChain$Encoder
+ XXX.network.chat.SignedMessageHeader
- XXX.network.chat.SignedMessageLink
+ XXX.network.chat.SignedMessageValidator$Unsigned
- XXX.network.protocol.package-info
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$1
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.packs.linkfs.LinkFileSystem
- XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
- XXX.packs.linkfs.LinkFSFileStore
- XXX.packs.linkfs.LinkFSPath$1
- XXX.packs.linkfs.LinkFSPath$3
- XXX.packs.linkfs.LinkFSProvider$1
- XXX.packs.linkfs.package-info
- XXX.packs.linkfs.PathContents$1
- XXX.packs.linkfs.PathContents$DirectoryContents
+ XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.MetadataSectionType
+ XXX.packs.metadata.package-info
- XXX.packs.repository.Pack$Info
+ XXX.packs.repository.Pack$PackConstructor
- XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.PackSource$1
- XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$ResourceWithSource
+ XXX.packs.resources.Resource$IoSupplier
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceFilterSection$1
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
+ XXX.protocol.game.ClientboundChatPreviewPacket
- XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandsPacket$NodeStub
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisconnectPacket
+ XXX.protocol.game.ClientboundPlayerChatHeaderPacket
- XXX.protocol.game.ClientboundPlayerChatPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$2
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$4
+ XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- XXX.protocol.game.ClientboundPlayerInfoRemovePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquipmentPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ XXX.protocol.game.ClientboundSetScorePacket
- XXX.protocol.game.ClientboundSetSimulationDistancePacket
+ XXX.protocol.game.ClientboundSetSubtitleTextPacket
- XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesAnimationPacket
+ XXX.protocol.game.ClientboundSetTitleTextPacket
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundSystemChatPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundChatPreviewPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPongPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
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
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.protocol.status.ServerStatusPacketListener
- XXX.recipes.packs.BundleRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.LiquidBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ XXX.renderer.block.ModelBlockRenderer$Cache
- XXX.renderer.block.ModelBlockRenderer$Cache$1
+ XXX.renderer.block.ModelBlockRenderer$Cache$2
- XXX.renderer.block.ModelBlockRenderer$SizeInfo
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
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ XXX.renderer.blockentity.LecternRenderer
- XXX.renderer.blockentity.package-info
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.SignRenderer
+ XXX.renderer.blockentity.SignRenderer$SignModel
- XXX.renderer.blockentity.SkullBlockRenderer
+ XXX.renderer.blockentity.SpawnerRenderer
- XXX.renderer.blockentity.StructureBlockRenderer
+ XXX.renderer.blockentity.StructureBlockRenderer$1
- XXX.renderer.blockentity.TheEndGatewayRenderer
+ XXX.renderer.blockentity.TheEndPortalRenderer
+ XXX.renderer.chunk.ChunkRenderDispatcher
- XXX.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
+ XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
- XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
+ XXX.renderer.chunk.package-info
- XXX.renderer.chunk.RenderChunk
+ XXX.renderer.chunk.RenderChunkRegion
- XXX.renderer.chunk.RenderRegionCache
+ XXX.renderer.chunk.RenderRegionCache$ChunkInfo
- XXX.renderer.chunk.VisGraph
+ XXX.renderer.chunk.VisGraph$1
- XXX.renderer.chunk.VisibilitySet
- XXX.renderer.culling.Frustum
+ XXX.renderer.culling.package-info
- XXX.renderer.debug.BeeDebugRenderer
+ XXX.renderer.debug.BeeDebugRenderer$BeeInfo
- XXX.renderer.debug.BeeDebugRenderer$HiveInfo
+ XXX.renderer.debug.BrainDebugRenderer
- XXX.renderer.debug.BrainDebugRenderer$BrainDump
+ XXX.renderer.debug.BrainDebugRenderer$PoiInfo
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
- XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ XXX.renderer.debug.HeightMapRenderer
- XXX.renderer.debug.HeightMapRenderer$1
+ XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.package-info
+ XXX.renderer.debug.PathfindingRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
+ XXX.renderer.debug.VillageSectionsDebugRenderer
- XXX.renderer.debug.WaterDebugRenderer
+ XXX.renderer.debug.WorldGenAttemptRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractZombieRenderer
+ XXX.renderer.entity.AllayRenderer
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.AxolotlRenderer
+ XXX.renderer.entity.BatRenderer
- XXX.renderer.entity.BeeRenderer
+ XXX.renderer.entity.BlazeRenderer
- XXX.renderer.entity.BoatRenderer
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
+ XXX.renderer.texture.package-info
- XXX.renderer.texture.PreloadedTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SimpleTexture$TextureImage
- XXX.renderer.texture.SpriteContents$AnimatedTexture
- XXX.renderer.texture.SpriteContents$InterpolationData
- XXX.renderer.texture.SpriteLoader
- XXX.renderer.texture.SpriteTicker
+ XXX.renderer.texture.Stitcher
- XXX.renderer.texture.Stitcher$Entry
+ XXX.renderer.texture.TextureAtlas$Preparations
- XXX.renderer.texture.TextureAtlasSprite
+ XXX.renderer.texture.TextureAtlasSprite$AnimatedTexture
+ XXX.renderer.texture.TextureAtlasSprite$Info
- XXX.renderer.texture.TextureAtlasSprite$Ticker
+ XXX.renderer.texture.TextureManager
- XXX.renderer.texture.Tickable
- XXX.resources.metadata.package-info
- XXX.resources.model.AtlasSet
- XXX.resources.model.AtlasSet$ResourceLister
- XXX.resources.model.BakedModel
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BuiltInModel
+ XXX.resources.model.Material
- XXX.resources.model.ModelBaker
- XXX.resources.model.ModelBakery$BakedCacheKey
+ XXX.resources.model.ModelBakery$BlockStateDefinitionException
- XXX.resources.model.ModelBakery$LoadedJson
- XXX.resources.model.ModelBakery$ModelGroupKey
+ XXX.resources.model.ModelManager
- XXX.resources.model.ModelManager$ReloadState
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
+ XXX.screens.achievement.package-info
- XXX.screens.achievement.StatsScreen
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlsScreen
- XXX.screens.controls.KeyBindsList
+ XXX.screens.controls.KeyBindsList$CategoryEntry
- XXX.screens.controls.KeyBindsList$CategoryEntry$1
+ XXX.screens.controls.KeyBindsList$Entry
- XXX.screens.controls.KeyBindsList$KeyEntry
+ XXX.screens.controls.KeyBindsList$KeyEntry$1
- XXX.screens.controls.KeyBindsList$KeyEntry$2
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
+ XXX.screens.multiplayer.ChatPreviewWarningScreen
+ XXX.screens.reporting.ChatLogSegmenter$MessageType
+ XXX.screens.reporting.ChatReportScreen
- XXX.screens.reporting.ChatReportScreen$DiscardReportWarningScreen
+ XXX.screens.reporting.ChatReportScreen$SubmitButtonTooltip
- XXX.screens.reporting.ChatSelectionLogFiller
+ XXX.screens.reporting.ChatSelectionLogFiller$Output
- XXX.screens.reporting.ChatSelectionScreen
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
+ XXX.screens.reporting.package-info
- XXX.screens.reporting.ReportReasonSelectionScreen
+ XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
- XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
+ XXX.screens.social.package-info
- XXX.screens.social.PlayerEntry
+ XXX.screens.social.PlayerEntry$1
- XXX.screens.social.PlayerEntry$2
+ XXX.screens.social.PlayerEntry$3
- XXX.screens.social.PlayerEntry$4
+ XXX.screens.social.PlayerEntry$5
- XXX.screens.social.PlayerEntry$6
+ XXX.screens.social.PlayerSocialManager
- XXX.screens.social.SocialInteractionsPlayerList
+ XXX.screens.social.SocialInteractionsScreen
- XXX.screens.social.SocialInteractionsScreen$1
+ XXX.screens.social.SocialInteractionsScreen$2
- XXX.screens.social.SocialInteractionsScreen$Page
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- XXX.screens.worldselection.CreateWorldScreen
+ XXX.screens.worldselection.CreateWorldScreen$1
- XXX.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
- XXX.screens.worldselection.package-info
- XXX.screens.worldselection.WorldCreationContext$OptionsModifier
+ XXX.screens.worldselection.WorldCreationContext$Updater
- XXX.screens.worldselection.WorldSelectionList
+ XXX.screens.worldselection.WorldSelectionList$Entry
- XXX.screens.worldselection.WorldSelectionList$LoadingHeader
+ XXX.screens.worldselection.WorldSelectionList$WorldListEntry
- XXX.server.packs.BuiltInMetadata
- XXX.server.packs.package-info
+ XXX.server.packs.PackResources
- XXX.server.packs.PackResources$ResourceOutput
- XXX.server.packs.PathPackResources
+ XXX.server.packs.ResourcePackFileNotFoundException
- XXX.server.packs.VanillaPackResourcesBuilder
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
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$Value
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.RotationSegment
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
- XXX.structure.pools.package-info
+ XXX.structure.pools.SinglePoolElement
- XXX.structure.pools.StructurePoolElement
+ XXX.structure.pools.StructurePoolElementType
- XXX.structure.pools.StructureTemplatePool
+ XXX.structure.pools.StructureTemplatePool$Projection
+ XXX.structure.structures.BuriedTreasurePieces
- XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.structure.structures.BuriedTreasureStructure
- XXX.structure.structures.DesertPyramidPiece
+ XXX.structure.structures.DesertPyramidStructure
- XXX.structure.structures.EndCityPieces
+ XXX.structure.structures.EndCityPieces$1
- XXX.structure.structures.EndCityPieces$2
+ XXX.structure.structures.EndCityPieces$3
- XXX.structure.structures.EndCityPieces$4
+ XXX.structure.structures.EndCityPieces$EndCityPiece
- XXX.structure.structures.EndCityPieces$SectionGenerator
+ XXX.structure.structures.EndCityStructure
- XXX.structure.structures.IglooPieces
+ XXX.structure.structures.IglooPieces$IglooPiece
- XXX.structure.structures.IglooStructure
+ XXX.structure.structures.JigsawStructure
- XXX.structure.structures.JigsawStructure$1
+ XXX.structure.structures.JungleTemplePiece
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
+ XXX.structure.structures.JungleTempleStructure
- XXX.structure.structures.MineshaftPieces
+ XXX.structure.structures.MineshaftPieces$1
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
+ XXX.structure.structures.MineshaftPieces$MineShaftCrossing
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
+ XXX.structure.structures.MineshaftPieces$MineShaftRoom
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
+ XXX.structure.structures.MineshaftStructure
- XXX.structure.structures.MineshaftStructure$Type
+ XXX.structure.structures.NetherFortressPieces
- XXX.structure.structures.NetherFortressPieces$1
+ XXX.structure.structures.NetherFortressPieces$BridgeCrossing
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
+ XXX.structure.structures.NetherFortressPieces$BridgeStraight
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
+ XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
- XXX.structure.structures.NetherFortressPieces$PieceWeight
+ XXX.structure.structures.NetherFortressPieces$RoomCrossing
- XXX.structure.structures.NetherFortressPieces$StairsRoom
+ XXX.structure.structures.NetherFortressPieces$StartPiece
- XXX.structure.structures.NetherFortressStructure
+ XXX.structure.structures.NetherFossilPieces
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
+ XXX.structure.structures.NetherFossilStructure
- XXX.structure.structures.OceanMonumentPieces
+ XXX.structure.structures.OceanMonumentPieces$1
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.structure.structures.OceanMonumentPieces$RoomDefinition
- XXX.structure.structures.OceanMonumentStructure
+ XXX.structure.structures.OceanRuinPieces
- XXX.structure.structures.OceanRuinPieces$1
+ XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
- XXX.structure.structures.OceanRuinStructure
+ XXX.structure.structures.OceanRuinStructure$Type
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
+ XXX.structure.structures.RuinedPortalPiece$Properties
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
+ XXX.structure.structures.RuinedPortalStructure
- XXX.structure.structures.RuinedPortalStructure$Setup
+ XXX.structure.structures.ShipwreckPieces
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
+ XXX.structure.structures.ShipwreckStructure
- XXX.structure.structures.StrongholdPieces
+ XXX.structure.structures.StrongholdPieces$1
- XXX.structure.structures.StrongholdPieces$2
+ XXX.structure.structures.StrongholdPieces$3
- XXX.structure.structures.StrongholdPieces$ChestCorridor
+ XXX.structure.structures.StrongholdPieces$FillerCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
+ XXX.structure.structures.StrongholdPieces$LeftTurn
- XXX.structure.structures.StrongholdPieces$Library
+ XXX.structure.structures.StrongholdPieces$PieceWeight
- XXX.structure.structures.StrongholdPieces$PortalRoom
+ XXX.structure.structures.StrongholdPieces$PrisonHall
- XXX.structure.structures.StrongholdPieces$RightTurn
+ XXX.structure.structures.StrongholdPieces$RoomCrossing
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
+ XXX.structure.structures.StrongholdPieces$StairsDown
- XXX.structure.structures.StrongholdPieces$StartPiece
+ XXX.structure.structures.StrongholdPieces$Straight
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.structure.structures.StrongholdPieces$Turn
- XXX.structure.structures.StrongholdStructure
+ XXX.structure.structures.SwampHutPiece
- XXX.structure.structures.SwampHutStructure
+ XXX.structure.structures.WoodlandMansionPieces
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
+ XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
+ XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
+ XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.structures.WoodlandMansionStructure
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
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
+ XXX.world.entity.package-info
- XXX.world.flag.FeatureFlag
- XXX.world.flag.FeatureFlagRegistry$Builder
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
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.AnvilMenu$1
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$FuelSlot
- XXX.world.inventory.BrewingStandMenu$IngredientsSlot
+ XXX.world.inventory.BrewingStandMenu$PotionSlot
- XXX.world.inventory.CartographyTableMenu
+ XXX.world.inventory.CartographyTableMenu$1
- XXX.world.inventory.CartographyTableMenu$2
+ XXX.world.inventory.CartographyTableMenu$3
- XXX.world.inventory.CartographyTableMenu$4
+ XXX.world.inventory.CartographyTableMenu$5
- XXX.world.inventory.ChestMenu
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.ContainerSynchronizer
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DispenserMenu
- XXX.world.inventory.EnchantmentMenu
+ XXX.world.inventory.EnchantmentMenu$1
- XXX.world.inventory.EnchantmentMenu$2
+ XXX.world.inventory.EnchantmentMenu$3
- XXX.world.inventory.FurnaceFuelSlot
+ XXX.world.inventory.FurnaceMenu
- XXX.world.inventory.FurnaceResultSlot
+ XXX.world.inventory.GrindstoneMenu
- XXX.world.inventory.GrindstoneMenu$1
+ XXX.world.inventory.GrindstoneMenu$2
- XXX.world.inventory.GrindstoneMenu$3
+ XXX.world.inventory.GrindstoneMenu$4
- XXX.world.inventory.HopperMenu
+ XXX.world.inventory.HorseInventoryMenu
- XXX.world.inventory.HorseInventoryMenu$1
+ XXX.world.inventory.HorseInventoryMenu$2
- XXX.world.inventory.InventoryMenu
+ XXX.world.inventory.InventoryMenu$1
- XXX.world.inventory.InventoryMenu$2
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.LecternMenu
+ XXX.world.inventory.LecternMenu$1
- XXX.world.inventory.LoomMenu
+ XXX.world.inventory.LoomMenu$1
- XXX.world.inventory.LoomMenu$2
+ XXX.world.inventory.LoomMenu$3
- XXX.world.inventory.LoomMenu$4
+ XXX.world.inventory.LoomMenu$5
- XXX.world.inventory.LoomMenu$6
+ XXX.world.inventory.MenuConstructor
- XXX.world.inventory.MenuType
+ XXX.world.inventory.MenuType$MenuSupplier
- XXX.world.inventory.MerchantContainer
+ XXX.world.inventory.MerchantMenu
- XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeHolder
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
+ XXX.world.item.AdventureModeCheck
- XXX.world.item.AirItem
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorItem$1
+ XXX.world.item.ArmorMaterial
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
- XXX.world.item.BookItem
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BowlFoodItem
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$10
+ XXX.world.item.CreativeModeTab$12
+ XXX.world.item.CreativeModeTab$3
+ XXX.world.item.CreativeModeTab$5
+ XXX.world.item.CreativeModeTab$7
+ XXX.world.item.CreativeModeTab$9
- XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTabs
- XXX.world.item.CreativeModeTabs$10
- XXX.world.item.CreativeModeTabs$12
- XXX.world.item.CreativeModeTabs$3
- XXX.world.item.CreativeModeTabs$5
- XXX.world.item.CreativeModeTabs$7
- XXX.world.item.CreativeModeTabs$9
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneyBottleItem
+ XXX.world.item.HoneycombItem
- XXX.world.item.HorseArmorItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$1
- XXX.world.item.Item$Properties
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUtils
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MapItem
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignItem
- XXX.world.item.SimpleFoiledItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
- XXX.world.item.TieredItem
+ XXX.world.item.Tiers
- XXX.world.item.TippedArrowItem
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.Vanishable
- XXX.world.item.Wearable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.package-info
- XXX.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.MacosUtil +1M -1M
```
```
XXX.mojang.realmsclient.RealmsMainScreen$NewsButton +2M -1M
```
```
net.minecraft.Util -1M
```
```
XXX.gui.components.ChatComponent +8M -3M | +4P
```
```
XXX.components.toasts.SystemToast$SystemToastIds -1P
```
```
XXX.gui.font.FontManager$1 +3M -4M
```
```
XXX.screens.inventory.CraftingScreen -1M
```
```
XXX.screens.inventory.CreativeModeInventoryScreen +1M -1M | +1P
```
```
XXX.screens.worldselection.PresetEditor +4M -4M
```
```
XXX.screens.worldselection.WorldCreationContext +12M -7M | +5P -3P
```
```
XXX.screens.worldselection.WorldOpenFlows +18M -15M
```
```
XXX.client.multiplayer.ClientHandshakePacketListenerImpl +1M -1M | +2P
```
```
XXX.client.multiplayer.ClientPacketListener$1 +1P -1P
```
```
XXX.chat.report.ChatReportBuilder +2M -16M
```
```
XXX.client.particle.ParticleEngine +14M -12M | +2P
```
```
XXX.renderer.entity.EntityRenderers +3M -2M
```
```
XXX.entity.layers.VillagerProfessionLayer +3M -2M
```
```
XXX.renderer.texture.Stitcher$Region +1M -2M
```
```
XXX.renderer.texture.StitcherException +1M -1M
```
```
XXX.client.resources.ClientPackSource +8M -27M | +6P -16P
```
```
XXX.client.resources.PaintingTextureManager -1M
```
```
XXX.client.resources.TextureAtlasHolder +5M -4M | -1P
```
```
XXX.metadata.animation.AnimationMetadataSection +1M -5M
```
```
XXX.resources.sounds.SimpleSoundInstance +1M -1M
```
```
XXX.client.server.LanServerDetection$LanServerList +1M -3M
```
```
XXX.client.sounds.SoundBufferLibrary +1M -1M | +1P -1P
```
```
XXX.client.sounds.SoundManager$Preparations +3M -2M | +1P
```
```
XXX.minecraft.commands.CommandBuildContext +1M -1M | +1P
```
```
XXX.commands.arguments.ArgumentSignatures +2M -6M
```
```
XXX.commands.arguments.ArgumentSignatures$Signer +1P -1P
```
```
XXX.commands.arguments.ResourceKeyArgument +7M -10M | -1P
```
```
XXX.commands.arguments.SignedArgument -1P
```
```
XXX.arguments.blocks.BlockStateParser +2M -4M
```
```
XXX.arguments.selector.EntitySelector +4M -2M
```
```
XXX.minecraft.core.Holder$Reference +2M
```
```
XXX.minecraft.core.HolderLookup +1M -1M
```
```
XXX.minecraft.core.MappedRegistry +7M -7M | +1P -2P
```
```
XXX.minecraft.core.RegistryAccess +2M -38M | +3P -5P
```
```
XXX.minecraft.core.RegistryCodecs +4M -6M
```
```
XXX.data.advancements.AdvancementProvider +1M -1M | +3P -2P
```
```
XXX.data.models.BlockModelGenerators$BlockFamilyProvider +2M
```
```
XXX.models.model.ModelLocationUtils +2M
```
```
XXX.models.model.ModelTemplates +11P
```
```
XXX.data.recipes.RecipeProvider +39M -32M | +4P -11P
```
```
XXX.data.recipes.ShapedRecipeBuilder$Result +1M -1M
```
```
XXX.data.recipes.ShapelessRecipeBuilder$Result +1M -1M
```
```
XXX.data.recipes.SimpleCookingRecipeBuilder$Result +1M -1M | +1P
```
```
XXX.data.recipes.SpecialRecipeBuilder$1 +1M -2M
```
```
XXX.data.structures.NbtToSnbt +1M -1M | +2P -1P
```
```
XXX.data.tags.BiomeTagsProvider +1M -1M
```
```
XXX.gametest.framework.GameTestHelper +21M -17M
```
```
XXX.minecraft.nbt.NbtUtils +1M -1M
```
```
XXX.network.chat.FilterMask +1M -1M | +1P
```
```
XXX.network.chat.LastSeenMessages +3M -4M
```
```
XXX.network.chat.LastSeenMessages$Update +3M -4M | +2P -2P
```
```
XXX.network.chat.MessageSignature +4M -8M | +1P -1P
```
```
XXX.network.chat.SignedMessageChain +8M -8M | +2P -1P
```
```
XXX.network.chat.SignedMessageValidator$KeyBased +2M -5M | +2P -2P
```
```
XXX.protocol.game.ClientGamePacketListener +4P -4P
```
```
XXX.protocol.game.ServerGamePacketListener -1P
```
```
XXX.protocol.game.ServerboundChatCommandPacket +1M -2M | -1P
```
```
XXX.minecraft.resources.RegistryOps +1M -5M | -2P
```
```
XXX.minecraft.resources.ResourceLocation +6M
```
```
XXX.minecraft.server.ServerFunctionLibrary +7M -8M | +1P -3P
```
```
XXX.minecraft.server.WorldLoader +4M -1M | +1P
```
```
XXX.minecraft.server.WorldLoader$PackConfig +3M -2M | +2P -1P
```
```
XXX.minecraft.server.WorldLoader$WorldDataSupplier +1P -1P
```
```
XXX.server.commands.EffectCommands +3M -3M
```
```
XXX.server.commands.EnchantCommand +2M -2M
```
```
XXX.server.commands.LocateCommand +18M -15M | -2P
```
```
XXX.server.commands.SummonCommand +2M -2M
```
```
XXX.server.commands.WardenSpawnTrackerCommand +1M
```
```
XXX.server.dedicated.DedicatedServer -1M
```
```
XXX.server.dedicated.DedicatedServerProperties +4M -1M | +4P -3P
```
```
XXX.server.level.WorldGenRegion +1M
```
```
XXX.server.network.ServerGamePacketListenerImpl +14M -27M | +5P -4P
```
```
XXX.server.network.ServerLoginPacketListenerImpl +1M -1M | +1P -1P
```
```
XXX.server.packs.FilePackResources +6M -4M | +2P
```
```
XXX.packs.repository.FolderRepositorySource +8M -6M | +3P -2P
```
```
XXX.packs.repository.ServerPacksSource +7M -2M | +5P -3P
```
```
XXX.packs.resources.MultiPackResourceManager +1M
```
```
XXX.packs.resources.ResourceProvider +2M
```
```
XXX.server.players.PlayerList +4M -5M | +1P -1P
```
```
XXX.minecraft.tags.ItemTags +3P
```
```
XXX.minecraft.tags.TagNetworkSerialization +1M -1M
```
```
XXX.minecraft.util.Crypt +1P
```
```
XXX.minecraft.util.FutureChain +4M -2M | +2P -1P
```
```
XXX.minecraft.util.TaskChainer$DelayedTask +1P
```
```
XXX.world.entity.AnimationState +1M
```
```
XXX.world.entity.Entity +6M -1M | -1P
```
```
XXX.world.entity.LivingEntity +3M -1M
```
```
XXX.world.entity.PlayerRideableJumping +1M
```
```
XXX.world.entity.Saddleable +1M
```
```
XXX.ai.attributes.AttributeMap +4M
```
```
XXX.ai.behavior.BlockPosTracker +1M
```
```
XXX.ai.behavior.LongJumpToRandomPos +5M -5M | +1P -1P
```
```
XXX.ai.memory.MemoryModuleType +1P
```
```
XXX.ai.sensing.TemptingSensor +1M
```
```
XXX.village.poi.PoiTypes +1M -1M
```
```
XXX.animal.allay.AllayAi +1P
```
```
XXX.item.crafting.SmeltingRecipe +1M -1M
```
```
XXX.item.crafting.TippedArrowRecipe +1M -1M
```
```
XXX.world.level.CommonLevelAccessor -1P
```
```
XXX.world.level.LevelReader +1M | +2P
```
```
XXX.world.level.StructureManager +2M -2M | +1P -1P
```
```
XXX.level.block.SupportType$2 +1M | +1P
```
```
XXX.level.block.TrapDoorBlock +1M -1M | +2P
```
```
XXX.level.chunk.ChunkAccess +1M -1M
```
```
XXX.level.chunk.ChunkGenerator +28M -22M | +1P
```
```
XXX.level.gameevent.GameEventDispatcher +4M -1M | +1P -5P
```
```
XXX.gameevent.vibrations.VibrationListener +13M -6M | +3P -2P
```
```
XXX.levelgen.presets.WorldPreset +1M -4M
```
```
XXX.storage.loot.LootTable +2M -2M
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.MacosUtil
</summary>

```diff
+ void loadIcon(InputStream)
- void loadIcon(IoSupplier)
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$NewsButton
</summary>

```diff
- void lambda$new$0(RealmsMainScreen,boolean)
+ void lambda$new$0(RealmsMainScreen,Button)
- void lambda$new$1(RealmsMainScreen,Button)
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ CompletableFuture failedFuture(Throwable)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.ChatComponent
</summary>

```diff
- boolean lambda$processMessageDeletionQueue$0(int,ChatComponent$DelayedMessageDeletion)
- ChatComponent$DelayedMessageDeletion deleteMessageOrDelay(MessageSignature)
+ ChatScreen getFocusedChat()
- GuiMessage createDeletedMarker(GuiMessage)
- int getMessageEndIndexAt(double,double)
+ int getMessageIndexAt(double)
- int getMessageLineIndexAt(double,double)
- void processMessageDeletionQueue()
- void render(PoseStack,int,int,int)
+ void render(PoseStack,int)
- void tick()
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.FontManager$1
</summary>

```diff
+ boolean lambda$prepare$0(ResourceLocation)
- List lambda$prepare$0(ResourceLocation)
+ List lambda$prepare$1(ResourceLocation)
- void lambda$apply$2(ResourceLocation,List)
+ void lambda$apply$3(ResourceLocation,List)
- void lambda$prepare$1(List,int)
+ void lambda$prepare$2(List,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.CraftingScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
</summary>

```diff
- void <init>(Player,FeatureFlagSet)
+ void <init>(Player)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.PresetEditor
</summary>

```diff
- WorldCreationContext$DimensionsUpdater fixedBiomeConfigurator(Holder)
- WorldCreationContext$DimensionsUpdater flatWorldConfigurator(FlatLevelGeneratorSettings)
+ WorldCreationContext$Updater fixedBiomeConfigurator(Holder)
+ WorldCreationContext$Updater flatWorldConfigurator(FlatLevelGeneratorSettings)
- WorldDimensions lambda$fixedBiomeConfigurator$5(Holder,RegistryAccess$Frozen,WorldDimensions)
- WorldDimensions lambda$flatWorldConfigurator$4(FlatLevelGeneratorSettings,RegistryAccess$Frozen,WorldDimensions)
+ WorldGenSettings lambda$fixedBiomeConfigurator$5(Holder,RegistryAccess$Frozen,WorldGenSettings)
+ WorldGenSettings lambda$flatWorldConfigurator$4(FlatLevelGeneratorSettings,RegistryAccess$Frozen,WorldGenSettings)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldCreationContext
</summary>

```diff
- LayeredRegistryAccess worldgenRegistries()
+ Lifecycle worldSettingsStability()
- Registry datapackDimensions()
+ RegistryAccess$Frozen registryAccess()
- RegistryAccess$Frozen worldgenLoadContext()
- void <init>(WorldGenSettings,LayeredRegistryAccess,ReloadableServerResources,WorldDataConfiguration)
+ void <init>(WorldGenSettings,Lifecycle,RegistryAccess$Frozen,ReloadableServerResources)
- void <init>(WorldOptions,Registry,WorldDimensions,LayeredRegistryAccess,ReloadableServerResources,WorldDataConfiguration)
- void <init>(WorldOptions,WorldDimensions,LayeredRegistryAccess,ReloadableServerResources,WorldDataConfiguration)
- WorldCreationContext withDimensions(WorldCreationContext$DimensionsUpdater)
- WorldCreationContext withOptions(WorldCreationContext$OptionsModifier)
+ WorldCreationContext withSettings(WorldCreationContext$SimpleUpdater)
+ WorldCreationContext withSettings(WorldCreationContext$Updater)
+ WorldCreationContext withSettings(WorldGenSettings)
- WorldCreationContext withSettings(WorldOptions,WorldDimensions)
- WorldDataConfiguration dataConfiguration()
- WorldDimensions selectedDimensions()
+ WorldGenSettings worldGenSettings()
- WorldOptions options()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldOpenFlows
</summary>

```diff
+ Boolean lambda$doLoadLevel$4(Void)
- Boolean lambda$doLoadLevel$6(Void)
+ CompletionStage lambda$doLoadLevel$5(Throwable)
- CompletionStage lambda$doLoadLevel$7(Throwable)
- Object loadWorldDataBlocking(WorldLoader$PackConfig,WorldLoader$WorldDataSupplier,WorldLoader$ResultFactory)
+ PackRepository createPackRepository(LevelStorageSource$LevelStorageAccess)
+ Pair lambda$createFreshLevel$0(LevelSettings,WorldGenSettings,RegistryAccess,ResourceManager,DataPackConfig)
+ Pair lambda$loadWorldStem$1(LevelStorageSource$LevelStorageAccess,ResourceManager,DataPackConfig)
- Pair lambda$recreateWorldData$3(CloseableResourceManager,ReloadableServerResources,LayeredRegistryAccess,WorldOpenFlows$1Data)
- Pair recreateWorldData(LevelStorageSource$LevelStorageAccess)
+ void createFreshLevel(String,LevelSettings,RegistryAccess,WorldGenSettings)
- void createFreshLevel(String,LevelSettings,WorldOptions,Function)
- void createLevelFromExistingSettings(LevelStorageSource$LevelStorageAccess,ReloadableServerResources,LayeredRegistryAccess,WorldData)
+ void createLevelFromExistingSettings(LevelStorageSource$LevelStorageAccess,ReloadableServerResources,RegistryAccess$Frozen,WorldData)
- void lambda$askForBackup$11(String,Runnable,boolean,boolean)
+ void lambda$askForBackup$9(String,Runnable,boolean,boolean)
+ void lambda$confirmWorldCreation$10(Runnable,Minecraft,CreateWorldScreen,boolean)
- void lambda$confirmWorldCreation$12(Runnable,Minecraft,CreateWorldScreen,boolean)
- Void lambda$doLoadLevel$10(Throwable)
+ void lambda$doLoadLevel$2(Screen,String,boolean)
+ void lambda$doLoadLevel$3(Screen,String,boolean)
- void lambda$doLoadLevel$4(Screen,String,boolean)
- void lambda$doLoadLevel$5(Screen,String,boolean)
+ void lambda$doLoadLevel$6(Screen)
+ void lambda$doLoadLevel$7(String,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Screen,Boolean)
- void lambda$doLoadLevel$8(Screen)
+ Void lambda$doLoadLevel$8(Throwable)
- void lambda$doLoadLevel$9(String,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Screen,Boolean)
- WorldLoader$DataLoadOutput lambda$createFreshLevel$0(Function,LevelSettings,WorldOptions,WorldLoader$DataLoadContext)
- WorldLoader$DataLoadOutput lambda$loadWorldStem$1(LevelStorageSource$LevelStorageAccess,WorldLoader$DataLoadContext)
- WorldLoader$DataLoadOutput lambda$recreateWorldData$2(LevelStorageSource$LevelStorageAccess,WorldLoader$DataLoadContext)
- WorldLoader$PackConfig getPackConfigFromLevelData(LevelStorageSource$LevelStorageAccess,boolean,PackRepository)
+ WorldStem loadWorldStem(WorldLoader$PackConfig,WorldLoader$WorldDataSupplier)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
</summary>

```diff
- void <init>(Connection,Minecraft,LocalChatSession,ServerData,Screen,Consumer)
+ void <init>(Connection,Minecraft,Screen,Consumer)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.chat.report.ChatReportBuilder
</summary>

```diff
+ boolean lambda$chainForPlayer$3(UUID,ChatLog$Entry)
+ boolean lambda$collectReferencedContext$4(Int2ObjectMap,int,int,LoggedChatMessage$Player)
+ ChatLog$Entry lambda$chainForPlayer$2(ChatLog$Entry)
+ ChatLog$Entry lambda$trailingContext$6(ChatLog$Entry)
+ Int2ObjectMap collectReferencedContext(ChatLog,int,AbuseReportLimits)
+ IntCollection messageReferences(ChatLog,int,PlayerChatMessage)
+ ReportChatMessage buildReportedChatHeader(LoggedChatMessageLink)
+ ReportChatMessage buildReportedChatMessage(int,LoggedChatMessage$Player)
- ReportChatMessage buildReportedChatMessage(LoggedChatMessage$Player,boolean)
+ ReportChatMessageBody$LastSeenSignature lambda$buildReportedChatMessage$7(LastSeenMessages$Entry)
+ Stream chainForPlayer(ChatLog,Int2ObjectMap,UUID)
+ Stream trailingContext(ChatLog,int,int)
+ String encodeComponent(Component)
+ void lambda$buildEvidence$0(Int2ObjectSortedMap,ChatLog$Entry)
- void lambda$buildEvidence$0(List,int,LoggedChatMessage$Player)
+ void lambda$buildEvidence$1(ChatLog,Int2ObjectSortedMap,int)
+ void lambda$collectReferencedContext$5(Int2ObjectMap,ChatLog$Entry)
+ void walkMessageReferenceGraph(ChatLog,int,ChatReportBuilder$ReferencedMessageVisitor)
```

</details>
<details>
<summary>
net.minecraft.client.particle.ParticleEngine
</summary>

```diff
+ CompletableFuture lambda$reload$1(ResourceManager,Map,Executor,ResourceLocation)
+ CompletableFuture[] lambda$reload$2(int)
- CompletionStage lambda$reload$3(Executor,Map)
- CompletionStage lambda$reload$5(Executor,Map)
- Map lambda$reload$0(ResourceManager)
- Map lambda$reload$4(ResourceManager)
- Optional loadParticleDescription(ResourceLocation,Resource)
- ParticleEngine$1ParticleDefinition lambda$reload$1(ResourceLocation,Resource)
- Queue lambda$tick$10(ParticleRenderType)
+ Queue lambda$tick$8(ParticleRenderType)
+ ResourceLocation lambda$loadParticleDescription$6(ResourceLocation)
- ResourceLocation lambda$loadParticleDescription$8(ResourceLocation)
+ TextureAtlas$Preparations lambda$reload$3(ProfilerFiller,ResourceManager,Map,Void)
+ void lambda$destroy$10(BlockPos,BlockState,double,double,double,double,double,double)
- void lambda$destroy$12(BlockPos,BlockState,double,double,double,double,double,double)
+ void lambda$reload$0(ResourceManager,ResourceLocation,Map)
- void lambda$reload$2(List,Executor,ResourceLocation,Resource)
+ void lambda$reload$4(TextureAtlasSprite,ResourceLocation,List)
+ void lambda$reload$5(ProfilerFiller,Map,TextureAtlas$Preparations)
- void lambda$reload$6(SpriteLoader$Preparations,Set,TextureAtlasSprite,ParticleEngine$1ParticleDefinition)
- void lambda$reload$7(ProfilerFiller,CompletableFuture,CompletableFuture,Void)
+ void lambda$tick$7(ParticleRenderType,Queue)
- void lambda$tick$9(ParticleRenderType,Queue)
- void lambda$tickParticleList$11(ParticleGroup)
+ void lambda$tickParticleList$9(ParticleGroup)
+ void loadParticleDescription(ResourceManager,ResourceLocation,Map)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderers
</summary>

```diff
- EntityRenderer lambda$static$25(EntityRendererProvider$Context)
+ void lambda$createEntityRenderers$25(ImmutableMap$Builder,EntityRendererProvider$Context,EntityType,EntityRendererProvider)
- void lambda$createEntityRenderers$26(ImmutableMap$Builder,EntityRendererProvider$Context,EntityType,EntityRendererProvider)
+ void lambda$createPlayerRenderers$26(ImmutableMap$Builder,EntityRendererProvider$Context,String,EntityRendererProvider)
- void lambda$createPlayerRenderers$27(ImmutableMap$Builder,EntityRendererProvider$Context,String,EntityRendererProvider)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
</summary>

```diff
+ Optional lambda$getHatData$1(Resource)
- Optional lambda$getHatData$2(Resource)
- String lambda$getResourceLocation$1(String,String)
+ VillagerMetaDataSection$Hat lambda$getHatData$2(String,DefaultedRegistry,Object,Object)
- VillagerMetaDataSection$Hat lambda$getHatData$3(String,DefaultedRegistry,Object,Object)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.Stitcher$Region
</summary>

```diff
+ Stitcher$Holder getHolder()
+ void walk(Consumer)
- void walk(Stitcher$SpriteLoader)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.StitcherException
</summary>

```diff
- void <init>(Stitcher$Entry,Collection)
+ void <init>(TextureAtlasSprite$Info,Collection)
```

</details>
<details>
<summary>
net.minecraft.client.resources.ClientPackSource
</summary>

```diff
+ boolean checkHash(String,File)
+ CompletableFuture clearServerPack()
+ CompletableFuture downloadAndSelectResourcePack(URL,String,boolean)
+ CompletableFuture loadBundledResourcePack(LevelStorageSource$LevelStorageAccess)
+ CompletableFuture setServerPack(File,PackSource)
+ CompletionStage lambda$downloadAndSelectResourcePack$3(String,File,Minecraft,boolean,Object)
+ CompletionStage lambda$downloadAndSelectResourcePack$7(File,Minecraft,Throwable)
- Component getPackTitle(String)
+ FolderPackResources createProgrammerArtDirPack(File)
+ Map getDownloadHeaders()
- Pack createBuiltinPack(String,Pack$ResourcesSupplier,Component)
+ Pack createProgrammerArtPack(Pack$PackConstructor,Supplier)
+ Pack createProgrammerArtPack(Pack$PackConstructor)
- Pack createVanillaPack(PackResources)
+ PackResources createProgrammerArtZipPack(File)
+ PackResources lambda$createProgrammerArtPack$10(File)
+ PackResources lambda$createProgrammerArtPack$11(File)
- PackResources lambda$createVanillaPack$0(PackResources,String)
+ PackResources lambda$loadPacks$0()
+ PackResources lambda$setServerPack$9(File)
- Path findExplodedAssetPacks(Path)
- VanillaPackResources createVanillaPackSource(Path)
+ VanillaPackResources getVanillaPack()
+ void <init>(File,AssetIndex)
- void <init>(Path)
+ void clearOldDownloads()
+ void deleteQuietly(File)
+ void lambda$downloadAndSelectResourcePack$1(Minecraft,ProgressScreen)
+ void lambda$downloadAndSelectResourcePack$2(boolean,Minecraft)
+ void lambda$downloadAndSelectResourcePack$4(Throwable,File,Void)
+ void lambda$downloadAndSelectResourcePack$5(Minecraft,boolean)
+ void lambda$downloadAndSelectResourcePack$6(Minecraft,Void)
+ void lambda$downloadAndSelectResourcePack$8(Void)
+ void loadPacks(Consumer,Pack$PackConstructor)
- void populatePackList(BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.client.resources.PaintingTextureManager
</summary>

```diff
+ Stream getResourcesToLoad()
```

</details>
<details>
<summary>
net.minecraft.client.resources.TextureAtlasHolder
</summary>

```diff
- CompletableFuture reload(PreparableReloadListener$PreparationBarrier,ResourceManager,ProfilerFiller,ProfilerFiller,Executor,Executor)
- CompletionStage lambda$reload$1(Executor,Map)
- Map lambda$reload$0(ResourceManager)
+ Object prepare(ResourceManager,ProfilerFiller)
+ TextureAtlas$Preparations prepare(ResourceManager,ProfilerFiller)
+ void apply(Object,ResourceManager,ProfilerFiller)
- void apply(SpriteLoader$Preparations,ProfilerFiller)
+ void apply(TextureAtlas$Preparations,ResourceManager,ProfilerFiller)
- void lambda$reload$2(ProfilerFiller,SpriteLoader$Preparations)
```

</details>
<details>
<summary>
net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
</summary>

```diff
+ boolean isDivisionInteger(int,int)
- FrameSize calculateFrameSize(int,int)
+ int getFrameHeight(int)
+ int getFrameWidth(int)
+ Pair calculateFrameSize(int,int)
+ Pair getFrameSize(int,int)
```

</details>
<details>
<summary>
net.minecraft.client.resources.sounds.SimpleSoundInstance
</summary>

```diff
+ SimpleSoundInstance forRecord(SoundEvent,double,double,double)
- SimpleSoundInstance forRecord(SoundEvent,Vec3)
```

</details>
<details>
<summary>
net.minecraft.client.server.LanServerDetection$LanServerList
</summary>

```diff
+ boolean isDirty()
+ List getServers()
- List takeDirtyServers()
+ void markClean()
```

</details>
<details>
<summary>
net.minecraft.client.sounds.SoundBufferLibrary
</summary>

```diff
+ void <init>(ResourceManager)
- void <init>(ResourceProvider)
```

</details>
<details>
<summary>
net.minecraft.client.sounds.SoundManager$Preparations
</summary>

```diff
- void apply(Map,Map,SoundEngine)
+ void apply(Map,SoundEngine)
+ void handleRegistration(ResourceLocation,SoundEventRegistration,ResourceManager)
- void handleRegistration(ResourceLocation,SoundEventRegistration)
- void listResources(ResourceManager)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandBuildContext
</summary>

```diff
- void <init>(RegistryAccess,FeatureFlagSet)
+ void <init>(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.ArgumentSignatures
</summary>

```diff
+ ArgumentSignatures signCommand(PreviewableCommand,ArgumentSignatures$Signer)
- ArgumentSignatures signCommand(SignableCommand,ArgumentSignatures$Signer)
- ArgumentSignatures$Entry lambda$signCommand$1(ArgumentSignatures$Signer,SignableCommand$Argument)
+ ArgumentSignatures$Entry lambda$signCommand$2(ArgumentSignatures$Signer,Pair)
+ boolean hasSignableArguments(PreviewableCommand)
+ boolean lambda$hasSignableArguments$1(PreviewableCommand$Argument)
+ List collectPlainSignableArguments(PreviewableCommand)
+ String getSignableText(SignedArgument,ParsedArgument)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.ResourceKeyArgument
</summary>

```diff
+ Attribute getAttribute(CommandContext,String)
+ CommandSyntaxException lambda$getAttribute$6(ResourceKey)
- CommandSyntaxException lambda$getRegistryKey$3(DynamicCommandExceptionType,ResourceKey)
+ CommandSyntaxException lambda$getRegistryKeyType$5(DynamicCommandExceptionType,ResourceKey)
+ CommandSyntaxException lambda$getRegistryType$4(DynamicCommandExceptionType,ResourceKey)
- CommandSyntaxException lambda$resolveKey$4(DynamicCommandExceptionType,ResourceKey)
+ Holder getConfiguredFeature(CommandContext,String)
+ Holder getRegistryKeyType(CommandContext,String,ResourceKey,DynamicCommandExceptionType)
+ Holder getStructure(CommandContext,String)
+ Holder getStructureTemplatePool(CommandContext,String)
- Holder$Reference getConfiguredFeature(CommandContext,String)
- Holder$Reference getStructure(CommandContext,String)
- Holder$Reference getStructureTemplatePool(CommandContext,String)
- Holder$Reference resolveKey(CommandContext,String,ResourceKey,DynamicCommandExceptionType)
+ Message lambda$static$3(Object)
- ResourceKey getRegistryKey(CommandContext,String,ResourceKey,DynamicCommandExceptionType)
+ ResourceKey getRegistryType(CommandContext,String,ResourceKey,DynamicCommandExceptionType)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockStateParser
</summary>

```diff
- BlockStateParser$BlockResult parseForBlock(HolderLookup,String,boolean)
+ BlockStateParser$BlockResult parseForBlock(Registry,String,boolean)
+ BlockStateParser$BlockResult parseForBlock(Registry,StringReader,boolean)
- Either parseForTesting(HolderLookup,String,boolean)
+ Either parseForTesting(Registry,String,boolean)
+ Either parseForTesting(Registry,StringReader,boolean)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.EntitySelector
</summary>

```diff
- boolean lambda$findEntities$0(CommandSourceStack,Entity)
+ boolean lambda$getPredicate$0(AABB,Entity)
- boolean lambda$getPredicate$1(AABB,Entity)
+ boolean lambda$getPredicate$1(Vec3,Entity)
- boolean lambda$getPredicate$2(Vec3,Entity)
- List findEntitiesRaw(CommandSourceStack)
```

</details>
<details>
<summary>
net.minecraft.core.Holder$Reference
</summary>

```diff
- void bindKey(ResourceKey)
- void bindValue(Object)
```

</details>
<details>
<summary>
net.minecraft.core.HolderLookup
</summary>

```diff
+ HolderLookup forRegistry(Registry)
- HolderLookup$RegistryLookup forRegistry(Registry)
```

</details>
<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
+ boolean lambda$freeze$4(Map$Entry)
- boolean lambda$freeze$5(Map$Entry)
+ boolean lambda$freeze$6(Holder$Reference)
+ Holder getOrCreateHolderOrThrow(ResourceKey)
+ Holder registerMapping(int,ResourceKey,Object,Lifecycle,boolean)
+ Holder registerOrOverride(OptionalInt,ResourceKey,Object,Lifecycle)
- Holder$Reference getOrCreateHolderOrThrow(ResourceKey)
+ ResourceLocation lambda$freeze$5(Map$Entry)
- ResourceLocation lambda$freeze$6(Map$Entry)
- void <init>(ResourceKey,Lifecycle,boolean)
+ void <init>(ResourceKey,Lifecycle,Function)
- void <init>(ResourceKey,Lifecycle)
- void lambda$freeze$4(Object,Holder$Reference)
- void validateWrite()
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess
</summary>

```diff
+ boolean lambda$ownedNetworkableRegistries$9(RegistryAccess$RegistryEntry)
+ Codec captureMap(UnboundedMapCodec)
+ Codec lambda$getNetworkCodec$10(RegistryAccess$RegistryData)
+ Codec lambda$makeNetworkCodec$4(ResourceKey,Codec)
+ Codec makeNetworkCodec()
+ DataResult getNetworkCodec(ResourceKey)
+ DataResult lambda$getNetworkCodec$11(ResourceKey)
+ DataResult lambda$makeNetworkCodec$3(Registry)
+ DataResult lambda$makeNetworkCodec$5(ResourceKey)
+ IllegalStateException lambda$ownedRegistryOrThrow$0(ResourceKey)
- IllegalStateException lambda$registryOrThrow$0(ResourceKey)
+ IllegalStateException lambda$registryOrThrow$1(ResourceKey)
+ IllegalStateException lambda$retrieveRegistry$15(ResourceKey)
+ ImmutableMap lambda$static$2()
+ Iterable knownRegistries()
- Lifecycle lambda$allElementsLifecycle$1(RegistryAccess$RegistryEntry)
+ Lifecycle lambda$allElementsLifecycle$16(RegistryAccess$RegistryEntry)
+ Map createFreshRegistries()
+ Map lambda$captureMap$8(RegistryAccess)
+ Optional registry(ResourceKey)
+ Registry lambda$captureMap$7(RegistryAccess$RegistryEntry)
+ Registry lambda$readFromDisk$14(Dynamic,ResourceKey)
+ Registry ownedRegistryOrThrow(ResourceKey)
+ Registry retrieveRegistry(ResourceKey,Dynamic)
+ RegistryAccess readFromDisk(Dynamic)
+ RegistryAccess$Frozen lambda$static$12()
+ RegistryAccess$Writable blankWriteable()
+ RegistryAccess$Writable builtinCopy()
+ ResourceKey lambda$captureMap$6(RegistryAccess$RegistryEntry)
+ Stream globalRegistries()
+ Stream networkSafeRegistries()
+ Stream ownedNetworkableRegistries()
+ Stream registries()
+ void addBuiltinElements(RegistryResourceAccess$InMemoryStorage,RegistryAccess$RegistryData)
+ void lambda$readRegistry$13(DataResult$PartialResult)
+ void load(RegistryAccess$Writable,DynamicOps,RegistryLoader)
+ void put(ImmutableMap$Builder,ResourceKey,Codec,Codec)
+ void put(ImmutableMap$Builder,ResourceKey,Codec)
+ void readRegistry(DynamicOps,RegistryLoader$Bound,RegistryAccess$RegistryData)
+ WritableRegistry createRegistry(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.core.RegistryCodecs
</summary>

```diff
+ Codec dataPackAwareCodec(ResourceKey,Lifecycle,Codec)
+ Codec directCodec(ResourceKey,Codec)
- Codec fullCodec(ResourceKey,Lifecycle,Codec)
+ Decoder dataPackAwareDecoder(ResourceKey,Codec,Decoder,Lifecycle)
+ Map lambda$dataPackAwareCodec$3(Registry)
- Map lambda$fullCodec$5(Registry)
- Registry lambda$fullCodec$4(ResourceKey,Lifecycle,Map)
+ void lambda$dataPackAwareDecoder$4(WritableRegistry,Lifecycle,ResourceKey,Object)
- void lambda$fullCodec$3(WritableRegistry,Lifecycle,ResourceKey,Object)
+ WritableRegistry lambda$dataPackAwareDecoder$5(ResourceKey,Lifecycle,Map)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.AdvancementProvider
</summary>

```diff
+ void <init>(DataGenerator)
- void <init>(String,PackOutput,List)
```

</details>
<details>
<summary>
net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
</summary>

```diff
- BlockModelGenerators$BlockFamilyProvider customFence(Block)
- BlockModelGenerators$BlockFamilyProvider customFenceGate(Block)
```

</details>
<details>
<summary>
net.minecraft.data.models.model.ModelLocationUtils
</summary>

```diff
- String lambda$getModelLocation$0(String,String)
- String lambda$getModelLocation$1(String,String)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- boolean lambda$generateForEnabledBlockFamilies$1(FeatureFlagSet,BlockFamily)
- RecipeBuilder lambda$static$19(ItemLike,ItemLike)
- RecipeBuilder lambda$static$20(ItemLike,ItemLike)
- RecipeBuilder lambda$static$21(ItemLike,ItemLike)
+ RecipeBuilder lambda$static$6(ItemLike,ItemLike)
+ RecipeBuilder polishedBuilder(ItemLike,Ingredient)
- RecipeBuilder polishedBuilder(RecipeCategory,ItemLike,Ingredient)
+ RecipeBuilder pressurePlateBuilder(ItemLike,Ingredient)
- RecipeBuilder pressurePlateBuilder(RecipeCategory,ItemLike,Ingredient)
+ RecipeBuilder slabBuilder(ItemLike,Ingredient)
- RecipeBuilder slabBuilder(RecipeCategory,ItemLike,Ingredient)
+ RecipeBuilder wallBuilder(ItemLike,Ingredient)
- RecipeBuilder wallBuilder(RecipeCategory,ItemLike,Ingredient)
+ ShapedRecipeBuilder chiseledBuilder(ItemLike,Ingredient)
- ShapedRecipeBuilder chiseledBuilder(RecipeCategory,ItemLike,Ingredient)
+ ShapedRecipeBuilder cutBuilder(ItemLike,Ingredient)
- ShapedRecipeBuilder cutBuilder(RecipeCategory,ItemLike,Ingredient)
+ String getName()
+ String lambda$generateRecipes$4(ItemLike)
- String lambda$generateRecipes$5(ItemLike)
+ void <init>(DataGenerator)
- void <init>(PackOutput)
- void buildAdvancement(CachedOutput,ResourceLocation,Advancement$Builder)
+ void buildCraftingRecipes(Consumer)
+ void chiseled(Consumer,ItemLike,ItemLike)
- void chiseled(Consumer,RecipeCategory,ItemLike,ItemLike)
- void cookRecipes(Consumer,String,RecipeSerializer,int)
+ void cookRecipes(Consumer,String,SimpleCookingSerializer,int)
+ void cut(Consumer,ItemLike,ItemLike)
- void cut(Consumer,RecipeCategory,ItemLike,ItemLike)
- void generateForEnabledBlockFamilies(Consumer,FeatureFlagSet)
- void hangingSign(Consumer,ItemLike,ItemLike,int)
- void hangingSign(Consumer,ItemLike,ItemLike)
+ void lambda$buildCraftingRecipes$1(Consumer,BlockFamily)
- void lambda$generateForEnabledBlockFamilies$2(Consumer,BlockFamily)
+ void lambda$generateRecipes$3(RecipeBuilder,BlockFamily$Variant,String)
- void lambda$generateRecipes$4(RecipeBuilder,BlockFamily$Variant,String)
+ void lambda$generateRecipes$5(BlockFamily,Consumer,BlockFamily$Variant,Block)
- void lambda$generateRecipes$6(BlockFamily,Consumer,BlockFamily$Variant,Block)
+ void lambda$waxRecipes$2(Consumer,Block,Block)
- void lambda$waxRecipes$3(Consumer,Block,Block)
- void mosaicBuilder(Consumer,RecipeCategory,ItemLike,ItemLike)
+ void netheriteSmithing(Consumer,Item,Item)
- void netheriteSmithing(Consumer,Item,RecipeCategory,Item)
+ void nineBlockStorageRecipes(Consumer,ItemLike,ItemLike,String,String,String,String)
+ void nineBlockStorageRecipes(Consumer,ItemLike,ItemLike)
- void nineBlockStorageRecipes(Consumer,RecipeCategory,ItemLike,RecipeCategory,ItemLike,String,String,String,String)
- void nineBlockStorageRecipes(Consumer,RecipeCategory,ItemLike,RecipeCategory,ItemLike)
+ void nineBlockStorageRecipesRecipesWithCustomUnpacking(Consumer,ItemLike,ItemLike,String,String)
- void nineBlockStorageRecipesRecipesWithCustomUnpacking(Consumer,RecipeCategory,ItemLike,RecipeCategory,ItemLike,String,String)
+ void nineBlockStorageRecipesWithCustomPacking(Consumer,ItemLike,ItemLike,String,String)
- void nineBlockStorageRecipesWithCustomPacking(Consumer,RecipeCategory,ItemLike,RecipeCategory,ItemLike,String,String)
+ void oreBlasting(Consumer,List,ItemLike,float,int,String)
- void oreBlasting(Consumer,List,RecipeCategory,ItemLike,float,int,String)
- void oreCooking(Consumer,RecipeSerializer,List,RecipeCategory,ItemLike,float,int,String,String)
+ void oreCooking(Consumer,SimpleCookingSerializer,List,ItemLike,float,int,String,String)
+ void oreSmelting(Consumer,List,ItemLike,float,int,String)
- void oreSmelting(Consumer,List,RecipeCategory,ItemLike,float,int,String)
+ void polished(Consumer,ItemLike,ItemLike)
- void polished(Consumer,RecipeCategory,ItemLike,ItemLike)
- void simpleCookingRecipe(Consumer,String,RecipeSerializer,int,ItemLike,ItemLike,float)
+ void simpleCookingRecipe(Consumer,String,SimpleCookingSerializer,int,ItemLike,ItemLike,float)
+ void slab(Consumer,ItemLike,ItemLike)
- void slab(Consumer,RecipeCategory,ItemLike,ItemLike)
+ void stonecutterResultFromBase(Consumer,ItemLike,ItemLike,int)
+ void stonecutterResultFromBase(Consumer,ItemLike,ItemLike)
- void stonecutterResultFromBase(Consumer,RecipeCategory,ItemLike,ItemLike,int)
- void stonecutterResultFromBase(Consumer,RecipeCategory,ItemLike,ItemLike)
- void twoByTwoPacker(Consumer,RecipeCategory,ItemLike,ItemLike)
+ void wall(Consumer,ItemLike,ItemLike)
- void wall(Consumer,RecipeCategory,ItemLike,ItemLike)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapedRecipeBuilder$Result
</summary>

```diff
- void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation)
+ void <init>(ResourceLocation,Item,int,String,List,Map,Advancement$Builder,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
</summary>

```diff
- void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Advancement$Builder,ResourceLocation)
+ void <init>(ResourceLocation,Item,int,String,List,Advancement$Builder,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
</summary>

```diff
- void <init>(ResourceLocation,String,CookingBookCategory,Ingredient,Item,float,int,Advancement$Builder,ResourceLocation,RecipeSerializer)
+ void <init>(ResourceLocation,String,Ingredient,Item,float,int,Advancement$Builder,ResourceLocation,RecipeSerializer)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.SpecialRecipeBuilder$1
</summary>

```diff
- void <init>(SpecialRecipeBuilder,CraftingBookCategory,String)
+ void <init>(SpecialRecipeBuilder,String)
+ void serializeRecipeData(JsonObject)
```

</details>
<details>
<summary>
net.minecraft.data.structures.NbtToSnbt
</summary>

```diff
+ void <init>(DataGenerator)
- void <init>(PackOutput,Collection)
```

</details>
<details>
<summary>
net.minecraft.data.tags.BiomeTagsProvider
</summary>

```diff
+ void <init>(DataGenerator)
- void <init>(PackOutput)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- boolean lambda$assertBlockProperty$10(Predicate,Property,BlockState)
+ boolean lambda$assertBlockProperty$10(Property,Comparable,BlockState)
+ boolean lambda$assertBlockProperty$12(Predicate,Property,BlockState)
- boolean lambda$assertEntityInstancePresent$12(Entity,Entity)
+ boolean lambda$assertEntityInstancePresent$14(Entity,Entity)
- boolean lambda$assertEntityNotTouching$15(Vec3,Entity)
+ boolean lambda$assertEntityNotTouching$17(Vec3,Entity)
- boolean lambda$assertEntityTouching$14(Vec3,Entity)
+ boolean lambda$assertEntityTouching$16(Vec3,Entity)
- Exception lambda$failIf$22()
+ Exception lambda$failIf$24()
- GameTestAssertPosException lambda$assertEntityInstancePresent$13(Entity,BlockPos,BlockPos)
+ GameTestAssertPosException lambda$assertEntityInstancePresent$15(Entity,BlockPos,BlockPos)
- ItemEntity spawnItem(Item,BlockPos)
- Player makeMockSurvivalPlayer()
+ String lambda$assertBlockProperty$11(Property,Comparable)
- String lambda$assertBlockProperty$11(String)
+ String lambda$assertBlockProperty$13(String)
- Vec3 relativeVec(Vec3)
- void assertEntityPresent(EntityType,Vec3,Vec3)
- void assertTrue(boolean,String)
- void lambda$assertAtTickTimeContainerContains$17(BlockPos,Item)
+ void lambda$assertAtTickTimeContainerContains$19(BlockPos,Item)
- void lambda$assertAtTickTimeContainerEmpty$18(BlockPos)
+ void lambda$assertAtTickTimeContainerEmpty$20(BlockPos)
- void lambda$assertSameBlockStates$16(BlockPos,BoundingBox,BlockPos)
+ void lambda$assertSameBlockStates$18(BlockPos,BoundingBox,BlockPos)
- void lambda$failIfEver$23(Runnable,long)
+ void lambda$failIfEver$25(Runnable,long)
- void lambda$onEachTick$24(Runnable,long)
+ void lambda$onEachTick$26(Runnable,long)
- void lambda$succeedWhenEntityData$19(BlockPos,EntityType,Function,Object)
+ void lambda$succeedWhenEntityData$21(BlockPos,EntityType,Function,Object)
- void lambda$succeedWhenEntityNotPresent$21(EntityType,BlockPos)
+ void lambda$succeedWhenEntityNotPresent$23(EntityType,BlockPos)
- void lambda$succeedWhenEntityPresent$20(EntityType,BlockPos)
+ void lambda$succeedWhenEntityPresent$22(EntityType,BlockPos)
- void useBlock(BlockPos,Player)
```

</details>
<details>
<summary>
net.minecraft.nbt.NbtUtils
</summary>

```diff
+ BlockState readBlockState(CompoundTag)
- BlockState readBlockState(HolderLookup,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.network.chat.FilterMask
</summary>

```diff
+ Component apply(ChatMessageContent)
- Component applyWithFormatting(String)
```

</details>
<details>
<summary>
net.minecraft.network.chat.LastSeenMessages
</summary>

```diff
- LastSeenMessages$Packed pack(MessageSignature$Packer)
- MessageSignature$Packed lambda$pack$0(MessageSignature$Packer,MessageSignature)
+ void <init>(FriendlyByteBuf)
+ void lambda$write$0(FriendlyByteBuf,LastSeenMessages$Entry)
+ void updateHash(DataOutput)
- void updateSignature(SignatureUpdater$Output)
+ void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.chat.LastSeenMessages$Update
</summary>

```diff
- BitSet acknowledged()
- int offset()
+ LastSeenMessages lastSeen()
+ Optional lastReceived()
- void <init>(int,BitSet)
+ void <init>(LastSeenMessages,Optional)
+ void lambda$write$0(FriendlyByteBuf,LastSeenMessages$Entry)
```

</details>
<details>
<summary>
net.minecraft.network.chat.MessageSignature
</summary>

```diff
+ boolean isEmpty()
- boolean verify(SignatureValidator,SignatureUpdater)
+ boolean verify(SignatureValidator,SignedMessageHeader,byte[])
+ boolean verify(SignatureValidator,SignedMessageHeader,SignedMessageBody)
- MessageSignature read(FriendlyByteBuf)
- MessageSignature$Packed pack(MessageSignature$Packer)
+ void <clinit>()
+ void <init>(FriendlyByteBuf)
+ void lambda$verify$0(SignedMessageHeader,byte[],SignatureUpdater$Output)
+ void lambda$verify$1(SignedMessageHeader,byte[],SignatureUpdater$Output)
- void write(FriendlyByteBuf,MessageSignature)
+ void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageChain
</summary>

```diff
- MessageSignature lambda$encoder$1(Signer,SignedMessageBody)
+ MessageSignature pack(Signer,MessageSigner,MessageSignature,ChatMessageContent,LastSeenMessages)
- PlayerChatMessage lambda$decoder$2(ProfilePublicKey,SignatureValidator,MessageSignature,SignedMessageBody)
+ PlayerChatMessage unpack(SignedMessageChain$Link,MessageSignature,MessageSigner,ChatMessageContent,LastSeenMessages)
+ PlayerChatMessage unpack(SignedMessageChain$Link,MessageSigner,ChatMessageContent,LastSeenMessages)
+ SignedMessageChain$Decoder decoder()
- SignedMessageChain$Decoder decoder(ProfilePublicKey)
+ SignedMessageChain$Encoder encoder()
- SignedMessageChain$Encoder encoder(Signer)
+ SignedMessageChain$Link pack(Signer,MessageSigner,ChatMessageContent,LastSeenMessages)
- SignedMessageLink advanceLink()
- void <clinit>()
+ void <init>()
- void <init>(UUID,UUID)
- void lambda$encoder$0(SignedMessageLink,SignedMessageBody,SignatureUpdater$Output)
+ void lambda$pack$0(SignedMessageHeader,byte[],SignatureUpdater$Output)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageValidator$KeyBased
</summary>

```diff
- boolean updateAndValidate(PlayerChatMessage)
- boolean validateChain(PlayerChatMessage)
+ boolean validateChain(SignedMessageHeader,MessageSignature,boolean)
+ boolean validateContents(SignedMessageHeader,MessageSignature,byte[],boolean)
+ SignedMessageValidator$State updateAndValidate(SignedMessageHeader,MessageSignature,byte[],boolean)
+ SignedMessageValidator$State validateHeader(SignedMessageHeader,MessageSignature,byte[])
+ SignedMessageValidator$State validateMessage(PlayerChatMessage)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundChatCommandPacket
</summary>

```diff
+ boolean signedPreview()
+ void <init>(String,Instant,long,ArgumentSignatures,boolean,LastSeenMessages$Update)
- void <init>(String,Instant,long,ArgumentSignatures,LastSeenMessages$Update)
```

</details>
<details>
<summary>
net.minecraft.resources.RegistryOps
</summary>

```diff
+ DynamicOps getAsJson()
+ Optional registryLoader()
+ RegistryOps createAndLoad(DynamicOps,RegistryAccess$Writable,RegistryResourceAccess)
+ RegistryOps createAndLoad(DynamicOps,RegistryAccess$Writable,ResourceManager)
+ void <init>(DynamicOps,RegistryAccess,Optional)
- void <init>(DynamicOps,RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.resources.ResourceLocation
</summary>

```diff
- ResourceLocation withPath(String)
- ResourceLocation withPath(UnaryOperator)
- ResourceLocation withPrefix(String)
- String assertValidNamespace(String,String)
- String assertValidPath(String,String)
- void <init>(String,String,ResourceLocation$Dummy)
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionLibrary
</summary>

```diff
+ boolean lambda$reload$1(ResourceLocation)
- CommandFunction lambda$reload$2(Map$Entry,ResourceLocation,CommandSourceStack)
+ CommandFunction lambda$reload$3(Map$Entry,ResourceLocation,CommandSourceStack)
- CompletionStage lambda$reload$4(Executor,Map)
+ CompletionStage lambda$reload$5(Executor,Map)
- Map lambda$reload$1(ResourceManager)
+ Map lambda$reload$2(ResourceManager)
- Map lambda$reload$3(Map,Void,Throwable)
+ Map lambda$reload$4(Map,Void,Throwable)
- Object lambda$reload$5(ResourceLocation,ImmutableMap$Builder,CommandFunction,Throwable)
+ Object lambda$reload$6(ResourceLocation,ImmutableMap$Builder,CommandFunction,Throwable)
- void lambda$reload$6(ImmutableMap$Builder,ResourceLocation,CompletableFuture)
+ void lambda$reload$7(ImmutableMap$Builder,ResourceLocation,CompletableFuture)
- void lambda$reload$7(Pair)
+ void lambda$reload$8(Pair)
```

</details>
<details>
<summary>
net.minecraft.server.WorldLoader
</summary>

```diff
- LayeredRegistryAccess loadAndReplaceLayer(ResourceManager,LayeredRegistryAccess,RegistryLayer,List)
- Object lambda$load$1(RegistryAccess$Frozen,WorldLoader$ResultFactory,CloseableResourceManager,LayeredRegistryAccess,WorldLoader$DataLoadOutput,ReloadableServerResources)
+ Object lambda$load$1(RegistryAccess$Frozen,WorldLoader$ResultFactory,CloseableResourceManager,Object,ReloadableServerResources)
- RegistryAccess$Frozen loadLayer(ResourceManager,LayeredRegistryAccess,RegistryLayer,List)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.server.WorldLoader$PackConfig
</summary>

```diff
- boolean initMode()
+ DataPackConfig initialDataPacks()
+ void <init>(PackRepository,DataPackConfig,boolean)
- void <init>(PackRepository,WorldDataConfiguration,boolean,boolean)
- WorldDataConfiguration initialDataConfig()
```

</details>
<details>
<summary>
net.minecraft.server.commands.EffectCommands
</summary>

```diff
- int clearEffect(CommandSourceStack,Collection,Holder)
+ int clearEffect(CommandSourceStack,Collection,MobEffect)
- int giveEffect(CommandSourceStack,Collection,Holder,Integer,int,boolean)
+ int giveEffect(CommandSourceStack,Collection,MobEffect,Integer,int,boolean)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.server.commands.EnchantCommand
</summary>

```diff
+ int enchant(CommandSourceStack,Collection,Enchantment,int)
- int enchant(CommandSourceStack,Collection,Holder,int)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.server.commands.LocateCommand
</summary>

```diff
- boolean lambda$register$4(CommandSourceStack)
+ boolean lambda$register$6(CommandSourceStack)
- CommandSyntaxException lambda$locateStructure$10(ResourceOrTagKeyArgument$Result)
+ CommandSyntaxException lambda$locateStructure$12(ResourceOrTagLocationArgument$Result)
+ HolderSet$Direct lambda$getHolders$10(Holder)
- HolderSet$Direct lambda$getHolders$8(Holder)
- int lambda$register$5(CommandContext)
- int lambda$register$6(CommandContext)
+ int lambda$register$8(CommandContext)
+ int lambda$register$9(CommandContext)
- int locateBiome(CommandSourceStack,ResourceOrTagArgument$Result)
+ int locateBiome(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int locatePoi(CommandSourceStack,ResourceOrTagArgument$Result)
+ int locatePoi(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int locateStructure(CommandSourceStack,ResourceOrTagKeyArgument$Result)
+ int locateStructure(CommandSourceStack,ResourceOrTagLocationArgument$Result)
- int showLocateResult(CommandSourceStack,BlockPos,Pair,String,boolean,String)
- int showLocateResult(CommandSourceStack,ResourceOrTagArgument$Result,BlockPos,Pair,String,boolean)
- int showLocateResult(CommandSourceStack,ResourceOrTagKeyArgument$Result,BlockPos,Pair,String,boolean)
+ int showLocateResult(CommandSourceStack,ResourceOrTagLocationArgument$Result,BlockPos,Pair,String,boolean)
+ Message lambda$static$4(Object)
+ Message lambda$static$5(Object)
- Optional getHolders(ResourceOrTagKeyArgument$Result,Registry)
+ Optional getHolders(ResourceOrTagLocationArgument$Result,Registry)
+ Optional lambda$getHolders$11(Registry,ResourceKey)
- Optional lambda$getHolders$9(Registry,ResourceKey)
- String getElementName(Pair)
- String lambda$getElementName$11(ResourceKey)
- String lambda$showLocateResult$12(ResourceOrTagArgument$Result,Holder$Reference)
+ String lambda$showLocateResult$13(ResourceKey)
- String lambda$showLocateResult$13(ResourceOrTagArgument$Result,Pair,HolderSet$Named)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SummonCommand
</summary>

```diff
- int spawnEntity(CommandSourceStack,Holder$Reference,Vec3,CompoundTag,boolean)
+ int spawnEntity(CommandSourceStack,ResourceLocation,Vec3,CompoundTag,boolean)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WardenSpawnTrackerCommand
</summary>

```diff
- void lambda$setWarningLevel$3(int,WardenSpawnTracker)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
+ boolean previewsChat()
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerProperties
</summary>

```diff
- DataPackConfig getDatapackConfig(String,String)
- FeatureFlagSet getFeatures(String)
- void lambda$getFeatures$4(String,Consumer)
- WorldDimensions createDimensions(RegistryAccess)
+ WorldGenSettings getWorldGenSettings(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
- FeatureFlagSet enabledFeatures()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
+ boolean handlesPreviewRequests()
+ boolean tryHandleChat(String,Instant,LastSeenMessages$Update)
+ boolean verifyChatMessage(PlayerChatMessage)
+ ChatMessageContent getSignedContent(ServerboundChatPacket)
+ CompletableFuture getPreviewedArgument(CommandSourceStack,PreviewableCommand)
- CompletableFuture lambda$handleChat$9(CompletableFuture,CompletableFuture,PlayerChatMessage,Executor)
+ CompletableFuture lambda$handleChat$9(PlayerChatMessage)
+ CompletableFuture lambda$handleChatPreview$14(ServerboundChatPreviewPacket)
+ CompletableFuture queryChatPreview(String)
+ CompletableFuture queryCommandPreview(String)
+ CompletableFuture queryPreview(String)
+ Component lambda$queryChatPreview$16(Component,Component)
+ Map collectSignedArguments(ServerboundChatCommandPacket,PreviewableCommand)
- Map collectSignedArguments(ServerboundChatCommandPacket,SignableCommand,LastSeenMessages)
- Optional tryHandleChat(String,Instant,LastSeenMessages$Update)
- Optional unpackAndApplyLastSeen(LastSeenMessages$Update)
+ Packet lambda$sendPreviewResponse$15(int)
- PlayerChatMessage getSignedMessage(ServerboundChatPacket,LastSeenMessages)
+ PlayerChatMessage getSignedMessage(ServerboundChatPacket)
+ SignedMessageChain$Decoder signedMessageDecoder()
+ void handleChatPreview(ServerboundChatPreviewPacket)
- void handleMessageDecodeFailure(SignedMessageChain$DecodeException)
+ void handleValidationFailure(Set)
- void lambda$handleChat$10(ServerboundChatPacket,Optional)
+ void lambda$handleChat$10(ServerboundChatPacket)
+ void lambda$handleChat$8(CompletableFuture,CompletableFuture,Void)
- void lambda$handleChat$8(PlayerChatMessage,CompletableFuture,CompletableFuture,Void)
- void lambda$handleChatCommand$11(ServerboundChatCommandPacket,Optional)
+ void lambda$handleChatCommand$11(ServerboundChatCommandPacket)
+ void lambda$handleChatPreview$13(int,Component)
- void lambda$handlePlaceRecipe$13(ServerboundPlaceRecipePacket,Recipe)
+ void lambda$handlePlaceRecipe$19(ServerboundPlaceRecipePacket,Recipe)
- void lambda$handleSignUpdate$14(ServerboundSignUpdatePacket,List)
+ void lambda$handleSignUpdate$20(ServerboundSignUpdatePacket,List)
+ void lambda$queryChatPreview$17(String,Component)
+ void lambda$queryCommandPreview$18(String,Component)
- void performChatCommand(ServerboundChatCommandPacket,LastSeenMessages)
+ void performChatCommand(ServerboundChatCommandPacket)
- void sendDisguisedChatMessage(Component,ChatType$Bound)
- void sendPlayerChatMessage(PlayerChatMessage,ChatType$Bound)
+ void sendPreviewResponse(int,Component)
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerLoginPacketListenerImpl
</summary>

```diff
+ ProfilePublicKey validatePublicKey(ProfilePublicKey$Data,UUID,SignatureValidator,boolean)
- RemoteChatSession validateChatSession(RemoteChatSession$Data,GameProfile,SignatureValidator,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.packs.FilePackResources
</summary>

```diff
+ boolean hasResource(String)
+ Collection getResources(PackType,String,String,Predicate)
+ InputStream getResource(String)
- IoSupplier getResource(PackType,ResourceLocation)
- IoSupplier getResource(String)
- IoSupplier getRootResource(String[])
- String getPathFromLocation(PackType,ResourceLocation)
+ void <init>(File)
- void <init>(String,File)
- void listResources(PackType,String,String,PackResources$ResourceOutput)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.FolderRepositorySource
</summary>

```diff
+ boolean lambda$static$0(File)
- Pack$ResourcesSupplier detectPackResources(Path)
+ PackResources lambda$createSupplier$1(File)
+ PackResources lambda$createSupplier$2(File)
- PackResources lambda$detectPackResources$1(Path,String)
- PackResources lambda$detectPackResources$2(File,String)
- String nameFromPath(Path)
+ Supplier createSupplier(File)
+ void <init>(File,PackSource)
- void <init>(Path,PackType,PackSource)
- void discoverPacks(Path,BiConsumer)
- void lambda$loadPacks$0(Consumer,Path,Pack$ResourcesSupplier)
+ void loadPacks(Consumer,Pack$PackConstructor)
- void loadPacks(Consumer)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.ServerPacksSource
</summary>

```diff
- Component getPackTitle(String)
- Pack createBuiltinPack(String,Pack$ResourcesSupplier,Component)
- Pack createVanillaPack(PackResources)
- PackRepository createPackRepository(LevelStorageSource$LevelStorageAccess)
- PackRepository createPackRepository(Path)
- PackResources lambda$createVanillaPack$0(PackResources,String)
+ PackResources lambda$loadPacks$0()
- VanillaPackResources createVanillaPackSource()
+ void loadPacks(Consumer,Pack$PackConstructor)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.MultiPackResourceManager
</summary>

```diff
- void checkTrailingDirectoryPath(String)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceProvider
</summary>

```diff
- Optional lambda$fromMap$1(Map,ResourceLocation)
- ResourceProvider fromMap(Map)
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ boolean verifyChatTrusted(PlayerChatMessage,ChatSender)
- boolean verifyChatTrusted(PlayerChatMessage)
+ ServerPlayer getPlayerForLogin(GameProfile,ProfilePublicKey)
- ServerPlayer getPlayerForLogin(GameProfile,RemoteChatSession)
- void <init>(MinecraftServer,LayeredRegistryAccess,PlayerDataStorage,int)
+ void <init>(MinecraftServer,RegistryAccess$Frozen,PlayerDataStorage,int)
+ void broadcastChatMessage(PlayerChatMessage,Predicate,ServerPlayer,ChatSender,ChatType$Bound)
- void broadcastChatMessage(PlayerChatMessage,Predicate,ServerPlayer,ChatType$Bound)
+ void broadcastMessageHeader(PlayerChatMessage,Set)
```

</details>
<details>
<summary>
net.minecraft.tags.TagNetworkSerialization
</summary>

```diff
- Map serializeTagsToNetwork(LayeredRegistryAccess)
+ Map serializeTagsToNetwork(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.util.FutureChain
</summary>

```diff
+ CompletionStage lambda$append$0(TaskChainer$DelayedTask,Object)
- CompletionStage lambda$append$1(TaskChainer$DelayedTask,Object)
+ Object lambda$append$1(Throwable)
- Object lambda$append$2(Throwable)
- void close()
- void lambda$new$0(Executor,Runnable)
```

</details>
<details>
<summary>
net.minecraft.world.entity.AnimationState
</summary>

```diff
- void animateWhen(boolean,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean allowsDismounting(Entity)
+ ChatSender asChatSender()
- Packet getAddEntityPacket()
- Vec3 getLeashOffset(float)
- void addDeltaMovement(Vec3)
- void checkSlowFallDistance()
- void teleportRelative(double,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean equipmentHasChanged(ItemStack,ItemStack)
- double getAttributeBaseValue(Holder)
- double getAttributeValue(Holder)
+ Packet getAddEntityPacket()
```

</details>
<details>
<summary>
net.minecraft.world.entity.PlayerRideableJumping
</summary>

```diff
- int getJumpCooldown()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Saddleable
</summary>

```diff
- SoundEvent getSaddleSoundEvent()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeMap
</summary>

```diff
- AttributeInstance getInstance(Holder)
- boolean hasAttribute(Holder)
- boolean hasModifier(Holder,UUID)
- double getModifierValue(Holder,UUID)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.BlockPosTracker
</summary>

```diff
- void <init>(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
</summary>

```diff
- boolean defaultAcceptableLandingSpot(Mob,BlockPos)
- boolean isClearTransition(Mob,EntityDimensions,Vec3,Vec3)
+ boolean isClearTransition(Mob,Vec3,Vec3)
+ boolean lambda$new$0(BlockState)
- boolean lambda$start$0(BlockPos,BlockPos)
+ boolean lambda$start$1(BlockPos,BlockPos)
- LongJumpToRandomPos$PossibleJump lambda$start$1(BlockPos,BlockPos)
+ LongJumpToRandomPos$PossibleJump lambda$start$2(BlockPos,BlockPos)
- void <init>(UniformInt,int,int,float,Function,BiPredicate)
+ void <init>(UniformInt,int,int,float,Function,Predicate)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.TemptingSensor
</summary>

```diff
- boolean lambda$doTick$2(PathfinderMob,ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiTypes
</summary>

```diff
- void registerBlockStates(Holder,Set)
+ void registerBlockStates(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmeltingRecipe
</summary>

```diff
- void <init>(ResourceLocation,String,CookingBookCategory,Ingredient,ItemStack,float,int)
+ void <init>(ResourceLocation,String,Ingredient,ItemStack,float,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.TippedArrowRecipe
</summary>

```diff
- void <init>(ResourceLocation,CraftingBookCategory)
+ void <init>(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelReader
</summary>

```diff
- HolderLookup holderLookup(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.level.StructureManager
</summary>

```diff
+ Boolean lambda$getStructureWithPieceAt$0(TagKey,Holder)
- Boolean lambda$getStructureWithPieceAt$0(TagKey,Holder$Reference)
+ void <init>(LevelAccessor,WorldGenSettings,StructureCheck)
- void <init>(LevelAccessor,WorldOptions,StructureCheck)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SupportType$2
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TrapDoorBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,SoundEvent,SoundEvent)
+ void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
+ GameEventDispatcher getEventDispatcher(int)
- GameEventListenerRegistry getListenerRegistry(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
- boolean hasBiomesForStructureSet(StructureSet)
+ boolean lambda$getMobsAt$15(StructureManager,BlockPos,StructureStart)
+ boolean lambda$getMobsAt$16(BlockPos,StructureStart)
- boolean lambda$getMobsAt$20(StructureManager,BlockPos,StructureStart)
- boolean lambda$getMobsAt$21(BlockPos,StructureStart)
- boolean lambda$new$3(Holder)
- ChunkAccess lambda$createBiomes$12(ChunkAccess,RandomState)
+ ChunkAccess lambda$createBiomes$7(ChunkAccess,RandomState)
- ChunkPos lambda$generateRingPositions$10(int,int,HolderSet,RandomSource,RandomState)
- Integer lambda$applyBiomeDecoration$14(Structure)
+ Integer lambda$applyBiomeDecoration$9(Structure)
+ List lambda$generatePositions$4(Structure)
- List lambda$generatePositions$8(Structure)
- List lambda$generateRingPositions$11(Stopwatch,Holder,List)
+ List lambda$generateRingPositions$6(ConcentricRingsStructurePlacement,RandomState,Holder)
+ List lambda$new$2(Function,Holder)
+ List lambda$new$3(BiomeSource,Function)
- List lambda$new$4(Optional,Registry)
- List lambda$new$5(Function,Holder)
- List lambda$new$6(BiomeSource,Function)
- List possibleStructureSets()
- Set lambda$findNearestMapStructure$13(StructurePlacement)
+ Set lambda$findNearestMapStructure$8(StructurePlacement)
- Stream lambda$hasBiomesForStructureSet$7(StructureSet$StructureSelectionEntry)
- Stream lambda$new$2(Registry)
+ Stream possibleStructureSets()
+ String lambda$applyBiomeDecoration$11(Registry,Structure)
+ String lambda$applyBiomeDecoration$14(Registry,PlacedFeature)
- String lambda$applyBiomeDecoration$16(Registry,Structure)
- String lambda$applyBiomeDecoration$19(Registry,PlacedFeature)
+ String lambda$createReferences$19(StructureStart,Registry)
+ String lambda$createReferences$20(Optional,StructureStart)
+ String lambda$createReferences$21(StructureStart)
+ String lambda$createReferences$22(StructureStart)
- String lambda$createReferences$24(StructureStart,Registry)
- String lambda$createReferences$25(Optional,StructureStart)
- String lambda$createReferences$26(StructureStart)
- String lambda$createReferences$27(StructureStart)
+ void lambda$applyBiomeDecoration$10(WorldGenLevel,Set,ChunkPos)
+ void lambda$applyBiomeDecoration$12(WorldGenLevel,StructureManager,WorldgenRandom,ChunkAccess,ChunkPos,StructureStart)
+ void lambda$applyBiomeDecoration$13(IntSet,FeatureSorter$StepFeatureData,PlacedFeature)
- void lambda$applyBiomeDecoration$15(WorldGenLevel,Set,ChunkPos)
- void lambda$applyBiomeDecoration$17(WorldGenLevel,StructureManager,WorldgenRandom,ChunkAccess,ChunkPos,StructureStart)
- void lambda$applyBiomeDecoration$18(IntSet,FeatureSorter$StepFeatureData,PlacedFeature)
+ void lambda$createStructures$18(StructureManager,SectionPos,ChunkAccess,RandomState,long,ChunkPos,RegistryAccess,StructureTemplateManager,Holder)
- void lambda$createStructures$23(StructureManager,SectionPos,ChunkAccess,RandomState,long,ChunkPos,RegistryAccess,StructureTemplateManager,Holder)
+ void lambda$generatePositions$5(Set,RandomState,Holder)
- void lambda$generatePositions$9(Set,RandomState,Holder)
+ void lambda$getMobsAt$17(MutableBoolean,Predicate,StructureStart)
- void lambda$getMobsAt$22(MutableBoolean,Predicate,StructureStart)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.GameEventDispatcher
</summary>

```diff
+ void <clinit>()
- void <init>(ServerLevel)
- void handleGameEventMessagesInQueue(List)
- void lambda$post$0(List,GameEvent,Vec3,GameEvent$Context,GameEventListener,Vec3)
- void post(GameEvent,Vec3,GameEvent$Context)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationListener
</summary>

```diff
- boolean handleGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
+ boolean handleGameEvent(ServerLevel,GameEvent$Message)
- boolean lambda$isOccluded$10(BlockState)
+ boolean lambda$isOccluded$7(BlockState)
+ Float lambda$codec$3(VibrationListener)
- int getGameEventFrequency(GameEvent)
+ VibrationListener lambda$codec$5(VibrationListener$VibrationListenerConfig,PositionSource,Integer,Optional,Float,Integer)
- VibrationListener lambda$codec$5(VibrationListener$VibrationListenerConfig,PositionSource,Integer,Optional,VibrationSelector,Integer)
- VibrationSelector lambda$codec$3(VibrationListener)
- void <clinit>()
- void <init>(PositionSource,int,VibrationListener$VibrationListenerConfig,VibrationInfo,VibrationSelector,int)
+ void <init>(PositionSource,int,VibrationListener$VibrationListenerConfig,VibrationListener$ReceivingEvent,float,int)
- void <init>(PositionSource,int,VibrationListener$VibrationListenerConfig)
- void forceGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- void lambda$forceGameEvent$9(ServerLevel,GameEvent,GameEvent$Context,Vec3,Vec3)
- void lambda$static$7(Object2IntOpenHashMap)
- void lambda$tick$8(ServerLevel,VibrationInfo)
+ void scheduleSignal(ServerLevel,GameEvent,GameEvent$Context,Vec3,Vec3)
- void scheduleVibration(ServerLevel,GameEvent,GameEvent$Context,Vec3,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPreset
</summary>

```diff
+ IllegalStateException lambda$overworldOrThrow$3()
+ LevelStem overworldOrThrow()
- WorldDimensions createWorldDimensions()
+ WorldGenSettings createWorldGenSettings(long,boolean,boolean)
+ WorldGenSettings recreateWorldGenSettings(WorldGenSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootTable
</summary>

```diff
+ Consumer createStackSplitter(Consumer)
- Consumer createStackSplitter(LootContext,Consumer)
+ void lambda$createStackSplitter$0(Consumer,ItemStack)
- void lambda$createStackSplitter$0(LootContext,Consumer,ItemStack)
```

</details>
</details>
<hr/>